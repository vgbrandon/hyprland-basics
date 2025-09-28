sh -c "$(curl -fsSL https://raw.githubusercontent.com/vgbrandon/hyprland-basics/main/postinstall.sh)"

or

sh -c "$(wget -qO- https://raw.githubusercontent.com/vgbrandon/hyprland-basics/main/postinstall.sh)"

Hyprland.conf

exec-once = /usr/lib/polkit-gnome/polkit-gnome-authentication-agent-1 &
