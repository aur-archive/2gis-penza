# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-penza
pkgver=22
pkgrel=1
pkgdesc="Map of Penza for 2GIS, February 2013"
arch=('i686' 'x86_64')
url="http://penza.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Penza-22.orig.zip")
md5sums=('fd9829180685b78865881fa74ca7395f')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Penza.dgdat "${startdir}/pkg/opt/2gis/penza.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Penza.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Penza.dglf" || return 1
     
}

