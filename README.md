# Decay Polybar

Decay Ported for polybar!

![decayce](./.assets/decayce.png)

## Installation

Just execute the next commands

```sh
git clone --depth=1 https://github.com/decaycs/polybar decay-polybar
cd decay-polybar
```

Then move the files into your polybar's configuration folder.

```sh
# remember to change <theme> to one of: decayce, dark-decay, decay or light-decay
cp -r ./themes/<theme>.ini ~/.config/polybar
```

## Usage

Then in your configuration, to get the colors in your scope, add this in the top of the
main config file.

```dosini
include-file = <theme>.ini
```

> remember to change `<theme>` to one of: `decayce`, `dark-decay`, `decay` or `light-decay`.

## Gallery

### Decay

![decay](./.assets/decay.png)

### Dark Decay

![dark-decay](./.assets/dark-decay.png)

### Decayce

![decayce](./.assets/decayce.png)

### Light Decay

![light-decay](./.assets/light-decay.png)

## Thanks to

- [Spaxly](https://github.com/Spaxly)

## Enjoy

That was all! Enjoy
