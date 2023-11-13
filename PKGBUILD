pkgbase=apocos
pkgver=0.0.3
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
    '7c82e02064a2f899b43a0fc248542ad9a2775c96025e23a8af727a9c4e4e50b4'
    '6e85afb59df2d05c770690128ffa69e1e87889927f3b6f53e9a83b06daa537f8'
)
depends=(
    'apocos-desktop'
    'awesome' 'rofi' 'dex' 'picom'
)

package(){
    install -Dm0644 rc.lua $pkgdir/etc/skel/.config/awesome/rc.lua
    install -Dm0755 theme.lua $pkgdir/usr/share/apocos/awesome/theme.lua
}
