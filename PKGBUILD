# Maintainer: Philip Müller <mail AT philip.in-aachen DOT net>
pkgname=emacs-dart-mode-svn
pkgver=20121129
pkgrel=1 
pkgdesc="emacs mode for the dart language"
url="http://www.dartlang.org"
arch=('any')
license=('GPL')
depends=('emacs')
source=("http://dart.googlecode.com/svn/trunk/dart/tools/utils/elisp/dart-mode.el")
md5sums=('00099a4ea0505ef5c5badb97549386dc')
install=${pkgname}.install

build() {
  cd "$srcdir/"
  install -Dm644 dart-mode.el $pkgdir/usr/share/emacs/site-lisp/dart-mode.el
}
