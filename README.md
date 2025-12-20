<div align="center">
  <h1>Jakubino2013's dotfiles :3</h1>
</div>

<div align="center">
  <h2>Waybar</h2>
  <img width="1917" height="63" alt="image" src="https://github.com/Jakubino2013/jakubinoos-dotfiles/blob/main/assets/2025-12-17-175234_hyprshot.png" />
  <h2>Rofi</h2>
  <h3>Menu</h3>
  <img alt="image" src="https://github.com/Jakubino2013/jakubinoos-dotfiles/blob/main/assets/2025-12-17-175350_hyprshot.png" />
  <h3>Powermenu</h3>
  <img alt="image" src="https://github.com/Jakubino2013/jakubinoos-dotfiles/blob/main/assets/2025-12-17-175416_hyprshot.png" />
  <p>Logout doesn`t work, but you can fix it</p>
  <h2>SwayNC</h2>
  <img alt="image" src="https://github.com/Jakubino2013/jakubinoos-dotfiles/blob/main/assets/2025-12-17-175307_hyprshot.png" />
</div>

<div>
  <h2>Default programs:<h2/>
    <p>Browser: Firefox</p>
    <p>Terminal: kitty</p>
    <p>File manager: Dolphin</p>
    <p>Menus: Rofi</p>
    <p>Bar: Waybar</p>
</div>

<div>
  <h2>Install</h2>
  <p> 1. clone this repo and get to the dotfiles directory:</p>
  
  ```fish
  git clone https://github.com/Jakubino2013/jakubinoos-dotfiles.git
  cd jakubinoos-dotfiles
  ```
  <p>2. install following packages with your AUR helper (this is required for function of dotfiles):</p>

  ```fish
  paru -S hyprland hyprpaper rofi waybar swaync 
  ```
  <p>Optional packages:</p>

  ```fish
  paru -S hyprsettings nwg-look
  ```
  <p>3. Copy config files:</p>

  ```fish
  cd config
  sudo cp -r hypr ~/.config
  sudo cp -r waybar ~/.config
  sudo cp -r rofi ~/.config
  sudo cp -r swaync ~/.config
  ```

  <h3>Note</h3>
  <p>You can customize the configs before copying</p>


</div>
  

    
