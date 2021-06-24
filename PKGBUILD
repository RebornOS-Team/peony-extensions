# Maintainer: CookieSource <cookiesource@rebornos.org>
# Co maintainer: RebornOS Team <team@rebornos.org>
pkgname=peony-extensions
_pkgname1=libpeony-bluetooth-plugin.so
_pkgname2=libpeony-engrampa-menu-plugin.so
_pkgname3=libpeony-menu-plugin-mate-terminal.so
_pkgname4=libpeony-send-to-device.so
_pkgname5=libpeony-set-wallpaper.so
_pkgname6=libpeony-share.so
pkgver=3.1.0
pkgrel=0
pkgdesc="Set of extensions for Peony, the UKUI file manager."
arch=('any')
url="https://github.com/ukui/peony-extensions"
license=('LGPL3')
makedepends=('make')
provides=(${pkgname})
conflicts=(${pkgname})
source=(${_pkgname1} ${_pkgname2} ${_pkgname3} ${_pkgname4} ${_pkgname5} ${_pkgname6})

package() {
           mkdir -p ${pkgdir}/usr/lib/peony-extensions/
           cp ${srcdir}/* ${pkgdir}/usr/lib/peony-extensions/
}

md5sums=('4c1c645493edb366c7d62d5e8ca327c4'
         'f0fc4572708e94c78df0cec39f9f3e81'
         '7f0f7f23841f1874a8fc86ab3222a40b'
         '05550d06031f1ae3fb8adaf983a2a618'
         '330875742781c9c40698adf129d07604'
         '6a30ea75dd7ab1dd0e3a690ffd8e4a7a')
