# Maintainer: Your Name <your.email@example.com>
pkgname=automouse
pkgver=1.0.0
pkgrel=1
pkgdesc="A simple mouse jiggler to show activity of microsft teams"
arch=('any')
url="https://github.com/haadisaqib/automouse"
license=('GPL')
depends=('xdotool')
source=("${pkgname}-${pkgver}.sh::https://raw.githubusercontent.com/haadisaqib/automouse/main/automouse.sh")
sha256sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/${pkgname}-${pkgver}.sh" "${pkgdir}/usr/bin/${pkgname}"
}
