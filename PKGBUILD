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
sha256sums=('f16e32b3877eda5cc1c44c06008b6594c8a76a9730f48ea337a1e6ed69d0bae1')
package() {
    install -d "${pkgdir}"/usr/share/icons
    cp -R "${srcdir}"/Oldschool-Runescape "${pkgdir}"/usr/share/icons
}