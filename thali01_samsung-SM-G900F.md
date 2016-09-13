#### Test 836273370459b7a_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
09-13 16:33:51.432   758  3478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
09-13 16:33:52.502  2379  2379 E audit   : type=1400 msg=audit(1473777232.492:284): avc:  denied  { execmod } for  pid=6238 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 16:33:52.502  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:52.502  2379  2379 E audit   : type=1300 msg=audit(1473777232.492:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3595 ppcomm=adbd pid=6238 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 16:33:52.502  2379  2379 E audit   : type=1327 msg=audit(1473777232.492:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 16:33:52.502  2379  2379 E audit   : type=1320 msg=audit(1473777232.492:284): 
09-13 16:33:52.562  2379  2379 E audit   : type=1400 msg=audit(1473777232.562:285): avc:  denied  { execmod } for  pid=6238 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 16:33:52.562  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:52.562  2379  2379 E audit   : type=1300 msg=audit(1473777232.562:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8c000 a1=51000 a2=5 a3=4 items=0 ppid=3595 ppcomm=adbd pid=6238 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 16:33:52.562  2379  2379 E audit   : type=1327 msg=audit(1473777232.562:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 16:33:52.562  2379  2379 E audit   : type=1320 msg=audit(1473777232.562:285): 
09-13 16:33:52.622  6238  6238 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 16:33:52.632  6238  6238 D AndroidRuntime: CheckJNI is OFF
09-13 16:33:52.632  6238  6238 D AndroidRuntime: readGMSProperty: start
09-13 16:33:52.632  6238  6238 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:33:52.632  6238  6238 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:33:52.632  6238  6238 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:33:52.632  6238  6238 D AndroidRuntime: readGMSProperty: end
09-13 16:33:52.632  6238  6238 D AndroidRuntime: addProductProperty: start
09-13 16:33:52.632  6238  6238 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 16:33:52.632  6238  6238 W art     : aedf3000-b1d19000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
09-13 16:33:52.632  6238  6238 W art     : b1d19000-b3f88000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
09-13 16:33:52.632  6238  6238 W art     : b3f88000-b3f89000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
09-13 16:33:52.632  6238  6238 W art     : b3f89000-b3f8a000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.632  6238  6238 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 16:33:52.632  6238  6238 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 946        /system/lib/libart.so
09-13 16:33:52.632  6238  6238 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b4733000-b473d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
09-13 16:33:52.632  6238  6238 W art     : b473d000-b473e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
09-13 16:33:52.632  6238  6238 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
09-13 16:33:52.632  6238  6238 W art     : b485f000-b4862000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
09-13 16:33:52.632  6238  6238 W art     : b4862000-b4863000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
09-13 16:33:52.632  6238  6238 W art     : b4863000-b4864000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
09-13 16:33:52.632  6238  6238 W art     : b4864000-b4865000 r--p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b4865000-b4885000 r--s 00000000 00:0b 9219       /dev/__properties__
09-13 16:33:52.632  6238  6238 W art     : b4885000-b5296000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
09-13 16:33:52.632  6238  6238 W art     : b5296000-b5297000 ---p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b5297000-b52e0000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
09-13 16:33:52.632  6238  6238 W art     : b52e0000-b52e1000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
09-13 16:33:52.632  6238  6238 W art     : b52e1000-b52e9000 rw-p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b52e9000-b531e000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
09-13 16:33:52.632  6238  6238 W art     : b531e000-b531f000 ---p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b531f000-b5320000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
09-13 16:33:52.632  6238  6238 W art     : b5320000-b5321000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
09-13 16:33:52.632  6238  6238 W art     : b5321000-b5379000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
09-13 16:33:52.632  6238  6238 W art     : b5379000-b537a000 ---p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b537a000-b537b000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
09-13 16:33:52.632  6238  6238 W art     : b537b000-b537c000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
09-13 16:33:52.632  6238  6238 W art     : b537d000-b5383000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
09-13 16:33:52.632  6238  6238 W art     : AD_v01009.so
09-13 16:33:52.632  6238  6238 W art     : b5383000-b5384000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 16:33:52.632  6238  6238 W art     : b5384000-b5385000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 16:33:52.632  6238  6238 W art     : b5385000-b5387000 rw-p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b5388000-b5392000 r-xp 00000000 b3:17 1088 
09-13 16:33:52.632  6238  6238 W art     :       /system/lib/libcommon_time_client.so
09-13 16:33:52.632  6238  6238 W art     : b5392000-b5395000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 16:33:52.632  6238  6238 W art     : b5395000-b5396000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 16:33:52.632  6238  6238 W art     : b5397000-b53ae000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 16:33:52.632  6238  6238 W art     : b53ae000-b53af000 ---p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b53af000-b53b0000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 16:33:52.632  6238  6238 W art     : b53b0000-b53b1000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 16:33:52.632  6238  6238 W art     : b53b2000-b53bc000 r-xp 00000000 b3:17 2671   
09-13 16:33:52.632  6238  6238 W art     :     /system/lib/libsec_km.so
09-13 16:33:52.632  6238  6238 W art     : b53bc000-b53bd000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
09-13 16:33:52.632  6238  6238 W art     : b53bd000-b53be000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
09-13 16:33:52.632  6238  6238 W art     : b53be000-b53c2000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 16:33:52.632  6238  6238 W art     : b53c2000-b53c3000 r--p 00003000 b
09-13 16:33:52.632  6238  6238 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
09-13 16:33:52.632  6238  6238 W art     : b53c3000-b53c4000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 16:33:52.632  6238  6238 W art     : b53c4000-b53da000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
09-13 16:33:52.632  6238  6238 W art     : b53da000-b53db000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
09-13 16:33:52.632  6238  6238 W art     : b53db000-b53dc000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
09-13 16:33:52.632  6238  6238 W art     : b53dc000-b53e9000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
09-13 16:33:52.632  6238  6238 W art     : b53e9000-b53ea000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
09-13 16:33:52.632  6238  6238 W art     : b53ea000-b53eb000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
09-13 16:33:52.632  6238  6238 W art     : b53eb000-b544b000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
09-13 16:33:52.632  6238  6238 W art     : b544b000-b544e000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
09-13 16:33:52.632  6238  6238 W art     : b544e000-b5452000 rw-p 00000000 00:00 0 
09-13 16:33:52.632  6238  6238 W art     : b5452000-b54b3000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
09-13 16:33:52.632  6238  6238 W art     : b54b3000-b54b4000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
09-13 16:33:52.642  6238  6238 W art     : b54b4000-b5503000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
09-13 16:33:52.642  6238  6238 W art     : b5503000-b5505000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
09-13 16:33:52.642  6238  6238 W art     : b5505000-b5506000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
09-13 16:33:52.642  6238  6238 W art     : b5506000-b5507000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5507000-b550e000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 16:33:52.642  6238  6238 W art     : b550e000-b550f000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 16:33:52.642  6238  6238 W art     : b550f000-b5510000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
09-13 16:33:52.642  6238  6238 W art     : avc_common.so
09-13 16:33:52.642  6238  6238 W art     : b5511000-b5514000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 16:33:52.642  6238  6238 W art     : b5514000-b5515000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 16:33:52.642  6238  6238 W art     : b5515000-b5516000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
09-13 16:33:52.642  6238  6238 W art     : enc_common.so
09-13 16:33:52.642  6238  6238 W art     : b5517000-b551b000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
09-13 16:33:52.642  2379  2379 E audit   : type=1400 msg=audit(1473777232.622:286): avc:  denied  { execmod } for  pid=6238 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 16:33:52.642  6238  6238 W art     : b551b000-b551c000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b551c000-b551d000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
09-13 16:33:52.642  6238  6238 W art     : b551d000-b551e000 rw-p 00005000 b3:17 2510       /syste
09-13 16:33:52.642  6238  6238 W art     : m/lib/libpowermanager.so
09-13 16:33:52.642  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:52.642  6238  6238 W art     : b551f000-b553c000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 16:33:52.642  6238  6238 W art     : b553c000-b553d000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 16:33:52.642  6238  6238 W art     : b553d000-b553e000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 16:33:52.642  6238  6238 W art     : b553f000-b5544000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 16:33:52.642  6238  6238 W art     : b5544000-b5545000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 16:33:52.642  6238  6238 W art     : b5545000-b5546000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 16:33:52.642  6238  6238 W art     : b5547000-b5578000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 16:33:52.642  2379  2379 E audit   : type=1300 msg=audit(1473777232.622:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8c000 a1=51000 a2=5 a3=4 items=0 ppid=3595 ppcomm=adbd pid=6238 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 16:33:52.642  6238  6238 W art     : b5578000-b5579000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5579000-b557c000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 16:33:52.642  6238  6238 W art     : b557c000-b557d000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 16:33:52.642  6238  6238 W art     : b557e000-b55b9000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
09-13 16:33:52.642  6238  6238 W art     : b55b9000-b55ba000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
09-13 16:33:52.642  2379  2379 E audit   : type=1327 msg=audit(1473777232.622:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 16:33:52.642  6238  6238 W art     : b55ba000-b55bb000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
09-13 16:33:52.642  6238  6238 W art     : b55bc000-b55c3000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
09-13 16:33:52.642  6238  6238 W art     : b55c3000-b55c4000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b55c4000-b55c5000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
09-13 16:33:52.642  6238  6238 W art     : b55c5000-b55c6000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
09-13 16:33:52.642  6238  6238 W art     : b55c6000-b55c7000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b55c7000-b55de000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
09-13 16:33:52.642  2379  2379 E audit   : type=1320 msg=audit(1473777232.622:286): 
09-13 16:33:52.642  6238  6238 W art     : b55de000-b55df000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b55df000-b55e2000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
09-13 16:33:52.642  6238  6238 W art     : b55e2000-b55e3000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
09-13 16:33:52.642  6238  6238 W art     : b55e3000-b5602000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
09-13 16:33:52.642  6238  6238 W art     : b5602000-b5603000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
09-13 16:33:52.642  6238  6238 W art     : b5603000-b5604000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
09-13 16:33:52.642  6238  6238 W art     : b5604000-b5642000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
09-13 16:33:52.642  6238  6238 W art     : b5642000-b5643000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5643000-b5645000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
09-13 16:33:52.642  6238  6238 W art     : b5645000-b5646000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
09-13 16:33:52.642  6238  6238 W art     : b5647000-b564e000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 16:33:52.642  6238  6238 W art     : b564e000-b564f000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 16:33:52.642  6238  6238 W art     : b564f000-b5650000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 16:33:52.642  6238  6238 W art     : b5651000-b5654000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 16:33:52.642  6238  6238 W art     : b5654000-b5655000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 16:33:52.642  6238  6238 W art     : b5655000-b5656000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 16:33:52.642  6238  6238 W art     : b5656000-b565c000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 16:33:52.642  6238  6238 W art     : b565c000-b565d000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b565d000-b565e000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 16:33:52.642  6238  6238 W art     : b565e000-b565f000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 16:33:52.642  6238  6238 W art     : b565f000-b5668000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
09-13 16:33:52.642  6238  6238 W art     : b5668000-b5669000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
09-13 16:33:52.642  6238  6238 W art     : b5669000-b566a000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
09-13 16:33:52.642  6238  6238 W art     : b566a000-b56fb000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 16:33:52.642  6238  6238 W art     : b56fb000-b56fc000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b56fc000-b5707000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 16:33:52.642  6238  6238 W art     : b5707000-b5708000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 16:33:52.642  6238  6238 W art     : b5709000-b571b000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
09-13 16:33:52.642  6238  6238 W art     : b571b000-b571c000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
09-13 16:33:52.642  6238  6238 W art     : b571c000-b571d000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
09-13 16:33:52.642  6238  6238 W art     : b571e000-b5723000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
09-13 16:33:52.642  6238  6238 W art     : b5723000-b5724000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
09-13 16:33:52.642  6238  6238 W art     : b5724000-b5725000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
09-13 16:33:52.642  6238  6238 W art     : b5726000-b5793000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
09-13 16:33:52.642  6238  6238 W art     : b5793000-b5794000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5794000-b5796000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
09-13 16:33:52.642  6238  6238 W art     : b5796000-b5797000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
09-13 16:33:52.642  6238  6238 W art     : b5797000-b5798000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5798000-b579f000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 16:33:52.642  6238  6238 W art     : b579f000-b57a0000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 16:33:52.642  6238  6238 W art     : b57a0000-b57a1000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 16:33:52.642  6238  6238 W art     : b57a2000-b5822000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 16:33:52.642  6238  6238 W art     : b5822000-b5823000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5823000-b5824000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 16:33:52.642  6238  6238 W art     : b5824000-b5825000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 16:33:52.642  6238  6238 W art     : b5825000-b583c000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b583c000-b5873000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 16:33:52.642  6238  6238 W art     : b5873000-b5874000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 16:33:52.642  6238  6238 W art     : b5874000-b5875000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 16:33:52.642  6238  6238 W art     : b5875000-b5891000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 16:33:52.642  6238  6238 W art     : b5891000-b5892000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 16:33:52.642  6238  6238 W art     : b5892000-b5893000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 16:33:52.642  6238  6238 W art     : b5894000-b58f5000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
09-13 16:33:52.642  6238  6238 W art     : b58f5000-b58f7000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
09-13 16:33:52.642  6238  6238 W art     : b58f7000-b58f8000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
09-13 16:33:52.642  6238  6238 W art     : b58f9000-b591e000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
09-13 16:33:52.642  6238  6238 W art     : b591e000-b591f000 r--p 00024000 b3:17 126        /system/lib/libpng.so
09-13 16:33:52.642  6238  6238 W art     : b591f000-b5920000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
09-13 16:33:52.642  6238  6238 W art     : b5921000-b5929000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 16:33:52.642  6238  6238 W art     : b5929000-b592b000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 16:33:52.642  6238  6238 W art     : b592b000-b592c000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 16:33:52.642  6238  6238 W art     : b592d000-b5930000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
09-13 16:33:52.642  6238  6238 W art     : b5930000-b5931000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
09-13 16:33:52.642  6238  6238 W art     : b5931000-b5932000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
09-13 16:33:52.642  6238  6238 W art     : b5932000-b5936000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
09-13 16:33:52.642  6238  6238 W art     : b5936000-b5937000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5937000-b5938000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
09-13 16:33:52.642  6238  6238 W art     : b5938000-b5939000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
09-13 16:33:52.642  6238  6238 W art     : b5939000-b5949000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
09-13 16:33:52.642  6238  6238 W art     : b5949000-b594a000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
09-13 16:33:52.642  6238  6238 W art     : b594a000-b594b000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
09-13 16:33:52.642  6238  6238 W art     : b594b000-b5991000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5991000-b599a000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
09-13 16:33:52.642  6238  6238 W art     : b599a000-b599b000 r--p 00008000 b3:17 982        /system/lib/libbase.so
09-13 16:33:52.642  6238  6238 W art     : b599b000-b599c000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
09-13 16:33:52.642  6238  6238 W art     : b599d000-b59a2000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
09-13 16:33:52.642  6238  6238 W art     : b59a2000-b59a3000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
09-13 16:33:52.642  6238  6238 W art     : b59a3000-b59a4000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
09-13 16:33:52.642  6238  6238 W art     : b59a4000-b59a7000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 16:33:52.642  6238  6238 W art     : b59a7000-b59a8000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b59a8000-b59a9000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 16:33:52.642  6238  6238 W art     : b59a9000-b59aa000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 16:33:52.642  6238  6238 W art     : b59ab000-b59c3000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
09-13 16:33:52.642  6238  6238 W art     : ght_foundation.so
09-13 16:33:52.642  6238  6238 W art     : b59c3000-b59c4000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b59c4000-b59c5000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 16:33:52.642  6238  6238 W art     : b59c5000-b59c6000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 16:33:52.642  6238  6238 W art     : b59c6000-b59c7000 rw-p 00000000 00:
09-13 16:33:52.642  6238  6238 W art     : 00 0          [anon:linker_alloc_vector]
09-13 16:33:52.642  6238  6238 W art     : b59c7000-b5b61000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
09-13 16:33:52.642  6238  6238 W art     : b5b61000-b5b62000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5b62000-b5b6f000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
09-13 16:33:52.642  6238  6238 W art     : b5b6f000-b5b70000 rw-p 001a7000 b3:17 604        /system/
09-13 16:33:52.642  6238  6238 W art     : lib/libstagefright.so
09-13 16:33:52.642  6238  6238 W art     : b5b70000-b5b74000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
09-13 16:33:52.642  6238  6238 W art     : b5b74000-b5b75000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5b75000-b5b76000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
09-13 16:33:52.642  6238  6238 W art     : b5b76000-b5b77000 rw-p 00005000 b3:17 2676       /system/lib/libp
09-13 16:33:52.642  6238  6238 W art     : ersona.so
09-13 16:33:52.642  6238  6238 W art     : b5b77000-b5b8a000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
09-13 16:33:52.642  6238  6238 W art     : b5b8a000-b5b8b000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
09-13 16:33:52.642  6238  6238 W art     : b5b8b000-b5b8c000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
09-13 16:33:52.642  6238  6238 W art     : b5b8d000-b5bd8000 r
09-13 16:33:52.642  6238  6238 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
09-13 16:33:52.642  6238  6238 W art     : b5bd8000-b5bd9000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
09-13 16:33:52.642  6238  6238 W art     : b5bd9000-b5bda000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
09-13 16:33:52.642  6238  6238 W art     : b5bda000-b5bdc000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5bdd000-b5bee000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 16:33:52.642  6238  6238 W art     : b5bee000-b5bef000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5bef000-b5bf0000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 16:33:52.642  6238  6238 W art     : b5bf0000-b5bf1000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 16:33:52.642  6238  6238 W art     : b5bf1000-b5bf2000 r--p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5bf2000-b5bfc000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
09-13 16:33:52.642  6238  6238 W art     : b5bfc000-b5bfe000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
09-13 16:33:52.642  6238  6238 W art     : b5bfe000-b5bff000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
09-13 16:33:52.642  6238  6238 W art     : b5bff000-b5c18000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
09-13 16:33:52.642  6238  6238 W art     : b5c18000-b5c19000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
09-13 16:33:52.642  6238  6238 W art     : b5c19000-b5c1c000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
09-13 16:33:52.642  6238  6238 W art     : b5c1c000-b5c20000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5c20000-b5c94000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
09-13 16:33:52.642  6238  6238 W art     : b5c94000-b5c95000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5c95000-b5c98000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
09-13 16:33:52.642  6238  6238 W art     : b5c98000-b5c99000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
09-13 16:33:52.642  6238  6238 W art     : b5c99000-b5c9a000 r--p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5c9a000-b5c9d000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
09-13 16:33:52.642  6238  6238 W art     : b5c9d000-b5c9e000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
09-13 16:33:52.642  6238  6238 W art     : b5c9e000-b5c9f000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
09-13 16:33:52.642  6238  6238 W art     : b5c9f000-b5ca0000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5ca0000-b5ca5000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 16:33:52.642  6238  6238 W art     : b5ca5000-b5ca6000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 16:33:52.642  6238  6238 W art     : b5ca6000-b5ca7000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 16:33:52.642  6238  6238 W art     : b5ca7000-b5ca8000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5ca8000-b5cab000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 16:33:52.642  6238  6238 W art     : b5cab000-b5cac000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 16:33:52.642  6238  6238 W art     : b5cac000-b5cad000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 16:33:52.642  6238  6238 W art     : b5cad000-b5cae000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:33:52.642  6238  6238 W art     : b5cae000-b5cb2000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
09-13 16:33:52.642  6238  6238 W art     : b5cb2000-b5cb3000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
09-13 16:33:52.642  6238  6238 W art     : b5cb3000-b5cb4000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
09-13 16:33:52.642  6238  6238 W art     : b5cb4000-b5cb5000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5cb5000-b5cb9000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 16:33:52.642  6238  6238 W art     : b5cb9000-b5cba000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 16:33:52.642  6238  6238 W art     : b5cba000-b5cbb000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 16:33:52.642  6238  6238 W art     : b5cbb000-b5cbc000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5cbc000-b5cca000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
09-13 16:33:52.642  6238  6238 W art     : b5cca000-b5ccb000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b5ccb000-b5ccc000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
09-13 16:33:52.642  6238  6238 W art     : b5ccc000-b5ccd000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
09-13 16:33:52.642  6238  6238 W art     : b5ccd000-b5cd7000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 16:33:52.642  6238  6238 W art     : b5cd7000-b5cda000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 16:33:52.642  6238  6238 W art     : b5cda000-b5cdb000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 16:33:52.642  6238  6238 W art     : b5cdb000-b5cdc000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5cdc000-b5ce6000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
09-13 16:33:52.642  6238  6238 W art     : b5ce6000-b5ce9000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
09-13 16:33:52.642  6238  6238 W art     : b5ce9000-b5cea000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
09-13 16:33:52.642  6238  6238 W art     : b5cea000-b5cee000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
09-13 16:33:52.642  6238  6238 W art     : b5cee000-b5cef000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
09-13 16:33:52.642  6238  6238 W art     : b5cef000-b5cf0000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
09-13 16:33:52.642  6238  6238 W art     : b5cf0000-b5cf1000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b5cf1000-b5cfe000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
09-13 16:33:52.642  6238  6238 W art     : b5cfe000-b5d00000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
09-13 16:33:52.642  6238  6238 W art     : b5d00000-b5d01000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
09-13 16:33:52.642  6238  6238 W art     : b5d01000-b6113000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
09-13 16:33:52.642  6238  6238 W art     : b6113000-b6114000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6114000-b611d000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
09-13 16:33:52.642  6238  6238 W art     : b611d000-b6121000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
09-13 16:33:52.642  6238  6238 W art     : b6121000-b6122000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6122000-b6129000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
09-13 16:33:52.642  6238  6238 W art     : b6129000-b612a000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
09-13 16:33:52.642  6238  6238 W art     : b612a000-b612b000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
09-13 16:33:52.642  6238  6238 W art     : b612b000-b612c000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b612c000-b6147000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
09-13 16:33:52.642  6238  6238 W art     : b6147000-b6148000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
09-13 16:33:52.642  6238  6238 W art     : b6148000-b6149000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
09-13 16:33:52.642  6238  6238 W art     : b6149000-b614a000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b614a000-b6196000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 16:33:52.642  6238  6238 W art     : b6196000-b6197000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6197000-b6198000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 16:33:52.642  6238  6238 W art     : b6198000-b6199000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 16:33:52.642  6238  6238 W art     : b6199000-b619a000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b619a000-b619e000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
09-13 16:33:52.642  6238  6238 W art     : b619e000-b619f000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b619f000-b61a0000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
09-13 16:33:52.642  6238  6238 W art     : b61a0000-b61a1000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
09-13 16:33:52.642  6238  6238 W art     : b61a1000-b61d9000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
09-13 16:33:52.642  6238  6238 W art     : b61d9000-b61da000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
09-13 16:33:52.642  6238  6238 W art     : b61da000-b61db000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
09-13 16:33:52.642  6238  6238 W art     : b61db000-b61dc000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b61dc000-b627b000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
09-13 16:33:52.642  6238  6238 W art     : b627b000-b6299000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
09-13 16:33:52.642  6238  6238 W art     : b6299000-b629a000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
09-13 16:33:52.642  6238  6238 W art     : b629a000-b640d000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
09-13 16:33:52.642  6238  6238 W art     : b640d000-b6418000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
09-13 16:33:52.642  6238  6238 W art     : b6418000-b6419000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
09-13 16:33:52.642  6238  6238 W art     : b6419000-b6530000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
09-13 16:33:52.642  6238  6238 W art     : b6530000-b653b000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
09-13 16:33:52.642  6238  6238 W art     : b653b000-b653c000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
09-13 16:33:52.642  6238  6238 W art     : b653c000-b6540000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6540000-b6564000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
09-13 16:33:52.642  6238  6238 W art     : b6564000-b6566000 r--p 00023000 b3:17 400        /system/lib/libssl.so
09-13 16:33:52.642  6238  6238 W art     : b6566000-b6567000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
09-13 16:33:52.642  6238  6238 W art     : b6567000-b660d000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
09-13 16:33:52.642  6238  6238 W art     : b660d000-b661a000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
09-13 16:33:52.642  6238  6238 W art     : b661a000-b661b000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
09-13 16:33:52.642  6238  6238 W art     : b661b000-b661c000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b661c000-b666f000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
09-13 16:33:52.642  6238  6238 W art     : b666f000-b6670000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6670000-b6671000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
09-13 16:33:52.642  6238  6238 W art     : b6671000-b6672000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
09-13 16:33:52.642  6238  6238 W art     : b6672000-b6677000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6677000-b6689000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
09-13 16:33:52.642  6238  6238 W art     : b6689000-b668a000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b668a000-b668b000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
09-13 16:33:52.642  6238  6238 W art     : b668b000-b668c000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
09-13 16:33:52.642  6238  6238 W art     : b668c000-b6693000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 16:33:52.642  6238  6238 W art     : b6693000-b6694000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 16:33:52.642  6238  6238 W art     : b6694000-b6695000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 16:33:52.642  6238  6238 W art     : b6695000-b6696000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6696000-b6699000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
09-13 16:33:52.642  6238  6238 W art     : b6699000-b669a000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
09-13 16:33:52.642  6238  6238 W art     : b669a000-b669b000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
09-13 16:33:52.642  6238  6238 W art     : b669b000-b669f000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
09-13 16:33:52.642  6238  6238 W art     : b669f000-b66a0000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
09-13 16:33:52.642  6238  6238 W art     : b66a0000-b66a1000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
09-13 16:33:52.642  6238  6238 W art     : b66a1000-b66af000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
09-13 16:33:52.642  6238  6238 W art     : b66af000-b66b0000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b66b0000-b66b1000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
09-13 16:33:52.642  6238  6238 W art     : b66b1000-b66b2000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
09-13 16:33:52.642  6238  6238 W art     : b66b2000-b66bb000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 16:33:52.642  6238  6238 W art     : b66bb000-b66bc000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 16:33:52.642  6238  6238 W art     : b66bc000-b66bd000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 16:33:52.642  6238  6238 W art     : b66bd000-b6723000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
09-13 16:33:52.642  6238  6238 W art     : b6723000-b6724000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6724000-b6726000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
09-13 16:33:52.642  6238  6238 W art     : b6726000-b672f000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
09-13 16:33:52.642  6238  6238 W art     : b672f000-b6732000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6732000-b67c9000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
09-13 16:33:52.642  6238  6238 W art     : b67c9000-b67cb000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
09-13 16:33:52.642  6238  6238 W art     : b67cb000-b67cc000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
09-13 16:33:52.642  6238  6238 W art     : b67cc000-b67cd000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b67cd000-b6aeb000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
09-13 16:33:52.642  6238  6238 W art     : b6aeb000-b6aec000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6aec000-b6b07000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
09-13 16:33:52.642  6238  6238 W art     : b6b07000-b6b0b000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
09-13 16:33:52.642  6238  6238 W art     : b6b0b000-b6b10000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6b10000-b6b18000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 16:33:52.642  6238  6238 W art     : b6b18000-b6b19000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 16:33:52.642  6238  6238 W art     : b6b19000-b6b1a000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 16:33:52.642  6238  6238 W art     : b6b1a000-b6b48000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
09-13 16:33:52.642  6238  6238 W art     : b6b48000-b6b49000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6b49000-b6b50000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
09-13 16:33:52.642  6238  6238 W art     : b6b50000-b6b51000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
09-13 16:33:52.642  6238  6238 W art     : b6b51000-b6b97000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
09-13 16:33:52.642  6238  6238 W art     : b6b97000-b6b98000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6b98000-b6b9b000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
09-13 16:33:52.642  6238  6238 W art     : b6b9b000-b6b9c000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
09-13 16:33:52.642  6238  6238 W art     : b6b9c000-b6bb7000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
09-13 16:33:52.642  6238  6238 W art     : b6bb7000-b6bbb000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
09-13 16:33:52.642  6238  6238 W art     : b6bbb000-b6bbc000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
09-13 16:33:52.642  6238  6238 W art     : b6bbc000-b6c09000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
09-13 16:33:52.642  6238  6238 W art     : b6c09000-b6c0a000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6c0a000-b6c16000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
09-13 16:33:52.642  6238  6238 W art     : b6c16000-b6c17000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
09-13 16:33:52.642  6238  6238 W art     : b6c17000-b6c24000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
09-13 16:33:52.642  6238  6238 W art     : b6c24000-b6c25000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6c25000-b6c26000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
09-13 16:33:52.642  6238  6238 W art     : b6c26000-b6c27000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
09-13 16:33:52.642  6238  6238 W art     : b6c27000-b6c2f000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
09-13 16:33:52.642  6238  6238 W art     : b6c2f000-b6c30000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6c30000-b6c31000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
09-13 16:33:52.642  6238  6238 W art     : b6c31000-b6c32000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
09-13 16:33:52.642  6238  6238 W art     : b6c32000-b6c39000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
09-13 16:33:52.642  6238  6238 W art     : b6c39000-b6c3a000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
09-13 16:33:52.642  6238  6238 W art     : b6c3a000-b6c3b000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
09-13 16:33:52.642  6238  6238 W art     : b6c3b000-b6c4f000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
09-13 16:33:52.642  6238  6238 W art     : b6c4f000-b6c51000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
09-13 16:33:52.642  6238  6238 W art     : b6c51000-b6c52000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
09-13 16:33:52.642  6238  6238 W art     : b6c52000-b6c7a000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
09-13 16:33:52.642  6238  6238 W art     : b6c7a000-b6c7c000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
09-13 16:33:52.642  6238  6238 W art     : b6c7c000-b6c7d000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
09-13 16:33:52.642  6238  6238 W art     : b6c7d000-b6c80000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
09-13 16:33:52.642  6238  6238 W art     : b6c80000-b6c81000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
09-13 16:33:52.642  6238  6238 W art     : b6c81000-b6c82000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
09-13 16:33:52.642  6238  6238 W art     : b6c82000-b6c8b000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
09-13 16:33:52.642  6238  6238 W art     : b6c8b000-b6c8c000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
09-13 16:33:52.642  6238  6238 W art     : b6c8c000-b6c8d000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
09-13 16:33:52.642  6238  6238 W art     : b6c8d000-b6cad000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
09-13 16:33:52.642  6238  6238 W art     : b6cad000-b6cae000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
09-13 16:33:52.642  6238  6238 W art     : b6cae000-b6caf000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
09-13 16:33:52.642  6238  6238 W art     : b6caf000-b6d22000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
09-13 16:33:52.642  6238  6238 W art     : b6d22000-b6d26000 r--p 00072000 b3:17 1016       /system/lib/libc.so
09-13 16:33:52.642  6238  6238 W art     : b6d26000-b6d29000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
09-13 16:33:52.642  6238  6238 W art     : b6d29000-b6d33000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6d33000-b6dbb000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
09-13 16:33:52.642  6238  6238 W art     : b6dbb000-b6dbc000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6dbc000-b6dc0000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
09-13 16:33:52.642  6238  6238 W art     : b6dc0000-b6dc1000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
09-13 16:33:52.642  6238  6238 W art     : b6dc1000-b6dc2000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6dc2000-b6deb000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
09-13 16:33:52.642  6238  6238 W art     : b6deb000-b6dec000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6dec000-b6def000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
09-13 16:33:52.642  6238  6238 W art     : b6def000-b6df0000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
09-13 16:33:52.642  6238  6238 W art     : b6df0000-b6eca000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 16:33:52.642  6238  6238 W art     : b6eca000-b6ed1000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 16:33:52.642  6238  6238 W art     : b6ed1000-b6ed9000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 16:33:52.642  6238  6238 W art     : b6ed9000-b6eda000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6eda000-b6edb000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:33:52.642  6238  6238 W art     : b6edb000-b6edc000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
09-13 16:33:52.642  6238  6238 W art     : b6edc000-b6edd000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b6edd000-b6ee0000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b6ee0000-b6f05000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
09-13 16:33:52.642  6238  6238 W art     : b6f05000-b6f06000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6f06000-b6f0d000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
09-13 16:33:52.642  6238  6238 W art     : b6f0d000-b6f0e000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
09-13 16:33:52.642  6238  6238 W art     : b6f0e000-b6f15000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
09-13 16:33:52.642  6238  6238 W art     : b6f15000-b6f16000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
09-13 16:33:52.642  6238  6238 W art     : b6f16000-b6f17000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
09-13 16:33:52.642  6238  6238 W art     : b6f17000-b6f18000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b6f18000-b6f30000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
09-13 16:33:52.642  6238  6238 W art     : b6f30000-b6f31000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6f31000-b6f32000 r--p 00018000 b3:17 918        /system/lib/libutils.so
09-13 16:33:52.642  6238  6238 W art     : b6f32000-b6f33000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
09-13 16:33:52.642  6238  6238 W art     : b6f33000-b6f41000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
09-13 16:33:52.642  6238  6238 W art     : b6f41000-b6f42000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6f42000-b6f43000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
09-13 16:33:52.642  6238  6238 W art     : b6f43000-b6f44000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
09-13 16:33:52.642  6238  6238 W art     : b6f44000-b6f45000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:33:52.642  6238  6238 W art     : b6f45000-b6f47000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b6f47000-b6f48000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b6f48000-b6f49000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:33:52.642  6238  6238 W art     : b6f49000-b6f4a000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
09-13 16:33:52.642  6238  6238 W art     : b6f4a000-b6f4b000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:33:52.642  6238  6238 W art     : b6f4b000-b6f6b000 r--s 00000000 00:0b 9219       /dev/__properties__
09-13 16:33:52.642  6238  6238 W art     : b6f6b000-b6f6c000 r--p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6f6c000-b6f6d000 ---p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6f6d000-b6f6f000 rw-p 00000000 00:00 0          [anon:thread signal stack]
09-13 16:33:52.642  6238  6238 W art     : b6f6f000-b6f70000 r-xp 00000000 00:00 0          [sigpage]
09-13 16:33:52.642  6238  6238 W art     : b6f70000-b6f8b000 r-xp 00000000 b3:17 341        /system/bin/linker
09-13 16:33:52.642  6238  6238 W art     : b6f8b000-b6f8c000 r--p 0001a000 b3:17 341        /system/bin/linker
09-13 16:33:52.642  6238  6238 W art     : b6f8c000-b6f8e000 rw-p 0001b000 b3:17 341        /system/bin/linker
09-13 16:33:52.642  6238  6238 W art     : b6f8e000-b6f90000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : b6f90000-b6f95000 r-xp 00000000 b3:17 978        /system/bin/app_process32
09-13 16:33:52.642  6238  6238 W art     : b6f95000-b6f96000 r--p 00004000 b3:17 978        /system/bin/app_process32
09-13 16:33:52.642  6238  6238 W art     : b6f96000-b6f97000 rw-p 00000000 00:00 0 
09-13 16:33:52.642  6238  6238 W art     : bed56000-bed77000 rw-p 00000000 00:00 0          [stack]
09-13 16:33:52.642  6238  6238 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
09-13 16:33:52.692  6238  6238 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 16:33:52.752  6238  6238 I Radio-JNI: register_android_hardware_Radio DONE
09-13 16:33:52.762  6238  6238 E AffinityControl: AffinityControl: registerfunction enter
09-13 16:33:52.792  6238  6238 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 16:33:52.802   758   774 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
09-13 16:33:52.812   758   774 D ActivityManager: mDVFSHelper.acquire()
09-13 16:33:52.812   758   774 V WindowManager: addAppToken: AppWindowToken{3a73118 token=Token{1d70cfb ActivityRecord{a9d2e8a u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
09-13 16:33:52.822   758   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3270b30 V.E...... R.....ID 0,0-0,0}
09-13 16:33:52.822   758   891 D SecWifiDisplayUtil: Metadata value : none
09-13 16:33:52.822   758   891 D ISSUE_DEBUG: InputChannelName : ffa8d2e Starting com.test.thalitest
09-13 16:33:52.832  6258  6258 E Zygote  : v2
09-13 16:33:52.832  6258  6258 I libpersona: KNOX_SDCARD checking this for 10004
09-13 16:33:52.832  6258  6258 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:52.832  6258  6258 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:52.832  6258  6258 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:52.832  6258  6258 E Zygote  : accessInfo : 0
09-13 16:33:52.832  6258  6258 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 16:33:52.842   758   774 I ActivityManager: Start proc 6258:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
09-13 16:33:52.842   758   774 D InputDispatcher: Focused application set to: xxxx
09-13 16:33:52.842   758   774 D InputDispatcher: Focus left window: 4503
09-13 16:33:52.842  6238  6238 D AndroidRuntime: Shutting down VM
09-13 16:33:52.842   758  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 16:33:52.852   758   852 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d213bda u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
09-13 16:33:52.852   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
09-13 16:33:52.852  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
09-13 16:33:52.872  6258  6258 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:52.872  6258  6258 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:52.872   758   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
09-13 16:33:52.872   758   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:33:52.872   758   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
09-13 16:33:52.872   758   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 16:33:52.872   758   891 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
09-13 16:33:52.872   758  2459 V WindowOrientationListener: setCurrentAppOrientation :-1
09-13 16:33:52.872   758  2459 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
09-13 16:33:52.892   758   852 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ffa8d2e u0 d0 Starting com.test.thalitest}
09-13 16:33:52.892  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
09-13 16:33:52.902   758  2459 D ActivityManager:  Launching com.test.thalitest, updated priority
09-13 16:33:52.912   758   891 V WindowStateAnimator: Finishing drawing window Window{ffa8d2e u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-13 16:33:52.912   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee0e364
09-13 16:33:52.932  1762  1892 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
09-13 16:33:52.932  1762  1762 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
09-13 16:33:52.932  4503  4503 V ActivityThread: updateVisibility : ActivityRecord{7c4a0c5 token=android.os.BinderProxy@88c2e5e {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
09-13 16:33:52.942   293   363 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
09-13 16:33:52.942   293   363 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
09-13 16:33:52.952   293  2067 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
09-13 16:33:52.952   293   822 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
09-13 16:33:52.952   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee0e3a4
09-13 16:33:52.952   293   363 I SurfaceFlinger: id=19 Removed YUIInstallC (5/9)
09-13 16:33:52.952   293   369 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/9)
09-13 16:33:52.962  2301  2314 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
09-13 16:33:52.962  1762  1762 V ActivityThread: updateVisibility : ActivityRecord{3a26ae9 token=android.os.BinderProxy@e10f2a3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 16:33:52.962  1762  1762 D Launcher: onTrimMemory. Level: 20
09-13 16:33:53.062   758   848 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-13 16:33:53.062   758  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-13 16:33:53.072  6258  6258 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 16:33:53.072   758  3435 D M       : limitCPUFreq:: freq = -1
09-13 16:33:53.072   758  3435 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 758  tag : SIOP_ARM_MAX@25
09-13 16:33:53.072   758  3435 D M       : limitGPUFreq:: freq = -1
09-13 16:33:53.102   758  3435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 16:33:53.102  6258  6258 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 16:33:53.112  6258  6258 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 16:33:53.122  6258  6258 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
09-13 16:33:53.152  6258  6258 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 16:33:53.152  6258  6258 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 16:33:53.162  6258  6258 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3063-3066)
09-13 16:33:53.162  6258  6258 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
09-13 16:33:53.192  6258  6276 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
09-13 16:33:53.192  6258  6258 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {61b6e30}
09-13 16:33:53.192  6258  6258 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
09-13 16:33:53.192  6258  6258 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 16:33:53.202  6258  6258 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
09-13 16:33:53.202   758   768 I art     : Background partial concurrent mark sweep GC freed 133918(8MB) AllocSpace objects, 11(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.974ms total 162.132ms
09-13 16:33:53.222  6258  6258 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 16:33:53.222  6258  6258 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 16:33:53.222  6258  6258 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 16:33:53.222  6258  6258 I Adreno-EGL: Local Branch: ss
09-13 16:33:53.222  6258  6258 I Adreno-EGL: Remote Branch: 
09-13 16:33:53.222  6258  6258 I Adreno-EGL: Local Patches: 
09-13 16:33:53.222  6258  6258 I Adreno-EGL: Reconstruct Branch: 
09-13 16:33:53.232  6258  6258 D libEGL  : eglInitialize EGLDisplay = 0xbed05dac
09-13 16:33:53.262   758  1795 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
09-13 16:33:53.262   758  1795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
09-13 16:33:53.312  6258  6258 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
09-13 16:33:53.312  6258  6258 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 16:33:53.312  6258  6258 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
09-13 16:33:53.322  6258  6258 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
09-13 16:33:53.322  6258  6258 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
09-13 16:33:53.332  6258  6258 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
09-13 16:33:53.342  6258  6258 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-13 16:33:53.412  6258  6258 D SecWifiDisplayUtil: Metadata value : none
09-13 16:33:53.412  6258  6258 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{edcc189 I.E...... R.....ID 0,0-0,0}
09-13 16:33:53.412  6258  6301 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-13 16:33:53.422   758   776 D ISSUE_DEBUG: InputChannelName : e42d453 com.test.thalitest/com.test.thalitest.MainActivity
09-13 16:33:53.422   758  1795 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-13 16:33:53.422   758  1795 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 16:33:53.422   758   758 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 16:33:53.422   758   758 I KnoxTimeoutHandler: Shared devices show user statefalse
09-13 16:33:53.442  6258  6258 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6258
09-13 16:33:53.452   758  1795 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6258 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:33:53.452   758  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
09-13 16:33:53.452   758  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 16:33:53.452   758  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-13 16:33:53.452   758  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 16:33:53.452   758  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-13 16:33:53.452   758  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 16:33:53.452   758  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 16:33:53.452   758  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-13 16:33:53.452   758  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 16:33:53.452   758  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:33:53.462  6258  6276 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-13 16:33:53.462  6258  6258 D SecWifiDisplayUtil: Metadata value : none
09-13 16:33:53.472   293   293 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
09-13 16:33:53.482   758  1629 D InputDispatcher: Focus entered window: 6258
09-13 16:33:53.482   758   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
09-13 16:33:53.482   758   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:33:53.482   758   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
09-13 16:33:53.482   758   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 16:33:53.482  6258  6301 D libEGL  : eglInitialize EGLDisplay = 0x9c9bf7c4
09-13 16:33:53.482  6258  6301 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 16:33:53.532  6258  6258 V ActivityThread: updateVisibility : ActivityRecord{1995a8 token=android.os.BinderProxy@939c490 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 16:33:53.532  5435  5435 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
09-13 16:33:53.532  5435  5435 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
09-13 16:33:53.532  5435  5435 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
09-13 16:33:53.542  6258  6258 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
09-13 16:33:53.542  6258  6258 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
09-13 16:33:53.542  5435  5435 I art     : System.exit called, status: 0
09-13 16:33:53.542  5435  5435 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 16:33:53.542   758  3724 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-13 16:33:53.552  6258  6258 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
09-13 16:33:53.572   758  1274 V WindowStateAnimator: Finishing drawing window Window{e42d453 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
09-13 16:33:53.572  6258  6258 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
09-13 16:33:53.572  6258  6258 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@939c490 time:103474
09-13 16:33:53.582   758   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 16:33:53.582   758   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +522ms (total +763ms)
09-13 16:33:53.582   758   891 D ActivityManager: mDVFSHelper.release()
09-13 16:33:53.582   758   758 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 16:33:53.582   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee0e364
09-13 16:33:53.582   758   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a9d2e8a u0 com.test.thalitest/.MainActivity t168} time:103484
09-13 16:33:53.582   758   758 I KnoxTimeoutHandler: SD activityfalse
09-13 16:33:53.582   758   891 D ViewRootImpl: #3 mView = null
09-13 16:33:53.582   293   363 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
09-13 16:33:53.582   293   369 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
09-13 16:33:53.592  6258  6310 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:33:53.592  6258  6310 D libEGL  : eglInitialize EGLDisplay = 0x9b16e3ec
09-13 16:33:53.602   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee0e3a4
09-13 16:33:53.602  5397  5397 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
09-13 16:33:53.602   758  3724 I ActivityManager: Process com.samsung.aasaservice (pid 5435)(adj 0) has died(92,740)
09-13 16:33:53.602   758  3724 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
09-13 16:33:53.602   758  3724 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
09-13 16:33:53.602   758  3724 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-13 16:33:53.622   758   848 I ActivityManager: Start proc 6313:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
09-13 16:33:53.622   758  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 16:33:53.622  6313  6313 E Zygote  : v2
09-13 16:33:53.622  6313  6313 I libpersona: KNOX_SDCARD checking this for 10014
09-13 16:33:53.622  6313  6313 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:53.622  6313  6313 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:53.622  6313  6313 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:53.622  6313  6313 E Zygote  : accessInfo : 0
09-13 16:33:53.622  6313  6313 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
09-13 16:33:53.642  6313  6313 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:53.642  6313  6313 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:53.652  6258  6258 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6258
09-13 16:33:53.652   758   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93e52a8 6313:com.google.android.partnersetup/u0a14}
09-13 16:33:53.652   758  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
09-13 16:33:53.662  6313  6313 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
09-13 16:33:53.672  6313  6313 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
09-13 16:33:53.692   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93e52a8 6313:com.google.android.partnersetup/u0a14}
09-13 16:33:53.712   758  1796 I ActivityManager: Start proc 6329:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
09-13 16:33:53.712  6329  6329 E Zygote  : v2
09-13 16:33:53.712  6329  6329 I libpersona: KNOX_SDCARD checking this for 10015
09-13 16:33:53.712  6329  6329 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:53.712  6329  6329 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:53.712  6329  6329 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:53.712  6329  6329 E Zygote  : accessInfo : 0
09-13 16:33:53.712  6329  6329 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
09-13 16:33:53.722   758  1415 I ActivityManager: Killing 5513:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
09-13 16:33:53.742  6329  6329 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:53.742  6329  6329 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:53.742   758  1778 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
09-13 16:33:53.752  6258  6258 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-13 16:33:53.752   758   776 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cff8a7 6329:com.samsung.groupcast/u0a15}
09-13 16:33:53.752  6329  6329 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
09-13 16:33:53.772  6329  6329 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
09-13 16:33:53.802  6329  6329 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
09-13 16:33:53.802  6329  6329 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
09-13 16:33:53.802  6329  6329 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
09-13 16:33:53.802  6329  6329 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
09-13 16:33:53.802  6329  6329 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:33:53.802  6329  6329 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
09-13 16:33:53.802  6329  6329 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:33:53.802  6329  6329 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 16:33:53.802  6329  6329 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 16:33:53.812   758  3728 I ActivityManager: Killing 5525:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
09-13 16:33:53.812   758  3728 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58f25ac 1904:com.sec.android.app.shealth:remote/u0a34}
09-13 16:33:53.832  6342  6342 E Zygote  : v2
09-13 16:33:53.832  6342  6342 I libpersona: KNOX_SDCARD checking this for 10041
09-13 16:33:53.832  6342  6342 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:53.832  6342  6342 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:53.832  6342  6342 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:53.832   758  2459 I ActivityManager: Start proc 6342:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
09-13 16:33:53.832  6342  6342 E Zygote  : accessInfo : 0
09-13 16:33:53.832  6342  6342 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
09-13 16:33:53.852   758  1635 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
09-13 16:33:53.852  6342  6342 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:53.852  6342  6342 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:53.862   758  1795 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e79f154 6342:com.samsung.android.sdk.samsunglink/u0a41}
09-13 16:33:53.872  6342  6342 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
09-13 16:33:53.932  6258  6354 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1701578448
09-13 16:33:53.932  6258  6354 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:33:53.932  6258  6354 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:33:53.932  6258  6354 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:33:53.932  6258  6354 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:33:53.932  6258  6354 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9df3e3e added. We now have 1 listener(s)
09-13 16:33:53.942  6258  6354 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
09-13 16:33:53.942  6258  6354 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 16:33:53.942  6258  6354 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:53.942  6258  6354 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:33:53.942  6258  6354 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d6b1b5 added. We now have 1 listener(s)
09-13 16:33:53.942  6258  6354 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:33:53.952  6342  6342 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 16:33:53.952  6342  6342 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:53.952  6258  6354 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
09-13 16:33:53.962  6258  6354 D BluetoothAdapter: STATE_ON
09-13 16:33:53.962  6258  6354 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:53.962  6258  6354 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:53.962  6258  6354 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 16:33:53.962  6258  6354 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:53.962  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:53.962  6258  6354 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:33:53.962  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:53.982  6258  6258 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 16:33:54.012  6342  6342 I SL_DEBUG: isLoggable:: isProductShip = 1
09-13 16:33:54.012  6342  6342 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
09-13 16:33:54.022   758  1796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.032   758  3724 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
09-13 16:33:54.032   758  1635 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.032   758  2068 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.032   758  1274 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.042   758   774 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.042   758  1795 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.042   758  1778 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.042   758  3728 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.042   758   776 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
09-13 16:33:54.062   758  3439 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,09-13 16:33:54.142  6342  6342 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,09-13 16:33:54.152  6342  6342 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
09-13 16:33:54.152  6342  6342 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
09-13 16:33:54.152  6342  6342 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
09-13 16:33:54.152  6342  6342 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
09-13 16:33:54.152  6342  6342 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:33:54.152  6342  6342 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
09-13 16:33:54.152  6342  6342 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:33:54.152  6342  6342 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 16:33:54.152  6342  6342 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,09-13 16:33:54.152   758  2459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11301c2 1682:android.process.acore/u0a19}
,09-13 16:33:54.162   758  1629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{809989c 5128:com.sec.android.gallery3d/u0a47}
,09-13 16:33:54.162  5128  5128 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-13 16:33:54.172   758  1795 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:33:54.192  6367  6367 E Zygote  : v2
09-13 16:33:54.192  6367  6367 I libpersona: KNOX_SDCARD checking this for 10050
09-13 16:33:54.192  6367  6367 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:54.192  6367  6367 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:54.192  6367  6367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:54.192  6367  6367 E Zygote  : accessInfo : 0
09-13 16:33:54.192  6367  6367 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
09-13 16:33:54.192   758  1778 I ActivityManager: Start proc 6367:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
,09-13 16:33:54.212  6367  6367 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:54.212  6367  6367 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:54.222   758  2459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11817ee 6367:com.sec.android.app.myfiles/u0a50}
,09-13 16:33:54.232  6367  6367 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,09-13 16:33:54.242  6367  6367 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,09-13 16:33:54.282  6367  6367 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-13 16:33:54.302   758  1274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a10a260 2822:com.android.settings/1000}
,09-13 16:33:54.312   331   331 E installd: system dir 0 : /system/app/
09-13 16:33:54.312   331   331 E installd: system dir 1 : /system/priv-app/
09-13 16:33:54.312   331   331 E installd: system dir 2 : /vendor/app/
09-13 16:33:54.312   331   331 E installd: system dir 3 : /oem/app/
,09-13 16:33:54.322   758   924 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-13 16:33:54.342   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a10a260 2822:com.android.settings/1000}
,09-13 16:33:54.362  6382  6382 E Zygote  : v2
,09-13 16:33:54.362  6382  6382 I libpersona: KNOX_SDCARD checking this for 10169
09-13 16:33:54.362  6382  6382 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:54.362  6382  6382 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:54.362   758  3728 I ActivityManager: Start proc 6382:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
09-13 16:33:54.362  6382  6382 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:54.362  6382  6382 E Zygote  : accessInfo : 0
,09-13 16:33:54.362  6382  6382 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,09-13 16:33:54.402  6382  6382 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:54.402  6382  6382 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:54.412   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71c4fa 6382:com.samsung.android.provider.shootingmodeprovider/u0a169}
,09-13 16:33:54.412  6382  6382 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,09-13 16:33:54.422  1451  1451 D Recents : onTaskStackChanged
,09-13 16:33:54.432  6382  6382 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,09-13 16:33:54.432  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,09-13 16:33:54.452   758   776 I ActivityManager: Killing 5543:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,09-13 16:33:54.462   758   776 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53d9ba8 1748:com.android.phone/1001}
,09-13 16:33:54.462   758  1635 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8947180 1845:com.google.android.googlequicksearchbox:search/u0a61}
,09-13 16:33:54.482   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8947180 1845:com.google.android.googlequicksearchbox:search/u0a61}
,09-13 16:33:54.482   758  1274 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,09-13 16:33:54.492   758   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d384508 6199:com.samsung.android.sm.provider/1000}
,09-13 16:33:54.512  6397  6397 E Zygote  : v2
,09-13 16:33:54.512  6397  6397 I libpersona: KNOX_SDCARD checking this for 5012
09-13 16:33:54.512  6397  6397 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:54.512  6397  6397 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 16:33:54.512   758   776 I ActivityManager: Start proc 6397:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
09-13 16:33:54.512  6397  6397 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:54.512  6397  6397 E Zygote  : accessInfo : 0
,09-13 16:33:54.522  6397  6397 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,09-13 16:33:54.522  1845  6395 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 16:33:54.552  6397  6397 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:54.552  6397  6397 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:54.562   758  1417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{22e04a1 6397:com.samsung.android.sm.devicesecurity/5012}
,09-13 16:33:54.572  6397  6397 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,09-13 16:33:54.582  6397  6397 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,09-13 16:33:54.612  1845  6395 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,09-13 16:33:54.612  6409  6409 E Zygote  : v2
09-13 16:33:54.612  6409  6409 I libpersona: KNOX_SDCARD checking this for 10210
09-13 16:33:54.612  6409  6409 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:54.612  6409  6409 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:54.612  6409  6409 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:54.612   758   848 I ActivityManager: Start proc 6409:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
09-13 16:33:54.612  6409  6409 E Zygote  : accessInfo : 0
09-13 16:33:54.612  6409  6409 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,09-13 16:33:54.662  6409  6409 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:54.662  6409  6409 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:54.692   758  1796 I ActivityManager: Killing 5150:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,09-13 16:33:54.702   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ec634c 3201:com.android.contacts/u0a19}
,09-13 16:33:54.722   758  2459 I ActivityManager: Start proc 6421:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
,09-13 16:33:54.722  6421  6421 E Zygote  : v2
09-13 16:33:54.722  6421  6421 I libpersona: KNOX_SDCARD checking this for 10049
09-13 16:33:54.722  6421  6421 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:54.722  6421  6421 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:54.722  6421  6421 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:54.722  6421  6421 E Zygote  : accessInfo : 0
09-13 16:33:54.722  6421  6421 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,09-13 16:33:54.722  1845  6395 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,09-13 16:33:54.752  6421  6421 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:54.752  6421  6421 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:54.762   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88736c6 6421:com.android.mms/u0a49}
,09-13 16:33:54.772   758  1795 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,09-13 16:33:54.772  6409  6409 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,09-13 16:33:54.782  6421  6421 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,09-13 16:33:54.802  6409  6409 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,09-13 16:33:54.822  6409  6409 D AASAservice: onCreate()
,09-13 16:33:54.832  5397  5397 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,09-13 16:33:54.842   758  1796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,09-13 16:33:54.872  6421  6421 W System  : ClassLoader referenced unknown path: imsmanager.jar
,09-13 16:33:54.882  6421  6421 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,09-13 16:33:54.932  6258  6355 W jxcore-log: Initializing JXcore engine
09-13 16:33:54.932  6258  6355 W jxcore-log: JXcore engine is ready
,09-13 16:33:54.972  4115  6433 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-13 16:33:54.982  6421  6421 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-13 16:33:54.982  2379  2379 E audit   : type=1400 msg=audit(1473777234.982:287): avc:  denied  { ioctl } for  pid=6355 comm="Thread-875" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 16:33:54.982  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:54.982  2379  2379 E audit   : type=1300 msg=audit(1473777234.982:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98dea3c8 items=0 ppid=351 ppcomm=main pid=6355 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-875" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 16:33:54.982  2379  2379 E audit   : type=1327 msg=audit(1473777234.982:287): proctitle="com.test.thalitest"
09-13 16:33:54.982  2379  2379 E audit   : type=1320 msg=audit(1473777234.982:287): 
,09-13 16:33:54.982  2379  2379 E audit   : type=1400 msg=audit(1473777234.982:288): avc:  denied  { ioctl } for  pid=6355 comm="Thread-875" path="socket:[40323]" dev="sockfs" ino=40323 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 16:33:54.982  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:54.982  2379  2379 E audit   : type=1300 msg=audit(1473777234.982:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=98dea3c8 items=0 ppid=351 ppcomm=main pid=6355 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-875" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 16:33:54.982  2379  2379 E audit   : type=1327 msg=audit(1473777234.982:288): proctitle="com.test.thalitest"
09-13 16:33:54.982  2379  2379 E audit   : type=1320 msg=audit(1473777234.982:288): 
,09-13 16:33:54.992  1845  6395 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 470 ms] updated apps [took 470 ms] 
,09-13 16:33:55.002  6258  6355 W jxcore-log: Starting JXcore engine
,09-13 16:33:55.002  6421  6421 D Mms/TelephonyPermission: start operation mode monitor
,09-13 16:33:55.002  6421  6421 D Mms/TelephonyPermission: User ID is null set current User Id
,09-13 16:33:55.002  6421  6436 D Mms/ArtClassLoader: init before art third
,09-13 16:33:55.002  6421  6435 D Mms/ArtClassLoader: init before art second
,09-13 16:33:55.012  6421  6434 D Mms/ArtClassLoader: init before art first
,09-13 16:33:55.012  6421  6421 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,09-13 16:33:55.012  6421  6421 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,09-13 16:33:55.022  6421  6421 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 16:33:55.022  6421  6421 D Mms/TelephonyPermission: isDefault true
,09-13 16:33:55.022  6421  6421 D Mms/MmsApp: onCreate() com.android.mms
,09-13 16:33:55.042  6421  6421 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,09-13 16:33:55.042  6421  6421 D Mms/MmsApp: [start]    initCountryIso consume time = 67.085625
,09-13 16:33:55.042   758  1629 D CountryDetector: The first listener is added
,09-13 16:33:55.052  6421  6421 D Mms/MmsApp: [end]    initCountryIso consume time = 9.757031
09-13 16:33:55.052  6421  6421 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.106667
,09-13 16:33:55.062  6421  6436 D Mms/ArtClassLoader: init [DONE] art
,09-13 16:33:55.072  6421  6421 D Mms/MmsConfig: before partial update
,09-13 16:33:55.082  6258  6355 W jxcore-log: Platform android
09-13 16:33:55.082  6258  6355 W jxcore-log: 
09-13 16:33:55.082  6258  6355 W jxcore-log: Process ARCH arm
09-13 16:33:55.082  6258  6355 W jxcore-log: 
,09-13 16:33:55.102  6421  6421 D Mms/MmsConfig: Load Resize quality : 80
,09-13 16:33:55.102  6421  6421 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,09-13 16:33:55.102  6421  6421 D EasySignUpManager_1.0.5: isAuth is false
09-13 16:33:55.102  6421  6421 I EasySignUpManager_1.0.5: auth : false, join : 2
,09-13 16:33:55.112  6421  6421 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,09-13 16:33:55.112  6421  6421 D EasySignUpManager_1.0.5: userSerialNumber = 0
,09-13 16:33:55.112  6421  6421 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
09-13 16:33:55.112  6421  6421 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,09-13 16:33:55.112  6421  6421 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
09-13 16:33:55.112  6421  6421 D EasySignUpManager_1.0.5: isAuth is false
,09-13 16:33:55.112  6421  6421 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
09-13 16:33:55.112  6421  6421 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,09-13 16:33:55.122  1748  2317 D TP/MmsSmsProvider: query, match:2117, calling pid = 6421, accessRestricted = false
,09-13 16:33:55.122  1748  2317 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.109 ms
,09-13 16:33:55.132  6421  6421 E CscParser: mps_code.dat does not exist
09-13 16:33:55.132  6421  6421 E CscParser: customer_path =/system/csc/customer.xml
,09-13 16:33:55.132  6421  6421 E CscParser: fileName + /system/csc/customer.xml
,09-13 16:33:55.142  6421  6421 E CscParser: mps_code.dat does not exist
09-13 16:33:55.142  6421  6421 E CscParser: customer_path =/system/csc/customer.xml
09-13 16:33:55.142  6421  6421 E CscParser: fileName + /system/csc/customer.xml
,09-13 16:33:55.152  6421  6421 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-13 16:33:55.152  6421  6421 D Mms/MmsConfig:  enable multiwindow = true
,09-13 16:33:55.152  6421  6421 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,09-13 16:33:55.152  6421  6421 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,09-13 16:33:55.152  6421  6421 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
09-13 16:33:55.152  6421  6421 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,09-13 16:33:55.152  6421  6421 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
09-13 16:33:55.152  6421  6421 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 16:33:55.152  6421  6421 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-13 16:33:55.162  6421  6421 D Mms/MmsConfig: [end]    init() consume time = 103.523958
,09-13 16:33:55.162  6421  6421 D Mms/Contact: [start]    init() consume time = 3.552292
,09-13 16:33:55.172  1748  1979 D TP/MmsSmsProvider: query, match:13, calling pid = 6421, accessRestricted = false
,09-13 16:33:55.172  6421  6421 D Mms/Contact: [end]    init consume time = 14.413697
,09-13 16:33:55.182  1748  1979 D TP/MmsSmsProvider: query, match 13:Elapsed time : 2.581 ms
,09-13 16:33:55.192  6421  6434 D Mms/ArtClassLoader: init [DONE] art
,09-13 16:33:55.192  6421  6421 D Mms:transaction: roaming -> false (slotId = 0)
,09-13 16:33:55.192  6421  6421 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 16:33:55.192  6421  6421 D Mms:transaction: auto download without roaming -> true
09-13 16:33:55.192  6421  6421 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,09-13 16:33:55.192  6421  6421 D Mms:transaction: roaming -> false (slotId = 1)
09-13 16:33:55.192  6421  6421 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 16:33:55.192  6421  6421 D Mms:transaction: auto download without roaming -> true
09-13 16:33:55.192  6421  6421 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 16:33:55.192  6421  6421 D Mms:transaction: auto download during roaming secondary -> false
,09-13 16:33:55.192  6421  6421 D Mms:transaction: mAutoDownload ------> true
,09-13 16:33:55.202  6421  6443 D Mms/DraftCache: [start]    rebuildCache consume time = 25.489272
,09-13 16:33:55.212  6421  6435 D Mms/ArtClassLoader: init [DONE] art
,09-13 16:33:55.212  1748  1773 D TP/MmsSmsProvider: query, match:12, calling pid = 6421, accessRestricted = false
,09-13 16:33:55.212  1748  1773 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.393 ms
,09-13 16:33:55.212  6421  6443 D Mms/DraftCache: [end]    rebuildCache consume time = 13.137239
,09-13 16:33:55.222  6421  6421 D ComposerPerformance: 1473777235238 ms / [DONE] Composer constructor
,09-13 16:33:55.232  6421  6421 D CII     : Log Level [5]
09-13 16:33:55.232  6421  6421 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,09-13 16:33:55.232  6421  6444 D Mms/Conversation: [start]    init() consume time = 15.785938
,09-13 16:33:55.232  1748  2066 D TP/MmsSmsProvider: delete, match:1, calling pid = 6421
,09-13 16:33:55.232  1748  2066 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-13 16:33:55.232  1748  2066 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,09-13 16:33:55.232  6421  6421 I Mms/ReservationManager: ReservationManager()
,09-13 16:33:55.232  6421  6421 I Mms/ReservationManager: resetAfterConnected()
,09-13 16:33:55.232  1748  2066 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,09-13 16:33:55.242  1748  2066 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 16:33:55.242  1748  2066 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-13 16:33:55.242  1748  1979 D TP/MmsSmsProvider: query, match:7, calling pid = 6421, accessRestricted = false
,09-13 16:33:55.242  1748  1979 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.370 ms
,09-13 16:33:55.242  1748  2066 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,09-13 16:33:55.252  1748  2066 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
,09-13 16:33:55.252  1748  2066 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
09-13 16:33:55.252  1748  2066 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 16:33:55.252  1748  2066 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 10.632 ms
09-13 16:33:55.252  1748  2066 D TP/MmsSmsProvider: need read changed broadcast:false
,09-13 16:33:55.252  6421  6444 D Mms/Conversation: [end]    init consume time = 23.365104
,09-13 16:33:55.252  6421  6421 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-13 16:33:55.252  6421  6444 D Mms/MessagingNotification: [start]    init() consume time = 2.164166
,09-13 16:33:55.262  6421  6444 D Mms/MessagingNotification: [end]    init consume time = 2.536772
,09-13 16:33:55.262  6421  6421 D Mms/MmsApp: [end]    onCreate() consume time = 0.782656
,09-13 16:33:55.262  6421  6421 D Mms/MmsApp: [end]    onCreate() consume time = 0.193073
,09-13 16:33:55.262  6421  6446 D Mms/Synchronizer: [start]    doSync consume time = 5.536041
,09-13 16:33:55.262  6421  6445 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.486718
,09-13 16:33:55.272  6421  6421 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,09-13 16:33:55.272  6421  6421 D Mms:transaction: roaming ------> false, mSimSlot = 0
,09-13 16:33:55.272  6421  6421 D Mms:transaction: roaming -> false (slotId = 0)
09-13 16:33:55.272  6421  6421 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 16:33:55.272  6421  6421 D Mms:transaction: auto download without roaming -> true
09-13 16:33:55.272  6421  6421 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,09-13 16:33:55.272  6421  6421 D Mms:transaction: mAutoDownload ------> true
09-13 16:33:55.272  1748  1773 D TP/MmsSmsProvider: query, match:0, calling pid = 6421, accessRestricted = false
09-13 16:33:55.272  1748  1773 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-13 16:33:55.272  1748  1773 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.164 ms
,09-13 16:33:55.272   758  1417 I ActivityManager: Start proc 6447:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,09-13 16:33:55.272  6447  6447 E Zygote  : v2
09-13 16:33:55.272  6447  6447 I libpersona: KNOX_SDCARD checking this for 1000
,09-13 16:33:55.272  6447  6447 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:55.272   758  1417 I ActivityManager: Killing 5166:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,09-13 16:33:55.272  6447  6447 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 16:33:55.272  6447  6447 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:55.282  6447  6447 E Zygote  : accessInfo : 0
,09-13 16:33:55.282  1748  1760 D TP/MmsSmsProvider: update, match:300, calling pid = 6421
,09-13 16:33:55.282  1748  1760 V TP/MmsSmsProvider: syncDBData start
,09-13 16:33:55.282  1748  1760 V TP/MmsSmsProvider: syncDBData sms end
,09-13 16:33:55.282  1748  1760 V TP/MmsSmsProvider: syncDBData mms end
,09-13 16:33:55.282  1748  1760 V TP/MmsSmsProvider: syncDBData end
,09-13 16:33:55.282  1748  1760 D TP/MmsSmsProvider: update, match 300:Elapsed time : 3.420 ms
,09-13 16:33:55.282  6421  6446 D Mms/Synchronizer: [end]    doSync consume time = 18.299323
,09-13 16:33:55.292  1748  1979 D TP/MmsSmsProvider: query, match:400, calling pid = 6421, accessRestricted = false
,09-13 16:33:55.302   758  2459 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,09-13 16:33:55.302  6421  6445 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 19.196823
,09-13 16:33:55.312  6447  6447 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:55.312  6035  6048 D BadgeProvider: query, [selection] : package=?
,09-13 16:33:55.312  6447  6447 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:55.322   758  1635 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b3d005 6447:com.samsung.android.bbc.bbcagent/1000}
,09-13 16:33:55.322  6421  6444 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-13 16:33:55.322  6258  6355 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:33:55.322  6258  6355 I jxcore-log: 
,09-13 16:33:55.332  6258  6355 W jxcore-log: JXcore engine is started
,09-13 16:33:55.332  6447  6447 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,09-13 16:33:55.332  1748  1773 D TP/SmsProvider: query,matched:26, calling pid = 6421
,09-13 16:33:55.332  1748  1773 D TP/SmsProvider: query, match 26:Elapsed time : 0.918 ms
,09-13 16:33:55.332  6258  6354 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 16:33:55.342  6258  6258 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:33:55.342  1748  1979 D TP/MmsSmsProvider: query, match:6, calling pid = 6421, accessRestricted = false
,09-13 16:33:55.342  1748  1979 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.064 ms
,09-13 16:33:55.372  6447  6447 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,09-13 16:33:55.372   758  1778 I ActivityManager: Start proc 6459:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
09-13 16:33:55.372  6459  6459 E Zygote  : v2
09-13 16:33:55.372  6459  6459 I libpersona: KNOX_SDCARD checking this for 10024
09-13 16:33:55.372  6459  6459 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:55.372  6459  6459 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:55.372  6459  6459 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:55.372  6459  6459 E Zygote  : accessInfo : 0
09-13 16:33:55.372  6459  6459 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,09-13 16:33:55.392  6459  6459 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:55.392  6459  6459 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:55.402   758  3728 I ActivityManager: Killing 5190:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,09-13 16:33:55.412  6459  6459 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,09-13 16:33:55.422   758  1629 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,09-13 16:33:55.432  6471  6471 E Zygote  : v2
09-13 16:33:55.432  6471  6471 I libpersona: KNOX_SDCARD checking this for 10097
09-13 16:33:55.432  6471  6471 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:55.432  6471  6471 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:55.432  6471  6471 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:55.432  6471  6471 E Zygote  : accessInfo : 0
09-13 16:33:55.432  6471  6471 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,09-13 16:33:55.442   758  1795 I ActivityManager: Start proc 6471:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,09-13 16:33:55.442   758  1795 I ActivityManager: Killing 4741:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,09-13 16:33:55.462  6459  6459 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,09-13 16:33:55.462  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:55.462  6471  6471 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:55.472   758  1629 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,09-13 16:33:55.482   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3cf485a 6471:com.google.android.apps.docs/u0a97}
,09-13 16:33:55.492  6471  6471 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,09-13 16:33:55.502  6471  6471 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,09-13 16:33:55.522  6459  6459 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,09-13 16:33:55.532  6421  6444 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-13 16:33:55.542  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-13 16:33:55.542  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-13 16:33:55.542  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-13 16:33:55.542  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-13 16:33:55.542  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-13 16:33:55.542  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-13 16:33:55.552  6459  6459 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 16:33:55.792  6471  6485 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
09-13 16:33:55.792  6471  6485 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 16:33:55.792  6471  6485 I GAv4    :   adb logcat -s GAv4
,09-13 16:33:55.812  6471  6485 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,09-13 16:33:55.812   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{a299026: PendingIntentRecord{1022467 com.google.android.apps.docs broadcastIntent}}
,09-13 16:33:55.812  6471  6485 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:55.812  6471  6485 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:55.822  6471  6490 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:55.862   758  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,09-13 16:33:55.912  6471  6471 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,09-13 16:33:55.922  6471  6471 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,09-13 16:33:55.952  6471  6485 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,09-13 16:33:55.952  6471  6485 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
09-13 16:33:55.952  6471  6485 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,09-13 16:33:55.952  6471  6485 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,09-13 16:33:55.982  6497  6497 E Zygote  : v2
09-13 16:33:55.982  6497  6497 I libpersona: KNOX_SDCARD checking this for 10098
09-13 16:33:55.982  6497  6497 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:55.992  6497  6497 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:55.992  6497  6497 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:55.992   758  1778 I ActivityManager: Start proc 6497:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,09-13 16:33:55.992  6497  6497 E Zygote  : accessInfo : 0
09-13 16:33:55.992  6497  6497 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,09-13 16:33:55.992   758  1778 I ActivityManager: Killing 5449:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): DHA:empty #37
,09-13 16:33:56.002   758  1417 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.SPlannerAppWidget, Auto Run ON
,09-13 16:33:56.012   758  6163 I HarmonyEASService: Updating for all 1
,09-13 16:33:56.022  4115  5085 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,09-13 16:33:56.022  6497  6497 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:56.022  6497  6497 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.042   758  3724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{402a003 6497:com.sec.android.automotive.drivelink/u0a98}
,09-13 16:33:56.062  6497  6497 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,09-13 16:33:56.082  6497  6497 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,09-13 16:33:56.122  2074  2074 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:56.122  6497  6497 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
09-13 16:33:56.122  2074  2074 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:56.132  4115  5085 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,09-13 16:33:56.142   758   768 I art     : Background partial concurrent mark sweep GC freed 21588(1413KB) AllocSpace objects, 1(20KB) LOS objects, 27% free, 42MB/58MB, paused 1.678ms total 107.428ms
,09-13 16:33:56.152  2074  2074 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:56.152   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{a6e0c7b: PendingIntentRecord{acafa98 com.sec.android.automotive.drivelink broadcastIntent}}
,09-13 16:33:56.152  6497  6513 I GMPM    : App measurement is starting up
,09-13 16:33:56.162  6497  6497 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,09-13 16:33:56.162  6497  6513 E GMPM    : getGoogleAppId failed with status: 10
,09-13 16:33:56.162  6497  6513 E GMPM    : Uploading is not possible. App measurement disabled
,09-13 16:33:56.162   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{a5732f1: PendingIntentRecord{acafa98 com.sec.android.automotive.drivelink broadcastIntent}}
,09-13 16:33:56.182  6497  6497 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,09-13 16:33:56.182  4115  5085 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,09-13 16:33:56.192  6497  6497 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,09-13 16:33:56.212  6471  6486 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,09-13 16:33:56.242  6519  6519 E Zygote  : v2
,09-13 16:33:56.242  6519  6519 I libpersona: KNOX_SDCARD checking this for 10032
09-13 16:33:56.242  6519  6519 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:56.242  6519  6519 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 16:33:56.242   758  1796 I ActivityManager: Start proc 6519:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
09-13 16:33:56.242   758  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 16:33:56.242  6519  6519 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:56.242  6519  6519 E Zygote  : accessInfo : 0
,09-13 16:33:56.242  6519  6519 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,09-13 16:33:56.262  6519  6519 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:56.262  6519  6519 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.272  6471  6486 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,09-13 16:33:56.272   758  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-13 16:33:56.282  6519  6519 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,09-13 16:33:56.292  6519  6519 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,09-13 16:33:56.312  6471  6486 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
09-13 16:33:56.312  6471  6486 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,09-13 16:33:56.312  6471  6486 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 16:33:56.342  6471  6486 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 16:33:56.382  6497  6497 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,09-13 16:33:56.382  6497  6497 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,09-13 16:33:56.382  6497  6497 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,09-13 16:33:56.392  6519  6519 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,09-13 16:33:56.412  6497  6497 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Sep 13 16:33:56 GMT+02:00 2016
,09-13 16:33:56.422  6533  6533 E Zygote  : v2
,09-13 16:33:56.422  6533  6533 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:56.422  6533  6533 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:56.422  6533  6533 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:56.422  6533  6533 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:56.422   758  2459 I ActivityManager: Start proc 6533:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,09-13 16:33:56.422  6497  6497 D DialogFlow: initQueue()
,09-13 16:33:56.422  6533  6533 E Zygote  : accessInfo : 0
09-13 16:33:56.422   758  2459 I ActivityManager: Killing 5473:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
09-13 16:33:56.422   758  2459 I ActivityManager: Killing 4783:com.android.calendar/u0a149 (adj 15): DHA:empty #37
,09-13 16:33:56.432  6519  6519 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,09-13 16:33:56.442   758  3478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:56.442   758  2459 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,09-13 16:33:56.452   758  1635 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,09-13 16:33:56.462  6533  6533 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:56.462  6533  6533 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.462   758  1795 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eca84b0 6533:com.samsung.android.app.filterinstaller/1000}
,09-13 16:33:56.472  6533  6533 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,09-13 16:33:56.482   758  1796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,09-13 16:33:56.492  6533  6533 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,09-13 16:33:56.502  6533  6533 E FilterPackageIntentReceiver: This package is not a effect filter
,09-13 16:33:56.512  6519  6519 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,09-13 16:33:56.512  6519  6519 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,09-13 16:33:56.512  6519  6519 D DialogFlow: initQueue()
,09-13 16:33:56.512  6549  6549 E Zygote  : v2
09-13 16:33:56.512  6549  6549 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:56.512  6549  6549 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:56.512  6549  6549 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:56.512  6549  6549 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:56.512  6549  6549 E Zygote  : accessInfo : 0
,09-13 16:33:56.522   758   776 I ActivityManager: Start proc 6549:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,09-13 16:33:56.522   758   776 I ActivityManager: Killing 5086:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
09-13 16:33:56.542  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:56.542  6549  6549 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:56.542   758   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a170a6b 6549:com.samsung.helphub/1000}
09-13 16:33:56.552   758  1415 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
09-13 16:33:56.552  6549  6549 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,09-13 16:33:56.562  6549  6549 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,09-13 16:33:56.602  6561  6561 E Zygote  : v2
09-13 16:33:56.602  6561  6561 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:56.602  6561  6561 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:56.602   758  2068 I ActivityManager: Start proc 6561:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,09-13 16:33:56.602  6561  6561 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:56.602  6561  6561 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:56.602   758  2068 I ActivityManager: Killing 5657:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
09-13 16:33:56.602  6561  6561 E Zygote  : accessInfo : 0
,09-13 16:33:56.632   758  3728 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,09-13 16:33:56.632  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:56.632  6561  6561 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.642   758  3724 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{abe39c8 6561:com.samsung.android.app.mirrorlink/1000}
,09-13 16:33:56.642  6561  6561 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,09-13 16:33:56.662  6561  6561 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,09-13 16:33:56.692  6561  6561 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,09-13 16:33:56.692  6561  6561 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,09-13 16:33:56.702   758   776 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a2ce63 5670:com.google.android.apps.plus/u0a134}
,09-13 16:33:56.712   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a2ce63 5670:com.google.android.apps.plus/u0a134}
,09-13 16:33:56.722   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a2ce63 5670:com.google.android.apps.plus/u0a134}
,09-13 16:33:56.742   758  1417 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,09-13 16:33:56.742   758   774 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,09-13 16:33:56.752   758   776 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,09-13 16:33:56.752   758  1415 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,09-13 16:33:56.762   758  2459 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,09-13 16:33:56.762   758  3724 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,09-13 16:33:56.762   758  1635 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,09-13 16:33:56.772   758  1417 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,09-13 16:33:56.802  6575  6575 E Zygote  : v2
09-13 16:33:56.802  6575  6575 I libpersona: KNOX_SDCARD checking this for 10165
09-13 16:33:56.802  6575  6575 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:56.802  6575  6575 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:56.802   758  2459 I ActivityManager: Start proc 6575:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
09-13 16:33:56.802  6575  6575 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:56.802  6575  6575 E Zygote  : accessInfo : 0
09-13 16:33:56.802  6575  6575 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,09-13 16:33:56.802   758  3724 I ActivityManager: Killing 5696:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,09-13 16:33:56.822   758  2068 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,09-13 16:33:56.842  6575  6575 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:56.842  6575  6575 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.852   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{899e247 6575:com.sec.kidsplat.installer/u0a165}
,09-13 16:33:56.862  6575  6575 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,09-13 16:33:56.872  6575  6575 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,09-13 16:33:56.882   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{899e247 6575:com.sec.kidsplat.installer/u0a165}
,09-13 16:33:56.892  6575  6575 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,09-13 16:33:56.902  6588  6588 E Zygote  : v2
,09-13 16:33:56.902  6588  6588 I libpersona: KNOX_SDCARD checking this for 10142
09-13 16:33:56.902  6588  6588 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:56.902  6588  6588 E Zygote  : isSdpEnabledProcess - SDP enabled
,09-13 16:33:56.902   758  1415 I ActivityManager: Start proc 6588:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
09-13 16:33:56.902  6588  6588 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 16:33:56.902  6588  6588 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:33:56.902  6588  6588 E Zygote  : accessInfo : 64
,09-13 16:33:56.902  6588  6588 E Zygote  : isSdpEnabledProcess - SDP enabled
09-13 16:33:56.902  6588  6588 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,09-13 16:33:56.902  6588  6588 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
09-13 16:33:56.902   758  1415 I ActivityManager: Killing 4860:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,09-13 16:33:56.932  6588  6588 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:56.932  6588  6588 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.942   758  1274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6612a74 6588:com.sec.android.app.sbrowser/u0a142}
,09-13 16:33:56.942  6588  6588 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,09-13 16:33:56.952   758   776 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,09-13 16:33:56.962  6588  6588 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,09-13 16:33:57.022  6588  6588 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,09-13 16:33:57.042  6588  6588 D ManifestProvider: onCreate()
,09-13 16:33:57.052  6588  6588 I SBrowserUtils: getSystemProperty of sales_code : XEO
,09-13 16:33:57.052  6588  6588 I SBrowserUtils: getSystemProperty of country_code : Poland
,09-13 16:33:57.052  6588  6588 I SBrowserUtils: getSystemProperty of country_code : Poland
09-13 16:33:57.052  6588  6588 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,09-13 16:33:57.062  6588  6588 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,09-13 16:33:57.062  6588  6588 D [MM]MHDataBaseProvider: onCreate()
,09-13 16:33:57.082  6588  6588 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@5615865)
,09-13 16:33:57.112   758  1778 I ActivityManager: Killing 5644:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,09-13 16:33:57.112   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df8398 2074:com.google.android.gms.persistent/u0a11}
,09-13 16:33:57.122  4115  6603 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:57.122   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4cdea04 4115:com.google.android.gms/u0a11}
,09-13 16:33:57.132  4115  6602 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,09-13 16:33:57.132  4115  6603 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:57.142   758   776 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,09-13 16:33:57.142  4115  4115 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 16:33:57.152  4115  6603 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:57.152  4115  6603 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:57.162   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df8398 2074:com.google.android.gms.persistent/u0a11}
,09-13 16:33:57.172   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4cdea04 4115:com.google.android.gms/u0a11}
,09-13 16:33:57.182  4115  5059 D nzm     : Processing package: com.test.thalitest
,09-13 16:33:57.182  4115  4115 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 16:33:57.222  4115  5059 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,09-13 16:33:57.222  4115  5059 D nzm     : Found info for package com.test.thalitest in db.
,09-13 16:33:57.292   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ee0dfb 6064:com.sec.android.app.samsungapps/u0a39}
,09-13 16:33:57.302  6421  6421 I Mms/MmsApp:  start initViewCache mms
,09-13 16:33:57.302   758  1274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ff0f14 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{939cbf6 4878:com.android.vending/u0a29}
,09-13 16:33:57.352  6519  6547 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,09-13 16:33:57.352  6519  6547 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 16:33:57.352  4878  4878 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,09-13 16:33:57.362  6609  6609 E Zygote  : v2
09-13 16:33:57.362  6609  6609 I libpersona: KNOX_SDCARD checking this for 10034
09-13 16:33:57.362  6609  6609 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:33:57.362  6609  6609 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:57.362  6609  6609 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 16:33:57.362   758  2459 I ActivityManager: Start proc 6609:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
09-13 16:33:57.362  6609  6609 E Zygote  : accessInfo : 0
09-13 16:33:57.362  6609  6609 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,09-13 16:33:57.382  2074  2074 D WearableService: callingUid 10011, callindPid: 2074
,09-13 16:33:57.382  6609  6609 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:57.382  6609  6609 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:57.392  4878  4878 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-13 16:33:57.402   758  1274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{53803d3 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2361b10 6609:com.sec.android.app.shealth/u0a34}
,09-13 16:33:57.422  6519  6547 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 16:33:57.422  6519  6547 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
09-13 16:33:57.422  6519  6547 I System.out: INFO:Resource not found:/Common.properties Using default values
,09-13 16:33:57.432  4878  4878 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 16:33:57.432  4878  4878 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-13 16:33:57.432  6519  6547 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 16:33:57.432  6519  6547 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 16:33:57.452  6609  6609 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,09-13 16:33:57.482  6609  6609 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,09-13 16:33:57.482  6609  6609 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 16:33:57.482  6609  6609 I MultiDex: install
09-13 16:33:57.482  6609  6609 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 16:33:57.482  6609  6609 I MultiDex: install
09-13 16:33:57.482  6609  6609 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 16:33:57.582  6609  6609 D HealthDataStore: Service for HealthDataStore is connected
,09-13 16:33:57.582  6609  6609 D HealthDataStore: HealthConnectionErrorResult code : 9
,09-13 16:33:57.582   758  1795 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{53803d3 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58f25ac 1904:com.sec.android.app.shealth:remote/u0a34}
,09-13 16:33:57.582  6609  6609 D HealthConsole: Service for HealthDataConsole is connected
,09-13 16:33:57.592   758  3724 I ActivityManager: Killing 5383:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,09-13 16:33:57.602  6609  6609 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,09-13 16:33:57.602  6609  6609 E HealthDataStore: disconnectService: Context instance is invalid
,09-13 16:33:57.612   758  1417 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,09-13 16:33:57.622   758  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{53803d3 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58f25ac 1904:com.sec.android.app.shealth:remote/u0a34}
,09-13 16:33:57.632   758  1274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37ed2e6 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df8398 2074:com.google.android.gms.persistent/u0a11}
,09-13 16:33:57.702  6421  6421 D Mms/BubbleViewCache: fillCache bubble = 4
,09-13 16:33:58.112  3515  3515 D FactoryTest: User mode
,09-13 16:33:58.112  3515  3515 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-13 16:33:58.112  3515  3515 D MTPRx   : still no open session command from host, so toast
,09-13 16:33:58.112   758  1778 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,09-13 16:33:58.122   758  1778 D ActivityManager: mDVFSHelper.acquire()
,09-13 16:33:58.122   758  1778 V WindowManager: addAppToken: AppWindowToken{cde2c7d token=Token{f4af2d4 ActivityRecord{5261027 u0 com.samsung.android.MtpApplication/.USBConnection t169}}} to stack=1 task=169 at 0
,09-13 16:33:58.122   758  1778 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,09-13 16:33:58.132   758   848 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-13 16:33:58.142   758  1778 D InputDispatcher: Focused application set to: xxxx
,09-13 16:33:58.142   758  1778 D InputDispatcher: Focus left window: 6258
,09-13 16:33:58.142  3515  3515 E MTPRx   : started activity for popup
,09-13 16:33:58.142   758   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
09-13 16:33:58.142   758   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:33:58.142   758   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
09-13 16:33:58.142   758   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,09-13 16:33:58.152  3515  3515 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,09-13 16:33:58.152  3515  3515 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,09-13 16:33:58.162  3515  3515 D MTPUSBConnection: onCreate in USBConnection
,09-13 16:33:58.162  3515  3515 V MTPUSBConnection: Registering broadcast receiver.
,09-13 16:33:58.162  3515  3515 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,09-13 16:33:58.162   758  1778 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,09-13 16:33:58.212  3515  3515 D TAG     : dev.kiessupport is : TRUE
,09-13 16:33:58.242  3515  3515 D SecWifiDisplayUtil: Metadata value : none
,09-13 16:33:58.242  3515  3515 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{665ecb9 V.E...... R.....I. 0,0-0,0}
,09-13 16:33:58.242  3515  6631 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 16:33:58.252   758  1417 D ISSUE_DEBUG: InputChannelName : 96b6e35 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,09-13 16:33:58.252   758  1417 D InputDispatcher: Focus entered window: 3515
,09-13 16:33:58.252   758   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
09-13 16:33:58.252   758   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:33:58.252   758   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
09-13 16:33:58.252   758   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 16:33:58.252   758   852 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{96b6e35 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-13 16:33:58.252  1379  1379 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,09-13 16:33:58.262  3515  3515 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c2b79f1 I.E...... R.....I. 0,0-0,0}
,09-13 16:33:58.262   758  1417 D ISSUE_DEBUG: InputChannelName : 8c22c3b com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,09-13 16:33:58.262   758  1635 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,09-13 16:33:58.262   758  1635 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 16:33:58.262   758   758 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 16:33:58.262   758   758 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-13 16:33:58.272   758   758 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-13 16:33:58.292   293   293 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, VSBConnecti
,09-13 16:33:58.302  3515  6631 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 16:33:58.302  3515  6631 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 16:33:58.302  3515  6631 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 16:33:58.302  3515  6631 I Adreno-EGL: Local Branch: ss
09-13 16:33:58.302  3515  6631 I Adreno-EGL: Remote Branch: 
09-13 16:33:58.302  3515  6631 I Adreno-EGL: Local Patches: 
09-13 16:33:58.302  3515  6631 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:33:58.302  3515  6631 D libEGL  : eglInitialize EGLDisplay = 0x9f0cb7c4
09-13 16:33:58.302  3515  6631 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:33:58.342   293   293 I SurfaceFlinger: id=24 createSurf (193x193),1 flag=4, VSBConnecti
,09-13 16:33:58.352  3515  3515 V ActivityThread: updateVisibility : ActivityRecord{9fb5b44 token=android.os.BinderProxy@79c58fe {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-13 16:33:58.362  3515  3515 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-13 16:33:58.432  4115  5038 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,09-13 16:33:58.482   758   776 V WindowStateAnimator: Finishing drawing window Window{96b6e35 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 16:33:58.482  3515  3515 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-13 16:33:58.482   758  1796 V WindowStateAnimator: Finishing drawing window Window{8c22c3b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 16:33:58.482  3515  3515 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
09-13 16:33:58.482  3515  3515 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,09-13 16:33:58.492   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee0e364
,09-13 16:33:58.492   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee0e364
,09-13 16:33:58.492   758   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 16:33:58.492   758  1274 V WindowStateAnimator: Finishing drawing window Window{96b6e35 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
09-13 16:33:58.492   758   758 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 16:33:58.492   758  1417 V WindowStateAnimator: Finishing drawing window Window{8c22c3b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
09-13 16:33:58.492   758   758 I KnoxTimeoutHandler: SD activityfalse
09-13 16:33:58.492  3515  3515 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@79c58fe time:108398
,09-13 16:33:58.492   758   891 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +359ms (total +373ms)
,09-13 16:33:58.502   758   891 D ActivityManager: mDVFSHelper.release()
,09-13 16:33:58.502   758   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5261027 u0 com.samsung.android.MtpApplication/.USBConnection t169} time:108402
,09-13 16:33:58.512   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbee0e364
,09-13 16:33:58.532  4115  5038 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 16:33:58.542  4115  5038 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 16:33:58.552  4115  5038 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,09-13 16:33:59.142   758  3439 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,09-13 16:33:59.262  1451  1451 D Recents : onTaskStackChanged
,09-13 16:33:59.272  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,09-13 16:33:59.752   758  1236 V AlarmManager: Expired Alarm result :4
,09-13 16:33:59.772   758  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 16:33:59.772   758  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 16:33:59.772   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{d71b8b1: PendingIntentRecord{6ed9c4b com.google.android.gms broadcastIntent}}
,09-13 16:33:59.812   758  2068 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:33:59.812   758  2068 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4305, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 16:33:59.812   758  2068 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 16:33:59.822   758  2068 D BatteryService: stay LED for charging
,09-13 16:33:59.822   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:59.822   758   758 I MotionRecognitionService: Plugged
,09-13 16:33:59.822   758   758 D MotionRecognitionService:   cableConnection= 1
,09-13 16:33:59.822   758   758 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 16:33:59.822   758   758 D MotionRecognitionService: skip setTransmitPower. 
,09-13 16:33:59.822  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:59.822  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 16:33:59.822  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:59.832  2373  2373 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:33:59.832  2373  2784 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:33:59.842  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:59.852  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:59.852  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:59.942   758  3435 D SSRM:n  : SIOP:: AP = 480, PST = 464, CUR = 300, LCD = 0
,09-13 16:33:59.952   758  3435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:33:59.992   758  1236 V AlarmManager: Expired Alarm result :8
,09-13 16:34:01.442   758  3478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:34:02.862   758   924 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 16:34:02.882   758   924 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 16:34:04.162   758  3435 D M       : limitCPUFreq:: freq = 1728000
,09-13 16:34:04.172   758  3435 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 758  pkgName : SIOP_ARM_MAX@25
,09-13 16:34:04.172   758  3435 D M       : limitGPUFreq:: freq = 389000000
,09-13 16:34:04.192   758  3435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:34:04.362   758   924 D PackageManager: [MSG] MCS_UNBIND
,09-13 16:34:04.382   758  1417 I ActivityManager: Killing 5397:com.policydm/1000 (adj 15): DHA:empty #37
,09-13 16:34:04.382   758  1417 I ActivityManager: Killing 5830:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,09-13 16:34:04.422   758  3724 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,09-13 16:34:04.442   758  1778 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,09-13 16:34:04.452  6409  6409 D AASAservice: onDestroy()
,09-13 16:34:04.452  6409  6409 I art     : System.exit called, status: 80
,09-13 16:34:04.452  6409  6409 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,09-13 16:34:04.462   758  1274 I ActivityManager: Process com.samsung.aasaservice (pid 6409)(adj 0) has died(76,709)
,09-13 16:34:04.462   758  1274 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,09-13 16:34:04.512   351   351 I Zygote  : Process 6409 exited cleanly (80)
,09-13 16:34:06.312  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:34:06.312  6258  6355 I jxcore-log: 
,09-13 16:34:06.312  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:34:06.312  6258  6355 I jxcore-log: 
,09-13 16:34:06.322  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:06.322  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:06.322  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:06.332  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:06.332  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:34:06.332  6258  6355 I jxcore-log: 
,09-13 16:34:06.332  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:34:06.332  6258  6355 I jxcore-log: 
,09-13 16:34:07.002  6258  6355 I jxcore-log: Unit Test app is loaded
09-13 16:34:07.002  6258  6355 I jxcore-log: 
,09-13 16:34:07.012  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:07.012  6258  6355 I jxcore-log: 
,09-13 16:34:07.012  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:34:07.012  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6d898c added. We now have 2 listener(s)
,09-13 16:34:07.022  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 16:34:07.022  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:07.022  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:34:07.022  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:07.022  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd468d5 added. We now have 2 listener(s)
09-13 16:34:07.022  6258  6355 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:07.022  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:07.022  6258  6258 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 16:34:07.022  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:07.032  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:07.032  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:07.032  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:07.032  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:07.032  6258  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:34:07.032  6258  6355 D ExecuteNativeTests: Running unit tests
,09-13 16:34:07.042  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:07.042  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:07.042  6258  6355 D BluetoothAdapter: enable()
,09-13 16:34:07.052  6258  6355 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:34:07.062   758   848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{66122 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{637ef7e 2415:com.samsung.android.providers.context/u0a174}
,09-13 16:34:07.072  6258  6355 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,09-13 16:34:07.072   758  1795 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,09-13 16:34:07.072   758  1795 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,09-13 16:34:07.082   758  1795 D WifiService: setWifiEnabled: true pid=6258, uid=10004
,09-13 16:34:07.082   758  1795 W ActivityManager: Permission Denial: getCurrentUser() from pid=6258, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,09-13 16:34:07.092   758  1795 W WifiService: Failed getting userId using ActivityManagerNative
09-13 16:34:07.092   758  1795 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6258, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
09-13 16:34:07.092   758  1795 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28202)
09-13 16:34:07.092   758  1795 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2437)
09-13 16:34:07.092   758  1795 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2425)
09-13 16:34:07.092   758  1795 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
09-13 16:34:07.092   758  1795 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 16:34:07.092   758  1795 D SettingsProvider: isChangeAllowed() : name = wifi_on
,09-13 16:34:07.092   758  1325 D WifiController: [FCC]setFccChannel() is called !!!
09-13 16:34:07.092   758  1325 D WifiStateMachine: setFccChannel: channel = 0
09-13 16:34:07.092   758  1325 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,09-13 16:34:07.092  6258  6355 I System.out: Running UT
,09-13 16:34:07.092   758  1324 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,09-13 16:34:07.102   758  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18701 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8638 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,09-13 16:34:07.102   758  1324 D WifiBigDataLog: init : 
,09-13 16:34:07.102   758   848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{69be7b3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{637ef7e 2415:com.samsung.android.providers.context/u0a174}
,09-13 16:34:07.102   758  1324 D WifiStateMachine: setFccChannelNative: channel = 0
09-13 16:34:07.102   758  1324 D WifiNative-wlan0: callSECApiInt - ID [230]
,09-13 16:34:09.142   758   848 I ActivityManager: Waited long enough for: ServiceRecord{9d19c16 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService},
,09-13 16:34:09.823   758  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 16:34:09.833   758  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,09-13 16:34:10.003   758  3435 D SSRM:n  : SIOP:: AP = 440, PST = 461, CUR = 300, LCD = 0
,09-13 16:34:10.052   758  3435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:34:11.513   758  1637 E Watchdog: !@Sync 3 [09-13 16:34:11.521]
,09-13 16:34:14.753   758  1236 V AlarmManager: Expired Alarm result :4
,09-13 16:34:14.822   758  1415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:34:14.822   758  1415 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4377, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 16:34:14.822   758  1415 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 16:34:14.822   758  1415 D BatteryService: stay LED for charging
,09-13 16:34:14.863   758   848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e6f27a u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df8398 2074:com.google.android.gms.persistent/u0a11}
,09-13 16:34:14.882   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{8929a2b: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:14.882  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 16:34:14.882  1379  1379 I PERF    : received broadcast android.intent.action.TIME_TICK
,09-13 16:34:14.882  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 16:34:14.892   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:14.902   313  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 16:34:14.902   313  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 16:34:14.902   313  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 16:34:14.902  1379  1379 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 16:34:14.902   758   758 I MotionRecognitionService: Plugged
09-13 16:34:14.902   758   758 D MotionRecognitionService:   cableConnection= 1
09-13 16:34:14.902   758   758 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 16:34:14.902   758   758 D MotionRecognitionService: skip setTransmitPower. 
,09-13 16:34:14.912  1379  1379 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 16:34:14.912  4878  4956 I Finsky  : [684] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-13 16:34:14.912  2373  2373 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 16:34:14.912  2373  2784 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:34:14.922  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 16:34:14.922  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 16:34:14.922  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
09-13 16:34:14.922  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 16:34:14.922  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 16:34:14.922  1379  1379 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 16:34:14.922  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
09-13 16:34:14.932  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:14.932  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:14.932  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 16:34:14.932  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:14.932  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 16:34:14.932  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:34:14.992  1379  1379 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 16:34:15.052   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{df13021: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:15.182  2074  2074 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:34:15.182  4115  5038 D NetworkUsageDbReporter: Started reporting usage
,09-13 16:34:15.212   758   848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{93556ff u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{df8398 2074:com.google.android.gms.persistent/u0a11}
,09-13 16:34:15.222   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{471eccc: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1621
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3203
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 11386
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3202
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1883
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3201
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1638
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3200
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5346
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3199
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 7456
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3198
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14905
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3197
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 7598
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3196
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 157418
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3195
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 28360
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3193
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 297340
09-13 16:34:15.242  4115  5038 D NetworkUsageDbReporter: keeping row: 3192
,09-13 16:34:15.252  4115  5038 D NetworkUsageDbReporter: Finished reporting usage.
,09-13 16:34:15.282   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{c702b15: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:15.322   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{20ee2a: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:15.352  4878  4956 I Finsky  : [684] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-13 16:34:15.352  4878  4878 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,09-13 16:34:15.382  4115  6702 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-13 16:34:15.382  4115  6702 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-13 16:34:15.462   758  1274 V AlarmManager:  remove PendingIntent] PendingIntent{7b56391: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:15.622  6713  6713 E Zygote  : v2
,09-13 16:34:15.622   758  1417 I ActivityManager: Start proc 6713:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,09-13 16:34:15.622  6713  6713 I libpersona: KNOX_SDCARD checking this for 10011
,09-13 16:34:15.622  6713  6713 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:15.622  6713  6713 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 16:34:15.632  6713  6713 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:34:15.632  6713  6713 E Zygote  : accessInfo : 0
,09-13 16:34:15.632  6713  6713 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,09-13 16:34:15.682  6713  6713 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:15.682  6713  6713 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:15.712  6713  6713 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 16:34:15.782  6713  6713 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 16:34:15.782  6713  6713 I MultiDex: install
,09-13 16:34:15.782  6713  6713 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 16:34:15.852  6713  6713 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,09-13 16:34:15.882  6713  6713 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
09-13 16:34:15.882  6713  6713 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,09-13 16:34:15.892  6713  6713 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 16:34:15.952  6713  6713 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 16:34:15.992  6713  6713 D ChimeraCfgMgr: Reading stored module config
,09-13 16:34:16.202   325   325 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6713)
,09-13 16:34:16.222  6713  6722 I art     : Background sticky concurrent mark sweep GC freed 38995(2MB) AllocSpace objects, 3(144KB) LOS objects, 31% free, 17MB/25MB, paused 9.732ms total 134.143ms
,09-13 16:34:16.262  6713  6727 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 16:34:16.272   325   325 D WVCdm   : Instantiating CDM.
,09-13 16:34:16.272   325   959 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6713)
,09-13 16:34:16.272   325   959 I WVCdm   : CdmEngine::OpenSession
09-13 16:34:16.272   325   959 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-13 16:34:16.282   325   959 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 16:34:16.292   325   959 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,09-13 16:34:16.292   325   959 D DrmWidevineDash: Service_Initialize: starts!
09-13 16:34:16.292   325   959 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-13 16:34:16.292   325   959 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 16:34:16.292   325   959 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
,09-13 16:34:16.292   325   959 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-13 16:34:16.292   325   959 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-13 16:34:16.292   325   959 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 16:34:16.292   325   959 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-13 16:34:16.292   325   959 E QSEECOMAPI: : Error::Loading image failed with ret = -1
,09-13 16:34:16.292   325   959 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-13 16:34:16.292   325   959 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 16:34:16.302  6713  6724 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 16:34:16.302  6713  6724 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:16.312   313  1198 D EnterpriseController: netId is 0
09-13 16:34:16.312   313  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:34:16.312   313  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 16:34:16.312   313  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 16:34:16.312   313  1194 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 16:34:16.332   325   959 D QSEECOMAPI: : Loaded image: APP id = 3
,09-13 16:34:16.332   325   959 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-13 16:34:16.332   325   959 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef56000
,09-13 16:34:16.332   325   959 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef56000
,09-13 16:34:16.362   325   959 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-13 16:34:16.362   325   959 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-13 16:34:16.362   325   959 D DrmWidevineDash: hlos api version =  10
,09-13 16:34:16.362   325   959 D DrmWidevineDash: tz api version =  10
,09-13 16:34:16.362   325   959 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,09-13 16:34:16.372   325   959 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-13 16:34:16.382   325   959 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-13 16:34:16.382   325   959 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,09-13 16:34:16.382   325   959 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf07e924
,09-13 16:34:16.392   325   959 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-13 16:34:16.392   325   959 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-13 16:34:16.392   325   959 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xae2126b8, dataLength=8
,09-13 16:34:16.392   325   959 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-13 16:34:16.392   325   959 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1d8d800, wrapped_rsa_key_length=1280
,09-13 16:34:16.402   325   959 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-13 16:34:16.402   325   959 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 16:34:16.402   325   325 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-13 16:34:16.402   325   325 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-13 16:34:16.402   325   325 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-13 16:34:16.402   325   325 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xad4fd300, idLength=0xbeb88cbc
,09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
,09-13 16:34:16.412   325   325 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-13 16:34:16.412   325   325 D DrmWidevineDash: hlos api version =  10
,09-13 16:34:16.412   325   325 D DrmWidevineDash: tz api version =  10
09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,09-13 16:34:16.422   325   325 D WVCdm   : PrepareKeyRequest: nonce=496978712
,09-13 16:34:16.422   325   325 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d83c00
09-13 16:34:16.422   325   325 D DrmWidevineDash: message_length=1631, signature=0xae9d7680, signature_length=3199765908
,09-13 16:34:16.472  6713  6724 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6713, getuid(): 10011
,09-13 16:34:16.512   325   325 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-13 16:34:16.512   325   942 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6713)
,09-13 16:34:16.512   325   942 I WVCdm   : CdmEngine::CloseSession
09-13 16:34:16.512   325   942 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-13 16:34:16.522   325   942 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-13 16:34:16.522   325   942 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,09-13 16:34:16.522   325   942 D DrmWidevineDash: Service_Uninitialize: starts!
09-13 16:34:16.522   325   942 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-13 16:34:16.522   325   942 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,09-13 16:34:16.522   325   942 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-13 16:34:16.522   325   942 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-13 16:34:17.262  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:34:17.262  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a added. We now have 3 listener(s)
,09-13 16:34:17.262  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 16:34:17.272  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:17.272  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:34:17.272  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:17.272  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb added. We now have 3 listener(s)
,09-13 16:34:17.272  6258  6355 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:17.272  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:17.272  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:17.282  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:17.282  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:17.282  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.282  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:17.282  6258  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:17.282  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:17.292  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:17.292  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.292  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:34:17.302  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:17.302  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:17.302  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:17.302  6258  6355 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 16:34:17.302  6258  6355 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 16:34:17.302  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 16:34:17.312  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:17.312  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:17.312  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:17.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:17.312  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:17.312  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:17.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:34:17.312  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a removed from the list
,09-13 16:34:17.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:17.312  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb removed from the list
,09-13 16:34:17.312  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:17.312  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:17.312  6258  6355 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 16:34:17.322  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:17.322  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:17.322  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:17.322  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:17.322  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:17.322  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:17.322  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:17.322  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:34:17.322  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 16:34:17.332  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:17.332  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:17.332  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:17.332  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:17.332  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:17.332  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:17.332  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop,
,09-13 16:34:17.332  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:17.332  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:17.332  6258  6355 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:34:17.342  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:17.342  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:17.342  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:17.342  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.352  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:17.352  6258  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:17.352  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:17.352  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:17.352  6258  6355 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-13 16:34:17.352  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 16:34:17.352  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:17.362  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:17.362  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:17.362  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:17.362  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:17.362  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:17.362  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:17.362  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:17.362  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:17.362  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:17.362  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:17.372  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:17.372  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:17.372  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:17.382  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.382  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.382  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.382  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:17.382  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.382  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.392  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 16:34:17.392  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:17.392  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.392  6258  6764 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:34:17.392  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:17.392  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 16:34:17.392  6258  6764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:17.402  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 7C F9 0E 34 8A A0
,09-13 16:34:17.402  6258  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:17.402  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:17.402  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:17.402  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:17.402  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.402  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.402  6258  6355 D BluetoothLeAdvertiser: start advertising
,09-13 16:34:17.402  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.412  2373  2781 D BtGatt.GattService: registerClient() - UUID=de038ce6-3844-4fe7-8457-14ed7fc4666f
,09-13 16:34:17.472  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=de038ce6-3844-4fe7-8457-14ed7fc4666f, clientIf=6
,09-13 16:34:17.472  6258  6269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:17.482  2373  2384 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:34:17.482  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:17.482  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:17.482  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,09-13 16:34:17.482  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:17.482  2373  2560 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:17.492  2373  2560 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 16:34:17.492  2373  2560 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:17.492  2373  2560 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:17.492  2373  2560 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:34:17.492  2373  2578 D bt_vendor: op for 7
,09-13 16:34:17.492  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:17.502  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:17.502  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:17.502  2373  2578 D bt_vendor: op for 7
,09-13 16:34:17.502  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.502  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.502   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{3c65500: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.512   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{7586139: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.512  2373  2519 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:17.512   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{956f37e: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.522   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{9aa40df: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.522  2373  2560 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:17.522  2373  2578 D bt_vendor: op for 7
,09-13 16:34:17.522  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.522  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.522   758  1635 V AlarmManager:  remove PendingIntent] PendingIntent{8bbc12c: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.522  2373  2519 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:17.532  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:17.532  2373  2560 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:17.532  2373  2560 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 16:34:17.532  2373  2560 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 16:34:17.532  6258  6268 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 16:34:17.532  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:17.532  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:17.532  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:17.532  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:17.532  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:17.532  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:17.532  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:17.532  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:17.542  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:17.542  6258  6258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:17.542  6258  6355 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:17.542  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:17.542  6258  6355 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:34:17.542  6258  6355 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:34:17.542  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:34:17.542  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:34:17.542  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:17.552  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:17.552  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:17.552  6258  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:17.552  6258  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:17.552  6258  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:17.552  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 16:34:17.552  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:17.552  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:17.552  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:17.552  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:17.552  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:17.552  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:17.552  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:17.552  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:17.552  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.552  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.552  6258  6355 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:17.552  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:17.552  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:17.562  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.562  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.562  6258  6355 D BluetoothLeAdvertiser: stop advertising
,09-13 16:34:17.562  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:17.562  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:17.562  2373  2560 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:17.562  2373  2560 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 16:34:17.562  2373  2560 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:17.562  2373  2578 D bt_vendor: op for 7
,09-13 16:34:17.562  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.562  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.562  2373  2578 D bt_vendor: op for 7
,09-13 16:34:17.562  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.562  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.572   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{d4d7f5: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.572  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 16:34:17.572  2373  2519 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:34:17.572  2373  2519 D BtGatt.GattService: Client app is not null!
09-13 16:34:17.572  6258  6269 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:34:17.572  2373  2578 D bt_vendor: op for 7
09-13 16:34:17.572  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.572  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.572  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 32
09-13 16:34:17.572  2373  2781 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:17.572  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:17.572  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:17.572  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:17.572  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:17.572  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:17.582   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{eac98a: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.582  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:17.582  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:17.582  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:17.582  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:17.582  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:34:17.582  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:34:17.592   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{81c0bfb: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:17.592  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:17.592  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:17.592  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562954
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:17.592  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 16:34:17.592  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:34:17.592   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{eb9c418: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.592   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{167fe71: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.592  6258  6355 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:34:17.592  6258  6355 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:34:17.592  6258  6355 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 16:34:17.592  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-13 16:34:17.602  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:17.602   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{533f456: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.602  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:17.602  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:17.602  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:17.602  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:34:17.602  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:17.602  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:17.602  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:17.602  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:17.602  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:17.602  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:17.602  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:17.602  6258  6779 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:34:17.602  6258  6779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:17.612  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:34:17.612  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:17.612  6258  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:17.612  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.612  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.612  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.612  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:17.612  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.612  6258  6355 D BluetoothAdapter: STATE_ON
09-13 16:34:17.612  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:17.612  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:17.612  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.622  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:34:17.622  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 16:34:17.622  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 7C F9 0E 34 8A A0
09-13 16:34:17.622  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:17.622  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:17.622  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:17.622  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.622  6258  6355 D BluetoothAdapter: STATE_ON
09-13 16:34:17.622  6258  6355 D BluetoothLeAdvertiser: start advertising
,09-13 16:34:17.622  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.622  2373  2393 D BtGatt.GattService: registerClient() - UUID=41a0a42e-1a4d-4c61-8811-3071e0d858e6
,09-13 16:34:17.662  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=41a0a42e-1a4d-4c61-8811-3071e0d858e6, clientIf=6
,09-13 16:34:17.662  6258  6269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:17.662  2373  2384 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:34:17.672  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:17.672  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:17.672  2373  2560 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:17.672  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:34:17.672  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:17.672  2373  2560 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 16:34:17.672  2373  2560 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:17.682  2373  2560 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:17.682  2373  2560 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:34:17.682  2373  2578 D bt_vendor: op for 7
09-13 16:34:17.682  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.682  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.682  2373  2578 D bt_vendor: op for 7
09-13 16:34:17.682  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.682  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.682   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{312ffe2: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.682  2373  2519 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:17.682  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 33
09-13 16:34:17.682  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562954
,09-13 16:34:17.682  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:34:17.682  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:17.682  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:17.682  2373  2560 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:17.692  2373  2578 D bt_vendor: op for 7
09-13 16:34:17.692  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:17.692  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:17.692   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{3d9ff73: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.692  2373  2519 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:34:17.692  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:34:17.692  2373  2560 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:34:17.692  2373  2560 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:34:17.692  2373  2560 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 16:34:17.692  6258  6268 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:34:17.692  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:17.692  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:17.692  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:17.692  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:17.692  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:17.692  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:17.692  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:17.692  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:17.692  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 16:34:17.692  6258  6355 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:17.692   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{598fe30: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.692  6258  6258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:34:17.692  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:17.702   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{8b70aa9: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.702   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{2e5382e: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:17.702   758  1274 V AlarmManager:  remove PendingIntent] PendingIntent{44b1fcf: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.202  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:18.202  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:18.202  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:18.202  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:18.212  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:18.212  6258  6779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:18.212  6258  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:18.212  6258  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:18.242  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 16:34:18.242  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:18.242  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:18.242  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.242  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:18.242  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:34:18.242  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:18.242  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:18.242  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.242  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.242  6258  6355 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:18.242  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:18.242  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:18.242  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.252  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.252  6258  6355 D BluetoothLeAdvertiser: stop advertising
,09-13 16:34:18.252  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:18.252  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:18.262  2373  2560 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:18.262  2373  2560 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 16:34:18.262  2373  2560 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:18.262  2373  2578 D bt_vendor: op for 7
,09-13 16:34:18.262  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:18.262  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:18.262  2373  2578 D bt_vendor: op for 7
,09-13 16:34:18.262  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:18.262  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:18.272  2373  2519 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:18.272  2373  2519 D BtGatt.GattService: Client app is not null!
,09-13 16:34:18.272  2373  2578 D bt_vendor: op for 7
,09-13 16:34:18.272  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:18.272  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:18.272  6258  6269 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:34:18.272  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:18.272  2373  2393 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:18.272  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:18.272  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:18.272  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:18.272  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:18.272  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:18.282  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:18.282  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:18.282  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:18.282  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:18.282  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
,09-13 16:34:18.282  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.282  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.282  6258  6355 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:34:18.292  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:18.292  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:18.292  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:18.292  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.302  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:18.302  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:18.302  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:18.302  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:18.302   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{503e9eb: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:18.302  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:18.302  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:18.302  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:18.302  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 16:34:18.302  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:18.302  6258  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:18.302  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:34:18.302  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:18.312  6258  6355 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 16:34:18.312  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 16:34:18.312  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 16:34:18.312  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:18.312  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:18.312  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:18.312  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:18.312  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:18.312  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:18.312  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:18.322   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{23539c7: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.322  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:18.322  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:18.322  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:18.322  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:18.322  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.322  6258  6810 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:34:18.322  6258  6810 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:18.322   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{f2e6bf4: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.322  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.322  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.332  6258  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:18.332  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:18.332  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.332   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{e607f1d: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.332  6258  6355 D BluetoothAdapter: STATE_ON
09-13 16:34:18.332  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:18.332  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:18.332   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{33f2592: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.332  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.342  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:34:18.342  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 16:34:18.342  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 7C F9 0E 34 8A A0
09-13 16:34:18.342  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:18.342  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:18.342  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:18.342  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.342  6258  6355 D BluetoothAdapter: STATE_ON
09-13 16:34:18.342  6258  6355 D BluetoothLeAdvertiser: start advertising
,09-13 16:34:18.342  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.342   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{41ab63: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.342  2373  2393 D BtGatt.GattService: registerClient() - UUID=9a3691e6-2000-40a2-83b3-d46089736af1
,09-13 16:34:18.382  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=9a3691e6-2000-40a2-83b3-d46089736af1, clientIf=6
,09-13 16:34:18.382  6258  6268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-13 16:34:18.392  2373  2384 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:34:18.392  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:18.392  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:18.392  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:34:18.392  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:18.392  2373  2560 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:18.402  2373  2560 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 16:34:18.402  2373  2560 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:18.402  2373  2560 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:18.402  2373  2560 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:34:18.402  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 34
09-13 16:34:18.402  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562954
09-13 16:34:18.402  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:34:18.402  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:18.402  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 16:34:18.402  2373  2578 D bt_vendor: op for 7
09-13 16:34:18.402  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:18.402  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
09-13 16:34:18.402  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:18.402   758  1635 V AlarmManager:  remove PendingIntent] PendingIntent{fc05360: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.402  2373  2578 D bt_vendor: op for 7
09-13 16:34:18.402  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:18.402  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:18.412  2373  2519 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:18.412  2373  2560 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:18.412  2373  2578 D bt_vendor: op for 7
09-13 16:34:18.412  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:18.412  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:18.412  2373  2519 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:34:18.412  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:34:18.412  2373  2560 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:34:18.412  2373  2560 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:34:18.412  2373  2560 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 16:34:18.412  6258  6269 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:34:18.412  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:18.412  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:18.412   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{a8af019: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.412  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:18.422  6258  6355 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:18.422  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:18.422  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:18.422  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:18.422  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:18.422  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:18.422  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:18.422  6258  6258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:34:18.422  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:18.422   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{ea608de: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.432   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{d199abf: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.432   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{fc7458c: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.432   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{55174d5: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:18.922  6258  6355 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:34:18.922  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:18.932  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:18.932  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:18.932  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:34:18.932  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:34:18.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:18.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:18.942  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:18.942  6258  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:18.942  6258  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:18.952  6258  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:18.952  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:18.952  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 16:34:18.952  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:18.962  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:18.962  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:34:18.962  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:18.962  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:34:18.962  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:18.972  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:18.972  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.982  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.982  6258  6355 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:18.982  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:18.982  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:18.992  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.992  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.992  6258  6355 D BluetoothLeAdvertiser: stop advertising
,09-13 16:34:19.002  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:19.002  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:19.002  2373  2560 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:19.002  2373  2560 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 16:34:19.002  2373  2560 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:19.012  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.012  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:19.012  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.012  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.012  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.012  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.022  2373  2519 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:19.022  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.022  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.022  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.022  2373  2519 D BtGatt.GattService: Client app is not null!
,09-13 16:34:19.022  6258  6268 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:34:19.022   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{705d4ea: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.032   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{b5723db: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.032   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{7692e78: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.032  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:19.042  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:34:19.042  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:19.042  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 16:34:19.042   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{cc18951: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.042  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:19.042  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 16:34:19.042   758  1635 V AlarmManager:  remove PendingIntent] PendingIntent{be455b6: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.052   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{31a22b7: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.052  2373  2393 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:19.052  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:19.052  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:19.052  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:19.052  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:34:19.052  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:19.062  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.062  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:19.062  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:19.062  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:19.062  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:19.062  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:34:19.062  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:19.062  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:19.062  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.062  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.072  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.072  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:19.072  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:19.072  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.072  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.072  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.072  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.072  6258  6355 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 16:34:19.072  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.072  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.072  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.072  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:19.072  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.072  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.072  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:19.072  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.072  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.072  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 16:34:19.072  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.072  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.072  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.072  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.072  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.072  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.072  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.072  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.082  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.082  6258  6355 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 16:34:19.082  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.082  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.082  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.082  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.082  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.082  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.082  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.082  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.082  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.082  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 16:34:19.082  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.082  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.082  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.082  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.082  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.082  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.082  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.082  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.082  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.082  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:34:19.092  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:19.092  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:19.092  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 16:34:19.092  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:19.092  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:19.092  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:34:19.092  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:19.092  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:19.102  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.102  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.102  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.102  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:19.112  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.112  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.112  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.112  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.112  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:19.112  6258  6355 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:34:19.112  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-13 16:34:19.112  6258  6355 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 16:34:19.112  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:34:19.112  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-13 16:34:19.112  6258  6355 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:19.112  6258  6355 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd,
09-13 16:34:19.112  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:34:19.112  6258  6355 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:19.112  6258  6355 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-13 16:34:19.112  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:19.112  6258  6355 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...,
09-13 16:34:19.112  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 16:34:19.122  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 16:34:19.122  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-13 16:34:19.122  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55,
09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-13 16:34:19.132  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:34:19.132  6258  6355 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:34:19.132  6258  6355 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads,
09-13 16:34:19.132  6258  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 976)
,09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
,09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.132  6258  6355 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.132  6258  6841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 976
09-13 16:34:19.132  6258  6355 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
,09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-13 16:34:19.132  6258  6355 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 16:34:19.132  6258  6355 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-13 16:34:19.132  6258  6355 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:34:19.132  6258  6355 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-13 16:34:19.132  6258  6355 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:34:19.132  6258  6355 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.132  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.132  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:19.132  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.142  6258  6355 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:34:19.162   758  1635 V AlarmManager:  remove PendingIntent] PendingIntent{4a43353: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:19.142  6258  6840 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-13 16:34:19.142  6258  6840 D BluetoothSocket: connect(): myUserId = 0
09-13 16:34:19.142  6258  6840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:19.142  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:19.152  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:19.152  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:34:19.152   758  3724 D SecContentProvider: insert(), uri = 2
,09-13 16:34:19.152  6258  6355 D BluetoothAdapter: STATE_ON
09-13 16:34:19.152  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:19.152  6258  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:34:19.152  6258  6355 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,09-13 16:34:19.152  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 16:34:19.162  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.162  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.162  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.162  2373  2720 W bt_btif : bta_dm_acl_change(), event : 2
09-13 16:34:19.162  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:19.162  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:19.162   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{6bf5490: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:19.162  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:19.162  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:19.162  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:19.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:19.172  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:19.172  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:19.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:19.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 16:34:19.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:19.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:19.172  6258  6842 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:34:19.172  6258  6842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:19.172  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:19.172  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:19.182  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:19.182  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:19.182  6258  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:19.182  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.182  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.182  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.182  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:19.182  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.182  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.182  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:19.182  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:19.192  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:34:19.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 16:34:19.192  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 7C F9 0E 34 8A A0
,09-13 16:34:19.192  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:19.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:19.192  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:19.192  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.192  6258  6355 D BluetoothAdapter: STATE_ON
09-13 16:34:19.192  6258  6355 D BluetoothLeAdvertiser: start advertising
,09-13 16:34:19.192  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.192  2373  2781 D BtGatt.GattService: registerClient() - UUID=71a0fdf7-4370-46a5-94ab-22f5d53bed38
,09-13 16:34:19.202  2373  2773 D bt_upio : ..proc_btwrite_timeout..
09-13 16:34:19.202  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:19.232  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=71a0fdf7-4370-46a5-94ab-22f5d53bed38, clientIf=6
,09-13 16:34:19.232  6258  6269 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:19.242  2373  2393 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:34:19.242  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:19.242  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:19.242  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:34:19.242  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:19.242  2373  2560 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:19.242  2373  2560 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 16:34:19.242  2373  2560 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:19.242  2373  2560 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:19.242  2373  2560 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:34:19.252  2373  2578 D bt_vendor: op for 7
09-13 16:34:19.252  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:19.252  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
09-13 16:34:19.252  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:19.252  2373  2578 D bt_vendor: op for 7
09-13 16:34:19.252  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.252  2373  2578 D bt_upio : BT_WAKE is asserted already
09-13 16:34:19.252  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 35
,09-13 16:34:19.252   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{f6d29bc: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:19.252  2373  2519 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:19.252  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562954
09-13 16:34:19.252  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:34:19.252  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:19.252  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 16:34:19.252  2373  2560 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:19.252  2373  2578 D bt_vendor: op for 7
09-13 16:34:19.252  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.252  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.252  2373  2519 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 16:34:19.252  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:34:19.252  2373  2560 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:34:19.252  2373  2560 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 16:34:19.252  2373  2560 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 16:34:19.252  6258  6268 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 16:34:19.252  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:19.252  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:19.252  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:19.262   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{79a3d45: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.262  6258  6355 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:19.262  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:19.262  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:19.262  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:19.262  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:19.262  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:19.262  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:19.262   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{3b54c9a: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.262  6258  6258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:19.262  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:19.272   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{aa4b9cb: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.272   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{6c125a8: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.272   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{1a668c1: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.772  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:19.772  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:19.772  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:19.772  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.772  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:19.782  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
,09-13 16:34:19.782  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,09-13 16:34:19.792  6258  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:19.792  6258  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:19.792  6258  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:19.802  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 16:34:19.812  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:19.812  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:19.812  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
,09-13 16:34:19.812  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.822  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,09-13 16:34:19.822  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,09-13 16:34:19.822  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,09-13 16:34:19.832  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,09-13 16:34:19.832  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.842  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.842  6258  6355 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:19.842  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:19.842  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:19.842  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:19.852  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.852  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:19.852  6258  6355 D BluetoothLeAdvertiser: stop advertising
,09-13 16:34:19.862  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:19.862  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:19.862  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:34:19.862  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:34:19.862  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 16:34:19.862  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:19.862  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 16:34:19.862  2373  2560 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:19.872  2373  2560 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 16:34:19.872  2373  2560 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:19.872  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.872  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.872  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.872  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.872  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.872  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.872  2373  2519 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:19.872  2373  2578 D bt_vendor: op for 7
,09-13 16:34:19.872  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:19.872  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:19.872  2373  2519 D BtGatt.GattService: Client app is not null!
,09-13 16:34:19.882  6258  6269 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:34:19.882  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:19.882   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{e0b9866: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.882   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{84327a7: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.892   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{cd6f454: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.892   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{2efcffd: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.892  2373  2781 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:19.902   758  1796 V AlarmManager:  remove PendingIntent] PendingIntent{c28d4f2: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.902  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:19.902  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:19.902  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:19.902  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:19.902  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:19.902  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.902  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:19.902  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:19.902  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:19.912  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
,09-13 16:34:19.912  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:19.912  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:19.912  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:19.912  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:19.912  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.912   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{3709743: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:19.922  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.922  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.922  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.922  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.922  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.922  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
,09-13 16:34:19.922  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.922  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.922  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.922  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:19.922  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:19.922  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:19.922  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:19.922  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:19.932  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:19.932  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.932  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.932  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:19.932  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.932  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.932  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:19.932  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:19.932  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.932  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.932  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.932  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.942  6258  6355 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 16:34:19.942  6258  6355 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:34:19.942  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 16:34:19.942  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:19.942  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:19.942  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.942  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.942  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.942  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.942  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.942  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
,09-13 16:34:19.942  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.942  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.942  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.952  6258  6852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:19.962  6258  6852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:19.962  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:19.962  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.962  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.962  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.962  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.962  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.962  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.962  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.962  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.962  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.962  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.962  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.962  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410309a not in the list
09-13 16:34:19.962  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.962  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acfcdcb not in the list
09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.962  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.962  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.962  6258  6355 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 16:34:19.962  6258  6355 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:34:19.962  6258  6355 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 16:34:19.962  6258  6355 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:34:19.962  6258  6355 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:34:19.962  6258  6355 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 16:34:19.962  6258  6355 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:34:19.972  6258  6355 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 16:34:19.972  6258  6355 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 16:34:19.972  6258  6355 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:34:19.972  6258  6355 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:34:19.972  6258  6355 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:34:19.972  6258  6355 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 16:34:19.972  6258  6869 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 16:34:19.972  6258  6869 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:34:20.052  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:20.052  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:20.142   758  3435 D SSRM:n  : SIOP:: AP = 420, PST = 456, CUR = 300, LCD = 0
,09-13 16:34:20.442  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:34:20.492   313  1198 D EnterpriseController: netId is 0
09-13 16:34:20.492   313  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10004
,09-13 16:34:20.512  6258  6869 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 16:34:20.522  6258  6869 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:34:20.522  6258  6869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.522  6258  6869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.522  6258  6869 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:34:20.522  6258  6880 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 16:34:20.532  6258  6880 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:34:20.532  6258  6880 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.532  6258  6880 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.532  6258  6880 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 16:34:20.532  6258  6884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1030, name: OutgoingSocketThread/Receiver)
,09-13 16:34:20.532  6258  6884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1030, thread name: OutgoingSocketThread/Receiver)
,09-13 16:34:20.532  6258  6883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1029, name: OutgoingSocketThread/Sender)
,09-13 16:34:20.542  6258  6884 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 16:34:20.542  6258  6884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1030, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:34:20.542  6258  6885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1031, name: IncomingSocketThread/Sender)
,09-13 16:34:20.542  6258  6886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1032, name: IncomingSocketThread/Receiver)
,09-13 16:34:20.542  6258  6886 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1032, thread name: IncomingSocketThread/Receiver)
,09-13 16:34:20.542  6258  6886 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 16:34:20.542  6258  6886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1032, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:34:21.002  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
,09-13 16:34:21.002  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 16:34:21.012  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@62e45b6 Bundle[{}]
,09-13 16:34:21.022  6258  6355 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:34:21.022  6258  6355 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 16:34:21.022  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:34:21.032  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 16:34:21.032  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 16:34:21.042  6258  6355 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:34:21.062  6258  6887 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 16:34:21.062  6258  6887 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:34:21.382  2373  2578 D bt_vendor: op for 7
,09-13 16:34:21.382  2373  2578 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:21.382  2373  2578 D bt_upio : BT_WAKE is de-asserted already
,09-13 16:34:21.382   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{5d901c0: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:21.442   758  3478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:34:21.582  6258  6887 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 16:34:21.582  6258  6887 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:34:21.592  6258  6887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:21.592  6258  6887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:21.592  6258  6887 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:34:21.602  6258  6889 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 16:34:21.602  6258  6889 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:34:21.612  6258  6889 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:21.612  6258  6889 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:21.612  6258  6889 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 16:34:21.612  6258  6892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1044, name: OutgoingSocketThread/Receiver)
,09-13 16:34:21.612  6258  6892 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1044, thread name: OutgoingSocketThread/Receiver)
,09-13 16:34:21.612  6258  6891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1043, name: OutgoingSocketThread/Sender)
,09-13 16:34:21.612  6258  6892 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:34:21.612  6258  6892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1044, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:34:21.622  6258  6894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1046, name: IncomingSocketThread/Receiver)
,09-13 16:34:21.622  6258  6893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1045, name: IncomingSocketThread/Sender)
,09-13 16:34:21.622  6258  6894 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1046, thread name: IncomingSocketThread/Receiver)
,09-13 16:34:21.622  6258  6894 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 16:34:21.622  6258  6894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1046, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:34:21.662  6713  6724 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6713, getuid(): 10011
,09-13 16:34:22.092  6258  6355 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1055)
,09-13 16:34:22.102  6258  6355 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 16:34:22.102  6258  6355 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1056)
,09-13 16:34:22.112  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:34:22.112  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ccd8 added. We now have 3 listener(s)
,09-13 16:34:22.122  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 16:34:22.122  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:34:22.122  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:34:22.132  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 16:34:22.132  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e23831 added. We now have 3 listener(s)
09-13 16:34:22.132  6258  6355 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:22.132  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:22.142  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:22.142  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:22.142  6258  6355 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:22.152  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.152  6258  6355 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:22.152  6258  6355 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:22.152  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:22.162  6258  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:22.162  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.162  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:22.162  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:22.162  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:22.162  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:34:22.162  6258  6355 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ccd8 removed from the list
,09-13 16:34:22.162  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:22.162  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e23831 removed from the list
,09-13 16:34:22.162  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:22.162  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:22.172  6258  6355 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-13 16:34:22.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 16:34:22.172  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
,09-13 16:34:22.172  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:22.172  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:22.172  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:22.182  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:22.182  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:22.182  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:22.182  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:22.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:22.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:22.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:22.192  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:22.192  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:22.192  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:22.202  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.202  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.202  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.202  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:22.202  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.202  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.202  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:22.202  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:22.202  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.212  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:22.212  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 16:34:22.212  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 7C F9 0E 34 8A A0
,09-13 16:34:22.212  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:22.212  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:22.212  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:22.212  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.212  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.212  6258  6355 D BluetoothLeAdvertiser: start advertising
,09-13 16:34:22.212  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:22.212  6258  6896 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:34:22.212  6258  6896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:22.212  2373  2781 D BtGatt.GattService: registerClient() - UUID=d8bf6f0d-6deb-4456-a3c4-9e619ca0d895
,09-13 16:34:22.222  6258  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:22.262  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=d8bf6f0d-6deb-4456-a3c4-9e619ca0d895, clientIf=6
,09-13 16:34:22.262  6258  6268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:22.262  2373  2384 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:34:22.262  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:22.262  2373  2384 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:22.262  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:34:22.262  2373  2560 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:22.272  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:22.272  2373  2560 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 16:34:22.272  2373  2560 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:22.272  2373  2560 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:22.272  2373  2560 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:34:22.272  2373  2578 D bt_vendor: op for 7
,09-13 16:34:22.272  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:22.282  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:22.282  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:22.282  2373  2578 D bt_vendor: op for 7
,09-13 16:34:22.282  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:22.292  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:22.292   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{43babbb: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:22.292  2373  2519 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:22.302  2373  2560 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:22.302  2373  2578 D bt_vendor: op for 7
,09-13 16:34:22.302  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:22.302  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:22.312  2373  2519 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:22.312  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:22.312  2373  2560 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:22.312  2373  2560 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 16:34:22.312  2373  2560 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 16:34:22.312  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 36
,09-13 16:34:22.312  6258  6269 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 16:34:22.322   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{95d48d8: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:22.322   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{7fa0431: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:22.332   758  1796 V AlarmManager:  remove PendingIntent] PendingIntent{1a0e716: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:22.332  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562954
,09-13 16:34:22.332  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:34:22.332  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 16:34:22.332  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:22.332  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:22.332  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:22.332  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:22.342   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{8ef4897: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:22.342  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:22.342  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:22.342  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:22.342  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:22.342  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:22.342  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:22.342  6258  6258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:22.352  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:22.862  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:34:22.862  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:22.862  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:23.092  2373  2773 D bt_upio : ..proc_btwrite_timeout..
09-13 16:34:23.092  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:23.812  2373  2578 D bt_vendor: op for 7
,09-13 16:34:23.812  2373  2578 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:23.812  2373  2578 D bt_upio : BT_WAKE is de-asserted already
,09-13 16:34:23.812   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{1ca1a84: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:24.942   758  3724 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:34:24.952   758  3724 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4363, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 16:34:24.952   758  3724 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 16:34:24.952   758  3724 D BatteryService: stay LED for charging
,09-13 16:34:24.963   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:24.973   758   758 I MotionRecognitionService: Plugged
,09-13 16:34:24.973   758   758 D MotionRecognitionService:   cableConnection= 1
,09-13 16:34:24.973   758   758 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 16:34:24.973   758   758 D MotionRecognitionService: skip setTransmitPower. 
,09-13 16:34:24.993  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:24.993  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:24.993  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:34:25.012  2373  2373 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:34:25.022  2373  2784 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:34:25.022  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:25.022  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:25.022  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:25.363  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:34:25.363  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:34:25.363  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:25.363  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:25.363  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:25.373  6258  6896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:25.373  6258  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:25.373  6258  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:25.383  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:25.383  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:25.383  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:25.383  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:25.393  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:34:25.393  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:25.393  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:34:25.393  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:25.393  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:25.402  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.402  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.402  6258  6355 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:25.412  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:25.412  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:25.412  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.412  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.412  6258  6355 D BluetoothLeAdvertiser: stop advertising
,09-13 16:34:25.422  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:25.422  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:25.422  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:34:25.422  2373  2560 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:25.422  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:25.422  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 16:34:25.422  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 16:34:25.422  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 16:34:25.422  2373  2560 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 16:34:25.422  2373  2560 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:25.422  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:25.422  2373  2578 D bt_vendor: op for 7
,09-13 16:34:25.422  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:25.432  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:25.432  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:25.432   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d39b26d: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.432  2373  2578 D bt_vendor: op for 7
,09-13 16:34:25.432  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.432  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.432  2373  2519 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:25.432  2373  2578 D bt_vendor: op for 7
,09-13 16:34:25.432  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.432  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.432  2373  2519 D BtGatt.GattService: Client app is not null!
,09-13 16:34:25.443  6258  6268 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:34:25.443  2373  2384 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:25.453   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{33c5ea2: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.453   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{8d5d733: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.463   758  1796 V AlarmManager:  remove PendingIntent] PendingIntent{f105af0: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.463   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{b4c0869: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.463  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:25.463  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:25.463  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:25.463  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:25.463  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:25.473  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:25.473  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:25.473  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:25.473  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:25.473  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:25.473  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:34:25.473  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:25.473  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:25.473  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:25.473  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:25.473  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:25.482  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:25.482  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ccd8 not in the list
09-13 16:34:25.482  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:25.482  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e23831 not in the list
,09-13 16:34:25.482  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:25.482  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:25.482  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:25.482  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:34:25.482  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:25.482  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 16:34:25.482  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:34:25.482  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:25.482  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:25.482  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:25.492  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:25.492  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.492  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.492  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.492  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:25.492  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.492  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.492  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:25.492  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:25.502  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.502  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.502  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 16:34:25.512  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.512  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.512  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 16:34:25.512  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 16:34:25.512  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 16:34:25.512  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 16:34:25.512  6258  6355 D BluetoothLeScanner: Start Scan
,09-13 16:34:25.522  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.522  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.522  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.522  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.532  2373  2384 D BtGatt.GattService: registerClient() - UUID=d9a1d5d0-5a0a-45cf-8467-bc50376ecf85
,09-13 16:34:25.562  2373  2720 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 16:34:25.562  2373  2720 E bt_btif_sock_rfcomm: SDP - Failed to look up a channel number to connect to
,09-13 16:34:25.562  2373  2720 W bt_btif : bta_dm_acl_change(), event : 2
,09-13 16:34:25.562  2373  2720 W bt_btif : bta_dm_acl_change(), event : 5
,09-13 16:34:25.562  2373  2860 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
,09-13 16:34:25.572  6258  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 976)
,09-13 16:34:25.582  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=d9a1d5d0-5a0a-45cf-8467-bc50376ecf85, clientIf=6
,09-13 16:34:25.582  6258  6269 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:25.582  2373  2514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc5282e
,09-13 16:34:25.582  2373  2393 D BtGatt.GattService: start scan with filters
09-13 16:34:25.582  2373  2519 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,09-13 16:34:25.582  2373  2393 D BtGatt.GattService: getScanSettings
,09-13 16:34:25.592  2373  2519 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 16:34:25.592  2373  2519 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,09-13 16:34:25.592  2822  2822 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-13 16:34:25.592  2373  2393 D BtGatt.GattService: Is it foreground application = false
,09-13 16:34:25.592  2373  2393 D BtGatt.GattService: not a background application
,09-13 16:34:25.602  2373  2393 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-13 16:34:25.602  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:25.602  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:25.612  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
,09-13 16:34:25.612  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:25.612  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 16:34:25.612  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 16:34:25.612  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 16:34:25.612  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 16:34:25.612  2373  2562 D BtGatt.ScanManager: handling starting scan
09-13 16:34:25.612  2373  2562 D BtGatt.ScanManager: isFilteringSupported
09-13 16:34:25.612  2373  2562 D BluetoothAdapter: enableStandAloneBleMode=
,09-13 16:34:25.622  2373  2562 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.622  2373  2562 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.622  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 54
09-13 16:34:25.622  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-13 16:34:25.622  2373  2562 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.622  2373  2562 D BluetoothAdapter: STATE_ON
09-13 16:34:25.622  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:34:25.622  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:25.622  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 16:34:25.622  2373  2562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc5282e
,09-13 16:34:25.622  2373  2578 D bt_vendor: op for 7
09-13 16:34:25.622  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.622  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.632   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{f13c225: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.632  2373  2519 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 16:34:25.632  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:25.632  2373  2562 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-13 16:34:25.632  2373  2562 D BtGatt.ScanManager: High Rssi Filter value is = -128
,09-13 16:34:25.632  2373  2562 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-13 16:34:25.632  2373  2562 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-13 16:34:25.632  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1606
,09-13 16:34:25.632  2373  2578 D bt_vendor: op for 7
09-13 16:34:25.632  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.632  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.632  2373  2519 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 16:34:25.632  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:25.632   758  1635 V AlarmManager:  remove PendingIntent] PendingIntent{e2f1ffa: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.642  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:25.642   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{b2af9ab: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.652  2373  2562 D BtGatt.ScanManager: Starting BLE batch scan
09-13 16:34:25.652  2373  2562 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 16:34:25.652  2373  2578 D bt_vendor: op for 7
09-13 16:34:25.652  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.652  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.652  2373  2578 D bt_vendor: op for 7
09-13 16:34:25.652  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.652  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.652  2373  2519 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 16:34:25.652  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:25.652  2373  2578 D bt_vendor: op for 7
09-13 16:34:25.652  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:25.652  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:25.652  2373  2519 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 16:34:25.652  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:25.652   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{ea09808: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.652  2373  2574 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562954
,09-13 16:34:25.652  2373  2574 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-13 16:34:25.662   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{6e35ba1: PendingIntentRecord{43f41c6 com.android.bluetooth broadcastIntent}}
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
,09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
,09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
,09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
09-13 16:34:25.662  2373  2574 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562954
,09-13 16:34:25.662   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{a1d8587: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.672   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{aab2cb4: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.682   758  1635 V AlarmManager:  remove PendingIntent] PendingIntent{9b910dd: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.682   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{eddb452: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.682   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{ac2f323: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:25.692   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{b286020: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.092  2373  2514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc5282e
,09-13 16:34:26.122   758   848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63addd9 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{637ef7e 2415:com.samsung.android.providers.context/u0a174}
,09-13 16:34:26.122  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 16:34:26.132  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:26.132  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:26.232  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:26.232  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:26.662   758  1236 V AlarmManager: Expired Alarm result :4
,09-13 16:34:26.662  2373  2373 D BtGatt.ScanManager: awakened up at time 136561
,09-13 16:34:26.662  2373  2562 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:26.672  2373  2578 D bt_vendor: op for 7
,09-13 16:34:26.672  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:26.672  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:26.672  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:26.672  2373  2578 D bt_vendor: op for 7
,09-13 16:34:26.672  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:26.672  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:26.672  2373  2578 D bt_vendor: op for 7
,09-13 16:34:26.672  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:26.672  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:26.672  2373  2519 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
,09-13 16:34:26.672  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:26.672  2373  2519 D BtGatt.GattService: current time is 136572302973,
,09-13 16:34:26.682  2373  2519 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0, 71, -122, -77, 84, 69, -12, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -76, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -77, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -77, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 16:34:26.682   758   774 V AlarmManager:  remove PendingIntent] PendingIntent{c79e7f: PendingIntentRecord{43f41c6 com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.682  2373  2519 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
,09-13 16:34:26.682  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:26.682  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 16:34:26.692  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:26.692  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.692  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 16:34:26.692  2373  2519 D ScanRecord: parseFromBytes
09-13 16:34:26.692  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.692  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 16:34:26.692  2373  2519 D ScanRecord: parseFromBytes
09-13 16:34:26.692  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.692  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-13 16:34:26.692  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:26.692  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.692  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 16:34:26.692  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:26.692  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.692   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{c835e4c: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.702  6258  6268 D ScanRecord: parseFromBytes
,09-13 16:34:26.702  6258  6268 D ScanRecord: first manudata for manu ID
09-13 16:34:26.702  6258  6268 D ScanRecord: parseFromBytes
,09-13 16:34:26.702  6258  6268 D ScanRecord: first manudata for manu ID
09-13 16:34:26.702  6258  6268 D ScanRecord: parseFromBytes
,09-13 16:34:26.702  6258  6268 D ScanRecord: parseFromBytes
09-13 16:34:26.702  6258  6268 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.702  6258  6268 D ScanRecord: parseFromBytes
09-13 16:34:26.702  6258  6268 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.702  6258  6268 D ScanRecord: parseFromBytes
09-13 16:34:26.702  6258  6268 D ScanRecord: first manudata for manu ID
,09-13 16:34:26.712  6258  6258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 6], added - the peer count is 1
,09-13 16:34:26.712  6258  6258 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 6], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-13 16:34:26.712   758  1274 V AlarmManager:  remove PendingIntent] PendingIntent{5727e95: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.712   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{8f7baa: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.722   758  1796 V AlarmManager:  remove PendingIntent] PendingIntent{441a39b: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.722   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{4ae1338: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:26.722   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d496f11: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:27.472  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:27.472  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:27.692   758  1236 V AlarmManager: Expired Alarm result :4
,09-13 16:34:27.692  2373  2373 D BtGatt.ScanManager: awakened up at time 137591
,09-13 16:34:27.702  2373  2562 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:27.702  2373  2578 D bt_vendor: op for 7
,09-13 16:34:27.702  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:27.702  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:27.712  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:27.722  2373  2578 D bt_vendor: op for 7
,09-13 16:34:27.722  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:27.722  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:27.722  2373  2519 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
,09-13 16:34:27.732  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:27.732  2373  2519 D BtGatt.GattService: current time is 137626628390
,09-13 16:34:27.732   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{e8cde77: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:27.742  2373  2519 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0, 81, 34, 97, 112, -14, -5, 1, -128, -77, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -77, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 16:34:27.742   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{4cd2ae4: PendingIntentRecord{43f41c6 com.android.bluetooth broadcastIntent}}
,09-13 16:34:27.742  2373  2519 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
,09-13 16:34:27.752  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:27.752  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 16:34:27.762  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:27.762  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:27.772  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 16:34:27.772  2373  2519 D ScanRecord: parseFromBytes
09-13 16:34:27.772  2373  2519 D ScanRecord: first manudata for manu ID
09-13 16:34:27.772  2373  2519 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 16:34:27.772  2373  2519 D ScanRecord: parseFromBytes
09-13 16:34:27.772  2373  2519 D ScanRecord: first manudata for manu ID
,09-13 16:34:27.772  6258  6269 D ScanRecord: parseFromBytes
,09-13 16:34:27.772  6258  6269 D ScanRecord: first manudata for manu ID
09-13 16:34:27.772  6258  6269 D ScanRecord: parseFromBytes
,09-13 16:34:27.772  6258  6269 D ScanRecord: first manudata for manu ID
09-13 16:34:27.772  6258  6269 D ScanRecord: parseFromBytes
,09-13 16:34:27.772  6258  6269 D ScanRecord: first manudata for manu ID
09-13 16:34:27.772  6258  6269 D ScanRecord: parseFromBytes
,09-13 16:34:27.782  6258  6258 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:37:96:AB 6] updated - the peer count is 1
,09-13 16:34:27.782   758  1274 V AlarmManager:  remove PendingIntent] PendingIntent{ec4eb4d: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:27.792   758  3724 V AlarmManager:  remove PendingIntent] PendingIntent{417d602: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:27.802   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{8e6eb13: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.112   758   768 I art     : Background partial concurrent mark sweep GC freed 47620(2MB) AllocSpace objects, 25(500KB) LOS objects, 27% free, 42MB/58MB, paused 2.540ms total 150.927ms
,09-13 16:34:28.512  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:28.512  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:28.652  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:28.652  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:28.652  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:28.652  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ccd8 not in the list
,09-13 16:34:28.652  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:28.652  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:28.652  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,09-13 16:34:28.652  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,09-13 16:34:28.662  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,09-13 16:34:28.662  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,09-13 16:34:28.672  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.672  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.672  6258  6355 D BluetoothLeScanner: Stop Scan
,09-13 16:34:28.692  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:28.692  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:28.692  2373  2393 D BtGatt.GattService: stopScan() - queue size =1
,09-13 16:34:28.692  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,09-13 16:34:28.692  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:28.692  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,09-13 16:34:28.692  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 2 => 2
,09-13 16:34:28.692  2373  2562 D BtGatt.ScanManager: filter size is 1
,09-13 16:34:28.692  2373  2562 D BtGatt.ScanManager: delete FilterIndex - 3
,09-13 16:34:28.702  2373  2578 D bt_vendor: op for 7
,09-13 16:34:28.702  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:28.702  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:28.702  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:28.702  2373  2519 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 16:34:28.702   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{9a41150: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.702  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:28.712   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{c01ef49: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.712  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 2 => 2
,09-13 16:34:28.712  2373  2562 D BtGatt.ScanManager: stopping BLe Batch
,09-13 16:34:28.712  2373  2578 D bt_vendor: op for 7
,09-13 16:34:28.712  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:28.712  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:28.722  2373  2519 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-13 16:34:28.722  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:28.722  2373  2384 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:28.722  2373  2562 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:28.722  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-13 16:34:28.722  2373  2578 D bt_vendor: op for 7
,09-13 16:34:28.722  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:28.722  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:28.722  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-13 16:34:28.722  2373  2578 D bt_vendor: op for 7
,09-13 16:34:28.722  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:28.722  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:28.732  2373  2519 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,09-13 16:34:28.732  2373  2519 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:28.732  2373  2519 D BtGatt.GattService: current time is 138625431306
,09-13 16:34:28.732  2373  2519 D BtGatt.GattService: Batch record : [76, 32, 1, -36, -22, 99, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -8, -49, -59, -39, -27, 97, 0]
,09-13 16:34:28.732  2373  2519 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -8, -49, -59, -39, -27, 97]
09-13 16:34:28.732  2373  2519 D ScanRecord: parseFromBytes
,09-13 16:34:28.732   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{f31504e: PendingIntentRecord{43f41c6 com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.732   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{8cb256f: PendingIntentRecord{43f41c6 com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.732  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:28.732  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:28.732  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 16:34:28.742  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 16:34:28.742  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 16:34:28.742  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:28.742  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.742  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.742  6258  6355 D BluetoothLeAdvertiser: stop advertising
09-13 16:34:28.742  6258  6355 D BluetoothLeAdvertiser: wrapper is null
09-13 16:34:28.742  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:28.742  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:28.742  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:28.742  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:28.742  6258  6355 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-13 16:34:28.742  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e23831 not in the list
,09-13 16:34:28.742  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:28.742  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:28.752  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:28.752  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:28.752  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:28.752  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:28.752   758  1274 V AlarmManager:  remove PendingIntent] PendingIntent{6c0f27c: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.752  6258  6355 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 16:34:28.752  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 16:34:28.752  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:28.752  6258  6355 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:28.752  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:28.762  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:28.762  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:28.762  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:28.762  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:28.762  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:28.762  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:28.762  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 16:34:28.762  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:28.762  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:28.772   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{868ba68: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.772  6258  6355 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:28.772  6258  6355 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:28.782  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.782  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.782  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.782  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:28.782  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.782  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.782  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:28.782  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:28.792  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.792  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:28.792  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 16:34:28.792  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 7C F9 0E 34 8A A0
,09-13 16:34:28.792  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:28.792  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:28.792  6258  6355 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:28.792   758  1274 V AlarmManager:  remove PendingIntent] PendingIntent{1d33e81: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.792  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.792  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.792  6258  6355 D BluetoothLeAdvertiser: start advertising
,09-13 16:34:28.792  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.812  6258  6952 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:34:28.812  6258  6952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:28.812  2373  2781 D BtGatt.GattService: registerClient() - UUID=6a406871-5f1f-467f-bc72-859a613f7f99
,09-13 16:34:28.812  6258  6952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:28.812   758  1629 V AlarmManager:  remove PendingIntent] PendingIntent{cc31b26: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.822   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{6bc5367: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.822   758  1417 V AlarmManager:  remove PendingIntent] PendingIntent{8431514: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.862  2373  2519 D BtGatt.GattService: onClientRegistered() - UUID=6a406871-5f1f-467f-bc72-859a613f7f99, clientIf=6
,09-13 16:34:28.862  6258  6268 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:28.862  2373  2393 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 16:34:28.862  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 16:34:28.862  2373  2393 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:28.862  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 16:34:28.862  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 16:34:28.862  2373  2560 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:28.872  2373  2560 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 16:34:28.872  2373  2560 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:28.872  2373  2560 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:28.872  2373  2560 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 16:34:28.872  2373  2578 D bt_vendor: op for 7
09-13 16:34:28.872  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:28.872  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:28.872  2373  2574 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 37
,09-13 16:34:28.872  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562954
09-13 16:34:28.872  2373  2574 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 16:34:28.872  2373  2578 D bt_vendor: op for 7
09-13 16:34:28.872  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:28.872  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:28.872  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 16:34:28.872  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:28.882  2373  2519 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:28.882   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{67441bd: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.882  2373  2560 D BtGatt.AdvertiseManager: starting multi advertising
09-13 16:34:28.882  2373  2578 D bt_vendor: op for 7
09-13 16:34:28.882  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:28.882  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:28.882  2373  2519 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:28.882  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 16:34:28.882  2373  2560 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 16:34:28.882  2373  2560 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 16:34:28.882  2373  2560 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 16:34:28.882   758  1415 V AlarmManager:  remove PendingIntent] PendingIntent{b5c3b2: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:28.882  6258  6269 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 16:34:28.882  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:28.882  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:28.882  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:28.892   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{cb0bf03: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.892  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:28.892  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:28.892  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:28.892  6258  6258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:28.892  6258  6258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:28.892  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:28.892  6258  6258 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:34:28.892  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:28.892   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{c66e80: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:28.902   758  2068 V AlarmManager:  remove PendingIntent] PendingIntent{1283cb9: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:29.402  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:29.402  6258  6258 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:29.402  6258  6258 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:29.512  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:29.512  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:30.212   758  3435 D SSRM:n  : SIOP:: AP = 400, PST = 444, CUR = 300, LCD = 0
,09-13 16:34:30.212   758  3435 D M       : limitCPUFreq:: freq = -1
,09-13 16:34:30.222   758  3435 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 758  tag : SIOP_ARM_MAX@25
,09-13 16:34:30.222   758  3435 D M       : limitGPUFreq:: freq = -1
,09-13 16:34:30.232   758  3435 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,09-13 16:34:30.282  2811  2811 D ContentApp:  LEVEL : 1
,09-13 16:34:30.292  6981  6981 E Zygote  : v2
,09-13 16:34:30.302   758   848 I ActivityManager: Start proc 6981:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,09-13 16:34:30.302   758  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-13 16:34:30.302  6981  6981 I libpersona: KNOX_SDCARD checking this for 10053
,09-13 16:34:30.312  6981  6981 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:30.312  6981  6981 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 16:34:30.312   758  3435 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 16:34:30.312  6981  6981 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:34:30.322  6981  6981 E Zygote  : accessInfo : 0
,09-13 16:34:30.322  6981  6981 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,09-13 16:34:30.382  2373  2578 D bt_vendor: op for 7
,09-13 16:34:30.382  2373  2578 D bt_upio : upio_set : pio 0 action 1, polarity 1
09-13 16:34:30.382  2373  2578 D bt_upio : BT_WAKE is de-asserted already
,09-13 16:34:30.432   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{b868fe: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:30.432  6981  6981 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:30.432  6981  6981 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:30.462   758  1635 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6485f u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b63f2ac 6981:com.sec.android.app.videoplayer/u0a53}
,09-13 16:34:30.462   758  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-13 16:34:30.472  6981  6981 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,09-13 16:34:30.522  6981  6981 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,09-13 16:34:30.582  6981  6981 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,09-13 16:34:30.672  6981  6981 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 16:34:30.682  6981  6981 D videowall-Global: core_num = 4
,09-13 16:34:30.702  6981  6981 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
09-13 16:34:30.702  6981  6981 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,09-13 16:34:30.712  6981  6981 D TranscodeReceiver:  SIOP_LEVEL: 1
,09-13 16:34:32.402  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:32.402  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:32.402  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
,09-13 16:34:32.402  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,09-13 16:34:32.412  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:32.412  6258  6355 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:32.412  6258  6258 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:32.412  6258  6952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:32.412  6258  6952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:32.422  6258  6952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:32.422  6258  6258 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:32.422  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ccd8 not in the list
,09-13 16:34:32.422  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:32.432  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:32.432  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:34:32.432  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:32.432  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:32.442  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:32.452  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:32.452  6258  6355 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:32.452  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:32.452  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:32.462  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:32.462  6258  6355 D BluetoothAdapter: STATE_ON
,09-13 16:34:32.462  6258  6355 D BluetoothLeAdvertiser: stop advertising
,09-13 16:34:32.482  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:32.482  2373  2781 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 16:34:32.482  2373  2574 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 16:34:32.482  2373  2574 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 16:34:32.482  2373  2574 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 16:34:32.482  2373  2574 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 16:34:32.482  2373  2574 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 16:34:32.492  2373  2560 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:32.492  2373  2560 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 16:34:32.492  2373  2560 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 16:34:32.492  2373  2578 D bt_vendor: op for 7
,09-13 16:34:32.492  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 16:34:32.492  2373  2560 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:32.492  2373  2578 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 16:34:32.502  2373  2578 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 16:34:32.502  2373  2578 D bt_vendor: op for 7
,09-13 16:34:32.502  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:32.502  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:32.502  2373  2519 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:32.502   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{a86eb75: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:32.502  2373  2578 D bt_vendor: op for 7
,09-13 16:34:32.502  2373  2578 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 16:34:32.512  2373  2578 D bt_upio : BT_WAKE is asserted already
,09-13 16:34:32.512  2373  2519 D BtGatt.GattService: Client app is not null!
,09-13 16:34:32.512  6258  6268 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 16:34:32.522  2373  2393 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:32.522   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{8ae170a: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:32.522  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:32.522  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:32.532  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:32.532  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:34:32.532  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:32.532   758  3728 V AlarmManager:  remove PendingIntent] PendingIntent{8e10b7b: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:32.532  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:32.532  6258  6355 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:32.532  6258  6355 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:32.542  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:32.542  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e23831 not in the list
,09-13 16:34:32.542  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:32.542  6258  6258 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:32.542  6258  6258 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:32.542  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:32.542  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:32.542  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:32.542   758  1795 V AlarmManager:  remove PendingIntent] PendingIntent{5738d98: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:32.542  6258  6355 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:32.542  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:32.542  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:32.542  6258  6355 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ccd8 not in the list
09-13 16:34:32.542  6258  6355 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:32.542  6258  6355 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e23831 not in the list
,09-13 16:34:32.542  6258  6355 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:32.542  6258  6355 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:32.542  6258  6355 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:32.552  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:32.552  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:32.552  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:32.552   758   776 V AlarmManager:  remove PendingIntent] PendingIntent{2e7c9f1: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
,09-13 16:34:32.552  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:34:32.552  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 16:34:32.552  6258  6355 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:32.562  6258  7021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1076, name: My test thread name)
,09-13 16:34:33.042  6258  6258 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:34:33.302  2373  2773 D bt_upio : ..proc_btwrite_timeout..
,09-13 16:34:33.302  2373  2773 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 16:34:34.012  2373  2578 D bt_vendor: op for 7
09-13 16:34:34.012   758  1778 V AlarmManager:  remove PendingIntent] PendingIntent{d9e99d6: PendingIntentRecord{feb836a com.android.bluetooth broadcastIntent}}
09-13 16:34:34.012  2373  2578 D bt_upio : upio_set : pio 0 action 1, polarity 1
09-13 16:34:34.012  2373  2578 D bt_upio : BT_WAKE is de-asserted already
,09-13 16:34:34.332  6713  6724 I qtaguid : Untagging socket 21
,09-13 16:34:34.422  6713  6724 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,09-13 16:34:34.422  6713  6724 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 16:34:34.562  6258  6355 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1076
,09-13 16:34:34.562  6258  6355 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1076, name: My test thread name)
,09-13 16:34:34.572  6258  7023 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1077, name: My test thread name)
,09-13 16:34:34.572  6258  7023 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1077, thread name: My test thread name)
,09-13 16:34:34.572  6258  7023 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1077, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 16:34:34.572  6258  6355 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:34.572  6258  7024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1081, name: My test thread name)
,09-13 16:34:34.582  6258  7024 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1081, thread name: My test thread name): Test exception.
,09-13 16:34:34.582  6258  7024 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1081, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 16:34:34.582  6258  6355 I jxcore-log: Total number of executed tests:  76
09-13 16:34:34.582  6258  6355 I jxcore-log: 
,09-13 16:34:34.582  6258  6355 I jxcore-log: Number of passed tests:  76
09-13 16:34:34.582  6258  6355 I jxcore-log: 
,09-13 16:34:34.582  6258  6355 I jxcore-log: Number of failed tests:  0
09-13 16:34:34.582  6258  6355 I jxcore-log: 
,09-13 16:34:34.582  6258  6355 I jxcore-log: Number of ignored tests:  0
09-13 16:34:34.582  6258  6355 I jxcore-log: 
,09-13 16:34:34.582  6258  6355 I jxcore-log: Total duration:  17321
09-13 16:34:34.582  6258  6355 I jxcore-log: 
,09-13 16:34:34.592  6258  6355 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:34:34.592  6258  6355 I jxcore-log: 
,09-13 16:34:34.592  6258  6355 I jxcore-log: My device name is: samsung-SM-G900F
09-13 16:34:34.592  6258  6355 I jxcore-log: 
09-13 16:34:34.592  6258  6355 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 16:34:34.592  6258  6355 I jxcore-log: 
09-13 16:34:34.602  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.602  6258  6355 I jxcore-log: 
,09-13 16:34:34.602  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.602  6258  6355 I jxcore-log: 
,09-13 16:34:34.602  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.602  6258  6355 I jxcore-log: 
,09-13 16:34:34.612  6258  7021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1076, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-13 16:34:34.612  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.612  6258  6355 I jxcore-log: 
,09-13 16:34:34.612  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.612  6258  6355 I jxcore-log: 
,09-13 16:34:34.612  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.612  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.622  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 16:34:34.622  6258  6355 I jxcore-log: 
,09-13 16:34:34.632  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.632  6258  6355 I jxcore-log: 
,09-13 16:34:34.632  6258  6355 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:34.632  6258  6355 I jxcore-log: 
,09-13 16:34:35.042   758  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:34:35.042   758  1778 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4308, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 16:34:35.042   758  1778 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 16:34:35.042   758  1778 D BatteryService: stay LED for charging
,09-13 16:34:35.042   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:35.052   758   758 I MotionRecognitionService: Plugged
,09-13 16:34:35.052   758   758 D MotionRecognitionService:   cableConnection= 1
09-13 16:34:35.052   758   758 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 16:34:35.052   758   758 D MotionRecognitionService: skip setTransmitPower. 
,09-13 16:34:35.052  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:35.052  1379  1379 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 16:34:35.052  1379  1379 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:34:35.062  2373  2373 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 16:34:35.062  2373  2784 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 16:34:35.072  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:35.072  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 16:34:35.072  1379  1379 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:35.122  7043  7043 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-13 16:34:35.292  7043  7043 I dex2oat : ----------------------------------------------------
09-13 16:34:35.292  7043  7043 I dex2oat : <SS>: S T A R T I N G . . .
09-13 16:34:35.292  7043  7043 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,09-13 16:34:35.292  7043  7043 I dex2oat : dex2oat took 172.374ms (threads: 4) arena alloc=187KB java alloc=39KB native alloc=1543KB free=1528KB
,09-13 16:34:35.302  6713  6724 W System  : ClassLoader referenced unknown path: 
,09-13 16:34:35.302  6713  6724 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,09-13 16:34:35.312  6713  6724 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 16:34:35.312  6713  6724 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 16:34:35.312  6713  6724 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 16:34:35.312  6713  6724 I Adreno-EGL: Local Branch: ss
09-13 16:34:35.312  6713  6724 I Adreno-EGL: Remote Branch: 
09-13 16:34:35.312  6713  6724 I Adreno-EGL: Local Patches: 
09-13 16:34:35.312  6713  6724 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:34:35.312  6713  6724 D libEGL  : eglInitialize EGLDisplay = 0xb2f8e174
,09-13 16:34:35.372  6713  6724 D libEGL  : eglTerminate EGLDisplay = 0xb2f8e1cc
,09-13 16:34:35.372  6713  6724 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 16:34:35.372  6713  6724 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 16:34:35.372  6713  6724 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 16:34:35.372  6713  6724 I Adreno-EGL: Local Branch: ss
09-13 16:34:35.372  6713  6724 I Adreno-EGL: Remote Branch: 
09-13 16:34:35.372  6713  6724 I Adreno-EGL: Local Patches: 
09-13 16:34:35.372  6713  6724 I Adreno-EGL: Reconstruct Branch: 
09-13 16:34:35.372  6713  6724 D libEGL  : eglInitialize EGLDisplay = 0xb2f8e174
,09-13 16:34:35.422  6713  6724 D libEGL  : eglTerminate EGLDisplay = 0xb2f8e1cc
,09-13 16:34:35.422  6713  6724 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 16:34:35.422  6713  6724 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 16:34:35.422  6713  6724 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 16:34:35.422  6713  6724 I Adreno-EGL: Local Branch: ss
09-13 16:34:35.422  6713  6724 I Adreno-EGL: Remote Branch: 
09-13 16:34:35.422  6713  6724 I Adreno-EGL: Local Patches: 
09-13 16:34:35.422  6713  6724 I Adreno-EGL: Reconstruct Branch: 
09-13 16:34:35.422  6713  6724 D libEGL  : eglInitialize EGLDisplay = 0xb2f8e174
,09-13 16:34:35.462  6713  6724 D libEGL  : eglTerminate EGLDisplay = 0xb2f8e1cc
,09-13 16:34:35.692  2379  2379 E audit   : type=1400 msg=audit(1473777275.692:289): avc:  denied  { execmod } for  pid=7025 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,09-13 16:34:35.692  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 16:34:35.692  2379  2379 E audit   : type=1300 msg=audit(1473777275.692:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3b000 a1=51000 a2=5 a3=4 items=0 ppid=3595 ppcomm=adbd pid=7025 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 16:34:35.692  2379  2379 E audit   : type=1327 msg=audit(1473777275.692:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
09-13 16:34:35.692  2379  2379 E audit   : type=1320 msg=audit(1473777275.692:289): 
,09-13 16:34:35.752  2379  2379 E audit   : type=1400 msg=audit(1473777275.752:290): avc:  denied  { execmod } for  pid=7025 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 16:34:35.752  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,09-13 16:34:35.752  2379  2379 E audit   : type=1300 msg=audit(1473777275.752:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3efb000 a1=51000 a2=5 a3=4 items=0 ppid=3595 ppcomm=adbd pid=7025 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 16:34:35.752  2379  2379 E audit   : type=1327 msg=audit(1473777275.752:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
09-13 16:34:35.752  2379  2379 E audit   : type=1320 msg=audit(1473777275.752:290): 
,09-13 16:34:35.752  2074  6705 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 16:34:35.752  2074  6705 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:35.752   313  1198 D EnterpriseController: netId is 0
09-13 16:34:35.752   313  1198 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:34:35.762  2074  6705 I qtaguid : Tagging socket 43 with tag 1000040100000000{268436481,0} uid 10011, pid: 2074, getuid(): 10011
,09-13 16:34:35.792  2379  2379 E audit   : type=1400 msg=audit(1473777275.792:291): avc:  denied  { execmod } for  pid=7025 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 16:34:35.792  2379  2379 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,09-13 16:34:35.792  2379  2379 E audit   : type=1300 msg=audit(1473777275.792:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3efb000 a1=51000 a2=5 a3=4 items=0 ppid=3595 ppcomm=adbd pid=7025 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 16:34:35.792  2379  2379 E audit   : type=1327 msg=audit(1473777275.792:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
09-13 16:34:35.792  2379  2379 E audit   : type=1320 msg=audit(1473777275.792:291): 
09-13 16:34:35.792  7025  7025 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 16:34:35.802  7025  7025 D AndroidRuntime: CheckJNI is OFF
,09-13 16:34:35.802  7025  7025 D AndroidRuntime: readGMSProperty: start
09-13 16:34:35.802  7025  7025 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:34:35.802  7025  7025 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:34:35.802  7025  7025 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:34:35.802  7025  7025 D AndroidRuntime: readGMSProperty: end
09-13 16:34:35.802  7025  7025 D AndroidRuntime: addProductProperty: start
,09-13 16:34:35.802  2074  6705 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 2074, getuid(): 10011
,09-13 16:34:35.802  7025  7025 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 16:34:35.802  7025  7025 W art     : aed62000-b1c88000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
09-13 16:34:35.802  7025  7025 W art     : b1c88000-b3ef7000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
09-13 16:34:35.802  7025  7025 W art     : b3ef7000-b3ef8000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
09-13 16:34:35.802  7025  7025 W art     : b3ef8000-b3ef9000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.802  7025  7025 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 16:34:35.802  7025  7025 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
09-13 16:34:35.802  7025  7025 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 946        /system/lib/libart.so
09-13 16:34:35.802  7025  7025 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 946        /system/lib/libart.so
09-13 16:34:35.802  7025  7025 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
09-13 16:34:35.802  7025  7025 W art     : b47cc000-b47cf000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
09-13 16:34:35.802  7025  7025 W art     : b47cf000-b47d0000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
09-13 16:34:35.802  7025  7025 W art     : b47d0000-b47d1000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
09-13 16:34:35.802  7025  7025 W art     : b47d1000-b47d2000 r--p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b47d2000-b47f2000 r--s 00000000 00:0b 9219       /dev/__properties__
09-13 16:34:35.802  7025  7025 W art     : b47f2000-b5203000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
09-13 16:34:35.802  7025  7025 W art     : b5203000-b5204000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b5204000-b524d000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
09-13 16:34:35.802  7025  7025 W art     : b524d000-b524e000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
09-13 16:34:35.802  7025  7025 W art     : b524e000-b5256000 rw-p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b5256000-b528b000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
09-13 16:34:35.802  7025  7025 W art     : b528b000-b528c000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b528c000-b528d000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
09-13 16:34:35.802  7025  7025 W art     : b528d000-b528e000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
09-13 16:34:35.802  7025  7025 W art     : b528e000-b52e6000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
09-13 16:34:35.802  7025  7025 W art     : b52e6000-b52e7000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b52e7000-b52e8000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
09-13 16:34:35.802  7025  7025 W art     : b52e8000-b52e9000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
09-13 16:34:35.802  7025  7025 W art     : b52ea000-b52f0000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
09-13 16:34:35.802  7025  7025 W art     : AD_v01009.so
09-13 16:34:35.802  7025  7025 W art     : b52f0000-b52f1000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 16:34:35.802  7025  7025 W art     : b52f1000-b52f2000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 16:34:35.802  7025  7025 W art     : b52f2000-b52f4000 rw-p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b52f5000-b52ff000 r-xp 00000000 b3:17 1088 
09-13 16:34:35.802  7025  7025 W art     :       /system/lib/libcommon_time_client.so
09-13 16:34:35.802  7025  7025 W art     : b52ff000-b5302000, r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 16:34:35.802  7025  7025 W art     : b5302000-b5303000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 16:34:35.802  7025  7025 W art     : b5304000-b531b000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 16:34:35.802  7025  7025 W art     : b531b000-b531c000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b531c000-b531d000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 16:34:35.802  7025  7025 W art     : b531d000-b531e000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 16:34:35.802  7025  7025 W art     : b531f000-b5329000 r-xp 00000000 b3:17 2671   
09-13 16:34:35.802  7025  7025 W art     :     /system/lib/libsec_km.so
09-13 16:34:35.802  7025  7025 W art     : b5329000-b532a000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
09-13 16:34:35.802  7025  7025 W art     : b532a000-b532b000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
09-13 16:34:35.802  7025  7025 W art     : b532b000-b532f000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 16:34:35.802  7025  7025 W art     : b532f000-b5330000 r--p 00003000 b
09-13 16:34:35.802  7025  7025 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
09-13 16:34:35.802  7025  7025 W art     : b5330000-b5331000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 16:34:35.802  7025  7025 W art     : b5331000-b5347000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
09-13 16:34:35.802  7025  7025 W art     : b5347000-b5348000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
09-13 16:34:35.802  7025  7025 W art     : b5348000-b5349000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
09-13 16:34:35.802  7025  7025 W art     : b5349000-b5356000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
09-13 16:34:35.802  7025  7025 W art     : b5356000-b5357000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
09-13 16:34:35.802  7025  7025 W art     : b5357000-b5358000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
09-13 16:34:35.802  7025  7025 W art     : b5358000-b53b8000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
09-13 16:34:35.802  7025  7025 W art     : b53b8000-b53bb000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
09-13 16:34:35.802  7025  7025 W art     : b53bb000-b53bf000 rw-p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b53bf000-b5420000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
09-13 16:34:35.802  7025  7025 W art     : b5420000-b5421000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
09-13 16:34:35.802  7025  7025 W art     : b5421000-b5470000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
09-13 16:34:35.802  7025  7025 W art     : b5470000-b5472000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
09-13 16:34:35.802  7025  7025 W art     : b5472000-b5473000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
09-13 16:34:35.802  7025  7025 W art     : b5473000-b5474000 rw-p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b5474000-b547b000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,09-13 16:34:35.802  7025  7025 W art     : b547b000-b547c000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 16:34:35.802  7025  7025 W art     : b547c000-b547d000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
09-13 16:34:35.802  7025  7025 W art     : avc_common.so
09-13 16:34:35.802  7025  7025 W art     : b547e000-b5481000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 16:34:35.802  7025  7025 W art     : b5481000-b5482000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 16:34:35.802  7025  7025 W art     : b5482000-b5483000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
09-13 16:34:35.802  7025  7025 W art     : enc_common.so
09-13 16:34:35.802  7025  7025 W art     : b5484000-b5488000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
09-13 16:34:35.802  7025  7025 W art     : b5488000-b5489000 ---p 00000000 00:00 0 
,09-13 16:34:35.802  7025  7025 W art     : b5489000-b548a000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
09-13 16:34:35.802  7025  7025 W art     : b548a000-b548b000 rw-p 00005000 b3:17 2510       /syste
09-13 16:34:35.802  7025  7025 W art     : m/lib/libpowermanager.so
09-13 16:34:35.802  7025  7025 W art     : b548c000-b54a9000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 16:34:35.802  7025  7025 W art     : b54a9000-b54aa000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 16:34:35.802  7025  7025 W art     : b54aa000-b54ab000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 16:34:35.802  7025  7025 W art     : b54ac000-b54b1000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 16:34:35.802  7025  7025 W art     : b54b1000-b54b2000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
,09-13 16:34:35.802  7025  7025 W art     : b54b2000-b54b3000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 16:34:35.802  7025  7025 W art     : b54b4000-b54e5000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 16:34:35.802  7025  7025 W art     : b54e5000-b54e6000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b54e6000-b54e9000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 16:34:35.802  7025  7025 W art     : b54e9000-b54ea000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 16:34:35.802  7025  7025 W art     : b54eb000-b5526000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
09-13 16:34:35.802  7025  7025 W art     : b5526000-b5527000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
09-13 16:34:35.802  7025  7025 W art     : b5527000-b5528000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,09-13 16:34:35.802  7025  7025 W art     : b5529000-b5530000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
09-13 16:34:35.802  7025  7025 W art     : b5530000-b5531000 ---p 00000000 00:00 0 
09-13 16:34:35.802  7025  7025 W art     : b5531000-b5532000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
09-13 16:34:35.802  7025  7025 W art     : b5532000-b5533000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
09-13 16:34:35.802  7025  7025 W art     : b5533000-b5534000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.802  7025  7025 W art     : b5534000-b554b000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
09-13 16:34:35.802  7025  7025 W art     : b554b000-b554c000 ---p 00000000 00:00 0 
,09-13 16:34:35.802  7025  7025 W art     : b554c000-b554f000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
09-13 16:34:35.802  7025  7025 W art     : b554f000-b5550000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
09-13 16:34:35.802  7025  7025 W art     : b5550000-b556f000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
09-13 16:34:35.802  7025  7025 W art     : b556f000-b5570000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
09-13 16:34:35.802  7025  7025 W art     : b5570000-b5571000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
09-13 16:34:35.812  7025  7025 W art     : b5571000-b55af000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
09-13 16:34:35.812  7025  7025 W art     : b55af000-b55b0000 ---p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b55b0000-b55b2000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
09-13 16:34:35.812  7025  7025 W art     : b55b2000-b55b3000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
09-13 16:34:35.812  7025  7025 W art     : b55b4000-b55bb000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 16:34:35.812  7025  7025 W art     : b55bb000-b55bc000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 16:34:35.812  7025  7025 W art     : b55bc000-b55bd000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 16:34:35.812  7025  7025 W art     : b55be000-b55c1000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 16:34:35.812  7025  7025 W art     : b55c1000-b55c2000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,09-13 16:34:35.812  7025  7025 W art     : b55c2000-b55c3000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 16:34:35.812  7025  7025 W art     : b55c3000-b55c9000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 16:34:35.812  7025  7025 W art     : b55c9000-b55ca000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b55ca000-b55cb000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 16:34:35.812  7025  7025 W art     : b55cb000-b55cc000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 16:34:35.812  7025  7025 W art     : b55cc000-b55d5000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
09-13 16:34:35.812  7025  7025 W art     : b55d5000-b55d6000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
,09-13 16:34:35.812  7025  7025 W art     : b55d6000-b55d7000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
09-13 16:34:35.812  7025  7025 W art     : b55d7000-b5668000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 16:34:35.812  7025  7025 W art     : b5668000-b5669000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5669000-b5674000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 16:34:35.812  7025  7025 W art     : b5674000-b5675000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 16:34:35.812  7025  7025 W art     : b5676000-b5688000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
09-13 16:34:35.812  7025  7025 W art     : b5688000-b5689000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
,09-13 16:34:35.812  7025  7025 W art     : b5689000-b568a000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
09-13 16:34:35.812  7025  7025 W art     : b568b000-b5690000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
09-13 16:34:35.812  7025  7025 W art     : b5690000-b5691000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
09-13 16:34:35.812  7025  7025 W art     : b5691000-b5692000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
09-13 16:34:35.812  7025  7025 W art     : b5693000-b5700000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
09-13 16:34:35.812  7025  7025 W art     : b5700000-b5701000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5701000-b5703000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
,09-13 16:34:35.812  7025  7025 W art     : b5703000-b5704000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
09-13 16:34:35.812  7025  7025 W art     : b5704000-b5705000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5705000-b570c000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 16:34:35.812  7025  7025 W art     : b570c000-b570d000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 16:34:35.812  7025  7025 W art     : b570d000-b570e000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 16:34:35.812  7025  7025 W art     : b570f000-b578f000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 16:34:35.812  7025  7025 W art     : b578f000-b5790000 ---p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b5790000-b5791000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 16:34:35.812  7025  7025 W art     : b5791000-b5792000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 16:34:35.812  7025  7025 W art     : b5792000-b57a9000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b57a9000-b57e0000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 16:34:35.812  7025  7025 W art     : b57e0000-b57e1000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,09-13 16:34:35.812  7025  7025 W art     : b57e1000-b57e2000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 16:34:35.812  7025  7025 W art     : b57e2000-b57fe000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 16:34:35.812  7025  7025 W art     : b57fe000-b57ff000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 16:34:35.812  7025  7025 W art     : b57ff000-b5800000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 16:34:35.812  7025  7025 W art     : b5801000-b5862000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
09-13 16:34:35.812  7025  7025 W art     : b5862000-b5864000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
09-13 16:34:35.812  7025  7025 W art     : b5864000-b5865000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
,09-13 16:34:35.812  7025  7025 W art     : b5866000-b588b000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
09-13 16:34:35.812  7025  7025 W art     : b588b000-b588c000 r--p 00024000 b3:17 126        /system/lib/libpng.so
09-13 16:34:35.812  7025  7025 W art     : b588c000-b588d000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
09-13 16:34:35.812  7025  7025 W art     : b588e000-b5896000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 16:34:35.812  7025  7025 W art     : b5896000-b5898000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 16:34:35.812  7025  7025 W art     : b5898000-b5899000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 16:34:35.812  7025  7025 W art     : b589a000-b589d000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
09-13 16:34:35.812  7025  7025 W art     : b589d000-b589e000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
,09-13 16:34:35.812  7025  7025 W art     : b589e000-b589f000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
09-13 16:34:35.812  7025  7025 W art     : b589f000-b58a3000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
09-13 16:34:35.812  7025  7025 W art     : b58a3000-b58a4000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b58a4000-b58a5000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
09-13 16:34:35.812  7025  7025 W art     : b58a5000-b58a6000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
09-13 16:34:35.812  7025  7025 W art     : b58a6000-b58b6000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
09-13 16:34:35.812  7025  7025 W art     : b58b6000-b58b7000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
,09-13 16:34:35.812  7025  7025 W art     : b58b7000-b58b8000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
09-13 16:34:35.812  7025  7025 W art     : b58b8000-b58fe000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b58fe000-b5907000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
09-13 16:34:35.812  7025  7025 W art     : b5907000-b5908000 r--p 00008000 b3:17 982        /system/lib/libbase.so
09-13 16:34:35.812  7025  7025 W art     : b5908000-b5909000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
09-13 16:34:35.812  7025  7025 W art     : b590a000-b590f000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
09-13 16:34:35.812  7025  7025 W art     : b590f000-b5910000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
,09-13 16:34:35.812  7025  7025 W art     : b5910000-b5911000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
09-13 16:34:35.812  7025  7025 W art     : b5911000-b5914000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 16:34:35.812  7025  7025 W art     : b5914000-b5915000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5915000-b5916000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 16:34:35.812  7025  7025 W art     : b5916000-b5917000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 16:34:35.812  7025  7025 W art     : b5918000-b5930000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
09-13 16:34:35.812  7025  7025 W art     : ght_foundation.so
,09-13 16:34:35.812  7025  7025 W art     : b5930000-b5931000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5931000-b5932000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 16:34:35.812  7025  7025 W art     : b5932000-b5933000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 16:34:35.812  7025  7025 W art     : b5933000-b5934000 rw-p 00000000 00:
09-13 16:34:35.812  7025  7025 W art     : 00 0          [anon:linker_alloc_vector]
09-13 16:34:35.812  7025  7025 W art     : b5934000-b5ace000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
09-13 16:34:35.812  7025  7025 W art     : b5ace000-b5acf000 ---p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b5acf000-b5adc000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
09-13 16:34:35.812  7025  7025 W art     : b5adc000-b5add000 rw-p 001a7000 b3:17 604        /system/
09-13 16:34:35.812  7025  7025 W art     : lib/libstagefright.so
09-13 16:34:35.812  7025  7025 W art     : b5add000-b5ae1000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
09-13 16:34:35.812  7025  7025 W art     : b5ae1000-b5ae2000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5ae2000-b5ae3000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
09-13 16:34:35.812  7025  7025 W art     : b5ae3000-b5ae4000 rw-p 00005000 b3:17 2676       /system/lib/libp
,09-13 16:34:35.812  7025  7025 W art     : ersona.so
09-13 16:34:35.812  7025  7025 W art     : b5ae4000-b5af7000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
09-13 16:34:35.812  7025  7025 W art     : b5af7000-b5af8000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
09-13 16:34:35.812  7025  7025 W art     : b5af8000-b5af9000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
09-13 16:34:35.812  7025  7025 W art     : b5afa000-b5b45000 r
09-13 16:34:35.812  7025  7025 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
09-13 16:34:35.812  7025  7025 W art     : b5b45000-b5b46000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
,09-13 16:34:35.812  7025  7025 W art     : b5b46000-b5b47000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
09-13 16:34:35.812  7025  7025 W art     : b5b47000-b5b49000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5b4a000-b5b5b000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 16:34:35.812  7025  7025 W art     : b5b5b000-b5b5c000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5b5c000-b5b5d000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 16:34:35.812  7025  7025 W art     : b5b5d000-b5b5e000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 16:34:35.812  7025  7025 W art     : b5b5e000-b5b5f000 r--p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b5b5f000-b5b69000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
09-13 16:34:35.812  7025  7025 W art     : b5b69000-b5b6b000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
09-13 16:34:35.812  7025  7025 W art     : b5b6b000-b5b6c000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
09-13 16:34:35.812  7025  7025 W art     : b5b6c000-b5b85000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
09-13 16:34:35.812  7025  7025 W art     : b5b85000-b5b86000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
09-13 16:34:35.812  7025  7025 W art     : b5b86000-b5b89000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
,09-13 16:34:35.812  7025  7025 W art     : b5b89000-b5b8d000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5b8d000-b5c01000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
09-13 16:34:35.812  7025  7025 W art     : b5c01000-b5c02000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5c02000-b5c05000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
09-13 16:34:35.812  7025  7025 W art     : b5c05000-b5c06000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
09-13 16:34:35.812  7025  7025 W art     : b5c06000-b5c07000 r--p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5c07000-b5c0a000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
,09-13 16:34:35.812  7025  7025 W art     : b5c0a000-b5c0b000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
09-13 16:34:35.812  7025  7025 W art     : b5c0b000-b5c0c000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
09-13 16:34:35.812  7025  7025 W art     : b5c0c000-b5c0d000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5c0d000-b5c12000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 16:34:35.812  7025  7025 W art     : b5c12000-b5c13000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 16:34:35.812  7025  7025 W art     : b5c13000-b5c14000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 16:34:35.812  7025  7025 W art     : b5c14000-b5c15000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5c15000-b5c18000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
,09-13 16:34:35.812  7025  7025 W art     : b5c18000-b5c19000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 16:34:35.812  7025  7025 W art     : b5c19000-b5c1a000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 16:34:35.812  7025  7025 W art     : b5c1a000-b5c1b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:34:35.812  7025  7025 W art     : b5c1b000-b5c1f000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
09-13 16:34:35.812  7025  7025 W art     : b5c1f000-b5c20000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
09-13 16:34:35.812  7025  7025 W art     : b5c20000-b5c21000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
09-13 16:34:35.812  7025  7025 W art     : b5c21000-b5c22000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5c22000-b5c26000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
,09-13 16:34:35.812  7025  7025 W art     : b5c26000-b5c27000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 16:34:35.812  7025  7025 W art     : b5c27000-b5c28000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 16:34:35.812  7025  7025 W art     : b5c28000-b5c29000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5c29000-b5c37000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
09-13 16:34:35.812  7025  7025 W art     : b5c37000-b5c38000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b5c38000-b5c39000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
09-13 16:34:35.812  7025  7025 W art     : b5c39000-b5c3a000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
09-13 16:34:35.812  7025  7025 W art     : b5c3a000-b5c44000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
,09-13 16:34:35.812  7025  7025 W art     : b5c44000-b5c47000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 16:34:35.812  7025  7025 W art     : b5c47000-b5c48000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 16:34:35.812  7025  7025 W art     : b5c48000-b5c49000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5c49000-b5c53000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
09-13 16:34:35.812  7025  7025 W art     : b5c53000-b5c56000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
09-13 16:34:35.812  7025  7025 W art     : b5c56000-b5c57000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
09-13 16:34:35.812  7025  7025 W art     : b5c57000-b5c5b000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
,09-13 16:34:35.812  7025  7025 W art     : b5c5b000-b5c5c000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
09-13 16:34:35.812  7025  7025 W art     : b5c5c000-b5c5d000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
09-13 16:34:35.812  7025  7025 W art     : b5c5d000-b5c5e000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b5c5e000-b5c6b000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
09-13 16:34:35.812  7025  7025 W art     : b5c6b000-b5c6d000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
09-13 16:34:35.812  7025  7025 W art     : b5c6d000-b5c6e000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
09-13 16:34:35.812  7025  7025 W art     : b5c6e000-b6080000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
,09-13 16:34:35.812  7025  7025 W art     : b6080000-b6081000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6081000-b608a000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
09-13 16:34:35.812  7025  7025 W art     : b608a000-b608e000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
09-13 16:34:35.812  7025  7025 W art     : b608e000-b608f000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b608f000-b6096000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
09-13 16:34:35.812  7025  7025 W art     : b6096000-b6097000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
09-13 16:34:35.812  7025  7025 W art     : b6097000-b6098000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
,09-13 16:34:35.812  7025  7025 W art     : b6098000-b6099000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6099000-b60b4000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
09-13 16:34:35.812  7025  7025 W art     : b60b4000-b60b5000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
09-13 16:34:35.812  7025  7025 W art     : b60b5000-b60b6000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
09-13 16:34:35.812  7025  7025 W art     : b60b6000-b60b7000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b60b7000-b6103000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 16:34:35.812  7025  7025 W art     : b6103000-b6104000 ---p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b6104000-b6105000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 16:34:35.812  7025  7025 W art     : b6105000-b6106000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 16:34:35.812  7025  7025 W art     : b6106000-b6107000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6107000-b610b000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
09-13 16:34:35.812  7025  7025 W art     : b610b000-b610c000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b610c000-b610d000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
09-13 16:34:35.812  7025  7025 W art     : b610d000-b610e000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
,09-13 16:34:35.812  7025  7025 W art     : b610e000-b6146000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
09-13 16:34:35.812  7025  7025 W art     : b6146000-b6147000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
09-13 16:34:35.812  7025  7025 W art     : b6147000-b6148000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
09-13 16:34:35.812  7025  7025 W art     : b6148000-b6149000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6149000-b61e8000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
09-13 16:34:35.812  7025  7025 W art     : b61e8000-b6206000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
09-13 16:34:35.812  7025  7025 W art     : b6206000-b6207000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
,09-13 16:34:35.812  7025  7025 W art     : b6207000-b637a000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
09-13 16:34:35.812  7025  7025 W art     : b637a000-b6385000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
09-13 16:34:35.812  7025  7025 W art     : b6385000-b6386000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
09-13 16:34:35.812  7025  7025 W art     : b6386000-b649d000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
09-13 16:34:35.812  7025  7025 W art     : b649d000-b64a8000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
09-13 16:34:35.812  7025  7025 W art     : b64a8000-b64a9000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
09-13 16:34:35.812  7025  7025 W art     : b64a9000-b64ad000 rw-p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b64ad000-b64d1000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
09-13 16:34:35.812  7025  7025 W art     : b64d1000-b64d3000 r--p 00023000 b3:17 400        /system/lib/libssl.so
09-13 16:34:35.812  7025  7025 W art     : b64d3000-b64d4000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
09-13 16:34:35.812  7025  7025 W art     : b64d4000-b657a000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
09-13 16:34:35.812  7025  7025 W art     : b657a000-b6587000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
09-13 16:34:35.812  7025  7025 W art     : b6587000-b6588000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
09-13 16:34:35.812  7025  7025 W art     : b6588000-b6589000 rw-p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b6589000-b65dc000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
09-13 16:34:35.812  7025  7025 W art     : b65dc000-b65dd000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b65dd000-b65de000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
09-13 16:34:35.812  7025  7025 W art     : b65de000-b65df000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
09-13 16:34:35.812  7025  7025 W art     : b65df000-b65e4000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b65e4000-b65f6000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
09-13 16:34:35.812  7025  7025 W art     : b65f6000-b65f7000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b65f7000-b65f8000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,09-13 16:34:35.812  7025  7025 W art     : b65f8000-b65f9000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
09-13 16:34:35.812  7025  7025 W art     : b65f9000-b6600000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 16:34:35.812  7025  7025 W art     : b6600000-b6601000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 16:34:35.812  7025  7025 W art     : b6601000-b6602000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 16:34:35.812  7025  7025 W art     : b6602000-b6603000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6603000-b6606000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
09-13 16:34:35.812  7025  7025 W art     : b6606000-b6607000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
,09-13 16:34:35.812  7025  7025 W art     : b6607000-b6608000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
09-13 16:34:35.812  7025  7025 W art     : b6608000-b660c000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
09-13 16:34:35.812  7025  7025 W art     : b660c000-b660d000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
09-13 16:34:35.812  7025  7025 W art     : b660d000-b660e000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
09-13 16:34:35.812  7025  7025 W art     : b660e000-b661c000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
09-13 16:34:35.812  7025  7025 W art     : b661c000-b661d000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b661d000-b661e000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
,09-13 16:34:35.812  7025  7025 W art     : b661e000-b661f000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
09-13 16:34:35.812  7025  7025 W art     : b661f000-b6628000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 16:34:35.812  7025  7025 W art     : b6628000-b6629000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 16:34:35.812  7025  7025 W art     : b6629000-b662a000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 16:34:35.812  7025  7025 W art     : b662a000-b6690000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
09-13 16:34:35.812  7025  7025 W art     : b6690000-b6691000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6691000-b6693000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
,09-13 16:34:35.812  7025  7025 W art     : b6693000-b669c000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
09-13 16:34:35.812  7025  7025 W art     : b669c000-b669f000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b669f000-b6736000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
09-13 16:34:35.812  7025  7025 W art     : b6736000-b6738000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
09-13 16:34:35.812  7025  7025 W art     : b6738000-b6739000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
09-13 16:34:35.812  7025  7025 W art     : b6739000-b673a000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b673a000-b6a58000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
,09-13 16:34:35.812  7025  7025 W art     : b6a58000-b6a59000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6a59000-b6a74000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
09-13 16:34:35.812  7025  7025 W art     : b6a74000-b6a78000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
09-13 16:34:35.812  7025  7025 W art     : b6a78000-b6a7d000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6a7d000-b6a85000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 16:34:35.812  7025  7025 W art     : b6a85000-b6a86000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 16:34:35.812  7025  7025 W art     : b6a86000-b6a87000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
,09-13 16:34:35.812  7025  7025 W art     : b6a87000-b6ab5000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
09-13 16:34:35.812  7025  7025 W art     : b6ab5000-b6ab6000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6ab6000-b6abd000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
09-13 16:34:35.812  7025  7025 W art     : b6abd000-b6abe000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
09-13 16:34:35.812  7025  7025 W art     : b6abe000-b6b04000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
09-13 16:34:35.812  7025  7025 W art     : b6b04000-b6b05000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6b05000-b6b08000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
,09-13 16:34:35.812  7025  7025 W art     : b6b08000-b6b09000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
09-13 16:34:35.812  7025  7025 W art     : b6b09000-b6b24000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
09-13 16:34:35.812  7025  7025 W art     : b6b24000-b6b28000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
09-13 16:34:35.812  7025  7025 W art     : b6b28000-b6b29000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
09-13 16:34:35.812  7025  7025 W art     : b6b29000-b6b76000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
09-13 16:34:35.812  7025  7025 W art     : b6b76000-b6b77000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6b77000-b6b83000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
,09-13 16:34:35.812  7025  7025 W art     : b6b83000-b6b84000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
09-13 16:34:35.812  7025  7025 W art     : b6b84000-b6b91000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
09-13 16:34:35.812  7025  7025 W art     : b6b91000-b6b92000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6b92000-b6b93000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
09-13 16:34:35.812  7025  7025 W art     : b6b93000-b6b94000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
09-13 16:34:35.812  7025  7025 W art     : b6b94000-b6b9c000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
09-13 16:34:35.812  7025  7025 W art     : b6b9c000-b6b9d000 ---p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b6b9d000-b6b9e000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
09-13 16:34:35.812  7025  7025 W art     : b6b9e000-b6b9f000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
09-13 16:34:35.812  7025  7025 W art     : b6b9f000-b6ba6000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
09-13 16:34:35.812  7025  7025 W art     : b6ba6000-b6ba7000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
09-13 16:34:35.812  7025  7025 W art     : b6ba7000-b6ba8000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
09-13 16:34:35.812  7025  7025 W art     : b6ba8000-b6bbc000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
09-13 16:34:35.812  7025  7025 W art     : b6bbc000-b6bbe000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
09-13 16:34:35.812  7025  7025 W art     : b6bbe000-b6bbf000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
,09-13 16:34:35.812  7025  7025 W art     : b6bbf000-b6be7000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
09-13 16:34:35.812  7025  7025 W art     : b6be7000-b6be9000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
09-13 16:34:35.812  7025  7025 W art     : b6be9000-b6bea000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
09-13 16:34:35.812  7025  7025 W art     : b6bea000-b6bed000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
09-13 16:34:35.812  7025  7025 W art     : b6bed000-b6bee000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
09-13 16:34:35.812  7025  7025 W art     : b6bee000-b6bef000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
09-13 16:34:35.812  7025  7025 W art     : b6bef000-b6bf8000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
,09-13 16:34:35.812  7025  7025 W art     : b6bf8000-b6bf9000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
09-13 16:34:35.812  7025  7025 W art     : b6bf9000-b6bfa000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
09-13 16:34:35.812  7025  7025 W art     : b6bfa000-b6c1a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
09-13 16:34:35.812  7025  7025 W art     : b6c1a000-b6c1b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
09-13 16:34:35.812  7025  7025 W art     : b6c1b000-b6c1c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
09-13 16:34:35.812  7025  7025 W art     : b6c1c000-b6c8f000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
09-13 16:34:35.812  7025  7025 W art     : b6c8f000-b6c93000 r--p 00072000 b3:17 1016       /system/lib/libc.so
,09-13 16:34:35.812  7025  7025 W art     : b6c93000-b6c96000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
09-13 16:34:35.812  7025  7025 W art     : b6c96000-b6ca0000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6ca0000-b6d28000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
09-13 16:34:35.812  7025  7025 W art     : b6d28000-b6d29000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6d29000-b6d2d000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
09-13 16:34:35.812  7025  7025 W art     : b6d2d000-b6d2e000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
09-13 16:34:35.812  7025  7025 W art     : b6d2e000-b6d2f000 rw-p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b6d2f000-b6d58000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
09-13 16:34:35.812  7025  7025 W art     : b6d58000-b6d59000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6d59000-b6d5c000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
09-13 16:34:35.812  7025  7025 W art     : b6d5c000-b6d5d000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
09-13 16:34:35.812  7025  7025 W art     : b6d5d000-b6e37000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 16:34:35.812  7025  7025 W art     : b6e37000-b6e3e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 16:34:35.812  7025  7025 W art     : b6e3e000-b6e46000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
,09-13 16:34:35.812  7025  7025 W art     : b6e46000-b6e47000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6e47000-b6e48000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:34:35.812  7025  7025 W art     : b6e48000-b6e49000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
09-13 16:34:35.812  7025  7025 W art     : b6e49000-b6e4a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6e4a000-b6e4d000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6e4d000-b6e72000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
09-13 16:34:35.812  7025  7025 W art     : b6e72000-b6e73000 ---p 00000000 00:00 0 
,09-13 16:34:35.812  7025  7025 W art     : b6e73000-b6e7a000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
09-13 16:34:35.812  7025  7025 W art     : b6e7a000-b6e7b000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
09-13 16:34:35.812  7025  7025 W art     : b6e7b000-b6e82000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
09-13 16:34:35.812  7025  7025 W art     : b6e82000-b6e83000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
09-13 16:34:35.812  7025  7025 W art     : b6e83000-b6e84000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
09-13 16:34:35.812  7025  7025 W art     : b6e84000-b6e85000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6e85000-b6e9d000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
,09-13 16:34:35.812  7025  7025 W art     : b6e9d000-b6e9e000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6e9e000-b6e9f000 r--p 00018000 b3:17 918        /system/lib/libutils.so
09-13 16:34:35.812  7025  7025 W art     : b6e9f000-b6ea0000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
09-13 16:34:35.812  7025  7025 W art     : b6ea0000-b6eae000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
09-13 16:34:35.812  7025  7025 W art     : b6eae000-b6eaf000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6eaf000-b6eb0000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
09-13 16:34:35.812  7025  7025 W art     : b6eb0000-b6eb1000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
,09-13 16:34:35.812  7025  7025 W art     : b6eb1000-b6eb2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:34:35.812  7025  7025 W art     : b6eb2000-b6eb4000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6eb4000-b6eb5000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6eb5000-b6eb6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 16:34:35.812  7025  7025 W art     : b6eb6000-b6eb7000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
09-13 16:34:35.812  7025  7025 W art     : b6eb7000-b6eb8000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 16:34:35.812  7025  7025 W art     : b6eb8000-b6ed8000 r--s 00000000 00:0b 9219       /dev/__properties__
,09-13 16:34:35.812  7025  7025 W art     : b6ed8000-b6ed9000 r--p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6ed9000-b6eda000 ---p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6eda000-b6edc000 rw-p 00000000 00:00 0          [anon:thread signal stack]
09-13 16:34:35.812  7025  7025 W art     : b6edc000-b6edd000 r-xp 00000000 00:00 0          [sigpage]
09-13 16:34:35.812  7025  7025 W art     : b6edd000-b6ef8000 r-xp 00000000 b3:17 341        /system/bin/linker
09-13 16:34:35.812  7025  7025 W art     : b6ef8000-b6ef9000 r--p 0001a000 b3:17 341        /system/bin/linker
09-13 16:34:35.812  7025  7025 W art     : b6ef9000-b6efb000 rw-p 0001b000 b3:17 341        /system/bin/linker
,09-13 16:34:35.812  7025  7025 W art     : b6efb000-b6efd000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : b6efd000-b6f02000 r-xp 00000000 b3:17 978        /system/bin/app_process32
09-13 16:34:35.812  7025  7025 W art     : b6f02000-b6f03000 r--p 00004000 b3:17 978        /system/bin/app_process32
09-13 16:34:35.812  7025  7025 W art     : b6f03000-b6f04000 rw-p 00000000 00:00 0 
09-13 16:34:35.812  7025  7025 W art     : bedf3000-bee14000 rw-p 00000000 00:00 0          [stack]
09-13 16:34:35.812  7025  7025 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,09-13 16:34:35.852  7025  7025 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 16:34:35.912  7025  7025 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 16:34:35.912  7025  7025 E AffinityControl: AffinityControl: registerfunction enter
,09-13 16:34:35.932  7025  7025 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:34:35.942   758  1796 D PackageManager: START PACKAGE DELETE: observer{188906850}
09-13 16:34:35.942   758  1796 D PackageManager: pkg{<packageName>}
09-13 16:34:35.942   758  1796 D PackageManager: user{0}
09-13 16:34:35.942   758  1796 D PackageManager: caller{2000}
09-13 16:34:35.942   758  1796 D PackageManager: flags{2}
,09-13 16:34:35.942   758  1796 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 16:34:35.942   758  1796 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 16:34:35.942   758  1796 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 16:34:35.942   758  1796 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 16:34:35.942   758  1796 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-13 16:34:35.942   758   924 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 16:34:35.942   758   924 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-13 16:34:35.952   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{94f6ef3: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:35.952   758   924 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 16:34:35.952   758   924 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 16:34:35.952   758   924 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 16:34:35.952   758   924 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-13 16:34:35.952   758   924 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-13 16:34:35.952   758   924 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,09-13 16:34:35.952   758   924 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 16:34:35.952   758   924 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-13 16:34:35.952   758   848 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,09-13 16:34:35.952   758   848 I ActivityManager: Killing 6258:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,09-13 16:34:35.962   758   848 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-13 16:34:35.962   758   848 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 16:34:35.972  7060  7060 E Zygote  : v2
09-13 16:34:35.972  7060  7060 I libpersona: KNOX_SDCARD checking this for 10004
09-13 16:34:35.972  7060  7060 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:35.972   758   848 I ActivityManager: Start proc 7060:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,09-13 16:34:35.972  7060  7060 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:34:35.972  7060  7060 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:34:35.972  7060  7060 E Zygote  : accessInfo : 0
,09-13 16:34:35.972  7060  7060 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,09-13 16:34:35.982   758   848 I ActivityManager:   Force finishing activity ActivityRecord{a9d2e8a u0 com.test.thalitest/.MainActivity t168}
,09-13 16:34:35.982   758   924 D AASAinstall: there is not AASApackages.xml file
,09-13 16:34:35.982   293   363 I SurfaceFlinger: id=22 Removed NainActivit (4/10)
,09-13 16:34:35.982   293   363 I SurfaceFlinger: id=22 Removed NainActivit (-2/10)
,09-13 16:34:35.992   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbee0e38c
,09-13 16:34:36.002  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:36.002  7060  7060 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:36.022   758   776 D GraphicsStats: Buffer count: 5
,09-13 16:34:36.022   758  1629 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d9277b0)
,09-13 16:34:36.022   758  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:34:36.022   758  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:34:36.032   758  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:34:36.292   758   924 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-13 16:34:36.392   758   924 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 16:34:36.422   333   333 W keystore: ENTER clear_uid from uid 1000 for 10004
,09-13 16:34:36.422   758   924 I art     : Starting a blocking GC Explicit
,09-13 16:34:36.442  7060  7060 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,09-13 16:34:36.472  7060  7060 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
09-13 16:34:36.472  7060  7060 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,09-13 16:34:36.472  7060  7060 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
09-13 16:34:36.472  7060  7060 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,09-13 16:34:36.492  7060  7060 D AndroidRuntime: Shutting down VM
,09-13 16:34:36.502  7060  7060 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:34:36.502  7060  7060 E AndroidRuntime: Process: com.test.thalitest, PID: 7060
09-13 16:34:36.502  7060  7060 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
09-13 16:34:36.502  7060  7060 E AndroidRuntime: 	... 9 more
,09-13 16:34:36.502   758  2459 V AlarmManager:  remove PendingIntent] PendingIntent{e4f0dae: PendingIntentRecord{cb417c9 com.google.android.gms broadcastIntent}}
,09-13 16:34:36.542   758   848 I ActivityManager: Start proc 7087:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,09-13 16:34:36.542  7087  7087 E Zygote  : v2
09-13 16:34:36.542  7087  7087 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:36.542  7087  7087 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:36.542  7087  7087 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 16:34:36.542  7087  7087 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 16:34:36.552  7087  7087 E Zygote  : accessInfo : 0
,09-13 16:34:36.552  7060  7060 I Process : Sending signal. PID: 7060 SIG: 9
,09-13 16:34:36.572   758  1796 I ActivityManager: Process com.test.thalitest (pid 7060)(adj 9) has died(144,717)
,09-13 16:34:36.572   758  1796 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 16:34:36.572   758  1796 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 16:34:36.582   758  1796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26698 com.android.server.am.ActivityManagerService.appDiedLocked:7560 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,09-13 16:34:36.582   758   848 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,09-13 16:34:36.582   758   848 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,09-13 16:34:36.592  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:36.592  7087  7087 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:36.602   758   776 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{78256ba u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c7c96b 7087:com.samsung.android.sm/1000}
,09-13 16:34:36.622  7087  7087 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,09-13 16:34:36.672   758   924 I art     : Explicit concurrent mark sweep GC freed 89687(4MB) AllocSpace objects, 11(220KB) LOS objects, 27% free, 42MB/58MB, paused 3.206ms total 243.243ms
,09-13 16:34:36.672  7087  7087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,09-13 16:34:36.692   758  1629 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{78256ba u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4cdea04 4115:com.google.android.gms/u0a11}
,09-13 16:34:36.702   758   924 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 16:34:36.702   758   924 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
09-13 16:34:36.702   758   924 D AASAinstall: there is not AASApackages.xml file
,09-13 16:34:36.702   758   924 D PackageManager: result of delete: 1{188906850}
,09-13 16:34:36.702  7025  7025 I art     : System.exit called, status: 0
09-13 16:34:36.702  7025  7025 I AndroidRuntime: VM exiting with result code 0.
,09-13 16:34:36.702   758   924 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 16:34:36.702   758   924 D PackageManager: userId{-1}
09-13 16:34:36.702   758   924 D PackageManager: andCode{true}
,09-13 16:34:36.732   758   924 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,09-13 16:34:36.732  5814  7109 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-13 16:34:36.732  5814  7109 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-13 16:34:36.742  5814  7109 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-13 16:34:36.762   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.772   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.772   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.772  1379  1379 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
09-13 16:34:36.772  1379  1379 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,09-13 16:34:36.772   758   891 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.782   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.782   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.782   758   891 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.782  2050  2050 E SamsungIME: mOCRHelper is null
,09-13 16:34:36.792   758   848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff623f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{64a0ca 4356:com.samsung.klmsagent/u0a18}
,09-13 16:34:36.792   758  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:34:36.792   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.792   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.792   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.792   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.792   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.792   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.792  2074  2313 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 16:34:36.802  4356  4356 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Sep 13 16:34:36 GMT+02:00 2016
,09-13 16:34:36.802   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.802   758   758 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.812   758   758 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.812  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
09-13 16:34:36.812   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.812  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,09-13 16:34:36.812  4356  4356 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
09-13 16:34:36.812  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
09-13 16:34:36.812  1748  1748 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 16:34:36.812   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.822   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.822  3201  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
09-13 16:34:36.822   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.822   758  1415 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
09-13 16:34:36.822   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.822   758   841 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.832   758  1796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff623f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e1503 758:system/1000}
09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.832   758   758 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.832  2074  2200 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-13 16:34:36.832  2074  2200 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 16:34:36.842   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.842   758  1366 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,09-13 16:34:36.842  4356  4356 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,09-13 16:34:36.842  4356  4356 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 16:34:36.842   758  1366 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/168_task_thumbnail.png
,09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: Getting service failed
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at ivh.c(:com.google.android.gms:73)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bzx.b(:com.google.android.gms:415)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bzx.a(:com.google.android.gms:360)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bzx.a(:com.google.android.gms:142)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bre.M(:com.google.android.gms:10077)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bre.a(:com.google.android.gms:1318)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bre.l(:com.google.android.gms:160)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bxr.<init>(:com.google.android.gms:44)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at bxp.a(:com.google.android.gms:154)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at ilk.a(:com.google.android.gms:592)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at ioe.onTransact(:com.google.android.gms:824)
09-13 16:34:36.842  2074  2200 E AbstractServiceBroker: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 16:34:36.852   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.852   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.852   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.852   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.852   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.852  4356  4356 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 16:34:36.852   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.852  4115  4115 D AndroidRuntime: Shutting down VM
09-13 16:34:36.852   758  1322 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
,09-13 16:34:36.852   758  1322 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,09-13 16:34:36.852  4356  7115 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
09-13 16:34:36.852  4356  7115 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,09-13 16:34:36.862   758  1321 V NetworkStats: removeUidsLocked() for UIDs [10004]
09-13 16:34:36.862   758  1321 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:36.862   758  1321 V NetworkStats: performPollLocked(flags=0x3)
,09-13 16:34:36.862  4356  7115 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,09-13 16:34:36.862  4356  7115 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-13 16:34:36.862  4356  7115 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-13 16:34:36.862  4356  7115 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.862   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.872   758  1321 V NetworkStats: performPollLocked() took 15ms
09-13 16:34:36.872   758  1321 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:36.872  4356  7115 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-13 16:34:36.872  4356  7115 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 16:34:36.882   758  1322 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:36.882   758  1322 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:36.882   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.882   758   758 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.882   758   841 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.882   758   841 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.882  1738  7116 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
09-13 16:34:36.882  1738  7116 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
09-13 16:34:36.882  1738  7116 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
09-13 16:34:36.882  1738  7116 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
09-13 16:34:36.882  1738  7116 D RegisteredComponentCache: Collect Tech packages for Knox
09-13 16:34:36.892   758   758 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.892   758   758 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.892   758   758 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.892   758   758 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.892  4115  4115 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQtNg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
09-13 16:34:36.892  4115  4115 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM4KRjm-eAR
09-13 16:34:36.892  4115  4115 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
09-13 16:34:36.892  4115  4115 I GCore-Chimera-Crash: ==
09-13 16:34:36.892  4115  4115 I GCore-Chimera-Crash: GCore-Chimera-Crash
09-13 16:34:36.892  4356  7115 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 16:34:36.902  4356  7115 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
09-13 16:34:36.902  4115  4115 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
09-13 16:34:36.902   758   758 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.902   758   758 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.902   758   758 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.902   758   758 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.902  4115  4115 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
09-13 16:34:36.902  4115  4115 W SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
09-13 16:34:36.902  4115  4115 E SQLiteLog: (14) cannot open file at line 31517 of [2ef4f3a5b1]
09-13 16:34:36.902  4115  4115 E SQLiteLog: (14) os_unix.c:31517: (2) open(/data/user/0/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
09-13 16:34:36.902  4356  7115 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 1294): Could not open database
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: #################################################################
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: Error Code : 1294 (SQLITE_CANTOPEN_ENOENT)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: Caused By : Specified directory or database file does not exist.
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	(unknown error (code 1294): Could not open database)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: #################################################################
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:622)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:277)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:277)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at iiq.c(:com.google.android.gms:207)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
09-13 16:34:36.912  4115  4115 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912   758   758 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.912  4115  4115 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:34:36.912  4115  4115 E AndroidRuntime: Process: com.google.android.gms, PID: 4115
09-13 16:34:36.912  4115  4115 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1628)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1573)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at iof.a(:com.google.android.gms:1949)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at ilq.a(:com.google.android.gms:1293)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at idd.a(:com.google.android.gms:824)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at idh.run(:com.google.android.gms:712)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at jch.run(:com.google.android.gms:17)
09-13 16:34:36.912  4115  4115 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: #################################################################
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: #################################################################
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:34:36.912  4356  7115 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: #################################################################
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: #################################################################
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
09-13 16:34:36.922  4356  7115 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:36.922  4356  7115 W SQLiteOpenHelper: Opened klms.db in read-only mode
09-13 16:34:36.922   758   758 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.922   758   758 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.932   758   758 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.932   758   758 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.932   758   841 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.932   758   841 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.932   758   841 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.942  4356  7115 E SQLiteLog: (10) unixRead() File Descriptor : 21 gets errno : 5
09-13 16:34:36.942  4356  7115 E SQLiteLog: (266) statement aborts at 14: [SELECT TIME, TRACKER_ID, PACKAGE_NAME, _id, LICENSE_EXPIRY, LICENSE_STATUS, NEXT_VALIDATION, ALARM_TIME, ONPREM_INFO FROM deviceinfo] 
,09-13 16:34:36.942   758  1298 I EventHub: Removing device '/dev/input/event4' due to inotify event
09-13 16:34:36.942  4356  7115 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x732b7950 in tid 7115 (IntentService[K)
09-13 16:34:36.942   758   758 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.942   758   758 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.942  2379  2379 E audit_log: File locking failed. error= Bad file descriptor
09-13 16:34:36.942  2379  2379 E audit_log: File locking failed. error= Bad file descriptor
09-13 16:34:36.942   758   758 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.942   758   758 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.942   758   758 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.942   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758   758 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.952   758  3728 I ActivityManager: Process com.samsung.klmsagent (pid 4356)(adj 5) has died(169,703)
09-13 16:34:36.962   758  3728 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
09-13 16:34:36.962   758  3728 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   841 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.962   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.972   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.972   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.972   758   841 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9dfa4eec in tid 841 (android.bg)
09-13 16:34:36.972   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.972   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.972   758   841 F libc    : Unable to open connection to debuggerd: Connection refused
09-13 16:34:36.972   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
09-13 16:34:36.972  2379  2379 E audit_log: File locking failed. error= Bad file descriptor
,09-13 16:34:37.012   351   351 I Zygote  : Process 4356 exited due to signal (7)
,09-13 16:34:37.432   293   565 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
