## Unix Time Converter for QGIS
A very rudimentary QT plugin for QGIs which can read time-second formats (Unix Timestamp, Unix Epoch, GPS Time) and appends an equivalent human-readable datetime field following ISO 8601 convention [YYYY-MM-DDTHH:MM:SSZ].   
This is useful for visualizing time-series data or integrating timestamps into time-aware layers supported by most softwares.

### Installation
1. Download or clone this repository
2. Copy the plugin folder (```unix2qgisdatetime/```) to your QGIs plugins directory:
   - Linux: ```~/.local/share/QGIS/QGIS3/profiles/default/python/plugins/```
   - Windows: ```%APPDATA%\QGIS\QGIS3\profiles\default\python\plugins\
3. Open QGIS and navigate to Plugins --> Manage and Install Plugins
4. Enable the Unix Time Converter plugin from the list



Developed with the help of [Plugin Builder](https://plugins.qgis.org/plugins/pluginbuilder/)
