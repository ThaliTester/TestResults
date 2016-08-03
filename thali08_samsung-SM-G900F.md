#### Test 79689775e33639d_thali08_samsung-SM-G900F Logs


```
--------- beginning of main
,08-03 17:29:08.032  1544  1544 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
08-03 17:29:08.042   304  1137 D Netd    : Iface wlan0 link up
08-03 17:29:08.062   773   860 D Tethering: interfaceLinkStateChanged wlan0, true
08-03 17:29:08.062   773   860 D Tethering: interfaceStatusChanged wlan0, true
08-03 17:29:08.071  1544  1544 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
--------- beginning of system
08-03 17:29:08.081   773  1323 D WifiP2pService: InactiveState{ what=147461 }
08-03 17:29:08.091   773  1323 D WifiP2pService: P2pEnabledState{ what=147461 }
08-03 17:29:08.091   773  1323 D WifiP2pService: DefaultState{ what=147461 }
08-03 17:29:08.221   773   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e29e2b9 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{552f6f3 1381:com.android.systemui/u0a58}
08-03 17:29:09.011  2307  2307 E audit   : type=1400 msg=audit(1470238149.011:285): avc:  denied  { execmod } for  pid=7120 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-03 17:29:09.011  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:09.011  2307  2307 E audit   : type=1300 msg=audit(1470238149.011:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe2000 a1=51000 a2=5 a3=4 items=0 ppid=3541 ppcomm=adbd pid=7120 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-03 17:29:09.011  2307  2307 E audit   : type=1327 msg=audit(1470238149.011:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-03 17:29:09.011  2307  2307 E audit   : type=1320 msg=audit(1470238149.011:285): 
08-03 17:29:09.071  2307  2307 E audit   : type=1400 msg=audit(1470238149.071:286): avc:  denied  { execmod } for  pid=7120 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-03 17:29:09.071  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:09.071  2307  2307 E audit   : type=1300 msg=audit(1470238149.071:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa2000 a1=51000 a2=5 a3=4 items=0 ppid=3541 ppcomm=adbd pid=7120 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-03 17:29:09.071  2307  2307 E audit   : type=1327 msg=audit(1470238149.071:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-03 17:29:09.071  2307  2307 E audit   : type=1320 msg=audit(1470238149.071:286): 
08-03 17:29:09.121  7120  7120 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 17:29:09.121  2307  2307 E audit   : type=1400 msg=audit(1470238149.121:287): avc:  denied  { execmod } for  pid=7120 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-03 17:29:09.121  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:09.121  2307  2307 E audit   : type=1300 msg=audit(1470238149.121:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa2000 a1=51000 a2=5 a3=4 items=0 ppid=3541 ppcomm=adbd pid=7120 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-03 17:29:09.121  2307  2307 E audit   : type=1327 msg=audit(1470238149.121:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-03 17:29:09.121  7120  7120 D AndroidRuntime: CheckJNI is OFF
08-03 17:29:09.131  7120  7120 D AndroidRuntime: readGMSProperty: start
08-03 17:29:09.131  7120  7120 D AndroidRuntime: readGMSProperty: already setted!!
08-03 17:29:09.131  7120  7120 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-03 17:29:09.131  7120  7120 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-03 17:29:09.131  7120  7120 D AndroidRuntime: readGMSProperty: end
08-03 17:29:09.131  7120  7120 D AndroidRuntime: addProductProperty: start
08-03 17:29:09.131  2307  2307 E audit   : type=1320 msg=audit(1470238149.121:287): 
08-03 17:29:09.131  7120  7120 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-03 17:29:09.131  7120  7120 W art     : aee09000-b1d2f000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-03 17:29:09.131  7120  7120 W art     : b1d2f000-b3f9e000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-03 17:29:09.131  7120  7120 W art     : b3f9e000-b3f9f000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-03 17:29:09.131  7120  7120 W art     : b3f9f000-b3fa0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.131  7120  7120 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-03 17:29:09.131  7120  7120 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-03 17:29:09.131  7120  7120 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-03 17:29:09.131  7120  7120 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-03 17:29:09.131  7120  7120 W art     : b484a000-b4873000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-03 17:29:09.131  7120  7120 W art     : b4873000-b4876000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-03 17:29:09.131  7120  7120 W art     : b4876000-b4877000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-03 17:29:09.131  7120  7120 W art     : b4877000-b4878000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-03 17:29:09.131  7120  7120 W art     : b4878000-b4879000 r--p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b4879000-b4899000 r--s 00000000 00:0b 6712       /dev/__properties__
08-03 17:29:09.131  7120  7120 W art     : b4899000-b52aa000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-03 17:29:09.131  7120  7120 W art     : b52aa000-b52ab000 ---p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b52ab000-b52f4000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-03 17:29:09.131  7120  7120 W art     : b52f4000-b52f5000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-03 17:29:09.131  7120  7120 W art     : b52f5000-b52fd000 rw-p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b52fd000-b52fe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.131  7120  7120 W art     : b52fe000-b5333000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-03 17:29:09.131  7120  7120 W art     : b5333000-b5334000 ---p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b5334000-b5335000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-03 17:29:09.131  7120  7120 W art     : b5335000-b5336000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-03 17:29:09.131  7120  7120 W art     : b5336000-b538e000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-03 17:29:09.131  7120  7120 W art     : b538e000-b538f000 ---p 00000000 00:00 0 
08-03 17:29:09.131  7120  7120 W art     : b538f000-b5390000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-03 17:29:09.131  7120  7120 W art     : b5390000-b5391000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-03 17:29:09.141  7120  7120 W art     : b5392000-b5398000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-03 17:29:09.141  7120  7120 W art     : b5398000-b5399000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-03 17:29:09.141  7120  7120 W art     : b5399000-b539a000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-03 17:29:09.141  7120  7120 W art     : b539a000-b539c000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b539d000-b53a7000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-03 17:29:09.141  7120  7120 W art     : b53a7000-b53aa000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-03 17:29:09.141  7120  7120 W art     : b53aa000-b53ab000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-03 17:29:09.141  7120  7120 W art     : b53ac000-b53c3000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-03 17:29:09.141  7120  7120 W art     : b53c3000-b53c4000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b53c4000-b53c5000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-03 17:29:09.141  7120  7120 W art     : b53c5000-b53c6000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-03 17:29:09.141  7120  7120 W art     : b53c7000-b53d1000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-03 17:29:09.141  7120  7120 W art     : b53d1000-b53d2000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-03 17:29:09.141  7120  7120 W art     : b53d2000-b53d3000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-03 17:29:09.141  7120  7120 W art     : b53d3000-b53d7000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-03 17:29:09.141  7120  7120 W art     : b53d7000-b53d8000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-03 17:29:09.141  7120  7120 W art     : b53d8000-b53d9000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-03 17:29:09.141  7120  7120 W art     : b53d9000-b53ef000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-03 17:29:09.141  7120  7120 W art     : b53ef000-b53f0000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-03 17:29:09.141  7120  7120 W art     : b53f0000-b53f1000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-03 17:29:09.141  7120  7120 W art     : b53f1000-b53fe000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-03 17:29:09.141  7120  7120 W art     : b53fe000-b53ff000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-03 17:29:09.141  7120  7120 W art     : b53ff000-b5400000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-03 17:29:09.141  7120  7120 W art     : b5400000-b5460000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-03 17:29:09.141  7120  7120 W art     : b5460000-b5463000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-03 17:29:09.141  7120  7120 W art     : b5463000-b5467000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5467000-b54c8000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-03 17:29:09.141  7120  7120 W art     : b54c8000-b54c9000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-03 17:29:09.141  7120  7120 W art     : b54c9000-b5518000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-03 17:29:09.141  7120  7120 W art     : b5518000-b551a000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-03 17:29:09.141  7120  7120 W art     : b551a000-b551b000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-03 17:29:09.141  7120  7120 W art     : b551b000-b551c000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b551c000-b5523000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-03 17:29:09.141  7120  7120 W art     : b5523000-b5524000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-03 17:29:09.141  7120  7120 W art     : b5524000-b5525000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-03 17:29:09.141  7120  7120 W art     : avc_common.so
08-03 17:29:09.141  7120  7120 W art     : b5526000-b5529000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-03 17:29:09.141  7120  7120 W art     : b5529000-b552a000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-03 17:29:09.141  7120  7120 W art     : b552a000-b552b000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-03 17:29:09.141  7120  7120 W art     : enc_common.so
08-03 17:29:09.141  7120  7120 W art     : b552c000-b5530000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-03 17:29:09.141  7120  7120 W art     : b5530000-b5531000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5531000-b5532000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-03 17:29:09.141  7120  7120 W art     : b5532000-b5533000 rw-p 00005000 b3:17 2510       /syste
08-03 17:29:09.141  7120  7120 W art     : m/lib/libpowermanager.so
08-03 17:29:09.141  7120  7120 W art     : b5534000-b5551000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-03 17:29:09.141  7120  7120 W art     : b5551000-b5552000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-03 17:29:09.141  7120  7120 W art     : b5552000-b5553000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-03 17:29:09.141  7120  7120 W art     : b5554000-b5559000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-03 17:29:09.141  7120  7120 W art     : b5559000-b555a000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-03 17:29:09.141  7120  7120 W art     : b555a000-b555b000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-03 17:29:09.141  7120  7120 W art     : b555c000-b558d000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-03 17:29:09.141  7120  7120 W art     : b558d000-b5590000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-03 17:29:09.141  7120  7120 W art     : b5590000-b5591000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-03 17:29:09.141  7120  7120 W art     : b5592000-b55cd000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-03 17:29:09.141  7120  7120 W art     : b55cd000-b55ce000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-03 17:29:09.141  7120  7120 W art     : b55ce000-b55cf000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-03 17:29:09.141  7120  7120 W art     : b55d0000-b55d7000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-03 17:29:09.141  7120  7120 W art     : b55d7000-b55d8000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b55d8000-b55d9000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-03 17:29:09.141  7120  7120 W art     : b55d9000-b55da000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-03 17:29:09.141  7120  7120 W art     : b55da000-b55db000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b55db000-b55f2000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-03 17:29:09.141  7120  7120 W art     : b55f2000-b55f3000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b55f3000-b55f6000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-03 17:29:09.141  7120  7120 W art     : b55f6000-b55f7000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-03 17:29:09.141  7120  7120 W art     : b55f7000-b5616000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-03 17:29:09.141  7120  7120 W art     : b5616000-b5617000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-03 17:29:09.141  7120  7120 W art     : b5617000-b5618000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-03 17:29:09.141  7120  7120 W art     : b5618000-b5656000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-03 17:29:09.141  7120  7120 W art     : b5656000-b5657000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5657000-b5659000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-03 17:29:09.141  7120  7120 W art     : b5659000-b565a000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-03 17:29:09.141  7120  7120 W art     : b565b000-b5662000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-03 17:29:09.141  7120  7120 W art     : b5662000-b5663000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-03 17:29:09.141  7120  7120 W art     : b5663000-b5664000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-03 17:29:09.141  7120  7120 W art     : b5665000-b5668000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-03 17:29:09.141  7120  7120 W art     : b5668000-b5669000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-03 17:29:09.141  7120  7120 W art     : b5669000-b566a000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-03 17:29:09.141  7120  7120 W art     : b566a000-b5670000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-03 17:29:09.141  7120  7120 W art     : b5670000-b5671000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5671000-b5672000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-03 17:29:09.141  7120  7120 W art     : b5672000-b5673000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-03 17:29:09.141  7120  7120 W art     : b5673000-b567c000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-03 17:29:09.141  7120  7120 W art     : b567c000-b567d000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-03 17:29:09.141  7120  7120 W art     : b567d000-b567e000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-03 17:29:09.141  7120  7120 W art     : b567e000-b570f000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-03 17:29:09.141  7120  7120 W art     : b570f000-b5710000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5710000-b571b000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-03 17:29:09.141  7120  7120 W art     : b571b000-b571c000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-03 17:29:09.141  7120  7120 W art     : b571d000-b572f000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-03 17:29:09.141  7120  7120 W art     : b572f000-b5730000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-03 17:29:09.141  7120  7120 W art     : b5730000-b5731000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-03 17:29:09.141  7120  7120 W art     : b5732000-b5737000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-03 17:29:09.141  7120  7120 W art     : b5737000-b5738000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-03 17:29:09.141  7120  7120 W art     : b5738000-b5739000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-03 17:29:09.141  7120  7120 W art     : b573a000-b57a7000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-03 17:29:09.141  7120  7120 W art     : b57a7000-b57a8000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b57a8000-b57aa000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-03 17:29:09.141  7120  7120 W art     : b57aa000-b57ab000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-03 17:29:09.141  7120  7120 W art     : b57ab000-b57ac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b57ac000-b57b3000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-03 17:29:09.141  7120  7120 W art     : b57b3000-b57b4000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-03 17:29:09.141  7120  7120 W art     : b57b4000-b57b5000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-03 17:29:09.141  7120  7120 W art     : b57b6000-b5836000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-03 17:29:09.141  7120  7120 W art     : b5836000-b5837000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5837000-b5838000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-03 17:29:09.141  7120  7120 W art     : b5838000-b5839000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-03 17:29:09.141  7120  7120 W art     : b5839000-b5850000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5850000-b5887000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-03 17:29:09.141  7120  7120 W art     : ib/libqc-opt.so
08-03 17:29:09.141  7120  7120 W art     : b5887000-b5888000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-03 17:29:09.141  7120  7120 W art     : b5888000-b5889000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-03 17:29:09.141  7120  7120 W art     : b5889000-b58a5000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-03 17:29:09.141  7120  7120 W art     : b58a5000-b58a6000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-03 17:29:09.141  7120  7120 W art     : b58a6000-b58a7000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-03 17:29:09.141  7120  7120 W art     : b58a8000-b5909000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-03 17:29:09.141  7120  7120 W art     : b5909000-b590b000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-03 17:29:09.141  7120  7120 W art     : b590b000-b590c000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-03 17:29:09.141  7120  7120 W art     : b590d000-b5934000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-03 17:29:09.141  7120  7120 W art     : b5934000-b5935000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5935000-b5936000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-03 17:29:09.141  7120  7120 W art     : b5936000-b5937000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-03 17:29:09.141  7120  7120 W art     : b5938000-b5940000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-03 17:29:09.141  7120  7120 W art     : b5940000-b5942000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-03 17:29:09.141  7120  7120 W art     : b5942000-b5943000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-03 17:29:09.141  7120  7120 W art     : b5944000-b5947000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-03 17:29:09.141  7120  7120 W art     : b5947000-b5948000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-03 17:29:09.141  7120  7120 W art     : b5948000-b5949000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-03 17:29:09.141  7120  7120 W art     : b5949000-b594d000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-03 17:29:09.141  7120  7120 W art     : b594d000-b594e000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b594e000-b594f000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-03 17:29:09.141  7120  7120 W art     : b594f000-b5950000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-03 17:29:09.141  7120  7120 W art     : b5950000-b5960000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-03 17:29:09.141  7120  7120 W art     : b5960000-b5961000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-03 17:29:09.141  7120  7120 W art     : b5961000-b5962000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-03 17:29:09.141  7120  7120 W art     : b5962000-b59a8000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b59a8000-b59b1000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-03 17:29:09.141  7120  7120 W art     : b59b1000-b59b2000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-03 17:29:09.141  7120  7120 W art     : b59b2000-b59b3000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-03 17:29:09.141  7120  7120 W art     : b59b4000-b59b9000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-03 17:29:09.141  7120  7120 W art     : b59b9000-b59ba000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-03 17:29:09.141  7120  7120 W art     : b59ba000-b59bb000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-03 17:29:09.141  7120  7120 W art     : b59bb000-b59be000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-03 17:29:09.141  7120  7120 W art     : b59be000-b59bf000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b59bf000-b59c0000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-03 17:29:09.141  7120  7120 W art     : b59c0000-b59c1000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-03 17:29:09.141  7120  7120 W art     : b59c2000-b59da000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-03 17:29:09.141  7120  7120 W art     : b59da000-b59db000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b59db000-b59dc000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-03 17:29:09.141  7120  7120 W art     : b59dc000-b59dd000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-03 17:29:09.141  7120  7120 W art     : b59de000-b5b78000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-03 17:29:09.141  7120  7120 W art     : b5b78000-b5b79000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5b79000-b5b86000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-03 17:29:09.141  7120  7120 W art     : b5b86000-b5b87000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-03 17:29:09.141  7120  7120 W art     : b5b87000-b5b8b000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-03 17:29:09.141  7120  7120 W art     : b5b8b000-b5b8c000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5b8c000-b5b8d000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-03 17:29:09.141  7120  7120 W art     : b5b8d000-b5b8e000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-03 17:29:09.141  7120  7120 W art     : b5b8e000-b5ba1000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-03 17:29:09.141  7120  7120 W art     : b5ba1000-b5ba2000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-03 17:29:09.141  7120  7120 W art     : b5ba2000-b5ba3000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-03 17:29:09.141  7120  7120 W art     : b5ba3000-b5ba4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:09.141  7120  7120 W art     : b5ba4000-b5bef000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-03 17:29:09.141  7120  7120 W art     : b5bef000-b5bf0000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-03 17:29:09.141  7120  7120 W art     : b5bf0000-b5bf1000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-03 17:29:09.141  7120  7120 W art     : b5bf1000-b5bf3000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5bf4000-b5c05000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-03 17:29:09.141  7120  7120 W art     : b5c05000-b5c06000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5c06000-b5c07000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-03 17:29:09.141  7120  7120 W art     : b5c07000-b5c08000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-03 17:29:09.141  7120  7120 W art     : b5c09000-b5c13000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-03 17:29:09.141  7120  7120 W art     : b5c13000-b5c15000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-03 17:29:09.141  7120  7120 W art     : b5c15000-b5c16000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-03 17:29:09.141  7120  7120 W art     : b5c16000-b5c2f000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-03 17:29:09.141  7120  7120 W art     : b5c2f000-b5c30000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-03 17:29:09.141  7120  7120 W art     : b5c30000-b5c33000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-03 17:29:09.141  7120  7120 W art     : b5c33000-b5c37000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5c37000-b5cab000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-03 17:29:09.141  7120  7120 W art     : b5cab000-b5cac000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5cac000-b5caf000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-03 17:29:09.141  7120  7120 W art     : b5caf000-b5cb0000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-03 17:29:09.141  7120  7120 W art     : b5cb0000-b5cb1000 r--p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5cb1000-b5cb4000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-03 17:29:09.141  7120  7120 W art     : b5cb4000-b5cb5000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-03 17:29:09.141  7120  7120 W art     : b5cb5000-b5cb6000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-03 17:29:09.141  7120  7120 W art     : b5cb6000-b5cb7000 r--p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5cb7000-b5cbc000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-03 17:29:09.141  7120  7120 W art     : b5cbc000-b5cbd000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-03 17:29:09.141  7120  7120 W art     : b5cbd000-b5cbe000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-03 17:29:09.141  7120  7120 W art     : b5cbe000-b5cbf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b5cbf000-b5cc2000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-03 17:29:09.141  7120  7120 W art     : b5cc2000-b5cc3000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-03 17:29:09.141  7120  7120 W art     : b5cc3000-b5cc4000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-03 17:29:09.141  7120  7120 W art     : b5cc4000-b5cc5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b5cc5000-b5cc9000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-03 17:29:09.141  7120  7120 W art     : b5cc9000-b5cca000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-03 17:29:09.141  7120  7120 W art     : b5cca000-b5ccb000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-03 17:29:09.141  7120  7120 W art     : b5ccb000-b5ccc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:09.141  7120  7120 W art     : b5ccc000-b5cd0000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-03 17:29:09.141  7120  7120 W art     : b5cd0000-b5cd1000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-03 17:29:09.141  7120  7120 W art     : b5cd1000-b5cd2000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-03 17:29:09.141  7120  7120 W art     : b5cd2000-b5cd3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b5cd3000-b5ce1000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-03 17:29:09.141  7120  7120 W art     : b5ce1000-b5ce2000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b5ce2000-b5ce3000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-03 17:29:09.141  7120  7120 W art     : b5ce3000-b5ce4000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-03 17:29:09.141  7120  7120 W art     : b5ce4000-b5cee000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-03 17:29:09.141  7120  7120 W art     : b5cee000-b5cf1000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-03 17:29:09.141  7120  7120 W art     : b5cf1000-b5cf2000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-03 17:29:09.141  7120  7120 W art     : b5cf2000-b5cf3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b5cf3000-b5cfd000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-03 17:29:09.141  7120  7120 W art     : b5cfd000-b5d00000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-03 17:29:09.141  7120  7120 W art     : b5d00000-b5d01000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-03 17:29:09.141  7120  7120 W art     : b5d01000-b5d05000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-03 17:29:09.141  7120  7120 W art     : b5d05000-b5d06000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-03 17:29:09.141  7120  7120 W art     : b5d06000-b5d07000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-03 17:29:09.141  7120  7120 W art     : b5d07000-b5d08000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b5d08000-b5d15000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-03 17:29:09.141  7120  7120 W art     : b5d15000-b5d17000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-03 17:29:09.141  7120  7120 W art     : b5d17000-b5d18000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-03 17:29:09.141  7120  7120 W art     : b5d18000-b612a000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-03 17:29:09.141  7120  7120 W art     : b612a000-b612b000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b612b000-b6134000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-03 17:29:09.141  7120  7120 W art     : b6134000-b6138000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-03 17:29:09.141  7120  7120 W art     : b6138000-b6139000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6139000-b6140000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-03 17:29:09.141  7120  7120 W art     : b6140000-b6141000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-03 17:29:09.141  7120  7120 W art     : b6141000-b6142000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-03 17:29:09.141  7120  7120 W art     : b6142000-b6143000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b6143000-b615e000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-03 17:29:09.141  7120  7120 W art     : b615e000-b615f000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-03 17:29:09.141  7120  7120 W art     : b615f000-b6160000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-03 17:29:09.141  7120  7120 W art     : b6160000-b6161000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b6161000-b61ad000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-03 17:29:09.141  7120  7120 W art     : b61ad000-b61ae000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b61ae000-b61af000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-03 17:29:09.141  7120  7120 W art     : b61af000-b61b0000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-03 17:29:09.141  7120  7120 W art     : b61b0000-b61b1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b61b1000-b61b5000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-03 17:29:09.141  7120  7120 W art     : b61b5000-b61b6000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b61b6000-b61b7000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-03 17:29:09.141  7120  7120 W art     : b61b7000-b61b8000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-03 17:29:09.141  7120  7120 W art     : b61b8000-b61f0000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-03 17:29:09.141  7120  7120 W art     : b61f0000-b61f1000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-03 17:29:09.141  7120  7120 W art     : b61f1000-b61f2000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-03 17:29:09.141  7120  7120 W art     : b61f2000-b61f3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.141  7120  7120 W art     : b61f3000-b6291000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-03 17:29:09.141  7120  7120 W art     : b6291000-b6292000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6292000-b62b0000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-03 17:29:09.141  7120  7120 W art     : b62b0000-b62b1000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-03 17:29:09.141  7120  7120 W art     : b62b1000-b6424000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-03 17:29:09.141  7120  7120 W art     : b6424000-b642f000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-03 17:29:09.141  7120  7120 W art     : b642f000-b6430000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-03 17:29:09.141  7120  7120 W art     : b6430000-b6547000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-03 17:29:09.141  7120  7120 W art     : b6547000-b6552000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-03 17:29:09.141  7120  7120 W art     : b6552000-b6553000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-03 17:29:09.141  7120  7120 W art     : b6553000-b6557000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6557000-b657b000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-03 17:29:09.141  7120  7120 W art     : b657b000-b657d000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-03 17:29:09.141  7120  7120 W art     : b657d000-b657e000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-03 17:29:09.141  7120  7120 W art     : b657e000-b6624000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-03 17:29:09.141  7120  7120 W art     : b6624000-b6631000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-03 17:29:09.141  7120  7120 W art     : b6631000-b6632000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-03 17:29:09.141  7120  7120 W art     : b6632000-b6633000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6633000-b6686000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-03 17:29:09.141  7120  7120 W art     : b6686000-b6687000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6687000-b6688000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-03 17:29:09.141  7120  7120 W art     : b6688000-b6689000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-03 17:29:09.141  7120  7120 W art     : b6689000-b668e000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b668e000-b66a0000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-03 17:29:09.141  7120  7120 W art     : b66a0000-b66a1000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b66a1000-b66a2000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-03 17:29:09.141  7120  7120 W art     : b66a2000-b66a3000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-03 17:29:09.141  7120  7120 W art     : b66a3000-b66aa000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-03 17:29:09.141  7120  7120 W art     : b66aa000-b66ab000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-03 17:29:09.141  7120  7120 W art     : b66ab000-b66ac000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-03 17:29:09.141  7120  7120 W art     : b66ac000-b66ad000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b66ad000-b66b0000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-03 17:29:09.141  7120  7120 W art     : b66b0000-b66b1000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-03 17:29:09.141  7120  7120 W art     : b66b1000-b66b2000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-03 17:29:09.141  7120  7120 W art     : b66b2000-b66b6000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-03 17:29:09.141  7120  7120 W art     : b66b6000-b66b7000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-03 17:29:09.141  7120  7120 W art     : b66b7000-b66b8000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-03 17:29:09.141  7120  7120 W art     : b66b8000-b66c6000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-03 17:29:09.141  7120  7120 W art     : b66c6000-b66c7000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b66c7000-b66c8000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-03 17:29:09.141  7120  7120 W art     : b66c8000-b66c9000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-03 17:29:09.141  7120  7120 W art     : b66c9000-b66d2000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-03 17:29:09.141  7120  7120 W art     : b66d2000-b66d3000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-03 17:29:09.141  7120  7120 W art     : b66d3000-b66d4000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-03 17:29:09.141  7120  7120 W art     : b66d4000-b673a000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-03 17:29:09.141  7120  7120 W art     : b673a000-b673b000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b673b000-b673d000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-03 17:29:09.141  7120  7120 W art     : b673d000-b6746000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-03 17:29:09.141  7120  7120 W art     : b6746000-b6749000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6749000-b67e0000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-03 17:29:09.141  7120  7120 W art     : b67e0000-b67e2000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-03 17:29:09.141  7120  7120 W art     : b67e2000-b67e3000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-03 17:29:09.141  7120  7120 W art     : b67e3000-b67e4000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b67e4000-b6b05000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-03 17:29:09.141  7120  7120 W art     : b6b05000-b6b06000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6b06000-b6b21000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-03 17:29:09.141  7120  7120 W art     : b6b21000-b6b25000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-03 17:29:09.141  7120  7120 W art     : b6b25000-b6b2a000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6b2a000-b6b32000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-03 17:29:09.141  7120  7120 W art     : b6b32000-b6b33000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-03 17:29:09.141  7120  7120 W art     : b6b33000-b6b34000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-03 17:29:09.141  7120  7120 W art     : b6b34000-b6b62000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-03 17:29:09.141  7120  7120 W art     : b6b62000-b6b63000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6b63000-b6b6a000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-03 17:29:09.141  7120  7120 W art     : b6b6a000-b6b6b000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-03 17:29:09.141  7120  7120 W art     : b6b6b000-b6bb1000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-03 17:29:09.141  7120  7120 W art     : b6bb1000-b6bb2000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6bb2000-b6bb5000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-03 17:29:09.141  7120  7120 W art     : b6bb5000-b6bb6000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-03 17:29:09.141  7120  7120 W art     : b6bb6000-b6bd1000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-03 17:29:09.141  7120  7120 W art     : b6bd1000-b6bd5000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-03 17:29:09.141  7120  7120 W art     : b6bd5000-b6bd6000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-03 17:29:09.141  7120  7120 W art     : b6bd6000-b6c23000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-03 17:29:09.141  7120  7120 W art     : b6c23000-b6c24000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6c24000-b6c30000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-03 17:29:09.141  7120  7120 W art     : b6c30000-b6c31000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-03 17:29:09.141  7120  7120 W art     : b6c31000-b6c3e000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-03 17:29:09.141  7120  7120 W art     : b6c3e000-b6c3f000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6c3f000-b6c40000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-03 17:29:09.141  7120  7120 W art     : b6c40000-b6c41000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-03 17:29:09.141  7120  7120 W art     : b6c41000-b6c49000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-03 17:29:09.141  7120  7120 W art     : b6c49000-b6c4a000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6c4a000-b6c4b000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-03 17:29:09.141  7120  7120 W art     : b6c4b000-b6c4c000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-03 17:29:09.141  7120  7120 W art     : b6c4c000-b6c53000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-03 17:29:09.141  7120  7120 W art     : b6c53000-b6c54000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-03 17:29:09.141  7120  7120 W art     : b6c54000-b6c55000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-03 17:29:09.141  7120  7120 W art     : b6c55000-b6c69000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-03 17:29:09.141  7120  7120 W art     : b6c69000-b6c6b000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-03 17:29:09.141  7120  7120 W art     : b6c6b000-b6c6c000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-03 17:29:09.141  7120  7120 W art     : b6c6c000-b6c94000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-03 17:29:09.141  7120  7120 W art     : b6c94000-b6c96000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-03 17:29:09.141  7120  7120 W art     : b6c96000-b6c97000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-03 17:29:09.141  7120  7120 W art     : b6c97000-b6c9a000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-03 17:29:09.141  7120  7120 W art     : b6c9a000-b6c9b000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-03 17:29:09.141  7120  7120 W art     : b6c9b000-b6c9c000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-03 17:29:09.141  7120  7120 W art     : b6c9c000-b6ca5000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-03 17:29:09.141  7120  7120 W art     : b6ca5000-b6ca6000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-03 17:29:09.141  7120  7120 W art     : b6ca6000-b6ca7000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-03 17:29:09.141  7120  7120 W art     : b6ca7000-b6cc7000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-03 17:29:09.141  7120  7120 W art     : b6cc7000-b6cc8000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-03 17:29:09.141  7120  7120 W art     : b6cc8000-b6cc9000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-03 17:29:09.141  7120  7120 W art     : b6cc9000-b6d3c000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-03 17:29:09.141  7120  7120 W art     : b6d3c000-b6d40000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-03 17:29:09.141  7120  7120 W art     : b6d40000-b6d43000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-03 17:29:09.141  7120  7120 W art     : b6d43000-b6d4d000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6d4d000-b6dd5000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-03 17:29:09.141  7120  7120 W art     : b6dd5000-b6dd6000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6dd6000-b6dda000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-03 17:29:09.141  7120  7120 W art     : b6dda000-b6ddb000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-03 17:29:09.141  7120  7120 W art     : b6ddb000-b6ddc000 rw-p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6ddc000-b6e05000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-03 17:29:09.141  7120  7120 W art     : b6e05000-b6e06000 ---p 00000000 00:00 0 
08-03 17:29:09.141  7120  7120 W art     : b6e06000-b6e09000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-03 17:29:09.141  7120  7120 W art     : b6e09000-b6e0a000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-03 17:29:09.151  7120  7120 W art     : b6e0a000-b6ee4000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-03 17:29:09.151  7120  7120 W art     : b6ee4000-b6eeb000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-03 17:29:09.151  7120  7120 W art     : b6eeb000-b6ef3000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-03 17:29:09.151  7120  7120 W art     : b6ef3000-b6ef4000 rw-p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6ef4000-b6ef5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:09.151  7120  7120 W art     : b6ef5000-b6ef6000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-03 17:29:09.151  7120  7120 W art     : b6ef6000-b6ef7000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.151  7120  7120 W art     : b6ef7000-b6efa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.151  7120  7120 W art     : b6efa000-b6f1f000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-03 17:29:09.151  7120  7120 W art     : b6f1f000-b6f20000 ---p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6f20000-b6f27000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-03 17:29:09.151  7120  7120 W art     : b6f27000-b6f28000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-03 17:29:09.151  7120  7120 W art     : b6f28000-b6f2f000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-03 17:29:09.151  7120  7120 W art     : b6f2f000-b6f30000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-03 17:29:09.151  7120  7120 W art     : b6f30000-b6f31000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-03 17:29:09.151  7120  7120 W art     : b6f31000-b6f32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.151  7120  7120 W art     : b6f32000-b6f4a000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-03 17:29:09.151  7120  7120 W art     : b6f4a000-b6f4b000 ---p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6f4b000-b6f4c000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-03 17:29:09.151  7120  7120 W art     : b6f4c000-b6f4d000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-03 17:29:09.151  7120  7120 W art     : b6f4d000-b6f5b000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-03 17:29:09.151  7120  7120 W art     : b6f5b000-b6f5c000 ---p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6f5c000-b6f5d000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-03 17:29:09.151  7120  7120 W art     : b6f5d000-b6f5e000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-03 17:29:09.151  7120  7120 W art     : b6f5e000-b6f5f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:09.151  7120  7120 W art     : b6f5f000-b6f61000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.151  7120  7120 W art     : b6f61000-b6f62000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.151  7120  7120 W art     : b6f62000-b6f63000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:09.151  7120  7120 W art     : b6f63000-b6f64000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-03 17:29:09.151  7120  7120 W art     : b6f64000-b6f65000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:09.151  7120  7120 W art     : b6f65000-b6f85000 r--s 00000000 00:0b 6712       /dev/__properties__
08-03 17:29:09.151  7120  7120 W art     : b6f85000-b6f86000 r--p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6f86000-b6f87000 ---p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6f87000-b6f89000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-03 17:29:09.151  7120  7120 W art     : b6f89000-b6f8a000 r-xp 00000000 00:00 0          [sigpage]
08-03 17:29:09.151  7120  7120 W art     : b6f8a000-b6fa5000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-03 17:29:09.151  7120  7120 W art     : b6fa5000-b6fa6000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-03 17:29:09.151  7120  7120 W art     : b6fa6000-b6fa8000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-03 17:29:09.151  7120  7120 W art     : b6fa8000-b6faa000 rw-p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : b6faa000-b6faf000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-03 17:29:09.151  7120  7120 W art     : b6faf000-b6fb0000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-03 17:29:09.151  7120  7120 W art     : b6fb0000-b6fb1000 rw-p 00000000 00:00 0 
08-03 17:29:09.151  7120  7120 W art     : bef54000-bef75000 rw-p 00000000 00:00 0          [stack]
08-03 17:29:09.151  7120  7120 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-03 17:29:09.211  7120  7120 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 17:29:09.261  7120  7120 I Radio-JNI: register_android_hardware_Radio DONE
08-03 17:29:09.271  7120  7120 E AffinityControl: AffinityControl: registerfunction enter
08-03 17:29:09.291  7120  7120 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 17:29:09.301   773  1203 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-03 17:29:09.321   773  1203 D ActivityManager: mDVFSHelper.acquire()
08-03 17:29:09.331   773  1203 V WindowManager: addAppToken: AppWindowToken{17650ac token=Token{7f5e5f ActivityRecord{f0016fe u0 com.test.thalitest/.MainActivity t115}}} to stack=1 task=115 at 0
08-03 17:29:09.341   773   903 D SecWifiDisplayUtil: Metadata value : none
08-03 17:29:09.341   773   903 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6200944 V.E...... R.....ID 0,0-0,0}
08-03 17:29:09.341   773   903 D ISSUE_DEBUG: InputChannelName : 19acb62 Starting com.test.thalitest
08-03 17:29:09.341  7135  7135 E Zygote  : v2
08-03 17:29:09.341  7135  7135 I libpersona: KNOX_SDCARD checking this for 10004
08-03 17:29:09.341  7135  7135 I libpersona: KNOX_SDCARD not a persona
08-03 17:29:09.341  7135  7135 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-03 17:29:09.341   773  1203 I ActivityManager: Start proc 7135:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-03 17:29:09.341  7135  7135 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:09.341   773  1203 D InputDispatcher: Focused application set to: xxxx
08-03 17:29:09.351  7135  7135 E Zygote  : accessInfo : 0
08-03 17:29:09.351   773  1203 D InputDispatcher: Focus left window: 3467
08-03 17:29:09.351  7120  7120 D AndroidRuntime: Shutting down VM
08-03 17:29:09.351   773  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-03 17:29:09.351  7135  7135 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-03 17:29:09.351   773   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3bd8ca4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-03 17:29:09.351  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-03 17:29:09.361   293   293 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
08-03 17:29:09.381  7135  7135 D TimaKeyStoreProvider: TimaSignature is unavailable
08-03 17:29:09.381  7135  7135 D ActivityThread: Added TimaKeyStore provider
08-03 17:29:09.381   773   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-03 17:29:09.381   773   791 V WindowOrientationListener: setCurrentAppOrientation :-1
08-03 17:29:09.381   773   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:09.381   773   791 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-03 17:29:09.381   773   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-03 17:29:09.381   773   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-03 17:29:09.381   773   903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-03 17:29:09.381   773   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{19acb62 u0 d0 Starting com.test.thalitest}
08-03 17:29:09.391  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-03 17:29:09.391   773   791 D ActivityManager:  Launching com.test.thalitest, updated priority
08-03 17:29:09.401   773   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-03 17:29:09.421  1692  1860 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-03 17:29:09.421  1692  1692 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-03 17:29:09.431   293   373 I SurfaceFlinger: id=15 Removed VSBConnecti (5/11)
08-03 17:29:09.431   293  1789 I SurfaceFlinger: id=15 Removed VSBConnecti (-2/11)
08-03 17:29:09.431   293  1789 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
08-03 17:29:09.431   293  1789 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
08-03 17:29:09.441   773   903 V WindowStateAnimator: Finishing drawing window Window{19acb62 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-03 17:29:09.441   293   373 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
08-03 17:29:09.441   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
08-03 17:29:09.441   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
08-03 17:29:09.441   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8f7364
08-03 17:29:09.441   293  5977 D libEGL  : eglTerminate EGLDisplay = 0xb454e64c
08-03 17:29:09.451   293  1789 I SurfaceFlinger: id=14 Removed VSBConnecti (5/9)
08-03 17:29:09.451   293   373 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/9)
08-03 17:29:09.451  3467  3467 V ActivityThread: updateVisibility : ActivityRecord{6bfdca7 token=android.os.BinderProxy@8dcde89 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-03 17:29:09.451  2127  2145 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-03 17:29:09.451  1692  1692 V ActivityThread: updateVisibility : ActivityRecord{ccf32f9 token=android.os.BinderProxy@6fab3f3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-03 17:29:09.451  1692  1692 D Launcher: onTrimMemory. Level: 20
08-03 17:29:09.461   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
,08-03 17:29:09.711   773   791 I WindowManager: Screenshot max retries 4 of Token{7f5e5f ActivityRecord{f0016fe u0 com.test.thalitest/.MainActivity t115}} appWin=Window{19acb62 u0 d0 Starting com.test.thalitest} drawState=4
,08-03 17:29:09.721   773  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-03 17:29:09.731  7135  7135 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-03 17:29:09.741   773  3397 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-03 17:29:09.781  7135  7135 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-03 17:29:09.781  7135  7135 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-03 17:29:09.801  7135  7135 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-03 17:29:09.831  7135  7135 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-03 17:29:09.831  7135  7135 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 17:29:09.841  7135  7135 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 7411-7414)
,08-03 17:29:09.841  7135  7135 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-03 17:29:09.861  7135  7135 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9d28cc3}
08-03 17:29:09.861  7135  7135 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-03 17:29:09.861  7135  7135 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 17:29:09.871  7135  7135 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-03 17:29:09.881  7135  7157 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-03 17:29:09.911  7135  7135 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-03 17:29:09.911  7135  7135 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-03 17:29:09.911  7135  7135 I Adreno-EGL: Build Date: 01/28/16 Thu
08-03 17:29:09.911  7135  7135 I Adreno-EGL: Local Branch: ss
08-03 17:29:09.911  7135  7135 I Adreno-EGL: Remote Branch: 
08-03 17:29:09.911  7135  7135 I Adreno-EGL: Local Patches: 
08-03 17:29:09.911  7135  7135 I Adreno-EGL: Reconstruct Branch: 
,08-03 17:29:09.911  7135  7135 D libEGL  : eglInitialize EGLDisplay = 0xbef00dac
,08-03 17:29:09.941   773  2393 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-03 17:29:09.941   773  2393 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-03 17:29:10.011  7135  7135 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-03 17:29:10.021  7135  7135 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 17:29:10.021  7135  7135 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-03 17:29:10.021  7135  7135 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-03 17:29:10.021  7135  7135 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-03 17:29:10.041  7135  7135 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-03 17:29:10.051  7135  7135 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-03 17:29:10.051   773  1707 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-03 17:29:10.051   773  1707 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-03 17:29:10.051   773  1707 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-03 17:29:10.051   773  1707 D BatteryService: stay LED for fully charged
08-03 17:29:10.051   773   773 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-03 17:29:10.051   773   773 I MotionRecognitionService: Plugged
08-03 17:29:10.051   773   773 D MotionRecognitionService:   cableConnection= 1
08-03 17:29:10.051   773   773 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-03 17:29:10.051   773   773 D MotionRecognitionService: skip setTransmitPower. 
,08-03 17:29:10.051  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-03 17:29:10.051  1381  1381 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-03 17:29:10.051  1381  1381 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-03 17:29:10.071  2301  2301 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-03 17:29:10.071  2301  2780 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-03 17:29:10.071  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-03 17:29:10.071  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-03 17:29:10.071  1381  1381 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-03 17:29:10.161  7135  7135 D SecWifiDisplayUtil: Metadata value : none
,08-03 17:29:10.161  7135  7135 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e4e4f59 I.E...... R.....ID 0,0-0,0}
,08-03 17:29:10.171  7135  7188 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 17:29:10.171   773  1707 D ISSUE_DEBUG: InputChannelName : 57a3037 com.test.thalitest/com.test.thalitest.MainActivity
,08-03 17:29:10.181   773  2335 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-03 17:29:10.181   773  2335 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:10.181   773   773 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-03 17:29:10.181   773   773 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-03 17:29:10.201  7135  7135 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7135
,08-03 17:29:10.201   773  2374 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7135 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:10.201   773  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-03 17:29:10.201   773  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 17:29:10.201   773  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-03 17:29:10.201   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-03 17:29:10.201   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:10.201   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:10.201   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-03 17:29:10.201   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:10.201   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:10.211   773  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-03 17:29:10.211   773  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:10.211  7135  7157 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-03 17:29:10.211  7135  7135 D SecWifiDisplayUtil: Metadata value : none
,08-03 17:29:10.221   293   293 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-03 17:29:10.241   773  1708 D InputDispatcher: Focus entered window: 7135
,08-03 17:29:10.241   773   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-03 17:29:10.241   773   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:10.241   773   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-03 17:29:10.241   773   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:29:10.241  7135  7188 D libEGL  : eglInitialize EGLDisplay = 0x9caff7c4
08-03 17:29:10.241  7135  7188 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 17:29:10.301  7135  7135 V ActivityThread: updateVisibility : ActivityRecord{a5bcab8 token=android.os.BinderProxy@984a7a0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-03 17:29:10.311  7135  7135 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-03 17:29:10.341   773  2374 V WindowStateAnimator: Finishing drawing window Window{57a3037 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-03 17:29:10.341  7135  7135 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-03 17:29:10.341  7135  7135 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-03 17:29:10.341   773  2335 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-03 17:29:10.351   773   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:10.351   773   773 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:10.351   773   773 I KnoxTimeoutHandler: SD activityfalse
08-03 17:29:10.351   773   903 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +643ms (total +1s22ms)
08-03 17:29:10.351   773   903 D ActivityManager: mDVFSHelper.release()
08-03 17:29:10.351   773   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f0016fe u0 com.test.thalitest/.MainActivity t115} time:337928
08-03 17:29:10.351   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8f7364
08-03 17:29:10.361   773   903 D ViewRootImpl: #3 mView = null
08-03 17:29:10.361  7135  7135 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-03 17:29:10.361   293   380 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
08-03 17:29:10.361   293  1789 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
08-03 17:29:10.371   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
08-03 17:29:10.381   773  1413 V WindowStateAnimator: Finishing drawing window Window{57a3037 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
08-03 17:29:10.381  7135  7135 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@984a7a0 time:337955
08-03 17:29:10.391   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8f7364
08-03 17:29:10.401  7135  7198 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 17:29:10.401  7135  7198 D libEGL  : eglInitialize EGLDisplay = 0x9a98c3ec
08-03 17:29:10.441  7135  7135 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7135
08-03 17:29:10.731   773  3400 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-03 17:29:10.741  7135  7135 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-03 17:29:10.941  7135  7207 D jxcore_app_log: JniHelper::setJavaVM(0xb483c000), pthread_self() = -1725826768
08-03 17:29:10.951  7135  7207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 17:29:10.951  7135  7207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 17:29:10.951  7135  7207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 17:29:10.951  7135  7207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 17:29:10.951  7135  7207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 17:29:10.951  7135  7207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48983ce added. We now have 1 listener(s)
08-03 17:29:10.951  7135  7207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
08-03 17:29:10.961  7135  7207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
08-03 17:29:10.961  7135  7207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 17:29:10.961  7135  7207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 17:29:10.961  7135  7207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fa085 added. We now have 1 listener(s)
08-03 17:29:10.961  7135  7207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 17:29:10.971  7135  7207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
08-03 17:29:10.981  7135  7207 D BluetoothAdapter: STATE_ON
08-03 17:29:10.981  7135  7207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 17:29:10.981  7135  7207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 17:29:10.981  7135  7207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 17:29:10.981  7135  7207 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 17:29:10.981  7135  7135 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 17:29:10.981  7135  7135 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 17:29:10.991  7135  7207 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 17:29:11.021  7135  7135 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-03 17:29:11.181  1449  1449 D Recents : onTaskStackChanged
08-03 17:29:11.191  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-03 17:29:12.171  7135  7208 W jxcore-log: Initializing JXcore engine
,08-03 17:29:12.171  7135  7208 W jxcore-log: JXcore engine is ready
,08-03 17:29:12.231  2307  2307 E audit   : type=1400 msg=audit(1470238152.231:288): avc:  denied  { ioctl } for  pid=7208 comm="Thread-964" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-03 17:29:12.231  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-03 17:29:12.231  2307  2307 E audit   : type=1300 msg=audit(1470238152.231:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9861f3c8 items=0 ppid=348 ppcomm=main pid=7208 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-964" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-03 17:29:12.231  2307  2307 E audit   : type=1327 msg=audit(1470238152.231:288): proctitle="com.test.thalitest"
08-03 17:29:12.231  2307  2307 E audit   : type=1320 msg=audit(1470238152.231:288): 
08-03 17:29:12.231  2307  2307 E audit   : type=1400 msg=audit(1470238152.231:289): avc:  denied  { ioctl } for  pid=7208 comm="Thread-964" path="socket:[41394]" dev="sockfs" ino=41394 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-03 17:29:12.231  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:12.231  2307  2307 E audit   : type=1300 msg=audit(1470238152.231:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=1 a3=9861f3c8 items=0 ppid=348 ppcomm=main pid=7208 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-964" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-03 17:29:12.231  2307  2307 E audit   : type=1327 msg=audit(1470238152.231:289): proctitle="com.test.thalitest"
08-03 17:29:12.231  2307  2307 E audit   : type=1320 msg=audit(1470238152.231:289): 
,08-03 17:29:12.241  7135  7208 W jxcore-log: Starting JXcore engine
,08-03 17:29:12.331  7135  7208 W jxcore-log: Platform android
08-03 17:29:12.331  7135  7208 W jxcore-log: 
08-03 17:29:12.331  7135  7208 W jxcore-log: Process ARCH arm
08-03 17:29:12.331  7135  7208 W jxcore-log: 
,08-03 17:29:12.371   773  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/115_task.xml.bak
,08-03 17:29:12.551  7135  7208 I jxcore-log: JXcore Cordova bridge is ready!
08-03 17:29:12.551  7135  7208 I jxcore-log: 
,08-03 17:29:12.551  7135  7208 W jxcore-log: JXcore engine is started
,08-03 17:29:12.561  7135  7207 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 17:29:12.561  7135  7135 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 17:29:12.581  7135  7208 E jxcore  : Error!: syntax error
08-03 17:29:12.581  7135  7208 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-03 17:29:12.581  7135  7135 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (57)
,08-03 17:29:12.591  7135  7135 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-03 17:29:12.591   773  1705 D InputDispatcher: Focused application set to: xxxx
08-03 17:29:12.601   773  1705 I ActivityManager: Killing 6068:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-03 17:29:12.611  7135  7135 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-03 17:29:12.611  7135  7135 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-03 17:29:12.611  7135  7207 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,08-03 17:29:12.621  7135  7135 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 17:29:12.621  7135  7135 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 17:29:12.621  7135  7135 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 17:29:12.621  7135  7135 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 17:29:12.621  7135  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48983ce removed from the list
08-03 17:29:12.621  7135  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 17:29:12.621  7135  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49fa085 removed from the list
08-03 17:29:12.621   773  2374 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
08-03 17:29:12.621  7135  7135 D io.jxcore.node.ConnectivityMonitor: stop
08-03 17:29:12.621  7135  7135 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-03 17:29:12.621  7135  7135 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 17:29:12.621  7135  7135 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-03 17:29:12.631   293  1789 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
,08-03 17:29:12.631  7135  7135 D ViewRootImpl: #3 mView = null
,08-03 17:29:12.631   293   373 I SurfaceFlinger: id=17 Removed NainActivit (6/8)
,08-03 17:29:12.631   293  5977 I SurfaceFlinger: id=17 Removed NainActivit (-2/8)
,08-03 17:29:12.641   773  1705 D InputDispatcher: Focus left window: 7135
,08-03 17:29:12.641   773   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-03 17:29:12.641   773   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:12.641   773   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-03 17:29:12.641   773   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:29:12.641   773  1708 D ActivityManager: mDVFSHelper.acquire()
,08-03 17:29:12.641   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
,08-03 17:29:12.651  7135  7135 D cr_Ime  : [ImeAdapter.java:587] detach
,08-03 17:29:12.651  7135  7135 E ViewRootImpl: sendUserActionEvent() mView == null
,08-03 17:29:12.651   773   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-03 17:29:12.651   773  1708 V WindowOrientationListener: setCurrentAppOrientation :1
08-03 17:29:12.651   773  1708 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-03 17:29:12.671   293   293 I SurfaceFlinger: id=18 createSurf (1146x1876),1 flag=4, VSBConnecti
08-03 17:29:12.671   773   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ddd6201 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-03 17:29:12.671  1381  1381 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-03 17:29:12.671   773  2335 D InputDispatcher: Focus entered window: 3467
08-03 17:29:12.671   773   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:773 uid:1000
08-03 17:29:12.671   773   903 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:12.671   773   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:773 uid:1000
08-03 17:29:12.671   773   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:29:12.681   773  2393 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-03 17:29:12.681   773  2393 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-03 17:29:12.681   773   773 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:12.691   773   773 I KnoxTimeoutHandler: Shared devices show user statefalse
08-03 17:29:12.691   773   773 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-03 17:29:12.701  1692  1692 D Launcher: onRestart, Launcher: 130495007
,08-03 17:29:12.701  1692  1692 D Launcher: onStart, Launcher: 130495007
,08-03 17:29:12.701  1692  1692 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-03 17:29:12.701  1692  1692 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-03 17:29:12.701  1692  1692 D Launcher.HomeView: onStart
,08-03 17:29:12.701   773  1497 V WindowStateAnimator: Finishing drawing window Window{ddd6201 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-03 17:29:12.711   293   293 I SurfaceFlinger: id=19 createSurf (1194x288),1 flag=4, VSBConnecti
,08-03 17:29:12.711  1692  1692 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-03 17:29:12.711  1692  1692 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-03 17:29:12.711  2127  2142 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
08-03 17:29:12.711   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8f7364
,08-03 17:29:12.711  1692  1692 V ActivityThread: updateVisibility : ActivityRecord{ccf32f9 token=android.os.BinderProxy@6fab3f3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-03 17:29:12.721   773   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:12.721   773   903 D ActivityManager: mDVFSHelper.release()
08-03 17:29:12.721   773   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bbb1293 u0 com.samsung.android.MtpApplication/.USBConnection t114} time:340293
08-03 17:29:12.721   773   773 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:12.721   773   773 I KnoxTimeoutHandler: SD activityfalse
,08-03 17:29:12.721  3467  3467 V ActivityThread: updateVisibility : ActivityRecord{6bfdca7 token=android.os.BinderProxy@8dcde89 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-03 17:29:12.731   293   293 I SurfaceFlinger: id=20 createSurf (1080x1920),1 flag=4, Mauncher
,08-03 17:29:12.751   773  2374 V WindowStateAnimator: Finishing drawing window Window{73fe2e7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-03 17:29:12.751  3467  3467 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8dcde89 time:340324
,08-03 17:29:12.751  1692  1692 D Launcher.HomeView: onStop
,08-03 17:29:12.751   773   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-03 17:29:12.761   773   773 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:12.761   773   773 I KnoxTimeoutHandler: SD activityfalse
,08-03 17:29:12.761   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8f7364
,08-03 17:29:12.881   773  1705 V WindowStateAnimator: Finishing drawing window Window{3bd8ca4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-03 17:29:12.891   773   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-03 17:29:12.891   773   773 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:12.891   773   773 I KnoxTimeoutHandler: SD activityfalse
,08-03 17:29:12.891   773   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d2aa7ec u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t112} time:340463
,08-03 17:29:12.891   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe8f7364
,08-03 17:29:13.461  2307  2307 E audit   : type=1400 msg=audit(1470238153.461:290): avc:  denied  { execmod } for  pid=7209 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-03 17:29:13.461  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:13.461  2307  2307 E audit   : type=1300 msg=audit(1470238153.461:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4020000 a1=51000 a2=5 a3=4 items=0 ppid=3541 ppcomm=adbd pid=7209 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-03 17:29:13.461  2307  2307 E audit   : type=1327 msg=audit(1470238153.461:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-03 17:29:13.461  2307  2307 E audit   : type=1320 msg=audit(1470238153.461:290): 
,08-03 17:29:13.521  2307  2307 E audit   : type=1400 msg=audit(1470238153.521:291): avc:  denied  { execmod } for  pid=7209 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-03 17:29:13.521  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:13.521  2307  2307 E audit   : type=1300 msg=audit(1470238153.521:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe0000 a1=51000 a2=5 a3=4 items=0 ppid=3541 ppcomm=adbd pid=7209 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-03 17:29:13.521  2307  2307 E audit   : type=1327 msg=audit(1470238153.521:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-03 17:29:13.521  2307  2307 E audit   : type=1320 msg=audit(1470238153.521:291): 
,08-03 17:29:13.561  2307  2307 E audit   : type=1400 msg=audit(1470238153.561:292): avc:  denied  { execmod } for  pid=7209 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-03 17:29:13.561  2307  2307 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:13.571  2307  2307 E audit   : type=1300 msg=audit(1470238153.561:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe0000 a1=51000 a2=5 a3=4 items=0 ppid=3541 ppcomm=adbd pid=7209 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-03 17:29:13.571  2307  2307 E audit   : type=1327 msg=audit(1470238153.561:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-03 17:29:13.571  2307  2307 E audit   : type=1320 msg=audit(1470238153.561:292): 
,08-03 17:29:13.571  7209  7209 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-03 17:29:13.571  7209  7209 D AndroidRuntime: CheckJNI is OFF
,08-03 17:29:13.571  7209  7209 D AndroidRuntime: readGMSProperty: start
08-03 17:29:13.571  7209  7209 D AndroidRuntime: readGMSProperty: already setted!!
08-03 17:29:13.571  7209  7209 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-03 17:29:13.571  7209  7209 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-03 17:29:13.571  7209  7209 D AndroidRuntime: readGMSProperty: end
08-03 17:29:13.571  7209  7209 D AndroidRuntime: addProductProperty: start
,08-03 17:29:13.581  7209  7209 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-03 17:29:13.581  7209  7209 W art     : af18e000-b20b4000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-03 17:29:13.581  7209  7209 W art     : b20b4000-b4323000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-03 17:29:13.581  7209  7209 W art     : b4323000-b4324000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
,08-03 17:29:13.581  7209  7209 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-03 17:29:13.581  7209  7209 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
,08-03 17:29:13.581  7209  7209 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-03 17:29:13.581  7209  7209 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-03 17:29:13.581  7209  7209 W art     : b4887000-b48b0000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-03 17:29:13.581  7209  7209 W art     : b48b0000-b48b3000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
,08-03 17:29:13.581  7209  7209 W art     : b48b3000-b48b4000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-03 17:29:13.581  7209  7209 W art     : b48b4000-b48b5000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so,
08-03 17:29:13.581  7209  7209 W art     : b48b5000-b48b6000 r--p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b48b6000-b48d6000 r--s 00000000 00:0b 6712       /dev/__properties__
08-03 17:29:13.581  7209  7209 W art     : b48d6000-b52e7000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
,08-03 17:29:13.581  7209  7209 W art     : b52e7000-b52e8000 ---p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b52e8000-b5331000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-03 17:29:13.581  7209  7209 W art     : b5331000-b5332000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-03 17:29:13.581  7209  7209 W art     : b5332000-b533a000 rw-p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b533a000-b533b000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-03 17:29:13.581  7209  7209 W art     : b533b000-b5370000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
,08-03 17:29:13.581  7209  7209 W art     : b5370000-b5371000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b5371000-b5372000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
,08-03 17:29:13.581  7209  7209 W art     : b5372000-b5373000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-03 17:29:13.581  7209  7209 W art     : b5373000-b53cb000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-03 17:29:13.581  7209  7209 W art     : b53cb000-b53cc000 ---p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b53cc000-b53cd000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-03 17:29:13.581  7209  7209 W art     : b53cd000-b53ce000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so,
08-03 17:29:13.581  7209  7209 W art     : b53cf000-b53d5000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-03 17:29:13.581  7209  7209 W art     : b53d5000-b53d6000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-03 17:29:13.581  7209  7209 W art     : b53d6000-b53d7000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-03 17:29:13.581  7209  7209 W art     : b53d7000-b53d9000 rw-p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b53da000-b53e4000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-03 17:29:13.581  7209  7209 W art     : b53e4000-b53e7000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-03 17:29:13.581  7209  7209 W art     : b53e7000-b53e8000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-03 17:29:13.581  7209  7209 W art     : b53e9000-b5400000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-03 17:29:13.581  7209  7209 W art     : b5400000-b5401000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b5401000-b5402000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-03 17:29:13.581  7209  7209 W art     : b5402000-b5403000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-03 17:29:13.581  7209  7209 W art     : b5404000-b540e000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-03 17:29:13.581  7209  7209 W art     : b540e000-b540f000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so,
08-03 17:29:13.581  7209  7209 W art     : b540f000-b5410000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
,08-03 17:29:13.581  7209  7209 W art     : b5410000-b5414000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-03 17:29:13.581  7209  7209 W art     : b5414000-b5415000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-03 17:29:13.581  7209  7209 W art     : b5415000-b5416000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-03 17:29:13.581  7209  7209 W art     : b5416000-b542c000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-03 17:29:13.581  7209  7209 W art     : b542c000-b542d000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
,08-03 17:29:13.581  7209  7209 W art     : b542d000-b542e000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-03 17:29:13.581  7209  7209 W art     : b542e000-b543b000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
,08-03 17:29:13.581  7209  7209 W art     : b543b000-b543c000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-03 17:29:13.581  7209  7209 W art     : b543c000-b543d000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-03 17:29:13.581  7209  7209 W art     : b543d000-b549d000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so,
08-03 17:29:13.581  7209  7209 W art     : b549d000-b54a0000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-03 17:29:13.581  7209  7209 W art     : b54a0000-b54a4000 rw-p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b54a4000-b5505000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-03 17:29:13.581  7209  7209 W art     : b5505000-b5506000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
,08-03 17:29:13.581  7209  7209 W art     : b5506000-b5555000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-03 17:29:13.581  7209  7209 W art     : b5555000-b5557000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-03 17:29:13.581  7209  7209 W art     : b5557000-b5558000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-03 17:29:13.581  7209  7209 W art     : b5558000-b5559000 rw-p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b5559000-b5560000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-03 17:29:13.581  7209  7209 W art     : b5560000-b5561000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-03 17:29:13.581  7209  7209 W art     : b5561000-b5562000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-03 17:29:13.581  7209  7209 W art     : b5563000-b5566000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-03 17:29:13.581  7209  7209 W art     : b5566000-b5567000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-03 17:29:13.581  7209  7209 W art     : b5567000-b5568000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-03 17:29:13.581  7209  7209 W art     : b5569000-b556d000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-03 17:29:13.581  7209  7209 W art     : b556d000-b556e000 ---p 00000000 00:00 0 
,08-03 17:29:13.581  7209  7209 W art     : b556e000-b556f000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-03 17:29:13.581  7209  7209 W art     : b556f000-b5570000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
,08-03 17:29:13.581  7209  7209 W art     : b5571000-b558e000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-03 17:29:13.581  7209  7209 W art     : b558e000-b558f000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
,08-03 17:29:13.581  7209  7209 W art     : b558f000-b5590000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-03 17:29:13.581  7209  7209 W art     : b5591000-b5596000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-03 17:29:13.581  7209  7209 W art     : b5596000-b5597000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-03 17:29:13.581  7209  7209 W art     : b5597000-b5598000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-03 17:29:13.581  7209  7209 W art     : b5599000-b55ca000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-03 17:29:13.581  7209  7209 W art     : b55ca000-b55cd000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-03 17:29:13.581  7209  7209 W art     : b55cd000-b55ce000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-03 17:29:13.581  7209  7209 W art     : b55cf000-b560a000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-03 17:29:13.581  7209  7209 W art     : b560a000-b560b000 r--p 0003a000 b3:17 893        /system/lib/libopus.so,
08-03 17:29:13.581  7209  7209 W art     : b560b000-b560c000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-03 17:29:13.581  7209  7209 W art     : b560d000-b5614000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-03 17:29:13.581  7209  7209 W art     : b5614000-b5615000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b5615000-b5616000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-03 17:29:13.581  7209  7209 W art     : b5616000-b5617000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-03 17:29:13.581  7209  7209 W art     : b5617000-b5618000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-03 17:29:13.581  7209  7209 W art     : b5618000-b562f000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-03 17:29:13.581  7209  7209 W art     : b562f000-b5630000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b5630000-b5633000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-03 17:29:13.581  7209  7209 W art     : b5633000-b5634000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-03 17:29:13.581  7209  7209 W art     : b5634000-b5653000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-03 17:29:13.581  7209  7209 W art     : b5653000-b5654000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
,08-03 17:29:13.581  7209  7209 W art     : b5654000-b5655000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-03 17:29:13.581  7209  7209 W art     : b5655000-b5693000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-03 17:29:13.581  7209  7209 W art     : b5693000-b5694000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b5694000-b5696000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-03 17:29:13.581  7209  7209 W art     : b5696000-b5697000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-03 17:29:13.581  7209  7209 W art     : b5698000-b569f000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
,08-03 17:29:13.581  7209  7209 W art     : b569f000-b56a0000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-03 17:29:13.581  7209  7209 W art     : b56a0000-b56a1000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-03 17:29:13.581  7209  7209 W art     : b56a2000-b56a5000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-03 17:29:13.581  7209  7209 W art     : b56a5000-b56a6000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-03 17:29:13.581  7209  7209 W art     : b56a6000-b56a7000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-03 17:29:13.581  7209  7209 W art     : b56a7000-b56ad000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-03 17:29:13.581  7209  7209 W art     : b56ad000-b56ae000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b56ae000-b56af000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-03 17:29:13.581  7209  7209 W art     : b56af000-b56b0000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-03 17:29:13.581  7209  7209 W art     : b56b0000-b56b9000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-03 17:29:13.581  7209  7209 W art     : b56b9000-b56ba000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-03 17:29:13.581  7209  7209 W art     : b56ba000-b56bb000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
,08-03 17:29:13.581  7209  7209 W art     : b56bb000-b574c000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-03 17:29:13.581  7209  7209 W art     : b574c000-b574d000 ---p 00000000 00:00 0 
08-03 17:29:13.581  7209  7209 W art     : b574d000-b5758000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-03 17:29:13.581  7209  7209 W art     : b5758000-b5759000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-03 17:29:13.581  7209  7209 W art     : b575a000-b576c000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-03 17:29:13.581  7209  7209 W art     : b576c000-b576d000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
,08-03 17:29:13.581  7209  7209 W art     : b576d000-b576e000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-03 17:29:13.581  7209  7209 W art     : b576f000-b5774000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-03 17:29:13.581  7209  7209 W art     : b5774000-b5775000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-03 17:29:13.581  7209  7209 W art     : b5775000-b5776000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-03 17:29:13.581  7209  7209 W art     : b5777000-b57e4000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-03 17:29:13.581  7209  7209 W art     : b57e4000-b57e5000 ---p 00000000 00:00 0 
,08-03 17:29:13.591  7209  7209 W art     : b57e5000-b57e7000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-03 17:29:13.591  7209  7209 W art     : b57e7000-b57e8000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-03 17:29:13.591  7209  7209 W art     : b57e8000-b57e9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b57e9000-b57f0000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-03 17:29:13.591  7209  7209 W art     : b57f0000-b57f1000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-03 17:29:13.591  7209  7209 W art     : b57f1000-b57f2000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-03 17:29:13.591  7209  7209 W art     : b57f3000-b5873000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-03 17:29:13.591  7209  7209 W art     : b5873000-b5874000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5874000-b5875000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-03 17:29:13.591  7209  7209 W art     : b5875000-b5876000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-03 17:29:13.591  7209  7209 W art     : b5876000-b588d000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b588d000-b58c4000 r-xp 00000000 b3:17 3244       /system/vendor/l
,08-03 17:29:13.591  7209  7209 W art     : ib/libqc-opt.so
08-03 17:29:13.591  7209  7209 W art     : b58c4000-b58c5000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-03 17:29:13.591  7209  7209 W art     : b58c5000-b58c6000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-03 17:29:13.591  7209  7209 W art     : b58c6000-b58e2000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-03 17:29:13.591  7209  7209 W art     : b58e2000-b58e3000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-03 17:29:13.591  7209  7209 W art     : b58e3000-b58e4000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
,08-03 17:29:13.591  7209  7209 W art     : b58e5000-b5946000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-03 17:29:13.591  7209  7209 W art     : b5946000-b5948000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-03 17:29:13.591  7209  7209 W art     : b5948000-b5949000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-03 17:29:13.591  7209  7209 W art     : b594a000-b5971000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-03 17:29:13.591  7209  7209 W art     : b5971000-b5972000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5972000-b5973000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
,08-03 17:29:13.591  7209  7209 W art     : b5973000-b5974000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-03 17:29:13.591  7209  7209 W art     : b5975000-b597d000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-03 17:29:13.591  7209  7209 W art     : b597d000-b597f000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-03 17:29:13.591  7209  7209 W art     : b597f000-b5980000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-03 17:29:13.591  7209  7209 W art     : b5981000-b5984000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-03 17:29:13.591  7209  7209 W art     : b5984000-b5985000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
,08-03 17:29:13.591  7209  7209 W art     : b5985000-b5986000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-03 17:29:13.591  7209  7209 W art     : b5986000-b598a000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-03 17:29:13.591  7209  7209 W art     : b598a000-b598b000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b598b000-b598c000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-03 17:29:13.591  7209  7209 W art     : b598c000-b598d000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-03 17:29:13.591  7209  7209 W art     : b598d000-b599d000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
,08-03 17:29:13.591  7209  7209 W art     : b599d000-b599e000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-03 17:29:13.591  7209  7209 W art     : b599e000-b599f000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-03 17:29:13.591  7209  7209 W art     : b599f000-b59e5000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b59e5000-b59ee000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-03 17:29:13.591  7209  7209 W art     : b59ee000-b59ef000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
,08-03 17:29:13.591  7209  7209 W art     : b59ef000-b59f0000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-03 17:29:13.591  7209  7209 W art     : b59f1000-b59f6000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-03 17:29:13.591  7209  7209 W art     : b59f6000-b59f7000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-03 17:29:13.591  7209  7209 W art     : b59f7000-b59f8000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-03 17:29:13.591  7209  7209 W art     : b59f8000-b59fb000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-03 17:29:13.591  7209  7209 W art     : b59fb000-b59fc000 ---p 00000000 00:00 0 
,08-03 17:29:13.591  7209  7209 W art     : b59fc000-b59fd000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-03 17:29:13.591  7209  7209 W art     : b59fd000-b59fe000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-03 17:29:13.591  7209  7209 W art     : b59ff000-b5a17000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-03 17:29:13.591  7209  7209 W art     : b5a17000-b5a18000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5a18000-b5a19000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-03 17:29:13.591  7209  7209 W art     : b5a19000-b5a1a000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-03 17:29:13.591  7209  7209 W art     : b5a1a000-b5a1b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:13.591  7209  7209 W art     : b5a1b000-b5bb5000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-03 17:29:13.591  7209  7209 W art     : b5bb5000-b5bb6000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5bb6000-b5bc3000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-03 17:29:13.591  7209  7209 W art     : b5bc3000-b5bc4000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-03 17:29:13.591  7209  7209 W art     : b5bc4000-b5bc8000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
,08-03 17:29:13.591  7209  7209 W art     : b5bc8000-b5bc9000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5bc9000-b5bca000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-03 17:29:13.591  7209  7209 W art     : b5bca000-b5bcb000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-03 17:29:13.591  7209  7209 W art     : b5bcb000-b5bde000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-03 17:29:13.591  7209  7209 W art     : b5bde000-b5bdf000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-03 17:29:13.591  7209  7209 W art     : b5bdf000-b5be0000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
,08-03 17:29:13.591  7209  7209 W art     : b5be1000-b5c2c000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-03 17:29:13.591  7209  7209 W art     : b5c2c000-b5c2d000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-03 17:29:13.591  7209  7209 W art     : b5c2d000-b5c2e000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-03 17:29:13.591  7209  7209 W art     : b5c2e000-b5c30000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5c31000-b5c42000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-03 17:29:13.591  7209  7209 W art     : b5c42000-b5c43000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5c43000-b5c44000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-03 17:29:13.591  7209  7209 W art     : b5c44000-b5c45000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-03 17:29:13.591  7209  7209 W art     : b5c45000-b5c46000 r--p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5c46000-b5c50000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-03 17:29:13.591  7209  7209 W art     : b5c50000-b5c52000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-03 17:29:13.591  7209  7209 W art     : b5c52000-b5c53000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-03 17:29:13.591  7209  7209 W art     : b5c53000-b5c6c000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-03 17:29:13.591  7209  7209 W art     : b5c6c000-b5c6d000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-03 17:29:13.591  7209  7209 W art     : b5c6d000-b5c70000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-03 17:29:13.591  7209  7209 W art     : b5c70000-b5c74000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5c74000-b5ce8000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-03 17:29:13.591  7209  7209 W art     : b5ce8000-b5ce9000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5ce9000-b5cec000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-03 17:29:13.591  7209  7209 W art     : b5cec000-b5ced000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-03 17:29:13.591  7209  7209 W art     : b5ced000-b5cee000 r--p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5cee000-b5cf1000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-03 17:29:13.591  7209  7209 W art     : b5cf1000-b5cf2000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-03 17:29:13.591  7209  7209 W art     : b5cf2000-b5cf3000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-03 17:29:13.591  7209  7209 W art     : b5cf3000-b5cf4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b5cf4000-b5cf9000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-03 17:29:13.591  7209  7209 W art     : b5cf9000-b5cfa000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-03 17:29:13.591  7209  7209 W art     : b5cfa000-b5cfb000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-03 17:29:13.591  7209  7209 W art     : b5cfb000-b5cfc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b5cfc000-b5cff000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-03 17:29:13.591  7209  7209 W art     : b5cff000-b5d00000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-03 17:29:13.591  7209  7209 W art     : b5d00000-b5d01000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-03 17:29:13.591  7209  7209 W art     : b5d01000-b5d02000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b5d02000-b5d06000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-03 17:29:13.591  7209  7209 W art     : b5d06000-b5d07000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-03 17:29:13.591  7209  7209 W art     : b5d07000-b5d08000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-03 17:29:13.591  7209  7209 W art     : b5d08000-b5d09000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:13.591  7209  7209 W art     : b5d09000-b5d0d000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-03 17:29:13.591  7209  7209 W art     : b5d0d000-b5d0e000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-03 17:29:13.591  7209  7209 W art     : b5d0e000-b5d0f000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-03 17:29:13.591  7209  7209 W art     : b5d0f000-b5d10000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b5d10000-b5d1e000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-03 17:29:13.591  7209  7209 W art     : b5d1e000-b5d1f000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b5d1f000-b5d20000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-03 17:29:13.591  7209  7209 W art     : b5d20000-b5d21000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-03 17:29:13.591  7209  7209 W art     : b5d21000-b5d2b000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-03 17:29:13.591  7209  7209 W art     : b5d2b000-b5d2e000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-03 17:29:13.591  7209  7209 W art     : b5d2e000-b5d2f000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-03 17:29:13.591  7209  7209 W art     : b5d2f000-b5d30000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b5d30000-b5d3a000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-03 17:29:13.591  7209  7209 W art     : b5d3a000-b5d3d000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-03 17:29:13.591  7209  7209 W art     : b5d3d000-b5d3e000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-03 17:29:13.591  7209  7209 W art     : b5d3e000-b5d42000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-03 17:29:13.591  7209  7209 W art     : b5d42000-b5d43000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-03 17:29:13.591  7209  7209 W art     : b5d43000-b5d44000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-03 17:29:13.591  7209  7209 W art     : b5d44000-b5d45000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b5d45000-b5d52000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-03 17:29:13.591  7209  7209 W art     : b5d52000-b5d54000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-03 17:29:13.591  7209  7209 W art     : b5d54000-b5d55000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-03 17:29:13.591  7209  7209 W art     : b5d55000-b6167000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-03 17:29:13.591  7209  7209 W art     : b6167000-b6168000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6168000-b6171000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-03 17:29:13.591  7209  7209 W art     : b6171000-b6175000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-03 17:29:13.591  7209  7209 W art     : b6175000-b6176000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6176000-b617d000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-03 17:29:13.591  7209  7209 W art     : b617d000-b617e000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-03 17:29:13.591  7209  7209 W art     : b617e000-b617f000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-03 17:29:13.591  7209  7209 W art     : b617f000-b6180000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6180000-b619b000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-03 17:29:13.591  7209  7209 W art     : b619b000-b619c000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-03 17:29:13.591  7209  7209 W art     : b619c000-b619d000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-03 17:29:13.591  7209  7209 W art     : b619d000-b619e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b619e000-b61ea000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-03 17:29:13.591  7209  7209 W art     : b61ea000-b61eb000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b61eb000-b61ec000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-03 17:29:13.591  7209  7209 W art     : b61ec000-b61ed000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-03 17:29:13.591  7209  7209 W art     : b61ed000-b61ee000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b61ee000-b61f2000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-03 17:29:13.591  7209  7209 W art     : b61f2000-b61f3000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b61f3000-b61f4000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-03 17:29:13.591  7209  7209 W art     : b61f4000-b61f5000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-03 17:29:13.591  7209  7209 W art     : b61f5000-b622d000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-03 17:29:13.591  7209  7209 W art     : b622d000-b622e000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
,08-03 17:29:13.591  7209  7209 W art     : b622e000-b622f000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-03 17:29:13.591  7209  7209 W art     : b622f000-b6230000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6230000-b62ce000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-03 17:29:13.591  7209  7209 W art     : b62ce000-b62cf000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b62cf000-b62ed000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-03 17:29:13.591  7209  7209 W art     : b62ed000-b62ee000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-03 17:29:13.591  7209  7209 W art     : b62ee000-b6461000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-03 17:29:13.591  7209  7209 W art     : b6461000-b646c000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
,08-03 17:29:13.591  7209  7209 W art     : b646c000-b646d000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-03 17:29:13.591  7209  7209 W art     : b646d000-b6584000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-03 17:29:13.591  7209  7209 W art     : b6584000-b658f000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-03 17:29:13.591  7209  7209 W art     : b658f000-b6590000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-03 17:29:13.591  7209  7209 W art     : b6590000-b6594000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6594000-b65b8000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-03 17:29:13.591  7209  7209 W art     : b65b8000-b65ba000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-03 17:29:13.591  7209  7209 W art     : b65ba000-b65bb000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-03 17:29:13.591  7209  7209 W art     : b65bb000-b6661000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-03 17:29:13.591  7209  7209 W art     : b6661000-b666e000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
,08-03 17:29:13.591  7209  7209 W art     : b666e000-b666f000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-03 17:29:13.591  7209  7209 W art     : b666f000-b6670000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6670000-b66c3000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-03 17:29:13.591  7209  7209 W art     : b66c3000-b66c4000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b66c4000-b66c5000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-03 17:29:13.591  7209  7209 W art     : b66c5000-b66c6000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-03 17:29:13.591  7209  7209 W art     : b66c6000-b66cb000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b66cb000-b66dd000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-03 17:29:13.591  7209  7209 W art     : b66dd000-b66de000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b66de000-b66df000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-03 17:29:13.591  7209  7209 W art     : b66df000-b66e0000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-03 17:29:13.591  7209  7209 W art     : b66e0000-b66e7000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-03 17:29:13.591  7209  7209 W art     : b66e7000-b66e8000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-03 17:29:13.591  7209  7209 W art     : b66e8000-b66e9000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-03 17:29:13.591  7209  7209 W art     : b66e9000-b66ea000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b66ea000-b66ed000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-03 17:29:13.591  7209  7209 W art     : b66ed000-b66ee000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-03 17:29:13.591  7209  7209 W art     : b66ee000-b66ef000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-03 17:29:13.591  7209  7209 W art     : b66ef000-b66f3000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-03 17:29:13.591  7209  7209 W art     : b66f3000-b66f4000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-03 17:29:13.591  7209  7209 W art     : b66f4000-b66f5000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-03 17:29:13.591  7209  7209 W art     : b66f5000-b6703000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-03 17:29:13.591  7209  7209 W art     : b6703000-b6704000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6704000-b6705000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-03 17:29:13.591  7209  7209 W art     : b6705000-b6706000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-03 17:29:13.591  7209  7209 W art     : b6706000-b670f000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-03 17:29:13.591  7209  7209 W art     : b670f000-b6710000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-03 17:29:13.591  7209  7209 W art     : b6710000-b6711000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-03 17:29:13.591  7209  7209 W art     : b6711000-b6777000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-03 17:29:13.591  7209  7209 W art     : b6777000-b6778000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6778000-b677a000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-03 17:29:13.591  7209  7209 W art     : b677a000-b6783000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-03 17:29:13.591  7209  7209 W art     : b6783000-b6786000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6786000-b681d000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-03 17:29:13.591  7209  7209 W art     : b681d000-b681f000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-03 17:29:13.591  7209  7209 W art     : b681f000-b6820000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-03 17:29:13.591  7209  7209 W art     : b6820000-b6821000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6821000-b6b42000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-03 17:29:13.591  7209  7209 W art     : b6b42000-b6b43000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6b43000-b6b5e000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-03 17:29:13.591  7209  7209 W art     : b6b5e000-b6b62000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-03 17:29:13.591  7209  7209 W art     : b6b62000-b6b67000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6b67000-b6b6f000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-03 17:29:13.591  7209  7209 W art     : b6b6f000-b6b70000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-03 17:29:13.591  7209  7209 W art     : b6b70000-b6b71000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-03 17:29:13.591  7209  7209 W art     : b6b71000-b6b9f000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-03 17:29:13.591  7209  7209 W art     : b6b9f000-b6ba0000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6ba0000-b6ba7000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-03 17:29:13.591  7209  7209 W art     : b6ba7000-b6ba8000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-03 17:29:13.591  7209  7209 W art     : b6ba8000-b6bee000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-03 17:29:13.591  7209  7209 W art     : b6bee000-b6bef000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6bef000-b6bf2000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-03 17:29:13.591  7209  7209 W art     : b6bf2000-b6bf3000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-03 17:29:13.591  7209  7209 W art     : b6bf3000-b6c0e000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-03 17:29:13.591  7209  7209 W art     : b6c0e000-b6c12000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-03 17:29:13.591  7209  7209 W art     : b6c12000-b6c13000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-03 17:29:13.591  7209  7209 W art     : b6c13000-b6c60000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-03 17:29:13.591  7209  7209 W art     : b6c60000-b6c61000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6c61000-b6c6d000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-03 17:29:13.591  7209  7209 W art     : b6c6d000-b6c6e000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-03 17:29:13.591  7209  7209 W art     : b6c6e000-b6c7b000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-03 17:29:13.591  7209  7209 W art     : b6c7b000-b6c7c000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6c7c000-b6c7d000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-03 17:29:13.591  7209  7209 W art     : b6c7d000-b6c7e000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-03 17:29:13.591  7209  7209 W art     : b6c7e000-b6c86000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-03 17:29:13.591  7209  7209 W art     : b6c86000-b6c87000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6c87000-b6c88000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-03 17:29:13.591  7209  7209 W art     : b6c88000-b6c89000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-03 17:29:13.591  7209  7209 W art     : b6c89000-b6c90000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-03 17:29:13.591  7209  7209 W art     : b6c90000-b6c91000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-03 17:29:13.591  7209  7209 W art     : b6c91000-b6c92000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-03 17:29:13.591  7209  7209 W art     : b6c92000-b6ca6000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-03 17:29:13.591  7209  7209 W art     : b6ca6000-b6ca8000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-03 17:29:13.591  7209  7209 W art     : b6ca8000-b6ca9000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-03 17:29:13.591  7209  7209 W art     : b6ca9000-b6cd1000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-03 17:29:13.591  7209  7209 W art     : b6cd1000-b6cd3000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-03 17:29:13.591  7209  7209 W art     : b6cd3000-b6cd4000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-03 17:29:13.591  7209  7209 W art     : b6cd4000-b6cd7000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-03 17:29:13.591  7209  7209 W art     : b6cd7000-b6cd8000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-03 17:29:13.591  7209  7209 W art     : b6cd8000-b6cd9000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-03 17:29:13.591  7209  7209 W art     : b6cd9000-b6ce2000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-03 17:29:13.591  7209  7209 W art     : b6ce2000-b6ce3000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-03 17:29:13.591  7209  7209 W art     : b6ce3000-b6ce4000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-03 17:29:13.591  7209  7209 W art     : b6ce4000-b6d04000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-03 17:29:13.591  7209  7209 W art     : b6d04000-b6d05000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-03 17:29:13.591  7209  7209 W art     : b6d05000-b6d06000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-03 17:29:13.591  7209  7209 W art     : b6d06000-b6d79000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-03 17:29:13.591  7209  7209 W art     : b6d79000-b6d7d000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-03 17:29:13.591  7209  7209 W art     : b6d7d000-b6d80000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-03 17:29:13.591  7209  7209 W art     : b6d80000-b6d8a000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6d8a000-b6e12000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-03 17:29:13.591  7209  7209 W art     : b6e12000-b6e13000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6e13000-b6e17000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-03 17:29:13.591  7209  7209 W art     : b6e17000-b6e18000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-03 17:29:13.591  7209  7209 W art     : b6e18000-b6e19000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6e19000-b6e42000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-03 17:29:13.591  7209  7209 W art     : b6e42000-b6e43000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6e43000-b6e46000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-03 17:29:13.591  7209  7209 W art     : b6e46000-b6e47000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-03 17:29:13.591  7209  7209 W art     : b6e47000-b6f21000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-03 17:29:13.591  7209  7209 W art     : b6f21000-b6f28000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-03 17:29:13.591  7209  7209 W art     : b6f28000-b6f30000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-03 17:29:13.591  7209  7209 W art     : b6f30000-b6f31000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6f31000-b6f32000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:13.591  7209  7209 W art     : b6f32000-b6f33000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-03 17:29:13.591  7209  7209 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6f34000-b6f37000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6f37000-b6f5c000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-03 17:29:13.591  7209  7209 W art     : b6f5c000-b6f5d000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6f5d000-b6f64000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-03 17:29:13.591  7209  7209 W art     : b6f64000-b6f65000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-03 17:29:13.591  7209  7209 W art     : b6f65000-b6f6c000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-03 17:29:13.591  7209  7209 W art     : b6f6c000-b6f6d000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-03 17:29:13.591  7209  7209 W art     : b6f6d000-b6f6e000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-03 17:29:13.591  7209  7209 W art     : b6f6e000-b6f6f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6f6f000-b6f87000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-03 17:29:13.591  7209  7209 W art     : b6f87000-b6f88000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6f88000-b6f89000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-03 17:29:13.591  7209  7209 W art     : b6f89000-b6f8a000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-03 17:29:13.591  7209  7209 W art     : b6f8a000-b6f98000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-03 17:29:13.591  7209  7209 W art     : b6f98000-b6f99000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6f99000-b6f9a000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-03 17:29:13.591  7209  7209 W art     : b6f9a000-b6f9b000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-03 17:29:13.591  7209  7209 W art     : b6f9b000-b6f9c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:13.591  7209  7209 W art     : b6f9c000-b6f9e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6f9e000-b6f9f000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6f9f000-b6fa0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-03 17:29:13.591  7209  7209 W art     : b6fa0000-b6fa1000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-03 17:29:13.591  7209  7209 W art     : b6fa1000-b6fa2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-03 17:29:13.591  7209  7209 W art     : b6fa2000-b6fc2000 r--s 00000000 00:0b 6712       /dev/__properties__
08-03 17:29:13.591  7209  7209 W art     : b6fc2000-b6fc3000 r--p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6fc3000-b6fc4000 ---p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6fc4000-b6fc6000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-03 17:29:13.591  7209  7209 W art     : b6fc6000-b6fc7000 r-xp 00000000 00:00 0          [sigpage]
08-03 17:29:13.591  7209  7209 W art     : b6fc7000-b6fe2000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-03 17:29:13.591  7209  7209 W art     : b6fe2000-b6fe3000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-03 17:29:13.591  7209  7209 W art     : b6fe3000-b6fe5000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-03 17:29:13.591  7209  7209 W art     : b6fe5000-b6fe7000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : b6fe7000-b6fec000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-03 17:29:13.591  7209  7209 W art     : b6fec000-b6fed000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-03 17:29:13.591  7209  7209 W art     : b6fed000-b6fee000 rw-p 00000000 00:00 0 
08-03 17:29:13.591  7209  7209 W art     : be82e000-be84f000 rw-p 00000000 00:00 0          [stack]
08-03 17:29:13.591  7209  7209 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-03 17:29:13.661  7209  7209 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-03 17:29:13.691  1449  1449 D Recents : onTaskStackChanged
08-03 17:29:13.691  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
08-03 17:29:13.711  7209  7209 I Radio-JNI: register_android_hardware_Radio DONE
,08-03 17:29:13.721  7209  7209 E AffinityControl: AffinityControl: registerfunction enter
,08-03 17:29:13.741  7209  7209 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 17:29:13.751   773  2374 D PackageManager: START PACKAGE DELETE: observer{88914497}
08-03 17:29:13.751   773  2374 D PackageManager: pkg{<packageName>}
08-03 17:29:13.751   773  2374 D PackageManager: user{0}
08-03 17:29:13.751   773  2374 D PackageManager: caller{2000}
08-03 17:29:13.751   773  2374 D PackageManager: flags{2}
08-03 17:29:13.751   773  2374 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-03 17:29:13.751   773  2374 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-03 17:29:13.751   773  2374 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-03 17:29:13.751   773  2374 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-03 17:29:13.751   773  2374 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-03 17:29:13.751   773   934 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-03 17:29:13.751   773   934 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-03 17:29:13.751   773   934 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-03 17:29:13.751   773   934 D ApplicationPolicy: getApplicationUninstallationEnabled
08-03 17:29:13.751   773   934 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-03 17:29:13.751   773   934 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-03 17:29:13.751   773   934 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-03 17:29:13.751   773   934 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-03 17:29:13.751   773   856 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-03 17:29:13.751   773   856 I ActivityManager: Killing 7135:com.test.thalitest/u0a4 (adj 9): stop com.test.thalitest cause uninstall pkg
08-03 17:29:13.751   773   856 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-03 17:29:13.771   773   934 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-03 17:29:13.771   773   934 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-03 17:29:13.791   773   934 D AASAinstall: there is not AASApackages.xml file
08-03 17:29:13.791   773  2374 D GraphicsStats: Buffer count: 4
08-03 17:29:13.791   773  2374 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1b14be6)
08-03 17:29:13.791   773  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 17:29:13.791   773  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 17:29:13.801   773  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:14.061   773   934 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-03 17:29:14.081   773   934 W PackageSettings: Skipping PackageSetting{e09b467 com.example.hello/10192} due to missing metadata
,08-03 17:29:14.151   773   934 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-03 17:29:14.151   326   326 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-03 17:29:14.161   773   934 I art     : Starting a blocking GC Explicit
,08-03 17:29:14.261   773   934 I art     : Explicit concurrent mark sweep GC freed 141069(8MB) AllocSpace objects, 111(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.328ms total 108.506ms
,08-03 17:29:14.291   773   934 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-03 17:29:14.291   773   934 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-03 17:29:14.291   773   934 D AASAinstall: there is not AASApackages.xml file
08-03 17:29:14.291   773   934 D PackageManager: result of delete: 1{88914497}
,08-03 17:29:14.291  7209  7209 I art     : System.exit called, status: 0
08-03 17:29:14.291  7209  7209 I AndroidRuntime: VM exiting with result code 0.
,08-03 17:29:14.301   773   934 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-03 17:29:14.301   773   934 D PackageManager: userId{-1}
08-03 17:29:14.301   773   934 D PackageManager: andCode{true}
,08-03 17:29:14.311   773   934 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-03 17:29:14.321  6459  7239 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-03 17:29:14.321  6459  7239 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-03 17:29:14.331  6459  7239 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-03 17:29:14.381   773   773 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.381   773   773 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.381   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.381  1381  1381 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-03 17:29:14.381  1381  1381 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.391   773   852 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-03 17:29:14.391   773   852 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.391   773   773 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.391   773   903 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.401   773   773 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.401   773   773 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.411   773   903 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.411   773  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 17:29:14.411  1945  2173 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 17:29:14.411   773   773 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.411   773   773 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.411   773   773 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.411   773   773 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.411  2022  2022 E SamsungIME: mOCRHelper is null
,08-03 17:29:14.421   773   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f04d058 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc41e1 4289:com.samsung.klmsagent/u0a18}
,08-03 17:29:14.421   773   773 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.421   773   773 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.421   773   773 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.421   773   773 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.421   773   773 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.421   773   773 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.431   773   773 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.431  1676  1676 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-03 17:29:14.431  4289  4289 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Aug 03 17:29:14 GMT+02:00 2016
,08-03 17:29:14.431   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.431   773   852 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.441   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.441   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.441  4289  4289 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-03 17:29:14.441  3188  3203 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-03 17:29:14.441   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.441   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451  3188  3203 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-03 17:29:14.451   773  2335 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f04d058 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e1e390 773:system/1000}
,08-03 17:29:14.451  3188  3203 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-03 17:29:14.451  3188  3203 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773  2374 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.451   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.461  4289  4289 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-03 17:29:14.461  4289  4289 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-03 17:29:14.461  4289  4289 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-03 17:29:14.461  4289  7255 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-03 17:29:14.461  4289  7255 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-03 17:29:14.461  4289  7255 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-03 17:29:14.461  4289  7255 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-03 17:29:14.461  4289  7255 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-03 17:29:14.461  4289  7255 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-03 17:29:14.461   773   773 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.461   773   773 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.461  4289  7255 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-03 17:29:14.471   773  1366 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/115_task.xml
08-03 17:29:14.471  4289  7255 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-03 17:29:14.471   773   773 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.471   773   773 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.471   773  1321 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-03 17:29:14.471   773  1321 D NtpTrustedTime: currentTimeMillis() cache hit
08-03 17:29:14.471   773  1321 V NetworkStats: performPollLocked(flags=0x3)
,08-03 17:29:14.471   773  1322 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
,08-03 17:29:14.471   773   773 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.471   773   773 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.471   773   852 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.471   773  1322 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-03 17:29:14.481   773   852 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.481  4289  7255 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-03 17:29:14.481  4289  7255 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-03 17:29:14.481  4289  7255 W System.err: mkdir failed: ENOENT (No such file or directory) : /data/user/0/com.samsung.klmsagent/databases
,08-03 17:29:14.481  4289  7255 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (2)
08-03 17:29:14.481  4289  7255 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131072) and mode_t (0) due to error (2)
08-03 17:29:14.481  4289  7255 E SQLiteLog: (14) cannot open file at line 31517 of [2ef4f3a5b1]
08-03 17:29:14.481  4289  7255 E SQLiteLog: (14) os_unix.c:31517: (2) open(/data/user/0/com.samsung.klmsagent/databases/klms.db) - 
,08-03 17:29:14.491   773  1321 V NetworkStats: performPollLocked() took 17ms
08-03 17:29:14.491   773  1321 D NtpTrustedTime: currentTimeMillis() cache hit
,08-03 17:29:14.491  4289  7255 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x733093a8 in tid 7255 (IntentService[K)
,08-03 17:29:14.491   773  1321 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9cf2fc39 in tid 1321 (NetworkStats)
,08-03 17:29:14.491   773   773 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.491   773   773 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.491  1666  7257 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-03 17:29:14.491  2307  2307 E audit_log: File locking failed. error= Bad file descriptor
,08-03 17:29:14.501  1666  7257 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-03 17:29:14.501  1666  7257 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-03 17:29:14.501  1666  7257 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-03 17:29:14.501  1666  7257 D RegisteredComponentCache: Collect Tech packages for Knox
,08-03 17:29:14.501  2307  2307 E audit_log: File locking failed. error= Bad file descriptor
,08-03 17:29:14.501   773  1298 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-03 17:29:14.501   773   773 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-03 17:29:14.501   773   773 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-03 17:29:14.501  2307  2307 E audit_log: File locking failed. error= Bad file descriptor
,08-03 17:29:14.541   348   348 I Zygote  : Process 4289 exited due to signal (7)
,08-03 17:29:14.581   292   292 I ServiceManager: service 'telecom' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'SEAMService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'media.camera.proxy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'account' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'content' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'DirEncryptService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'LSManager' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'ReactiveService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'EngineeringModeService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'SatsService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sedenial' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'vibrator' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'tw_toolbox' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'tima' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'iccc' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'cepproxyks' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'emailksproxy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'consumer_ir' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'alarm' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'input_method' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'accessibility' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'cover' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'mount' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'lock_settings' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'deviceidle' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'device_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'harmony_eas_service' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sdp' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sdp_log' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'dlp' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'log_manager_service' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'display' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'persona_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'user' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'package' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'procstats' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'meminfo' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'gfxinfo' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'dbinfo' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'cpuinfo' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'permission' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'processinfo' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sensorservice' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'battery' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'usagestats' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'webviewupdate' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'scheduling_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'telephony.registry' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'persona' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sec_analytics' died
08-03 17:29:14.581   292   ,292 I ServiceManager: service 'servicediscovery' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'updatelock' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'notification' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'location' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'country_detector' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sec_location' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'search' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'execute' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'dropbox' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'wallpaper' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'audio' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'DockObserver' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'midi' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'usb' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'serial' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'kiesusb' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'jobscheduler' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'backup' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'appwidget' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'voiceinteraction' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'diskstats' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'mDNIe' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'AAS' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'MSCS' died
08-03 17:29:14.581  2362  2383 W Sensors : sensorservice died [0xb3f96c80]
08-03 17:29:14.581   292   292 I ServiceManager: service 'spengestureservice' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'quickconnect' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'samplingprofiler' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'commontime_management' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'dreams' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'graphicsstats' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'print' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'restrictions' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'media_session' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'media_router' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'trust' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'fingerprint' died,
,08-03 17:29:14.581   292   292 I ServiceManager: service 'launcherapps' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'voip' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'media_projection' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'lpnet' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'context_aware' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'scontext' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'barbeam' died
,08-03 17:29:14.581   292   292 I ServiceManager: service 'multiwindow_facade' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'window' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'input' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'bluetooth_manager' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'rcp' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'enterprise_license_policy' died
,08-03 17:29:14.581  1692  1706 W Sensors : sensorservice died [0xb4823380]
08-03 17:29:14.581   292   292 I ServiceManager: service 'application_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'wifi_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-03 17:29:14.591  2307  2307 E audit_log: File locking failed. error= Bad file descriptor
08-03 17:29:14.581   292   292 I ServiceManager: service 'remoteinjection' died
08-03 17:29:14.591  2307  2307 E audit_log: File locking failed. error= Bad file descriptor
,08-03 17:29:14.581   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'edm_proxy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'mum_container_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'otp_service' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
,08-03 17:29:14.581   292   292 I ServiceManager: service 'enterprise_policy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'statusbar' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'clipboard' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'clipboardEx' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'network_management' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'imms' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'textservices' died
,08-03 17:29:14.581   292   292 I ServiceManager: service 'network_score' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'netstats' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'netpolicy' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'wifip2p' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'wifi' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'wifihs20' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'wifiscanner' died
,08-03 17:29:14.581   292   292 I ServiceManager: service 'rttmanager' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'ethernet' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'connectivity' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'sb_service' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'edmnativehelper' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'activity' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'uimode' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'batterystats' died
,08-03 17:29:14.581   292   292 I ServiceManager: service 'appops' died
08-03 17:29:14.581   292   292 I ServiceManager: service 'power' died
08-03 17:29:14.581   317   317 W AudioFlinger: power manager service died !!!
08-03 17:29:14.581   317   317 W AudioFlinger: power manager service died !!!
08-03 17:29:14.581   293  1789 D libEGL  : eglTerminate EGLDisplay = 0xb476f6fc
08-03 17:29:14.581   293  1789 D libEGL  : eglTerminate EGLDisplay = 0xb476f6fc
08-03 17:29:14.581  1945  1964 W Sensors : sensorservice died [0xad826a40]
,08-03 17:29:14.581   293   373 I SurfaceFlinger: id=5 Removed TtatusBar (9/10)
08-03 17:29:14.581   293   373 I SurfaceFlinger: id=5 Removed TtatusBar (-2/10)
08-03 17:29:14.581   293   373 I SurfaceFlinger: id=6 Removed JmageWallpa (3/9)
08-03 17:29:14.581   293   373 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/9)
08-03 17:29:14.581  1803  1928 E WifiManager: Channel connection lost
08-03 17:29:14.581   293   380 I SurfaceFlinger: restart the boot-animation @ binderDied
08-03 17:29:14.591  2301  2301 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9eedf30a in tid 2301 (droid.bluetooth)
08-03 17:29:14.591  1666  1666 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x716012bd in tid 1666 (com.android.nfc)
08-03 17:29:14.591  2301  2301 F libc    : Unable to open connection to debuggerd: Connection refused
08-03 17:29:14.591  1666  1666 F libc    : Unable to open connection to debuggerd: Connection refused
,08-03 17:29:14.591  1945  2172 E WifiManager: Channel connection lost
08-03 17:29:14.591  1676  1676 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-03 17:29:14.591  1676  2170 E WifiManager: Channel connection lost
08-03 17:29:14.591  1381  1985 W Sensors : sensorservice died [0xaa3d4c80]
08-03 17:29:14.591  2822  2833 W Sensors : sensorservice died [0xadaa6d00]
,08-03 17:29:14.591  1381  1634 E WifiManager: Channel connection lost
,08-03 17:29:14.601  1958  1983 W Sensors : sensorservice died [0xb3f96d00]
,08-03 17:29:14.601  2822  3159 E WifiManager: Channel connection lost
,08-03 17:29:14.601  6181  6251 E WifiManager: Channel connection lost
,08-03 17:29:14.611   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=20 Removed Mauncher (3/8)
08-03 17:29:14.611   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=8 Removed EimLayer(Di (5/7)
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=9 Removed EimLayer(An (2/6)
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=13 Removed DolorFade (5/5)
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=13 Removed DolorFade (-2/5)
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=19 Removed VSBConnecti (3/4)
08-03 17:29:14.611   293   373 I SurfaceFlinger: id=18 Removed VSBConnecti (3/3)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=8 Removed EimLayer(Di (-2/3)
08-03 17:29:14.611   293  5977 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/3)
08-03 17:29:14.611   293  5977 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/3)
08-03 17:29:14.611   293  5977 I SurfaceFlinger: id=20 Removed Mauncher (-2/3)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=9 Removed EimLayer(An (-2/0)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
08-03 17:29:14.611   293  1789 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-03 17:29:14.621   292   292 I ServiceManager: service 'nfc' died
08-03 17:29:14.621   292   292 I ServiceManager: service 'secontroller' died
08-03 17:29:14.621   292   292 I ServiceManager: service 'nfccontroller' died
,08-03 17:29:14.631  2350  2350 D BluetoothA2dp: Proxy object disconnected
08-03 17:29:14.631  2822  2822 D BluetoothA2dp: Proxy object disconnected
08-03 17:29:14.631  2822  2822 D A2dpProfile: Bluetooth service disconnected
08-03 17:29:14.631  2822  2822 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 17:29:14.631  2822  2822 D PanProfile: Bluetooth service disconnected
08-03 17:29:14.631  2822  2822 D BluetoothMap: Proxy object disconnected
08-03 17:29:14.631  2822  2822 D MapProfile: Bluetooth service disconnected
,08-03 17:29:14.631  2822  2822 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ba122bd in tid 2822 (ndroid.settings)
,08-03 17:29:14.631  2822  2822 F libc    : Unable to open connection to debuggerd: Connection refused
08-03 17:29:14.631  2307  2307 E audit_log: File locking failed. error= Bad file descriptor
,08-03 17:29:14.661   348   348 I Zygote  : Process 1666 exited due to signal (7)
,08-03 17:29:14.691   348   348 I Zygote  : Process 2301 exited due to signal (7)
,08-03 17:29:14.721   348   348 I Zygote  : Process 2822 exited due to signal (7)
,08-03 17:29:14.861   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
08-03 17:29:14.861   293   546 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-03 17:29:15.031   320   320 E installd: eof
08-03 17:29:15.031   320   320 E installd: failed to read size
08-03 17:29:15.031   320   320 I installd: closing connection
,08-03 17:29:15.031   291   291 I lowmemorykiller: ActivityManager disconnected
08-03 17:29:15.031   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-03 17:29:15.111   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-03 17:29:15.111   293   546 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-03 17:29:15.111   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f738c
08-03 17:29:15.111   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f738c
,08-03 17:29:15.111   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f738c
08-03 17:29:15.111   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
,08-03 17:29:15.121   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f738c
,08-03 17:29:15.121   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4
,08-03 17:29:15.121   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f738c
,08-03 17:29:15.121   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f738c
,08-03 17:29:15.121   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe8f73a4

```
