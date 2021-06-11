# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=snapshot
pkgver=0.0.1
pkgrel=1
epoch=
pkgdesc=""
arch=("x86_64")
url="https://github.com/RyanBruno/Snapshot"
license=('GPL')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("snapshot")
noextract=()
md5sums=()
validpgpkeys=()

#prepare() {
	#cd "$pkgname-$pkgver"
	#patch -p1 -i "$srcdir/$pkgname-$pkgver.patch"
#}

#build() {
	#cd "$pkgname-$pkgver"
	#./configure --prefix=/usr
	#make
#}

#check() {
	#cd "$pkgname-$pkgver"
	#make -k check
#}

package() {
	#cd "$pkgname-$pkgver"
	#make DESTDIR="$pkgdir/" install
    mkdir -p $pkgdir/usr/bin
    install snapshot $pkgdir/usr/bin/snapshot
}
