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
sha256sums=('2d50240ebd175999a07f54dd8371135567b4147ca02d726018f5520fb2e374ea')

package() {
	#cd "${srcdir}/${pkgname}-${pkgver}"
	cd "${srcdir}/apricity-keyring"
	make PREFIX=/usr DESTDIR=${pkgdir} install
}
# -*- mode: bash;-*-
