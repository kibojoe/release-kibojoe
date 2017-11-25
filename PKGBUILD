# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=release-kibojoe
pkgver=1709
pkgrel=7
pkgdesc="Kibojoe's release definition"
arch=("any")
url="https://github.com/kibojoe/release-kibojoe"
license=('GPL3')
depends=('lsb-release')
source=('lsb-release')
conflicts=('manjaro-release' 'manjaro-release-dev')
install="release-kibojoe.install"
sha256sums=(SKIP)

package() {
	mkdir -p ${pkgdir}/etc
	install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
