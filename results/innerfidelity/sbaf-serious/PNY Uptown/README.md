# PNY Uptown
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -11.5; 23 -11.4; 25 -11.3; 28 -11.2; 31 -11.0; 34 -10.8; 37 -10.7; 41 -10.5; 45 -10.3; 49 -10.1; 54 -9.9; 60 -9.8; 66 -9.6; 72 -9.4; 79 -9.3; 87 -9.2; 96 -9.1; 106 -8.7; 116 -8.4; 128 -8.1; 141 -7.8; 155 -7.4; 170 -7.0; 187 -6.5; 206 -6.0; 227 -5.4; 249 -5.0; 274 -4.4; 302 -3.8; 332 -3.3; 365 -2.7; 402 -2.2; 442 -1.5; 486 -1.2; 535 -0.7; 588 -0.1; 647 0.2; 712 0.2; 783 1.0; 861 0.8; 947 0.3; 1042 -0.3; 1146 -0.7; 1261 -1.4; 1387 -2.3; 1526 -3.4; 1678 -4.8; 1846 -6.3; 2031 -7.2; 2234 -7.4; 2457 -5.3; 2703 -2.3; 2973 1.8; 3270 4.6; 3597 6.0; 3957 5.7; 4353 3.4; 4788 1.4; 5267 -0.1; 5793 -5.2; 6373 -8.0; 7010 -2.4; 7711 0.2; 8482 -0.0; 9330 -1.2; 10263 -0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`PNY Uptown GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `PNY Uptown ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.5dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 21 Hz   | 0.19 | -11.2 dB |
| Peaking | 158 Hz  | 0.78 | -3.6 dB  |
| Peaking | 2164 Hz | 2    | -9.5 dB  |
| Peaking | 3609 Hz | 1.99 | 8.4 dB   |
| Peaking | 6212 Hz | 5.74 | -10.2 dB |
| Peaking | 308 Hz  | 2.3  | -0.7 dB  |
| Peaking | 799 Hz  | 1.72 | 1.8 dB   |
| Peaking | 1600 Hz | 3.75 | -1.1 dB  |
| Peaking | 7694 Hz | 8.24 | 1.2 dB   |
| Peaking | 9376 Hz | 9.83 | -1.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/PNY%20Uptown/PNY%20Uptown.png)