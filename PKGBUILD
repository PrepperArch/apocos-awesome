pkgbase=apocos
pkgver=0.0.1
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
    'a17833792133af16e1b0f0e95f863ac5c4728373422360da778aa316fb325528'
    '2aecd8eeae69a2654ffb40994e5b313fd05d8fe8058bde418a5021da60c5551c'
)
depends=(
    'apocos-desktop'
)

package(){
    install -Dm0644 rc.lua $pkgdir/etc/skel/.config/awesome/rc.lua
    install -Dm0755 theme.lua $pkgdir/usr/share/apocos/awesome/theme.lua
}
