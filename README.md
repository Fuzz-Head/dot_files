# dot_files
all dot files lul 

## Mind attic 

linux installtion and dev machines trials and installs 


I will have to do the selections properly 
vrtualBox 
other options available are Hyper-V and VMWare 

OS preference high towards arch linux 
Arch linux 
all arch derivatives 
- Manajaro 
- EndavourOS 
- ArcoLinuxD/ ArcoLinux 
gogh seems to show 16 colors but alacritty supports only 8 so 
I will have to do the selections properly 

Terminal emulators 
- Alacritty - fast and highly customisible 
- foot - i guess it just works 

Termainal shells 
- oh my zsh - have used a lot of omz back in the days so would like to give other a try 
- fish - look very decent and will give it a try 

Windows managers 
- i3wm - have used a lot of i3wm and is pretty configurable and easy to use 
- awesomewm - used a little bit didnt like it much and didnt try out much and
    stopped using it soon 
- bspwm - used a fair bit and liked it too, very configurable and easy to use 
the bspwm configuration got wiped out when I upgraded ubuntu to 24.xx 

- swaywm - wanting to try out as new to it, seemed a little difficult to get it to work and 
    starting out, need more patience to try and test 
- qtile - is a python based and will be tried if everything goes well with swaywm 
- xmonad - maybe?

when all is set up and up and running all dot files will be committed to github
all the data will be stored and backed up in case of vm failure and unforseen changes or 
corruptions that may/will take place in the future. 

main purpose of setting up linux vm is to continously gain familarity with the 
unix system commands and interfaces and for the use of vim - which is better in linux 

also various other things can be tried and tested, once I have the bare bones of the 
system working as per my expectations.

currently lot of issues with the graphics driver, and display resolution
issue with a very laggy mouse on arch with sway wm 
issues of resizing in manjaro, worked fine on the first boot


if eventually none of the installations work out, will resort on trying ubuntu or 
fedora in gnome or sway environment 
and/or remove the gnome installtion and put something lightweight 

the current main purpose for using linux and wm is for better effencicy and 
boosting productivity and learning purposes, no intentions of ricing the VM

ricing will be considered only when everything works as expected and on 
maintaining a solid grip on the fundamentals of linux, all required vim stuff,
 dot files and the entire linux file system. 

Configuration for i3wm 
fc-list will output all available fonts on the system 
fonts in i3wm should be space seperated - Font Awesome 6 Free ; Font Awesome 6 Free Regular - this should get 
Font Awesome to work atleast 
or try this 
# font pango:Source Code Pro for Powerline, FontAwesome Regular, Icons 9

going though others config files is always helpful and can show a lot 
of possibilities and configuration options 
here is one : https://github.com/erikdubois/Archi3/blob/master/config

when ever i log into i3wm i just hate the color scheme, I would like to change the bar theme and other color
to get a little ease 
https://colorhunt.co/palettes/sea - some sea based color pallets to match the current wallpaper 

# class                 border  backgr. text    indicator child_border
client.focused          #4c7899 #285577 #ffffff #2e9ef4   #285577
client.focused_inactive #333333 #5f676a #ffffff #484e50   #5f676a
client.unfocused        #333333 #222222 #888888 #292d2e   #222222
client.urgent           #2f343a #900000 #ffffff #900000   #900000
client.placeholder      #000000 #0c0c0c #ffffff #000000   #0c0c0c

client.background       #ffffff

with sea theme applied 
# class                 border  backgr. text    indicator child_border
client.focused          #092635 #5C8374 #9EC8B9 #2e9ef4   #285577
client.focused_inactive #333333 #5f676a #ffffff #484e50   #5f676a
client.unfocused        #333333 #222222 #888888 #292d2e   #222222
client.urgent           #2f343a #900000 #ffffff #900000   #900000
client.placeholder      #000000 #0c0c0c #ffffff #000000   #0c0c0c

client.background       #ffffff


as much as i like to rice the desktop, it will be very hard and annoying as 
there will be cascading issues: installing a compositor, and getting it to work 
specially with broken or worng graphic drivers, then getting alacritty to working 
correctly as it doesnt launch normally now 


configuring the terminal 

alacritty.toml 

Iosevka
or 
monospace argon 

for terminal colors I will start with gogh and then take it from there,
because eventually I have to start somewhere and then continously tweak 
till i get the desired result 
gogh seems to show 16 colors but alacritty supports only 8 so 
I will have to do the selections properly 



Other linux commands and handy stuff 

