# Archtrack maintainer: Evan Teitelman <teitelmanevan at gmail dot com>
# Contributor: Francesco Piccinno <stack.box@gmail.com>

pkgname=lbd
pkgver=latest
pkgrel=1
pkgdesc="Load Balancing detector"
url="http://ge.mine.nu/code/lbd"
arch=(any)
license=('GPL')
depends=('bash')
source=(http://ge.mine.nu/code/lbd)
# If the hash is wrong, audit the script
md5sums=('de0378c208909945c685cef29c85dc9e')

groups=(archtrack archtrack-info-gathering)

build() {
  cd "$srcdir"
  install -Dm755 lbd $pkgdir/usr/bin/lbd
}

