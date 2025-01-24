# Backup of K1 Max setup

## Device setup
NOTE: this is the original way to setup the printer. Current setup uses [simpleaf](https://github-wiki-see.page/m/pellcorp/creality/wiki/Simple-AF)

[From wayback machine](https://web.archive.org/web/20240912171239/https://docs.cartographer3d.com/cartographer-probe/installation-and-setup)

[original url](https://docs.cartographer3d.com/cartographer-probe/installation-and-setup)

### what I did:
1. Root access
2. Guilouz script
	- Moonraker & Nginx
	- Fluidd
	- Entware
	- Klipper Gcode Shell Command
	- Klipper Adaptive Meshing and Purging
	- Buzzer Support
	- Guppy Screen
	- Git backup
3. Update klipper - https://github.com/K1-Klipper/installer_script_k1_and_max
	- typo: extra should be extras in installer.sh
		- ``wget --no-check-certificate -P /usr/data/klipper/klippy/extra/ https://raw.githubusercontent.com/Guilouz/Creality-Helper-Script/main/files/klipper-virtual-pins/virtual_pins.py``
4. cartographer-klipper script
	- ``git clone https://github.com/K1-Klipper/cartographer-klipper.git``
	- ``cd cartographer-klipper && sh ./k1_installer.sh``
