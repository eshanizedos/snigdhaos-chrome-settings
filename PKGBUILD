
# Maintainer: Eshan Roy <src.eshan@gmail.com>

pkgname=snigdhaos-chrome-settings
org=eshanizedos
pkgver=1.0.0
pkgrel=1
pkgdesc="Snigdha OS Chrome Config!"
arch=('any')
url="https://github.com/$org/$pkgname"
license=("GPL3")
depends=('gnome-keyring')
source=("psd.conf"
        "$pkgname.tar.gz")

package() {
  install -dm 755 "${pkgdir}/etc/skel/.config/google-chrome/"
  install -dm 755 "${pkgdir}/etc/skel/.config/psd"

  cp -rf "${srcdir}/google-chrome" "${pkgdir}/etc/skel/.config/"
  cp -rf "${srcdir}/psd.conf" "${pkgdir}/etc/skel/.config/psd/"  
  
}
sha512sums=('SKIP'
            'SKIP')
