# TL431 Test Fixture Adapter for Tektronix Curve Tracers

Test fixture adapter for Tektronix curve tracers. Fits Tek 576, Tek 577 test fixtures, possibly others.

![TL431 adapter, bottom view](img/tl431-bottom.png)

## Bill Of Materials

| Item | Qty | Source |
| --- | --- | --- |
| Prototype Board, 5x7mm, 0.1 in. hole pitch | 1 | [Amazon](https://amzn.to/3WRZzZg "Amazon")|
| 4 mm RC-style banana plugs | 3 | [Amazon](https://amzn.to/3YWXP2K "Amazon")|
| 6mm silicone rubber feet | 4 | [Amazon](https://amzn.to/3Wtbopl "Amazon")|
| 3 pin female 2.54mm pitch header | 1 | [Amazon](https://amzn.to/3YYWmcj "Amazon"), [Sparkfun](https://www.sparkfun.com/products/13875 Sparkfun"), [Newark](https://www.newark.com/samtec/bcs-103-f-s-pe/connector-receptacle-3-contacts/dp/38AC3722?CMP=AFC-OP "Newark")|
| M3x8mm button head socket screws | 4 | [Bolt Depot](https://www.boltdepot.com/Product-Details.aspx?product=4783 "Bolt Depot")|
| M3 nuts | 4 | [Bolt Depot](https://www.boltdepot.com/Product-Details.aspx?product=4783 "Bolt Depot")|

## Tools

Drill Press*, 3/16" drill bit*, 3D printer, any rigid filament (PETG, PLA, ABS, etc.), soldering iron, hookup wire.

## Assembly

1. Print bottom, middle, and top pieces, as well as two jigs. Printing parameters: 0.6mm or smaller nozzle, layer height 0.3mm or lower.

STLs with "hires" in the name are containing fine details, the 0.25mm or smaller nozzle and 0.1mm or smaller layer height is recommended.

2. Using the drill jig find holes that can be used as pilots for 3mm screws on the prototype board, mark them, remove the jig, then drill 3mm holes where marked.

3. Screw the drill jig to the board, drill 3/16" holes for the banana plugs.

4. Mark the outer border of the board, cut the excess material. A drill jig can be used to make the clean edge.

5. Insert banana plugs as shown. Check the height protruding from the other side, should be 1mm*. A leveling jig can be used.

6. Insert* and solder the 3 pin header as shown. Connect the header pins to the banana plugs.

7. Assemble 3 printed pieces and PCB as shown.

