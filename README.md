# HP8570P-OpenCore
HP8570P OpenCore
* Enhanced OpenCore configuration file and folder for OpenCore. Used this [Base folder](https://github.com/vzahradnik/hp-elitebook-8570p-opencore)
Tested with High SIerra and Catalina.

* What works?
> Ughh... everything with the exception of the "What does not work" below?

* What does not work?
> I will add to this section if/when I find it along the road...
<details>
  <summary>Hardware Summary:</summary>

```

#=========================================================================================
┬[0000:00]
├─00:00.0       #                [8086:0154] [0600] (rev 09) Host bridge               : Intel Corporation 3rd Gen Core processor DRAM Controller
├─00:02.0       #                [8086:0166] [0300] (rev 09) VGA compatible controller : Intel Corporation 3rd Gen Core processor Graphics Controller
├─00:14.0       #                [8086:1e31] [0c03] (rev 04) USB controller            : Intel Corporation 7 Series/C210 Series Chipset Family USB xHCI Host Controller
├─00:16.0       #                [8086:1e3a] [0780] (rev 04) Communication controller  : Intel Corporation 7 Series/C216 Chipset Family MEI Controller #1
├─00:16.3       #                [8086:1e3d] [0700] (rev 04) Serial controller         : Intel Corporation 7 Series/C210 Series Chipset Family KT Controller
├─00:19.0       #                [8086:1502] [0200] (rev 04) Ethernet controller       : Intel Corporation 82579LM Gigabit Network Connection (Lewisville)
├─00:1a.0       #                [8086:1e2d] [0c03] (rev 04) USB controller            : Intel Corporation 7 Series/C216 Chipset Family USB Enhanced Host Controller #2
├─00:1b.0       # g0x0           [8086:1e20] [0403] (rev 04) Audio device              : Intel Corporation 7 Series/C216 Chipset Family High Definition Audio Controller
├┬00:1c.0-[01]  # g2x1 > g1x0    [8086:1e10] [0604] (rev c4) PCI bridge                : Intel Corporation 7 Series/C216 Chipset Family PCI Express Root Port 1
├┬00:1c.1-[26]  # g2x1 > g1x0    [8086:1e12] [0604] (rev c4) PCI bridge                : Intel Corporation 7 Series/C210 Series Chipset Family PCI Express Root Port 2
├┬00:1c.2-[25]  # g2x1 > g1x1    [8086:1e14] [0604] (rev c4) PCI bridge                : Intel Corporation 7 Series/C210 Series Chipset Family PCI Express Root Port 3
│├─25:00.0      # g1x1           [197b:2380] [0c00] (rev 30) FireWire (IEEE 1394)      : JMicron Technology Corp. IEEE 1394 Host Controller
│├─25:00.1      # g1x1           [197b:2392] [0880] (rev 30) System peripheral         : JMicron Technology Corp. SD/MMC Host Controller
│└─25:00.2      # g1x1           [197b:2391] [0805] (rev 30) SD Host controller        : JMicron Technology Corp. Standard SD Host Controller
├┬00:1c.3-[24]  # g2x1 > g1x1    [8086:1e16] [0604] (rev c4) PCI bridge                : Intel Corporation 7 Series/C216 Chipset Family PCI Express Root Port 4
│└─24:00.0      # g1x1           [8086:0082] [0280] (rev 34) Network controller        : Intel Corporation Centrino Advanced-N 6205 [Taylor Peak]
├─00:1d.0       #                [8086:1e26] [0c03] (rev 04) USB controller            : Intel Corporation 7 Series/C216 Chipset Family USB Enhanced Host Controller #1
├─00:1f.0       #                [8086:1e55] [0601] (rev 04) ISA bridge                : Intel Corporation QM77 Express Chipset LPC Controller
└─00:1f.2       #                [8086:1e03] [0106] (rev 04) SATA controller           : Intel Corporation 7 Series Chipset Family 6-port SATA Controller [AHCI mode]

```
</details>

# Credits:
- Apple for the operating system
- Acidanthera for Opencore
- @vzahradnik for the original configuration folder
- Mald0n for the battery status, audio, power management, and the DSDT patching. 

