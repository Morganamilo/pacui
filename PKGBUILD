# Maintainer: Chrysostomus @forum.manjaro.org

pkgname=pacli
pkgver=0.1
pkgrel=1
pkgdesc="An interactive pacman interface using pmenu"
arch=(any)
url="https://github.com/Manjaro-Pek/$pkgname"
license=MIT
depends=('pmenu'
	'pacman'
	'yaourt'
	'sudo'
	'gzip'
	'downgrade'
	'bash')
makedepends=('git')
source=("git://github.com/Manjaro-Pek/$pkgname")
md5sums=('SKIP')

package () {
	cd "$srcdir"
        install -Dm755 "$srcdir/$pkgname/pacli" "$pkgdir/usr/bin/pacli"
}