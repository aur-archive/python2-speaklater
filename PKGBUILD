# Maintainer: warddr <aur@warddr.eu>
# Submitter: Frank Smit <frank/61924/nl>

pkgname=python2-speaklater
pkgver=1.3
pkgrel=1
pkgdesc="Implements a lazy string for python useful for use with gettext."
arch=(any)
url="http://pypi.python.org/pypi/speaklater"
license=("BSD")
depends=("python2")
makedepends=("setuptools")
source=("http://pypi.python.org/packages/source/s/speaklater/speaklater-${pkgver}.tar.gz")
md5sums=("e8d5dbe36e53d5a35cff227e795e8bbf")

build() {
    cd $srcdir/speaklater-$pkgver
    python2 setup.py install --root="$pkgdir" --prefix=/usr
}
