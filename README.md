# photoshop_hsl_plugin
html extension for showing hcy or hsl color in photoshop
hcy means hue, chroma and luminance, which is commonly used in Photoshop, such as the Color and Luminace blending mode.
y = 0.30 * r + 0.59 * g + 0.11 * b;

## installation
put the whole directory in cep extension folder, for me, it's
C:/Users/[me]/AppData/Roaming/Adobe/CEP/extensions

## to avoid signature problem
regedit > HKEY_CURRENT_USER/Software/Adobe/CSXS.8, then add a new entry PlayerDebugMode of type "string" with the value of "1".
n in CSXS.n depends on your Photoshop version.



## known issues
1. Photoshop sometimes may slow down after running this extension for a long time, you can just close this extension and reopen it to solve this.
   It seems to have been solved though.
2. The samplers color is different from that of Info panel if selecting an ajustment layer.
   Hope anyone could help me solve this.


