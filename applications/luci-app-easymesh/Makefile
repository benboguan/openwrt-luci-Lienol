#
#-- Copyright (C) 2021 dz <dingzhong110@gmail.com>
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for easymesh
LUCI_DEPENDS:=+kmod-cfg80211 +batctl-default +kmod-batman-adv +wpad-basic-wolfssl +dawn
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-easymesh

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
