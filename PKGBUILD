pkgname=python3-sexpdata
pkgver=0.0.3
pkgrel=1
pkgdesc="S-expression parser for Python."
arch=('x86_64')
url="http://sexpdata.readthedocs.org"
license=('BSD')
depends=('python3')
source=("http://pypi.python.org/packages/source/s/sexpdata/sexpdata-${pkgver}.tar.gz")
md5sums=('de9c2c3ee28551e766cb535c0b2cebf0')

package() {
  cd "$srcdir/sexpdata-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}
