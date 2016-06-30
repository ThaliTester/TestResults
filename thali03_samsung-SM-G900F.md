#### Test 757892682551a10_thali03_samsung-SM-G900F Logs


```
--------- beginning of system
06-30 13:51:59.478   757  3339 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:51:59.988   757  1237 V AlarmManager: Expired Alarm result :8
--------- beginning of main
06-30 13:52:00.418  2280  2280 E audit   : type=1400 msg=audit(1467287520.418:275): avc:  denied  { execmod } for  pid=6115 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:52:00.428  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:00.428  2280  2280 E audit   : type=1300 msg=audit(1467287520.418:275): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3476 ppcomm=adbd pid=6115 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:52:00.428  2280  2280 E audit   : type=1327 msg=audit(1467287520.418:275): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 13:52:00.428  2280  2280 E audit   : type=1320 msg=audit(1467287520.418:275): 
06-30 13:52:00.498  2280  2280 E audit   : type=1400 msg=audit(1467287520.498:276): avc:  denied  { execmod } for  pid=6115 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:52:00.498  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:00.508  2280  2280 E audit   : type=1300 msg=audit(1467287520.498:276): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3a000 a1=51000 a2=5 a3=4 items=0 ppid=3476 ppcomm=adbd pid=6115 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:52:00.508  2280  2280 E audit   : type=1327 msg=audit(1467287520.498:276): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 13:52:00.508  2280  2280 E audit   : type=1320 msg=audit(1467287520.498:276): 
06-30 13:52:00.548  2280  2280 E audit   : type=1400 msg=audit(1467287520.548:277): avc:  denied  { execmod } for  pid=6115 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:52:00.548  6115  6115 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:52:00.548  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:00.548  2280  2280 E audit   : type=1300 msg=audit(1467287520.548:277): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3b000 a1=51000 a2=5 a3=4 items=0 ppid=3476 ppcomm=adbd pid=6115 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:52:00.548  2280  2280 E audit   : type=1327 msg=audit(1467287520.548:277): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 13:52:00.548  2280  2280 E audit   : type=1320 msg=audit(1467287520.548:277): 
06-30 13:52:00.558  6115  6115 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:00.558  6115  6115 D AndroidRuntime: readGMSProperty: start
06-30 13:52:00.558  6115  6115 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:52:00.558  6115  6115 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:52:00.558  6115  6115 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:52:00.558  6115  6115 D AndroidRuntime: readGMSProperty: end
06-30 13:52:00.558  6115  6115 D AndroidRuntime: addProductProperty: start
06-30 13:52:00.558  6115  6115 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 13:52:00.558  6115  6115 W art     : af0e4000-b200a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:52:00.558  6115  6115 W art     : b200a000-b4279000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:52:00.558  6115  6115 W art     : b4279000-b427a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:52:00.558  6115  6115 W art     : b427a000-b42a3000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 13:52:00.558  6115  6115 W art     : b42a3000-b46f1000 r-xp 00000000 b3:17 594        /system/lib/libart.so
06-30 13:52:00.558  6115  6115 W art     : b46f1000-b46f2000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b46f2000-b46fc000 r--p 0044e000 b3:17 594        /system/lib/libart.so
06-30 13:52:00.558  6115  6115 W art     : b46fc000-b46fd000 rw-p 00458000 b3:17 594        /system/lib/libart.so
06-30 13:52:00.558  6115  6115 W art     : b46fd000-b46ff000 rw-p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b46ff000-b4700000 r--p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 13:52:00.558  6115  6115 W art     : b4808000-b480b000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
06-30 13:52:00.558  6115  6115 W art     : b480b000-b480c000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
06-30 13:52:00.558  6115  6115 W art     : b480c000-b480d000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
06-30 13:52:00.558  6115  6115 W art     : b480d000-b480e000 r--p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b480e000-b482e000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 13:52:00.558  6115  6115 W art     : b482e000-b523f000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
06-30 13:52:00.558  6115  6115 W art     : b523f000-b5240000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b5240000-b5289000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
06-30 13:52:00.558  6115  6115 W art     : b5289000-b528a000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
06-30 13:52:00.558  6115  6115 W art     : b528a000-b5292000 rw-p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b5292000-b5293000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.558  6115  6115 W art     : b5293000-b52c8000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
06-30 13:52:00.558  6115  6115 W art     : b52c8000-b52c9000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b52c9000-b52ca000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
06-30 13:52:00.558  6115  6115 W art     : b52ca000-b52cb000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
06-30 13:52:00.558  6115  6115 W art     : b52cb000-b5323000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
06-30 13:52:00.558  6115  6115 W art     : b5323000-b5324000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b5324000-b5325000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
06-30 13:52:00.558  6115  6115 W art     : b5325000-b5326000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
06-30 13:52:00.558  6115  6115 W art     : b5327000-b532d000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:52:00.558  6115  6115 W art     : b532d000-b532e000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:52:00.558  6115  6115 W art     : b532e000-b532f000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:52:00.558  6115  6115 W art     : b532f000-b5331000 rw-p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b5332000-b533c000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 13:52:00.558  6115  6115 W art     : b533c000-b533f000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 13:52:00.558  6115  6115 W art     : b533f000-b5340000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 13:52:00.558  6115  6115 W art     : b5341000-b5358000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 13:52:00.558  6115  6115 W art     : b5358000-b5359000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b5359000-b535a000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 13:52:00.558  6115  6115 W art     : b535a000-b535b000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 13:52:00.558  6115  6115 W art     : b535c000-b5366000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
06-30 13:52:00.558  6115  6115 W art     : b5366000-b5367000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
06-30 13:52:00.558  6115  6115 W art     : b5367000-b5368000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
06-30 13:52:00.558  6115  6115 W art     : b5368000-b536c000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 13:52:00.558  6115  6115 W art     : b536c000-b536d000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 13:52:00.558  6115  6115 W art     : b536d000-b536e000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 13:52:00.558  6115  6115 W art     : b536e000-b5384000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
06-30 13:52:00.558  6115  6115 W art     : b5384000-b5385000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
06-30 13:52:00.558  6115  6115 W art     : b5385000-b5386000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
06-30 13:52:00.558  6115  6115 W art     : b5386000-b5393000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
06-30 13:52:00.558  6115  6115 W art     : b5393000-b5394000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
06-30 13:52:00.558  6115  6115 W art     : b5394000-b5395000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
06-30 13:52:00.558  6115  6115 W art     : b5395000-b53f5000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
06-30 13:52:00.558  6115  6115 W art     : b53f5000-b53f8000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
06-30 13:52:00.558  6115  6115 W art     : b53f8000-b53fc000 rw-p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b53fc000-b545d000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
06-30 13:52:00.558  6115  6115 W art     : b545d000-b545e000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
06-30 13:52:00.558  6115  6115 W art     : b545e000-b54ad000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
06-30 13:52:00.558  6115  6115 W art     : b54ad000-b54af000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
06-30 13:52:00.558  6115  6115 W art     : b54af000-b54b0000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
06-30 13:52:00.558  6115  6115 W art     : b54b0000-b54b1000 rw-p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b54b1000-b54b8000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 13:52:00.558  6115  6115 W art     : b54b8000-b54b9000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 13:52:00.558  6115  6115 W art     : b54b9000-b54ba000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_
06-30 13:52:00.558  6115  6115 W art     : avc_common.so
06-30 13:52:00.558  6115  6115 W art     : b54bb000-b54be000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 13:52:00.558  6115  6115 W art     : b54be000-b54bf000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 13:52:00.558  6115  6115 W art     : b54bf000-b54c0000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_
06-30 13:52:00.558  6115  6115 W art     : enc_common.so
06-30 13:52:00.558  6115  6115 W art     : b54c1000-b54c5000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
06-30 13:52:00.558  6115  6115 W art     : b54c5000-b54c6000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b54c6000-b54c7000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
06-30 13:52:00.558  6115  6115 W art     : b54c7000-b54c8000 rw-p 00005000 b3:17 2517       /syste
06-30 13:52:00.558  6115  6115 W art     : m/lib/libpowermanager.so
06-30 13:52:00.558  6115  6115 W art     : b54c9000-b54e6000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 13:52:00.558  6115  6115 W art     : b54e6000-b54e7000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 13:52:00.558  6115  6115 W art     : b54e7000-b54e8000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 13:52:00.558  6115  6115 W art     : b54e9000-b54ee000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 13:52:00.558  6115  6115 W art     : b54ee000-b54ef000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 13:52:00.558  6115  6115 W art     : b54ef000-b54f0000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 13:52:00.558  6115  6115 W art     : b54f1000-b5522000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 13:52:00.558  6115  6115 W art     : b5522000-b5525000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 13:52:00.558  6115  6115 W art     : b5525000-b5526000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 13:52:00.558  6115  6115 W art     : b5527000-b5562000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
06-30 13:52:00.558  6115  6115 W art     : b5562000-b5563000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
06-30 13:52:00.558  6115  6115 W art     : b5563000-b5564000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
06-30 13:52:00.558  6115  6115 W art     : b5565000-b556c000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
06-30 13:52:00.558  6115  6115 W art     : b556c000-b556d000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b556d000-b556e000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
06-30 13:52:00.558  6115  6115 W art     : b556e000-b556f000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
06-30 13:52:00.558  6115  6115 W art     : b556f000-b5570000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.558  6115  6115 W art     : b5570000-b5587000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
06-30 13:52:00.558  6115  6115 W art     : b5587000-b5588000 ---p 00000000 00:00 0 
06-30 13:52:00.558  6115  6115 W art     : b5588000-b558b000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
06-30 13:52:00.568  6115  6115 W art     : b558b000-b558c000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
06-30 13:52:00.568  6115  6115 W art     : b558c000-b55ab000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
06-30 13:52:00.568  6115  6115 W art     : b55ab000-b55ac000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
06-30 13:52:00.568  6115  6115 W art     : b55ac000-b55ad000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
06-30 13:52:00.568  6115  6115 W art     : b55ad000-b55eb000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 13:52:00.568  6115  6115 W art     : b55eb000-b55ec000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b55ec000-b55ee000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 13:52:00.568  6115  6115 W art     : b55ee000-b55ef000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 13:52:00.568  6115  6115 W art     : b55f0000-b55f7000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
06-30 13:52:00.568  6115  6115 W art     : b55f7000-b55f8000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
06-30 13:52:00.568  6115  6115 W art     : b55f8000-b55f9000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
06-30 13:52:00.568  6115  6115 W art     : b55fa000-b55fd000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
06-30 13:52:00.568  6115  6115 W art     : b55fd000-b55fe000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
06-30 13:52:00.568  6115  6115 W art     : b55fe000-b55ff000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
06-30 13:52:00.568  6115  6115 W art     : b55ff000-b5605000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:52:00.568  6115  6115 W art     : b5605000-b5606000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5606000-b5607000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:52:00.568  6115  6115 W art     : b5607000-b5608000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:52:00.568  6115  6115 W art     : b5608000-b5611000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
06-30 13:52:00.568  6115  6115 W art     : b5611000-b5612000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
06-30 13:52:00.568  6115  6115 W art     : b5612000-b5613000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
06-30 13:52:00.568  6115  6115 W art     : b5613000-b56a4000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 13:52:00.568  6115  6115 W art     : b56a4000-b56a5000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b56a5000-b56b0000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 13:52:00.568  6115  6115 W art     : b56b0000-b56b1000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 13:52:00.568  6115  6115 W art     : b56b2000-b56c4000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
06-30 13:52:00.568  6115  6115 W art     : b56c4000-b56c5000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
06-30 13:52:00.568  6115  6115 W art     : b56c5000-b56c6000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
06-30 13:52:00.568  6115  6115 W art     : b56c7000-b56cc000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
06-30 13:52:00.568  6115  6115 W art     : b56cc000-b56cd000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
06-30 13:52:00.568  6115  6115 W art     : b56cd000-b56ce000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
06-30 13:52:00.568  6115  6115 W art     : b56cf000-b573c000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 13:52:00.568  6115  6115 W art     : b573c000-b573d000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b573d000-b573f000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 13:52:00.568  6115  6115 W art     : b573f000-b5740000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 13:52:00.568  6115  6115 W art     : b5740000-b5741000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5741000-b5748000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:52:00.568  6115  6115 W art     : b5748000-b5749000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:52:00.568  6115  6115 W art     : b5749000-b574a000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:52:00.568  6115  6115 W art     : b574b000-b57cb000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 13:52:00.568  6115  6115 W art     : b57cb000-b57cc000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b57cc000-b57cd000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 13:52:00.568  6115  6115 W art     : b57cd000-b57ce000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 13:52:00.568  6115  6115 W art     : b57ce000-b57e5000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b57e5000-b581c000 r-xp 00000000 b3:17 3247       /system/vendor/l
06-30 13:52:00.568  6115  6115 W art     : ib/libqc-opt.so
06-30 13:52:00.568  6115  6115 W art     : b581c000-b581d000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 13:52:00.568  6115  6115 W art     : b581d000-b581e000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 13:52:00.568  6115  6115 W art     : b581e000-b583a000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 13:52:00.568  6115  6115 W art     : b583a000-b583b000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 13:52:00.568  6115  6115 W art     : b583b000-b583c000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 13:52:00.568  6115  6115 W art     : b583d000-b589e000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 13:52:00.568  6115  6115 W art     : b589e000-b58a0000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 13:52:00.568  6115  6115 W art     : b58a0000-b58a1000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 13:52:00.568  6115  6115 W art     : b58a2000-b58c9000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
06-30 13:52:00.568  6115  6115 W art     : b58c9000-b58ca000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b58ca000-b58cb000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
06-30 13:52:00.568  6115  6115 W art     : b58cb000-b58cc000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
06-30 13:52:00.568  6115  6115 W art     : b58cd000-b58d5000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 13:52:00.568  6115  6115 W art     : b58d5000-b58d7000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 13:52:00.568  6115  6115 W art     : b58d7000-b58d8000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 13:52:00.568  6115  6115 W art     : b58d9000-b58dc000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
06-30 13:52:00.568  6115  6115 W art     : b58dc000-b58dd000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
06-30 13:52:00.568  6115  6115 W art     : b58dd000-b58de000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
06-30 13:52:00.568  6115  6115 W art     : b58de000-b58e2000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
06-30 13:52:00.568  6115  6115 W art     : b58e2000-b58e3000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b58e3000-b58e4000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
06-30 13:52:00.568  6115  6115 W art     : b58e4000-b58e5000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
06-30 13:52:00.568  6115  6115 W art     : b58e5000-b58f5000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
06-30 13:52:00.568  6115  6115 W art     : b58f5000-b58f6000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
06-30 13:52:00.568  6115  6115 W art     : b58f6000-b58f7000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
06-30 13:52:00.568  6115  6115 W art     : b58f7000-b593d000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b593d000-b5946000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
06-30 13:52:00.568  6115  6115 W art     : b5946000-b5947000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
06-30 13:52:00.568  6115  6115 W art     : b5947000-b5948000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
06-30 13:52:00.568  6115  6115 W art     : b5949000-b594e000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
06-30 13:52:00.568  6115  6115 W art     : b594e000-b594f000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
06-30 13:52:00.568  6115  6115 W art     : b594f000-b5950000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
06-30 13:52:00.568  6115  6115 W art     : b5950000-b5953000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 13:52:00.568  6115  6115 W art     : b5953000-b5954000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5954000-b5955000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 13:52:00.568  6115  6115 W art     : b5955000-b5956000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 13:52:00.568  6115  6115 W art     : b5957000-b596f000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:52:00.568  6115  6115 W art     : b596f000-b5970000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5970000-b5971000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:52:00.568  6115  6115 W art     : b5971000-b5972000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:52:00.568  6115  6115 W art     : b5973000-b5b0d000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
06-30 13:52:00.568  6115  6115 W art     : b5b0d000-b5b0e000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5b0e000-b5b1b000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
06-30 13:52:00.568  6115  6115 W art     : b5b1b000-b5b1c000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
06-30 13:52:00.568  6115  6115 W art     : b5b1c000-b5b20000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
06-30 13:52:00.568  6115  6115 W art     : b5b20000-b5b21000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5b21000-b5b22000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
06-30 13:52:00.568  6115  6115 W art     : b5b22000-b5b23000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
06-30 13:52:00.568  6115  6115 W art     : b5b23000-b5b36000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
06-30 13:52:00.568  6115  6115 W art     : b5b36000-b5b37000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
06-30 13:52:00.568  6115  6115 W art     : b5b37000-b5b38000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
06-30 13:52:00.568  6115  6115 W art     : b5b38000-b5b39000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:00.568  6115  6115 W art     : b5b39000-b5b84000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 13:52:00.568  6115  6115 W art     : b5b84000-b5b85000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 13:52:00.568  6115  6115 W art     : b5b85000-b5b86000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 13:52:00.568  6115  6115 W art     : b5b86000-b5b88000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5b89000-b5b9a000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 13:52:00.568  6115  6115 W art     : b5b9a000-b5b9b000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5b9b000-b5b9c000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 13:52:00.568  6115  6115 W art     : b5b9c000-b5b9d000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 13:52:00.568  6115  6115 W art     : b5b9e000-b5ba8000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
06-30 13:52:00.568  6115  6115 W art     : b5ba8000-b5baa000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
06-30 13:52:00.568  6115  6115 W art     : b5baa000-b5bab000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
06-30 13:52:00.568  6115  6115 W art     : b5bab000-b5bc4000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
06-30 13:52:00.568  6115  6115 W art     : b5bc4000-b5bc5000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
06-30 13:52:00.568  6115  6115 W art     : b5bc5000-b5bc8000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
06-30 13:52:00.568  6115  6115 W art     : b5bc8000-b5bcc000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5bcc000-b5c40000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
06-30 13:52:00.568  6115  6115 W art     : b5c40000-b5c41000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5c41000-b5c44000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
06-30 13:52:00.568  6115  6115 W art     : b5c44000-b5c45000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
06-30 13:52:00.568  6115  6115 W art     : b5c45000-b5c46000 r--p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5c46000-b5c49000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
06-30 13:52:00.568  6115  6115 W art     : b5c49000-b5c4a000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
06-30 13:52:00.568  6115  6115 W art     : b5c4a000-b5c4b000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
06-30 13:52:00.568  6115  6115 W art     : b5c4b000-b5c4c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5c4c000-b5c51000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 13:52:00.568  6115  6115 W art     : b5c51000-b5c52000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 13:52:00.568  6115  6115 W art     : b5c52000-b5c53000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 13:52:00.568  6115  6115 W art     : b5c53000-b5c54000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5c54000-b5c57000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 13:52:00.568  6115  6115 W art     : b5c57000-b5c58000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 13:52:00.568  6115  6115 W art     : b5c58000-b5c59000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 13:52:00.568  6115  6115 W art     : b5c59000-b5c5a000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5c5a000-b5c5e000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
06-30 13:52:00.568  6115  6115 W art     : b5c5e000-b5c5f000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
06-30 13:52:00.568  6115  6115 W art     : b5c5f000-b5c60000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
06-30 13:52:00.568  6115  6115 W art     : b5c60000-b5c61000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:00.568  6115  6115 W art     : b5c61000-b5c65000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 13:52:00.568  6115  6115 W art     : b5c65000-b5c66000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 13:52:00.568  6115  6115 W art     : b5c66000-b5c67000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 13:52:00.568  6115  6115 W art     : b5c67000-b5c68000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5c68000-b5c76000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 13:52:00.568  6115  6115 W art     : b5c76000-b5c77000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b5c77000-b5c78000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 13:52:00.568  6115  6115 W art     : b5c78000-b5c79000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 13:52:00.568  6115  6115 W art     : b5c79000-b5c83000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 13:52:00.568  6115  6115 W art     : b5c83000-b5c86000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 13:52:00.568  6115  6115 W art     : b5c86000-b5c87000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 13:52:00.568  6115  6115 W art     : b5c87000-b5c88000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5c88000-b5c92000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
06-30 13:52:00.568  6115  6115 W art     : b5c92000-b5c95000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
06-30 13:52:00.568  6115  6115 W art     : b5c95000-b5c96000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
06-30 13:52:00.568  6115  6115 W art     : b5c96000-b5c9a000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
06-30 13:52:00.568  6115  6115 W art     : b5c9a000-b5c9b000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
06-30 13:52:00.568  6115  6115 W art     : b5c9b000-b5c9c000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
06-30 13:52:00.568  6115  6115 W art     : b5c9c000-b5c9d000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b5c9d000-b5caa000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:52:00.568  6115  6115 W art     : b5caa000-b5cac000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:52:00.568  6115  6115 W art     : b5cac000-b5cad000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:52:00.568  6115  6115 W art     : b5cad000-b60bf000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
06-30 13:52:00.568  6115  6115 W art     : b60bf000-b60c0000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b60c0000-b60c9000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
06-30 13:52:00.568  6115  6115 W art     : b60c9000-b60cd000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
06-30 13:52:00.568  6115  6115 W art     : b60cd000-b60ce000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b60ce000-b60d5000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:52:00.568  6115  6115 W art     : b60d5000-b60d6000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:52:00.568  6115  6115 W art     : b60d6000-b60d7000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:52:00.568  6115  6115 W art     : b60d7000-b60d8000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b60d8000-b60f3000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 13:52:00.568  6115  6115 W art     : b60f3000-b60f4000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 13:52:00.568  6115  6115 W art     : b60f4000-b60f5000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 13:52:00.568  6115  6115 W art     : b60f5000-b60f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b60f6000-b6142000 r-xp 00000000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 13:52:00.568  6115  6115 W art     : b6142000-b6143000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6143000-b6144000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 13:52:00.568  6115  6115 W art     : b6144000-b6145000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 13:52:00.568  6115  6115 W art     : b6145000-b6146000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6146000-b614a000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
06-30 13:52:00.568  6115  6115 W art     : b614a000-b614b000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b614b000-b614c000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
06-30 13:52:00.568  6115  6115 W art     : b614c000-b614d000 rw-p 00005000 b3:17 2688       /system/lib/libusbhost.so
06-30 13:52:00.568  6115  6115 W art     : b614d000-b6185000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
06-30 13:52:00.568  6115  6115 W art     : b6185000-b6186000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
06-30 13:52:00.568  6115  6115 W art     : b6186000-b6187000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
06-30 13:52:00.568  6115  6115 W art     : b6187000-b6188000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6188000-b6226000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
06-30 13:52:00.568  6115  6115 W art     : b6226000-b6227000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6227000-b6245000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
06-30 13:52:00.568  6115  6115 W art     : b6245000-b6246000 rw-p 000bc000 b3:17 409        /system/lib/libmedia.so
06-30 13:52:00.568  6115  6115 W art     : b6246000-b63b9000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
06-30 13:52:00.568  6115  6115 W art     : b63b9000-b63c4000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
06-30 13:52:00.568  6115  6115 W art     : b63c4000-b63c5000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
06-30 13:52:00.568  6115  6115 W art     : b63c5000-b64dc000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:52:00.568  6115  6115 W art     : b64dc000-b64e7000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:52:00.568  6115  6115 W art     : b64e7000-b64e8000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:52:00.568  6115  6115 W art     : b64e8000-b64ec000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b64ec000-b6510000 r-xp 00000000 b3:17 405        /system/lib/libssl.so
06-30 13:52:00.568  6115  6115 W art     : b6510000-b6512000 r--p 00023000 b3:17 405        /system/lib/libssl.so
06-30 13:52:00.568  6115  6115 W art     : b6512000-b6513000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
06-30 13:52:00.568  6115  6115 W art     : b6513000-b65b9000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
06-30 13:52:00.568  6115  6115 W art     : b65b9000-b65c6000 r--p 000a5000 b3:17 110        /system/lib/libcrypto.so
06-30 13:52:00.568  6115  6115 W art     : b65c6000-b65c7000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
06-30 13:52:00.568  6115  6115 W art     : b65c7000-b65c8000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b65c8000-b661b000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
06-30 13:52:00.568  6115  6115 W art     : b661b000-b661c000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b661c000-b661d000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
06-30 13:52:00.568  6115  6115 W art     : b661d000-b661e000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
06-30 13:52:00.568  6115  6115 W art     : b661e000-b6623000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6623000-b6635000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
06-30 13:52:00.568  6115  6115 W art     : b6635000-b6636000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6636000-b6637000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
06-30 13:52:00.568  6115  6115 W art     : b6637000-b6638000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
06-30 13:52:00.568  6115  6115 W art     : b6638000-b663f000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 13:52:00.568  6115  6115 W art     : b663f000-b6640000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 13:52:00.568  6115  6115 W art     : b6640000-b6641000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 13:52:00.568  6115  6115 W art     : b6641000-b6642000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6642000-b6645000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
06-30 13:52:00.568  6115  6115 W art     : b6645000-b6646000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
06-30 13:52:00.568  6115  6115 W art     : b6646000-b6647000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
06-30 13:52:00.568  6115  6115 W art     : b6647000-b664b000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
06-30 13:52:00.568  6115  6115 W art     : b664b000-b664c000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
06-30 13:52:00.568  6115  6115 W art     : b664c000-b664d000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
06-30 13:52:00.568  6115  6115 W art     : b664d000-b665b000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
06-30 13:52:00.568  6115  6115 W art     : b665b000-b665c000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b665c000-b665d000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
06-30 13:52:00.568  6115  6115 W art     : b665d000-b665e000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
06-30 13:52:00.568  6115  6115 W art     : b665e000-b6667000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 13:52:00.568  6115  6115 W art     : b6667000-b6668000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 13:52:00.568  6115  6115 W art     : b6668000-b6669000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 13:52:00.568  6115  6115 W art     : b6669000-b66cf000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
06-30 13:52:00.568  6115  6115 W art     : b66cf000-b66d0000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b66d0000-b66d2000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
06-30 13:52:00.568  6115  6115 W art     : b66d2000-b66db000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
06-30 13:52:00.568  6115  6115 W art     : b66db000-b66de000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b66de000-b6775000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 13:52:00.568  6115  6115 W art     : b6775000-b6777000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 13:52:00.568  6115  6115 W art     : b6777000-b6778000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 13:52:00.568  6115  6115 W art     : b6778000-b6779000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6779000-b6a9a000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
06-30 13:52:00.568  6115  6115 W art     : b6a9a000-b6a9b000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6a9b000-b6ab6000 r--p 00321000 b3:17 286        /system/lib/libskia.so
06-30 13:52:00.568  6115  6115 W art     : b6ab6000-b6aba000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
06-30 13:52:00.568  6115  6115 W art     : b6aba000-b6abf000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6abf000-b6ac7000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 13:52:00.568  6115  6115 W art     : b6ac7000-b6ac8000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 13:52:00.568  6115  6115 W art     : b6ac8000-b6ac9000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 13:52:00.568  6115  6115 W art     : b6ac9000-b6af7000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:52:00.568  6115  6115 W art     : b6af7000-b6af8000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6af8000-b6aff000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:52:00.568  6115  6115 W art     : b6aff000-b6b00000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:52:00.568  6115  6115 W art     : b6b00000-b6b46000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:52:00.568  6115  6115 W art     : b6b46000-b6b47000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6b47000-b6b4a000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:52:00.568  6115  6115 W art     : b6b4a000-b6b4b000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:52:00.568  6115  6115 W art     : b6b4b000-b6b66000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
06-30 13:52:00.568  6115  6115 W art     : b6b66000-b6b6a000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
06-30 13:52:00.568  6115  6115 W art     : b6b6a000-b6b6b000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
06-30 13:52:00.568  6115  6115 W art     : b6b6b000-b6bb8000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
06-30 13:52:00.568  6115  6115 W art     : b6bb8000-b6bb9000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6bb9000-b6bc5000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
06-30 13:52:00.568  6115  6115 W art     : b6bc5000-b6bc6000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
06-30 13:52:00.568  6115  6115 W art     : b6bc6000-b6bd3000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
06-30 13:52:00.568  6115  6115 W art     : b6bd3000-b6bd4000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6bd4000-b6bd5000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
06-30 13:52:00.568  6115  6115 W art     : b6bd5000-b6bd6000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
06-30 13:52:00.568  6115  6115 W art     : b6bd6000-b6bde000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
06-30 13:52:00.568  6115  6115 W art     : b6bde000-b6bdf000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6bdf000-b6be0000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
06-30 13:52:00.568  6115  6115 W art     : b6be0000-b6be1000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
06-30 13:52:00.568  6115  6115 W art     : b6be1000-b6be8000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:52:00.568  6115  6115 W art     : b6be8000-b6be9000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:52:00.568  6115  6115 W art     : b6be9000-b6bea000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:52:00.568  6115  6115 W art     : b6bea000-b6bfe000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
06-30 13:52:00.568  6115  6115 W art     : b6bfe000-b6c00000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
06-30 13:52:00.568  6115  6115 W art     : b6c00000-b6c01000 rw-p 00015000 b3:17 2082       /system/lib/libexpat.so
06-30 13:52:00.568  6115  6115 W art     : b6c01000-b6c29000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
06-30 13:52:00.568  6115  6115 W art     : b6c29000-b6c2b000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
06-30 13:52:00.568  6115  6115 W art     : b6c2b000-b6c2c000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
06-30 13:52:00.568  6115  6115 W art     : b6c2c000-b6c2f000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
06-30 13:52:00.568  6115  6115 W art     : b6c2f000-b6c30000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
06-30 13:52:00.568  6115  6115 W art     : b6c30000-b6c31000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
06-30 13:52:00.568  6115  6115 W art     : b6c31000-b6c3a000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:52:00.568  6115  6115 W art     : b6c3a000-b6c3b000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:52:00.568  6115  6115 W art     : b6c3b000-b6c3c000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:52:00.568  6115  6115 W art     : b6c3c000-b6c5c000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 13:52:00.568  6115  6115 W art     : b6c5c000-b6c5d000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 13:52:00.568  6115  6115 W art     : b6c5d000-b6c5e000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 13:52:00.568  6115  6115 W art     : b6c5e000-b6cd1000 r-xp 00000000 b3:17 328        /system/lib/libc.so
06-30 13:52:00.568  6115  6115 W art     : b6cd1000-b6cd5000 r--p 00072000 b3:17 328        /system/lib/libc.so
06-30 13:52:00.568  6115  6115 W art     : b6cd5000-b6cd8000 rw-p 00076000 b3:17 328        /system/lib/libc.so
06-30 13:52:00.568  6115  6115 W art     : b6cd8000-b6ce2000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6ce2000-b6d6a000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 13:52:00.568  6115  6115 W art     : b6d6a000-b6d6b000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6d6b000-b6d6f000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 13:52:00.568  6115  6115 W art     : b6d6f000-b6d70000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 13:52:00.568  6115  6115 W art     : b6d70000-b6d71000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6d71000-b6d9a000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:52:00.568  6115  6115 W art     : b6d9a000-b6d9b000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6d9b000-b6d9e000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:52:00.568  6115  6115 W art     : b6d9e000-b6d9f000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:52:00.568  6115  6115 W art     : b6d9f000-b6e79000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 13:52:00.568  6115  6115 W art     : b6e79000-b6e80000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 13:52:00.568  6115  6115 W art     : b6e80000-b6e88000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 13:52:00.568  6115  6115 W art     : b6e88000-b6e89000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6e89000-b6e8a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:00.568  6115  6115 W art     : b6e8a000-b6e8b000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 13:52:00.568  6115  6115 W art     : b6e8b000-b6e8c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6e8c000-b6e8f000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6e8f000-b6eb4000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
06-30 13:52:00.568  6115  6115 W art     : b6eb4000-b6eb5000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6eb5000-b6ebc000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
06-30 13:52:00.568  6115  6115 W art     : b6ebc000-b6ebd000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
06-30 13:52:00.568  6115  6115 W art     : b6ebd000-b6ec4000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 13:52:00.568  6115  6115 W art     : b6ec4000-b6ec5000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 13:52:00.568  6115  6115 W art     : b6ec5000-b6ec6000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 13:52:00.568  6115  6115 W art     : b6ec6000-b6ec7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6ec7000-b6edf000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
06-30 13:52:00.568  6115  6115 W art     : b6edf000-b6ee0000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6ee0000-b6ee1000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
06-30 13:52:00.568  6115  6115 W art     : b6ee1000-b6ee2000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
06-30 13:52:00.568  6115  6115 W art     : b6ee2000-b6ef0000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
06-30 13:52:00.568  6115  6115 W art     : b6ef0000-b6ef1000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6ef1000-b6ef2000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
06-30 13:52:00.568  6115  6115 W art     : b6ef2000-b6ef3000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
06-30 13:52:00.568  6115  6115 W art     : b6ef3000-b6ef4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:00.568  6115  6115 W art     : b6ef4000-b6ef6000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6ef6000-b6ef7000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6ef7000-b6ef8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:00.568  6115  6115 W art     : b6ef8000-b6ef9000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 13:52:00.568  6115  6115 W art     : b6ef9000-b6efa000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:00.568  6115  6115 W art     : b6efa000-b6f1a000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 13:52:00.568  6115  6115 W art     : b6f1a000-b6f1b000 r--p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6f1b000-b6f1c000 ---p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6f1c000-b6f1e000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 13:52:00.568  6115  6115 W art     : b6f1e000-b6f1f000 r-xp 00000000 00:00 0          [sigpage]
06-30 13:52:00.568  6115  6115 W art     : b6f1f000-b6f3a000 r-xp 00000000 b3:17 2771       /system/bin/linker
06-30 13:52:00.568  6115  6115 W art     : b6f3a000-b6f3b000 r--p 0001a000 b3:17 2771       /system/bin/linker
06-30 13:52:00.568  6115  6115 W art     : b6f3b000-b6f3d000 rw-p 0001b000 b3:17 2771       /system/bin/linker
06-30 13:52:00.568  6115  6115 W art     : b6f3d000-b6f3f000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : b6f3f000-b6f44000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 13:52:00.568  6115  6115 W art     : b6f44000-b6f45000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 13:52:00.568  6115  6115 W art     : b6f45000-b6f46000 rw-p 00000000 00:00 0 
06-30 13:52:00.568  6115  6115 W art     : bed0e000-bed2f000 rw-p 00000000 00:00 0          [stack]
06-30 13:52:00.568  6115  6115 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 13:52:00.618  6115  6115 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:52:00.668  6115  6115 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:52:00.678  6115  6115 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:52:00.698  6115  6115 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:52:00.708   757  1618 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
06-30 13:52:00.718   757  1618 D ActivityManager: mDVFSHelper.acquire()
06-30 13:52:00.718   757  1618 V WindowManager: addAppToken: AppWindowToken{c7cf3d4 token=Token{9cb7527 ActivityRecord{976abe6 u0 com.test.thalitest/.MainActivity t78}}} to stack=1 task=78 at 0
06-30 13:52:00.728   757   898 D SecWifiDisplayUtil: Metadata value : none
06-30 13:52:00.728   757   898 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ba2e96c V.E...... R.....ID 0,0-0,0}
06-30 13:52:00.728   757   898 D ISSUE_DEBUG: InputChannelName : 870cbca Starting com.test.thalitest
06-30 13:52:00.738   757  1618 D InputDispatcher: Focused application set to: xxxx
06-30 13:52:00.738   757  1618 I ActivityManager: Start proc 6130:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 13:52:00.738  6130  6130 E Zygote  : v2
06-30 13:52:00.738  6130  6130 I libpersona: KNOX_SDCARD checking this for 10004
06-30 13:52:00.738  6130  6130 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:00.738   757  1618 D InputDispatcher: Focus left window: 3585
06-30 13:52:00.738  6130  6130 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:52:00.738  6130  6130 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:00.738   757  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 13:52:00.738   757   852 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{eab301 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 13:52:00.738  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 13:52:00.738  6130  6130 E Zygote  : accessInfo : 0
06-30 13:52:00.738  6130  6130 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 13:52:00.738  6115  6115 D AndroidRuntime: Shutting down VM
06-30 13:52:00.748   292   292 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
06-30 13:52:00.768   757   898 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:757 uid:1000
06-30 13:52:00.768  6130  6130 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:00.768  6130  6130 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:00.768   757   898 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:00.768   757   898 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:757 uid:1000
06-30 13:52:00.768   757   898 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:00.768   757   898 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 13:52:00.768   757  1746 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 13:52:00.768   757  1746 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 13:52:00.778   757   852 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{870cbca u0 d0 Starting com.test.thalitest}
06-30 13:52:00.778  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 13:52:00.778   757  1746 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 13:52:00.788   757   850 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 13:52:00.818   757   898 V WindowStateAnimator: Finishing drawing window Window{870cbca u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 13:52:00.818   292   399 D libEGL  : eglTerminate EGLDisplay = 0xb677f64c
06-30 13:52:00.828   292   391 I SurfaceFlinger: id=13 Removed VSBConnecti (7/11)
06-30 13:52:00.828   292  1825 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
06-30 13:52:00.828   292   399 I SurfaceFlinger: id=14 Removed VSBConnecti (5/10)
06-30 13:52:00.828   292   399 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/10)
06-30 13:52:00.828   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbee913a4
06-30 13:52:00.828   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbee913a4
06-30 13:52:00.838  1699  1871 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
06-30 13:52:00.838   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbee91364
06-30 13:52:00.838  3585  3585 V ActivityThread: updateVisibility : ActivityRecord{997fb4c token=android.os.BinderProxy@31fb6c6 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 13:52:00.838  1699  1699 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
06-30 13:52:00.838   292  1824 D libEGL  : eglTerminate EGLDisplay = 0xb47ef64c
06-30 13:52:00.838   292  1824 D libEGL  : eglTerminate EGLDisplay = 0xb47ef64c
06-30 13:52:00.848   292   391 I SurfaceFlinger: id=7 Removed Mauncher (4/9)
06-30 13:52:00.848   292  1825 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
06-30 13:52:00.848   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbee913a4
06-30 13:52:00.848  2200  2211 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
06-30 13:52:00.848  1699  1699 V ActivityThread: updateVisibility : ActivityRecord{1c6f49 token=android.os.BinderProxy@6febc28 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 13:52:00.848  1699  1699 D Launcher: onTrimMemory. Level: 20
,06-30 13:52:01.088   757  1746 I WindowManager: Screenshot max retries 4 of Token{9cb7527 ActivityRecord{976abe6 u0 com.test.thalitest/.MainActivity t78}} appWin=Window{870cbca u0 d0 Starting com.test.thalitest} drawState=4
,06-30 13:52:01.098   757  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,06-30 13:52:01.108  6130  6130 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 13:52:01.118   757  3339 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:01.128  6130  6130 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 13:52:01.138  6130  6130 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 13:52:01.148  6130  6130 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,06-30 13:52:01.178  6130  6130 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 13:52:01.188  6130  6130 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 13:52:01.188  6130  6130 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3504-3507)
,06-30 13:52:01.188  6130  6130 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 13:52:01.218  6130  6145 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-30 13:52:01.228  6130  6130 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0e76b8}
,06-30 13:52:01.228  6130  6130 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 13:52:01.238  6130  6130 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 13:52:01.258  6130  6130 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-30 13:52:01.318  6130  6146 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,06-30 13:52:01.338  6130  6130 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 13:52:01.338  6130  6130 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 13:52:01.338  6130  6130 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 13:52:01.338  6130  6130 I Adreno-EGL: Local Branch: ss
06-30 13:52:01.338  6130  6130 I Adreno-EGL: Remote Branch: 
06-30 13:52:01.338  6130  6130 I Adreno-EGL: Local Patches: 
06-30 13:52:01.338  6130  6130 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:52:01.348  6130  6130 D libEGL  : eglInitialize EGLDisplay = 0xbe83cdac
,06-30 13:52:01.388   757  1618 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,06-30 13:52:01.388   757  1618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,06-30 13:52:01.448  6130  6130 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-30 13:52:01.458  6130  6130 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:52:01.458  6130  6130 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,06-30 13:52:01.458  6130  6130 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-30 13:52:01.458  6130  6130 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-30 13:52:01.468  6130  6130 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-30 13:52:01.478  6130  6130 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 13:52:01.518  6130  6130 D SecWifiDisplayUtil: Metadata value : none
,06-30 13:52:01.528  6130  6130 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7202956 I.E...... R.....ID 0,0-0,0}
,06-30 13:52:01.528  6130  6170 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:01.528   757   774 D ISSUE_DEBUG: InputChannelName : 768dbff com.test.thalitest/com.test.thalitest.MainActivity
,06-30 13:52:01.538   757  1746 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,06-30 13:52:01.538   757  1746 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:01.538   757   757 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 13:52:01.538   757   757 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 13:52:01.558  6130  6130 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6130
,06-30 13:52:01.558   757  1320 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6130 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:52:01.568  6130  6145 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-30 13:52:01.568  6130  6130 D SecWifiDisplayUtil: Metadata value : none
,06-30 13:52:01.578   292   292 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,06-30 13:52:01.588   757  1422 D InputDispatcher: Focus entered window: 6130
,06-30 13:52:01.588   757   898 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:757 uid:1000
,06-30 13:52:01.588   757   898 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:01.588   757   898 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:757 uid:1000
06-30 13:52:01.588   757   898 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 13:52:01.588  6130  6170 D libEGL  : eglInitialize EGLDisplay = 0x9c9bf7c4
06-30 13:52:01.598  6130  6170 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:01.628  6130  6130 V ActivityThread: updateVisibility : ActivityRecord{d0aa073 token=android.os.BinderProxy@53fe771 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 13:52:01.628  6130  6130 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,06-30 13:52:01.638  6130  6130 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 13:52:01.638   757  1711 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 13:52:01.648  6130  6130 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 13:52:01.678   757   774 V WindowStateAnimator: Finishing drawing window Window{768dbff u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-30 13:52:01.678  6130  6130 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 13:52:01.678  6130  6130 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@53fe771 time:113995
,06-30 13:52:01.688   757   898 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 13:52:01.688   757   757 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:01.688   757   898 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +596ms (total +963ms)
06-30 13:52:01.688   757   898 D ActivityManager: mDVFSHelper.release()
06-30 13:52:01.688   757   898 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{976abe6 u0 com.test.thalitest/.MainActivity t78} time:114005
,06-30 13:52:01.688   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbee91364
,06-30 13:52:01.688   757   757 I KnoxTimeoutHandler: SD activityfalse
,06-30 13:52:01.688   757   898 D ViewRootImpl: #3 mView = null
,06-30 13:52:01.688   292   391 I SurfaceFlinger: id=15 Removed uhalitest (7/9)
,06-30 13:52:01.698   292   399 I SurfaceFlinger: id=15 Removed uhalitest (-2/9)
,06-30 13:52:01.708  6130  6183 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:01.708  6130  6183 D libEGL  : eglInitialize EGLDisplay = 0x9a3d03ec
,06-30 13:52:01.708   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbee913a4
,06-30 13:52:01.738  6130  6130 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6130
,06-30 13:52:01.928  6130  6130 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:52:02.048  6130  6188 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1714423504
,06-30 13:52:02.048  6130  6188 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:02.048  6130  6188 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:02.048  6130  6188 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:02.048  6130  6188 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:02.048  6130  6188 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 13:52:02.048  6130  6188 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c088ee1 added. We now have 1 listener(s)
,06-30 13:52:02.058  6130  6188 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:3F:75:69
,06-30 13:52:02.058  6130  6188 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:3F:75:69"
,06-30 13:52:02.058  6130  6188 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:02.058  6130  6188 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:3F:75:69
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:02.068  6130  6188 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5db68f4 added. We now have 1 listener(s)
,06-30 13:52:02.068  6130  6188 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:52:02.068  6130  6188 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:02.068  6130  6188 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 13:52:02.068  6130  6188 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:02.068  6130  6188 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2,
,06-30 13:52:02.068  6130  6188 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3,
06-30 13:52:02.068  6130  6188 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2,
06-30 13:52:02.068  6130  6188 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:52:02.068  6130  6188 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:3F:75:69
06-30 13:52:02.078  6130  6188 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:02.078  6130  6188 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:02.078  6130  6188 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:02.078  6130  6188 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:02.078  6130  6188 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:52:02.098   757  3340 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null,
,06-30 13:52:02.108  6130  6130 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:02.288   757  3339 D SSRM:n  : SIOP:: AP = 400, PST = 453, CUR = 300, LCD = 0
,06-30 13:52:02.328  6130  6139 I art     : Background sticky concurrent mark sweep GC freed 50543(3MB) AllocSpace objects, 7(140KB) LOS objects, 30% free, 17MB/25MB, paused 717us total 130.779ms
,06-30 13:52:02.538  1447  1447 D Recents : onTaskStackChanged
,06-30 13:52:02.548  1447  1447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,06-30 13:52:03.198  6130  6192 W jxcore-log: Initializing JXcore engine
,06-30 13:52:03.198  6130  6192 W jxcore-log: JXcore engine is ready
,06-30 13:52:03.248  2280  2280 E audit   : type=1400 msg=audit(1467287523.248:278): avc:  denied  { ioctl } for  pid=6192 comm="Thread-863" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 13:52:03.248  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:03.248  2280  2280 E audit   : type=1300 msg=audit(1467287523.248:278): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9963f3c8 items=0 ppid=345 ppcomm=main pid=6192 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-863" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 13:52:03.248  2280  2280 E audit   : type=1327 msg=audit(1467287523.248:278): proctitle="com.test.thalitest"
06-30 13:52:03.248  2280  2280 E audit   : type=1320 msg=audit(1467287523.248:278): 
,06-30 13:52:03.248  2280  2280 E audit   : type=1400 msg=audit(1467287523.248:279): avc:  denied  { ioctl } for  pid=6192 comm="Thread-863" path="socket:[35563]" dev="sockfs" ino=35563 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 13:52:03.248  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:03.248  2280  2280 E audit   : type=1300 msg=audit(1467287523.248:279): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9963f3c8 items=0 ppid=345 ppcomm=main pid=6192 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-863" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 13:52:03.248  2280  2280 E audit   : type=1327 msg=audit(1467287523.248:279): proctitle="com.test.thalitest"
06-30 13:52:03.248  2280  2280 E audit   : type=1320 msg=audit(1467287523.248:279): 
,06-30 13:52:03.258  6130  6192 W jxcore-log: Starting JXcore engine
,06-30 13:52:03.328  6130  6192 W jxcore-log: Platform android
06-30 13:52:03.328  6130  6192 W jxcore-log: 
06-30 13:52:03.328  6130  6192 W jxcore-log: Process ARCH arm
06-30 13:52:03.328  6130  6192 W jxcore-log: 
,06-30 13:52:03.518  6130  6192 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:03.518  6130  6192 I jxcore-log: 
06-30 13:52:03.518  6130  6192 W jxcore-log: JXcore engine is started
,06-30 13:52:03.528  6130  6188 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:03.538   757  1547 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package null
,06-30 13:52:03.558   757  1547 D ActivityManager: mDVFSHelper.acquire()
,06-30 13:52:03.558   757  1547 V WindowManager: addAppToken: AppWindowToken{6f6c2ef token=Token{17af3ce ActivityRecord{3a5f0c9 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t78}}} to stack=1 task=78 at 1
,06-30 13:52:03.568   757  1547 I ActivityManager: Start proc 6194:com.android.packageinstaller/u0a130 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 13:52:03.568   757  1547 D InputDispatcher: Focused application set to: xxxx
,06-30 13:52:03.568   757  1547 D InputDispatcher: Focus left window: 6130
06-30 13:52:03.568  6194  6194 E Zygote  : v2
06-30 13:52:03.568  6194  6194 I libpersona: KNOX_SDCARD checking this for 10130
06-30 13:52:03.568   757   898 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:757 uid:1000
06-30 13:52:03.568  6194  6194 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:03.568   757   898 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:03.568   757   898 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:757 uid:1000
06-30 13:52:03.568   757   898 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:03.568  6130  6188 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 48ms. Plugin should use CordovaInterface.getThreadPool().
06-30 13:52:03.568  6194  6194 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:52:03.568  6194  6194 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:03.578  6194  6194 E Zygote  : accessInfo : 0
06-30 13:52:03.578  6194  6194 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-30 13:52:03.598  6194  6194 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:03.598  6194  6194 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:03.598   757  1740 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 13:52:03.608   757   850 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 13:52:03.918   757  1740 I WindowManager: Screenshot max retries 4 of Token{17af3ce ActivityRecord{3a5f0c9 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t78}} appWin=Window{768dbff u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 13:52:04.008  6194  6194 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.058   757  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/78_task.xml.bak
,06-30 13:52:04.068  6194  6194 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 13:52:04.088  6194  6194 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.098  6194  6194 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.118  6194  6194 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.148  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.148  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.158  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.158  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.168  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.168  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.238  6194  6194 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 13:52:04.248  6194  6194 D SecWifiDisplayUtil: Metadata value : none
,06-30 13:52:04.248  6194  6194 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8c34ec0 I.E...... R.....I. 0,0-0,0}
,06-30 13:52:04.258  6194  6209 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:04.258   757  1547 D ISSUE_DEBUG: InputChannelName : a9941e8 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 13:52:04.258   757   772 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,06-30 13:52:04.258   757   772 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:04.268   757   757 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 13:52:04.268   757   757 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 13:52:04.268   757   757 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 13:52:04.288   292   292 I SurfaceFlinger: id=17 createSurf (145x145),1 flag=4, HrantPermis
,06-30 13:52:04.288   757   852 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a9941e8 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 13:52:04.288  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 13:52:04.298   757  1623 D InputDispatcher: Focus entered window: 6194
,06-30 13:52:04.298  6194  6209 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 13:52:04.298  6194  6209 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 13:52:04.298  6194  6209 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 13:52:04.298  6194  6209 I Adreno-EGL: Local Branch: ss
06-30 13:52:04.298  6194  6209 I Adreno-EGL: Remote Branch: 
06-30 13:52:04.298  6194  6209 I Adreno-EGL: Local Patches: 
06-30 13:52:04.298  6194  6209 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:52:04.298   757   898 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:757 uid:1000
,06-30 13:52:04.298   757   898 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:04.298   757   898 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:757 uid:1000
06-30 13:52:04.298   757   898 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 13:52:04.308  6194  6209 D libEGL  : eglInitialize EGLDisplay = 0xae1e67c4
,06-30 13:52:04.308  6194  6209 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:04.358  6194  6194 V ActivityThread: updateVisibility : ActivityRecord{ac62cbb token=android.os.BinderProxy@38ff843 {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 13:52:04.368  6194  6194 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 13:52:04.368   757   772 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 13:52:04.378  1960  1960 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 13:52:04.388  6194  6194 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 13:52:04.428   757  2337 V WindowStateAnimator: Finishing drawing window Window{a9941e8 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,06-30 13:52:04.428  6194  6194 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38ff843 time:116744
,06-30 13:52:04.428   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbee91364
,06-30 13:52:04.428   757   898 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 13:52:04.428   757   757 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:04.428   757   898 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +496ms (total +876ms)
,06-30 13:52:04.428   757   757 I KnoxTimeoutHandler: SD activityfalse
06-30 13:52:04.438   757   898 D ActivityManager: mDVFSHelper.release()
06-30 13:52:04.438   757   898 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a5f0c9 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t78} time:116750
,06-30 13:52:05.268  1447  1447 D Recents : onTaskStackChanged
,06-30 13:52:05.648   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 13:52:05.688   757  1644 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 13:52:05.698   757  1644 V AlarmManager:  remove PendingIntent] PendingIntent{ed8e2dd: PendingIntentRecord{b661e52 android broadcastIntent}}
,06-30 13:52:05.718   757  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:05.718   757  1422 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4377, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:52:05.718   757  1422 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 13:52:05.718   757  1422 D BatteryService: stay LED for charging
,06-30 13:52:05.718   757   850 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a08b3d u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a04778 1951:com.google.android.gms/u0a12}
,06-30 13:52:05.748   757   757 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,06-30 13:52:05.748   757   757 V AlarmManagerEXT: <AppSync3 Whitelist>
,06-30 13:52:05.748   757   757 V AlarmManagerEXT: (AppSync) ### 0 added ###
,06-30 13:52:05.758  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:52:05.758  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 13:52:05.758  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:52:05.758   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:05.768  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:52:05.788  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:52:05.788   757   757 I MotionRecognitionService: Plugged
06-30 13:52:05.788   757   757 D MotionRecognitionService:   cableConnection= 1
06-30 13:52:05.788   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:52:05.788   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:05.798  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.798  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.798  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.798  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 13:52:05.798  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.798  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.798  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.798  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:05.798  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:05.798  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:05.808   757  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71ec7e u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7d3d4d 1632:com.google.android.gms.persistent/u0a12}
,06-30 13:52:05.818  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:05.818  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:52:05.818  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:05.828   757  1615 V AlarmManager:  remove PendingIntent] PendingIntent{e0445df: PendingIntentRecord{5dd0ae6 com.google.android.gms broadcastIntent}}
,06-30 13:52:05.888  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:05.918  1951  6237 I EventLogService: Aggregate from 1467285698241 (log), 1467285698241 (data)
,06-30 13:52:06.038  6238  6238 E Zygote  : v2
06-30 13:52:06.038  6238  6238 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:06.038  6238  6238 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:06.038   757   850 I ActivityManager: Start proc 6238:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,06-30 13:52:06.038  6238  6238 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:52:06.038  6238  6238 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:52:06.038  6238  6238 E Zygote  : accessInfo : 0
,06-30 13:52:06.068  6238  6238 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:06.068  6238  6238 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:06.078   757  1712 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89160fb u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e94f518 6238:com.samsung.android.sm/1000}
,06-30 13:52:06.078  6238  6238 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,06-30 13:52:06.128   757  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9db71 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e94f518 6238:com.samsung.android.sm/1000}
,06-30 13:52:06.148  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:06.148  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:06.148  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:06.168  1632  2990 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 13:52:06.168  1632  2990 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 13:52:06.168  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 13:52:06.168  1632  2990 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:52:06.168  1632  2990 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:52:06.168  1632  2990 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:52:06.178  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 13:52:06.178  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:52:06.178  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
06-30 13:52:06.188   757  1712 I ActivityManager: Killing 3761:com.google.android.talk/u0a117 (adj 15): DHA:empty #37
,06-30 13:52:06.218   757  1618 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,06-30 13:52:08.558   757  1568 E Watchdog: !@Sync 3 [06-30 13:52:08.567]
,06-30 13:52:10.018   757  3339 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:10.728   757   923 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 13:52:10.778   757   923 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 13:52:12.348   757  3339 D SSRM:n  : SIOP:: AP = 380, PST = 445, CUR = 300, LCD = 0
,06-30 13:52:12.378   757  3339 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:15.818   757  2337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:52:15.828   757  2337 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4380, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:52:15.828   757  2337 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:52:15.838   757  2337 D BatteryService: stay LED for charging
,06-30 13:52:15.838   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:15.848   757   757 I MotionRecognitionService: Plugged
,06-30 13:52:15.848   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:52:15.848  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:15.848  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:15.858  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:52:15.858   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:52:15.858   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:15.878  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:15.878  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:15.878  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:16.458   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:52:22.448   757  3339 D SSRM:n  : SIOP:: AP = 350, PST = 432, CUR = 300, LCD = 0
,06-30 13:52:26.198   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 13:52:26.268   757  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:26.268   757  1547 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:52:26.268   757  1547 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 13:52:26.268   757  1547 D BatteryService: stay LED for charging
,06-30 13:52:26.278   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:26.288   757   757 I MotionRecognitionService: Plugged
,06-30 13:52:26.288   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:52:26.288   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:52:26.288   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:26.288  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:26.288  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:26.288  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:52:26.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:26.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 13:52:26.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:26.798  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:26.818  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:26.828  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:26.848  1632  2990 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 13:52:26.848  1632  2990 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 13:52:26.848  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 13:52:26.848  1632  2990 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:52:26.848  1632  2990 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:52:26.848  1632  2990 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:52:26.868  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:52:26.868  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 13:52:26.868  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 13:52:32.508   757  3339 D SSRM:n  : SIOP:: AP = 340, PST = 419, CUR = 300, LCD = 0
,06-30 13:52:32.518   757  3339 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,06-30 13:52:32.528  2717  2717 D ContentApp:  LEVEL : 0
,06-30 13:52:32.578   757   850 I ActivityManager: Start proc 6288:com.sec.android.app.videoplayer/u0a54 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,06-30 13:52:32.578   757  1323 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 13:52:32.588  6288  6288 E Zygote  : v2
,06-30 13:52:32.598  6288  6288 I libpersona: KNOX_SDCARD checking this for 10054
,06-30 13:52:32.598   757  3339 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:32.598  6288  6288 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:32.598  6288  6288 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 13:52:32.608  6288  6288 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:52:32.608  6288  6288 E Zygote  : accessInfo : 0
,06-30 13:52:32.618  6288  6288 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,06-30 13:52:32.688  6288  6288 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:32.688  6288  6288 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:32.708   757  1711 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccfddea u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71af8db 6288:com.sec.android.app.videoplayer/u0a54}
,06-30 13:52:32.708   757  1323 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,06-30 13:52:32.718  6288  6288 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,06-30 13:52:32.758  6288  6288 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,06-30 13:52:32.798  6288  6288 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,06-30 13:52:32.838  6288  6288 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,06-30 13:52:32.838  6288  6288 D videowall-Global: core_num = 4
,06-30 13:52:32.858  6288  6288 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
06-30 13:52:32.858  6288  6288 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,06-30 13:52:32.878  6288  6288 D TranscodeReceiver:  SIOP_LEVEL: 0
,06-30 13:52:32.878   757  1422 I ActivityManager: Killing 5345:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,06-30 13:52:32.888   757  1712 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,06-30 13:52:36.348   757  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:36.358   757  1618 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:52:36.358   757  1618 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:52:36.358   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:36.378   757   757 I MotionRecognitionService: Plugged
,06-30 13:52:36.378   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:52:36.378   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:52:36.388   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:36.388   757  1618 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,06-30 13:52:36.388   757  1618 D BatteryService: stay LED for charging
,06-30 13:52:36.408  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:36.408  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:36.408  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:52:36.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:36.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:36.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:36.468   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:52:38.568   757  1568 E Watchdog: !@Sync 4 [06-30 13:52:38.576]
,06-30 13:52:39.848  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:52:42.658   757  3339 D SSRM:n  : SIOP:: AP = 330, PST = 405, CUR = 300, LCD = 0
,06-30 13:52:42.668   757  3339 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,06-30 13:52:42.678  2717  2717 D ContentApp:  LEVEL : -1
,06-30 13:52:42.718   757   850 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b0df78 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71af8db 6288:com.sec.android.app.videoplayer/u0a54}
,06-30 13:52:42.718  6288  6288 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
06-30 13:52:42.718  6288  6288 D TranscodeReceiver:  SIOP_LEVEL: -1
,06-30 13:52:46.888   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 13:52:46.968   757  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:46.968   757  1618 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:52:46.968   757  1618 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 13:52:46.968   757  1618 D BatteryService: stay LED for charging
06-30 13:52:46.968   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:52:46.978   757   757 I MotionRecognitionService: Plugged
,06-30 13:52:46.978   757   757 D MotionRecognitionService:   cableConnection= 1
06-30 13:52:46.978   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:52:46.978   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:46.978  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:46.978  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:46.978  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:52:47.008  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 13:52:47.008  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 13:52:47.008  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 13:52:47.318  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:47.328  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:47.328  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:47.348  1632  2990 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 13:52:47.348  1632  2990 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 13:52:47.348  1632  2990 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 13:52:47.348  1632  2990 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:52:47.348  1632  2990 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:52:47.348  1632  2990 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:52:47.368  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:52:47.368  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:52:47.368  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 13:52:52.768   757  3339 D SSRM:n  : SIOP:: AP = 330, PST = 391, CUR = 300, LCD = 0
,06-30 13:52:56.468   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:52:57.078   757  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:57.078   757  1547 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:52:57.078   757  1547 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:52:57.078   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:57.088   757   757 I MotionRecognitionService: Plugged
,06-30 13:52:57.088   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:52:57.088   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:52:57.098   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:57.098   757  1547 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,06-30 13:52:57.098   757  1547 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 757) 
,06-30 13:52:57.108  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:57.108  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:57.108  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:52:57.118  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:52:57.118   757  1547 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,06-30 13:52:57.128   757  1547 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 13:52:57.138   757  1547 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 13:52:57.148  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:52:57.148  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:52:57.158  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:52:57.178   757  1547 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 13:52:57.178   757  1547 D BatteryService: turn on LED for fully charged
,06-30 13:52:57.538   757  1219 E LightSensor: RED : 1, GREEN : 1, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 8282.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=2, cp1=4, cpl=3202560
,06-30 13:52:57.538   757   910 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 13:52:57.538   757   910 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 13:52:57.548   757   910 D SensorManager: unregisterListener ::   
,06-30 13:52:57.558   757   910 D lights  : led_pattern : 5 +
,06-30 13:52:57.578   757   910 D lights  : led_pattern : 5 -
,06-30 13:52:57.578   757   910 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,06-30 13:52:57.578   757   910 V AlarmManager:  remove PendingIntent] PendingIntent{b5ee15e: PendingIntentRecord{cc4c93f android broadcastIntent}}
,06-30 13:52:59.988   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 13:53:02.838   757  3339 D SSRM:n  : SIOP:: AP = 320, PST = 380, CUR = 300, LCD = 0
,06-30 13:53:03.548  1632  3196 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:07.378   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 13:53:07.478   757  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:07.508  6337  6337 E Zygote  : v2
,06-30 13:53:07.508  6337  6337 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:53:07.518  6337  6337 I libpersona: KNOX_SDCARD not a persona
,06-30 13:53:07.518  6337  6337 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:53:07.518  6337  6337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:53:07.518  6337  6337 E Zygote  : accessInfo : 0
,06-30 13:53:07.518   757  1237 I ActivityManager: Start proc 6337:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 13:53:07.528  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:53:07.528  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 13:53:07.528  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:53:07.538  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:53:07.538   757  1644 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 13:53:07.538   757  1644 V AlarmManager:  remove PendingIntent] PendingIntent{ed8e2dd: PendingIntentRecord{b661e52 android broadcastIntent}}
,06-30 13:53:07.548  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:53:07.548  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.548  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.558   757   757 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3673df2 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7d3d4d 1632:com.google.android.gms.persistent/u0a12}
,06-30 13:53:07.558  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.568   757   774 V AlarmManager:  remove PendingIntent] PendingIntent{3014c43: PendingIntentRecord{5dd0ae6 com.google.android.gms broadcastIntent}}
,06-30 13:53:07.578  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.578  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.588  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.588  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.638  6337  6337 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:53:07.638  6337  6337 D ActivityThread: Added TimaKeyStore provider
,06-30 13:53:07.668  6337  6337 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,06-30 13:53:07.678  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.688  6337  6337 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,06-30 13:53:08.088  1632  1632 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=99437686-28a7-40c7-865b-8394bdbc1d5e
,06-30 13:53:08.098  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:08.108  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:08.168  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:08.198  1632  4056 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 13:53:08.198  1632  4056 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 13:53:08.198  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 13:53:08.198  1632  4056 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:53:08.198  1632  4056 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:53:08.198  1632  4056 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:53:08.248  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:08.248  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 13:53:08.248  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 13:53:08.338  1951  6366 D UdcContextInitService: registered all accounts: true
,06-30 13:53:08.348  1632  2128 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:53:08.358   757   767 I art     : Background partial concurrent mark sweep GC freed 48052(3MB) AllocSpace objects, 45(900KB) LOS objects, 27% free, 41MB/57MB, paused 2.919ms total 210.709ms
,06-30 13:53:08.378  1632  6369 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 13:53:08.508   757  1712 V AlarmManager:  remove PendingIntent] PendingIntent{6660377: PendingIntentRecord{5dd0ae6 com.google.android.gms broadcastIntent}}
,06-30 13:53:08.528  1632  6369 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10012, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 13:53:08.568   757  1568 E Watchdog: !@Sync 5 [06-30 13:53:08.583]
,06-30 13:53:08.608   757  1746 I ActivityManager: Killing 5357:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #37
,06-30 13:53:08.618  1632  1632 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 13:53:08.638  1632  6380 I VacuumService: Vacuum at: now=1467287588646 tag=VacuumService
,06-30 13:53:08.648   757  1711 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,06-30 13:53:08.768   757  1740 V AlarmManager:  remove PendingIntent] PendingIntent{8caff02: PendingIntentRecord{5dd0ae6 com.google.android.gms broadcastIntent}}
,06-30 13:53:08.788   757  3340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 13:53:08.798   757   850 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f2d37c u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43a8967 5731:com.samsung.android.sm.provider/1000}
,06-30 13:53:08.908   757  3340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 13:53:08.938   757   850 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6256c5a u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43a8967 5731:com.samsung.android.sm.provider/1000}
,06-30 13:53:12.908   757  3339 D SSRM:n  : SIOP:: AP = 320, PST = 366, CUR = 300, LCD = 0
,06-30 13:53:16.478   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:17.538   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:22.968   757  3339 D SSRM:n  : SIOP:: AP = 320, PST = 350, CUR = 300, LCD = 0
,06-30 13:53:28.268   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 13:53:28.348   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:28.628  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:28.638  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:28.638  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:28.658  1632  4056 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 13:53:28.658  1632  4056 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 13:53:28.658  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 13:53:28.658  1632  4056 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:53:28.658  1632  4056 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:53:28.658  1632  4056 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:53:28.678  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:28.678  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:53:28.678  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 13:53:33.048   757  3339 D SSRM:n  : SIOP:: AP = 310, PST = 340, CUR = 300, LCD = 0
,06-30 13:53:36.478   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:38.428   757  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:38.438   757  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:53:38.438   757  1623 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:53:38.438   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:38.448   757   757 I MotionRecognitionService: Plugged
,06-30 13:53:38.448   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:53:38.458   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:53:38.458   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:38.458   757  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:53:38.468   757  1623 D BatteryService: stay LED for fully charged
,06-30 13:53:38.478  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:38.478  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:38.488  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:38.508  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:38.508  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:38.508  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:38.578   757  1568 E Watchdog: !@Sync 6 [06-30 13:53:38.585]
,06-30 13:53:39.858  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:53:40.078  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 211ms lastUpdatedAfter : 125647ms
,06-30 13:53:43.108   757  3339 D SSRM:n  : SIOP:: AP = 310, PST = 331, CUR = 300, LCD = 0
,06-30 13:53:48.518   757  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:48.518   757  1422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:53:48.518   757  1422 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:53:48.518   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:48.538   757   757 I MotionRecognitionService: Plugged
,06-30 13:53:48.538   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:53:48.538   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:48.538   757  1422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,06-30 13:53:48.538   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:48.548   757  1422 D BatteryService: stay LED for fully charged
,06-30 13:53:48.558  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:48.558  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:48.558  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:48.588  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:48.588  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:48.588  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:53.168   757  3339 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 300, LCD = 0
,06-30 13:53:56.478   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:58.608   757  2337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:59.988   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 13:54:03.228   757  3339 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 300, LCD = 0
,06-30 13:54:07.548   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 13:54:08.578   757  1568 E Watchdog: !@Sync 7 [06-30 13:54:08.588]
,06-30 13:54:08.688   757  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:08.688   757  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 13:54:08.688   757  1740 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 13:54:08.688   757  1740 D BatteryService: stay LED for fully charged
,06-30 13:54:08.688   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:08.688   757   757 I MotionRecognitionService: Plugged
,06-30 13:54:08.698   757   757 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:08.698   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:08.698   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:08.698  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:08.698  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:08.698  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:08.718  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:08.718  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:08.718  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:08.778  1632  6369 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:08.778  1632  6369 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:08.778  1632  6369 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 13:54:08.778  1632  6369 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 13:54:08.778  1632  6369 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 13:54:08.798  1632  6369 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 13:54:13.288   757  3339 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 300, LCD = 0
,06-30 13:54:16.488   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:18.778   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:23.348   757  3339 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 300, LCD = 0
,06-30 13:54:28.868   757  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:28.868   757  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:28.868   757  1623 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:54:28.878   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:28.888   757   757 I MotionRecognitionService: Plugged
,06-30 13:54:28.888   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:28.888   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:28.888   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:28.898   757  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:54:28.898   757  1623 D BatteryService: stay LED for fully charged
,06-30 13:54:28.908  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:28.908  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:28.908  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:28.938  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:28.938  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:28.938  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:33.398   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 312, CUR = 300, LCD = 0
,06-30 13:54:36.488   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:38.578   757  1568 E Watchdog: !@Sync 8 [06-30 13:54:38.592]
,06-30 13:54:38.948   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:38.958   757  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:38.958   757  1712 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:54:38.958   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:38.968   757   757 I MotionRecognitionService: Plugged
,06-30 13:54:38.978   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:38.978   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:38.978   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:38.978   757  1712 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:54:38.988   757  1712 D BatteryService: stay LED for fully charged
,06-30 13:54:38.988  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:38.988  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:38.988  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:39.018  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:39.018  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:39.018  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:40.118  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:54:43.458   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 310, CUR = 300, LCD = 0
,06-30 13:54:49.028   757  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:49.038   757  1746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:49.038   757  1746 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:54:49.038   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:49.048   757   757 I MotionRecognitionService: Plugged
,06-30 13:54:49.058   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:49.058   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:49.058   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:49.058   757  1746 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:54:49.068   757  1746 D BatteryService: stay LED for fully charged
,06-30 13:54:49.078  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:49.078  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:49.078  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:49.108  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:49.108  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:49.108  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:53.518   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,06-30 13:54:56.498   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:59.128   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:03.578   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,06-30 13:55:08.588   757  1568 E Watchdog: !@Sync 9 [06-30 13:55:08.596]
,06-30 13:55:09.208   757  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:13.638   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,06-30 13:55:16.508   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:19.298   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:19.298   757  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:55:19.298   757  1712 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:55:19.298   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:19.318   757   757 I MotionRecognitionService: Plugged
,06-30 13:55:19.318   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:55:19.318   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:55:19.318   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:19.328   757  1712 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:55:19.328   757  1712 D BatteryService: stay LED for fully charged
,06-30 13:55:19.338  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:19.338  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:19.338  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:19.358  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:19.358  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:19.358  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:23.398   757  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:55:23.418   757  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:55:23.418   757  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:55:23.428   757  1231 I TLC_TIMA_PKM_initialize: initializing...
,06-30 13:55:23.438   757  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 13:55:23.438   757  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,06-30 13:55:23.438   757  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 13:55:23.438   757  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 13:55:23.438   757  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,06-30 13:55:23.448   757  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 13:55:23.448   757  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 13:55:23.448   757  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 13:55:23.458   757  1231 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 13:55:23.508   757  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,06-30 13:55:23.528   757  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 13:55:23.538   757  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 13:55:23.698   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,06-30 13:55:26.588   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:55:26.588   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:55:26.598   757  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:26.608   757  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:29.388   757  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:29.388   757  1746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:55:29.398   757  1746 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:55:29.398   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:29.408   757   757 I MotionRecognitionService: Plugged
,06-30 13:55:29.408   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:55:29.408   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:55:29.418   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:29.418   757  1746 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 13:55:29.418   757  1746 D BatteryService: stay LED for fully charged
,06-30 13:55:29.438  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:29.438  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:29.438  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:29.458  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:29.458  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:29.458  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:33.768   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,06-30 13:55:36.498   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:38.588   757  1568 E Watchdog: !@Sync 10 [06-30 13:55:38.603]
,06-30 13:55:39.478   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:39.478   757  1615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:55:39.478   757  1615 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:55:39.488   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:39.498   757   757 I MotionRecognitionService: Plugged
,06-30 13:55:39.498   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:55:39.498   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:55:39.508   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:39.508   757  1615 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 13:55:39.508   757  1615 D BatteryService: stay LED for fully charged
,06-30 13:55:39.518  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:39.528  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:39.528  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:39.558  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:39.558  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:39.558  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:40.138  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:55:43.828   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,06-30 13:55:49.558   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:53.888   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,06-30 13:55:56.508   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:59.648   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:59.648   757  1615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:55:59.648   757  1615 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:55:59.658   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:59.668   757   757 I MotionRecognitionService: Plugged
,06-30 13:55:59.668   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:55:59.668   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:55:59.668   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:59.678   757  1615 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:55:59.678   757  1615 D BatteryService: stay LED for fully charged
,06-30 13:55:59.688  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:59.688  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:59.688  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:59.708  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:59.708  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:59.718  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:03.948   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:56:07.188  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:07.228  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:07.238  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:07.268  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 13:56:07.268  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 13:56:07.268  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 13:56:07.268  1632  1645 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:56:07.268  1632  1645 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:56:07.268  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:56:07.288  1632  1645 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 13:56:07.288  1632  1645 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 13:56:07.288  1632  1645 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 13:56:07.288  1632  1645 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 13:56:07.288  1632  1645 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:56:07.288  1632  1645 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:56:07.288  1632  1645 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:56:07.298  5291  5336 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:56:07.298  5291  5336 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:56:07.298  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 13:56:07.298  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 13:56:07.298  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 13:56:07.298  5291  5336 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:56:07.298  5291  5336 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:56:07.338  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:56:07.338  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:56:07.348   303  1097 D EnterpriseController: netId is 0
06-30 13:56:07.348   303  1097 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 13:56:08.598   757  1568 E Watchdog: !@Sync 11 [06-30 13:56:08.608]
,06-30 13:56:11.608   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 13:56:11.628  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:56:11.628  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 13:56:11.638  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:56:11.688   757  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:11.688   757  1644 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 13:56:11.688   757  1644 V AlarmManager:  remove PendingIntent] PendingIntent{ed8e2dd: PendingIntentRecord{b661e52 android broadcastIntent}}
,06-30 13:56:11.698  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:56:11.698  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:56:11.708  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.718  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.718  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.718  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.728   757  1644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 13:56:11.728  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.738  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.748  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.808  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:14.008   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:56:16.518   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:21.758   757  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:21.768   757  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:56:21.768   757  1623 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:56:21.768   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:21.778   757   757 I MotionRecognitionService: Plugged
,06-30 13:56:21.788   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:56:21.788   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:56:21.788   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:56:21.788   757  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:56:21.798   757  1623 D BatteryService: stay LED for fully charged
,06-30 13:56:21.798  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:21.798  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:56:21.798  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:21.818  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:21.828  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:21.828  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:24.058   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:56:31.868   757  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:31.878   757  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:56:31.878   757  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:56:31.878   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:31.888   757   757 I MotionRecognitionService: Plugged
,06-30 13:56:31.888   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:56:31.898   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:56:31.898   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:56:31.898   757  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
06-30 13:56:31.898   757  1320 D BatteryService: stay LED for fully charged
,06-30 13:56:31.898  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:31.898  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:56:31.898  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:31.928  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:31.928  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:31.928  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:34.118   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:56:36.518   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:38.598   757  1568 E Watchdog: !@Sync 12 [06-30 13:56:38.612]
,06-30 13:56:40.158  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:56:40.308  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 143ms lastUpdatedAfter : 180236ms
,06-30 13:56:44.168   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:56:54.218   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:56:56.518   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:59.988   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 13:57:01.938   757  2337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:01.938   757  2337 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:57:01.948   757  2337 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:57:01.948   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:01.958   757   757 I MotionRecognitionService: Plugged
,06-30 13:57:01.958   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:57:01.958   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:57:01.968   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:57:01.968   757  2337 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,06-30 13:57:01.968   757  2337 D BatteryService: stay LED for fully charged
,06-30 13:57:01.988  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:01.988  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:01.988  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:02.018  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:02.018  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:02.018  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:04.268   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:57:08.608   757  1568 E Watchdog: !@Sync 13 [06-30 13:57:08.617]
,06-30 13:57:14.328   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:57:16.518   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:24.378   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:57:32.018   757   774 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:32.018   757   774 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:57:32.018   757   774 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:57:32.028   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:32.038   757   757 I MotionRecognitionService: Plugged
,06-30 13:57:32.038   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:57:32.038   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:57:32.038   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:57:32.048   757   774 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 13:57:32.048   757   774 D BatteryService: stay LED for fully charged
,06-30 13:57:32.058  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:32.058  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:32.058  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:32.088  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:32.098  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:32.098  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:34.428   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:57:36.528   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:38.618   757  1568 E Watchdog: !@Sync 14 [06-30 13:57:38.621]
,06-30 13:57:40.318  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:57:44.488   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:57:54.538   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:57:56.528   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:02.098   757  1746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:02.098   757  1746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:58:02.098   757  1746 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:58:02.108   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:02.118   757   757 I MotionRecognitionService: Plugged
,06-30 13:58:02.118   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:58:02.118   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:58:02.118   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:58:02.128   757  1746 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:58:02.128   757  1746 D BatteryService: stay LED for fully charged
,06-30 13:58:02.138  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:02.148  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:58:02.148  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:02.168  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:02.168  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:02.168  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:04.588   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:58:08.618   757  1568 E Watchdog: !@Sync 15 [06-30 13:58:08.625]
,06-30 13:58:13.038   353   353 I bootchecker: bootchecker wake up!!
,06-30 13:58:14.638   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:58:16.528   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:24.698   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:58:32.178   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:32.178   757   772 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:58:32.178   757   772 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:58:32.188   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:32.198   757   757 I MotionRecognitionService: Plugged
,06-30 13:58:32.198   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:58:32.198   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:58:32.198   757   772 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,06-30 13:58:32.208   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:58:32.208   757   772 D BatteryService: stay LED for fully charged
,06-30 13:58:32.218  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:32.228  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:32.228  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:32.258  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:32.258  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:32.268  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:34.748   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:58:36.538   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:38.618   757  1568 E Watchdog: !@Sync 16 [06-30 13:58:38.632]
,06-30 13:58:40.368  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:58:44.808   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 13:58:54.858   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,06-30 13:58:56.538   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:02.258   757  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:02.258   757  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:59:02.258   757  1740 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 13:59:02.258   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:02.278   757   757 I MotionRecognitionService: Plugged
,06-30 13:59:02.278   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 13:59:02.278   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:59:02.278   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:59:02.288   757  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:59:02.288   757  1740 D BatteryService: stay LED for fully charged
,06-30 13:59:02.298  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:02.298  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:59:02.298  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:59:02.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:02.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:02.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:04.918   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,06-30 13:59:08.628   757  1568 E Watchdog: !@Sync 17 [06-30 13:59:08.636]
,06-30 13:59:14.968   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,06-30 13:59:16.548   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:25.028   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,06-30 13:59:32.338   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:35.088   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,06-30 13:59:36.548   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:38.628   757  1568 E Watchdog: !@Sync 18 [06-30 13:59:38.641]
,06-30 13:59:40.388  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:59:40.548  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 152ms lastUpdatedAfter : 180238ms
,06-30 13:59:45.168   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,06-30 13:59:55.228   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,06-30 13:59:56.558   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:02.418   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:05.288   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,06-30 14:00:08.638   757  1568 E Watchdog: !@Sync 19 [06-30 14:00:08.645]
,06-30 14:00:15.348   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:00:16.558   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:23.398   757  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:00:23.408   757  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:00:23.408   757  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:00:24.738   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:00:24.738   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:00:24.748   757  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:24.748   757  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:25.398   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 300, LCD = 0
,06-30 14:00:32.498   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:32.498   757  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:00:32.498   757  1712 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:00:32.508   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:00:32.518   757   757 I MotionRecognitionService: Plugged
,06-30 14:00:32.518   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:00:32.518   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:00:32.518   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:00:32.528   757  1712 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:00:32.528   757  1712 D BatteryService: stay LED for fully charged
,06-30 14:00:32.538  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:00:32.548  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:00:32.548  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:00:32.568  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:32.568  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:32.568  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:35.458   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:00:36.558   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:38.638   757  1568 E Watchdog: !@Sync 20 [06-30 14:00:38.652]
,06-30 14:00:40.558  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:42.698   757   834 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10051, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10058, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10076, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10084, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10088, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10092, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10096, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10103, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.708   757   834 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10138, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10141, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10143, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.718   757   834 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10173, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10175, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10207, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10211, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10212, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10213, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.728   757   834 D NetworkPolicy: isUidForegroundLocked: 10221, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:42.818   757   898 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,06-30 14:00:42.828   757   898 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 14:00:45.518   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:00:55.568   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:00:56.568   757  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:01:02.578   757  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:02.578   757  1547 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:01:02.578   757  1547 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:01:02.588   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:01:02.598   757   757 I MotionRecognitionService: Plugged
,06-30 14:01:02.598   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:01:02.598   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:01:02.598   757  1547 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,06-30 14:01:02.608   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:01:02.608   757  1547 D BatteryService: stay LED for fully charged
,06-30 14:01:02.628  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:02.628  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:02.628  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:02.658  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:02.668  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:02.668  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:05.628   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:01:07.428   757  1740 I ActivityManager: Killing 4276:com.sec.spp.push/u0a38 (adj 8): SSR - service for lastStateTime 609s, lastActivityTime 601s
,06-30 14:01:07.428   757  1740 I ActivityManager: Killing 3970:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 612s, lastActivityTime 612s
,06-30 14:01:07.438   757  1740 I ActivityManager: Killing 3656:com.sec.android.pagebuddynotisvc/u0a27 (adj 8): SSR - service for lastStateTime 614s, lastActivityTime 614s,
,06-30 14:01:07.478  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:07.508  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:07.518  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:07.558  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:01:07.558  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 14:01:07.558  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 14:01:07.558  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:01:07.558  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:01:07.558  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:07.588  1632  3075 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 14:01:07.588  1632  3075 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 14:01:07.588  1632  3075 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 14:01:07.588  1632  3075 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 14:01:07.588  1632  3075 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:01:07.588  1632  3075 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:01:07.588  1632  3075 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:07.618  5291  5336 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:01:07.618  5291  5336 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:01:07.618  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 14:01:07.618  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 14:01:07.618  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 14:01:07.618  5291  5336 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:01:07.618  5291  5336 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:07.618  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 14:01:07.618  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:01:07.628   303  1097 D EnterpriseController: netId is 0
06-30 14:01:07.628   303  1097 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 14:01:07.628   291   291 I ServiceManager: service 'AtCmdFwd' died
,06-30 14:01:07.638   363  4840 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 14:01:07.638   363  4840 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 14:01:07.638   757  1711 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
06-30 14:01:07.638   757  1711 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 14:01:07.638   757  1711 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 14:01:07.648   757  1740 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 14:01:07.648   757  1740 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 14:01:07.648   757  1740 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10988ms
,06-30 14:01:07.668   757  1422 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
06-30 14:01:07.668   757  1422 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,06-30 14:01:08.638   363  4840 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 14:01:08.648   757  1568 E Watchdog: !@Sync 21 [06-30 14:01:08.657]
,06-30 14:01:08.718   757   850 I ActivityManager: Start proc 6489:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 14:01:08.728  6489  6489 E Zygote  : v2
,06-30 14:01:08.728  6489  6489 I libpersona: KNOX_SDCARD checking this for 1000
06-30 14:01:08.728  6489  6489 I libpersona: KNOX_SDCARD not a persona
,06-30 14:01:08.728  6489  6489 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:01:08.728  6489  6489 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:01:08.728  6489  6489 E Zygote  : accessInfo : 0
,06-30 14:01:08.778  6489  6489 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:01:08.778  6489  6489 D ActivityThread: Added TimaKeyStore provider
,06-30 14:01:08.798  6489  6489 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 14:01:08.808  6489  6489 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 14:01:08.818  6489  6489 D AtFwdService: onCreate method
,06-30 14:01:08.818  6489  6489 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 14:01:08.828  6489  6501 D AtCkpdCmdHandler: De-queing command
,06-30 14:01:12.008   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 14:01:15.678   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:01:18.718   757   850 I ActivityManager: Start proc 6504:com.sec.android.pagebuddynotisvc/u0a27 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 14:01:18.728  6504  6504 E Zygote  : v2
,06-30 14:01:18.728  6504  6504 I libpersona: KNOX_SDCARD checking this for 10027
06-30 14:01:18.728  6504  6504 I libpersona: KNOX_SDCARD not a persona
,06-30 14:01:18.728  6504  6504 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:01:18.728  6504  6504 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:01:18.728  6504  6504 E Zygote  : accessInfo : 0
,06-30 14:01:18.738  6504  6504 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 14:01:18.778  6504  6504 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:01:18.778  6504  6504 D ActivityThread: Added TimaKeyStore provider
,06-30 14:01:18.788   757   774 I ActivityManager: Killing 1517:com.sec.android.daemonapp/u0a182 (adj 8): SSR - service for lastStateTime 613s, lastActivityTime 607s
,06-30 14:01:18.818  6504  6504 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 14:01:18.818   757  1618 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,06-30 14:01:18.828   757  1618 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 14:01:18.828   757  1618 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,06-30 14:01:18.838  6504  6504 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 14:01:18.868  6504  6504 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 14:01:18.868  6504  6504 D ContextualPageNotification: resetAllNotification : all clear!!!
,06-30 14:01:19.898   757   850 I ActivityManager: Start proc 6525:com.sec.android.daemonapp/u0a182 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,06-30 14:01:19.908   757  1323 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 14:01:19.918  6525  6525 E Zygote  : v2
,06-30 14:01:19.918  6525  6525 I libpersona: KNOX_SDCARD checking this for 10182
06-30 14:01:19.918  6525  6525 I libpersona: KNOX_SDCARD not a persona
,06-30 14:01:19.918  6525  6525 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:01:19.918  6525  6525 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:01:19.918  6525  6525 E Zygote  : accessInfo : 0
,06-30 14:01:19.928  6525  6525 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,06-30 14:01:19.968  6525  6525 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:01:19.968  6525  6525 D ActivityThread: Added TimaKeyStore provider
,06-30 14:01:19.988   757  1323 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 14:01:19.998  6525  6525 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,06-30 14:01:20.018  6525  6525 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,06-30 14:01:20.048  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,06-30 14:01:20.058  6525  6525 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:01:20.068   757   850 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6f35436 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1077f37 6525:com.sec.android.daemonapp/u0a182}
,06-30 14:01:20.078  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,06-30 14:01:20.078  6525  6525 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:01:20.078  6525  6525 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,06-30 14:01:20.078  6525  6525 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:01:20.078  6525  6525 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,06-30 14:01:20.078  6525  6525 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:01:20.098  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:01:20.098  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 14:01:20.098  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,06-30 14:01:20.108  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:01:20.108  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 14:01:20.108  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,06-30 14:01:20.108  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 14:01:20.138  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,06-30 14:01:20.138  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:01:20.138  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 14:01:20.148  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,06-30 14:01:20.148  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 14:01:20.148  6525  6525 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:01:20.158  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:01:20.158  6525  6525 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 14:01:20.158  6525  6525 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 14:01:20.158  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:01:20.158  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 14:01:20.158  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 14:01:20.158  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:01:20.158  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 14:01:20.158  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 14:01:20.158  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.168  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:01:20.168   757  1711 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d4ad7d3 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1077f37 6525:com.sec.android.daemonapp/u0a182}
,06-30 14:01:20.178  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:01:20.178  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 14:01:20.178  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 14:01:20.178  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:01:20.188  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:01:20.188  6525  6525 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 14:01:20.188  6525  6525 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 14:01:20.188  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.188  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:01:20.198   757  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d25f10 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1077f37 6525:com.sec.android.daemonapp/u0a182}
,06-30 14:01:20.208  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:01:20.208  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 14:01:20.208  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 14:01:20.208  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.208  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:01:20.218  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:01:20.218  6525  6525 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 14:01:20.218  6525  6525 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 14:01:20.218  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.218  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:01:20.228   757   772 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e98a09 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1077f37 6525:com.sec.android.daemonapp/u0a182}
,06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:01:20.238  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:01:20.238  6525  6525 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 14:01:20.238  6525  6525 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 14:01:20.238  6525  6525 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 14:01:20.238  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 14:01:20.248  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:01:20.248  6525  6525 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 14:01:20.248  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 14:01:20.248  6525  6525 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:01:20.248  6525  6525 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:01:25.768   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:01:32.658   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:35.818   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:01:38.678   757  1568 E Watchdog: !@Sync 22 [06-30 14:01:38.687]
,06-30 14:01:40.588  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:01:45.868   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:01:55.928   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:02:02.738   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:02.738   757   772 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:02:02.748   757   772 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:02:02.748   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:02.758   757   757 I MotionRecognitionService: Plugged
,06-30 14:02:02.758   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:02:02.758   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:02:02.768   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:02:02.768   757   772 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:02:02.768   757   772 D BatteryService: stay LED for fully charged
,06-30 14:02:02.778  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:02.778  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:02.788  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:02:02.818  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:02.818  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:02:02.818  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:05.978   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:02:08.678   757  1568 E Watchdog: !@Sync 23 [06-30 14:02:08.691]
,06-30 14:02:16.028   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:02:26.088   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:02:32.818   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:32.818   757  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:02:32.818   757  1712 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:02:32.828   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:32.838   757   757 I MotionRecognitionService: Plugged
,06-30 14:02:32.838   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:02:32.838   757  1712 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
,06-30 14:02:32.838   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:02:32.848   757  1712 D BatteryService: stay LED for fully charged
,06-30 14:02:32.848   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:02:32.858  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:32.868  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:02:32.868  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:02:32.888  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:32.888  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:02:32.888  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:36.148   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:02:38.688   757  1568 E Watchdog: !@Sync 24 [06-30 14:02:38.695]
,06-30 14:02:40.688  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:02:40.858  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 160ms lastUpdatedAfter : 180306ms
,06-30 14:02:46.218   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:02:56.268   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:03:02.898   757  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:06.328   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:03:07.588  1632  3196 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 14:03:08.688   757  1568 E Watchdog: !@Sync 25 [06-30 14:03:08.699]
,06-30 14:03:16.378   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:03:26.438   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:03:32.978   757  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:32.988   757  1618 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:03:32.988   757  1618 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:03:32.988   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:32.998   757   757 I MotionRecognitionService: Plugged
,06-30 14:03:33.008   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:03:33.008   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:03:33.008   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:03:33.008   757  1618 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:03:33.018   757  1618 D BatteryService: stay LED for fully charged
,06-30 14:03:33.018  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:33.018  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:33.018  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:33.048  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:33.048  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:33.048  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:36.488   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:03:38.698   757  1568 E Watchdog: !@Sync 26 [06-30 14:03:38.704]
,06-30 14:03:40.888  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:03:42.858   757  2396 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 14:03:42.858   757  2396 V MARsPolicyManager: updateSMDBValues
,06-30 14:03:42.868   757   895 E MARsDBManager: updateDBAll : begin --size 1
,06-30 14:03:42.898   757   895 I ActivityManager: Killing 1885:com.sec.android.app.shealth:remote/u0a35 (adj 8): SSR - service for lastStateTime 782s, lastActivityTime 721s
,06-30 14:03:42.908   757   895 I ActivityManager: Killing 5820:com.samsung.android.sdk.samsunglink/u0a42 (adj 8): SSR - service for lastStateTime 723s, lastActivityTime 723s
,06-30 14:03:42.928   757   895 E MARsDBManager: updateDBAll : end
,06-30 14:03:42.928   757   895 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 14:03:42.988   757  2337 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,06-30 14:03:42.988   757  2337 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,06-30 14:03:42.998   757  1740 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,06-30 14:03:42.998   757  1740 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,06-30 14:03:42.998   757  1740 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
06-30 14:03:42.998   757  1740 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 14:03:42.998   757  1740 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 11000ms
,06-30 14:03:43.008  5451  5451 D HealthConsole: Service for HealthDataStore is disconnected
,06-30 14:03:43.028   757  1618 I ActivityManager: Start proc 6542:com.sec.android.app.shealth:remote/u0a35 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,06-30 14:03:43.038  6542  6542 E Zygote  : v2
06-30 14:03:43.038  6542  6542 I libpersona: KNOX_SDCARD checking this for 10035
06-30 14:03:43.038  6542  6542 I libpersona: KNOX_SDCARD not a persona
,06-30 14:03:43.048  6542  6542 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:03:43.048  6542  6542 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:03:43.048  6542  6542 E Zygote  : accessInfo : 0
,06-30 14:03:43.048  6542  6542 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,06-30 14:03:43.078  6542  6542 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:03:43.078  6542  6542 D ActivityThread: Added TimaKeyStore provider
,06-30 14:03:43.098  6542  6542 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,06-30 14:03:43.118  6542  6542 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,06-30 14:03:43.128  6542  6542 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 14:03:43.128  6542  6542 I MultiDex: install
06-30 14:03:43.128  6542  6542 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 14:03:43.128  6542  6542 I MultiDex: install
06-30 14:03:43.128  6542  6542 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 14:03:43.258  6571  6571 E Zygote  : v2
06-30 14:03:43.258  6571  6571 I libpersona: KNOX_SDCARD checking this for 10017
06-30 14:03:43.258  6571  6571 I libpersona: KNOX_SDCARD not a persona
,06-30 14:03:43.258  6571  6571 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:03:43.258  6571  6571 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 14:03:43.258   757  2337 I ActivityManager: Start proc 6571:com.sec.android.service.health/u0a17 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,06-30 14:03:43.268  6571  6571 E Zygote  : accessInfo : 0
,06-30 14:03:43.268  6571  6571 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,06-30 14:03:43.338  6571  6571 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:03:43.338  6571  6571 D ActivityThread: Added TimaKeyStore provider
,06-30 14:03:43.388  6571  6571 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,06-30 14:03:43.458  6542  6542 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
06-30 14:03:43.458  6542  6542 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 14:03:43.538  1378  1378 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,06-30 14:03:43.538   757   774 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10035
,06-30 14:03:43.558   757  1740 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10035
,06-30 14:03:43.568  1378  1378 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{d554257 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,06-30 14:03:43.568  1378  1378 D AdaptiveEventManager: M updateContainers()
06-30 14:03:43.568  1378  1378 D AdaptiveEventContainerSmall: C updatePedoContainer()
,06-30 14:03:43.568  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate()
,06-30 14:03:43.578  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,06-30 14:03:43.578   757  1746 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10035
,06-30 14:03:43.588   757  1711 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10035
,06-30 14:03:43.638  6542  6542 I Health.HealthService: HealthService: onCreate() start (6542)
,06-30 14:03:43.828  5451  5451 D HealthDataStore: Service for HealthDataStore is connected
,06-30 14:03:43.828  5451  5451 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 14:03:43.858   757  1746 I ActivityManager: Killing 5116:com.sec.providers.settingsearch/u0a168 (adj 15): DHA:empty #37
,06-30 14:03:43.878  5451  5451 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 14:03:43.878  5451  5451 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 14:03:43.908  6542  6542 D HealthDataStore: Service for HealthDataStore is connected
,06-30 14:03:43.908  6542  6542 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 14:03:43.908   757  1740 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,06-30 14:03:43.918  6542  6542 D HealthConsole: Service for HealthDataConsole is connected
,06-30 14:03:43.938  6542  6542 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 14:03:43.938  6542  6542 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 14:03:44.098  6542  6595 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,06-30 14:03:44.138  6542  6609 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,06-30 14:03:44.158  6571  6586 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 14:03:44.168   385   385 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 10017, gid 10017, pid 6571
06-30 14:03:44.168   385   385 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,06-30 14:03:44.368  6571  6586 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,06-30 14:03:44.478  6542  6609 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,06-30 14:03:44.638  6542  6609 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 14:03:44.638  6542  6609 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 14:03:44.708   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,06-30 14:03:44.748  6571  6586 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,06-30 14:03:44.758  6571  6586 I SecureStorage: [INFO]: SPID(0x00000007)Skip using SecureStorageExceptionJNI
,06-30 14:03:44.758  6571  6586 D HSCheck : SS_G-2d de 1c 15 c8 bf 9d d9 69 c1 84 f0 50 9f a4 42 
,06-30 14:03:46.568   757  3339 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 300, LCD = 0
,06-30 14:03:56.628   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:04:03.068   757   774 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:03.068   757   774 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:04:03.068   757   774 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:04:03.078   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:04:03.088   757   757 I MotionRecognitionService: Plugged
,06-30 14:04:03.088   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:04:03.088   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:04:03.088   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:04:03.108   757   774 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,06-30 14:04:03.108   757   774 D BatteryService: stay LED for fully charged
,06-30 14:04:03.108  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:04:03.118  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:04:03.118  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:04:03.148  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:03.148  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:03.148  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:06.678   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:04:08.698   757  1568 E Watchdog: !@Sync 27 [06-30 14:04:08.709]
,06-30 14:04:16.738   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:04:26.788   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:04:33.138   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:33.138   757  1615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:04:33.148   757  1615 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:04:33.148   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:04:33.158   757   757 I MotionRecognitionService: Plugged
,06-30 14:04:33.158   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:04:33.158   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:04:33.168   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:04:33.168   757  1615 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 14:04:33.178   757  1615 D BatteryService: stay LED for fully charged
,06-30 14:04:33.178  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:04:33.178  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:04:33.178  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:04:33.198  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:33.198  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:33.208  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:36.838   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:04:38.698   757  1568 E Watchdog: !@Sync 28 [06-30 14:04:38.714]
,06-30 14:04:40.998  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:04:46.888   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:04:56.938   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:05:03.218   757  1711 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:07.038   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:05:08.708   757  1568 E Watchdog: !@Sync 29 [06-30 14:05:08.719]
,06-30 14:05:17.088   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 14:05:23.408   757  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:05:23.408   757  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:05:23.408   757  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:05:26.478   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:05:26.478   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:05:26.488   757  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:26.488   757  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:27.148   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:05:33.298   757  1711 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:33.298   757  1711 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:05:33.308   757  1711 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:05:33.308   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:05:33.318   757   757 I MotionRecognitionService: Plugged
,06-30 14:05:33.318   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:05:33.328   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:05:33.328   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:05:33.328   757  1711 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:05:33.328   757  1711 D BatteryService: stay LED for fully charged
,06-30 14:05:33.338  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:33.338  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:33.348  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:05:33.378  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:33.378  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:33.378  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:37.198   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:05:38.708   757  1568 E Watchdog: !@Sync 30 [06-30 14:05:38.723]
,06-30 14:05:41.018  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:05:41.208  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 188ms lastUpdatedAfter : 180354ms
,06-30 14:05:47.348   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:05:47.418   757   767 I art     : Background sticky concurrent mark sweep GC freed 60300(7MB) AllocSpace objects, 379(7MB) LOS objects, 27% free, 41MB/57MB, paused 2.356ms total 145.988ms
,06-30 14:05:57.398   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:01.148   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:06:01.218  5291  5291 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,06-30 14:06:01.258  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:01.268  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 14:06:01.268  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 14:06:01.268  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:06:01.278  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 14:06:01.278   757   850 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,06-30 14:06:01.298  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 14:06:01.298  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.308  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.308  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.328  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:01.328  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:01.338  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.338  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.338  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.358   757   757 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 14:06:01.358   757   757 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 14:06:01.368   757   757 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 14:06:01.368  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.378  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:06:01.378  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:01.378  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:01.378  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:01.378  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:01.378  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:01.378   757   757 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 14:06:01.388  1810  6642 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,06-30 14:06:01.418  5291  5291 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 14:06:01.428  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:06:01.428  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:01.448  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:06:01.448  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:01.448  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:01.448  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:01.448  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:01.448  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:01.468  1810  6625 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 14:06:01.488  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:01.498  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:06:01.498  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:01.498  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:01.498  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:01.498  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:01.498  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:01.518  5291  5291 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 14:06:01.588  1810  6625 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
06-30 14:06:01.588  1810  6625 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 14:06:01.608  1810  6625 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 14:06:01.608  1810  6625 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 14:06:01.648  1810  6625 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
06-30 14:06:01.648  1810  6625 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 14:06:01.738   757  1219 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,06-30 14:06:01.738   757   910 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 14:06:01.748   757   910 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 14:06:01.748   757   910 D SensorManager: unregisterListener ::   
06-30 14:06:01.748   757   910 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,06-30 14:06:01.748   757   910 V AlarmManager:  remove PendingIntent] PendingIntent{b5ee15e: PendingIntentRecord{cc4c93f android broadcastIntent}}
,06-30 14:06:01.818  1951  5312 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-30 14:06:01.908  1810  6625 I ContextCompilationHandl: Recognition context unchanged for APP_NAMES en-US
06-30 14:06:01.908  1810  6625 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 14:06:01.938  1951  5305 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 14:06:01.998  1951  3905 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 14:06:02.048  1951  5311 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 14:06:02.088  1951  5305 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 14:06:02.118  1810  6625 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,06-30 14:06:02.178  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:02.198  1632  1642 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:06:02.198  1632  1642 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:02.198  1632  1642 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:02.198  1632  1642 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:02.198  1632  1642 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:02.198  1632  1642 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:02.238  5291  5291 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 14:06:02.238  5291  5291 D Finsky  : [1] WearSupportService.startHygiene: disabled
,06-30 14:06:02.238  5291  5291 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,06-30 14:06:02.248  5291  5291 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,06-30 14:06:02.248  1632  1645 D DeviceConnectionService: client connected with version: 8296000
,06-30 14:06:03.378   757  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:07.458   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:07.678  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:07.708  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:07.718  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:07.758  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:06:07.758  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 14:06:07.758  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 14:06:07.758  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:07.758  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:07.758  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:07.778  1632  3075 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 14:06:07.778  1632  3075 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 14:06:07.778  1632  3075 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 14:06:07.778  1632  3075 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 14:06:07.778  1632  3075 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:07.778  1632  3075 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:07.778  1632  3075 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:07.778  5291  5336 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:06:07.778  5291  5336 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:06:07.778  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 14:06:07.778  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 14:06:07.778  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 14:06:07.778  5291  5336 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:06:07.778  5291  5336 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:07.778  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:06:07.778  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:06:07.778   303  1097 D EnterpriseController: netId is 0
06-30 14:06:07.778   303  1097 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 14:06:08.718   757  1568 E Watchdog: !@Sync 31 [06-30 14:06:08.730]
,06-30 14:06:16.518   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:06:17.098  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:17.118  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:17.128  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:17.158  1632  4056 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 14:06:17.158  1632  4056 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:17.158  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:17.158  1632  4056 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:17.158  1632  4056 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:17.158  1632  4056 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:17.198  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:06:17.198  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 14:06:17.198  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 14:06:17.558   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:27.608   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:37.208   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:06:37.278   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:37.278   757   772 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 14:06:37.278   757   772 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:06:37.278   757   772 D BatteryService: stay LED for fully charged
06-30 14:06:37.278   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:37.288   757   757 I MotionRecognitionService: Plugged
,06-30 14:06:37.288   757   757 D MotionRecognitionService:   cableConnection= 1
06-30 14:06:37.288   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:06:37.288   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:06:37.288  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:37.298  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:06:37.298  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:37.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:37.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:37.318  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:37.678   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:37.828  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:37.848  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:37.848  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:37.888  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 14:06:37.888  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:37.888  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:37.888  1632  1645 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:37.888  1632  1645 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:37.888  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:37.918  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:06:37.918  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 14:06:37.918  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 14:06:38.728   757  1568 E Watchdog: !@Sync 32 [06-30 14:06:38.735]
,06-30 14:06:41.228  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:06:47.758   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:57.818   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:06:57.928   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:06:58.318  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:58.328  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:58.328  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:58.348  1632  1645 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 14:06:58.348  1632  1645 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:06:58.348  1632  1645 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:06:58.348  1632  1645 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:58.348  1632  1645 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:58.348  1632  1645 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:58.368  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:06:58.368  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:06:58.368  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 14:06:59.988   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 14:07:07.358   757  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:07.358   757  1422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:07:07.368   757  1422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 14:07:07.368   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:07:07.378   757   757 I MotionRecognitionService: Plugged
,06-30 14:07:07.378   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:07:07.378   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:07:07.388   757   757 D MotionRecognitionService: skip setTransmitPower. 
06-30 14:07:07.388   757  1422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,06-30 14:07:07.388   757  1422 D BatteryService: stay LED for fully charged
,06-30 14:07:07.398  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:07.398  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:07.398  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:07:07.428  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:07.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:07.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:07.868   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:07:08.728   757  1568 E Watchdog: !@Sync 33 [06-30 14:07:08.742]
,06-30 14:07:17.968   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:07:18.368   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:07:18.438  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 14:07:18.438  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 14:07:18.438  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:07:18.468  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 14:07:18.468  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 14:07:18.478  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.478  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.488  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.488  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.488  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.488  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.488  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:18.548  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 14:07:19.138  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:07:19.158  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:07:19.158  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:07:19.178  1632  4056 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 14:07:19.178  1632  4056 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:07:19.178  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:07:19.178  1632  4056 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:07:19.178  1632  4056 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:07:19.178  1632  4056 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:07:19.198  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:07:19.198  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:07:19.198  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 14:07:28.018   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:07:38.078   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:07:38.738   757  1568 E Watchdog: !@Sync 34 [06-30 14:07:38.747]
,06-30 14:07:39.218   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:07:39.288   757  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:39.808  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:07:39.838  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:07:39.838  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:07:39.888  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 14:07:39.888  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:07:39.888  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:07:39.888  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:07:39.888  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:07:39.888  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:07:39.928  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:07:39.928  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:07:39.928  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 14:07:41.328  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:07:48.128   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:07:58.188   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:07:59.928   757  1237 V AlarmManager: Expired Alarm result :4
,06-30 14:07:59.998   757  1237 V AlarmManager: Expired Alarm result :8
,06-30 14:08:00.358  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:08:00.368  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:08:00.368  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:08:00.388  1632  3075 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 14:08:00.388  1632  3075 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:08:00.388  1632  3075 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 14:08:00.388  1632  3075 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:08:00.388  1632  3075 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:08:00.388  1632  3075 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:08:00.408  5291  5291 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:08:00.408  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:08:00.408  5291  5291 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 14:08:08.268   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0,
,06-30 14:08:08.738   757  1568 E Watchdog: !@Sync 35 [06-30 14:08:08.751]
,06-30 14:08:09.358   757  2337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:09.358   757  2337 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:08:09.368   757  2337 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:08:09.368   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:09.378   757   757 I MotionRecognitionService: Plugged
,06-30 14:08:09.378   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:08:09.388   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:08:09.388   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:08:09.388   757  2337 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:08:09.388   757  2337 D BatteryService: stay LED for fully charged
,06-30 14:08:09.398  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:09.398  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:09.408  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:09.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:09.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:09.438  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:18.338   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:08:28.388   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:08:38.448   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:08:38.748   757  1568 E Watchdog: !@Sync 36 [06-30 14:08:38.755]
,06-30 14:08:39.438   757   774 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:41.348  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:08:41.508  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 151ms lastUpdatedAfter : 159869ms
,06-30 14:08:48.538   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:08:58.588   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:09:08.638   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:09:08.758   757  1568 E Watchdog: !@Sync 37 [06-30 14:09:08.759]
,06-30 14:09:09.518   757   774 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:18.728   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:09:28.788   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:09:38.748   757  1568 E Watchdog: !@Sync 38 [06-30 14:09:38.764]
,06-30 14:09:38.838   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:09:39.598   757   774 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:39.598   757   774 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:09:39.598   757   774 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:09:39.608   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:39.618   757   757 I MotionRecognitionService: Plugged
,06-30 14:09:39.618   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:09:39.618   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:09:39.628   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:09:39.628   757   774 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:09:39.628   757   774 D BatteryService: stay LED for fully charged
,06-30 14:09:39.638  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:39.638  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:39.638  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:39.658  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:39.668  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:39.668  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:41.518  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:09:48.888   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:09:58.948   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:10:08.758   757  1568 E Watchdog: !@Sync 39 [06-30 14:10:08.770]
,06-30 14:10:09.038   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:10:09.678   757   772 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:09.678   757   772 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:10:09.688   757   772 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:10:09.688   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:10:09.698   757   757 I MotionRecognitionService: Plugged
,06-30 14:10:09.698   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:10:09.698   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:10:09.708   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:10:09.708   757   772 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:10:09.708   757   772 D BatteryService: stay LED for fully charged
,06-30 14:10:09.728  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:09.728  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:09.728  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:10:09.758  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:09.758  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:09.758  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:19.098   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:10:23.398   757  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:10:23.408   757  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:10:23.408   757  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:10:24.748   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:10:24.748   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:10:24.758   757  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:24.768   757  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:29.188   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:10:35.478   757   834 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:38.758   757  1568 E Watchdog: !@Sync 40 [06-30 14:10:38.774]
,06-30 14:10:39.238   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:10:39.758   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:39.758   757  1615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:10:39.768   757  1615 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:10:39.768   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:10:39.778   757   757 I MotionRecognitionService: Plugged
,06-30 14:10:39.778   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:10:39.788   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:10:39.788   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:10:39.788   757  1615 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:10:39.788   757  1615 D BatteryService: stay LED for fully charged
,06-30 14:10:39.798  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:39.798  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:39.808  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:10:39.838  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:39.838  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:39.838  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:41.618  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:10:49.288   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:10:59.348   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:11:07.878  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:07.908  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:07.908  1632  1632 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:07.948  1632  4056 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 14:11:07.948  1632  4056 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 14:11:07.948  1632  4056 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 14:11:07.948  1632  4056 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:11:07.948  1632  4056 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:11:07.948  1632  4056 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:07.968  1632  4056 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 14:11:07.968  1632  4056 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 14:11:07.968  1632  4056 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 14:11:07.968  1632  4056 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 14:11:07.968  1632  4056 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:11:07.968  1632  4056 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:11:07.968  1632  4056 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:08.008  5291  5336 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:11:08.008  5291  5336 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:11:08.008  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 14:11:08.008  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 14:11:08.008  5291  5336 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 14:11:08.008  5291  5336 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:11:08.008  5291  5336 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:08.008  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:11:08.008  5291  5336 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 14:11:08.008   303  1097 D EnterpriseController: netId is 0
06-30 14:11:08.008   303  1097 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 14:11:08.128   757   767 I art     : Background partial concurrent mark sweep GC freed 59107(4MB) AllocSpace objects, 160(3MB) LOS objects, 27% free, 41MB/57MB, paused 2.482ms total 334.526ms
,06-30 14:11:08.768   757  1568 E Watchdog: !@Sync 41 [06-30 14:11:08.784]
,06-30 14:11:09.398   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:11:09.838   757  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:09.838   757  1422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:11:09.848   757  1422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:11:09.848   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:11:09.858   757   757 I MotionRecognitionService: Plugged
,06-30 14:11:09.858   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:11:09.858   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:11:09.868   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:11:09.868   757  1422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:11:09.868   757  1422 D BatteryService: stay LED for fully charged
,06-30 14:11:09.878  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:09.878  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:09.878  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:11:09.908  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:09.908  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:09.908  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:19.458   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:11:29.508   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:11:38.778   757  1568 E Watchdog: !@Sync 42 [06-30 14:11:38.790]
,06-30 14:11:39.568   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:11:39.918   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:41.638  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:11:41.798  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 148ms lastUpdatedAfter : 180287ms
,06-30 14:11:49.618   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:11:59.678   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:12:08.788   757  1568 E Watchdog: !@Sync 43 [06-30 14:12:08.795]
,06-30 14:12:09.728   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:12:09.998   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:19.788   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:12:29.838   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:12:38.788   757  1568 E Watchdog: !@Sync 44 [06-30 14:12:38.802]
,06-30 14:12:39.888   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:12:40.078   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:41.808  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:12:49.968   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:13:00.018   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:13:07.968  1632  3196 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 14:13:08.798   757  1568 E Watchdog: !@Sync 45 [06-30 14:13:08.808]
,06-30 14:13:10.068   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:13:10.158   757  1615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:10.168   757  1615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:13:10.168   757  1615 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:13:10.168   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:10.178   757   757 I MotionRecognitionService: Plugged
,06-30 14:13:10.178   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:13:10.188   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:13:10.188   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:13:10.188   757  1615 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:13:10.198   757  1615 D BatteryService: stay LED for fully charged
,06-30 14:13:10.208  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:10.208  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:10.218  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:13:10.248  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:10.248  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:10.248  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:20.128   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:13:30.178   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:13:38.798   757  1568 E Watchdog: !@Sync 46 [06-30 14:13:38.812]
,06-30 14:13:40.238   757  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:40.248   757  1422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:13:40.248   757  1422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:13:40.248   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:40.258   757   757 I MotionRecognitionService: Plugged
,06-30 14:13:40.268   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:13:40.268   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:13:40.268   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:13:40.278   757  1422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 14:13:40.278   757  1422 D BatteryService: stay LED for fully charged
,06-30 14:13:40.278  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:40.278  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:40.278  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:13:40.298   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:13:40.308  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:40.308  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:40.308  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:41.928  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:13:50.348   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:14:00.408   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:14:08.808   757  1568 E Watchdog: !@Sync 47 [06-30 14:14:08.818]
,06-30 14:14:10.318   757  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:10.318   757  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:14:10.328   757  1320 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:14:10.328   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:10.338   757   757 I MotionRecognitionService: Plugged
,06-30 14:14:10.338   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:14:10.338   757  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
,06-30 14:14:10.348   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:14:10.348   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:14:10.348   757  1320 D BatteryService: stay LED for fully charged
,06-30 14:14:10.368  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:10.368  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:10.368  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:10.398  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:10.398  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:10.398  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:10.448   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:14:20.498   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:14:30.558   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:14:38.808   757  1568 E Watchdog: !@Sync 48 [06-30 14:14:38.823]
,06-30 14:14:40.398   757  1712 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:40.398   757  1712 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:14:40.408   757  1712 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 14:14:40.408   757   757 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:40.418   757   757 I MotionRecognitionService: Plugged
,06-30 14:14:40.418   757   757 D MotionRecognitionService:   cableConnection= 1
,06-30 14:14:40.418   757   757 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:14:40.428   757   757 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:14:40.428   757  1712 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:14:40.428   757  1712 D BatteryService: stay LED for fully charged
,06-30 14:14:40.438  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:40.438  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:40.438  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:40.468  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:40.478  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:40.478  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:40.608   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:14:41.948  1783  1828 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:14:42.148  1783  1828 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 182ms lastUpdatedAfter : 180348ms
,06-30 14:14:50.658   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:15:00.708   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:15:08.818   757  1568 E Watchdog: !@Sync 49 [06-30 14:15:08.828]
,06-30 14:15:10.478   757  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:10.768   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:15:20.818   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 14:15:23.398   757  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:15:23.408   757  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:15:23.408   757  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:15:26.458   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:15:26.458   757  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:15:26.478   757  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:26.478   757  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:30.868   757  3339 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:15:32.088  2280  2280 E audit   : type=1400 msg=audit(1467288932.078:284): avc:  denied  { execmod } for  pid=6801 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 14:15:32.088  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 14:15:32.088  2280  2280 E audit   : type=1300 msg=audit(1467288932.078:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ffd000 a1=51000 a2=5 a3=4 items=0 ppid=3476 ppcomm=adbd pid=6801 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 14:15:32.098  2280  2280 E audit   : type=1327 msg=audit(1467288932.078:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 14:15:32.098  2280  2280 E audit   : type=1320 msg=audit(1467288932.078:284): 
06-30 14:15:32.138  2280  2280 E audit   : type=1400 msg=audit(1467288932.138:285): avc:  denied  { execmod } for  pid=6801 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 14:15:32.138  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 14:15:32.148  2280  2280 E audit   : type=1300 msg=audit(1467288932.138:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc0000 a1=51000 a2=5 a3=4 items=0 ppid=3476 ppcomm=adbd pid=6801 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 14:15:32.148  2280  2280 E audit   : type=1327 msg=audit(1467288932.138:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 14:15:32.148  2280  2280 E audit   : type=1320 msg=audit(1467288932.138:285): 
06-30 14:15:32.188  2280  2280 E audit   : type=1400 msg=audit(1467288932.188:286): avc:  denied  { execmod } for  pid=6801 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 14:15:32.188  2280  2280 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 14:15:32.188  6801  6801 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 14:15:32.188  2280  2280 E audit   : type=1300 msg=audit(1467288932.188:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc0000 a1=51000 a2=5 a3=4 items=0 ppid=3476 ppcomm=adbd pid=6801 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 14:15:32.188  2280  2280 E audit   : type=1327 msg=audit(1467288932.188:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 14:15:32.188  2280  2280 E audit   : type=1320 msg=audit(1467288932.188:286): 
06-30 14:15:32.188  6801  6801 D AndroidRuntime: CheckJNI is OFF
06-30 14:15:32.198  6801  6801 D AndroidRuntime: readGMSProperty: start
06-30 14:15:32.198  6801  6801 D AndroidRuntime: readGMSProperty: already setted!!
06-30 14:15:32.198  6801  6801 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 14:15:32.198  6801  6801 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 14:15:32.198  6801  6801 D AndroidRuntime: readGMSProperty: end
06-30 14:15:32.198  6801  6801 D AndroidRuntime: addProductProperty: start
06-30 14:15:32.198  6801  6801 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 14:15:32.208  6801  6801 W art     : aee24000-b1d4a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 14:15:32.208  6801  6801 W art     : b1d4a000-b3fb9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 14:15:32.208  6801  6801 W art     : b3fb9000-b3fba000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 14:15:32.208  6801  6801 W art     : b3fba000-b3fbb000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.208  6801  6801 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 14:15:32.208  6801  6801 W art     : b4323000-b4771000 r-xp 00000000 b3:17 594        /system/lib/libart.so
06-30 14:15:32.208  6801  6801 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b4772000-b477c000 r--p 0044e000 b3:17 594        /system/lib/libart.so
06-30 14:15:32.208  6801  6801 W art     : b477c000-b477d000 rw-p 00458000 b3:17 594        /system/lib/libart.so
06-30 14:15:32.208  6801  6801 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 14:15:32.208  6801  6801 W art     : b488e000-b4891000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
06-30 14:15:32.208  6801  6801 W art     : b4891000-b4892000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
06-30 14:15:32.208  6801  6801 W art     : b4892000-b4893000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
06-30 14:15:32.208  6801  6801 W art     : b4893000-b4894000 r--p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b4894000-b48b4000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 14:15:32.208  6801  6801 W art     : b48b4000-b52c5000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
06-30 14:15:32.208  6801  6801 W art     : b52c5000-b52c6000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b52c6000-b530f000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
06-30 14:15:32.208  6801  6801 W art     : b530f000-b5310000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
06-30 14:15:32.208  6801  6801 W art     : b5310000-b5318000 rw-p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5318000-b5319000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.208  6801  6801 W art     : b5319000-b534e000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
06-30 14:15:32.208  6801  6801 W art     : b534e000-b534f000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b534f000-b5350000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
06-30 14:15:32.208  6801  6801 W art     : b5350000-b5351000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
06-30 14:15:32.208  6801  6801 W art     : b5351000-b53a9000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
06-30 14:15:32.208  6801  6801 W art     : b53a9000-b53aa000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b53aa000-b53ab000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
06-30 14:15:32.208  6801  6801 W art     : b53ab000-b53ac000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
06-30 14:15:32.208  6801  6801 W art     : b53ad000-b53b3000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 14:15:32.208  6801  6801 W art     : b53b3000-b53b4000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 14:15:32.208  6801  6801 W art     : b53b4000-b53b5000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 14:15:32.208  6801  6801 W art     : b53b5000-b53b7000 rw-p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b53b8000-b53c2000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 14:15:32.208  6801  6801 W art     : b53c2000-b53c5000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 14:15:32.208  6801  6801 W art     : b53c5000-b53c6000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 14:15:32.208  6801  6801 W art     : b53c7000-b53de000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 14:15:32.208  6801  6801 W art     : b53de000-b53df000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b53df000-b53e0000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 14:15:32.208  6801  6801 W art     : b53e0000-b53e1000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 14:15:32.208  6801  6801 W art     : b53e2000-b53ec000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
06-30 14:15:32.208  6801  6801 W art     : b53ec000-b53ed000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
06-30 14:15:32.208  6801  6801 W art     : b53ed000-b53ee000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
06-30 14:15:32.208  6801  6801 W art     : b53ee000-b53f2000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 14:15:32.208  6801  6801 W art     : b53f2000-b53f3000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 14:15:32.208  6801  6801 W art     : b53f3000-b53f4000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 14:15:32.208  6801  6801 W art     : b53f4000-b540a000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
06-30 14:15:32.208  6801  6801 W art     : b540a000-b540b000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
06-30 14:15:32.208  6801  6801 W art     : b540b000-b540c000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
06-30 14:15:32.208  6801  6801 W art     : b540c000-b5419000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
06-30 14:15:32.208  6801  6801 W art     : b5419000-b541a000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
06-30 14:15:32.208  6801  6801 W art     : b541a000-b541b000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
06-30 14:15:32.208  6801  6801 W art     : b541b000-b547b000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
06-30 14:15:32.208  6801  6801 W art     : b547b000-b547e000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
06-30 14:15:32.208  6801  6801 W art     : b547e000-b5482000 rw-p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5482000-b54e3000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
06-30 14:15:32.208  6801  6801 W art     : b54e3000-b54e4000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
06-30 14:15:32.208  6801  6801 W art     : b54e4000-b5533000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
06-30 14:15:32.208  6801  6801 W art     : b5533000-b5535000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
06-30 14:15:32.208  6801  6801 W art     : b5535000-b5536000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
06-30 14:15:32.208  6801  6801 W art     : b5536000-b5537000 rw-p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5537000-b553e000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 14:15:32.208  6801  6801 W art     : b553e000-b553f000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 14:15:32.208  6801  6801 W art     : b553f000-b5540000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 14:15:32.208  6801  6801 W art     : b5541000-b5544000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 14:15:32.208  6801  6801 W art     : b5544000-b5545000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 14:15:32.208  6801  6801 W art     : b5545000-b5546000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 14:15:32.208  6801  6801 W art     : b5547000-b554b000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
06-30 14:15:32.208  6801  6801 W art     : b554b000-b554c000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b554c000-b554d000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
06-30 14:15:32.208  6801  6801 W art     : b554d000-b554e000 rw-p 00005000 b3:17 2517       /system/lib/libpowermanager.so
06-30 14:15:32.208  6801  6801 W art     : b554f000-b556c000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 14:15:32.208  6801  6801 W art     : b556c000-b556d000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 14:15:32.208  6801  6801 W art     : b556d000-b556e000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 14:15:32.208  6801  6801 W art     : b556f000-b5574000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 14:15:32.208  6801  6801 W art     : b5574000-b5575000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 14:15:32.208  6801  6801 W art     : b5575000-b5576000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 14:15:32.208  6801  6801 W art     : b5577000-b55a8000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 14:15:32.208  6801  6801 W art     : b55a8000-b55ab000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 14:15:32.208  6801  6801 W art     : b55ab000-b55ac000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 14:15:32.208  6801  6801 W art     : b55ad000-b55e8000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
06-30 14:15:32.208  6801  6801 W art     : b55e8000-b55e9000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
06-30 14:15:32.208  6801  6801 W art     : b55e9000-b55ea000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
06-30 14:15:32.208  6801  6801 W art     : b55eb000-b55f2000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
06-30 14:15:32.208  6801  6801 W art     : b55f2000-b55f3000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b55f3000-b55f4000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
06-30 14:15:32.208  6801  6801 W art     : b55f4000-b55f5000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
06-30 14:15:32.208  6801  6801 W art     : b55f5000-b55f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.208  6801  6801 W art     : b55f6000-b560d000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
06-30 14:15:32.208  6801  6801 W art     : b560d000-b560e000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b560e000-b5611000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
06-30 14:15:32.208  6801  6801 W art     : b5611000-b5612000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
06-30 14:15:32.208  6801  6801 W art     : b5612000-b5631000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
06-30 14:15:32.208  6801  6801 W art     : b5631000-b5632000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
06-30 14:15:32.208  6801  6801 W art     : b5632000-b5633000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
06-30 14:15:32.208  6801  6801 W art     : b5633000-b5671000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 14:15:32.208  6801  6801 W art     : b5671000-b5672000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5672000-b5674000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 14:15:32.208  6801  6801 W art     : b5674000-b5675000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 14:15:32.208  6801  6801 W art     : b5676000-b567d000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
06-30 14:15:32.208  6801  6801 W art     : b567d000-b567e000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
06-30 14:15:32.208  6801  6801 W art     : b567e000-b567f000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
06-30 14:15:32.208  6801  6801 W art     : b5680000-b5683000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
06-30 14:15:32.208  6801  6801 W art     : b5683000-b5684000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
06-30 14:15:32.208  6801  6801 W art     : b5684000-b5685000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
06-30 14:15:32.208  6801  6801 W art     : b5685000-b568b000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 14:15:32.208  6801  6801 W art     : b568b000-b568c000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b568c000-b568d000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 14:15:32.208  6801  6801 W art     : b568d000-b568e000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 14:15:32.208  6801  6801 W art     : b568e000-b5697000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
06-30 14:15:32.208  6801  6801 W art     : b5697000-b5698000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
06-30 14:15:32.208  6801  6801 W art     : b5698000-b5699000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
06-30 14:15:32.208  6801  6801 W art     : b5699000-b572a000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 14:15:32.208  6801  6801 W art     : b572a000-b572b000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b572b000-b5736000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 14:15:32.208  6801  6801 W art     : b5736000-b5737000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 14:15:32.208  6801  6801 W art     : b5738000-b574a000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
06-30 14:15:32.208  6801  6801 W art     : b574a000-b574b000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
06-30 14:15:32.208  6801  6801 W art     : b574b000-b574c000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
06-30 14:15:32.208  6801  6801 W art     : b574d000-b5752000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
06-30 14:15:32.208  6801  6801 W art     : b5752000-b5753000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
06-30 14:15:32.208  6801  6801 W art     : b5753000-b5754000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
06-30 14:15:32.208  6801  6801 W art     : b5755000-b57c2000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 14:15:32.208  6801  6801 W art     : b57c2000-b57c3000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b57c3000-b57c5000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 14:15:32.208  6801  6801 W art     : b57c5000-b57c6000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 14:15:32.208  6801  6801 W art     : b57c6000-b57c7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.208  6801  6801 W art     : b57c7000-b57ce000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 14:15:32.208  6801  6801 W art     : b57ce000-b57cf000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 14:15:32.208  6801  6801 W art     : b57cf000-b57d0000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 14:15:32.208  6801  6801 W art     : b57d1000-b5851000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 14:15:32.208  6801  6801 W art     : b5851000-b5852000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5852000-b5853000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 14:15:32.208  6801  6801 W art     : b5853000-b5854000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 14:15:32.208  6801  6801 W art     : b5854000-b586b000 rw-p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b586b000-b58a2000 r-xp 00000000 b3:17 3247       /system/vendor/l
06-30 14:15:32.208  6801  6801 W art     : ib/libqc-opt.so
06-30 14:15:32.208  6801  6801 W art     : b58a2000-b58a3000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 14:15:32.208  6801  6801 W art     : b58a3000-b58a4000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 14:15:32.208  6801  6801 W art     : b58a4000-b58c0000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 14:15:32.208  6801  6801 W art     : b58c0000-b58c1000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 14:15:32.208  6801  6801 W art     : b58c1000-b58c2000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 14:15:32.208  6801  6801 W art     : b58c3000-b5924000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 14:15:32.208  6801  6801 W art     : b5924000-b5926000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 14:15:32.208  6801  6801 W art     : b5926000-b5927000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 14:15:32.208  6801  6801 W art     : b5928000-b594f000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
06-30 14:15:32.208  6801  6801 W art     : b594f000-b5950000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5950000-b5951000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
06-30 14:15:32.208  6801  6801 W art     : b5951000-b5952000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
06-30 14:15:32.208  6801  6801 W art     : b5953000-b595b000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 14:15:32.208  6801  6801 W art     : b595b000-b595d000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 14:15:32.208  6801  6801 W art     : b595d000-b595e000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 14:15:32.208  6801  6801 W art     : b595f000-b5962000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
06-30 14:15:32.208  6801  6801 W art     : b5962000-b5963000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
06-30 14:15:32.208  6801  6801 W art     : b5963000-b5964000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
06-30 14:15:32.208  6801  6801 W art     : b5964000-b5968000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
06-30 14:15:32.208  6801  6801 W art     : b5968000-b5969000 ---p 00000000 00:00 0 
06-30 14:15:32.208  6801  6801 W art     : b5969000-b596a000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
06-30 14:15:32.208  6801  6801 W art     : b596a000-b596b000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
06-30 14:15:32.208  6801  6801 W art     : b596b000-b597b000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
06-30 14:15:32.208  6801  6801 W art     : b597b000-b597c000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
06-30 14:15:32.208  6801  6801 W art     : b597c000-b597d000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
06-30 14:15:32.218  6801  6801 W art     : b597d000-b59c3000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b59c3000-b59cc000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
06-30 14:15:32.218  6801  6801 W art     : b59cc000-b59cd000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
06-30 14:15:32.218  6801  6801 W art     : b59cd000-b59ce000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
06-30 14:15:32.218  6801  6801 W art     : b59cf000-b59d4000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
06-30 14:15:32.218  6801  6801 W art     : b59d4000-b59d5000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
06-30 14:15:32.218  6801  6801 W art     : b59d5000-b59d6000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
06-30 14:15:32.218  6801  6801 W art     : b59d6000-b59d9000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 14:15:32.218  6801  6801 W art     : b59d9000-b59da000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b59da000-b59db000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 14:15:32.218  6801  6801 W art     : b59db000-b59dc000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 14:15:32.218  6801  6801 W art     : b59dd000-b59f5000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 14:15:32.218  6801  6801 W art     : b59f5000-b59f6000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b59f6000-b59f7000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 14:15:32.218  6801  6801 W art     : b59f7000-b59f8000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 14:15:32.218  6801  6801 W art     : b59f9000-b5b93000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
06-30 14:15:32.218  6801  6801 W art     : b5b93000-b5b94000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5b94000-b5ba1000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
06-30 14:15:32.218  6801  6801 W art     : b5ba1000-b5ba2000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
06-30 14:15:32.218  6801  6801 W art     : b5ba2000-b5ba6000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
06-30 14:15:32.218  6801  6801 W art     : b5ba6000-b5ba7000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5ba7000-b5ba8000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
06-30 14:15:32.218  6801  6801 W art     : b5ba8000-b5ba9000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
06-30 14:15:32.218  6801  6801 W art     : b5ba9000-b5bbc000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
06-30 14:15:32.218  6801  6801 W art     : b5bbc000-b5bbd000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
06-30 14:15:32.218  6801  6801 W art     : b5bbd000-b5bbe000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
06-30 14:15:32.218  6801  6801 W art     : b5bbf000-b5c0a000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 14:15:32.218  6801  6801 W art     : b5c0a000-b5c0b000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 14:15:32.218  6801  6801 W art     : b5c0b000-b5c0c000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 14:15:32.218  6801  6801 W art     : b5c0c000-b5c0e000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5c0e000-b5c0f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:15:32.218  6801  6801 W art     : b5c0f000-b5c20000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 14:15:32.218  6801  6801 W art     : b5c20000-b5c21000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5c21000-b5c22000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 14:15:32.218  6801  6801 W art     : b5c22000-b5c23000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 14:15:32.218  6801  6801 W art     : b5c24000-b5c2e000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
06-30 14:15:32.218  6801  6801 W art     : b5c2e000-b5c30000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
06-30 14:15:32.218  6801  6801 W art     : b5c30000-b5c31000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
06-30 14:15:32.218  6801  6801 W art     : b5c31000-b5c4a000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
06-30 14:15:32.218  6801  6801 W art     : b5c4a000-b5c4b000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
06-30 14:15:32.218  6801  6801 W art     : b5c4b000-b5c4e000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
06-30 14:15:32.218  6801  6801 W art     : b5c4e000-b5c52000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5c52000-b5cc6000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
06-30 14:15:32.218  6801  6801 W art     : b5cc6000-b5cc7000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5cc7000-b5cca000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
06-30 14:15:32.218  6801  6801 W art     : b5cca000-b5ccb000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
06-30 14:15:32.218  6801  6801 W art     : b5ccc000-b5ccf000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
06-30 14:15:32.218  6801  6801 W art     : b5ccf000-b5cd0000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
06-30 14:15:32.218  6801  6801 W art     : b5cd0000-b5cd1000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
06-30 14:15:32.218  6801  6801 W art     : b5cd1000-b5cd2000 r--p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5cd2000-b5cd7000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 14:15:32.218  6801  6801 W art     : b5cd7000-b5cd8000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 14:15:32.218  6801  6801 W art     : b5cd8000-b5cd9000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 14:15:32.218  6801  6801 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b5cda000-b5cdd000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 14:15:32.218  6801  6801 W art     : b5cdd000-b5cde000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 14:15:32.218  6801  6801 W art     : b5cde000-b5cdf000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 14:15:32.218  6801  6801 W art     : b5cdf000-b5ce0000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b5ce0000-b5ce4000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
06-30 14:15:32.218  6801  6801 W art     : b5ce4000-b5ce5000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
06-30 14:15:32.218  6801  6801 W art     : b5ce5000-b5ce6000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
06-30 14:15:32.218  6801  6801 W art     : b5ce6000-b5ce7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:15:32.218  6801  6801 W art     : b5ce7000-b5ceb000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 14:15:32.218  6801  6801 W art     : b5ceb000-b5cec000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 14:15:32.218  6801  6801 W art     : b5cec000-b5ced000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 14:15:32.218  6801  6801 W art     : b5ced000-b5cee000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b5cee000-b5cfc000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 14:15:32.218  6801  6801 W art     : b5cfc000-b5cfd000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b5cfd000-b5cfe000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 14:15:32.218  6801  6801 W art     : b5cfe000-b5cff000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 14:15:32.218  6801  6801 W art     : b5cff000-b5d09000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 14:15:32.218  6801  6801 W art     : b5d09000-b5d0c000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 14:15:32.218  6801  6801 W art     : b5d0c000-b5d0d000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 14:15:32.218  6801  6801 W art     : b5d0d000-b5d0e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b5d0e000-b5d18000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
06-30 14:15:32.218  6801  6801 W art     : b5d18000-b5d1b000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
06-30 14:15:32.218  6801  6801 W art     : b5d1b000-b5d1c000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
06-30 14:15:32.218  6801  6801 W art     : b5d1c000-b5d20000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
06-30 14:15:32.218  6801  6801 W art     : b5d20000-b5d21000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
06-30 14:15:32.218  6801  6801 W art     : b5d21000-b5d22000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
06-30 14:15:32.218  6801  6801 W art     : b5d22000-b5d23000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b5d23000-b5d30000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 14:15:32.218  6801  6801 W art     : b5d30000-b5d32000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 14:15:32.218  6801  6801 W art     : b5d32000-b5d33000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 14:15:32.218  6801  6801 W art     : b5d33000-b6145000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
06-30 14:15:32.218  6801  6801 W art     : b6145000-b6146000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6146000-b614f000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
06-30 14:15:32.218  6801  6801 W art     : b614f000-b6153000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
06-30 14:15:32.218  6801  6801 W art     : b6153000-b6154000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6154000-b615b000 r-xp 00000000 b3:17 2571       /system/lib/libaud
06-30 14:15:32.218  6801  6801 W art     : ioutils.so
06-30 14:15:32.218  6801  6801 W art     : b615b000-b615c000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 14:15:32.218  6801  6801 W art     : b615c000-b615d000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 14:15:32.218  6801  6801 W art     : b615d000-b615e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b615e000-b6179000 r-xp 00000000
06-30 14:15:32.218  6801  6801 W art     :  b3:17 1184       /system/lib/libz.so
06-30 14:15:32.218  6801  6801 W art     : b6179000-b617a000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 14:15:32.218  6801  6801 W art     : b617a000-b617b000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 14:15:32.218  6801  6801 W art     : b617b000-b617c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b617c000-b61c8000 r-xp 00000000 b3:17 342        
06-30 14:15:32.218  6801  6801 W art     : /system/lib/libharfbuzz_ng.so
06-30 14:15:32.218  6801  6801 W art     : b61c8000-b61c9000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b61c9000-b61ca000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 14:15:32.218  6801  6801 W art     : b61ca000-b61cb000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 14:15:32.218  6801  6801 W art     : b61cb000-b61cc000 r--p 00000000 00:00 0          [anon:li
06-30 14:15:32.218  6801  6801 W art     : nker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b61cc000-b61d0000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
06-30 14:15:32.218  6801  6801 W art     : b61d0000-b61d1000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b61d1000-b61d2000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
06-30 14:15:32.218  6801  6801 W art     : b61d2000-b61d3000 rw-p 00005000 b3:17 2688       /system/lib/libu
06-30 14:15:32.218  6801  6801 W art     : sbhost.so
06-30 14:15:32.218  6801  6801 W art     : b61d3000-b620b000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
06-30 14:15:32.218  6801  6801 W art     : b620b000-b620c000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
06-30 14:15:32.218  6801  6801 W art     : b620c000-b620d000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
06-30 14:15:32.218  6801  6801 W art     : b620d000-b620e000 r--p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     :          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b620e000-b62ac000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
06-30 14:15:32.218  6801  6801 W art     : b62ac000-b62ad000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b62ad000-b62cb000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
06-30 14:15:32.218  6801  6801 W art     : b62cb000-b62cc000 rw-p 000bc000 b3:17 409        /system/lib/libmedia
06-30 14:15:32.218  6801  6801 W art     : .so
06-30 14:15:32.218  6801  6801 W art     : b62cc000-b643f000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
06-30 14:15:32.218  6801  6801 W art     : b643f000-b644a000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
06-30 14:15:32.218  6801  6801 W art     : b644a000-b644b000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
06-30 14:15:32.218  6801  6801 W art     : b644b000-b6562000 r-xp 00000000
06-30 14:15:32.218  6801  6801 W art     :  b3:17 2041       /system/lib/libicuuc.so
06-30 14:15:32.218  6801  6801 W art     : b6562000-b656d000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 14:15:32.218  6801  6801 W art     : b656d000-b656e000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 14:15:32.218  6801  6801 W art     : b656e000-b6572000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6572000-b6596000 r-xp 00000000 b3:17 405        /system/lib/libssl.s
06-30 14:15:32.218  6801  6801 W art     : o
06-30 14:15:32.218  6801  6801 W art     : b6596000-b6598000 r--p 00023000 b3:17 405        /system/lib/libssl.so
06-30 14:15:32.218  6801  6801 W art     : b6598000-b6599000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
06-30 14:15:32.218  6801  6801 W art     : b6599000-b663f000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
06-30 14:15:32.218  6801  6801 W art     : b663f000-b664c000 r--p 000a5000 b3:17 11
06-30 14:15:32.218  6801  6801 W art     : 0        /system/lib/libcrypto.so
06-30 14:15:32.218  6801  6801 W art     : b664c000-b664d000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
06-30 14:15:32.218  6801  6801 W art     : b664d000-b664e000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b664e000-b66a1000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
06-30 14:15:32.218  6801  6801 W art     : b66a1000-b66a2000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b66a2000-b66a3000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
06-30 14:15:32.218  6801  6801 W art     : b66a3000-b66a4000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
06-30 14:15:32.218  6801  6801 W art     : b66a4000-b66a9000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b66a9000-b66bb000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
06-30 14:15:32.218  6801  6801 W art     : b66bb000-b66bc000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b66bc000-b66bd000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
06-30 14:15:32.218  6801  6801 W art     : b66bd000-b66be000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
06-30 14:15:32.218  6801  6801 W art     : b66be000-b66c5000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 14:15:32.218  6801  6801 W art     : b66c5000-b66c6000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 14:15:32.218  6801  6801 W art     : b66c6000-b66c7000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 14:15:32.218  6801  6801 W art     : b66c7000-b66c8000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b66c8000-b66cb000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
06-30 14:15:32.218  6801  6801 W art     : b66cb000-b66cc000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
06-30 14:15:32.218  6801  6801 W art     : b66cc000-b66cd000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
06-30 14:15:32.218  6801  6801 W art     : b66cd000-b66d1000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
06-30 14:15:32.218  6801  6801 W art     : b66d1000-b66d2000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
06-30 14:15:32.218  6801  6801 W art     : b66d2000-b66d3000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
06-30 14:15:32.218  6801  6801 W art     : b66d3000-b66e1000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
06-30 14:15:32.218  6801  6801 W art     : b66e1000-b66e2000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b66e2000-b66e3000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
06-30 14:15:32.218  6801  6801 W art     : b66e3000-b66e4000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
06-30 14:15:32.218  6801  6801 W art     : b66e4000-b66ed000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 14:15:32.218  6801  6801 W art     : b66ed000-b66ee000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 14:15:32.218  6801  6801 W art     : b66ee000-b66ef000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 14:15:32.218  6801  6801 W art     : b66ef000-b6755000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
06-30 14:15:32.218  6801  6801 W art     : b6755000-b6756000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6756000-b6758000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
06-30 14:15:32.218  6801  6801 W art     : b6758000-b6761000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
06-30 14:15:32.218  6801  6801 W art     : b6761000-b6764000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6764000-b67fb000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 14:15:32.218  6801  6801 W art     : b67fb000-b67fd000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 14:15:32.218  6801  6801 W art     : b67fd000-b67fe000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 14:15:32.218  6801  6801 W art     : b67fe000-b67ff000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b67ff000-b6b20000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
06-30 14:15:32.218  6801  6801 W art     : b6b20000-b6b21000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6b21000-b6b3c000 r--p 00321000 b3:17 286        /system/lib/libskia.so
06-30 14:15:32.218  6801  6801 W art     : b6b3c000-b6b40000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
06-30 14:15:32.218  6801  6801 W art     : b6b40000-b6b45000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6b45000-b6b4d000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 14:15:32.218  6801  6801 W art     : b6b4d000-b6b4e000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 14:15:32.218  6801  6801 W art     : b6b4e000-b6b4f000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 14:15:32.218  6801  6801 W art     : b6b4f000-b6b7d000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 14:15:32.218  6801  6801 W art     : b6b7d000-b6b7e000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6b7e000-b6b85000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 14:15:32.218  6801  6801 W art     : b6b85000-b6b86000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 14:15:32.218  6801  6801 W art     : b6b86000-b6bcc000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 14:15:32.218  6801  6801 W art     : b6bcc000-b6bcd000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6bcd000-b6bd0000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 14:15:32.218  6801  6801 W art     : b6bd0000-b6bd1000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 14:15:32.218  6801  6801 W art     : b6bd1000-b6bec000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
06-30 14:15:32.218  6801  6801 W art     : b6bec000-b6bf0000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
06-30 14:15:32.218  6801  6801 W art     : b6bf0000-b6bf1000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
06-30 14:15:32.218  6801  6801 W art     : b6bf1000-b6c3e000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
06-30 14:15:32.218  6801  6801 W art     : b6c3e000-b6c3f000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6c3f000-b6c4b000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
06-30 14:15:32.218  6801  6801 W art     : b6c4b000-b6c4c000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
06-30 14:15:32.218  6801  6801 W art     : b6c4c000-b6c59000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
06-30 14:15:32.218  6801  6801 W art     : b6c59000-b6c5a000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6c5a000-b6c5b000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
06-30 14:15:32.218  6801  6801 W art     : b6c5b000-b6c5c000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
06-30 14:15:32.218  6801  6801 W art     : b6c5c000-b6c64000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
06-30 14:15:32.218  6801  6801 W art     : b6c64000-b6c65000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6c65000-b6c66000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
06-30 14:15:32.218  6801  6801 W art     : b6c66000-b6c67000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
06-30 14:15:32.218  6801  6801 W art     : b6c67000-b6c6e000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 14:15:32.218  6801  6801 W art     : b6c6e000-b6c6f000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 14:15:32.218  6801  6801 W art     : b6c6f000-b6c70000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 14:15:32.218  6801  6801 W art     : b6c70000-b6c84000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
06-30 14:15:32.218  6801  6801 W art     : b6c84000-b6c86000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
06-30 14:15:32.218  6801  6801 W art     : b6c86000-b6c87000 rw-p 00015000 b3:17 2082       /system/lib/libexpat.so
06-30 14:15:32.218  6801  6801 W art     : b6c87000-b6caf000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
06-30 14:15:32.218  6801  6801 W art     : b6caf000-b6cb1000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
06-30 14:15:32.218  6801  6801 W art     : b6cb1000-b6cb2000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
06-30 14:15:32.218  6801  6801 W art     : b6cb2000-b6cb5000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
06-30 14:15:32.218  6801  6801 W art     : b6cb5000-b6cb6000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
06-30 14:15:32.218  6801  6801 W art     : b6cb6000-b6cb7000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
06-30 14:15:32.218  6801  6801 W art     : b6cb7000-b6cc0000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 14:15:32.218  6801  6801 W art     : b6cc0000-b6cc1000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 14:15:32.218  6801  6801 W art     : b6cc1000-b6cc2000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 14:15:32.218  6801  6801 W art     : b6cc2000-b6ce2000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 14:15:32.218  6801  6801 W art     : b6ce2000-b6ce3000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 14:15:32.218  6801  6801 W art     : b6ce3000-b6ce4000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 14:15:32.218  6801  6801 W art     : b6ce4000-b6d57000 r-xp 00000000 b3:17 328        /system/lib/libc.so
06-30 14:15:32.218  6801  6801 W art     : b6d57000-b6d5b000 r--p 00072000 b3:17 328        /system/lib/libc.so
06-30 14:15:32.218  6801  6801 W art     : b6d5b000-b6d5e000 rw-p 00076000 b3:17 328        /system/lib/libc.so
06-30 14:15:32.218  6801  6801 W art     : b6d5e000-b6d68000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6d68000-b6df0000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 14:15:32.218  6801  6801 W art     : b6df0000-b6df1000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6df1000-b6df5000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 14:15:32.218  6801  6801 W art     : b6df5000-b6df6000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 14:15:32.218  6801  6801 W art     : b6df6000-b6df7000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6df7000-b6e20000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 14:15:32.218  6801  6801 W art     : b6e20000-b6e21000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6e21000-b6e24000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 14:15:32.218  6801  6801 W art     : b6e24000-b6e25000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 14:15:32.218  6801  6801 W art     : b6e25000-b6eff000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 14:15:32.218  6801  6801 W art     : b6eff000-b6f06000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 14:15:32.218  6801  6801 W art     : b6f06000-b6f0e000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 14:15:32.218  6801  6801 W art     : b6f0e000-b6f0f000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6f0f000-b6f10000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:15:32.218  6801  6801 W art     : b6f10000-b6f11000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 14:15:32.218  6801  6801 W art     : b6f11000-b6f12000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b6f12000-b6f15000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b6f15000-b6f3a000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
06-30 14:15:32.218  6801  6801 W art     : b6f3a000-b6f3b000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6f3b000-b6f42000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
06-30 14:15:32.218  6801  6801 W art     : b6f42000-b6f43000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
06-30 14:15:32.218  6801  6801 W art     : b6f43000-b6f4a000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 14:15:32.218  6801  6801 W art     : b6f4a000-b6f4b000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 14:15:32.218  6801  6801 W art     : b6f4b000-b6f4c000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 14:15:32.218  6801  6801 W art     : b6f4c000-b6f4d000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b6f4d000-b6f65000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
06-30 14:15:32.218  6801  6801 W art     : b6f65000-b6f66000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6f66000-b6f67000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
06-30 14:15:32.218  6801  6801 W art     : b6f67000-b6f68000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
06-30 14:15:32.218  6801  6801 W art     : b6f68000-b6f76000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
06-30 14:15:32.218  6801  6801 W art     : b6f76000-b6f77000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6f77000-b6f78000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
06-30 14:15:32.218  6801  6801 W art     : b6f78000-b6f79000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
06-30 14:15:32.218  6801  6801 W art     : b6f79000-b6f7a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:15:32.218  6801  6801 W art     : b6f7a000-b6f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b6f7c000-b6f7d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b6f7d000-b6f7e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:15:32.218  6801  6801 W art     : b6f7e000-b6f7f000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 14:15:32.218  6801  6801 W art     : b6f7f000-b6f80000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:15:32.218  6801  6801 W art     : b6f80000-b6fa0000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 14:15:32.218  6801  6801 W art     : b6fa0000-b6fa1000 r--p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6fa1000-b6fa2000 ---p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6fa2000-b6fa4000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 14:15:32.218  6801  6801 W art     : b6fa4000-b6fa5000 r-xp 00000000 00:00 0          [sigpage]
06-30 14:15:32.218  6801  6801 W art     : b6fa5000-b6fc0000 r-xp 00000000 b3:17 2771       /system/bin/linker
06-30 14:15:32.218  6801  6801 W art     : b6fc0000-b6fc1000 r--p 0001a000 b3:17 2771       /system/bin/linker
06-30 14:15:32.218  6801  6801 W art     : b6fc1000-b6fc3000 rw-p 0001b000 b3:17 2771       /system/bin/linker
06-30 14:15:32.218  6801  6801 W art     : b6fc3000-b6fc5000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : b6fc5000-b6fca000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 14:15:32.218  6801  6801 W art     : b6fca000-b6fcb000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 14:15:32.218  6801  6801 W art     : b6fcb000-b6fcc000 rw-p 00000000 00:00 0 
06-30 14:15:32.218  6801  6801 W art     : bea4e000-bea6f000 rw-p 00000000 00:00 0          [stack]
06-30 14:15:32.218  6801  6801 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 14:15:32.258  6801  6801 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 14:15:32.308  6801  6801 I Radio-JNI: register_android_hardware_Radio DONE
06-30 14:15:32.318  6801  6801 E AffinityControl: AffinityControl: registerfunction enter
06-30 14:15:32.338  6801  6801 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 14:15:32.348   757   772 D PackageManager: START PACKAGE DELETE: observer{138176434}
06-30 14:15:32.348   757   772 D PackageManager: pkg{<packageName>}
06-30 14:15:32.348   757   772 D PackageManager: user{0}
06-30 14:15:32.348   757   772 D PackageManager: caller{2000}
06-30 14:15:32.348   757   772 D PackageManager: flags{2}
06-30 14:15:32.348   757   772 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 14:15:32.348   757   772 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 14:15:32.348   757   772 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 14:15:32.348   757   772 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 14:15:32.348   757   772 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 14:15:32.348   757   923 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 14:15:32.348   757   923 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 14:15:32.348   757   923 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 14:15:32.348   757   923 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 14:15:32.348   757   923 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 14:15:32.348   757   923 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 14:15:32.348   757   923 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 14:15:32.348   757   923 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
06-30 14:15:32.348   757   850 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
06-30 14:15:32.358   757   923 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 14:15:32.358   757   923 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 14:15:32.358   757   850 I ActivityManager: Killing 6130:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
06-30 14:15:32.358   757   850 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 14:15:32.358   757   850 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 14:15:32.378   757   850 I ActivityManager: Start proc 6822:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 14:15:32.378  6822  6822 E Zygote  : v2
06-30 14:15:32.378  6822  6822 I libpersona: KNOX_SDCARD checking this for 10004
06-30 14:15:32.378  6822  6822 I libpersona: KNOX_SDCARD not a persona
06-30 14:15:32.378   757   850 I ActivityManager: Killing 6542:com.sec.android.app.shealth:remote/u0a35 (adj 5): SSR - service for lastStateTime 709s, lastActivityTime 708s
06-30 14:15:32.378   757   850 I ActivityManager: Killing 6525:com.sec.android.daemonapp/u0a182 (adj 5): SSR - service for lastStateTime 852s, lastActivityTime 852s
06-30 14:15:32.378   757   850 I ActivityManager: Killing 6504:com.sec.android.pagebuddynotisvc/u0a27 (adj 8): SSR - service for lastStateTime 853s, lastActivityTime 853s
06-30 14:15:32.378  6822  6822 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 14:15:32.378  6822  6822 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 14:15:32.378   757   850 I ActivityManager: Killing 6489:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 863s, lastActivityTime 863s
06-30 14:15:32.378  6822  6822 E Zygote  : accessInfo : 0
06-30 14:15:32.378  6822  6822 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 14:15:32.378   757   850 I ActivityManager:   Force finishing activity ActivityRecord{976abe6 u0 com.test.thalitest/.MainActivity t78}
06-30 14:15:32.378   757   850 I ActivityManager:   Force finishing activity ActivityRecord{3a5f0c9 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t78}

```
