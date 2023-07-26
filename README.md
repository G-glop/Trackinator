
# Todo

- [X] Put Obsidian notes inside the repo
- [X] Add a README.md
- [ ] Search the calendar for any Trackinator info and add it here
	- [ ] select the flex connector & crystals & oscillators (to free up browser tabs)
	- [ ] transfer my eyetrack diagram to kicad (don't worry about simple component values/choices)
	- [ ] abandon fully flex design and opt into frunkable + flex illuminators / extensions
	- [ ] drive all ir leds from a single current limited source to ensure sum i <= safe limit
- [x] Import new FFC connector
- FCC connector orientaion:
	- Face cams prefer pins up
	- Eye cams prefer pins down
	- Nose cam doesn't care
- [x] Add camera pinout to it
	- Did the option with least fewest crossing lines, could've copied the xiao but eh
- [x] Connect it to the ESP32
- [ ] Select a suitable crystal + caps and add it
- [ ] Add option to use central oscillator / clock source
- [ ] Select and add USB C and A female connectors
  - [ ] What does USB C need in addition to P+N+5V+GND?
- [ ] Use painters tape + scanner + 3d printer to prototype a flex PCB
  - [ ] IR illumination
  - [ ] Ambilight
  - [ ] Reuse the 24P FFC connector
- [ ] Add headers as an alternative to the flex PCB + FFC connector
- [ ] Add a few ERM drivers
- [ ] Move tasks from the system diagram here
- [ ] Add good quality voltage sources (switch mode where applicable)
	- Could steal the 3.3 V Buck and the camera LDOs from the Xiao Sense 
- [ ] Add a footprint for the google coral AI chip? (G313-06329-00)
	- [ ] Needs usb + power + space for all the ground pins
- [ ] (meme) composite all 5 camera feeds together into a cursed webcam - "vision pro without ai"
[[ESP32_CAM_V1.6.pdf]]