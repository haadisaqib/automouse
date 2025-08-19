# automouse

A simple tool to keep your system active by automatically moving the mouse cursor. (🖕🏽teams)

## Installation

`automouse` is available on the Arch User Repository (AUR). The easiest way to install it is with an AUR helper like `yay`.

If you don't have `yay`, you can install it first:

```bash
git clone [https://aur.archlinux.org/yay.git](https://aur.archlinux.org/yay.git)
cd yay
makepkg -si
```

Once yay is installed, run the following command to install automouse:
```bash
yay -S automouse
```

Usage
To keep your status active with the default 30-second interval:
```bash
automouse
```

To set a custom interval (in seconds):
```bash
automouse 5
```

