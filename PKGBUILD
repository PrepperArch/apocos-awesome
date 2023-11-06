pkgbase=apocos
pkgver=0.0.3
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
    'e750b6ac8f4b96089810f362c0bedc86384fa390a31bc0bfce6c9c9a170d4f7b'
    '6e85afb59df2d05c770690128ffa69e1e87889927f3b6f53e9a83b06daa537f8'
)
depends=(
    'apocos-desktop'
    'awesome' 'rofi'
)

package(){
    install -Dm0644 rc.lua $pkgdir/etc/skel/.config/awesome/rc.lua
    install -Dm0755 theme.lua $pkgdir/usr/share/apocos/awesome/theme.lua
}
