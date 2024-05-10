# Maintainer: Alessandro Bernardello
# Contributor: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=2.0.54
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v2.0.54/ente-auth-v2.0.54-x86_64.deb")
sha512sums_x86_64=('6f15198e46ecde8a070e02105685eec232809fbfcf27fcdf8fcb05cec9a5995e03c6cc1f0098db48340703e84dec7d4d2c2ebfaf7788850279e0d83edf3dd4dc')
provides=("ente-auth")
conflicts=("ente-auth")

package(){

	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
