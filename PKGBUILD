pkgname=parch-hyprland-config
pkgver=1.0
pkgrel=1
pkgdesc="Parch Linux Hyprland dotfiles"
depends=(
    'hyprland'
    'xorg-xwayland'
    'xdg-desktop-portal-hyprland'
    'polkit-kde-agent'
    'qt6-wayland'
    'qt6ct-kde'
    'kvantum'
    'kvantum-qt5'
    'kvantum-theme-materia'
    'papirus-icon-theme'
    'materia-kde'
    'materia-gtk-theme'
    'kitty'
    'quickshell'
    'noctalia'
    'playerctl'
    'sddm'
    'hyprmod'
    'ttf-google-sans'
)
arch=('any')
license=('GPL3')

package() {
    install -dm755 "$pkgdir/etc/skel"

    cp -r "$startdir/skel/." "$pkgdir/etc/skel/"
}
