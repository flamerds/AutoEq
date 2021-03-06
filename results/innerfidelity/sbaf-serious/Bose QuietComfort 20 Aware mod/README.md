# Bose QuietComfort 20 Aware mod
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 2.4; 25 1.3; 28 0.1; 31 -0.4; 34 -0.6; 37 -0.5; 41 -0.3; 45 -0.1; 49 0.1; 54 0.2; 60 0.2; 66 -0.1; 72 -0.5; 79 -1.0; 87 -1.5; 96 -2.1; 106 -2.4; 116 -2.4; 128 -2.5; 141 -2.4; 155 -2.4; 170 -2.4; 187 -2.4; 206 -2.4; 227 -2.3; 249 -2.2; 274 -2.0; 302 -1.8; 332 -1.7; 365 -1.6; 402 -1.7; 442 -1.6; 486 -1.7; 535 -1.4; 588 -0.8; 647 -0.7; 712 -0.9; 783 -0.1; 861 0.3; 947 0.3; 1042 -0.3; 1146 -1.2; 1261 -2.3; 1387 -3.9; 1526 -5.5; 1678 -6.2; 1846 -5.1; 2031 -3.5; 2234 -2.6; 2457 -1.5; 2703 -0.9; 2973 0.9; 3270 2.4; 3597 2.0; 3957 -0.2; 4353 -1.9; 4788 1.5; 5267 5.9; 5793 6.0; 6373 5.5; 7010 1.4; 7711 -3.7; 8482 -1.9; 9330 -0.8; 10263 -0.3; 11289 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Bose QuietComfort 20 Aware mod GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Bose QuietComfort 20 Aware mod ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 181 Hz  |  0.61 | -2.6 dB |
| Peaking | 1691 Hz |  2.36 | -6.3 dB |
| Peaking | 3304 Hz |  7.34 | 3.0 dB  |
| Peaking | 5986 Hz |  3.23 | 7.7 dB  |
| Peaking | 7786 Hz |  4.63 | -5.5 dB |
| Peaking | 19 Hz   |  2.85 | 4.4 dB  |
| Peaking | 477 Hz  |  3.44 | -0.7 dB |
| Peaking | 923 Hz  |  4.18 | 1.5 dB  |
| Peaking | 4343 Hz |  7.77 | -3.6 dB |
| Peaking | 5150 Hz | 10.43 | 2.8 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Bose%20QuietComfort%2020%20Aware%20mod/Bose%20QuietComfort%2020%20Aware%20mod.png)