
# Dogshit Low Effort Dotfiles

Hi, I see you are here, welcome to my dotfiles, they are not so good but provides everything I need :). Ofcourse as the name, the effort in these dotfiles is significantly low, and it's filled with weird idiotic hacks, but *trust me you won't notice them.* <br>

<div align='center'>

![GitHub last commit](https://img.shields.io/github/last-commit/OhEmmaGee/low-effort-dotfiles?color=7374f7)

</div>

## **Summary**

#### ~~Sponsored~~ Spoonfeeded By:
- 27 Cups of coffee! (As of 10th Jan 2022)
### **Stuff:**
- ArchLinux as a distro, *but bloated*  
- ZSH as shell, *more bloated than yo momma*   
- XFCE as Desktop Environment   
- Alacritty as the terminal   
- Picom as the compositor, *with a shit config*   
- Rofi as launcher  
- Inter as font
- EWW and Conky as widgets!
- Deadd notification center as notification daemon and center

## Wanna use it? Lets do this

The folders in the `.config` directory are actual dotfiles, so you copy them into your "/home/`<username>`/.config" folder and edit them according to your needs.
 
#### Just make sure to:
- Edit the `API_KEY` and the `CITY_ID` in conky to get the weather stuff working, it is located in `~/.config/conky/Kochab/scripts/weather.sh`. You can get one key from [OpenWeatherMap](https://openweathermap.org/api)
- Make sure to edit the EWW widgets for your name, username and hostname to be displayed. They can be edited in `~/.config/eww/structs/main-utils/user/user.yuck`.

#### Done? Neat!     

**So...Packages?**  
Glad you asked! Below is the list :>    

`-` **Layan-GTK-Theme**  
Please use the modified one included in this repository, inside `.themes` folder. Just to eliminate those sucky right, left and botton window borders!    

`-` **Layan-Kvantum-Theme**  
Required for QT Applications, it can be again found in this repository, inside `.config/Kvantum` folder.  
To apply the theme, install [Kvantum Manager](https://github.com/tsujan/Kvantum/tree/master/Kvantum)  
Optionally Install QT5ct to style QT Applications.  

`-` **Rofi**  
To get the Application launcher, install [Rofi](https://github.com/davatorium/rofi)  
Optionally, to get a nice sexy looking emoji selector context menu, install the [Rofi emoji](https://github.com/Mange/rofi-emoji) package. The emoji menu configuration file is located in the rofi folder :)  

`-` **Conky**  
Ofcourse, to get some smoking hot widgets on your desktop! See [Conky](https://github.com/brndnmtthws/conky)  

`-` **EWW! 🤮**  
Just kidding, EWW isn't actually EWW, its beautiful. Install it to get some dashboard like widgets. See [EWW](https://github.com/elkowar/eww)    

`-` **Vala-Panel-Appmenu**
This is our MacOS like Appmenu in the top panel, see [Vala Panel Appmenu](https://github.com/rilian-la-te/vala-panel-appmenu). Make sure to install the XFCE version.  
After you install the XFCE Appmenu, make sure to run the below commands to enable it:  
```bash
xfconf-query -c xsettings -p /Gtk/ShellShowsMenubar -n -t bool -s true
xfconf-query -c xsettings -p /Gtk/ShellShowsAppmenu -n -t bool -s true
```  

`-` **Deadd Notification Center**  
Ofcourse, how can we forget the notifications? The XFCE notification stuff is shittier than fortnite kids, so I decided to move on from it, then I found Deadd, it is quite good, ngl.
See [linux_notification_center](https://github.com/phuhl/linux_notification_center)

### **Dont with the packages? AWESOME!**  
Time for some extra stuff!  
- To get an apple like looking menu, install [Xpple Menu](https://www.pling.com/p/1529470)
- A good lightdm theme is the start of your beautiful and amazing session, I would recommend [lightdm-webkit2-theme-glorious](https://github.com/manilarome/lightdm-webkit2-theme-glorious)
- Dolphin as the file manager, *Thunar kinda sucks..* ~~Don't cancel me please 🥺~~
- If you are an emacs fanboy/fangirl, there is a theme included for doom emacs in the repository! Tho it is just the doom-palenight theme with some color values changed 😒

## **Time for some screenshots!**
| Home Screen |
| --- |
| ![Homescreen Baby](https://cdn.upload.systems/uploads/mNlL9yBw.png) |    

| EWW Widgets |
| --- |
| ![EWW!](https://cdn.upload.systems/uploads/LvUQlx0t.png) |  
    

| Spotify |
| --- |
| ![Spotify](https://cdn.upload.systems/uploads/FTS8dU48.png) |   

## **Credits!**  
- The EWW widgets are from pagankeymaster with changed colors, [repo](https://github.com/pagankeymaster/vile)
- The conky theme is from closebox73 with changed colors and switched music state from mocp to mpris, [repo](https://github.com/closebox73/Leonis)
- The Spotify theme is a modified version of Dribblish theme, [repo](https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish)
- The rofi launcher is derived from adi1090x, [repo](https://github.com/adi1090x/rofi)

