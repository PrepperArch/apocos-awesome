pkgbase=apocos
pkgver=0.0.2
pkgrel=1
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
    '78623c8124e5baff71922408a5e7ad525acbb95115eb2691b9253e477dc8d6f5'
)
depends=(
    'apocos-desktop'
    'awesome' 'rofi'
)

package(){
    install -Dm0644 rc.lua $pkgdir/etc/skel/.config/awesome/rc.lua
    install -Dm0755 theme.lua $pkgdir/usr/share/apocos/awesome/theme.lua
}
