#### Test 7578926851a8f91_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
06-30 12:52:06.789   774  3386 D SSRM:n  : SIOP:: AP = 320, PST = 382, CUR = 450, LCD = 0
,--------- beginning of main
06-30 12:52:08.809  2351  2351 E audit   : type=1400 msg=audit(1467283928.809:275): avc:  denied  { execmod } for  pid=6282 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 12:52:08.809  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:08.809  2351  2351 E audit   : type=1300 msg=audit(1467283928.809:275): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa3000 a1=51000 a2=5 a3=4 items=0 ppid=3510 ppcomm=adbd pid=6282 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 12:52:08.809  2351  2351 E audit   : type=1327 msg=audit(1467283928.809:275): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 12:52:08.809  2351  2351 E audit   : type=1320 msg=audit(1467283928.809:275): 
06-30 12:52:08.869  2351  2351 E audit   : type=1400 msg=audit(1467283928.859:276): avc:  denied  { execmod } for  pid=6282 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 12:52:08.869  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:08.869  2351  2351 E audit   : type=1300 msg=audit(1467283928.859:276): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f63000 a1=51000 a2=5 a3=4 items=0 ppid=3510 ppcomm=adbd pid=6282 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 12:52:08.869  2351  2351 E audit   : type=1327 msg=audit(1467283928.859:276): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 12:52:08.869  2351  2351 E audit   : type=1320 msg=audit(1467283928.859:276): 
06-30 12:52:08.909  6282  6282 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 12:52:08.909  2351  2351 E audit   : type=1400 msg=audit(1467283928.909:277): avc:  denied  { execmod } for  pid=6282 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 12:52:08.919  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:08.919  2351  2351 E audit   : type=1300 msg=audit(1467283928.909:277): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f63000 a1=51000 a2=5 a3=4 items=0 ppid=3510 ppcomm=adbd pid=6282 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 12:52:08.919  6282  6282 D AndroidRuntime: CheckJNI is OFF
06-30 12:52:08.919  2351  2351 E audit   : type=1327 msg=audit(1467283928.909:277): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 12:52:08.919  6282  6282 D AndroidRuntime: readGMSProperty: start
06-30 12:52:08.919  6282  6282 D AndroidRuntime: readGMSProperty: already setted!!
06-30 12:52:08.919  6282  6282 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 12:52:08.919  6282  6282 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 12:52:08.919  6282  6282 D AndroidRuntime: readGMSProperty: end
06-30 12:52:08.919  6282  6282 D AndroidRuntime: addProductProperty: start
06-30 12:52:08.919  2351  2351 E audit   : type=1320 msg=audit(1467283928.909:277): 
06-30 12:52:08.929  6282  6282 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 12:52:08.929  6282  6282 W art     : aedca000-b1cf0000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 12:52:08.929  6282  6282 W art     : b1cf0000-b3f5f000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 12:52:08.929  6282  6282 W art     : b3f5f000-b3f60000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 12:52:08.929  6282  6282 W art     : b3f60000-b3f61000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.929  6282  6282 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
06-30 12:52:08.929  6282  6282 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
06-30 12:52:08.929  6282  6282 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
06-30 12:52:08.929  6282  6282 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 12:52:08.929  6282  6282 W art     : b480b000-b4834000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 12:52:08.929  6282  6282 W art     : b4834000-b4837000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
06-30 12:52:08.929  6282  6282 W art     : b4837000-b4838000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
06-30 12:52:08.929  6282  6282 W art     : b4838000-b4839000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
06-30 12:52:08.929  6282  6282 W art     : b4839000-b483a000 r--p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b483a000-b485a000 r--s 00000000 00:0b 9219       /dev/__properties__
06-30 12:52:08.929  6282  6282 W art     : b485a000-b526b000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
06-30 12:52:08.929  6282  6282 W art     : b526b000-b526c000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b526c000-b52b5000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
06-30 12:52:08.929  6282  6282 W art     : b52b5000-b52b6000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
06-30 12:52:08.929  6282  6282 W art     : b52b6000-b52be000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b52be000-b52bf000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.929  6282  6282 W art     : b52bf000-b52f4000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
06-30 12:52:08.929  6282  6282 W art     : b52f4000-b52f5000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b52f5000-b52f6000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
06-30 12:52:08.929  6282  6282 W art     : b52f6000-b52f7000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
06-30 12:52:08.929  6282  6282 W art     : b52f7000-b534f000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
06-30 12:52:08.929  6282  6282 W art     : b534f000-b5350000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5350000-b5351000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
06-30 12:52:08.929  6282  6282 W art     : b5351000-b5352000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
06-30 12:52:08.929  6282  6282 W art     : b5353000-b5359000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 12:52:08.929  6282  6282 W art     : b5359000-b535a000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 12:52:08.929  6282  6282 W art     : b535a000-b535b000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 12:52:08.929  6282  6282 W art     : b535b000-b535d000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b535e000-b5368000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 12:52:08.929  6282  6282 W art     : b5368000-b536b000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 12:52:08.929  6282  6282 W art     : b536b000-b536c000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 12:52:08.929  6282  6282 W art     : b536d000-b5384000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 12:52:08.929  6282  6282 W art     : b5384000-b5385000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5385000-b5386000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 12:52:08.929  6282  6282 W art     : b5386000-b5387000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 12:52:08.929  6282  6282 W art     : b5388000-b5392000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
06-30 12:52:08.929  6282  6282 W art     : b5392000-b5393000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
06-30 12:52:08.929  6282  6282 W art     : b5393000-b5394000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
06-30 12:52:08.929  6282  6282 W art     : b5394000-b5398000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 12:52:08.929  6282  6282 W art     : b5398000-b5399000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 12:52:08.929  6282  6282 W art     : b5399000-b539a000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 12:52:08.929  6282  6282 W art     : b539a000-b53b0000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
06-30 12:52:08.929  6282  6282 W art     : b53b0000-b53b1000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
06-30 12:52:08.929  6282  6282 W art     : b53b1000-b53b2000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
06-30 12:52:08.929  6282  6282 W art     : b53b2000-b53bf000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
06-30 12:52:08.929  6282  6282 W art     : b53bf000-b53c0000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
06-30 12:52:08.929  6282  6282 W art     : b53c0000-b53c1000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
06-30 12:52:08.929  6282  6282 W art     : b53c1000-b5421000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
06-30 12:52:08.929  6282  6282 W art     : b5421000-b5424000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
06-30 12:52:08.929  6282  6282 W art     : b5424000-b5428000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5428000-b5489000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
06-30 12:52:08.929  6282  6282 W art     : b5489000-b548a000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
06-30 12:52:08.929  6282  6282 W art     : b548a000-b54d9000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
06-30 12:52:08.929  6282  6282 W art     : b54d9000-b54db000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
06-30 12:52:08.929  6282  6282 W art     : b54db000-b54dc000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
06-30 12:52:08.929  6282  6282 W art     : b54dc000-b54dd000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b54dd000-b54e4000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 12:52:08.929  6282  6282 W art     : b54e4000-b54e5000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 12:52:08.929  6282  6282 W art     : b54e5000-b54e6000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
06-30 12:52:08.929  6282  6282 W art     : avc_common.so
06-30 12:52:08.929  6282  6282 W art     : b54e7000-b54ea000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 12:52:08.929  6282  6282 W art     : b54ea000-b54eb000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 12:52:08.929  6282  6282 W art     : b54eb000-b54ec000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
06-30 12:52:08.929  6282  6282 W art     : enc_common.so
06-30 12:52:08.929  6282  6282 W art     : b54ed000-b54f1000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
06-30 12:52:08.929  6282  6282 W art     : b54f1000-b54f2000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b54f2000-b54f3000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
06-30 12:52:08.929  6282  6282 W art     : b54f3000-b54f4000 rw-p 00005000 b3:17 2510       /syste
06-30 12:52:08.929  6282  6282 W art     : m/lib/libpowermanager.so
06-30 12:52:08.929  6282  6282 W art     : b54f5000-b5512000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 12:52:08.929  6282  6282 W art     : b5512000-b5513000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 12:52:08.929  6282  6282 W art     : b5513000-b5514000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 12:52:08.929  6282  6282 W art     : b5515000-b551a000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 12:52:08.929  6282  6282 W art     : b551a000-b551b000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 12:52:08.929  6282  6282 W art     : b551b000-b551c000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 12:52:08.929  6282  6282 W art     : b551d000-b554e000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 12:52:08.929  6282  6282 W art     : b554e000-b5551000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 12:52:08.929  6282  6282 W art     : b5551000-b5552000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 12:52:08.929  6282  6282 W art     : b5553000-b558e000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
06-30 12:52:08.929  6282  6282 W art     : b558e000-b558f000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
06-30 12:52:08.929  6282  6282 W art     : b558f000-b5590000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
06-30 12:52:08.929  6282  6282 W art     : b5591000-b5598000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
06-30 12:52:08.929  6282  6282 W art     : b5598000-b5599000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5599000-b559a000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
06-30 12:52:08.929  6282  6282 W art     : b559a000-b559b000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
06-30 12:52:08.929  6282  6282 W art     : b559b000-b559c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.929  6282  6282 W art     : b559c000-b55b3000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
06-30 12:52:08.929  6282  6282 W art     : b55b3000-b55b4000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b55b4000-b55b7000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
06-30 12:52:08.929  6282  6282 W art     : b55b7000-b55b8000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
06-30 12:52:08.929  6282  6282 W art     : b55b8000-b55d7000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
06-30 12:52:08.929  6282  6282 W art     : b55d7000-b55d8000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
06-30 12:52:08.929  6282  6282 W art     : b55d8000-b55d9000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
06-30 12:52:08.929  6282  6282 W art     : b55d9000-b5617000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 12:52:08.929  6282  6282 W art     : b5617000-b5618000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5618000-b561a000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 12:52:08.929  6282  6282 W art     : b561a000-b561b000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 12:52:08.929  6282  6282 W art     : b561c000-b5623000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 12:52:08.929  6282  6282 W art     : b5623000-b5624000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 12:52:08.929  6282  6282 W art     : b5624000-b5625000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 12:52:08.929  6282  6282 W art     : b5626000-b5629000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 12:52:08.929  6282  6282 W art     : b5629000-b562a000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 12:52:08.929  6282  6282 W art     : b562a000-b562b000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 12:52:08.929  6282  6282 W art     : b562b000-b5631000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 12:52:08.929  6282  6282 W art     : b5631000-b5632000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5632000-b5633000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 12:52:08.929  6282  6282 W art     : b5633000-b5634000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 12:52:08.929  6282  6282 W art     : b5634000-b563d000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
06-30 12:52:08.929  6282  6282 W art     : b563d000-b563e000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
06-30 12:52:08.929  6282  6282 W art     : b563e000-b563f000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
06-30 12:52:08.929  6282  6282 W art     : b563f000-b56d0000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 12:52:08.929  6282  6282 W art     : b56d0000-b56d1000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b56d1000-b56dc000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 12:52:08.929  6282  6282 W art     : b56dc000-b56dd000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 12:52:08.929  6282  6282 W art     : b56de000-b56f0000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
06-30 12:52:08.929  6282  6282 W art     : b56f0000-b56f1000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
06-30 12:52:08.929  6282  6282 W art     : b56f1000-b56f2000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
06-30 12:52:08.929  6282  6282 W art     : b56f3000-b56f8000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
06-30 12:52:08.929  6282  6282 W art     : b56f8000-b56f9000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
06-30 12:52:08.929  6282  6282 W art     : b56f9000-b56fa000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
06-30 12:52:08.929  6282  6282 W art     : b56fb000-b5768000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
06-30 12:52:08.929  6282  6282 W art     : b5768000-b5769000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5769000-b576b000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
06-30 12:52:08.929  6282  6282 W art     : b576b000-b576c000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
06-30 12:52:08.929  6282  6282 W art     : b576c000-b576d000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.929  6282  6282 W art     : b576d000-b5774000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 12:52:08.929  6282  6282 W art     : b5774000-b5775000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 12:52:08.929  6282  6282 W art     : b5775000-b5776000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 12:52:08.929  6282  6282 W art     : b5777000-b57f7000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 12:52:08.929  6282  6282 W art     : b57f7000-b57f8000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b57f8000-b57f9000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 12:52:08.929  6282  6282 W art     : b57f9000-b57fa000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 12:52:08.929  6282  6282 W art     : b57fa000-b5811000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5811000-b5848000 r-xp 00000000 b3:17 3244       /system/vendor/l
06-30 12:52:08.929  6282  6282 W art     : ib/libqc-opt.so
06-30 12:52:08.929  6282  6282 W art     : b5848000-b5849000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 12:52:08.929  6282  6282 W art     : b5849000-b584a000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 12:52:08.929  6282  6282 W art     : b584a000-b5866000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 12:52:08.929  6282  6282 W art     : b5866000-b5867000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 12:52:08.929  6282  6282 W art     : b5867000-b5868000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 12:52:08.929  6282  6282 W art     : b5869000-b58ca000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 12:52:08.929  6282  6282 W art     : b58ca000-b58cc000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 12:52:08.929  6282  6282 W art     : b58cc000-b58cd000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 12:52:08.929  6282  6282 W art     : b58ce000-b58f5000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
06-30 12:52:08.929  6282  6282 W art     : b58f5000-b58f6000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b58f6000-b58f7000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
06-30 12:52:08.929  6282  6282 W art     : b58f7000-b58f8000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
06-30 12:52:08.929  6282  6282 W art     : b58f9000-b5901000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 12:52:08.929  6282  6282 W art     : b5901000-b5903000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 12:52:08.929  6282  6282 W art     : b5903000-b5904000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 12:52:08.929  6282  6282 W art     : b5905000-b5908000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
06-30 12:52:08.929  6282  6282 W art     : b5908000-b5909000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
06-30 12:52:08.929  6282  6282 W art     : b5909000-b590a000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
06-30 12:52:08.929  6282  6282 W art     : b590a000-b590e000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
06-30 12:52:08.929  6282  6282 W art     : b590e000-b590f000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b590f000-b5910000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
06-30 12:52:08.929  6282  6282 W art     : b5910000-b5911000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
06-30 12:52:08.929  6282  6282 W art     : b5911000-b5921000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
06-30 12:52:08.929  6282  6282 W art     : b5921000-b5922000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
06-30 12:52:08.929  6282  6282 W art     : b5922000-b5923000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
06-30 12:52:08.929  6282  6282 W art     : b5923000-b5969000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5969000-b5972000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
06-30 12:52:08.929  6282  6282 W art     : b5972000-b5973000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
06-30 12:52:08.929  6282  6282 W art     : b5973000-b5974000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
06-30 12:52:08.929  6282  6282 W art     : b5975000-b597a000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
06-30 12:52:08.929  6282  6282 W art     : b597a000-b597b000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
06-30 12:52:08.929  6282  6282 W art     : b597b000-b597c000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
06-30 12:52:08.929  6282  6282 W art     : b597c000-b597f000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 12:52:08.929  6282  6282 W art     : b597f000-b5980000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5980000-b5981000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 12:52:08.929  6282  6282 W art     : b5981000-b5982000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 12:52:08.929  6282  6282 W art     : b5983000-b599b000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 12:52:08.929  6282  6282 W art     : b599b000-b599c000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b599c000-b599d000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 12:52:08.929  6282  6282 W art     : b599d000-b599e000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 12:52:08.929  6282  6282 W art     : b599f000-b5b39000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
06-30 12:52:08.929  6282  6282 W art     : b5b39000-b5b3a000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5b3a000-b5b47000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
06-30 12:52:08.929  6282  6282 W art     : b5b47000-b5b48000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
06-30 12:52:08.929  6282  6282 W art     : b5b48000-b5b4c000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
06-30 12:52:08.929  6282  6282 W art     : b5b4c000-b5b4d000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5b4d000-b5b4e000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
06-30 12:52:08.929  6282  6282 W art     : b5b4e000-b5b4f000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
06-30 12:52:08.929  6282  6282 W art     : b5b4f000-b5b62000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
06-30 12:52:08.929  6282  6282 W art     : b5b62000-b5b63000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
06-30 12:52:08.929  6282  6282 W art     : b5b63000-b5b64000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
06-30 12:52:08.929  6282  6282 W art     : b5b64000-b5b65000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 12:52:08.929  6282  6282 W art     : b5b65000-b5bb0000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
06-30 12:52:08.929  6282  6282 W art     : b5bb0000-b5bb1000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
06-30 12:52:08.929  6282  6282 W art     : b5bb1000-b5bb2000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
06-30 12:52:08.929  6282  6282 W art     : b5bb2000-b5bb4000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5bb5000-b5bc6000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 12:52:08.929  6282  6282 W art     : b5bc6000-b5bc7000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5bc7000-b5bc8000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 12:52:08.929  6282  6282 W art     : b5bc8000-b5bc9000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 12:52:08.929  6282  6282 W art     : b5bca000-b5bd4000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
06-30 12:52:08.929  6282  6282 W art     : b5bd4000-b5bd6000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
06-30 12:52:08.929  6282  6282 W art     : b5bd6000-b5bd7000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
06-30 12:52:08.929  6282  6282 W art     : b5bd7000-b5bf0000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
06-30 12:52:08.929  6282  6282 W art     : b5bf0000-b5bf1000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
06-30 12:52:08.929  6282  6282 W art     : b5bf1000-b5bf4000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
06-30 12:52:08.929  6282  6282 W art     : b5bf4000-b5bf8000 rw-p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5bf8000-b5c6c000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
06-30 12:52:08.929  6282  6282 W art     : b5c6c000-b5c6d000 ---p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5c6d000-b5c70000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
06-30 12:52:08.929  6282  6282 W art     : b5c70000-b5c71000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
06-30 12:52:08.929  6282  6282 W art     : b5c71000-b5c72000 r--p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5c72000-b5c75000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
06-30 12:52:08.929  6282  6282 W art     : b5c75000-b5c76000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
06-30 12:52:08.929  6282  6282 W art     : b5c76000-b5c77000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
06-30 12:52:08.929  6282  6282 W art     : b5c77000-b5c78000 r--p 00000000 00:00 0 
06-30 12:52:08.929  6282  6282 W art     : b5c78000-b5c7d000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 12:52:08.929  6282  6282 W art     : b5c7d000-b5c7e000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 12:52:08.929  6282  6282 W art     : b5c7e000-b5c7f000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 12:52:08.929  6282  6282 W art     : b5c7f000-b5c80000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.929  6282  6282 W art     : b5c80000-b5c83000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 12:52:08.929  6282  6282 W art     : b5c83000-b5c84000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 12:52:08.929  6282  6282 W art     : b5c84000-b5c85000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 12:52:08.929  6282  6282 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.929  6282  6282 W art     : b5c86000-b5c8a000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
06-30 12:52:08.939  6282  6282 W art     : b5c8a000-b5c8b000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
06-30 12:52:08.939  6282  6282 W art     : b5c8b000-b5c8c000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
06-30 12:52:08.939  6282  6282 W art     : b5c8c000-b5c8d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 12:52:08.939  6282  6282 W art     : b5c8d000-b5c91000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 12:52:08.939  6282  6282 W art     : b5c91000-b5c92000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 12:52:08.939  6282  6282 W art     : b5c92000-b5c93000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 12:52:08.939  6282  6282 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b5c94000-b5ca2000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 12:52:08.939  6282  6282 W art     : b5ca2000-b5ca3000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b5ca3000-b5ca4000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 12:52:08.939  6282  6282 W art     : b5ca4000-b5ca5000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 12:52:08.939  6282  6282 W art     : b5ca5000-b5caf000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 12:52:08.939  6282  6282 W art     : b5caf000-b5cb2000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 12:52:08.939  6282  6282 W art     : b5cb2000-b5cb3000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 12:52:08.939  6282  6282 W art     : b5cb3000-b5cb4000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b5cb4000-b5cbe000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
06-30 12:52:08.939  6282  6282 W art     : b5cbe000-b5cc1000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
06-30 12:52:08.939  6282  6282 W art     : b5cc1000-b5cc2000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
06-30 12:52:08.939  6282  6282 W art     : b5cc2000-b5cc6000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
06-30 12:52:08.939  6282  6282 W art     : b5cc6000-b5cc7000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
06-30 12:52:08.939  6282  6282 W art     : b5cc7000-b5cc8000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
06-30 12:52:08.939  6282  6282 W art     : b5cc8000-b5cc9000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b5cc9000-b5cd6000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 12:52:08.939  6282  6282 W art     : b5cd6000-b5cd8000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 12:52:08.939  6282  6282 W art     : b5cd8000-b5cd9000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 12:52:08.939  6282  6282 W art     : b5cd9000-b60eb000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
06-30 12:52:08.939  6282  6282 W art     : b60eb000-b60ec000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b60ec000-b60f5000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
06-30 12:52:08.939  6282  6282 W art     : b60f5000-b60f9000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
06-30 12:52:08.939  6282  6282 W art     : b60f9000-b60fa000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b60fa000-b6101000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 12:52:08.939  6282  6282 W art     : b6101000-b6102000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 12:52:08.939  6282  6282 W art     : b6102000-b6103000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 12:52:08.939  6282  6282 W art     : b6103000-b6104000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6104000-b611f000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 12:52:08.939  6282  6282 W art     : b611f000-b6120000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 12:52:08.939  6282  6282 W art     : b6120000-b6121000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 12:52:08.939  6282  6282 W art     : b6121000-b6122000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6122000-b616e000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 12:52:08.939  6282  6282 W art     : b616e000-b616f000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b616f000-b6170000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 12:52:08.939  6282  6282 W art     : b6170000-b6171000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 12:52:08.939  6282  6282 W art     : b6171000-b6172000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6172000-b6176000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
06-30 12:52:08.939  6282  6282 W art     : b6176000-b6177000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6177000-b6178000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
06-30 12:52:08.939  6282  6282 W art     : b6178000-b6179000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
06-30 12:52:08.939  6282  6282 W art     : b6179000-b61b1000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
06-30 12:52:08.939  6282  6282 W art     : b61b1000-b61b2000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
06-30 12:52:08.939  6282  6282 W art     : b61b2000-b61b3000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
06-30 12:52:08.939  6282  6282 W art     : b61b3000-b61b4000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b61b4000-b6252000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
06-30 12:52:08.939  6282  6282 W art     : b6252000-b6253000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6253000-b6271000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
06-30 12:52:08.939  6282  6282 W art     : b6271000-b6272000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
06-30 12:52:08.939  6282  6282 W art     : b6272000-b63e5000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
06-30 12:52:08.939  6282  6282 W art     : b63e5000-b63f0000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
06-30 12:52:08.939  6282  6282 W art     : b63f0000-b63f1000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
06-30 12:52:08.939  6282  6282 W art     : b63f1000-b6508000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 12:52:08.939  6282  6282 W art     : b6508000-b6513000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 12:52:08.939  6282  6282 W art     : b6513000-b6514000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 12:52:08.939  6282  6282 W art     : b6514000-b6518000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6518000-b653c000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
06-30 12:52:08.939  6282  6282 W art     : b653c000-b653e000 r--p 00023000 b3:17 400        /system/lib/libssl.so
06-30 12:52:08.939  6282  6282 W art     : b653e000-b653f000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
06-30 12:52:08.939  6282  6282 W art     : b653f000-b65e5000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
06-30 12:52:08.939  6282  6282 W art     : b65e5000-b65f2000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
06-30 12:52:08.939  6282  6282 W art     : b65f2000-b65f3000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
06-30 12:52:08.939  6282  6282 W art     : b65f3000-b65f4000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b65f4000-b6647000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
06-30 12:52:08.939  6282  6282 W art     : b6647000-b6648000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6648000-b6649000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
06-30 12:52:08.939  6282  6282 W art     : b6649000-b664a000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
06-30 12:52:08.939  6282  6282 W art     : b664a000-b664f000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b664f000-b6661000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
06-30 12:52:08.939  6282  6282 W art     : b6661000-b6662000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6662000-b6663000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
06-30 12:52:08.939  6282  6282 W art     : b6663000-b6664000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
06-30 12:52:08.939  6282  6282 W art     : b6664000-b666b000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 12:52:08.939  6282  6282 W art     : b666b000-b666c000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 12:52:08.939  6282  6282 W art     : b666c000-b666d000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 12:52:08.939  6282  6282 W art     : b666d000-b666e000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b666e000-b6671000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
06-30 12:52:08.939  6282  6282 W art     : b6671000-b6672000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
06-30 12:52:08.939  6282  6282 W art     : b6672000-b6673000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
06-30 12:52:08.939  6282  6282 W art     : b6673000-b6677000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
06-30 12:52:08.939  6282  6282 W art     : b6677000-b6678000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
06-30 12:52:08.939  6282  6282 W art     : b6678000-b6679000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
06-30 12:52:08.939  6282  6282 W art     : b6679000-b6687000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
06-30 12:52:08.939  6282  6282 W art     : b6687000-b6688000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6688000-b6689000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
06-30 12:52:08.939  6282  6282 W art     : b6689000-b668a000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
06-30 12:52:08.939  6282  6282 W art     : b668a000-b6693000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 12:52:08.939  6282  6282 W art     : b6693000-b6694000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 12:52:08.939  6282  6282 W art     : b6694000-b6695000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 12:52:08.939  6282  6282 W art     : b6695000-b66fb000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
06-30 12:52:08.939  6282  6282 W art     : b66fb000-b66fc000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b66fc000-b66fe000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
06-30 12:52:08.939  6282  6282 W art     : b66fe000-b6707000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
06-30 12:52:08.939  6282  6282 W art     : b6707000-b670a000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b670a000-b67a1000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 12:52:08.939  6282  6282 W art     : b67a1000-b67a3000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 12:52:08.939  6282  6282 W art     : b67a3000-b67a4000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 12:52:08.939  6282  6282 W art     : b67a4000-b67a5000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b67a5000-b6ac6000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
06-30 12:52:08.939  6282  6282 W art     : b6ac6000-b6ac7000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6ac7000-b6ae2000 r--p 00321000 b3:17 377        /system/lib/libskia.so
06-30 12:52:08.939  6282  6282 W art     : b6ae2000-b6ae6000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
06-30 12:52:08.939  6282  6282 W art     : b6ae6000-b6aeb000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6aeb000-b6af3000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 12:52:08.939  6282  6282 W art     : b6af3000-b6af4000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 12:52:08.939  6282  6282 W art     : b6af4000-b6af5000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 12:52:08.939  6282  6282 W art     : b6af5000-b6b23000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 12:52:08.939  6282  6282 W art     : b6b23000-b6b24000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6b24000-b6b2b000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 12:52:08.939  6282  6282 W art     : b6b2b000-b6b2c000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 12:52:08.939  6282  6282 W art     : b6b2c000-b6b72000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 12:52:08.939  6282  6282 W art     : b6b72000-b6b73000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6b73000-b6b76000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 12:52:08.939  6282  6282 W art     : b6b76000-b6b77000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 12:52:08.939  6282  6282 W art     : b6b77000-b6b92000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
06-30 12:52:08.939  6282  6282 W art     : b6b92000-b6b96000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
06-30 12:52:08.939  6282  6282 W art     : b6b96000-b6b97000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
06-30 12:52:08.939  6282  6282 W art     : b6b97000-b6be4000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
06-30 12:52:08.939  6282  6282 W art     : b6be4000-b6be5000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6be5000-b6bf1000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
06-30 12:52:08.939  6282  6282 W art     : b6bf1000-b6bf2000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
06-30 12:52:08.939  6282  6282 W art     : b6bf2000-b6bff000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
06-30 12:52:08.939  6282  6282 W art     : b6bff000-b6c00000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6c00000-b6c01000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
06-30 12:52:08.939  6282  6282 W art     : b6c01000-b6c02000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
06-30 12:52:08.939  6282  6282 W art     : b6c02000-b6c0a000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
06-30 12:52:08.939  6282  6282 W art     : b6c0a000-b6c0b000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6c0b000-b6c0c000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
06-30 12:52:08.939  6282  6282 W art     : b6c0c000-b6c0d000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
06-30 12:52:08.939  6282  6282 W art     : b6c0d000-b6c14000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 12:52:08.939  6282  6282 W art     : b6c14000-b6c15000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 12:52:08.939  6282  6282 W art     : b6c15000-b6c16000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 12:52:08.939  6282  6282 W art     : b6c16000-b6c2a000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
06-30 12:52:08.939  6282  6282 W art     : b6c2a000-b6c2c000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
06-30 12:52:08.939  6282  6282 W art     : b6c2c000-b6c2d000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
06-30 12:52:08.939  6282  6282 W art     : b6c2d000-b6c55000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
06-30 12:52:08.939  6282  6282 W art     : b6c55000-b6c57000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
06-30 12:52:08.939  6282  6282 W art     : b6c57000-b6c58000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
06-30 12:52:08.939  6282  6282 W art     : b6c58000-b6c5b000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
06-30 12:52:08.939  6282  6282 W art     : b6c5b000-b6c5c000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
06-30 12:52:08.939  6282  6282 W art     : b6c5c000-b6c5d000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
06-30 12:52:08.939  6282  6282 W art     : b6c5d000-b6c66000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 12:52:08.939  6282  6282 W art     : b6c66000-b6c67000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 12:52:08.939  6282  6282 W art     : b6c67000-b6c68000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 12:52:08.939  6282  6282 W art     : b6c68000-b6c88000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 12:52:08.939  6282  6282 W art     : b6c88000-b6c89000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 12:52:08.939  6282  6282 W art     : b6c89000-b6c8a000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 12:52:08.939  6282  6282 W art     : b6c8a000-b6cfd000 r-xp 00000000 b3:17 860        /system/lib/libc.so
06-30 12:52:08.939  6282  6282 W art     : b6cfd000-b6d01000 r--p 00072000 b3:17 860        /system/lib/libc.so
06-30 12:52:08.939  6282  6282 W art     : b6d01000-b6d04000 rw-p 00076000 b3:17 860        /system/lib/libc.so
06-30 12:52:08.939  6282  6282 W art     : b6d04000-b6d0e000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6d0e000-b6d96000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 12:52:08.939  6282  6282 W art     : b6d96000-b6d97000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6d97000-b6d9b000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 12:52:08.939  6282  6282 W art     : b6d9b000-b6d9c000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 12:52:08.939  6282  6282 W art     : b6d9c000-b6d9d000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6d9d000-b6dc6000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 12:52:08.939  6282  6282 W art     : b6dc6000-b6dc7000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6dc7000-b6dca000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 12:52:08.939  6282  6282 W art     : b6dca000-b6dcb000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 12:52:08.939  6282  6282 W art     : b6dcb000-b6ea5000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 12:52:08.939  6282  6282 W art     : b6ea5000-b6eac000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 12:52:08.939  6282  6282 W art     : b6eac000-b6eb4000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 12:52:08.939  6282  6282 W art     : b6eb4000-b6eb5000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6eb5000-b6eb6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 12:52:08.939  6282  6282 W art     : b6eb6000-b6eb7000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 12:52:08.939  6282  6282 W art     : b6eb7000-b6eb8000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6eb8000-b6ebb000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6ebb000-b6ee0000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
06-30 12:52:08.939  6282  6282 W art     : b6ee0000-b6ee1000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6ee1000-b6ee8000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
06-30 12:52:08.939  6282  6282 W art     : b6ee8000-b6ee9000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
06-30 12:52:08.939  6282  6282 W art     : b6ee9000-b6ef0000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 12:52:08.939  6282  6282 W art     : b6ef0000-b6ef1000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 12:52:08.939  6282  6282 W art     : b6ef1000-b6ef2000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 12:52:08.939  6282  6282 W art     : b6ef2000-b6ef3000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6ef3000-b6f0b000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
06-30 12:52:08.939  6282  6282 W art     : b6f0b000-b6f0c000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6f0c000-b6f0d000 r--p 00018000 b3:17 918        /system/lib/libutils.so
06-30 12:52:08.939  6282  6282 W art     : b6f0d000-b6f0e000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
06-30 12:52:08.939  6282  6282 W art     : b6f0e000-b6f1c000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
06-30 12:52:08.939  6282  6282 W art     : b6f1c000-b6f1d000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6f1d000-b6f1e000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
06-30 12:52:08.939  6282  6282 W art     : b6f1e000-b6f1f000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
06-30 12:52:08.939  6282  6282 W art     : b6f1f000-b6f20000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 12:52:08.939  6282  6282 W art     : b6f20000-b6f22000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6f22000-b6f23000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6f23000-b6f24000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 12:52:08.939  6282  6282 W art     : b6f24000-b6f25000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 12:52:08.939  6282  6282 W art     : b6f25000-b6f26000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 12:52:08.939  6282  6282 W art     : b6f26000-b6f46000 r--s 00000000 00:0b 9219       /dev/__properties__
06-30 12:52:08.939  6282  6282 W art     : b6f46000-b6f47000 r--p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6f47000-b6f48000 ---p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6f48000-b6f4a000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 12:52:08.939  6282  6282 W art     : b6f4a000-b6f4b000 r-xp 00000000 00:00 0          [sigpage]
06-30 12:52:08.939  6282  6282 W art     : b6f4b000-b6f66000 r-xp 00000000 b3:17 2770       /system/bin/linker
06-30 12:52:08.939  6282  6282 W art     : b6f66000-b6f67000 r--p 0001a000 b3:17 2770       /system/bin/linker
06-30 12:52:08.939  6282  6282 W art     : b6f67000-b6f69000 rw-p 0001b000 b3:17 2770       /system/bin/linker
06-30 12:52:08.939  6282  6282 W art     : b6f69000-b6f6b000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : b6f6b000-b6f70000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 12:52:08.939  6282  6282 W art     : b6f70000-b6f71000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 12:52:08.939  6282  6282 W art     : b6f71000-b6f72000 rw-p 00000000 00:00 0 
06-30 12:52:08.939  6282  6282 W art     : bed9e000-bedbf000 rw-p 00000000 00:00 0          [stack]
06-30 12:52:08.939  6282  6282 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 12:52:08.989  6282  6282 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 12:52:09.039  6282  6282 I Radio-JNI: register_android_hardware_Radio DONE
06-30 12:52:09.049  6282  6282 E AffinityControl: AffinityControl: registerfunction enter
06-30 12:52:09.069  6282  6282 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:52:09.089   774  1737 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
06-30 12:52:09.099   774  1737 D ActivityManager: mDVFSHelper.acquire()
06-30 12:52:09.099   774  1737 V WindowManager: addAppToken: AppWindowToken{f745e55 token=Token{965e50c ActivityRecord{899083f u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
06-30 12:52:09.109   774   906 D SecWifiDisplayUtil: Metadata value : none
06-30 12:52:09.109   774   906 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3ab030d V.E...... R.....ID 0,0-0,0}
06-30 12:52:09.119   774   906 D ISSUE_DEBUG: InputChannelName : d1028d3 Starting com.test.thalitest
06-30 12:52:09.119  6297  6297 E Zygote  : v2
06-30 12:52:09.119   774  1737 I ActivityManager: Start proc 6297:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 12:52:09.119   774  1737 D InputDispatcher: Focused application set to: xxxx
06-30 12:52:09.119  6297  6297 I libpersona: KNOX_SDCARD checking this for 10004
06-30 12:52:09.119  6297  6297 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:09.119   774  1737 D InputDispatcher: Focus left window: 3443
06-30 12:52:09.119  6282  6282 D AndroidRuntime: Shutting down VM
06-30 12:52:09.119   774   850 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9bccf58 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 12:52:09.119  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 12:52:09.119   774  1321 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 12:52:09.129  6297  6297 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 12:52:09.129  6297  6297 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:09.129  6297  6297 E Zygote  : accessInfo : 0
06-30 12:52:09.129  6297  6297 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 12:52:09.129   292   292 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
06-30 12:52:09.149   774   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
06-30 12:52:09.149   774   906 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:09.149   774   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
06-30 12:52:09.149   774   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 12:52:09.149   774   906 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 12:52:09.159  6297  6297 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:09.159  6297  6297 D ActivityThread: Added TimaKeyStore provider
06-30 12:52:09.159   774  1641 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 12:52:09.159   774  1641 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 12:52:09.159   774   850 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d1028d3 u0 d0 Starting com.test.thalitest}
06-30 12:52:09.169  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 12:52:09.179   774  1641 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 12:52:09.189   774   906 V WindowStateAnimator: Finishing drawing window Window{d1028d3 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 12:52:09.189   774   841 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 12:52:09.189   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbecf9364
06-30 12:52:09.209  1724  1930 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
06-30 12:52:09.209  1724  1724 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
06-30 12:52:09.219   292   373 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
06-30 12:52:09.219   292  4732 I SurfaceFlinger: id=18 Removed VSBConnecti (7/11)
06-30 12:52:09.219   292   362 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
06-30 12:52:09.219   292  4732 D libEGL  : eglTerminate EGLDisplay = 0xb2a3f64c
06-30 12:52:09.219   292  4732 D libEGL  : eglTerminate EGLDisplay = 0xb2a3f64c
06-30 12:52:09.219  3443  3443 V ActivityThread: updateVisibility : ActivityRecord{b2d36e0 token=android.os.BinderProxy@c0190ba {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 12:52:09.219   292   362 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
06-30 12:52:09.229   292   373 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
06-30 12:52:09.229   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbecf93a4
06-30 12:52:09.229   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbecf93a4
06-30 12:52:09.229  2264  2287 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
06-30 12:52:09.229  1724  1724 V ActivityThread: updateVisibility : ActivityRecord{a3153a3 token=android.os.BinderProxy@b5dedfc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 12:52:09.229  1724  1724 D Launcher: onTrimMemory. Level: 20
06-30 12:52:09.249   292   362 I SurfaceFlinger: id=19 Removed VSBConnecti (4/9)
06-30 12:52:09.249   292   373 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/9)
06-30 12:52:09.259   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbecf93a4
06-30 12:52:09.319   774  1321 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
06-30 12:52:09.319  6297  6297 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 12:52:09.329   774  3386 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 12:52:09.349  6297  6297 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 12:52:09.359  6297  6297 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 12:52:09.379  6297  6297 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,06-30 12:52:09.409  6297  6297 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 12:52:09.409  6297  6297 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 12:52:09.419  6297  6297 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 9035-9038)
,06-30 12:52:09.419  6297  6297 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 12:52:09.439  6297  6297 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ecbef8c}
06-30 12:52:09.439  6297  6297 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 12:52:09.439  6297  6297 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 12:52:09.439  6297  6316 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-30 12:52:09.449  6297  6297 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-30 12:52:09.449   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:09.459   774   784 I art     : Background partial concurrent mark sweep GC freed 14922(1080KB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 42MB/58MB, paused 2.078ms total 156.893ms
,06-30 12:52:09.469  6297  6317 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,06-30 12:52:09.479  6297  6297 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 12:52:09.479  6297  6297 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 12:52:09.479  6297  6297 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 12:52:09.479  6297  6297 I Adreno-EGL: Local Branch: ss
06-30 12:52:09.479  6297  6297 I Adreno-EGL: Remote Branch: 
06-30 12:52:09.479  6297  6297 I Adreno-EGL: Local Patches: 
06-30 12:52:09.479  6297  6297 I Adreno-EGL: Reconstruct Branch: 
,06-30 12:52:09.479  6297  6297 D libEGL  : eglInitialize EGLDisplay = 0xbefc1dac
,06-30 12:52:09.509   774  1642 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,06-30 12:52:09.509   774  1642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,06-30 12:52:09.579  6297  6297 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-30 12:52:09.599  6297  6297 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 12:52:09.599  6297  6297 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,06-30 12:52:09.599  6297  6297 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-30 12:52:09.599  6297  6297 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-30 12:52:09.609  6297  6297 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-30 12:52:09.619  6297  6297 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 12:52:09.699  6297  6297 D SecWifiDisplayUtil: Metadata value : none
,06-30 12:52:09.709  6297  6297 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{35cca4a I.E...... R.....ID 0,0-0,0}
,06-30 12:52:09.719  6297  6343 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:52:09.719   774  1643 D ISSUE_DEBUG: InputChannelName : 56aea04 com.test.thalitest/com.test.thalitest.MainActivity
06-30 12:52:09.719   774  1740 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 12:52:09.719   774  1740 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 12:52:09.719   774   774 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 12:52:09.719   774   774 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 12:52:09.729  6297  6297 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6297
,06-30 12:52:09.739   774  1739 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6297 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:52:09.749  6297  6316 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-30 12:52:09.749  6297  6297 D SecWifiDisplayUtil: Metadata value : none
,06-30 12:52:09.749   292   292 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,06-30 12:52:09.769   774  1421 D InputDispatcher: Focus entered window: 6297
,06-30 12:52:09.779   774   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
,06-30 12:52:09.779  6297  6343 D libEGL  : eglInitialize EGLDisplay = 0x9d73f7c4
06-30 12:52:09.779  6297  6343 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:52:09.779   774   906 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:09.779   774   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
06-30 12:52:09.779   774   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 12:52:09.819  6297  6297 V ActivityThread: updateVisibility : ActivityRecord{a359a97 token=android.os.BinderProxy@93f63b5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 12:52:09.819  6297  6297 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 12:52:09.839   774  1495 V WindowStateAnimator: Finishing drawing window Window{56aea04 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-30 12:52:09.839  6297  6297 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,06-30 12:52:09.839  6297  6297 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 12:52:09.839   774   786 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 12:52:09.849   774   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 12:52:09.849   774   906 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +538ms (total +746ms)
,06-30 12:52:09.849   774   774 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 12:52:09.849   774   774 I KnoxTimeoutHandler: SD activityfalse
,06-30 12:52:09.849   774   906 D ActivityManager: mDVFSHelper.release()
06-30 12:52:09.849   774   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{899083f u0 com.test.thalitest/.MainActivity t64} time:149469
,06-30 12:52:09.859   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbecf9364
,06-30 12:52:09.859   774   906 D ViewRootImpl: #3 mView = null
,06-30 12:52:09.859   292  4732 I SurfaceFlinger: id=20 Removed uhalitest (7/9)
,06-30 12:52:09.859  6297  6297 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 12:52:09.859   292   373 I SurfaceFlinger: id=20 Removed uhalitest (-2/9)
,06-30 12:52:09.869   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbecf93a4
,06-30 12:52:09.879   774   787 V WindowStateAnimator: Finishing drawing window Window{56aea04 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,06-30 12:52:09.879  6297  6297 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@93f63b5 time:149493
,06-30 12:52:09.889   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbecf9364
,06-30 12:52:09.899  6297  6351 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:09.899  6297  6351 D libEGL  : eglInitialize EGLDisplay = 0x9a9fc3ec
,06-30 12:52:09.939  6297  6297 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6297
,06-30 12:52:10.089  6297  6297 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 12:52:10.189  6297  6362 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1708918480
,06-30 12:52:10.189  6297  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:52:10.189  6297  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:52:10.189  6297  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:52:10.189  6297  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:52:10.189  6297  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:52:10.189  6297  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d1a425 added. We now have 1 listener(s)
06-30 12:52:10.189  6297  6362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
06-30 12:52:10.189  6297  6362 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
06-30 12:52:10.189  6297  6362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:52:10.189  6297  6362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:52:10.199  6297  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d96208 added. We now have 1 listener(s)
06-30 12:52:10.199  6297  6362 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:52:10.199  6297  6362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:10.199  6297  6362 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 12:52:10.199  6297  6362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 12:52:10.199  6297  6362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 12:52:10.199  6297  6362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:52:10.199  6297  6362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 12:52:10.199  6297  6362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:52:10.199  6297  6362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,06-30 12:52:10.199  6297  6362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:10.199  6297  6362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:52:10.199  6297  6362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:52:10.199  6297  6362 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:52:10.199  6297  6362 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 12:52:10.229  6297  6297 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:52:10.319   774  3387 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,06-30 12:52:10.719  1448  1448 D Recents : onTaskStackChanged
,06-30 12:52:10.729  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,06-30 12:52:10.949  6297  6366 W jxcore-log: Initializing JXcore engine
,06-30 12:52:10.949  6297  6366 W jxcore-log: JXcore engine is ready
,06-30 12:52:10.999  2351  2351 E audit   : type=1400 msg=audit(1467283930.999:278): avc:  denied  { ioctl } for  pid=6366 comm="Thread-891" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 12:52:10.999  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,06-30 12:52:10.999  2351  2351 E audit   : type=1300 msg=audit(1467283930.999:278): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a1373c8 items=0 ppid=351 ppcomm=main pid=6366 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 12:52:10.999  2351  2351 E audit   : type=1327 msg=audit(1467283930.999:278): proctitle="com.test.thalitest"
06-30 12:52:10.999  2351  2351 E audit   : type=1320 msg=audit(1467283930.999:278): 
06-30 12:52:10.999  2351  2351 E audit   : type=1400 msg=audit(1467283930.999:279): avc:  denied  { ioctl } for  pid=6366 comm="Thread-891" path="socket:[40332]" dev="sockfs" ino=40332 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 12:52:10.999  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,06-30 12:52:10.999  2351  2351 E audit   : type=1300 msg=audit(1467283930.999:279): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=2 a3=9a1373c8 items=0 ppid=351 ppcomm=main pid=6366 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-891" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 12:52:10.999  2351  2351 E audit   : type=1327 msg=audit(1467283930.999:279): proctitle="com.test.thalitest"
06-30 12:52:10.999  2351  2351 E audit   : type=1320 msg=audit(1467283930.999:279): 
,06-30 12:52:11.009  6297  6366 W jxcore-log: Starting JXcore engine
,06-30 12:52:11.079  6297  6366 W jxcore-log: Platform android
06-30 12:52:11.079  6297  6366 W jxcore-log: 
,06-30 12:52:11.079  6297  6366 W jxcore-log: Process ARCH arm
06-30 12:52:11.079  6297  6366 W jxcore-log: 
,06-30 12:52:11.269  6297  6366 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:52:11.269  6297  6366 I jxcore-log: 
,06-30 12:52:11.269  6297  6366 W jxcore-log: JXcore engine is started
,06-30 12:52:11.269   774  1583 E Watchdog: !@Sync 4 [06-30 12:52:11.280]
,06-30 12:52:11.269  6297  6362 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 12:52:11.279   774  1697 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package null
,06-30 12:52:11.289   774  1697 D ActivityManager: mDVFSHelper.acquire()
,06-30 12:52:11.299   774  1697 V WindowManager: addAppToken: AppWindowToken{5dedc34 token=Token{b1c4307 ActivityRecord{2348546 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}}} to stack=1 task=64 at 1
,06-30 12:52:11.309  6367  6367 E Zygote  : v2
06-30 12:52:11.309  6367  6367 I libpersona: KNOX_SDCARD checking this for 10129
06-30 12:52:11.309  6367  6367 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:11.309  6367  6367 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 12:52:11.309  6367  6367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 12:52:11.309  6367  6367 E Zygote  : accessInfo : 0
06-30 12:52:11.309  6367  6367 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-30 12:52:11.309   774  1697 I ActivityManager: Start proc 6367:com.android.packageinstaller/u0a129 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 12:52:11.309   774  1697 D InputDispatcher: Focused application set to: xxxx
,06-30 12:52:11.309   774  1697 D InputDispatcher: Focus left window: 6297
,06-30 12:52:11.319   774   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
,06-30 12:52:11.319   774   906 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:11.319   774   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
,06-30 12:52:11.319   774   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 12:52:11.319  6297  6362 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 45ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 12:52:11.329  6367  6367 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:11.329  6367  6367 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:11.339   774  1698 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 12:52:11.339   774   841 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 12:52:11.649   774  1698 I WindowManager: Screenshot max retries 4 of Token{b1c4307 ActivityRecord{2348546 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}} appWin=Window{56aea04 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 12:52:11.699  6367  6367 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.739  6367  6367 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 12:52:11.759  6367  6367 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.759  6367  6367 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.789  6367  6367 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.819  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.819  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.829  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.829  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.839  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.839  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.909  6367  6367 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 12:52:11.919  6367  6367 D SecWifiDisplayUtil: Metadata value : none
,06-30 12:52:11.929  6367  6367 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c3b7f14 I.E...... R.....I. 0,0-0,0}
,06-30 12:52:11.929  6367  6382 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:52:11.929   774  1421 D ISSUE_DEBUG: InputChannelName : a67af59 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 12:52:11.939   774  1697 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,06-30 12:52:11.939   774  1697 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 12:52:11.939   774   774 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 12:52:11.939   774   774 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 12:52:11.939   774   774 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 12:52:11.959   292   292 I SurfaceFlinger: id=22 createSurf (145x145),1 flag=4, HrantPermis
,06-30 12:52:11.959   774   850 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a67af59 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 12:52:11.969  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 12:52:11.979   774  1203 D InputDispatcher: Focus entered window: 6367
,06-30 12:52:11.979   774   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:774 uid:1000
,06-30 12:52:11.979   774   906 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 12:52:11.979   774   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:774 uid:1000
,06-30 12:52:11.979   774   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 12:52:11.979  6367  6382 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 12:52:11.979  6367  6382 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 12:52:11.979  6367  6382 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 12:52:11.979  6367  6382 I Adreno-EGL: Local Branch: ss
06-30 12:52:11.979  6367  6382 I Adreno-EGL: Remote Branch: 
06-30 12:52:11.979  6367  6382 I Adreno-EGL: Local Patches: 
06-30 12:52:11.979  6367  6382 I Adreno-EGL: Reconstruct Branch: 
,06-30 12:52:11.989  6367  6382 D libEGL  : eglInitialize EGLDisplay = 0xae1cd7c4
,06-30 12:52:11.989  6367  6382 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:52:12.039  6367  6367 V ActivityThread: updateVisibility : ActivityRecord{12e5a5f token=android.os.BinderProxy@b0c2567 {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 12:52:12.039  6367  6367 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 12:52:12.049   774  1697 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 12:52:12.069  6367  6367 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 12:52:12.099   774  1739 V WindowStateAnimator: Finishing drawing window Window{a67af59 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
06-30 12:52:12.099  2036  2036 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 12:52:12.099  6367  6367 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b0c2567 time:151715
,06-30 12:52:12.099   774   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 12:52:12.109   774   906 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +449ms (total +808ms)
06-30 12:52:12.109   774   774 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 12:52:12.109   774   774 I KnoxTimeoutHandler: SD activityfalse
,06-30 12:52:12.109   774   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2348546 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64} time:151721
06-30 12:52:12.109   774   906 D ActivityManager: mDVFSHelper.release()
,06-30 12:52:12.109   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbecf9364
,06-30 12:52:12.149   774  1363 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,06-30 12:52:12.209  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:52:12.939  1448  1448 D Recents : onTaskStackChanged
,06-30 12:52:14.849   774  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:14.849   774  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:52:14.849   774  1421 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
06-30 12:52:14.849   774  1421 D BatteryService: stay LED for fully charged
,06-30 12:52:14.849   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:14.849   774   774 I MotionRecognitionService: Plugged
,06-30 12:52:14.849   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:52:14.849   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:52:14.859   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:14.859  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:14.859  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:14.859  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:14.879  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:14.879  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:14.889  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:16.849   774  3386 D SSRM:n  : SIOP:: AP = 330, PST = 371, CUR = 450, LCD = 0
,06-30 12:52:17.739   774  3386 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 12:52:19.109   774   930 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 12:52:19.149   774   930 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 12:52:24.939   774  1239 V AlarmManager: Expired Alarm result :4
,06-30 12:52:25.009   774  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:25.009   774  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:52:25.009   774  1739 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:52:25.019   774  1739 D BatteryService: stay LED for fully charged
,06-30 12:52:25.049   774  1239 I ActivityManager: Start proc 6424:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 12:52:25.059  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:52:25.069  6424  6424 E Zygote  : v2
,06-30 12:52:25.069  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 12:52:25.069  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:52:25.069  6424  6424 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:25.069  6424  6424 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:25.069  6424  6424 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 12:52:25.069  6424  6424 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 12:52:25.079  6424  6424 E Zygote  : accessInfo : 0
,06-30 12:52:25.089   774  1637 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 12:52:25.089   774  1637 V AlarmManager:  remove PendingIntent] PendingIntent{c7276e5: PendingIntentRecord{71495ba android broadcastIntent}}
,06-30 12:52:25.099  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:52:25.109  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:52:25.119   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:25.119  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM,
,06-30 12:52:25.119  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.119  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.129  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.129   774   774 I MotionRecognitionService: Plugged
,06-30 12:52:25.129   774   774 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:25.129   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:25.129   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:25.129  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.129  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.129  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.139  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:25.139  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:25.139  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:25.139  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:25.139  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:25.159  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:25.159  6424  6424 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:25.159  6424  6424 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:25.179  6424  6424 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,06-30 12:52:25.189  6424  6424 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,06-30 12:52:25.189  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:52:25.229  4232  4232 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10011, CallingPid : 4232
,06-30 12:52:25.229   774  1495 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/4232 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:52:25.279  4232  6455 W DriveInitializer: Background init thread started
,06-30 12:52:25.309   774  1642 I ActivityManager: Killing 5028:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,06-30 12:52:25.339   774  1641 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,06-30 12:52:25.359  4232  6455 W DriveInitializer: Background init thread ended
,06-30 12:52:26.909   774  3386 D SSRM:n  : SIOP:: AP = 320, PST = 358, CUR = 450, LCD = 0
,06-30 12:52:29.449   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:36.159  1974  3268 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:36.969   774  3386 D SSRM:n  : SIOP:: AP = 310, PST = 349, CUR = 450, LCD = 0
,06-30 12:52:38.859   774  1239 V AlarmManager: Expired Alarm result :4
,06-30 12:52:38.909   774   841 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5cf63ce u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f18f9eb 1974:com.google.android.gms.persistent/u0a11}
,06-30 12:52:38.919   774  1642 V AlarmManager:  remove PendingIntent] PendingIntent{90a72ef: PendingIntentRecord{a60a1c8 com.google.android.gms broadcastIntent}}
,06-30 12:52:38.929   774   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:38.929   774   786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:52:38.929   774   786 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
06-30 12:52:38.929   774   786 D BatteryService: stay LED for fully charged
06-30 12:52:38.929   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:38.939   774   774 I MotionRecognitionService: Plugged
,06-30 12:52:38.939   774   774 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:38.939   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:38.939   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:38.939  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:38.939  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:38.949  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:52:38.969  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:38.969  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:38.969  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:41.269   774  1583 E Watchdog: !@Sync 5 [06-30 12:52:41.281]
,06-30 12:52:41.489   774  3387 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 12:52:41.499   774   841 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fa01ea6 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75d5825 5884:com.samsung.android.sm.provider/1000}
,06-30 12:52:41.629   774  3387 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 12:52:41.639   774   841 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{48494 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75d5825 5884:com.samsung.android.sm.provider/1000}
,06-30 12:52:47.019   774  3386 D SSRM:n  : SIOP:: AP = 310, PST = 344, CUR = 450, LCD = 0
,06-30 12:52:49.019   774  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:49.469   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:57.079   774  3386 D SSRM:n  : SIOP:: AP = 310, PST = 338, CUR = 450, LCD = 0
,06-30 12:53:00.009   774  1239 V AlarmManager: Expired Alarm result :8
,06-30 12:53:00.079   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:00.079   774  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:53:00.089   774  1495 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:53:00.089   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:00.099   774   774 I MotionRecognitionService: Plugged
,06-30 12:53:00.099   774   774 D MotionRecognitionService:   cableConnection= 1
06-30 12:53:00.099   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:53:00.109   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:00.109   774  1495 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
06-30 12:53:00.109   774  1495 D BatteryService: stay LED for fully charged
,06-30 12:53:00.119  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:00.129  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:00.129  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:00.159  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:00.169  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:00.169  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:07.159   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 327, CUR = 450, LCD = 0
,06-30 12:53:09.469   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:10.169   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:10.169   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:53:10.169   774   787 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:53:10.169   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:10.189   774   774 I MotionRecognitionService: Plugged
,06-30 12:53:10.189   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:53:10.199   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:53:10.199   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:10.199   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 12:53:10.199   774   787 D BatteryService: stay LED for fully charged
,06-30 12:53:10.199  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:10.199  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:10.199  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:10.229  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:10.229  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:10.229  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:11.279   774  1583 E Watchdog: !@Sync 6 [06-30 12:53:11.286]
,06-30 12:53:12.219  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:53:17.219   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 318, CUR = 450, LCD = 0
,06-30 12:53:25.099   774  1239 V AlarmManager: Expired Alarm result :4
,06-30 12:53:25.129  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:53:25.129  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 12:53:25.129  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:53:25.159  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:53:25.159   774  1637 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 12:53:25.159   774  1637 V AlarmManager:  remove PendingIntent] PendingIntent{c7276e5: PendingIntentRecord{71495ba android broadcastIntent}}
,06-30 12:53:25.179   774  1637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 12:53:25.189   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:25.189   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:53:25.189   774   787 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:53:25.189   774   787 D BatteryService: stay LED for fully charged
,06-30 12:53:25.199  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:53:25.209  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.219   774   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11bce39 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f18f9eb 1974:com.google.android.gms.persistent/u0a11}
,06-30 12:53:25.219  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.229   774  1642 V AlarmManager:  remove PendingIntent] PendingIntent{ac25c7e: PendingIntentRecord{a60a1c8 com.google.android.gms broadcastIntent}}
,06-30 12:53:25.249  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.249   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:25.249  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.259  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.259  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.259   774   774 I MotionRecognitionService: Plugged
06-30 12:53:25.259   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:53:25.259   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:25.259   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:25.259  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.279  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:25.279  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:25.279  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:25.279  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:25.279  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:25.279  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:25.359  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:25.989  1974  1986 I art     : Background partial concurrent mark sweep GC freed 53669(3MB) AllocSpace objects, 39(780KB) LOS objects, 40% free, 19MB/32MB, paused 2.998ms total 124.605ms
,06-30 12:53:26.089  1974  1974 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=881795c1-374b-490d-833c-c3b02afc0bb3
,06-30 12:53:26.109  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:26.109  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:26.289  1974  2143 W GCoreFlp: No location to return for getLastLocation()
,06-30 12:53:26.389  4232  6527 D UdcContextInitService: registered all accounts: true
,06-30 12:53:26.409  1974  2185 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 12:53:26.439  1974  2322 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 12:53:26.539  1974  2322 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:53:26.669  1974  2322 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 12:53:26.679   774  1698 V AlarmManager:  remove PendingIntent] PendingIntent{14ec68d: PendingIntentRecord{a60a1c8 com.google.android.gms broadcastIntent}}
,06-30 12:53:26.809  4232  4987 D NetworkUsageDbReporter: Started reporting usage
,06-30 12:53:26.909  4232  4987 D NetworkUsageDbReporter: Finished reporting usage.
,06-30 12:53:26.959   774  1697 V AlarmManager:  remove PendingIntent] PendingIntent{2f48e8e: PendingIntentRecord{a60a1c8 com.google.android.gms broadcastIntent}}
,06-30 12:53:27.289   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 313, CUR = 450, LCD = 0
,06-30 12:53:28.729  1974  2322 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:53:28.729  1974  2322 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 12:53:29.469   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:37.339   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 310, CUR = 450, LCD = 0
,06-30 12:53:41.279   774  1583 E Watchdog: !@Sync 7 [06-30 12:53:41.291]
,06-30 12:53:47.399   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450, LCD = 0
,06-30 12:53:49.479   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:55.259   774  1203 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:55.269   774  1203 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:53:55.269   774  1203 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:53:55.269   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:55.279   774   774 I MotionRecognitionService: Plugged
,06-30 12:53:55.279   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:53:55.289   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:53:55.289   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:55.289   774  1203 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 12:53:55.299   774  1203 D BatteryService: stay LED for fully charged
,06-30 12:53:55.309  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:55.309  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:55.309  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:55.339  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:55.339  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:55.349  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:57.459   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,06-30 12:53:59.989   774  1239 V AlarmManager: Expired Alarm result :8
,06-30 12:54:07.519   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,06-30 12:54:09.479   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:11.289   774  1583 E Watchdog: !@Sync 8 [06-30 12:54:11.297]
,06-30 12:54:12.239  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:54:12.449  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 210ms lastUpdatedAfter : 164911ms
,06-30 12:54:17.579   774  3386 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,06-30 12:54:25.339   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:25.349   774  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:54:25.349   774  1495 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:54:25.349   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:54:25.359   774   774 I MotionRecognitionService: Plugged
,06-30 12:54:25.369   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:54:25.369   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:54:25.369   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:54:25.379   774  1495 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,06-30 12:54:25.379   774  1495 D BatteryService: stay LED for fully charged
,06-30 12:54:25.389  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:25.389  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:25.399  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:25.419  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:25.419  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:25.419  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:27.629   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 300, CUR = 450, LCD = 0
,06-30 12:54:29.489   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:37.689   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,06-30 12:54:41.289   774  1583 E Watchdog: !@Sync 9 [06-30 12:54:41.300]
,06-30 12:54:47.769   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,06-30 12:54:49.489   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:55.419   774  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:56.139   774  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:54:56.139   774  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:54:56.149   774  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:54:56.159   774  1233 I TLC_TIMA_PKM_initialize: initializing...
,06-30 12:54:56.159   774  1233 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 12:54:56.169   774  1233 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,06-30 12:54:56.169   774  1233 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 12:54:56.169   774  1233 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 12:54:56.169   774  1233 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,06-30 12:54:56.169   774  1233 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 12:54:56.169   774  1233 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 12:54:56.179   774  1233 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 12:54:56.179   774  1233 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:54:56.229   774  1233 D QSEECOMAPI: : Loaded image: APP id = 2
,06-30 12:54:56.249   774  1233 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 12:54:56.269   774  1233 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 12:54:57.849   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,06-30 12:54:59.289   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 12:54:59.289   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:54:59.299   774  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:54:59.299   774  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:07.909   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,06-30 12:55:09.489   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:11.299   774  1583 E Watchdog: !@Sync 10 [06-30 12:55:11.305]
,06-30 12:55:12.459  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:55:17.969   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,06-30 12:55:25.499   774  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:25.509   774  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:55:25.509   774  1642 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:55:25.509   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:25.519   774   774 I MotionRecognitionService: Plugged
,06-30 12:55:25.519   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:55:25.529   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:55:25.529   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:55:25.529   774  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 12:55:25.529   774  1642 D BatteryService: stay LED for fully charged
,06-30 12:55:25.549  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:25.549  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:25.549  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:25.569  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:25.569  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:25.569  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:28.019   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,06-30 12:55:29.499   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:33.499  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:33.519  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:33.519  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:33.589  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:33.589  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:33.599   305  1126 D EnterpriseController: netId is 0
06-30 12:55:33.599   305  1126 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 12:55:38.079   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,06-30 12:55:41.299   774  1583 E Watchdog: !@Sync 11 [06-30 12:55:41.308]
,06-30 12:55:45.119   774  1239 V AlarmManager: Expired Alarm result :4
,06-30 12:55:45.139  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:55:45.149  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 12:55:45.149  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:55:45.179  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:55:45.199  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:55:45.229  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.239  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.239  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.239  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.249  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.249  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.249  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:45.299  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:48.139   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 12:55:49.499   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:55.579   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:58.209   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:55:59.989   774  1239 V AlarmManager: Expired Alarm result :8
,06-30 12:56:08.269   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:56:09.499   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:11.299   774  1583 E Watchdog: !@Sync 12 [06-30 12:56:11.313]
,06-30 12:56:12.479  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:56:18.319   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:56:25.659   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:25.659   774  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:56:25.669   774  1495 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:56:25.669   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:25.679   774   774 I MotionRecognitionService: Plugged
,06-30 12:56:25.679   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:56:25.679   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:56:25.689   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:56:25.689   774  1495 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 12:56:25.689   774  1495 D BatteryService: stay LED for fully charged
,06-30 12:56:25.709  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:25.709  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:25.709  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:25.729  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:25.729  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:25.729  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:28.369   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:56:29.509   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:38.469   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:56:41.309   774  1583 E Watchdog: !@Sync 13 [06-30 12:56:41.317]
,06-30 12:56:48.609   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:56:49.509   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:55.739   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:55.739   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:56:55.739   774   787 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:56:55.749   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:55.759   774   774 I MotionRecognitionService: Plugged
,06-30 12:56:55.759   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:56:55.759   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:56:55.759   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:56:55.769   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 12:56:55.769   774   787 D BatteryService: stay LED for fully charged
,06-30 12:56:55.789  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:55.789  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:55.789  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:55.819  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:55.829  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:55.829  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:58.669   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:57:08.719   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:57:09.519   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:11.309   774  1583 E Watchdog: !@Sync 14 [06-30 12:57:11.321]
,06-30 12:57:12.499  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:57:12.669  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 156ms lastUpdatedAfter : 180217ms
,06-30 12:57:18.819   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:57:25.819   774  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:25.819   774  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:57:25.819   774  1421 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:57:25.829   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:25.839   774   774 I MotionRecognitionService: Plugged
,06-30 12:57:25.839   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:57:25.839   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:57:25.839   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:57:25.849   774  1421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 12:57:25.849   774  1421 D BatteryService: stay LED for fully charged
,06-30 12:57:25.859  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:25.859  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:57:25.859  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:25.879  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:25.879  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:25.879  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:28.879   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:57:29.519   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:38.929   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:57:41.319   774  1583 E Watchdog: !@Sync 15 [06-30 12:57:41.328]
,06-30 12:57:45.869   361   361 I bootchecker: bootchecker wake up!!
,06-30 12:57:48.989   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:57:49.519   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:55.899   774  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:55.899   774  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:57:55.899   774  1643 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:57:55.909   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:55.919   774   774 I MotionRecognitionService: Plugged
,06-30 12:57:55.919   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:57:55.919   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:57:55.919   774  1643 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,06-30 12:57:55.929   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:57:55.929   774  1643 D BatteryService: stay LED for fully charged
,06-30 12:57:55.939  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:55.949  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:55.949  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:55.979  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:55.979  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:55.979  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:59.039   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:58:09.089   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:58:09.529   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:11.319   774  1583 E Watchdog: !@Sync 16 [06-30 12:58:11.332]
,06-30 12:58:12.679  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:58:19.139   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:58:25.979   774  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:29.199   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:58:29.529   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:39.259   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:58:41.329   774  1583 E Watchdog: !@Sync 17 [06-30 12:58:41.336]
,06-30 12:58:49.309   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:58:49.529   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:56.059   774  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:56.059   774  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 12:58:56.069   774  1740 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 12:58:56.069   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:56.079   774   774 I MotionRecognitionService: Plugged
,06-30 12:58:56.079   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 12:58:56.089   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 12:58:56.089   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:58:56.089   774  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 12:58:56.089   774  1740 D BatteryService: stay LED for fully charged
,06-30 12:58:56.109  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:58:56.109  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:58:56.109  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:58:56.129  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:56.129  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:56.129  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:59.359   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:59:09.409   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:59:09.539   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:11.329   774  1583 E Watchdog: !@Sync 18 [06-30 12:59:11.340]
,06-30 12:59:12.699  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 12:59:19.459   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:59:26.139   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:29.519   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:59:29.539   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:39.569   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:59:41.339   774  1583 E Watchdog: !@Sync 19 [06-30 12:59:41.345]
,06-30 12:59:49.549   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:49.619   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 12:59:56.149   774  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:59:56.149   774  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:59:56.149   774  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:59:56.229   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:57.519   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 12:59:57.519   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:59:57.529   774  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:59:57.529   774  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:59:59.669   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:00:09.549   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:09.719   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:00:11.339   774  1583 E Watchdog: !@Sync 20 [06-30 13:00:11.349]
,06-30 13:00:12.719  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:00:12.889  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 153ms lastUpdatedAfter : 180216ms
,06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 13:00:15.689   774   835 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.699   774   835 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
,06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:15.709   774   835 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:15.719   774   835 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:15.809   774   906 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,06-30 13:00:15.809   774   906 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 13:00:19.789   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:00:26.299   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:26.299   774  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:00:26.299   774  1495 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:00:26.309   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:00:26.319   774   774 I MotionRecognitionService: Plugged
,06-30 13:00:26.319   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:00:26.319   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:00:26.319   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:00:26.329   774  1495 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:00:26.329   774  1495 D BatteryService: stay LED for fully charged
,06-30 13:00:26.339  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:00:26.349  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:00:26.349  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:00:26.379  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:26.379  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:00:26.379  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:29.549   774  3420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:29.839   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:00:33.689   774  1740 I ActivityManager: Killing 4516:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 603s, lastActivityTime 603s
,06-30 13:00:33.699   774  1740 I ActivityManager: Killing 3776:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 607s, lastActivityTime 607s
,06-30 13:00:33.729  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:33.879   291   291 I ServiceManager: service 'AtCmdFwd' died
,06-30 13:00:33.879   367  4973 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 13:00:33.879   367  4973 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:00:33.889  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:00:33.889   774  1697 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 13:00:33.889   774  1697 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 13:00:33.889   774  1697 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
06-30 13:00:33.889  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:33.909   774   784 I art     : Background partial concurrent mark sweep GC freed 51829(5MB) AllocSpace objects, 255(4MB) LOS objects, 27% free, 42MB/58MB, paused 2.195ms total 263.389ms
,06-30 13:00:33.909   774  1643 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 13:00:33.909   774  1643 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 13:00:33.909   774  1643 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10973ms
,06-30 13:00:33.969  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:00:33.969  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:00:33.969   305  1126 D EnterpriseController: netId is 0
06-30 13:00:33.969   305  1126 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 13:00:34.879   367  4973 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:00:34.959   774   841 I ActivityManager: Start proc 6622:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 13:00:34.969  6622  6622 E Zygote  : v2
,06-30 13:00:34.969  6622  6622 I libpersona: KNOX_SDCARD checking this for 1000
,06-30 13:00:34.969  6622  6622 I libpersona: KNOX_SDCARD not a persona
,06-30 13:00:34.979  6622  6622 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 13:00:34.979  6622  6622 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:00:34.979  6622  6622 E Zygote  : accessInfo : 0
,06-30 13:00:35.019  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:00:35.029  6622  6622 D ActivityThread: Added TimaKeyStore provider
,06-30 13:00:35.049  6622  6622 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 13:00:35.059  6622  6622 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 13:00:35.069  6622  6622 D AtFwdService: onCreate method
,06-30 13:00:35.069  6622  6622 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 13:00:35.079  6622  6634 D AtCkpdCmdHandler: De-queing command
,06-30 13:00:39.899   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:00:41.349   774  1583 E Watchdog: !@Sync 21 [06-30 13:00:41.353]
,06-30 13:00:44.969   774   841 I ActivityManager: Start proc 6636:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 13:00:44.979  6636  6636 E Zygote  : v2
,06-30 13:00:44.979  6636  6636 I libpersona: KNOX_SDCARD checking this for 10026
06-30 13:00:44.979  6636  6636 I libpersona: KNOX_SDCARD not a persona
,06-30 13:00:44.979  6636  6636 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 13:00:44.979  6636  6636 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:00:44.989  6636  6636 E Zygote  : accessInfo : 0
,06-30 13:00:44.989  6636  6636 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 13:00:45.029  6636  6636 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:00:45.029  6636  6636 D ActivityThread: Added TimaKeyStore provider
,06-30 13:00:45.039   774   787 I ActivityManager: Killing 3725:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 618s, lastActivityTime 608s
,06-30 13:00:45.069  6636  6636 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 13:00:45.079   774  1739 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,06-30 13:00:45.079   774  1739 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,06-30 13:00:45.099  6636  6636 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 13:00:45.109  6636  6636 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 13:00:45.119  6636  6636 D ContextualPageNotification: resetAllNotification : all clear!!!
,06-30 13:00:45.909   774  1239 V AlarmManager: Expired Alarm result :8
,06-30 13:00:49.959   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:00:56.379   774  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:00.029   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:01:10.089   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:01:11.349   774  1583 E Watchdog: !@Sync 22 [06-30 13:01:11.360]
,06-30 13:01:12.899  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:01:20.139   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:01:26.449   774  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:26.459   774  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:01:26.459   774  1421 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:01:26.459   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:26.469   774   774 I MotionRecognitionService: Plugged
,06-30 13:01:26.479   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:01:26.479   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:01:26.479   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:01:26.479   774  1421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:01:26.489   774  1421 D BatteryService: stay LED for fully charged
,06-30 13:01:26.499  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:26.499  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:26.499  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:26.519  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:26.519  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:26.529  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:30.199   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:01:40.289   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:01:41.359   774  1583 E Watchdog: !@Sync 23 [06-30 13:01:41.367]
,06-30 13:01:50.349   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:01:56.529   774  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:56.529   774  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:01:56.539   774  1697 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:01:56.539   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:56.549   774   774 I MotionRecognitionService: Plugged
,06-30 13:01:56.549   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:01:56.559   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:01:56.559   774  1697 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:01:56.559   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:01:56.569   774  1697 D BatteryService: stay LED for fully charged
,06-30 13:01:56.579  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:56.579  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:56.579  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:56.619  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:56.619  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:56.619  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:00.399   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:02:10.499   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:02:11.359   774  1583 E Watchdog: !@Sync 24 [06-30 13:02:11.371]
,06-30 13:02:12.939  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:02:20.559   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:02:26.609   774  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:26.609   774  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:02:26.609   774  1642 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:02:26.619   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:26.629   774   774 I MotionRecognitionService: Plugged
,06-30 13:02:26.629   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:02:26.629   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:02:26.629   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:02:26.639   774  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:02:26.639   774  1642 D BatteryService: stay LED for fully charged
,06-30 13:02:26.649  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:26.649  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:02:26.649  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:26.669  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:26.669  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:26.669  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:30.609   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:02:40.699   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:02:41.369   774  1583 E Watchdog: !@Sync 25 [06-30 13:02:41.377]
,06-30 13:02:50.789   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:02:56.689   774  1203 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:56.689   774  1203 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:02:56.699   774  1203 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:02:56.699   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:56.709   774   774 I MotionRecognitionService: Plugged
,06-30 13:02:56.709   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:02:56.709   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:02:56.719   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:02:56.719   774  1203 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:02:56.719   774  1203 D BatteryService: stay LED for fully charged
,06-30 13:02:56.739  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:56.739  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:56.739  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:56.769  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:56.769  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:56.769  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:00.849   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:03:10.899   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:03:11.369   774  1583 E Watchdog: !@Sync 26 [06-30 13:03:11.381]
,06-30 13:03:12.959  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:03:13.139  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 166ms lastUpdatedAfter : 180253ms
,06-30 13:03:15.789   774  2438 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 13:03:15.789   774  2438 V MARsPolicyManager: updateSMDBValues
,06-30 13:03:15.799   774   904 E MARsDBManager: updateDBAll : begin --size 1
,06-30 13:03:15.819   774   904 I ActivityManager: Killing 1832:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 783s, lastActivityTime 706s
,06-30 13:03:15.829   774   904 I ActivityManager: Killing 1512:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 759s, lastActivityTime 749s
,06-30 13:03:15.889   774   904 E MARsDBManager: updateDBAll : end
,06-30 13:03:15.889   774   904 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 13:03:15.949   774  1697 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,06-30 13:03:15.949   774  1697 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 13:03:15.949   774  1697 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,06-30 13:03:15.959   774  1737 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,06-30 13:03:15.959   774  1737 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 13:03:15.959   774  1737 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 10985ms
06-30 13:03:15.959   774  1737 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 13:03:15.959   774  1737 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 20985ms
,06-30 13:03:15.969  5605  5605 D HealthConsole: Service for HealthDataStore is disconnected
,06-30 13:03:15.989   774  1643 I ActivityManager: Start proc 6664:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,06-30 13:03:15.999  6664  6664 E Zygote  : v2
06-30 13:03:15.999  6664  6664 I libpersona: KNOX_SDCARD checking this for 10034
06-30 13:03:15.999  6664  6664 I libpersona: KNOX_SDCARD not a persona
,06-30 13:03:15.999  6664  6664 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:03:15.999  6664  6664 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:03:16.009  6664  6664 E Zygote  : accessInfo : 0
,06-30 13:03:16.009  6664  6664 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,06-30 13:03:16.039  6664  6664 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:03:16.039  6664  6664 D ActivityThread: Added TimaKeyStore provider
,06-30 13:03:16.069  6664  6664 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,06-30 13:03:16.099  6664  6664 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,06-30 13:03:16.099  6664  6664 I MultiDex: VM with version 2.1.0 has multidex support
06-30 13:03:16.099  6664  6664 I MultiDex: install
06-30 13:03:16.099  6664  6664 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 13:03:16.099  6664  6664 I MultiDex: install
06-30 13:03:16.109  6664  6664 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 13:03:16.219   774  1421 I ActivityManager: Start proc 6689:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
06-30 13:03:16.219  6689  6689 E Zygote  : v2
06-30 13:03:16.219  6689  6689 I libpersona: KNOX_SDCARD checking this for 10016
06-30 13:03:16.219  6689  6689 I libpersona: KNOX_SDCARD not a persona
,06-30 13:03:16.219  6689  6689 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:03:16.219  6689  6689 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:03:16.219  6689  6689 E Zygote  : accessInfo : 0
,06-30 13:03:16.219  6689  6689 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,06-30 13:03:16.259  6689  6689 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:03:16.259  6689  6689 D ActivityThread: Added TimaKeyStore provider
,06-30 13:03:16.279  6689  6689 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,06-30 13:03:16.329  6664  6664 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 13:03:16.329  6664  6664 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 13:03:16.389  1378  1378 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,06-30 13:03:16.399   774  1697 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,06-30 13:03:16.409   774  1737 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,06-30 13:03:16.429   774  1740 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,06-30 13:03:16.439   774  1495 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,06-30 13:03:16.439  1378  1378 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{62f9d72 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
06-30 13:03:16.439  1378  1378 D AdaptiveEventManager: M updateContainers()
06-30 13:03:16.439  1378  1378 D AdaptiveEventContainerSmall: C updatePedoContainer()
06-30 13:03:16.439  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate()
,06-30 13:03:16.439  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,06-30 13:03:16.489  6664  6664 I Health.HealthService: HealthService: onCreate() start (6664)
,06-30 13:03:16.639  5605  5605 D HealthDataStore: Service for HealthDataStore is connected
,06-30 13:03:16.649  5605  5605 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 13:03:16.679   774  1421 I ActivityManager: Killing 5045:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,06-30 13:03:16.699  5605  5605 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 13:03:16.699  5605  5605 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 13:03:16.719   774  1740 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,06-30 13:03:16.729  6664  6664 D HealthDataStore: Service for HealthDataStore is connected
,06-30 13:03:16.729  6664  6664 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 13:03:16.729  6664  6664 D HealthConsole: Service for HealthDataConsole is connected
,06-30 13:03:16.739  6664  6664 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 13:03:16.749  6664  6664 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 13:03:16.959  6664  6709 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,06-30 13:03:16.999   774   841 I ActivityManager: Start proc 6722:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,06-30 13:03:16.999   774  1321 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 13:03:16.999  6722  6722 E Zygote  : v2
06-30 13:03:16.999  6722  6722 I libpersona: KNOX_SDCARD checking this for 10181
06-30 13:03:16.999  6722  6722 I libpersona: KNOX_SDCARD not a persona
,06-30 13:03:16.999  6722  6722 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:03:16.999  6722  6722 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:03:16.999  6722  6722 E Zygote  : accessInfo : 0
,06-30 13:03:16.999  6722  6722 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,06-30 13:03:17.009  6664  6728 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,06-30 13:03:17.029   774  1321 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:03:17.039  6689  6700 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 13:03:17.049  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:03:17.049  6722  6722 D ActivityThread: Added TimaKeyStore provider
,06-30 13:03:17.049   390   390 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 10016, gid 10016, pid 6689
06-30 13:03:17.049   390   390 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,06-30 13:03:17.059  6722  6722 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,06-30 13:03:17.079  6722  6722 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,06-30 13:03:17.099  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,06-30 13:03:17.109  6722  6722 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 13:03:17.109  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,06-30 13:03:17.119  6722  6722 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
06-30 13:03:17.119   774   841 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6673b95 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{859f4aa 6722:com.sec.android.daemonapp/u0a181}
,06-30 13:03:17.119  6722  6722 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
06-30 13:03:17.119  6722  6722 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 13:03:17.119  6722  6722 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,06-30 13:03:17.119  6722  6722 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 13:03:17.199  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 13:03:17.199  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 13:03:17.199  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,06-30 13:03:17.199  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 13:03:17.199  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 13:03:17.199  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,06-30 13:03:17.209  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 13:03:17.229  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,06-30 13:03:17.239  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 13:03:17.239  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 13:03:17.239  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,06-30 13:03:17.239  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 13:03:17.239  6722  6722 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 13:03:17.249  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 13:03:17.249  6722  6722 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 13:03:17.249  6722  6722 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 13:03:17.249  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 13:03:17.249  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 13:03:17.259   774  1421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cbab176 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{859f4aa 6722:com.sec.android.daemonapp/u0a181}
,06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 13:03:17.269  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 13:03:17.269  6722  6722 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 13:03:17.269  6722  6722 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 13:03:17.269  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 13:03:17.269  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 13:03:17.279  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 13:03:17.279  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 13:03:17.279  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 13:03:17.279  6689  6700 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,06-30 13:03:17.279   774  1643 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d3b377 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{859f4aa 6722:com.sec.android.daemonapp/u0a181}
,06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 13:03:17.299  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 13:03:17.299  6722  6722 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 13:03:17.299  6722  6722 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 13:03:17.299  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 13:03:17.299  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 13:03:17.309  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 13:03:17.309  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 13:03:17.309  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 13:03:17.309   774  1641 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3dbdbe4 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{859f4aa 6722:com.sec.android.daemonapp/u0a181}
,06-30 13:03:17.319  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 13:03:17.319  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 13:03:17.319  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 13:03:17.319  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 13:03:17.319  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 13:03:17.329  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 13:03:17.329  6722  6722 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 13:03:17.329  6722  6722 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 13:03:17.329  6722  6722 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 13:03:17.329  6722  6722 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 13:03:17.339  6664  6728 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,06-30 13:03:17.469  6664  6728 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
06-30 13:03:17.479  6664  6728 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 13:03:17.889   390   390 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,06-30 13:03:18.009  6689  6700 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,06-30 13:03:18.009  6689  6700 I SecureStorage: [INFO]: SPID(0x00000007)Skip using SecureStorageExceptionJNI
,06-30 13:03:18.019  6689  6700 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,06-30 13:03:20.999   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:03:26.769   774  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:26.769   774  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:03:26.769   774  1739 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:03:26.779   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:26.789   774   774 I MotionRecognitionService: Plugged
,06-30 13:03:26.789   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:03:26.789   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:03:26.799   774  1739 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:03:26.799   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:03:26.799   774  1739 D BatteryService: stay LED for fully charged
,06-30 13:03:26.819  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:26.819  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:26.819  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:26.849  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:26.849  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:26.849  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:31.049   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:03:41.099   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:03:41.379   774  1583 E Watchdog: !@Sync 27 [06-30 13:03:41.386]
,06-30 13:03:51.159   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:03:56.849   774  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:56.849   774  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:03:56.849   774  1737 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:03:56.859   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:56.869   774   774 I MotionRecognitionService: Plugged
,06-30 13:03:56.869   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:03:56.869   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:03:56.869   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:03:56.879   774  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:03:56.879   774  1737 D BatteryService: stay LED for fully charged
,06-30 13:03:56.889  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:56.889  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:56.889  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:56.919  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:56.929  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:56.929  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:01.209   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:04:11.269   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:04:11.379   774  1583 E Watchdog: !@Sync 28 [06-30 13:04:11.391]
,06-30 13:04:13.149  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:04:21.319   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:04:26.929   774  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:26.929   774  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:04:26.929   774  1421 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:04:26.929   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:04:26.949   774   774 I MotionRecognitionService: Plugged
,06-30 13:04:26.949   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:04:26.949   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:04:26.949   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:04:26.959   774  1421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:04:26.959   774  1421 D BatteryService: stay LED for fully charged
,06-30 13:04:26.969  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:26.969  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:26.979  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:26.999  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:26.999  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:26.999  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:31.379   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:04:41.389   774  1583 E Watchdog: !@Sync 29 [06-30 13:04:41.398]
,06-30 13:04:41.449   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:04:51.499   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:04:56.149   774  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:04:56.149   774  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:04:56.149   774  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:04:57.009   774  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:57.019   774  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:04:57.019   774  1697 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:04:57.019   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:04:57.029   774   774 I MotionRecognitionService: Plugged
,06-30 13:04:57.029   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:04:57.029   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:04:57.039   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:04:57.039   774  1697 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:04:57.039   774  1697 D BatteryService: stay LED for fully charged
,06-30 13:04:57.049  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:57.049  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:57.049  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:57.079  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:57.079  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:57.089  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:59.239   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:04:59.239   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:04:59.249   774  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:04:59.259   774  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:01.549   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:05:11.389   774  1583 E Watchdog: !@Sync 30 [06-30 13:05:11.402]
,06-30 13:05:11.609   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:05:13.169  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:05:21.659   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:05:27.069   774  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:27.079   774  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:05:27.079   774  1643 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:05:27.079   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:27.089   774   774 I MotionRecognitionService: Plugged
,06-30 13:05:27.089   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:05:27.099   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:05:27.099   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:05:27.109   774  1643 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:05:27.109   774  1643 D BatteryService: stay LED for fully charged
,06-30 13:05:27.119  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:27.119  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:27.129  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:27.149  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:27.149  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:27.149  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:31.689   774  1239 V AlarmManager: Expired Alarm result :8
,06-30 13:05:31.719   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:05:34.069  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:34.099  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:34.099  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:34.159  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:05:34.159  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:05:34.159   305  1126 D EnterpriseController: netId is 0
06-30 13:05:34.159   305  1126 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 13:05:41.399   774  1583 E Watchdog: !@Sync 31 [06-30 13:05:41.407],
,06-30 13:05:41.789   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:05:51.839   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:05:57.159   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:57.159   774  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:05:57.159   774  1495 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:05:57.169   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:57.179   774   774 I MotionRecognitionService: Plugged
,06-30 13:05:57.179   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:05:57.179   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:05:57.179   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:05:57.189   774  1495 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:05:57.189   774  1495 D BatteryService: stay LED for fully charged
,06-30 13:05:57.199  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:57.199  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:57.199  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:57.229  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:57.229  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:57.229  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:01.899   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:06:11.409   774  1583 E Watchdog: !@Sync 32 [06-30 13:06:11.416]
,06-30 13:06:11.949   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:06:13.199  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:06:13.369  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 165ms lastUpdatedAfter : 180229ms
,06-30 13:06:22.009   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:06:27.229   774  1697 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:27.229   774  1697 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:06:27.239   774  1697 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:06:27.239   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:27.249   774   774 I MotionRecognitionService: Plugged
,06-30 13:06:27.249   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:06:27.249   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:06:27.259   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:06:27.259   774  1697 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 13:06:27.259   774  1697 D BatteryService: stay LED for fully charged
,06-30 13:06:27.279  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:27.279  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:06:27.279  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:27.299  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:27.299  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:27.299  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:32.059   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:06:41.409   774  1583 E Watchdog: !@Sync 33 [06-30 13:06:41.421]
,06-30 13:06:42.109   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:06:52.169   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:06:57.309   774  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:57.309   774  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:06:57.319   774  1740 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:06:57.319   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:57.329   774   774 I MotionRecognitionService: Plugged
,06-30 13:06:57.329   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:06:57.329   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:06:57.339   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:06:57.339   774  1740 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:06:57.339   774  1740 D BatteryService: stay LED for fully charged
,06-30 13:06:57.359  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:57.359  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:57.359  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:57.399  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:57.399  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:57.399  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:02.219   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:07:11.419   774  1583 E Watchdog: !@Sync 34 [06-30 13:07:11.426]
,06-30 13:07:12.269   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:07:13.379  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:07:22.329   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:07:27.389   774  1203 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:27.389   774  1203 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:07:27.399   774  1203 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:07:27.399   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:27.409   774   774 I MotionRecognitionService: Plugged
,06-30 13:07:27.409   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:07:27.419   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:07:27.419   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:07:27.419   774  1203 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 13:07:27.429   774  1203 D BatteryService: stay LED for fully charged
,06-30 13:07:27.429  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:27.429  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:07:27.429  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:27.449  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:27.459  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:27.459  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:32.379   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:07:41.419   774  1583 E Watchdog: !@Sync 35 [06-30 13:07:41.431]
,06-30 13:07:42.439   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:07:52.489   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:07:57.469   774  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:57.469   774  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:07:57.479   774  1739 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:07:57.479   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:57.489   774   774 I MotionRecognitionService: Plugged
,06-30 13:07:57.489   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:07:57.489   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:07:57.499   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:07:57.499   774  1739 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 13:07:57.499   774  1739 D BatteryService: stay LED for fully charged
,06-30 13:07:57.519  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:57.519  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:57.519  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:57.549  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:57.549  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:57.549  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:02.539   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:08:11.429   774  1583 E Watchdog: !@Sync 36 [06-30 13:08:11.437]
,06-30 13:08:12.589   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:08:13.409  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:08:22.639   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:08:27.549   774  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:27.549   774  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:08:27.559   774  1737 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:08:27.559   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:27.569   774   774 I MotionRecognitionService: Plugged
,06-30 13:08:27.569   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:08:27.569   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:08:27.579   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:08:27.579   774  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 13:08:27.579   774  1737 D BatteryService: stay LED for fully charged
,06-30 13:08:27.589  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:27.589  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:27.599  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:27.629  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:27.629  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:27.629  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:32.699   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:08:41.429   774  1583 E Watchdog: !@Sync 37 [06-30 13:08:41.441]
,06-30 13:08:42.749   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:08:52.809   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:08:57.629   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:57.629   774   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:08:57.629   774   787 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:08:57.639   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:57.649   774   774 I MotionRecognitionService: Plugged
,06-30 13:08:57.649   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:08:57.649   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:08:57.649   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:08:57.659   774   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:08:57.659   774   787 D BatteryService: stay LED for fully charged
,06-30 13:08:57.679  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:57.679  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:08:57.679  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:57.699  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:57.699  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:57.699  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:02.859   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:09:11.439   774  1583 E Watchdog: !@Sync 38 [06-30 13:09:11.447]
,06-30 13:09:12.909   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:09:13.419  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:09:13.579  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 146ms lastUpdatedAfter : 180209ms
,06-30 13:09:22.979   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:09:27.709   774  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:27.709   774  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:09:27.709   774  1642 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:09:27.719   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:27.729   774   774 I MotionRecognitionService: Plugged
,06-30 13:09:27.729   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:09:27.729   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:09:27.729   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:09:27.739   774  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:09:27.739   774  1642 D BatteryService: stay LED for fully charged
,06-30 13:09:27.759  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:27.759  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:27.759  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:27.789  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:27.799  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:27.799  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:33.039   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:09:41.439   774  1583 E Watchdog: !@Sync 39 [06-30 13:09:41.451]
,06-30 13:09:43.089   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:09:53.149   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:09:56.149   774  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:09:56.149   774  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:09:56.149   774  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:09:57.489   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:09:57.489   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:09:57.499   774  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:09:57.499   774  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:09:57.789   774  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:57.789   774  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:09:57.799   774  1421 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:09:57.799   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:57.809   774   774 I MotionRecognitionService: Plugged
,06-30 13:09:57.809   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:09:57.809   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:09:57.819   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:09:57.819   774  1421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:09:57.819   774  1421 D BatteryService: stay LED for fully charged
,06-30 13:09:57.829  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:57.829  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:57.829  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:57.849  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:57.849  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:57.849  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:03.209   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:10:08.189   774   835 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:11.449   774  1583 E Watchdog: !@Sync 40 [06-30 13:10:11.457]
,06-30 13:10:13.269   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:10:13.619  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:10:23.329   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:10:27.869   774  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:33.379   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:10:34.269  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:34.289  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:34.299  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:34.359  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:10:34.359  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:10:34.369   305  1126 D EnterpriseController: netId is 0
06-30 13:10:34.369   305  1126 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 13:10:41.449   774  1583 E Watchdog: !@Sync 41 [06-30 13:10:41.461]
,06-30 13:10:43.439   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:10:53.489   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:10:57.949   774  1203 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:57.949   774  1203 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:10:57.949   774  1203 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:10:57.959   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:57.969   774   774 I MotionRecognitionService: Plugged
,06-30 13:10:57.969   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:10:57.969   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:10:57.969   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:10:57.979   774  1203 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:10:57.979   774  1203 D BatteryService: stay LED for fully charged
,06-30 13:10:57.999  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:57.999  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:57.999  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:58.029  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:58.029  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:58.029  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:03.549   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:11:11.459   774  1583 E Watchdog: !@Sync 42 [06-30 13:11:11.467]
,06-30 13:11:13.599   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:11:13.749  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:11:23.649   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:11:28.029   774  1739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:28.029   774  1739 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:11:28.039   774  1739 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:11:28.039   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:28.049   774   774 I MotionRecognitionService: Plugged
,06-30 13:11:28.049   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:11:28.049   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:11:28.059   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:11:28.059   774  1739 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 13:11:28.059   774  1739 D BatteryService: stay LED for fully charged
,06-30 13:11:28.069  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:28.069  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:28.069  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:28.099  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:28.109  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:28.109  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:33.709   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:11:41.459   774  1583 E Watchdog: !@Sync 43 [06-30 13:11:41.471]
,06-30 13:11:43.779   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:11:53.839   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:11:58.109   774  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:03.889   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:12:11.469   774  1583 E Watchdog: !@Sync 44 [06-30 13:12:11.477]
,06-30 13:12:13.769  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:12:13.929  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 150ms lastUpdatedAfter : 180344ms
,06-30 13:12:13.979   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:12:24.029   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:12:28.189   774  1643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:28.189   774  1643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:12:28.189   774  1643 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:12:28.199   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:28.209   774   774 I MotionRecognitionService: Plugged
,06-30 13:12:28.209   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:12:28.209   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:12:28.209   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:12:28.219   774  1643 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:12:28.219   774  1643 D BatteryService: stay LED for fully charged
,06-30 13:12:28.229  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:28.239  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:28.239  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:28.269  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:28.269  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:28.269  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:34.089   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:12:41.469   774  1583 E Watchdog: !@Sync 45 [06-30 13:12:41.481]
,06-30 13:12:44.139   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:12:54.189   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:12:58.269   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:04.249   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:13:11.479   774  1583 E Watchdog: !@Sync 46 [06-30 13:13:11.487]
,06-30 13:13:13.939  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:13:14.299   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:13:24.349   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:13:28.349   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:34.409   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:13:41.479   774  1583 E Watchdog: !@Sync 47 [06-30 13:13:41.491]
,06-30 13:13:44.459   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:13:54.509   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:13:58.439   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:04.569   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:14:11.489   774  1583 E Watchdog: !@Sync 48 [06-30 13:14:11.496]
,06-30 13:14:13.959  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:14:14.639   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:14:14.769   774   784 I art     : Background sticky concurrent mark sweep GC freed 44095(7MB) AllocSpace objects, 413(8MB) LOS objects, 26% free, 42MB/58MB, paused 2.518ms total 144.305ms
,06-30 13:14:24.699   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:14:28.519   774  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:28.519   774  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:14:28.519   774  1495 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:14:28.529   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:28.539   774   774 I MotionRecognitionService: Plugged
,06-30 13:14:28.539   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:14:28.539   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:14:28.549   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:14:28.549   774  1495 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 13:14:28.549   774  1495 D BatteryService: stay LED for fully charged
,06-30 13:14:28.559  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:28.559  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:28.559  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:28.579  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:28.589  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:28.589  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:34.749   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:14:41.489   774  1583 E Watchdog: !@Sync 49 [06-30 13:14:41.501]
,06-30 13:14:44.799   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:14:54.859   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:14:56.149   774  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:14:56.149   774  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:14:56.149   774  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:14:58.609   774  1641 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:58.619   774  1641 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:14:58.619   774  1641 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:14:58.619   774   774 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:58.629   774   774 I MotionRecognitionService: Plugged
,06-30 13:14:58.629   774   774 D MotionRecognitionService:   cableConnection= 1
,06-30 13:14:58.629   774   774 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:14:58.639   774   774 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:14:58.639   774  1641 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:14:58.649   774  1641 D BatteryService: stay LED for fully charged
,06-30 13:14:58.659  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:58.659  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:58.659  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:58.679  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:58.679  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:58.689  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:59.229   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:14:59.229   774  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:14:59.239   774  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:14:59.249   774  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:15:04.909   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:15:11.499   774  1583 E Watchdog: !@Sync 50 [06-30 13:15:11.507]
,06-30 13:15:14.029  1667  1782 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:15:14.199  1667  1782 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 157ms lastUpdatedAfter : 180269ms
,06-30 13:15:14.969   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:15:15.799   774  2438 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 13:15:15.799   774  2438 V MARsPolicyManager: updateSMDBValues
,06-30 13:15:15.799   774   904 E MARsDBManager: updateDBAll : begin --size 0
,06-30 13:15:15.809   774   904 E MARsDBManager: updateDBAll : end
,06-30 13:15:25.019   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:15:28.669   774   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:34.499   774  1737 I ActivityManager: Killing 6722:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 737s, lastActivityTime 737s
,06-30 13:15:34.509   774  1737 I ActivityManager: Killing 6664:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 738s, lastActivityTime 738s
,06-30 13:15:34.519   774  1737 I ActivityManager: Killing 6636:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 889s, lastActivityTime 889s
,06-30 13:15:34.519   774  1737 I ActivityManager: Killing 6622:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 899s, lastActivityTime 899s
,06-30 13:15:34.539  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:15:34.569  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:15:34.569  1974  1974 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:15:34.649   291   291 I ServiceManager: service 'AtCmdFwd' died
,06-30 13:15:34.659   367  4975 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 13:15:34.659   367  4975 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:15:34.659   774  1697 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 13:15:34.659   774  1697 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 13:15:34.659   774  1697 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 13:15:34.679  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:15:34.679  4841  4873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:15:34.679   305  1126 D EnterpriseController: netId is 0
06-30 13:15:34.679   305  1126 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 13:15:34.689   774   786 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 13:15:34.689   774   786 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 13:15:34.689   774   786 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10967ms
,06-30 13:15:34.709   774  1737 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
06-30 13:15:34.709   774  1737 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 13:15:34.719   774  1737 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20947ms
,06-30 13:15:34.729   774  1642 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
06-30 13:15:34.729   774  1642 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 13:15:34.729   774  1642 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 30933ms
,06-30 13:15:35.129   774  3386 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:15:35.659   367  4975 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:15:35.729  6837  6837 E Zygote  : v2
,06-30 13:15:35.729   774   841 I ActivityManager: Start proc 6837:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 13:15:35.729  6837  6837 I libpersona: KNOX_SDCARD checking this for 1000
,06-30 13:15:35.729  6837  6837 I libpersona: KNOX_SDCARD not a persona
,06-30 13:15:35.739  6837  6837 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 13:15:35.739  6837  6837 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:15:35.739  6837  6837 E Zygote  : accessInfo : 0
,06-30 13:15:35.789  6837  6837 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:15:35.789  6837  6837 D ActivityThread: Added TimaKeyStore provider
,06-30 13:15:35.809  6837  6837 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 13:15:35.819  6837  6837 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 13:15:35.829  6837  6837 D AtFwdService: onCreate method
,06-30 13:15:35.829  6837  6837 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 13:15:35.839  6837  6849 D AtCkpdCmdHandler: De-queing command
,TIME-OUT KILL (timeout was 1400000ms),06-30 13:15:40.509  2351  2351 E audit   : type=1400 msg=audit(1467285340.509:284): avc:  denied  { execmod } for  pid=6851 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:15:40.519  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:15:40.519  2351  2351 E audit   : type=1300 msg=audit(1467285340.509:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa3000 a1=51000 a2=5 a3=4 items=0 ppid=3510 ppcomm=adbd pid=6851 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:15:40.519  2351  2351 E audit   : type=1327 msg=audit(1467285340.509:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 13:15:40.529  2351  2351 E audit   : type=1320 msg=audit(1467285340.509:284): 
06-30 13:15:40.569  2351  2351 E audit   : type=1400 msg=audit(1467285340.559:285): avc:  denied  { execmod } for  pid=6851 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:15:40.569  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:15:40.569  2351  2351 E audit   : type=1300 msg=audit(1467285340.559:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f63000 a1=51000 a2=5 a3=4 items=0 ppid=3510 ppcomm=adbd pid=6851 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:15:40.569  2351  2351 E audit   : type=1327 msg=audit(1467285340.559:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 13:15:40.579  2351  2351 E audit   : type=1320 msg=audit(1467285340.559:285): 
06-30 13:15:40.609  2351  2351 E audit   : type=1400 msg=audit(1467285340.609:286): avc:  denied  { execmod } for  pid=6851 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:15:40.609  6851  6851 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:15:40.609  2351  2351 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:15:40.619  6851  6851 D AndroidRuntime: CheckJNI is OFF
06-30 13:15:40.619  6851  6851 D AndroidRuntime: readGMSProperty: start
06-30 13:15:40.619  6851  6851 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:15:40.619  2351  2351 E audit   : type=1300 msg=audit(1467285340.609:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f63000 a1=51000 a2=5 a3=4 items=0 ppid=3510 ppcomm=adbd pid=6851 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:15:40.619  6851  6851 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:15:40.619  6851  6851 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:15:40.619  6851  6851 D AndroidRuntime: readGMSProperty: end
06-30 13:15:40.619  6851  6851 D AndroidRuntime: addProductProperty: start
06-30 13:15:40.619  2351  2351 E audit   : type=1327 msg=audit(1467285340.609:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 13:15:40.619  2351  2351 E audit   : type=1320 msg=audit(1467285340.609:286): 
06-30 13:15:40.619  6851  6851 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 13:15:40.619  6851  6851 W art     : aedca000-b1cf0000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:15:40.619  6851  6851 W art     : b1cf0000-b3f5f000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:15:40.629  6851  6851 W art     : b3f5f000-b3f60000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:15:40.629  6851  6851 W art     : b3f60000-b3f61000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.629  6851  6851 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
06-30 13:15:40.629  6851  6851 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
06-30 13:15:40.629  6851  6851 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
06-30 13:15:40.629  6851  6851 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 13:15:40.629  6851  6851 W art     : b4809000-b4832000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 13:15:40.629  6851  6851 W art     : b4832000-b4835000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
06-30 13:15:40.629  6851  6851 W art     : b4835000-b4836000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
06-30 13:15:40.629  6851  6851 W art     : b4836000-b4837000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
06-30 13:15:40.629  6851  6851 W art     : b4837000-b4838000 r--p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b4838000-b4858000 r--s 00000000 00:0b 9219       /dev/__properties__
06-30 13:15:40.629  6851  6851 W art     : b4858000-b5269000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
06-30 13:15:40.629  6851  6851 W art     : b5269000-b526a000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b526a000-b52b3000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
06-30 13:15:40.629  6851  6851 W art     : b52b3000-b52b4000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
06-30 13:15:40.629  6851  6851 W art     : b52b4000-b52bc000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b52bc000-b52bd000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.629  6851  6851 W art     : b52bd000-b52f2000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
06-30 13:15:40.629  6851  6851 W art     : b52f2000-b52f3000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b52f3000-b52f4000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
06-30 13:15:40.629  6851  6851 W art     : b52f4000-b52f5000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
06-30 13:15:40.629  6851  6851 W art     : b52f5000-b534d000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
06-30 13:15:40.629  6851  6851 W art     : b534d000-b534e000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b534e000-b534f000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
06-30 13:15:40.629  6851  6851 W art     : b534f000-b5350000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
06-30 13:15:40.629  6851  6851 W art     : b5351000-b5357000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:15:40.629  6851  6851 W art     : b5357000-b5358000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:15:40.629  6851  6851 W art     : b5358000-b5359000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:15:40.629  6851  6851 W art     : b5359000-b535b000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b535c000-b5366000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 13:15:40.629  6851  6851 W art     : b5366000-b5369000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 13:15:40.629  6851  6851 W art     : b5369000-b536a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 13:15:40.629  6851  6851 W art     : b536b000-b5382000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 13:15:40.629  6851  6851 W art     : b5382000-b5383000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5383000-b5384000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 13:15:40.629  6851  6851 W art     : b5384000-b5385000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 13:15:40.629  6851  6851 W art     : b5386000-b5390000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
06-30 13:15:40.629  6851  6851 W art     : b5390000-b5391000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
06-30 13:15:40.629  6851  6851 W art     : b5391000-b5392000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
06-30 13:15:40.629  6851  6851 W art     : b5392000-b5396000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 13:15:40.629  6851  6851 W art     : b5396000-b5397000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 13:15:40.629  6851  6851 W art     : b5397000-b5398000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 13:15:40.629  6851  6851 W art     : b5398000-b53ae000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
06-30 13:15:40.629  6851  6851 W art     : b53ae000-b53af000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
06-30 13:15:40.629  6851  6851 W art     : b53af000-b53b0000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
06-30 13:15:40.629  6851  6851 W art     : b53b0000-b53bd000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
06-30 13:15:40.629  6851  6851 W art     : b53bd000-b53be000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
06-30 13:15:40.629  6851  6851 W art     : b53be000-b53bf000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
06-30 13:15:40.629  6851  6851 W art     : b53bf000-b541f000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
06-30 13:15:40.629  6851  6851 W art     : b541f000-b5422000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
06-30 13:15:40.629  6851  6851 W art     : b5422000-b5426000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5426000-b5487000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
06-30 13:15:40.629  6851  6851 W art     : b5487000-b5488000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
06-30 13:15:40.629  6851  6851 W art     : b5488000-b54d7000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
06-30 13:15:40.629  6851  6851 W art     : b54d7000-b54d9000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
06-30 13:15:40.629  6851  6851 W art     : b54d9000-b54da000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
06-30 13:15:40.629  6851  6851 W art     : b54da000-b54db000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b54db000-b54e2000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 13:15:40.629  6851  6851 W art     : b54e2000-b54e3000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 13:15:40.629  6851  6851 W art     : b54e3000-b54e4000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
06-30 13:15:40.629  6851  6851 W art     : avc_common.so
06-30 13:15:40.629  6851  6851 W art     : b54e5000-b54e8000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 13:15:40.629  6851  6851 W art     : b54e8000-b54e9000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 13:15:40.629  6851  6851 W art     : b54e9000-b54ea000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
06-30 13:15:40.629  6851  6851 W art     : enc_common.so
06-30 13:15:40.629  6851  6851 W art     : b54eb000-b54ef000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
06-30 13:15:40.629  6851  6851 W art     : b54ef000-b54f0000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b54f0000-b54f1000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
06-30 13:15:40.629  6851  6851 W art     : b54f1000-b54f2000 rw-p 00005000 b3:17 2510       /syste
06-30 13:15:40.629  6851  6851 W art     : m/lib/libpowermanager.so
06-30 13:15:40.629  6851  6851 W art     : b54f3000-b5510000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 13:15:40.629  6851  6851 W art     : b5510000-b5511000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 13:15:40.629  6851  6851 W art     : b5511000-b5512000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 13:15:40.629  6851  6851 W art     : b5513000-b5518000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 13:15:40.629  6851  6851 W art     : b5518000-b5519000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 13:15:40.629  6851  6851 W art     : b5519000-b551a000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 13:15:40.629  6851  6851 W art     : b551b000-b554c000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 13:15:40.629  6851  6851 W art     : b554c000-b554f000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 13:15:40.629  6851  6851 W art     : b554f000-b5550000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 13:15:40.629  6851  6851 W art     : b5551000-b558c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
06-30 13:15:40.629  6851  6851 W art     : b558c000-b558d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
06-30 13:15:40.629  6851  6851 W art     : b558d000-b558e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
06-30 13:15:40.629  6851  6851 W art     : b558f000-b5596000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
06-30 13:15:40.629  6851  6851 W art     : b5596000-b5597000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5597000-b5598000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
06-30 13:15:40.629  6851  6851 W art     : b5598000-b5599000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
06-30 13:15:40.629  6851  6851 W art     : b5599000-b559a000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.629  6851  6851 W art     : b559a000-b55b1000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
06-30 13:15:40.629  6851  6851 W art     : b55b1000-b55b2000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b55b2000-b55b5000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
06-30 13:15:40.629  6851  6851 W art     : b55b5000-b55b6000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
06-30 13:15:40.629  6851  6851 W art     : b55b6000-b55d5000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
06-30 13:15:40.629  6851  6851 W art     : b55d5000-b55d6000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
06-30 13:15:40.629  6851  6851 W art     : b55d6000-b55d7000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
06-30 13:15:40.629  6851  6851 W art     : b55d7000-b5615000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 13:15:40.629  6851  6851 W art     : b5615000-b5616000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5616000-b5618000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 13:15:40.629  6851  6851 W art     : b5618000-b5619000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 13:15:40.629  6851  6851 W art     : b561a000-b5621000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 13:15:40.629  6851  6851 W art     : b5621000-b5622000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 13:15:40.629  6851  6851 W art     : b5622000-b5623000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 13:15:40.629  6851  6851 W art     : b5624000-b5627000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 13:15:40.629  6851  6851 W art     : b5627000-b5628000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 13:15:40.629  6851  6851 W art     : b5628000-b5629000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 13:15:40.629  6851  6851 W art     : b5629000-b562f000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:15:40.629  6851  6851 W art     : b562f000-b5630000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5630000-b5631000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:15:40.629  6851  6851 W art     : b5631000-b5632000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:15:40.629  6851  6851 W art     : b5632000-b563b000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
06-30 13:15:40.629  6851  6851 W art     : b563b000-b563c000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
06-30 13:15:40.629  6851  6851 W art     : b563c000-b563d000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
06-30 13:15:40.629  6851  6851 W art     : b563d000-b56ce000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 13:15:40.629  6851  6851 W art     : b56ce000-b56cf000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b56cf000-b56da000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 13:15:40.629  6851  6851 W art     : b56da000-b56db000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 13:15:40.629  6851  6851 W art     : b56dc000-b56ee000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
06-30 13:15:40.629  6851  6851 W art     : b56ee000-b56ef000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
06-30 13:15:40.629  6851  6851 W art     : b56ef000-b56f0000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
06-30 13:15:40.629  6851  6851 W art     : b56f1000-b56f6000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
06-30 13:15:40.629  6851  6851 W art     : b56f6000-b56f7000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
06-30 13:15:40.629  6851  6851 W art     : b56f7000-b56f8000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
06-30 13:15:40.629  6851  6851 W art     : b56f9000-b5766000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
06-30 13:15:40.629  6851  6851 W art     : b5766000-b5767000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5767000-b5769000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
06-30 13:15:40.629  6851  6851 W art     : b5769000-b576a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
06-30 13:15:40.629  6851  6851 W art     : b576a000-b576b000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.629  6851  6851 W art     : b576b000-b5772000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:15:40.629  6851  6851 W art     : b5772000-b5773000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:15:40.629  6851  6851 W art     : b5773000-b5774000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:15:40.629  6851  6851 W art     : b5775000-b57f5000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 13:15:40.629  6851  6851 W art     : b57f5000-b57f6000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b57f6000-b57f7000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 13:15:40.629  6851  6851 W art     : b57f7000-b57f8000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 13:15:40.629  6851  6851 W art     : b57f8000-b580f000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b580f000-b5846000 r-xp 00000000 b3:17 3244       /system/vendor/l
06-30 13:15:40.629  6851  6851 W art     : ib/libqc-opt.so
06-30 13:15:40.629  6851  6851 W art     : b5846000-b5847000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 13:15:40.629  6851  6851 W art     : b5847000-b5848000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 13:15:40.629  6851  6851 W art     : b5848000-b5864000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 13:15:40.629  6851  6851 W art     : b5864000-b5865000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 13:15:40.629  6851  6851 W art     : b5865000-b5866000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 13:15:40.629  6851  6851 W art     : b5867000-b58c8000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 13:15:40.629  6851  6851 W art     : b58c8000-b58ca000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 13:15:40.629  6851  6851 W art     : b58ca000-b58cb000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 13:15:40.629  6851  6851 W art     : b58cc000-b58f3000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
06-30 13:15:40.629  6851  6851 W art     : b58f3000-b58f4000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b58f4000-b58f5000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
06-30 13:15:40.629  6851  6851 W art     : b58f5000-b58f6000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
06-30 13:15:40.629  6851  6851 W art     : b58f7000-b58ff000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 13:15:40.629  6851  6851 W art     : b58ff000-b5901000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 13:15:40.629  6851  6851 W art     : b5901000-b5902000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 13:15:40.629  6851  6851 W art     : b5903000-b5906000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
06-30 13:15:40.629  6851  6851 W art     : b5906000-b5907000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
06-30 13:15:40.629  6851  6851 W art     : b5907000-b5908000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
06-30 13:15:40.629  6851  6851 W art     : b5908000-b590c000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
06-30 13:15:40.629  6851  6851 W art     : b590c000-b590d000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b590d000-b590e000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
06-30 13:15:40.629  6851  6851 W art     : b590e000-b590f000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
06-30 13:15:40.629  6851  6851 W art     : b590f000-b591f000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
06-30 13:15:40.629  6851  6851 W art     : b591f000-b5920000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
06-30 13:15:40.629  6851  6851 W art     : b5920000-b5921000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
06-30 13:15:40.629  6851  6851 W art     : b5921000-b5967000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5967000-b5970000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
06-30 13:15:40.629  6851  6851 W art     : b5970000-b5971000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
06-30 13:15:40.629  6851  6851 W art     : b5971000-b5972000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
06-30 13:15:40.629  6851  6851 W art     : b5973000-b5978000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
06-30 13:15:40.629  6851  6851 W art     : b5978000-b5979000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
06-30 13:15:40.629  6851  6851 W art     : b5979000-b597a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
06-30 13:15:40.629  6851  6851 W art     : b597a000-b597d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 13:15:40.629  6851  6851 W art     : b597d000-b597e000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b597e000-b597f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 13:15:40.629  6851  6851 W art     : b597f000-b5980000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 13:15:40.629  6851  6851 W art     : b5981000-b5999000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:15:40.629  6851  6851 W art     : b5999000-b599a000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b599a000-b599b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:15:40.629  6851  6851 W art     : b599b000-b599c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:15:40.629  6851  6851 W art     : b599d000-b5b37000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
06-30 13:15:40.629  6851  6851 W art     : b5b37000-b5b38000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5b38000-b5b45000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
06-30 13:15:40.629  6851  6851 W art     : b5b45000-b5b46000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
06-30 13:15:40.629  6851  6851 W art     : b5b46000-b5b4a000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
06-30 13:15:40.629  6851  6851 W art     : b5b4a000-b5b4b000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5b4b000-b5b4c000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
06-30 13:15:40.629  6851  6851 W art     : b5b4c000-b5b4d000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
06-30 13:15:40.629  6851  6851 W art     : b5b4d000-b5b60000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
06-30 13:15:40.629  6851  6851 W art     : b5b60000-b5b61000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
06-30 13:15:40.629  6851  6851 W art     : b5b61000-b5b62000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
06-30 13:15:40.629  6851  6851 W art     : b5b62000-b5b63000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:15:40.629  6851  6851 W art     : b5b63000-b5bae000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
06-30 13:15:40.629  6851  6851 W art     : b5bae000-b5baf000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
06-30 13:15:40.629  6851  6851 W art     : b5baf000-b5bb0000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
06-30 13:15:40.629  6851  6851 W art     : b5bb0000-b5bb2000 rw-p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5bb3000-b5bc4000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 13:15:40.629  6851  6851 W art     : b5bc4000-b5bc5000 ---p 00000000 00:00 0 
06-30 13:15:40.629  6851  6851 W art     : b5bc5000-b5bc6000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 13:15:40.629  6851  6851 W art     : b5bc6000-b5bc7000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 13:15:40.629  6851  6851 W art     : b5bc8000-b5bd2000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
06-30 13:15:40.639  6851  6851 W art     : b5bd2000-b5bd4000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
06-30 13:15:40.639  6851  6851 W art     : b5bd4000-b5bd5000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
06-30 13:15:40.639  6851  6851 W art     : b5bd5000-b5bee000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
06-30 13:15:40.639  6851  6851 W art     : b5bee000-b5bef000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
06-30 13:15:40.639  6851  6851 W art     : b5bef000-b5bf2000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
06-30 13:15:40.639  6851  6851 W art     : b5bf2000-b5bf6000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b5bf6000-b5c6a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
06-30 13:15:40.639  6851  6851 W art     : b5c6a000-b5c6b000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b5c6b000-b5c6e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
06-30 13:15:40.639  6851  6851 W art     : b5c6e000-b5c6f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
06-30 13:15:40.639  6851  6851 W art     : b5c6f000-b5c70000 r--p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b5c70000-b5c73000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
06-30 13:15:40.639  6851  6851 W art     : b5c73000-b5c74000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
06-30 13:15:40.639  6851  6851 W art     : b5c74000-b5c75000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
06-30 13:15:40.639  6851  6851 W art     : b5c75000-b5c76000 r--p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b5c76000-b5c7b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 13:15:40.639  6851  6851 W art     : b5c7b000-b5c7c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 13:15:40.639  6851  6851 W art     : b5c7c000-b5c7d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 13:15:40.639  6851  6851 W art     : b5c7d000-b5c7e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b5c7e000-b5c81000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 13:15:40.639  6851  6851 W art     : b5c81000-b5c82000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 13:15:40.639  6851  6851 W art     : b5c82000-b5c83000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 13:15:40.639  6851  6851 W art     : b5c83000-b5c84000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b5c84000-b5c88000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
06-30 13:15:40.639  6851  6851 W art     : b5c88000-b5c89000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
06-30 13:15:40.639  6851  6851 W art     : b5c89000-b5c8a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
06-30 13:15:40.639  6851  6851 W art     : b5c8a000-b5c8b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:15:40.639  6851  6851 W art     : b5c8b000-b5c8f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 13:15:40.639  6851  6851 W art     : b5c8f000-b5c90000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 13:15:40.639  6851  6851 W art     : b5c90000-b5c91000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 13:15:40.639  6851  6851 W art     : b5c91000-b5c92000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b5c92000-b5ca0000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 13:15:40.639  6851  6851 W art     : b5ca0000-b5ca1000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b5ca1000-b5ca2000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 13:15:40.639  6851  6851 W art     : b5ca2000-b5ca3000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 13:15:40.639  6851  6851 W art     : b5ca3000-b5cad000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 13:15:40.639  6851  6851 W art     : b5cad000-b5cb0000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 13:15:40.639  6851  6851 W art     : b5cb0000-b5cb1000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 13:15:40.639  6851  6851 W art     : b5cb1000-b5cb2000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b5cb2000-b5cbc000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
06-30 13:15:40.639  6851  6851 W art     : b5cbc000-b5cbf000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
06-30 13:15:40.639  6851  6851 W art     : b5cbf000-b5cc0000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
06-30 13:15:40.639  6851  6851 W art     : b5cc0000-b5cc4000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
06-30 13:15:40.639  6851  6851 W art     : b5cc4000-b5cc5000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
06-30 13:15:40.639  6851  6851 W art     : b5cc5000-b5cc6000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
06-30 13:15:40.639  6851  6851 W art     : b5cc6000-b5cc7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b5cc7000-b5cd4000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:15:40.639  6851  6851 W art     : b5cd4000-b5cd6000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:15:40.639  6851  6851 W art     : b5cd6000-b5cd7000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:15:40.639  6851  6851 W art     : b5cd7000-b60e9000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
06-30 13:15:40.639  6851  6851 W art     : b60e9000-b60ea000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b60ea000-b60f3000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
06-30 13:15:40.639  6851  6851 W art     : b60f3000-b60f7000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
06-30 13:15:40.639  6851  6851 W art     : b60f7000-b60f8000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b60f8000-b60ff000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:15:40.639  6851  6851 W art     : b60ff000-b6100000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:15:40.639  6851  6851 W art     : b6100000-b6101000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:15:40.639  6851  6851 W art     : b6101000-b6102000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6102000-b611d000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 13:15:40.639  6851  6851 W art     : b611d000-b611e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 13:15:40.639  6851  6851 W art     : b611e000-b611f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 13:15:40.639  6851  6851 W art     : b611f000-b6120000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6120000-b616c000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 13:15:40.639  6851  6851 W art     : b616c000-b616d000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b616d000-b616e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 13:15:40.639  6851  6851 W art     : b616e000-b616f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 13:15:40.639  6851  6851 W art     : b616f000-b6170000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6170000-b6174000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
06-30 13:15:40.639  6851  6851 W art     : b6174000-b6175000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6175000-b6176000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
06-30 13:15:40.639  6851  6851 W art     : b6176000-b6177000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
06-30 13:15:40.639  6851  6851 W art     : b6177000-b61af000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
06-30 13:15:40.639  6851  6851 W art     : b61af000-b61b0000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
06-30 13:15:40.639  6851  6851 W art     : b61b0000-b61b1000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
06-30 13:15:40.639  6851  6851 W art     : b61b1000-b61b2000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b61b2000-b6250000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
06-30 13:15:40.639  6851  6851 W art     : b6250000-b6251000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6251000-b626f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
06-30 13:15:40.639  6851  6851 W art     : b626f000-b6270000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
06-30 13:15:40.639  6851  6851 W art     : b6270000-b63e3000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
06-30 13:15:40.639  6851  6851 W art     : b63e3000-b63ee000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
06-30 13:15:40.639  6851  6851 W art     : b63ee000-b63ef000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
06-30 13:15:40.639  6851  6851 W art     : b63ef000-b6506000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:15:40.639  6851  6851 W art     : b6506000-b6511000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:15:40.639  6851  6851 W art     : b6511000-b6512000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:15:40.639  6851  6851 W art     : b6512000-b6516000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6516000-b653a000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
06-30 13:15:40.639  6851  6851 W art     : b653a000-b653c000 r--p 00023000 b3:17 400        /system/lib/libssl.so
06-30 13:15:40.639  6851  6851 W art     : b653c000-b653d000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
06-30 13:15:40.639  6851  6851 W art     : b653d000-b65e3000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
06-30 13:15:40.639  6851  6851 W art     : b65e3000-b65f0000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
06-30 13:15:40.639  6851  6851 W art     : b65f0000-b65f1000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
06-30 13:15:40.639  6851  6851 W art     : b65f1000-b65f2000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b65f2000-b6645000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
06-30 13:15:40.639  6851  6851 W art     : b6645000-b6646000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6646000-b6647000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
06-30 13:15:40.639  6851  6851 W art     : b6647000-b6648000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
06-30 13:15:40.639  6851  6851 W art     : b6648000-b664d000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b664d000-b665f000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
06-30 13:15:40.639  6851  6851 W art     : b665f000-b6660000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6660000-b6661000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
06-30 13:15:40.639  6851  6851 W art     : b6661000-b6662000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
06-30 13:15:40.639  6851  6851 W art     : b6662000-b6669000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 13:15:40.639  6851  6851 W art     : b6669000-b666a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 13:15:40.639  6851  6851 W art     : b666a000-b666b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 13:15:40.639  6851  6851 W art     : b666b000-b666c000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b666c000-b666f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
06-30 13:15:40.639  6851  6851 W art     : b666f000-b6670000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
06-30 13:15:40.639  6851  6851 W art     : b6670000-b6671000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
06-30 13:15:40.639  6851  6851 W art     : b6671000-b6675000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
06-30 13:15:40.639  6851  6851 W art     : b6675000-b6676000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
06-30 13:15:40.639  6851  6851 W art     : b6676000-b6677000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
06-30 13:15:40.639  6851  6851 W art     : b6677000-b6685000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
06-30 13:15:40.639  6851  6851 W art     : b6685000-b6686000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6686000-b6687000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
06-30 13:15:40.639  6851  6851 W art     : b6687000-b6688000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
06-30 13:15:40.639  6851  6851 W art     : b6688000-b6691000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 13:15:40.639  6851  6851 W art     : b6691000-b6692000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 13:15:40.639  6851  6851 W art     : b6692000-b6693000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 13:15:40.639  6851  6851 W art     : b6693000-b66f9000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
06-30 13:15:40.639  6851  6851 W art     : b66f9000-b66fa000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b66fa000-b66fc000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
06-30 13:15:40.639  6851  6851 W art     : b66fc000-b6705000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
06-30 13:15:40.639  6851  6851 W art     : b6705000-b6708000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6708000-b679f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 13:15:40.639  6851  6851 W art     : b679f000-b67a1000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 13:15:40.639  6851  6851 W art     : b67a1000-b67a2000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 13:15:40.639  6851  6851 W art     : b67a2000-b67a3000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b67a3000-b6ac4000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
06-30 13:15:40.639  6851  6851 W art     : b6ac4000-b6ac5000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6ac5000-b6ae0000 r--p 00321000 b3:17 377        /system/lib/libskia.so
06-30 13:15:40.639  6851  6851 W art     : b6ae0000-b6ae4000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
06-30 13:15:40.639  6851  6851 W art     : b6ae4000-b6ae9000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6ae9000-b6af1000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 13:15:40.639  6851  6851 W art     : b6af1000-b6af2000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 13:15:40.639  6851  6851 W art     : b6af2000-b6af3000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 13:15:40.639  6851  6851 W art     : b6af3000-b6b21000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:15:40.639  6851  6851 W art     : b6b21000-b6b22000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6b22000-b6b29000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:15:40.639  6851  6851 W art     : b6b29000-b6b2a000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:15:40.639  6851  6851 W art     : b6b2a000-b6b70000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:15:40.639  6851  6851 W art     : b6b70000-b6b71000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6b71000-b6b74000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:15:40.639  6851  6851 W art     : b6b74000-b6b75000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:15:40.639  6851  6851 W art     : b6b75000-b6b90000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
06-30 13:15:40.639  6851  6851 W art     : b6b90000-b6b94000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
06-30 13:15:40.639  6851  6851 W art     : b6b94000-b6b95000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
06-30 13:15:40.639  6851  6851 W art     : b6b95000-b6be2000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
06-30 13:15:40.639  6851  6851 W art     : b6be2000-b6be3000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6be3000-b6bef000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
06-30 13:15:40.639  6851  6851 W art     : b6bef000-b6bf0000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
06-30 13:15:40.639  6851  6851 W art     : b6bf0000-b6bfd000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
06-30 13:15:40.639  6851  6851 W art     : b6bfd000-b6bfe000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6bfe000-b6bff000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
06-30 13:15:40.639  6851  6851 W art     : b6bff000-b6c00000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
06-30 13:15:40.639  6851  6851 W art     : b6c00000-b6c08000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
06-30 13:15:40.639  6851  6851 W art     : b6c08000-b6c09000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6c09000-b6c0a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
06-30 13:15:40.639  6851  6851 W art     : b6c0a000-b6c0b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
06-30 13:15:40.639  6851  6851 W art     : b6c0b000-b6c12000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:15:40.639  6851  6851 W art     : b6c12000-b6c13000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:15:40.639  6851  6851 W art     : b6c13000-b6c14000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:15:40.639  6851  6851 W art     : b6c14000-b6c28000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
06-30 13:15:40.639  6851  6851 W art     : b6c28000-b6c2a000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
06-30 13:15:40.639  6851  6851 W art     : b6c2a000-b6c2b000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
06-30 13:15:40.639  6851  6851 W art     : b6c2b000-b6c53000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
06-30 13:15:40.639  6851  6851 W art     : b6c53000-b6c55000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
06-30 13:15:40.639  6851  6851 W art     : b6c55000-b6c56000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
06-30 13:15:40.639  6851  6851 W art     : b6c56000-b6c59000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
06-30 13:15:40.639  6851  6851 W art     : b6c59000-b6c5a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
06-30 13:15:40.639  6851  6851 W art     : b6c5a000-b6c5b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
06-30 13:15:40.639  6851  6851 W art     : b6c5b000-b6c64000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:15:40.639  6851  6851 W art     : b6c64000-b6c65000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:15:40.639  6851  6851 W art     : b6c65000-b6c66000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:15:40.639  6851  6851 W art     : b6c66000-b6c86000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 13:15:40.639  6851  6851 W art     : b6c86000-b6c87000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 13:15:40.639  6851  6851 W art     : b6c87000-b6c88000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 13:15:40.639  6851  6851 W art     : b6c88000-b6cfb000 r-xp 00000000 b3:17 860        /system/lib/libc.so
06-30 13:15:40.639  6851  6851 W art     : b6cfb000-b6cff000 r--p 00072000 b3:17 860        /system/lib/libc.so
06-30 13:15:40.639  6851  6851 W art     : b6cff000-b6d02000 rw-p 00076000 b3:17 860        /system/lib/libc.so
06-30 13:15:40.639  6851  6851 W art     : b6d02000-b6d0c000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6d0c000-b6d94000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 13:15:40.639  6851  6851 W art     : b6d94000-b6d95000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6d95000-b6d99000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 13:15:40.639  6851  6851 W art     : b6d99000-b6d9a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 13:15:40.639  6851  6851 W art     : b6d9a000-b6d9b000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6d9b000-b6dc4000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:15:40.639  6851  6851 W art     : b6dc4000-b6dc5000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6dc5000-b6dc8000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:15:40.639  6851  6851 W art     : b6dc8000-b6dc9000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:15:40.639  6851  6851 W art     : b6dc9000-b6ea3000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 13:15:40.639  6851  6851 W art     : b6ea3000-b6eaa000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 13:15:40.639  6851  6851 W art     : b6eaa000-b6eb2000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 13:15:40.639  6851  6851 W art     : b6eb2000-b6eb3000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6eb3000-b6eb4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:15:40.639  6851  6851 W art     : b6eb4000-b6eb5000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 13:15:40.639  6851  6851 W art     : b6eb5000-b6eb6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6eb6000-b6eb9000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6eb9000-b6ede000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
06-30 13:15:40.639  6851  6851 W art     : b6ede000-b6edf000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6edf000-b6ee6000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
06-30 13:15:40.639  6851  6851 W art     : b6ee6000-b6ee7000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
06-30 13:15:40.639  6851  6851 W art     : b6ee7000-b6eee000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 13:15:40.639  6851  6851 W art     : b6eee000-b6eef000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 13:15:40.639  6851  6851 W art     : b6eef000-b6ef0000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 13:15:40.639  6851  6851 W art     : b6ef0000-b6ef1000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6ef1000-b6f09000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
06-30 13:15:40.639  6851  6851 W art     : b6f09000-b6f0a000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6f0a000-b6f0b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
06-30 13:15:40.639  6851  6851 W art     : b6f0b000-b6f0c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
06-30 13:15:40.639  6851  6851 W art     : b6f0c000-b6f1a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
06-30 13:15:40.639  6851  6851 W art     : b6f1a000-b6f1b000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6f1b000-b6f1c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
06-30 13:15:40.639  6851  6851 W art     : b6f1c000-b6f1d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
06-30 13:15:40.639  6851  6851 W art     : b6f1d000-b6f1e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:15:40.639  6851  6851 W art     : b6f1e000-b6f20000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6f20000-b6f21000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6f21000-b6f22000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:15:40.639  6851  6851 W art     : b6f22000-b6f23000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 13:15:40.639  6851  6851 W art     : b6f23000-b6f24000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:15:40.639  6851  6851 W art     : b6f24000-b6f44000 r--s 00000000 00:0b 9219       /dev/__properties__
06-30 13:15:40.639  6851  6851 W art     : b6f44000-b6f45000 r--p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6f45000-b6f46000 ---p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6f46000-b6f48000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 13:15:40.639  6851  6851 W art     : b6f48000-b6f49000 r-xp 00000000 00:00 0          [sigpage]
06-30 13:15:40.639  6851  6851 W art     : b6f49000-b6f64000 r-xp 00000000 b3:17 2770       /system/bin/linker
06-30 13:15:40.639  6851  6851 W art     : b6f64000-b6f65000 r--p 0001a000 b3:17 2770       /system/bin/linker
06-30 13:15:40.639  6851  6851 W art     : b6f65000-b6f67000 rw-p 0001b000 b3:17 2770       /system/bin/linker
06-30 13:15:40.639  6851  6851 W art     : b6f67000-b6f69000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : b6f69000-b6f6e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 13:15:40.639  6851  6851 W art     : b6f6e000-b6f6f000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 13:15:40.639  6851  6851 W art     : b6f6f000-b6f70000 rw-p 00000000 00:00 0 
06-30 13:15:40.639  6851  6851 W art     : bef0a000-bef2b000 rw-p 00000000 00:00 0          [stack]
06-30 13:15:40.639  6851  6851 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 13:15:40.689  6851  6851 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:15:40.729  6851  6851 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:15:40.739  6851  6851 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:15:40.759  6851  6851 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 13:15:40.769   774  1643 D PackageManager: START PACKAGE DELETE: observer{155203927}
06-30 13:15:40.769   774  1643 D PackageManager: pkg{<packageName>}
06-30 13:15:40.769   774  1643 D PackageManager: user{0}
06-30 13:15:40.769   774  1643 D PackageManager: caller{2000}
06-30 13:15:40.769   774  1643 D PackageManager: flags{2}
06-30 13:15:40.769   774  1643 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 13:15:40.769   774  1643 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 13:15:40.769   774  1643 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 13:15:40.769   774  1643 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:15:40.769   774  1643 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:15:40.769   774   930 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 13:15:40.769   774   930 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 13:15:40.769   774   930 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 13:15:40.769   774   930 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 13:15:40.769   774   930 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 13:15:40.769   774   930 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 13:15:40.779   774   930 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 13:15:40.779   774   930 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
06-30 13:15:40.779   774   841 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
06-30 13:15:40.779   774   930 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 13:15:40.779   774   930 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 13:15:40.779   774   841 I ActivityManager: Killing 6297:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
06-30 13:15:40.779   774   841 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:15:40.779   774   841 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 13:15:40.789  6866  6866 E Zygote  : v2
06-30 13:15:40.799  6866  6866 I libpersona: KNOX_SDCARD checking this for 10004
06-30 13:15:40.799  6866  6866 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:40.799  6866  6866 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:15:40.799  6866  6866 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 13:15:40.799   774   841 I ActivityManager: Start proc 6866:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 13:15:40.799  6866  6866 E Zygote  : accessInfo : 0
06-30 13:15:40.799   774   841 I ActivityManager:   Force finishing activity ActivityRecord{899083f u0 com.test.thalitest/.MainActivity t64}
06-30 13:15:40.799  6866  6866 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 13:15:40.799   774   841 I ActivityManager:   Force finishing activity ActivityRecord{2348546 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}
06-30 13:15:40.809   774   841 D InputDispatcher: Focused application set to: xxxx
06-30 13:15:40.819   774   841 I ActivityManager: Killing 4584:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
06-30 13:15:40.829   774   930 D AASAinstall: there is not AASApackages.xml file
06-30 13:15:40.829   774   841 D ActivityManager: mDVFSHelper.acquire()
06-30 13:15:40.839  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:40.839  6866  6866 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:40.849  6367  6367 D ViewRootImpl: #3 mView = null
06-30 13:15:40.849   292   373 I SurfaceFlinger: id=22 Removed HrantPermis (7/9)
06-30 13:15:40.849   292  1501 I SurfaceFlinger: id=22 Removed HrantPermis (-2/9)
06-30 13:15:40.849   774  1697 D InputDispatcher: Focus left window: 6367
06-30 13:15:40.849   774  1697 D InputDispatcher: Focus entered window: 6297
06-30 13:15:40.859   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbecf93a4
06-30 13:15:40.879   292   362 D libEGL  : eglTerminate EGLDisplay = 0xb69016fc
06-30 13:15:40.889   774  1642 D GraphicsStats: Buffer count: 5
06-30 13:15:40.889   774  1698 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@21b1c44)
06-30 13:15:40.889   774  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:15:40.889   774  1421 I WindowState: WIN DEATH: Window{56aea04 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:15:40.889   292  1501 I SurfaceFlinger: id=21 Removed NainActivit (4/8)
06-30 13:15:40.889   292  4732 I SurfaceFlinger: id=21 Removed NainActivit (-2/8)
06-30 13:15:40.889   292  4732 I SurfaceFlinger: id=21 Removed NainActivit (-2/8)

```
