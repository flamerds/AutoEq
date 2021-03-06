# Jabra Elite Sport
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.7dB
GraphicEQ: 21 -3.7; 23 -3.8; 25 -3.8; 28 -3.8; 31 -3.8; 34 -3.8; 37 -3.9; 41 -4.0; 45 -4.0; 49 -4.0; 54 -4.2; 60 -4.6; 66 -5.0; 72 -5.3; 79 -5.6; 87 -6.1; 96 -6.4; 106 -6.9; 116 -7.3; 128 -7.7; 141 -8.0; 155 -8.0; 170 -8.0; 187 -7.7; 206 -7.4; 227 -7.0; 249 -6.3; 274 -5.3; 302 -4.1; 332 -3.2; 365 -2.6; 402 -2.2; 442 -2.0; 486 -1.9; 535 -1.6; 588 -1.1; 647 -0.5; 712 -0.0; 783 0.1; 861 0.2; 947 0.2; 1042 -0.1; 1146 -0.2; 1261 0.3; 1387 0.8; 1526 0.9; 1678 0.3; 1846 -0.6; 2031 -1.3; 2234 -1.0; 2457 -0.3; 2703 0.4; 2973 1.1; 3270 1.6; 3597 1.9; 3957 2.2; 4353 2.2; 4788 2.9; 5267 3.5; 5793 3.5; 6373 2.0; 7010 -0.5; 7711 -3.3; 8482 -3.4; 9330 -3.5; 10263 -5.6; 11289 -6.8; 12418 -4.9; 13660 -1.9; 15026 -1.5; 16529 -3.3; 18182 -1.1; 20000 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Jabra Elite Sport GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-36**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Jabra Elite Sport ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.8dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 25 Hz    | 0.2  | -3.5 dB |
| Peaking | 125 Hz   | 0.92 | -4.1 dB |
| Peaking | 212 Hz   | 1.12 | -4.5 dB |
| Peaking | 5445 Hz  | 1.43 | 5.7 dB  |
| Peaking | 10267 Hz | 0.9  | -6.5 dB |
| Peaking | 1612 Hz  | 1.9  | 1.7 dB  |
| Peaking | 2015 Hz  | 2.47 | -2.5 dB |
| Peaking | 3227 Hz  | 3.59 | 0.9 dB  |
| Peaking | 14188 Hz | 5.4  | 2.2 dB  |
| Peaking | 16867 Hz | 4.16 | -2.4 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Jabra%20Elite%20Sport/Jabra%20Elite%20Sport.png)