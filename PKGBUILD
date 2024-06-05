# Maintainer: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=3.0.8
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v${pkgver}/ente-auth-v${pkgver}-x86_64.deb")
sha512sums_x86_64=('c26bb76f4baa0fc31ea59db459c0ad9750b33a84fb5d77cff6fa021d849733a6b0fa0dd7e1a7009429fc7cdc9cdf72d120be98c9286d51ac2b42f699d21cbbb5')
provides=("ente-auth")
conflicts=("ente-auth")

package(){
	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
