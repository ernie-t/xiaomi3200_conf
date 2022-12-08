# xiaomi3200_conf
Config & Modifications


mt7615-common.ko

path: /lib/modules/5.15.80/mt7615-common.ko

perl -i -pe 's/\xf2\x54\x2c\x12/\xf2\x3c\x2c\x12/g' mt76x0-common.ko

