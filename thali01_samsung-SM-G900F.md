#### Test 80912877664003a_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
,08-12 09:21:59.996   738  1237 V AlarmManager: Expired Alarm result :8
--------- beginning of main
08-12 09:22:01.075  2152  2152 E audit   : type=1400 msg=audit(1470986521.075:284): avc:  denied  { execmod } for  pid=6872 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 09:22:01.085  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:01.085  2152  2152 E audit   : type=1300 msg=audit(1470986521.075:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f97000 a1=51000 a2=5 a3=4 items=0 ppid=3582 ppcomm=adbd pid=6872 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 09:22:01.085  2152  2152 E audit   : type=1327 msg=audit(1470986521.075:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 09:22:01.085  2152  2152 E audit   : type=1320 msg=audit(1470986521.075:284): 
08-12 09:22:01.135  2152  2152 E audit   : type=1400 msg=audit(1470986521.135:285): avc:  denied  { execmod } for  pid=6872 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 09:22:01.135  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:01.135  2152  2152 E audit   : type=1300 msg=audit(1470986521.135:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f57000 a1=51000 a2=5 a3=4 items=0 ppid=3582 ppcomm=adbd pid=6872 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 09:22:01.135  2152  2152 E audit   : type=1327 msg=audit(1470986521.135:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 09:22:01.135  2152  2152 E audit   : type=1320 msg=audit(1470986521.135:285): 
08-12 09:22:01.185  6872  6872 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 09:22:01.185  2152  2152 E audit   : type=1400 msg=audit(1470986521.175:286): avc:  denied  { execmod } for  pid=6872 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 09:22:01.185  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:01.185  2152  2152 E audit   : type=1300 msg=audit(1470986521.175:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f57000 a1=51000 a2=5 a3=4 items=0 ppid=3582 ppcomm=adbd pid=6872 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 09:22:01.185  6872  6872 D AndroidRuntime: CheckJNI is OFF
08-12 09:22:01.185  2152  2152 E audit   : type=1327 msg=audit(1470986521.175:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-12 09:22:01.185  6872  6872 D AndroidRuntime: readGMSProperty: start
08-12 09:22:01.185  6872  6872 D AndroidRuntime: readGMSProperty: already setted!!
08-12 09:22:01.185  6872  6872 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 09:22:01.185  6872  6872 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 09:22:01.185  6872  6872 D AndroidRuntime: readGMSProperty: end
08-12 09:22:01.185  6872  6872 D AndroidRuntime: addProductProperty: start
08-12 09:22:01.195  2152  2152 E audit   : type=1320 msg=audit(1470986521.175:286): 
08-12 09:22:01.195  6872  6872 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 09:22:01.195  6872  6872 W art     : aedbe000-b1ce4000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-12 09:22:01.195  6872  6872 W art     : b1ce4000-b3f53000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-12 09:22:01.195  6872  6872 W art     : b3f53000-b3f54000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-12 09:22:01.195  6872  6872 W art     : b3f54000-b3f55000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.195  6872  6872 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-12 09:22:01.195  6872  6872 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-12 09:22:01.195  6872  6872 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-12 09:22:01.195  6872  6872 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-12 09:22:01.195  6872  6872 W art     : b4803000-b482c000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 09:22:01.195  6872  6872 W art     : b482c000-b482f000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 09:22:01.195  6872  6872 W art     : b482f000-b4830000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-12 09:22:01.195  6872  6872 W art     : b4830000-b4831000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 09:22:01.195  6872  6872 W art     : b4831000-b4832000 r--p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b4832000-b4852000 r--s 00000000 00:0b 7179       /dev/__properties__
08-12 09:22:01.195  6872  6872 W art     : b4852000-b5263000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 09:22:01.195  6872  6872 W art     : b5263000-b5264000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5264000-b52ad000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-12 09:22:01.195  6872  6872 W art     : b52ad000-b52ae000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 09:22:01.195  6872  6872 W art     : b52ae000-b52b6000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b52b6000-b52b7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.195  6872  6872 W art     : b52b7000-b52ec000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 09:22:01.195  6872  6872 W art     : b52ec000-b52ed000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b52ed000-b52ee000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 09:22:01.195  6872  6872 W art     : b52ee000-b52ef000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-12 09:22:01.195  6872  6872 W art     : b52ef000-b5347000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 09:22:01.195  6872  6872 W art     : b5347000-b5348000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5348000-b5349000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 09:22:01.195  6872  6872 W art     : b5349000-b534a000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-12 09:22:01.195  6872  6872 W art     : b534b000-b5351000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 09:22:01.195  6872  6872 W art     : b5351000-b5352000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 09:22:01.195  6872  6872 W art     : b5352000-b5353000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 09:22:01.195  6872  6872 W art     : b5353000-b5355000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5356000-b5360000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 09:22:01.195  6872  6872 W art     : b5360000-b5363000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 09:22:01.195  6872  6872 W art     : b5363000-b5364000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 09:22:01.195  6872  6872 W art     : b5365000-b537c000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 09:22:01.195  6872  6872 W art     : b537c000-b537d000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b537d000-b537e000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 09:22:01.195  6872  6872 W art     : b537e000-b537f000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 09:22:01.195  6872  6872 W art     : b5380000-b538a000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 09:22:01.195  6872  6872 W art     : b538a000-b538b000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-12 09:22:01.195  6872  6872 W art     : b538b000-b538c000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 09:22:01.195  6872  6872 W art     : b538c000-b5390000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 09:22:01.195  6872  6872 W art     : b5390000-b5391000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 09:22:01.195  6872  6872 W art     : b5391000-b5392000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 09:22:01.195  6872  6872 W art     : b5392000-b53a8000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-12 09:22:01.195  6872  6872 W art     : b53a8000-b53a9000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 09:22:01.195  6872  6872 W art     : b53a9000-b53aa000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 09:22:01.195  6872  6872 W art     : b53aa000-b53b7000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 09:22:01.195  6872  6872 W art     : b53b7000-b53b8000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 09:22:01.195  6872  6872 W art     : b53b8000-b53b9000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 09:22:01.195  6872  6872 W art     : b53b9000-b5419000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-12 09:22:01.195  6872  6872 W art     : b5419000-b541c000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 09:22:01.195  6872  6872 W art     : b541c000-b5420000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5420000-b5481000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 09:22:01.195  6872  6872 W art     : b5481000-b5482000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 09:22:01.195  6872  6872 W art     : b5482000-b54d1000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 09:22:01.195  6872  6872 W art     : b54d1000-b54d3000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-12 09:22:01.195  6872  6872 W art     : b54d3000-b54d4000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 09:22:01.195  6872  6872 W art     : b54d4000-b54d5000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b54d5000-b54dc000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 09:22:01.195  6872  6872 W art     : b54dc000-b54dd000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 09:22:01.195  6872  6872 W art     : b54dd000-b54de000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 09:22:01.195  6872  6872 W art     : avc_common.so
08-12 09:22:01.195  6872  6872 W art     : b54df000-b54e2000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 09:22:01.195  6872  6872 W art     : b54e2000-b54e3000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 09:22:01.195  6872  6872 W art     : b54e3000-b54e4000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 09:22:01.195  6872  6872 W art     : enc_common.so
08-12 09:22:01.195  6872  6872 W art     : b54e5000-b54e9000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 09:22:01.195  6872  6872 W art     : b54e9000-b54ea000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b54ea000-b54eb000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-12 09:22:01.195  6872  6872 W art     : b54eb000-b54ec000 rw-p 00005000 b3:17 2510       /syste
08-12 09:22:01.195  6872  6872 W art     : m/lib/libpowermanager.so
08-12 09:22:01.195  6872  6872 W art     : b54ed000-b550a000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 09:22:01.195  6872  6872 W art     : b550a000-b550b000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 09:22:01.195  6872  6872 W art     : b550b000-b550c000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 09:22:01.195  6872  6872 W art     : b550d000-b5512000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 09:22:01.195  6872  6872 W art     : b5512000-b5513000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 09:22:01.195  6872  6872 W art     : b5513000-b5514000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 09:22:01.195  6872  6872 W art     : b5515000-b5546000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 09:22:01.195  6872  6872 W art     : b5546000-b5549000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 09:22:01.195  6872  6872 W art     : b5549000-b554a000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 09:22:01.195  6872  6872 W art     : b554b000-b5586000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 09:22:01.195  6872  6872 W art     : b5586000-b5587000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-12 09:22:01.195  6872  6872 W art     : b5587000-b5588000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 09:22:01.195  6872  6872 W art     : b5589000-b5590000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 09:22:01.195  6872  6872 W art     : b5590000-b5591000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5591000-b5592000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 09:22:01.195  6872  6872 W art     : b5592000-b5593000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 09:22:01.195  6872  6872 W art     : b5593000-b5594000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.195  6872  6872 W art     : b5594000-b55ab000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 09:22:01.195  6872  6872 W art     : b55ab000-b55ac000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b55ac000-b55af000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 09:22:01.195  6872  6872 W art     : b55af000-b55b0000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 09:22:01.195  6872  6872 W art     : b55b0000-b55cf000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 09:22:01.195  6872  6872 W art     : b55cf000-b55d0000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 09:22:01.195  6872  6872 W art     : b55d0000-b55d1000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-12 09:22:01.195  6872  6872 W art     : b55d1000-b560f000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 09:22:01.195  6872  6872 W art     : b560f000-b5610000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5610000-b5612000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 09:22:01.195  6872  6872 W art     : b5612000-b5613000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 09:22:01.195  6872  6872 W art     : b5614000-b561b000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 09:22:01.195  6872  6872 W art     : b561b000-b561c000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 09:22:01.195  6872  6872 W art     : b561c000-b561d000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 09:22:01.195  6872  6872 W art     : b561e000-b5621000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 09:22:01.195  6872  6872 W art     : b5621000-b5622000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 09:22:01.195  6872  6872 W art     : b5622000-b5623000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 09:22:01.195  6872  6872 W art     : b5623000-b5629000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 09:22:01.195  6872  6872 W art     : b5629000-b562a000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b562a000-b562b000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 09:22:01.195  6872  6872 W art     : b562b000-b562c000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 09:22:01.195  6872  6872 W art     : b562c000-b5635000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 09:22:01.195  6872  6872 W art     : b5635000-b5636000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 09:22:01.195  6872  6872 W art     : b5636000-b5637000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 09:22:01.195  6872  6872 W art     : b5637000-b56c8000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 09:22:01.195  6872  6872 W art     : b56c8000-b56c9000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b56c9000-b56d4000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 09:22:01.195  6872  6872 W art     : b56d4000-b56d5000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 09:22:01.195  6872  6872 W art     : b56d6000-b56e8000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 09:22:01.195  6872  6872 W art     : b56e8000-b56e9000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 09:22:01.195  6872  6872 W art     : b56e9000-b56ea000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 09:22:01.195  6872  6872 W art     : b56eb000-b56f0000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-12 09:22:01.195  6872  6872 W art     : b56f0000-b56f1000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 09:22:01.195  6872  6872 W art     : b56f1000-b56f2000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 09:22:01.195  6872  6872 W art     : b56f3000-b5760000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 09:22:01.195  6872  6872 W art     : b5760000-b5761000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5761000-b5763000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 09:22:01.195  6872  6872 W art     : b5763000-b5764000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 09:22:01.195  6872  6872 W art     : b5764000-b5765000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.195  6872  6872 W art     : b5765000-b576c000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 09:22:01.195  6872  6872 W art     : b576c000-b576d000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 09:22:01.195  6872  6872 W art     : b576d000-b576e000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 09:22:01.195  6872  6872 W art     : b576f000-b57ef000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 09:22:01.195  6872  6872 W art     : b57ef000-b57f0000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b57f0000-b57f1000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 09:22:01.195  6872  6872 W art     : b57f1000-b57f2000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 09:22:01.195  6872  6872 W art     : b57f2000-b5809000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5809000-b5840000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 09:22:01.195  6872  6872 W art     : ib/libqc-opt.so
08-12 09:22:01.195  6872  6872 W art     : b5840000-b5841000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 09:22:01.195  6872  6872 W art     : b5841000-b5842000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 09:22:01.195  6872  6872 W art     : b5842000-b585e000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 09:22:01.195  6872  6872 W art     : b585e000-b585f000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 09:22:01.195  6872  6872 W art     : b585f000-b5860000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 09:22:01.195  6872  6872 W art     : b5861000-b58c2000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 09:22:01.195  6872  6872 W art     : b58c2000-b58c4000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 09:22:01.195  6872  6872 W art     : b58c4000-b58c5000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 09:22:01.195  6872  6872 W art     : b58c6000-b58ed000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 09:22:01.195  6872  6872 W art     : b58ed000-b58ee000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b58ee000-b58ef000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 09:22:01.195  6872  6872 W art     : b58ef000-b58f0000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 09:22:01.195  6872  6872 W art     : b58f1000-b58f9000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 09:22:01.195  6872  6872 W art     : b58f9000-b58fb000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 09:22:01.195  6872  6872 W art     : b58fb000-b58fc000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 09:22:01.195  6872  6872 W art     : b58fd000-b5900000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 09:22:01.195  6872  6872 W art     : b5900000-b5901000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 09:22:01.195  6872  6872 W art     : b5901000-b5902000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 09:22:01.195  6872  6872 W art     : b5902000-b5906000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 09:22:01.195  6872  6872 W art     : b5906000-b5907000 ---p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5907000-b5908000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 09:22:01.195  6872  6872 W art     : b5908000-b5909000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 09:22:01.195  6872  6872 W art     : b5909000-b5919000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 09:22:01.195  6872  6872 W art     : b5919000-b591a000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 09:22:01.195  6872  6872 W art     : b591a000-b591b000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 09:22:01.195  6872  6872 W art     : b591b000-b5961000 rw-p 00000000 00:00 0 
08-12 09:22:01.195  6872  6872 W art     : b5961000-b596a000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 09:22:01.205  6872  6872 W art     : b596a000-b596b000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 09:22:01.205  6872  6872 W art     : b596b000-b596c000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 09:22:01.205  6872  6872 W art     : b596d000-b5972000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 09:22:01.205  6872  6872 W art     : b5972000-b5973000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 09:22:01.205  6872  6872 W art     : b5973000-b5974000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 09:22:01.205  6872  6872 W art     : b5974000-b5977000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 09:22:01.205  6872  6872 W art     : b5977000-b5978000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5978000-b5979000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 09:22:01.205  6872  6872 W art     : b5979000-b597a000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 09:22:01.205  6872  6872 W art     : b597b000-b5993000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 09:22:01.205  6872  6872 W art     : b5993000-b5994000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5994000-b5995000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 09:22:01.205  6872  6872 W art     : b5995000-b5996000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 09:22:01.205  6872  6872 W art     : b5997000-b5b31000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 09:22:01.205  6872  6872 W art     : b5b31000-b5b32000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5b32000-b5b3f000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 09:22:01.205  6872  6872 W art     : b5b3f000-b5b40000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 09:22:01.205  6872  6872 W art     : b5b40000-b5b44000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 09:22:01.205  6872  6872 W art     : b5b44000-b5b45000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5b45000-b5b46000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 09:22:01.205  6872  6872 W art     : b5b46000-b5b47000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 09:22:01.205  6872  6872 W art     : b5b47000-b5b5a000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 09:22:01.205  6872  6872 W art     : b5b5a000-b5b5b000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 09:22:01.205  6872  6872 W art     : b5b5b000-b5b5c000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 09:22:01.205  6872  6872 W art     : b5b5c000-b5b5d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:01.205  6872  6872 W art     : b5b5d000-b5ba8000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 09:22:01.205  6872  6872 W art     : b5ba8000-b5ba9000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 09:22:01.205  6872  6872 W art     : b5ba9000-b5baa000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 09:22:01.205  6872  6872 W art     : b5baa000-b5bac000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5bad000-b5bbe000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 09:22:01.205  6872  6872 W art     : b5bbe000-b5bbf000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5bbf000-b5bc0000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 09:22:01.205  6872  6872 W art     : b5bc0000-b5bc1000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 09:22:01.205  6872  6872 W art     : b5bc2000-b5bcc000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 09:22:01.205  6872  6872 W art     : b5bcc000-b5bce000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 09:22:01.205  6872  6872 W art     : b5bce000-b5bcf000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 09:22:01.205  6872  6872 W art     : b5bcf000-b5be8000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 09:22:01.205  6872  6872 W art     : b5be8000-b5be9000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 09:22:01.205  6872  6872 W art     : b5be9000-b5bec000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 09:22:01.205  6872  6872 W art     : b5bec000-b5bf0000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5bf0000-b5c64000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 09:22:01.205  6872  6872 W art     : b5c64000-b5c65000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5c65000-b5c68000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 09:22:01.205  6872  6872 W art     : b5c68000-b5c69000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 09:22:01.205  6872  6872 W art     : b5c69000-b5c6a000 r--p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5c6a000-b5c6d000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 09:22:01.205  6872  6872 W art     : b5c6d000-b5c6e000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 09:22:01.205  6872  6872 W art     : b5c6e000-b5c6f000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 09:22:01.205  6872  6872 W art     : b5c6f000-b5c70000 r--p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5c70000-b5c75000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 09:22:01.205  6872  6872 W art     : b5c75000-b5c76000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 09:22:01.205  6872  6872 W art     : b5c76000-b5c77000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 09:22:01.205  6872  6872 W art     : b5c77000-b5c78000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b5c78000-b5c7b000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 09:22:01.205  6872  6872 W art     : b5c7b000-b5c7c000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 09:22:01.205  6872  6872 W art     : b5c7c000-b5c7d000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 09:22:01.205  6872  6872 W art     : b5c7d000-b5c7e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b5c7e000-b5c82000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 09:22:01.205  6872  6872 W art     : b5c82000-b5c83000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 09:22:01.205  6872  6872 W art     : b5c83000-b5c84000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 09:22:01.205  6872  6872 W art     : b5c84000-b5c85000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:01.205  6872  6872 W art     : b5c85000-b5c89000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 09:22:01.205  6872  6872 W art     : b5c89000-b5c8a000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 09:22:01.205  6872  6872 W art     : b5c8a000-b5c8b000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 09:22:01.205  6872  6872 W art     : b5c8b000-b5c8c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b5c8c000-b5c9a000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 09:22:01.205  6872  6872 W art     : b5c9a000-b5c9b000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b5c9b000-b5c9c000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 09:22:01.205  6872  6872 W art     : b5c9c000-b5c9d000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 09:22:01.205  6872  6872 W art     : b5c9d000-b5ca7000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 09:22:01.205  6872  6872 W art     : b5ca7000-b5caa000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 09:22:01.205  6872  6872 W art     : b5caa000-b5cab000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 09:22:01.205  6872  6872 W art     : b5cab000-b5cac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b5cac000-b5cb6000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 09:22:01.205  6872  6872 W art     : b5cb6000-b5cb9000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 09:22:01.205  6872  6872 W art     : b5cb9000-b5cba000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 09:22:01.205  6872  6872 W art     : b5cba000-b5cbe000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 09:22:01.205  6872  6872 W art     : b5cbe000-b5cbf000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 09:22:01.205  6872  6872 W art     : b5cbf000-b5cc0000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 09:22:01.205  6872  6872 W art     : b5cc0000-b5cc1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b5cc1000-b5cce000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 09:22:01.205  6872  6872 W art     : b5cce000-b5cd0000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 09:22:01.205  6872  6872 W art     : b5cd0000-b5cd1000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 09:22:01.205  6872  6872 W art     : b5cd1000-b60e3000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 09:22:01.205  6872  6872 W art     : b60e3000-b60e4000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b60e4000-b60ed000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 09:22:01.205  6872  6872 W art     : b60ed000-b60f1000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 09:22:01.205  6872  6872 W art     : b60f1000-b60f2000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b60f2000-b60f9000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 09:22:01.205  6872  6872 W art     : b60f9000-b60fa000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 09:22:01.205  6872  6872 W art     : b60fa000-b60fb000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 09:22:01.205  6872  6872 W art     : b60fb000-b60fc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b60fc000-b6117000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 09:22:01.205  6872  6872 W art     : b6117000-b6118000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 09:22:01.205  6872  6872 W art     : b6118000-b6119000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 09:22:01.205  6872  6872 W art     : b6119000-b611a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b611a000-b6166000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 09:22:01.205  6872  6872 W art     : b6166000-b6167000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6167000-b6168000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 09:22:01.205  6872  6872 W art     : b6168000-b6169000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 09:22:01.205  6872  6872 W art     : b6169000-b616a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b616a000-b616e000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 09:22:01.205  6872  6872 W art     : b616e000-b616f000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b616f000-b6170000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 09:22:01.205  6872  6872 W art     : b6170000-b6171000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 09:22:01.205  6872  6872 W art     : b6171000-b61a9000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 09:22:01.205  6872  6872 W art     : b61a9000-b61aa000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 09:22:01.205  6872  6872 W art     : b61aa000-b61ab000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 09:22:01.205  6872  6872 W art     : b61ab000-b61ac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b61ac000-b624a000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 09:22:01.205  6872  6872 W art     : b624a000-b624b000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b624b000-b6269000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 09:22:01.205  6872  6872 W art     : b6269000-b626a000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 09:22:01.205  6872  6872 W art     : b626a000-b63dd000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 09:22:01.205  6872  6872 W art     : b63dd000-b63e8000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 09:22:01.205  6872  6872 W art     : b63e8000-b63e9000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 09:22:01.205  6872  6872 W art     : b63e9000-b6500000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 09:22:01.205  6872  6872 W art     : b6500000-b650b000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 09:22:01.205  6872  6872 W art     : b650b000-b650c000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 09:22:01.205  6872  6872 W art     : b650c000-b6510000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6510000-b6534000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 09:22:01.205  6872  6872 W art     : b6534000-b6536000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 09:22:01.205  6872  6872 W art     : b6536000-b6537000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 09:22:01.205  6872  6872 W art     : b6537000-b65dd000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 09:22:01.205  6872  6872 W art     : b65dd000-b65ea000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 09:22:01.205  6872  6872 W art     : b65ea000-b65eb000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 09:22:01.205  6872  6872 W art     : b65eb000-b65ec000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b65ec000-b663f000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 09:22:01.205  6872  6872 W art     : b663f000-b6640000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6640000-b6641000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 09:22:01.205  6872  6872 W art     : b6641000-b6642000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 09:22:01.205  6872  6872 W art     : b6642000-b6647000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6647000-b6659000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 09:22:01.205  6872  6872 W art     : b6659000-b665a000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b665a000-b665b000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 09:22:01.205  6872  6872 W art     : b665b000-b665c000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 09:22:01.205  6872  6872 W art     : b665c000-b6663000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 09:22:01.205  6872  6872 W art     : b6663000-b6664000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 09:22:01.205  6872  6872 W art     : b6664000-b6665000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 09:22:01.205  6872  6872 W art     : b6665000-b6666000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6666000-b6669000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 09:22:01.205  6872  6872 W art     : b6669000-b666a000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 09:22:01.205  6872  6872 W art     : b666a000-b666b000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 09:22:01.205  6872  6872 W art     : b666b000-b666f000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 09:22:01.205  6872  6872 W art     : b666f000-b6670000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 09:22:01.205  6872  6872 W art     : b6670000-b6671000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 09:22:01.205  6872  6872 W art     : b6671000-b667f000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 09:22:01.205  6872  6872 W art     : b667f000-b6680000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6680000-b6681000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 09:22:01.205  6872  6872 W art     : b6681000-b6682000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 09:22:01.205  6872  6872 W art     : b6682000-b668b000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 09:22:01.205  6872  6872 W art     : b668b000-b668c000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 09:22:01.205  6872  6872 W art     : b668c000-b668d000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 09:22:01.205  6872  6872 W art     : b668d000-b66f3000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 09:22:01.205  6872  6872 W art     : b66f3000-b66f4000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b66f4000-b66f6000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 09:22:01.205  6872  6872 W art     : b66f6000-b66ff000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 09:22:01.205  6872  6872 W art     : b66ff000-b6702000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6702000-b6799000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 09:22:01.205  6872  6872 W art     : b6799000-b679b000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 09:22:01.205  6872  6872 W art     : b679b000-b679c000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 09:22:01.205  6872  6872 W art     : b679c000-b679d000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b679d000-b6abe000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 09:22:01.205  6872  6872 W art     : b6abe000-b6abf000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6abf000-b6ada000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 09:22:01.205  6872  6872 W art     : b6ada000-b6ade000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 09:22:01.205  6872  6872 W art     : b6ade000-b6ae3000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6ae3000-b6aeb000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 09:22:01.205  6872  6872 W art     : b6aeb000-b6aec000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 09:22:01.205  6872  6872 W art     : b6aec000-b6aed000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 09:22:01.205  6872  6872 W art     : b6aed000-b6b1b000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 09:22:01.205  6872  6872 W art     : b6b1b000-b6b1c000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6b1c000-b6b23000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 09:22:01.205  6872  6872 W art     : b6b23000-b6b24000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 09:22:01.205  6872  6872 W art     : b6b24000-b6b6a000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 09:22:01.205  6872  6872 W art     : b6b6a000-b6b6b000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6b6b000-b6b6e000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 09:22:01.205  6872  6872 W art     : b6b6e000-b6b6f000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 09:22:01.205  6872  6872 W art     : b6b6f000-b6b8a000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 09:22:01.205  6872  6872 W art     : b6b8a000-b6b8e000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 09:22:01.205  6872  6872 W art     : b6b8e000-b6b8f000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 09:22:01.205  6872  6872 W art     : b6b8f000-b6bdc000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 09:22:01.205  6872  6872 W art     : b6bdc000-b6bdd000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6bdd000-b6be9000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 09:22:01.205  6872  6872 W art     : b6be9000-b6bea000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 09:22:01.205  6872  6872 W art     : b6bea000-b6bf7000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 09:22:01.205  6872  6872 W art     : b6bf7000-b6bf8000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6bf8000-b6bf9000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 09:22:01.205  6872  6872 W art     : b6bf9000-b6bfa000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 09:22:01.205  6872  6872 W art     : b6bfa000-b6c02000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 09:22:01.205  6872  6872 W art     : b6c02000-b6c03000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6c03000-b6c04000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 09:22:01.205  6872  6872 W art     : b6c04000-b6c05000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 09:22:01.205  6872  6872 W art     : b6c05000-b6c0c000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 09:22:01.205  6872  6872 W art     : b6c0c000-b6c0d000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 09:22:01.205  6872  6872 W art     : b6c0d000-b6c0e000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 09:22:01.205  6872  6872 W art     : b6c0e000-b6c22000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 09:22:01.205  6872  6872 W art     : b6c22000-b6c24000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 09:22:01.205  6872  6872 W art     : b6c24000-b6c25000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 09:22:01.205  6872  6872 W art     : b6c25000-b6c4d000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 09:22:01.205  6872  6872 W art     : b6c4d000-b6c4f000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 09:22:01.205  6872  6872 W art     : b6c4f000-b6c50000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 09:22:01.205  6872  6872 W art     : b6c50000-b6c53000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 09:22:01.205  6872  6872 W art     : b6c53000-b6c54000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 09:22:01.205  6872  6872 W art     : b6c54000-b6c55000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 09:22:01.205  6872  6872 W art     : b6c55000-b6c5e000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 09:22:01.205  6872  6872 W art     : b6c5e000-b6c5f000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 09:22:01.205  6872  6872 W art     : b6c5f000-b6c60000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 09:22:01.205  6872  6872 W art     : b6c60000-b6c80000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 09:22:01.205  6872  6872 W art     : b6c80000-b6c81000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 09:22:01.205  6872  6872 W art     : b6c81000-b6c82000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 09:22:01.205  6872  6872 W art     : b6c82000-b6cf5000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 09:22:01.205  6872  6872 W art     : b6cf5000-b6cf9000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 09:22:01.205  6872  6872 W art     : b6cf9000-b6cfc000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 09:22:01.205  6872  6872 W art     : b6cfc000-b6d06000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6d06000-b6d8e000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 09:22:01.205  6872  6872 W art     : b6d8e000-b6d8f000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6d8f000-b6d93000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 09:22:01.205  6872  6872 W art     : b6d93000-b6d94000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 09:22:01.205  6872  6872 W art     : b6d94000-b6d95000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6d95000-b6dbe000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 09:22:01.205  6872  6872 W art     : b6dbe000-b6dbf000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6dbf000-b6dc2000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 09:22:01.205  6872  6872 W art     : b6dc2000-b6dc3000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 09:22:01.205  6872  6872 W art     : b6dc3000-b6e9d000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 09:22:01.205  6872  6872 W art     : b6e9d000-b6ea4000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 09:22:01.205  6872  6872 W art     : b6ea4000-b6eac000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 09:22:01.205  6872  6872 W art     : b6eac000-b6ead000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6ead000-b6eae000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:01.205  6872  6872 W art     : b6eae000-b6eaf000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 09:22:01.205  6872  6872 W art     : b6eaf000-b6eb0000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b6eb0000-b6eb3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b6eb3000-b6ed8000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 09:22:01.205  6872  6872 W art     : b6ed8000-b6ed9000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6ed9000-b6ee0000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 09:22:01.205  6872  6872 W art     : b6ee0000-b6ee1000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 09:22:01.205  6872  6872 W art     : b6ee1000-b6ee8000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 09:22:01.205  6872  6872 W art     : b6ee8000-b6ee9000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 09:22:01.205  6872  6872 W art     : b6ee9000-b6eea000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 09:22:01.205  6872  6872 W art     : b6eea000-b6eeb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b6eeb000-b6f03000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 09:22:01.205  6872  6872 W art     : b6f03000-b6f04000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6f04000-b6f05000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 09:22:01.205  6872  6872 W art     : b6f05000-b6f06000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 09:22:01.205  6872  6872 W art     : b6f06000-b6f14000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 09:22:01.205  6872  6872 W art     : b6f14000-b6f15000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6f15000-b6f16000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 09:22:01.205  6872  6872 W art     : b6f16000-b6f17000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 09:22:01.205  6872  6872 W art     : b6f17000-b6f18000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:01.205  6872  6872 W art     : b6f18000-b6f1a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b6f1a000-b6f1b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b6f1b000-b6f1c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:01.205  6872  6872 W art     : b6f1c000-b6f1d000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 09:22:01.205  6872  6872 W art     : b6f1d000-b6f1e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:01.205  6872  6872 W art     : b6f1e000-b6f3e000 r--s 00000000 00:0b 7179       /dev/__properties__
08-12 09:22:01.205  6872  6872 W art     : b6f3e000-b6f3f000 r--p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6f3f000-b6f40000 ---p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6f40000-b6f42000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 09:22:01.205  6872  6872 W art     : b6f42000-b6f43000 r-xp 00000000 00:00 0          [sigpage]
08-12 09:22:01.205  6872  6872 W art     : b6f43000-b6f5e000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 09:22:01.205  6872  6872 W art     : b6f5e000-b6f5f000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 09:22:01.205  6872  6872 W art     : b6f5f000-b6f61000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 09:22:01.205  6872  6872 W art     : b6f61000-b6f63000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : b6f63000-b6f68000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 09:22:01.205  6872  6872 W art     : b6f68000-b6f69000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 09:22:01.205  6872  6872 W art     : b6f69000-b6f6a000 rw-p 00000000 00:00 0 
08-12 09:22:01.205  6872  6872 W art     : beb20000-beb41000 rw-p 00000000 00:00 0          [stack]
08-12 09:22:01.205  6872  6872 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 09:22:01.265  6872  6872 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 09:22:01.315  6872  6872 I Radio-JNI: register_android_hardware_Radio DONE
08-12 09:22:01.325  6872  6872 E AffinityControl: AffinityControl: registerfunction enter
08-12 09:22:01.345  6872  6872 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 09:22:01.365   738  1546 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-12 09:22:01.375   738  1546 D ActivityManager: mDVFSHelper.acquire()
08-12 09:22:01.375   738  1546 V WindowManager: addAppToken: AppWindowToken{208cb16 token=Token{342f831 ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164}}} to stack=1 task=164 at 0
08-12 09:22:01.385   738   881 D SecWifiDisplayUtil: Metadata value : none
08-12 09:22:01.385   738   881 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{52626ee V.E...... R.....ID 0,0-0,0}
08-12 09:22:01.385   738   881 D ISSUE_DEBUG: InputChannelName : 2893a1c Starting com.test.thalitest
08-12 09:22:01.405  6887  6887 E Zygote  : v2
08-12 09:22:01.405   738  1546 I ActivityManager: Start proc 6887:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-12 09:22:01.405   738  1546 D InputDispatcher: Focused application set to: xxxx
08-12 09:22:01.405  6887  6887 I libpersona: KNOX_SDCARD checking this for 10004
08-12 09:22:01.405  6887  6887 I libpersona: KNOX_SDCARD not a persona
08-12 09:22:01.405  6887  6887 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 09:22:01.405  6887  6887 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:01.405   738  1546 D InputDispatcher: Focus left window: 3699
08-12 09:22:01.405   738  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-12 09:22:01.405   738   824 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9307a4f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-12 09:22:01.405  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-12 09:22:01.405   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-12 09:22:01.405  6872  6872 D AndroidRuntime: Shutting down VM
08-12 09:22:01.405  6887  6887 E Zygote  : accessInfo : 0
08-12 09:22:01.405  6887  6887 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-12 09:22:01.435   738   881 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:738 uid:1000
08-12 09:22:01.435   738   881 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 09:22:01.435   738   881 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:738 uid:1000
08-12 09:22:01.435   738   881 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-12 09:22:01.435   738   881 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-12 09:22:01.445  6887  6887 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 09:22:01.445  6887  6887 D ActivityThread: Added TimaKeyStore provider
08-12 09:22:01.445   738  2248 V WindowOrientationListener: setCurrentAppOrientation :-1
08-12 09:22:01.445   738  2248 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-12 09:22:01.445   738   824 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2893a1c u0 d0 Starting com.test.thalitest}
08-12 09:22:01.445  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-12 09:22:01.455   738  2248 D ActivityManager:  Launching com.test.thalitest, updated priority
08-12 09:22:01.465   738   823 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-12 09:22:01.485   738   881 V WindowStateAnimator: Finishing drawing window Window{2893a1c u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-12 09:22:01.495   294   368 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
08-12 09:22:01.495  1730  1870 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-12 09:22:01.495  1730  1730 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-12 09:22:01.495   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbed52364
08-12 09:22:01.505   294   368 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
08-12 09:22:01.505   294   368 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
08-12 09:22:01.505  3699  3699 V ActivityThread: updateVisibility : ActivityRecord{a9901d9 token=android.os.BinderProxy@deefdab {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-12 09:22:01.505   294   366 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-12 09:22:01.505   294   366 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-12 09:22:01.515   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
08-12 09:22:01.515   294  5155 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-12 09:22:01.515   294  1297 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-12 09:22:01.525  2405  2420 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-12 09:22:01.525  1730  1730 V ActivityThread: updateVisibility : ActivityRecord{acd665b token=android.os.BinderProxy@4c3ef3c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-12 09:22:01.525  1730  1730 D Launcher: onTrimMemory. Level: 20
08-12 09:22:01.525   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
08-12 09:22:01.535   294   366 I SurfaceFlinger: id=20 Removed VSBConnecti (4/9)
08-12 09:22:01.535   294  5155 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/9)
08-12 09:22:01.545   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
,08-12 09:22:01.765   738  2248 I WindowManager: Screenshot max retries 4 of Token{342f831 ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164}} appWin=Window{2893a1c u0 d0 Starting com.test.thalitest} drawState=4
,08-12 09:22:01.775   738  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-12 09:22:01.785  6887  6887 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 09:22:01.795   738  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 09:22:01.805  6887  6887 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 09:22:01.805  6887  6887 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 09:22:01.825  6887  6887 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-12 09:22:01.845  6887  6887 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-12 09:22:01.855  6887  6887 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 09:22:01.865  6887  6887 I cr_LibraryLoader: Time to load native libraries: 5 ms (timestamps 3138-3143)
,08-12 09:22:01.865  6887  6887 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 09:22:01.885  6887  6887 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4848f15}
,08-12 09:22:01.885  6887  6907 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
08-12 09:22:01.885  6887  6887 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-12 09:22:01.885  6887  6887 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 09:22:01.905  6887  6887 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-12 09:22:01.925  6887  6887 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-12 09:22:01.925  6887  6887 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-12 09:22:01.925  6887  6887 I Adreno-EGL: Build Date: 01/28/16 Thu
08-12 09:22:01.925  6887  6887 I Adreno-EGL: Local Branch: ss
08-12 09:22:01.925  6887  6887 I Adreno-EGL: Remote Branch: 
08-12 09:22:01.925  6887  6887 I Adreno-EGL: Local Patches: 
08-12 09:22:01.925  6887  6887 I Adreno-EGL: Reconstruct Branch: 
,08-12 09:22:01.935  6887  6887 D libEGL  : eglInitialize EGLDisplay = 0xbece0dac
,08-12 09:22:01.965   738  2261 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-12 09:22:01.965   738  2261 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-12 09:22:02.015  6887  6887 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-12 09:22:02.035  6887  6887 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 09:22:02.035  6887  6887 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-12 09:22:02.035  6887  6887 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-12 09:22:02.035  6887  6887 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-12 09:22:02.055  6887  6887 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-12 09:22:02.065  6887  6887 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-12 09:22:02.135  6887  6887 D SecWifiDisplayUtil: Metadata value : none
,08-12 09:22:02.135  6887  6887 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3730ffb I.E...... R.....ID 0,0-0,0}
,08-12 09:22:02.145  6887  6931 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 09:22:02.145   738  2239 D ISSUE_DEBUG: InputChannelName : 7bf6349 com.test.thalitest/com.test.thalitest.MainActivity
,08-12 09:22:02.155   738  2257 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-12 09:22:02.155   738  2257 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 09:22:02.155   738   738 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 09:22:02.155   738   738 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-12 09:22:02.175  6887  6887 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6887
,08-12 09:22:02.175   738  1924 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6887 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 09:22:02.175   738  1333 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-12 09:22:02.175   738  1333 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-12 09:22:02.175   738  1333 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-12 09:22:02.175   738  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 09:22:02.175   738  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 09:22:02.175   738  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 09:22:02.175   738  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-12 09:22:02.175   738  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-12 09:22:02.175   738  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-12 09:22:02.175   738  1333 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 09:22:02.195  6887  6907 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-12 09:22:02.195  6887  6887 D SecWifiDisplayUtil: Metadata value : none
,08-12 09:22:02.205   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-12 09:22:02.225   738  2261 D InputDispatcher: Focus entered window: 6887
,08-12 09:22:02.225   738   881 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:738 uid:1000
,08-12 09:22:02.225   738   881 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 09:22:02.225   738   881 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:738 uid:1000
08-12 09:22:02.225   738   881 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 09:22:02.235  6887  6931 D libEGL  : eglInitialize EGLDisplay = 0x9cb397c4
08-12 09:22:02.235  6887  6931 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 09:22:02.305  6887  6887 V ActivityThread: updateVisibility : ActivityRecord{61213e2 token=android.os.BinderProxy@eeb5d8a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-12 09:22:02.315  6887  6887 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-12 09:22:02.345   738  2239 V WindowStateAnimator: Finishing drawing window Window{7bf6349 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-12 09:22:02.355  6887  6887 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-12 09:22:02.355   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbed52364
,08-12 09:22:02.365   738   881 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 09:22:02.365   738   738 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-12 09:22:02.365   738   738 I KnoxTimeoutHandler: SD activityfalse
,08-12 09:22:02.365   738   881 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +595ms (total +977ms)
,08-12 09:22:02.375  6887  6887 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-12 09:22:02.375   738  1415 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-12 09:22:02.375   738   881 D ActivityManager: mDVFSHelper.release()
,08-12 09:22:02.375   738   881 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164} time:163655
,08-12 09:22:02.375   738   881 D ViewRootImpl: #3 mView = null
,08-12 09:22:02.375   294  5155 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-12 09:22:02.375   294  1297 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-12 09:22:02.385   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
,08-12 09:22:02.405   738  2257 V WindowStateAnimator: Finishing drawing window Window{7bf6349 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-12 09:22:02.405  6887  6887 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-12 09:22:02.405  6887  6887 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@eeb5d8a time:163681
,08-12 09:22:02.405   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbed52364
,08-12 09:22:02.445  6887  6939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 09:22:02.445  6887  6939 D libEGL  : eglInitialize EGLDisplay = 0x9ac7c3ec
,08-12 09:22:02.505  6887  6887 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6887
,08-12 09:22:02.645  6887  6887 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 09:22:02.775   738  3447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-12 09:22:02.955  6887  6948 D jxcore_app_log: JniHelper::setJavaVM(0xb473c000), pthread_self() = -1705981648
,08-12 09:22:02.955  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 09:22:02.955  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 09:22:02.955  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 09:22:02.955  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 09:22:02.955  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 09:22:02.955  6887  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8c1748 added. We now have 1 listener(s)
,08-12 09:22:02.965  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-12 09:22:02.965  6887  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-12 09:22:02.965  6887  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-12 09:22:02.965  6887  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
,08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0,
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76,
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
,08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
,08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 09:22:02.975  6887  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f517dc7 added. We now have 1 listener(s)
08-12 09:22:02.975  6887  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 09:22:02.975  6887  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-12 09:22:02.995  6887  6948 D BluetoothAdapter: STATE_ON,
08-12 09:22:03.005  6887  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:22:03.005  6887  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 09:22:03.005  6887  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
08-12 09:22:03.005  6887  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 09:22:03.005  6887  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 09:22:03.005  6887  6948 I io.jxcore.node.LifeCycleMonitor: start: OK,
,08-12 09:22:03.015  6887  6887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 09:22:03.035  6887  6887 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 09:22:03.165  1452  1452 D Recents : onTaskStackChanged
,08-12 09:22:03.165  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-12 09:22:04.025  6887  6949 W jxcore-log: Initializing JXcore engine
08-12 09:22:04.025  6887  6949 W jxcore-log: JXcore engine is ready
08-12 09:22:04.105  2152  2152 E audit   : type=1400 msg=audit(1470986524.105:287): avc:  denied  { ioctl } for  pid=6949 comm="Thread-975" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 09:22:04.105  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:04.105  2152  2152 E audit   : type=1300 msg=audit(1470986524.105:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a4023c8 items=0 ppid=350 ppcomm=main pid=6949 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-975" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 09:22:04.105  2152  2152 E audit   : type=1327 msg=audit(1470986524.105:287): proctitle="com.test.thalitest"
08-12 09:22:04.105  2152  2152 E audit   : type=1320 msg=audit(1470986524.105:287): 
08-12 09:22:04.105  2152  2152 E audit   : type=1400 msg=audit(1470986524.105:288): avc:  denied  { ioctl } for  pid=6949 comm="Thread-975" path="socket:[43268]" dev="sockfs" ino=43268 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 09:22:04.105  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:04.105  2152  2152 E audit   : type=1300 msg=audit(1470986524.105:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=2 a3=9a4023c8 items=0 ppid=350 ppcomm=main pid=6949 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-975" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-12 09:22:04.105  2152  2152 E audit   : type=1327 msg=audit(1470986524.105:288): proctitle="com.test.thalitest"
08-12 09:22:04.105  2152  2152 E audit   : type=1320 msg=audit(1470986524.105:288): 
08-12 09:22:04.115  6887  6949 W jxcore-log: Starting JXcore engine
08-12 09:22:04.205  6887  6949 W jxcore-log: Platform android
08-12 09:22:04.205  6887  6949 W jxcore-log: 
08-12 09:22:04.205  6887  6949 W jxcore-log: Process ARCH arm
08-12 09:22:04.205  6887  6949 W jxcore-log: 
08-12 09:22:04.435   738  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/164_task.xml.bak
08-12 09:22:04.455  6887  6949 I jxcore-log: JXcore Cordova bridge is ready!
08-12 09:22:04.455  6887  6949 I jxcore-log: 
08-12 09:22:04.465  6887  6949 W jxcore-log: JXcore engine is started
08-12 09:22:04.465  6887  6948 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 09:22:04.465  6887  6887 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 09:22:04.995   738  1237 V AlarmManager: Expired Alarm result :4
,08-12 09:22:05.035  6958  6958 E Zygote  : v2
08-12 09:22:05.035  6958  6958 I libpersona: KNOX_SDCARD checking this for 1000
08-12 09:22:05.035  6958  6958 I libpersona: KNOX_SDCARD not a persona
,08-12 09:22:05.035  6958  6958 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-12 09:22:05.035  6958  6958 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-12 09:22:05.035  6958  6958 E Zygote  : accessInfo : 0
,08-12 09:22:05.045   738  1237 I ActivityManager: Start proc 6958:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-12 09:22:05.045  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-12 09:22:05.045  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
08-12 09:22:05.045  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 09:22:05.055  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-12 09:22:05.065   738  2261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 09:22:05.065   738  2261 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 09:22:05.065   738  2261 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-12 09:22:05.065   738  2261 D BatteryService: stay LED for fully charged
08-12 09:22:05.065   738   738 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 09:22:05.075  2147  2147 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-12 09:22:05.075  2147  2684 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 09:22:05.075   738   738 I MotionRecognitionService: Plugged
,08-12 09:22:05.075   738   738 D MotionRecognitionService:   cableConnection= 1
08-12 09:22:05.075   738   738 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 09:22:05.075   738   738 D MotionRecognitionService: skip setTransmitPower. 
,08-12 09:22:05.085  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,08-12 09:22:05.095  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 09:22:05.095  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 09:22:05.095  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 09:22:05.095  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 09:22:05.095  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 09:22:05.095  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-12 09:22:05.095  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 09:22:05.095  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-12 09:22:05.095  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 09:22:05.095  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 09:22:05.095  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 09:22:05.105  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-12 09:22:05.105  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 09:22:05.125  6958  6958 D TimaKeyStoreProvider: TimaSignature is unavailable
08-12 09:22:05.125  6958  6958 D ActivityThread: Added TimaKeyStore provider
,08-12 09:22:05.135  6958  6958 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-12 09:22:05.145  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-12 09:22:05.155  6958  6958 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-12 09:22:05.185   738  1744 I ActivityManager: Killing 6049:com.android.email/u0a162 (adj 15): DHA:empty #37
,08-12 09:22:05.205   738  1415 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,08-12 09:22:07.815   738  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 09:22:08.045   738  3443 D SSRM:n  : SIOP:: AP = 350, PST = 393, CUR = 300, LCD = 0
,08-12 09:22:09.445   738  3476 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-12 09:22:10.965   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-12 09:22:10.965   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-12 09:22:10.965   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-12 09:22:11.445   738   906 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-12 09:22:11.455   738   906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 09:22:14.695  6887  6949 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 09:22:14.695  6887  6949 I jxcore-log: 
,08-12 09:22:14.695  6887  6949 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 09:22:14.695  6887  6949 I jxcore-log: 
,08-12 09:22:14.705  6887  6949 D BluetoothAdapter: STATE_ON
,08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 09:22:14.705  6887  6949 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 09:22:14.715  6887  6949 D BluetoothAdapter: STATE_ON
,08-12 09:22:14.715  6887  6949 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 09:22:14.715  6887  6949 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 09:22:14.715  6887  6949 I jxcore-log: 
,08-12 09:22:14.715  6887  6949 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 09:22:14.715  6887  6949 I jxcore-log: 
,08-12 09:22:15.055  6887  6949 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 09:22:15.055  6887  6949 I jxcore-log: Failed to execute UT.
08-12 09:22:15.055  6887  6949 I jxcore-log: 
08-12 09:22:15.055  6887  6949 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 09:22:15.055  6887  6949 I jxcore-log: 
,08-12 09:22:15.065  6887  6949 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 09:22:15.065  6887  6949 I jxcore-log: 
08-12 09:22:15.065  6887  6887 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 09:22:15.125   738   753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-12 09:22:15.125   738   753 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-12 09:22:15.125   738   753 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-12 09:22:15.125   738   753 D BatteryService: stay LED for fully charged
,08-12 09:22:15.125   738   738 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-12 09:22:15.125   738   738 I MotionRecognitionService: Plugged
08-12 09:22:15.125   738   738 D MotionRecognitionService:   cableConnection= 1
08-12 09:22:15.125   738   738 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-12 09:22:15.125   738   738 D MotionRecognitionService: skip setTransmitPower. 
,08-12 09:22:15.135  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-12 09:22:15.135  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-12 09:22:15.135  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-12 09:22:15.145  2147  2147 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-12 09:22:15.145  2147  2684 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-12 09:22:15.155  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 09:22:15.155  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 09:22:15.155  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-12 09:22:15.885  4350  5095 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 09:22:15.915  2152  2152 E audit   : type=1400 msg=audit(1470986535.915:289): avc:  denied  { execmod } for  pid=7004 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 09:22:15.915  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:15.915  2152  2152 E audit   : type=1300 msg=audit(1470986535.915:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa5000 a1=51000 a2=5 a3=4 items=0 ppid=3582 ppcomm=adbd pid=7004 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 09:22:15.915  2152  2152 E audit   : type=1327 msg=audit(1470986535.915:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 09:22:15.915  2152  2152 E audit   : type=1320 msg=audit(1470986535.915:289): 
,08-12 09:22:15.965  2152  2152 E audit   : type=1400 msg=audit(1470986535.965:290): avc:  denied  { execmod } for  pid=7004 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 09:22:15.965  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:15.975  2152  2152 E audit   : type=1300 msg=audit(1470986535.965:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f65000 a1=51000 a2=5 a3=4 items=0 ppid=3582 ppcomm=adbd pid=7004 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 09:22:15.975  2152  2152 E audit   : type=1327 msg=audit(1470986535.965:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 09:22:15.975  2152  2152 E audit   : type=1320 msg=audit(1470986535.965:290): 
,08-12 09:22:16.015  2152  2152 E audit   : type=1400 msg=audit(1470986536.015:291): avc:  denied  { execmod } for  pid=7004 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-12 09:22:16.015  7004  7004 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 09:22:16.015  2152  2152 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-12 09:22:16.015  2152  2152 E audit   : type=1300 msg=audit(1470986536.015:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f65000 a1=51000 a2=5 a3=4 items=0 ppid=3582 ppcomm=adbd pid=7004 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-12 09:22:16.015  2152  2152 E audit   : type=1327 msg=audit(1470986536.015:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-12 09:22:16.015  2152  2152 E audit   : type=1320 msg=audit(1470986536.015:291): 
08-12 09:22:16.015  7004  7004 D AndroidRuntime: CheckJNI is OFF
08-12 09:22:16.015  7004  7004 D AndroidRuntime: readGMSProperty: start
08-12 09:22:16.015  7004  7004 D AndroidRuntime: readGMSProperty: already setted!!
08-12 09:22:16.015  7004  7004 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-12 09:22:16.015  7004  7004 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-12 09:22:16.015  7004  7004 D AndroidRuntime: readGMSProperty: end
08-12 09:22:16.015  7004  7004 D AndroidRuntime: addProductProperty: start
,08-12 09:22:16.025  7004  7004 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-12 09:22:16.025  7004  7004 W art     : aedcc000-b1cf2000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-12 09:22:16.025  7004  7004 W art     : b1cf2000-b3f61000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
,08-12 09:22:16.025  7004  7004 W art     : b3f61000-b3f62000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
,08-12 09:22:16.025  7004  7004 W art     : b3f62000-b3f63000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 09:22:16.025  7004  7004 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so,
,08-12 09:22:16.025  7004  7004 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
,08-12 09:22:16.025  7004  7004 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
,08-12 09:22:16.025  7004  7004 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-12 09:22:16.025  7004  7004 W art     : b480e000-b4837000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-12 09:22:16.025  7004  7004 W art     : b4837000-b483a000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-12 09:22:16.025  7004  7004 W art     : b483a000-b483b000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-12 09:22:16.025  7004  7004 W art     : b483b000-b483c000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-12 09:22:16.025  7004  7004 W art     : b483c000-b483d000 r--p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b483d000-b485d000 r--s 00000000 00:0b 7179       /dev/__properties__,
,08-12 09:22:16.025  7004  7004 W art     : b485d000-b526e000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-12 09:22:16.025  7004  7004 W art     : b526e000-b526f000 ---p 00000000 00:00 0 ,
08-12 09:22:16.025  7004  7004 W art     : b526f000-b52b8000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
,08-12 09:22:16.025  7004  7004 W art     : b52b8000-b52b9000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-12 09:22:16.025  7004  7004 W art     : b52b9000-b52c1000 rw-p 00000000 00:00 0 
,08-12 09:22:16.025  7004  7004 W art     : b52c1000-b52c2000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 09:22:16.025  7004  7004 W art     : b52c2000-b52f7000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-12 09:22:16.025  7004  7004 W art     : b52f7000-b52f8000 ---p 00000000 00:00 0 
,08-12 09:22:16.025  7004  7004 W art     : b52f8000-b52f9000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-12 09:22:16.025  7004  7004 W art     : b52f9000-b52fa000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
,08-12 09:22:16.025  7004  7004 W art     : b52fa000-b5352000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-12 09:22:16.025  7004  7004 W art     : b5352000-b5353000 ---p 00000000 00:00 0 
,08-12 09:22:16.025  7004  7004 W art     : b5353000-b5354000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-12 09:22:16.025  7004  7004 W art     : b5354000-b5355000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
,08-12 09:22:16.025  7004  7004 W art     : b5356000-b535c000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 09:22:16.025  7004  7004 W art     : b535c000-b535d000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-12 09:22:16.025  7004  7004 W art     : b535d000-b535e000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so,
08-12 09:22:16.025  7004  7004 W art     : b535e000-b5360000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5361000-b536b000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-12 09:22:16.025  7004  7004 W art     : b536b000-b536e000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-12 09:22:16.025  7004  7004 W art     : b536e000-b536f000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-12 09:22:16.025  7004  7004 W art     : b5370000-b5387000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 09:22:16.025  7004  7004 W art     : b5387000-b5388000 ---p 00000000 00:00 0 
,08-12 09:22:16.025  7004  7004 W art     : b5388000-b5389000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-12 09:22:16.025  7004  7004 W art     : b5389000-b538a000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-12 09:22:16.025  7004  7004 W art     : b538b000-b5395000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-12 09:22:16.025  7004  7004 W art     : b5395000-b5396000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
,08-12 09:22:16.025  7004  7004 W art     : b5396000-b5397000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-12 09:22:16.025  7004  7004 W art     : b5397000-b539b000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-12 09:22:16.025  7004  7004 W art     : b539b000-b539c000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 09:22:16.025  7004  7004 W art     : b539c000-b539d000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-12 09:22:16.025  7004  7004 W art     : b539d000-b53b3000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-12 09:22:16.025  7004  7004 W art     : b53b3000-b53b4000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-12 09:22:16.025  7004  7004 W art     : b53b4000-b53b5000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-12 09:22:16.025  7004  7004 W art     : b53b5000-b53c2000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-12 09:22:16.025  7004  7004 W art     : b53c2000-b53c3000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-12 09:22:16.025  7004  7004 W art     : b53c3000-b53c4000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-12 09:22:16.025  7004  7004 W art     : b53c4000-b5424000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
,08-12 09:22:16.025  7004  7004 W art     : b5424000-b5427000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-12 09:22:16.025  7004  7004 W art     : b5427000-b542b000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b542b000-b548c000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-12 09:22:16.025  7004  7004 W art     : b548c000-b548d000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-12 09:22:16.025  7004  7004 W art     : b548d000-b54dc000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-12 09:22:16.025  7004  7004 W art     : b54dc000-b54de000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-12 09:22:16.025  7004  7004 W art     : b54de000-b54df000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-12 09:22:16.025  7004  7004 W art     : b54df000-b54e0000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b54e0000-b54e7000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 09:22:16.025  7004  7004 W art     : b54e7000-b54e8000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-12 09:22:16.025  7004  7004 W art     : b54e8000-b54e9000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-12 09:22:16.025  7004  7004 W art     : avc_common.so
08-12 09:22:16.025  7004  7004 W art     : b54ea000-b54ed000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-12 09:22:16.025  7004  7004 W art     : b54ed000-b54ee000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-12 09:22:16.025  7004  7004 W art     : b54ee000-b54ef000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-12 09:22:16.025  7004  7004 W art     : enc_common.so
08-12 09:22:16.025  7004  7004 W art     : b54f0000-b54f4000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-12 09:22:16.025  7004  7004 W art     : b54f4000-b54f5000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b54f5000-b54f6000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
,08-12 09:22:16.025  7004  7004 W art     : b54f6000-b54f7000 rw-p 00005000 b3:17 2510       /syste
08-12 09:22:16.025  7004  7004 W art     : m/lib/libpowermanager.so
08-12 09:22:16.025  7004  7004 W art     : b54f8000-b5515000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 09:22:16.025  7004  7004 W art     : b5515000-b5516000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 09:22:16.025  7004  7004 W art     : b5516000-b5517000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-12 09:22:16.025  7004  7004 W art     : b5518000-b551d000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 09:22:16.025  7004  7004 W art     : b551d000-b551e000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-12 09:22:16.025  7004  7004 W art     : b551e000-b551f000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-12 09:22:16.025  7004  7004 W art     : b5520000-b5551000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 09:22:16.025  7004  7004 W art     : b5551000-b5554000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 09:22:16.025  7004  7004 W art     : b5554000-b5555000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-12 09:22:16.025  7004  7004 W art     : b5556000-b5591000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-12 09:22:16.025  7004  7004 W art     : b5591000-b5592000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
,08-12 09:22:16.025  7004  7004 W art     : b5592000-b5593000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-12 09:22:16.025  7004  7004 W art     : b5594000-b559b000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-12 09:22:16.025  7004  7004 W art     : b559b000-b559c000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b559c000-b559d000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-12 09:22:16.025  7004  7004 W art     : b559d000-b559e000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-12 09:22:16.025  7004  7004 W art     : b559e000-b559f000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 09:22:16.025  7004  7004 W art     : b559f000-b55b6000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-12 09:22:16.025  7004  7004 W art     : b55b6000-b55b7000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b55b7000-b55ba000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-12 09:22:16.025  7004  7004 W art     : b55ba000-b55bb000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-12 09:22:16.025  7004  7004 W art     : b55bb000-b55da000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-12 09:22:16.025  7004  7004 W art     : b55da000-b55db000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-12 09:22:16.025  7004  7004 W art     : b55db000-b55dc000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
,08-12 09:22:16.025  7004  7004 W art     : b55dc000-b561a000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-12 09:22:16.025  7004  7004 W art     : b561a000-b561b000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b561b000-b561d000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-12 09:22:16.025  7004  7004 W art     : b561d000-b561e000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-12 09:22:16.025  7004  7004 W art     : b561f000-b5626000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 09:22:16.025  7004  7004 W art     : b5626000-b5627000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-12 09:22:16.025  7004  7004 W art     : b5627000-b5628000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
,08-12 09:22:16.025  7004  7004 W art     : b5629000-b562c000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 09:22:16.025  7004  7004 W art     : b562c000-b562d000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 09:22:16.025  7004  7004 W art     : b562d000-b562e000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-12 09:22:16.025  7004  7004 W art     : b562e000-b5634000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 09:22:16.025  7004  7004 W art     : b5634000-b5635000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5635000-b5636000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-12 09:22:16.025  7004  7004 W art     : b5636000-b5637000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-12 09:22:16.025  7004  7004 W art     : b5637000-b5640000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-12 09:22:16.025  7004  7004 W art     : b5640000-b5641000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-12 09:22:16.025  7004  7004 W art     : b5641000-b5642000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-12 09:22:16.025  7004  7004 W art     : b5642000-b56d3000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 09:22:16.025  7004  7004 W art     : b56d3000-b56d4000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b56d4000-b56df000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
,08-12 09:22:16.025  7004  7004 W art     : b56df000-b56e0000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-12 09:22:16.025  7004  7004 W art     : b56e1000-b56f3000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-12 09:22:16.025  7004  7004 W art     : b56f3000-b56f4000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-12 09:22:16.025  7004  7004 W art     : b56f4000-b56f5000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-12 09:22:16.025  7004  7004 W art     : b56f6000-b56fb000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
,08-12 09:22:16.025  7004  7004 W art     : b56fb000-b56fc000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-12 09:22:16.025  7004  7004 W art     : b56fc000-b56fd000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-12 09:22:16.025  7004  7004 W art     : b56fe000-b576b000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-12 09:22:16.025  7004  7004 W art     : b576b000-b576c000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b576c000-b576e000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-12 09:22:16.025  7004  7004 W art     : b576e000-b576f000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-12 09:22:16.025  7004  7004 W art     : b576f000-b5770000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-12 09:22:16.025  7004  7004 W art     : b5770000-b5777000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 09:22:16.025  7004  7004 W art     : b5777000-b5778000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 09:22:16.025  7004  7004 W art     : b5778000-b5779000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-12 09:22:16.025  7004  7004 W art     : b577a000-b57fa000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 09:22:16.025  7004  7004 W art     : b57fa000-b57fb000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b57fb000-b57fc000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-12 09:22:16.025  7004  7004 W art     : b57fc000-b57fd000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-12 09:22:16.025  7004  7004 W art     : b57fd000-b5814000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5814000-b584b000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-12 09:22:16.025  7004  7004 W art     : ib/libqc-opt.so
08-12 09:22:16.025  7004  7004 W art     : b584b000-b584c000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 09:22:16.025  7004  7004 W art     : b584c000-b584d000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-12 09:22:16.025  7004  7004 W art     : b584d000-b5869000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 09:22:16.025  7004  7004 W art     : b5869000-b586a000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 09:22:16.025  7004  7004 W art     : b586a000-b586b000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-12 09:22:16.025  7004  7004 W art     : b586c000-b58cd000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-12 09:22:16.025  7004  7004 W art     : b58cd000-b58cf000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-12 09:22:16.025  7004  7004 W art     : b58cf000-b58d0000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-12 09:22:16.025  7004  7004 W art     : b58d1000-b58f8000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-12 09:22:16.025  7004  7004 W art     : b58f8000-b58f9000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b58f9000-b58fa000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-12 09:22:16.025  7004  7004 W art     : b58fa000-b58fb000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-12 09:22:16.025  7004  7004 W art     : b58fc000-b5904000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 09:22:16.025  7004  7004 W art     : b5904000-b5906000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 09:22:16.025  7004  7004 W art     : b5906000-b5907000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-12 09:22:16.025  7004  7004 W art     : b5908000-b590b000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-12 09:22:16.025  7004  7004 W art     : b590b000-b590c000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-12 09:22:16.025  7004  7004 W art     : b590c000-b590d000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-12 09:22:16.025  7004  7004 W art     : b590d000-b5911000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-12 09:22:16.025  7004  7004 W art     : b5911000-b5912000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5912000-b5913000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-12 09:22:16.025  7004  7004 W art     : b5913000-b5914000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-12 09:22:16.025  7004  7004 W art     : b5914000-b5924000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-12 09:22:16.025  7004  7004 W art     : b5924000-b5925000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-12 09:22:16.025  7004  7004 W art     : b5925000-b5926000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-12 09:22:16.025  7004  7004 W art     : b5926000-b596c000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b596c000-b5975000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-12 09:22:16.025  7004  7004 W art     : b5975000-b5976000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-12 09:22:16.025  7004  7004 W art     : b5976000-b5977000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-12 09:22:16.025  7004  7004 W art     : b5978000-b597d000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-12 09:22:16.025  7004  7004 W art     : b597d000-b597e000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-12 09:22:16.025  7004  7004 W art     : b597e000-b597f000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-12 09:22:16.025  7004  7004 W art     : b597f000-b5982000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 09:22:16.025  7004  7004 W art     : b5982000-b5983000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5983000-b5984000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 09:22:16.025  7004  7004 W art     : b5984000-b5985000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-12 09:22:16.025  7004  7004 W art     : b5986000-b599e000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 09:22:16.025  7004  7004 W art     : b599e000-b599f000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b599f000-b59a0000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 09:22:16.025  7004  7004 W art     : b59a0000-b59a1000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-12 09:22:16.025  7004  7004 W art     : b59a2000-b5b3c000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-12 09:22:16.025  7004  7004 W art     : b5b3c000-b5b3d000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5b3d000-b5b4a000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-12 09:22:16.025  7004  7004 W art     : b5b4a000-b5b4b000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-12 09:22:16.025  7004  7004 W art     : b5b4b000-b5b4f000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-12 09:22:16.025  7004  7004 W art     : b5b4f000-b5b50000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5b50000-b5b51000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-12 09:22:16.025  7004  7004 W art     : b5b51000-b5b52000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-12 09:22:16.025  7004  7004 W art     : b5b52000-b5b65000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-12 09:22:16.025  7004  7004 W art     : b5b65000-b5b66000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-12 09:22:16.025  7004  7004 W art     : b5b66000-b5b67000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-12 09:22:16.025  7004  7004 W art     : b5b67000-b5b68000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:16.025  7004  7004 W art     : b5b68000-b5bb3000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-12 09:22:16.025  7004  7004 W art     : b5bb3000-b5bb4000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-12 09:22:16.025  7004  7004 W art     : b5bb4000-b5bb5000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-12 09:22:16.025  7004  7004 W art     : b5bb5000-b5bb7000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5bb8000-b5bc9000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 09:22:16.025  7004  7004 W art     : b5bc9000-b5bca000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5bca000-b5bcb000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 09:22:16.025  7004  7004 W art     : b5bcb000-b5bcc000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-12 09:22:16.025  7004  7004 W art     : b5bcd000-b5bd7000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-12 09:22:16.025  7004  7004 W art     : b5bd7000-b5bd9000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-12 09:22:16.025  7004  7004 W art     : b5bd9000-b5bda000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-12 09:22:16.025  7004  7004 W art     : b5bda000-b5bf3000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-12 09:22:16.025  7004  7004 W art     : b5bf3000-b5bf4000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-12 09:22:16.025  7004  7004 W art     : b5bf4000-b5bf7000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-12 09:22:16.025  7004  7004 W art     : b5bf7000-b5bfb000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5bfb000-b5c6f000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-12 09:22:16.025  7004  7004 W art     : b5c6f000-b5c70000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5c70000-b5c73000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-12 09:22:16.025  7004  7004 W art     : b5c73000-b5c74000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-12 09:22:16.025  7004  7004 W art     : b5c74000-b5c75000 r--p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5c75000-b5c78000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-12 09:22:16.025  7004  7004 W art     : b5c78000-b5c79000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-12 09:22:16.025  7004  7004 W art     : b5c79000-b5c7a000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-12 09:22:16.025  7004  7004 W art     : b5c7a000-b5c7b000 r--p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5c7b000-b5c80000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 09:22:16.025  7004  7004 W art     : b5c80000-b5c81000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 09:22:16.025  7004  7004 W art     : b5c81000-b5c82000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-12 09:22:16.025  7004  7004 W art     : b5c82000-b5c83000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.025  7004  7004 W art     : b5c83000-b5c86000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 09:22:16.025  7004  7004 W art     : b5c86000-b5c87000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 09:22:16.025  7004  7004 W art     : b5c87000-b5c88000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-12 09:22:16.025  7004  7004 W art     : b5c88000-b5c89000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.025  7004  7004 W art     : b5c89000-b5c8d000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-12 09:22:16.025  7004  7004 W art     : b5c8d000-b5c8e000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-12 09:22:16.025  7004  7004 W art     : b5c8e000-b5c8f000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-12 09:22:16.025  7004  7004 W art     : b5c8f000-b5c90000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:16.025  7004  7004 W art     : b5c90000-b5c94000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 09:22:16.025  7004  7004 W art     : b5c94000-b5c95000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 09:22:16.025  7004  7004 W art     : b5c95000-b5c96000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-12 09:22:16.025  7004  7004 W art     : b5c96000-b5c97000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.025  7004  7004 W art     : b5c97000-b5ca5000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-12 09:22:16.025  7004  7004 W art     : b5ca5000-b5ca6000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b5ca6000-b5ca7000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-12 09:22:16.025  7004  7004 W art     : b5ca7000-b5ca8000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-12 09:22:16.025  7004  7004 W art     : b5ca8000-b5cb2000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 09:22:16.025  7004  7004 W art     : b5cb2000-b5cb5000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 09:22:16.025  7004  7004 W art     : b5cb5000-b5cb6000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-12 09:22:16.025  7004  7004 W art     : b5cb6000-b5cb7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.025  7004  7004 W art     : b5cb7000-b5cc1000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-12 09:22:16.025  7004  7004 W art     : b5cc1000-b5cc4000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-12 09:22:16.025  7004  7004 W art     : b5cc4000-b5cc5000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-12 09:22:16.025  7004  7004 W art     : b5cc5000-b5cc9000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-12 09:22:16.025  7004  7004 W art     : b5cc9000-b5cca000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-12 09:22:16.025  7004  7004 W art     : b5cca000-b5ccb000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-12 09:22:16.025  7004  7004 W art     : b5ccb000-b5ccc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.025  7004  7004 W art     : b5ccc000-b5cd9000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-12 09:22:16.025  7004  7004 W art     : b5cd9000-b5cdb000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-12 09:22:16.025  7004  7004 W art     : b5cdb000-b5cdc000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-12 09:22:16.025  7004  7004 W art     : b5cdc000-b60ee000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-12 09:22:16.025  7004  7004 W art     : b60ee000-b60ef000 ---p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b60ef000-b60f8000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-12 09:22:16.025  7004  7004 W art     : b60f8000-b60fc000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-12 09:22:16.025  7004  7004 W art     : b60fc000-b60fd000 rw-p 00000000 00:00 0 
08-12 09:22:16.025  7004  7004 W art     : b60fd000-b6104000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-12 09:22:16.025  7004  7004 W art     : b6104000-b6105000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-12 09:22:16.025  7004  7004 W art     : b6105000-b6106000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-12 09:22:16.035  7004  7004 W art     : b6106000-b6107000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6107000-b6122000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-12 09:22:16.035  7004  7004 W art     : b6122000-b6123000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-12 09:22:16.035  7004  7004 W art     : b6123000-b6124000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-12 09:22:16.035  7004  7004 W art     : b6124000-b6125000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6125000-b6171000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 09:22:16.035  7004  7004 W art     : b6171000-b6172000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6172000-b6173000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 09:22:16.035  7004  7004 W art     : b6173000-b6174000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-12 09:22:16.035  7004  7004 W art     : b6174000-b6175000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6175000-b6179000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-12 09:22:16.035  7004  7004 W art     : b6179000-b617a000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b617a000-b617b000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-12 09:22:16.035  7004  7004 W art     : b617b000-b617c000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-12 09:22:16.035  7004  7004 W art     : b617c000-b61b4000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-12 09:22:16.035  7004  7004 W art     : b61b4000-b61b5000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-12 09:22:16.035  7004  7004 W art     : b61b5000-b61b6000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-12 09:22:16.035  7004  7004 W art     : b61b6000-b61b7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b61b7000-b6255000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-12 09:22:16.035  7004  7004 W art     : b6255000-b6256000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6256000-b6274000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-12 09:22:16.035  7004  7004 W art     : b6274000-b6275000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-12 09:22:16.035  7004  7004 W art     : b6275000-b63e8000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-12 09:22:16.035  7004  7004 W art     : b63e8000-b63f3000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-12 09:22:16.035  7004  7004 W art     : b63f3000-b63f4000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-12 09:22:16.035  7004  7004 W art     : b63f4000-b650b000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-12 09:22:16.035  7004  7004 W art     : b650b000-b6516000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-12 09:22:16.035  7004  7004 W art     : b6516000-b6517000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-12 09:22:16.035  7004  7004 W art     : b6517000-b651b000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b651b000-b653f000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-12 09:22:16.035  7004  7004 W art     : b653f000-b6541000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-12 09:22:16.035  7004  7004 W art     : b6541000-b6542000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-12 09:22:16.035  7004  7004 W art     : b6542000-b65e8000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-12 09:22:16.035  7004  7004 W art     : b65e8000-b65f5000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-12 09:22:16.035  7004  7004 W art     : b65f5000-b65f6000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-12 09:22:16.035  7004  7004 W art     : b65f6000-b65f7000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b65f7000-b664a000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-12 09:22:16.035  7004  7004 W art     : b664a000-b664b000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b664b000-b664c000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-12 09:22:16.035  7004  7004 W art     : b664c000-b664d000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-12 09:22:16.035  7004  7004 W art     : b664d000-b6652000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6652000-b6664000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-12 09:22:16.035  7004  7004 W art     : b6664000-b6665000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6665000-b6666000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-12 09:22:16.035  7004  7004 W art     : b6666000-b6667000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-12 09:22:16.035  7004  7004 W art     : b6667000-b666e000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 09:22:16.035  7004  7004 W art     : b666e000-b666f000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 09:22:16.035  7004  7004 W art     : b666f000-b6670000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-12 09:22:16.035  7004  7004 W art     : b6670000-b6671000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6671000-b6674000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-12 09:22:16.035  7004  7004 W art     : b6674000-b6675000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-12 09:22:16.035  7004  7004 W art     : b6675000-b6676000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-12 09:22:16.035  7004  7004 W art     : b6676000-b667a000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-12 09:22:16.035  7004  7004 W art     : b667a000-b667b000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-12 09:22:16.035  7004  7004 W art     : b667b000-b667c000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-12 09:22:16.035  7004  7004 W art     : b667c000-b668a000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-12 09:22:16.035  7004  7004 W art     : b668a000-b668b000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b668b000-b668c000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-12 09:22:16.035  7004  7004 W art     : b668c000-b668d000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-12 09:22:16.035  7004  7004 W art     : b668d000-b6696000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 09:22:16.035  7004  7004 W art     : b6696000-b6697000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 09:22:16.035  7004  7004 W art     : b6697000-b6698000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-12 09:22:16.035  7004  7004 W art     : b6698000-b66fe000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-12 09:22:16.035  7004  7004 W art     : b66fe000-b66ff000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b66ff000-b6701000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-12 09:22:16.035  7004  7004 W art     : b6701000-b670a000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-12 09:22:16.035  7004  7004 W art     : b670a000-b670d000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b670d000-b67a4000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-12 09:22:16.035  7004  7004 W art     : b67a4000-b67a6000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-12 09:22:16.035  7004  7004 W art     : b67a6000-b67a7000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-12 09:22:16.035  7004  7004 W art     : b67a7000-b67a8000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b67a8000-b6ac9000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-12 09:22:16.035  7004  7004 W art     : b6ac9000-b6aca000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6aca000-b6ae5000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-12 09:22:16.035  7004  7004 W art     : b6ae5000-b6ae9000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-12 09:22:16.035  7004  7004 W art     : b6ae9000-b6aee000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6aee000-b6af6000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 09:22:16.035  7004  7004 W art     : b6af6000-b6af7000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 09:22:16.035  7004  7004 W art     : b6af7000-b6af8000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-12 09:22:16.035  7004  7004 W art     : b6af8000-b6b26000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-12 09:22:16.035  7004  7004 W art     : b6b26000-b6b27000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6b27000-b6b2e000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-12 09:22:16.035  7004  7004 W art     : b6b2e000-b6b2f000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-12 09:22:16.035  7004  7004 W art     : b6b2f000-b6b75000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-12 09:22:16.035  7004  7004 W art     : b6b75000-b6b76000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6b76000-b6b79000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-12 09:22:16.035  7004  7004 W art     : b6b79000-b6b7a000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-12 09:22:16.035  7004  7004 W art     : b6b7a000-b6b95000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-12 09:22:16.035  7004  7004 W art     : b6b95000-b6b99000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-12 09:22:16.035  7004  7004 W art     : b6b99000-b6b9a000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-12 09:22:16.035  7004  7004 W art     : b6b9a000-b6be7000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-12 09:22:16.035  7004  7004 W art     : b6be7000-b6be8000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6be8000-b6bf4000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-12 09:22:16.035  7004  7004 W art     : b6bf4000-b6bf5000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-12 09:22:16.035  7004  7004 W art     : b6bf5000-b6c02000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-12 09:22:16.035  7004  7004 W art     : b6c02000-b6c03000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6c03000-b6c04000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-12 09:22:16.035  7004  7004 W art     : b6c04000-b6c05000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-12 09:22:16.035  7004  7004 W art     : b6c05000-b6c0d000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-12 09:22:16.035  7004  7004 W art     : b6c0d000-b6c0e000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6c0e000-b6c0f000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-12 09:22:16.035  7004  7004 W art     : b6c0f000-b6c10000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-12 09:22:16.035  7004  7004 W art     : b6c10000-b6c17000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-12 09:22:16.035  7004  7004 W art     : b6c17000-b6c18000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-12 09:22:16.035  7004  7004 W art     : b6c18000-b6c19000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-12 09:22:16.035  7004  7004 W art     : b6c19000-b6c2d000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-12 09:22:16.035  7004  7004 W art     : b6c2d000-b6c2f000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-12 09:22:16.035  7004  7004 W art     : b6c2f000-b6c30000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-12 09:22:16.035  7004  7004 W art     : b6c30000-b6c58000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-12 09:22:16.035  7004  7004 W art     : b6c58000-b6c5a000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-12 09:22:16.035  7004  7004 W art     : b6c5a000-b6c5b000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-12 09:22:16.035  7004  7004 W art     : b6c5b000-b6c5e000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-12 09:22:16.035  7004  7004 W art     : b6c5e000-b6c5f000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-12 09:22:16.035  7004  7004 W art     : b6c5f000-b6c60000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-12 09:22:16.035  7004  7004 W art     : b6c60000-b6c69000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-12 09:22:16.035  7004  7004 W art     : b6c69000-b6c6a000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-12 09:22:16.035  7004  7004 W art     : b6c6a000-b6c6b000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-12 09:22:16.035  7004  7004 W art     : b6c6b000-b6c8b000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-12 09:22:16.035  7004  7004 W art     : b6c8b000-b6c8c000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-12 09:22:16.035  7004  7004 W art     : b6c8c000-b6c8d000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-12 09:22:16.035  7004  7004 W art     : b6c8d000-b6d00000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-12 09:22:16.035  7004  7004 W art     : b6d00000-b6d04000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-12 09:22:16.035  7004  7004 W art     : b6d04000-b6d07000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-12 09:22:16.035  7004  7004 W art     : b6d07000-b6d11000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6d11000-b6d99000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-12 09:22:16.035  7004  7004 W art     : b6d99000-b6d9a000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6d9a000-b6d9e000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-12 09:22:16.035  7004  7004 W art     : b6d9e000-b6d9f000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-12 09:22:16.035  7004  7004 W art     : b6d9f000-b6da0000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6da0000-b6dc9000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-12 09:22:16.035  7004  7004 W art     : b6dc9000-b6dca000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6dca000-b6dcd000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-12 09:22:16.035  7004  7004 W art     : b6dcd000-b6dce000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-12 09:22:16.035  7004  7004 W art     : b6dce000-b6ea8000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 09:22:16.035  7004  7004 W art     : b6ea8000-b6eaf000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 09:22:16.035  7004  7004 W art     : b6eaf000-b6eb7000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-12 09:22:16.035  7004  7004 W art     : b6eb7000-b6eb8000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6eb8000-b6eb9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:16.035  7004  7004 W art     : b6eb9000-b6eba000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-12 09:22:16.035  7004  7004 W art     : b6eba000-b6ebb000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6ebb000-b6ebe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6ebe000-b6ee3000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-12 09:22:16.035  7004  7004 W art     : b6ee3000-b6ee4000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6ee4000-b6eeb000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-12 09:22:16.035  7004  7004 W art     : b6eeb000-b6eec000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-12 09:22:16.035  7004  7004 W art     : b6eec000-b6ef3000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-12 09:22:16.035  7004  7004 W art     : b6ef3000-b6ef4000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-12 09:22:16.035  7004  7004 W art     : b6ef4000-b6ef5000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-12 09:22:16.035  7004  7004 W art     : b6ef5000-b6ef6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6ef6000-b6f0e000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-12 09:22:16.035  7004  7004 W art     : b6f0e000-b6f0f000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6f0f000-b6f10000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-12 09:22:16.035  7004  7004 W art     : b6f10000-b6f11000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-12 09:22:16.035  7004  7004 W art     : b6f11000-b6f1f000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-12 09:22:16.035  7004  7004 W art     : b6f1f000-b6f20000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6f20000-b6f21000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-12 09:22:16.035  7004  7004 W art     : b6f21000-b6f22000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-12 09:22:16.035  7004  7004 W art     : b6f22000-b6f23000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:16.035  7004  7004 W art     : b6f23000-b6f25000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6f25000-b6f26000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6f26000-b6f27000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-12 09:22:16.035  7004  7004 W art     : b6f27000-b6f28000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-12 09:22:16.035  7004  7004 W art     : b6f28000-b6f29000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-12 09:22:16.035  7004  7004 W art     : b6f29000-b6f49000 r--s 00000000 00:0b 7179       /dev/__properties__
08-12 09:22:16.035  7004  7004 W art     : b6f49000-b6f4a000 r--p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6f4a000-b6f4b000 ---p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6f4b000-b6f4d000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-12 09:22:16.035  7004  7004 W art     : b6f4d000-b6f4e000 r-xp 00000000 00:00 0          [sigpage]
08-12 09:22:16.035  7004  7004 W art     : b6f4e000-b6f69000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-12 09:22:16.035  7004  7004 W art     : b6f69000-b6f6a000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-12 09:22:16.035  7004  7004 W art     : b6f6a000-b6f6c000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-12 09:22:16.035  7004  7004 W art     : b6f6c000-b6f6e000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : b6f6e000-b6f73000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-12 09:22:16.035  7004  7004 W art     : b6f73000-b6f74000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-12 09:22:16.035  7004  7004 W art     : b6f74000-b6f75000 rw-p 00000000 00:00 0 
08-12 09:22:16.035  7004  7004 W art     : be8a9000-be8ca000 rw-p 00000000 00:00 0          [stack]
08-12 09:22:16.035  7004  7004 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-12 09:22:16.095  7004  7004 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 09:22:16.135  7004  7004 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 09:22:16.145  7004  7004 E AffinityControl: AffinityControl: registerfunction enter
,08-12 09:22:16.165  7004  7004 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 09:22:16.175   738  1745 D PackageManager: START PACKAGE DELETE: observer{240121516}
08-12 09:22:16.175   738  1745 D PackageManager: pkg{<packageName>}
08-12 09:22:16.175   738  1745 D PackageManager: user{0}
08-12 09:22:16.175   738  1745 D PackageManager: caller{2000}
08-12 09:22:16.175   738  1745 D PackageManager: flags{2}
,08-12 09:22:16.175   738  1745 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-12 09:22:16.175   738  1745 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-12 09:22:16.175   738  1745 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-12 09:22:16.175   738  1745 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-12 09:22:16.175   738  1745 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-12 09:22:16.175   738   906 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-12 09:22:16.175   738   906 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-12 09:22:16.175   738   906 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-12 09:22:16.175   738   906 D ApplicationPolicy: getApplicationUninstallationEnabled
08-12 09:22:16.175   738   906 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-12 09:22:16.175   738   906 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-12 09:22:16.175   738   906 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 09:22:16.185   738   906 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-12 09:22:16.185   738   823 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-12 09:22:16.185   738   906 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-12 09:22:16.185   738   906 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-12 09:22:16.185   738   823 I ActivityManager: Killing 6887:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-12 09:22:16.195   738   906 D AASAinstall: there is not AASApackages.xml file
,08-12 09:22:16.235   738  1744 D GraphicsStats: Buffer count: 4
,08-12 09:22:16.235   294   366 D libEGL  : eglTerminate EGLDisplay = 0xb69016fc
,08-12 09:22:16.235   738   752 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a3c9f75)
08-12 09:22:16.235   738  2253 I WindowState: WIN DEATH: Window{7bf6349 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 09:22:16.235   738  1333 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 09:22:16.235   738  1333 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 09:22:16.235   738  1333 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 09:22:16.235   294  5155 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
,08-12 09:22:16.245   294  1297 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
08-12 09:22:16.245   294  1297 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-12 09:22:16.245   738  2253 D InputDispatcher: Focus left window: 6887
,08-12 09:22:16.255   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
,08-12 09:22:16.475   738   906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-12 09:22:16.495   738   906 W PackageSettings: Skipping PackageSetting{6cfb99 com.example.hello/10192} due to missing metadata
,08-12 09:22:16.565   738   906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-12 09:22:16.565   738   823 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 09:22:16.565   738   823 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 09:22:16.565   323   323 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-12 09:22:16.565   738   823 D ActivityManager: mDVFSHelper.acquire()
,08-12 09:22:16.575   738   823 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 09:22:16.575   738   906 I art     : Starting a blocking GC Explicit
,08-12 09:22:16.575   738   823 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 09:22:16.585   738   823 E ActivityManager: Failure starting process com.test.thalitest
08-12 09:22:16.585   738   823 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4999)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4960)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7375)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
08-12 09:22:16.585   738   823 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:22:16.585   738   823 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 09:22:16.585   738   823 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 09:22:16.585   738   823 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 09:22:16.585   738   823 I ActivityManager:   Force finishing activity ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164}
,08-12 09:22:16.605   738   823 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-12 09:22:16.605   738   823 D InputDispatcher: Focused application released
,08-12 09:22:16.605   738   881 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 09:22:16.615   738   881 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-12 09:22:16.615   738   881 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-12 09:22:16.615   738   881 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-12 09:22:16.615   738   881 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
08-12 09:22:16.615   738   881 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-12 09:22:16.615   738   881 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:22:16.615   738   881 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-12 09:22:16.615   738   881 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 09:22:16.615   738   881 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 09:22:16.615   738   881 D SecWifiDisplayUtil: Metadata value : none
,08-12 09:22:16.615   738   881 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8d2f857 V.E...... R.....ID 0,0-0,0}
08-12 09:22:16.615   294   294 I SurfaceFlinger: id=23 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-12 09:22:16.615   738  2239 V WindowOrientationListener: setCurrentAppOrientation :1
,08-12 09:22:16.615   738  2239 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-12 09:22:16.625  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-12 09:22:16.625   738  2239 D InputDispatcher: Focus entered window: 3699
08-12 09:22:16.625   738   824 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3808522 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-12 09:22:16.625   738   881 W WindowManager: Attempted to add application window with unknown token Token{342f831 ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164 f}}.  Aborting.
,08-12 09:22:16.625   738   881 D ViewRootImpl: #3 mView = null
,08-12 09:22:16.625   738   881 W WindowManager: Token{342f831 ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164 f}} already running, starting window not displayed. Unable to add window -- token Token{342f831 ActivityRecord{9218cd8 u0 com.test.thalitest/.MainActivity t164 f}} is not valid; is your activity running?
,08-12 09:22:16.625   738   881 W WindowManager: view not successfully added to wm, removing view
,08-12 09:22:16.625   738   881 W WindowManager: Exception when adding starting window
08-12 09:22:16.625   738   881 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{8d2f857 V.E...... R.....ID 0,0-0,0} not attached to window manager
08-12 09:22:16.625   738   881 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
08-12 09:22:16.625   738   881 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
08-12 09:22:16.625   738   881 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
08-12 09:22:16.625   738   881 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4399)
08-12 09:22:16.625   738   881 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-12 09:22:16.625   738   881 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:22:16.625   738   881 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-12 09:22:16.625   738   881 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 09:22:16.625   738   881 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 09:22:16.625   738   881 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:738 uid:1000
,08-12 09:22:16.625   738   881 D PointerIcon: setMouseCustomIcon IconType is same.101
08-12 09:22:16.625   738   881 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:738 uid:1000
08-12 09:22:16.625   738   881 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-12 09:22:16.625  1730  1730 D Launcher: onRestart, Launcher: 159931723
,08-12 09:22:16.625  1730  1730 D Launcher: onStart, Launcher: 159931723
,08-12 09:22:16.635   738  2257 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-12 09:22:16.635   738  2257 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 09:22:16.635   738   738 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 09:22:16.635   738   738 I KnoxTimeoutHandler: Shared devices show user statefalse
08-12 09:22:16.635   738   738 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-12 09:22:16.635  1730  1730 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-12 09:22:16.635  1730  1730 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-12 09:22:16.635  1730  1730 D Launcher.HomeView: onStart
,08-12 09:22:16.645  1730  1730 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
08-12 09:22:16.645  1730  1730 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-12 09:22:16.645  2405  2484 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-12 09:22:16.655   738  1747 V WindowStateAnimator: Finishing drawing window Window{3808522 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 09:22:16.655  1730  1730 V ActivityThread: updateVisibility : ActivityRecord{acd665b token=android.os.BinderProxy@4c3ef3c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-12 09:22:16.655   738   881 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 09:22:16.665   294   294 I SurfaceFlinger: id=24 createSurf (1194x288),1 flag=4, VSBConnecti
,08-12 09:22:16.665   738   738 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 09:22:16.665   738   738 I KnoxTimeoutHandler: SD activityfalse
,08-12 09:22:16.665   738  3443 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-12 09:22:16.665   294   294 I SurfaceFlinger: id=25 createSurf (1080x1920),1 flag=4, Mauncher
,08-12 09:22:16.665   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbed52364
,08-12 09:22:16.675  3699  3699 V ActivityThread: updateVisibility : ActivityRecord{a9901d9 token=android.os.BinderProxy@deefdab {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-12 09:22:16.675   738   881 D ActivityManager: mDVFSHelper.release()
,08-12 09:22:16.675   738   881 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e51cc6c u0 com.samsung.android.MtpApplication/.USBConnection t163} time:177955
,08-12 09:22:16.685  1730  1730 D Launcher.HomeView: onStop
,08-12 09:22:16.715   738  2257 V WindowStateAnimator: Finishing drawing window Window{72d2570 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-12 09:22:16.715  3699  3699 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@deefdab time:177996
,08-12 09:22:16.715   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbed52364
,08-12 09:22:16.735   738   881 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 09:22:16.735   738   738 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-12 09:22:16.735   738   738 I KnoxTimeoutHandler: SD activityfalse
,08-12 09:22:16.755   738  1321 V WindowStateAnimator: Finishing drawing window Window{9307a4f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-12 09:22:16.755   738   881 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 09:22:16.755   738   738 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-12 09:22:16.755   738   881 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c04f89c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t161} time:178039
08-12 09:22:16.755   738   738 I KnoxTimeoutHandler: SD activityfalse
,08-12 09:22:16.765   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbed52364
,08-12 09:22:16.815   738   906 I art     : Explicit concurrent mark sweep GC freed 140431(7MB) AllocSpace objects, 50(1000KB) LOS objects, 27% free, 42MB/58MB, paused 2.094ms total 242.611ms
,08-12 09:22:16.845   738   906 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 09:22:16.845   738   906 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-12 09:22:16.845   738   906 D AASAinstall: there is not AASApackages.xml file
08-12 09:22:16.845   738   906 D PackageManager: result of delete: 1{240121516}
,08-12 09:22:16.845  7004  7004 I art     : System.exit called, status: 0
08-12 09:22:16.845  7004  7004 I AndroidRuntime: VM exiting with result code 0.
,08-12 09:22:16.855   738   906 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-12 09:22:16.855   738   906 D PackageManager: userId{-1}
08-12 09:22:16.855   738   906 D PackageManager: andCode{true}
,08-12 09:22:16.855   738   906 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-12 09:22:16.875  5821  7028 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-12 09:22:16.875  5821  7028 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-12 09:22:16.875  5821  7028 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-12 09:22:16.895   738   823 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 09:22:16.895   738   823 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 09:22:16.895   738   823 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-12 09:22:16.905   738   738 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.905   738   738 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.905   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-12 09:22:16.915  1378  1378 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.915   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.925   738   881 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.925   738   881 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.925   738  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 09:22:16.925   738   811 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.935  2022  2469 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 09:22:16.935   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.935   738   738 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.935  1986  1986 E SamsungIME: mOCRHelper is null
,08-12 09:22:16.945   738   823 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f39d6b u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88c9cf1 4309:com.samsung.klmsagent/u0a18}
,08-12 09:22:16.945  4309  4309 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 12 09:22:16 GMT+02:00 2016
,08-12 09:22:16.955   738   738 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.955   738   738 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.955  4309  4309 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-12 09:22:16.955  1711  1711 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 09:22:16.965   738   811 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.965   738   811 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.965   738  2261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f39d6b u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc9c25 738:system/1000}
08-12 09:22:16.965   738   738 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.965   738   738 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.965   738   738 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.965   738   738 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.965  4309  4309 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-12 09:22:16.965  4309  4309 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 09:22:16.965  3192  3208 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 09:22:16.965  4309  4309 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-12 09:22:16.975  4309  7035 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-12 09:22:16.975  3192  3208 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 09:22:16.975  3192  3208 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 09:22:16.975  3192  3208 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-12 09:22:16.975   738   738 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-12 09:22:16.975   738  1415 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-12 09:22:16.975   738   738 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.975   738   738 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.975   738  1366 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/164_task.xml
,08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-12 09:22:16.975  4309  7035 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-12 09:22:16.975   738   738 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.985   738   738 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-12 09:22:16.985  4309  7035 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-12 09:22:16.985   738   738 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.985   738   738 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.985  4309  7035 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-12 09:22:16.985   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.995  4309  7035 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-12 09:22:16.995   738  1324 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-12 09:22:16.995   738  1324 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-12 09:22:16.995   738  1323 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-12 09:22:16.995   738  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 09:22:16.995   738  1323 V NetworkStats: performPollLocked(flags=0x3)
,08-12 09:22:16.995   738   811 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 09:22:16.995   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.005   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.005  1705  7036 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-12 09:22:17.005   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.005   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.005   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.005  1705  7036 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-12 09:22:17.005   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.005  1705  7036 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-12 09:22:17.005  1705  7036 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-12 09:22:17.005  1705  7036 D RegisteredComponentCache: Collect Tech packages for Knox
,08-12 09:22:17.005  4309  7035 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: #################################################################
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: #################################################################
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-12 09:22:17.005  4309  7035 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: #################################################################
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: #################################################################
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-12 09:22:17.005  4309  7035 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 09:22:17.015   738  1323 V NetworkStats: performPollLocked() took 15ms
,08-12 09:22:17.015   738  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 09:22:17.015  4309  7035 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015   738   811 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.015   738   811 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015  4309  7035 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.015   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.015   738   811 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738  1324 D NtpTrustedTime: currentTimeMillis() cache hit
08-12 09:22:17.025   738  1324 D NtpTrustedTime: currentTimeMillis() cache hit
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   811 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.025   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.035   738  1415 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-12 09:22:17.035   738  1415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-12 09:22:17.035   738  1415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-12 09:22:17.035   738  1415 D SettingsProvider: selectionArgs: false
08-12 09:22:17.035   738  1415 D SettingsProvider: selectionArgs: 10018
,08-12 09:22:17.035   738  1415 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-12 09:22:17.035   738  1415 D SettingsProvider: ret = -1
,08-12 09:22:17.035  4309  7035 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-12 09:22:17.035  4309  7035 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-12 09:22:17.035   738   738 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.035   738   738 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.035   738   811 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.035   738   811 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.035   738   738 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.035   738   738 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-12 09:22:17.045   738  1323 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7088e436 in tid 1323 (NetworkStats)
,08-12 09:22:17.045  2152  2152 E audit_log: File locking failed. error= Bad file descriptor
,08-12 09:22:17.045  2152  2152 E audit_log: File locking failed. error= Bad file descriptor
,08-12 09:22:17.115   321   321 E installd: eof
08-12 09:22:17.115   321   321 E installd: failed to read size
08-12 09:22:17.115   321   321 I installd: closing connection
,08-12 09:22:17.115   293   293 I ServiceManager: service 'notification' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'devicestoragemonitor' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'location' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'country_detector' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'sec_location' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'search' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'execute' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'dropbox' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'wallpaper' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'audio' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'DockObserver' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'midi' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'usb' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'serial' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'kiesusb' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'jobscheduler' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'backup' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'appwidget' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'voiceinteraction' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'SecExternalDisplayService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'diskstats' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'mDNIe' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'AAS' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'MSCS' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'spengestureservice' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'quickconnect' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'samplingprofiler' died
08-12 09:22:17.115   318   947 W AudioFlinger: power manager service died !!!
08-12 09:22:17.115   293   293 I ServiceManager: service 'commontime_management' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'dreams' died
08-12 09:22:17.115   318   947 W AudioFlinger: power manager service died !!!
08-12 09:22:17.115   293   293 I ServiceManager: service 'graphicsstats' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'print' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'restrictions' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'media_session' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'media_router' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'trust' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'fingerprint' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'launcherapps' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'voip' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'media_projection' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'lpnet' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'imms' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'sec_analytics' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'telecom' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'edmnativehelper' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'user' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'procstats' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'meminfo' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'gfxinfo' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'dbinfo' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'cpuinfo' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'permi,ssion' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'processinfo' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'sensorservice' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'mdm.remotedesktop' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'battery' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'usagestats' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'webviewupdate' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'scheduling_policy' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'telephony.registry' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'persona' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'clipboard' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'clipboardEx' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'network_management' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'ABTPersistenceService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'textservices' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'network_score' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'netstats' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'netpolicy' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'wifip2p' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'wifi' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'wifihs20' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'wifiscanner' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'rttmanager' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'ethernet' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'connectivity' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'sb_service' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'servicediscovery' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'updatelock' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'SEAMService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'media.camera.proxy' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'account' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'content' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'DirEncryptService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'LSManager' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'ReactiveService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'DeviceRootKeyService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'EngineeringModeService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'SatsService' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'sedenial' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'vibrator' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'tw_toolbox' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'tima' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'iccc' died
08-12 09:22:17.115   293   293 I ServiceManager: service 'cepproxyks' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'emailksproxy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'CustomFrequencyManagerService' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'consumer_ir' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'alarm' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'persona_policy' died
08-12 09:22:17.125  2152  2152 E audit_log: File locking failed. error= Bad file descriptor
08-12 09:22:17.125   293   293 I ServiceManager: service 'cover' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'mount' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'lock_settings' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'deviceidle' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'device_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'harmony_eas_service' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'sdp' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'sdp_log' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'dlp' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'log_manager_service' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'context_aware' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'scontext' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'barbeam' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'multiwindow_facade' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'window' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'input' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'bluetooth_manager' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'rcp' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'input_method' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'accessibility' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'package' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'activity' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'knox_ccm_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'enterprise_license_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'application_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'wifi_policy' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'phone_restriction_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'remoteinjection' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'knox_ucsm_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'edm_proxy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'mum_container_policy' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'enterprise_billing_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'otp_service' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'enterprise_shared_device_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'knox_timakeystore_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'enterprise_policy' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'statusbar' died
,08-12 09:22:17.125   293   293 I ServiceManager: service 'uimode' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'batterystats' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'appops' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'power' died
08-12 09:22:17.125   293   293 I ServiceManager: service 'display' died
,08-12 09:22:17.125   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-12 09:22:17.125   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-12 09:22:17.125   294  5155 I SurfaceFlinger: restart the boot-animation @ binderDied
08-12 09:22:17.125  1705  1705 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x710b601e in tid 1705 (com.android.nfc)
08-12 09:22:17.125  1705  1705 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 09:22:17.125  1814  1960 E WifiManager: Channel connection lost
,08-12 09:22:17.125  1378  1624 E WifiManager: Channel connection lost
08-12 09:22:17.135  1711  1711 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-12 09:22:17.135  2202  2214 W Sensors : sensorservice died [0xad73eb40]
08-12 09:22:17.135  1874  1884 W Sensors : sensorservice died [0xad73eb80]
08-12 09:22:17.135  1378  1408 W Sensors : sensorservice died [0xa9869d00]
08-12 09:22:17.135  2147  2147 D HeadsetStateMachine: Proxy object disconnected
,08-12 09:22:17.135   294   368 I SurfaceFlinger: id=15 Removed EimLayer(An (2/10)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=2 Removed GocusedStac (7/9)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=14 Removed EimLayer(Di (3/6)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=2 Removed GocusedStac (-2/6)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/6)
08-12 09:22:17.135   294   368 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/6)
,08-12 09:22:17.135  2147  2147 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ecad894 in tid 2147 (droid.bluetooth)
,08-12 09:22:17.135  2022  2466 E WifiManager: Channel connection lost
,08-12 09:22:17.135  5857  5914 E WifiManager: Channel connection lost
,08-12 09:22:17.135  2022  2033 W Sensors : sensorservice died [0xa9867e00]
,08-12 09:22:17.145   294   368 I SurfaceFlinger: id=5 Removed TtatusBar (4/5)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=25 Removed Mauncher (1/4)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=7 Removed JmageWallpa (0/3)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/3)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/3)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/3)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=23 Removed VSBConnecti (1/2)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=24 Removed VSBConnecti (0/1)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=25 Removed Mauncher (-2/1)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=24 Removed VSBConnecti (-2/1)
08-12 09:22:17.145   294   368 I SurfaceFlinger: id=23 Removed VSBConnecti (-2/1)
,08-12 09:22:17.145  2147  2147 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 09:22:17.145  1730  3073 W Sensors : sensorservice died [0xad96a300]
,08-12 09:22:17.145  2152  2152 E audit_log: File locking failed. error= Bad file descriptor
,08-12 09:22:17.155  1711  2452 E WifiManager: Channel connection lost
,08-12 09:22:17.155   294   366 I SurfaceFlinger: id=18 Removed DolorFade (0/0)
08-12 09:22:17.155   294   366 I SurfaceFlinger: id=18 Removed DolorFade (-2/0)
08-12 09:22:17.155   294   366 I SurfaceFlinger: id=5 Removed TtatusBar (-2/0)
,08-12 09:22:17.155   294  1297 D libEGL  : eglTerminate EGLDisplay = 0xb46bf6fc
,08-12 09:22:17.155   294  1297 D libEGL  : eglTerminate EGLDisplay = 0xb46bf6fc
,08-12 09:22:17.155  4309  7035 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x715b90c1 in tid 7035 (IntentService[K)
,08-12 09:22:17.155  4309  7035 F libc    : Unable to open connection to debuggerd: Connection refused
,08-12 09:22:17.155  2152  2152 E audit_log: File locking failed. error= Bad file descriptor
,08-12 09:22:17.165  2188  2188 D BluetoothA2dp: Proxy object disconnected
,08-12 09:22:17.165  5000  5000 D BluetoothA2dp: Proxy object disconnected
08-12 09:22:17.165  5000  5000 D A2dpProfile: Bluetooth service disconnected
08-12 09:22:17.165  5000  5000 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 09:22:17.165  5000  5000 D PanProfile: Bluetooth service disconnected
08-12 09:22:17.165  5000  5000 D BluetoothMap: Proxy object disconnected
08-12 09:22:17.165  5000  5000 D MapProfile: Bluetooth service disconnected
,08-12 09:22:17.165  5000  5000 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b8ce2bd in tid 5000 (ndroid.settings)
,08-12 09:22:17.165  5000  5000 F libc    : Unable to open connection to debuggerd: Connection refused
08-12 09:22:17.165  2152  2152 E audit_log: File locking failed. error= Bad file descriptor
,08-12 09:22:17.175   293   293 I ServiceManager: service 'nfc' died
08-12 09:22:17.175   293   293 I ServiceManager: service 'secontroller' died
08-12 09:22:17.175   293   293 I ServiceManager: service 'nfccontroller' died
,08-12 09:22:17.205   350   350 I Zygote  : Process 4309 exited due to signal (7)
,08-12 09:22:17.205   350   350 I Zygote  : Process 1705 exited due to signal (7)
,08-12 09:22:17.225   350   350 I Zygote  : Process 2147 exited due to signal (7)
,08-12 09:22:17.225   350   350 I Zygote  : Process 5000 exited due to signal (7)
,08-12 09:22:17.375   294   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-12 09:22:17.375   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-12 09:22:17.385   292   292 I lowmemorykiller: ActivityManager disconnected
08-12 09:22:17.385   292   292 I lowmemorykiller: Closing Activity Manager data connection
,08-12 09:22:17.625   294   294 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-12 09:22:17.625   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
,08-12 09:22:17.635   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
,08-12 09:22:17.635   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
08-12 09:22:17.635   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
,08-12 09:22:17.635   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
,08-12 09:22:17.635   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
,08-12 09:22:17.645   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
,08-12 09:22:17.645   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed5238c
,08-12 09:22:17.645   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbed523a4
,08-12 09:22:17.665   294   294 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
08-12 09:22:17.665   294   294 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
08-12 09:22:17.665   294   294 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,08-12 09:22:17.725   294   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
