# Grado SR125i
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 5.8; 34 5.1; 37 4.2; 41 3.3; 45 2.4; 49 1.6; 54 0.9; 60 0.1; 66 -0.5; 72 -1.0; 79 -1.5; 87 -1.9; 96 -2.3; 106 -2.3; 116 -2.3; 128 -2.5; 141 -2.4; 155 -2.3; 170 -2.1; 187 -1.9; 206 -1.6; 227 -1.2; 249 -1.0; 274 -0.6; 302 -0.1; 332 -0.7; 365 -0.7; 402 -0.7; 442 -0.4; 486 -0.3; 535 -0.2; 588 0.3; 647 0.3; 712 0.2; 783 0.4; 861 0.2; 947 0.1; 1042 -0.0; 1146 -0.1; 1261 -0.6; 1387 -1.5; 1526 -2.9; 1678 -3.6; 1846 -6.0; 2031 -10.1; 2234 -8.8; 2457 -5.9; 2703 -3.9; 2973 -1.9; 3270 -0.3; 3597 -1.9; 3957 -1.6; 4353 0.2; 4788 -0.1; 5267 -0.9; 5793 1.1; 6373 1.4; 7010 -2.2; 7711 -3.6; 8482 -4.2; 9330 -3.5; 10263 -0.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado SR125i GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR125i ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.5dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 26 Hz    | 0.85 | 6.7 dB   |
| Peaking | 109 Hz   | 0.74 | -3.1 dB  |
| Peaking | 2109 Hz  | 3.09 | -10.5 dB |
| Peaking | 8463 Hz  | 3.81 | -4.9 dB  |
| Peaking | 22050 Hz | 2.1  | -2.7 dB  |
| Peaking | 893 Hz   | 0.93 | 1.9 dB   |
| Peaking | 966 Hz   | 0.58 | -1.2 dB  |
| Peaking | 6183 Hz  | 7.41 | 3.1 dB   |
| Peaking | 7259 Hz  | 7.75 | -1.9 dB  |
| Peaking | 10753 Hz | 6.64 | 0.9 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Grado%20SR125i/Grado%20SR125i.png)