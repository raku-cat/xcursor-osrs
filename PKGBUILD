# Maintainer: Raku <raku at raku dot party>
# PKGBUILD based on:
# https://github.com/archlinux/svntogit-community/blob/packages/xcursor-comix/trunk/PKGBUILD
# https://github.com/archlinux/svntogit-community/blob/packages/xcursor-bluecurve/trunk/PKGBUILD

pkgname=xcursor-osrs
pkgver=1.0.1
pkgrel=1
pkgdesc="X11 Mouse theme using OSRS icons"
arch=('any')
url="https://github.com/raku-cat/xcursor-osrs/"
license=('CC0-1.0')
source=("https://github.com/raku-cat/xcursor-osrs/releases/download/v${pkgver}/xcursor-osrs.tar.xz")
sha256sums('9f51f85bfc770b36f71bea9617a0780d060edd505a961653d012ff65dc4141b0')

package() {
    install -d "${pkgdir}"/usr/share/icons
    cp -R "${srcdr}"/Oldschool-Runescape "${pkgdir}"/usr/share/icons
}