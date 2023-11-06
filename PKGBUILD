pkgbase=apocos
pkgver=0.0.2
pkgrel=4
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
    'e750b6ac8f4b96089810f362c0bedc86384fa390a31bc0bfce6c9c9a170d4f7b'
    '41d336d52b8b192051771b5e535fab978fa62c0661d73c681ac30465e9217fdd'
)
depends=(
    'apocos-desktop'
    'awesome' 'rofi'
)

package(){
    install -Dm0644 rc.lua $pkgdir/etc/skel/.config/awesome/rc.lua
    install -Dm0755 theme.lua $pkgdir/usr/share/apocos/awesome/theme.lua
}
