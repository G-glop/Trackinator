---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==

# Text Elements
 ESP32-S3FH4R2 ^vqoFYbiM

24 pin FFC camera connector ^X9ut4d1o

crystal ^mOUvv2EH

7 port USB HUB
FE2.1-CQFP48A ^ov8sC0wv

N * XL-1010RGBC-WS2812B ^cprpwiTy

IR illuminators ^Ljxem1nd

USB C port ^0XZTxs6J

USB C/A ports ^dYpMYbas

(second ESP) ^AIH5WdnS

(thid ESP) ^PpPARAMv

(fourth ESP) ^lnArmqg0

crystal ^zTbpD40d

Oscillator (backup) ^r8Ca8q0R

Oscillator (backup) ^1jq8McEe

Motor Driver (haptics) ^aLS85O1T

any mA @ 3.5 V ^hVRw2FKO

53 ma @ 5 + 3.3 + 1.8 V
(mostly 3.3 V) ^HbStJU8o

30 mA @ 2.8 V
35 mA @ 1.2 V
6 mA @ 3.3 V ^KSPYLUTo

5.7 mA @ cca 2 V ^1NqTY7E3

-1 A @ 5 V ^x8wVP4jL

[[https://community.nxp.com/t5/LPC-FAQs/How-to-calculate-the-value-of-crystal-load-capacitors/m-p/464589|load cap calculation]] ^hiiRsVWm

[[https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf|datsheet]] ^QXWKhf9Y

[[https://www.espressif.com/sites/default/files/documentation/esp32_hardware_design_guidelines_en.pdf|hw design]] ^MLY6WYG3

[[https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/XIAO_ESP32S3_SCH_v1.1.pdf|xiao sense schematics]] ^dw3TyTC5

[[obsidian://open?vault=Trackinator&file=pdfs%2FESP32_CAM_V1.6.pdf|esp cam schematic]] ^QLMu9XLC

series CLK_OUT
(backup) ^mW57GQgu

ESPs connected to a shared bus (I2C?) for sidechannel communication ^1UJkMTAC

Strapping pins so each ESP can tell where it is ^LBxZwfDz

[[https://github.com/espressif/kicad-libraries|kicad libs]] ^WzelJzLN

91 mA @ 3.3 V ^w9kI7con

Shared RESET and GPIO0 signals connected to buttons ^LcLTOY8V

Series JTAG for the hell of it ^UDNgwO2i

5.1k pulldowns on CC1/CC2
Can sense voltage to measure cable orientation ^gDDstPv8

480 Mb/s
keep short! ^WAAK4yfb

toggle LEDs between frames for some jank structured light scheme? ^yKogbfd4

Hatching instead of solid pours provide better flexibility
but shouldn't be used with high frequency
Use denser hatching if possible ^ux70v0so

some rando design has 20p
cnlohr has 10p ^Xk1dzFqD

[[https://datasheet.lcsc.com/lcsc/1808311640_AWINIC-Shanghai-Awinic-Tech-AW9106BTQR_C252448.pdf|neat LED driver]] ^RmcGFCNC

[[https://datasheet.lcsc.com/lcsc/2210111600_AWINIC-Shanghai-Awinic-Tech-AW9110CQNR_C2943134.pdf|10 channel]] ^ZedtAyBi

(fifth ESP) ^8Aes8ko9

PWM + Tacho PC fan header (commodity PC fans run at 12 V and usually require at least 7 V to start - do i need a boost converter?) ^4PVAnT7v

Make a few recordings to try out how much of an impact the dead cats make on audio - they're right in the space for mouth tracking cameras ^OCMfFMZA

Or USB A for frunkability
(somehow do both?) ^FI3PvyOE

[[https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/XIAO_ESP32S3_ExpBoard_v1.0_SCH.pdf|expansion board schematic]] ^OO7LF31v

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.9.8",
	"elements": [
		{
			"type": "text",
			"version": 85,
			"versionNonce": 992328975,
			"isDeleted": false,
			"id": "vqoFYbiM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.77678017172178,
			"y": -319.0405448108187,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 173.81988525390625,
			"height": 25,
			"seed": 1377805300,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": " ESP32-S3FH4R2",
			"rawText": " ESP32-S3FH4R2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": " ESP32-S3FH4R2",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 160,
			"versionNonce": 1089183585,
			"isDeleted": false,
			"id": "X9ut4d1o",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.1875723948301,
			"y": -302.5836526194873,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 287.1398010253906,
			"height": 25,
			"seed": 1543020748,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "24 pin FFC camera connector",
			"rawText": "24 pin FFC camera connector",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "24 pin FFC camera connector",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1286161199,
			"isDeleted": false,
			"id": "mOUvv2EH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -175.1207944736916,
			"y": -386.23925968449686,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.77993774414062,
			"height": 25,
			"seed": 108112588,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "crystal",
			"rawText": "crystal",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "crystal",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 190,
			"versionNonce": 534973249,
			"isDeleted": false,
			"id": "ov8sC0wv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -573.5131960627591,
			"y": -349.03999958662115,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 162.41990661621094,
			"height": 50,
			"seed": 324808820,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "7 port USB HUB\nFE2.1-CQFP48A",
			"rawText": "7 port USB HUB\nFE2.1-CQFP48A",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "7 port USB HUB\nFE2.1-CQFP48A",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 202835279,
			"isDeleted": false,
			"id": "cprpwiTy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.18767702453363,
			"y": -111.10156445510916,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 269.51983642578125,
			"height": 25,
			"seed": 955194828,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "N * XL-1010RGBC-WS2812B",
			"rawText": "N * XL-1010RGBC-WS2812B",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "N * XL-1010RGBC-WS2812B",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 106,
			"versionNonce": 683801377,
			"isDeleted": false,
			"id": "Ljxem1nd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 138.24474931231134,
			"y": -201.6141576183212,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142.27987670898438,
			"height": 25,
			"seed": 30340596,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "IR illuminators",
			"rawText": "IR illuminators",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "IR illuminators",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 952599407,
			"isDeleted": false,
			"id": "0XZTxs6J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -862.1932446172087,
			"y": -353.6683729979806,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 114.69992065429688,
			"height": 25,
			"seed": 1727352012,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "USB C port",
			"rawText": "USB C port",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "USB C port",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 187,
			"versionNonce": 1006104321,
			"isDeleted": false,
			"id": "dYpMYbas",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -865.9311665162055,
			"y": -9.138833707361869,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 148.67990112304688,
			"height": 25,
			"seed": 1012120436,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "USB C/A ports",
			"rawText": "USB C/A ports",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "USB C/A ports",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "freedraw",
			"version": 49,
			"versionNonce": 318979471,
			"isDeleted": false,
			"id": "FRNB4uc2YqbVk9XzUJeAk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -725.0530518194826,
			"y": -341.3256515396302,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.34035745957817,
			"height": 13.714024511257776,
			"seed": 1529483724,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6857430774443856,
					0
				],
				[
					4.799939967851287,
					0.6856907625925146
				],
				[
					11.656952223480175,
					2.0570984452035077
				],
				[
					21.942470606923507,
					2.7428153652219294
				],
				[
					34.970804355588825,
					4.114196890406959
				],
				[
					52.113334994661045,
					6.171321493036373
				],
				[
					71.31293792151075,
					8.228419938239881
				],
				[
					87.7697777979904,
					10.285518383443332
				],
				[
					99.42667770661888,
					11.656926066054325
				],
				[
					103.54092691187759,
					11.656926066054325
				],
				[
					104.22661767447016,
					11.656926066054325
				],
				[
					106.96943303969203,
					11.656926066054325
				],
				[
					113.14070221787665,
					12.34261682864684
				],
				[
					122.05483907613484,
					13.714024511257776
				],
				[
					129.5975420943563,
					13.714024511257776
				],
				[
					132.34035745957817,
					13.714024511257776
				],
				[
					132.34035745957817,
					13.714024511257776
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 69,
			"versionNonce": 288481,
			"isDeleted": false,
			"id": "5q3EJTpzw2j-ZK_A-VSHo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -381.51674827544605,
			"y": -318.0118255649471,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.7117389847632,
			"height": 8.228393780813917,
			"seed": 374656628,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6856907625925714,
					0
				],
				[
					1.3714338400368433,
					0
				],
				[
					4.114196890407015,
					0
				],
				[
					7.542703018221459,
					0
				],
				[
					14.399715273850347,
					0
				],
				[
					23.313852132108536,
					0
				],
				[
					32.91367975295941,
					0.6856907625925146
				],
				[
					44.57057966158777,
					1.3713815251850292
				],
				[
					54.170459597290346,
					2.0570984452035077
				],
				[
					61.71311030065999,
					2.7427892077960223
				],
				[
					67.88448410854812,
					2.7427892077960223
				],
				[
					71.99862868410332,
					3.428506127814444
				],
				[
					76.11287788936204,
					3.428506127814444
				],
				[
					78.85564093973221,
					4.114196890406959
				],
				[
					83.65552859273168,
					4.114196890406959
				],
				[
					89.14115932317554,
					4.799887652999473
				],
				[
					98.05529618143373,
					5.485604573017895
				],
				[
					106.96943303969203,
					5.485604573017895
				],
				[
					113.14070221787654,
					5.485604573017895
				],
				[
					116.56920834569098,
					5.485604573017895
				],
				[
					118.6263329483204,
					5.485604573017895
				],
				[
					119.31207602576478,
					6.171295335610466
				],
				[
					119.99771447350543,
					6.171295335610466
				],
				[
					120.68345755094981,
					6.171295335610466
				],
				[
					121.36909599869057,
					6.857012255628888
				],
				[
					122.74058215357923,
					6.857012255628888
				],
				[
					124.79760212650501,
					6.857012255628888
				],
				[
					126.16908828139367,
					6.857012255628888
				],
				[
					128.22610825431946,
					7.5427030182214025
				],
				[
					129.5975944092081,
					7.5427030182214025
				],
				[
					130.28323285694876,
					7.5427030182214025
				],
				[
					130.96897593439314,
					7.5427030182214025
				],
				[
					131.6546143821339,
					7.5427030182214025
				],
				[
					132.34035745957817,
					8.228393780813917
				],
				[
					133.02610053702256,
					8.228393780813917
				],
				[
					133.7117389847632,
					8.228393780813917
				],
				[
					133.7117389847632,
					8.228393780813917
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 46,
			"versionNonce": 1040364463,
			"isDeleted": false,
			"id": "4dFyg-sBLdssE8ApAHzaG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -136.03568859799134,
			"y": -359.15389909872044,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 0.6857430774443856,
			"height": 35.65644280332947,
			"seed": 1633504844,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6856907625925714
				],
				[
					0,
					2.7427892077960223
				],
				[
					0,
					6.857012255628888
				],
				[
					0,
					11.656899908628418
				],
				[
					0,
					17.14253063907222
				],
				[
					0,
					21.94241829207175
				],
				[
					0,
					26.74233210249713
				],
				[
					0,
					30.170838230311574
				],
				[
					0.6857430774443856,
					32.227936675515025
				],
				[
					0.6857430774443856,
					32.9136535955335
				],
				[
					0.6857430774443856,
					34.28506127814444
				],
				[
					0.6857430774443856,
					35.65644280332947
				],
				[
					0.6857430774443856,
					35.65644280332947
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 58,
			"versionNonce": 505840737,
			"isDeleted": false,
			"id": "Oz8AFlvZlfUSvpVdm4FCi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -46.66242087939568,
			"y": -304.29782721111525,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 172.7966879159071,
			"height": 7.5427030182214025,
			"seed": 398644980,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933379778,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6856907625925714,
					0
				],
				[
					2.0570722877776006,
					0.6856907625925146
				],
				[
					7.542703018221459,
					2.057098445203451
				],
				[
					17.14253063907222,
					3.428506127814444
				],
				[
					30.856555150329996,
					4.79991381042538
				],
				[
					45.25627042418023,
					4.79991381042538
				],
				[
					61.71311030065999,
					5.485604573017895
				],
				[
					77.48425941454707,
					6.1713214930363165
				],
				[
					89.82690240061982,
					6.1713214930363165
				],
				[
					101.48380230924818,
					6.1713214930363165
				],
				[
					113.14070221787654,
					6.857012255628888
				],
				[
					122.7404775238756,
					6.857012255628888
				],
				[
					132.34035745957817,
					7.5427030182214025
				],
				[
					139.88300816294782,
					7.5427030182214025
				],
				[
					144.68300044565092,
					7.5427030182214025
				],
				[
					148.11150657346536,
					7.5427030182214025
				],
				[
					152.91139422646484,
					7.5427030182214025
				],
				[
					159.08266340464934,
					7.5427030182214025
				],
				[
					165.25403721253758,
					7.5427030182214025
				],
				[
					169.36818178809267,
					7.5427030182214025
				],
				[
					171.42530639072208,
					7.5427030182214025
				],
				[
					172.11104946816647,
					7.5427030182214025
				],
				[
					172.7966879159071,
					7.5427030182214025
				],
				[
					172.7966879159071,
					7.5427030182214025
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 88,
			"versionNonce": 1643013583,
			"isDeleted": false,
			"id": "BBpjl--BGdGyl7l-KNtjP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -105.17913344766117,
			"y": -289.21239501724654,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.65278596093816,
			"height": 102.85518383443326,
			"seed": 1636173556,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6856907625925146,
					0
				],
				[
					2.7428153652219294,
					0
				],
				[
					6.857012255628888,
					2.057124602629358
				],
				[
					13.028333748665261,
					4.799887652999473
				],
				[
					21.25672752947918,
					8.914136858258246
				],
				[
					34.28506127814438,
					14.39971527385029
				],
				[
					50.05615807717976,
					20.571036766886664
				],
				[
					67.19868871625198,
					27.42804902251555
				],
				[
					82.2841470675466,
					32.913679752959354
				],
				[
					99.42667770661882,
					39.77069200858824
				],
				[
					114.51208374306162,
					45.256270424180286
				],
				[
					129.59748977950443,
					51.4275919172166
				],
				[
					143.3115142907622,
					56.91322264766046
				],
				[
					154.2827757516498,
					61.713110300659935
				],
				[
					164.56829413509314,
					67.1987410311038
				],
				[
					172.79668791590717,
					71.99862868410327
				],
				[
					179.65370017153606,
					75.42713481191771
				],
				[
					185.8250739794242,
					78.85564093973215
				],
				[
					191.31060008016442,
					80.91276554236151
				],
				[
					194.73910620797886,
					82.2841470675466
				],
				[
					198.1676123357933,
					83.65552859273163
				],
				[
					200.910480015867,
					85.02696243276853
				],
				[
					203.65324306623705,
					85.71265319536104
				],
				[
					205.71036766886647,
					87.7697777979904
				],
				[
					208.45313071923664,
					89.14115932317549
				],
				[
					210.51025532186594,
					89.826850085768
				],
				[
					213.25312300193974,
					91.88397468839742
				],
				[
					215.31014297486553,
					92.56966545098993
				],
				[
					217.36726757749483,
					93.94104697617496
				],
				[
					218.73864910267997,
					94.62679005361929
				],
				[
					219.42439218012424,
					95.3124808162118
				],
				[
					220.79577370530927,
					95.99817157880437
				],
				[
					222.16715523049442,
					98.05529618143373
				],
				[
					224.22427983312372,
					100.11236846921133
				],
				[
					226.28140443575313,
					101.48380230924818
				],
				[
					227.65278596093816,
					102.16949307184069
				],
				[
					227.65278596093816,
					102.85518383443326
				],
				[
					227.65278596093816,
					102.85518383443326
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 71,
			"versionNonce": 1190060705,
			"isDeleted": false,
			"id": "tNQuln8_7ZrGCam1qEL-x",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.97861631021357,
			"y": -288.526704254654,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 246.8524935174916,
			"height": 193.36777699764565,
			"seed": 804417012,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6856907625925146
				],
				[
					0,
					2.7428153652219294
				],
				[
					2.7428153652219294,
					8.914136858258303
				],
				[
					6.857012255628888,
					17.14253063907222
				],
				[
					15.08545835129462,
					27.42804902251555
				],
				[
					23.999542894701108,
					39.08500124599573
				],
				[
					32.913679752959354,
					49.37051962943906
				],
				[
					43.199198136402686,
					60.341728775474905
				],
				[
					56.91322264766046,
					71.99862868410327
				],
				[
					71.31293792151075,
					84.34127167017601
				],
				[
					86.39839627280537,
					95.31248081621186
				],
				[
					100.11242078406309,
					104.91230843706262
				],
				[
					110.39793916750642,
					112.45501145528408
				],
				[
					119.31202371091291,
					117.94064218572788
				],
				[
					129.59754209435624,
					124.11191136391244
				],
				[
					139.88306047779957,
					132.34035745957817
				],
				[
					150.85426962383548,
					140.56875124039215
				],
				[
					161.1398403221305,
					146.0543819708359
				],
				[
					169.36823410294454,
					150.1685788612429
				],
				[
					172.79674023075899,
					152.91139422646478
				],
				[
					176.22524635857343,
					153.59708498905735
				],
				[
					181.0251340115729,
					156.33990035427922
				],
				[
					188.56788934464606,
					160.45409724468624
				],
				[
					196.79628312545998,
					163.88260337250068
				],
				[
					204.33903845853325,
					167.9968002629077
				],
				[
					208.45318303408845,
					170.053924865537
				],
				[
					209.82456455927348,
					170.053924865537
				],
				[
					211.19605071416214,
					170.73961562812957
				],
				[
					212.56743223934717,
					172.79674023075899
				],
				[
					217.36731989234664,
					175.53950328112904
				],
				[
					222.8529506227905,
					178.9680094089435
				],
				[
					227.65283827578997,
					181.0251340115729
				],
				[
					230.39560132616015,
					183.08225861420232
				],
				[
					231.7670874810488,
					183.76794937679477
				],
				[
					233.8241074539746,
					184.45364013938735
				],
				[
					237.9383566592333,
					187.8821462672018
				],
				[
					242.05260586449214,
					189.9392708698312
				],
				[
					244.10962583741792,
					191.9963431576087
				],
				[
					245.48111199230658,
					192.68203392020126
				],
				[
					246.8524935174916,
					193.36777699764565
				],
				[
					246.8524935174916,
					193.36777699764565
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 93,
			"versionNonce": 232707055,
			"isDeleted": false,
			"id": "YdJ9fnTOIpwsKyEtc-1VM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.4034132807849,
			"y": -311.8405302293369,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.914032228554674,
			"height": 469.70536566800445,
			"seed": 1630482548,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337938,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6856907625925714
				],
				[
					0,
					5.485604573017952
				],
				[
					0.6857430774443856,
					13.028333748665261
				],
				[
					2.0571246026294148,
					26.742358259923037
				],
				[
					3.428506127814444,
					41.82776429636584
				],
				[
					5.485630730443859,
					60.341702618049
				],
				[
					6.171373807888131,
					81.59845630495408
				],
				[
					6.857012255628888,
					105.59799919965519
				],
				[
					6.857012255628888,
					126.16903596654186
				],
				[
					6.857012255628888,
					146.74007273342846
				],
				[
					6.857012255628888,
					165.9397018177042
				],
				[
					6.857012255628888,
					181.71085093159132
				],
				[
					6.171373807888131,
					197.4819477306267
				],
				[
					4.799992282703101,
					212.56740608192132
				],
				[
					2.7428676800736866,
					229.02419364354915
				],
				[
					1.3714861548886574,
					245.48103352002886
				],
				[
					-0.6856384477407573,
					266.0520702869155
				],
				[
					-1.3713815251850292,
					284.5660347660246
				],
				[
					-1.3713815251850292,
					303.07994693028184
				],
				[
					-2.0570199729257865,
					317.4796622041322
				],
				[
					-2.0570199729257865,
					329.8223051902048
				],
				[
					-2.0570199729257865,
					339.4221328110557
				],
				[
					-2.0570199729257865,
					348.33621735446206
				],
				[
					-2.0570199729257865,
					357.25035421272037
				],
				[
					-2.0570199729257865,
					364.7930572309418
				],
				[
					-2.0570199729257865,
					372.3357602491632
				],
				[
					-2.0570199729257865,
					378.5070817421996
				],
				[
					-2.0570199729257865,
					382.6212786326065
				],
				[
					-2.0570199729257865,
					388.10690936305036
				],
				[
					-1.3713815251850292,
					391.5354154908648
				],
				[
					-1.3713815251850292,
					396.3353031438643
				],
				[
					-1.3713815251850292,
					400.4495000342713
				],
				[
					-1.3713815251850292,
					404.56374923953
				],
				[
					-1.3713815251850292,
					408.677946129937
				],
				[
					-1.3713815251850292,
					412.10645225775147
				],
				[
					-0.6856384477407573,
					417.5920306733435
				],
				[
					0,
					422.3919706411948
				],
				[
					0.6857430774443856,
					427.87754905678673
				],
				[
					0.6857430774443856,
					431.3060551846012
				],
				[
					1.3714861548886574,
					435.42030438986
				],
				[
					2.0571246026294148,
					438.84881051767445
				],
				[
					2.0571246026294148,
					440.90588280545205
				],
				[
					2.7428676800736866,
					443.6486981706739
				],
				[
					3.428506127814444,
					446.3915135358959
				],
				[
					3.428506127814444,
					449.1343289011178
				],
				[
					3.428506127814444,
					450.5057104263028
				],
				[
					4.1142492052588295,
					452.5628350289322
				],
				[
					4.1142492052588295,
					453.93421655411726
				],
				[
					4.799992282703101,
					455.3055980793023
				],
				[
					4.799992282703101,
					455.99134115674667
				],
				[
					4.799992282703101,
					456.67703191933913
				],
				[
					4.799992282703101,
					457.3627226819317
				],
				[
					4.799992282703101,
					458.0484134445243
				],
				[
					4.799992282703101,
					458.73410420711673
				],
				[
					5.485630730443859,
					460.1055380471536
				],
				[
					5.485630730443859,
					460.79122880974614
				],
				[
					5.485630730443859,
					462.84835341237556
				],
				[
					5.485630730443859,
					464.2197349375606
				],
				[
					5.485630730443859,
					466.27685954019
				],
				[
					5.485630730443859,
					467.64824106537503
				],
				[
					6.171373807888131,
					468.3339318279676
				],
				[
					6.171373807888131,
					469.70536566800445
				],
				[
					6.171373807888131,
					469.01962259056006
				],
				[
					6.171373807888131,
					469.01962259056006
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 49,
			"versionNonce": 1662772865,
			"isDeleted": false,
			"id": "bgXPKTJWCo-TjI1Rrh7ci",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -323.9177825503412,
			"y": 153.06489547081628,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.3714338400369002,
			"height": 45.9419611867728,
			"seed": 1616375756,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6856907625925714
				],
				[
					0,
					2.0570722877776006
				],
				[
					0.6856907625925714,
					5.485578415592045
				],
				[
					0.6856907625925714,
					10.285518383443332
				],
				[
					1.3714338400369002,
					15.771096799035377
				],
				[
					1.3714338400369002,
					20.571036766886664
				],
				[
					1.3714338400369002,
					25.370924419886137
				],
				[
					1.3714338400369002,
					30.17081207288561
				],
				[
					1.3714338400369002,
					34.28506127814444
				],
				[
					1.3714338400369002,
					37.0278243285145
				],
				[
					1.3714338400369002,
					37.713567405958884
				],
				[
					1.3714338400369002,
					38.39925816855134
				],
				[
					1.3714338400369002,
					39.08494893114391
				],
				[
					1.3714338400369002,
					39.770639693736484
				],
				[
					1.3714338400369002,
					41.14207353377333
				],
				[
					1.3714338400369002,
					42.51345505895836
				],
				[
					1.3714338400369002,
					43.884836584143386
				],
				[
					1.3714338400369002,
					45.25627042418023
				],
				[
					1.3714338400369002,
					45.9419611867728
				],
				[
					1.3714338400369002,
					45.9419611867728
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 61,
			"versionNonce": 1507622415,
			"isDeleted": false,
			"id": "H0hPV4XhAo2xJpq4I5EFg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -330.0891040433769,
			"y": 10.43896731294194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 374.39291100921855,
			"height": 5.485578415592045,
			"seed": 179905908,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6857430774443856,
					0
				],
				[
					-3.428506127814444,
					0
				],
				[
					-8.914136858258303,
					-0.6856907625924578
				],
				[
					-17.14253063907222,
					-0.6856907625924578
				],
				[
					-28.79953517740421,
					-1.3713815251850292
				],
				[
					-45.25632273903216,
					-2.7428153652218725
				],
				[
					-68.57012255628888,
					-3.428506127814444
				],
				[
					-90.5126454780642,
					-3.428506127814444
				],
				[
					-115.19787913535777,
					-3.428506127814444
				],
				[
					-140.56880355524402,
					-3.428506127814444
				],
				[
					-163.88265568735255,
					-3.428506127814444
				],
				[
					-189.2535801072387,
					-3.428506127814444
				],
				[
					-212.56743223934723,
					-4.114196890406902
				],
				[
					-230.3956536410119,
					-4.114196890406902
				],
				[
					-247.53818428008412,
					-4.114196890406902
				],
				[
					-266.0521487591932,
					-4.799887652999473
				],
				[
					-283.880370160858,
					-4.799887652999473
				],
				[
					-301.0229007999302,
					-4.799887652999473
				],
				[
					-316.108306836373,
					-4.799887652999473
				],
				[
					-327.7652590598532,
					-4.799887652999473
				],
				[
					-336.67934360325967,
					-4.799887652999473
				],
				[
					-343.53635585888856,
					-4.799887652999473
				],
				[
					-349.0219865893323,
					-4.799887652999473
				],
				[
					-352.45049271714674,
					-4.799887652999473
				],
				[
					-355.8789988449612,
					-4.799887652999473
				],
				[
					-359.30750497277563,
					-4.799887652999473
				],
				[
					-361.36457726055323,
					-4.799887652999473
				],
				[
					-365.47882646581206,
					-4.799887652999473
				],
				[
					-369.59302335621896,
					-4.799887652999473
				],
				[
					-372.33583872144095,
					-5.485578415592045
				],
				[
					-373.707220246626,
					-5.485578415592045
				],
				[
					-374.39291100921855,
					-5.485578415592045
				],
				[
					-374.39291100921855,
					-5.485578415592045
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 44,
			"versionNonce": 515731041,
			"isDeleted": false,
			"id": "sjRwvYxRiZw_Qzbal0cET",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -321.1750194999712,
			"y": -127.3869685622285,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 62.39880106325245,
			"height": 5.485630730443802,
			"seed": 873155148,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6856907625925146,
					0
				],
				[
					4.114196890406959,
					-0.6856907625925146
				],
				[
					8.228393780813917,
					-1.3714338400368433
				],
				[
					14.39971527385029,
					-2.7428153652219294
				],
				[
					21.25672752947918,
					-3.428506127814444
				],
				[
					26.056667497330466,
					-4.114196890406959
				],
				[
					30.856555150329996,
					-4.799939967851287
				],
				[
					34.970752040736954,
					-4.799939967851287
				],
				[
					38.3992581685514,
					-4.799939967851287
				],
				[
					41.14207353377327,
					-4.799939967851287
				],
				[
					44.57057966158777,
					-4.799939967851287
				],
				[
					47.999085789402216,
					-4.799939967851287
				],
				[
					52.79897344240169,
					-4.799939967851287
				],
				[
					56.913222647660405,
					-4.799939967851287
				],
				[
					60.34172877547485,
					-4.799939967851287
				],
				[
					61.71311030065999,
					-4.799939967851287
				],
				[
					62.39880106325245,
					-5.485630730443802
				],
				[
					62.39880106325245,
					-5.485630730443802
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 42,
			"versionNonce": 1222632495,
			"isDeleted": false,
			"id": "wGwGnt5k0qvE4Jo6Jvfdk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -332.83191940859956,
			"y": 8.381842710312299,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.7985163371028,
			"height": 2.7428153652218725,
			"seed": 189340492,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.3713815251850292,
					0
				],
				[
					4.799887652999473,
					0
				],
				[
					10.285518383443332,
					-0.6856907625924578
				],
				[
					17.142530639072163,
					-0.6856907625924578
				],
				[
					26.742305945071166,
					-0.6856907625924578
				],
				[
					37.0278243285145,
					0
				],
				[
					46.627651949365315,
					0.6857430774443856
				],
				[
					56.22747957021613,
					1.3714338400368433
				],
				[
					64.45587335103005,
					2.0571246026294148
				],
				[
					69.94150408147391,
					2.0571246026294148
				],
				[
					74.05570097188081,
					2.0571246026294148
				],
				[
					74.74139173447338,
					2.0571246026294148
				],
				[
					75.42713481191765,
					2.0571246026294148
				],
				[
					76.11282557451023,
					2.0571246026294148
				],
				[
					76.7985163371028,
					2.0571246026294148
				],
				[
					76.7985163371028,
					2.0571246026294148
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 46,
			"versionNonce": 547551809,
			"isDeleted": false,
			"id": "hWGuIRZ3wuCiYprQY81AI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -327.3463409930076,
			"y": 204.49243507317976,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.57012255628882,
			"height": 11.656952223480175,
			"seed": 1234716108,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6857430774442719
				],
				[
					4.799939967851344,
					-2.057124602629301
				],
				[
					10.971209146035847,
					-4.114249205258716
				],
				[
					20.571036766886664,
					-5.485630730443745
				],
				[
					29.48517362514491,
					-6.1713214930363165
				],
				[
					39.77069200858824,
					-7.54275533307316
				],
				[
					45.942013501624615,
					-8.914136858258189
				],
				[
					50.741901154624145,
					-8.914136858258189
				],
				[
					52.799025757253446,
					-9.59982762085076
				],
				[
					54.17040728243859,
					-9.59982762085076
				],
				[
					55.54178880762362,
					-9.59982762085076
				],
				[
					56.91322264766046,
					-9.59982762085076
				],
				[
					58.97029493543806,
					-9.59982762085076
				],
				[
					61.713110300659935,
					-10.285518383443332
				],
				[
					63.08454414069678,
					-10.285518383443332
				],
				[
					64.45592566588192,
					-10.971261460887604
				],
				[
					65.82730719106695,
					-10.971261460887604
				],
				[
					67.1987410311038,
					-11.656952223480175
				],
				[
					68.57012255628882,
					-11.656952223480175
				],
				[
					68.57012255628882,
					-11.656952223480175
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 39,
			"versionNonce": 1792116303,
			"isDeleted": false,
			"id": "k6caFYlZZDnKXL1wLhct9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -264.94753992975507,
			"y": -132.1869085300798,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.971261460887604,
			"height": 1.3713815251850292,
			"seed": 1286667596,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6857430774442719,
					0
				],
				[
					1.3714338400368433,
					0
				],
				[
					2.7428153652218725,
					-0.6856907625925146
				],
				[
					4.114249205258716,
					-0.6856907625925146
				],
				[
					5.485630730443859,
					-0.6856907625925146
				],
				[
					6.857012255628888,
					-0.6856907625925146
				],
				[
					7.54275533307316,
					-0.6856907625925146
				],
				[
					8.228446095665731,
					-1.3713815251850292
				],
				[
					8.914136858258303,
					-1.3713815251850292
				],
				[
					9.59982762085076,
					-1.3713815251850292
				],
				[
					10.285518383443332,
					-1.3713815251850292
				],
				[
					10.971261460887604,
					-1.3713815251850292
				],
				[
					10.971261460887604,
					-1.3713815251850292
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 162269729,
			"isDeleted": false,
			"id": "AIH5WdnS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -240.26225395760935,
			"y": -147.27231456652277,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127.55989074707031,
			"height": 25,
			"seed": 1272494068,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(second ESP)",
			"rawText": "(second ESP)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(second ESP)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 109,
			"versionNonce": 1049224303,
			"isDeleted": false,
			"id": "PpPARAMv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -243.01477979307708,
			"y": -3.0895949883731646,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.85990905761719,
			"height": 25,
			"seed": 1107023732,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(thid ESP)",
			"rawText": "(thid ESP)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(thid ESP)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 39,
			"versionNonce": 851975681,
			"isDeleted": false,
			"id": "lnArmqg0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -243.69070777057203,
			"y": 184.60708906888556,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 125.85987854003906,
			"height": 25,
			"seed": 1000688716,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(fourth ESP)",
			"rawText": "(fourth ESP)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(fourth ESP)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 1406238351,
			"isDeleted": false,
			"id": "zTbpD40d",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -528.5331643721627,
			"y": -418.96747722751536,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.77993774414062,
			"height": 25,
			"seed": 895833804,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "crystal",
			"rawText": "crystal",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "crystal",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "freedraw",
			"version": 36,
			"versionNonce": 720811489,
			"isDeleted": false,
			"id": "_tzpKC4q4YLaWFmxMbeeM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -495.343141255916,
			"y": -385.2107496980363,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 0.6857430774443287,
			"height": 23.9995167372752,
			"seed": 1060055284,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6857430774443287,
					0
				],
				[
					0.6857430774443287,
					0.6856907625925714
				],
				[
					0.6857430774443287,
					4.79988765299953
				],
				[
					0.6857430774443287,
					8.914110700832396
				],
				[
					0.6857430774443287,
					15.085432193868769
				],
				[
					0,
					19.199629084275728
				],
				[
					0,
					21.942444449497657
				],
				[
					0,
					23.313825974682686
				],
				[
					0,
					23.9995167372752
				],
				[
					0,
					23.9995167372752
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 130,
			"versionNonce": 761320623,
			"isDeleted": false,
			"id": "G3dn3punQ6hqJ3kX_t4Sl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -306.08950883382744,
			"y": -391.38204503364534,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 82.96983783013917,
			"height": 558.8464988337539,
			"seed": 44623948,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6856907625925146
				],
				[
					0,
					1.3714076826109363
				],
				[
					0,
					7.542703018221346
				],
				[
					0,
					16.456813719053798
				],
				[
					-0.6856907625925146,
					27.428049022515495
				],
				[
					-0.6856907625925146,
					42.51348121638421
				],
				[
					-1.3713815251850292,
					58.28460417284549
				],
				[
					-2.0570722877776006,
					76.11282557451023
				],
				[
					-2.0570722877776006,
					92.56966545098987
				],
				[
					-2.0570722877776006,
					109.02647917004367
				],
				[
					-2.7428153652219294,
					126.16900980911589
				],
				[
					-2.7428153652219294,
					143.31156660561402
				],
				[
					-2.7428153652219294,
					161.82547876987127
				],
				[
					-2.7428153652219294,
					180.33944324898033
				],
				[
					-2.7428153652219294,
					196.11054004801565
				],
				[
					-2.7428153652219294,
					207.76749227149588
				],
				[
					-2.7428153652219294,
					218.73870141753173
				],
				[
					-2.7428153652219294,
					229.70991056356758
				],
				[
					-2.7428153652219294,
					240.68111970960342
				],
				[
					-2.7428153652219294,
					251.65232885563927
				],
				[
					-2.7428153652219294,
					262.62359031652693
				],
				[
					-2.7428153652219294,
					272.90910869997026
				],
				[
					-3.428506127814444,
					282.5088840059692
				],
				[
					-3.428506127814444,
					291.4230208642275
				],
				[
					-3.428506127814444,
					301.02284848507827
				],
				[
					-4.114196890406959,
					309.2512422658923
				],
				[
					-4.114196890406959,
					318.85106988674306
				],
				[
					-4.799887652999473,
					327.76520674500136
				],
				[
					-5.485578415592045,
					335.9936005258153
				],
				[
					-6.171321493036373,
					344.2219943066292
				],
				[
					-6.171321493036373,
					352.45044040229493
				],
				[
					-6.171321493036373,
					358.62176189533125
				],
				[
					-6.857012255628888,
					365.47877415096013
				],
				[
					-6.857012255628888,
					372.335786406589
				],
				[
					-6.857012255628888,
					377.1356740595885
				],
				[
					-6.857012255628888,
					382.62130479003235
				],
				[
					-6.857012255628888,
					387.4211924430318
				],
				[
					-6.857012255628888,
					392.2210800960314
				],
				[
					-6.857012255628888,
					397.0210200638827
				],
				[
					-6.171321493036373,
					401.8209077168822
				],
				[
					-6.171321493036373,
					406.62084768473346
				],
				[
					-5.485578415592045,
					411.42073533773294
				],
				[
					-5.485578415592045,
					416.2206229907324
				],
				[
					-5.485578415592045,
					422.39194448376884
				],
				[
					-4.799887652999473,
					427.8775752142127
				],
				[
					-4.799887652999473,
					434.048896707249
				],
				[
					-4.799887652999473,
					439.53447512284106
				],
				[
					-4.114196890406959,
					445.0201058532848
				],
				[
					-4.114196890406959,
					449.8199935062844
				],
				[
					-4.114196890406959,
					455.30562423672814
				],
				[
					-4.114196890406959,
					459.41982112713515
				],
				[
					-4.114196890406959,
					464.905451857579
				],
				[
					-3.428506127814444,
					469.7053395105785
				],
				[
					-3.428506127814444,
					474.50522716357796
				],
				[
					-3.428506127814444,
					479.30516713142924
				],
				[
					-3.428506127814444,
					484.7907455470213
				],
				[
					-3.428506127814444,
					488.9049947522801
				],
				[
					-3.428506127814444,
					493.7048824052796
				],
				[
					-2.7428153652219294,
					497.8190792956865
				],
				[
					-2.7428153652219294,
					503.30471002613035
				],
				[
					-2.7428153652219294,
					507.41890691653737
				],
				[
					-2.0570722877776006,
					512.9045376469811
				],
				[
					-2.0570722877776006,
					517.7044252999807
				],
				[
					-2.0570722877776006,
					521.1329314277951
				],
				[
					-1.3713815251850292,
					524.5614375556096
				],
				[
					-1.3713815251850292,
					527.989943683424
				],
				[
					-0.6856907625925146,
					530.0470682860533
				],
				[
					-0.6856907625925146,
					532.1041405738309
				],
				[
					-0.6856907625925146,
					533.4755744138678
				],
				[
					-0.6856907625925146,
					534.8469559390528
				],
				[
					0,
					536.9040805416822
				],
				[
					0,
					538.2754620668672
				],
				[
					0,
					538.9611528294598
				],
				[
					0,
					541.7039681946817
				],
				[
					0.6856907625925146,
					543.7610927973111
				],
				[
					0.6856907625925146,
					545.8181650850887
				],
				[
					1.3714338400368433,
					547.8752896877181
				],
				[
					1.3714338400368433,
					548.5609804503106
				],
				[
					1.3714338400368433,
					549.9323619754957
				],
				[
					2.057124602629358,
					551.989486578125
				],
				[
					2.057124602629358,
					553.3608681033102
				],
				[
					2.057124602629358,
					554.0466111807544
				],
				[
					2.057124602629358,
					554.732301943347
				],
				[
					2.057124602629358,
					555.4179927059395
				],
				[
					2.057124602629358,
					556.103683468532
				],
				[
					2.057124602629358,
					556.7893742311246
				],
				[
					2.057124602629358,
					557.4751173085689
				],
				[
					2.057124602629358,
					558.1608080711615
				],
				[
					2.057124602629358,
					558.8464988337539
				],
				[
					2.7428153652219294,
					558.8464988337539
				],
				[
					4.114196890406959,
					558.8464988337539
				],
				[
					6.857012255628888,
					558.8464988337539
				],
				[
					8.914136858258246,
					558.8464988337539
				],
				[
					13.028333748665261,
					558.8464988337539
				],
				[
					16.456839876479705,
					558.1608080711615
				],
				[
					20.571036766886664,
					557.4751173085689
				],
				[
					24.685233657293622,
					557.4751173085689
				],
				[
					29.48517362514491,
					557.4751173085689
				],
				[
					35.656495118181226,
					557.4751173085689
				],
				[
					41.82776429636584,
					557.4751173085689
				],
				[
					47.99908578940216,
					557.4751173085689
				],
				[
					51.4275919172166,
					557.4751173085689
				],
				[
					55.54178880762362,
					557.4751173085689
				],
				[
					58.28460417284549,
					556.7893742311246
				],
				[
					61.02741953806736,
					556.7893742311246
				],
				[
					64.45592566588181,
					556.103683468532
				],
				[
					67.1987410311038,
					556.103683468532
				],
				[
					68.57012255628882,
					555.4179927059395
				],
				[
					69.94155639632567,
					555.4179927059395
				],
				[
					70.62724715891824,
					555.4179927059395
				],
				[
					71.3129379215107,
					555.4179927059395
				],
				[
					71.99862868410327,
					555.4179927059395
				],
				[
					72.68431944669584,
					555.4179927059395
				],
				[
					74.05575328673268,
					555.4179927059395
				],
				[
					74.74144404932514,
					555.4179927059395
				],
				[
					75.42713481191771,
					555.4179927059395
				],
				[
					76.11282557451028,
					555.4179927059395
				],
				[
					76.11282557451028,
					555.4179927059395
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 38,
			"versionNonce": 1967608257,
			"isDeleted": false,
			"id": "O-vSO1rvJjE8hZygxm6xh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -312.9465210894563,
			"y": -24.531889357500063,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 81.59845630495403,
			"height": 8.228393780813917,
			"seed": 1735921228,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6856907625925146,
					0
				],
				[
					2.0571246026294148,
					1.3713815251850292
				],
				[
					5.485630730443859,
					2.057124602629301
				],
				[
					8.914136858258246,
					2.7428153652218725
				],
				[
					13.714024511257776,
					3.428506127814444
				],
				[
					20.571036766886664,
					4.799887652999473
				],
				[
					27.42804902251555,
					5.485630730443745
				],
				[
					34.28506127814438,
					6.1713214930363165
				],
				[
					41.82776429636584,
					6.857012255628774
				],
				[
					48.68477655199473,
					6.857012255628774
				],
				[
					54.17040728243859,
					6.857012255628774
				],
				[
					58.97029493543806,
					6.857012255628774
				],
				[
					65.14161642847438,
					7.542703018221346
				],
				[
					69.2558133188814,
					7.542703018221346
				],
				[
					72.68431944669584,
					8.228393780813917
				],
				[
					75.42713481191771,
					8.228393780813917
				],
				[
					76.11282557451028,
					8.228393780813917
				],
				[
					76.79856865195455,
					8.228393780813917
				],
				[
					77.48425941454713,
					8.228393780813917
				],
				[
					78.16995017713958,
					8.228393780813917
				],
				[
					78.85564093973215,
					8.228393780813917
				],
				[
					79.54133170232473,
					8.228393780813917
				],
				[
					80.227074779769,
					8.228393780813917
				],
				[
					80.91276554236157,
					8.228393780813917
				],
				[
					81.59845630495403,
					8.228393780813917
				],
				[
					81.59845630495403,
					8.228393780813917
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 37,
			"versionNonce": 1658873551,
			"isDeleted": false,
			"id": "dNftJN8zldRfGA03UNVoO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -309.5180149616419,
			"y": -167.15776520052168,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 92.56966545098993,
			"height": 4.799939967851287,
			"seed": 892393804,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6857430774443856
				],
				[
					2.0571246026294148,
					0.6857430774443856
				],
				[
					7.5427030182214025,
					0.6857430774443856
				],
				[
					13.028333748665261,
					0.6857430774443856
				],
				[
					21.25672752947918,
					0.6857430774443856
				],
				[
					30.17086438773748,
					0.6857430774443856
				],
				[
					37.02787664336637,
					0.6857430774443856
				],
				[
					43.199198136402686,
					0.6857430774443856
				],
				[
					50.741901154624145,
					0.6857430774443856
				],
				[
					55.54178880762362,
					1.3714338400368433
				],
				[
					59.656038012882334,
					1.3714338400368433
				],
				[
					61.713110300659935,
					1.3714338400368433
				],
				[
					63.77023490328935,
					2.0571246026294148
				],
				[
					65.82730719106695,
					2.0571246026294148
				],
				[
					68.57012255628882,
					2.7428153652218725
				],
				[
					72.68431944669584,
					2.7428153652218725
				],
				[
					76.79856865195455,
					3.428506127814444
				],
				[
					80.91276554236157,
					4.1142492052588295
				],
				[
					82.96983783013917,
					4.1142492052588295
				],
				[
					84.34127167017601,
					4.1142492052588295
				],
				[
					85.71265319536104,
					4.1142492052588295
				],
				[
					88.45546856058291,
					4.1142492052588295
				],
				[
					90.51259316321233,
					4.799939967851287
				],
				[
					92.56966545098993,
					4.799939967851287
				],
				[
					92.56966545098993,
					4.799939967851287
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 67,
			"versionNonce": 114913697,
			"isDeleted": false,
			"id": "gRrNpdlsSJ5-Z9mQ-hdpe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -307.46089035901275,
			"y": -354.35416839027914,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 141.25449431783647,
			"height": 33.599318200700054,
			"seed": 1415353588,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6856907625925714
				],
				[
					3.428506127814444,
					-0.6856907625925714
				],
				[
					8.914084543406489,
					-0.6856907625925714
				],
				[
					16.456839876479705,
					-0.6856907625925714
				],
				[
					25.370924419886137,
					-1.371381525185086
				],
				[
					36.34213356592204,
					-1.371381525185086
				],
				[
					46.62765194936537,
					-2.0570722877776006
				],
				[
					57.598913410252976,
					-2.0570722877776006
				],
				[
					69.25581331888134,
					-2.0570722877776006
				],
				[
					78.85564093973221,
					-1.371381525185086
				],
				[
					87.08403472054613,
					-0.6856907625925714
				],
				[
					93.25540852843426,
					-0.6856907625925714
				],
				[
					95.31242850136005,
					-0.6856907625925714
				],
				[
					97.36955310398946,
					-0.6856907625925714
				],
				[
					98.05529618143373,
					-0.6856907625925714
				],
				[
					100.7980592318039,
					-0.6856907625925714
				],
				[
					104.22656535961835,
					0
				],
				[
					106.96943303969203,
					0
				],
				[
					110.39793916750648,
					0.6856907625925146
				],
				[
					113.82644529532092,
					0.6856907625925146
				],
				[
					116.56920834569098,
					0.6856907625925146
				],
				[
					119.99771447350543,
					1.3714338400368433
				],
				[
					124.79760212650501,
					2.057124602629358
				],
				[
					128.22610825431946,
					2.7428153652218725
				],
				[
					130.28323285694876,
					2.7428153652218725
				],
				[
					131.6546143821339,
					2.7428153652218725
				],
				[
					132.34035745957817,
					2.7428153652218725
				],
				[
					133.02599590731893,
					2.7428153652218725
				],
				[
					134.3974820622076,
					2.7428153652218725
				],
				[
					135.08312050994834,
					2.7428153652218725
				],
				[
					135.76886358739262,
					2.7428153652218725
				],
				[
					136.45450203513337,
					2.7428153652218725
				],
				[
					137.14024511257765,
					2.7428153652218725
				],
				[
					137.82598819002203,
					2.7428153652218725
				],
				[
					137.82598819002203,
					3.428506127814387
				],
				[
					138.5116266377628,
					3.428506127814387
				],
				[
					139.19736971520706,
					4.799939967851287
				],
				[
					139.19736971520706,
					6.1713214930363165
				],
				[
					139.88300816294782,
					8.228446095665731
				],
				[
					139.88300816294782,
					10.285518383443332
				],
				[
					139.88300816294782,
					13.028333748665204
				],
				[
					139.88300816294782,
					15.771149113887077
				],
				[
					139.88300816294782,
					19.19965524170152
				],
				[
					140.5687512403921,
					21.942470606923507
				],
				[
					140.5687512403921,
					23.313852132108536
				],
				[
					140.5687512403921,
					24.685233657293566
				],
				[
					140.5687512403921,
					26.05666749733041
				],
				[
					140.5687512403921,
					26.74235825992298
				],
				[
					140.5687512403921,
					27.42804902251555
				],
				[
					140.5687512403921,
					28.799482862552395
				],
				[
					140.5687512403921,
					29.485173625144853
				],
				[
					141.25449431783647,
					30.170864387737424
				],
				[
					141.25449431783647,
					30.856555150329996
				],
				[
					141.25449431783647,
					31.542245912922453
				],
				[
					141.25449431783647,
					31.542245912922453
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 65,
			"versionNonce": 48805103,
			"isDeleted": false,
			"id": "r8Ca8q0R",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -379.45967598767146,
			"y": -425.66710631179205,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 184.1998291015625,
			"height": 25,
			"seed": 1490858484,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Oscillator (backup)",
			"rawText": "Oscillator (backup)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Oscillator (backup)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 81565057,
			"isDeleted": false,
			"id": "1jq8McEe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -632.0136877831392,
			"y": -469.3664806859926,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 184.1998291015625,
			"height": 25,
			"seed": 1224598476,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Oscillator (backup)",
			"rawText": "Oscillator (backup)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Oscillator (backup)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "freedraw",
			"version": 73,
			"versionNonce": 889339663,
			"isDeleted": false,
			"id": "Otgr35GKKFyLsZR-T-Iql",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -572.827400670466,
			"y": -442.1239461882718,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 72.68431944669584,
			"height": 84.34127167017596,
			"seed": 1515850484,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6856907625925714,
					1.3714338400368433
				],
				[
					0.6856907625925714,
					4.799939967851287
				],
				[
					0.6856907625925714,
					8.228446095665731
				],
				[
					0,
					13.714024511257776
				],
				[
					-0.6857430774442719,
					19.199655241701578
				],
				[
					-1.3714338400368433,
					23.313852132108593
				],
				[
					-2.057124602629301,
					27.42804902251555
				],
				[
					-2.7428153652218725,
					30.856555150329996
				],
				[
					-3.428506127814444,
					35.65649511818128
				],
				[
					-4.114249205258716,
					39.77069200858824
				],
				[
					-4.799939967851287,
					41.82776429636584
				],
				[
					-4.799939967851287,
					44.57057966158777
				],
				[
					-5.485630730443745,
					46.62770426421713
				],
				[
					-6.1713214930363165,
					48.68477655199473
				],
				[
					-6.1713214930363165,
					50.74190115462409
				],
				[
					-6.857012255628888,
					52.7990257572535
				],
				[
					-6.857012255628888,
					54.17040728243853
				],
				[
					-6.857012255628888,
					55.54178880762356
				],
				[
					-6.857012255628888,
					56.22753188506795
				],
				[
					-6.857012255628888,
					57.598913410252976
				],
				[
					-6.857012255628888,
					58.970294935438005
				],
				[
					-6.857012255628888,
					61.02741953806742
				],
				[
					-6.857012255628888,
					61.71311030065999
				],
				[
					-6.1713214930363165,
					61.71311030065999
				],
				[
					-4.114249205258716,
					61.71311030065999
				],
				[
					-0.6857430774442719,
					61.71311030065999
				],
				[
					4.799887652999587,
					61.71311030065999
				],
				[
					10.285518383443332,
					61.02741953806742
				],
				[
					15.771096799035377,
					61.02741953806742
				],
				[
					20.571036766886664,
					61.02741953806742
				],
				[
					25.37092441988625,
					61.02741953806742
				],
				[
					30.17081207288561,
					61.02741953806742
				],
				[
					34.28506127814444,
					61.02741953806742
				],
				[
					37.713567405958884,
					61.02741953806742
				],
				[
					41.14207353377333,
					61.02741953806742
				],
				[
					43.19914582155093,
					61.02741953806742
				],
				[
					45.25627042418023,
					61.02741953806742
				],
				[
					46.62765194936537,
					61.02741953806742
				],
				[
					47.999085789402216,
					61.02741953806742
				],
				[
					50.741848839772274,
					61.02741953806742
				],
				[
					53.48466420499426,
					61.02741953806742
				],
				[
					56.22747957021613,
					61.02741953806742
				],
				[
					58.28460417284555,
					61.02741953806742
				],
				[
					60.34167646062315,
					61.02741953806742
				],
				[
					61.71311030065999,
					61.02741953806742
				],
				[
					63.08449182584502,
					61.02741953806742
				],
				[
					64.4558733510301,
					61.02741953806742
				],
				[
					65.14161642847444,
					61.02741953806742
				],
				[
					65.14161642847444,
					61.71311030065999
				],
				[
					65.14161642847444,
					62.39880106325245
				],
				[
					65.82730719106695,
					64.45592566588186
				],
				[
					65.82730719106695,
					65.8273071910669
				],
				[
					65.82730719106695,
					69.25581331888134
				],
				[
					65.82730719106695,
					71.31293792151075
				],
				[
					65.82730719106695,
					74.05575328673262
				],
				[
					65.82730719106695,
					77.48425941454707
				],
				[
					65.82730719106695,
					80.22707477976905
				],
				[
					65.14161642847444,
					82.28414706754666
				],
				[
					65.14161642847444,
					83.6555809075835
				],
				[
					65.14161642847444,
					84.34127167017596
				],
				[
					65.14161642847444,
					84.34127167017596
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 1116749153,
			"isDeleted": false,
			"id": "aLS85O1T",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 133.44486165931198,
			"y": -13.560680211466547,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 220.67979431152344,
			"height": 25,
			"seed": 135099596,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Motor Driver (haptics)",
			"rawText": "Motor Driver (haptics)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Motor Driver (haptics)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "freedraw",
			"version": 109,
			"versionNonce": 463832367,
			"isDeleted": false,
			"id": "Byemy_KUJsa6_WB3vuD39",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -140.8357331955466,
			"y": -289.898295039251,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 265.36635336689704,
			"height": 286.62313321122804,
			"seed": 139389172,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6856907625925714,
					0
				],
				[
					-0.6856907625925714,
					1.371407682610993
				],
				[
					-1.371381525185086,
					2.7428153652219294
				],
				[
					-2.0570722877776006,
					6.857012255628888
				],
				[
					-2.0570722877776006,
					13.028333748665261
				],
				[
					-2.0570722877776006,
					19.88534600429415
				],
				[
					-2.0570722877776006,
					26.056641339904616
				],
				[
					-1.371381525185086,
					33.599370515551925
				],
				[
					0,
					39.08497508856982
				],
				[
					1.3714338400368433,
					43.88488889899526
				],
				[
					2.057124602629358,
					47.999085789402216
				],
				[
					2.7428153652218725,
					52.798999599827596
				],
				[
					4.799939967851287,
					58.97032109286397
				],
				[
					6.857012255628888,
					64.45592566588186
				],
				[
					8.914136858258246,
					70.62722100149233
				],
				[
					10.97126146088766,
					76.11285173193619
				],
				[
					13.028333748665204,
					81.59845630495408
				],
				[
					14.399767588702105,
					86.39837011537952
				],
				[
					16.45683987647965,
					92.56966545098993
				],
				[
					19.199655241701578,
					97.36957926141537
				],
				[
					21.942470606923507,
					102.85518383443326
				],
				[
					23.313852132108536,
					106.2836899622477
				],
				[
					25.37097673473795,
					111.083629930099
				],
				[
					27.428049022515495,
					115.19782682050601
				],
				[
					30.170864387737424,
					119.31202371091297
				],
				[
					33.59937051555187,
					124.79765444135677
				],
				[
					36.3421858807738,
					129.5975420943563
				],
				[
					39.77069200858824,
					133.71173898476326
				],
				[
					42.513507373810114,
					137.1402451125777
				],
				[
					44.570579661587715,
					139.88306047779957
				],
				[
					46.62770426421713,
					143.31156660561402
				],
				[
					49.370519629439,
					146.05438197083595
				],
				[
					52.799025757253446,
					148.79719733605788
				],
				[
					55.541841122475375,
					152.91139422646484
				],
				[
					58.97034725028982,
					156.33990035427928
				],
				[
					63.08454414069678,
					159.76840648209372
				],
				[
					65.82735950591871,
					162.51122184731565
				],
				[
					68.57012255628882,
					165.25398489768577
				],
				[
					71.31293792151075,
					167.31110950031513
				],
				[
					74.7414440493252,
					170.73961562812957
				],
				[
					78.16995017713964,
					174.16812175594401
				],
				[
					82.96989014499093,
					177.59662788375846
				],
				[
					87.08408703539789,
					181.0251340115729
				],
				[
					89.82690240061982,
					184.45364013938735
				],
				[
					93.25540852843426,
					187.19645550460928
				],
				[
					95.3124808162118,
					189.25352779238682
				],
				[
					98.74098694402625,
					191.99634315760875
				],
				[
					102.8551838344332,
					195.4248492854232
				],
				[
					105.59799919965513,
					198.16766465064512
				],
				[
					109.7121960900621,
					202.28186154105208
				],
				[
					114.51213605791344,
					205.71036766886652
				],
				[
					117.94064218572788,
					209.13887379668097
				],
				[
					122.74052983872735,
					212.5673799244954
				],
				[
					126.1690359665418,
					215.31019528971734
				],
				[
					129.59754209435624,
					218.7387014175318
				],
				[
					133.7117389847632,
					220.79582602016114
				],
				[
					136.45455434998513,
					223.53858907053126
				],
				[
					139.19736971520706,
					225.59571367316062
				],
				[
					141.94018508042893,
					226.9670951983457
				],
				[
					144.68300044565086,
					229.02421980097506
				],
				[
					148.1115065734653,
					231.767035166197
				],
				[
					152.91139422646478,
					235.19554129401143
				],
				[
					157.0255911168718,
					237.93835665923336
				],
				[
					162.5112218473156,
					240.68111970960348
				],
				[
					167.31110950031507,
					243.4239350748254
				],
				[
					174.16812175594396,
					246.85244120263985
				],
				[
					180.33944324898033,
					249.59525656786172
				],
				[
					187.88214626720173,
					253.02376269567617
				],
				[
					195.42484928542314,
					256.4522688234906
				],
				[
					201.5961707784595,
					259.1950841887125
				],
				[
					207.76749227149588,
					260.5664657138976
				],
				[
					213.25312300193968,
					262.62359031652693
				],
				[
					218.73870141753173,
					265.3664056817489
				],
				[
					224.22433214797553,
					267.4234779695265
				],
				[
					229.024219800975,
					269.4806025721558
				],
				[
					234.50985053141886,
					270.85198409734096
				],
				[
					238.62404742182588,
					272.2234179373778
				],
				[
					241.36686278704775,
					274.2804902251554
				],
				[
					244.10967815226962,
					274.96618098774786
				],
				[
					246.16675044004722,
					275.65192406519225
				],
				[
					246.8524412026398,
					276.3376148277847
				],
				[
					248.22387504267664,
					277.0233055903773
				],
				[
					249.59525656786167,
					278.3946871155623
				],
				[
					252.33807193308365,
					280.4518117181917
				],
				[
					255.08088729830553,
					281.1375024807842
				],
				[
					255.7665780608981,
					281.82319324337675
				],
				[
					256.45226882349056,
					281.82319324337675
				],
				[
					256.45226882349056,
					282.50893632082114
				],
				[
					257.1379595860831,
					283.1946270834136
				],
				[
					258.50939342611997,
					283.88031784600616
				],
				[
					259.19508418871254,
					283.88031784600616
				],
				[
					259.880774951305,
					284.5660086085986
				],
				[
					260.56646571389757,
					285.2516993711912
				],
				[
					261.9378995539344,
					285.9374424486356
				],
				[
					261.9378995539344,
					286.62313321122804
				],
				[
					262.6235903165269,
					286.62313321122804
				],
				[
					263.30928107911944,
					286.62313321122804
				],
				[
					263.30928107911944,
					286.62313321122804
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 110,
			"versionNonce": 2135157057,
			"isDeleted": false,
			"id": "hVRw2FKO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 447.5828180565278,
			"y": -111.41622918859366,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 155.73992919921875,
			"height": 25,
			"seed": 831477364,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "any mA @ 3.5 V",
			"rawText": "any mA @ 3.5 V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "any mA @ 3.5 V",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 1983579983,
			"isDeleted": false,
			"id": "HbStJU8o",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -641.217200254019,
			"y": -289.81625360265616,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 254.6999053955078,
			"height": 50,
			"seed": 1069263092,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "53 ma @ 5 + 3.3 + 1.8 V\n(mostly 3.3 V)",
			"rawText": "53 ma @ 5 + 3.3 + 1.8 V\n(mostly 3.3 V)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "53 ma @ 5 + 3.3 + 1.8 V\n(mostly 3.3 V)",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 67,
			"versionNonce": 1683429665,
			"isDeleted": false,
			"id": "KSPYLUTo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 449.9827661766451,
			"y": -330.6163634659374,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 154.61993408203125,
			"height": 75,
			"seed": 529531852,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "30 mA @ 2.8 V\n35 mA @ 1.2 V\n6 mA @ 3.3 V",
			"rawText": "30 mA @ 2.8 V\n35 mA @ 1.2 V\n6 mA @ 3.3 V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "30 mA @ 2.8 V\n35 mA @ 1.2 V\n6 mA @ 3.3 V",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 52118895,
			"isDeleted": false,
			"id": "1NqTY7E3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 307.5828485741062,
			"y": -201.01620477453116,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 178.47991943359375,
			"height": 25,
			"seed": 1742092620,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "5.7 mA @ cca 2 V",
			"rawText": "5.7 mA @ cca 2 V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5.7 mA @ cca 2 V",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1127828737,
			"isDeleted": false,
			"id": "x8wVP4jL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -857.1577865074026,
			"y": -327.4756581939989,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 105.55995178222656,
			"height": 25,
			"seed": 1390065012,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1 A @ 5 V",
			"rawText": "-1 A @ 5 V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1 A @ 5 V",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 586,
			"versionNonce": 1088700225,
			"isDeleted": false,
			"id": "hiiRsVWm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -149.5208656685785,
			"y": -420.57924492727466,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.7010498046875,
			"height": 16.028815764140663,
			"seed": 1330356172,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933390097,
			"link": "https://community.nxp.com/t5/LPC-FAQs/How-to-calculate-the-value-of-crystal-load-capacitors/m-p/464589",
			"locked": false,
			"fontSize": 12.823052611312532,
			"fontFamily": 1,
			"text": "🌐[[load cap calculation]]",
			"rawText": "[[https://community.nxp.com/t5/LPC-FAQs/How-to-calculate-the-value-of-crystal-load-capacitors/m-p/464589|load cap calculation]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[load cap calculation]]",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 209,
			"versionNonce": 58782721,
			"isDeleted": false,
			"id": "QXWKhf9Y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -61.092674506085146,
			"y": -349.4256402855272,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.0322265625,
			"height": 12.215597429806746,
			"seed": 738533108,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933383963,
			"link": "https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf",
			"locked": false,
			"fontSize": 9.772477943845397,
			"fontFamily": 1,
			"text": "🌐[[datsheet]]",
			"rawText": "[[https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf|datsheet]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[datsheet]]",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 1174013857,
			"isDeleted": false,
			"id": "MLY6WYG3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -61.627687661917236,
			"y": -334.0963989236938,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 75.563232421875,
			"height": 12.215597429806746,
			"seed": 1001494900,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933386719,
			"link": "https://www.espressif.com/sites/default/files/documentation/esp32_hardware_design_guidelines_en.pdf",
			"locked": false,
			"fontSize": 9.772477943845397,
			"fontFamily": 1,
			"text": "🌐[[hw design]]",
			"rawText": "[[https://www.espressif.com/sites/default/files/documentation/esp32_hardware_design_guidelines_en.pdf|hw design]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[hw design]]",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 139,
			"versionNonce": 145807937,
			"isDeleted": false,
			"id": "dw3TyTC5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 42.508145711351176,
			"y": -347.16518443663693,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 138.2376708984375,
			"height": 12.215597429806746,
			"seed": 102604,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689934747965,
			"link": "https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/XIAO_ESP32S3_SCH_v1.1.pdf",
			"locked": false,
			"fontSize": 9.772477943845397,
			"fontFamily": 1,
			"text": "🌐[[xiao sense schematics]]",
			"rawText": "[[https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/XIAO_ESP32S3_SCH_v1.1.pdf|xiao sense schematics]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[xiao sense schematics]]",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 631358127,
			"isDeleted": false,
			"id": "QLMu9XLC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 44.10361035047637,
			"y": -331.53229544389325,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.58332824707031,
			"height": 12.215597429806746,
			"seed": 100210164,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689935142368,
			"link": "obsidian://open?vault=Trackinator&file=pdfs%2FESP32_CAM_V1.6.pdf",
			"locked": false,
			"fontSize": 9.772477943845397,
			"fontFamily": 1,
			"text": "🌐[[esp cam schematic]]",
			"rawText": "[[obsidian://open?vault=Trackinator&file=pdfs%2FESP32_CAM_V1.6.pdf|esp cam schematic]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[esp cam schematic]]",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "freedraw",
			"version": 93,
			"versionNonce": 1476722849,
			"isDeleted": false,
			"id": "k1KjV5fsJkcTR02U4JELg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -180.66174043725846,
			"y": -293.0592181599494,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 114.26994772518378,
			"height": 108.25575884650732,
			"seed": 658258804,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.8591595818013502,
					0
				],
				[
					-0.8591595818013502,
					0.8591595818014639
				],
				[
					-1.7183191636029278,
					1.7183909696690876
				],
				[
					-1.7183191636029278,
					3.436674230238964
				],
				[
					-2.577478745404278,
					5.155029296875
				],
				[
					-2.577478745404278,
					7.7325439453125
				],
				[
					-2.577478745404278,
					9.450899011948536
				],
				[
					-3.4366383272058556,
					10.310094496783051
				],
				[
					-3.4366383272058556,
					11.169218175551464
				],
				[
					-4.295869715073422,
					11.169218175551464
				],
				[
					-6.01418887867635,
					11.169218175551464
				],
				[
					-9.450899011948422,
					12.028413660386036
				],
				[
					-12.887537339154278,
					12.028413660386036
				],
				[
					-19.760957605698422,
					12.028413660386036
				],
				[
					-27.49353745404403,
					12.028413660386036
				],
				[
					-35.22604549632342,
					12.028413660386036
				],
				[
					-42.95862534466903,
					11.169218175551464
				],
				[
					-50.69113338694842,
					10.310094496783051
				],
				[
					-58.42371323529403,
					9.450899011948536
				],
				[
					-67.0154526654411,
					8.591703527113964
				],
				[
					-75.60719209558818,
					7.7325439453125
				],
				[
					-80.76222139246318,
					6.873348460477928
				],
				[
					-85.91725068933818,
					6.873348460477928
				],
				[
					-88.49472943474257,
					6.014260684742624
				],
				[
					-90.21312040441171,
					6.014260684742624
				],
				[
					-92.7905991498161,
					6.014260684742624
				],
				[
					-94.50899011948525,
					6.014260684742624
				],
				[
					-97.08646886488964,
					5.155029296875
				],
				[
					-100.52317899816171,
					5.155029296875
				],
				[
					-101.38233857996318,
					5.155029296875
				],
				[
					-103.95988913143378,
					5.155029296875
				],
				[
					-105.67820829503671,
					5.155029296875
				],
				[
					-106.53736787683818,
					5.155029296875
				],
				[
					-106.53736787683818,
					6.014260684742624
				],
				[
					-108.25575884650732,
					12.028413660386036
				],
				[
					-109.97407801011025,
					15.465087890625
				],
				[
					-111.69239717371318,
					23.19770364200366
				],
				[
					-112.55162856158086,
					29.211856617647072
				],
				[
					-112.55162856158086,
					35.226045496323536
				],
				[
					-113.41078814338232,
					40.38114659926464
				],
				[
					-113.41078814338232,
					44.677016314338175
				],
				[
					-113.41078814338232,
					48.97288602941171
				],
				[
					-113.41078814338232,
					53.26875574448525
				],
				[
					-114.26994772518378,
					57.56462545955878
				],
				[
					-114.26994772518378,
					62.71958295036768
				],
				[
					-114.26994772518378,
					67.01545266544122
				],
				[
					-114.26994772518378,
					72.17048196231622
				],
				[
					-114.26994772518378,
					77.32551125919122
				],
				[
					-114.26994772518378,
					80.76222139246318
				],
				[
					-114.26994772518378,
					85.05809110753671
				],
				[
					-114.26994772518378,
					87.63564165900732
				],
				[
					-114.26994772518378,
					89.35396082261025
				],
				[
					-114.26994772518378,
					91.07227998621318
				],
				[
					-114.26994772518378,
					92.79059914981622
				],
				[
					-114.26994772518378,
					94.50899011948525
				],
				[
					-113.41078814338232,
					96.22738108915439
				],
				[
					-113.41078814338232,
					97.08646886488964
				],
				[
					-113.41078814338232,
					97.94562844669122
				],
				[
					-113.41078814338232,
					98.80485983455878
				],
				[
					-112.55162856158086,
					100.52325080422793
				],
				[
					-112.55162856158086,
					101.38233857996318
				],
				[
					-112.55162856158086,
					103.10072954963232
				],
				[
					-112.55162856158086,
					103.95988913143378
				],
				[
					-111.69239717371318,
					104.81912051930146
				],
				[
					-111.69239717371318,
					105.67820829503671
				],
				[
					-110.83323759191171,
					105.67820829503671
				],
				[
					-109.11491842830878,
					105.67820829503671
				],
				[
					-106.53736787683818,
					105.67820829503671
				],
				[
					-103.95988913143378,
					105.67820829503671
				],
				[
					-100.52317899816171,
					105.67820829503671
				],
				[
					-96.22730928308818,
					105.67820829503671
				],
				[
					-91.93143956801464,
					105.67820829503671
				],
				[
					-88.49472943474257,
					105.67820829503671
				],
				[
					-84.19893152573525,
					105.67820829503671
				],
				[
					-79.04383042279403,
					105.67820829503671
				],
				[
					-75.60719209558818,
					105.67820829503671
				],
				[
					-72.1704819623161,
					106.53736787683818
				],
				[
					-68.73377182904403,
					106.53736787683818
				],
				[
					-65.29713350183818,
					106.53736787683818
				],
				[
					-62.71958295036757,
					107.39652745863964
				],
				[
					-61.00126378676464,
					107.39652745863964
				],
				[
					-58.42371323529403,
					107.39652745863964
				],
				[
					-56.7053940716911,
					108.25575884650732
				],
				[
					-54.127843520220495,
					108.25575884650732
				],
				[
					-52.40952435661757,
					108.25575884650732
				],
				[
					-50.69113338694842,
					108.25575884650732
				],
				[
					-50.69113338694842,
					108.25575884650732
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 96,
			"versionNonce": 1463916015,
			"isDeleted": false,
			"id": "55mD-F4AlyH46SnKnlVtY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -229.63455466060395,
			"y": -117.78800664800087,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 61.00126378676475,
			"height": 86.77648207720586,
			"seed": 761488332,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.8591595818014639,
					0
				],
				[
					-0.8591595818014639,
					0.8591595818014639
				],
				[
					-1.7183191636029278,
					0.8591595818014639
				],
				[
					-2.5775505514706083,
					0.8591595818014639
				],
				[
					-4.295869715073536,
					1.7183191636029278
				],
				[
					-6.014188878676464,
					1.7183191636029278
				],
				[
					-9.450899011948536,
					2.5775505514706083
				],
				[
					-12.887609145220608,
					2.5775505514706083
				],
				[
					-18.04263844209561,
					2.5775505514706083
				],
				[
					-24.056827320772072,
					2.5775505514706083
				],
				[
					-28.35269703584561,
					2.5775505514706083
				],
				[
					-35.22611730238975,
					0.8591595818014639
				],
				[
					-40.38114659926475,
					0
				],
				[
					-44.67701631433829,
					-0.8591595818014639
				],
				[
					-48.97281422334561,
					-1.7183191636029278
				],
				[
					-52.40952435661768,
					-1.7183191636029278
				],
				[
					-53.268683938419144,
					-2.5775505514706083
				],
				[
					-54.127915326286825,
					-2.5775505514706083
				],
				[
					-54.98707490808829,
					-2.5775505514706083
				],
				[
					-55.84623448988975,
					-2.5775505514706083
				],
				[
					-56.70539407169122,
					-2.5775505514706083
				],
				[
					-57.56455365349268,
					-2.5775505514706083
				],
				[
					-58.423713235294144,
					-2.5775505514706083
				],
				[
					-59.282944623161825,
					-2.5775505514706083
				],
				[
					-59.282944623161825,
					-1.7183191636029278
				],
				[
					-59.282944623161825,
					0
				],
				[
					-60.14210420496329,
					2.5775505514706083
				],
				[
					-60.14210420496329,
					5.155029296875
				],
				[
					-60.14210420496329,
					7.732508042279392
				],
				[
					-60.14210420496329,
					10.31005859375
				],
				[
					-60.14210420496329,
					13.746768727022072
				],
				[
					-60.14210420496329,
					17.183407054227928
				],
				[
					-60.14210420496329,
					19.76102941176464
				],
				[
					-60.14210420496329,
					22.338508157169144
				],
				[
					-60.14210420496329,
					24.915986902573536
				],
				[
					-60.14210420496329,
					27.493537454044144
				],
				[
					-60.14210420496329,
					30.071016199448536
				],
				[
					-60.14210420496329,
					32.648566750919144
				],
				[
					-61.00126378676475,
					34.36688591452207
				],
				[
					-61.00126378676475,
					36.94443646599268
				],
				[
					-61.00126378676475,
					39.52191521139707
				],
				[
					-61.00126378676475,
					42.09946576286768
				],
				[
					-61.00126378676475,
					44.67694450827207
				],
				[
					-61.00126378676475,
					46.39533547794122
				],
				[
					-61.00126378676475,
					48.97281422334561
				],
				[
					-61.00126378676475,
					52.40952435661768
				],
				[
					-61.00126378676475,
					54.98700310202207
				],
				[
					-61.00126378676475,
					57.56455365349268
				],
				[
					-61.00126378676475,
					60.142104204963175
				],
				[
					-61.00126378676475,
					61.86042336856622
				],
				[
					-61.00126378676475,
					63.578742532169144
				],
				[
					-61.00126378676475,
					65.29713350183818
				],
				[
					-61.00126378676475,
					66.15629308363964
				],
				[
					-61.00126378676475,
					67.01552447150732
				],
				[
					-61.00126378676475,
					68.73377182904414
				],
				[
					-61.00126378676475,
					69.59300321691171
				],
				[
					-61.00126378676475,
					70.45216279871318
				],
				[
					-61.00126378676475,
					71.31139418658086
				],
				[
					-61.00126378676475,
					73.02964154411768
				],
				[
					-61.00126378676475,
					73.88880112591914
				],
				[
					-61.00126378676475,
					74.74803251378671
				],
				[
					-61.00126378676475,
					76.46635167738964
				],
				[
					-61.00126378676475,
					77.32551125919122
				],
				[
					-61.00126378676475,
					78.18467084099268
				],
				[
					-61.00126378676475,
					79.04390222886025
				],
				[
					-61.00126378676475,
					81.62138097426464
				],
				[
					-59.282944623161825,
					83.33970013786768
				],
				[
					-58.423713235294144,
					83.33970013786768
				],
				[
					-57.56455365349268,
					84.19893152573525
				],
				[
					-56.70539407169122,
					84.19893152573525
				],
				[
					-55.84623448988975,
					84.19893152573525
				],
				[
					-54.127915326286825,
					84.19893152573525
				],
				[
					-52.40952435661768,
					84.19893152573525
				],
				[
					-49.83204561121329,
					84.19893152573525
				],
				[
					-46.39533547794122,
					84.19893152573525
				],
				[
					-42.958625344669144,
					83.33970013786768
				],
				[
					-39.52191521139707,
					83.33970013786768
				],
				[
					-35.22611730238975,
					83.33970013786768
				],
				[
					-30.930247587316217,
					83.33970013786768
				],
				[
					-26.63437787224268,
					83.33970013786768
				],
				[
					-23.19766773897061,
					83.33970013786768
				],
				[
					-18.901798023897072,
					83.33970013786768
				],
				[
					-15.465087890625,
					83.33970013786768
				],
				[
					-13.746768727022072,
					83.33970013786768
				],
				[
					-11.169218175551464,
					83.33970013786768
				],
				[
					-8.591739430147072,
					83.33970013786768
				],
				[
					-7.732579848345608,
					83.33970013786768
				],
				[
					-6.873420266544144,
					83.33970013786768
				],
				[
					-6.014188878676464,
					83.33970013786768
				],
				[
					-6.014188878676464,
					83.33970013786768
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "freedraw",
			"version": 102,
			"versionNonce": 1740522625,
			"isDeleted": false,
			"id": "dIaZJad-LRNdE8TipME89",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -230.49371424240542,
			"y": 25.693797694829982,
			"strokeColor": "#ffd814",
			"backgroundColor": "transparent",
			"width": 68.73384363511036,
			"height": 122.00252757352939,
			"seed": 784752332,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.8591595818014639,
					0
				],
				[
					-1.7183909696691444,
					0
				],
				[
					-5.155029296875,
					0
				],
				[
					-9.450899011948536,
					0.8591595818014639
				],
				[
					-12.887609145220608,
					0.8591595818014639
				],
				[
					-17.183478860294144,
					0.8591595818014639
				],
				[
					-23.19766773897061,
					0.8591595818014639
				],
				[
					-27.493537454044144,
					0.8591595818014639
				],
				[
					-34.36695772058829,
					0.8591595818014639
				],
				[
					-40.38114659926475,
					0
				],
				[
					-47.25449505974268,
					-0.8591595818014639
				],
				[
					-53.26875574448536,
					-1.7183191636029278
				],
				[
					-56.70539407169122,
					-1.7183191636029278
				],
				[
					-58.42378504136036,
					-1.7183191636029278
				],
				[
					-59.282944623161825,
					-1.7183191636029278
				],
				[
					-60.14210420496329,
					-1.7183191636029278
				],
				[
					-61.86042336856622,
					-1.7183191636029278
				],
				[
					-63.57881433823536,
					-1.7183191636029278
				],
				[
					-65.29713350183829,
					-1.7183191636029278
				],
				[
					-67.8746840533089,
					-1.7183191636029278
				],
				[
					-68.73384363511036,
					-1.7183191636029278
				],
				[
					-68.73384363511036,
					-0.8591595818014639
				],
				[
					-68.73384363511036,
					2.5775505514706083
				],
				[
					-68.73384363511036,
					6.014188878676464
				],
				[
					-68.73384363511036,
					10.31005859375
				],
				[
					-68.73384363511036,
					14.605928308823536
				],
				[
					-68.73384363511036,
					18.04263844209561
				],
				[
					-67.8746840533089,
					22.338508157169144
				],
				[
					-67.01545266544122,
					26.63437787224268
				],
				[
					-66.15629308363975,
					30.930247587316217
				],
				[
					-65.29713350183829,
					35.22611730238975
				],
				[
					-64.43797392003682,
					40.38114659926475
				],
				[
					-64.43797392003682,
					43.81778492647061
				],
				[
					-64.43797392003682,
					48.113654641544144
				],
				[
					-63.57881433823536,
					50.69120519301475
				],
				[
					-63.57881433823536,
					54.127915326286825
				],
				[
					-62.7196547564339,
					56.70539407169122
				],
				[
					-62.7196547564339,
					60.14210420496329
				],
				[
					-61.86042336856622,
					64.43797392003682
				],
				[
					-61.86042336856622,
					68.73384363511036
				],
				[
					-61.86042336856622,
					71.31132238051475
				],
				[
					-61.00126378676475,
					73.88887293198536
				],
				[
					-61.00126378676475,
					76.46635167738975
				],
				[
					-61.00126378676475,
					79.04390222886036
				],
				[
					-61.00126378676475,
					81.62138097426475
				],
				[
					-61.00126378676475,
					83.33977194393378
				],
				[
					-61.00126378676475,
					85.91725068933829
				],
				[
					-61.00126378676475,
					87.63564165900732
				],
				[
					-61.00126378676475,
					90.21312040441182
				],
				[
					-61.00126378676475,
					92.79067095588232
				],
				[
					-61.00126378676475,
					94.50899011948536
				],
				[
					-61.00126378676475,
					97.08654067095586
				],
				[
					-61.00126378676475,
					99.66401941636036
				],
				[
					-61.00126378676475,
					101.38241038602939
				],
				[
					-61.00126378676475,
					103.9598891314339
				],
				[
					-60.14210420496329,
					105.67828010110293
				],
				[
					-60.14210420496329,
					107.39659926470586
				],
				[
					-60.14210420496329,
					108.25575884650732
				],
				[
					-60.14210420496329,
					109.97407801011036
				],
				[
					-59.282944623161825,
					110.83330939797793
				],
				[
					-59.282944623161825,
					112.55162856158086
				],
				[
					-59.282944623161825,
					113.41078814338232
				],
				[
					-59.282944623161825,
					114.2699477251839
				],
				[
					-59.282944623161825,
					115.12917911305146
				],
				[
					-58.42378504136036,
					116.84749827665439
				],
				[
					-58.42378504136036,
					117.70665785845586
				],
				[
					-58.42378504136036,
					118.56581744025732
				],
				[
					-58.42378504136036,
					119.4249770220589
				],
				[
					-57.56455365349268,
					119.4249770220589
				],
				[
					-55.84623448988975,
					119.4249770220589
				],
				[
					-53.26875574448536,
					119.4249770220589
				],
				[
					-49.83204561121329,
					119.4249770220589
				],
				[
					-45.53617589613975,
					119.4249770220589
				],
				[
					-42.958625344669144,
					119.4249770220589
				],
				[
					-39.52198701746329,
					119.4249770220589
				],
				[
					-36.94443646599268,
					119.4249770220589
				],
				[
					-34.36695772058829,
					119.4249770220589
				],
				[
					-31.78940716911768,
					119.4249770220589
				],
				[
					-29.211856617647072,
					119.4249770220589
				],
				[
					-26.63437787224268,
					119.4249770220589
				],
				[
					-24.916058708639753,
					119.4249770220589
				],
				[
					-23.19766773897061,
					119.4249770220589
				],
				[
					-22.338508157169144,
					119.4249770220589
				],
				[
					-21.47934857536768,
					119.4249770220589
				],
				[
					-19.760957605698536,
					119.4249770220589
				],
				[
					-18.04263844209561,
					119.4249770220589
				],
				[
					-16.32431927849268,
					119.4249770220589
				],
				[
					-14.605928308823536,
					119.4249770220589
				],
				[
					-13.746768727022072,
					119.4249770220589
				],
				[
					-12.887609145220608,
					119.4249770220589
				],
				[
					-12.028449563419144,
					119.4249770220589
				],
				[
					-11.16928998161768,
					119.4249770220589
				],
				[
					-10.31005859375,
					119.4249770220589
				],
				[
					-10.31005859375,
					120.28420840992646
				],
				[
					-9.450899011948536,
					120.28420840992646
				],
				[
					-9.450899011948536,
					120.28420840992646
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 145,
			"versionNonce": 764870671,
			"isDeleted": false,
			"id": "mW57GQgu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -282.9034540172223,
			"y": -275.87584700875476,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.07992553710938,
			"height": 40,
			"seed": 1388774644,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "series CLK_OUT\n(backup)",
			"rawText": "series CLK_OUT\n(backup)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "series CLK_OUT\n(backup)",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 299,
			"versionNonce": 1533283425,
			"isDeleted": false,
			"id": "1UJkMTAC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 28.976069764947624,
			"y": 115.12530906891061,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 695.7194213867188,
			"height": 25,
			"seed": 1692522700,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ESPs connected to a shared bus (I2C?) for sidechannel communication",
			"rawText": "ESPs connected to a shared bus (I2C?) for sidechannel communication",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ESPs connected to a shared bus (I2C?) for sidechannel communication",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 109,
			"versionNonce": 100279855,
			"isDeleted": false,
			"id": "LBxZwfDz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 28.11691018314616,
			"y": 157.1471524742413,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 467.2396240234375,
			"height": 25,
			"seed": 1931427276,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Strapping pins so each ESP can tell where it is",
			"rawText": "Strapping pins so each ESP can tell where it is",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Strapping pins so each ESP can tell where it is",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 130,
			"versionNonce": 481269409,
			"isDeleted": false,
			"id": "WzelJzLN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 43.37625809770937,
			"y": -360.9217359908424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 75.8367919921875,
			"height": 12.215597429806746,
			"seed": 702303564,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933397854,
			"link": "https://github.com/espressif/kicad-libraries",
			"locked": false,
			"fontSize": 9.772477943845397,
			"fontFamily": 1,
			"text": "🌐[[kicad libs]]",
			"rawText": "[[https://github.com/espressif/kicad-libraries|kicad libs]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[kicad libs]]",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 1330874447,
			"isDeleted": false,
			"id": "w9kI7con",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -49.20845746391035,
			"y": -288.9037293042511,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 114.03192138671875,
			"height": 20,
			"seed": 1552578636,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "91 mA @ 3.3 V",
			"rawText": "91 mA @ 3.3 V",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "91 mA @ 3.3 V",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 105,
			"versionNonce": 667101217,
			"isDeleted": false,
			"id": "LcLTOY8V",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 26.398770534711275,
			"y": 193.16952724446242,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 563.5396118164062,
			"height": 25,
			"seed": 1981914700,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Shared RESET and GPIO0 signals connected to buttons",
			"rawText": "Shared RESET and GPIO0 signals connected to buttons",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Shared RESET and GPIO0 signals connected to buttons",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 125544047,
			"isDeleted": false,
			"id": "UDNgwO2i",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 28.117161504380533,
			"y": 230.89571635291844,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 304.8797607421875,
			"height": 25,
			"seed": 1106536692,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Series JTAG for the hell of it",
			"rawText": "Series JTAG for the hell of it",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Series JTAG for the hell of it",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 292,
			"versionNonce": 2085321729,
			"isDeleted": false,
			"id": "gDDstPv8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1168.7103746858766,
			"y": -418.2623244353646,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 381.4398193359375,
			"height": 40,
			"seed": 1301541196,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "5.1k pulldowns on CC1/CC2\nCan sense voltage to measure cable orientation",
			"rawText": "5.1k pulldowns on CC1/CC2\nCan sense voltage to measure cable orientation",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5.1k pulldowns on CC1/CC2\nCan sense voltage to measure cable orientation",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 1564147855,
			"isDeleted": false,
			"id": "WAAK4yfb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -753.7298700328437,
			"y": -539.0633900923942,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87.29592895507812,
			"height": 40,
			"seed": 632470604,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "480 Mb/s\nkeep short!",
			"rawText": "480 Mb/s\nkeep short!",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "480 Mb/s\nkeep short!",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "freedraw",
			"version": 66,
			"versionNonce": 1751012321,
			"isDeleted": false,
			"id": "a8ftX52pMYW1QBpk36Q6V",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -713.348723433579,
			"y": -464.3152498695082,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 40.38114659926464,
			"height": 98.80478802849268,
			"seed": 871920116,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.7183909696690307,
					1.718247357536825
				],
				[
					4.295869715073536,
					9.45082720588232
				],
				[
					7.732579848345495,
					18.04256663602939
				],
				[
					10.31005859375,
					28.35262522977939
				],
				[
					13.746768727022072,
					37.80352424172793
				],
				[
					17.18347886029403,
					45.53603228400732
				],
				[
					19.760957605698536,
					53.26861213235293
				],
				[
					21.479348575367567,
					59.28280101102939
				],
				[
					22.33850815716903,
					66.15622127757354
				],
				[
					24.056827320772072,
					71.31125057444854
				],
				[
					24.915986902573536,
					77.32551125919122
				],
				[
					25.775218290441103,
					81.62138097426475
				],
				[
					26.634377872242567,
					83.33962833180146
				],
				[
					26.634377872242567,
					85.05801930147061
				],
				[
					27.49353745404403,
					87.635498046875
				],
				[
					27.49353745404403,
					90.21312040441182
				],
				[
					27.49353745404403,
					91.93136776194854
				],
				[
					27.49353745404403,
					92.79052734375
				],
				[
					27.49353745404403,
					93.64975873161768
				],
				[
					28.35269703584561,
					93.64975873161768
				],
				[
					28.35269703584561,
					96.22723747702207
				],
				[
					28.35269703584561,
					97.08639705882354
				],
				[
					29.211856617647072,
					97.945556640625
				],
				[
					29.211856617647072,
					98.80478802849268
				],
				[
					28.35269703584561,
					98.80478802849268
				],
				[
					24.915986902573536,
					96.22723747702207
				],
				[
					21.479348575367567,
					94.50891831341914
				],
				[
					18.901798023897072,
					91.93136776194854
				],
				[
					17.18347886029403,
					89.35388901654414
				],
				[
					14.605928308823536,
					85.91725068933829
				],
				[
					11.169289981617567,
					83.33962833180146
				],
				[
					8.591739430147072,
					80.76214958639707
				],
				[
					7.732579848345495,
					79.90299000459561
				],
				[
					7.732579848345495,
					80.76214958639707
				],
				[
					8.591739430147072,
					82.48046875
				],
				[
					9.450899011948536,
					85.05801930147061
				],
				[
					11.169289981617567,
					87.635498046875
				],
				[
					13.746768727022072,
					90.21312040441182
				],
				[
					15.465087890625,
					91.07220818014707
				],
				[
					16.324319278492567,
					91.07220818014707
				],
				[
					16.324319278492567,
					91.93136776194854
				],
				[
					18.042638442095495,
					91.93136776194854
				],
				[
					19.760957605698536,
					92.79052734375
				],
				[
					21.479348575367567,
					93.64975873161768
				],
				[
					22.33850815716903,
					94.50891831341914
				],
				[
					23.19766773897061,
					94.50891831341914
				],
				[
					24.056827320772072,
					94.50891831341914
				],
				[
					25.775218290441103,
					94.50891831341914
				],
				[
					27.49353745404403,
					94.50891831341914
				],
				[
					29.211856617647072,
					93.64975873161768
				],
				[
					30.930247587316103,
					91.93136776194854
				],
				[
					32.64856675091903,
					90.21312040441182
				],
				[
					34.36688591452207,
					88.49465762867646
				],
				[
					36.0852768841911,
					86.77633846507354
				],
				[
					37.80359604779403,
					85.05801930147061
				],
				[
					38.66275562959561,
					83.33962833180146
				],
				[
					39.521987017463175,
					83.33962833180146
				],
				[
					39.521987017463175,
					81.62138097426475
				],
				[
					40.38114659926464,
					79.90299000459561
				],
				[
					40.38114659926464,
					79.04375861672793
				],
				[
					40.38114659926464,
					79.04375861672793
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 294,
			"versionNonce": 306845359,
			"isDeleted": false,
			"id": "yKogbfd4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 254.28620812285862,
			"y": -175.84722325356714,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 542.0796508789062,
			"height": 20,
			"seed": 48275660,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "toggle LEDs between frames for some jank structured light scheme?",
			"rawText": "toggle LEDs between frames for some jank structured light scheme?",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "toggle LEDs between frames for some jank structured light scheme?",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 266,
			"versionNonce": 537604033,
			"isDeleted": false,
			"id": "ux70v0so",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -360.8397594054413,
			"y": -615.5121111538115,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 442.17572021484375,
			"height": 60,
			"seed": 846029260,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Hatching instead of solid pours provide better flexibility\nbut shouldn't be used with high frequency\nUse denser hatching if possible",
			"rawText": "Hatching instead of solid pours provide better flexibility\nbut shouldn't be used with high frequency\nUse denser hatching if possible",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Hatching instead of solid pours provide better flexibility\nbut shouldn't be used with high frequency\nUse denser hatching if possible",
			"lineHeight": 1.25,
			"baseline": 54
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 491874511,
			"isDeleted": false,
			"id": "Xk1dzFqD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -144.80502431849274,
			"y": -458.56767397408356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 171.8775634765625,
			"height": 32.05763152828133,
			"seed": 1906346612,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 12.82305261131253,
			"fontFamily": 1,
			"text": "some rando design has 20p\ncnlohr has 10p",
			"rawText": "some rando design has 20p\ncnlohr has 10p",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "some rando design has 20p\ncnlohr has 10p",
			"lineHeight": 1.25,
			"baseline": 27
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1986317909,
			"isDeleted": false,
			"id": "RmcGFCNC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 843.4706531152806,
			"y": -208.24093856560762,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 180.83547973632812,
			"height": 20,
			"seed": 1517948959,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690480964724,
			"link": "https://datasheet.lcsc.com/lcsc/1808311640_AWINIC-Shanghai-Awinic-Tech-AW9106BTQR_C252448.pdf",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "🌐[[neat LED driver]]",
			"rawText": "[[https://datasheet.lcsc.com/lcsc/1808311640_AWINIC-Shanghai-Awinic-Tech-AW9106BTQR_C252448.pdf|neat LED driver]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[neat LED driver]]",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 1193281505,
			"isDeleted": false,
			"id": "ZedtAyBi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 844.7232471094212,
			"y": -176.7522148107248,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.4195098876953,
			"height": 20,
			"seed": 1718740529,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933433179,
			"link": "https://datasheet.lcsc.com/lcsc/2210111600_AWINIC-Shanghai-Awinic-Tech-AW9110CQNR_C2943134.pdf",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "🌐[[10 channel]]",
			"rawText": "[[https://datasheet.lcsc.com/lcsc/2210111600_AWINIC-Shanghai-Awinic-Tech-AW9110CQNR_C2943134.pdf|10 channel]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[10 channel]]",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 448852865,
			"isDeleted": false,
			"id": "8Aes8ko9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260.938573655578,
			"y": 270.2766312942149,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.91989135742188,
			"height": 25,
			"seed": 2144794833,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(fifth ESP)",
			"rawText": "(fifth ESP)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(fifth ESP)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 230,
			"versionNonce": 258800981,
			"isDeleted": false,
			"id": "4PVAnT7v",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 28.639832617784805,
			"y": 281.63614701560425,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1096.17529296875,
			"height": 20,
			"seed": 761214719,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1690399154246,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "PWM + Tacho PC fan header (commodity PC fans run at 12 V and usually require at least 7 V to start - do i need a boost converter?)",
			"rawText": "PWM + Tacho PC fan header (commodity PC fans run at 12 V and usually require at least 7 V to start - do i need a boost converter?)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PWM + Tacho PC fan header (commodity PC fans run at 12 V and usually require at least 7 V to start - do i need a boost converter?)",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 236,
			"versionNonce": 406379361,
			"isDeleted": false,
			"id": "OCMfFMZA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 9.553175376087438,
			"y": 349.0014051927376,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1146.7994384765625,
			"height": 20,
			"seed": 100025247,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Make a few recordings to try out how much of an impact the dead cats make on audio - they're right in the space for mouth tracking cameras",
			"rawText": "Make a few recordings to try out how much of an impact the dead cats make on audio - they're right in the space for mouth tracking cameras",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Make a few recordings to try out how much of an impact the dead cats make on audio - they're right in the space for mouth tracking cameras",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 118,
			"versionNonce": 1222493999,
			"isDeleted": false,
			"id": "FI3PvyOE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -898.9859763630827,
			"y": -298.62644956820264,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 202.86386108398438,
			"height": 40,
			"seed": 753410545,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689933337939,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Or USB A for frunkability\n(somehow do both?)",
			"rawText": "Or USB A for frunkability\n(somehow do both?)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Or USB A for frunkability\n(somehow do both?)",
			"lineHeight": 1.25,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 1378927265,
			"isDeleted": false,
			"id": "OO7LF31v",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 195.42362796476596,
			"y": -348.1957421416904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 178.08416748046875,
			"height": 13.748963066459188,
			"seed": 1647090543,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1689934742621,
			"link": "https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/XIAO_ESP32S3_ExpBoard_v1.0_SCH.pdf",
			"locked": false,
			"fontSize": 10.99917045316735,
			"fontFamily": 1,
			"text": "🌐[[expansion board schematic]]",
			"rawText": "[[https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/XIAO_ESP32S3_ExpBoard_v1.0_SCH.pdf|expansion board schematic]]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "🌐[[expansion board schematic]]",
			"lineHeight": 1.25,
			"baseline": 10
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "cross-hatch",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": -369.32267251252426,
		"scrollY": 522.5835286998331,
		"zoom": {
			"value": 1.2188714462194405
		},
		"currentItemRoundness": "sharp",
		"gridSize": null,
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%