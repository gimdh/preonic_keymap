
# QMK Configurator Preset for OLKB Preonic

## Optimized for programmers (Especially for non-Vim users)

### Layer 0 (Default layer)
![image](https://github.com/gimdh/preonic_keymap/blob/master/screenshots/layer0.png?raw=true)

### Layer 1 (Thumb raise/lower)
![image](https://github.com/gimdh/preonic_keymap/blob/master/screenshots/layer1.png?raw=true)

If you have 2x1 spacebar, then you may want to create a new layer and assign each to `raise` and `lower` so that spacebar of each layer functions as either `enter` or `delete`.

### Layer 2 (Fn)
![image](https://github.com/gimdh/preonic_keymap/blob/master/screenshots/layer2.png?raw=true)

I guess current QMK implementation of `Swap LCtrl/Caps` is somewhat buggy. Once you turn on the toggle, it would stuck in 'on' or 'swapped' position. You can avoid this by simply creating duplicate layers with `Ctrl` and `Caps` swapped and replace `Swap LCtrl/Caps` to `TG(Layer toggle)`.
