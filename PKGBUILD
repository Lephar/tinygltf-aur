# Maintainer: Ali Emre Gülcü <aliemreglc at gmail dot com>
# Update PKGSums: updpkgsums
# Update SRCINFO: makepkg --printsrcinfo > .SRCINFO

pkgname=tinygltf
pkgver=2.8.21
pkgrel=1
pkgdesc="Header only C++ tiny glTF library(loader/saver)"
arch=('any')
url="https://github.com/syoyo/$pkgname"
license=('MIT')
source=("$pkgname-$pkgver.tar.gz::$url/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('e567257d7addde58b0a483832cbaa5dd8f15e5bcaee6f023831e215d1a2c0502')

package() {
  cd $pkgname-$pkgver
  mkdir -p $pkgdir/usr/include/$pkgname $pkgdir/usr/share/licenses/$pkgname
  install *.h $pkgdir/usr/include/$pkgname
  install *.hpp $pkgdir/usr/include/$pkgname
  install LICENSE $pkgdir/usr/share/licenses/$pkgname
}
