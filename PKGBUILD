pkgbase=apocos
pkgver=0.0.2
pkgrel=2
pkgname='apocos-awesome'
pkgdesc="Awesome wheme and config for Apocalypse OS"
arch=('any')
url="https://github.com/PrepperArch/apocos-awesome"
license=('MIT')
source=(
    'rc.lua'
    'theme.lua'
)
sha256sums=(
    '71917b600757afb1492cae7f83ea5a345d55236bbb3a6c3e61b4a941b1711a93'
    '7840ed0bcff32fedc1fe86d75c51cdb19006310db822416aedc552f49431cf77'
)
depends=(
    'apocos-desktop'
    'awesome' 'rofi'
)

package(){
    install -Dm0644 rc.lua $pkgdir/etc/skel/.config/awesome/rc.lua
    install -Dm0755 theme.lua $pkgdir/usr/share/apocos/awesome/theme.lua
}
