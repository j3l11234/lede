# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#
# licheng
# www.maxlicheng.com
# 2019-06-08
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-unblockmusic
PKG_VERSION:=2.2.0
PKG_RELEASE:=8

PKG_LICENSE:=Apache-2.0

LUCI_TITLE:=LuCI support for Unblock NeteaseCloudMusic
LUCI_DEPENDS:=+UnblockNeteaseMusic +bash +dnsmasq-full +ipset +bash
LUCI_PKGARCH:=all

PKG_MAINTAINER:=lean

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature

