# Sennheiser PXC 550 Wired Power On
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 0.1; 25 -0.3; 28 -0.8; 31 -1.1; 34 -1.3; 37 -1.5; 41 -1.7; 45 -1.9; 49 -2.0; 54 -2.1; 60 -2.2; 66 -2.2; 72 -2.2; 79 -2.0; 87 -2.1; 96 -2.1; 106 -2.5; 116 -3.0; 128 -3.5; 141 -3.6; 155 -3.8; 170 -1.8; 187 -2.5; 206 -1.6; 227 -0.2; 249 0.9; 274 1.9; 302 2.5; 332 2.8; 365 2.8; 402 2.8; 442 2.8; 486 2.6; 535 2.5; 588 2.6; 647 2.4; 712 1.8; 783 1.6; 861 0.8; 947 0.3; 1042 -0.1; 1146 0.1; 1261 0.2; 1387 -1.1; 1526 -2.0; 1678 -2.5; 1846 -1.6; 2031 -1.7; 2234 -1.0; 2457 0.2; 2703 1.4; 2973 2.3; 3270 3.2; 3597 2.8; 3957 3.5; 4353 5.8; 4788 -2.2; 5267 -0.7; 5793 4.7; 6373 5.2; 7010 2.5; 7711 0.3; 8482 -2.7; 9330 -5.4; 10263 -1.6; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 0.0; 18182 0.0; 20000 -1.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser PXC 550 Wired Power On GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser PXC 550 Wired Power On ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 489 Hz  |  0.46 | 10.4 dB |
| Peaking | 498 Hz  |  0.14 | -7.3 dB |
| Peaking | 3448 Hz |  1.59 | 6.4 dB  |
| Peaking | 6262 Hz |  5.3  | 6.7 dB  |
| Peaking | 9280 Hz |  5.67 | -5.8 dB |
| Peaking | 11 Hz   |  1.66 | 2.0 dB  |
| Peaking | 149 Hz  |  4.28 | -1.7 dB |
| Peaking | 289 Hz  |  4.48 | 1.4 dB  |
| Peaking | 4316 Hz | 11.2  | 5.0 dB  |
| Peaking | 4925 Hz |  9.29 | -5.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20PXC%20550%20Wired%20Power%20On/Sennheiser%20PXC%20550%20Wired%20Power%20On.png)