# gigabyte-z370md3h-hackintosh-efi
intel i5 8400, 16gb ddr4 2400, gigabit z370m d3h, 480gb Kingston ssd

-v keepsyms=1 swd_panic=1 igfxrpsc=1 igfxonln=1 boot args currently

opencore 0.69
bigsur 11.3.1


need add igfxonln=1 (purely for DVID) to boot args for dual display via DVID as well as HDMI after dortania igpu patching guide (framebuffer + connectors)
