# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: pspiagicw <pspiagicw@gmail.com>
pkgname=pspiagicw-iosevka-basic
pkgver=1.0
pkgrel=1
epoch=
pkgdesc="Iosevka Font without large download size, only essential and simple fonts present"
arch=(x86_64)
url="https://github.com/pspiagicw/iosevka-basic"
license=('MIT')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=(pspiagicw-iosevka-basic)
conflicts=(ttf-iosevka)
replaces=()
backup=()
options=()
install=
changelog=
source=("git+$url")
noextract=()
md5sums=('SKIP')
validpgpkeys=()

package() {
    cd "iosevka-basic"
    install -D -m 644 *.ttf -t "$pkgdir/usr/share/fonts/pspiagicw-iosevka"
}
