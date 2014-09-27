# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=oneosui
pkgver=20140908
pkgrel=1
pkgdesc="This provides to Infinity OS's UI."
arch=('i686' 'x86_64')
url="http://infinityos.org/repo/oneosui"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('bzr')
replaces=('gnome-shell')
_repanthalver=0.3.1
provides=('oneosui')
_fileurl=http://infinityos.org/repo/oneosui.tar.gz
source=("${_fileurl}")
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/themes
    cp -R usr/share/themes "${pkgdir}"/usr/share/

    mkdir -p "${pkgdir}"/usr/share/gnome-shell
    cp -R usr/share/gnome-shell "${pkgdir}"/usr/share/

}
