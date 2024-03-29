# Dotfiles
Simple pack of dotfiles for my Linux desktop. Mostly made to work with i3 and Openbox, and themes such as [Fluent](https://github.com/vinceliuice/Fluent-gtk-theme) and Arc-Dark.
Here you will find configs for i3 (and i3bar and i3status), openbox, tint2, conky, rofi, dunst and much more.

# Structure
This repo contains configs of various stages of completion: the main one is for my Arch desktop with i3wm, for the Fluent theme, in red and grey variations. (also containing former color options for the Arc theme, should be fairly easy to set up).  
On this setup I recommend using [oh-my-bash](https://ohmybash.nntoan.com/) or [powerlevel10k](https://github.com/romkatv/powerlevel10k) in combination with [zsh4humans](https://github.com/romkatv/zsh4humans) as the shell.

I also have configs for Debian to replicate the Openbox environment of Crunchbang, made to work with [Bunsen-Faenza](https://github.com/BunsenLabs/bunsen-faenza-icon-theme) icons and the [Bunsen-He](https://github.com/BunsenLabs/bunsen-themes) theme.  
On Openbox I use the [Openbox Applications Menu](https://github.com/Lestibournes/Openbox-Applicatons-Menu) for my pipe menu because it's easy to install and configure.

As a little gimmick I use the [i3spotifystatus](https://github.com/rpieja/i3spotifystatus) script and slightly modified it.

# Fonts  
Here are all the main fonts used in these configs:  
- In my Fluent rice I use Cantarell for the UI,  MesloLGS NF for the terminal and ZSH and FontAwesome 6 for icons in i3bar (optional, uncomment lines in i3 config and i3status to enable).
- You will need to install ipa-fonts from the AUR if you want unimatrix to work.
- For my Debian rice I use FreeSans for the UI, Lato Black for the titlebars, and Noto Mono for the terminal and monospace font (all fonts available in stock Debian).

# Credits
- Conky configs are modified from [BunsenLabs](https://www.bunsenlabs.org/)
- Picom config based off [this one](https://github.com/Sup3r-Us3r/MyDotfiles/blob/master/.config/picom/picom.conf)
- Rofi theme is a heavily edited version of [Darker than Black v2](https://github.com/avasz/rofi-themes-avasz)

# Screenshots
![Debian #!](https://media.discordapp.net/attachments/834207032437243974/961330939240280165/Screenshot_2022-04-06.png)
![Fluent-red](https://media.discordapp.net/attachments/543141038534033408/938538200614445056/unknown.png)
![Fluent-grey](https://i.redd.it/67qth3n2vb281.png)
![Arc-Dark openbox](https://cdn.discordapp.com/attachments/769950055405715456/906270043581612052/unknown.png)
![Arc-Dark i3](https://media.discordapp.net/attachments/769950055405715456/899344138141581312/VirtualBox_EndeavourOS_17_10_2021_20_09_55.png)
