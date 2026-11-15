pkgname=parch-labwc-config
pkgver=1.0
pkgrel=1
pkgdesc="Parch Linux LABWC dotfiles"
depends=(
    'labwc'
    'xorg-xwayland'
    'lxqt-policykit'
    'qt6-wayland'
    'qt6ct-kde'
    'papirus-icon-theme'
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
