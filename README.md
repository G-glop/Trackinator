
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
- [x] Move tasks from the system diagram here
	- Flex PCB hatching instead of solid pours provide better flexibility but shouldn't be used with high frequency. Use denser hatching if possible
	- [ ] ESPs connected to a shared bus (I2C?) for sidechannel communication
	- [ ] Strapping pins so each ESP can tell where it is
	- [ ] Shared RESET and GPIO0 signals connected to buttons
	- [ ] Series JTAG for the hell of it
	- [ ] PWM + Tacho PC fan header (commodity PC fans run at 12 V and usually require at least 7 V to start - do i need a boost converter?)
	- [ ] Make a few recordings to try out how much of an impact the dead cats make on audio - they're right in the space for mouth tracking cameras
- [ ] Add good quality voltage sources (switch mode where applicable)
	- Could steal the 3.3 V Buck and the camera LDOs from the Xiao Sense 
- [ ] Add a footprint for the google coral AI chip? (G313-06329-00)
	- [ ] Needs usb + power + space for all the ground pins
- [ ] (meme) composite all 5 camera feeds together into a cursed webcam - "vision pro without ai"
- [ ] Align the USB A male 3d model with footprint
- [ ] Use the "Round Tracks" plugin from mixtela together with via/pad teardrops
- [ ] Add an automatically updating "Exported at \[date] \[tag] \[branch] \[commit #]" text
	- Date is easy using the ${CURRENT_DATE} variable
- [ ] Export a 3D model of the board and make it into a VRChat world with the top & bottom (copper + mask + silkscreen) are the ceiling & floor, and vias are columns between the two (scale correct?)
	- The VRML export is fine (imports into Blender) but everything is geometry, use it only for vias and export everything else as SVG (later rasterzied)?
	- There're no gradients and sharp edges are greatly reduced by using teardrops, mSDF(s) could be a better choice than an RGB texture.
		- https://github.com/Chlumsky/msdfgen (only accepts SVG - use Plot in KiCad)
		- (a) 2 mSDFs selecting between 3 colors
		- (b) 1 mSDF selecting between 2 textures
		- or (c) quantize the interpolated RGB value back to one of the 3 colors
	- Rave mode which shows the frequency and direction of signal on each trace.
		- SDFs could be useful for outlines

Notes:
	Command to download LCSC/EasyEDA footprint: `easyeda2kicad --full --lcsc_id [Cxxxx]`