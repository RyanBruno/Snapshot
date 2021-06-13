# Maintainer: Ryan Bruno <ryan@rbruno.com>
pkgname=snapshot
pkgver=0.0.1
pkgrel=1
pkgdesc='A utility for enabling snapshot backups on *nix systems.'
arch=('any')
url='https://github.com/RyanBruno/Snapshot'
license=('GPL')
depends=('rsync')
backup=('etc/snapshot/config')
source=(https://github.com/RyanBruno/Snapshot/releases/download/${pkgver}/${pkgname}-${pkgver}.tar.gz
        https://github.com/RyanBruno/Snapshot/releases/download/${pkgver}/${pkgname}-${pkgver}.tar.gz.gpg)
#source=(snapshot config)
sha256sums=('4f982d406df1cae711b13896a1cf8bce3737be0153e59d9ed271808aa4c66055' 'SKIP')
validpgpkeys=('915EBB9C9889E4AEB983CD96F15F942AA25D5A6A')

package() {
    mkdir -p $pkgdir/usr/bin
    mkdir -p $pkgdir/etc/snapshot
    install snapshot $pkgdir/usr/bin/snapshot
    install config $pkgdir/etc/snapshot/config
}
