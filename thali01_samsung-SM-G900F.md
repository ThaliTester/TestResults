#### Test 82642184cbac892_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-30 02:45:59.986   781  1234 V AlarmManager: Expired Alarm result :8
,08-30 02:46:00.366   781  3587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
08-30 02:46:00.866  2548  2548 E audit   : type=1400 msg=audit(1472517960.866:285): avc:  denied  { execmod } for  pid=6442 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 02:46:00.866  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:00.866  2548  2548 E audit   : type=1300 msg=audit(1472517960.866:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff1000 a1=51000 a2=5 a3=4 items=0 ppid=3683 ppcomm=adbd pid=6442 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 02:46:00.866  2548  2548 E audit   : type=1327 msg=audit(1472517960.866:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 02:46:00.866  2548  2548 E audit   : type=1320 msg=audit(1472517960.866:285): 
08-30 02:46:00.926  2548  2548 E audit   : type=1400 msg=audit(1472517960.916:286): avc:  denied  { execmod } for  pid=6442 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 02:46:00.926  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:00.926  2548  2548 E audit   : type=1300 msg=audit(1472517960.916:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb1000 a1=51000 a2=5 a3=4 items=0 ppid=3683 ppcomm=adbd pid=6442 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 02:46:00.926  2548  2548 E audit   : type=1327 msg=audit(1472517960.916:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 02:46:00.926  2548  2548 E audit   : type=1320 msg=audit(1472517960.916:286): 
08-30 02:46:00.966  2548  2548 E audit   : type=1400 msg=audit(1472517960.966:287): avc:  denied  { execmod } for  pid=6442 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 02:46:00.966  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:00.966  2548  2548 E audit   : type=1300 msg=audit(1472517960.966:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb1000 a1=51000 a2=5 a3=4 items=0 ppid=3683 ppcomm=adbd pid=6442 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 02:46:00.966  2548  2548 E audit   : type=1327 msg=audit(1472517960.966:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 02:46:00.966  2548  2548 E audit   : type=1320 msg=audit(1472517960.966:287): 
08-30 02:46:00.966  6442  6442 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 02:46:00.966  6442  6442 D AndroidRuntime: CheckJNI is OFF
08-30 02:46:00.966  6442  6442 D AndroidRuntime: readGMSProperty: start
08-30 02:46:00.966  6442  6442 D AndroidRuntime: readGMSProperty: already setted!!
08-30 02:46:00.966  6442  6442 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 02:46:00.966  6442  6442 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 02:46:00.966  6442  6442 D AndroidRuntime: readGMSProperty: end
08-30 02:46:00.966  6442  6442 D AndroidRuntime: addProductProperty: start
08-30 02:46:00.976  6442  6442 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 02:46:00.976  6442  6442 W art     : af160000-b2086000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-30 02:46:00.976  6442  6442 W art     : b2086000-b42f5000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-30 02:46:00.976  6442  6442 W art     : b42f5000-b42f6000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-30 02:46:00.976  6442  6442 W art     : b42f6000-b431f000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 02:46:00.976  6442  6442 W art     : b431f000-b4322000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-30 02:46:00.976  6442  6442 W art     : b4322000-b4323000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-30 02:46:00.976  6442  6442 W art     : b4323000-b4324000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-30 02:46:00.976  6442  6442 W art     : b4324000-b4772000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-30 02:46:00.976  6442  6442 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b4773000-b477d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-30 02:46:00.976  6442  6442 W art     : b477d000-b477e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-30 02:46:00.976  6442  6442 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-30 02:46:00.976  6442  6442 W art     : b4882000-b4883000 r--p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b4883000-b48a3000 r--s 00000000 00:0b 7201       /dev/__properties__
08-30 02:46:00.976  6442  6442 W art     : b48a3000-b52b4000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-30 02:46:00.976  6442  6442 W art     : b52b4000-b52b5000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b52b5000-b52fe000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-30 02:46:00.976  6442  6442 W art     : b52fe000-b52ff000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-30 02:46:00.976  6442  6442 W art     : b52ff000-b5307000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5307000-b533c000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-30 02:46:00.976  6442  6442 W art     : b533c000-b533d000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b533d000-b533e000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-30 02:46:00.976  6442  6442 W art     : b533e000-b533f000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-30 02:46:00.976  6442  6442 W art     : b533f000-b5397000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-30 02:46:00.976  6442  6442 W art     : b5397000-b5398000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5398000-b5399000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-30 02:46:00.976  6442  6442 W art     : b5399000-b539a000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-30 02:46:00.976  6442  6442 W art     : b539b000-b53a1000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 02:46:00.976  6442  6442 W art     : b53a1000-b53a2000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 02:46:00.976  6442  6442 W art     : b53a2000-b53a3000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 02:46:00.976  6442  6442 W art     : b53a3000-b53a5000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b53a6000-b53b0000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 02:46:00.976  6442  6442 W art     : b53b0000-b53b3000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 02:46:00.976  6442  6442 W art     : b53b3000-b53b4000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 02:46:00.976  6442  6442 W art     : b53b5000-b53cc000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 02:46:00.976  6442  6442 W art     : b53cc000-b53cd000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b53cd000-b53ce000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 02:46:00.976  6442  6442 W art     : b53ce000-b53cf000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 02:46:00.976  6442  6442 W art     : b53d0000-b53da000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-30 02:46:00.976  6442  6442 W art     : b53da000-b53db000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-30 02:46:00.976  6442  6442 W art     : b53db000-b53dc000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-30 02:46:00.976  6442  6442 W art     : b53dc000-b53e0000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 02:46:00.976  6442  6442 W art     : b53e0000-b53e1000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 02:46:00.976  6442  6442 W art     : b53e1000-b53e2000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 02:46:00.976  6442  6442 W art     : b53e2000-b53f8000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-30 02:46:00.976  6442  6442 W art     : b53f8000-b53f9000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-30 02:46:00.976  6442  6442 W art     : b53f9000-b53fa000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-30 02:46:00.976  6442  6442 W art     : b53fa000-b5407000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-30 02:46:00.976  6442  6442 W art     : b5407000-b5408000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-30 02:46:00.976  6442  6442 W art     : b5408000-b5409000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-30 02:46:00.976  6442  6442 W art     : b5409000-b5469000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-30 02:46:00.976  6442  6442 W art     : b5469000-b546c000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-30 02:46:00.976  6442  6442 W art     : b546c000-b5470000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5470000-b54d1000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-30 02:46:00.976  6442  6442 W art     : b54d1000-b54d2000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-30 02:46:00.976  6442  6442 W art     : b54d2000-b5521000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-30 02:46:00.976  6442  6442 W art     : b5521000-b5523000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-30 02:46:00.976  6442  6442 W art     : b5523000-b5524000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-30 02:46:00.976  6442  6442 W art     : b5524000-b5525000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5525000-b552c000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 02:46:00.976  6442  6442 W art     : b552c000-b552d000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 02:46:00.976  6442  6442 W art     : b552d000-b552e000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-30 02:46:00.976  6442  6442 W art     : avc_common.so
08-30 02:46:00.976  6442  6442 W art     : b552f000-b5532000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 02:46:00.976  6442  6442 W art     : b5532000-b5533000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 02:46:00.976  6442  6442 W art     : b5533000-b5534000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-30 02:46:00.976  6442  6442 W art     : enc_common.so
08-30 02:46:00.976  6442  6442 W art     : b5535000-b5539000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-30 02:46:00.976  6442  6442 W art     : b5539000-b553a000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b553a000-b553b000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-30 02:46:00.976  6442  6442 W art     : b553b000-b553c000 rw-p 00005000 b3:17 2510       /syste
08-30 02:46:00.976  6442  6442 W art     : m/lib/libpowermanager.so
08-30 02:46:00.976  6442  6442 W art     : b553d000-b555a000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 02:46:00.976  6442  6442 W art     : b555a000-b555b000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 02:46:00.976  6442  6442 W art     : b555b000-b555c000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 02:46:00.976  6442  6442 W art     : b555d000-b5562000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 02:46:00.976  6442  6442 W art     : b5562000-b5563000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 02:46:00.976  6442  6442 W art     : b5563000-b5564000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 02:46:00.976  6442  6442 W art     : b5565000-b5596000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 02:46:00.976  6442  6442 W art     : b5596000-b5597000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5597000-b559a000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 02:46:00.976  6442  6442 W art     : b559a000-b559b000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 02:46:00.976  6442  6442 W art     : b559c000-b55d7000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-30 02:46:00.976  6442  6442 W art     : b55d7000-b55d8000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-30 02:46:00.976  6442  6442 W art     : b55d8000-b55d9000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-30 02:46:00.976  6442  6442 W art     : b55da000-b55e1000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-30 02:46:00.976  6442  6442 W art     : b55e1000-b55e2000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b55e2000-b55e3000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-30 02:46:00.976  6442  6442 W art     : b55e3000-b55e4000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-30 02:46:00.976  6442  6442 W art     : b55e4000-b55e5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b55e5000-b55fc000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-30 02:46:00.976  6442  6442 W art     : b55fc000-b55fd000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b55fd000-b5600000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-30 02:46:00.976  6442  6442 W art     : b5600000-b5601000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-30 02:46:00.976  6442  6442 W art     : b5601000-b5620000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-30 02:46:00.976  6442  6442 W art     : b5620000-b5621000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-30 02:46:00.976  6442  6442 W art     : b5621000-b5622000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-30 02:46:00.976  6442  6442 W art     : b5622000-b5660000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-30 02:46:00.976  6442  6442 W art     : b5660000-b5661000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5661000-b5663000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-30 02:46:00.976  6442  6442 W art     : b5663000-b5664000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-30 02:46:00.976  6442  6442 W art     : b5665000-b566c000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 02:46:00.976  6442  6442 W art     : b566c000-b566d000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 02:46:00.976  6442  6442 W art     : b566d000-b566e000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 02:46:00.976  6442  6442 W art     : b566f000-b5672000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 02:46:00.976  6442  6442 W art     : b5672000-b5673000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 02:46:00.976  6442  6442 W art     : b5673000-b5674000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 02:46:00.976  6442  6442 W art     : b5674000-b567a000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 02:46:00.976  6442  6442 W art     : b567a000-b567b000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b567b000-b567c000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 02:46:00.976  6442  6442 W art     : b567c000-b567d000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 02:46:00.976  6442  6442 W art     : b567d000-b5686000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-30 02:46:00.976  6442  6442 W art     : b5686000-b5687000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-30 02:46:00.976  6442  6442 W art     : b5687000-b5688000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-30 02:46:00.976  6442  6442 W art     : b5688000-b5719000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 02:46:00.976  6442  6442 W art     : b5719000-b571a000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b571a000-b5725000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 02:46:00.976  6442  6442 W art     : b5725000-b5726000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 02:46:00.976  6442  6442 W art     : b5727000-b5739000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-30 02:46:00.976  6442  6442 W art     : b5739000-b573a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-30 02:46:00.976  6442  6442 W art     : b573a000-b573b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-30 02:46:00.976  6442  6442 W art     : b573c000-b5741000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-30 02:46:00.976  6442  6442 W art     : b5741000-b5742000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-30 02:46:00.976  6442  6442 W art     : b5742000-b5743000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-30 02:46:00.976  6442  6442 W art     : b5744000-b57b1000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-30 02:46:00.976  6442  6442 W art     : b57b1000-b57b2000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b57b2000-b57b4000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-30 02:46:00.976  6442  6442 W art     : b57b4000-b57b5000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-30 02:46:00.976  6442  6442 W art     : b57b5000-b57b6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b57b6000-b57bd000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 02:46:00.976  6442  6442 W art     : b57bd000-b57be000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 02:46:00.976  6442  6442 W art     : b57be000-b57bf000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 02:46:00.976  6442  6442 W art     : b57c0000-b5840000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 02:46:00.976  6442  6442 W art     : b5840000-b5841000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5841000-b5842000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 02:46:00.976  6442  6442 W art     : b5842000-b5843000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 02:46:00.976  6442  6442 W art     : b5843000-b585a000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b585a000-b5891000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 02:46:00.976  6442  6442 W art     : b5891000-b5892000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 02:46:00.976  6442  6442 W art     : b5892000-b5893000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 02:46:00.976  6442  6442 W art     : b5893000-b58af000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 02:46:00.976  6442  6442 W art     : b58af000-b58b0000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 02:46:00.976  6442  6442 W art     : b58b0000-b58b1000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 02:46:00.976  6442  6442 W art     : b58b2000-b5913000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-30 02:46:00.976  6442  6442 W art     : b5913000-b5915000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-30 02:46:00.976  6442  6442 W art     : b5915000-b5916000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-30 02:46:00.976  6442  6442 W art     : b5917000-b593c000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-30 02:46:00.976  6442  6442 W art     : b593c000-b593d000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-30 02:46:00.976  6442  6442 W art     : b593d000-b593e000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-30 02:46:00.976  6442  6442 W art     : b593f000-b5947000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 02:46:00.976  6442  6442 W art     : b5947000-b5949000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 02:46:00.976  6442  6442 W art     : b5949000-b594a000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 02:46:00.976  6442  6442 W art     : b594b000-b594e000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-30 02:46:00.976  6442  6442 W art     : b594e000-b594f000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-30 02:46:00.976  6442  6442 W art     : b594f000-b5950000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-30 02:46:00.976  6442  6442 W art     : b5950000-b5954000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-30 02:46:00.976  6442  6442 W art     : b5954000-b5955000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5955000-b5956000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-30 02:46:00.976  6442  6442 W art     : b5956000-b5957000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-30 02:46:00.976  6442  6442 W art     : b5957000-b5967000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-30 02:46:00.976  6442  6442 W art     : b5967000-b5968000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-30 02:46:00.976  6442  6442 W art     : b5968000-b5969000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-30 02:46:00.976  6442  6442 W art     : b5969000-b59af000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b59af000-b59b8000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-30 02:46:00.976  6442  6442 W art     : b59b8000-b59b9000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-30 02:46:00.976  6442  6442 W art     : b59b9000-b59ba000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-30 02:46:00.976  6442  6442 W art     : b59bb000-b59c0000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-30 02:46:00.976  6442  6442 W art     : b59c0000-b59c1000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-30 02:46:00.976  6442  6442 W art     : b59c1000-b59c2000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-30 02:46:00.976  6442  6442 W art     : b59c2000-b59c5000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 02:46:00.976  6442  6442 W art     : b59c5000-b59c6000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b59c6000-b59c7000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 02:46:00.976  6442  6442 W art     : b59c7000-b59c8000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 02:46:00.976  6442  6442 W art     : b59c8000-b59c9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-30 02:46:00.976  6442  6442 W art     : or]
08-30 02:46:00.976  6442  6442 W art     : b59c9000-b59e1000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 02:46:00.976  6442  6442 W art     : b59e1000-b59e2000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b59e2000-b59e3000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 02:46:00.976  6442  6442 W art     : b59e3000-b59e4000 rw-p 00019000 b3:
08-30 02:46:00.976  6442  6442 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-30 02:46:00.976  6442  6442 W art     : b59e5000-b5b7f000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-30 02:46:00.976  6442  6442 W art     : b5b7f000-b5b80000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5b80000-b5b8d000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-30 02:46:00.976  6442  6442 W art     : b5b8d000-b5b8e000 rw-p 001a7000 b3:17 604        /system/
08-30 02:46:00.976  6442  6442 W art     : lib/libstagefright.so
08-30 02:46:00.976  6442  6442 W art     : b5b8e000-b5b92000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-30 02:46:00.976  6442  6442 W art     : b5b92000-b5b93000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5b93000-b5b94000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-30 02:46:00.976  6442  6442 W art     : b5b94000-b5b95000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-30 02:46:00.976  6442  6442 W art     : ersona.so
08-30 02:46:00.976  6442  6442 W art     : b5b95000-b5ba8000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-30 02:46:00.976  6442  6442 W art     : b5ba8000-b5ba9000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-30 02:46:00.976  6442  6442 W art     : b5ba9000-b5baa000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-30 02:46:00.976  6442  6442 W art     : b5bab000-b5bf6000 r
08-30 02:46:00.976  6442  6442 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-30 02:46:00.976  6442  6442 W art     : b5bf6000-b5bf7000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-30 02:46:00.976  6442  6442 W art     : b5bf7000-b5bf8000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-30 02:46:00.976  6442  6442 W art     : b5bf8000-b5bfa000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5bfa000-b5bfb000 r--p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5bfb000-b5c0c000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 02:46:00.976  6442  6442 W art     : b5c0c000-b5c0d000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5c0d000-b5c0e000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 02:46:00.976  6442  6442 W art     : b5c0e000-b5c0f000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 02:46:00.976  6442  6442 W art     : b5c0f000-b5c10000 r--p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5c10000-b5c1a000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-30 02:46:00.976  6442  6442 W art     : b5c1a000-b5c1c000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-30 02:46:00.976  6442  6442 W art     : b5c1c000-b5c1d000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-30 02:46:00.976  6442  6442 W art     : b5c1d000-b5c36000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-30 02:46:00.976  6442  6442 W art     : b5c36000-b5c37000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-30 02:46:00.976  6442  6442 W art     : b5c37000-b5c3a000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-30 02:46:00.976  6442  6442 W art     : b5c3a000-b5c3e000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5c3e000-b5cb2000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-30 02:46:00.976  6442  6442 W art     : b5cb2000-b5cb3000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5cb3000-b5cb6000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-30 02:46:00.976  6442  6442 W art     : b5cb6000-b5cb7000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-30 02:46:00.976  6442  6442 W art     : b5cb7000-b5cb8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5cb8000-b5cbb000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-30 02:46:00.976  6442  6442 W art     : b5cbb000-b5cbc000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-30 02:46:00.976  6442  6442 W art     : b5cbc000-b5cbd000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-30 02:46:00.976  6442  6442 W art     : b5cbd000-b5cbe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5cbe000-b5cc3000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 02:46:00.976  6442  6442 W art     : b5cc3000-b5cc4000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 02:46:00.976  6442  6442 W art     : b5cc4000-b5cc5000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 02:46:00.976  6442  6442 W art     : b5cc5000-b5cc6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5cc6000-b5cc9000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 02:46:00.976  6442  6442 W art     : b5cc9000-b5cca000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 02:46:00.976  6442  6442 W art     : b5cca000-b5ccb000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 02:46:00.976  6442  6442 W art     : b5ccb000-b5ccc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:00.976  6442  6442 W art     : b5ccc000-b5cd0000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-30 02:46:00.976  6442  6442 W art     : b5cd0000-b5cd1000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-30 02:46:00.976  6442  6442 W art     : b5cd1000-b5cd2000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-30 02:46:00.976  6442  6442 W art     : b5cd2000-b5cd3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5cd3000-b5cd7000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 02:46:00.976  6442  6442 W art     : b5cd7000-b5cd8000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 02:46:00.976  6442  6442 W art     : b5cd8000-b5cd9000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 02:46:00.976  6442  6442 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5cda000-b5ce8000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-30 02:46:00.976  6442  6442 W art     : b5ce8000-b5ce9000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b5ce9000-b5cea000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-30 02:46:00.976  6442  6442 W art     : b5cea000-b5ceb000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-30 02:46:00.976  6442  6442 W art     : b5ceb000-b5cf5000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 02:46:00.976  6442  6442 W art     : b5cf5000-b5cf8000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 02:46:00.976  6442  6442 W art     : b5cf8000-b5cf9000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 02:46:00.976  6442  6442 W art     : b5cf9000-b5cfa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5cfa000-b5d04000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-30 02:46:00.976  6442  6442 W art     : b5d04000-b5d07000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-30 02:46:00.976  6442  6442 W art     : b5d07000-b5d08000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-30 02:46:00.976  6442  6442 W art     : b5d08000-b5d0c000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-30 02:46:00.976  6442  6442 W art     : b5d0c000-b5d0d000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-30 02:46:00.976  6442  6442 W art     : b5d0d000-b5d0e000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-30 02:46:00.976  6442  6442 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b5d0f000-b5d1c000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-30 02:46:00.976  6442  6442 W art     : b5d1c000-b5d1e000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-30 02:46:00.976  6442  6442 W art     : b5d1e000-b5d1f000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-30 02:46:00.976  6442  6442 W art     : b5d1f000-b6131000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-30 02:46:00.976  6442  6442 W art     : b6131000-b6132000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6132000-b613b000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-30 02:46:00.976  6442  6442 W art     : b613b000-b613f000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-30 02:46:00.976  6442  6442 W art     : b613f000-b6140000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6140000-b6147000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-30 02:46:00.976  6442  6442 W art     : b6147000-b6148000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-30 02:46:00.976  6442  6442 W art     : b6148000-b6149000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-30 02:46:00.976  6442  6442 W art     : b6149000-b614a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b614a000-b6165000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-30 02:46:00.976  6442  6442 W art     : b6165000-b6166000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-30 02:46:00.976  6442  6442 W art     : b6166000-b6167000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-30 02:46:00.976  6442  6442 W art     : b6167000-b6168000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b6168000-b61b4000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 02:46:00.976  6442  6442 W art     : b61b4000-b61b5000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b61b5000-b61b6000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 02:46:00.976  6442  6442 W art     : b61b6000-b61b7000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 02:46:00.976  6442  6442 W art     : b61b7000-b61b8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b61b8000-b61bc000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-30 02:46:00.976  6442  6442 W art     : b61bc000-b61bd000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b61bd000-b61be000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-30 02:46:00.976  6442  6442 W art     : b61be000-b61bf000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-30 02:46:00.976  6442  6442 W art     : b61bf000-b61f7000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-30 02:46:00.976  6442  6442 W art     : b61f7000-b61f8000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-30 02:46:00.976  6442  6442 W art     : b61f8000-b61f9000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-30 02:46:00.976  6442  6442 W art     : b61f9000-b61fa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.976  6442  6442 W art     : b61fa000-b6299000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-30 02:46:00.976  6442  6442 W art     : b6299000-b62b7000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-30 02:46:00.976  6442  6442 W art     : b62b7000-b62b8000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-30 02:46:00.976  6442  6442 W art     : b62b8000-b642b000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-30 02:46:00.976  6442  6442 W art     : b642b000-b6436000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-30 02:46:00.976  6442  6442 W art     : b6436000-b6437000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-30 02:46:00.976  6442  6442 W art     : b6437000-b654e000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-30 02:46:00.976  6442  6442 W art     : b654e000-b6559000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-30 02:46:00.976  6442  6442 W art     : b6559000-b655a000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-30 02:46:00.976  6442  6442 W art     : b655a000-b655e000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b655e000-b6582000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-30 02:46:00.976  6442  6442 W art     : b6582000-b6584000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-30 02:46:00.976  6442  6442 W art     : b6584000-b6585000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-30 02:46:00.976  6442  6442 W art     : b6585000-b662b000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-30 02:46:00.976  6442  6442 W art     : b662b000-b6638000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-30 02:46:00.976  6442  6442 W art     : b6638000-b6639000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-30 02:46:00.976  6442  6442 W art     : b6639000-b663a000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b663a000-b668d000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-30 02:46:00.976  6442  6442 W art     : b668d000-b668e000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b668e000-b668f000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-30 02:46:00.976  6442  6442 W art     : b668f000-b6690000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-30 02:46:00.976  6442  6442 W art     : b6690000-b6695000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6695000-b66a7000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-30 02:46:00.976  6442  6442 W art     : b66a7000-b66a8000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b66a8000-b66a9000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-30 02:46:00.976  6442  6442 W art     : b66a9000-b66aa000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-30 02:46:00.976  6442  6442 W art     : b66aa000-b66b1000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 02:46:00.976  6442  6442 W art     : b66b1000-b66b2000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 02:46:00.976  6442  6442 W art     : b66b2000-b66b3000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 02:46:00.976  6442  6442 W art     : b66b3000-b66b4000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b66b4000-b66b7000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-30 02:46:00.976  6442  6442 W art     : b66b7000-b66b8000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-30 02:46:00.976  6442  6442 W art     : b66b8000-b66b9000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-30 02:46:00.976  6442  6442 W art     : b66b9000-b66bd000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-30 02:46:00.976  6442  6442 W art     : b66bd000-b66be000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-30 02:46:00.976  6442  6442 W art     : b66be000-b66bf000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-30 02:46:00.976  6442  6442 W art     : b66bf000-b66cd000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-30 02:46:00.976  6442  6442 W art     : b66cd000-b66ce000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b66ce000-b66cf000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-30 02:46:00.976  6442  6442 W art     : b66cf000-b66d0000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-30 02:46:00.976  6442  6442 W art     : b66d0000-b66d9000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 02:46:00.976  6442  6442 W art     : b66d9000-b66da000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 02:46:00.976  6442  6442 W art     : b66da000-b66db000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 02:46:00.976  6442  6442 W art     : b66db000-b6741000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-30 02:46:00.976  6442  6442 W art     : b6741000-b6742000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6742000-b6744000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-30 02:46:00.976  6442  6442 W art     : b6744000-b674d000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-30 02:46:00.976  6442  6442 W art     : b674d000-b6750000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6750000-b67e7000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-30 02:46:00.976  6442  6442 W art     : b67e7000-b67e9000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-30 02:46:00.976  6442  6442 W art     : b67e9000-b67ea000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-30 02:46:00.976  6442  6442 W art     : b67ea000-b67eb000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b67eb000-b6b09000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-30 02:46:00.976  6442  6442 W art     : b6b09000-b6b0a000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6b0a000-b6b25000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-30 02:46:00.976  6442  6442 W art     : b6b25000-b6b29000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-30 02:46:00.976  6442  6442 W art     : b6b29000-b6b2e000 rw-p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6b2e000-b6b36000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 02:46:00.976  6442  6442 W art     : b6b36000-b6b37000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 02:46:00.976  6442  6442 W art     : b6b37000-b6b38000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 02:46:00.976  6442  6442 W art     : b6b38000-b6b66000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-30 02:46:00.976  6442  6442 W art     : b6b66000-b6b67000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6b67000-b6b6e000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-30 02:46:00.976  6442  6442 W art     : b6b6e000-b6b6f000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-30 02:46:00.976  6442  6442 W art     : b6b6f000-b6bb5000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-30 02:46:00.976  6442  6442 W art     : b6bb5000-b6bb6000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6bb6000-b6bb9000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-30 02:46:00.976  6442  6442 W art     : b6bb9000-b6bba000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-30 02:46:00.976  6442  6442 W art     : b6bba000-b6bd5000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-30 02:46:00.976  6442  6442 W art     : b6bd5000-b6bd9000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-30 02:46:00.976  6442  6442 W art     : b6bd9000-b6bda000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-30 02:46:00.976  6442  6442 W art     : b6bda000-b6c27000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-30 02:46:00.976  6442  6442 W art     : b6c27000-b6c28000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6c28000-b6c34000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-30 02:46:00.976  6442  6442 W art     : b6c34000-b6c35000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-30 02:46:00.976  6442  6442 W art     : b6c35000-b6c42000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-30 02:46:00.976  6442  6442 W art     : b6c42000-b6c43000 ---p 00000000 00:00 0 
08-30 02:46:00.976  6442  6442 W art     : b6c43000-b6c44000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-30 02:46:00.976  6442  6442 W art     : b6c44000-b6c45000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-30 02:46:00.976  6442  6442 W art     : b6c45000-b6c4d000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-30 02:46:00.986  6442  6442 W art     : b6c4d000-b6c4e000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6c4e000-b6c4f000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-30 02:46:00.986  6442  6442 W art     : b6c4f000-b6c50000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-30 02:46:00.986  6442  6442 W art     : b6c50000-b6c57000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-30 02:46:00.986  6442  6442 W art     : b6c57000-b6c58000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-30 02:46:00.986  6442  6442 W art     : b6c58000-b6c59000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-30 02:46:00.986  6442  6442 W art     : b6c59000-b6c6d000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-30 02:46:00.986  6442  6442 W art     : b6c6d000-b6c6f000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-30 02:46:00.986  6442  6442 W art     : b6c6f000-b6c70000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-30 02:46:00.986  6442  6442 W art     : b6c70000-b6c98000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-30 02:46:00.986  6442  6442 W art     : b6c98000-b6c9a000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-30 02:46:00.986  6442  6442 W art     : b6c9a000-b6c9b000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-30 02:46:00.986  6442  6442 W art     : b6c9b000-b6c9e000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-30 02:46:00.986  6442  6442 W art     : b6c9e000-b6c9f000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-30 02:46:00.986  6442  6442 W art     : b6c9f000-b6ca0000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-30 02:46:00.986  6442  6442 W art     : b6ca0000-b6ca9000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-30 02:46:00.986  6442  6442 W art     : b6ca9000-b6caa000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-30 02:46:00.986  6442  6442 W art     : b6caa000-b6cab000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-30 02:46:00.986  6442  6442 W art     : b6cab000-b6ccb000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-30 02:46:00.986  6442  6442 W art     : b6ccb000-b6ccc000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-30 02:46:00.986  6442  6442 W art     : b6ccc000-b6ccd000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-30 02:46:00.986  6442  6442 W art     : b6ccd000-b6d40000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-30 02:46:00.986  6442  6442 W art     : b6d40000-b6d44000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-30 02:46:00.986  6442  6442 W art     : b6d44000-b6d47000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-30 02:46:00.986  6442  6442 W art     : b6d47000-b6d51000 rw-p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6d51000-b6dd9000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-30 02:46:00.986  6442  6442 W art     : b6dd9000-b6dda000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6dda000-b6dde000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-30 02:46:00.986  6442  6442 W art     : b6dde000-b6ddf000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-30 02:46:00.986  6442  6442 W art     : b6ddf000-b6de0000 rw-p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6de0000-b6e09000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-30 02:46:00.986  6442  6442 W art     : b6e09000-b6e0a000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6e0a000-b6e0d000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-30 02:46:00.986  6442  6442 W art     : b6e0d000-b6e0e000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-30 02:46:00.986  6442  6442 W art     : b6e0e000-b6ee8000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 02:46:00.986  6442  6442 W art     : b6ee8000-b6eef000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 02:46:00.986  6442  6442 W art     : b6eef000-b6ef7000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 02:46:00.986  6442  6442 W art     : b6ef7000-b6ef8000 rw-p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6ef8000-b6ef9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:00.986  6442  6442 W art     : b6ef9000-b6efa000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-30 02:46:00.986  6442  6442 W art     : b6efa000-b6efb000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.986  6442  6442 W art     : b6efb000-b6efe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.986  6442  6442 W art     : b6efe000-b6f23000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-30 02:46:00.986  6442  6442 W art     : b6f23000-b6f24000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6f24000-b6f2b000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-30 02:46:00.986  6442  6442 W art     : b6f2b000-b6f2c000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-30 02:46:00.986  6442  6442 W art     : b6f2c000-b6f33000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-30 02:46:00.986  6442  6442 W art     : b6f33000-b6f34000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-30 02:46:00.986  6442  6442 W art     : b6f34000-b6f35000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-30 02:46:00.986  6442  6442 W art     : b6f35000-b6f36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.986  6442  6442 W art     : b6f36000-b6f4e000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-30 02:46:00.986  6442  6442 W art     : b6f4e000-b6f4f000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6f4f000-b6f50000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-30 02:46:00.986  6442  6442 W art     : b6f50000-b6f51000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-30 02:46:00.986  6442  6442 W art     : b6f51000-b6f5f000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-30 02:46:00.986  6442  6442 W art     : b6f5f000-b6f60000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6f60000-b6f61000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-30 02:46:00.986  6442  6442 W art     : b6f61000-b6f62000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-30 02:46:00.986  6442  6442 W art     : b6f62000-b6f63000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:00.986  6442  6442 W art     : b6f63000-b6f65000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.986  6442  6442 W art     : b6f65000-b6f66000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.986  6442  6442 W art     : b6f66000-b6f67000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:00.986  6442  6442 W art     : b6f67000-b6f68000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-30 02:46:00.986  6442  6442 W art     : b6f68000-b6f69000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:00.986  6442  6442 W art     : b6f69000-b6f89000 r--s 00000000 00:0b 7201       /dev/__properties__
08-30 02:46:00.986  6442  6442 W art     : b6f89000-b6f8a000 r--p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6f8a000-b6f8b000 ---p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6f8b000-b6f8d000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-30 02:46:00.986  6442  6442 W art     : b6f8d000-b6f8e000 r-xp 00000000 00:00 0          [sigpage]
08-30 02:46:00.986  6442  6442 W art     : b6f8e000-b6fa9000 r-xp 00000000 b3:17 341        /system/bin/linker
08-30 02:46:00.986  6442  6442 W art     : b6fa9000-b6faa000 r--p 0001a000 b3:17 341        /system/bin/linker
08-30 02:46:00.986  6442  6442 W art     : b6faa000-b6fac000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-30 02:46:00.986  6442  6442 W art     : b6fac000-b6fae000 rw-p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : b6fae000-b6fb3000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-30 02:46:00.986  6442  6442 W art     : b6fb3000-b6fb4000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-30 02:46:00.986  6442  6442 W art     : b6fb4000-b6fb5000 rw-p 00000000 00:00 0 
08-30 02:46:00.986  6442  6442 W art     : bedd6000-bedf7000 rw-p 00000000 00:00 0          [stack]
08-30 02:46:00.986  6442  6442 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-30 02:46:01.026  6442  6442 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 02:46:01.066  6442  6442 I Radio-JNI: register_android_hardware_Radio DONE
08-30 02:46:01.076  6442  6442 E AffinityControl: AffinityControl: registerfunction enter
08-30 02:46:01.086  5473  5473 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-30 02:46:01.086  5473  5473 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-30 02:46:01.086  5473  5473 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-30 02:46:01.086  5473  5473 I art     : System.exit called, status: 0
08-30 02:46:01.086  5473  5473 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 02:46:01.096  6442  6442 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 02:46:01.106   781  1640 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-30 02:46:01.126   781  1640 D ActivityManager: mDVFSHelper.acquire()
08-30 02:46:01.126   781  1640 D FocusedStackFrame: Set to : 0
08-30 02:46:01.126   781  1640 V WindowManager: addAppToken: AppWindowToken{7b60472 token=Token{fbe0d7d ActivityRecord{e29b7d4 u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-30 02:46:01.126  5440  5440 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-30 02:46:01.126   781   923 D SecWifiDisplayUtil: Metadata value : none
08-30 02:46:01.126   781   923 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{dddafca V.E...... R.....ID 0,0-0,0}
08-30 02:46:01.136   781   923 D ISSUE_DEBUG: InputChannelName : 15cb458 Starting com.test.thalitest
08-30 02:46:01.146  6462  6462 E Zygote  : v2
08-30 02:46:01.146  6462  6462 I libpersona: KNOX_SDCARD checking this for 10004
08-30 02:46:01.146  6462  6462 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:01.146   781  1640 I ActivityManager: Start proc 6462:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-30 02:46:01.146  6462  6462 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:01.146  6462  6462 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:01.146   292   292 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-30 02:46:01.156  6462  6462 E Zygote  : accessInfo : 0
08-30 02:46:01.156  6462  6462 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 02:46:01.166   781   923 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-30 02:46:01.166   781  1640 D InputDispatcher: Focused application set to: xxxx
08-30 02:46:01.166   781  1640 D InputDispatcher: Focus left window: 1728
08-30 02:46:01.176  6442  6442 D AndroidRuntime: Shutting down VM
08-30 02:46:01.176   781  1798 I ActivityManager: Process com.samsung.aasaservice (pid 5473)(adj 0) has died(129,721)
08-30 02:46:01.176   781  1798 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-30 02:46:01.176   781  1798 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-30 02:46:01.176   781  1798 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-30 02:46:01.196  6474  6474 E Zygote  : v2
08-30 02:46:01.196   781   860 I ActivityManager: Start proc 6474:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-30 02:46:01.196   781  1320 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 02:46:01.196  6474  6474 I libpersona: KNOX_SDCARD checking this for 10014
08-30 02:46:01.196  6474  6474 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:01.196  6474  6474 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:01.196  6474  6474 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:01.196  6474  6474 E Zygote  : accessInfo : 0
08-30 02:46:01.196  6474  6474 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-30 02:46:01.206  6462  6462 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:01.206  6462  6462 D ActivityThread: Added TimaKeyStore provider
08-30 02:46:01.206   781   923 V WindowStateAnimator: Finishing drawing window Window{15cb458 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 02:46:01.206   781  1317 V WindowOrientationListener: setCurrentAppOrientation :-1
08-30 02:46:01.206   781  1317 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-30 02:46:01.206   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-30 02:46:01.206   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 02:46:01.206   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-30 02:46:01.206   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-30 02:46:01.216   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeb7364
08-30 02:46:01.216   781   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{15cb458 u0 d0 Starting com.test.thalitest}
08-30 02:46:01.236  1374  1374 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-30 02:46:01.236  1728  1902 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-30 02:46:01.236  1728  1728 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-30 02:46:01.236   781  1317 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 02:46:01.236  6474  6474 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:01.236  6474  6474 D ActivityThread: Added TimaKeyStore provider
08-30 02:46:01.256   292   369 D libEGL  : eglTerminate EGLDisplay = 0xb663f64c
08-30 02:46:01.256   292   369 D libEGL  : eglTerminate EGLDisplay = 0xb663f64c
08-30 02:46:01.266   292   951 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-30 02:46:01.266   292   369 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-30 02:46:01.286   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeb73a4
08-30 02:46:01.286  2325  3131 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-30 02:46:01.286  1728  1728 V ActivityThread: updateVisibility : ActivityRecord{7e3c4c6 token=android.os.BinderProxy@8c9cb38 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 02:46:01.286  1728  1728 D Launcher: onTrimMemory. Level: 20
08-30 02:46:01.296   781   860 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-30 02:46:01.306  6462  6462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 02:46:01.306   781  1801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f84a17 6474:com.google.android.partnersetup/u0a14}
08-30 02:46:01.306   781  1320 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-30 02:46:01.316  6474  6474 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-30 02:46:01.316   781  3557 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 02:46:01.326  6474  6474 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-30 02:46:01.336  6462  6462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 02:46:01.336  6462  6462 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 02:46:01.356   781  1734 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f84a17 6474:com.google.android.partnersetup/u0a14}
08-30 02:46:01.356  6462  6462 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
08-30 02:46:01.376  6462  6462 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 02:46:01.376  6490  6490 E Zygote  : v2
08-30 02:46:01.376  6490  6490 I libpersona: KNOX_SDCARD checking this for 10015
08-30 02:46:01.376  6490  6490 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:01.376  6490  6490 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:01.386  6490  6490 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:01.386  6490  6490 E Zygote  : accessInfo : 0
08-30 02:46:01.386  6490  6490 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-30 02:46:01.386   781  1798 I ActivityManager: Start proc 6490:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
,08-30 02:46:01.396   781   799 I ActivityManager: Killing 5594:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
,08-30 02:46:01.396  6462  6462 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 02:46:01.406  6462  6462 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 2971-2974)
08-30 02:46:01.406  6462  6462 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-30 02:46:01.426  6462  6502 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-30 02:46:01.426   781  1698 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,08-30 02:46:01.436   781   793 I art     : Background partial concurrent mark sweep GC freed 45139(2MB) AllocSpace objects, 11(360KB) LOS objects, 27% free, 42MB/58MB, paused 2.231ms total 164.206ms
,08-30 02:46:01.436  6462  6462 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9591261}
08-30 02:46:01.436  6462  6462 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-30 02:46:01.436  6462  6462 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 02:46:01.446  6490  6490 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:01.446  6490  6490 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:01.446  6462  6462 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 02:46:01.456   781  1640 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{22d70b3 6490:com.samsung.groupcast/u0a15}
,08-30 02:46:01.456  6490  6490 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
,08-30 02:46:01.476  6462  6462 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 02:46:01.476  6462  6462 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 02:46:01.476  6462  6462 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 02:46:01.476  6462  6462 I Adreno-EGL: Local Branch: ss
08-30 02:46:01.476  6462  6462 I Adreno-EGL: Remote Branch: 
08-30 02:46:01.476  6462  6462 I Adreno-EGL: Local Patches: 
08-30 02:46:01.476  6462  6462 I Adreno-EGL: Reconstruct Branch: 
,08-30 02:46:01.476  6490  6490 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
,08-30 02:46:01.486  6462  6462 D libEGL  : eglInitialize EGLDisplay = 0xbeba5dac
,08-30 02:46:01.496  6490  6490 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
,08-30 02:46:01.496  6490  6490 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,08-30 02:46:01.496  6490  6490 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 02:46:01.496  6490  6490 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-30 02:46:01.496  6490  6490 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-30 02:46:01.496  6490  6490 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-30 02:46:01.496  6490  6490 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-30 02:46:01.496  6490  6490 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
,08-30 02:46:01.496  6490  6490 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 02:46:01.496  6490  6490 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:01.496  6490  6490 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:46:01.496  6490  6490 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 02:46:01.496  6490  6490 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:01.496  6490  6490 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 02:46:01.496  6490  6490 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-30 02:46:01.506   781  1804 I ActivityManager: Killing 5275:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-30 02:46:01.506   781  1804 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7782e43 1908:com.sec.android.app.shealth:remote/u0a34}
,08-30 02:46:01.526   781  1621 I ActivityManager: Start proc 6516:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,08-30 02:46:01.526  6516  6516 E Zygote  : v2
08-30 02:46:01.526  6516  6516 I libpersona: KNOX_SDCARD checking this for 10041
08-30 02:46:01.526  6516  6516 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:01.526  6516  6516 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:01.526  6516  6516 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:01.526  6516  6516 E Zygote  : accessInfo : 0
,08-30 02:46:01.526  6516  6516 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-30 02:46:01.526   781  1422 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
08-30 02:46:01.526   781  1422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-30 02:46:01.546   781   799 D CountryDetector: No listener is left
,08-30 02:46:01.546   781  1175 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-30 02:46:01.566  6516  6516 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:01.566  6516  6516 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:01.576   781  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4dfac15 6516:com.samsung.android.sdk.samsunglink/u0a41}
,08-30 02:46:01.586  6462  6462 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-30 02:46:01.586  6516  6516 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
,08-30 02:46:01.596  6462  6462 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 02:46:01.596  6462  6462 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-30 02:46:01.596  6462  6462 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-30 02:46:01.596  6462  6462 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-30 02:46:01.616  6462  6462 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-30 02:46:01.616  6462  6462 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 02:46:01.696  6516  6516 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 02:46:01.696  6516  6516 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 02:46:01.726  6462  6462 D SecWifiDisplayUtil: Metadata value : none
,08-30 02:46:01.726  6462  6462 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4734ae6 I.E...... R.....ID 0,0-0,0}
,08-30 02:46:01.736  6462  6541 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 02:46:01.736   781  1422 D ISSUE_DEBUG: InputChannelName : 32f8e64 com.test.thalitest/com.test.thalitest.MainActivity
,08-30 02:46:01.736   781   799 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-30 02:46:01.746   781   799 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:46:01.746   781   781 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 02:46:01.746   781   781 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 02:46:01.756  6516  6516 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-30 02:46:01.766  6462  6462 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6462
,08-30 02:46:01.766  6516  6516 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-30 02:46:01.766   781  1422 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6462 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:46:01.766   781  1329 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-30 02:46:01.766   781  1329 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 02:46:01.766   781  1329 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 02:46:01.766   781  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-30 02:46:01.766   781  1329 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:46:01.776  6462  6462 D SecWifiDisplayUtil: Metadata value : none
,08-30 02:46:01.786  6462  6502 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-30 02:46:01.786   781  1804 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.786   781  1745 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-30 02:46:01.786   292   292 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-30 02:46:01.796   781  1805 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.796   781  1640 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.796   781  1317 D InputDispatcher: Focus entered window: 6462
,08-30 02:46:01.796   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-30 02:46:01.796   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 02:46:01.796   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-30 02:46:01.796   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 02:46:01.796  6462  6541 D libEGL  : eglInitialize EGLDisplay = 0x9ca7a7c4
08-30 02:46:01.796  6462  6541 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 02:46:01.806   781  1422 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.806   781  1734 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.806   781  1798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.806   781   801 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.816   781  1621 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.816   781  1698 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-30 02:46:01.856  6462  6462 V ActivityThread: updateVisibility : ActivityRecord{9d46b79 token=android.os.BinderProxy@7eb5541 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 02:46:01.856  6462  6462 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-30 02:46:01.856  6462  6462 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-30 02:46:01.856   781  1422 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 02:46:01.866  6462  6462 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 02:46:01.886   781  1804 V WindowStateAnimator: Finishing drawing window Window{32f8e64 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-30 02:46:01.886  6462  6462 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-30 02:46:01.886  6462  6462 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7eb5541 time:103459
,08-30 02:46:01.896   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeb7364
,08-30 02:46:01.896   781   923 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 02:46:01.896   781   923 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms (total +764ms)
,08-30 02:46:01.896   781   923 D ActivityManager: mDVFSHelper.release()
08-30 02:46:01.896   781   923 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e29b7d4 u0 com.test.thalitest/.MainActivity t167} time:103469
08-30 02:46:01.906   781   781 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-30 02:46:01.906   781   923 D ViewRootImpl: #3 mView = null
08-30 02:46:01.906   781   781 I KnoxTimeoutHandler: SD activityfalse
08-30 02:46:01.906   292  2007 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-30 02:46:01.906   292   355 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-30 02:46:01.916   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeb73a4
,08-30 02:46:01.926  6462  6555 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 02:46:01.926  6462  6555 D libEGL  : eglInitialize EGLDisplay = 0x9aeff3ec
,08-30 02:46:01.966  6516  6516 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-30 02:46:01.966  6516  6516 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-30 02:46:01.966  6516  6516 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-30 02:46:01.966  6516  6516 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-30 02:46:01.966  6516  6516 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-30 02:46:01.966  6516  6516 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-30 02:46:01.966  6516  6516 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-30 02:46:01.966  6516  6516 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-30 02:46:01.966  6516  6516 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
,08-30 02:46:01.966  6462  6462 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6462
,08-30 02:46:01.966  6516  6516 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 02:46:01.966  6516  6516 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:01.966  6516  6516 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:46:01.966  6516  6516 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
,08-30 02:46:01.966  6516  6516 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:01.966  6516  6516 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 02:46:01.966  6516  6516 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-30 02:46:01.976   781  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca9aa98 1662:android.process.acore/u0a19}
,08-30 02:46:01.986   781   801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7c551b9 5155:com.sec.android.gallery3d/u0a47}
,08-30 02:46:01.986  5155  5155 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-30 02:46:01.996   781  1805 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 02:46:02.006   781  1317 I ActivityManager: Start proc 6564:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-30 02:46:02.006  6564  6564 E Zygote  : v2
08-30 02:46:02.006  6564  6564 I libpersona: KNOX_SDCARD checking this for 10050
08-30 02:46:02.006  6564  6564 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:02.006  6564  6564 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:02.006  6564  6564 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:02.006  6564  6564 E Zygote  : accessInfo : 0
08-30 02:46:02.006  6564  6564 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-30 02:46:02.036  6564  6564 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:02.036  6564  6564 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:02.046   781  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e419df 6564:com.sec.android.app.myfiles/u0a50}
,08-30 02:46:02.056  6564  6564 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-30 02:46:02.076  6564  6564 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-30 02:46:02.116  6564  6564 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-30 02:46:02.126   781   801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c591d1 2750:com.android.settings/1000}
,08-30 02:46:02.126   328   328 E installd: system dir 0 : /system/app/
08-30 02:46:02.126   328   328 E installd: system dir 1 : /system/priv-app/
08-30 02:46:02.126   328   328 E installd: system dir 2 : /vendor/app/
08-30 02:46:02.126   328   328 E installd: system dir 3 : /oem/app/
,08-30 02:46:02.126  6462  6462 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 02:46:02.136   781   799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8c591d1 2750:com.android.settings/1000}
,08-30 02:46:02.146   781  1001 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-30 02:46:02.156  6580  6580 E Zygote  : v2
,08-30 02:46:02.156  6580  6580 I libpersona: KNOX_SDCARD checking this for 10169
08-30 02:46:02.156  6580  6580 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:02.156   781  1745 I ActivityManager: Start proc 6580:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-30 02:46:02.156  6580  6580 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:02.156  6580  6580 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:02.156  6580  6580 E Zygote  : accessInfo : 0
,08-30 02:46:02.156  6580  6580 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-30 02:46:02.186   781   860 I ActivityManager: Start proc 6591:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-30 02:46:02.186  6591  6591 E Zygote  : v2
,08-30 02:46:02.186  6591  6591 I libpersona: KNOX_SDCARD checking this for 10210
08-30 02:46:02.186  6591  6591 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:02.186  6591  6591 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-30 02:46:02.186  6591  6591 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:02.186  6591  6591 E Zygote  : accessInfo : 0
,08-30 02:46:02.186  6591  6591 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-30 02:46:02.196  6580  6580 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:02.196  6580  6580 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:02.206   781  1422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29a74fb 6580:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-30 02:46:02.226  6580  6580 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-30 02:46:02.226  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:02.226  6591  6591 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:02.236  6580  6580 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-30 02:46:02.246  6591  6591 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-30 02:46:02.246  6591  6591 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-30 02:46:02.256  6591  6591 D AASAservice: onCreate()
,08-30 02:46:02.256   781  1805 I ActivityManager: Killing 5609:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,08-30 02:46:02.256  5440  5440 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-30 02:46:02.266   781  1640 I ActivityManager: Killing 5172:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-30 02:46:02.266   781  1640 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebbaa46 1712:com.android.phone/1001}
,08-30 02:46:02.276   781  1640 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ea22c9 1839:com.google.android.googlequicksearchbox:search/u0a61}
,08-30 02:46:02.276   781  1734 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-30 02:46:02.286  6462  6604 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1702635216
,08-30 02:46:02.286  6462  6604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:46:02.286  6462  6604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:46:02.286  6462  6604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:46:02.286  6462  6604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:46:02.286  6462  6604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 02:46:02.286  6462  6604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3a6917 added. We now have 1 listener(s)
,08-30 02:46:02.296  6462  6604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-30 02:46:02.296  6462  6604 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
08-30 02:46:02.296   781  1798 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,08-30 02:46:02.296  6462  6604 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 02:46:02.296  6462  6604 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 02:46:02.296  6462  6604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb85922 added. We now have 1 listener(s)
08-30 02:46:02.296  6462  6604 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 02:46:02.296  6462  6604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 02:46:02.296  6462  6604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 02:46:02.296   781   799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ea22c9 1839:com.google.android.googlequicksearchbox:search/u0a61}
,08-30 02:46:02.306  6462  6604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 02:46:02.306  6462  6604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:46:02.306  6462  6604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 02:46:02.306  6462  6604 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 02:46:02.306  6462  6604 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-30 02:46:02.306   781  3558 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-30 02:46:02.316   781  1734 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{83a0ec4 6383:com.samsung.android.sm.provider/1000}
,08-30 02:46:02.316  6462  6604 D BluetoothAdapter: STATE_ON
,08-30 02:46:02.316  6462  6604 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:02.316  6462  6604 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 02:46:02.316  6462  6604 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 02:46:02.316  6462  6604 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 02:46:02.316  6462  6604 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 02:46:02.326  6462  6462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:46:02.336   781  1317 I ActivityManager: Start proc 6608:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-30 02:46:02.336  6608  6608 E Zygote  : v2
08-30 02:46:02.336  6608  6608 I libpersona: KNOX_SDCARD checking this for 5012
08-30 02:46:02.336  6608  6608 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:02.336  6462  6462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 02:46:02.336  6608  6608 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:02.336  6608  6608 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:02.336  6608  6608 E Zygote  : accessInfo : 0
,08-30 02:46:02.336  6608  6608 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-30 02:46:02.356  6462  6462 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 02:46:02.366  6608  6608 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:02.366  6608  6608 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:02.376   781  1734 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b5330 6608:com.samsung.android.sm.devicesecurity/5012}
,08-30 02:46:02.386  6608  6608 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-30 02:46:02.396  6608  6608 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-30 02:46:02.416  1839  6605 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 02:46:02.446   781  1734 I ActivityManager: Killing 5189:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-30 02:46:02.446   781  1734 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bae65d8 3305:com.android.contacts/u0a19}
,08-30 02:46:02.466   781   799 I ActivityManager: Start proc 6621:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-30 02:46:02.466  6621  6621 E Zygote  : v2
08-30 02:46:02.466  6621  6621 I libpersona: KNOX_SDCARD checking this for 10049
08-30 02:46:02.466  6621  6621 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:02.466  6621  6621 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:02.466  6621  6621 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:02.466  6621  6621 E Zygote  : accessInfo : 0
,08-30 02:46:02.466  6621  6621 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-30 02:46:02.496   781  1640 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-30 02:46:02.496  6621  6621 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:02.496  6621  6621 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:02.506   781  1805 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ceb3ba9 6621:com.android.mms/u0a49}
,08-30 02:46:02.516  1839  6605 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-30 02:46:02.516  6621  6621 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-30 02:46:02.526  1839  6605 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-30 02:46:02.536  6621  6621 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-30 02:46:02.536  6621  6621 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-30 02:46:02.546  6621  6621 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-30 02:46:02.546  6621  6633 D Mms/ArtClassLoader: init before art first
,08-30 02:46:02.556  6621  6621 D Mms/TelephonyPermission: start operation mode monitor
,08-30 02:46:02.556  6621  6621 D Mms/TelephonyPermission: User ID is null set current User Id
,08-30 02:46:02.566  6621  6634 D Mms/ArtClassLoader: init before art second
,08-30 02:46:02.576   781  1800 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,08-30 02:46:02.586  6621  6621 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-30 02:46:02.586  6621  6621 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-30 02:46:02.596  6621  6635 D Mms/ArtClassLoader: init before art third
,08-30 02:46:02.616  6621  6635 D Mms/ArtClassLoader: init [DONE] art
,08-30 02:46:02.636  4531  6636 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-30 02:46:02.646  6621  6621 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-30 02:46:02.646  6621  6621 D Mms/TelephonyPermission: isDefault true
,08-30 02:46:02.646  6621  6621 D Mms/MmsApp: onCreate() com.android.mms
,08-30 02:46:02.716  1839  6605 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 299 ms] updated apps [took 299 ms] 
,08-30 02:46:02.736  6621  6621 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-30 02:46:02.746  6621  6621 D Mms/MmsApp: [start]    initCountryIso consume time = 198.154479
,08-30 02:46:02.746   781  1798 D CountryDetector: The first listener is added
,08-30 02:46:02.746  1451  1451 D Recents : onTaskStackChanged
,08-30 02:46:02.756  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-30 02:46:02.766  6621  6633 D Mms/ArtClassLoader: init [DONE] art
,08-30 02:46:02.776  6621  6621 D Mms/MmsApp: [end]    initCountryIso consume time = 28.713802
,08-30 02:46:02.776  6621  6621 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.252917
,08-30 02:46:02.776  6621  6621 D Mms/MmsConfig: before partial update
,08-30 02:46:02.786  6621  6634 D Mms/ArtClassLoader: init [DONE] art
,08-30 02:46:02.806  6621  6621 D Mms/MmsConfig: Load Resize quality : 80
,08-30 02:46:02.806  6621  6621 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-30 02:46:02.806  6621  6621 D EasySignUpManager_1.0.5: isAuth is false
08-30 02:46:02.806  6621  6621 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-30 02:46:02.806  6621  6621 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-30 02:46:02.806  6621  6621 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-30 02:46:02.806  6621  6621 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-30 02:46:02.806  6621  6621 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-30 02:46:02.816  6621  6621 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-30 02:46:02.816  6621  6621 D EasySignUpManager_1.0.5: isAuth is false
08-30 02:46:02.816  6621  6621 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
,08-30 02:46:02.816  6621  6621 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-30 02:46:02.816  1712  1727 D TP/MmsSmsProvider: query, match:2117, calling pid = 6621, accessRestricted = false
,08-30 02:46:02.826  1712  1727 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.199 ms
,08-30 02:46:02.826  6621  6621 E CscParser: mps_code.dat does not exist
08-30 02:46:02.826  6621  6621 E CscParser: customer_path =/system/csc/customer.xml
08-30 02:46:02.826  6621  6621 E CscParser: fileName + /system/csc/customer.xml
,08-30 02:46:02.836  6621  6621 E CscParser: mps_code.dat does not exist
08-30 02:46:02.836  6621  6621 E CscParser: customer_path =/system/csc/customer.xml
08-30 02:46:02.836  6621  6621 E CscParser: fileName + /system/csc/customer.xml
,08-30 02:46:02.846  6621  6621 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-30 02:46:02.846  6621  6621 D Mms/MmsConfig:  enable multiwindow = true
,08-30 02:46:02.846  6621  6621 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-30 02:46:02.846  6621  6621 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-30 02:46:02.846  6621  6621 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
,08-30 02:46:02.846  6621  6621 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-30 02:46:02.846  6621  6621 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-30 02:46:02.846  6621  6621 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-30 02:46:02.846  6621  6621 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-30 02:46:02.856  6621  6621 D Mms/MmsConfig: [end]    init() consume time = 80.428645
,08-30 02:46:02.856  6621  6621 D Mms/Contact: [start]    init() consume time = 3.610729
,08-30 02:46:02.866  1712  1935 D TP/MmsSmsProvider: query, match:13, calling pid = 6621, accessRestricted = false
,08-30 02:46:02.866  1712  1935 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.185 ms
,08-30 02:46:02.866  6621  6621 D Mms/Contact: [end]    init consume time = 12.051146
,08-30 02:46:02.876  6621  6642 D Mms/DraftCache: [start]    rebuildCache consume time = 3.435938
,08-30 02:46:02.876  6621  6621 D Mms:transaction: roaming -> false (slotId = 0)
,08-30 02:46:02.876  6621  6621 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 02:46:02.876  6621  6621 D Mms:transaction: auto download without roaming -> true
08-30 02:46:02.876  6621  6621 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-30 02:46:02.876  6621  6621 D Mms:transaction: roaming -> false (slotId = 1)
08-30 02:46:02.876  6621  6621 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-30 02:46:02.876  6621  6621 D Mms:transaction: auto download without roaming -> true
,08-30 02:46:02.876  6621  6621 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-30 02:46:02.876  6621  6621 D Mms:transaction: auto download during roaming secondary -> false
08-30 02:46:02.876  6621  6621 D Mms:transaction: mAutoDownload ------> true
,08-30 02:46:02.886  1712  1724 D TP/MmsSmsProvider: query, match:12, calling pid = 6621, accessRestricted = false
,08-30 02:46:02.886  1712  1724 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.320 ms
,08-30 02:46:02.886  6621  6642 D Mms/DraftCache: [end]    rebuildCache consume time = 16.34875
,08-30 02:46:02.896  6621  6621 D ComposerPerformance: 1472517962912 ms / [DONE] Composer constructor
,08-30 02:46:02.896  6621  6644 D Mms/Conversation: [start]    init() consume time = 9.859896
,08-30 02:46:02.896  6621  6621 D CII     : Log Level [5]
08-30 02:46:02.896  1712  1935 D TP/MmsSmsProvider: delete, match:1, calling pid = 6621
08-30 02:46:02.896  6621  6621 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-30 02:46:02.896  1712  1935 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-30 02:46:02.896  1712  1935 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-30 02:46:02.896  6621  6621 I Mms/ReservationManager: ReservationManager()
08-30 02:46:02.896  6621  6621 I Mms/ReservationManager: resetAfterConnected()
,08-30 02:46:02.906  1712  1935 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-30 02:46:02.906  1712  1935 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-30 02:46:02.906  1712  1935 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-30 02:46:02.906  1712  1935 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
08-30 02:46:02.906  1712  1936 D TP/MmsSmsProvider: query, match:7, calling pid = 6621, accessRestricted = false
,08-30 02:46:02.916  1712  1936 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.197 ms
,08-30 02:46:02.916  6621  6621 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-30 02:46:02.916  1712  1935 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,08-30 02:46:02.916  1712  1935 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-30 02:46:02.916  1712  1935 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,08-30 02:46:02.916  1712  1935 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 9.874 ms
08-30 02:46:02.916  1712  1935 D TP/MmsSmsProvider: need read changed broadcast:false
,08-30 02:46:02.916  6621  6644 D Mms/Conversation: [end]    init consume time = 21.554791
08-30 02:46:02.916  6621  6621 D Mms/MmsApp: [end]    onCreate() consume time = 0.020886
08-30 02:46:02.916  6621  6621 D Mms/MmsApp: [end]    onCreate() consume time = 0.055
,08-30 02:46:02.926  6621  6644 D Mms/MessagingNotification: [start]    init() consume time = 2.473229
,08-30 02:46:02.926  6621  6644 D Mms/MessagingNotification: [end]    init consume time = 1.836354
,08-30 02:46:02.926  6621  6645 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.231927
,08-30 02:46:02.926  6621  6621 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-30 02:46:02.936  6621  6621 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-30 02:46:02.936  6621  6621 D Mms:transaction: roaming -> false (slotId = 0)
08-30 02:46:02.936  6621  6621 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 02:46:02.936  6621  6621 D Mms:transaction: auto download without roaming -> true
,08-30 02:46:02.936  6621  6621 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-30 02:46:02.936  6621  6621 D Mms:transaction: mAutoDownload ------> true
,08-30 02:46:02.946  6647  6647 E Zygote  : v2
,08-30 02:46:02.946  6647  6647 I libpersona: KNOX_SDCARD checking this for 1000
08-30 02:46:02.946  6647  6647 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:02.946  6647  6647 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:02.946  6647  6647 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:02.946  1712  1724 D TP/MmsSmsProvider: query, match:400, calling pid = 6621, accessRestricted = false
08-30 02:46:02.946  6647  6647 E Zygote  : accessInfo : 0
,08-30 02:46:02.946  6621  6646 D Mms/Synchronizer: [start]    doSync consume time = 19.769896
,08-30 02:46:02.946   781   799 I ActivityManager: Start proc 6647:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-30 02:46:02.946  1712  1727 D TP/MmsSmsProvider: query, match:0, calling pid = 6621, accessRestricted = false
,08-30 02:46:02.946  1712  1727 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-30 02:46:02.946  1712  1727 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.134 ms
08-30 02:46:02.946  1712  1935 D TP/MmsSmsProvider: update, match:300, calling pid = 6621
08-30 02:46:02.946  1712  1935 V TP/MmsSmsProvider: syncDBData start
,08-30 02:46:02.946  1712  1935 V TP/MmsSmsProvider: syncDBData sms end
,08-30 02:46:02.956  1712  1935 V TP/MmsSmsProvider: syncDBData mms end
,08-30 02:46:02.956  1712  1935 V TP/MmsSmsProvider: syncDBData end
08-30 02:46:02.956  1712  1935 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.719 ms
,08-30 02:46:02.956  6621  6646 D Mms/Synchronizer: [end]    doSync consume time = 11.709896
,08-30 02:46:02.966  6120  6151 D BadgeProvider: query, [selection] : package=?
,08-30 02:46:02.966  6621  6644 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-30 02:46:02.976  6621  6645 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 22.737604
,08-30 02:46:02.976  6647  6647 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:02.976  6647  6647 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:02.986  1712  1727 D TP/SmsProvider: query,matched:26, calling pid = 6621
,08-30 02:46:02.986  1712  1727 D TP/SmsProvider: query, match 26:Elapsed time : 1.079 ms
,08-30 02:46:02.986   781  1698 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d069bb7 6647:com.samsung.android.bbc.bbcagent/1000}
,08-30 02:46:02.996  6647  6647 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-30 02:46:03.006  1712  1724 D TP/MmsSmsProvider: query, match:6, calling pid = 6621, accessRestricted = false
,08-30 02:46:03.006  1712  1724 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.379 ms
,08-30 02:46:03.016  6647  6647 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-30 02:46:03.026  6659  6659 E Zygote  : v2
08-30 02:46:03.026  6659  6659 I libpersona: KNOX_SDCARD checking this for 10024
08-30 02:46:03.026  6659  6659 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:03.026  6659  6659 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:03.026  6659  6659 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:03.026  6659  6659 E Zygote  : accessInfo : 0
08-30 02:46:03.026  6659  6659 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
08-30 02:46:03.036   781  1422 I ActivityManager: Start proc 6659:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-30 02:46:03.056  6671  6671 E Zygote  : v2
08-30 02:46:03.056  6671  6671 I libpersona: KNOX_SDCARD checking this for 10097
08-30 02:46:03.056  6671  6671 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:03.056  6671  6671 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:03.056  6671  6671 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:03.056  6671  6671 E Zygote  : accessInfo : 0
08-30 02:46:03.056  6671  6671 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-30 02:46:03.056   781  1805 I ActivityManager: Start proc 6671:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-30 02:46:03.066   781  1805 I ActivityManager: Killing 5219:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-30 02:46:03.076  6659  6659 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:03.076  6659  6659 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:03.086   781  1801 I ActivityManager: Killing 4736:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-30 02:46:03.086  6671  6671 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:03.086  6671  6671 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:03.096   781   799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5cc3f24 6671:com.google.android.apps.docs/u0a97}
,08-30 02:46:03.106  6659  6659 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-30 02:46:03.106   781  1734 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-30 02:46:03.116  6671  6671 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 02:46:03.116  6659  6659 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-30 02:46:03.126   781  1175 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-30 02:46:03.166  6671  6671 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-30 02:46:03.196  6659  6659 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-30 02:46:03.206  6621  6644 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-30 02:46:03.226  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-30 02:46:03.226  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-30 02:46:03.226  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-30 02:46:03.236  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-30 02:46:03.236  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-30 02:46:03.236  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-30 02:46:03.236  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-30 02:46:03.246  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-30 02:46:03.246  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-30 02:46:03.246  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-30 02:46:03.246  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-30 02:46:03.256  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-30 02:46:03.256  6659  6659 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-30 02:46:03.376  6462  6607 W jxcore-log: Initializing JXcore engine
,08-30 02:46:03.376  6462  6607 W jxcore-log: JXcore engine is ready
,08-30 02:46:03.426  2548  2548 E audit   : type=1400 msg=audit(1472517963.426:288): avc:  denied  { ioctl } for  pid=6607 comm="Thread-887" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 02:46:03.426  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:03.426  2548  2548 E audit   : type=1300 msg=audit(1472517963.426:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98b6a3c8 items=0 ppid=347 ppcomm=main pid=6607 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-887" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 02:46:03.426  2548  2548 E audit   : type=1327 msg=audit(1472517963.426:288): proctitle="com.test.thalitest"
08-30 02:46:03.426  2548  2548 E audit   : type=1320 msg=audit(1472517963.426:288): 
,08-30 02:46:03.426  2548  2548 E audit   : type=1400 msg=audit(1472517963.426:289): avc:  denied  { ioctl } for  pid=6607 comm="Thread-887" path="socket:[42041]" dev="sockfs" ino=42041 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 02:46:03.426  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:03.426  2548  2548 E audit   : type=1300 msg=audit(1472517963.426:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=98b6a3c8 items=0 ppid=347 ppcomm=main pid=6607 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-887" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 02:46:03.426  2548  2548 E audit   : type=1327 msg=audit(1472517963.426:289): proctitle="com.test.thalitest"
08-30 02:46:03.426  2548  2548 E audit   : type=1320 msg=audit(1472517963.426:289): 
,08-30 02:46:03.436  6462  6607 W jxcore-log: Starting JXcore engine
,08-30 02:46:03.516  6462  6607 W jxcore-log: Platform android
08-30 02:46:03.516  6462  6607 W jxcore-log: 
,08-30 02:46:03.516  6462  6607 W jxcore-log: Process ARCH arm
08-30 02:46:03.516  6462  6607 W jxcore-log: 
,08-30 02:46:03.526  6671  6685 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-30 02:46:03.526  6671  6685 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 02:46:03.526  6671  6685 I GAv4    :   adb logcat -s GAv4
,08-30 02:46:03.546  6671  6685 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 02:46:03.546   781  1798 V AlarmManager:  remove PendingIntent] PendingIntent{f202990: PendingIntentRecord{2bbc289 com.google.android.apps.docs broadcastIntent}}
,08-30 02:46:03.546  6671  6685 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 02:46:03.556  6671  6685 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 02:46:03.566  6671  6691 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 02:46:03.656  6671  6671 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-30 02:46:03.656  6671  6671 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-30 02:46:03.696  6671  6685 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-30 02:46:03.696  6671  6685 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-30 02:46:03.696  6671  6685 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-30 02:46:03.696  6671  6685 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-30 02:46:03.726  6462  6607 I jxcore-log: JXcore Cordova bridge is ready!
08-30 02:46:03.726  6462  6607 I jxcore-log: 
08-30 02:46:03.726  6697  6697 E Zygote  : v2
08-30 02:46:03.726  6697  6697 I libpersona: KNOX_SDCARD checking this for 10098
08-30 02:46:03.726  6462  6607 W jxcore-log: JXcore engine is started
08-30 02:46:03.726  6697  6697 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:03.726  6697  6697 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:03.726  6697  6697 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:03.726  6697  6697 E Zygote  : accessInfo : 0
08-30 02:46:03.736  6697  6697 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-30 02:46:03.736   781  1800 I ActivityManager: Start proc 6697:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-30 02:46:03.736  6462  6604 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 02:46:03.736   781  1800 I ActivityManager: Killing 5095:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-30 02:46:03.736  6462  6462 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 02:46:03.746  4531  5085 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-30 02:46:03.776   781  1805 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-30 02:46:03.786  6697  6697 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:03.786  6697  6697 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:03.796   781  1801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{794fe45 6697:com.sec.android.automotive.drivelink/u0a98}
,08-30 02:46:03.806  6697  6697 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-30 02:46:03.816  4531  5085 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-30 02:46:03.816  6697  6697 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-30 02:46:03.866  2112  2112 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 02:46:03.866  2112  2112 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 02:46:03.886  6697  6697 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-30 02:46:03.906   781   799 V AlarmManager:  remove PendingIntent] PendingIntent{d0c39c1: PendingIntentRecord{4139566 com.sec.android.automotive.drivelink broadcastIntent}}
,08-30 02:46:03.916  6697  6697 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-30 02:46:03.936   781  6353 I HarmonyEASService: Updating for all 1
,08-30 02:46:03.936  6697  6713 I GMPM    : App measurement is starting up
,08-30 02:46:03.946  6697  6713 E GMPM    : getGoogleAppId failed with status: 10
,08-30 02:46:03.946  6697  6697 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-30 02:46:03.946  6697  6697 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-30 02:46:03.946  6697  6713 E GMPM    : Uploading is not possible. App measurement disabled
,08-30 02:46:03.946  2112  2112 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 02:46:03.956   781  1640 V AlarmManager:  remove PendingIntent] PendingIntent{f7fe043: PendingIntentRecord{4139566 com.sec.android.automotive.drivelink broadcastIntent}}
,08-30 02:46:03.986  4531  5085 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-30 02:46:04.006  6719  6719 E Zygote  : v2
,08-30 02:46:04.006  6719  6719 I libpersona: KNOX_SDCARD checking this for 10032
08-30 02:46:04.006  6719  6719 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:04.006  6719  6719 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:04.006  6719  6719 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:04.006   781  1801 I ActivityManager: Start proc 6719:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-30 02:46:04.006   781  1320 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 02:46:04.006  6719  6719 E Zygote  : accessInfo : 0
,08-30 02:46:04.006  6719  6719 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-30 02:46:04.016  6671  6686 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 02:46:04.036  6719  6719 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:04.036  6719  6719 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:04.046   781  1320 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-30 02:46:04.046  6719  6719 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-30 02:46:04.066  6719  6719 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-30 02:46:04.076  6671  6686 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-30 02:46:04.096  6671  6686 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-30 02:46:04.096  6671  6686 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-30 02:46:04.096  6671  6686 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 02:46:04.136  6671  6686 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 02:46:04.146  6697  6697 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-30 02:46:04.146  6697  6697 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-30 02:46:04.156  6697  6697 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-30 02:46:04.166  6719  6719 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-30 02:46:04.176   781  1362 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-30 02:46:04.176  6697  6697 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 30 02:46:04 GMT+02:00 2016
,08-30 02:46:04.186  6697  6697 D DialogFlow: initQueue()
,08-30 02:46:04.196  6733  6733 E Zygote  : v2
,08-30 02:46:04.196  6733  6733 I libpersona: KNOX_SDCARD checking this for 1000
08-30 02:46:04.196  6733  6733 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:04.196   781  1800 I ActivityManager: Start proc 6733:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-30 02:46:04.196   781  1800 I ActivityManager: Killing 5428:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-30 02:46:04.196   781  1800 I ActivityManager: Killing 5669:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
08-30 02:46:04.196  6733  6733 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:04.196  6733  6733 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:04.196  6733  6733 E Zygote  : accessInfo : 0
,08-30 02:46:04.206  6719  6719 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-30 02:46:04.206   781  1175 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-30 02:46:04.216   781  1801 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-30 02:46:04.226  6733  6733 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:04.226  6733  6733 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:04.236   781  1317 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c17d4a 6733:com.samsung.android.app.filterinstaller/1000}
,08-30 02:46:04.236  6733  6733 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-30 02:46:04.246   781  1801 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-30 02:46:04.246  6733  6733 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-30 02:46:04.256  6733  6733 E FilterPackageIntentReceiver: This package is not a effect filter
,08-30 02:46:04.266   781  1745 I ActivityManager: Start proc 6749:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-30 02:46:04.266  6749  6749 E Zygote  : v2
08-30 02:46:04.266  6749  6749 I libpersona: KNOX_SDCARD checking this for 1000
08-30 02:46:04.266  6749  6749 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:04.266  6749  6749 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:04.266  6749  6749 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:04.266   781  1745 I ActivityManager: Killing 5720:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-30 02:46:04.286  6749  6749 E Zygote  : accessInfo : 0
,08-30 02:46:04.286   781   801 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-30 02:46:04.306  6749  6749 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 02:46:04.306  6749  6749 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:04.306  6719  6719 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-30 02:46:04.306  6719  6719 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-30 02:46:04.306   781  1422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c65d36d 6749:com.samsung.helphub/1000}
,08-30 02:46:04.316  6719  6719 D DialogFlow: initQueue()
,08-30 02:46:04.316  6749  6749 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-30 02:46:04.326  6749  6749 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-30 02:46:04.376  6761  6761 E Zygote  : v2
,08-30 02:46:04.376  6761  6761 I libpersona: KNOX_SDCARD checking this for 1000
08-30 02:46:04.376   781  1801 I ActivityManager: Start proc 6761:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-30 02:46:04.376  6761  6761 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:04.376  6761  6761 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:04.376  6761  6761 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:04.376   781  1801 I ActivityManager: Killing 5440:com.policydm/1000 (adj 15): DHA:empty #37
,08-30 02:46:04.376  6761  6761 E Zygote  : accessInfo : 0
,08-30 02:46:04.396  6761  6761 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:04.396  6761  6761 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:04.396   781  1621 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-30 02:46:04.396  6591  6591 D AASAservice: onDestroy()
,08-30 02:46:04.396  6591  6591 I art     : System.exit called, status: 80
,08-30 02:46:04.396  6591  6591 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-30 02:46:04.406   781   799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc96033 6761:com.samsung.android.app.mirrorlink/1000}
,08-30 02:46:04.416   781  1801 I ActivityManager: Process com.samsung.aasaservice (pid 6591)(adj 0) has died(47,766)
,08-30 02:46:04.416   781  1801 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-30 02:46:04.416  6761  6761 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-30 02:46:04.436   347   347 I Zygote  : Process 6591 exited cleanly (80)
,08-30 02:46:04.436  6761  6761 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-30 02:46:04.456  6761  6761 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-30 02:46:04.456  6761  6761 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-30 02:46:04.466   781   799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a22346 5816:com.google.android.apps.plus/u0a134}
,08-30 02:46:04.476   781  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a22346 5816:com.google.android.apps.plus/u0a134}
,08-30 02:46:04.486   781  1175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a22346 5816:com.google.android.apps.plus/u0a134}
,08-30 02:46:04.526   781  1175 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-30 02:46:04.526   781  1621 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-30 02:46:04.526   781  1698 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-30 02:46:04.536   781   799 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-30 02:46:04.536   781   801 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-30 02:46:04.536   781  1798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-30 02:46:04.536   781  1317 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-30 02:46:04.536   781  1804 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-30 02:46:04.576  6776  6776 E Zygote  : v2
,08-30 02:46:04.576  6776  6776 I libpersona: KNOX_SDCARD checking this for 10165
08-30 02:46:04.576  6776  6776 I libpersona: KNOX_SDCARD not a persona
,08-30 02:46:04.576   781  1698 I ActivityManager: Start proc 6776:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-30 02:46:04.576  6776  6776 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:04.576  6776  6776 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:04.576  6776  6776 E Zygote  : accessInfo : 0
,08-30 02:46:04.576  6776  6776 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-30 02:46:04.606  6776  6776 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:04.606  6776  6776 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:04.606   781  1798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf19fee 6776:com.sec.kidsplat.installer/u0a165}
,08-30 02:46:04.616  6776  6776 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-30 02:46:04.626  6776  6776 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-30 02:46:04.636   781  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf19fee 6776:com.sec.kidsplat.installer/u0a165}
,08-30 02:46:04.636  6776  6776 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-30 02:46:04.646   781  1640 I ActivityManager: Start proc 6788:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-30 02:46:04.646  6788  6788 E Zygote  : v2
08-30 02:46:04.646  6788  6788 I libpersona: KNOX_SDCARD checking this for 10142
08-30 02:46:04.646  6788  6788 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:04.646   781  1320 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-30 02:46:04.646  6788  6788 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-30 02:46:04.646  6788  6788 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:04.646  6788  6788 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:04.656  6788  6788 E Zygote  : accessInfo : 64
,08-30 02:46:04.656  6788  6788 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 02:46:04.656  6788  6788 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-30 02:46:04.656  6788  6788 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
08-30 02:46:04.656   781  1640 I ActivityManager: Killing 5748:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-30 02:46:04.656   781  1320 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-30 02:46:04.676   781  1798 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-30 02:46:04.686  6788  6788 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:04.686  6788  6788 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:04.696   781  1801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4afcc8f 6788:com.sec.android.app.sbrowser/u0a142}
,08-30 02:46:04.696  6788  6788 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-30 02:46:04.716  6788  6788 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-30 02:46:04.726  6788  6788 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-30 02:46:04.726  6788  6788 D ManifestProvider: onCreate()
,08-30 02:46:04.736  6788  6788 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-30 02:46:04.736  6788  6788 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 02:46:04.736  6788  6788 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 02:46:04.736  6788  6788 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-30 02:46:04.746  6788  6788 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-30 02:46:04.746  6788  6788 D [MM]MHDataBaseProvider: onCreate()
,08-30 02:46:04.766  6788  6788 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@f104012)
,08-30 02:46:04.816   781  1801 I ActivityManager: Killing 4544:com.wssyncmldm/1000 (adj 15): DHA:empty #37
,08-30 02:46:04.826   781  1801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe6ab5c 2112:com.google.android.gms.persistent/u0a11}
,08-30 02:46:04.836   781   799 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,08-30 02:46:04.836  4531  6803 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 02:46:04.836  4531  6802 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-30 02:46:04.846   781  1800 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{676398 4531:com.google.android.gms/u0a11}
,08-30 02:46:04.856  4531  6803 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 02:46:04.866  4531  4531 D AsyncTaskServiceImpl: Submit a task: nzm
,08-30 02:46:04.876  4531  6803 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 02:46:04.876   781  1175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe6ab5c 2112:com.google.android.gms.persistent/u0a11}
,08-30 02:46:04.876  4531  6803 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 02:46:04.886   781  1801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{676398 4531:com.google.android.gms/u0a11}
,08-30 02:46:04.886  4531  5093 D nzm     : Processing package: com.test.thalitest
,08-30 02:46:04.896  4531  4531 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 02:46:04.946  4531  5093 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-30 02:46:04.946  4531  5093 D nzm     : Found info for package com.test.thalitest in db.
,08-30 02:46:04.956  6621  6621 I Mms/MmsApp:  start initViewCache mms
,08-30 02:46:04.996   781  1745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f9f5a3c 6245:com.sec.android.app.samsungapps/u0a39}
,08-30 02:46:05.006   781  1745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{744b690 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{636008a 5845:com.android.vending/u0a29}
,08-30 02:46:05.066   781   799 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d62f77f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f4f8606 5899:com.sec.android.app.shealth/u0a34}
,08-30 02:46:05.066  5845  5845 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-30 02:46:05.076  2112  2112 D WearableService: callingUid 10011, callindPid: 2112
,08-30 02:46:05.076  5845  5845 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,08-30 02:46:05.086   781  1640 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d62f77f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7782e43 1908:com.sec.android.app.shealth:remote/u0a34}
,08-30 02:46:05.106  5845  5845 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-30 02:46:05.106  5845  5845 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-30 02:46:05.106   781  1317 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d62f77f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7782e43 1908:com.sec.android.app.shealth:remote/u0a34}
,08-30 02:46:05.136   781  1175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b98c9b u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe6ab5c 2112:com.google.android.gms.persistent/u0a11}
,08-30 02:46:05.146  6719  6747 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 02:46:05.146  6719  6747 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 02:46:05.176  6719  6747 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-30 02:46:05.176  6719  6747 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-30 02:46:05.176  6719  6747 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-30 02:46:05.176  6719  6747 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-30 02:46:05.176  6719  6747 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 02:46:05.286  6621  6621 D Mms/BubbleViewCache: fillCache bubble = 4
,08-30 02:46:05.376   781  3587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 02:46:06.056  4531  5076 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-30 02:46:06.116  4531  5076 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 02:46:06.146  4531  5076 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 02:46:06.146  4531  5076 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-30 02:46:07.226  3803  3803 D FactoryTest: User mode
,08-30 02:46:07.236  3803  3803 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 02:46:07.236  3803  3803 D MTPRx   : still no open session command from host, so toast
,08-30 02:46:07.236   781  1801 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-30 02:46:07.256   781  1801 D ActivityManager: mDVFSHelper.acquire()
,08-30 02:46:07.256   781  1801 V WindowManager: addAppToken: AppWindowToken{a256576 token=Token{7a20011 ActivityRecord{fba4838 u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-30 02:46:07.256   781  1801 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-30 02:46:07.276   781  1801 D InputDispatcher: Focused application set to: xxxx
,08-30 02:46:07.276   781  1801 D InputDispatcher: Focus left window: 6462
,08-30 02:46:07.276   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
,08-30 02:46:07.276   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 02:46:07.276   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
,08-30 02:46:07.276   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 02:46:07.286   781   860 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-30 02:46:07.286  3803  3803 E MTPRx   : started activity for popup
,08-30 02:46:07.286  3803  3803 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-30 02:46:07.296  3803  3803 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-30 02:46:07.306  3803  3803 D MTPUSBConnection: onCreate in USBConnection
,08-30 02:46:07.306  3803  3803 V MTPUSBConnection: Registering broadcast receiver.
,08-30 02:46:07.306  3803  3803 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-30 02:46:07.316   781  1804 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-30 02:46:07.356  3803  3803 D TAG     : dev.kiessupport is : TRUE
,08-30 02:46:07.376  3803  3803 D SecWifiDisplayUtil: Metadata value : none
,08-30 02:46:07.376  3803  3803 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b6e6c56 V.E...... R.....I. 0,0-0,0}
,08-30 02:46:07.386  3803  6832 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 02:46:07.386   781  1621 D ISSUE_DEBUG: InputChannelName : 2fad4e com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-30 02:46:07.386   781  1621 D InputDispatcher: Focus entered window: 3803
,08-30 02:46:07.386   781   862 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2fad4e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-30 02:46:07.386  1374  1374 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-30 02:46:07.386   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
,08-30 02:46:07.386   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 02:46:07.386   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-30 02:46:07.386   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 02:46:07.396  3803  3803 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6f6b02e I.E...... R.....I. 0,0-0,0}
,08-30 02:46:07.396   781  1798 D ISSUE_DEBUG: InputChannelName : d07177c com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-30 02:46:07.396   781  1805 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-30 02:46:07.396   781  1805 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:46:07.396   781   781 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 02:46:07.406   781   781 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 02:46:07.406   781   781 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-30 02:46:07.436   292   292 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,08-30 02:46:07.446  3803  6832 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 02:46:07.446  3803  6832 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 02:46:07.446  3803  6832 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 02:46:07.446  3803  6832 I Adreno-EGL: Local Branch: ss
08-30 02:46:07.446  3803  6832 I Adreno-EGL: Remote Branch: 
08-30 02:46:07.446  3803  6832 I Adreno-EGL: Local Patches: 
08-30 02:46:07.446  3803  6832 I Adreno-EGL: Reconstruct Branch: 
08-30 02:46:07.446  3803  6832 D libEGL  : eglInitialize EGLDisplay = 0x9efe07c4
08-30 02:46:07.446  3803  6832 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 02:46:07.476   292   292 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
08-30 02:46:07.506  3803  3803 V ActivityThread: updateVisibility : ActivityRecord{3468065 token=android.os.BinderProxy@38a84d7 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
08-30 02:46:07.516  3803  3803 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-30 02:46:07.606   781  1805 V WindowStateAnimator: Finishing drawing window Window{2fad4e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 02:46:07.616  3803  3803 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-30 02:46:07.616   781   801 V WindowStateAnimator: Finishing drawing window Window{d07177c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-30 02:46:07.616  3803  3803 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:46:07.616  3803  3803 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 02:46:07.616   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeb7364
08-30 02:46:07.616   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeb7364
08-30 02:46:07.626   781   923 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:46:07.626   781   781 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 02:46:07.626   781   923 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +352ms (total +370ms)
08-30 02:46:07.626   781   781 I KnoxTimeoutHandler: SD activityfalse
08-30 02:46:07.626   781  1745 V WindowStateAnimator: Finishing drawing window Window{2fad4e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 02:46:07.626   781  1804 V WindowStateAnimator: Finishing drawing window Window{d07177c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 02:46:07.626  3803  3803 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38a84d7 time:109196
08-30 02:46:07.626   781   923 D ActivityManager: mDVFSHelper.release()
08-30 02:46:07.626   781   923 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fba4838 u0 com.samsung.android.MtpApplication/.USBConnection t168} time:109197
08-30 02:46:07.636   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeb7364
08-30 02:46:08.286   781  3558 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-30 02:46:08.406  1451  1451 D Recents : onTaskStackChanged
08-30 02:46:08.416  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-30 02:46:09.106   781  1234 V AlarmManager: Expired Alarm result :4
,08-30 02:46:09.116  1374  1374 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-30 02:46:09.116  1374  1374 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-30 02:46:09.116  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 02:46:09.126   781  1698 V AlarmManager:  remove PendingIntent] PendingIntent{9d2d28b: PendingIntentRecord{3a6e731 com.google.android.gms broadcastIntent}}
,08-30 02:46:09.136   781  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-30 02:46:09.136   781  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-30 02:46:09.136  1374  1374 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-30 02:46:09.146  1374  1374 D SecKeyguardClockView: HomeTimezone(): 1
,08-30 02:46:09.146  1374  1374 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.146  1374  1374 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.146  1374  1374 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.146  1374  1374 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.146  1374  1374 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 02:46:09.146  1374  1374 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.156  1374  1374 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.186   781   799 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 02:46:09.186   781   799 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4305, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-30 02:46:09.186   781   799 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-30 02:46:09.186   781   799 D BatteryService: stay LED for charging
,08-30 02:46:09.186   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 02:46:09.196   781   781 I MotionRecognitionService: Plugged
08-30 02:46:09.196   781   781 D MotionRecognitionService:   cableConnection= 1
,08-30 02:46:09.196   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 02:46:09.196   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-30 02:46:09.196  1374  1374 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 02:46:09.196  1374  1374 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-30 02:46:09.196  1374  1374 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 02:46:09.196  1374  1374 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 02:46:09.196  1374  1374 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 02:46:09.196  2541  2541 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 02:46:09.196  2541  2964 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 02:46:09.216  1374  1374 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 02:46:09.236  1374  1374 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-30 02:46:09.326   781  3557 D SSRM:n  : SIOP:: AP = 480, PST = 453, CUR = 300, LCD = 0
,08-30 02:46:10.376   781  3587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 02:46:11.176   781  1001 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 02:46:11.206   781  1001 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 02:46:12.156   781  1001 D PackageManager: [MSG] MCS_UNBIND
,08-30 02:46:12.176   781  1698 I ActivityManager: Killing 5791:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-30 02:46:12.176   781  1698 I ActivityManager: Killing 4842:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-30 02:46:12.206   781  1745 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-30 02:46:12.226   781  1175 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-30 02:46:13.326   781  3557 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 02:46:16.946   781   860 I ActivityManager: Waited long enough for: ServiceRecord{49774e7 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-30 02:46:18.816  6462  6607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:46:18.816  6462  6607 I jxcore-log: 
,08-30 02:46:18.816  6462  6607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:46:18.816  6462  6607 I jxcore-log: 
,08-30 02:46:18.826  6462  6607 D BluetoothAdapter: STATE_ON
,08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 02:46:18.826  6462  6607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 02:46:18.826  6462  6607 D BluetoothAdapter: STATE_ON
,08-30 02:46:18.826  6462  6607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 02:46:18.826  6462  6607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:46:18.826  6462  6607 I jxcore-log: 
,08-30 02:46:18.826  6462  6607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:46:18.826  6462  6607 I jxcore-log: 
,08-30 02:46:19.176   781  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-30 02:46:19.176   781  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-30 02:46:19.206  6462  6607 I jxcore-log: Running unit tests
08-30 02:46:19.206  6462  6607 I jxcore-log: 
,08-30 02:46:19.216  6462  6607 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:46:19.216  6462  6607 I jxcore-log: Failed to execute UT.
08-30 02:46:19.216  6462  6607 I jxcore-log: 
,08-30 02:46:19.216  6462  6607 I jxcore-log: Unit Test app is loaded
08-30 02:46:19.216  6462  6607 I jxcore-log: 
,08-30 02:46:19.216  6462  6607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 02:46:19.216  6462  6607 I jxcore-log: 
,08-30 02:46:19.226  6462  6462 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:46:19.226  6462  6607 I jxcore-log: My device name is: samsung-SM-G900F
08-30 02:46:19.226  6462  6607 I jxcore-log: 
,08-30 02:46:19.346   781  1571 E Watchdog: !@Sync 3 [08-30 02:46:19.356]
,08-30 02:46:19.366   781  3557 D SSRM:n  : SIOP:: AP = 450, PST = 452, CUR = 300, LCD = 0
,08-30 02:46:21.846  6462  6607 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 02:46:21.846  6462  6607 I jxcore-log: 
,08-30 02:46:22.336  6462  6607 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 02:46:22.336  6462  6607 I jxcore-log: 
,08-30 02:46:22.366  6462  6607 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 02:46:22.366  6462  6607 I jxcore-log: 
,08-30 02:46:23.846  6462  6607 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:46:23.846  6462  6607 I jxcore-log: 
,08-30 02:46:24.096  6462  6607 I jxcore-log: ERROR runTests: 
08-30 02:46:24.096  6462  6607 I jxcore-log: 
,08-30 02:46:24.106  6462  6607 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:24.106  6462  6607 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 02:46:24.116  6462  6607 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _functionName: 'loadFile',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _lineNumber: '26',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _columnNumber: '11',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:46:24.116  6462  6607 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _functionName: '',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _lineNumber: '38',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _columnNumber: '7',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:46:24.116  6462  6607 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _functionName: '',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _lineNumber: '35',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _columnNumber: '3',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:46:24.116  6462  6607 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _lineNumber: '621',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _columnNumber: '8',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 02:46:24.116  6462  6607 I jxcore-log:   { _fileName: 'module.js',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _lineNumber: '651',
08-30 02:46:24.116  6462  6607 I jxcore-log:     _columnNumber: '1',
08-30 02:46:24.116  6462  6607 I jxcore-log:    
08-30 02:46:24.116  6462  6607 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:46:24.116  6462  6607 I jxcore-log: 
08-30 02:46:24.116  6462  6607 E jxcore-log: Error: 
08-30 02:46:24.116  6462  6607 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:46:24.116  6462  6607 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:46:24.116  6462  6607 E jxcore-log: 
,08-30 02:46:24.276   307  1192 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-30 02:46:24.276   307  1192 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-30 02:46:24.276   307  1192 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-30 02:46:25.056  2548  2548 E audit   : type=1400 msg=audit(1472517985.056:290): avc:  denied  { execmod } for  pid=6871 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 02:46:25.056  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:25.056  2548  2548 E audit   : type=1300 msg=audit(1472517985.056:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f84000 a1=51000 a2=5 a3=4 items=0 ppid=3683 ppcomm=adbd pid=6871 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 02:46:25.056  2548  2548 E audit   : type=1327 msg=audit(1472517985.056:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-30 02:46:25.056  2548  2548 E audit   : type=1320 msg=audit(1472517985.056:290): 
,08-30 02:46:25.116  2548  2548 E audit   : type=1400 msg=audit(1472517985.116:291): avc:  denied  { execmod } for  pid=6871 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 02:46:25.116  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-30 02:46:25.116  2548  2548 E audit   : type=1300 msg=audit(1472517985.116:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f44000 a1=51000 a2=5 a3=4 items=0 ppid=3683 ppcomm=adbd pid=6871 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 02:46:25.116  2548  2548 E audit   : type=1327 msg=audit(1472517985.116:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-30 02:46:25.116  2548  2548 E audit   : type=1320 msg=audit(1472517985.116:291): 
,08-30 02:46:25.166  2548  2548 E audit   : type=1400 msg=audit(1472517985.166:292): avc:  denied  { execmod } for  pid=6871 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 02:46:25.166  2548  2548 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:25.166  2548  2548 E audit   : type=1300 msg=audit(1472517985.166:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f44000 a1=51000 a2=5 a3=4 items=0 ppid=3683 ppcomm=adbd pid=6871 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 02:46:25.166  2548  2548 E audit   : type=1327 msg=audit(1472517985.166:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-30 02:46:25.166  2548  2548 E audit   : type=1320 msg=audit(1472517985.166:292): 
08-30 02:46:25.166  6871  6871 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 02:46:25.176  6871  6871 D AndroidRuntime: CheckJNI is OFF
,08-30 02:46:25.176  6871  6871 D AndroidRuntime: readGMSProperty: start
08-30 02:46:25.176  6871  6871 D AndroidRuntime: readGMSProperty: already setted!!
08-30 02:46:25.176  6871  6871 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 02:46:25.176  6871  6871 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 02:46:25.176  6871  6871 D AndroidRuntime: readGMSProperty: end
08-30 02:46:25.176  6871  6871 D AndroidRuntime: addProductProperty: start
,08-30 02:46:25.186  6871  6871 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
,08-30 02:46:25.186  6871  6871 W art     : aedab000-b1cd1000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
,08-30 02:46:25.186  6871  6871 W art     : b1cd1000-b3f40000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-30 02:46:25.186  6871  6871 W art     : b3f40000-b3f41000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
,08-30 02:46:25.186  6871  6871 W art     : b3f41000-b3f42000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art,
08-30 02:46:25.186  6871  6871 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
,08-30 02:46:25.186  6871  6871 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 946        /system/lib/libart.so,
08-30 02:46:25.186  6871  6871 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 946        /system/lib/libart.so,
08-30 02:46:25.186  6871  6871 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-30 02:46:25.186  6871  6871 W art     : b4812000-b4815000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-30 02:46:25.186  6871  6871 W art     : b4815000-b4816000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so,
08-30 02:46:25.186  6871  6871 W art     : b4816000-b4817000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
,08-30 02:46:25.186  6871  6871 W art     : b4817000-b4818000 r--p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b4818000-b4838000 r--s 00000000 00:0b 7201       /dev/__properties__
08-30 02:46:25.186  6871  6871 W art     : b4838000-b5249000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so,
08-30 02:46:25.186  6871  6871 W art     : b5249000-b524a000 ---p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b524a000-b5293000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so,
08-30 02:46:25.186  6871  6871 W art     : b5293000-b5294000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
,08-30 02:46:25.186  6871  6871 W art     : b5294000-b529c000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b529c000-b52d1000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
,08-30 02:46:25.186  6871  6871 W art     : b52d1000-b52d2000 ---p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b52d2000-b52d3000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-30 02:46:25.186  6871  6871 W art     : b52d3000-b52d4000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
,08-30 02:46:25.186  6871  6871 W art     : b52d4000-b532c000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
,08-30 02:46:25.186  6871  6871 W art     : b532c000-b532d000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b532d000-b532e000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
,08-30 02:46:25.186  6871  6871 W art     : b532e000-b532f000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
,08-30 02:46:25.186  6871  6871 W art     : b5330000-b5336000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
08-30 02:46:25.186  6871  6871 W art     : AD_v01009.so
08-30 02:46:25.186  6871  6871 W art     : b5336000-b5337000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-30 02:46:25.186  6871  6871 W art     : b5337000-b5338000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 02:46:25.186  6871  6871 W art     : b5338000-b533a000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b533b000-b5345000 r-xp 00000000 b3:17 1088 
08-30 02:46:25.186  6871  6871 W art     :       /system/lib/libcommon_time_client.so
08-30 02:46:25.186  6871  6871 W art     : b5345000-b5348000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-30 02:46:25.186  6871  6871 W art     : b5348000-b5349000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 02:46:25.186  6871  6871 W art     : b534a000-b5361000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 02:46:25.186  6871  6871 W art     : b5361000-b5362000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5362000-b5363000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 02:46:25.186  6871  6871 W art     : b5363000-b5364000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 02:46:25.186  6871  6871 W art     : b5365000-b536f000 r-xp 00000000 b3:17 2671   
08-30 02:46:25.186  6871  6871 W art     :     /system/lib/libsec_km.so
,08-30 02:46:25.186  6871  6871 W art     : b536f000-b5370000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-30 02:46:25.186  6871  6871 W art     : b5370000-b5371000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-30 02:46:25.186  6871  6871 W art     : b5371000-b5375000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 02:46:25.186  6871  6871 W art     : b5375000-b5376000 r--p 00003000 b
08-30 02:46:25.186  6871  6871 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
08-30 02:46:25.186  6871  6871 W art     : b5376000-b5377000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-30 02:46:25.186  6871  6871 W art     : b5377000-b538d000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-30 02:46:25.186  6871  6871 W art     : b538d000-b538e000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-30 02:46:25.186  6871  6871 W art     : b538e000-b538f000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-30 02:46:25.186  6871  6871 W art     : b538f000-b539c000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-30 02:46:25.186  6871  6871 W art     : b539c000-b539d000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-30 02:46:25.186  6871  6871 W art     : b539d000-b539e000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-30 02:46:25.186  6871  6871 W art     : b539e000-b53fe000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-30 02:46:25.186  6871  6871 W art     : b53fe000-b5401000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-30 02:46:25.186  6871  6871 W art     : b5401000-b5405000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5405000-b5466000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-30 02:46:25.186  6871  6871 W art     : b5466000-b5467000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-30 02:46:25.186  6871  6871 W art     : b5467000-b54b6000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-30 02:46:25.186  6871  6871 W art     : b54b6000-b54b8000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-30 02:46:25.186  6871  6871 W art     : b54b8000-b54b9000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-30 02:46:25.186  6871  6871 W art     : b54b9000-b54ba000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b54ba000-b54c1000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 02:46:25.186  6871  6871 W art     : b54c1000-b54c2000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 02:46:25.186  6871  6871 W art     : b54c2000-b54c3000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-30 02:46:25.186  6871  6871 W art     : avc_common.so
08-30 02:46:25.186  6871  6871 W art     : b54c4000-b54c7000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 02:46:25.186  6871  6871 W art     : b54c7000-b54c8000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-30 02:46:25.186  6871  6871 W art     : b54c8000-b54c9000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-30 02:46:25.186  6871  6871 W art     : enc_common.so
08-30 02:46:25.186  6871  6871 W art     : b54ca000-b54ce000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-30 02:46:25.186  6871  6871 W art     : b54ce000-b54cf000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b54cf000-b54d0000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-30 02:46:25.186  6871  6871 W art     : b54d0000-b54d1000 rw-p 00005000 b3:17 2510       /syste
,08-30 02:46:25.186  6871  6871 W art     : m/lib/libpowermanager.so
08-30 02:46:25.186  6871  6871 W art     : b54d2000-b54ef000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 02:46:25.186  6871  6871 W art     : b54ef000-b54f0000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 02:46:25.186  6871  6871 W art     : b54f0000-b54f1000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 02:46:25.186  6871  6871 W art     : b54f2000-b54f7000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 02:46:25.186  6871  6871 W art     : b54f7000-b54f8000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 02:46:25.186  6871  6871 W art     : b54f8000-b54f9000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
,08-30 02:46:25.186  6871  6871 W art     : b54fa000-b552b000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 02:46:25.186  6871  6871 W art     : b552b000-b552c000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b552c000-b552f000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 02:46:25.186  6871  6871 W art     : b552f000-b5530000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 02:46:25.186  6871  6871 W art     : b5531000-b556c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-30 02:46:25.186  6871  6871 W art     : b556c000-b556d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-30 02:46:25.186  6871  6871 W art     : b556d000-b556e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-30 02:46:25.186  6871  6871 W art     : b556f000-b5576000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-30 02:46:25.186  6871  6871 W art     : b5576000-b5577000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5577000-b5578000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-30 02:46:25.186  6871  6871 W art     : b5578000-b5579000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-30 02:46:25.186  6871  6871 W art     : b5579000-b557a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b557a000-b5591000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
,08-30 02:46:25.186  6871  6871 W art     : b5591000-b5592000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5592000-b5595000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-30 02:46:25.186  6871  6871 W art     : b5595000-b5596000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-30 02:46:25.186  6871  6871 W art     : b5596000-b55b5000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-30 02:46:25.186  6871  6871 W art     : b55b5000-b55b6000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-30 02:46:25.186  6871  6871 W art     : b55b6000-b55b7000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-30 02:46:25.186  6871  6871 W art     : b55b7000-b55f5000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
,08-30 02:46:25.186  6871  6871 W art     : b55f5000-b55f6000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b55f6000-b55f8000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-30 02:46:25.186  6871  6871 W art     : b55f8000-b55f9000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-30 02:46:25.186  6871  6871 W art     : b55fa000-b5601000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 02:46:25.186  6871  6871 W art     : b5601000-b5602000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 02:46:25.186  6871  6871 W art     : b5602000-b5603000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 02:46:25.186  6871  6871 W art     : b5604000-b5607000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
,08-30 02:46:25.186  6871  6871 W art     : b5607000-b5608000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 02:46:25.186  6871  6871 W art     : b5608000-b5609000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 02:46:25.186  6871  6871 W art     : b5609000-b560f000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 02:46:25.186  6871  6871 W art     : b560f000-b5610000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5610000-b5611000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-30 02:46:25.186  6871  6871 W art     : b5611000-b5612000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 02:46:25.186  6871  6871 W art     : b5612000-b561b000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-30 02:46:25.186  6871  6871 W art     : b561b000-b561c000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-30 02:46:25.186  6871  6871 W art     : b561c000-b561d000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-30 02:46:25.186  6871  6871 W art     : b561d000-b56ae000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 02:46:25.186  6871  6871 W art     : b56ae000-b56af000 ---p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b56af000-b56ba000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 02:46:25.186  6871  6871 W art     : b56ba000-b56bb000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 02:46:25.186  6871  6871 W art     : b56bc000-b56ce000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-30 02:46:25.186  6871  6871 W art     : b56ce000-b56cf000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-30 02:46:25.186  6871  6871 W art     : b56cf000-b56d0000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-30 02:46:25.186  6871  6871 W art     : b56d1000-b56d6000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
,08-30 02:46:25.186  6871  6871 W art     : b56d6000-b56d7000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-30 02:46:25.186  6871  6871 W art     : b56d7000-b56d8000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-30 02:46:25.186  6871  6871 W art     : b56d9000-b5746000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-30 02:46:25.186  6871  6871 W art     : b5746000-b5747000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5747000-b5749000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-30 02:46:25.186  6871  6871 W art     : b5749000-b574a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-30 02:46:25.186  6871  6871 W art     : b574a000-b574b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b574b000-b5752000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-30 02:46:25.186  6871  6871 W art     : b5752000-b5753000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 02:46:25.186  6871  6871 W art     : b5753000-b5754000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 02:46:25.186  6871  6871 W art     : b5755000-b57d5000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 02:46:25.186  6871  6871 W art     : b57d5000-b57d6000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b57d6000-b57d7000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 02:46:25.186  6871  6871 W art     : b57d7000-b57d8000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 02:46:25.186  6871  6871 W art     : b57d8000-b57ef000 rw-p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b57ef000-b5826000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 02:46:25.186  6871  6871 W art     : b5826000-b5827000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 02:46:25.186  6871  6871 W art     : b5827000-b5828000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 02:46:25.186  6871  6871 W art     : b5828000-b5844000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 02:46:25.186  6871  6871 W art     : b5844000-b5845000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 02:46:25.186  6871  6871 W art     : b5845000-b5846000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 02:46:25.186  6871  6871 W art     : b5847000-b58a8000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
,08-30 02:46:25.186  6871  6871 W art     : b58a8000-b58aa000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-30 02:46:25.186  6871  6871 W art     : b58aa000-b58ab000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-30 02:46:25.186  6871  6871 W art     : b58ac000-b58d1000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-30 02:46:25.186  6871  6871 W art     : b58d1000-b58d2000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-30 02:46:25.186  6871  6871 W art     : b58d2000-b58d3000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-30 02:46:25.186  6871  6871 W art     : b58d4000-b58dc000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 02:46:25.186  6871  6871 W art     : b58dc000-b58de000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-30 02:46:25.186  6871  6871 W art     : b58de000-b58df000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 02:46:25.186  6871  6871 W art     : b58e0000-b58e3000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-30 02:46:25.186  6871  6871 W art     : b58e3000-b58e4000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-30 02:46:25.186  6871  6871 W art     : b58e4000-b58e5000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-30 02:46:25.186  6871  6871 W art     : b58e5000-b58e9000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-30 02:46:25.186  6871  6871 W art     : b58e9000-b58ea000 ---p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b58ea000-b58eb000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-30 02:46:25.186  6871  6871 W art     : b58eb000-b58ec000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-30 02:46:25.186  6871  6871 W art     : b58ec000-b58fc000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-30 02:46:25.186  6871  6871 W art     : b58fc000-b58fd000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-30 02:46:25.186  6871  6871 W art     : b58fd000-b58fe000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-30 02:46:25.186  6871  6871 W art     : b58fe000-b5944000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5944000-b594d000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-30 02:46:25.186  6871  6871 W art     : b594d000-b594e000 r--p 00008000 b3:17 982        /system/lib/libbase.so
,08-30 02:46:25.186  6871  6871 W art     : b594e000-b594f000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-30 02:46:25.186  6871  6871 W art     : b5950000-b5955000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-30 02:46:25.186  6871  6871 W art     : b5955000-b5956000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-30 02:46:25.186  6871  6871 W art     : b5956000-b5957000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-30 02:46:25.186  6871  6871 W art     : b5957000-b595a000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 02:46:25.186  6871  6871 W art     : b595a000-b595b000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b595b000-b595c000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
,08-30 02:46:25.186  6871  6871 W art     : b595c000-b595d000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 02:46:25.186  6871  6871 W art     : b595e000-b5976000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
08-30 02:46:25.186  6871  6871 W art     : ght_foundation.so
08-30 02:46:25.186  6871  6871 W art     : b5976000-b5977000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5977000-b5978000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 02:46:25.186  6871  6871 W art     : b5978000-b5979000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
,08-30 02:46:25.186  6871  6871 W art     : b5979000-b597a000 rw-p 00000000 00:
08-30 02:46:25.186  6871  6871 W art     : 00 0          [anon:linker_alloc_vector]
08-30 02:46:25.186  6871  6871 W art     : b597a000-b5b14000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-30 02:46:25.186  6871  6871 W art     : b5b14000-b5b15000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5b15000-b5b22000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-30 02:46:25.186  6871  6871 W art     : b5b22000-b5b23000 rw-p 001a7000 b3:17 604        /system/
08-30 02:46:25.186  6871  6871 W art     : lib/libstagefright.so
,08-30 02:46:25.186  6871  6871 W art     : b5b23000-b5b27000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-30 02:46:25.186  6871  6871 W art     : b5b27000-b5b28000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5b28000-b5b29000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-30 02:46:25.186  6871  6871 W art     : b5b29000-b5b2a000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-30 02:46:25.186  6871  6871 W art     : ersona.so
08-30 02:46:25.186  6871  6871 W art     : b5b2a000-b5b3d000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-30 02:46:25.186  6871  6871 W art     : b5b3d000-b5b3e000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
,08-30 02:46:25.186  6871  6871 W art     : b5b3e000-b5b3f000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-30 02:46:25.186  6871  6871 W art     : b5b40000-b5b8b000 r
08-30 02:46:25.186  6871  6871 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-30 02:46:25.186  6871  6871 W art     : b5b8b000-b5b8c000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-30 02:46:25.186  6871  6871 W art     : b5b8c000-b5b8d000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-30 02:46:25.186  6871  6871 W art     : b5b8d000-b5b8f000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5b90000-b5ba1000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-30 02:46:25.186  6871  6871 W art     : b5ba1000-b5ba2000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5ba2000-b5ba3000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 02:46:25.186  6871  6871 W art     : b5ba3000-b5ba4000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 02:46:25.186  6871  6871 W art     : b5ba4000-b5ba5000 r--p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b5ba5000-b5baf000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-30 02:46:25.186  6871  6871 W art     : b5baf000-b5bb1000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-30 02:46:25.186  6871  6871 W art     : b5bb1000-b5bb2000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-30 02:46:25.186  6871  6871 W art     : b5bb2000-b5bcb000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-30 02:46:25.186  6871  6871 W art     : b5bcb000-b5bcc000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-30 02:46:25.186  6871  6871 W art     : b5bcc000-b5bcf000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-30 02:46:25.186  6871  6871 W art     : b5bcf000-b5bd3000 rw-p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b5bd3000-b5c47000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-30 02:46:25.186  6871  6871 W art     : b5c47000-b5c48000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5c48000-b5c4b000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-30 02:46:25.186  6871  6871 W art     : b5c4b000-b5c4c000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-30 02:46:25.186  6871  6871 W art     : b5c4c000-b5c4d000 r--p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5c4d000-b5c50000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-30 02:46:25.186  6871  6871 W art     : b5c50000-b5c51000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-30 02:46:25.186  6871  6871 W art     : b5c51000-b5c52000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
,08-30 02:46:25.186  6871  6871 W art     : b5c52000-b5c53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b5c53000-b5c58000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 02:46:25.186  6871  6871 W art     : b5c58000-b5c59000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 02:46:25.186  6871  6871 W art     : b5c59000-b5c5a000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 02:46:25.186  6871  6871 W art     : b5c5a000-b5c5b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b5c5b000-b5c5e000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 02:46:25.186  6871  6871 W art     : b5c5e000-b5c5f000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 02:46:25.186  6871  6871 W art     : b5c5f000-b5c60000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
,08-30 02:46:25.186  6871  6871 W art     : b5c60000-b5c61000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:25.186  6871  6871 W art     : b5c61000-b5c65000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-30 02:46:25.186  6871  6871 W art     : b5c65000-b5c66000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-30 02:46:25.186  6871  6871 W art     : b5c66000-b5c67000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-30 02:46:25.186  6871  6871 W art     : b5c67000-b5c68000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b5c68000-b5c6c000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 02:46:25.186  6871  6871 W art     : b5c6c000-b5c6d000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 02:46:25.186  6871  6871 W art     : b5c6d000-b5c6e000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 02:46:25.186  6871  6871 W art     : b5c6e000-b5c6f000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-30 02:46:25.186  6871  6871 W art     : b5c6f000-b5c7d000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-30 02:46:25.186  6871  6871 W art     : b5c7d000-b5c7e000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b5c7e000-b5c7f000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-30 02:46:25.186  6871  6871 W art     : b5c7f000-b5c80000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-30 02:46:25.186  6871  6871 W art     : b5c80000-b5c8a000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 02:46:25.186  6871  6871 W art     : b5c8a000-b5c8d000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 02:46:25.186  6871  6871 W art     : b5c8d000-b5c8e000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
,08-30 02:46:25.186  6871  6871 W art     : b5c8e000-b5c8f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b5c8f000-b5c99000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-30 02:46:25.186  6871  6871 W art     : b5c99000-b5c9c000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-30 02:46:25.186  6871  6871 W art     : b5c9c000-b5c9d000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-30 02:46:25.186  6871  6871 W art     : b5c9d000-b5ca1000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-30 02:46:25.186  6871  6871 W art     : b5ca1000-b5ca2000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-30 02:46:25.186  6871  6871 W art     : b5ca2000-b5ca3000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-30 02:46:25.186  6871  6871 W art     : b5ca3000-b5ca4000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-30 02:46:25.186  6871  6871 W art     : b5ca4000-b5cb1000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-30 02:46:25.186  6871  6871 W art     : b5cb1000-b5cb3000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-30 02:46:25.186  6871  6871 W art     : b5cb3000-b5cb4000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-30 02:46:25.186  6871  6871 W art     : b5cb4000-b60c6000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-30 02:46:25.186  6871  6871 W art     : b60c6000-b60c7000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b60c7000-b60d0000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-30 02:46:25.186  6871  6871 W art     : b60d0000-b60d4000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-30 02:46:25.186  6871  6871 W art     : b60d4000-b60d5000 rw-p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b60d5000-b60dc000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-30 02:46:25.186  6871  6871 W art     : b60dc000-b60dd000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-30 02:46:25.186  6871  6871 W art     : b60dd000-b60de000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-30 02:46:25.186  6871  6871 W art     : b60de000-b60df000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b60df000-b60fa000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-30 02:46:25.186  6871  6871 W art     : b60fa000-b60fb000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-30 02:46:25.186  6871  6871 W art     : b60fb000-b60fc000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-30 02:46:25.186  6871  6871 W art     : b60fc000-b60fd000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-30 02:46:25.186  6871  6871 W art     : b60fd000-b6149000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 02:46:25.186  6871  6871 W art     : b6149000-b614a000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b614a000-b614b000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 02:46:25.186  6871  6871 W art     : b614b000-b614c000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 02:46:25.186  6871  6871 W art     : b614c000-b614d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b614d000-b6151000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-30 02:46:25.186  6871  6871 W art     : b6151000-b6152000 ---p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b6152000-b6153000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-30 02:46:25.186  6871  6871 W art     : b6153000-b6154000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-30 02:46:25.186  6871  6871 W art     : b6154000-b618c000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-30 02:46:25.186  6871  6871 W art     : b618c000-b618d000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-30 02:46:25.186  6871  6871 W art     : b618d000-b618e000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-30 02:46:25.186  6871  6871 W art     : b618e000-b618f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.186  6871  6871 W art     : b618f000-b622e000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-30 02:46:25.186  6871  6871 W art     : b622e000-b624c000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
,08-30 02:46:25.186  6871  6871 W art     : b624c000-b624d000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-30 02:46:25.186  6871  6871 W art     : b624d000-b63c0000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-30 02:46:25.186  6871  6871 W art     : b63c0000-b63cb000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-30 02:46:25.186  6871  6871 W art     : b63cb000-b63cc000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-30 02:46:25.186  6871  6871 W art     : b63cc000-b64e3000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-30 02:46:25.186  6871  6871 W art     : b64e3000-b64ee000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-30 02:46:25.186  6871  6871 W art     : b64ee000-b64ef000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
,08-30 02:46:25.186  6871  6871 W art     : b64ef000-b64f3000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b64f3000-b6517000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-30 02:46:25.186  6871  6871 W art     : b6517000-b6519000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-30 02:46:25.186  6871  6871 W art     : b6519000-b651a000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-30 02:46:25.186  6871  6871 W art     : b651a000-b65c0000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-30 02:46:25.186  6871  6871 W art     : b65c0000-b65cd000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-30 02:46:25.186  6871  6871 W art     : b65cd000-b65ce000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-30 02:46:25.186  6871  6871 W art     : b65ce000-b65cf000 rw-p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b65cf000-b6622000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-30 02:46:25.186  6871  6871 W art     : b6622000-b6623000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6623000-b6624000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-30 02:46:25.186  6871  6871 W art     : b6624000-b6625000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-30 02:46:25.186  6871  6871 W art     : b6625000-b662a000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b662a000-b663c000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-30 02:46:25.186  6871  6871 W art     : b663c000-b663d000 ---p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b663d000-b663e000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-30 02:46:25.186  6871  6871 W art     : b663e000-b663f000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-30 02:46:25.186  6871  6871 W art     : b663f000-b6646000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 02:46:25.186  6871  6871 W art     : b6646000-b6647000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 02:46:25.186  6871  6871 W art     : b6647000-b6648000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-30 02:46:25.186  6871  6871 W art     : b6648000-b6649000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6649000-b664c000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-30 02:46:25.186  6871  6871 W art     : b664c000-b664d000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-30 02:46:25.186  6871  6871 W art     : b664d000-b664e000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-30 02:46:25.186  6871  6871 W art     : b664e000-b6652000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-30 02:46:25.186  6871  6871 W art     : b6652000-b6653000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-30 02:46:25.186  6871  6871 W art     : b6653000-b6654000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
,08-30 02:46:25.186  6871  6871 W art     : b6654000-b6662000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-30 02:46:25.186  6871  6871 W art     : b6662000-b6663000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6663000-b6664000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-30 02:46:25.186  6871  6871 W art     : b6664000-b6665000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-30 02:46:25.186  6871  6871 W art     : b6665000-b666e000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 02:46:25.186  6871  6871 W art     : b666e000-b666f000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 02:46:25.186  6871  6871 W art     : b666f000-b6670000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 02:46:25.186  6871  6871 W art     : b6670000-b66d6000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
,08-30 02:46:25.186  6871  6871 W art     : b66d6000-b66d7000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b66d7000-b66d9000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-30 02:46:25.186  6871  6871 W art     : b66d9000-b66e2000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-30 02:46:25.186  6871  6871 W art     : b66e2000-b66e5000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b66e5000-b677c000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-30 02:46:25.186  6871  6871 W art     : b677c000-b677e000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-30 02:46:25.186  6871  6871 W art     : b677e000-b677f000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-30 02:46:25.186  6871  6871 W art     : b677f000-b6780000 rw-p 00000000 00:00 0 
,08-30 02:46:25.186  6871  6871 W art     : b6780000-b6a9e000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-30 02:46:25.186  6871  6871 W art     : b6a9e000-b6a9f000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6a9f000-b6aba000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-30 02:46:25.186  6871  6871 W art     : b6aba000-b6abe000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-30 02:46:25.186  6871  6871 W art     : b6abe000-b6ac3000 rw-p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6ac3000-b6acb000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 02:46:25.186  6871  6871 W art     : b6acb000-b6acc000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
,08-30 02:46:25.186  6871  6871 W art     : b6acc000-b6acd000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 02:46:25.186  6871  6871 W art     : b6acd000-b6afb000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-30 02:46:25.186  6871  6871 W art     : b6afb000-b6afc000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6afc000-b6b03000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-30 02:46:25.186  6871  6871 W art     : b6b03000-b6b04000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-30 02:46:25.186  6871  6871 W art     : b6b04000-b6b4a000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-30 02:46:25.186  6871  6871 W art     : b6b4a000-b6b4b000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6b4b000-b6b4e000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-30 02:46:25.186  6871  6871 W art     : b6b4e000-b6b4f000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
,08-30 02:46:25.186  6871  6871 W art     : b6b4f000-b6b6a000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-30 02:46:25.186  6871  6871 W art     : b6b6a000-b6b6e000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-30 02:46:25.186  6871  6871 W art     : b6b6e000-b6b6f000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-30 02:46:25.186  6871  6871 W art     : b6b6f000-b6bbc000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-30 02:46:25.186  6871  6871 W art     : b6bbc000-b6bbd000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6bbd000-b6bc9000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-30 02:46:25.186  6871  6871 W art     : b6bc9000-b6bca000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-30 02:46:25.186  6871  6871 W art     : b6bca000-b6bd7000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
,08-30 02:46:25.186  6871  6871 W art     : b6bd7000-b6bd8000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6bd8000-b6bd9000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-30 02:46:25.186  6871  6871 W art     : b6bd9000-b6bda000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-30 02:46:25.186  6871  6871 W art     : b6bda000-b6be2000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-30 02:46:25.186  6871  6871 W art     : b6be2000-b6be3000 ---p 00000000 00:00 0 
08-30 02:46:25.186  6871  6871 W art     : b6be3000-b6be4000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-30 02:46:25.186  6871  6871 W art     : b6be4000-b6be5000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-30 02:46:25.186  6871  6871 W art     : b6be5000-b6bec000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-30 02:46:25.186  6871  6871 W art     : b6bec000-b6bed000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
,08-30 02:46:25.186  6871  6871 W art     : b6bed000-b6bee000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-30 02:46:25.186  6871  6871 W art     : b6bee000-b6c02000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-30 02:46:25.186  6871  6871 W art     : b6c02000-b6c04000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-30 02:46:25.186  6871  6871 W art     : b6c04000-b6c05000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-30 02:46:25.186  6871  6871 W art     : b6c05000-b6c2d000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-30 02:46:25.186  6871  6871 W art     : b6c2d000-b6c2f000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-30 02:46:25.186  6871  6871 W art     : b6c2f000-b6c30000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
,08-30 02:46:25.186  6871  6871 W art     : b6c30000-b6c33000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-30 02:46:25.186  6871  6871 W art     : b6c33000-b6c34000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-30 02:46:25.186  6871  6871 W art     : b6c34000-b6c35000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-30 02:46:25.186  6871  6871 W art     : b6c35000-b6c3e000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-30 02:46:25.186  6871  6871 W art     : b6c3e000-b6c3f000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-30 02:46:25.196  6871  6871 W art     : b6c3f000-b6c40000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-30 02:46:25.196  6871  6871 W art     : b6c40000-b6c60000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-30 02:46:25.196  6871  6871 W art     : b6c60000-b6c61000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-30 02:46:25.196  6871  6871 W art     : b6c61000-b6c62000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-30 02:46:25.196  6871  6871 W art     : b6c62000-b6cd5000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-30 02:46:25.196  6871  6871 W art     : b6cd5000-b6cd9000 r--p 00072000 b3:17 1016       /system/lib/libc.so
,08-30 02:46:25.196  6871  6871 W art     : b6cd9000-b6cdc000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-30 02:46:25.196  6871  6871 W art     : b6cdc000-b6ce6000 rw-p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6ce6000-b6d6e000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-30 02:46:25.196  6871  6871 W art     : b6d6e000-b6d6f000 ---p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6d6f000-b6d73000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-30 02:46:25.196  6871  6871 W art     : b6d73000-b6d74000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-30 02:46:25.196  6871  6871 W art     : b6d74000-b6d75000 rw-p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6d75000-b6d9e000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-30 02:46:25.196  6871  6871 W art     : b6d9e000-b6d9f000 ---p 00000000 00:00 0 
,08-30 02:46:25.196  6871  6871 W art     : b6d9f000-b6da2000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-30 02:46:25.196  6871  6871 W art     : b6da2000-b6da3000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-30 02:46:25.196  6871  6871 W art     : b6da3000-b6e7d000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 02:46:25.196  6871  6871 W art     : b6e7d000-b6e84000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 02:46:25.196  6871  6871 W art     : b6e84000-b6e8c000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 02:46:25.196  6871  6871 W art     : b6e8c000-b6e8d000 rw-p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6e8d000-b6e8e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:25.196  6871  6871 W art     : b6e8e000-b6e8f000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
,08-30 02:46:25.196  6871  6871 W art     : b6e8f000-b6e90000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.196  6871  6871 W art     : b6e90000-b6e93000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.196  6871  6871 W art     : b6e93000-b6eb8000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-30 02:46:25.196  6871  6871 W art     : b6eb8000-b6eb9000 ---p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6eb9000-b6ec0000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-30 02:46:25.196  6871  6871 W art     : b6ec0000-b6ec1000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-30 02:46:25.196  6871  6871 W art     : b6ec1000-b6ec8000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
,08-30 02:46:25.196  6871  6871 W art     : b6ec8000-b6ec9000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-30 02:46:25.196  6871  6871 W art     : b6ec9000-b6eca000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-30 02:46:25.196  6871  6871 W art     : b6eca000-b6ecb000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-30 02:46:25.196  6871  6871 W art     : b6ecb000-b6ee3000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-30 02:46:25.196  6871  6871 W art     : b6ee3000-b6ee4000 ---p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6ee4000-b6ee5000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-30 02:46:25.196  6871  6871 W art     : b6ee5000-b6ee6000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-30 02:46:25.196  6871  6871 W art     : b6ee6000-b6ef4000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-30 02:46:25.196  6871  6871 W art     : b6ef4000-b6ef5000 ---p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6ef5000-b6ef6000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
,08-30 02:46:25.196  6871  6871 W art     : b6ef6000-b6ef7000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-30 02:46:25.196  6871  6871 W art     : b6ef7000-b6ef8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:25.196  6871  6871 W art     : b6ef8000-b6efa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.196  6871  6871 W art     : b6efa000-b6efb000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.196  6871  6871 W art     : b6efb000-b6efc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 02:46:25.196  6871  6871 W art     : b6efc000-b6efd000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-30 02:46:25.196  6871  6871 W art     : b6efd000-b6efe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 02:46:25.196  6871  6871 W art     : b6efe000-b6f1e000 r--s 00000000 00:0b 7201       /dev/__properties__
,08-30 02:46:25.196  6871  6871 W art     : b6f1e000-b6f1f000 r--p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6f1f000-b6f20000 ---p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6f20000-b6f22000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-30 02:46:25.196  6871  6871 W art     : b6f22000-b6f23000 r-xp 00000000 00:00 0          [sigpage]
08-30 02:46:25.196  6871  6871 W art     : b6f23000-b6f3e000 r-xp 00000000 b3:17 341        /system/bin/linker
08-30 02:46:25.196  6871  6871 W art     : b6f3e000-b6f3f000 r--p 0001a000 b3:17 341        /system/bin/linker
,08-30 02:46:25.196  6871  6871 W art     : b6f3f000-b6f41000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-30 02:46:25.196  6871  6871 W art     : b6f41000-b6f43000 rw-p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : b6f43000-b6f48000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-30 02:46:25.196  6871  6871 W art     : b6f48000-b6f49000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-30 02:46:25.196  6871  6871 W art     : b6f49000-b6f4a000 rw-p 00000000 00:00 0 
08-30 02:46:25.196  6871  6871 W art     : bed4d000-bed6e000 rw-p 00000000 00:00 0          [stack]
08-30 02:46:25.196  6871  6871 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-30 02:46:25.266  6871  6871 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 02:46:25.316  6871  6871 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 02:46:25.326  6871  6871 E AffinityControl: AffinityControl: registerfunction enter
,08-30 02:46:25.346  6871  6871 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 02:46:25.356   781  1317 D PackageManager: START PACKAGE DELETE: observer{225193832}
08-30 02:46:25.356   781  1317 D PackageManager: pkg{<packageName>}
08-30 02:46:25.356   781  1317 D PackageManager: user{0}
08-30 02:46:25.356   781  1317 D PackageManager: caller{2000}
08-30 02:46:25.356   781  1317 D PackageManager: flags{2}
,08-30 02:46:25.356   781  1317 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 02:46:25.356   781  1317 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 02:46:25.356   781  1317 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 02:46:25.356   781  1317 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 02:46:25.356   781  1317 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 02:46:25.356   781  1001 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 02:46:25.356   781  1001 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 02:46:25.356   781  1001 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 02:46:25.356   781  1001 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 02:46:25.356   781  1001 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 02:46:25.356   781  1001 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 02:46:25.356   781  1001 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-30 02:46:25.356   781  1001 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-30 02:46:25.356   781   860 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-30 02:46:25.356   781   860 I ActivityManager: Killing 6462:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-30 02:46:25.356   781   860 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 02:46:25.366   781  1001 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-30 02:46:25.366   781  1001 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-30 02:46:25.376  6880  6880 E Zygote  : v2
08-30 02:46:25.376   781   860 I ActivityManager: Start proc 6880:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-30 02:46:25.376  6880  6880 I libpersona: KNOX_SDCARD checking this for 10004
08-30 02:46:25.386  6880  6880 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-30 02:46:25.376  6880  6880 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:25.386  6880  6880 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:25.386  6880  6880 E Zygote  : accessInfo : 0
08-30 02:46:25.386  6880  6880 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 02:46:25.386   781   860 I ActivityManager:   Force finishing activity ActivityRecord{e29b7d4 u0 com.test.thalitest/.MainActivity t167}
,08-30 02:46:25.396   292  2007 I SurfaceFlinger: id=20 Removed NainActivit (4/10)
,08-30 02:46:25.396   292  2008 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-30 02:46:25.396   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeb738c
,08-30 02:46:25.416   781  1001 D AASAinstall: there is not AASApackages.xml file
,08-30 02:46:25.416  6880  6880 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:25.416  6880  6880 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:25.456   781  1745 D GraphicsStats: Buffer count: 4
,08-30 02:46:25.456   781  1804 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@ff20f81)
,08-30 02:46:25.456   781  1329 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:46:25.456   781  1329 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 02:46:25.456   781  1329 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 02:46:25.706   781  1001 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 02:46:25.786   781  1001 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 02:46:25.796   781  1798 I ActivityManager: Killing 5804:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-30 02:46:25.796   332   332 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-30 02:46:25.806   781  1001 I art     : Starting a blocking GC Explicit
,08-30 02:46:25.816   781  1640 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-30 02:46:25.816  6880  6880 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 02:46:25.816  6880  6880 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-30 02:46:25.826  6880  6880 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
08-30 02:46:25.826  6880  6880 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-30 02:46:25.826  6880  6880 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-30 02:46:25.836  6880  6880 D AndroidRuntime: Shutting down VM
,08-30 02:46:25.836  6880  6880 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:46:25.836  6880  6880 E AndroidRuntime: Process: com.test.thalitest, PID: 6880
08-30 02:46:25.836  6880  6880 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-30 02:46:25.836  6880  6880 E AndroidRuntime: 	... 9 more
,08-30 02:46:25.846  6880  6880 I Process : Sending signal. PID: 6880 SIG: 9
,08-30 02:46:25.856   781   860 I ActivityManager: Start proc 6905:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-30 02:46:25.856  6905  6905 E Zygote  : v2
08-30 02:46:25.856  6905  6905 I libpersona: KNOX_SDCARD checking this for 1000
08-30 02:46:25.856  6905  6905 I libpersona: KNOX_SDCARD not a persona
08-30 02:46:25.856  6905  6905 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 02:46:25.856  6905  6905 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 02:46:25.856  6905  6905 E Zygote  : accessInfo : 0
,08-30 02:46:25.866   781  1734 I ActivityManager: Process com.test.thalitest (pid 6880)(adj 9) has died(164,717)
,08-30 02:46:25.866   781  1734 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 02:46:25.866   781  1734 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 02:46:25.866   781  1734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26698 com.android.server.am.ActivityManagerService.appDiedLocked:7560 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-30 02:46:25.866   781   860 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
08-30 02:46:25.866   781   860 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-30 02:46:25.886  6905  6905 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 02:46:25.886  6905  6905 D ActivityThread: Added TimaKeyStore provider
,08-30 02:46:25.886   781  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9901826 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d1a0c67 6905:com.samsung.android.sm/1000}
,08-30 02:46:25.896  6905  6905 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-30 02:46:25.926  6905  6905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-30 02:46:25.936   781  1175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9901826 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{676398 4531:com.google.android.gms/u0a11}
,08-30 02:46:25.956   781  1001 I art     : Explicit concurrent mark sweep GC freed 98664(5MB) AllocSpace objects, 20(400KB) LOS objects, 27% free, 42MB/58MB, paused 1.748ms total 146.591ms
,08-30 02:46:25.976   781  1001 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 02:46:25.976   781  1001 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-30 02:46:25.976   781  1001 D AASAinstall: there is not AASApackages.xml file
,08-30 02:46:25.976   781  1001 D PackageManager: result of delete: 1{225193832}
,08-30 02:46:25.986  6871  6871 I art     : System.exit called, status: 0
08-30 02:46:25.986  6871  6871 I AndroidRuntime: VM exiting with result code 0.
,08-30 02:46:25.986   781  1001 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 02:46:25.986   781  1001 D PackageManager: userId{-1}
08-30 02:46:25.986   781  1001 D PackageManager: andCode{true}
,08-30 02:46:25.996   781  1001 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-30 02:46:26.006  6166  6921 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-30 02:46:26.006  6166  6921 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 02:46:26.006  6166  6921 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-30 02:46:26.046   781   781 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.046  1374  1374 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-30 02:46:26.046  1374  1374 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-30 02:46:26.046   781   781 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.056   781   923 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.056   781   923 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.056   781  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 02:46:26.056   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066  2018  2018 E SamsungIME: mOCRHelper is null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.066   781   856 W System.err: remove failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml.bak
08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.066   781   781 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.076   781   781 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.076   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.076   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.076   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.076   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.076   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.086  2112  2414 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 02:46:26.086  1712  1712 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 02:46:26.096   781   860 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{edc03dc u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f94c814 4422:com.samsung.klmsagent/u0a18}
08-30 02:46:26.096   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.096   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.096   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.096   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.096   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.096   781   781 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.106  4422  4422 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 30 02:46:26 GMT+02:00 2016
,08-30 02:46:26.106  4531  6919 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-30 02:46:26.106   781   781 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.106   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.106   781   856 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.116   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.116   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.116   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.116  4422  4422 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
08-30 02:46:26.116   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.126   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.126  3305  3324 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-30 02:46:26.126   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.126  3305  3324 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 02:46:26.126  4422  4422 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-30 02:46:26.126  3305  3324 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 02:46:26.126  3305  3324 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 02:46:26.126  4422  4422 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 02:46:26.126   781  1621 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-30 02:46:26.126  4422  4422 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 02:46:26.126  4422  6931 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-30 02:46:26.126  4422  6931 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-30 02:46:26.126   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.126   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136  4422  6931 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-30 02:46:26.136  4422  6931 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-30 02:46:26.136  4422  6931 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-30 02:46:26.136  4422  6931 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.136   781  1745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{edc03dc u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{186a18 781:system/1000}
,08-30 02:46:26.136   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146  4422  6931 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146  4422  6931 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.146   781   781 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.156  1701  6933 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-30 02:46:26.156  1701  6933 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-30 02:46:26.156  1701  6933 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-30 02:46:26.156  1701  6933 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-30 02:46:26.156  1701  6933 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 02:46:26.156   781   781 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.156   781   781 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.156   781  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/167_task.xml
,08-30 02:46:26.156   781   781 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.156   781   781 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-30 02:46:26.156   781  1320 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-30 02:46:26.156   781  1319 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-30 02:46:26.156   781  1320 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-30 02:46:26.156   781  1319 V NetworkStats: performPollLocked(flags=0x3)
,08-30 02:46:26.156   781  1319 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 02:46:26.166  4422  6931 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7285ddde in tid 6931 (IntentService[K)
,08-30 02:46:26.166   781  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/167_task_thumbnail.png
,08-30 02:46:26.166  2548  2548 E audit_log: File locking failed. error= Bad file descriptor
,08-30 02:46:26.166  2548  2548 E audit_log: File locking failed. error= Bad file descriptor
,08-30 02:46:26.166   781  1319 V NetworkStats: performPollLocked() took 9ms
,08-30 02:46:26.166   781  1319 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 02:46:26.176   781   781 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-30 02:46:26.176   781  1295 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-30 02:46:26.176   781  1319 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ce7ad13 in tid 1319 (NetworkStats)
,08-30 02:46:26.176   781  1319 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 02:46:26.176  2548  2548 E audit_log: File locking failed. error= Bad file descriptor
,08-30 02:46:26.206   347   347 I Zygote  : Process 4422 exited due to signal (7)
,08-30 02:46:26.546   292   547 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
