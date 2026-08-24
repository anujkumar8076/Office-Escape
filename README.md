Office Escape
A top-down escape room game built with vanilla HTML5 Canvas and JavaScript. No dependencies, no build step — open the .html file and play.

🎮 How to Play
Explore a dark office building, collect items, solve puzzles, and find the USB Keycard to escape through the exit door.

⌨️ Controls
Key	Action
WASD / Arrow Keys	Move
E / Left Click	Interact with nearby objects
1–5	Select inventory item
0 / ESC	Deselect item
ESC	Close puzzle overlays
SPACE	Start / Restart
💡 Puzzle Solutions (spoilers)
Red Key — Search the potted plant in Reception

Plant Key — Search the manager's desk drawer in Manager Cabin (requires Red Key to enter)

Sticky Note — Pick up from a desk in Open Office (shows keypad code: 4821)

Keypad Door — Enter 4821 on the keypad wall panel to access Secret Room

USB Drive — Pick up from the desk in Secret Room

Blue Keycard — Sort the 4 documents in correct page order (1→2→3→4) on the desk in Storage Room (requires Plant Key to enter)

Exit — Select the USB Drive and interact with the EXIT door in Exit Corridor (requires Blue Keycard to enter)

🗺️ Recommended Path
Reception → get Red Key → Manager Cabin → get Plant Key → Open Office → get Sticky Note → Storage Room → solve document puzzle → get Blue Keycard → Manager Cabin → enter keypad code → Secret Room → get USB Drive → Exit Corridor → escape

⚙️ Technical Details
Map: 45×30 tile grid, 32px per tile, camera-following viewport (800×600)

Rooms: Reception, Open Office, Manager Cabin, Secret Room, Storage Room, Exit Corridor

Lighting: Offscreen canvas with radial gradient cutout for flashlight effect

Rendering: 2D Canvas API, procedural furniture drawing, particle system for footsteps

UI: Minimap, inventory bar, message log, room name indicator, puzzle overlays

🌐 Browser Support
Works in any modern browser (Chrome, Firefox, Edge, Safari). Canvas scaling is handled via CSS for different screen sizes.
