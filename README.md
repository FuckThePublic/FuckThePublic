sudo DEBIAN_FRONTEND=noninteractive \
apt install --assume-yes xfce4 desktop-base dbus-x11 xscreensaver

wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb



sudo bash -c 'echo "exec /etc/X11/Xsession /us/bin/xfce4-session" › /etc/c /etc/X11/Xsession /usr/bin/xfce4-session" › /etc/chrome-remote-desktop-session’
