# Maintainer: Alessandro Bernardello
# Contributor: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=3.0.1
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v3.0.1/ente-auth-v3.0.1-x86_64.deb")
sha512sums_x86_64=('b1fab98d3ac657d574abc2ebedab1779c4492d4c0f95a9e0568c032ccd751df4b1011a57497bf6ca009b37cc569afbf3b10cddf910efb63da4de9c74e9b79215')
provides=("ente-auth")
conflicts=("ente-auth")

package(){

	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
