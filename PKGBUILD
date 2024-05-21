# Maintainer: Alessandro Bernardello
# Contributor: Alessandro Bernardello
pkgname=ente-auth-bin
pkgver=3.0.4
pkgrel=1
pkgdesc="Ente two-factor authenticator."
arch=('x86_64')
url="https://github.com/ente-io/ente/tree/main/auth"
license=('AGPL-3.0')
depends=('at-spi2-core' 'ayatana-ido' 'cairo' 'desktop-file-utils' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'harfbuzz' 'hicolor-icon-theme' 'libappindicator-gtk3' 'libayatana-appindicator' 'libsecret' 'libsodium' 'pango' 'sqlite' 'webkit2gtk')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://github.com/ente-io/ente/releases/download/auth-v3.0.4/ente-auth-v3.0.4-x86_64.deb")
sha512sums_x86_64=('939b75ffdb404463b79e430f46be29c9a3d73ee14bc2449e20737619a85c374dc0318f4a17c385ff9dac503aca0233ab9d011a5c96af52de2a6cfdbc2e2aba19')
provides=("ente-auth")
conflicts=("ente-auth")

package(){

	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"
}
