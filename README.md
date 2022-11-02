# Sync-Separator-PCB
Eagle printed circuit board for VGA or NTSC/PAL CSYNC to H/V

This is a work-in-progress repo. As of today, 2022/10/22 this is a prototype pcb which has been ordered for further testing.

The circuit is based on a EL1883 which splits the input of a composite sync signal into horizontal and vertical sync to the output-vga-port. This is useful if you have any hardware that outputs CSYNC only and your display device is not happy with that. For example I designed this for using my Atomiswave arcade mainboard on a VGA CRT monitor which expects both H- and V-Sync to be present to work.

As pointed out by by [maki9000](https://circuit-board.de/forum/index.php/User/20222-maki9000/), the EL1883 performs better when it's powered by 3.3V which is why there is an AMS1117 regulator in the BOM. This is likely to be replaced by either a TPS78233DDCR or TLV70033DDCR in future versions.

### Enclosure
[KEMO G026](https://www.kemo-electronic.de/de/Bauelemente/Geh%C3%A4use/Geschlossen/G026N-Gehaeuse-schwarz-ca-72-x-50-x-28-mm.php)

Both sides need a rectangular cut for the vga connectors. 4 PT-screws 3x5mm needed for pcb mounting inside the case.
