# Maintainer: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=3.0.7
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v${pkgver}/ente-auth-v${pkgver}-x86_64.deb")
sha512sums_x86_64=('ddf5b8bfbe91737146ab841d14547a1eade63e549a9d1c1ffd3982cde43057ba2c59a3058aa805ee9ef1de68e2edc0d697b0b52a969e997707ff67da3f21815c')
provides=("ente-auth")
conflicts=("ente-auth")

package(){
	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
