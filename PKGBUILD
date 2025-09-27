pkgname=tmpvoid
pkgver=1.0.0
pkgrel=1
pkgdesc="Part of the tmplinux suite. Temporary Void Linux"
arch=('any')
url="https://github.com/TheOddCell/tmpvoid"
license=('MIT')
depends=('bash' 'tar' 'xz' 'curl' 'shadow' 'util-linux' 'systemd' 'squashfs-tools')
makedepends=()
source=('tmpvoid')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpvoid "$pkgdir/usr/bin/tmpvoid"
}
