# Audio-Technica ATH-M20x
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 5.8; 25 5.4; 28 4.3; 31 3.3; 34 2.4; 37 1.7; 41 0.9; 45 0.2; 49 -0.4; 54 -1.2; 60 -1.9; 66 -2.4; 72 -2.6; 79 -2.6; 87 -2.5; 96 -2.5; 106 -2.7; 116 -2.8; 128 -2.8; 141 -2.3; 155 -1.5; 170 -0.4; 187 0.8; 206 2.3; 227 3.5; 249 3.8; 274 2.7; 302 1.4; 332 0.7; 365 0.1; 402 -0.4; 442 -0.8; 486 -1.0; 535 -1.1; 588 -1.0; 647 -0.9; 712 -0.6; 783 -0.3; 861 -0.1; 947 -0.0; 1042 0.2; 1146 0.0; 1261 -0.5; 1387 -1.1; 1526 -1.8; 1678 -2.4; 1846 -3.3; 2031 -3.9; 2234 -3.3; 2457 -1.9; 2703 -0.7; 2973 -0.3; 3270 0.5; 3597 3.3; 3957 5.0; 4353 3.5; 4788 4.7; 5267 6.0; 5793 6.0; 6373 5.2; 7010 0.5; 7711 -2.5; 8482 -2.5; 9330 -0.2; 10263 0.0; 11289 -0.2; 12418 -1.6; 13660 -0.9; 15026 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audio-Technica ATH-M20x GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio-Technica ATH-M20x ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 0.8  | 7.1 dB  |
| Peaking | 114 Hz  | 0.33 | -4.1 dB |
| Peaking | 235 Hz  | 1.71 | 7.1 dB  |
| Peaking | 2017 Hz | 2.56 | -4.3 dB |
| Peaking | 5037 Hz | 2.1  | 6.4 dB  |
| Peaking | 3800 Hz | 7.89 | 4.6 dB  |
| Peaking | 5615 Hz | 4.37 | 2.3 dB  |
| Peaking | 5742 Hz | 1.18 | -2.9 dB |
| Peaking | 6297 Hz | 5.19 | 4.6 dB  |
| Peaking | 7922 Hz | 4.36 | -3.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Audio-Technica%20ATH-M20x/Audio-Technica%20ATH-M20x.png)