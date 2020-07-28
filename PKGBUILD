# Created by SkyyySi

pkgname=i3-gnome-flashback-git
_pkgname=i3-gnome-flashback
pkgver=3.36
pkgrel=1
pkgdesc='Starts i3 inside a GNOME-Flashback session.'
arch=('any')
url='https://github.com/SkyyySi/i3-gnome-flashback'
license=('MIT')
depends=('i3-wm' 'gnome-flashback')
conflicts=('i3-gnome-flashback')
source=("i3-gnome-flashback::git+https://github.com/SkyyySi/i3-gnome-flashback.git#branch=master")
md5sums=('SKIP')

package() {
	cd "$_pkgname"
	make DESTDIR="$pkgdir/" install
}
