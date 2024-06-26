# Maintainer: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=3.0.17
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v${pkgver}/ente-auth-v${pkgver}-x86_64.deb")
sha256sums_x86_64=('8ad5befa3dca9a4f0862280183b1d9bb03f07010e25054d7f119df336dceea45')
provides=("ente-auth")
conflicts=("ente-auth")

package(){
	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
