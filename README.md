QGEP-customizer allows customization of main [QGEP](https://github.com/QGEP) project.
It handles the following changes in the project:
- coordinate reference system
- translation (fields, forms, layers, legend, etc.)
- custom symbology
- additional background layers

Requirements :

 - QGIS 2.18.X
 - qgis 2 compat extension : [link](https://plugins.qgis.org/plugins/qgis2compat/)

Use `./customizer.sh config.yaml` to customize the QGEP project.

See the template [config_yaml.template](https://github.com/qwat/QGEP-customizer/blob/master/config_template.yaml) for an example.

Custom symbology file can be saved from the QGIS project menu.
