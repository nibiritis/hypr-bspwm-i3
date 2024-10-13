## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/nibiritis/hypr-bspwm-i3.git ~/HBi
```
### Step 2: BSPWM Script

```bash
curl https://raw.githubusercontent.com/gh0stzk/dotfiles/master/RiceInstaller -o $HOME/RiceInstaller

# Maybe you want a short url??

curl -L https://is.gd/gh0stzk_dotfiles -o $HOME/RiceInstaller
```

```bash
chmod +x RiceInstaller
```

```bash
./RiceInstaller
```

### Step 3: Hyprland - Hyprdots (Prasanthrangan HyDE)

```bash
git clone --depth 1 https://github.com/prasanthrangan/hyprdots ~/HyDE
cd ~/HyDE/Scripts
./install.sh
```

### Optional Step: Install i3 if you want
```bash
sudo pacman -S i3
```
or,

```bash
yay -S i3
```

### Step 4: Managing the Dots

```bash
cd ~/HBi
cp -r * ~/
```


this should work

## Keybinds for BSPWM
### Press F1 to show

## Keybinds for Hyprland
### Press Super + / to show


## To install new themes in Hyprland
```bash
Hyde thene import
```






## Credits and Acknowledgments

Special thanks to the following individuals for their amazing contributions and inspiration:

- [gh0stzk](https://github.com/gh0stzk) - For their dotfiles and guidance in customizing Linux environments.
- [prasanthrangan](https://github.com/prasanthrangan) - For their Hyprland configurations and inspiring ricing setups.

Their work has been incredibly helpful in creating this setup!
