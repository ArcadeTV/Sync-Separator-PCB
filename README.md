# Sync-Separator-PCB
Eagle printed circuit board for VGA or NTSC/PAL CSYNC to H/V

This is a work-in-progress repo. As of today, 2022/10/22 this is a prototype pcb which has been ordered for further testing.

The circuit is based on a EL1883 which splits the input of a composite sync signal into horizontal and vertical sync to the output-vga-port. This is useful if you have any hardware that outputs CSYNC only and your display device is not happy with that. For example I designed this for using my Atomiswave arcade mainboard on a VGA CRT monitor which expects both H- and V-Sync to be present to work.
