

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.0.1-20240822
PKG_RELEASE:=

LUCI_TITLE:=LuCI support for bmtedge
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+lsblk +docker +luci-lib-taskd

define Package/luci-app-bmtedge/conffiles
/etc/config/bmtedge
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
