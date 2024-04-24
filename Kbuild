ifeq ($(CONFIG_ARCH_KALAMA), y)
dtbo-y += kalama-audio.dtbo \
                 kalama-audio-cdp.dtbo \
                 kalama-audio-cdp-nfc.dtbo \
                 kalama-audio-wsa883x-cdp.dtbo \
                 kalama-audio-cdp-apq.dtbo \
                 kalama-audio-mtp.dtbo \
                 kalama-audio-mtp-nfc.dtbo \
                 kalama-audio-mtp-apq.dtbo \
                 kalama-audio-qrd.dtbo \
                 kalama-audio-atp.dtbo \
                 kalama-audio-rcm.dtbo \
                 kalama-audio-rumi.dtbo \
                 kalama-audio-hdk.dtbo \
                 kalama-sg-audio-hhg.dtbo \
                 somc-yodo-audio-pdx234.dtbo
endif
endif

ifeq ($(CONFIG_ARCH_CROW), y)
dtbo-y += crow-audio.dtbo \
                 crow-audio-idp.dtbo \
                 crow-audio-idp-wcd9395-aatc.dtbo \
                 crow-audio-idp-wcd9395-dmic.dtbo \
                 crow-audio-idp-wcd9395-wcd-dmic.dtbo \
                 crow-audio-qrd.dtbo \
                 crow-audio-atp.dtbo
endif

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
