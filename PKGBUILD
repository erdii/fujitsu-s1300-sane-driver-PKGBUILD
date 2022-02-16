# Maintainer: erdii <me at erdii dot engineering>
pkgname=fujitsu-s1300-drivers
pkgver=0.1.0
pkgrel=1
pkgdesc="SANE drivers for Fujitsu S1300"
arch=('any')
license=()
depends=('sane')
makedepends=()

package() {
  install -Dm644 "../dist/1300_0C26.nal" "${pkgdir}/usr/share/sane/epjitsu/1300_0C26.nal"
}
