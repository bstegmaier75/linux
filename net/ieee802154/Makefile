obj-$(CONFIG_IEEE802154) += ieee802154.o af_802154.o
obj-$(CONFIG_IEEE802154_6LOWPAN) += 6lowpan.o
obj-$(CONFIG_6LOWPAN_IPHC) += 6lowpan_iphc.o

6lowpan-y := 6lowpan_rtnl.o reassembly.o
ieee802154-y := netlink.o nl-mac.o nl-phy.o nl_policy.o wpan-class.o \
                header_ops.o
af_802154-y := af_ieee802154.o raw.o dgram.o

ccflags-y += -D__CHECK_ENDIAN__
