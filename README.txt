GIRAFFIC PARK — FULL PARK WEBGL PROTOTYPE

Open index.html in a modern browser while connected to the internet.
The project loads Three.js from jsDelivr. Browser hardware acceleration should be
enabled for best performance.

DESKTOP CONTROLS
W / S      Move forward / backward relative to the camera
A / D      Strafe left / right
Mouse      Look
Left click or F  Fire tranquilizer dart after acquiring the gun
Shift      Sprint
Space      Jump
E          Inspect / activate / collect
R          Return to entrance
M          Open main menu
P          Open park map / fast travel
G          Toggle Chaos Mode
Esc        Release mouse pointer without opening the menu

MOBILE CONTROLS
Select MOBILE or AUTO-DETECT in the menu.
Left virtual stick moves. Drag the right side to look.
Dedicated buttons provide Use, Fire, Jump, Map, Chaos, and Menu actions.

GAMEPLAY SYSTEMS
- Pick up the tranquilizer dart gun in the Ranger Station.
- Collect the Security Keycard and Generator Fuse to restore park power.
- Find additional tranquilizer ammo in the Veterinary Clinic.
- Tranquilized giraffes sleep temporarily and stop moving or firing lasers.
- NPCs patrol normally, talk when approached, and flee during Chaos Mode.
- Giraffes hunt deer during Chaos Mode; synthesized sound hooks accompany events.
- Building doors animate and selected restricted doors require restored power.
- The live minimap shows roads, destinations, animals, NPCs, collectibles, and heading.
- The Visitors Center park map and HUD park-map button support fast travel.

GRAPHICS / PERFORMANCE
- Flat billboard sky with old-DOS-style texture parallax avoids sky-sphere artifacts.
- WebGL requests the high-performance GPU when available.
- AUTO display mode dynamically adjusts internal resolution.
- Distance culling, streamed sectors, instancing, cached geometry, and THREE.LOD reduce load.
- Buildings have detailed near interiors and inexpensive distant shells.
- Giraffes use simplified distant models and restore detail when nearby.
- The HUD reports approximate FPS and draw calls.

If startup fails, the loading panel displays the JavaScript/WebGL error instead of
remaining indefinitely on “Constructing Low-Poly Park.”
