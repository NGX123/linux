## Panel
* Right click -> Configure panel
	* Panel
		* Size`(30px)`
		* Icon size`(22px)`
		* Position`(Top of the desktop)`
	* Widgets
		* Choose Desktop Switcher -> `(- Icon)`Remove
		* Choose Task Manager -> Settings button -> Button style`(Only icon)`, Maximum button width`(30px)`

## Preferences
* Kvantum
	* `(Terminal)`sudo apt install qt5-style-kvantum
	* `(Optional)`[Download and unpack](https://store.kde.org/p/1373831) -> Files -> *.zip -> Download

* LXQT Configuration Center
	* Desktop
		* Advanced -> Visible shortcuts -> All`(OFF)`
	* Apperance
		* Widget Style
			* (Install kvantum before) Qt Style`(kvantum-dark)`
			* GTK 2 Theme`(Adwaita-dark)`
			* GTK 3 Theme`(Adwaita-dark)`
		* Icon Theme
			* Choose`(Papirus-Dark)`

## Extra
* Remove libre office
	* 	```
		sudo apt-get remove --purge libreoffice*
		```
* Remove other unneeded apps
	* 	```
		sudo apt remove k3b trojita quassel skanlite 2048-qt noblenote
		```