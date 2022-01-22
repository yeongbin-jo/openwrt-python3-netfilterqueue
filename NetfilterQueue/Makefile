include $(TOPDIR)/rules.mk

PKG_NAME:=NetfilterQueue
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

PKG_SOURCE:=NetfilterQueue-1.0.0.tar.gz
PKG_SOURCE_URL:=https://files.pythonhosted.org/packages/52/40/cc706275da4c9b968ce1223f586e0ab6ef20f3f6e840724b43070e85234e/
PKG_HASH:=507be475d8c9f98834763aacf2f6cfe800b253ccd283f14f3d6f89a4f87a5878
PKG_SOURCE_VERSION:=1.0.0
PKG_SOURCE_SUBDIR:=NetfilterQueue-1.0.0

HOST_PYTHON3_PACKAGE_BUILD_DEPENDS:=Cython

include $(INCLUDE_DIR)/package.mk
include $(TOPDIR)/feeds/packages/lang/python/python3-package.mk

define Package/NetfilterQueue
  SECTION:=lang
  CATEGORY:=Languages
  SUBMENU:=Python
  TITLE:=NetfilterQueue binding for Python
  URL:=https://github.com/oremanj/python-netfilterqueue
  DEPENDS:=+python3 +libnfnetlink +libnetfilter-queue
endef

define Package/NetfilterQueue/description
  NetfilterQueue binding for Python
endef

$(eval $(call Py3Package,NetfilterQueue))
$(eval $(call BuildPackage,NetfilterQueue))
$(eval $(call BuildPackage,NetfilterQueue-src))
