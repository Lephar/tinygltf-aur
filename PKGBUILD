# Maintainer: Ali Emre Gülcü <aliemreglc at gmail dot com>
# Update PKGSums: updpkgsums
# Update SRCINFO: makepkg --printsrcinfo > .SRCINFO

pkgname=tinygltf
pkgver=2.9.3
pkgrel=1
pkgdesc="Header only C++ tiny glTF library(loader/saver)"
arch=('any')
url="https://github.com/syoyo/$pkgname"
license=('MIT')
source=("$pkgname-$pkgver.tar.gz::$url/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('f5f282508609a0098048c8ff25d72f4ef0995bc1d46bc7a5d740e559d80023d2')

package() {
  cd $pkgname-$pkgver
  mkdir -p $pkgdir/usr/include/$pkgname $pkgdir/usr/share/licenses/$pkgname
  install *.h $pkgdir/usr/include/$pkgname
  install *.hpp $pkgdir/usr/include/$pkgname
  install LICENSE $pkgdir/usr/share/licenses/$pkgname
}
