# SoundPeats QY8
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -1.8dB
GraphicEQ: 21 -6.2; 23 -6.1; 25 -6.0; 28 -5.8; 31 -5.6; 34 -5.3; 37 -5.1; 41 -4.8; 45 -4.4; 49 -4.2; 54 -4.0; 60 -4.0; 66 -3.9; 72 -3.9; 79 -3.9; 87 -3.9; 96 -4.0; 106 -4.1; 116 -4.3; 128 -4.8; 141 -5.6; 155 -5.9; 170 -5.7; 187 -5.2; 206 -4.7; 227 -4.3; 249 -3.8; 274 -3.3; 302 -2.8; 332 -2.3; 365 -1.8; 402 -1.3; 442 -0.8; 486 -0.3; 535 0.3; 588 0.9; 647 1.5; 712 1.7; 783 1.7; 861 1.3; 947 0.5; 1042 -0.4; 1146 -1.4; 1261 -2.0; 1387 -2.4; 1526 -2.9; 1678 -3.7; 1846 -5.2; 2031 -7.0; 2234 -7.2; 2457 -6.9; 2703 -6.2; 2973 -5.3; 3270 -5.1; 3597 -6.0; 3957 -8.0; 4353 -10.9; 4788 -10.6; 5267 -6.4; 5793 -2.8; 6373 -1.9; 7010 -3.0; 7711 -5.8; 8482 -5.2; 9330 -3.5; 10263 -4.5; 11289 -4.8; 12418 -2.5; 13660 -1.3; 15026 -1.1; 16529 -0.3; 18182 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`SoundPeats QY8 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-18**.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `SoundPeats QY8 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-1.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-0.0dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 13 Hz   | 0.2  | -6.3 dB  |
| Peaking | 170 Hz  | 1.12 | -5.1 dB  |
| Peaking | 2253 Hz | 1.8  | -7.0 dB  |
| Peaking | 4472 Hz | 3.18 | -10.4 dB |
| Peaking | 9805 Hz | 1.18 | -4.5 dB  |
| Peaking | 330 Hz  | 1.89 | -1.0 dB  |
| Peaking | 768 Hz  | 1.41 | 3.0 dB   |
| Peaking | 1206 Hz | 1.55 | -1.4 dB  |
| Peaking | 6261 Hz | 5.89 | 2.2 dB   |
| Peaking | 7812 Hz | 8.34 | -2.6 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/SoundPeats%20QY8/SoundPeats%20QY8.png)