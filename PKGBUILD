# Based on the file created for Arch Linux by:
# Pierre Schmitz <pierre@archlinux.de>

# Maintainer: Alex Gajewski <agajews@gmail.com>

pkgname=apricity-keyring
pkgver=0.0.1
pkgrel=1
pkgdesc='Apricity PGP keyring'
arch=('any')
url='http://apricityos.com'
license=('GPL')
install="${pkgname}.install"
source=('Makefile'
        'apricity.gpg'
        'apricity-revoked'
        'apricity-trusted')
sha256sums=('a1a91c59146b244e01272b7bffc12951bf854fa8197679abdc573d0367be6e2a'
            'a8c4d490c96b1a227d6fa8c839364156ef396d652f735fd0f810498713e8f5ef'
            'e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855'
            'a799d0b7b860f932adcd5b2d583fe40ec58d8b68fbbc0093bf35dd7b027c7927')

package() {
	#cd "${srcdir}/${pkgname}-${pkgver}"
	cd "${srcdir}"
	make PREFIX=/usr DESTDIR=${pkgdir} install
}
# -*- mode: bash;-*-
