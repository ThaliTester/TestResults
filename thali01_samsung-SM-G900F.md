#### Test 8091062436177d0_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-11 09:06:04.061   744  2269 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
08-11 09:06:04.061   744  2269 V MARsPolicyManager: updateSMDBValues
08-11 09:06:04.061   744   866 E MARsDBManager: updateDBAll : begin --size 0
08-11 09:06:04.061   744   866 E MARsDBManager: updateDBAll : end
08-11 09:06:04.071   744  2039 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,08-11 09:06:04.841   744  3460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-11 09:06:05.001   744  1237 V AlarmManager: Expired Alarm result :4
--------- beginning of main
08-11 09:06:05.001  2176  2176 E audit   : type=1400 msg=audit(1470899165.001:285): avc:  denied  { execmod } for  pid=6386 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 09:06:05.001  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:05.011  2176  2176 E audit   : type=1300 msg=audit(1470899165.001:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ffb000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6386 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 09:06:05.011  2176  2176 E audit   : type=1327 msg=audit(1470899165.001:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 09:06:05.011  2176  2176 E audit   : type=1320 msg=audit(1470899165.001:285): 
08-11 09:06:05.061  2176  2176 E audit   : type=1400 msg=audit(1470899165.061:286): avc:  denied  { execmod } for  pid=6386 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 09:06:05.061  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:05.061  2176  2176 E audit   : type=1300 msg=audit(1470899165.061:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fba000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6386 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 09:06:05.061  2176  2176 E audit   : type=1327 msg=audit(1470899165.061:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 09:06:05.061  2176  2176 E audit   : type=1320 msg=audit(1470899165.061:286): 
08-11 09:06:05.111  2176  2176 E audit   : type=1400 msg=audit(1470899165.111:287): avc:  denied  { execmod } for  pid=6386 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 09:06:05.111  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:05.111  2176  2176 E audit   : type=1300 msg=audit(1470899165.111:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb8000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6386 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 09:06:05.111  2176  2176 E audit   : type=1327 msg=audit(1470899165.111:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 09:06:05.111  2176  2176 E audit   : type=1320 msg=audit(1470899165.111:287): 
08-11 09:06:05.111  6386  6386 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 09:06:05.121  6386  6386 D AndroidRuntime: CheckJNI is OFF
08-11 09:06:05.121  6386  6386 D AndroidRuntime: readGMSProperty: start
08-11 09:06:05.121  6386  6386 D AndroidRuntime: readGMSProperty: already setted!!
08-11 09:06:05.121  6386  6386 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-11 09:06:05.121  6386  6386 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-11 09:06:05.121  6386  6386 D AndroidRuntime: readGMSProperty: end
08-11 09:06:05.121  6386  6386 D AndroidRuntime: addProductProperty: start
08-11 09:06:05.121  6386  6386 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 09:06:05.121  6386  6386 W art     : af164000-b208a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-11 09:06:05.121  6386  6386 W art     : b208a000-b42f9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-11 09:06:05.121  6386  6386 W art     : b42f9000-b42fa000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-11 09:06:05.121  6386  6386 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 09:06:05.121  6386  6386 W art     : b4323000-b4771000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-11 09:06:05.121  6386  6386 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b4772000-b477c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-11 09:06:05.121  6386  6386 W art     : b477c000-b477d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-11 09:06:05.121  6386  6386 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-11 09:06:05.121  6386  6386 W art     : b488a000-b488d000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-11 09:06:05.121  6386  6386 W art     : b488d000-b488e000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-11 09:06:05.121  6386  6386 W art     : b488e000-b488f000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-11 09:06:05.121  6386  6386 W art     : b488f000-b4890000 r--p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b4890000-b48b0000 r--s 00000000 00:0b 8249       /dev/__properties__
08-11 09:06:05.121  6386  6386 W art     : b48b0000-b52c1000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-11 09:06:05.121  6386  6386 W art     : b52c1000-b52c2000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b52c2000-b530b000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-11 09:06:05.121  6386  6386 W art     : b530b000-b530c000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-11 09:06:05.121  6386  6386 W art     : b530c000-b5314000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5314000-b5315000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.121  6386  6386 W art     : b5315000-b534a000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-11 09:06:05.121  6386  6386 W art     : b534a000-b534b000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b534b000-b534c000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-11 09:06:05.121  6386  6386 W art     : b534c000-b534d000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-11 09:06:05.121  6386  6386 W art     : b534d000-b53a5000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-11 09:06:05.121  6386  6386 W art     : b53a5000-b53a6000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b53a6000-b53a7000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-11 09:06:05.121  6386  6386 W art     : b53a7000-b53a8000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-11 09:06:05.121  6386  6386 W art     : b53a9000-b53af000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 09:06:05.121  6386  6386 W art     : b53af000-b53b0000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 09:06:05.121  6386  6386 W art     : b53b0000-b53b1000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 09:06:05.121  6386  6386 W art     : b53b1000-b53b3000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b53b4000-b53be000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 09:06:05.121  6386  6386 W art     : b53be000-b53c1000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 09:06:05.121  6386  6386 W art     : b53c1000-b53c2000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 09:06:05.121  6386  6386 W art     : b53c3000-b53da000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 09:06:05.121  6386  6386 W art     : b53da000-b53db000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b53db000-b53dc000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 09:06:05.121  6386  6386 W art     : b53dc000-b53dd000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 09:06:05.121  6386  6386 W art     : b53de000-b53e8000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-11 09:06:05.121  6386  6386 W art     : b53e8000-b53e9000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-11 09:06:05.121  6386  6386 W art     : b53e9000-b53ea000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-11 09:06:05.121  6386  6386 W art     : b53ea000-b53ee000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 09:06:05.121  6386  6386 W art     : b53ee000-b53ef000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 09:06:05.121  6386  6386 W art     : b53ef000-b53f0000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 09:06:05.121  6386  6386 W art     : b53f0000-b5406000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-11 09:06:05.121  6386  6386 W art     : b5406000-b5407000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-11 09:06:05.121  6386  6386 W art     : b5407000-b5408000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-11 09:06:05.121  6386  6386 W art     : b5408000-b5415000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-11 09:06:05.121  6386  6386 W art     : b5415000-b5416000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-11 09:06:05.121  6386  6386 W art     : b5416000-b5417000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-11 09:06:05.121  6386  6386 W art     : b5417000-b5477000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-11 09:06:05.121  6386  6386 W art     : b5477000-b547a000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-11 09:06:05.121  6386  6386 W art     : b547a000-b547e000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b547e000-b54df000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-11 09:06:05.121  6386  6386 W art     : b54df000-b54e0000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-11 09:06:05.121  6386  6386 W art     : b54e0000-b552f000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-11 09:06:05.121  6386  6386 W art     : b552f000-b5531000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-11 09:06:05.121  6386  6386 W art     : b5531000-b5532000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-11 09:06:05.121  6386  6386 W art     : b5532000-b5533000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5533000-b553a000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 09:06:05.121  6386  6386 W art     : b553a000-b553b000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 09:06:05.121  6386  6386 W art     : b553b000-b553c000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-11 09:06:05.121  6386  6386 W art     : avc_common.so
08-11 09:06:05.121  6386  6386 W art     : b553d000-b5540000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 09:06:05.121  6386  6386 W art     : b5540000-b5541000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 09:06:05.121  6386  6386 W art     : b5541000-b5542000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-11 09:06:05.121  6386  6386 W art     : enc_common.so
08-11 09:06:05.121  6386  6386 W art     : b5543000-b5547000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-11 09:06:05.121  6386  6386 W art     : b5547000-b5548000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5548000-b5549000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-11 09:06:05.121  6386  6386 W art     : b5549000-b554a000 rw-p 00005000 b3:17 2510       /syste
08-11 09:06:05.121  6386  6386 W art     : m/lib/libpowermanager.so
08-11 09:06:05.121  6386  6386 W art     : b554b000-b5568000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 09:06:05.121  6386  6386 W art     : b5568000-b5569000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 09:06:05.121  6386  6386 W art     : b5569000-b556a000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 09:06:05.121  6386  6386 W art     : b556b000-b5570000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 09:06:05.121  6386  6386 W art     : b5570000-b5571000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 09:06:05.121  6386  6386 W art     : b5571000-b5572000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 09:06:05.121  6386  6386 W art     : b5573000-b55a4000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 09:06:05.121  6386  6386 W art     : b55a4000-b55a7000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 09:06:05.121  6386  6386 W art     : b55a7000-b55a8000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 09:06:05.121  6386  6386 W art     : b55a9000-b55e4000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-11 09:06:05.121  6386  6386 W art     : b55e4000-b55e5000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-11 09:06:05.121  6386  6386 W art     : b55e5000-b55e6000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-11 09:06:05.121  6386  6386 W art     : b55e7000-b55ee000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-11 09:06:05.121  6386  6386 W art     : b55ee000-b55ef000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b55ef000-b55f0000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-11 09:06:05.121  6386  6386 W art     : b55f0000-b55f1000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-11 09:06:05.121  6386  6386 W art     : b55f1000-b55f2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.121  6386  6386 W art     : b55f2000-b5609000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-11 09:06:05.121  6386  6386 W art     : b5609000-b560a000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b560a000-b560d000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-11 09:06:05.121  6386  6386 W art     : b560d000-b560e000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-11 09:06:05.121  6386  6386 W art     : b560e000-b562d000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-11 09:06:05.121  6386  6386 W art     : b562d000-b562e000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-11 09:06:05.121  6386  6386 W art     : b562e000-b562f000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-11 09:06:05.121  6386  6386 W art     : b562f000-b566d000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-11 09:06:05.121  6386  6386 W art     : b566d000-b566e000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b566e000-b5670000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-11 09:06:05.121  6386  6386 W art     : b5670000-b5671000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-11 09:06:05.121  6386  6386 W art     : b5672000-b5679000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 09:06:05.121  6386  6386 W art     : b5679000-b567a000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 09:06:05.121  6386  6386 W art     : b567a000-b567b000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 09:06:05.121  6386  6386 W art     : b567c000-b567f000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 09:06:05.121  6386  6386 W art     : b567f000-b5680000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 09:06:05.121  6386  6386 W art     : b5680000-b5681000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 09:06:05.121  6386  6386 W art     : b5681000-b5687000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 09:06:05.121  6386  6386 W art     : b5687000-b5688000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5688000-b5689000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 09:06:05.121  6386  6386 W art     : b5689000-b568a000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 09:06:05.121  6386  6386 W art     : b568a000-b5693000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-11 09:06:05.121  6386  6386 W art     : b5693000-b5694000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-11 09:06:05.121  6386  6386 W art     : b5694000-b5695000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-11 09:06:05.121  6386  6386 W art     : b5695000-b5726000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 09:06:05.121  6386  6386 W art     : b5726000-b5727000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5727000-b5732000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 09:06:05.121  6386  6386 W art     : b5732000-b5733000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 09:06:05.121  6386  6386 W art     : b5734000-b5746000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-11 09:06:05.121  6386  6386 W art     : b5746000-b5747000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-11 09:06:05.121  6386  6386 W art     : b5747000-b5748000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-11 09:06:05.121  6386  6386 W art     : b5749000-b574e000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-11 09:06:05.121  6386  6386 W art     : b574e000-b574f000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-11 09:06:05.121  6386  6386 W art     : b574f000-b5750000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-11 09:06:05.121  6386  6386 W art     : b5751000-b57be000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-11 09:06:05.121  6386  6386 W art     : b57be000-b57bf000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b57bf000-b57c1000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-11 09:06:05.121  6386  6386 W art     : b57c1000-b57c2000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-11 09:06:05.121  6386  6386 W art     : b57c2000-b57c3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.121  6386  6386 W art     : b57c3000-b57ca000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 09:06:05.121  6386  6386 W art     : b57ca000-b57cb000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 09:06:05.121  6386  6386 W art     : b57cb000-b57cc000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 09:06:05.121  6386  6386 W art     : b57cd000-b584d000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 09:06:05.121  6386  6386 W art     : b584d000-b584e000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b584e000-b584f000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 09:06:05.121  6386  6386 W art     : b584f000-b5850000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 09:06:05.121  6386  6386 W art     : b5850000-b5867000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5867000-b589e000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-11 09:06:05.121  6386  6386 W art     : ib/libqc-opt.so
08-11 09:06:05.121  6386  6386 W art     : b589e000-b589f000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 09:06:05.121  6386  6386 W art     : b589f000-b58a0000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 09:06:05.121  6386  6386 W art     : b58a0000-b58bc000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 09:06:05.121  6386  6386 W art     : b58bc000-b58bd000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 09:06:05.121  6386  6386 W art     : b58bd000-b58be000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 09:06:05.121  6386  6386 W art     : b58bf000-b5920000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-11 09:06:05.121  6386  6386 W art     : b5920000-b5922000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-11 09:06:05.121  6386  6386 W art     : b5922000-b5923000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-11 09:06:05.121  6386  6386 W art     : b5924000-b594b000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-11 09:06:05.121  6386  6386 W art     : b594b000-b594c000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b594c000-b594d000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-11 09:06:05.121  6386  6386 W art     : b594d000-b594e000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-11 09:06:05.121  6386  6386 W art     : b594f000-b5957000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 09:06:05.121  6386  6386 W art     : b5957000-b5959000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 09:06:05.121  6386  6386 W art     : b5959000-b595a000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 09:06:05.121  6386  6386 W art     : b595b000-b595e000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-11 09:06:05.121  6386  6386 W art     : b595e000-b595f000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-11 09:06:05.121  6386  6386 W art     : b595f000-b5960000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-11 09:06:05.121  6386  6386 W art     : b5960000-b5964000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-11 09:06:05.121  6386  6386 W art     : b5964000-b5965000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5965000-b5966000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-11 09:06:05.121  6386  6386 W art     : b5966000-b5967000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-11 09:06:05.121  6386  6386 W art     : b5967000-b5977000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-11 09:06:05.121  6386  6386 W art     : b5977000-b5978000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-11 09:06:05.121  6386  6386 W art     : b5978000-b5979000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-11 09:06:05.121  6386  6386 W art     : b5979000-b59bf000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b59bf000-b59c8000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-11 09:06:05.121  6386  6386 W art     : b59c8000-b59c9000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-11 09:06:05.121  6386  6386 W art     : b59c9000-b59ca000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-11 09:06:05.121  6386  6386 W art     : b59cb000-b59d0000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-11 09:06:05.121  6386  6386 W art     : b59d0000-b59d1000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-11 09:06:05.121  6386  6386 W art     : b59d1000-b59d2000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-11 09:06:05.121  6386  6386 W art     : b59d2000-b59d5000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 09:06:05.121  6386  6386 W art     : b59d5000-b59d6000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b59d6000-b59d7000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 09:06:05.121  6386  6386 W art     : b59d7000-b59d8000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 09:06:05.121  6386  6386 W art     : b59d9000-b59f1000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 09:06:05.121  6386  6386 W art     : b59f1000-b59f2000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b59f2000-b59f3000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 09:06:05.121  6386  6386 W art     : b59f3000-b59f4000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 09:06:05.121  6386  6386 W art     : b59f5000-b5b8f000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-11 09:06:05.121  6386  6386 W art     : b5b8f000-b5b90000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5b90000-b5b9d000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-11 09:06:05.121  6386  6386 W art     : b5b9d000-b5b9e000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-11 09:06:05.121  6386  6386 W art     : b5b9e000-b5ba2000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-11 09:06:05.121  6386  6386 W art     : b5ba2000-b5ba3000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5ba3000-b5ba4000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-11 09:06:05.121  6386  6386 W art     : b5ba4000-b5ba5000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-11 09:06:05.121  6386  6386 W art     : b5ba5000-b5bb8000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-11 09:06:05.121  6386  6386 W art     : b5bb8000-b5bb9000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-11 09:06:05.121  6386  6386 W art     : b5bb9000-b5bba000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-11 09:06:05.121  6386  6386 W art     : b5bba000-b5bbb000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:05.121  6386  6386 W art     : b5bbb000-b5c06000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-11 09:06:05.121  6386  6386 W art     : b5c06000-b5c07000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-11 09:06:05.121  6386  6386 W art     : b5c07000-b5c08000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-11 09:06:05.121  6386  6386 W art     : b5c08000-b5c0a000 rw-p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5c0b000-b5c1c000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 09:06:05.121  6386  6386 W art     : b5c1c000-b5c1d000 ---p 00000000 00:00 0 
08-11 09:06:05.121  6386  6386 W art     : b5c1d000-b5c1e000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 09:06:05.121  6386  6386 W art     : b5c1e000-b5c1f000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 09:06:05.131  6386  6386 W art     : b5c20000-b5c2a000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-11 09:06:05.131  6386  6386 W art     : b5c2a000-b5c2c000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-11 09:06:05.131  6386  6386 W art     : b5c2c000-b5c2d000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-11 09:06:05.131  6386  6386 W art     : b5c2d000-b5c46000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-11 09:06:05.131  6386  6386 W art     : b5c46000-b5c47000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-11 09:06:05.131  6386  6386 W art     : b5c47000-b5c4a000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-11 09:06:05.131  6386  6386 W art     : b5c4a000-b5c4e000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b5c4e000-b5cc2000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-11 09:06:05.131  6386  6386 W art     : b5cc2000-b5cc3000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b5cc3000-b5cc6000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-11 09:06:05.131  6386  6386 W art     : b5cc6000-b5cc7000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-11 09:06:05.131  6386  6386 W art     : b5cc7000-b5cc8000 r--p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b5cc8000-b5ccb000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-11 09:06:05.131  6386  6386 W art     : b5ccb000-b5ccc000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-11 09:06:05.131  6386  6386 W art     : b5ccc000-b5ccd000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-11 09:06:05.131  6386  6386 W art     : b5ccd000-b5cce000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b5cce000-b5cd3000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 09:06:05.131  6386  6386 W art     : b5cd3000-b5cd4000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 09:06:05.131  6386  6386 W art     : b5cd4000-b5cd5000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 09:06:05.131  6386  6386 W art     : b5cd5000-b5cd6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b5cd6000-b5cd9000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 09:06:05.131  6386  6386 W art     : b5cd9000-b5cda000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 09:06:05.131  6386  6386 W art     : b5cda000-b5cdb000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 09:06:05.131  6386  6386 W art     : b5cdb000-b5cdc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b5cdc000-b5ce0000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-11 09:06:05.131  6386  6386 W art     : b5ce0000-b5ce1000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-11 09:06:05.131  6386  6386 W art     : b5ce1000-b5ce2000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-11 09:06:05.131  6386  6386 W art     : b5ce2000-b5ce3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:05.131  6386  6386 W art     : b5ce3000-b5ce7000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 09:06:05.131  6386  6386 W art     : b5ce7000-b5ce8000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 09:06:05.131  6386  6386 W art     : b5ce8000-b5ce9000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 09:06:05.131  6386  6386 W art     : b5ce9000-b5cea000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b5cea000-b5cf8000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-11 09:06:05.131  6386  6386 W art     : b5cf8000-b5cf9000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b5cf9000-b5cfa000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-11 09:06:05.131  6386  6386 W art     : b5cfa000-b5cfb000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-11 09:06:05.131  6386  6386 W art     : b5cfb000-b5d05000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 09:06:05.131  6386  6386 W art     : b5d05000-b5d08000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 09:06:05.131  6386  6386 W art     : b5d08000-b5d09000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 09:06:05.131  6386  6386 W art     : b5d09000-b5d0a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b5d0a000-b5d14000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-11 09:06:05.131  6386  6386 W art     : b5d14000-b5d17000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-11 09:06:05.131  6386  6386 W art     : b5d17000-b5d18000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-11 09:06:05.131  6386  6386 W art     : b5d18000-b5d1c000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-11 09:06:05.131  6386  6386 W art     : b5d1c000-b5d1d000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-11 09:06:05.131  6386  6386 W art     : b5d1d000-b5d1e000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-11 09:06:05.131  6386  6386 W art     : b5d1e000-b5d1f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b5d1f000-b5d2c000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-11 09:06:05.131  6386  6386 W art     : b5d2c000-b5d2e000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-11 09:06:05.131  6386  6386 W art     : b5d2e000-b5d2f000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-11 09:06:05.131  6386  6386 W art     : b5d2f000-b6141000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-11 09:06:05.131  6386  6386 W art     : b6141000-b6142000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6142000-b614b000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-11 09:06:05.131  6386  6386 W art     : b614b000-b614f000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-11 09:06:05.131  6386  6386 W art     : b614f000-b6150000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6150000-b6157000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-11 09:06:05.131  6386  6386 W art     : b6157000-b6158000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-11 09:06:05.131  6386  6386 W art     : b6158000-b6159000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-11 09:06:05.131  6386  6386 W art     : b6159000-b615a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b615a000-b6175000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-11 09:06:05.131  6386  6386 W art     : b6175000-b6176000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-11 09:06:05.131  6386  6386 W art     : b6176000-b6177000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-11 09:06:05.131  6386  6386 W art     : b6177000-b6178000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6178000-b61c4000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 09:06:05.131  6386  6386 W art     : b61c4000-b61c5000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b61c5000-b61c6000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 09:06:05.131  6386  6386 W art     : b61c6000-b61c7000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 09:06:05.131  6386  6386 W art     : b61c7000-b61c8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b61c8000-b61cc000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-11 09:06:05.131  6386  6386 W art     : b61cc000-b61cd000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b61cd000-b61ce000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-11 09:06:05.131  6386  6386 W art     : b61ce000-b61cf000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-11 09:06:05.131  6386  6386 W art     : b61cf000-b6207000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-11 09:06:05.131  6386  6386 W art     : b6207000-b6208000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-11 09:06:05.131  6386  6386 W art     : b6208000-b6209000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-11 09:06:05.131  6386  6386 W art     : b6209000-b620a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b620a000-b62a8000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-11 09:06:05.131  6386  6386 W art     : b62a8000-b62a9000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b62a9000-b62c7000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-11 09:06:05.131  6386  6386 W art     : b62c7000-b62c8000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-11 09:06:05.131  6386  6386 W art     : b62c8000-b643b000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-11 09:06:05.131  6386  6386 W art     : b643b000-b6446000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-11 09:06:05.131  6386  6386 W art     : b6446000-b6447000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-11 09:06:05.131  6386  6386 W art     : b6447000-b655e000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-11 09:06:05.131  6386  6386 W art     : b655e000-b6569000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-11 09:06:05.131  6386  6386 W art     : b6569000-b656a000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-11 09:06:05.131  6386  6386 W art     : b656a000-b656e000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b656e000-b6592000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-11 09:06:05.131  6386  6386 W art     : b6592000-b6594000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-11 09:06:05.131  6386  6386 W art     : b6594000-b6595000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-11 09:06:05.131  6386  6386 W art     : b6595000-b663b000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-11 09:06:05.131  6386  6386 W art     : b663b000-b6648000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-11 09:06:05.131  6386  6386 W art     : b6648000-b6649000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-11 09:06:05.131  6386  6386 W art     : b6649000-b664a000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b664a000-b669d000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-11 09:06:05.131  6386  6386 W art     : b669d000-b669e000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b669e000-b669f000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-11 09:06:05.131  6386  6386 W art     : b669f000-b66a0000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-11 09:06:05.131  6386  6386 W art     : b66a0000-b66a5000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b66a5000-b66b7000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-11 09:06:05.131  6386  6386 W art     : b66b7000-b66b8000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b66b8000-b66b9000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-11 09:06:05.131  6386  6386 W art     : b66b9000-b66ba000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-11 09:06:05.131  6386  6386 W art     : b66ba000-b66c1000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 09:06:05.131  6386  6386 W art     : b66c1000-b66c2000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 09:06:05.131  6386  6386 W art     : b66c2000-b66c3000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 09:06:05.131  6386  6386 W art     : b66c3000-b66c4000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b66c4000-b66c7000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-11 09:06:05.131  6386  6386 W art     : b66c7000-b66c8000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-11 09:06:05.131  6386  6386 W art     : b66c8000-b66c9000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-11 09:06:05.131  6386  6386 W art     : b66c9000-b66cd000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-11 09:06:05.131  6386  6386 W art     : b66cd000-b66ce000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-11 09:06:05.131  6386  6386 W art     : b66ce000-b66cf000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-11 09:06:05.131  6386  6386 W art     : b66cf000-b66dd000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-11 09:06:05.131  6386  6386 W art     : b66dd000-b66de000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b66de000-b66df000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-11 09:06:05.131  6386  6386 W art     : b66df000-b66e0000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-11 09:06:05.131  6386  6386 W art     : b66e0000-b66e9000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 09:06:05.131  6386  6386 W art     : b66e9000-b66ea000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 09:06:05.131  6386  6386 W art     : b66ea000-b66eb000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 09:06:05.131  6386  6386 W art     : b66eb000-b6751000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-11 09:06:05.131  6386  6386 W art     : b6751000-b6752000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6752000-b6754000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-11 09:06:05.131  6386  6386 W art     : b6754000-b675d000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-11 09:06:05.131  6386  6386 W art     : b675d000-b6760000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6760000-b67f7000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-11 09:06:05.131  6386  6386 W art     : b67f7000-b67f9000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-11 09:06:05.131  6386  6386 W art     : b67f9000-b67fa000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-11 09:06:05.131  6386  6386 W art     : b67fa000-b67fb000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b67fb000-b6b1c000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-11 09:06:05.131  6386  6386 W art     : b6b1c000-b6b1d000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6b1d000-b6b38000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-11 09:06:05.131  6386  6386 W art     : b6b38000-b6b3c000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-11 09:06:05.131  6386  6386 W art     : b6b3c000-b6b41000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6b41000-b6b49000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 09:06:05.131  6386  6386 W art     : b6b49000-b6b4a000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 09:06:05.131  6386  6386 W art     : b6b4a000-b6b4b000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 09:06:05.131  6386  6386 W art     : b6b4b000-b6b79000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-11 09:06:05.131  6386  6386 W art     : b6b79000-b6b7a000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6b7a000-b6b81000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-11 09:06:05.131  6386  6386 W art     : b6b81000-b6b82000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-11 09:06:05.131  6386  6386 W art     : b6b82000-b6bc8000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-11 09:06:05.131  6386  6386 W art     : b6bc8000-b6bc9000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6bc9000-b6bcc000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-11 09:06:05.131  6386  6386 W art     : b6bcc000-b6bcd000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-11 09:06:05.131  6386  6386 W art     : b6bcd000-b6be8000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-11 09:06:05.131  6386  6386 W art     : b6be8000-b6bec000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-11 09:06:05.131  6386  6386 W art     : b6bec000-b6bed000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-11 09:06:05.131  6386  6386 W art     : b6bed000-b6c3a000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-11 09:06:05.131  6386  6386 W art     : b6c3a000-b6c3b000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6c3b000-b6c47000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-11 09:06:05.131  6386  6386 W art     : b6c47000-b6c48000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-11 09:06:05.131  6386  6386 W art     : b6c48000-b6c55000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-11 09:06:05.131  6386  6386 W art     : b6c55000-b6c56000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6c56000-b6c57000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-11 09:06:05.131  6386  6386 W art     : b6c57000-b6c58000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-11 09:06:05.131  6386  6386 W art     : b6c58000-b6c60000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-11 09:06:05.131  6386  6386 W art     : b6c60000-b6c61000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6c61000-b6c62000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-11 09:06:05.131  6386  6386 W art     : b6c62000-b6c63000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-11 09:06:05.131  6386  6386 W art     : b6c63000-b6c6a000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-11 09:06:05.131  6386  6386 W art     : b6c6a000-b6c6b000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-11 09:06:05.131  6386  6386 W art     : b6c6b000-b6c6c000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-11 09:06:05.131  6386  6386 W art     : b6c6c000-b6c80000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-11 09:06:05.131  6386  6386 W art     : b6c80000-b6c82000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-11 09:06:05.131  6386  6386 W art     : b6c82000-b6c83000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-11 09:06:05.131  6386  6386 W art     : b6c83000-b6cab000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-11 09:06:05.131  6386  6386 W art     : b6cab000-b6cad000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-11 09:06:05.131  6386  6386 W art     : b6cad000-b6cae000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-11 09:06:05.131  6386  6386 W art     : b6cae000-b6cb1000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-11 09:06:05.131  6386  6386 W art     : b6cb1000-b6cb2000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-11 09:06:05.131  6386  6386 W art     : b6cb2000-b6cb3000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-11 09:06:05.131  6386  6386 W art     : b6cb3000-b6cbc000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-11 09:06:05.131  6386  6386 W art     : b6cbc000-b6cbd000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-11 09:06:05.131  6386  6386 W art     : b6cbd000-b6cbe000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-11 09:06:05.131  6386  6386 W art     : b6cbe000-b6cde000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-11 09:06:05.131  6386  6386 W art     : b6cde000-b6cdf000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-11 09:06:05.131  6386  6386 W art     : b6cdf000-b6ce0000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-11 09:06:05.131  6386  6386 W art     : b6ce0000-b6d53000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-11 09:06:05.131  6386  6386 W art     : b6d53000-b6d57000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-11 09:06:05.131  6386  6386 W art     : b6d57000-b6d5a000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-11 09:06:05.131  6386  6386 W art     : b6d5a000-b6d64000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6d64000-b6dec000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-11 09:06:05.131  6386  6386 W art     : b6dec000-b6ded000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6ded000-b6df1000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-11 09:06:05.131  6386  6386 W art     : b6df1000-b6df2000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-11 09:06:05.131  6386  6386 W art     : b6df2000-b6df3000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6df3000-b6e1c000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-11 09:06:05.131  6386  6386 W art     : b6e1c000-b6e1d000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6e1d000-b6e20000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-11 09:06:05.131  6386  6386 W art     : b6e20000-b6e21000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-11 09:06:05.131  6386  6386 W art     : b6e21000-b6efb000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 09:06:05.131  6386  6386 W art     : b6efb000-b6f02000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 09:06:05.131  6386  6386 W art     : b6f02000-b6f0a000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 09:06:05.131  6386  6386 W art     : b6f0a000-b6f0b000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6f0b000-b6f0c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:05.131  6386  6386 W art     : b6f0c000-b6f0d000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-11 09:06:05.131  6386  6386 W art     : b6f0d000-b6f0e000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6f0e000-b6f11000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6f11000-b6f36000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-11 09:06:05.131  6386  6386 W art     : b6f36000-b6f37000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6f37000-b6f3e000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-11 09:06:05.131  6386  6386 W art     : b6f3e000-b6f3f000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-11 09:06:05.131  6386  6386 W art     : b6f3f000-b6f46000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-11 09:06:05.131  6386  6386 W art     : b6f46000-b6f47000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-11 09:06:05.131  6386  6386 W art     : b6f47000-b6f48000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-11 09:06:05.131  6386  6386 W art     : b6f48000-b6f49000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6f49000-b6f61000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-11 09:06:05.131  6386  6386 W art     : b6f61000-b6f62000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6f62000-b6f63000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-11 09:06:05.131  6386  6386 W art     : b6f63000-b6f64000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-11 09:06:05.131  6386  6386 W art     : b6f64000-b6f72000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-11 09:06:05.131  6386  6386 W art     : b6f72000-b6f73000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6f73000-b6f74000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-11 09:06:05.131  6386  6386 W art     : b6f74000-b6f75000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-11 09:06:05.131  6386  6386 W art     : b6f75000-b6f76000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:05.131  6386  6386 W art     : b6f76000-b6f78000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6f78000-b6f79000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6f79000-b6f7a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:05.131  6386  6386 W art     : b6f7a000-b6f7b000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-11 09:06:05.131  6386  6386 W art     : b6f7b000-b6f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:05.131  6386  6386 W art     : b6f7c000-b6f9c000 r--s 00000000 00:0b 8249       /dev/__properties__
08-11 09:06:05.131  6386  6386 W art     : b6f9c000-b6f9d000 r--p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6f9d000-b6f9e000 ---p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6f9e000-b6fa0000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-11 09:06:05.131  6386  6386 W art     : b6fa0000-b6fa1000 r-xp 00000000 00:00 0          [sigpage]
08-11 09:06:05.131  6386  6386 W art     : b6fa1000-b6fbc000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-11 09:06:05.131  6386  6386 W art     : b6fbc000-b6fbd000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-11 09:06:05.131  6386  6386 W art     : b6fbd000-b6fbf000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-11 09:06:05.131  6386  6386 W art     : b6fbf000-b6fc1000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : b6fc1000-b6fc6000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-11 09:06:05.131  6386  6386 W art     : b6fc6000-b6fc7000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-11 09:06:05.131  6386  6386 W art     : b6fc7000-b6fc8000 rw-p 00000000 00:00 0 
08-11 09:06:05.131  6386  6386 W art     : bedfe000-bee1f000 rw-p 00000000 00:00 0          [stack]
08-11 09:06:05.131  6386  6386 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-11 09:06:05.161  6386  6386 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 09:06:05.211  6386  6386 I Radio-JNI: register_android_hardware_Radio DONE
08-11 09:06:05.221  6386  6386 E AffinityControl: AffinityControl: registerfunction enter
08-11 09:06:05.241  6386  6386 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 09:06:05.251   744  2266 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-11 09:06:05.271   744  2266 D ActivityManager: mDVFSHelper.acquire()
08-11 09:06:05.271   744  2266 V WindowManager: addAppToken: AppWindowToken{6523cf1 token=Token{103ec98 ActivityRecord{70b867b u0 com.test.thalitest/.MainActivity t153}}} to stack=1 task=153 at 0
08-11 09:06:05.301  6402  6402 E Zygote  : v2
08-11 09:06:05.301  6402  6402 I libpersona: KNOX_SDCARD checking this for 10004
08-11 09:06:05.301   744  2266 I ActivityManager: Start proc 6402:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-11 09:06:05.301  6402  6402 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:05.301   744  2266 D InputDispatcher: Focused application set to: xxxx
08-11 09:06:05.301  6402  6402 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:05.301  6402  6402 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:05.301   744   868 D SecWifiDisplayUtil: Metadata value : none
08-11 09:06:05.301   744   868 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{bda9929 V.E...... R.....ID 0,0-0,0}
08-11 09:06:05.301  6402  6402 E Zygote  : accessInfo : 0
08-11 09:06:05.301  6402  6402 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-11 09:06:05.301   744  2266 D InputDispatcher: Focus left window: 4409
08-11 09:06:05.301   744   868 D ISSUE_DEBUG: InputChannelName : e99924f Starting com.test.thalitest
08-11 09:06:05.301   744  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 09:06:05.301   744   800 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ac462ce u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-11 09:06:05.301  6386  6386 D AndroidRuntime: Shutting down VM
08-11 09:06:05.311  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-11 09:06:05.321   293   293 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
08-11 09:06:05.331  6402  6402 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:05.331  6402  6402 D ActivityThread: Added TimaKeyStore provider
08-11 09:06:05.331   744   868 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
08-11 09:06:05.331   744   868 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 09:06:05.331   744   868 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-11 09:06:05.331   744   868 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-11 09:06:05.331   744   868 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-11 09:06:05.331   744  1321 V WindowOrientationListener: setCurrentAppOrientation :-1
08-11 09:06:05.331   744  1321 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-11 09:06:05.341   744   800 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e99924f u0 d0 Starting com.test.thalitest}
08-11 09:06:05.341  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-11 09:06:05.351   744  1321 D ActivityManager:  Launching com.test.thalitest, updated priority
08-11 09:06:05.371  1669  1883 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-11 09:06:05.371  1669  1669 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-11 09:06:05.381   744   868 V WindowStateAnimator: Finishing drawing window Window{e99924f u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-11 09:06:05.381   293  1297 I SurfaceFlinger: id=14 Removed YUIInstallC (6/10)
08-11 09:06:05.391   293   337 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-11 09:06:05.391   293   337 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-11 09:06:05.391   293   337 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/10)
08-11 09:06:05.391  4409  4409 V ActivityThread: updateVisibility : ActivityRecord{e954803 token=android.os.BinderProxy@fd2efe4 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-11 09:06:05.391   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe963364
08-11 09:06:05.401   293  1297 I SurfaceFlinger: id=7 Removed Mauncher (4/9)
08-11 09:06:05.401   293   339 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-11 09:06:05.401  1669  1669 V ActivityThread: updateVisibility : ActivityRecord{c5143a1 token=android.os.BinderProxy@ee1b836 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-11 09:06:05.401  1669  1669 D Launcher: onTrimMemory. Level: 20
08-11 09:06:05.401  2287  2318 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-11 09:06:05.411   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9633a4
,08-11 09:06:05.671   744  1321 I WindowManager: Screenshot max retries 4 of Token{103ec98 ActivityRecord{70b867b u0 com.test.thalitest/.MainActivity t153}} appWin=Window{e99924f u0 d0 Starting com.test.thalitest} drawState=4
,08-11 09:06:05.681   744   798 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-11 09:06:05.681   744  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-11 09:06:05.701  6402  6402 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 09:06:05.701   744  3432 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 09:06:05.721  6402  6402 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 09:06:05.721  6402  6402 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 09:06:05.741  6402  6402 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-11 09:06:05.761  6402  6402 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 09:06:05.761  6402  6402 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 09:06:05.771  6402  6402 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 6741-6744)
,08-11 09:06:05.771  6402  6402 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-11 09:06:05.791  6402  6402 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {97b7946}
,08-11 09:06:05.791  6402  6402 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-11 09:06:05.791  6402  6402 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 09:06:05.801  6402  6423 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-11 09:06:05.801  6402  6402 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-11 09:06:05.821  6402  6402 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-11 09:06:05.821  6402  6402 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-11 09:06:05.821  6402  6402 I Adreno-EGL: Build Date: 01/28/16 Thu
08-11 09:06:05.821  6402  6402 I Adreno-EGL: Local Branch: ss
08-11 09:06:05.821  6402  6402 I Adreno-EGL: Remote Branch: 
08-11 09:06:05.821  6402  6402 I Adreno-EGL: Local Patches: 
08-11 09:06:05.821  6402  6402 I Adreno-EGL: Reconstruct Branch: 
,08-11 09:06:05.831  6402  6402 D libEGL  : eglInitialize EGLDisplay = 0xbec92dac
,08-11 09:06:05.831  4948  4948 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-11 09:06:05.831  4948  4948 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-11 09:06:05.831  4948  4948 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-11 09:06:05.831  4948  4948 I art     : System.exit called, status: 0
08-11 09:06:05.831  4948  4948 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 09:06:05.861   744  1666 I ActivityManager: Process com.samsung.aasaservice (pid 4948)(adj 0) has died(85,765)
,08-11 09:06:05.861   744  1666 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-11 09:06:05.861   744  1666 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
,08-11 09:06:05.861  4911  4911 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-11 09:06:05.861   744  1666 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,08-11 09:06:05.871  6444  6444 E Zygote  : v2
08-11 09:06:05.871  6444  6444 I libpersona: KNOX_SDCARD checking this for 10014
08-11 09:06:05.871  6444  6444 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:05.881  6444  6444 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:05.881  6444  6444 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:05.881  6444  6444 E Zygote  : accessInfo : 0
,08-11 09:06:05.881   744   798 I ActivityManager: Start proc 6444:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-11 09:06:05.881  6444  6444 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-11 09:06:05.881   744   760 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
08-11 09:06:05.881   744  1324 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 09:06:05.881   744   760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-11 09:06:05.901   744  1324 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-11 09:06:05.911  6444  6444 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:05.911  6444  6444 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:05.921   744  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ca0537 6444:com.google.android.partnersetup/u0a14}
,08-11 09:06:05.931  6444  6444 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
,08-11 09:06:05.931  6402  6402 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-11 09:06:05.941  6444  6444 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-11 09:06:05.941  6402  6402 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 09:06:05.941  6402  6402 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-11 09:06:05.941  6402  6402 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-11 09:06:05.941  6402  6402 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-11 09:06:05.961  6402  6402 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-11 09:06:05.961  6402  6402 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-11 09:06:05.971   744  2038 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ca0537 6444:com.google.android.partnersetup/u0a14}
,08-11 09:06:05.991   744  1720 I ActivityManager: Start proc 6466:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
,08-11 09:06:05.991  6466  6466 E Zygote  : v2
08-11 09:06:05.991  6466  6466 I libpersona: KNOX_SDCARD checking this for 10015
08-11 09:06:05.991  6466  6466 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:06.001  6466  6466 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 09:06:06.001  6466  6466 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:06.001  6466  6466 E Zygote  : accessInfo : 0
,08-11 09:06:06.001  6466  6466 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
,08-11 09:06:06.031  6466  6466 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:06.031  6466  6466 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:06.051   744  1295 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a7e009 6466:com.samsung.groupcast/u0a15}
,08-11 09:06:06.051  6402  6402 D SecWifiDisplayUtil: Metadata value : none
,08-11 09:06:06.051  6402  6402 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5809894 I.E...... R.....ID 0,0-0,0}
,08-11 09:06:06.061  6402  6480 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 09:06:06.061  6466  6466 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
,08-11 09:06:06.061   744   758 D ISSUE_DEBUG: InputChannelName : e573c5 com.test.thalitest/com.test.thalitest.MainActivity
,08-11 09:06:06.061   744  1720 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-11 09:06:06.061   744  1720 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-11 09:06:06.061   744   744 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 09:06:06.061   744   744 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-11 09:06:06.081  6402  6402 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6402
,08-11 09:06:06.081   744  2038 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6402 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 09:06:06.081   744  1333 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-11 09:06:06.081   744  1333 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 09:06:06.081   744  1333 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 09:06:06.081   744  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-11 09:06:06.081   744  1333 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 09:06:06.081   744  1593 I ActivityManager: Killing 5500:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-11 09:06:06.091  6402  6402 D SecWifiDisplayUtil: Metadata value : none
,08-11 09:06:06.091  6466  6466 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
,08-11 09:06:06.101   293   293 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-11 09:06:06.101   744   760 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-11 09:06:06.101  6402  6423 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-11 09:06:06.101   744  1682 D InputDispatcher: Focus entered window: 6402
,08-11 09:06:06.111  6402  6480 D libEGL  : eglInitialize EGLDisplay = 0x9ca807c4
08-11 09:06:06.111   744   868 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
08-11 09:06:06.111   744   868 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 09:06:06.111   744   868 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-11 09:06:06.111   744   868 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 09:06:06.111  6402  6480 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 09:06:06.121  6466  6466 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
,08-11 09:06:06.121  6466  6466 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,08-11 09:06:06.121  6466  6466 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-11 09:06:06.121  6466  6466 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-11 09:06:06.121  6466  6466 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 09:06:06.121  6466  6466 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 09:06:06.121  6466  6466 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:06:06.121  6466  6466 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 09:06:06.121  6466  6466 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-11 09:06:06.131   744  1721 I ActivityManager: Killing 5543:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
08-11 09:06:06.131   744  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e03496 1963:com.sec.android.app.shealth:remote/u0a34}
,08-11 09:06:06.151  6485  6485 E Zygote  : v2
08-11 09:06:06.161   744  2261 I ActivityManager: Start proc 6485:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,08-11 09:06:06.161  6485  6485 I libpersona: KNOX_SDCARD checking this for 10041
08-11 09:06:06.161  6485  6485 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:06.161  6485  6485 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:06.161  6485  6485 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:06.161  6485  6485 E Zygote  : accessInfo : 0
08-11 09:06:06.161  6485  6485 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-11 09:06:06.161   744  1666 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-11 09:06:06.171  6402  6402 V ActivityThread: updateVisibility : ActivityRecord{e4c59df token=android.os.BinderProxy@f37b4e7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-11 09:06:06.171  6402  6402 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-11 09:06:06.171  6402  6402 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-11 09:06:06.171   744  1593 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-11 09:06:06.181  6402  6402 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 09:06:06.201  6485  6485 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:06.201  6485  6485 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:06.201   744  1721 V WindowStateAnimator: Finishing drawing window Window{e573c5 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-11 09:06:06.211  6402  6402 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-11 09:06:06.211  6402  6402 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f37b4e7 time:97182
,08-11 09:06:06.211   744  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{69b567d 6485:com.samsung.android.sdk.samsunglink/u0a41}
,08-11 09:06:06.221   744   868 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 09:06:06.221   744   868 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +552ms (total +934ms)
,08-11 09:06:06.221   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe963364
,08-11 09:06:06.221   744   744 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 09:06:06.221   744   744 I KnoxTimeoutHandler: SD activityfalse
,08-11 09:06:06.221   744   868 D ActivityManager: mDVFSHelper.release()
08-11 09:06:06.221   744   868 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{70b867b u0 com.test.thalitest/.MainActivity t153} time:97196
,08-11 09:06:06.221   744   868 D ViewRootImpl: #3 mView = null
,08-11 09:06:06.221   293  1297 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
,08-11 09:06:06.231   293   337 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
,08-11 09:06:06.231  6485  6485 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
,08-11 09:06:06.241   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9633a4
,08-11 09:06:06.251  6402  6501 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 09:06:06.251  6402  6501 D libEGL  : eglInitialize EGLDisplay = 0x9b3bf3ec
,08-11 09:06:06.281  6402  6402 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6402
,08-11 09:06:06.341  6485  6485 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-11 09:06:06.341  6485  6485 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 09:06:06.411  6485  6485 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-11 09:06:06.411  6485  6485 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-11 09:06:06.421   744   758 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.421   744  1717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-11 09:06:06.421   744  2266 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.431   744  1666 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.431   744  1321 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.431  6402  6402 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 09:06:06.431   744  2039 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.431   744  1677 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.441   744  2038 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.441   744  1593 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.441   744  2261 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-11 09:06:06.541  6402  6512 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1697130192
,08-11 09:06:06.541  6402  6512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:06:06.541  6402  6512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:06:06.541  6402  6512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:06:06.541  6402  6512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:06:06.541  6402  6512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 09:06:06.541  6402  6512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61a71ad added. We now have 1 listener(s)
,08-11 09:06:06.551  6402  6512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-11 09:06:06.551  6485  6485 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-11 09:06:06.551  6402  6512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-11 09:06:06.551  6402  6512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 09:06:06.551  6485  6485 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-11 09:06:06.551  6485  6485 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-11 09:06:06.551  6485  6485 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-11 09:06:06.551  6485  6485 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-11 09:06:06.551  6485  6485 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 09:06:06.551  6485  6485 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 09:06:06.551  6485  6485 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:06:06.551  6485  6485 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 09:06:06.551  6485  6485 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-11 09:06:06.551  6402  6512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-11 09:06:06.561  6402  6512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4aa9330 added. We now have 1 listener(s)
08-11 09:06:06.561  6402  6512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 09:06:06.561   744  1295 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be0498a 1694:android.process.acore/u0a19}
,08-11 09:06:06.561  6402  6512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 09:06:06.561  6402  6512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 09:06:06.561  6402  6512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-11 09:06:06.561  6402  6512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 09:06:06.561  6402  6512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 09:06:06.571   744   760 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b794d 5080:com.sec.android.gallery3d/u0a47}
08-11 09:06:06.571  6402  6512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 09:06:06.571  6402  6512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
08-11 09:06:06.571  5080  5080 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-11 09:06:06.571  6402  6512 D BluetoothAdapter: STATE_ON
08-11 09:06:06.571  6402  6512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:06:06.571  6402  6512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:06:06.571  6402  6512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-11 09:06:06.571  6402  6512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 09:06:06.571  6402  6512 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 09:06:06.581  6402  6402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 09:06:06.581  6402  6402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 09:06:06.591  6518  6518 E Zygote  : v2
08-11 09:06:06.591  6518  6518 I libpersona: KNOX_SDCARD checking this for 10050
08-11 09:06:06.591  6518  6518 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:06.591  6518  6518 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:06.591  6518  6518 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:06.591   744  1721 I ActivityManager: Start proc 6518:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-11 09:06:06.591  6518  6518 E Zygote  : accessInfo : 0
08-11 09:06:06.591  6518  6518 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-11 09:06:06.611   744  1666 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 09:06:06.611  6402  6402 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 09:06:06.631  6518  6518 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:06.631  6518  6518 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:06.641   744  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ed1a60f 6518:com.sec.android.app.myfiles/u0a50}
,08-11 09:06:06.651  6518  6518 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-11 09:06:06.661   744  2038 I ActivityManager: Killing 5559:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
,08-11 09:06:06.671  6518  6518 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-11 09:06:06.681   744  3434 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:06.681   744  1295 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
,08-11 09:06:06.721  6518  6518 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-11 09:06:06.741   744  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{146a18 5189:com.android.settings/1000}
,08-11 09:06:06.761   329   329 E installd: system dir 0 : /system/app/
08-11 09:06:06.761   329   329 E installd: system dir 1 : /system/priv-app/
08-11 09:06:06.761   329   329 E installd: system dir 2 : /vendor/app/
08-11 09:06:06.761   329   329 E installd: system dir 3 : /oem/app/
,08-11 09:06:06.761   744   760 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{146a18 5189:com.android.settings/1000}
,08-11 09:06:06.781   744   909 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-11 09:06:06.781   744   758 I ActivityManager: Start proc 6535:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-11 09:06:06.781  6535  6535 E Zygote  : v2
,08-11 09:06:06.791  6535  6535 I libpersona: KNOX_SDCARD checking this for 10169
08-11 09:06:06.791  6535  6535 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:06.791  6535  6535 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 09:06:06.791  6535  6535 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:06.791  6535  6535 E Zygote  : accessInfo : 0
,08-11 09:06:06.791  6535  6535 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-11 09:06:06.811  6535  6535 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:06.811  6535  6535 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:06.821   744  2039 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a0c942b 6535:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-11 09:06:06.831  6535  6535 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-11 09:06:06.841  6535  6535 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-11 09:06:06.851   744  1666 I ActivityManager: Killing 4071:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,08-11 09:06:06.861   744  1666 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dfb9279 1652:com.android.phone/1001}
,08-11 09:06:06.871  6547  6547 E Zygote  : v2
,08-11 09:06:06.871  6547  6547 I libpersona: KNOX_SDCARD checking this for 10210
08-11 09:06:06.871  6547  6547 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:06.871  6547  6547 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 09:06:06.871  6547  6547 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:06.871  6547  6547 E Zygote  : accessInfo : 0
,08-11 09:06:06.871  6547  6547 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-11 09:06:06.881   744   798 I ActivityManager: Start proc 6547:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-11 09:06:06.881   744  2266 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-11 09:06:06.891   744   760 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0d94e9 1805:com.google.android.googlequicksearchbox:search/u0a61}
,08-11 09:06:06.901  6547  6547 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:06.901  6547  6547 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:06.911   744  2261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0d94e9 1805:com.google.android.googlequicksearchbox:search/u0a61}
,08-11 09:06:06.931   744  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5cba21 6320:com.samsung.android.sm.provider/1000}
,08-11 09:06:06.931  6547  6547 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-11 09:06:06.951   744  1321 I ActivityManager: Start proc 6561:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-11 09:06:06.951  6547  6547 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-11 09:06:06.951  6547  6547 D AASAservice: onCreate()
,08-11 09:06:06.951  6561  6561 E Zygote  : v2
08-11 09:06:06.951  6561  6561 I libpersona: KNOX_SDCARD checking this for 5012
08-11 09:06:06.951  6561  6561 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:06.951  6561  6561 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:06.961  6561  6561 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:06.961  6561  6561 E Zygote  : accessInfo : 0
,08-11 09:06:06.961  6561  6561 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-11 09:06:06.961   744  2261 I ActivityManager: Killing 5282:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-11 09:06:06.961  4911  4911 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-11 09:06:06.981   744  1666 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-11 09:06:06.981  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:06.981  6561  6561 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:06.991   744  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b77e46 6561:com.samsung.android.sm.devicesecurity/5012}
,08-11 09:06:06.991  1805  6559 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-11 09:06:07.001  6561  6561 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-11 09:06:07.011  6561  6561 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-11 09:06:07.061  1452  1452 D Recents : onTaskStackChanged
,08-11 09:06:07.071  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-11 09:06:07.091   744  1593 I ActivityManager: Killing 5144:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-11 09:06:07.091   744  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ca4172 3209:com.android.contacts/u0a19}
,08-11 09:06:07.111   744  1682 I ActivityManager: Start proc 6573:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-11 09:06:07.111  6573  6573 E Zygote  : v2
08-11 09:06:07.111  6573  6573 I libpersona: KNOX_SDCARD checking this for 10049
08-11 09:06:07.111  6573  6573 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:07.111  6573  6573 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:07.111  6573  6573 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:07.111  6573  6573 E Zygote  : accessInfo : 0
,08-11 09:06:07.111  6573  6573 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-11 09:06:07.141   744   755 I art     : Background partial concurrent mark sweep GC freed 149530(8MB) AllocSpace objects, 7(1856KB) LOS objects, 27% free, 42MB/58MB, paused 1.571ms total 133.554ms
,08-11 09:06:07.141  1805  6559 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-11 09:06:07.151  1805  6559 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-11 09:06:07.161  6573  6573 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:07.161  6573  6573 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:07.161   744  2261 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-11 09:06:07.171   744  1666 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1be4807 6573:com.android.mms/u0a49}
,08-11 09:06:07.201  6573  6573 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 09:06:07.231  6573  6573 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-11 09:06:07.241  6573  6573 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-11 09:06:07.251  6573  6573 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-11 09:06:07.261  6573  6573 D Mms/TelephonyPermission: start operation mode monitor
,08-11 09:06:07.261  6573  6573 D Mms/TelephonyPermission: User ID is null set current User Id
,08-11 09:06:07.271  6573  6588 D Mms/ArtClassLoader: init before art third
,08-11 09:06:07.281  6573  6586 D Mms/ArtClassLoader: init before art first
,08-11 09:06:07.281  6573  6587 D Mms/ArtClassLoader: init before art second
,08-11 09:06:07.281  1805  6559 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 290 ms] updated apps [took 290 ms] 
,08-11 09:06:07.291  6573  6573 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 09:06:07.291  6573  6573 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 09:06:07.291  6573  6588 D Mms/ArtClassLoader: init [DONE] art
,08-11 09:06:07.311  6573  6573 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-11 09:06:07.311  6573  6573 D Mms/TelephonyPermission: isDefault true
,08-11 09:06:07.311  6573  6573 D Mms/MmsApp: onCreate() com.android.mms
,08-11 09:06:07.341  6573  6573 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-11 09:06:07.361  6573  6573 D Mms/MmsApp: [start]    initCountryIso consume time = 103.524064
,08-11 09:06:07.361   744  1720 D CountryDetector: The first listener is added
,08-11 09:06:07.361  6573  6573 D Mms/MmsApp: [end]    initCountryIso consume time = 7.448801
08-11 09:06:07.361  6573  6573 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.095729
,08-11 09:06:07.371  6573  6573 D Mms/MmsConfig: before partial update
,08-11 09:06:07.411  6573  6586 D Mms/ArtClassLoader: init [DONE] art
,08-11 09:06:07.411  6573  6587 D Mms/ArtClassLoader: init [DONE] art
,08-11 09:06:07.411  6573  6573 D Mms/MmsConfig: Load Resize quality : 80
,08-11 09:06:07.411  6573  6573 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 09:06:07.411  6573  6573 D EasySignUpManager_1.0.5: isAuth is false
08-11 09:06:07.411  6573  6573 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-11 09:06:07.421  6573  6573 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-11 09:06:07.421  6573  6573 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-11 09:06:07.421  6573  6573 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 09:06:07.421  6573  6573 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-11 09:06:07.421  6573  6573 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 09:06:07.421  6573  6573 D EasySignUpManager_1.0.5: isAuth is false
08-11 09:06:07.421  6573  6573 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-11 09:06:07.421  6573  6573 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-11 09:06:07.431  1652  1902 D TP/MmsSmsProvider: query, match:2117, calling pid = 6573, accessRestricted = false
,08-11 09:06:07.431  1652  1902 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.934 ms
,08-11 09:06:07.431  6573  6573 E CscParser: mps_code.dat does not exist
08-11 09:06:07.431  6573  6573 E CscParser: customer_path =/system/csc/customer.xml
08-11 09:06:07.431  6573  6573 E CscParser: fileName + /system/csc/customer.xml
,08-11 09:06:07.441  6573  6573 E CscParser: mps_code.dat does not exist
08-11 09:06:07.441  6573  6573 E CscParser: customer_path =/system/csc/customer.xml
08-11 09:06:07.441  6573  6573 E CscParser: fileName + /system/csc/customer.xml
,08-11 09:06:07.451  6573  6573 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-11 09:06:07.451  6573  6573 D Mms/MmsConfig:  enable multiwindow = true
,08-11 09:06:07.461  6573  6573 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-11 09:06:07.461  6573  6573 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-11 09:06:07.461  6573  6573 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-11 09:06:07.461  6573  6573 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-11 09:06:07.461  6573  6573 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-11 09:06:07.461  6573  6573 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-11 09:06:07.461  6573  6573 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-11 09:06:07.461  6573  6573 D Mms/MmsConfig: [end]    init() consume time = 100.994113
,08-11 09:06:07.471  6573  6573 D Mms/Contact: [start]    init() consume time = 4.967656
,08-11 09:06:07.481  6402  6523 W jxcore-log: Initializing JXcore engine
08-11 09:06:07.481  6402  6523 W jxcore-log: JXcore engine is ready
,08-11 09:06:07.481  1652  2662 D TP/MmsSmsProvider: query, match:13, calling pid = 6573, accessRestricted = false
,08-11 09:06:07.491  1652  2662 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.410 ms
,08-11 09:06:07.491  6573  6573 D Mms/Contact: [end]    init consume time = 22.880104
,08-11 09:06:07.501  6573  6573 D Mms:transaction: roaming -> false (slotId = 0)
08-11 09:06:07.501  6573  6573 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-11 09:06:07.501  6573  6573 D Mms:transaction: auto download without roaming -> true
08-11 09:06:07.501  6573  6573 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-11 09:06:07.501  6573  6573 D Mms:transaction: roaming -> false (slotId = 1)
08-11 09:06:07.501  6573  6573 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-11 09:06:07.501  6573  6573 D Mms:transaction: auto download without roaming -> true
08-11 09:06:07.501  6573  6573 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-11 09:06:07.501  6573  6573 D Mms:transaction: auto download during roaming secondary -> false
08-11 09:06:07.501  6573  6573 D Mms:transaction: mAutoDownload ------> true
,08-11 09:06:07.501  6573  6596 D Mms/DraftCache: [start]    rebuildCache consume time = 11.73547
,08-11 09:06:07.511  1652  1668 D TP/MmsSmsProvider: query, match:12, calling pid = 6573, accessRestricted = false
,08-11 09:06:07.511  1652  1668 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.277 ms
,08-11 09:06:07.521  6573  6596 D Mms/DraftCache: [end]    rebuildCache consume time = 13.860209
,08-11 09:06:07.521  2176  2176 E audit   : type=1400 msg=audit(1470899167.521:288): avc:  denied  { ioctl } for  pid=6523 comm="Thread-879" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 09:06:07.521  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:07.521  2176  2176 E audit   : type=1300 msg=audit(1470899167.521:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a67f3c8 items=0 ppid=353 ppcomm=main pid=6523 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-879" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-11 09:06:07.521  2176  2176 E audit   : type=1327 msg=audit(1470899167.521:288): proctitle="com.test.thalitest"
08-11 09:06:07.521  2176  2176 E audit   : type=1320 msg=audit(1470899167.521:288): 
,08-11 09:06:07.521  2176  2176 E audit   : type=1400 msg=audit(1470899167.521:289): avc:  denied  { ioctl } for  pid=6523 comm="Thread-879" path="socket:[39156]" dev="sockfs" ino=39156 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 09:06:07.521  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:07.521  2176  2176 E audit   : type=1300 msg=audit(1470899167.521:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a67f3c8 items=0 ppid=353 ppcomm=main pid=6523 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-879" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-11 09:06:07.521  2176  2176 E audit   : type=1327 msg=audit(1470899167.521:289): proctitle="com.test.thalitest"
08-11 09:06:07.521  2176  2176 E audit   : type=1320 msg=audit(1470899167.521:289): 
,08-11 09:06:07.531  6573  6573 D ComposerPerformance: 1470899167539 ms / [DONE] Composer constructor
,08-11 09:06:07.531  6573  6573 D CII     : Log Level [5]
08-11 09:06:07.531  6573  6573 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-11 09:06:07.531  6402  6523 W jxcore-log: Starting JXcore engine
,08-11 09:06:07.531  6573  6597 D Mms/Conversation: [start]    init() consume time = 13.367135
08-11 09:06:07.531  6573  6573 I Mms/ReservationManager: ReservationManager()
,08-11 09:06:07.531  6573  6573 I Mms/ReservationManager: resetAfterConnected()
08-11 09:06:07.531  1652  1665 D TP/MmsSmsProvider: delete, match:1, calling pid = 6573
08-11 09:06:07.531  1652  1665 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-11 09:06:07.531  1652  1665 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-11 09:06:07.541  1652  1665 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-11 09:06:07.541  1652  1665 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-11 09:06:07.541  1652  1665 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-11 09:06:07.541  1652  1665 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-11 09:06:07.541  1652  2662 D TP/MmsSmsProvider: query, match:7, calling pid = 6573, accessRestricted = false
,08-11 09:06:07.541  1652  2662 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.898 ms
,08-11 09:06:07.551  6573  6573 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-11 09:06:07.551  1652  1665 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-11 09:06:07.551  1652  1665 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-11 09:06:07.551  1652  1665 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-11 09:06:07.551  1652  1665 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 7.751 ms
08-11 09:06:07.551  1652  1665 D TP/MmsSmsProvider: need read changed broadcast:false
,08-11 09:06:07.551  6573  6597 D Mms/Conversation: [end]    init consume time = 18.88099
,08-11 09:06:07.551  6573  6597 D Mms/MessagingNotification: [start]    init() consume time = 1.947968
,08-11 09:06:07.551  6573  6597 D Mms/MessagingNotification: [end]    init consume time = 1.11125
,08-11 09:06:07.551  6573  6598 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.980677
,08-11 09:06:07.561  1652  1668 D TP/MmsSmsProvider: query, match:400, calling pid = 6573, accessRestricted = false
,08-11 09:06:07.561  6573  6599 D Mms/Synchronizer: [start]    doSync consume time = 7.320938
,08-11 09:06:07.561  6573  6598 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 2.553958
,08-11 09:06:07.571  1652  1665 D TP/MmsSmsProvider: update, match:300, calling pid = 6573
08-11 09:06:07.571  1652  1665 V TP/MmsSmsProvider: syncDBData start
,08-11 09:06:07.571  1652  1665 V TP/MmsSmsProvider: syncDBData sms end
,08-11 09:06:07.571  1652  1665 V TP/MmsSmsProvider: syncDBData mms end
,08-11 09:06:07.571  6573  6573 D Mms/MmsApp: [end]    onCreate() consume time = 4.855157
08-11 09:06:07.571  1652  1665 V TP/MmsSmsProvider: syncDBData end
,08-11 09:06:07.571  1652  1665 D TP/MmsSmsProvider: update, match 300:Elapsed time : 3.219 ms
,08-11 09:06:07.571  6573  6573 D Mms/MmsApp: [end]    onCreate() consume time = 0.078489
08-11 09:06:07.571  6573  6599 D Mms/Synchronizer: [end]    doSync consume time = 0.931146
08-11 09:06:07.571  1652  2662 D TP/MmsSmsProvider: query, match:0, calling pid = 6573, accessRestricted = false
08-11 09:06:07.571  1652  2662 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-11 09:06:07.571  1652  2662 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.870 ms
,08-11 09:06:07.581  6198  6208 D BadgeProvider: query, [selection] : package=?
,08-11 09:06:07.591  6573  6597 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-11 09:06:07.591  6573  6573 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-11 09:06:07.591  6573  6573 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-11 09:06:07.591  6573  6573 D Mms:transaction: roaming -> false (slotId = 0)
08-11 09:06:07.591  6573  6573 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-11 09:06:07.591  6573  6573 D Mms:transaction: auto download without roaming -> true
08-11 09:06:07.591  6573  6573 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-11 09:06:07.591  6573  6573 D Mms:transaction: mAutoDownload ------> true
,08-11 09:06:07.601  1652  1668 D TP/SmsProvider: query,matched:26, calling pid = 6573
,08-11 09:06:07.601  1652  1668 D TP/SmsProvider: query, match 26:Elapsed time : 0.900 ms
,08-11 09:06:07.601  6600  6600 E Zygote  : v2
08-11 09:06:07.601  6600  6600 I libpersona: KNOX_SDCARD checking this for 1000
08-11 09:06:07.601  6600  6600 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:07.601  6600  6600 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:07.601  6600  6600 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:07.601  6600  6600 E Zygote  : accessInfo : 0
,08-11 09:06:07.611   744  1593 I ActivityManager: Start proc 6600:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-11 09:06:07.621  6402  6523 W jxcore-log: Platform android
08-11 09:06:07.621  6402  6523 W jxcore-log: 
08-11 09:06:07.621  6402  6523 W jxcore-log: Process ARCH arm
08-11 09:06:07.621  6402  6523 W jxcore-log: 
,08-11 09:06:07.631  1652  1665 D TP/MmsSmsProvider: query, match:6, calling pid = 6573, accessRestricted = false
,08-11 09:06:07.631  1652  1665 D TP/MmsSmsProvider: query, match 6:Elapsed time : 2.517 ms
,08-11 09:06:07.651  6600  6600 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:07.651  6600  6600 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:07.661   744  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c0f593 6600:com.samsung.android.bbc.bbcagent/1000}
,08-11 09:06:07.671  6600  6600 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-11 09:06:07.671  6612  6612 E Zygote  : v2
08-11 09:06:07.671  6612  6612 I libpersona: KNOX_SDCARD checking this for 10024
08-11 09:06:07.671  6612  6612 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:07.671  6612  6612 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:07.671  6612  6612 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:07.671  6612  6612 E Zygote  : accessInfo : 0
,08-11 09:06:07.671  6612  6612 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-11 09:06:07.671   744  1321 I ActivityManager: Start proc 6612:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-11 09:06:07.691  6612  6612 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:07.691  6612  6612 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:07.701   744  1677 I ActivityManager: Killing 5307:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-11 09:06:07.711  6600  6600 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-11 09:06:07.711  6612  6612 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-11 09:06:07.721   744  2038 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-11 09:06:07.741  6612  6612 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-11 09:06:07.781   744   760 I ActivityManager: Start proc 6625:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-11 09:06:07.781  6625  6625 E Zygote  : v2
08-11 09:06:07.781  6625  6625 I libpersona: KNOX_SDCARD checking this for 10097
08-11 09:06:07.781  6625  6625 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:07.781  6625  6625 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:07.781  6625  6625 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:07.781  6625  6625 E Zygote  : accessInfo : 0
,08-11 09:06:07.781  6625  6625 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-11 09:06:07.781   744   760 I ActivityManager: Killing 5627:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-11 09:06:07.811   744  1717 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-11 09:06:07.811  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:07.811  6625  6625 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:07.821  6402  6523 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:06:07.821  6402  6523 I jxcore-log: 
,08-11 09:06:07.821  6402  6523 W jxcore-log: JXcore engine is started
,08-11 09:06:07.821  6402  6512 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 09:06:07.831  6402  6402 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 09:06:07.831  6612  6612 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-11 09:06:07.841   744  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fad89d0 6625:com.google.android.apps.docs/u0a97}
,08-11 09:06:07.841  6573  6597 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-11 09:06:07.851  6625  6625 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 09:06:07.851  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-11 09:06:07.851  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-11 09:06:07.861  6625  6625 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-11 09:06:07.861  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-11 09:06:07.871  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-11 09:06:07.871  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-11 09:06:07.871  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-11 09:06:07.871  6612  6612 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-11 09:06:08.131  6625  6639 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-11 09:06:08.131  6625  6639 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 09:06:08.131  6625  6639 I GAv4    :   adb logcat -s GAv4
,08-11 09:06:08.141  6625  6639 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 09:06:08.141   744  1677 V AlarmManager:  remove PendingIntent] PendingIntent{32972fc: PendingIntentRecord{496ed85 com.google.android.apps.docs broadcastIntent}}
08-11 09:06:08.141  6625  6639 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 09:06:08.151  6625  6639 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 09:06:08.151  6625  6644 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 09:06:08.231   744  6298 I HarmonyEASService: Updating for all 1
,08-11 09:06:08.251  6625  6625 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-11 09:06:08.251  6625  6625 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-11 09:06:08.271  6625  6639 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-11 09:06:08.271  6625  6639 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-11 09:06:08.271  6625  6639 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-11 09:06:08.271  6625  6639 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-11 09:06:08.281  2813  4943 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-11 09:06:08.311  6351  6351 D CAR.SERVICE: onUnbind
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: CSB onClientsDisconnected
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: tearDown
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: tearDownCarState
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: Skip, car not connected.
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: tearDownClientState
,08-11 09:06:08.311  6351  6351 D CAR.SERVICE: requestStop
,08-11 09:06:08.311  6351  6351 D CAR.SERVICE: onDestroy
,08-11 09:06:08.311  6351  6351 D CAR.SERVICE: tearDown
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: tearDownCarState
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: Skip, car not connected.
,08-11 09:06:08.311  6351  6351 D CAR.SERVICE: tearDownClientState
08-11 09:06:08.311  6351  6351 D CAR.SERVICE: requestStop
,08-11 09:06:08.321  2813  4943 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-11 09:06:08.331   744  1368 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/153_task.xml.bak
,08-11 09:06:08.331  6351  6351 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@108fb3 that was originally bound here
08-11 09:06:08.331  6351  6351 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@108fb3 that was originally bound here
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 09:06:08.331  6351  6351 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-11 09:06:08.331   744  1666 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@a7fd7da
,08-11 09:06:08.341   744  1682 I ActivityManager: Start proc 6651:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-11 09:06:08.341   744  1682 I ActivityManager: Killing 5512:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-11 09:06:08.351  6651  6651 E Zygote  : v2
08-11 09:06:08.351  6651  6651 I libpersona: KNOX_SDCARD checking this for 10098
08-11 09:06:08.351  6651  6651 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:08.351  6651  6651 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:08.351  6651  6651 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:08.351  6651  6651 E Zygote  : accessInfo : 0
,08-11 09:06:08.351  6651  6651 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-11 09:06:08.371   744   758 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-11 09:06:08.371  6651  6651 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:08.371  6651  6651 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:08.391   744  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1397a6 6651:com.sec.android.automotive.drivelink/u0a98}
,08-11 09:06:08.401  6651  6651 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-11 09:06:08.411  6651  6651 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-11 09:06:08.421  2813  4943 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-11 09:06:08.431  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 09:06:08.461  6651  6651 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-11 09:06:08.471   744  1666 V AlarmManager:  remove PendingIntent] PendingIntent{982b39: PendingIntentRecord{50bf57e com.sec.android.automotive.drivelink broadcastIntent}}
,08-11 09:06:08.471  6651  6667 I GMPM    : App measurement is starting up
,08-11 09:06:08.471  6651  6651 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-11 09:06:08.481  6625  6640 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 09:06:08.481  6651  6667 E GMPM    : getGoogleAppId failed with status: 10
,08-11 09:06:08.481  6651  6667 E GMPM    : Uploading is not possible. App measurement disabled
,08-11 09:06:08.481   744   760 V AlarmManager:  remove PendingIntent] PendingIntent{8581adf: PendingIntentRecord{50bf57e com.sec.android.automotive.drivelink broadcastIntent}}
,08-11 09:06:08.511  6625  6640 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-11 09:06:08.511  6651  6651 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-11 09:06:08.521  6651  6651 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-11 09:06:08.541  6625  6640 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-11 09:06:08.541  6625  6640 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-11 09:06:08.541  6625  6640 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-11 09:06:08.561  6673  6673 E Zygote  : v2
08-11 09:06:08.561  6673  6673 I libpersona: KNOX_SDCARD checking this for 10032
08-11 09:06:08.561  6673  6673 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:08.561  6673  6673 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:08.561  6673  6673 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:08.561   744  2039 I ActivityManager: Start proc 6673:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-11 09:06:08.561   744  1324 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 09:06:08.571  6673  6673 E Zygote  : accessInfo : 0
08-11 09:06:08.571  6673  6673 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-11 09:06:08.591  6673  6673 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:08.591  6673  6673 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:08.591  6625  6640 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 09:06:08.601   744  1324 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-11 09:06:08.601  6673  6673 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-11 09:06:08.611  6673  6673 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-11 09:06:08.691  6651  6651 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-11 09:06:08.691  6651  6651 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-11 09:06:08.691  6651  6651 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-11 09:06:08.711  6651  6651 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDThu Aug 11 09:06:08 GMT+02:00 2016
,08-11 09:06:08.721  6651  6651 D DialogFlow: initQueue()
,08-11 09:06:08.721   744  1717 I ActivityManager: Start proc 6687:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-11 09:06:08.731  6687  6687 E Zygote  : v2
08-11 09:06:08.731  6687  6687 I libpersona: KNOX_SDCARD checking this for 1000
08-11 09:06:08.731   744  1717 I ActivityManager: Killing 5682:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
08-11 09:06:08.731  6687  6687 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:08.731   744  1717 I ActivityManager: Killing 5252:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
08-11 09:06:08.731  6687  6687 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:08.731  6687  6687 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:08.731  6687  6687 E Zygote  : accessInfo : 0
,08-11 09:06:08.731  6673  6673 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-11 09:06:08.751   744  2039 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-11 09:06:08.761  6687  6687 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:08.761  6687  6687 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:08.761   744  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e473656 6687:com.samsung.android.app.filterinstaller/1000}
,08-11 09:06:08.771  6673  6673 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-11 09:06:08.771  6687  6687 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-11 09:06:08.781   744  2261 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-11 09:06:08.791   744  3432 D SSRM:n  : SIOP:: AP = 480, PST = 441, CUR = 450, LCD = 0
,08-11 09:06:08.791  6687  6687 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-11 09:06:08.801  6687  6687 E FilterPackageIntentReceiver: This package is not a effect filter
,08-11 09:06:08.811  6703  6703 E Zygote  : v2
,08-11 09:06:08.811  6703  6703 I libpersona: KNOX_SDCARD checking this for 1000
08-11 09:06:08.811   744  1717 I ActivityManager: Start proc 6703:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-11 09:06:08.811  6703  6703 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:08.811  6703  6703 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 09:06:08.811  6703  6703 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:08.811   744  1717 I ActivityManager: Killing 4782:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-11 09:06:08.811  6703  6703 E Zygote  : accessInfo : 0
,08-11 09:06:08.831   744  2039 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-11 09:06:08.831  6703  6703 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:08.831  6703  6703 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:08.841   744   760 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-11 09:06:08.851   744  2261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7d54a9 6703:com.samsung.helphub/1000}
,08-11 09:06:08.851  6703  6703 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-11 09:06:08.861  6673  6673 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-11 09:06:08.861  6673  6673 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-11 09:06:08.871  6703  6703 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-11 09:06:08.871  6673  6673 D DialogFlow: initQueue()
,08-11 09:06:08.911   744  1295 I ActivityManager: Start proc 6715:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-11 09:06:08.911  6715  6715 E Zygote  : v2
,08-11 09:06:08.911  6715  6715 I libpersona: KNOX_SDCARD checking this for 1000
08-11 09:06:08.911  6715  6715 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:08.911   744  1295 I ActivityManager: Killing 5706:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-11 09:06:08.911  6715  6715 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:08.911  6715  6715 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:08.911  6715  6715 E Zygote  : accessInfo : 0
,08-11 09:06:08.931   744   758 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-11 09:06:08.931  6715  6715 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:08.931  6715  6715 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:08.941   744  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{edeba2e 6715:com.samsung.android.app.mirrorlink/1000}
,08-11 09:06:08.951  6715  6715 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-11 09:06:08.961  6715  6715 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-11 09:06:08.991  6715  6715 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-11 09:06:08.991  6715  6715 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-11 09:06:08.991   744  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{648f3f 5744:com.google.android.apps.plus/u0a134}
,08-11 09:06:09.011   744  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{648f3f 5744:com.google.android.apps.plus/u0a134}
,08-11 09:06:09.021   744   760 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{648f3f 5744:com.google.android.apps.plus/u0a134}
,08-11 09:06:09.041   744  2266 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-11 09:06:09.051   744  1721 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-11 09:06:09.051   744  1295 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-11 09:06:09.051   744   758 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-11 09:06:09.051   744   760 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-11 09:06:09.061   744  1720 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-11 09:06:09.061   744  1717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-11 09:06:09.061   744  1677 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-11 09:06:09.091   744  1717 I ActivityManager: Start proc 6729:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-11 09:06:09.091  6729  6729 E Zygote  : v2
,08-11 09:06:09.091  6729  6729 I libpersona: KNOX_SDCARD checking this for 10165
08-11 09:06:09.091  6729  6729 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:09.091  6729  6729 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 09:06:09.091  6729  6729 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:09.091  6729  6729 E Zygote  : accessInfo : 0
,08-11 09:06:09.091  6729  6729 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
08-11 09:06:09.091   744  1666 I ActivityManager: Killing 5728:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-11 09:06:09.111   744  2038 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-11 09:06:09.111  6729  6729 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:09.111  6729  6729 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:09.121   744  2266 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ad9265 6729:com.sec.kidsplat.installer/u0a165}
,08-11 09:06:09.131  6729  6729 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-11 09:06:09.141  6729  6729 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-11 09:06:09.141   744  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ad9265 6729:com.sec.kidsplat.installer/u0a165}
,08-11 09:06:09.151  6729  6729 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-11 09:06:09.161   744  2261 I ActivityManager: Start proc 6741:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-11 09:06:09.161  6741  6741 E Zygote  : v2
08-11 09:06:09.161  6741  6741 I libpersona: KNOX_SDCARD checking this for 10142
08-11 09:06:09.161  6741  6741 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:09.161  6741  6741 E Zygote  : isSdpEnabledProcess - SDP enabled
08-11 09:06:09.161  6741  6741 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:09.161  6741  6741 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:09.161   744  2261 I ActivityManager: Killing 5825:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
08-11 09:06:09.161  6741  6741 E Zygote  : accessInfo : 64
08-11 09:06:09.161  6741  6741 E Zygote  : isSdpEnabledProcess - SDP enabled
08-11 09:06:09.161  6741  6741 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-11 09:06:09.161  6741  6741 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-11 09:06:09.181   744  1721 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-11 09:06:09.181  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:09.181  6741  6741 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:09.191   744  1666 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a04b3a 6741:com.sec.android.app.sbrowser/u0a142}
,08-11 09:06:09.201  6741  6741 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-11 09:06:09.231  6741  6741 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-11 09:06:09.251  6741  6741 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-11 09:06:09.251  6741  6741 D ManifestProvider: onCreate()
,08-11 09:06:09.261  6741  6741 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-11 09:06:09.261  6741  6741 I SBrowserUtils: getSystemProperty of country_code : Poland
08-11 09:06:09.261  6741  6741 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-11 09:06:09.261  6741  6741 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-11 09:06:09.271  6741  6741 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-11 09:06:09.271  6741  6741 D [MM]MHDataBaseProvider: onCreate()
,08-11 09:06:09.281  6741  6741 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@1382ca3)
,08-11 09:06:09.331   744  1321 I ActivityManager: Killing 5407:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-11 09:06:09.331   744  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8102d6f 1934:com.google.android.gms.persistent/u0a11}
,08-11 09:06:09.351   744  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53312a4 2813:com.google.android.gms/u0a11}
,08-11 09:06:09.351  2813  6757 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 09:06:09.361   744  1295 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-11 09:06:09.361  2813  6756 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-11 09:06:09.371  2813  6757 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 09:06:09.381  2813  2813 D AsyncTaskServiceImpl: Submit a task: nzm
,08-11 09:06:09.381  2813  6757 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 09:06:09.381  2813  6757 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 09:06:09.391   744  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8102d6f 1934:com.google.android.gms.persistent/u0a11}
,08-11 09:06:09.401   744  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53312a4 2813:com.google.android.gms/u0a11}
,08-11 09:06:09.411  2813  5073 D nzm     : Processing package: com.test.thalitest
,08-11 09:06:09.411  2813  2813 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 09:06:09.441  2813  5073 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-11 09:06:09.441  2813  5073 D nzm     : Found info for package com.test.thalitest in db.
,08-11 09:06:09.511   744  1720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11d3a1e 5771:com.android.vending/u0a29}
,08-11 09:06:09.551  5771  5771 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-11 09:06:09.551   744  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c7e909 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6e3974 6239:com.sec.android.app.samsungapps/u0a39}
,08-11 09:06:09.571  1934  1934 D WearableService: callingUid 10011, callindPid: 1934
,08-11 09:06:09.571  5771  5771 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-11 09:06:09.581  5771  5771 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 09:06:09.581  5771  5771 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-11 09:06:09.591   744   744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3872078 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8102d6f 1934:com.google.android.gms.persistent/u0a11}
,08-11 09:06:09.611  6573  6573 I Mms/MmsApp:  start initViewCache mms
,08-11 09:06:09.611   744  1721 V AlarmManager:  remove PendingIntent] PendingIntent{13d9351: PendingIntentRecord{3cbb87c com.google.android.gms broadcastIntent}}
,08-11 09:06:09.621   744  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e49cc24 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11d3a1e 5771:com.android.vending/u0a29}
,08-11 09:06:09.651   744   744 I BackgroundCompactionService: onStart. jobID=801
,08-11 09:06:09.651  5771  6763 I Finsky  : [829] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-11 09:06:09.651   744   744 I BackgroundCompactionService: onStart done. jobID=801
08-11 09:06:09.651   744  6764 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-11 09:06:09.651   744  6764 I BackgroundCompactionService: compact_memory command done
,08-11 09:06:09.661   744  1321 I ActivityManager: Start proc 6766:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-11 09:06:09.661  6766  6766 E Zygote  : v2
08-11 09:06:09.661  6766  6766 I libpersona: KNOX_SDCARD checking this for 10034
08-11 09:06:09.661  6766  6766 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:09.661  6766  6766 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:09.661  6766  6766 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:09.661  6766  6766 E Zygote  : accessInfo : 0
,08-11 09:06:09.661  6766  6766 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-11 09:06:09.701  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:09.701  6766  6766 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:09.701  5771  5800 I PlayCommon: [797] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-11 09:06:09.711   744  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{736e78e u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c20baf 6766:com.sec.android.app.shealth/u0a34}
,08-11 09:06:09.731  6766  6766 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-11 09:06:09.761  5771  6777 I PlayCommon: [830] com.google.android.play.a.w.a(27553): Starting to flush logs
,08-11 09:06:09.761  5771  6777 I PlayCommon: [830] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-11 09:06:09.781  6766  6766 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-11 09:06:09.791  6766  6766 I MultiDex: VM with version 2.1.0 has multidex support
08-11 09:06:09.791  6766  6766 I MultiDex: install
08-11 09:06:09.791  6766  6766 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-11 09:06:09.791  6766  6766 I MultiDex: install
08-11 09:06:09.791  6766  6766 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 09:06:09.801  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 09:06:09.831  5771  5800 I PlayCommon: [797] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-11 09:06:09.841   744  3460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 09:06:09.841  6673  6701 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 09:06:09.841  6673  6701 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 09:06:09.851  5771  5800 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-11 09:06:09.851  5771  5800 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-11 09:06:09.861   309  1174 D EnterpriseController: netId is 0
08-11 09:06:09.861   309  1174 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-11 09:06:09.901  6673  6701 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 09:06:09.901  6673  6701 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-11 09:06:09.901  6673  6701 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-11 09:06:09.911  6673  6701 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 09:06:09.911  6673  6701 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 09:06:09.931   744   755 I art     : Background partial concurrent mark sweep GC freed 27234(1743KB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 41MB/57MB, paused 3.230ms total 149.459ms
,08-11 09:06:10.021  6766  6766 D HealthDataStore: Service for HealthDataStore is connected
,08-11 09:06:10.031   744  2261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{736e78e u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e03496 1963:com.sec.android.app.shealth:remote/u0a34}
,08-11 09:06:10.051   744  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{736e78e u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e03496 1963:com.sec.android.app.shealth:remote/u0a34}
,08-11 09:06:10.051  6766  6766 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-11 09:06:10.061  6766  6766 D HealthConsole: Service for HealthDataConsole is connected
,08-11 09:06:10.061   744  1682 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e933e9f u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8102d6f 1934:com.google.android.gms.persistent/u0a11}
,08-11 09:06:10.111  6766  6766 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-11 09:06:10.121  6766  6766 E HealthDataStore: disconnectService: Context instance is invalid
,08-11 09:06:10.121  6673  6682 W art     : Suspending all threads took: 9.609ms
,08-11 09:06:10.191  6573  6573 D Mms/BubbleViewCache: fillCache bubble = 4
,08-11 09:06:10.331  5771  5800 I PlayCommon: [797] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-11 09:06:10.331  5771  5800 I PlayCommon: [797] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-11 09:06:10.331  5771  5800 I PlayCommon: [797] com.google.android.play.a.al.e(732): No file ready to send
,08-11 09:06:10.351   744   760 I ActivityManager: Killing 5999:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-11 09:06:10.361   744  2266 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-11 09:06:10.561  2813  4933 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-11 09:06:10.621  2813  4933 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 09:06:10.621  2813  4933 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 09:06:10.631  2813  4933 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-11 09:06:11.721   744  3432 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 09:06:14.841   744  3460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 09:06:15.321   744   909 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-11 09:06:15.361   744   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-11 09:06:16.441  3673  3673 D FactoryTest: User mode
,08-11 09:06:16.451  3673  3673 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-11 09:06:16.451  3673  3673 D MTPRx   : still no open session command from host, so toast
,08-11 09:06:16.451   744  1677 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-11 09:06:16.461   744  1677 D ActivityManager: mDVFSHelper.acquire()
,08-11 09:06:16.461   744  1677 V WindowManager: addAppToken: AppWindowToken{7430e31 token=Token{75c3ad8 ActivityRecord{3f725bb u0 com.samsung.android.MtpApplication/.USBConnection t154}}} to stack=1 task=154 at 0
,08-11 09:06:16.461   744  1677 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-11 09:06:16.471   744  1677 I ActivityManager: Killing 4911:com.policydm/1000 (adj 15): DHA:empty #37
,08-11 09:06:16.481   744   798 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-11 09:06:16.501   744  1677 D InputDispatcher: Focused application set to: xxxx
,08-11 09:06:16.501   744  1677 D InputDispatcher: Focus left window: 6402
,08-11 09:06:16.501   744   868 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
,08-11 09:06:16.501   744   868 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-11 09:06:16.501   744   868 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-11 09:06:16.501   744   868 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 09:06:16.511  3673  3673 E MTPRx   : started activity for popup
,08-11 09:06:16.511  3673  3673 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-11 09:06:16.521  3673  3673 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-11 09:06:16.531   744  3432 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 09:06:16.541  6547  6547 D AASAservice: onDestroy()
,08-11 09:06:16.541  6547  6547 I art     : System.exit called, status: 80
08-11 09:06:16.541  6547  6547 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-11 09:06:16.541   744  1717 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-11 09:06:16.541  3673  3673 D MTPUSBConnection: onCreate in USBConnection
08-11 09:06:16.541  3673  3673 V MTPUSBConnection: Registering broadcast receiver.
,08-11 09:06:16.551  3673  3673 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-11 09:06:16.551   744  2261 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-11 09:06:16.551   744  1593 I ActivityManager: Process com.samsung.aasaservice (pid 6547)(adj 0) has died(82,749)
,08-11 09:06:16.551   744  1593 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-11 09:06:16.581   353   353 I Zygote  : Process 6547 exited cleanly (80)
,08-11 09:06:16.591  3673  3673 D TAG     : dev.kiessupport is : TRUE
,08-11 09:06:16.621  3673  3673 D SecWifiDisplayUtil: Metadata value : none
,08-11 09:06:16.621  3673  3673 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{dfc8197 V.E...... R.....I. 0,0-0,0}
,08-11 09:06:16.621  3673  6808 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 09:06:16.621   744  2261 D ISSUE_DEBUG: InputChannelName : 67144ee com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-11 09:06:16.631   744  2261 D InputDispatcher: Focus entered window: 3673
,08-11 09:06:16.631   744   800 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{67144ee u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-11 09:06:16.631  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-11 09:06:16.631   744   868 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:744 uid:1000
08-11 09:06:16.631   744   868 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 09:06:16.631   744   868 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:744 uid:1000
08-11 09:06:16.631   744   868 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 09:06:16.641  3673  3673 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7e80c8f I.E...... R.....I. 0,0-0,0}
,08-11 09:06:16.641   744  1682 D ISSUE_DEBUG: InputChannelName : 664881c com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-11 09:06:16.641   744  1721 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-11 09:06:16.641   744  1721 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 09:06:16.641   744   744 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 09:06:16.641   744   744 I KnoxTimeoutHandler: Shared devices show user statefalse
08-11 09:06:16.641   744   744 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-11 09:06:16.671   293   293 I SurfaceFlinger: id=18 createSurf (145x145),1 flag=4, VSBConnecti
,08-11 09:06:16.681  3673  6808 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-11 09:06:16.681  3673  6808 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-11 09:06:16.681  3673  6808 I Adreno-EGL: Build Date: 01/28/16 Thu
08-11 09:06:16.681  3673  6808 I Adreno-EGL: Local Branch: ss
08-11 09:06:16.681  3673  6808 I Adreno-EGL: Remote Branch: 
08-11 09:06:16.681  3673  6808 I Adreno-EGL: Local Patches: 
08-11 09:06:16.681  3673  6808 I Adreno-EGL: Reconstruct Branch: 
,08-11 09:06:16.691  3673  6808 D libEGL  : eglInitialize EGLDisplay = 0x9f0b77c4
08-11 09:06:16.691  3673  6808 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 09:06:16.721   293   293 I SurfaceFlinger: id=19 createSurf (193x193),1 flag=4, VSBConnecti
,08-11 09:06:16.741  3673  3673 V ActivityThread: updateVisibility : ActivityRecord{9210cfa token=android.os.BinderProxy@5c95f84 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-11 09:06:16.741  3673  3673 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 09:06:16.821   744   909 D PackageManager: [MSG] MCS_UNBIND
,08-11 09:06:16.851   744  2039 V WindowStateAnimator: Finishing drawing window Window{67144ee u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-11 09:06:16.851  3673  3673 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 09:06:16.851   744  1321 V WindowStateAnimator: Finishing drawing window Window{664881c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-11 09:06:16.851  3673  3673 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-11 09:06:16.851  3673  3673 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-11 09:06:16.861   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe963364
,08-11 09:06:16.861   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe963364
,08-11 09:06:16.861   744   868 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 09:06:16.861   744   744 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 09:06:16.861   744   868 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +368ms (total +398ms)
08-11 09:06:16.861   744   744 I KnoxTimeoutHandler: SD activityfalse
,08-11 09:06:16.861   744   868 D ActivityManager: mDVFSHelper.release()
08-11 09:06:16.861   744   868 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f725bb u0 com.samsung.android.MtpApplication/.USBConnection t154} time:107838
,08-11 09:06:16.861   744  1666 V WindowStateAnimator: Finishing drawing window Window{67144ee u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-11 09:06:16.871   744  2266 V WindowStateAnimator: Finishing drawing window Window{664881c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-11 09:06:16.871  3673  3673 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5c95f84 time:107840
,08-11 09:06:16.871   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe963364
,08-11 09:06:17.511   744  3434 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-11 09:06:17.641  1452  1452 D Recents : onTaskStackChanged
,08-11 09:06:17.651  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-11 09:06:18.411  6402  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:06:18.411  6402  6523 I jxcore-log: 
,08-11 09:06:18.411  6402  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:06:18.411  6402  6523 I jxcore-log: 
,08-11 09:06:18.421  6402  6523 D BluetoothAdapter: STATE_ON
,08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:06:18.421  6402  6523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 09:06:18.431  6402  6523 D BluetoothAdapter: STATE_ON
,08-11 09:06:18.431  6402  6523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 09:06:18.431  6402  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:06:18.431  6402  6523 I jxcore-log: 
,08-11 09:06:18.431  6402  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:06:18.431  6402  6523 I jxcore-log: 
,08-11 09:06:18.651   744  1237 V AlarmManager: Expired Alarm result :4
,08-11 09:06:18.681   744  2039 V AlarmManager:  remove PendingIntent] PendingIntent{6b0c1fa: PendingIntentRecord{78e6d89 com.google.android.gms broadcastIntent}}
,08-11 09:06:18.691   744  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-11 09:06:18.691   744  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-11 09:06:18.731   744  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-11 09:06:18.731   744  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4357, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-11 09:06:18.731   744  1321 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-11 09:06:18.731   744  1321 D BatteryService: stay LED for charging
08-11 09:06:18.731   744   744 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-11 09:06:18.731   744   744 I MotionRecognitionService: Plugged
08-11 09:06:18.731   744   744 D MotionRecognitionService:   cableConnection= 1
08-11 09:06:18.731   744   744 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-11 09:06:18.731   744   744 D MotionRecognitionService: skip setTransmitPower. 
,08-11 09:06:18.731  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-11 09:06:18.731  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-11 09:06:18.731  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-11 09:06:18.741  2170  2170 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-11 09:06:18.741  2170  2710 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-11 09:06:18.751  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 09:06:18.751  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-11 09:06:18.751  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 09:06:18.781  6402  6523 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 09:06:18.781  6402  6523 I jxcore-log: Failed to execute UT.
08-11 09:06:18.781  6402  6523 I jxcore-log: 
08-11 09:06:18.781  6402  6523 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:06:18.781  6402  6523 I jxcore-log: 
,08-11 09:06:18.791  6402  6523 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:06:18.791  6402  6523 I jxcore-log: 
08-11 09:06:18.791  6402  6402 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 09:06:18.821   744  3432 D SSRM:n  : SIOP:: AP = 450, PST = 442, CUR = 450, LCD = 0
,08-11 09:06:19.741  2176  2176 E audit   : type=1400 msg=audit(1470899179.731:290): avc:  denied  { execmod } for  pid=6821 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 09:06:19.741  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:19.741  2176  2176 E audit   : type=1300 msg=audit(1470899179.731:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f95000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6821 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 09:06:19.741  2176  2176 E audit   : type=1327 msg=audit(1470899179.731:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 09:06:19.741  2176  2176 E audit   : type=1320 msg=audit(1470899179.731:290): 
,08-11 09:06:19.791  2176  2176 E audit   : type=1400 msg=audit(1470899179.791:291): avc:  denied  { execmod } for  pid=6821 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 09:06:19.791  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:19.791  2176  2176 E audit   : type=1300 msg=audit(1470899179.791:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f55000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6821 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 09:06:19.791  2176  2176 E audit   : type=1327 msg=audit(1470899179.791:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 09:06:19.791  2176  2176 E audit   : type=1320 msg=audit(1470899179.791:291): 
,08-11 09:06:19.841  2176  2176 E audit   : type=1400 msg=audit(1470899179.841:292): avc:  denied  { execmod } for  pid=6821 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 09:06:19.841  2176  2176 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:19.841  2176  2176 E audit   : type=1300 msg=audit(1470899179.841:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f55000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6821 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 09:06:19.841  2176  2176 E audit   : type=1327 msg=audit(1470899179.841:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 09:06:19.841  2176  2176 E audit   : type=1320 msg=audit(1470899179.841:292): 
08-11 09:06:19.841  6821  6821 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 09:06:19.841   744  3460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 09:06:19.851  6821  6821 D AndroidRuntime: CheckJNI is OFF
,08-11 09:06:19.851  6821  6821 D AndroidRuntime: readGMSProperty: start
08-11 09:06:19.851  6821  6821 D AndroidRuntime: readGMSProperty: already setted!!
08-11 09:06:19.851  6821  6821 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-11 09:06:19.851  6821  6821 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-11 09:06:19.851  6821  6821 D AndroidRuntime: readGMSProperty: end
08-11 09:06:19.851  6821  6821 D AndroidRuntime: addProductProperty: start
,08-11 09:06:19.851  6821  6821 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 09:06:19.851  6821  6821 W art     : aedbc000-b1ce2000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-11 09:06:19.851  6821  6821 W art     : b1ce2000-b3f51000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-11 09:06:19.861  6821  6821 W art     : b3f51000-b3f52000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-11 09:06:19.861  6821  6821 W art     : b3f52000-b3f53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 09:06:19.861  6821  6821 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-11 09:06:19.861  6821  6821 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-11 09:06:19.861  6821  6821 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-11 09:06:19.861  6821  6821 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-11 09:06:19.861  6821  6821 W art     : b4826000-b4829000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
,08-11 09:06:19.861  6821  6821 W art     : b4829000-b482a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-11 09:06:19.861  6821  6821 W art     : b482a000-b482b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
,08-11 09:06:19.861  6821  6821 W art     : b482b000-b482c000 r--p 00000000 00:00 0 
,08-11 09:06:19.861  6821  6821 W art     : b482c000-b484c000 r--s 00000000 00:0b 8249       /dev/__properties__
,08-11 09:06:19.861  6821  6821 W art     : b484c000-b525d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so,
08-11 09:06:19.861  6821  6821 W art     : b525d000-b525e000 ---p 00000000 00:00 0 ,
,08-11 09:06:19.861  6821  6821 W art     : b525e000-b52a7000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so,
08-11 09:06:19.861  6821  6821 W art     : b52a7000-b52a8000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-11 09:06:19.861  6821  6821 W art     : b52a8000-b52b0000 rw-p 00000000 00:00 0 
,08-11 09:06:19.861  6821  6821 W art     : b52b0000-b52b1000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-11 09:06:19.861  6821  6821 W art     : b52b1000-b52e6000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so,
08-11 09:06:19.861  6821  6821 W art     : b52e6000-b52e7000 ---p 00000000 00:00 0 ,
08-11 09:06:19.861  6821  6821 W art     : b52e7000-b52e8000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
,08-11 09:06:19.861  6821  6821 W art     : b52e8000-b52e9000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
,08-11 09:06:19.861  6821  6821 W art     : b52e9000-b5341000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-11 09:06:19.861  6821  6821 W art     : b5341000-b5342000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5342000-b5343000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-11 09:06:19.861  6821  6821 W art     : b5343000-b5344000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
,08-11 09:06:19.861  6821  6821 W art     : b5345000-b534b000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 09:06:19.861  6821  6821 W art     : b534b000-b534c000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 09:06:19.861  6821  6821 W art     : b534c000-b534d000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 09:06:19.861  6821  6821 W art     : b534d000-b534f000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5350000-b535a000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 09:06:19.861  6821  6821 W art     : b535a000-b535d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 09:06:19.861  6821  6821 W art     : b535d000-b535e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 09:06:19.861  6821  6821 W art     : b535f000-b5376000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 09:06:19.861  6821  6821 W art     : b5376000-b5377000 ---p 00000000 00:00 0 
,08-11 09:06:19.861  6821  6821 W art     : b5377000-b5378000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 09:06:19.861  6821  6821 W art     : b5378000-b5379000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 09:06:19.861  6821  6821 W art     : b537a000-b5384000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
,08-11 09:06:19.861  6821  6821 W art     : b5384000-b5385000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-11 09:06:19.861  6821  6821 W art     : b5385000-b5386000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-11 09:06:19.861  6821  6821 W art     : b5386000-b538a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 09:06:19.861  6821  6821 W art     : b538a000-b538b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 09:06:19.861  6821  6821 W art     : b538b000-b538c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 09:06:19.861  6821  6821 W art     : b538c000-b53a2000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-11 09:06:19.861  6821  6821 W art     : b53a2000-b53a3000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-11 09:06:19.861  6821  6821 W art     : b53a3000-b53a4000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
,08-11 09:06:19.861  6821  6821 W art     : b53a4000-b53b1000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-11 09:06:19.861  6821  6821 W art     : b53b1000-b53b2000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-11 09:06:19.861  6821  6821 W art     : b53b2000-b53b3000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-11 09:06:19.861  6821  6821 W art     : b53b3000-b5413000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so,
08-11 09:06:19.861  6821  6821 W art     : b5413000-b5416000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-11 09:06:19.861  6821  6821 W art     : b5416000-b541a000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b541a000-b547b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
,08-11 09:06:19.861  6821  6821 W art     : b547b000-b547c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-11 09:06:19.861  6821  6821 W art     : b547c000-b54cb000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-11 09:06:19.861  6821  6821 W art     : b54cb000-b54cd000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-11 09:06:19.861  6821  6821 W art     : b54cd000-b54ce000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so,
08-11 09:06:19.861  6821  6821 W art     : b54ce000-b54cf000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b54cf000-b54d6000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 09:06:19.861  6821  6821 W art     : b54d6000-b54d7000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-11 09:06:19.861  6821  6821 W art     : b54d7000-b54d8000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-11 09:06:19.861  6821  6821 W art     : avc_common.so
08-11 09:06:19.861  6821  6821 W art     : b54d9000-b54dc000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-11 09:06:19.861  6821  6821 W art     : b54dc000-b54dd000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 09:06:19.861  6821  6821 W art     : b54dd000-b54de000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-11 09:06:19.861  6821  6821 W art     : enc_common.so
,08-11 09:06:19.861  6821  6821 W art     : b54df000-b54e3000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-11 09:06:19.861  6821  6821 W art     : b54e3000-b54e4000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b54e4000-b54e5000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
,08-11 09:06:19.861  6821  6821 W art     : b54e5000-b54e6000 rw-p 00005000 b3:17 2510       /syste
08-11 09:06:19.861  6821  6821 W art     : m/lib/libpowermanager.so
08-11 09:06:19.861  6821  6821 W art     : b54e7000-b5504000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 09:06:19.861  6821  6821 W art     : b5504000-b5505000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
,08-11 09:06:19.861  6821  6821 W art     : b5505000-b5506000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 09:06:19.861  6821  6821 W art     : b5507000-b550c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 09:06:19.861  6821  6821 W art     : b550c000-b550d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-11 09:06:19.861  6821  6821 W art     : b550d000-b550e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 09:06:19.861  6821  6821 W art     : b550f000-b5540000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 09:06:19.861  6821  6821 W art     : b5540000-b5543000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 09:06:19.861  6821  6821 W art     : b5543000-b5544000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 09:06:19.861  6821  6821 W art     : b5545000-b5580000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-11 09:06:19.861  6821  6821 W art     : b5580000-b5581000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-11 09:06:19.861  6821  6821 W art     : b5581000-b5582000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-11 09:06:19.861  6821  6821 W art     : b5583000-b558a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-11 09:06:19.861  6821  6821 W art     : b558a000-b558b000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b558b000-b558c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-11 09:06:19.861  6821  6821 W art     : b558c000-b558d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-11 09:06:19.861  6821  6821 W art     : b558d000-b558e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b558e000-b55a5000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-11 09:06:19.861  6821  6821 W art     : b55a5000-b55a6000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b55a6000-b55a9000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
,08-11 09:06:19.861  6821  6821 W art     : b55a9000-b55aa000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-11 09:06:19.861  6821  6821 W art     : b55aa000-b55c9000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-11 09:06:19.861  6821  6821 W art     : b55c9000-b55ca000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-11 09:06:19.861  6821  6821 W art     : b55ca000-b55cb000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-11 09:06:19.861  6821  6821 W art     : b55cb000-b5609000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
,08-11 09:06:19.861  6821  6821 W art     : b5609000-b560a000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b560a000-b560c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-11 09:06:19.861  6821  6821 W art     : b560c000-b560d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-11 09:06:19.861  6821  6821 W art     : b560e000-b5615000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
,08-11 09:06:19.861  6821  6821 W art     : b5615000-b5616000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 09:06:19.861  6821  6821 W art     : b5616000-b5617000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 09:06:19.861  6821  6821 W art     : b5618000-b561b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 09:06:19.861  6821  6821 W art     : b561b000-b561c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 09:06:19.861  6821  6821 W art     : b561c000-b561d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
,08-11 09:06:19.861  6821  6821 W art     : b561d000-b5623000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 09:06:19.861  6821  6821 W art     : b5623000-b5624000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5624000-b5625000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 09:06:19.861  6821  6821 W art     : b5625000-b5626000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 09:06:19.861  6821  6821 W art     : b5626000-b562f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-11 09:06:19.861  6821  6821 W art     : b562f000-b5630000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-11 09:06:19.861  6821  6821 W art     : b5630000-b5631000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-11 09:06:19.861  6821  6821 W art     : b5631000-b56c2000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 09:06:19.861  6821  6821 W art     : b56c2000-b56c3000 ---p 00000000 00:00 0 ,
08-11 09:06:19.861  6821  6821 W art     : b56c3000-b56ce000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 09:06:19.861  6821  6821 W art     : b56ce000-b56cf000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 09:06:19.861  6821  6821 W art     : b56d0000-b56e2000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-11 09:06:19.861  6821  6821 W art     : b56e2000-b56e3000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
,08-11 09:06:19.861  6821  6821 W art     : b56e3000-b56e4000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-11 09:06:19.861  6821  6821 W art     : b56e5000-b56ea000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-11 09:06:19.861  6821  6821 W art     : b56ea000-b56eb000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-11 09:06:19.861  6821  6821 W art     : b56eb000-b56ec000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
,08-11 09:06:19.861  6821  6821 W art     : b56ed000-b575a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-11 09:06:19.861  6821  6821 W art     : b575a000-b575b000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b575b000-b575d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-11 09:06:19.861  6821  6821 W art     : b575d000-b575e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-11 09:06:19.861  6821  6821 W art     : b575e000-b575f000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-11 09:06:19.861  6821  6821 W art     : b575f000-b5766000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 09:06:19.861  6821  6821 W art     : b5766000-b5767000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 09:06:19.861  6821  6821 W art     : b5767000-b5768000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 09:06:19.861  6821  6821 W art     : b5769000-b57e9000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 09:06:19.861  6821  6821 W art     : b57e9000-b57ea000 ---p 00000000 00:00 0 
,08-11 09:06:19.861  6821  6821 W art     : b57ea000-b57eb000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 09:06:19.861  6821  6821 W art     : b57eb000-b57ec000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 09:06:19.861  6821  6821 W art     : b57ec000-b5803000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5803000-b583a000 r-xp 00000000 b3:17 3244       /system/vendor/l
,08-11 09:06:19.861  6821  6821 W art     : ib/libqc-opt.so
08-11 09:06:19.861  6821  6821 W art     : b583a000-b583b000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 09:06:19.861  6821  6821 W art     : b583b000-b583c000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 09:06:19.861  6821  6821 W art     : b583c000-b5858000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 09:06:19.861  6821  6821 W art     : b5858000-b5859000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so,
08-11 09:06:19.861  6821  6821 W art     : b5859000-b585a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 09:06:19.861  6821  6821 W art     : b585b000-b58bc000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-11 09:06:19.861  6821  6821 W art     : b58bc000-b58be000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-11 09:06:19.861  6821  6821 W art     : b58be000-b58bf000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
,08-11 09:06:19.861  6821  6821 W art     : b58c0000-b58e7000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-11 09:06:19.861  6821  6821 W art     : b58e7000-b58e8000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b58e8000-b58e9000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-11 09:06:19.861  6821  6821 W art     : b58e9000-b58ea000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-11 09:06:19.861  6821  6821 W art     : b58eb000-b58f3000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 09:06:19.861  6821  6821 W art     : b58f3000-b58f5000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 09:06:19.861  6821  6821 W art     : b58f5000-b58f6000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 09:06:19.861  6821  6821 W art     : b58f7000-b58fa000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-11 09:06:19.861  6821  6821 W art     : b58fa000-b58fb000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-11 09:06:19.861  6821  6821 W art     : b58fb000-b58fc000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so,
08-11 09:06:19.861  6821  6821 W art     : b58fc000-b5900000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-11 09:06:19.861  6821  6821 W art     : b5900000-b5901000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5901000-b5902000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-11 09:06:19.861  6821  6821 W art     : b5902000-b5903000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
,08-11 09:06:19.861  6821  6821 W art     : b5903000-b5913000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-11 09:06:19.861  6821  6821 W art     : b5913000-b5914000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-11 09:06:19.861  6821  6821 W art     : b5914000-b5915000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-11 09:06:19.861  6821  6821 W art     : b5915000-b595b000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b595b000-b5964000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-11 09:06:19.861  6821  6821 W art     : b5964000-b5965000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-11 09:06:19.861  6821  6821 W art     : b5965000-b5966000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-11 09:06:19.861  6821  6821 W art     : b5967000-b596c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-11 09:06:19.861  6821  6821 W art     : b596c000-b596d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-11 09:06:19.861  6821  6821 W art     : b596d000-b596e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
,08-11 09:06:19.861  6821  6821 W art     : b596e000-b5971000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 09:06:19.861  6821  6821 W art     : b5971000-b5972000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5972000-b5973000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 09:06:19.861  6821  6821 W art     : b5973000-b5974000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 09:06:19.861  6821  6821 W art     : b5975000-b598d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-11 09:06:19.861  6821  6821 W art     : b598d000-b598e000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b598e000-b598f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 09:06:19.861  6821  6821 W art     : b598f000-b5990000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 09:06:19.861  6821  6821 W art     : b5991000-b5b2b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-11 09:06:19.861  6821  6821 W art     : b5b2b000-b5b2c000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5b2c000-b5b39000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-11 09:06:19.861  6821  6821 W art     : b5b39000-b5b3a000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-11 09:06:19.861  6821  6821 W art     : b5b3a000-b5b3e000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-11 09:06:19.861  6821  6821 W art     : b5b3e000-b5b3f000 ---p 00000000 00:00 0 
,08-11 09:06:19.861  6821  6821 W art     : b5b3f000-b5b40000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-11 09:06:19.861  6821  6821 W art     : b5b40000-b5b41000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-11 09:06:19.861  6821  6821 W art     : b5b41000-b5b54000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-11 09:06:19.861  6821  6821 W art     : b5b54000-b5b55000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-11 09:06:19.861  6821  6821 W art     : b5b55000-b5b56000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
,08-11 09:06:19.861  6821  6821 W art     : b5b56000-b5b57000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:19.861  6821  6821 W art     : b5b57000-b5ba2000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-11 09:06:19.861  6821  6821 W art     : b5ba2000-b5ba3000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-11 09:06:19.861  6821  6821 W art     : b5ba3000-b5ba4000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-11 09:06:19.861  6821  6821 W art     : b5ba4000-b5ba6000 rw-p 00000000 00:00 0 ,
08-11 09:06:19.861  6821  6821 W art     : b5ba7000-b5bb8000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 09:06:19.861  6821  6821 W art     : b5bb8000-b5bb9000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5bb9000-b5bba000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 09:06:19.861  6821  6821 W art     : b5bba000-b5bbb000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 09:06:19.861  6821  6821 W art     : b5bbc000-b5bc6000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so,
08-11 09:06:19.861  6821  6821 W art     : b5bc6000-b5bc8000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-11 09:06:19.861  6821  6821 W art     : b5bc8000-b5bc9000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-11 09:06:19.861  6821  6821 W art     : b5bc9000-b5be2000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-11 09:06:19.861  6821  6821 W art     : b5be2000-b5be3000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-11 09:06:19.861  6821  6821 W art     : b5be3000-b5be6000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-11 09:06:19.861  6821  6821 W art     : b5be6000-b5bea000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5bea000-b5c5e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-11 09:06:19.861  6821  6821 W art     : b5c5e000-b5c5f000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5c5f000-b5c62000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-11 09:06:19.861  6821  6821 W art     : b5c62000-b5c63000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-11 09:06:19.861  6821  6821 W art     : b5c63000-b5c64000 r--p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5c64000-b5c67000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-11 09:06:19.861  6821  6821 W art     : b5c67000-b5c68000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-11 09:06:19.861  6821  6821 W art     : b5c68000-b5c69000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-11 09:06:19.861  6821  6821 W art     : b5c69000-b5c6a000 r--p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5c6a000-b5c6f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 09:06:19.861  6821  6821 W art     : b5c6f000-b5c70000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 09:06:19.861  6821  6821 W art     : b5c70000-b5c71000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 09:06:19.861  6821  6821 W art     : b5c71000-b5c72000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b5c72000-b5c75000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 09:06:19.861  6821  6821 W art     : b5c75000-b5c76000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 09:06:19.861  6821  6821 W art     : b5c76000-b5c77000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 09:06:19.861  6821  6821 W art     : b5c77000-b5c78000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b5c78000-b5c7c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-11 09:06:19.861  6821  6821 W art     : b5c7c000-b5c7d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-11 09:06:19.861  6821  6821 W art     : b5c7d000-b5c7e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-11 09:06:19.861  6821  6821 W art     : b5c7e000-b5c7f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:19.861  6821  6821 W art     : b5c7f000-b5c83000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 09:06:19.861  6821  6821 W art     : b5c83000-b5c84000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 09:06:19.861  6821  6821 W art     : b5c84000-b5c85000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 09:06:19.861  6821  6821 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b5c86000-b5c94000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-11 09:06:19.861  6821  6821 W art     : b5c94000-b5c95000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b5c95000-b5c96000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-11 09:06:19.861  6821  6821 W art     : b5c96000-b5c97000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-11 09:06:19.861  6821  6821 W art     : b5c97000-b5ca1000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 09:06:19.861  6821  6821 W art     : b5ca1000-b5ca4000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 09:06:19.861  6821  6821 W art     : b5ca4000-b5ca5000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 09:06:19.861  6821  6821 W art     : b5ca5000-b5ca6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b5ca6000-b5cb0000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-11 09:06:19.861  6821  6821 W art     : b5cb0000-b5cb3000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-11 09:06:19.861  6821  6821 W art     : b5cb3000-b5cb4000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-11 09:06:19.861  6821  6821 W art     : b5cb4000-b5cb8000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-11 09:06:19.861  6821  6821 W art     : b5cb8000-b5cb9000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-11 09:06:19.861  6821  6821 W art     : b5cb9000-b5cba000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-11 09:06:19.861  6821  6821 W art     : b5cba000-b5cbb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b5cbb000-b5cc8000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-11 09:06:19.861  6821  6821 W art     : b5cc8000-b5cca000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-11 09:06:19.861  6821  6821 W art     : b5cca000-b5ccb000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-11 09:06:19.861  6821  6821 W art     : b5ccb000-b60dd000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-11 09:06:19.861  6821  6821 W art     : b60dd000-b60de000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b60de000-b60e7000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-11 09:06:19.861  6821  6821 W art     : b60e7000-b60eb000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-11 09:06:19.861  6821  6821 W art     : b60eb000-b60ec000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b60ec000-b60f3000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-11 09:06:19.861  6821  6821 W art     : b60f3000-b60f4000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-11 09:06:19.861  6821  6821 W art     : b60f4000-b60f5000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-11 09:06:19.861  6821  6821 W art     : b60f5000-b60f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b60f6000-b6111000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-11 09:06:19.861  6821  6821 W art     : b6111000-b6112000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-11 09:06:19.861  6821  6821 W art     : b6112000-b6113000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-11 09:06:19.861  6821  6821 W art     : b6113000-b6114000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6114000-b6160000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 09:06:19.861  6821  6821 W art     : b6160000-b6161000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6161000-b6162000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 09:06:19.861  6821  6821 W art     : b6162000-b6163000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 09:06:19.861  6821  6821 W art     : b6163000-b6164000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6164000-b6168000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-11 09:06:19.861  6821  6821 W art     : b6168000-b6169000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6169000-b616a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-11 09:06:19.861  6821  6821 W art     : b616a000-b616b000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-11 09:06:19.861  6821  6821 W art     : b616b000-b61a3000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-11 09:06:19.861  6821  6821 W art     : b61a3000-b61a4000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-11 09:06:19.861  6821  6821 W art     : b61a4000-b61a5000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-11 09:06:19.861  6821  6821 W art     : b61a5000-b61a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b61a6000-b6244000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-11 09:06:19.861  6821  6821 W art     : b6244000-b6245000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6245000-b6263000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-11 09:06:19.861  6821  6821 W art     : b6263000-b6264000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-11 09:06:19.861  6821  6821 W art     : b6264000-b63d7000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-11 09:06:19.861  6821  6821 W art     : b63d7000-b63e2000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-11 09:06:19.861  6821  6821 W art     : b63e2000-b63e3000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-11 09:06:19.861  6821  6821 W art     : b63e3000-b64fa000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-11 09:06:19.861  6821  6821 W art     : b64fa000-b6505000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-11 09:06:19.861  6821  6821 W art     : b6505000-b6506000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-11 09:06:19.861  6821  6821 W art     : b6506000-b650a000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b650a000-b652e000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-11 09:06:19.861  6821  6821 W art     : b652e000-b6530000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-11 09:06:19.861  6821  6821 W art     : b6530000-b6531000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-11 09:06:19.861  6821  6821 W art     : b6531000-b65d7000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-11 09:06:19.861  6821  6821 W art     : b65d7000-b65e4000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-11 09:06:19.861  6821  6821 W art     : b65e4000-b65e5000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-11 09:06:19.861  6821  6821 W art     : b65e5000-b65e6000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b65e6000-b6639000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-11 09:06:19.861  6821  6821 W art     : b6639000-b663a000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b663a000-b663b000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-11 09:06:19.861  6821  6821 W art     : b663b000-b663c000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-11 09:06:19.861  6821  6821 W art     : b663c000-b6641000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6641000-b6653000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-11 09:06:19.861  6821  6821 W art     : b6653000-b6654000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6654000-b6655000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-11 09:06:19.861  6821  6821 W art     : b6655000-b6656000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-11 09:06:19.861  6821  6821 W art     : b6656000-b665d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 09:06:19.861  6821  6821 W art     : b665d000-b665e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 09:06:19.861  6821  6821 W art     : b665e000-b665f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 09:06:19.861  6821  6821 W art     : b665f000-b6660000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6660000-b6663000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-11 09:06:19.861  6821  6821 W art     : b6663000-b6664000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-11 09:06:19.861  6821  6821 W art     : b6664000-b6665000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-11 09:06:19.861  6821  6821 W art     : b6665000-b6669000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-11 09:06:19.861  6821  6821 W art     : b6669000-b666a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-11 09:06:19.861  6821  6821 W art     : b666a000-b666b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-11 09:06:19.861  6821  6821 W art     : b666b000-b6679000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-11 09:06:19.861  6821  6821 W art     : b6679000-b667a000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b667a000-b667b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-11 09:06:19.861  6821  6821 W art     : b667b000-b667c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-11 09:06:19.861  6821  6821 W art     : b667c000-b6685000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 09:06:19.861  6821  6821 W art     : b6685000-b6686000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 09:06:19.861  6821  6821 W art     : b6686000-b6687000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 09:06:19.861  6821  6821 W art     : b6687000-b66ed000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-11 09:06:19.861  6821  6821 W art     : b66ed000-b66ee000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b66ee000-b66f0000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-11 09:06:19.861  6821  6821 W art     : b66f0000-b66f9000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-11 09:06:19.861  6821  6821 W art     : b66f9000-b66fc000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b66fc000-b6793000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-11 09:06:19.861  6821  6821 W art     : b6793000-b6795000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-11 09:06:19.861  6821  6821 W art     : b6795000-b6796000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-11 09:06:19.861  6821  6821 W art     : b6796000-b6797000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6797000-b6ab8000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-11 09:06:19.861  6821  6821 W art     : b6ab8000-b6ab9000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6ab9000-b6ad4000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-11 09:06:19.861  6821  6821 W art     : b6ad4000-b6ad8000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-11 09:06:19.861  6821  6821 W art     : b6ad8000-b6add000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6add000-b6ae5000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 09:06:19.861  6821  6821 W art     : b6ae5000-b6ae6000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 09:06:19.861  6821  6821 W art     : b6ae6000-b6ae7000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 09:06:19.861  6821  6821 W art     : b6ae7000-b6b15000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-11 09:06:19.861  6821  6821 W art     : b6b15000-b6b16000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6b16000-b6b1d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-11 09:06:19.861  6821  6821 W art     : b6b1d000-b6b1e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-11 09:06:19.861  6821  6821 W art     : b6b1e000-b6b64000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-11 09:06:19.861  6821  6821 W art     : b6b64000-b6b65000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6b65000-b6b68000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-11 09:06:19.861  6821  6821 W art     : b6b68000-b6b69000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-11 09:06:19.861  6821  6821 W art     : b6b69000-b6b84000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-11 09:06:19.861  6821  6821 W art     : b6b84000-b6b88000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-11 09:06:19.861  6821  6821 W art     : b6b88000-b6b89000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-11 09:06:19.861  6821  6821 W art     : b6b89000-b6bd6000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-11 09:06:19.861  6821  6821 W art     : b6bd6000-b6bd7000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6bd7000-b6be3000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-11 09:06:19.861  6821  6821 W art     : b6be3000-b6be4000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-11 09:06:19.861  6821  6821 W art     : b6be4000-b6bf1000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-11 09:06:19.861  6821  6821 W art     : b6bf1000-b6bf2000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6bf2000-b6bf3000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-11 09:06:19.861  6821  6821 W art     : b6bf3000-b6bf4000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-11 09:06:19.861  6821  6821 W art     : b6bf4000-b6bfc000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-11 09:06:19.861  6821  6821 W art     : b6bfc000-b6bfd000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6bfd000-b6bfe000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-11 09:06:19.861  6821  6821 W art     : b6bfe000-b6bff000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-11 09:06:19.861  6821  6821 W art     : b6bff000-b6c06000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-11 09:06:19.861  6821  6821 W art     : b6c06000-b6c07000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-11 09:06:19.861  6821  6821 W art     : b6c07000-b6c08000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-11 09:06:19.861  6821  6821 W art     : b6c08000-b6c1c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-11 09:06:19.861  6821  6821 W art     : b6c1c000-b6c1e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-11 09:06:19.861  6821  6821 W art     : b6c1e000-b6c1f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-11 09:06:19.861  6821  6821 W art     : b6c1f000-b6c47000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-11 09:06:19.861  6821  6821 W art     : b6c47000-b6c49000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-11 09:06:19.861  6821  6821 W art     : b6c49000-b6c4a000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-11 09:06:19.861  6821  6821 W art     : b6c4a000-b6c4d000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-11 09:06:19.861  6821  6821 W art     : b6c4d000-b6c4e000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-11 09:06:19.861  6821  6821 W art     : b6c4e000-b6c4f000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-11 09:06:19.861  6821  6821 W art     : b6c4f000-b6c58000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-11 09:06:19.861  6821  6821 W art     : b6c58000-b6c59000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-11 09:06:19.861  6821  6821 W art     : b6c59000-b6c5a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-11 09:06:19.861  6821  6821 W art     : b6c5a000-b6c7a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-11 09:06:19.861  6821  6821 W art     : b6c7a000-b6c7b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-11 09:06:19.861  6821  6821 W art     : b6c7b000-b6c7c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-11 09:06:19.861  6821  6821 W art     : b6c7c000-b6cef000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-11 09:06:19.861  6821  6821 W art     : b6cef000-b6cf3000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-11 09:06:19.861  6821  6821 W art     : b6cf3000-b6cf6000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-11 09:06:19.861  6821  6821 W art     : b6cf6000-b6d00000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6d00000-b6d88000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-11 09:06:19.861  6821  6821 W art     : b6d88000-b6d89000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6d89000-b6d8d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-11 09:06:19.861  6821  6821 W art     : b6d8d000-b6d8e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-11 09:06:19.861  6821  6821 W art     : b6d8e000-b6d8f000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6d8f000-b6db8000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-11 09:06:19.861  6821  6821 W art     : b6db8000-b6db9000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6db9000-b6dbc000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-11 09:06:19.861  6821  6821 W art     : b6dbc000-b6dbd000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-11 09:06:19.861  6821  6821 W art     : b6dbd000-b6e97000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 09:06:19.861  6821  6821 W art     : b6e97000-b6e9e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 09:06:19.861  6821  6821 W art     : b6e9e000-b6ea6000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 09:06:19.861  6821  6821 W art     : b6ea6000-b6ea7000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6ea7000-b6ea8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:19.861  6821  6821 W art     : b6ea8000-b6ea9000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-11 09:06:19.861  6821  6821 W art     : b6ea9000-b6eaa000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6eaa000-b6ead000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6ead000-b6ed2000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-11 09:06:19.861  6821  6821 W art     : b6ed2000-b6ed3000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6ed3000-b6eda000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-11 09:06:19.861  6821  6821 W art     : b6eda000-b6edb000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-11 09:06:19.861  6821  6821 W art     : b6edb000-b6ee2000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-11 09:06:19.861  6821  6821 W art     : b6ee2000-b6ee3000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-11 09:06:19.861  6821  6821 W art     : b6ee3000-b6ee4000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-11 09:06:19.861  6821  6821 W art     : b6ee4000-b6ee5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6ee5000-b6efd000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-11 09:06:19.861  6821  6821 W art     : b6efd000-b6efe000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6efe000-b6eff000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-11 09:06:19.861  6821  6821 W art     : b6eff000-b6f00000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-11 09:06:19.861  6821  6821 W art     : b6f00000-b6f0e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-11 09:06:19.861  6821  6821 W art     : b6f0e000-b6f0f000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6f0f000-b6f10000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-11 09:06:19.861  6821  6821 W art     : b6f10000-b6f11000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-11 09:06:19.861  6821  6821 W art     : b6f11000-b6f12000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:19.861  6821  6821 W art     : b6f12000-b6f14000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6f14000-b6f15000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6f15000-b6f16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 09:06:19.861  6821  6821 W art     : b6f16000-b6f17000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-11 09:06:19.861  6821  6821 W art     : b6f17000-b6f18000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 09:06:19.861  6821  6821 W art     : b6f18000-b6f38000 r--s 00000000 00:0b 8249       /dev/__properties__
08-11 09:06:19.861  6821  6821 W art     : b6f38000-b6f39000 r--p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6f39000-b6f3a000 ---p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6f3a000-b6f3c000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-11 09:06:19.861  6821  6821 W art     : b6f3c000-b6f3d000 r-xp 00000000 00:00 0          [sigpage]
08-11 09:06:19.861  6821  6821 W art     : b6f3d000-b6f58000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-11 09:06:19.861  6821  6821 W art     : b6f58000-b6f59000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-11 09:06:19.861  6821  6821 W art     : b6f59000-b6f5b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-11 09:06:19.861  6821  6821 W art     : b6f5b000-b6f5d000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : b6f5d000-b6f62000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-11 09:06:19.861  6821  6821 W art     : b6f62000-b6f63000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-11 09:06:19.861  6821  6821 W art     : b6f63000-b6f64000 rw-p 00000000 00:00 0 
08-11 09:06:19.861  6821  6821 W art     : bee15000-bee36000 rw-p 00000000 00:00 0          [stack]
08-11 09:06:19.861  6821  6821 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-11 09:06:19.921  6821  6821 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 09:06:19.991  6821  6821 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 09:06:20.001  6821  6821 E AffinityControl: AffinityControl: registerfunction enter
,08-11 09:06:20.021  6821  6821 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:06:20.031   744  1720 D PackageManager: START PACKAGE DELETE: observer{96007083}
08-11 09:06:20.031   744  1720 D PackageManager: pkg{<packageName>}
08-11 09:06:20.031   744  1720 D PackageManager: user{0}
08-11 09:06:20.031   744  1720 D PackageManager: caller{2000}
08-11 09:06:20.031   744  1720 D PackageManager: flags{2}
,08-11 09:06:20.031   744  1720 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-11 09:06:20.031   744  1720 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-11 09:06:20.031   744  1720 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-11 09:06:20.031   744  1720 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-11 09:06:20.031   744  1720 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-11 09:06:20.031   744   909 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-11 09:06:20.031   744   909 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-11 09:06:20.031   744   909 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-11 09:06:20.031   744   909 D ApplicationPolicy: getApplicationUninstallationEnabled
08-11 09:06:20.031   744   909 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-11 09:06:20.041   744   909 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-11 09:06:20.041   744   909 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-11 09:06:20.041   744   909 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-11 09:06:20.041   744   798 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-11 09:06:20.041   744   909 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-11 09:06:20.041   744   909 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-11 09:06:20.041   744   798 I ActivityManager: Killing 6402:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-11 09:06:20.041   744   798 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-11 09:06:20.041   744   798 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-11 09:06:20.061  6830  6830 E Zygote  : v2
08-11 09:06:20.061  6830  6830 I libpersona: KNOX_SDCARD checking this for 10004
08-11 09:06:20.061  6830  6830 I libpersona: KNOX_SDCARD not a persona
,08-11 09:06:20.061  6830  6830 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:20.061  6830  6830 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 09:06:20.061  6830  6830 E Zygote  : accessInfo : 0
08-11 09:06:20.061  6830  6830 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-11 09:06:20.061   744   798 I ActivityManager: Start proc 6830:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,08-11 09:06:20.071   744   798 I ActivityManager:   Force finishing activity ActivityRecord{70b867b u0 com.test.thalitest/.MainActivity t153}
,08-11 09:06:20.071   293   337 I SurfaceFlinger: id=17 Removed NainActivit (4/10)
,08-11 09:06:20.081   293   337 I SurfaceFlinger: id=17 Removed NainActivit (-2/10)
,08-11 09:06:20.081   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
,08-11 09:06:20.111  6830  6830 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 09:06:20.111  6830  6830 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:20.111   744   909 D AASAinstall: there is not AASApackages.xml file
,08-11 09:06:20.131   744  1666 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b400a08)
,08-11 09:06:20.131   744  1333 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 09:06:20.131   744  2038 D GraphicsStats: Buffer count: 5
,08-11 09:06:20.131   744  1333 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 09:06:20.131   744  1333 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 09:06:20.401   744   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-11 09:06:20.441   744   909 W PackageSettings: Skipping PackageSetting{2d85fba com.example.hello/10192} due to missing metadata
,08-11 09:06:20.511   744   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-11 09:06:20.511   744  1677 I ActivityManager: Killing 6083:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-11 09:06:20.531   331   331 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-11 09:06:20.531  6830  6830 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 09:06:20.531   744   909 I art     : Starting a blocking GC Explicit
,08-11 09:06:20.551   744  1720 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-11 09:06:20.551  6830  6830 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-11 09:06:20.551  6830  6830 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-11 09:06:20.551  6830  6830 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-11 09:06:20.551  6830  6830 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-11 09:06:20.561  6830  6830 D AndroidRuntime: Shutting down VM
,08-11 09:06:20.571  6830  6830 E AndroidRuntime: FATAL EXCEPTION: main
08-11 09:06:20.571  6830  6830 E AndroidRuntime: Process: com.test.thalitest, PID: 6830
08-11 09:06:20.571  6830  6830 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-11 09:06:20.571  6830  6830 E AndroidRuntime: 	... 9 more
,08-11 09:06:20.581  6830  6830 I Process : Sending signal. PID: 6830 SIG: 9
,08-11 09:06:20.601  6867  6867 E Zygote  : v2
,08-11 09:06:20.601  6867  6867 I libpersona: KNOX_SDCARD checking this for 1000
08-11 09:06:20.601  6867  6867 I libpersona: KNOX_SDCARD not a persona
08-11 09:06:20.601   744   798 I ActivityManager: Start proc 6867:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-11 09:06:20.601   744  1677 I ActivityManager: Process com.test.thalitest (pid 6830)(adj 9) has died(163,732)
,08-11 09:06:20.601  6867  6867 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 09:06:20.601  6867  6867 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 09:06:20.601  6867  6867 E Zygote  : accessInfo : 0
,08-11 09:06:20.601   744  1677 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 09:06:20.601   744  1677 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-11 09:06:20.611   744  1677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-11 09:06:20.611   744   798 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-11 09:06:20.611   744   798 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-11 09:06:20.631  6867  6867 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 09:06:20.631  6867  6867 D ActivityThread: Added TimaKeyStore provider
,08-11 09:06:20.641   744  1593 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{782e5a1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3903c6 6867:com.samsung.android.sm/1000}
,08-11 09:06:20.651  6867  6867 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-11 09:06:20.691  6867  6867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-11 09:06:20.701   744   758 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{782e5a1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53312a4 2813:com.google.android.gms/u0a11}
,08-11 09:06:20.701   744   909 I art     : Explicit concurrent mark sweep GC freed 86791(4MB) AllocSpace objects, 13(260KB) LOS objects, 27% free, 41MB/57MB, paused 1.697ms total 160.253ms
,08-11 09:06:20.721   744   909 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 09:06:20.721   744   909 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-11 09:06:20.721   744   909 D AASAinstall: there is not AASApackages.xml file
08-11 09:06:20.721   744   909 D PackageManager: result of delete: 1{96007083}
,08-11 09:06:20.721  6821  6821 I art     : System.exit called, status: 0
08-11 09:06:20.721  6821  6821 I AndroidRuntime: VM exiting with result code 0.
,08-11 09:06:20.731   744   909 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-11 09:06:20.731   744   909 D PackageManager: userId{-1}
08-11 09:06:20.731   744   909 D PackageManager: andCode{true}
,08-11 09:06:20.751   744   909 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-11 09:06:20.761  5953  6884 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-11 09:06:20.761  5953  6884 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-11 09:06:20.761  5953  6884 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-11 09:06:20.791   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.801   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.801   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.801  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-11 09:06:20.801  1382  1382 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-11 09:06:20.801   744   868 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.811   744   868 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.811   744  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 09:06:20.811   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.811  2007  2007 E SamsungIME: mOCRHelper is null
08-11 09:06:20.811   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821   744   744 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.821  1934  2393 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 09:06:20.831   744   744 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.831   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.831   744   798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90e0538 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7387fe2 4281:com.samsung.klmsagent/u0a18}
,08-11 09:06:20.831   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.831  4281  4281 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Thu Aug 11 09:06:20 GMT+02:00 2016
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.841   744   744 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.841   744  1324 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-11 09:06:20.841   744  1324 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-11 09:06:20.841   744  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-11 09:06:20.841   744  1323 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-11 09:06:20.841   744  1323 V NetworkStats: performPollLocked(flags=0x3)
,08-11 09:06:20.851  1652  1652 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 09:06:20.851  3209  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 09:06:20.851  3209  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 09:06:20.851  3209  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-11 09:06:20.851   744  1323 V NetworkStats: performPollLocked() took 8ms
,08-11 09:06:20.851   744  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,08-11 09:06:20.851  3209  3225 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 09:06:20.851  4281  4281 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-11 09:06:20.851   744   744 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.861   744  2038 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-11 09:06:20.861   744  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90e0538 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6b50216 744:system/1000}
,08-11 09:06:20.861   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.861  4281  4281 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-11 09:06:20.861  4281  4281 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-11 09:06:20.861  4281  4281 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-11 09:06:20.861  4281  6891 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
,08-11 09:06:20.861  4281  6891 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-11 09:06:20.861  4281  6891 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-11 09:06:20.861  4281  6891 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,08-11 09:06:20.861  4281  6891 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-11 09:06:20.861  4281  6891 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-11 09:06:20.871   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.871   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.871   744  1324 D NtpTrustedTime: currentTimeMillis() cache hit
,08-11 09:06:20.871   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.871   744  1324 D NtpTrustedTime: currentTimeMillis() cache hit
08-11 09:06:20.871   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.871   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.871   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881  1643  6892 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-11 09:06:20.881  4281  6891 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-11 09:06:20.881  1643  6892 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-11 09:06:20.881  1643  6892 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 09:06:20.881  1643  6892 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 09:06:20.881  1643  6892 D RegisteredComponentCache: Collect Tech packages for Knox
,08-11 09:06:20.881  4281  6891 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.881   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.891   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.901   744   744 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.901   744   744 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.901  4281  6891 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-11 09:06:20.901  4281  6891 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-11 09:06:20.921  4281  6891 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-11 09:06:20.921  4281  6891 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x733093a8 in tid 6891 (IntentService[K)
,08-11 09:06:20.921  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:20.931   744   744 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.931   744   744 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.931   744  1299 I EventHub: Removing device '/dev/input/event4' due to inotify event
08-11 09:06:20.931  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:20.931   744   744 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.931   744   744 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.941   744   744 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.941   744   744 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.941   744  1666 I ActivityManager: Process com.samsung.klmsagent (pid 4281)(adj 5) has died(188,718)
,08-11 09:06:20.941   744  1666 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
08-11 09:06:20.941   744   744 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.941   744  1666 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
08-11 09:06:20.941   744   744 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.941   744   744 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.951   744   744 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.961   744   744 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.961   744   744 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.961  1934  1934 D ChimeraCfgMgr: Reading stored module config
,08-11 09:06:20.961  1934  1934 E ChimeraCfgMgr: Failed to read module config: /data/user/0/com.google.android.gms/app_chimera/current_config.pb: open failed: ENOENT (No such file or directory)
,08-11 09:06:20.961   744   744 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.961   744   744 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   353   353 I Zygote  : Process 4281 exited due to signal (7)
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.971   744   744 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.981   744  1299 I EventHub: Removing device '/dev/input/event5' due to inotify event
,08-11 09:06:20.981  1934  1934 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9c15e87c in tid 1934 (.gms.persistent)
,08-11 09:06:20.981  1934  1934 F libc    : Unable to open connection to debuggerd: Connection refused
08-11 09:06:20.981  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:20.981   744   744 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.981   744   744 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.981   744   744 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.981   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.981   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.981   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991  2813  6894 D ChimeraCfgMgr: Reading stored module config
08-11 09:06:20.991  2813  6894 E ChimeraCfgMgr: Failed to read module config: /data/user/0/com.google.android.gms/app_chimera/current_config.pb: open failed: ENOENT (No such file or directory)
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:20.991   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 09:06:21.001   744   744 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-11 09:06:21.001   744   744 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d795aeb in tid 744 (system_server)
,08-11 09:06:21.001   744   744 F libc    : Unable to open connection to debuggerd: Connection refused
08-11 09:06:21.001  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:21.011  2813  2813 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9aeb6a0f in tid 2813 (gle.android.gms)
,08-11 09:06:21.011  2813  2813 F libc    : Unable to open connection to debuggerd: Connection refused
08-11 09:06:21.011  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:21.071   353   353 I Zygote  : Process 1934 exited due to signal (7)
,08-11 09:06:21.081   292   292 I ServiceManager: service 'dropbox' died
,08-11 09:06:21.081   329   329 E installd: eof
08-11 09:06:21.081   329   329 E installd: failed to read size
08-11 09:06:21.081   329   329 I installd: closing connection
,08-11 09:06:21.081  1669  6415 W Sensors : sensorservice died [0xacece0c0]
08-11 09:06:21.081   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb4a3f6fc
08-11 09:06:21.081   292   292 I ServiceManager: service 'wallpaper' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'audio' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'DockObserver' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'midi' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'usb' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'serial' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'kiesusb' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'jobscheduler' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'backup' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'appwidget' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'voiceinteraction' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'diskstats' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'mDNIe' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'AAS' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'MSCS' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'spengestureservice' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'quickconnect' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'samplingprofiler' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'commontime_management' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'dreams' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'graphicsstats' died
08-11 09:06:21.081   353   353 I Zygote  : Process 2813 exited due to signal (7)
08-11 09:06:21.081   292   292 I ServiceManager: service 'print' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'restrictions' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'media_session' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'media_router' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'trust' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'fingerprint' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'launcherapps' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'voip' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'media_projection' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'lpnet' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'imms' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'textservices' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'network_score' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'netstats' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'netpolicy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'wifip2p' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'wifi' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'wifihs20' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'wifiscanner' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'rttmanager' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'ethernet' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'connectivity' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sb_service' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'servicediscovery' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'updatelock' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'notification' died
08-11 09:06:21.081   292   292 I Service,Manager: service 'devicestoragemonitor' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'location' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'country_detector' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sec_location' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'search' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'execute' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'edmnativehelper' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sec_analytics' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'telecom' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'SEAMService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'media.camera.proxy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'account' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'content' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'DirEncryptService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'LSManager' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'ReactiveService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'EngineeringModeService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'SatsService' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sedenial' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'vibrator' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'tw_toolbox' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'tima' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'iccc' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'cepproxyks' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'emailksproxy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'consumer_ir' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'alarm' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'context_aware' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'activity' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'user' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'procstats' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'meminfo' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'gfxinfo' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'dbinfo' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'cpuinfo' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'permission' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'processinfo' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sensorservice' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'battery' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'usagestats' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'webviewupdate' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'scheduling_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'telephony.registry' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'persona' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-11 09:06:21.091  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
08-11 09:06:21.081   292   292 I ServiceManager: service 'enterprise_license_policy' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'application_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'wifi_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'remoteinjection' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'knox_ucsm_policy' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'edm_proxy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'mum_container_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'otp_service' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'enterprise_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'statusbar' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'clipboard' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'clipboardEx' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'network_management' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'scontext' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'barbeam' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'multiwindow_facade' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'window' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'input' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'bluetooth_manager' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'rcp' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'input_method' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'accessibility' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'cover' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'mount' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'batterystats' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'appops' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'power' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'display' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'uimode' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'persona_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'package' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'lock_settings' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'deviceidle' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'device_policy' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'harmony_eas_service' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sdp' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'sdp_log' died
,08-11 09:06:21.081   292   292 I ServiceManager: service 'dlp' died
08-11 09:06:21.081   292   292 I ServiceManager: service 'log_manager_service' died
08-11 09:06:21.081  2215  2250 W Sensors : sensorservice died [0xb3ab3a40]
08-11 09:06:21.081  1963  1974 W Sensors : sensorservice died [0xb3ab3980]
08-11 09:06:21.081   293   339 I SurfaceFlinger: restart the boot-animation @ binderDied
08-11 09:06:21.081   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
08-11 09:06:21.081   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=2 Removed GocusedStac (4/9)
08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=9 Removed EimLayer(Di (3/6)
08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=10 Removed EimLayer(An (0/5)
,08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-11 09:06:21.091   293  1297 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-11 09:06:21.091  2170  2170 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ef99cef in tid 2170 (droid.bluetooth)
08-11 09:06:21.091  2170  2170 F libc    : Unable to open connection to debuggerd: Connection refused
08-11 09:06:21.091   293   337 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
,08-11 09:06:21.091   293   337 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-11 09:06:21.091   293   337 I SurfaceFlinger: id=6 Removed JmageWallpa (0/3)
08-11 09:06:21.091   293   337 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/3)
08-11 09:06:21.091  1382  1625 E WifiManager: Channel connection lost
,08-11 09:06:21.101  6012  6078 E WifiManager: Channel connection lost
,08-11 09:06:21.101   325   325 W AudioFlinger: power manager service died !!!
08-11 09:06:21.101   325   325 W AudioFlinger: power manager service died !!!
,08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=18 Removed VSBConnecti (1/2)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=19 Removed VSBConnecti (0/1)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/1)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/1)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=15 Removed DolorFade (0/0)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=15 Removed DolorFade (-2/0)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=9 Removed EimLayer(Di (-2/0)
08-11 09:06:21.111   293  1297 I SurfaceFlinger: id=10 Removed EimLayer(An (-2/0)
,08-11 09:06:21.111  1805  1957 E WifiManager: Channel connection lost
08-11 09:06:21.111  1652  1652 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-11 09:06:21.111  5771  5771 D AndroidRuntime: Shutting down VM
08-11 09:06:21.111  1652  2465 E WifiManager: Channel connection lost
,08-11 09:06:21.111  1382  2376 W Sensors : sensorservice died [0xb3a88c80]
,08-11 09:06:21.111  5771  5771 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e0a1134 in tid 5771 (android.vending)
,08-11 09:06:21.111  5771  5771 F libc    : Unable to open connection to debuggerd: Connection refused
,08-11 09:06:21.111  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:21.111  6129  6129 D AndroidRuntime: Shutting down VM
,08-11 09:06:21.111  6129  6129 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x715f9400 in tid 6129 (.apps.magazines)
,08-11 09:06:21.111  6129  6129 F libc    : Unable to open connection to debuggerd: Connection refused
,08-11 09:06:21.111  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:21.131  2206  2206 D BluetoothA2dp: Proxy object disconnected
,08-11 09:06:21.131  5189  5189 D BluetoothMap: Proxy object disconnected
,08-11 09:06:21.131  5189  5189 D MapProfile: Bluetooth service disconnected
,08-11 09:06:21.131  5189  5189 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9832bd in tid 5189 (ndroid.settings),
,08-11 09:06:21.131  5189  5189 F libc    : Unable to open connection to debuggerd: Connection refused
,08-11 09:06:21.131  2176  2176 E audit_log: File locking failed. error= Bad file descriptor
,08-11 09:06:21.171   353   353 I Zygote  : Process 6129 exited due to signal (7)
08-11 09:06:21.171   353  6868 I Zygote  : Process 5771 exited due to signal (7)
,08-11 09:06:21.201   353   353 I Zygote  : Process 2170 exited due to signal (7)
,08-11 09:06:21.201   353   353 I Zygote  : Process 5189 exited due to signal (7)
,08-11 09:06:21.331   291   291 I lowmemorykiller: ActivityManager disconnected
08-11 09:06:21.331   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-11 09:06:21.331   293   540 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-11 09:06:21.331   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-11 09:06:21.591   293   540 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 09:06:21.591   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-11 09:06:21.591   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9633a4
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9633a4
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe96338c
,08-11 09:06:21.601   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9633a4

```
