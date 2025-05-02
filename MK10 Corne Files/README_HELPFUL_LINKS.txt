------------Keyboard Case, PCB, Plates--------------

	https://github.com/foostan/crkbd/releases/tag/corne-cherry-v3.0.1

------------Build guide & Material List------------

	https://github.com/foostan/crkbd/blob/main/docs/corne-cherry/v3/buildguide_en.md

------------Firmware an Software-------------------

	Firmware Compiler: https://msys.qmk.fm/
	Firmware Files: https://www.caniusevia.com/docs/download_firmware
	Via: https://github.com/the-via
	Enabling Via Tutorial: https://www.caniusevia.com/docs/configuring_qmk
	QMK (Firmware building) Tutorial: https://docs.qmk.fm/newbs
	QMK Tutorial (Video): https://www.youtube.com/watch?v=7d5yzBOup9U&t=2s&ab_channel=JoeScotto

------------Helpful commands for QMK MSYS-----------

	qmk compile -e CONVERT_TO=promicro_rp2040 -kb keyboardhere -km keymaphere
	(for rp2040 clones on AliExpress that need uf2 File)