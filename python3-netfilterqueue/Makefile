include $(TOPDIR)/rules.mk

PKG_NAME:=python3-netfilterqueue
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

PKG_SOURCE:=NetfilterQueue-1.0.0.tar.gz
PKG_SOURCE_URL:=https://files.pythonhosted.org/packages/52/40/cc706275da4c9b968ce1223f586e0ab6ef20f3f6e840724b43070e85234e/
PKG_SOURCE_VERSION:=1.0.0
PKG_SOURCE_SUBDIR:=python3-netfilterqueue-1.0.0
PKG_BUILD_DIR:=$(BUILD_DIR)/$(PKG_NAME)-$(PKG_VERSION)/

HOST_PYTHON3_PACKAGE_BUILD_DEPENDS:=Cython

include $(INCLUDE_DIR)/package.mk
include $(TOPDIR)/feeds/packages/lang/python/python3-package.mk

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

$(eval $(call Py3Packageython3-netfilterqueue))
$(eval $(call BuildPackageython3-netfilterqueue))
