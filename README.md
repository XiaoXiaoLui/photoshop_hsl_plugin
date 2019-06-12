# photoshop_hsl_plugin
html extension for showing hsl color in photoshop

## installation
put the whole directory in cep extension folder, for me, it's
C:/Users/[me]/AppData/Roaming/Adobe/CEP/extensions

## to avoid signature problem
regedit > HKEY_CURRENT_USER/Software/Adobe/CSXS.8, then add a new entry PlayerDebugMode of type "string" with the value of "1".


## known issues
1. Photoshop may slow down after running this extension for a long time, you can just close this extension and reopen it to solve this.
2. The samplers color may be different from that of Info panel depending on the type of layers.
