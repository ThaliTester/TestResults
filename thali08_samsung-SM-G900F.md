#### Test 794266502283b5d_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
,08-04 11:16:09.803   755  3427 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
08-04 11:16:09.864   755  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
08-04 11:16:10.813  2223  2223 E audit   : type=1400 msg=audit(1470302170.803:284): avc:  denied  { execmod } for  pid=7187 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-04 11:16:10.813  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:10.813  2223  2223 E audit   : type=1300 msg=audit(1470302170.803:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f63000 a1=51000 a2=5 a3=4 items=0 ppid=3562 ppcomm=adbd pid=7187 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-04 11:16:10.813  2223  2223 E audit   : type=1327 msg=audit(1470302170.803:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-04 11:16:10.813  2223  2223 E audit   : type=1320 msg=audit(1470302170.803:284): 
08-04 11:16:10.873  2223  2223 E audit   : type=1400 msg=audit(1470302170.863:285): avc:  denied  { execmod } for  pid=7187 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-04 11:16:10.873  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:10.873  2223  2223 E audit   : type=1300 msg=audit(1470302170.863:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f23000 a1=51000 a2=5 a3=4 items=0 ppid=3562 ppcomm=adbd pid=7187 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-04 11:16:10.873  2223  2223 E audit   : type=1327 msg=audit(1470302170.863:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-04 11:16:10.873  2223  2223 E audit   : type=1320 msg=audit(1470302170.863:285): 
08-04 11:16:10.923  2223  2223 E audit   : type=1400 msg=audit(1470302170.923:286): avc:  denied  { execmod } for  pid=7187 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-04 11:16:10.923  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:10.923  2223  2223 E audit   : type=1300 msg=audit(1470302170.923:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f23000 a1=51000 a2=5 a3=4 items=0 ppid=3562 ppcomm=adbd pid=7187 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-04 11:16:10.923  2223  2223 E audit   : type=1327 msg=audit(1470302170.923:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-04 11:16:10.923  2223  2223 E audit   : type=1320 msg=audit(1470302170.923:286): 
08-04 11:16:10.923  7187  7187 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 11:16:10.933  7187  7187 D AndroidRuntime: CheckJNI is OFF
08-04 11:16:10.933  7187  7187 D AndroidRuntime: readGMSProperty: start
08-04 11:16:10.933  7187  7187 D AndroidRuntime: readGMSProperty: already setted!!
08-04 11:16:10.933  7187  7187 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-04 11:16:10.933  7187  7187 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-04 11:16:10.933  7187  7187 D AndroidRuntime: readGMSProperty: end
08-04 11:16:10.933  7187  7187 D AndroidRuntime: addProductProperty: start
08-04 11:16:10.943  7187  7187 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-04 11:16:10.943  7187  7187 W art     : aed8a000-b1cb0000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-04 11:16:10.943  7187  7187 W art     : b1cb0000-b3f1f000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-04 11:16:10.943  7187  7187 W art     : b3f1f000-b3f20000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-04 11:16:10.943  7187  7187 W art     : b3f20000-b3f21000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.943  7187  7187 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-04 11:16:10.943  7187  7187 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-04 11:16:10.943  7187  7187 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-04 11:16:10.943  7187  7187 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-04 11:16:10.943  7187  7187 W art     : b47cb000-b47f4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-04 11:16:10.943  7187  7187 W art     : b47f4000-b47f7000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-04 11:16:10.943  7187  7187 W art     : b47f7000-b47f8000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-04 11:16:10.943  7187  7187 W art     : b47f8000-b47f9000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-04 11:16:10.943  7187  7187 W art     : b47f9000-b47fa000 r--p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b47fa000-b481a000 r--s 00000000 00:0b 8244       /dev/__properties__
08-04 11:16:10.943  7187  7187 W art     : b481a000-b522b000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-04 11:16:10.943  7187  7187 W art     : b522b000-b522c000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b522c000-b5275000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-04 11:16:10.943  7187  7187 W art     : b5275000-b5276000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-04 11:16:10.943  7187  7187 W art     : b5276000-b527e000 rw-p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b527e000-b527f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.943  7187  7187 W art     : b527f000-b52b4000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-04 11:16:10.943  7187  7187 W art     : b52b4000-b52b5000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b52b5000-b52b6000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-04 11:16:10.943  7187  7187 W art     : b52b6000-b52b7000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-04 11:16:10.943  7187  7187 W art     : b52b7000-b530f000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-04 11:16:10.943  7187  7187 W art     : b530f000-b5310000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b5310000-b5311000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-04 11:16:10.943  7187  7187 W art     : b5311000-b5312000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-04 11:16:10.943  7187  7187 W art     : b5313000-b5319000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-04 11:16:10.943  7187  7187 W art     : b5319000-b531a000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-04 11:16:10.943  7187  7187 W art     : b531a000-b531b000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-04 11:16:10.943  7187  7187 W art     : b531b000-b531d000 rw-p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b531e000-b5328000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-04 11:16:10.943  7187  7187 W art     : b5328000-b532b000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-04 11:16:10.943  7187  7187 W art     : b532b000-b532c000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-04 11:16:10.943  7187  7187 W art     : b532d000-b5344000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-04 11:16:10.943  7187  7187 W art     : b5344000-b5345000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b5345000-b5346000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-04 11:16:10.943  7187  7187 W art     : b5346000-b5347000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-04 11:16:10.943  7187  7187 W art     : b5348000-b5352000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-04 11:16:10.943  7187  7187 W art     : b5352000-b5353000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-04 11:16:10.943  7187  7187 W art     : b5353000-b5354000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-04 11:16:10.943  7187  7187 W art     : b5354000-b5358000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-04 11:16:10.943  7187  7187 W art     : b5358000-b5359000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-04 11:16:10.943  7187  7187 W art     : b5359000-b535a000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-04 11:16:10.943  7187  7187 W art     : b535a000-b5370000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-04 11:16:10.943  7187  7187 W art     : b5370000-b5371000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-04 11:16:10.943  7187  7187 W art     : b5371000-b5372000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-04 11:16:10.943  7187  7187 W art     : b5372000-b537f000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-04 11:16:10.943  7187  7187 W art     : b537f000-b5380000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-04 11:16:10.943  7187  7187 W art     : b5380000-b5381000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-04 11:16:10.943  7187  7187 W art     : b5381000-b53e1000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-04 11:16:10.943  7187  7187 W art     : b53e1000-b53e4000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-04 11:16:10.943  7187  7187 W art     : b53e4000-b53e8000 rw-p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b53e8000-b5449000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-04 11:16:10.943  7187  7187 W art     : b5449000-b544a000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-04 11:16:10.943  7187  7187 W art     : b544a000-b5499000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-04 11:16:10.943  7187  7187 W art     : b5499000-b549b000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-04 11:16:10.943  7187  7187 W art     : b549b000-b549c000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-04 11:16:10.943  7187  7187 W art     : b549c000-b549d000 rw-p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b549d000-b54a4000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-04 11:16:10.943  7187  7187 W art     : b54a4000-b54a5000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-04 11:16:10.943  7187  7187 W art     : b54a5000-b54a6000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-04 11:16:10.943  7187  7187 W art     : avc_common.so
08-04 11:16:10.943  7187  7187 W art     : b54a7000-b54aa000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-04 11:16:10.943  7187  7187 W art     : b54aa000-b54ab000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-04 11:16:10.943  7187  7187 W art     : b54ab000-b54ac000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-04 11:16:10.943  7187  7187 W art     : enc_common.so
08-04 11:16:10.943  7187  7187 W art     : b54ad000-b54b1000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-04 11:16:10.943  7187  7187 W art     : b54b1000-b54b2000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b54b2000-b54b3000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-04 11:16:10.943  7187  7187 W art     : b54b3000-b54b4000 rw-p 00005000 b3:17 2510       /syste
08-04 11:16:10.943  7187  7187 W art     : m/lib/libpowermanager.so
08-04 11:16:10.943  7187  7187 W art     : b54b5000-b54d2000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-04 11:16:10.943  7187  7187 W art     : b54d2000-b54d3000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-04 11:16:10.943  7187  7187 W art     : b54d3000-b54d4000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-04 11:16:10.943  7187  7187 W art     : b54d5000-b54da000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-04 11:16:10.943  7187  7187 W art     : b54da000-b54db000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-04 11:16:10.943  7187  7187 W art     : b54db000-b54dc000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-04 11:16:10.943  7187  7187 W art     : b54dd000-b550e000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-04 11:16:10.943  7187  7187 W art     : b550e000-b5511000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-04 11:16:10.943  7187  7187 W art     : b5511000-b5512000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-04 11:16:10.943  7187  7187 W art     : b5513000-b554e000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-04 11:16:10.943  7187  7187 W art     : b554e000-b554f000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-04 11:16:10.943  7187  7187 W art     : b554f000-b5550000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-04 11:16:10.943  7187  7187 W art     : b5551000-b5558000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-04 11:16:10.943  7187  7187 W art     : b5558000-b5559000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b5559000-b555a000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-04 11:16:10.943  7187  7187 W art     : b555a000-b555b000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-04 11:16:10.943  7187  7187 W art     : b555b000-b555c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.943  7187  7187 W art     : b555c000-b5573000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-04 11:16:10.943  7187  7187 W art     : b5573000-b5574000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b5574000-b5577000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-04 11:16:10.943  7187  7187 W art     : b5577000-b5578000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-04 11:16:10.943  7187  7187 W art     : b5578000-b5597000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-04 11:16:10.943  7187  7187 W art     : b5597000-b5598000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-04 11:16:10.943  7187  7187 W art     : b5598000-b5599000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-04 11:16:10.943  7187  7187 W art     : b5599000-b55d7000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-04 11:16:10.943  7187  7187 W art     : b55d7000-b55d8000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b55d8000-b55da000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-04 11:16:10.943  7187  7187 W art     : b55da000-b55db000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-04 11:16:10.943  7187  7187 W art     : b55dc000-b55e3000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-04 11:16:10.943  7187  7187 W art     : b55e3000-b55e4000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-04 11:16:10.943  7187  7187 W art     : b55e4000-b55e5000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-04 11:16:10.943  7187  7187 W art     : b55e6000-b55e9000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-04 11:16:10.943  7187  7187 W art     : b55e9000-b55ea000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-04 11:16:10.943  7187  7187 W art     : b55ea000-b55eb000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-04 11:16:10.943  7187  7187 W art     : b55eb000-b55f1000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-04 11:16:10.943  7187  7187 W art     : b55f1000-b55f2000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b55f2000-b55f3000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-04 11:16:10.943  7187  7187 W art     : b55f3000-b55f4000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-04 11:16:10.943  7187  7187 W art     : b55f4000-b55fd000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-04 11:16:10.943  7187  7187 W art     : b55fd000-b55fe000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-04 11:16:10.943  7187  7187 W art     : b55fe000-b55ff000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-04 11:16:10.943  7187  7187 W art     : b55ff000-b5690000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-04 11:16:10.943  7187  7187 W art     : b5690000-b5691000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b5691000-b569c000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-04 11:16:10.943  7187  7187 W art     : b569c000-b569d000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-04 11:16:10.943  7187  7187 W art     : b569e000-b56b0000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-04 11:16:10.943  7187  7187 W art     : b56b0000-b56b1000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-04 11:16:10.943  7187  7187 W art     : b56b1000-b56b2000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-04 11:16:10.943  7187  7187 W art     : b56b3000-b56b8000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-04 11:16:10.943  7187  7187 W art     : b56b8000-b56b9000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-04 11:16:10.943  7187  7187 W art     : b56b9000-b56ba000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-04 11:16:10.943  7187  7187 W art     : b56bb000-b5728000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-04 11:16:10.943  7187  7187 W art     : b5728000-b5729000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b5729000-b572b000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-04 11:16:10.943  7187  7187 W art     : b572b000-b572c000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-04 11:16:10.943  7187  7187 W art     : b572c000-b572d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.943  7187  7187 W art     : b572d000-b5734000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-04 11:16:10.943  7187  7187 W art     : b5734000-b5735000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-04 11:16:10.943  7187  7187 W art     : b5735000-b5736000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-04 11:16:10.943  7187  7187 W art     : b5737000-b57b7000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-04 11:16:10.943  7187  7187 W art     : b57b7000-b57b8000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b57b8000-b57b9000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-04 11:16:10.943  7187  7187 W art     : b57b9000-b57ba000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-04 11:16:10.943  7187  7187 W art     : b57ba000-b57d1000 rw-p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b57d1000-b5808000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-04 11:16:10.943  7187  7187 W art     : ib/libqc-opt.so
08-04 11:16:10.943  7187  7187 W art     : b5808000-b5809000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-04 11:16:10.943  7187  7187 W art     : b5809000-b580a000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-04 11:16:10.943  7187  7187 W art     : b580a000-b5826000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-04 11:16:10.943  7187  7187 W art     : b5826000-b5827000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-04 11:16:10.943  7187  7187 W art     : b5827000-b5828000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-04 11:16:10.943  7187  7187 W art     : b5829000-b588a000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-04 11:16:10.943  7187  7187 W art     : b588a000-b588c000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-04 11:16:10.943  7187  7187 W art     : b588c000-b588d000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-04 11:16:10.943  7187  7187 W art     : b588e000-b58b5000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-04 11:16:10.943  7187  7187 W art     : b58b5000-b58b6000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b58b6000-b58b7000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-04 11:16:10.943  7187  7187 W art     : b58b7000-b58b8000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-04 11:16:10.943  7187  7187 W art     : b58b9000-b58c1000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-04 11:16:10.943  7187  7187 W art     : b58c1000-b58c3000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-04 11:16:10.943  7187  7187 W art     : b58c3000-b58c4000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-04 11:16:10.943  7187  7187 W art     : b58c5000-b58c8000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-04 11:16:10.943  7187  7187 W art     : b58c8000-b58c9000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-04 11:16:10.943  7187  7187 W art     : b58c9000-b58ca000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-04 11:16:10.943  7187  7187 W art     : b58ca000-b58ce000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-04 11:16:10.943  7187  7187 W art     : b58ce000-b58cf000 ---p 00000000 00:00 0 
08-04 11:16:10.943  7187  7187 W art     : b58cf000-b58d0000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-04 11:16:10.943  7187  7187 W art     : b58d0000-b58d1000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-04 11:16:10.943  7187  7187 W art     : b58d1000-b58e1000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-04 11:16:10.953  7187  7187 W art     : b58e1000-b58e2000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-04 11:16:10.953  7187  7187 W art     : b58e2000-b58e3000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-04 11:16:10.953  7187  7187 W art     : b58e3000-b5929000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5929000-b5932000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-04 11:16:10.953  7187  7187 W art     : b5932000-b5933000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-04 11:16:10.953  7187  7187 W art     : b5933000-b5934000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-04 11:16:10.953  7187  7187 W art     : b5935000-b593a000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-04 11:16:10.953  7187  7187 W art     : b593a000-b593b000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-04 11:16:10.953  7187  7187 W art     : b593b000-b593c000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-04 11:16:10.953  7187  7187 W art     : b593c000-b593f000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-04 11:16:10.953  7187  7187 W art     : b593f000-b5940000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5940000-b5941000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-04 11:16:10.953  7187  7187 W art     : b5941000-b5942000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-04 11:16:10.953  7187  7187 W art     : b5943000-b595b000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-04 11:16:10.953  7187  7187 W art     : b595b000-b595c000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b595c000-b595d000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-04 11:16:10.953  7187  7187 W art     : b595d000-b595e000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-04 11:16:10.953  7187  7187 W art     : b595f000-b5af9000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-04 11:16:10.953  7187  7187 W art     : b5af9000-b5afa000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5afa000-b5b07000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-04 11:16:10.953  7187  7187 W art     : b5b07000-b5b08000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-04 11:16:10.953  7187  7187 W art     : b5b08000-b5b0c000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-04 11:16:10.953  7187  7187 W art     : b5b0c000-b5b0d000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5b0d000-b5b0e000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-04 11:16:10.953  7187  7187 W art     : b5b0e000-b5b0f000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-04 11:16:10.953  7187  7187 W art     : b5b0f000-b5b22000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-04 11:16:10.953  7187  7187 W art     : b5b22000-b5b23000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-04 11:16:10.953  7187  7187 W art     : b5b23000-b5b24000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-04 11:16:10.953  7187  7187 W art     : b5b24000-b5b25000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:10.953  7187  7187 W art     : b5b25000-b5b70000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-04 11:16:10.953  7187  7187 W art     : b5b70000-b5b71000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-04 11:16:10.953  7187  7187 W art     : b5b71000-b5b72000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-04 11:16:10.953  7187  7187 W art     : b5b72000-b5b74000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5b75000-b5b86000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-04 11:16:10.953  7187  7187 W art     : b5b86000-b5b87000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5b87000-b5b88000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-04 11:16:10.953  7187  7187 W art     : b5b88000-b5b89000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-04 11:16:10.953  7187  7187 W art     : b5b8a000-b5b94000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-04 11:16:10.953  7187  7187 W art     : b5b94000-b5b96000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-04 11:16:10.953  7187  7187 W art     : b5b96000-b5b97000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-04 11:16:10.953  7187  7187 W art     : b5b97000-b5bb0000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-04 11:16:10.953  7187  7187 W art     : b5bb0000-b5bb1000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-04 11:16:10.953  7187  7187 W art     : b5bb1000-b5bb4000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-04 11:16:10.953  7187  7187 W art     : b5bb4000-b5bb8000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5bb8000-b5c2c000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-04 11:16:10.953  7187  7187 W art     : b5c2c000-b5c2d000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5c2d000-b5c30000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-04 11:16:10.953  7187  7187 W art     : b5c30000-b5c31000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-04 11:16:10.953  7187  7187 W art     : b5c31000-b5c32000 r--p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5c32000-b5c35000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-04 11:16:10.953  7187  7187 W art     : b5c35000-b5c36000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-04 11:16:10.953  7187  7187 W art     : b5c36000-b5c37000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-04 11:16:10.953  7187  7187 W art     : b5c37000-b5c38000 r--p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5c38000-b5c3d000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-04 11:16:10.953  7187  7187 W art     : b5c3d000-b5c3e000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-04 11:16:10.953  7187  7187 W art     : b5c3e000-b5c3f000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-04 11:16:10.953  7187  7187 W art     : b5c3f000-b5c40000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b5c40000-b5c43000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-04 11:16:10.953  7187  7187 W art     : b5c43000-b5c44000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-04 11:16:10.953  7187  7187 W art     : b5c44000-b5c45000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-04 11:16:10.953  7187  7187 W art     : b5c45000-b5c46000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b5c46000-b5c4a000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-04 11:16:10.953  7187  7187 W art     : b5c4a000-b5c4b000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-04 11:16:10.953  7187  7187 W art     : b5c4b000-b5c4c000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-04 11:16:10.953  7187  7187 W art     : b5c4c000-b5c4d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:10.953  7187  7187 W art     : b5c4d000-b5c51000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-04 11:16:10.953  7187  7187 W art     : b5c51000-b5c52000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-04 11:16:10.953  7187  7187 W art     : b5c52000-b5c53000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-04 11:16:10.953  7187  7187 W art     : b5c53000-b5c54000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b5c54000-b5c62000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-04 11:16:10.953  7187  7187 W art     : b5c62000-b5c63000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b5c63000-b5c64000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-04 11:16:10.953  7187  7187 W art     : b5c64000-b5c65000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-04 11:16:10.953  7187  7187 W art     : b5c65000-b5c6f000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-04 11:16:10.953  7187  7187 W art     : b5c6f000-b5c72000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-04 11:16:10.953  7187  7187 W art     : b5c72000-b5c73000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-04 11:16:10.953  7187  7187 W art     : b5c73000-b5c74000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b5c74000-b5c7e000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-04 11:16:10.953  7187  7187 W art     : b5c7e000-b5c81000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-04 11:16:10.953  7187  7187 W art     : b5c81000-b5c82000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-04 11:16:10.953  7187  7187 W art     : b5c82000-b5c86000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-04 11:16:10.953  7187  7187 W art     : b5c86000-b5c87000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-04 11:16:10.953  7187  7187 W art     : b5c87000-b5c88000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-04 11:16:10.953  7187  7187 W art     : b5c88000-b5c89000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b5c89000-b5c96000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-04 11:16:10.953  7187  7187 W art     : b5c96000-b5c98000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-04 11:16:10.953  7187  7187 W art     : b5c98000-b5c99000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-04 11:16:10.953  7187  7187 W art     : b5c99000-b60ab000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-04 11:16:10.953  7187  7187 W art     : b60ab000-b60ac000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b60ac000-b60b5000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-04 11:16:10.953  7187  7187 W art     : b60b5000-b60b9000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-04 11:16:10.953  7187  7187 W art     : b60b9000-b60ba000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b60ba000-b60c1000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-04 11:16:10.953  7187  7187 W art     : b60c1000-b60c2000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-04 11:16:10.953  7187  7187 W art     : b60c2000-b60c3000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-04 11:16:10.953  7187  7187 W art     : b60c3000-b60c4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b60c4000-b60df000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-04 11:16:10.953  7187  7187 W art     : b60df000-b60e0000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-04 11:16:10.953  7187  7187 W art     : b60e0000-b60e1000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-04 11:16:10.953  7187  7187 W art     : b60e1000-b60e2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b60e2000-b612e000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-04 11:16:10.953  7187  7187 W art     : b612e000-b612f000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b612f000-b6130000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-04 11:16:10.953  7187  7187 W art     : b6130000-b6131000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-04 11:16:10.953  7187  7187 W art     : b6131000-b6132000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6132000-b6136000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-04 11:16:10.953  7187  7187 W art     : b6136000-b6137000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6137000-b6138000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-04 11:16:10.953  7187  7187 W art     : b6138000-b6139000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-04 11:16:10.953  7187  7187 W art     : b6139000-b6171000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-04 11:16:10.953  7187  7187 W art     : b6171000-b6172000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-04 11:16:10.953  7187  7187 W art     : b6172000-b6173000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-04 11:16:10.953  7187  7187 W art     : b6173000-b6174000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6174000-b6212000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-04 11:16:10.953  7187  7187 W art     : b6212000-b6213000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6213000-b6231000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-04 11:16:10.953  7187  7187 W art     : b6231000-b6232000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-04 11:16:10.953  7187  7187 W art     : b6232000-b63a5000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-04 11:16:10.953  7187  7187 W art     : b63a5000-b63b0000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-04 11:16:10.953  7187  7187 W art     : b63b0000-b63b1000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-04 11:16:10.953  7187  7187 W art     : b63b1000-b64c8000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-04 11:16:10.953  7187  7187 W art     : b64c8000-b64d3000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-04 11:16:10.953  7187  7187 W art     : b64d3000-b64d4000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-04 11:16:10.953  7187  7187 W art     : b64d4000-b64d8000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b64d8000-b64fc000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-04 11:16:10.953  7187  7187 W art     : b64fc000-b64fe000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-04 11:16:10.953  7187  7187 W art     : b64fe000-b64ff000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-04 11:16:10.953  7187  7187 W art     : b64ff000-b65a5000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-04 11:16:10.953  7187  7187 W art     : b65a5000-b65b2000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-04 11:16:10.953  7187  7187 W art     : b65b2000-b65b3000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-04 11:16:10.953  7187  7187 W art     : b65b3000-b65b4000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b65b4000-b6607000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-04 11:16:10.953  7187  7187 W art     : b6607000-b6608000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6608000-b6609000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-04 11:16:10.953  7187  7187 W art     : b6609000-b660a000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-04 11:16:10.953  7187  7187 W art     : b660a000-b660f000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b660f000-b6621000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-04 11:16:10.953  7187  7187 W art     : b6621000-b6622000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6622000-b6623000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-04 11:16:10.953  7187  7187 W art     : b6623000-b6624000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-04 11:16:10.953  7187  7187 W art     : b6624000-b662b000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-04 11:16:10.953  7187  7187 W art     : b662b000-b662c000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-04 11:16:10.953  7187  7187 W art     : b662c000-b662d000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-04 11:16:10.953  7187  7187 W art     : b662d000-b662e000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b662e000-b6631000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-04 11:16:10.953  7187  7187 W art     : b6631000-b6632000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-04 11:16:10.953  7187  7187 W art     : b6632000-b6633000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-04 11:16:10.953  7187  7187 W art     : b6633000-b6637000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-04 11:16:10.953  7187  7187 W art     : b6637000-b6638000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-04 11:16:10.953  7187  7187 W art     : b6638000-b6639000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-04 11:16:10.953  7187  7187 W art     : b6639000-b6647000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-04 11:16:10.953  7187  7187 W art     : b6647000-b6648000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6648000-b6649000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-04 11:16:10.953  7187  7187 W art     : b6649000-b664a000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-04 11:16:10.953  7187  7187 W art     : b664a000-b6653000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-04 11:16:10.953  7187  7187 W art     : b6653000-b6654000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-04 11:16:10.953  7187  7187 W art     : b6654000-b6655000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-04 11:16:10.953  7187  7187 W art     : b6655000-b66bb000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-04 11:16:10.953  7187  7187 W art     : b66bb000-b66bc000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b66bc000-b66be000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-04 11:16:10.953  7187  7187 W art     : b66be000-b66c7000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-04 11:16:10.953  7187  7187 W art     : b66c7000-b66ca000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b66ca000-b6761000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-04 11:16:10.953  7187  7187 W art     : b6761000-b6763000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-04 11:16:10.953  7187  7187 W art     : b6763000-b6764000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-04 11:16:10.953  7187  7187 W art     : b6764000-b6765000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6765000-b6a86000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-04 11:16:10.953  7187  7187 W art     : b6a86000-b6a87000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6a87000-b6aa2000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-04 11:16:10.953  7187  7187 W art     : b6aa2000-b6aa6000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-04 11:16:10.953  7187  7187 W art     : b6aa6000-b6aab000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6aab000-b6ab3000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-04 11:16:10.953  7187  7187 W art     : b6ab3000-b6ab4000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-04 11:16:10.953  7187  7187 W art     : b6ab4000-b6ab5000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-04 11:16:10.953  7187  7187 W art     : b6ab5000-b6ae3000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-04 11:16:10.953  7187  7187 W art     : b6ae3000-b6ae4000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6ae4000-b6aeb000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-04 11:16:10.953  7187  7187 W art     : b6aeb000-b6aec000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-04 11:16:10.953  7187  7187 W art     : b6aec000-b6b32000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-04 11:16:10.953  7187  7187 W art     : b6b32000-b6b33000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6b33000-b6b36000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-04 11:16:10.953  7187  7187 W art     : b6b36000-b6b37000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-04 11:16:10.953  7187  7187 W art     : b6b37000-b6b52000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-04 11:16:10.953  7187  7187 W art     : b6b52000-b6b56000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-04 11:16:10.953  7187  7187 W art     : b6b56000-b6b57000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-04 11:16:10.953  7187  7187 W art     : b6b57000-b6ba4000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-04 11:16:10.953  7187  7187 W art     : b6ba4000-b6ba5000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6ba5000-b6bb1000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-04 11:16:10.953  7187  7187 W art     : b6bb1000-b6bb2000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-04 11:16:10.953  7187  7187 W art     : b6bb2000-b6bbf000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-04 11:16:10.953  7187  7187 W art     : b6bbf000-b6bc0000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6bc0000-b6bc1000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-04 11:16:10.953  7187  7187 W art     : b6bc1000-b6bc2000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-04 11:16:10.953  7187  7187 W art     : b6bc2000-b6bca000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-04 11:16:10.953  7187  7187 W art     : b6bca000-b6bcb000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6bcb000-b6bcc000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-04 11:16:10.953  7187  7187 W art     : b6bcc000-b6bcd000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-04 11:16:10.953  7187  7187 W art     : b6bcd000-b6bd4000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-04 11:16:10.953  7187  7187 W art     : b6bd4000-b6bd5000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-04 11:16:10.953  7187  7187 W art     : b6bd5000-b6bd6000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-04 11:16:10.953  7187  7187 W art     : b6bd6000-b6bea000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-04 11:16:10.953  7187  7187 W art     : b6bea000-b6bec000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-04 11:16:10.953  7187  7187 W art     : b6bec000-b6bed000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-04 11:16:10.953  7187  7187 W art     : b6bed000-b6c15000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-04 11:16:10.953  7187  7187 W art     : b6c15000-b6c17000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-04 11:16:10.953  7187  7187 W art     : b6c17000-b6c18000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-04 11:16:10.953  7187  7187 W art     : b6c18000-b6c1b000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-04 11:16:10.953  7187  7187 W art     : b6c1b000-b6c1c000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-04 11:16:10.953  7187  7187 W art     : b6c1c000-b6c1d000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-04 11:16:10.953  7187  7187 W art     : b6c1d000-b6c26000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-04 11:16:10.953  7187  7187 W art     : b6c26000-b6c27000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-04 11:16:10.953  7187  7187 W art     : b6c27000-b6c28000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-04 11:16:10.953  7187  7187 W art     : b6c28000-b6c48000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-04 11:16:10.953  7187  7187 W art     : b6c48000-b6c49000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-04 11:16:10.953  7187  7187 W art     : b6c49000-b6c4a000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-04 11:16:10.953  7187  7187 W art     : b6c4a000-b6cbd000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-04 11:16:10.953  7187  7187 W art     : b6cbd000-b6cc1000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-04 11:16:10.953  7187  7187 W art     : b6cc1000-b6cc4000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-04 11:16:10.953  7187  7187 W art     : b6cc4000-b6cce000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6cce000-b6d56000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-04 11:16:10.953  7187  7187 W art     : b6d56000-b6d57000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6d57000-b6d5b000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-04 11:16:10.953  7187  7187 W art     : b6d5b000-b6d5c000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-04 11:16:10.953  7187  7187 W art     : b6d5c000-b6d5d000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6d5d000-b6d86000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-04 11:16:10.953  7187  7187 W art     : b6d86000-b6d87000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6d87000-b6d8a000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-04 11:16:10.953  7187  7187 W art     : b6d8a000-b6d8b000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-04 11:16:10.953  7187  7187 W art     : b6d8b000-b6e65000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-04 11:16:10.953  7187  7187 W art     : b6e65000-b6e6c000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-04 11:16:10.953  7187  7187 W art     : b6e6c000-b6e74000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-04 11:16:10.953  7187  7187 W art     : b6e74000-b6e75000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6e75000-b6e76000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:10.953  7187  7187 W art     : b6e76000-b6e77000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-04 11:16:10.953  7187  7187 W art     : b6e77000-b6e78000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6e78000-b6e7b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6e7b000-b6ea0000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-04 11:16:10.953  7187  7187 W art     : b6ea0000-b6ea1000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6ea1000-b6ea8000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-04 11:16:10.953  7187  7187 W art     : b6ea8000-b6ea9000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-04 11:16:10.953  7187  7187 W art     : b6ea9000-b6eb0000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-04 11:16:10.953  7187  7187 W art     : b6eb0000-b6eb1000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-04 11:16:10.953  7187  7187 W art     : b6eb1000-b6eb2000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-04 11:16:10.953  7187  7187 W art     : b6eb2000-b6eb3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6eb3000-b6ecb000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-04 11:16:10.953  7187  7187 W art     : b6ecb000-b6ecc000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6ecc000-b6ecd000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-04 11:16:10.953  7187  7187 W art     : b6ecd000-b6ece000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-04 11:16:10.953  7187  7187 W art     : b6ece000-b6edc000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-04 11:16:10.953  7187  7187 W art     : b6edc000-b6edd000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6edd000-b6ede000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-04 11:16:10.953  7187  7187 W art     : b6ede000-b6edf000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-04 11:16:10.953  7187  7187 W art     : b6edf000-b6ee0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:10.953  7187  7187 W art     : b6ee0000-b6ee2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6ee2000-b6ee3000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6ee3000-b6ee4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:10.953  7187  7187 W art     : b6ee4000-b6ee5000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-04 11:16:10.953  7187  7187 W art     : b6ee5000-b6ee6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:10.953  7187  7187 W art     : b6ee6000-b6f06000 r--s 00000000 00:0b 8244       /dev/__properties__
08-04 11:16:10.953  7187  7187 W art     : b6f06000-b6f07000 r--p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6f07000-b6f08000 ---p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6f08000-b6f0a000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-04 11:16:10.953  7187  7187 W art     : b6f0a000-b6f0b000 r-xp 00000000 00:00 0          [sigpage]
08-04 11:16:10.953  7187  7187 W art     : b6f0b000-b6f26000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-04 11:16:10.953  7187  7187 W art     : b6f26000-b6f27000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-04 11:16:10.953  7187  7187 W art     : b6f27000-b6f29000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-04 11:16:10.953  7187  7187 W art     : b6f29000-b6f2b000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : b6f2b000-b6f30000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-04 11:16:10.953  7187  7187 W art     : b6f30000-b6f31000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-04 11:16:10.953  7187  7187 W art     : b6f31000-b6f32000 rw-p 00000000 00:00 0 
08-04 11:16:10.953  7187  7187 W art     : be90b000-be92c000 rw-p 00000000 00:00 0          [stack]
08-04 11:16:10.953  7187  7187 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-04 11:16:11.003  7187  7187 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 11:16:11.063  7187  7187 I Radio-JNI: register_android_hardware_Radio DONE
08-04 11:16:11.073  7187  7187 E AffinityControl: AffinityControl: registerfunction enter
08-04 11:16:11.083  7187  7187 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 11:16:11.093   755  1544 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-04 11:16:11.113   755  1544 D ActivityManager: mDVFSHelper.acquire()
08-04 11:16:11.113   755  1544 V WindowManager: addAppToken: AppWindowToken{6b49b85 token=Token{59918fc ActivityRecord{1e9d5ef u0 com.test.thalitest/.MainActivity t115}}} to stack=1 task=115 at 0
08-04 11:16:11.123   755   894 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{aafb63d V.E...... R.....ID 0,0-0,0}
08-04 11:16:11.123   755   894 D SecWifiDisplayUtil: Metadata value : none
08-04 11:16:11.123   755   894 D ISSUE_DEBUG: InputChannelName : 6288783 Starting com.test.thalitest
08-04 11:16:11.133   755  1544 D InputDispatcher: Focused application set to: xxxx
08-04 11:16:11.133   755  1544 I ActivityManager: Start proc 7202:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-04 11:16:11.133   755  1544 D InputDispatcher: Focus left window: 3664
08-04 11:16:11.133   755   830 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{20d6a8f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-04 11:16:11.133   755  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-04 11:16:11.133  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-04 11:16:11.133  7187  7187 D AndroidRuntime: Shutting down VM
08-04 11:16:11.133  7202  7202 I libpersona: KNOX_SDCARD checking this for 10004
08-04 11:16:11.133  7202  7202 E Zygote  : v2
08-04 11:16:11.133  7202  7202 I libpersona: KNOX_SDCARD not a persona
08-04 11:16:11.133  7202  7202 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-04 11:16:11.133  7202  7202 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:11.133  7202  7202 E Zygote  : accessInfo : 0
08-04 11:16:11.133  7202  7202 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-04 11:16:11.143   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-04 11:16:11.163   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
08-04 11:16:11.163   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:16:11.163   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-04 11:16:11.163   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 11:16:11.163   755   894 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-04 11:16:11.163  7202  7202 D TimaKeyStoreProvider: TimaSignature is unavailable
08-04 11:16:11.163  7202  7202 D ActivityThread: Added TimaKeyStore provider
08-04 11:16:11.173   755  1805 V WindowOrientationListener: setCurrentAppOrientation :-1
08-04 11:16:11.173   755  1805 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-04 11:16:11.173   755   830 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6288783 u0 d0 Starting com.test.thalitest}
08-04 11:16:11.173  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-04 11:16:11.183   755  1805 D ActivityManager:  Launching com.test.thalitest, updated priority
08-04 11:16:11.193   755   827 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-04 11:16:11.203  1745  1888 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-04 11:16:11.203  1745  1745 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-04 11:16:11.223   294   349 I SurfaceFlinger: id=20 Removed VSBConnecti (5/11)
08-04 11:16:11.223   294  1808 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/11)
08-04 11:16:11.223   755   894 V WindowStateAnimator: Finishing drawing window Window{6288783 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-04 11:16:11.223  3664  3664 V ActivityThread: updateVisibility : ActivityRecord{e9e0a25 token=android.os.BinderProxy@b555097 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-04 11:16:11.223   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
08-04 11:16:11.223   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebe2364
08-04 11:16:11.233   294  1808 D libEGL  : eglTerminate EGLDisplay = 0xb169164c
08-04 11:16:11.233   294  1808 D libEGL  : eglTerminate EGLDisplay = 0xb169164c
08-04 11:16:11.233   294   349 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-04 11:16:11.233   294  1296 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-04 11:16:11.243  2332  2347 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-04 11:16:11.243  1745  1745 V ActivityThread: updateVisibility : ActivityRecord{b114847 token=android.os.BinderProxy@99c9ff8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-04 11:16:11.243  1745  1745 D Launcher: onTrimMemory. Level: 20
08-04 11:16:11.243   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
08-04 11:16:11.253   294  1808 D libEGL  : eglTerminate EGLDisplay = 0xb169164c
08-04 11:16:11.263   294   349 I SurfaceFlinger: id=19 Removed VSBConnecti (5/9)
08-04 11:16:11.263   294   349 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/9)
08-04 11:16:11.273   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
,08-04 11:16:11.493   755  1805 I WindowManager: Screenshot max retries 4 of Token{59918fc ActivityRecord{1e9d5ef u0 com.test.thalitest/.MainActivity t115}} appWin=Window{6288783 u0 d0 Starting com.test.thalitest} drawState=4
,08-04 11:16:11.503   755  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-04 11:16:11.513  7202  7202 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-04 11:16:11.523   755  3427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:11.543  7202  7202 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-04 11:16:11.543  7202  7202 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-04 11:16:11.563  7202  7202 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-04 11:16:11.603  7202  7202 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-04 11:16:11.613  7202  7202 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 11:16:11.623  7202  7202 I cr_LibraryLoader: Time to load native libraries: 5 ms (timestamps 2690-2695)
08-04 11:16:11.623  7202  7202 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-04 11:16:11.653  7202  7202 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c7f821}
08-04 11:16:11.653  7202  7202 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-04 11:16:11.653  7202  7225 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-04 11:16:11.653  7202  7202 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 11:16:11.673  7202  7202 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-04 11:16:11.713  7202  7202 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-04 11:16:11.713  7202  7202 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-04 11:16:11.713  7202  7202 I Adreno-EGL: Build Date: 01/28/16 Thu
08-04 11:16:11.713  7202  7202 I Adreno-EGL: Local Branch: ss
08-04 11:16:11.713  7202  7202 I Adreno-EGL: Remote Branch: 
08-04 11:16:11.713  7202  7202 I Adreno-EGL: Local Patches: 
08-04 11:16:11.713  7202  7202 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:16:11.723  7202  7202 D libEGL  : eglInitialize EGLDisplay = 0xbec47dac
,08-04 11:16:11.763   755   767 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-04 11:16:11.763   755   767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-04 11:16:11.833  7202  7202 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-04 11:16:11.853  7202  7202 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 11:16:11.853  7202  7202 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-04 11:16:11.853  7202  7202 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-04 11:16:11.853  7202  7202 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-04 11:16:11.873  7202  7202 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-04 11:16:11.883  7202  7202 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-04 11:16:11.993  7202  7202 D SecWifiDisplayUtil: Metadata value : none
,08-04 11:16:11.993   755   827 W ActivityManager: Activity pause timeout for ActivityRecord{1e9d5ef u0 com.test.thalitest/.MainActivity t115}
,08-04 11:16:12.003  7202  7202 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{707c3e7 I.E...... R.....ID 0,0-0,0}
,08-04 11:16:12.013  7202  7249 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 11:16:12.013   755   767 D ISSUE_DEBUG: InputChannelName : 9a63f4 com.test.thalitest/com.test.thalitest.MainActivity
,08-04 11:16:12.023   755  1743 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-04 11:16:12.023   755  1743 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-04 11:16:12.023   755   755 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:12.023   755   755 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-04 11:16:12.043  7202  7202 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7202
,08-04 11:16:12.043   755  2270 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7202 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:16:12.043   755  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-04 11:16:12.043   755  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 11:16:12.043   755  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-04 11:16:12.043   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:12.053   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:12.053   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:12.053   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-04 11:16:12.053   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:12.053   755  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-04 11:16:12.053   755  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:16:12.063  7202  7225 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-04 11:16:12.063  7202  7202 V ActivityThread: updateVisibility : ActivityRecord{bc42939 token=android.os.BinderProxy@74bfda6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-04 11:16:12.063  7202  7202 D SecWifiDisplayUtil: Metadata value : none
,08-04 11:16:12.073   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-04 11:16:12.093   755  1600 D InputDispatcher: Focus entered window: 7202
,08-04 11:16:12.093   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
,08-04 11:16:12.093   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:16:12.093   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-04 11:16:12.093   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 11:16:12.093  7202  7249 D libEGL  : eglInitialize EGLDisplay = 0x9d7ff7c4
08-04 11:16:12.093  7202  7249 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 11:16:12.153  7202  7202 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-04 11:16:12.153  7202  7202 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-04 11:16:12.163   755  2270 V WindowStateAnimator: Finishing drawing window Window{9a63f4 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-04 11:16:12.163  7202  7202 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-04 11:16:12.163   755   767 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-04 11:16:12.163   755   894 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:12.163   755   755 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:12.173   755   755 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:12.173  7202  7202 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@74bfda6 time:313244
,08-04 11:16:12.183  7202  7202 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-04 11:16:12.183   755   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +685ms (total +1s66ms)
,08-04 11:16:12.183   755   894 D ActivityManager: mDVFSHelper.release()
08-04 11:16:12.183   755   894 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e9d5ef u0 com.test.thalitest/.MainActivity t115} time:313258
,08-04 11:16:12.193   755   894 D ViewRootImpl: #3 mView = null
,08-04 11:16:12.193   294   349 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-04 11:16:12.193   294  1296 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-04 11:16:12.203   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
,08-04 11:16:12.233  7202  7256 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 11:16:12.233  7202  7256 D libEGL  : eglInitialize EGLDisplay = 0x9cd7f3ec
,08-04 11:16:12.293  7202  7202 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7202
,08-04 11:16:12.503   755  3430 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-04 11:16:12.513  7202  7202 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 11:16:12.693  7202  7269 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1675097808
,08-04 11:16:12.693  7202  7269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:16:12.693  7202  7269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:16:12.693  7202  7269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:16:12.693  7202  7269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:16:12.693  7202  7269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-04 11:16:12.693  7202  7269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc71c4 added. We now have 1 listener(s)
,08-04 11:16:12.703  7202  7269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-04 11:16:12.703  7202  7269 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-04 11:16:12.703  7202  7269 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:16:12.703  7202  7269 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 11:16:12.713  7202  7269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd08773 added. We now have 1 listener(s)
08-04 11:16:12.713  7202  7269 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:16:12.713  7202  7269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:16:12.713  7202  7269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-04 11:16:12.713  7202  7269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:16:12.713  7202  7269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 11:16:12.713  7202  7269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-04 11:16:12.723  7202  7269 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:16:12.723  7202  7269 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-04 11:16:12.723  7202  7269 D BluetoothAdapter: STATE_ON
,08-04 11:16:12.723  7202  7269 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:16:12.723  7202  7269 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:16:12.733  7202  7269 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 11:16:12.733  7202  7269 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:16:12.733  7202  7269 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 11:16:12.733  7202  7202 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:16:12.733  7202  7202 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:16:12.763  7202  7202 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 11:16:13.003  1451  1451 D Recents : onTaskStackChanged
,08-04 11:16:13.003  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-04 11:16:14.163   755  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/115_task.xml.bak
,08-04 11:16:14.253  7202  7270 W jxcore-log: Initializing JXcore engine
,08-04 11:16:14.253  7202  7270 W jxcore-log: JXcore engine is ready
,08-04 11:16:14.293   305  1183 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-04 11:16:14.293   305  1183 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-04 11:16:14.293   305  1183 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-04 11:16:14.303  2223  2223 E audit   : type=1400 msg=audit(1470302174.303:287): avc:  denied  { ioctl } for  pid=7270 comm="Thread-995" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-04 11:16:14.303  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-04 11:16:14.303  2223  2223 E audit   : type=1300 msg=audit(1470302174.303:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9ba3f3c8 items=0 ppid=359 ppcomm=main pid=7270 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-995" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-04 11:16:14.303  2223  2223 E audit   : type=1327 msg=audit(1470302174.303:287): proctitle="com.test.thalitest"
08-04 11:16:14.303  2223  2223 E audit   : type=1320 msg=audit(1470302174.303:287): 
,08-04 11:16:14.303  2223  2223 E audit   : type=1400 msg=audit(1470302174.303:288): avc:  denied  { ioctl } for  pid=7270 comm="Thread-995" path="socket:[44113]" dev="sockfs" ino=44113 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-04 11:16:14.303  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-04 11:16:14.303  2223  2223 E audit   : type=1300 msg=audit(1470302174.303:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=1 a3=9ba3f3c8 items=0 ppid=359 ppcomm=main pid=7270 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-995" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-04 11:16:14.303  2223  2223 E audit   : type=1327 msg=audit(1470302174.303:288): proctitle="com.test.thalitest"
08-04 11:16:14.303  2223  2223 E audit   : type=1320 msg=audit(1470302174.303:288): 
,08-04 11:16:14.313  7202  7270 W jxcore-log: Starting JXcore engine
,08-04 11:16:14.403  7202  7270 W jxcore-log: Platform android
08-04 11:16:14.403  7202  7270 W jxcore-log: 
,08-04 11:16:14.403  7202  7270 W jxcore-log: Process ARCH arm
08-04 11:16:14.403  7202  7270 W jxcore-log: 
,08-04 11:16:14.603  7202  7270 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:16:14.603  7202  7270 I jxcore-log: 
,08-04 11:16:14.613  7202  7270 W jxcore-log: JXcore engine is started
,08-04 11:16:14.613   755  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-04 11:16:14.623  7202  7269 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 11:16:14.623  7202  7202 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 11:16:14.623   755  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-04 11:16:14.623   755  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,08-04 11:16:14.623   755  1230 I TLC_TIMA_PKM_initialize: initializing...
,08-04 11:16:14.623   755  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-04 11:16:14.623   755  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-04 11:16:14.623   755  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-04 11:16:14.623   755  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-04 11:16:14.623   755  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-04 11:16:14.623   755  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-04 11:16:14.633   755  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-04 11:16:14.633   755  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-04 11:16:14.633   755  1230 D QSEECOMAPI: : App is not loaded in QSEE
,08-04 11:16:14.643   755  1230 D QSEECOMAPI: : Loaded image: APP id = 3
,08-04 11:16:14.643   755  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-04 11:16:14.653   755  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-04 11:16:16.963   755  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
08-04 11:16:16.963   755  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-04 11:16:16.973   755  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-04 11:16:16.973   755  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-04 11:16:17.543   755  3427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:17.913   755  1744 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 11:16:17.913   755  1744 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-04 11:16:17.913   755  1744 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,08-04 11:16:17.913   755  1744 D BatteryService: stay LED for fully charged
08-04 11:16:17.913   755   755 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-04 11:16:17.923  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-04 11:16:17.923  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-04 11:16:17.923  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
08-04 11:16:17.923   755   755 I MotionRecognitionService: Plugged
08-04 11:16:17.923   755   755 D MotionRecognitionService:   cableConnection= 1
08-04 11:16:17.923   755   755 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-04 11:16:17.923   755   755 D MotionRecognitionService: skip setTransmitPower. 
,08-04 11:16:17.933  2215  2215 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 11:16:17.933  2215  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-04 11:16:17.943  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:16:17.943  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:16:17.943  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:16:19.863   755  3427 D SSRM:n  : SIOP:: AP = 330, PST = 306, CUR = 450, LCD = 0
,08-04 11:16:21.143   755   923 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-04 11:16:21.173   755   923 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-04 11:16:27.943  7202  7270 E jxcore  : Error!: Cannot find module '../thalilogger'
08-04 11:16:27.943  7202  7270 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-04 11:16:27.953  7202  7202 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-04 11:16:27.953  7202  7202 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-04 11:16:27.963   755   768 D InputDispatcher: Focused application set to: xxxx
08-04 11:16:27.973   755   768 I ActivityManager: Killing 6156:com.sec.android.provider.badge/u0a77 (adj 15): DHA:empty #37
,08-04 11:16:27.973  7202  7269 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,08-04 11:16:27.983  7202  7202 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 11:16:27.983  7202  7202 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-04 11:16:27.983  7202  7202 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 11:16:27.983  7202  7202 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:16:27.983  7202  7202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:16:27.983  7202  7202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:16:27.983  7202  7202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc71c4 removed from the list
08-04 11:16:27.983  7202  7202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:16:27.983  7202  7202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd08773 removed from the list
08-04 11:16:27.983  7202  7202 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:16:27.983  7202  7202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-04 11:16:27.983  7202  7202 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 11:16:27.983  7202  7202 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
08-04 11:16:27.983   755  3427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:28.003  7202  7202 D ViewRootImpl: #3 mView = null
08-04 11:16:28.003   294  1296 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
08-04 11:16:28.003   294  1808 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-04 11:16:28.003   755  1429 D InputDispatcher: Focus left window: 7202
,08-04 11:16:28.003   755  1216 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,08-04 11:16:28.013  7202  7202 D cr_Ime  : [ImeAdapter.java:587] detach
,08-04 11:16:28.013   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
,08-04 11:16:28.013   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:16:28.013   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-04 11:16:28.013   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 11:16:28.023  7202  7202 E ViewRootImpl: sendUserActionEvent() mView == null
,08-04 11:16:28.023   755   767 D ActivityManager: mDVFSHelper.acquire()
,08-04 11:16:28.043   755   827 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-04 11:16:28.043   755   767 V WindowOrientationListener: setCurrentAppOrientation :1
08-04 11:16:28.043   755   767 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-04 11:16:28.063   294   294 I SurfaceFlinger: id=23 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-04 11:16:28.063   755   830 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{38d9802 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-04 11:16:28.063  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-04 11:16:28.063   755  1544 D InputDispatcher: Focus entered window: 3664
,08-04 11:16:28.073   755   894 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:755 uid:1000
08-04 11:16:28.073   755   894 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:16:28.073   755   894 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:755 uid:1000
08-04 11:16:28.073   755   894 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 11:16:28.073  1745  1745 D Launcher: onRestart, Launcher: 72573495
,08-04 11:16:28.073   755  1599 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-04 11:16:28.073   755  1599 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-04 11:16:28.073   755   755 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:28.073   755   755 I KnoxTimeoutHandler: Shared devices show user statefalse
08-04 11:16:28.073   755   755 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-04 11:16:28.083  1745  1745 D Launcher: onStart, Launcher: 72573495
08-04 11:16:28.083  1745  1745 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
08-04 11:16:28.083  1745  1745 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-04 11:16:28.083  1745  1745 D Launcher.HomeView: onStart
,08-04 11:16:28.083  1745  1745 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-04 11:16:28.083  1745  1745 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
08-04 11:16:28.083  2332  4040 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-04 11:16:28.083  1745  1745 V ActivityThread: updateVisibility : ActivityRecord{b114847 token=android.os.BinderProxy@99c9ff8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-04 11:16:28.093   755   768 V WindowStateAnimator: Finishing drawing window Window{38d9802 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-04 11:16:28.103   755   894 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:28.103   755   755 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:28.103   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebe2364
,08-04 11:16:28.103   294   294 I SurfaceFlinger: id=24 createSurf (1194x288),1 flag=4, VSBConnecti
,08-04 11:16:28.103   755   894 D ActivityManager: mDVFSHelper.release()
,08-04 11:16:28.103   755   755 I KnoxTimeoutHandler: SD activityfalse
08-04 11:16:28.103   755   894 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ca904c u0 com.samsung.android.MtpApplication/.USBConnection t114} time:329177
,08-04 11:16:28.113   294   294 I SurfaceFlinger: id=25 createSurf (1080x1920),1 flag=4, Mauncher
,08-04 11:16:28.113  3664  3664 V ActivityThread: updateVisibility : ActivityRecord{e9e0a25 token=android.os.BinderProxy@b555097 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-04 11:16:28.133  1745  1745 D Launcher.HomeView: onStop
,08-04 11:16:28.153   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebe2364
,08-04 11:16:28.153   755  1216 V WindowStateAnimator: Finishing drawing window Window{ba4a350 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-04 11:16:28.163  3664  3664 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b555097 time:329230
,08-04 11:16:28.173   755   894 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:28.173   755   755 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:28.173   755   755 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:28.273   755  1544 V WindowStateAnimator: Finishing drawing window Window{20d6a8f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-04 11:16:28.283   755   894 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:28.283   755   755 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-04 11:16:28.283   755   894 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{269f22f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t112} time:329355
08-04 11:16:28.283   755   755 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:28.283   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebe2364
,08-04 11:16:28.873  2223  2223 E audit   : type=1400 msg=audit(1470302188.873:289): avc:  denied  { execmod } for  pid=7300 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-04 11:16:28.873  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:28.873  2223  2223 E audit   : type=1300 msg=audit(1470302188.873:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbe000 a1=51000 a2=5 a3=4 items=0 ppid=3562 ppcomm=adbd pid=7300 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-04 11:16:28.873  2223  2223 E audit   : type=1327 msg=audit(1470302188.873:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-04 11:16:28.873  2223  2223 E audit   : type=1320 msg=audit(1470302188.873:289): 
,08-04 11:16:28.933  2223  2223 E audit   : type=1400 msg=audit(1470302188.933:290): avc:  denied  { execmod } for  pid=7300 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-04 11:16:28.933  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-04 11:16:28.933  2223  2223 E audit   : type=1300 msg=audit(1470302188.933:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f80000 a1=51000 a2=5 a3=4 items=0 ppid=3562 ppcomm=adbd pid=7300 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-04 11:16:28.933  2223  2223 E audit   : type=1327 msg=audit(1470302188.933:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-04 11:16:28.933  2223  2223 E audit   : type=1320 msg=audit(1470302188.933:290): ,
,08-04 11:16:28.973  2223  2223 E audit   : type=1400 msg=audit(1470302188.973:291): avc:  denied  { execmod } for  pid=7300 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-04 11:16:28.983  2223  2223 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-04 11:16:28.983  2223  2223 E audit   : type=1300 msg=audit(1470302188.973:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f80000 a1=51000 a2=5 a3=4 items=0 ppid=3562 ppcomm=adbd pid=7300 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-04 11:16:28.983  2223  2223 E audit   : type=1327 msg=audit(1470302188.973:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-04 11:16:28.983  2223  2223 E audit   : type=1320 msg=audit(1470302188.973:291): 
,08-04 11:16:28.983  7300  7300 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 11:16:28.993  7300  7300 D AndroidRuntime: CheckJNI is OFF
,08-04 11:16:28.993  7300  7300 D AndroidRuntime: readGMSProperty: start
,08-04 11:16:28.993  7300  7300 D AndroidRuntime: readGMSProperty: already setted!!
08-04 11:16:28.993  7300  7300 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-04 11:16:28.993  7300  7300 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-04 11:16:28.993  7300  7300 D AndroidRuntime: readGMSProperty: end
08-04 11:16:28.993  7300  7300 D AndroidRuntime: addProductProperty: start
,08-04 11:16:29.003  7300  7300 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-04 11:16:29.003  7300  7300 W art     : aede5000-b1d0b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-04 11:16:29.003  7300  7300 W art     : b1d0b000-b3f7a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-04 11:16:29.003  7300  7300 W art     : b3f7a000-b3f7b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-04 11:16:29.003  7300  7300 W art     : b3f7b000-b3f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.003  7300  7300 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-04 11:16:29.003  7300  7300 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-04 11:16:29.003  7300  7300 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
,08-04 11:16:29.003  7300  7300 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-04 11:16:29.003  7300  7300 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-04 11:16:29.003  7300  7300 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-04 11:16:29.003  7300  7300 W art     : b484d000-b4850000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-04 11:16:29.003  7300  7300 W art     : b4850000-b4851000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-04 11:16:29.003  7300  7300 W art     : b4851000-b4852000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-04 11:16:29.003  7300  7300 W art     : b4852000-b4853000 r--p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b4853000-b4873000 r--s 00000000 00:0b 8244       /dev/__properties__
08-04 11:16:29.003  7300  7300 W art     : b4873000-b5284000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-04 11:16:29.003  7300  7300 W art     : b5284000-b5285000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b5285000-b52ce000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-04 11:16:29.003  7300  7300 W art     : b52ce000-b52cf000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-04 11:16:29.003  7300  7300 W art     : b52cf000-b52d7000 rw-p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b52d7000-b52d8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.003  7300  7300 W art     : b52d8000-b530d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-04 11:16:29.003  7300  7300 W art     : b530d000-b530e000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b530e000-b530f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-04 11:16:29.003  7300  7300 W art     : b530f000-b5310000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-04 11:16:29.003  7300  7300 W art     : b5310000-b5368000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-04 11:16:29.003  7300  7300 W art     : b5368000-b5369000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b5369000-b536a000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-04 11:16:29.003  7300  7300 W art     : b536a000-b536b000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-04 11:16:29.003  7300  7300 W art     : b536c000-b5372000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-04 11:16:29.003  7300  7300 W art     : b5372000-b5373000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-04 11:16:29.003  7300  7300 W art     : b5373000-b5374000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-04 11:16:29.003  7300  7300 W art     : b5374000-b5376000 rw-p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b5377000-b5381000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-04 11:16:29.003  7300  7300 W art     : b5381000-b5384000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-04 11:16:29.003  7300  7300 W art     : b5384000-b5385000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-04 11:16:29.003  7300  7300 W art     : b5386000-b539d000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-04 11:16:29.003  7300  7300 W art     : b539d000-b539e000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b539e000-b539f000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-04 11:16:29.003  7300  7300 W art     : b539f000-b53a0000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-04 11:16:29.003  7300  7300 W art     : b53a1000-b53ab000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
,08-04 11:16:29.003  7300  7300 W art     : b53ab000-b53ac000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-04 11:16:29.003  7300  7300 W art     : b53ac000-b53ad000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-04 11:16:29.003  7300  7300 W art     : b53ad000-b53b1000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-04 11:16:29.003  7300  7300 W art     : b53b1000-b53b2000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-04 11:16:29.003  7300  7300 W art     : b53b2000-b53b3000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-04 11:16:29.003  7300  7300 W art     : b53b3000-b53c9000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-04 11:16:29.003  7300  7300 W art     : b53c9000-b53ca000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-04 11:16:29.003  7300  7300 W art     : b53ca000-b53cb000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-04 11:16:29.003  7300  7300 W art     : b53cb000-b53d8000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-04 11:16:29.003  7300  7300 W art     : b53d8000-b53d9000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-04 11:16:29.003  7300  7300 W art     : b53d9000-b53da000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-04 11:16:29.003  7300  7300 W art     : b53da000-b543a000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-04 11:16:29.003  7300  7300 W art     : b543a000-b543d000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-04 11:16:29.003  7300  7300 W art     : b543d000-b5441000 rw-p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b5441000-b54a2000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-04 11:16:29.003  7300  7300 W art     : b54a2000-b54a3000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-04 11:16:29.003  7300  7300 W art     : b54a3000-b54f2000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-04 11:16:29.003  7300  7300 W art     : b54f2000-b54f4000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-04 11:16:29.003  7300  7300 W art     : b54f4000-b54f5000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-04 11:16:29.003  7300  7300 W art     : b54f5000-b54f6000 rw-p 00000000 00:00 0 ,
08-04 11:16:29.003  7300  7300 W art     : b54f6000-b54fd000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-04 11:16:29.003  7300  7300 W art     : b54fd000-b54fe000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-04 11:16:29.003  7300  7300 W art     : b54fe000-b54ff000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-04 11:16:29.003  7300  7300 W art     : b5500000-b5503000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-04 11:16:29.003  7300  7300 W art     : b5503000-b5504000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-04 11:16:29.003  7300  7300 W art     : b5504000-b5505000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-04 11:16:29.003  7300  7300 W art     : b5506000-b550a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
,08-04 11:16:29.003  7300  7300 W art     : b550a000-b550b000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b550b000-b550c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so,
08-04 11:16:29.003  7300  7300 W art     : b550c000-b550d000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-04 11:16:29.003  7300  7300 W art     : b550e000-b552b000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so,
08-04 11:16:29.003  7300  7300 W art     : b552b000-b552c000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
,08-04 11:16:29.003  7300  7300 W art     : b552c000-b552d000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-04 11:16:29.003  7300  7300 W art     : b552e000-b5533000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-04 11:16:29.003  7300  7300 W art     : b5533000-b5534000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-04 11:16:29.003  7300  7300 W art     : b5534000-b5535000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so,
08-04 11:16:29.003  7300  7300 W art     : b5536000-b5567000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-04 11:16:29.003  7300  7300 W art     : b5567000-b556a000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so,
08-04 11:16:29.003  7300  7300 W art     : b556a000-b556b000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-04 11:16:29.003  7300  7300 W art     : b556c000-b55a7000 r-xp 00000000 b3:17 893        /system/lib/libopus.so,
08-04 11:16:29.003  7300  7300 W art     : b55a7000-b55a8000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-04 11:16:29.003  7300  7300 W art     : b55a8000-b55a9000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-04 11:16:29.003  7300  7300 W art     : b55aa000-b55b1000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-04 11:16:29.003  7300  7300 W art     : b55b1000-b55b2000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b55b2000-b55b3000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so,
08-04 11:16:29.003  7300  7300 W art     : b55b3000-b55b4000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-04 11:16:29.003  7300  7300 W art     : b55b4000-b55b5000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-04 11:16:29.003  7300  7300 W art     : b55b5000-b55cc000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-04 11:16:29.003  7300  7300 W art     : b55cc000-b55cd000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b55cd000-b55d0000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so,
08-04 11:16:29.003  7300  7300 W art     : b55d0000-b55d1000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-04 11:16:29.003  7300  7300 W art     : b55d1000-b55f0000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
,08-04 11:16:29.003  7300  7300 W art     : b55f0000-b55f1000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-04 11:16:29.003  7300  7300 W art     : b55f1000-b55f2000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-04 11:16:29.003  7300  7300 W art     : b55f2000-b5630000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so,
08-04 11:16:29.003  7300  7300 W art     : b5630000-b5631000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b5631000-b5633000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
,08-04 11:16:29.003  7300  7300 W art     : b5633000-b5634000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
,08-04 11:16:29.003  7300  7300 W art     : b5635000-b563c000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
,08-04 11:16:29.003  7300  7300 W art     : b563c000-b563d000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
,08-04 11:16:29.003  7300  7300 W art     : b563d000-b563e000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
,08-04 11:16:29.003  7300  7300 W art     : b563f000-b5642000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so,
08-04 11:16:29.003  7300  7300 W art     : b5642000-b5643000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,08-04 11:16:29.003  7300  7300 W art     : b5643000-b5644000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-04 11:16:29.003  7300  7300 W art     : b5644000-b564a000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-04 11:16:29.003  7300  7300 W art     : b564a000-b564b000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b564b000-b564c000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-04 11:16:29.003  7300  7300 W art     : b564c000-b564d000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-04 11:16:29.003  7300  7300 W art     : b564d000-b5656000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
,08-04 11:16:29.003  7300  7300 W art     : b5656000-b5657000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-04 11:16:29.003  7300  7300 W art     : b5657000-b5658000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-04 11:16:29.003  7300  7300 W art     : b5658000-b56e9000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
,08-04 11:16:29.003  7300  7300 W art     : b56e9000-b56ea000 ---p 00000000 00:00 0 
08-04 11:16:29.003  7300  7300 W art     : b56ea000-b56f5000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
,08-04 11:16:29.003  7300  7300 W art     : b56f5000-b56f6000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-04 11:16:29.003  7300  7300 W art     : b56f7000-b5709000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-04 11:16:29.003  7300  7300 W art     : b5709000-b570a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-04 11:16:29.003  7300  7300 W art     : b570a000-b570b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-04 11:16:29.013  7300  7300 W art     : b570c000-b5711000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so,
08-04 11:16:29.013  7300  7300 W art     : b5711000-b5712000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-04 11:16:29.013  7300  7300 W art     : b5712000-b5713000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
,08-04 11:16:29.013  7300  7300 W art     : b5714000-b5781000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-04 11:16:29.013  7300  7300 W art     : b5781000-b5782000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b5782000-b5784000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-04 11:16:29.013  7300  7300 W art     : b5784000-b5785000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-04 11:16:29.013  7300  7300 W art     : b5785000-b5786000 r--p 00000000 00:00 0          [anon:linker_alloc],
,08-04 11:16:29.013  7300  7300 W art     : b5786000-b578d000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-04 11:16:29.013  7300  7300 W art     : b578d000-b578e000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-04 11:16:29.013  7300  7300 W art     : b578e000-b578f000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-04 11:16:29.013  7300  7300 W art     : b5790000-b5810000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-04 11:16:29.013  7300  7300 W art     : b5810000-b5811000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5811000-b5812000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-04 11:16:29.013  7300  7300 W art     : b5812000-b5813000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so,
08-04 11:16:29.013  7300  7300 W art     : b5813000-b582a000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b582a000-b5861000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-04 11:16:29.013  7300  7300 W art     : ib/libqc-opt.so
08-04 11:16:29.013  7300  7300 W art     : b5861000-b5862000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so,
08-04 11:16:29.013  7300  7300 W art     : b5862000-b5863000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-04 11:16:29.013  7300  7300 W art     : b5863000-b587f000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-04 11:16:29.013  7300  7300 W art     : b587f000-b5880000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
,08-04 11:16:29.013  7300  7300 W art     : b5880000-b5881000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-04 11:16:29.013  7300  7300 W art     : b5882000-b58e3000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-04 11:16:29.013  7300  7300 W art     : b58e3000-b58e5000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-04 11:16:29.013  7300  7300 W art     : b58e5000-b58e6000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
,08-04 11:16:29.013  7300  7300 W art     : b58e7000-b590e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-04 11:16:29.013  7300  7300 W art     : b590e000-b590f000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b590f000-b5910000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
,08-04 11:16:29.013  7300  7300 W art     : b5910000-b5911000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-04 11:16:29.013  7300  7300 W art     : b5912000-b591a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-04 11:16:29.013  7300  7300 W art     : b591a000-b591c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-04 11:16:29.013  7300  7300 W art     : b591c000-b591d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-04 11:16:29.013  7300  7300 W art     : b591e000-b5921000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-04 11:16:29.013  7300  7300 W art     : b5921000-b5922000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-04 11:16:29.013  7300  7300 W art     : b5922000-b5923000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-04 11:16:29.013  7300  7300 W art     : b5923000-b5927000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
,08-04 11:16:29.013  7300  7300 W art     : b5927000-b5928000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5928000-b5929000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-04 11:16:29.013  7300  7300 W art     : b5929000-b592a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
,08-04 11:16:29.013  7300  7300 W art     : b592a000-b593a000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-04 11:16:29.013  7300  7300 W art     : b593a000-b593b000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-04 11:16:29.013  7300  7300 W art     : b593b000-b593c000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-04 11:16:29.013  7300  7300 W art     : b593c000-b5982000 rw-p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b5982000-b598b000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-04 11:16:29.013  7300  7300 W art     : b598b000-b598c000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-04 11:16:29.013  7300  7300 W art     : b598c000-b598d000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
,08-04 11:16:29.013  7300  7300 W art     : b598e000-b5993000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-04 11:16:29.013  7300  7300 W art     : b5993000-b5994000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-04 11:16:29.013  7300  7300 W art     : b5994000-b5995000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
,08-04 11:16:29.013  7300  7300 W art     : b5995000-b5998000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-04 11:16:29.013  7300  7300 W art     : b5998000-b5999000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b5999000-b599a000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-04 11:16:29.013  7300  7300 W art     : b599a000-b599b000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-04 11:16:29.013  7300  7300 W art     : b599c000-b59b4000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-04 11:16:29.013  7300  7300 W art     : b59b4000-b59b5000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b59b5000-b59b6000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-04 11:16:29.013  7300  7300 W art     : b59b6000-b59b7000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-04 11:16:29.013  7300  7300 W art     : b59b8000-b5b52000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-04 11:16:29.013  7300  7300 W art     : b5b52000-b5b53000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b5b53000-b5b60000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-04 11:16:29.013  7300  7300 W art     : b5b60000-b5b61000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-04 11:16:29.013  7300  7300 W art     : b5b61000-b5b65000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-04 11:16:29.013  7300  7300 W art     : b5b65000-b5b66000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b5b66000-b5b67000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-04 11:16:29.013  7300  7300 W art     : b5b67000-b5b68000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-04 11:16:29.013  7300  7300 W art     : b5b68000-b5b7b000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-04 11:16:29.013  7300  7300 W art     : b5b7b000-b5b7c000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
,08-04 11:16:29.013  7300  7300 W art     : b5b7c000-b5b7d000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-04 11:16:29.013  7300  7300 W art     : b5b7e000-b5bc9000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-04 11:16:29.013  7300  7300 W art     : b5bc9000-b5bca000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
,08-04 11:16:29.013  7300  7300 W art     : b5bca000-b5bcb000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-04 11:16:29.013  7300  7300 W art     : b5bcb000-b5bcd000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5bcd000-b5bce000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-04 11:16:29.013  7300  7300 W art     : b5bce000-b5bdf000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-04 11:16:29.013  7300  7300 W art     : b5bdf000-b5be0000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5be0000-b5be1000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-04 11:16:29.013  7300  7300 W art     : b5be1000-b5be2000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-04 11:16:29.013  7300  7300 W art     : b5be3000-b5bed000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-04 11:16:29.013  7300  7300 W art     : b5bed000-b5bef000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
,08-04 11:16:29.013  7300  7300 W art     : b5bef000-b5bf0000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-04 11:16:29.013  7300  7300 W art     : b5bf0000-b5c09000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-04 11:16:29.013  7300  7300 W art     : b5c09000-b5c0a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-04 11:16:29.013  7300  7300 W art     : b5c0a000-b5c0d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
,08-04 11:16:29.013  7300  7300 W art     : b5c0d000-b5c11000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5c11000-b5c85000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-04 11:16:29.013  7300  7300 W art     : b5c85000-b5c86000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5c86000-b5c89000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
,08-04 11:16:29.013  7300  7300 W art     : b5c89000-b5c8a000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-04 11:16:29.013  7300  7300 W art     : b5c8b000-b5c8e000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-04 11:16:29.013  7300  7300 W art     : b5c8e000-b5c8f000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-04 11:16:29.013  7300  7300 W art     : b5c8f000-b5c90000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so,
08-04 11:16:29.013  7300  7300 W art     : b5c90000-b5c91000 r--p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b5c91000-b5c96000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-04 11:16:29.013  7300  7300 W art     : b5c96000-b5c97000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-04 11:16:29.013  7300  7300 W art     : b5c97000-b5c98000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-04 11:16:29.013  7300  7300 W art     : b5c98000-b5c99000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b5c99000-b5c9c000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-04 11:16:29.013  7300  7300 W art     : b5c9c000-b5c9d000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-04 11:16:29.013  7300  7300 W art     : b5c9d000-b5c9e000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
,08-04 11:16:29.013  7300  7300 W art     : b5c9e000-b5c9f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b5c9f000-b5ca3000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-04 11:16:29.013  7300  7300 W art     : b5ca3000-b5ca4000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-04 11:16:29.013  7300  7300 W art     : b5ca4000-b5ca5000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-04 11:16:29.013  7300  7300 W art     : b5ca5000-b5ca6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-04 11:16:29.013  7300  7300 W art     : b5ca6000-b5caa000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-04 11:16:29.013  7300  7300 W art     : b5caa000-b5cab000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-04 11:16:29.013  7300  7300 W art     : b5cab000-b5cac000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-04 11:16:29.013  7300  7300 W art     : b5cac000-b5cad000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b5cad000-b5cbb000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-04 11:16:29.013  7300  7300 W art     : b5cbb000-b5cbc000 ---p 00000000 00:00 0 ,
08-04 11:16:29.013  7300  7300 W art     : b5cbc000-b5cbd000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-04 11:16:29.013  7300  7300 W art     : b5cbd000-b5cbe000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-04 11:16:29.013  7300  7300 W art     : b5cbe000-b5cc8000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-04 11:16:29.013  7300  7300 W art     : b5cc8000-b5ccb000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-04 11:16:29.013  7300  7300 W art     : b5ccb000-b5ccc000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
,08-04 11:16:29.013  7300  7300 W art     : b5ccc000-b5ccd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b5ccd000-b5cd7000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-04 11:16:29.013  7300  7300 W art     : b5cd7000-b5cda000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-04 11:16:29.013  7300  7300 W art     : b5cda000-b5cdb000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-04 11:16:29.013  7300  7300 W art     : b5cdb000-b5cdf000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
,08-04 11:16:29.013  7300  7300 W art     : b5cdf000-b5ce0000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-04 11:16:29.013  7300  7300 W art     : b5ce0000-b5ce1000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-04 11:16:29.013  7300  7300 W art     : b5ce1000-b5ce2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b5ce2000-b5cef000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-04 11:16:29.013  7300  7300 W art     : b5cef000-b5cf1000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-04 11:16:29.013  7300  7300 W art     : b5cf1000-b5cf2000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so,
08-04 11:16:29.013  7300  7300 W art     : b5cf2000-b6104000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-04 11:16:29.013  7300  7300 W art     : b6104000-b6105000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6105000-b610e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-04 11:16:29.013  7300  7300 W art     : b610e000-b6112000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-04 11:16:29.013  7300  7300 W art     : b6112000-b6113000 rw-p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b6113000-b611a000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-04 11:16:29.013  7300  7300 W art     : ioutils.so
08-04 11:16:29.013  7300  7300 W art     : b611a000-b611b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-04 11:16:29.013  7300  7300 W art     : b611b000-b611c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-04 11:16:29.013  7300  7300 W art     : b611c000-b611d000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-04 11:16:29.013  7300  7300 W art     : b611d000-b6138000 r-xp 00000000
08-04 11:16:29.013  7300  7300 W art     :  b3:17 1184       /system/lib/libz.so
08-04 11:16:29.013  7300  7300 W art     : b6138000-b6139000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-04 11:16:29.013  7300  7300 W art     : b6139000-b613a000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-04 11:16:29.013  7300  7300 W art     : b613a000-b613b000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-04 11:16:29.013  7300  7300 W art     : b613b000-b6187000 r-xp 00000000 b3:17 994        
08-04 11:16:29.013  7300  7300 W art     : /system/lib/libharfbuzz_ng.so
08-04 11:16:29.013  7300  7300 W art     : b6187000-b6188000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6188000-b6189000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-04 11:16:29.013  7300  7300 W art     : b6189000-b618a000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
,08-04 11:16:29.013  7300  7300 W art     : b618a000-b618b000 r--p 00000000 00:00 0          [anon:li
08-04 11:16:29.013  7300  7300 W art     : nker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b618b000-b618f000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-04 11:16:29.013  7300  7300 W art     : b618f000-b6190000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6190000-b6191000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
,08-04 11:16:29.013  7300  7300 W art     : b6191000-b6192000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-04 11:16:29.013  7300  7300 W art     : sbhost.so
08-04 11:16:29.013  7300  7300 W art     : b6192000-b61ca000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-04 11:16:29.013  7300  7300 W art     : b61ca000-b61cb000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-04 11:16:29.013  7300  7300 W art     : b61cb000-b61cc000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so,
08-04 11:16:29.013  7300  7300 W art     : b61cc000-b61cd000 r--p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     :          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b61cd000-b626b000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-04 11:16:29.013  7300  7300 W art     : b626b000-b626c000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b626c000-b628a000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-04 11:16:29.013  7300  7300 W art     : b628a000-b628b000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-04 11:16:29.013  7300  7300 W art     : .so
08-04 11:16:29.013  7300  7300 W art     : b628b000-b63fe000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
,08-04 11:16:29.013  7300  7300 W art     : b63fe000-b6409000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-04 11:16:29.013  7300  7300 W art     : b6409000-b640a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-04 11:16:29.013  7300  7300 W art     : b640a000-b6521000 r-xp 00000000
08-04 11:16:29.013  7300  7300 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-04 11:16:29.013  7300  7300 W art     : b6521000-b652c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
,08-04 11:16:29.013  7300  7300 W art     : b652c000-b652d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-04 11:16:29.013  7300  7300 W art     : b652d000-b6531000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6531000-b6555000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-04 11:16:29.013  7300  7300 W art     : o
08-04 11:16:29.013  7300  7300 W art     : b6555000-b6557000 r--p 00023000 b3:17 400        /system/lib/libssl.so
,08-04 11:16:29.013  7300  7300 W art     : b6557000-b6558000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-04 11:16:29.013  7300  7300 W art     : b6558000-b65fe000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-04 11:16:29.013  7300  7300 W art     : b65fe000-b660b000 r--p 000a5000 b3:17 13
08-04 11:16:29.013  7300  7300 W art     : 2        /system/lib/libcrypto.so
08-04 11:16:29.013  7300  7300 W art     : b660b000-b660c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so,
08-04 11:16:29.013  7300  7300 W art     : b660c000-b660d000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b660d000-b6660000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-04 11:16:29.013  7300  7300 W art     : b6660000-b6661000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6661000-b6662000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
,08-04 11:16:29.013  7300  7300 W art     : b6662000-b6663000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-04 11:16:29.013  7300  7300 W art     : b6663000-b6668000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6668000-b667a000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-04 11:16:29.013  7300  7300 W art     : b667a000-b667b000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b667b000-b667c000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-04 11:16:29.013  7300  7300 W art     : b667c000-b667d000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-04 11:16:29.013  7300  7300 W art     : b667d000-b6684000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-04 11:16:29.013  7300  7300 W art     : b6684000-b6685000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-04 11:16:29.013  7300  7300 W art     : b6685000-b6686000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-04 11:16:29.013  7300  7300 W art     : b6686000-b6687000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6687000-b668a000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so,
08-04 11:16:29.013  7300  7300 W art     : b668a000-b668b000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-04 11:16:29.013  7300  7300 W art     : b668b000-b668c000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-04 11:16:29.013  7300  7300 W art     : b668c000-b6690000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
,08-04 11:16:29.013  7300  7300 W art     : b6690000-b6691000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-04 11:16:29.013  7300  7300 W art     : b6691000-b6692000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-04 11:16:29.013  7300  7300 W art     : b6692000-b66a0000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-04 11:16:29.013  7300  7300 W art     : b66a0000-b66a1000 ---p 00000000 00:00 0 ,
08-04 11:16:29.013  7300  7300 W art     : b66a1000-b66a2000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-04 11:16:29.013  7300  7300 W art     : b66a2000-b66a3000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-04 11:16:29.013  7300  7300 W art     : b66a3000-b66ac000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-04 11:16:29.013  7300  7300 W art     : b66ac000-b66ad000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-04 11:16:29.013  7300  7300 W art     : b66ad000-b66ae000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so,
08-04 11:16:29.013  7300  7300 W art     : b66ae000-b6714000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-04 11:16:29.013  7300  7300 W art     : b6714000-b6715000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6715000-b6717000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-04 11:16:29.013  7300  7300 W art     : b6717000-b6720000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-04 11:16:29.013  7300  7300 W art     : b6720000-b6723000 rw-p 00000000 00:00 0 ,
08-04 11:16:29.013  7300  7300 W art     : b6723000-b67ba000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-04 11:16:29.013  7300  7300 W art     : b67ba000-b67bc000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-04 11:16:29.013  7300  7300 W art     : b67bc000-b67bd000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-04 11:16:29.013  7300  7300 W art     : b67bd000-b67be000 rw-p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b67be000-b6adf000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-04 11:16:29.013  7300  7300 W art     : b6adf000-b6ae0000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6ae0000-b6afb000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-04 11:16:29.013  7300  7300 W art     : b6afb000-b6aff000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-04 11:16:29.013  7300  7300 W art     : b6aff000-b6b04000 rw-p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b6b04000-b6b0c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-04 11:16:29.013  7300  7300 W art     : b6b0c000-b6b0d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-04 11:16:29.013  7300  7300 W art     : b6b0d000-b6b0e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-04 11:16:29.013  7300  7300 W art     : b6b0e000-b6b3c000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-04 11:16:29.013  7300  7300 W art     : b6b3c000-b6b3d000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b6b3d000-b6b44000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-04 11:16:29.013  7300  7300 W art     : b6b44000-b6b45000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-04 11:16:29.013  7300  7300 W art     : b6b45000-b6b8b000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-04 11:16:29.013  7300  7300 W art     : b6b8b000-b6b8c000 ---p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b6b8c000-b6b8f000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-04 11:16:29.013  7300  7300 W art     : b6b8f000-b6b90000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-04 11:16:29.083  1451  1451 D Recents : onTaskStackChanged
08-04 11:16:29.013  7300  7300 W art     : b6b90000-b6bab000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
,08-04 11:16:29.013  7300  7300 W art     : b6bab000-b6baf000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-04 11:16:29.013  7300  7300 W art     : b6baf000-b6bb0000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-04 11:16:29.013  7300  7300 W art     : b6bb0000-b6bfd000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
,08-04 11:16:29.013  7300  7300 W art     : b6bfd000-b6bfe000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6bfe000-b6c0a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-04 11:16:29.013  7300  7300 W art     : b6c0a000-b6c0b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
,08-04 11:16:29.013  7300  7300 W art     : b6c0b000-b6c18000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-04 11:16:29.013  7300  7300 W art     : b6c18000-b6c19000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6c19000-b6c1a000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-04 11:16:29.013  7300  7300 W art     : b6c1a000-b6c1b000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-04 11:16:29.013  7300  7300 W art     : b6c1b000-b6c23000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-04 11:16:29.013  7300  7300 W art     : b6c23000-b6c24000 ---p 00000000 00:00 0 ,
08-04 11:16:29.013  7300  7300 W art     : b6c24000-b6c25000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-04 11:16:29.013  7300  7300 W art     : b6c25000-b6c26000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-04 11:16:29.013  7300  7300 W art     : b6c26000-b6c2d000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-04 11:16:29.013  7300  7300 W art     : b6c2d000-b6c2e000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
,08-04 11:16:29.013  7300  7300 W art     : b6c2e000-b6c2f000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-04 11:16:29.013  7300  7300 W art     : b6c2f000-b6c43000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-04 11:16:29.013  7300  7300 W art     : b6c43000-b6c45000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-04 11:16:29.013  7300  7300 W art     : b6c45000-b6c46000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-04 11:16:29.013  7300  7300 W art     : b6c46000-b6c6e000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
,08-04 11:16:29.013  7300  7300 W art     : b6c6e000-b6c70000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-04 11:16:29.013  7300  7300 W art     : b6c70000-b6c71000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-04 11:16:29.013  7300  7300 W art     : b6c71000-b6c74000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-04 11:16:29.013  7300  7300 W art     : b6c74000-b6c75000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-04 11:16:29.013  7300  7300 W art     : b6c75000-b6c76000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-04 11:16:29.013  7300  7300 W art     : b6c76000-b6c7f000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so,
08-04 11:16:29.013  7300  7300 W art     : b6c7f000-b6c80000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-04 11:16:29.013  7300  7300 W art     : b6c80000-b6c81000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-04 11:16:29.013  7300  7300 W art     : b6c81000-b6ca1000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-04 11:16:29.013  7300  7300 W art     : b6ca1000-b6ca2000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-04 11:16:29.013  7300  7300 W art     : b6ca2000-b6ca3000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
,08-04 11:16:29.013  7300  7300 W art     : b6ca3000-b6d16000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-04 11:16:29.013  7300  7300 W art     : b6d16000-b6d1a000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-04 11:16:29.013  7300  7300 W art     : b6d1a000-b6d1d000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-04 11:16:29.013  7300  7300 W art     : b6d1d000-b6d27000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6d27000-b6daf000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
,08-04 11:16:29.013  7300  7300 W art     : b6daf000-b6db0000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6db0000-b6db4000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-04 11:16:29.013  7300  7300 W art     : b6db4000-b6db5000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-04 11:16:29.083  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
08-04 11:16:29.013  7300  7300 W art     : b6db5000-b6db6000 rw-p 00000000 00:00 0 
,08-04 11:16:29.013  7300  7300 W art     : b6db6000-b6ddf000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-04 11:16:29.013  7300  7300 W art     : b6ddf000-b6de0000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6de0000-b6de3000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-04 11:16:29.013  7300  7300 W art     : b6de3000-b6de4000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
,08-04 11:16:29.013  7300  7300 W art     : b6de4000-b6ebe000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-04 11:16:29.013  7300  7300 W art     : b6ebe000-b6ec5000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-04 11:16:29.013  7300  7300 W art     : b6ec5000-b6ecd000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-04 11:16:29.013  7300  7300 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6ece000-b6ecf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:29.013  7300  7300 W art     : b6ecf000-b6ed0000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
,08-04 11:16:29.013  7300  7300 W art     : b6ed0000-b6ed1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b6ed1000-b6ed4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b6ed4000-b6ef9000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-04 11:16:29.013  7300  7300 W art     : b6ef9000-b6efa000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6efa000-b6f01000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
,08-04 11:16:29.013  7300  7300 W art     : b6f01000-b6f02000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-04 11:16:29.013  7300  7300 W art     : b6f02000-b6f09000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-04 11:16:29.013  7300  7300 W art     : b6f09000-b6f0a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-04 11:16:29.013  7300  7300 W art     : b6f0a000-b6f0b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
,08-04 11:16:29.013  7300  7300 W art     : b6f0b000-b6f0c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b6f0c000-b6f24000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-04 11:16:29.013  7300  7300 W art     : b6f24000-b6f25000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6f25000-b6f26000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-04 11:16:29.013  7300  7300 W art     : b6f26000-b6f27000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
,08-04 11:16:29.013  7300  7300 W art     : b6f27000-b6f35000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-04 11:16:29.013  7300  7300 W art     : b6f35000-b6f36000 ---p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6f36000-b6f37000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-04 11:16:29.013  7300  7300 W art     : b6f37000-b6f38000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so,
08-04 11:16:29.013  7300  7300 W art     : b6f38000-b6f39000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-04 11:16:29.013  7300  7300 W art     : b6f39000-b6f3b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b6f3b000-b6f3c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b6f3c000-b6f3d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-04 11:16:29.013  7300  7300 W art     : b6f3d000-b6f3e000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-04 11:16:29.013  7300  7300 W art     : b6f3e000-b6f3f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-04 11:16:29.013  7300  7300 W art     : b6f3f000-b6f5f000 r--s 00000000 00:0b 8244       /dev/__properties__
08-04 11:16:29.013  7300  7300 W art     : b6f5f000-b6f60000 r--p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6f60000-b6f61000 ---p 00000000 00:00 0 ,
08-04 11:16:29.013  7300  7300 W art     : b6f61000-b6f63000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-04 11:16:29.013  7300  7300 W art     : b6f63000-b6f64000 r-xp 00000000 00:00 0          [sigpage]
08-04 11:16:29.013  7300  7300 W art     : b6f64000-b6f7f000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-04 11:16:29.013  7300  7300 W art     : b6f7f000-b6f80000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-04 11:16:29.013  7300  7300 W art     : b6f80000-b6f82000 rw-p 0001b000 b3:17 2770       /system/bin/linker
,08-04 11:16:29.013  7300  7300 W art     : b6f82000-b6f84000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : b6f84000-b6f89000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-04 11:16:29.013  7300  7300 W art     : b6f89000-b6f8a000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-04 11:16:29.013  7300  7300 W art     : b6f8a000-b6f8b000 rw-p 00000000 00:00 0 
08-04 11:16:29.013  7300  7300 W art     : bea52000-bea73000 rw-p 00000000 00:00 0          [stack]
,08-04 11:16:29.013  7300  7300 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-04 11:16:29.053  7300  7300 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 11:16:29.113  7300  7300 I Radio-JNI: register_android_hardware_Radio DONE,
,08-04 11:16:29.123  7300  7300 E AffinityControl: AffinityControl: registerfunction enter,
,08-04 11:16:29.133  7300  7300 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:16:29.143   755  1743 D PackageManager: START PACKAGE DELETE: observer{92245430}
08-04 11:16:29.143   755  1743 D PackageManager: pkg{<packageName>}
08-04 11:16:29.143   755  1743 D PackageManager: user{0}
08-04 11:16:29.143   755  1743 D PackageManager: caller{2000}
08-04 11:16:29.143   755  1743 D PackageManager: flags{2}
08-04 11:16:29.143   755  1743 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-04 11:16:29.143   755  1743 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-04 11:16:29.143   755  1743 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-04 11:16:29.143   755  1743 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-04 11:16:29.143   755  1743 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-04 11:16:29.143   755   923 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-04 11:16:29.143   755   923 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-04 11:16:29.143   755   923 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-04 11:16:29.143   755   923 D ApplicationPolicy: getApplicationUninstallationEnabled
08-04 11:16:29.143   755   923 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-04 11:16:29.153   755   923 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-04 11:16:29.153   755   923 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-04 11:16:29.153   755   923 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-04 11:16:29.153   755   827 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-04 11:16:29.153   755   923 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-04 11:16:29.153   755   923 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-04 11:16:29.153   755   827 I ActivityManager: Killing 7202:com.test.thalitest/u0a4 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-04 11:16:29.163   755   827 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-04 11:16:29.163   755   827 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-04 11:16:29.193   755   923 D AASAinstall: there is not AASApackages.xml file
,08-04 11:16:29.213   755   768 D GraphicsStats: Buffer count: 4
,08-04 11:16:29.213   755  1599 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@540fab7)
,08-04 11:16:29.213   755  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:16:29.213   755  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:16:29.213   755  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:16:29.483   755   923 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-04 11:16:29.503   755   923 W PackageSettings: Skipping PackageSetting{cf6efe5 com.example.hello/10192} due to missing metadata
,08-04 11:16:29.583   755   923 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-04 11:16:29.583   327   327 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-04 11:16:29.583   755   923 I art     : Starting a blocking GC Explicit
,08-04 11:16:29.713   755   923 I art     : Explicit concurrent mark sweep GC freed 130581(7MB) AllocSpace objects, 105(2MB) LOS objects, 27% free, 41MB/57MB, paused 1.390ms total 124.102ms
,08-04 11:16:29.733   755   923 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 11:16:29.733   755   923 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-04 11:16:29.733   755   923 D AASAinstall: there is not AASApackages.xml file
08-04 11:16:29.733   755   923 D PackageManager: result of delete: 1{92245430}
,08-04 11:16:29.733   755   923 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-04 11:16:29.733   755   923 D PackageManager: userId{-1}
08-04 11:16:29.733   755   923 D PackageManager: andCode{true}
,08-04 11:16:29.733  7300  7300 I art     : System.exit called, status: 0
08-04 11:16:29.733  7300  7300 I AndroidRuntime: VM exiting with result code 0.
,08-04 11:16:29.763   755   923 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-04 11:16:29.763  6473  7329 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-04 11:16:29.773  6473  7329 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-04 11:16:29.773  6473  7329 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-04 11:16:29.833   755   755 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.833   755   755 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.833   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.833  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-04 11:16:29.833  1383  1383 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-04 11:16:29.843   755   894 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.843   755   894 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.843   755  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 11:16:29.853   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.853  1971  2351 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 11:16:29.853   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.853  2003  2003 E SamsungIME: mOCRHelper is null
,08-04 11:16:29.853   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.853   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.853   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.863   755  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-04 11:16:29.863   755   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ceb049a u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1587581 4330:com.samsung.klmsagent/u0a18}
,08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.863   755   755 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.873   755   755 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.873   755   755 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.873   755   755 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.873   755   755 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.873  4330  4330 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Thu Aug 04 11:16:29 GMT+02:00 2016
,08-04 11:16:29.873  1729  1729 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-04 11:16:29.883   755   755 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.883   755   755 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.883   755   755 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.883   755   755 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.883   755   755 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.883   755   755 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.893   755  1321 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-04 11:16:29.893   755  1321 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:16:29.893   755  1321 V NetworkStats: performPollLocked(flags=0x3)
,08-04 11:16:29.893   755  1322 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-04 11:16:29.893   755  1322 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-04 11:16:29.893   755   755 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.893  3198  3213 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-04 11:16:29.893  4330  4330 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-04 11:16:29.903   755   819 W System.err: remove failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml
,08-04 11:16:29.903  4330  4330 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-04 11:16:29.903  4330  4330 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:16:29.903   755   819 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml.bak -> /data/system/users/0/runtime-permissions.xml
,08-04 11:16:29.903  4330  4330 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-04 11:16:29.903  4330  7348 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-04 11:16:29.903  4330  7348 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-04 11:16:29.903  4330  7348 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-04 11:16:29.903  4330  7348 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-04 11:16:29.903  4330  7348 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-04 11:16:29.903  4330  7348 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-04 11:16:29.903  3198  3213 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
08-04 11:16:29.903   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.903  3198  3213 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-04 11:16:29.903   755   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ceb049a u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d8c2231 755:system/1000}
08-04 11:16:29.903  3198  3213 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-04 11:16:29.903   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.903   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.913   755  4063 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-04 11:16:29.913  4330  7348 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:16:29.913  4330  7348 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-04 11:16:29.913   755  1321 V NetworkStats: performPollLocked() took 24ms
,08-04 11:16:29.923  1718  7347 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-04 11:16:29.923  1718  7347 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-04 11:16:29.923  1718  7347 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-04 11:16:29.923  1718  7347 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-04 11:16:29.923  1718  7347 D RegisteredComponentCache: Collect Tech packages for Knox
08-04 11:16:29.923   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.923   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.923   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.923   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.923   755  1321 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:16:29.923  4330  7348 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-04 11:16:29.923   755   819 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.933  4330  7348 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-04 11:16:29.933   755  1321 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d487820 in tid 1321 (NetworkStats)
,08-04 11:16:29.933   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.933   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-04 11:16:29.933   755  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:16:29.933   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.933   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.933   755  1322 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:16:29.933  4330  7348 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2e1f3f4 in tid 7348 (IntentService[K)
08-04 11:16:29.933  2223  2223 E audit_log: File locking failed. error= Bad file descriptor
08-04 11:16:29.933  4330  7348 F libc    : Unable to open connection to debuggerd: Connection refused
08-04 11:16:29.933  2223  2223 E audit_log: File locking failed. error= Bad file descriptor
08-04 11:16:29.933   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.933   755   755 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-04 11:16:29.933  2223  2223 E audit_log: File locking failed. error= Bad file descriptor
,08-04 11:16:29.993   359   359 I Zygote  : Process 4330 exited due to signal (7)
,08-04 11:16:30.013   325   325 E installd: eof
08-04 11:16:30.013   325   325 E installd: failed to read size
08-04 11:16:30.013   325   325 I installd: closing connection
08-04 11:16:30.013   293   293 I ServiceManager: service 'telecom' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'knox_ccm_policy' died
,08-04 11:16:30.013   293   293 I ServiceManager: service 'enterprise_license_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'application_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'wifi_policy' died
,08-04 11:16:30.013   293   293 I ServiceManager: service 'phone_restriction_policy' died
08-04 11:16:30.013  2223  2223 E audit_log: File locking failed. error= Bad file descriptor
08-04 11:16:30.013   293   293 I ServiceManager: service 'remoteinjection' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'knox_ucsm_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'edm_proxy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'mum_container_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sb_service' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'servicediscovery' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'updatelock' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'notification' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'devicestoragemonitor' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'location' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'country_detector' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sec_location' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'search' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'execute' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'dropbox' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'wallpaper' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'audio' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'DockObserver' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'midi' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'usb' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'serial' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'kiesusb' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'jobscheduler' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'backup' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'appwidget' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'voiceinteraction' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'SecExternalDisplayService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'diskstats' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'mDNIe' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'AAS' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'MSCS' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'spengestureservice' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'quickconnect' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'samplingprofiler' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'commontime_management' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'dreams' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'graphicsstats' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'print' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'restrictions' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'media_session' died
08-04 11:16:30.013  1729  2328 E WifiManager: Channel connection lost
08-04 11:16:30.013   293   293 I ServiceManager: service 'media_router' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sec_analytics' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'media_projection' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'lpnet' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'imms' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'alarm' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'context_aware' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'scontext' died
08-04 11:16:30.023  2223  2223 E audit_log: File locking failed. error=, Bad file descriptor
08-04 11:16:30.013   293   293 I ServiceManager: service 'barbeam' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'multiwindow_facade' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'window' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'input' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'trust' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'bluetooth_manager' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'input_method' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'accessibility' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'cover' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'mount' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'lock_settings' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'deviceidle' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'device_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'harmony_eas_service' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sdp' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sdp_log' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'dlp' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'log_manager_service' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'display' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'persona_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'package' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'user' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'procstats' died
08-04 11:16:30.013  3198  3213 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e6b8b55 in tid 3213 (AccountChangeLi)
08-04 11:16:30.013   293   293 I ServiceManager: service 'meminfo' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'gfxinfo' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'dbinfo' died
08-04 11:16:30.013  1729  1729 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-04 11:16:30.013   293   293 I ServiceManager: service 'cpuinfo' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'permission' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'processinfo' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sensorservice' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'activity' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'mdm.remotedesktop' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'battery' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'usagestats' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'webviewupdate' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'scheduling_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'telephony.registry' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'persona' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'fingerprint' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'SEAMService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'media.camera.proxy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'account' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'content' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'DirEncryptService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'LSManager' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'ReactiveService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'DeviceRootKeyService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'EngineeringModeService' died
08-04 11:16:30.013  3198  3213 F libc    : Unable to open connection to debuggerd: Connection refused
08-04 11:16:30.013   293   293 I ServiceManager: service 'SatsService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'sedenial' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'vibrator' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'tw_toolbox' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'tima' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'iccc' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'cepproxyks' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'emailksproxy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'CustomFrequencyManagerService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'consumer_ir' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'rcp' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'edmnativehelper' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'enterprise_billing_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'otp_service' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'enterprise_shared_device_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'knox_timakeystore_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'enterprise_policy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'statusbar' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'clipboard' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'clipboardEx' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'network_management' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'launcherapps' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'voip' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'ABTPersistenceService' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'textservices' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'network_score' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'netstats' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'netpolicy' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'wifip2p' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'wifi' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'wifihs20' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'wifiscanner' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'rttmanager' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'ethernet' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'connectivity' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'uimode' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'batterystats' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'appops' died
08-04 11:16:30.013   293   293 I ServiceManager: service 'power' died
08-04 11:16:30.013  1718  1718 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7168ab05 in tid 1718 (com.android.nfc)
08-04 11:16:30.023  5743  5829 E WifiManager: Channel connection lost
08-04 11:16:30.023  1718  1718 F libc    : Unable to open connection to debuggerd: Connection refused
08-04 11:16:30.023  1924  2066 W Sensors : sensorservice died [0xb3f9fe80]
08-04 11:16:30.023  1971  2350 E WifiManager: Channel connection lost
08-04 11:16:30.023  1890  1901 W Sensors : sensorservice died [0xb3f9fd40]
08-04 11:16:30.023  1971  1981 W Sensors : sensorservice died [0xad92dec0]
08-04 11:16:30.023   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
08-04 11:16:30.023   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-04 11:16:30.033   294   355 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
08-04 11:16:30.033   294   355 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
08-04 11:16:30.033  2271  2292 W Sensors : sensorservice died [0xb3f9fd00]
08-04 11:16:30.033  1745  1757 W Sensors : sensorservice died [0xad44d380]
08-04 11:16:30.033   321   964 W AudioFlinger: power manager service died !!!
08-04 11:16:30.033   321   964 W AudioFlinger: power manager service died !!!
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=7 Removed JmageWallpa (3/10)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=25 Removed Mauncher (3/9)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=14 Removed EimLayer(Di (5/8)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=15 Removed EimLayer(An (2/7)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=23 Removed VSBConnecti (4/6)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=24 Removed VSBConnecti (3/5)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=25 Removed Mauncher (-2/5)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=18 Removed DolorFade (4/4)
08-04 11:16:30.033   294   355 I SurfaceFlinger: id=18 Removed DolorFade (-2/4)
08-04 11:16:30.033   294  1296 I SurfaceFlinger: restart the boot-animation @ binderDied
08-04 11:16:30.033  1830  1992 E WifiManager: Channel connection lost
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=2 Removed GocusedStac (2/3)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/2)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=4 Removed EimLayer(An (0/1)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/1)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/1)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=2 Removed GocusedStac (-2/1)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/1)
08-04 11:16:30.033   294  1808 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/1)
08-04 11:16:30.033  1383  1630 E WifiManager: Channel connection lost
08-04 11:16:30.043  2215  2215 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9eebd30a in tid 2215 (droid.bluetooth)
08-04 11:16:30.043  2215  2215 F libc    : Unable to open connection to debuggerd: Connection refused
08-04 11:16:30.043  2223  2223 E audit_log: File locking failed. error= Bad file descriptor
08-04 11:16:30.043  1383  1663 W Sensors : sensorservice died [0xadacaf40]
08-04 11:16:30.053   294   349 I SurfaceFlinger: id=5 Removed TtatusBar (0/0)
08-04 11:16:30.053   294   349 I SurfaceFlinger: id=24 Removed VSBConnecti (-2/0)
08-04 11:16:30.053   294   349 I SurfaceFlinger: id=23 Removed VSBConnecti (-2/0)
08-04 11:16:30.053   294   349 I SurfaceFlinger: id=5 Removed TtatusBar (-2/0)
08-04 11:16:30.053   294   349 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/0)
,08-04 11:16:30.063   293   293 I ServiceManager: service 'nfc' died
08-04 11:16:30.063   293   293 I ServiceManager: service 'secontroller' died
08-04 11:16:30.063   293   293 I ServiceManager: service 'nfccontroller' died
08-04 11:16:30.073  5249  5249 D BluetoothA2dp: Proxy object disconnected
08-04 11:16:30.073  5249  5249 D A2dpProfile: Bluetooth service disconnected
08-04 11:16:30.073  5249  5249 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 11:16:30.073  5249  5249 D PanProfile: Bluetooth service disconnected
08-04 11:16:30.073  5249  5249 D BluetoothPbap: Proxy object disconnected
08-04 11:16:30.073  5249  5249 D PbapServerProfile: Bluetooth service disconnected
08-04 11:16:30.073  5249  5249 D BluetoothSap: Proxy object disconnected
08-04 11:16:30.073  5249  5249 D SapProfile: Bluetooth service disconnected
08-04 11:16:30.073  2264  2264 D BluetoothA2dp: Proxy object disconnected
08-04 11:16:30.073  5249  5249 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9f0e7c in tid 5249 (ndroid.settings)
08-04 11:16:30.073  5249  5249 F libc    : Unable to open connection to debuggerd: Connection refused
08-04 11:16:30.073  2223  2223 E audit_log: File locking failed. error= Bad file descriptor
,08-04 11:16:30.103   359   359 I Zygote  : Process 3198 exited due to signal (7)
,08-04 11:16:30.103   359   359 I Zygote  : Process 1718 exited due to signal (7)
,08-04 11:16:30.123   359   359 I Zygote  : Process 2215 exited due to signal (7)
,08-04 11:16:30.123   359   359 I Zygote  : Process 5249 exited due to signal (7)
,08-04 11:16:30.163   292   292 I lowmemorykiller: ActivityManager disconnected
08-04 11:16:30.163   292   292 I lowmemorykiller: Closing Activity Manager data connection
,08-04 11:16:30.273   294   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-04 11:16:30.273   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-04 11:16:30.523   294   294 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-04 11:16:30.523   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
,08-04 11:16:30.523   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe238c
,08-04 11:16:30.543   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe238c
,08-04 11:16:30.543   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe238c
,08-04 11:16:30.553   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
,08-04 11:16:30.553   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe23a4
,08-04 11:16:30.553   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe238c
,08-04 11:16:30.553   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe238c
08-04 11:16:30.553   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebe238c
,08-04 11:16:30.553   294   553 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
