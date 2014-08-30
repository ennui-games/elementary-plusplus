elementary-plusplus
===================

elementary icon theme expansion pack for people who hate shit icons

At the moment the aim of this project is not to replace every single icon, rather to pick at the low hanging fruit of awful icons, for applications used every day. If you want to tip me off to an icon that's really awful file a bug I guess, it might take a while for me to get around to it.

If you want to submit your own artwork let me know, I'm not really sure how that's going to work at the moment :)

(UNTESTED) method for installing theme

    mkdir ~/.icons
    cd ~/.icons
    git clone https://github.com/ennui-games/elementary-plusplus.git
    gsettings set org.gnome.desktop.interface icon-theme 'elementary-plusplus'