In this 5V power supply PCB design, I have implemented a single ground plane approach to ensure minimal noise and better return paths. 
All GND connections were routed through a dedicated polygon pour (zone) on the front layer, ensuring low impedance grounding across the board.

To connect ground pins from different locations to the main GND plane, I used vias with 0.7 mm diameter and 0.5 mm drill size, providing solid vertical connections between layers. 
The track width used throughout the layout is 0.3 mm, which is suitable for the expected current flow of up to 1–1.5 A.

The design successfully passed all Design Rule Checks (DRC), with no errors or unconnected items, confirming the integrity of the routing and electrical connectivity.
