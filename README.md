<p align="center">
  <img width="30%" src="https://github.com/NatryN/MinimalSur-Xfce/blob/main/src/img/image.png" />
</p>

<p align="center">
  <b> 🐭 XFCE4 Dotfiles by Natry </b>
</p>

### Details of my rice

<img src="https://github.com/NatryN/MinimalSur-Xfce/blob/main/src/img/src-1.png?raw=true" alt="img" align="right" width="400px">

This is my personal collection of configuration files.

Here are some details about my setup:

   - **WM:**                   [Xfce](https://wiki.archlinux.org/title/Xfce)
   - **OS:**                   [Arch Linux](https://archlinux.org)
   - **Terminal:**             [kitty](https://github.com/kovidgoyal/kitty)
   - **Shell:**                [zsh](https://wiki.archlinux.org/index.php/Zsh)
   - **Compositor:**           [picom](https://github.com/ibhagwan/picom)
   - **Editor:**               [neovim](https://github.com/neovim/neovim)
   - **Browser:**              [firefox](https://www.mozilla.org/en-US/firefox)
   - **File Manager:**         [thunar](https://github.com/xfce-mirror/thunar)
   - **Application Launcher:** [rofi](https://github.com/davatorium/rofi)

### Installation (Manual)

   > After cloning the repository, install the necessary dependencies to replicate by setup.

   <details open>
   <summary><strong>Arch Linux (and Arch-based distributions)</strong></summary>

   > Assuming your **AUR Helper** is [yay](https://github.com/Jguer/yay).

   ```sh
    $ yay -S bspwm sxhkd rofi kitty picom-ibhagwan-git calcurse todotxt \
    feh jq dunst betterlockscreen brightnessctl playerctl maim \
    xclip imagemagick vala-panel-appmenu-common-git vala-panel-appmenu-xfce-git vala-panel-appmenu-valapanel-git \
    vala-panel-appmenu-registrar-git libdbusmenu-glib libdbusmenu-gtk3 libdbusmenu-gtk2 appmenu-qt4 \
    xfce4-docklike-plugin
     
   ```
  </details>
  
   <br>

   > You will need to install a few fonts.(I can't upload all fonts, but it's in a Drive)

   - **Fonts:** [here](https://drive.google.com/drive/folders/1MflR6nEbgSnao5DpHo4jXkpqXQBUENuI?usp=sharing)

   <br>

   <details open>
   <summary><strong>Config and Binaries</strong></summary>

   ```sh
    $ mkdir -p $HOME/.config/ && cp -r ./config/* $HOME/.config/
    $ mkdir -p $HOME/.mozilla/firefox/"yourprofile".default-relase/chrome/ && cp -r ./chrome/* $HOME/.mozilla/firefox/"yourprofile".default-relase/chrome/
    $ mkdir -p $HOME/.rofi-themes/ && cp -r ./.rofi-themes/* $HOME/.rofi-themes/
    $ mkdir -p $HOME/.xfce4-plugins/ && cp -r ./xfce-plugins/* $HOME/.xfce4-plugins/
   ```

   </details>
   
   <br>

   > Once finished copying the files, you might want to finalize the changes to your system.

   ```sh
    # Reboot your system to aply vala-panel works
    $ reboot
   ```

   <br>
