# Maintainer: Steven! Ragnarök <steven@nuclearsandwich.com>
pkgname=mwifiex-firmware-git
pkgver=20140811
pkgrel=1
pkgdesc="Marvell Wireless Firmware"
arch=(i686 x86_64)
url="https://origin-www.marvell.com/wireless/avastar/88W8897/"
license=('custom')
makedepends=('git')
source=(git://git.marvell.com/mwifiex-firmware.git)
noextract=()
sha512sums=('SKIP')

package() {
  install -Dd $srcdir/mwifiex-firmware/mrvl $pkgdir/lib/firmware/mrvl
  install -Dd $srcdir/mwifiex-firmware/mrvl $pkgdir/lib64/firmware/mrvl
  install -D $srcdir/mwifiex-firmware/LICENCE.Marvell $pkgdir/usr/share/licenses/mwifiex-firmware-git/LICENCE.Marvell
}

# vim:set ts=2 sw=2 et:
