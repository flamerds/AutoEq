# Grado SR325e
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 5.4; 45 4.4; 49 3.6; 54 2.9; 60 2.0; 66 1.2; 72 0.6; 79 0.1; 87 -0.4; 96 -0.7; 106 -0.8; 116 -0.9; 128 -1.0; 141 -1.0; 155 -1.0; 170 -0.8; 187 -0.7; 206 -0.6; 227 -0.3; 249 -0.1; 274 -0.2; 302 -0.1; 332 0.2; 365 0.5; 402 0.7; 442 0.1; 486 0.2; 535 0.3; 588 0.7; 647 0.8; 712 0.5; 783 0.8; 861 0.5; 947 0.3; 1042 0.1; 1146 -0.2; 1261 -0.6; 1387 -1.6; 1526 -2.7; 1678 -3.4; 1846 -7.7; 2031 -8.6; 2234 -6.7; 2457 -4.0; 2703 -1.4; 2973 1.3; 3270 2.9; 3597 1.1; 3957 -0.7; 4353 0.3; 4788 2.2; 5267 4.8; 5793 2.7; 6373 1.5; 7010 1.1; 7711 -1.2; 8482 -5.6; 9330 -8.6; 10263 -5.9; 11289 -0.2; 12418 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado SR325e GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR325e ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 30 Hz   | 1.2  | 7.1 dB   |
| Peaking | 2014 Hz | 2.46 | -11.1 dB |
| Peaking | 4109 Hz | 0.28 | 2.5 dB   |
| Peaking | 5186 Hz | 7.72 | 3.4 dB   |
| Peaking | 9328 Hz | 3.35 | -11.2 dB |
| Peaking | 48 Hz   | 2.19 | 1.5 dB   |
| Peaking | 115 Hz  | 1.04 | -1.5 dB  |
| Peaking | 3325 Hz | 4.62 | 5.1 dB   |
| Peaking | 3731 Hz | 2.49 | -3.7 dB  |
| Peaking | 6178 Hz | 3.03 | 1.1 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Grado%20SR325e/Grado%20SR325e.png)