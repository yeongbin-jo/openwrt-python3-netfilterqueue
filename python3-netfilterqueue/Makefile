include $(TOPDIR)/rules.mk

PKG_NAME:=python3-netfilterqueue
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

PYPI_NAME:=NetfilterQueue
PKG_HASH:=507be475d8c9f98834763aacf2f6cfe800b253ccd283f14f3d6f89a4f87a5878

PKG_MAINTAINER:=Josef Schlehofer <josef.schlehofer@nic.cz>
PKG_LICENSE:=MIT
PKG_LICENSE_FILES:=LICENSE.txt

HOST_PYTHON3_PACKAGE_BUILD_DEPENDS:=Cython

include ../pypi.mk
include $(INCLUDE_DIR)/package.mk
include ../python3-package.mk

define Package/python3-netfilterqueue
  SECTION:=lang
  CATEGORY:=Languages
  SUBMENU:=Python
  TITLE:=NetfilterQueue binding for Python
  URL:=https://github.com/oremanj/python-netfilterqueue
  DEPENDS:=+python3
endef

define Package/python3-netfilterqueue/description
  NetfilterQueue binding for Python
endef

$(eval $(call Py3Package,python3-netfilterqueue))
$(eval $(call BuildPackage,python3-netfilterqueue))
$(eval $(call BuildPackage,python3-netfilterqueue-src))
