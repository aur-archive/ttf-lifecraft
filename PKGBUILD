pkgname=ttf-lifecraft
pkgver=20080801
pkgrel=2
pkgdesc="The popular Warcraft font"
arch=(any)
url="http://www.dafont.com/lifecraft.font"
license=("unknown")
depends=(fontconfig xorg-font-utils)
source=("lifecraft.zip::http://img.dafont.com/dl/?f=lifecraft")
md5sums=('208d69bc6e2641fe87ebf9f226a196d5')
install="$pkgname.install"

package() {
  install -Dm644 "$srcdir/LifeCraft_Font.ttf" "$pkgdir/usr/share/fonts/TTF/LifeCraft_Font.ttf"
}
