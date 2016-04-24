# Based on the file created for Arch Linux by:
# Pierre Schmitz <pierre@archlinux.de>

# Maintainer: Alex Gajewski <agajews@gmail.com>

pkgname=apricity-keyring
pkgver=0.0.2
pkgrel=1
pkgdesc='Apricity PGP keyring'
arch=('any')
url='http://apricityos.com'
license=('GPL')
install="${pkgname}.install"
source=('apricity-keyring.tar.gz')
sha256sums=('e0efe7a7e458ce00675407177a88ca69a37077012f84a86eb90c79fe52488b21')

package() {
	#cd "${srcdir}/${pkgname}-${pkgver}"
	cd "${srcdir}/apricity-keyring"
	make PREFIX=/usr DESTDIR=${pkgdir} install
}
# -*- mode: bash;-*-
