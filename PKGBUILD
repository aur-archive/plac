# Maintainer: archtux <antonio dot arias99999 at gmail dot com>

pkgname=plac
pkgver=0.9.1
pkgrel=2
pkgdesc="Command line arguments parser"
arch=('any')
url="http://pypi.python.org/pypi/plac"
license=('BSD')
depends=('python2')
source=(http://pypi.python.org/packages/source/p/plac/plac-$pkgver.tar.gz)
md5sums=('d7c90a689341c9a8f2706669f4be8b2b')

package() {
  cd $srcdir/$pkgname-$pkgver
  python2 setup.py install --root=$pkgdir --optimize=1
}