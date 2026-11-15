pkgname=parch-hyprland-config
pkgver=1.6
pkgrel=3
pkgdesc="Parch Linux Hyprland dotfiles"
depends=(
    'hyprland'
    'xorg-xwayland'
    'xdg-desktop-portal-hyprland'
    'qt6-wayland'
    'qt6ct-kde'
    'papirus-icon-theme'
    'quickshell'
    'noctalia'
    'playerctl'
    'sddm'
    'ttf-google-sans'
)
arch=('any')
license=('GPL3')

package() {
    install -dm755 "$pkgdir/etc/skel"

    cp -r "$startdir/skel/." "$pkgdir/etc/skel/"
}
