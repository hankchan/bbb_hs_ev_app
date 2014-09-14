bbb_hs_ev_app
=============

bbb_hs_ev_app

compile:

    dtc -O dtb -o HS-CAN-00A0.dtbo -b 0 -@ HS-CAN-00A0.dts

test:

    echo HS-CAN >/sys/devices/bone_capemgr*/slots