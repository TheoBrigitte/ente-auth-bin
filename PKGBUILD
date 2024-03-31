# Maintainer: Alessandro Bernardello
# Contributor: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=2.0.50
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v2.0.50/ente-auth-v2.0.50-x86_64.deb")
sha512sums_x86_64=('28ef28a6855ed3eb50c8cbbabb09cea89a2074bc5e1cf9783fb683ca88334e0ef217fd3c1b1c014876e82959769a5f69f7f8ce7e4f56c6d444782a355250cf66')
provides=("ente-auth")
conflicts=("ente-auth")

package(){

	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
