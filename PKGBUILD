pkgname=ls-repo-outdated
pkgver=1.0.0
pkgrel=0
pkgdesc='poor mans semantic-release'
arch=('any')
url='https://github.com/arlac77/ls-repo-outdated.git'
license=(MIT)
public=true

package() {
    depends=(perl)
    install -dm755 "$pkgdir/usr/bin"
    install -Dm755 $srcdir/../ls-repo-outdated "$pkgdir/usr/bin"
}
