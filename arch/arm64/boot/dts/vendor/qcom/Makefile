ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

ifneq (,$(filter ZS670KS,$(ASUS_BUILD_PROJECT)))
		dtbo-$(CONFIG_ARCH_KONA) += \
				kona-mtp-overlay.dtbo \
                zs670ks-evb-asus-overlay.dtbo \
                zs670ks-sr-asus-overlay.dtbo \
                zs670ks-sr2-asus-overlay.dtbo \
                zs670ks-sr3-asus-overlay.dtbo \
                zs670ks-er-asus-overlay.dtbo \
                zs670ks-er2-asus-overlay.dtbo \
                zs670ks-pr-asus-overlay.dtbo \
                zs670ks-mp-asus-overlay.dtbo

kona-mtp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-evb-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-sr-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-sr2-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-sr3-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-er-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-er2-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-pr-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
zs670ks-mp-asus-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
else

ifneq (,$(filter ZS661KS,$(ASUS_BUILD_PROJECT)))

        dtbo-$(CONFIG_ARCH_KONA) += \
                ZS661KS-EVB-overlay.dtbo \
                ZS661KS-SR-overlay.dtbo \
                ZS661KS-ER-overlay.dtbo \
                ZS661KS-ER2-overlay.dtbo \
                ZS661KS-PR-overlay.dtbo \
                ZS661KS-PR2-overlay.dtbo \
                ZS661KS-MP-overlay.dtbo \

ZS661KS-EVB-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
ZS661KS-SR-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
ZS661KS-ER-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
ZS661KS-ER2-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
ZS661KS-PR-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
ZS661KS-PR2-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
ZS661KS-MP-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb

else #else ifneq (,$(filter ZS661KS,$(ASUS_BUILD_PROJECT)))
        dtbo-$(CONFIG_ARCH_KONA) += \
                kona-cdp-overlay.dtbo \
                kona-cdp-lcd-overlay.dtbo \
                kona-mtp-overlay.dtbo \
                kona-mtp-ws-overlay.dtbo \
                kona-xr-overlay.dtbo \
                kona-rumi-overlay.dtbo \
                kona-qrd-overlay.dtbo \
		kona-xrfusion-overlay.dtbo \
                kona-hdk-overlay.dtbo

kona-cdp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-cdp-lcd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-ws-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xr-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-rumi-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-qrd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrfusion-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-hdk-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
endif #endif of ifneq (,$(filter ZS661KS,$(ASUS_BUILD_PROJECT)))
endif

else #else of ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y) for CONFIG_ARCH_KONA
dtb-$(CONFIG_ARCH_KONA) += kona-rumi.dtb \
        kona-mtp.dtb \
        kona-mtp-ws.dtb \
        kona-xr.dtb \
	kona-xrfusion.dtb \
        kona-cdp.dtb \
        kona-cdp-lcd.dtb \
        kona-qrd.dtb \
        kona-v2-rumi.dtb \
        kona-v2-mtp.dtb \
        kona-v2-mtp-ws.dtb \
        kona-v2-cdp.dtb \
        kona-v2-qrd.dtb \
	kona-v2-xrfusion.dtb \
        kona-hdk.dtb \
        kona-v2.1-mtp.dtb \
        kona-v2.1-mtp-ws.dtb \
        kona-v2.1-cdp.dtb \
        kona-v2.1-qrd.dtb \
        kona-v2.1-hdk.dtb \
	kona-v2.1-xrfusion.dtb \
        qrb5165-iot-rb5.dtb \
        kona-v2.1-iot-rb5.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LITO) += lito-rumi-overlay.dtbo \
                lito-mtp-overlay.dtbo \
                lito-v2-mtp-overlay.dtbo \
                lito-cdp-overlay.dtbo \
                lito-v2-cdp-overlay.dtbo \
                lito-atp-overlay.dtbo \
                lito-v2-atp-overlay.dtbo \
                lito-v2-atp-lcd-overlay.dtbo \
                lito-qrd-overlay.dtbo \
                lito-v2-qrd-overlay.dtbo

lito-rumi-overlay.dtbo-base := lito.dtb lito-v2.dtb
lito-mtp-overlay.dtbo-base := lito.dtb
lito-v2-mtp-overlay.dtbo-base := lito-v2.dtb
lito-cdp-overlay.dtbo-base := lito.dtb
lito-v2-cdp-overlay.dtbo-base := lito-v2.dtb
lito-atp-overlay.dtbo-base := lito.dtb
lito-v2-atp-overlay.dtbo-base := lito-v2.dtb
lito-v2-atp-lcd-overlay.dtbo-base := lito-v2.dtb
lito-qrd-overlay.dtbo-base := lito.dtb
lito-v2-qrd-overlay.dtbo-base := lito-v2.dtb
else
dtb-$(CONFIG_ARCH_LITO) += lito-rumi.dtb \
                lito-mtp.dtb \
                lito-cdp.dtb \
                lito-atp.dtb \
                lito-qrd.dtb \
                lito-v2-mtp.dtb \
                lito-v2-cdp.dtb \
                lito-v2-atp.dtb \
                lito-v2-atp-lcd.dtb \
                lito-v2-qrd.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LAGOON) += \
		lagoon-rumi-overlay.dtbo \
		lagoon-mtp-overlay.dtbo \
		lagoon-mtp-usbc-overlay.dtbo \
		lagoon-cdp-overlay.dtbo \
		lagoon-atp-overlay.dtbo \
		lagoon-qrd-overlay.dtbo

lagoon-rumi-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-usbc-overlay.dtbo-base := lagoon.dtb
lagoon-cdp-overlay.dtbo-base := lagoon.dtb
lagoon-atp-overlay.dtbo-base := lagoon.dtb
lagoon-qrd-overlay.dtbo-base := lagoon.dtb
else
dtb-$(CONFIG_ARCH_LAGOON) += \
		lagoon-rumi.dtb \
		lagoon-mtp.dtb \
		lagoon-mtp-usbc.dtb \
		lagoon-cdp.dtb \
		lagoon-atp.dtb \
		lagoon-qrd.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_BENGAL) += \
                bengal-rumi-overlay.dtbo \
                bengal-qrd-overlay.dtbo \
                bengal-idp-overlay.dtbo \
                bengal-idp-usbc-overlay.dtbo \
                bengalp-idp-overlay.dtbo \
                bengal-idp-1gb-overlay.dtbo \
                bengal-idp-2gb-overlay.dtbo \
                bengal-idp-usbc-1gb-overlay.dtbo \
                bengal-idp-usbc-2gb-overlay.dtbo \
                qcm4290-iot-idp-overlay.dtbo \
                qcs4290-iot-idp-overlay.dtbo \
                qcm4290-iot-idp-1gb-overlay.dtbo \
                qcm4290-iot-idp-2gb-overlay.dtbo \
                qcm4290-iot-idp-usbc-1gb-overlay.dtbo \
                qcm4290-iot-idp-usbc-2gb-overlay.dtbo \
                qcm4290-iot-idp-usbc-overlay.dtbo

bengal-rumi-overlay.dtbo-base := bengal.dtb
bengal-qrd-overlay.dtbo-base := bengal.dtb
bengal-idp-overlay.dtbo-base := bengal.dtb
bengal-idp-usbc-overlay.dtbo-base := bengal.dtb
bengalp-idp-overlay.dtbo-base := bengalp.dtb
bengal-idp-1gb-overlay.dtbo-base := bengal-1gb.dtb
bengal-idp-2gb-overlay.dtbo-base := bengal-2gb.dtb
bengal-idp-usbc-1gb-overlay.dtbo-base := bengal-1gb.dtb
bengal-idp-usbc-2gb-overlay.dtbo-base := bengal-2gb.dtb
qcm4290-iot-idp-overlay.dtbo-base := qcm4290.dtb
qcs4290-iot-idp-overlay.dtbo-base := qcs4290.dtb
qcm4290-iot-idp-1gb-overlay.dtbo-base := qcm4290-iot-1gb.dtb
qcm4290-iot-idp-2gb-overlay.dtbo-base := qcm4290-iot-2gb.dtb
qcm4290-iot-idp-usbc-1gb-overlay.dtbo-base := qcm4290-iot-1gb.dtb
qcm4290-iot-idp-usbc-2gb-overlay.dtbo-base := qcm4290-iot-2gb.dtb
qcm4290-iot-idp-usbc-overlay.dtbo-base := qcm4290.dtb
else
dtb-$(CONFIG_ARCH_BENGAL) += bengal-rumi.dtb \
                bengal-qrd.dtb \
		bengal-idp.dtb \
		bengal-idp-usbc.dtb \
		bengalp-idp.dtb \
		bengal-idp-1gb.dtb \
		bengal-idp-2gb.dtb \
		bengal-idp-usbc-1gb.dtb \
		bengal-idp-usbc-2gb.dtb \
		qcm4290-iot-idp.dtb \
		qcs4290-iot-idp.dtb \
		qcm4290-iot-idp-1gb.dtb \
		qcm4290-iot-idp-2gb.dtb \
		qcm4290-iot-idp-usbc-1gb.dtb \
		qcm4290-iot-idp-usbc-2gb.dtb \
		qcm4290-iot-idp-usbc.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SCUBA) += \
		scuba-rumi-overlay.dtbo \
		scuba-idp-overlay.dtbo \
		scuba-idp-usbc-overlay.dtbo \
		scuba-qrd-eldo-overlay.dtbo \
		scuba-qrd-non-eldo-overlay.dtbo

scuba-rumi-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-idp-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-qrd-eldo-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-qrd-non-eldo-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-idp-usbc-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
else
dtb-$(CONFIG_ARCH_SCUBA) += scuba-rumi.dtb \
	scuba-idp.dtb \
	scuba-idp-usbc.dtb \
	scuba-qrd-eldo.dtb \
	scuba-qrd-non-eldo.dtb \
	scubap-idp.dtb \
	scubap-idp-2gb.dtb \
	scuba-idp-2gb.dtb \
	scuba-idp-usbc-2gb.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
