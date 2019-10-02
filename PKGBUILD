pkgname=plymouth-theme-catergos-arch	
pkgver=v1	
pkgrel=1	
pkgdesc="A Plymouth theme for catergos linux"	
arch=('any')	
url="https://github.com/Catergos/plymouth"	
license=('GPL-3.0')	
depends=('plymouth')	

source=('v-1.tar.gz::https://github.com/Catergos/plymouth/archive/v-1.tar.gz')	

sha256sums=('460480820ad6988ab06738e338ffb210ce6f009de43d9cd746f18844749b5471')	
package() {	
    cd $srcdir/plymouth-v-1	
    mkdir -p $pkgdir/usr/share/plymouth/themes/catergos	
    install -Dm644 * $pkgdir/usr/share/plymouth/themes/catergos	
}
