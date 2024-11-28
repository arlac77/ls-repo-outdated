pkgname=ls-repo-outdated
pkgver=1.1.0
pkgrel=0
pkgdesc='list outdated packages form package repositories (.deb,.rpm,.pkg.tar)'
arch=('any')
url='https://github.com/arlac77/ls-repo-outdated.git'
license=(MIT)
public=true

package() {
    depends=(perl)
    install -dm755 "$pkgdir/usr/bin"
    install -Dm755 $srcdir/../ls-repo-outdated "$pkgdir/usr/bin"
}
