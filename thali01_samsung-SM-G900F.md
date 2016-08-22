#### Test 79763830f325397_thali01_samsung-SM-G900F Logs


```
--------- beginning of main,
08-22 12:04:36.330  3878  4771 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
08-22 12:04:37.270  2114  2114 E audit   : type=1400 msg=audit(1471860277.270:278): avc:  denied  { execmod } for  pid=6155 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-22 12:04:37.270  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:37.270  2114  2114 E audit   : type=1300 msg=audit(1471860277.270:278): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f43000 a1=51000 a2=5 a3=4 items=0 ppid=3392 ppcomm=adbd pid=6155 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-22 12:04:37.280  2114  2114 E audit   : type=1327 msg=audit(1471860277.270:278): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-22 12:04:37.280  2114  2114 E audit   : type=1320 msg=audit(1471860277.270:278): 
08-22 12:04:37.330  2114  2114 E audit   : type=1400 msg=audit(1471860277.320:279): avc:  denied  { execmod } for  pid=6155 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-22 12:04:37.330  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:37.330  2114  2114 E audit   : type=1300 msg=audit(1471860277.320:279): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f02000 a1=51000 a2=5 a3=4 items=0 ppid=3392 ppcomm=adbd pid=6155 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-22 12:04:37.330  2114  2114 E audit   : type=1327 msg=audit(1471860277.320:279): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-22 12:04:37.340  2114  2114 E audit   : type=1320 msg=audit(1471860277.320:279): 
08-22 12:04:37.370  2114  2114 E audit   : type=1400 msg=audit(1471860277.370:280): avc:  denied  { execmod } for  pid=6155 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-22 12:04:37.370  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:37.370  6155  6155 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-22 12:04:37.370  2114  2114 E audit   : type=1300 msg=audit(1471860277.370:280): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f02000 a1=51000 a2=5 a3=4 items=0 ppid=3392 ppcomm=adbd pid=6155 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-22 12:04:37.370  2114  2114 E audit   : type=1327 msg=audit(1471860277.370:280): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-22 12:04:37.380  2114  2114 E audit   : type=1320 msg=audit(1471860277.370:280): 
08-22 12:04:37.380  6155  6155 D AndroidRuntime: CheckJNI is OFF
08-22 12:04:37.380  6155  6155 D AndroidRuntime: readGMSProperty: start
08-22 12:04:37.380  6155  6155 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:04:37.380  6155  6155 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 12:04:37.380  6155  6155 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:04:37.380  6155  6155 D AndroidRuntime: readGMSProperty: end
08-22 12:04:37.380  6155  6155 D AndroidRuntime: addProductProperty: start
08-22 12:04:37.390  6155  6155 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-22 12:04:37.390  6155  6155 W art     : af0a4000-b1fca000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-22 12:04:37.390  6155  6155 W art     : b1fca000-b4239000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-22 12:04:37.390  6155  6155 W art     : b4239000-b423a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-22 12:04:37.390  6155  6155 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-22 12:04:37.390  6155  6155 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-22 12:04:37.390  6155  6155 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-22 12:04:37.390  6155  6155 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-22 12:04:37.390  6155  6155 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-22 12:04:37.390  6155  6155 W art     : b47d3000-b47d6000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-22 12:04:37.390  6155  6155 W art     : b47d6000-b47d7000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-22 12:04:37.390  6155  6155 W art     : b47d7000-b47d8000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-22 12:04:37.390  6155  6155 W art     : b47d8000-b47d9000 r--p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b47d9000-b47f9000 r--s 00000000 00:0b 8200       /dev/__properties__
08-22 12:04:37.390  6155  6155 W art     : b47f9000-b520a000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-22 12:04:37.390  6155  6155 W art     : b520a000-b520b000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b520b000-b5254000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-22 12:04:37.390  6155  6155 W art     : b5254000-b5255000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-22 12:04:37.390  6155  6155 W art     : b5255000-b525d000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b525d000-b525e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b525e000-b5293000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-22 12:04:37.390  6155  6155 W art     : b5293000-b5294000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5294000-b5295000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-22 12:04:37.390  6155  6155 W art     : b5295000-b5296000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-22 12:04:37.390  6155  6155 W art     : b5296000-b52ee000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-22 12:04:37.390  6155  6155 W art     : b52ee000-b52ef000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b52ef000-b52f0000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-22 12:04:37.390  6155  6155 W art     : b52f0000-b52f1000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-22 12:04:37.390  6155  6155 W art     : b52f2000-b52f8000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-22 12:04:37.390  6155  6155 W art     : b52f8000-b52f9000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-22 12:04:37.390  6155  6155 W art     : b52f9000-b52fa000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-22 12:04:37.390  6155  6155 W art     : b52fa000-b52fc000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b52fd000-b5307000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-22 12:04:37.390  6155  6155 W art     : b5307000-b530a000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-22 12:04:37.390  6155  6155 W art     : b530a000-b530b000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-22 12:04:37.390  6155  6155 W art     : b530c000-b5323000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-22 12:04:37.390  6155  6155 W art     : b5323000-b5324000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5324000-b5325000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-22 12:04:37.390  6155  6155 W art     : b5325000-b5326000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-22 12:04:37.390  6155  6155 W art     : b5327000-b5331000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-22 12:04:37.390  6155  6155 W art     : b5331000-b5332000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-22 12:04:37.390  6155  6155 W art     : b5332000-b5333000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-22 12:04:37.390  6155  6155 W art     : b5333000-b5337000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-22 12:04:37.390  6155  6155 W art     : b5337000-b5338000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-22 12:04:37.390  6155  6155 W art     : b5338000-b5339000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-22 12:04:37.390  6155  6155 W art     : b5339000-b534f000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-22 12:04:37.390  6155  6155 W art     : b534f000-b5350000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-22 12:04:37.390  6155  6155 W art     : b5350000-b5351000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-22 12:04:37.390  6155  6155 W art     : b5351000-b535e000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-22 12:04:37.390  6155  6155 W art     : b535e000-b535f000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-22 12:04:37.390  6155  6155 W art     : b535f000-b5360000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-22 12:04:37.390  6155  6155 W art     : b5360000-b53c0000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-22 12:04:37.390  6155  6155 W art     : b53c0000-b53c3000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-22 12:04:37.390  6155  6155 W art     : b53c3000-b53c7000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b53c7000-b5428000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-22 12:04:37.390  6155  6155 W art     : b5428000-b5429000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-22 12:04:37.390  6155  6155 W art     : b5429000-b5478000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-22 12:04:37.390  6155  6155 W art     : b5478000-b547a000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-22 12:04:37.390  6155  6155 W art     : b547a000-b547b000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-22 12:04:37.390  6155  6155 W art     : b547b000-b547c000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b547c000-b5483000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-22 12:04:37.390  6155  6155 W art     : b5483000-b5484000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-22 12:04:37.390  6155  6155 W art     : b5484000-b5485000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-22 12:04:37.390  6155  6155 W art     : avc_common.so
08-22 12:04:37.390  6155  6155 W art     : b5486000-b5489000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-22 12:04:37.390  6155  6155 W art     : b5489000-b548a000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-22 12:04:37.390  6155  6155 W art     : b548a000-b548b000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-22 12:04:37.390  6155  6155 W art     : enc_common.so
08-22 12:04:37.390  6155  6155 W art     : b548c000-b5490000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-22 12:04:37.390  6155  6155 W art     : b5490000-b5491000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5491000-b5492000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-22 12:04:37.390  6155  6155 W art     : b5492000-b5493000 rw-p 00005000 b3:17 2510       /syste
08-22 12:04:37.390  6155  6155 W art     : m/lib/libpowermanager.so
08-22 12:04:37.390  6155  6155 W art     : b5494000-b54b1000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-22 12:04:37.390  6155  6155 W art     : b54b1000-b54b2000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-22 12:04:37.390  6155  6155 W art     : b54b2000-b54b3000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-22 12:04:37.390  6155  6155 W art     : b54b4000-b54b9000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-22 12:04:37.390  6155  6155 W art     : b54b9000-b54ba000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-22 12:04:37.390  6155  6155 W art     : b54ba000-b54bb000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-22 12:04:37.390  6155  6155 W art     : b54bc000-b54ed000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-22 12:04:37.390  6155  6155 W art     : b54ed000-b54f0000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-22 12:04:37.390  6155  6155 W art     : b54f0000-b54f1000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-22 12:04:37.390  6155  6155 W art     : b54f2000-b552d000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-22 12:04:37.390  6155  6155 W art     : b552d000-b552e000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-22 12:04:37.390  6155  6155 W art     : b552e000-b552f000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-22 12:04:37.390  6155  6155 W art     : b5530000-b5537000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-22 12:04:37.390  6155  6155 W art     : b5537000-b5538000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5538000-b5539000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-22 12:04:37.390  6155  6155 W art     : b5539000-b553a000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-22 12:04:37.390  6155  6155 W art     : b553a000-b553b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b553b000-b5552000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-22 12:04:37.390  6155  6155 W art     : b5552000-b5553000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5553000-b5556000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-22 12:04:37.390  6155  6155 W art     : b5556000-b5557000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-22 12:04:37.390  6155  6155 W art     : b5557000-b5576000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-22 12:04:37.390  6155  6155 W art     : b5576000-b5577000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-22 12:04:37.390  6155  6155 W art     : b5577000-b5578000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-22 12:04:37.390  6155  6155 W art     : b5578000-b55b6000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-22 12:04:37.390  6155  6155 W art     : b55b6000-b55b7000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b55b7000-b55b9000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-22 12:04:37.390  6155  6155 W art     : b55b9000-b55ba000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-22 12:04:37.390  6155  6155 W art     : b55bb000-b55c2000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-22 12:04:37.390  6155  6155 W art     : b55c2000-b55c3000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-22 12:04:37.390  6155  6155 W art     : b55c3000-b55c4000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-22 12:04:37.390  6155  6155 W art     : b55c5000-b55c8000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-22 12:04:37.390  6155  6155 W art     : b55c8000-b55c9000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-22 12:04:37.390  6155  6155 W art     : b55c9000-b55ca000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-22 12:04:37.390  6155  6155 W art     : b55ca000-b55d0000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-22 12:04:37.390  6155  6155 W art     : b55d0000-b55d1000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b55d1000-b55d2000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-22 12:04:37.390  6155  6155 W art     : b55d2000-b55d3000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-22 12:04:37.390  6155  6155 W art     : b55d3000-b55dc000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-22 12:04:37.390  6155  6155 W art     : b55dc000-b55dd000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-22 12:04:37.390  6155  6155 W art     : b55dd000-b55de000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-22 12:04:37.390  6155  6155 W art     : b55de000-b566f000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-22 12:04:37.390  6155  6155 W art     : b566f000-b5670000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5670000-b567b000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-22 12:04:37.390  6155  6155 W art     : b567b000-b567c000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-22 12:04:37.390  6155  6155 W art     : b567d000-b568f000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-22 12:04:37.390  6155  6155 W art     : b568f000-b5690000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-22 12:04:37.390  6155  6155 W art     : b5690000-b5691000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-22 12:04:37.390  6155  6155 W art     : b5692000-b5697000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-22 12:04:37.390  6155  6155 W art     : b5697000-b5698000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-22 12:04:37.390  6155  6155 W art     : b5698000-b5699000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-22 12:04:37.390  6155  6155 W art     : b569a000-b5707000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-22 12:04:37.390  6155  6155 W art     : b5707000-b5708000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5708000-b570a000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-22 12:04:37.390  6155  6155 W art     : b570a000-b570b000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-22 12:04:37.390  6155  6155 W art     : b570b000-b570c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b570c000-b5713000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-22 12:04:37.390  6155  6155 W art     : b5713000-b5714000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-22 12:04:37.390  6155  6155 W art     : b5714000-b5715000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-22 12:04:37.390  6155  6155 W art     : b5716000-b5796000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-22 12:04:37.390  6155  6155 W art     : b5796000-b5797000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5797000-b5798000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-22 12:04:37.390  6155  6155 W art     : b5798000-b5799000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-22 12:04:37.390  6155  6155 W art     : b5799000-b57b0000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b57b0000-b57e7000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-22 12:04:37.390  6155  6155 W art     : ib/libqc-opt.so
08-22 12:04:37.390  6155  6155 W art     : b57e7000-b57e8000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-22 12:04:37.390  6155  6155 W art     : b57e8000-b57e9000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-22 12:04:37.390  6155  6155 W art     : b57e9000-b5805000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-22 12:04:37.390  6155  6155 W art     : b5805000-b5806000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-22 12:04:37.390  6155  6155 W art     : b5806000-b5807000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-22 12:04:37.390  6155  6155 W art     : b5808000-b5869000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-22 12:04:37.390  6155  6155 W art     : b5869000-b586b000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-22 12:04:37.390  6155  6155 W art     : b586b000-b586c000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-22 12:04:37.390  6155  6155 W art     : b586d000-b5894000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-22 12:04:37.390  6155  6155 W art     : b5894000-b5895000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5895000-b5896000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-22 12:04:37.390  6155  6155 W art     : b5896000-b5897000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-22 12:04:37.390  6155  6155 W art     : b5898000-b58a0000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-22 12:04:37.390  6155  6155 W art     : b58a0000-b58a2000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-22 12:04:37.390  6155  6155 W art     : b58a2000-b58a3000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-22 12:04:37.390  6155  6155 W art     : b58a4000-b58a7000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-22 12:04:37.390  6155  6155 W art     : b58a7000-b58a8000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-22 12:04:37.390  6155  6155 W art     : b58a8000-b58a9000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-22 12:04:37.390  6155  6155 W art     : b58a9000-b58ad000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-22 12:04:37.390  6155  6155 W art     : b58ad000-b58ae000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b58ae000-b58af000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-22 12:04:37.390  6155  6155 W art     : b58af000-b58b0000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-22 12:04:37.390  6155  6155 W art     : b58b0000-b58c0000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-22 12:04:37.390  6155  6155 W art     : b58c0000-b58c1000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-22 12:04:37.390  6155  6155 W art     : b58c1000-b58c2000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-22 12:04:37.390  6155  6155 W art     : b58c2000-b5908000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5908000-b5911000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-22 12:04:37.390  6155  6155 W art     : b5911000-b5912000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-22 12:04:37.390  6155  6155 W art     : b5912000-b5913000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-22 12:04:37.390  6155  6155 W art     : b5914000-b5919000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-22 12:04:37.390  6155  6155 W art     : b5919000-b591a000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-22 12:04:37.390  6155  6155 W art     : b591a000-b591b000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-22 12:04:37.390  6155  6155 W art     : b591b000-b591e000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-22 12:04:37.390  6155  6155 W art     : b591e000-b591f000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b591f000-b5920000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-22 12:04:37.390  6155  6155 W art     : b5920000-b5921000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-22 12:04:37.390  6155  6155 W art     : b5922000-b593a000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-22 12:04:37.390  6155  6155 W art     : b593a000-b593b000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b593b000-b593c000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-22 12:04:37.390  6155  6155 W art     : b593c000-b593d000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-22 12:04:37.390  6155  6155 W art     : b593e000-b5ad8000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-22 12:04:37.390  6155  6155 W art     : b5ad8000-b5ad9000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5ad9000-b5ae6000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-22 12:04:37.390  6155  6155 W art     : b5ae6000-b5ae7000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-22 12:04:37.390  6155  6155 W art     : b5ae7000-b5aeb000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-22 12:04:37.390  6155  6155 W art     : b5aeb000-b5aec000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5aec000-b5aed000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-22 12:04:37.390  6155  6155 W art     : b5aed000-b5aee000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-22 12:04:37.390  6155  6155 W art     : b5aee000-b5b01000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-22 12:04:37.390  6155  6155 W art     : b5b01000-b5b02000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-22 12:04:37.390  6155  6155 W art     : b5b02000-b5b03000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-22 12:04:37.390  6155  6155 W art     : b5b03000-b5b04000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:37.390  6155  6155 W art     : b5b04000-b5b4f000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-22 12:04:37.390  6155  6155 W art     : b5b4f000-b5b50000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-22 12:04:37.390  6155  6155 W art     : b5b50000-b5b51000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-22 12:04:37.390  6155  6155 W art     : b5b51000-b5b53000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5b54000-b5b65000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-22 12:04:37.390  6155  6155 W art     : b5b65000-b5b66000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5b66000-b5b67000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-22 12:04:37.390  6155  6155 W art     : b5b67000-b5b68000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-22 12:04:37.390  6155  6155 W art     : b5b69000-b5b73000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-22 12:04:37.390  6155  6155 W art     : b5b73000-b5b75000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-22 12:04:37.390  6155  6155 W art     : b5b75000-b5b76000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-22 12:04:37.390  6155  6155 W art     : b5b76000-b5b8f000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-22 12:04:37.390  6155  6155 W art     : b5b8f000-b5b90000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-22 12:04:37.390  6155  6155 W art     : b5b90000-b5b93000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-22 12:04:37.390  6155  6155 W art     : b5b93000-b5b97000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5b97000-b5c0b000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-22 12:04:37.390  6155  6155 W art     : b5c0b000-b5c0c000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5c0c000-b5c0f000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-22 12:04:37.390  6155  6155 W art     : b5c0f000-b5c10000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-22 12:04:37.390  6155  6155 W art     : b5c10000-b5c11000 r--p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5c11000-b5c14000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-22 12:04:37.390  6155  6155 W art     : b5c14000-b5c15000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-22 12:04:37.390  6155  6155 W art     : b5c15000-b5c16000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-22 12:04:37.390  6155  6155 W art     : b5c16000-b5c17000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b5c17000-b5c1c000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-22 12:04:37.390  6155  6155 W art     : b5c1c000-b5c1d000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-22 12:04:37.390  6155  6155 W art     : b5c1d000-b5c1e000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-22 12:04:37.390  6155  6155 W art     : b5c1e000-b5c1f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b5c1f000-b5c22000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-22 12:04:37.390  6155  6155 W art     : b5c22000-b5c23000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-22 12:04:37.390  6155  6155 W art     : b5c23000-b5c24000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-22 12:04:37.390  6155  6155 W art     : b5c24000-b5c25000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b5c25000-b5c29000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-22 12:04:37.390  6155  6155 W art     : b5c29000-b5c2a000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-22 12:04:37.390  6155  6155 W art     : b5c2a000-b5c2b000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-22 12:04:37.390  6155  6155 W art     : b5c2b000-b5c2c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:37.390  6155  6155 W art     : b5c2c000-b5c30000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-22 12:04:37.390  6155  6155 W art     : b5c30000-b5c31000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-22 12:04:37.390  6155  6155 W art     : b5c31000-b5c32000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-22 12:04:37.390  6155  6155 W art     : b5c32000-b5c33000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b5c33000-b5c41000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-22 12:04:37.390  6155  6155 W art     : b5c41000-b5c42000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b5c42000-b5c43000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-22 12:04:37.390  6155  6155 W art     : b5c43000-b5c44000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-22 12:04:37.390  6155  6155 W art     : b5c44000-b5c4e000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-22 12:04:37.390  6155  6155 W art     : b5c4e000-b5c51000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-22 12:04:37.390  6155  6155 W art     : b5c51000-b5c52000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-22 12:04:37.390  6155  6155 W art     : b5c52000-b5c53000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-22 12:04:37.390  6155  6155 W art     : b5c5d000-b5c60000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-22 12:04:37.390  6155  6155 W art     : b5c60000-b5c61000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-22 12:04:37.390  6155  6155 W art     : b5c61000-b5c65000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-22 12:04:37.390  6155  6155 W art     : b5c65000-b5c66000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-22 12:04:37.390  6155  6155 W art     : b5c66000-b5c67000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-22 12:04:37.390  6155  6155 W art     : b5c67000-b5c68000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b5c68000-b5c75000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-22 12:04:37.390  6155  6155 W art     : b5c75000-b5c77000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-22 12:04:37.390  6155  6155 W art     : b5c77000-b5c78000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-22 12:04:37.390  6155  6155 W art     : b5c78000-b608a000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-22 12:04:37.390  6155  6155 W art     : b608a000-b608b000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b608b000-b6094000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-22 12:04:37.390  6155  6155 W art     : b6094000-b6098000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-22 12:04:37.390  6155  6155 W art     : b6098000-b6099000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6099000-b60a0000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-22 12:04:37.390  6155  6155 W art     : b60a0000-b60a1000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-22 12:04:37.390  6155  6155 W art     : b60a1000-b60a2000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-22 12:04:37.390  6155  6155 W art     : b60a2000-b60a3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b60a3000-b60be000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-22 12:04:37.390  6155  6155 W art     : b60be000-b60bf000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-22 12:04:37.390  6155  6155 W art     : b60bf000-b60c0000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-22 12:04:37.390  6155  6155 W art     : b60c0000-b60c1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b60c1000-b610d000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-22 12:04:37.390  6155  6155 W art     : b610d000-b610e000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b610e000-b610f000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-22 12:04:37.390  6155  6155 W art     : b610f000-b6110000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-22 12:04:37.390  6155  6155 W art     : b6110000-b6111000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6111000-b6115000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-22 12:04:37.390  6155  6155 W art     : b6115000-b6116000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6116000-b6117000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-22 12:04:37.390  6155  6155 W art     : b6117000-b6118000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-22 12:04:37.390  6155  6155 W art     : b6118000-b6150000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-22 12:04:37.390  6155  6155 W art     : b6150000-b6151000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-22 12:04:37.390  6155  6155 W art     : b6151000-b6152000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-22 12:04:37.390  6155  6155 W art     : b6152000-b6153000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6153000-b61f1000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-22 12:04:37.390  6155  6155 W art     : b61f1000-b61f2000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b61f2000-b6210000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-22 12:04:37.390  6155  6155 W art     : b6210000-b6211000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-22 12:04:37.390  6155  6155 W art     : b6211000-b6384000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-22 12:04:37.390  6155  6155 W art     : b6384000-b638f000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-22 12:04:37.390  6155  6155 W art     : b638f000-b6390000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-22 12:04:37.390  6155  6155 W art     : b6390000-b64a7000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-22 12:04:37.390  6155  6155 W art     : b64a7000-b64b2000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-22 12:04:37.390  6155  6155 W art     : b64b2000-b64b3000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-22 12:04:37.390  6155  6155 W art     : b64b3000-b64b7000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b64b7000-b64db000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-22 12:04:37.390  6155  6155 W art     : b64db000-b64dd000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-22 12:04:37.390  6155  6155 W art     : b64dd000-b64de000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-22 12:04:37.390  6155  6155 W art     : b64de000-b6584000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-22 12:04:37.390  6155  6155 W art     : b6584000-b6591000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-22 12:04:37.390  6155  6155 W art     : b6591000-b6592000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-22 12:04:37.390  6155  6155 W art     : b6592000-b6593000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6593000-b65e6000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-22 12:04:37.390  6155  6155 W art     : b65e6000-b65e7000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b65e7000-b65e8000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-22 12:04:37.390  6155  6155 W art     : b65e8000-b65e9000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-22 12:04:37.390  6155  6155 W art     : b65e9000-b65ee000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b65ee000-b6600000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-22 12:04:37.390  6155  6155 W art     : b6600000-b6601000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6601000-b6602000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-22 12:04:37.390  6155  6155 W art     : b6602000-b6603000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-22 12:04:37.390  6155  6155 W art     : b6603000-b660a000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-22 12:04:37.390  6155  6155 W art     : b660a000-b660b000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-22 12:04:37.390  6155  6155 W art     : b660b000-b660c000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-22 12:04:37.390  6155  6155 W art     : b660c000-b660d000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b660d000-b6610000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-22 12:04:37.390  6155  6155 W art     : b6610000-b6611000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-22 12:04:37.390  6155  6155 W art     : b6611000-b6612000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-22 12:04:37.390  6155  6155 W art     : b6612000-b6616000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-22 12:04:37.390  6155  6155 W art     : b6616000-b6617000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-22 12:04:37.390  6155  6155 W art     : b6617000-b6618000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-22 12:04:37.390  6155  6155 W art     : b6618000-b6626000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-22 12:04:37.390  6155  6155 W art     : b6626000-b6627000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6627000-b6628000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-22 12:04:37.390  6155  6155 W art     : b6628000-b6629000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-22 12:04:37.390  6155  6155 W art     : b6629000-b6632000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-22 12:04:37.390  6155  6155 W art     : b6632000-b6633000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-22 12:04:37.390  6155  6155 W art     : b6633000-b6634000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-22 12:04:37.390  6155  6155 W art     : b6634000-b669a000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-22 12:04:37.390  6155  6155 W art     : b669a000-b669b000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b669b000-b669d000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-22 12:04:37.390  6155  6155 W art     : b669d000-b66a6000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-22 12:04:37.390  6155  6155 W art     : b66a6000-b66a9000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b66a9000-b6740000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-22 12:04:37.390  6155  6155 W art     : b6740000-b6742000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-22 12:04:37.390  6155  6155 W art     : b6742000-b6743000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-22 12:04:37.390  6155  6155 W art     : b6743000-b6744000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6744000-b6a65000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-22 12:04:37.390  6155  6155 W art     : b6a65000-b6a66000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6a66000-b6a81000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-22 12:04:37.390  6155  6155 W art     : b6a81000-b6a85000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-22 12:04:37.390  6155  6155 W art     : b6a85000-b6a8a000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6a8a000-b6a92000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-22 12:04:37.390  6155  6155 W art     : b6a92000-b6a93000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-22 12:04:37.390  6155  6155 W art     : b6a93000-b6a94000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-22 12:04:37.390  6155  6155 W art     : b6a94000-b6ac2000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-22 12:04:37.390  6155  6155 W art     : b6ac2000-b6ac3000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6ac3000-b6aca000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-22 12:04:37.390  6155  6155 W art     : b6aca000-b6acb000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-22 12:04:37.390  6155  6155 W art     : b6acb000-b6b11000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-22 12:04:37.390  6155  6155 W art     : b6b11000-b6b12000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6b12000-b6b15000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-22 12:04:37.390  6155  6155 W art     : b6b15000-b6b16000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-22 12:04:37.390  6155  6155 W art     : b6b16000-b6b31000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-22 12:04:37.390  6155  6155 W art     : b6b31000-b6b35000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-22 12:04:37.390  6155  6155 W art     : b6b35000-b6b36000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-22 12:04:37.390  6155  6155 W art     : b6b36000-b6b83000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-22 12:04:37.390  6155  6155 W art     : b6b83000-b6b84000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6b84000-b6b90000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-22 12:04:37.390  6155  6155 W art     : b6b90000-b6b91000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-22 12:04:37.390  6155  6155 W art     : b6b91000-b6b9e000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-22 12:04:37.390  6155  6155 W art     : b6b9e000-b6b9f000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6b9f000-b6ba0000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-22 12:04:37.390  6155  6155 W art     : b6ba0000-b6ba1000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-22 12:04:37.390  6155  6155 W art     : b6ba1000-b6ba9000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-22 12:04:37.390  6155  6155 W art     : b6ba9000-b6baa000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6baa000-b6bab000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-22 12:04:37.390  6155  6155 W art     : b6bab000-b6bac000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-22 12:04:37.390  6155  6155 W art     : b6bac000-b6bb3000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-22 12:04:37.390  6155  6155 W art     : b6bb3000-b6bb4000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-22 12:04:37.390  6155  6155 W art     : b6bb4000-b6bb5000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-22 12:04:37.390  6155  6155 W art     : b6bb5000-b6bc9000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-22 12:04:37.390  6155  6155 W art     : b6bc9000-b6bcb000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-22 12:04:37.390  6155  6155 W art     : b6bcb000-b6bcc000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-22 12:04:37.390  6155  6155 W art     : b6bcc000-b6bf4000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-22 12:04:37.390  6155  6155 W art     : b6bf4000-b6bf6000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-22 12:04:37.390  6155  6155 W art     : b6bf6000-b6bf7000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-22 12:04:37.390  6155  6155 W art     : b6bf7000-b6bfa000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-22 12:04:37.390  6155  6155 W art     : b6bfa000-b6bfb000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-22 12:04:37.390  6155  6155 W art     : b6bfb000-b6bfc000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-22 12:04:37.390  6155  6155 W art     : b6bfc000-b6c05000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-22 12:04:37.390  6155  6155 W art     : b6c05000-b6c06000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-22 12:04:37.390  6155  6155 W art     : b6c06000-b6c07000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-22 12:04:37.390  6155  6155 W art     : b6c07000-b6c27000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-22 12:04:37.390  6155  6155 W art     : b6c27000-b6c28000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-22 12:04:37.390  6155  6155 W art     : b6c28000-b6c29000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-22 12:04:37.390  6155  6155 W art     : b6c29000-b6c9c000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-22 12:04:37.390  6155  6155 W art     : b6c9c000-b6ca0000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-22 12:04:37.390  6155  6155 W art     : b6ca0000-b6ca3000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-22 12:04:37.390  6155  6155 W art     : b6ca3000-b6cad000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6cad000-b6d35000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-22 12:04:37.390  6155  6155 W art     : b6d35000-b6d36000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6d36000-b6d3a000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-22 12:04:37.390  6155  6155 W art     : b6d3a000-b6d3b000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-22 12:04:37.390  6155  6155 W art     : b6d3b000-b6d3c000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6d3c000-b6d65000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-22 12:04:37.390  6155  6155 W art     : b6d65000-b6d66000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6d66000-b6d69000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-22 12:04:37.390  6155  6155 W art     : b6d69000-b6d6a000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-22 12:04:37.390  6155  6155 W art     : b6d6a000-b6e44000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-22 12:04:37.390  6155  6155 W art     : b6e44000-b6e4b000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-22 12:04:37.390  6155  6155 W art     : b6e4b000-b6e53000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-22 12:04:37.390  6155  6155 W art     : b6e53000-b6e54000 rw-p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6e54000-b6e55000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:37.390  6155  6155 W art     : b6e55000-b6e56000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-22 12:04:37.390  6155  6155 W art     : b6e56000-b6e57000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6e57000-b6e5a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6e5a000-b6e7f000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-22 12:04:37.390  6155  6155 W art     : b6e7f000-b6e80000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6e80000-b6e87000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-22 12:04:37.390  6155  6155 W art     : b6e87000-b6e88000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-22 12:04:37.390  6155  6155 W art     : b6e88000-b6e8f000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-22 12:04:37.390  6155  6155 W art     : b6e8f000-b6e90000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-22 12:04:37.390  6155  6155 W art     : b6e90000-b6e91000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-22 12:04:37.390  6155  6155 W art     : b6e91000-b6e92000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6e92000-b6eaa000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-22 12:04:37.390  6155  6155 W art     : b6eaa000-b6eab000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6eab000-b6eac000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-22 12:04:37.390  6155  6155 W art     : b6eac000-b6ead000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-22 12:04:37.390  6155  6155 W art     : b6ead000-b6ebb000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-22 12:04:37.390  6155  6155 W art     : b6ebb000-b6ebc000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6ebc000-b6ebd000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-22 12:04:37.390  6155  6155 W art     : b6ebd000-b6ebe000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-22 12:04:37.390  6155  6155 W art     : b6ebe000-b6ebf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:37.390  6155  6155 W art     : b6ebf000-b6ec1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6ec1000-b6ec2000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6ec2000-b6ec3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:37.390  6155  6155 W art     : b6ec3000-b6ec4000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-22 12:04:37.390  6155  6155 W art     : b6ec4000-b6ec5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:37.390  6155  6155 W art     : b6ec5000-b6ee5000 r--s 00000000 00:0b 8200       /dev/__properties__
08-22 12:04:37.390  6155  6155 W art     : b6ee5000-b6ee6000 r--p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6ee6000-b6ee7000 ---p 00000000 00:00 0 
08-22 12:04:37.390  6155  6155 W art     : b6ee7000-b6ee9000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-22 12:04:37.390  6155  6155 W art     : b6ee9000-b6eea000 r-xp 00000000 00:00 0          [sigpage]
08-22 12:04:37.390  6155  6155 W art     : b6eea000-b6f05000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-22 12:04:37.390  6155  6155 W art     : b6f05000-b6f06000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-22 12:04:37.390  6155  6155 W art     : b6f06000-b6f08000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-22 12:04:37.400  6155  6155 W art     : b6f08000-b6f0a000 rw-p 00000000 00:00 0 
08-22 12:04:37.400  6155  6155 W art     : b6f0a000-b6f0f000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-22 12:04:37.400  6155  6155 W art     : b6f0f000-b6f10000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-22 12:04:37.400  6155  6155 W art     : b6f10000-b6f11000 rw-p 00000000 00:00 0 
08-22 12:04:37.400  6155  6155 W art     : bee9f000-beec0000 rw-p 00000000 00:00 0          [stack]
08-22 12:04:37.400  6155  6155 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-22 12:04:37.450  6155  6155 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-22 12:04:37.500  6155  6155 I Radio-JNI: register_android_hardware_Radio DONE
08-22 12:04:37.510  6155  6155 E AffinityControl: AffinityControl: registerfunction enter
08-22 12:04:37.530  6155  6155 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 12:04:37.550   758  1217 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-22 12:04:37.560   758  1217 D ActivityManager: mDVFSHelper.acquire()
08-22 12:04:37.560   758  1217 V WindowManager: addAppToken: AppWindowToken{e92d522 token=Token{79df2ed ActivityRecord{f0d0d04 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-22 12:04:37.580   758  1217 I ActivityManager: Start proc 6170:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-22 12:04:37.580   758  1217 D InputDispatcher: Focused application set to: xxxx
08-22 12:04:37.580   758  1217 D InputDispatcher: Focus left window: 3503
08-22 12:04:37.580   758  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-22 12:04:37.580   758   823 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4878ba4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-22 12:04:37.580  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-22 12:04:37.590  6155  6155 D AndroidRuntime: Shutting down VM
08-22 12:04:37.590  6170  6170 I libpersona: KNOX_SDCARD checking this for 10004
08-22 12:04:37.590  6170  6170 E Zygote  : v2
08-22 12:04:37.590  6170  6170 I libpersona: KNOX_SDCARD not a persona
08-22 12:04:37.590  6170  6170 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-22 12:04:37.590  6170  6170 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:37.600  6170  6170 E Zygote  : accessInfo : 0
08-22 12:04:37.600  6170  6170 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-22 12:04:37.600   758   865 D SecWifiDisplayUtil: Metadata value : none
08-22 12:04:37.600   758   865 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{20de67a V.E...... R.....ID 0,0-0,0}
08-22 12:04:37.600   758   865 D ISSUE_DEBUG: InputChannelName : 5690288 Starting com.test.thalitest
08-22 12:04:37.610   758   865 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
08-22 12:04:37.610   758   865 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:04:37.610   758   865 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
08-22 12:04:37.610   758   865 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-22 12:04:37.620   293   293 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
08-22 12:04:37.630  6170  6170 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:04:37.630  6170  6170 D ActivityThread: Added TimaKeyStore provider
08-22 12:04:37.640   758   865 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-22 12:04:37.640   758  2184 V WindowOrientationListener: setCurrentAppOrientation :-1
08-22 12:04:37.640   758  2184 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-22 12:04:37.640   758   823 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5690288 u0 d0 Starting com.test.thalitest}
08-22 12:04:37.640  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-22 12:04:37.650   758  2184 D ActivityManager:  Launching com.test.thalitest, updated priority
08-22 12:04:37.660   758   822 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-22 12:04:37.680   293   383 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
08-22 12:04:37.690   293   365 I SurfaceFlinger: id=13 Removed VSBConnecti (7/11)
08-22 12:04:37.690   293  1502 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
08-22 12:04:37.690  3503  3503 V ActivityThread: updateVisibility : ActivityRecord{bf99869 token=android.os.BinderProxy@f98bbbb {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-22 12:04:37.690  1656  1823 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-22 12:04:37.700   758   865 V WindowStateAnimator: Finishing drawing window Window{5690288 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-22 12:04:37.710   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4
08-22 12:04:37.710   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe84b364
08-22 12:04:37.710  1656  1656 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-22 12:04:37.710   293  1503 D libEGL  : eglTerminate EGLDisplay = 0xb1f0a64c
08-22 12:04:37.710   293  1503 D libEGL  : eglTerminate EGLDisplay = 0xb1f0a64c
08-22 12:04:37.720   293  1502 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
08-22 12:04:37.720   293   365 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
08-22 12:04:37.720   293   383 I SurfaceFlinger: id=14 Removed VSBConnecti (4/9)
08-22 12:04:37.720   293  1503 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/9)
08-22 12:04:37.730  2053  2064 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-22 12:04:37.730  1656  1656 V ActivityThread: updateVisibility : ActivityRecord{cc5bdee token=android.os.BinderProxy@69d326a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 12:04:37.730  1656  1656 D Launcher: onTrimMemory. Level: 20
08-22 12:04:37.730   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4
08-22 12:04:37.730   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4
,08-22 12:04:37.820   758  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-22 12:04:37.820  6170  6170 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-22 12:04:37.830   758  3286 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-22 12:04:37.850  6170  6170 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-22 12:04:37.860  6170  6170 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-22 12:04:37.880  6170  6170 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-22 12:04:37.910  6170  6170 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-22 12:04:37.920  6170  6170 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-22 12:04:37.920   758   768 I art     : Background partial concurrent mark sweep GC freed 22599(1832KB) AllocSpace objects, 40(800KB) LOS objects, 27% free, 41MB/57MB, paused 1.631ms total 123.592ms
,08-22 12:04:37.930  6170  6170 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 4601-4604)
,08-22 12:04:37.930  6170  6170 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-22 12:04:37.950  6170  6170 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {62bdea5}
,08-22 12:04:37.950  6170  6188 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-22 12:04:37.950  6170  6170 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-22 12:04:37.950  6170  6170 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 12:04:37.960  6170  6170 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-22 12:04:37.990  6170  6189 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,08-22 12:04:37.990  6170  6170 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-22 12:04:37.990  6170  6170 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-22 12:04:37.990  6170  6170 I Adreno-EGL: Build Date: 01/28/16 Thu
08-22 12:04:37.990  6170  6170 I Adreno-EGL: Local Branch: ss
08-22 12:04:37.990  6170  6170 I Adreno-EGL: Remote Branch: 
08-22 12:04:37.990  6170  6170 I Adreno-EGL: Local Patches: 
08-22 12:04:37.990  6170  6170 I Adreno-EGL: Reconstruct Branch: 
,08-22 12:04:38.000  6170  6170 D libEGL  : eglInitialize EGLDisplay = 0xbee45dac
,08-22 12:04:38.030   758  1491 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-22 12:04:38.030   758  1491 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-22 12:04:38.110  6170  6170 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-22 12:04:38.120  6170  6170 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 12:04:38.130  6170  6170 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-22 12:04:38.130  6170  6170 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-22 12:04:38.130  6170  6170 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-22 12:04:38.140  6170  6170 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-22 12:04:38.140  6170  6170 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-22 12:04:38.230  6170  6170 D SecWifiDisplayUtil: Metadata value : none
,08-22 12:04:38.230  6170  6170 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2399a0b I.E...... R.....ID 0,0-0,0}
,08-22 12:04:38.240  6170  6213 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-22 12:04:38.240   758  2209 D ISSUE_DEBUG: InputChannelName : cbf4785 com.test.thalitest/com.test.thalitest.MainActivity
,08-22 12:04:38.240   758  1655 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-22 12:04:38.240   758  1655 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-22 12:04:38.240   758   758 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-22 12:04:38.240   758   758 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-22 12:04:38.250  6170  6170 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6170
,08-22 12:04:38.260   758  1663 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6170 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 12:04:38.270  6170  6188 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-22 12:04:38.270  6170  6170 D SecWifiDisplayUtil: Metadata value : none
,08-22 12:04:38.270   293   293 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,08-22 12:04:38.280   758  1491 D InputDispatcher: Focus entered window: 6170
,08-22 12:04:38.280   758   865 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
,08-22 12:04:38.280   758   865 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:04:38.280   758   865 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
08-22 12:04:38.280   758   865 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-22 12:04:38.280  6170  6213 D libEGL  : eglInitialize EGLDisplay = 0x9ca787c4
,08-22 12:04:38.280  6170  6213 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 12:04:38.330  6170  6170 V ActivityThread: updateVisibility : ActivityRecord{2a26394 token=android.os.BinderProxy@98c85da {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-22 12:04:38.330  6170  6170 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-22 12:04:38.330  6170  6170 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-22 12:04:38.330   758  1661 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 12:04:38.340  6170  6170 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-22 12:04:38.360  1986  3164 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-22 12:04:38.360   758  1664 V WindowStateAnimator: Finishing drawing window Window{cbf4785 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-22 12:04:38.360  6170  6170 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-22 12:04:38.360  6170  6170 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@98c85da time:175038
,08-22 12:04:38.360   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe84b364
,08-22 12:04:38.370   758   865 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-22 12:04:38.370   758   758 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-22 12:04:38.370   758   758 I KnoxTimeoutHandler: SD activityfalse
,08-22 12:04:38.370   758   865 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +572ms (total +806ms)
,08-22 12:04:38.370   758   865 D ActivityManager: mDVFSHelper.release()
08-22 12:04:38.370   758   865 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f0d0d04 u0 com.test.thalitest/.MainActivity t168} time:175049
,08-22 12:04:38.380   758   865 D ViewRootImpl: #3 mView = null
,08-22 12:04:38.380   293   383 I SurfaceFlinger: id=15 Removed uhalitest (7/9)
08-22 12:04:38.380   293  1502 I SurfaceFlinger: id=15 Removed uhalitest (-2/9)
,08-22 12:04:38.380   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4
,08-22 12:04:38.410  6170  6221 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 12:04:38.410  6170  6221 D libEGL  : eglInitialize EGLDisplay = 0x9b06c3ec
,08-22 12:04:38.450  6170  6170 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6170
,08-22 12:04:38.590  6170  6170 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 12:04:38.690  6170  6230 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1701316304
,08-22 12:04:38.700  6170  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 12:04:38.700  6170  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 12:04:38.700  6170  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 12:04:38.700  6170  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 12:04:38.700  6170  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 12:04:38.700  6170  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a82198a added. We now have 1 listener(s)
,08-22 12:04:38.700  6170  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-22 12:04:38.700  6170  6230 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-22 12:04:38.700  6170  6230 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 12:04:38.700  6170  6230 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 12:04:38.710  6170  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8238e71 added. We now have 1 listener(s)
08-22 12:04:38.710  6170  6230 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 12:04:38.710  6170  6230 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-22 12:04:38.710  6170  6230 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:04:38.710  6170  6230 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:04:38.710  6170  6230 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 12:04:38.720  6170  6230 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 12:04:38.720  6170  6230 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 12:04:38.750  6170  6170 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 12:04:38.810   758  3288 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-22 12:04:38.870   758  3286 D SSRM:n  : SIOP:: AP = 370, PST = 406, CUR = 350, LCD = 0
08-22 12:04:38.870   758  3286 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-22 12:04:38.870  2651  2651 D ContentApp:  LEVEL : -1
,08-22 12:04:38.870   758   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{614e4df u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{71e1358 6079:com.sec.android.app.videoplayer/u0a53}
,08-22 12:04:38.880  4851  4851 D SystemBroadcastReceiver: [FACE] Received broadcast 
,08-22 12:04:38.880  6079  6079 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
08-22 12:04:38.880  6079  6079 D TranscodeReceiver:  SIOP_LEVEL: -1
08-22 12:04:38.880  4851  4851 I SystemBroadcastReceiver: [FACE] onReceive broadcastcompleted  
08-22 12:04:38.880  4851  6232 I SystemBroadcastReceiver: [FACE] Calling notifyListeners. 
08-22 12:04:38.880  4851  6232 D SystemBroadcastReceiver: [FACE] Event id =  EVENT_SIOP
08-22 12:04:38.880  4851  6232 D SystemBroadcastReceiver: [FACE] getRegisteredListnersForIntent completed 
08-22 12:04:38.880  4851  6232 I PolicyManager: [FACE] onReceive action = EVENT_SIOP
,08-22 12:04:39.250  1450  1450 D Recents : onTaskStackChanged
,08-22 12:04:39.250  1450  1450 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-22 12:04:39.590  6170  6231 W jxcore-log: Initializing JXcore engine
08-22 12:04:39.590  6170  6231 W jxcore-log: JXcore engine is ready
,08-22 12:04:39.640  2114  2114 E audit   : type=1400 msg=audit(1471860279.640:281): avc:  denied  { ioctl } for  pid=6231 comm="Thread-879" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-22 12:04:39.640  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-22 12:04:39.640  2114  2114 E audit   : type=1300 msg=audit(1471860279.640:281): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a8573c8 items=0 ppid=351 ppcomm=main pid=6231 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-879" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-22 12:04:39.640  2114  2114 E audit   : type=1327 msg=audit(1471860279.640:281): proctitle="com.test.thalitest"
08-22 12:04:39.640  2114  2114 E audit   : type=1320 msg=audit(1471860279.640:281): 
08-22 12:04:39.640  2114  2114 E audit   : type=1400 msg=audit(1471860279.640:282): avc:  denied  { ioctl } for  pid=6231 comm="Thread-879" path="socket:[40879]" dev="sockfs" ino=40879 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-22 12:04:39.640  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:39.640  2114  2114 E audit   : type=1300 msg=audit(1471860279.640:282): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=2 a3=9a8573c8 items=0 ppid=351 ppcomm=main pid=6231 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-879" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-22 12:04:39.640  2114  2114 E audit   : type=1327 msg=audit(1471860279.640:282): proctitle="com.test.thalitest"
08-22 12:04:39.640  2114  2114 E audit   : type=1320 msg=audit(1471860279.640:282): 
,08-22 12:04:39.650  6170  6231 W jxcore-log: Starting JXcore engine
,08-22 12:04:39.730  6170  6231 W jxcore-log: Platform android
08-22 12:04:39.730  6170  6231 W jxcore-log: 
,08-22 12:04:39.730  6170  6231 W jxcore-log: Process ARCH arm
08-22 12:04:39.730  6170  6231 W jxcore-log: 
,08-22 12:04:39.930  6170  6231 I jxcore-log: JXcore Cordova bridge is ready!
08-22 12:04:39.930  6170  6231 I jxcore-log: 
08-22 12:04:39.930  6170  6231 W jxcore-log: JXcore engine is started
,08-22 12:04:39.930  6170  6230 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 12:04:39.940  6170  6170 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 12:04:40.610   758  1362 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-22 12:04:41.630   758  1234 V AlarmManager: Expired Alarm result :4
,08-22 12:04:41.660  6233  6233 E Zygote  : v2
,08-22 12:04:41.660  6233  6233 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:04:41.660  6233  6233 I libpersona: KNOX_SDCARD not a persona
,08-22 12:04:41.660  6233  6233 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-22 12:04:41.660  6233  6233 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-22 12:04:41.660  6233  6233 E Zygote  : accessInfo : 0
,08-22 12:04:41.660   758  1234 I ActivityManager: Start proc 6233:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-22 12:04:41.670  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-22 12:04:41.670  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
08-22 12:04:41.670  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,08-22 12:04:41.680   758  1603 D NtpTrustedTime: forceRefresh: no connectivity
,08-22 12:04:41.680   758  1603 V AlarmManager:  remove PendingIntent] PendingIntent{832adfc: PendingIntentRecord{ec70ada android broadcastIntent}}
,08-22 12:04:41.690  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-22 12:04:41.700   758   758 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{642d818 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{da2d0f1 1986:com.google.android.gms.persistent/u0a11}
,08-22 12:04:41.700  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,08-22 12:04:41.720   758  2209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 12:04:41.720   758  2209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 336, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-22 12:04:41.720   758  2209 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-22 12:04:41.720   758  2209 D BatteryService: stay LED for fully charged
,08-22 12:04:41.720   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 12:04:41.720   758  3575 V AlarmManager:  remove PendingIntent] PendingIntent{2dd8271: PendingIntentRecord{9659f0a com.google.android.gms broadcastIntent}}
,08-22 12:04:41.720   758   758 I MotionRecognitionService: Plugged
08-22 12:04:41.720   758   758 D MotionRecognitionService:   cableConnection= 1
08-22 12:04:41.720   758   758 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-22 12:04:41.720   758   758 D MotionRecognitionService: skip setTransmitPower. 
,08-22 12:04:41.720  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.730  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.730  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.730  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.730  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.730  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.730  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.740  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 12:04:41.740  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-22 12:04:41.740  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 12:04:41.740  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 12:04:41.740  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 12:04:41.740  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 12:04:41.740  6233  6233 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:04:41.740  6233  6233 D ActivityThread: Added TimaKeyStore provider
,08-22 12:04:41.770  6233  6233 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-22 12:04:41.780  6233  6233 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-22 12:04:41.780  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-22 12:04:41.810   758  1410 I ActivityManager: Killing 4851:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-22 12:04:41.820   758  1410 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-22 12:04:43.840   758  3286 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-22 12:04:44.180   758  1546 E Watchdog: !@Sync 5 [08-22 12:04:44.191]
,08-22 12:04:44.380   758  3288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-22 12:04:44.380   758   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{30aec65 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad67e5c 5532:com.samsung.android.sm.provider/1000}
,08-22 12:04:44.470   758  3288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-22 12:04:44.470   758   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{775cdeb u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad67e5c 5532:com.samsung.android.sm.provider/1000}
,08-22 12:04:47.610   758   901 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-22 12:04:47.640   758   901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-22 12:04:48.920   758  3286 D SSRM:n  : SIOP:: AP = 400, PST = 398, CUR = 350, LCD = 0
,08-22 12:04:49.540  6170  6231 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 12:04:49.540  6170  6231 I jxcore-log: 
,08-22 12:04:49.540  6170  6231 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 12:04:49.540  6170  6231 I jxcore-log: 
,08-22 12:04:49.540  6170  6231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:04:49.540  6170  6231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:04:49.540  6170  6231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:04:49.540  6170  6231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 12:04:49.540  6170  6231 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 12:04:49.540  6170  6231 I jxcore-log: 
,08-22 12:04:49.550  6170  6231 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 12:04:49.550  6170  6231 I jxcore-log: 
,08-22 12:04:50.040  6170  6231 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-22 12:04:50.040  6170  6231 I jxcore-log: Failed to execute UT.
08-22 12:04:50.040  6170  6231 I jxcore-log: 
08-22 12:04:50.040  6170  6231 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 12:04:50.040  6170  6231 I jxcore-log: 
,08-22 12:04:50.040  6170  6231 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 12:04:50.040  6170  6231 I jxcore-log: 
08-22 12:04:50.040  6170  6170 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 12:04:51.000  2114  2114 E audit   : type=1400 msg=audit(1471860291.000:283): avc:  denied  { execmod } for  pid=6296 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-22 12:04:51.000  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:51.000  2114  2114 E audit   : type=1300 msg=audit(1471860291.000:283): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbb000 a1=51000 a2=5 a3=4 items=0 ppid=3392 ppcomm=adbd pid=6296 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-22 12:04:51.000  2114  2114 E audit   : type=1327 msg=audit(1471860291.000:283): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-22 12:04:51.000  2114  2114 E audit   : type=1320 msg=audit(1471860291.000:283): 
,08-22 12:04:51.060  2114  2114 E audit   : type=1400 msg=audit(1471860291.060:284): avc:  denied  { execmod } for  pid=6296 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-22 12:04:51.060  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-22 12:04:51.060  2114  2114 E audit   : type=1300 msg=audit(1471860291.060:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7a000 a1=51000 a2=5 a3=4 items=0 ppid=3392 ppcomm=adbd pid=6296 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-22 12:04:51.060  2114  2114 E audit   : type=1327 msg=audit(1471860291.060:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-22 12:04:51.060  2114  2114 E audit   : type=1320 msg=audit(1471860291.060:284): 
,08-22 12:04:51.110  2114  2114 E audit   : type=1400 msg=audit(1471860291.110:285): avc:  denied  { execmod } for  pid=6296 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-22 12:04:51.110  2114  2114 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:51.110  2114  2114 E audit   : type=1300 msg=audit(1471860291.110:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3392 ppcomm=adbd pid=6296 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-22 12:04:51.110  2114  2114 E audit   : type=1327 msg=audit(1471860291.110:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-22 12:04:51.110  2114  2114 E audit   : type=1320 msg=audit(1471860291.110:285): 
,08-22 12:04:51.110  6296  6296 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<,
,08-22 12:04:51.120  6296  6296 D AndroidRuntime: CheckJNI is OFF,
08-22 12:04:51.120  6296  6296 D AndroidRuntime: readGMSProperty: start
08-22 12:04:51.120  6296  6296 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:04:51.120  6296  6296 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-22 12:04:51.120  6296  6296 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:04:51.120  6296  6296 D AndroidRuntime: readGMSProperty: end
08-22 12:04:51.120  6296  6296 D AndroidRuntime: addProductProperty: start
,08-22 12:04:51.130  6296  6296 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-22 12:04:51.130  6296  6296 W art     : af124000-b204a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-22 12:04:51.130  6296  6296 W art     : b204a000-b42b9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-22 12:04:51.130  6296  6296 W art     : b42b9000-b42ba000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-22 12:04:51.130  6296  6296 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-22 12:04:51.130  6296  6296 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-22 12:04:51.130  6296  6296 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-22 12:04:51.130  6296  6296 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
,08-22 12:04:51.130  6296  6296 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-22 12:04:51.130  6296  6296 W art     : b4848000-b484b000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
,08-22 12:04:51.130  6296  6296 W art     : b484b000-b484c000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-22 12:04:51.130  6296  6296 W art     : b484c000-b484d000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-22 12:04:51.130  6296  6296 W art     : b484d000-b484e000 r--p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b484e000-b486e000 r--s 00000000 00:0b 8200       /dev/__properties__
,08-22 12:04:51.130  6296  6296 W art     : b486e000-b527f000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-22 12:04:51.130  6296  6296 W art     : b527f000-b5280000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5280000-b52c9000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-22 12:04:51.130  6296  6296 W art     : b52c9000-b52ca000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-22 12:04:51.130  6296  6296 W art     : b52ca000-b52d2000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b52d2000-b52d3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b52d3000-b5308000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-22 12:04:51.130  6296  6296 W art     : b5308000-b5309000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b5309000-b530a000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-22 12:04:51.130  6296  6296 W art     : b530a000-b530b000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-22 12:04:51.130  6296  6296 W art     : b530b000-b5363000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-22 12:04:51.130  6296  6296 W art     : b5363000-b5364000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b5364000-b5365000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-22 12:04:51.130  6296  6296 W art     : b5365000-b5366000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-22 12:04:51.130  6296  6296 W art     : b5367000-b536d000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-22 12:04:51.130  6296  6296 W art     : b536d000-b536e000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-22 12:04:51.130  6296  6296 W art     : b536e000-b536f000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-22 12:04:51.130  6296  6296 W art     : b536f000-b5371000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5372000-b537c000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
,08-22 12:04:51.130  6296  6296 W art     : b537c000-b537f000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-22 12:04:51.130  6296  6296 W art     : b537f000-b5380000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-22 12:04:51.130  6296  6296 W art     : b5381000-b5398000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-22 12:04:51.130  6296  6296 W art     : b5398000-b5399000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5399000-b539a000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-22 12:04:51.130  6296  6296 W art     : b539a000-b539b000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-22 12:04:51.130  6296  6296 W art     : b539c000-b53a6000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so,
08-22 12:04:51.130  6296  6296 W art     : b53a6000-b53a7000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-22 12:04:51.130  6296  6296 W art     : b53a7000-b53a8000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-22 12:04:51.130  6296  6296 W art     : b53a8000-b53ac000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-22 12:04:51.130  6296  6296 W art     : b53ac000-b53ad000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-22 12:04:51.130  6296  6296 W art     : b53ad000-b53ae000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-22 12:04:51.130  6296  6296 W art     : b53ae000-b53c4000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-22 12:04:51.130  6296  6296 W art     : b53c4000-b53c5000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
,08-22 12:04:51.130  6296  6296 W art     : b53c5000-b53c6000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-22 12:04:51.130  6296  6296 W art     : b53c6000-b53d3000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-22 12:04:51.130  6296  6296 W art     : b53d3000-b53d4000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,08-22 12:04:51.130  6296  6296 W art     : b53d4000-b53d5000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-22 12:04:51.130  6296  6296 W art     : b53d5000-b5435000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-22 12:04:51.130  6296  6296 W art     : b5435000-b5438000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-22 12:04:51.130  6296  6296 W art     : b5438000-b543c000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b543c000-b549d000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-22 12:04:51.130  6296  6296 W art     : b549d000-b549e000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-22 12:04:51.130  6296  6296 W art     : b549e000-b54ed000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-22 12:04:51.130  6296  6296 W art     : b54ed000-b54ef000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-22 12:04:51.130  6296  6296 W art     : b54ef000-b54f0000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-22 12:04:51.130  6296  6296 W art     : b54f0000-b54f1000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b54f1000-b54f8000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-22 12:04:51.130  6296  6296 W art     : b54f8000-b54f9000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-22 12:04:51.130  6296  6296 W art     : b54f9000-b54fa000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-22 12:04:51.130  6296  6296 W art     : avc_common.so
08-22 12:04:51.130  6296  6296 W art     : b54fb000-b54fe000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-22 12:04:51.130  6296  6296 W art     : b54fe000-b54ff000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-22 12:04:51.130  6296  6296 W art     : b54ff000-b5500000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-22 12:04:51.130  6296  6296 W art     : enc_common.so
08-22 12:04:51.130  6296  6296 W art     : b5501000-b5505000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-22 12:04:51.130  6296  6296 W art     : b5505000-b5506000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b5506000-b5507000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-22 12:04:51.130  6296  6296 W art     : b5507000-b5508000 rw-p 00005000 b3:17 2510       /syste
08-22 12:04:51.130  6296  6296 W art     : m/lib/libpowermanager.so
08-22 12:04:51.130  6296  6296 W art     : b5509000-b5526000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-22 12:04:51.130  6296  6296 W art     : b5526000-b5527000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so,
08-22 12:04:51.130  6296  6296 W art     : b5527000-b5528000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-22 12:04:51.130  6296  6296 W art     : b5529000-b552e000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-22 12:04:51.130  6296  6296 W art     : b552e000-b552f000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-22 12:04:51.130  6296  6296 W art     : b552f000-b5530000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-22 12:04:51.130  6296  6296 W art     : b5531000-b5562000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-22 12:04:51.130  6296  6296 W art     : b5562000-b5565000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-22 12:04:51.130  6296  6296 W art     : b5565000-b5566000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-22 12:04:51.130  6296  6296 W art     : b5567000-b55a2000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-22 12:04:51.130  6296  6296 W art     : b55a2000-b55a3000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
,08-22 12:04:51.130  6296  6296 W art     : b55a3000-b55a4000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-22 12:04:51.130  6296  6296 W art     : b55a5000-b55ac000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-22 12:04:51.130  6296  6296 W art     : b55ac000-b55ad000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b55ad000-b55ae000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
,08-22 12:04:51.130  6296  6296 W art     : b55ae000-b55af000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-22 12:04:51.130  6296  6296 W art     : b55af000-b55b0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b55b0000-b55c7000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-22 12:04:51.130  6296  6296 W art     : b55c7000-b55c8000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b55c8000-b55cb000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-22 12:04:51.130  6296  6296 W art     : b55cb000-b55cc000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
,08-22 12:04:51.130  6296  6296 W art     : b55cc000-b55eb000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-22 12:04:51.130  6296  6296 W art     : b55eb000-b55ec000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-22 12:04:51.130  6296  6296 W art     : b55ec000-b55ed000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-22 12:04:51.130  6296  6296 W art     : b55ed000-b562b000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-22 12:04:51.130  6296  6296 W art     : b562b000-b562c000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b562c000-b562e000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
,08-22 12:04:51.130  6296  6296 W art     : b562e000-b562f000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-22 12:04:51.130  6296  6296 W art     : b5630000-b5637000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-22 12:04:51.130  6296  6296 W art     : b5637000-b5638000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-22 12:04:51.130  6296  6296 W art     : b5638000-b5639000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-22 12:04:51.130  6296  6296 W art     : b563a000-b563d000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-22 12:04:51.130  6296  6296 W art     : b563d000-b563e000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,08-22 12:04:51.130  6296  6296 W art     : b563e000-b563f000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-22 12:04:51.130  6296  6296 W art     : b563f000-b5645000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-22 12:04:51.130  6296  6296 W art     : b5645000-b5646000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5646000-b5647000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-22 12:04:51.130  6296  6296 W art     : b5647000-b5648000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-22 12:04:51.130  6296  6296 W art     : b5648000-b5651000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
,08-22 12:04:51.130  6296  6296 W art     : b5651000-b5652000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-22 12:04:51.130  6296  6296 W art     : b5652000-b5653000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-22 12:04:51.130  6296  6296 W art     : b5653000-b56e4000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-22 12:04:51.130  6296  6296 W art     : b56e4000-b56e5000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b56e5000-b56f0000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
,08-22 12:04:51.130  6296  6296 W art     : b56f0000-b56f1000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-22 12:04:51.130  6296  6296 W art     : b56f2000-b5704000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-22 12:04:51.130  6296  6296 W art     : b5704000-b5705000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-22 12:04:51.130  6296  6296 W art     : b5705000-b5706000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
,08-22 12:04:51.130  6296  6296 W art     : b5707000-b570c000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-22 12:04:51.130  6296  6296 W art     : b570c000-b570d000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-22 12:04:51.130  6296  6296 W art     : b570d000-b570e000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
,08-22 12:04:51.130  6296  6296 W art     : b570f000-b577c000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-22 12:04:51.130  6296  6296 W art     : b577c000-b577d000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b577d000-b577f000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
,08-22 12:04:51.130  6296  6296 W art     : b577f000-b5780000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-22 12:04:51.130  6296  6296 W art     : b5780000-b5781000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5781000-b5788000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-22 12:04:51.130  6296  6296 W art     : b5788000-b5789000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-22 12:04:51.130  6296  6296 W art     : b5789000-b578a000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-22 12:04:51.130  6296  6296 W art     : b578b000-b580b000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-22 12:04:51.130  6296  6296 W art     : b580b000-b580c000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b580c000-b580d000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
,08-22 12:04:51.130  6296  6296 W art     : b580d000-b580e000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-22 12:04:51.130  6296  6296 W art     : b580e000-b5825000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5825000-b585c000 r-xp 00000000 b3:17 3244       /system/vendor/l
,08-22 12:04:51.130  6296  6296 W art     : ib/libqc-opt.so
08-22 12:04:51.130  6296  6296 W art     : b585c000-b585d000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-22 12:04:51.130  6296  6296 W art     : b585d000-b585e000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-22 12:04:51.130  6296  6296 W art     : b585e000-b587a000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-22 12:04:51.130  6296  6296 W art     : b587a000-b587b000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
,08-22 12:04:51.130  6296  6296 W art     : b587b000-b587c000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-22 12:04:51.130  6296  6296 W art     : b587d000-b58de000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-22 12:04:51.130  6296  6296 W art     : b58de000-b58e0000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-22 12:04:51.130  6296  6296 W art     : b58e0000-b58e1000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-22 12:04:51.130  6296  6296 W art     : b58e2000-b5909000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
,08-22 12:04:51.130  6296  6296 W art     : b5909000-b590a000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b590a000-b590b000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-22 12:04:51.130  6296  6296 W art     : b590b000-b590c000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-22 12:04:51.130  6296  6296 W art     : b590d000-b5915000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-22 12:04:51.130  6296  6296 W art     : b5915000-b5917000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-22 12:04:51.130  6296  6296 W art     : b5917000-b5918000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-22 12:04:51.130  6296  6296 W art     : b5919000-b591c000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
,08-22 12:04:51.130  6296  6296 W art     : b591c000-b591d000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-22 12:04:51.130  6296  6296 W art     : b591d000-b591e000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-22 12:04:51.130  6296  6296 W art     : b591e000-b5922000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
,08-22 12:04:51.130  6296  6296 W art     : b5922000-b5923000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5923000-b5924000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-22 12:04:51.130  6296  6296 W art     : b5924000-b5925000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
,08-22 12:04:51.130  6296  6296 W art     : b5925000-b5935000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-22 12:04:51.130  6296  6296 W art     : b5935000-b5936000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-22 12:04:51.130  6296  6296 W art     : b5936000-b5937000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
,08-22 12:04:51.130  6296  6296 W art     : b5937000-b597d000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b597d000-b5986000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-22 12:04:51.130  6296  6296 W art     : b5986000-b5987000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
,08-22 12:04:51.130  6296  6296 W art     : b5987000-b5988000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-22 12:04:51.130  6296  6296 W art     : b5989000-b598e000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-22 12:04:51.130  6296  6296 W art     : b598e000-b598f000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-22 12:04:51.130  6296  6296 W art     : b598f000-b5990000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-22 12:04:51.130  6296  6296 W art     : b5990000-b5993000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-22 12:04:51.130  6296  6296 W art     : b5993000-b5994000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5994000-b5995000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-22 12:04:51.130  6296  6296 W art     : b5995000-b5996000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-22 12:04:51.130  6296  6296 W art     : b5997000-b59af000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-22 12:04:51.130  6296  6296 W art     : b59af000-b59b0000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b59b0000-b59b1000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-22 12:04:51.130  6296  6296 W art     : b59b1000-b59b2000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-22 12:04:51.130  6296  6296 W art     : b59b3000-b5b4d000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-22 12:04:51.130  6296  6296 W art     : b5b4d000-b5b4e000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5b4e000-b5b5b000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-22 12:04:51.130  6296  6296 W art     : b5b5b000-b5b5c000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-22 12:04:51.130  6296  6296 W art     : b5b5c000-b5b60000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-22 12:04:51.130  6296  6296 W art     : b5b60000-b5b61000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b5b61000-b5b62000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-22 12:04:51.130  6296  6296 W art     : b5b62000-b5b63000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-22 12:04:51.130  6296  6296 W art     : b5b63000-b5b76000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-22 12:04:51.130  6296  6296 W art     : b5b76000-b5b77000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-22 12:04:51.130  6296  6296 W art     : b5b77000-b5b78000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-22 12:04:51.130  6296  6296 W art     : b5b78000-b5b79000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-22 12:04:51.130  6296  6296 W art     : b5b79000-b5bc4000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-22 12:04:51.130  6296  6296 W art     : b5bc4000-b5bc5000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
,08-22 12:04:51.130  6296  6296 W art     : b5bc5000-b5bc6000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-22 12:04:51.130  6296  6296 W art     : b5bc6000-b5bc8000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5bc9000-b5bda000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-22 12:04:51.130  6296  6296 W art     : b5bda000-b5bdb000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5bdb000-b5bdc000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-22 12:04:51.130  6296  6296 W art     : b5bdc000-b5bdd000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-22 12:04:51.130  6296  6296 W art     : b5bde000-b5be8000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-22 12:04:51.130  6296  6296 W art     : b5be8000-b5bea000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
,08-22 12:04:51.130  6296  6296 W art     : b5bea000-b5beb000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-22 12:04:51.130  6296  6296 W art     : b5beb000-b5c04000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-22 12:04:51.130  6296  6296 W art     : b5c04000-b5c05000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-22 12:04:51.130  6296  6296 W art     : b5c05000-b5c08000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-22 12:04:51.130  6296  6296 W art     : b5c08000-b5c0c000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5c0c000-b5c80000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-22 12:04:51.130  6296  6296 W art     : b5c80000-b5c81000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b5c81000-b5c84000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-22 12:04:51.130  6296  6296 W art     : b5c84000-b5c85000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-22 12:04:51.130  6296  6296 W art     : b5c85000-b5c86000 r--p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5c86000-b5c89000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-22 12:04:51.130  6296  6296 W art     : b5c89000-b5c8a000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-22 12:04:51.130  6296  6296 W art     : b5c8a000-b5c8b000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-22 12:04:51.130  6296  6296 W art     : b5c8b000-b5c8c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5c8c000-b5c91000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-22 12:04:51.130  6296  6296 W art     : b5c91000-b5c92000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-22 12:04:51.130  6296  6296 W art     : b5c92000-b5c93000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-22 12:04:51.130  6296  6296 W art     : b5c93000-b5c94000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5c94000-b5c97000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-22 12:04:51.130  6296  6296 W art     : b5c97000-b5c98000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-22 12:04:51.130  6296  6296 W art     : b5c98000-b5c99000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-22 12:04:51.130  6296  6296 W art     : b5c99000-b5c9a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5c9a000-b5c9e000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
,08-22 12:04:51.130  6296  6296 W art     : b5c9e000-b5c9f000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-22 12:04:51.130  6296  6296 W art     : b5c9f000-b5ca0000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-22 12:04:51.130  6296  6296 W art     : b5ca0000-b5ca1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:51.130  6296  6296 W art     : b5ca1000-b5ca5000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-22 12:04:51.130  6296  6296 W art     : b5ca5000-b5ca6000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-22 12:04:51.130  6296  6296 W art     : b5ca6000-b5ca7000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-22 12:04:51.130  6296  6296 W art     : b5ca7000-b5ca8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5ca8000-b5cb6000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
,08-22 12:04:51.130  6296  6296 W art     : b5cb6000-b5cb7000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b5cb7000-b5cb8000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-22 12:04:51.130  6296  6296 W art     : b5cb8000-b5cb9000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-22 12:04:51.130  6296  6296 W art     : b5cb9000-b5cc3000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-22 12:04:51.130  6296  6296 W art     : b5cc3000-b5cc6000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-22 12:04:51.130  6296  6296 W art     : b5cc6000-b5cc7000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-22 12:04:51.130  6296  6296 W art     : b5cc7000-b5cc8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5cc8000-b5cd2000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-22 12:04:51.130  6296  6296 W art     : b5cd2000-b5cd5000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
,08-22 12:04:51.130  6296  6296 W art     : b5cd5000-b5cd6000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-22 12:04:51.130  6296  6296 W art     : b5cd6000-b5cda000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-22 12:04:51.130  6296  6296 W art     : b5cda000-b5cdb000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-22 12:04:51.130  6296  6296 W art     : b5cdb000-b5cdc000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-22 12:04:51.130  6296  6296 W art     : b5cdc000-b5cdd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b5cdd000-b5cea000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
,08-22 12:04:51.130  6296  6296 W art     : b5cea000-b5cec000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-22 12:04:51.130  6296  6296 W art     : b5cec000-b5ced000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-22 12:04:51.130  6296  6296 W art     : b5ced000-b60ff000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-22 12:04:51.130  6296  6296 W art     : b60ff000-b6100000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6100000-b6109000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-22 12:04:51.130  6296  6296 W art     : b6109000-b610d000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
,08-22 12:04:51.130  6296  6296 W art     : b610d000-b610e000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b610e000-b6115000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-22 12:04:51.130  6296  6296 W art     : b6115000-b6116000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-22 12:04:51.130  6296  6296 W art     : b6116000-b6117000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-22 12:04:51.130  6296  6296 W art     : b6117000-b6118000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6118000-b6133000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-22 12:04:51.130  6296  6296 W art     : b6133000-b6134000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-22 12:04:51.130  6296  6296 W art     : b6134000-b6135000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
,08-22 12:04:51.130  6296  6296 W art     : b6135000-b6136000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6136000-b6182000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-22 12:04:51.130  6296  6296 W art     : b6182000-b6183000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6183000-b6184000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-22 12:04:51.130  6296  6296 W art     : b6184000-b6185000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-22 12:04:51.130  6296  6296 W art     : b6185000-b6186000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6186000-b618a000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-22 12:04:51.130  6296  6296 W art     : b618a000-b618b000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b618b000-b618c000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-22 12:04:51.130  6296  6296 W art     : b618c000-b618d000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-22 12:04:51.130  6296  6296 W art     : b618d000-b61c5000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-22 12:04:51.130  6296  6296 W art     : b61c5000-b61c6000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-22 12:04:51.130  6296  6296 W art     : b61c6000-b61c7000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-22 12:04:51.130  6296  6296 W art     : b61c7000-b61c8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b61c8000-b6266000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
,08-22 12:04:51.130  6296  6296 W art     : b6266000-b6267000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6267000-b6285000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-22 12:04:51.130  6296  6296 W art     : b6285000-b6286000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-22 12:04:51.130  6296  6296 W art     : b6286000-b63f9000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-22 12:04:51.130  6296  6296 W art     : b63f9000-b6404000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-22 12:04:51.130  6296  6296 W art     : b6404000-b6405000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
,08-22 12:04:51.130  6296  6296 W art     : b6405000-b651c000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-22 12:04:51.130  6296  6296 W art     : b651c000-b6527000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-22 12:04:51.130  6296  6296 W art     : b6527000-b6528000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-22 12:04:51.130  6296  6296 W art     : b6528000-b652c000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b652c000-b6550000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-22 12:04:51.130  6296  6296 W art     : b6550000-b6552000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-22 12:04:51.130  6296  6296 W art     : b6552000-b6553000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-22 12:04:51.130  6296  6296 W art     : b6553000-b65f9000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-22 12:04:51.130  6296  6296 W art     : b65f9000-b6606000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
,08-22 12:04:51.130  6296  6296 W art     : b6606000-b6607000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-22 12:04:51.130  6296  6296 W art     : b6607000-b6608000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6608000-b665b000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-22 12:04:51.130  6296  6296 W art     : b665b000-b665c000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b665c000-b665d000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-22 12:04:51.130  6296  6296 W art     : b665d000-b665e000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-22 12:04:51.130  6296  6296 W art     : b665e000-b6663000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6663000-b6675000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
,08-22 12:04:51.130  6296  6296 W art     : b6675000-b6676000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6676000-b6677000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-22 12:04:51.130  6296  6296 W art     : b6677000-b6678000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-22 12:04:51.130  6296  6296 W art     : b6678000-b667f000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-22 12:04:51.130  6296  6296 W art     : b667f000-b6680000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-22 12:04:51.130  6296  6296 W art     : b6680000-b6681000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-22 12:04:51.130  6296  6296 W art     : b6681000-b6682000 rw-p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b6682000-b6685000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-22 12:04:51.130  6296  6296 W art     : b6685000-b6686000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-22 12:04:51.130  6296  6296 W art     : b6686000-b6687000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-22 12:04:51.130  6296  6296 W art     : b6687000-b668b000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-22 12:04:51.130  6296  6296 W art     : b668b000-b668c000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-22 12:04:51.130  6296  6296 W art     : b668c000-b668d000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-22 12:04:51.130  6296  6296 W art     : b668d000-b669b000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-22 12:04:51.130  6296  6296 W art     : b669b000-b669c000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b669c000-b669d000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-22 12:04:51.130  6296  6296 W art     : b669d000-b669e000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-22 12:04:51.130  6296  6296 W art     : b669e000-b66a7000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-22 12:04:51.130  6296  6296 W art     : b66a7000-b66a8000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-22 12:04:51.130  6296  6296 W art     : b66a8000-b66a9000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-22 12:04:51.130  6296  6296 W art     : b66a9000-b670f000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-22 12:04:51.130  6296  6296 W art     : b670f000-b6710000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6710000-b6712000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
,08-22 12:04:51.130  6296  6296 W art     : b6712000-b671b000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-22 12:04:51.130  6296  6296 W art     : b671b000-b671e000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b671e000-b67b5000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-22 12:04:51.130  6296  6296 W art     : b67b5000-b67b7000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-22 12:04:51.130  6296  6296 W art     : b67b7000-b67b8000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-22 12:04:51.130  6296  6296 W art     : b67b8000-b67b9000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b67b9000-b6ada000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-22 12:04:51.130  6296  6296 W art     : b6ada000-b6adb000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b6adb000-b6af6000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-22 12:04:51.130  6296  6296 W art     : b6af6000-b6afa000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-22 12:04:51.130  6296  6296 W art     : b6afa000-b6aff000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6aff000-b6b07000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-22 12:04:51.130  6296  6296 W art     : b6b07000-b6b08000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-22 12:04:51.130  6296  6296 W art     : b6b08000-b6b09000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-22 12:04:51.130  6296  6296 W art     : b6b09000-b6b37000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-22 12:04:51.130  6296  6296 W art     : b6b37000-b6b38000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b6b38000-b6b3f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-22 12:04:51.130  6296  6296 W art     : b6b3f000-b6b40000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-22 12:04:51.130  6296  6296 W art     : b6b40000-b6b86000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-22 12:04:51.130  6296  6296 W art     : b6b86000-b6b87000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6b87000-b6b8a000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-22 12:04:51.130  6296  6296 W art     : b6b8a000-b6b8b000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-22 12:04:51.130  6296  6296 W art     : b6b8b000-b6ba6000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-22 12:04:51.130  6296  6296 W art     : b6ba6000-b6baa000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
,08-22 12:04:51.130  6296  6296 W art     : b6baa000-b6bab000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-22 12:04:51.130  6296  6296 W art     : b6bab000-b6bf8000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-22 12:04:51.130  6296  6296 W art     : b6bf8000-b6bf9000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6bf9000-b6c05000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-22 12:04:51.130  6296  6296 W art     : b6c05000-b6c06000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-22 12:04:51.130  6296  6296 W art     : b6c06000-b6c13000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-22 12:04:51.130  6296  6296 W art     : b6c13000-b6c14000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6c14000-b6c15000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
,08-22 12:04:51.130  6296  6296 W art     : b6c15000-b6c16000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-22 12:04:51.130  6296  6296 W art     : b6c16000-b6c1e000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-22 12:04:51.130  6296  6296 W art     : b6c1e000-b6c1f000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6c1f000-b6c20000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-22 12:04:51.130  6296  6296 W art     : b6c20000-b6c21000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-22 12:04:51.130  6296  6296 W art     : b6c21000-b6c28000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-22 12:04:51.130  6296  6296 W art     : b6c28000-b6c29000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
,08-22 12:04:51.130  6296  6296 W art     : b6c29000-b6c2a000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-22 12:04:51.130  6296  6296 W art     : b6c2a000-b6c3e000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-22 12:04:51.130  6296  6296 W art     : b6c3e000-b6c40000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-22 12:04:51.130  6296  6296 W art     : b6c40000-b6c41000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-22 12:04:51.130  6296  6296 W art     : b6c41000-b6c69000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-22 12:04:51.130  6296  6296 W art     : b6c69000-b6c6b000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-22 12:04:51.130  6296  6296 W art     : b6c6b000-b6c6c000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-22 12:04:51.130  6296  6296 W art     : b6c6c000-b6c6f000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
,08-22 12:04:51.130  6296  6296 W art     : b6c6f000-b6c70000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-22 12:04:51.130  6296  6296 W art     : b6c70000-b6c71000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-22 12:04:51.130  6296  6296 W art     : b6c71000-b6c7a000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-22 12:04:51.130  6296  6296 W art     : b6c7a000-b6c7b000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-22 12:04:51.130  6296  6296 W art     : b6c7b000-b6c7c000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-22 12:04:51.130  6296  6296 W art     : b6c7c000-b6c9c000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
,08-22 12:04:51.130  6296  6296 W art     : b6c9c000-b6c9d000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-22 12:04:51.130  6296  6296 W art     : b6c9d000-b6c9e000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-22 12:04:51.130  6296  6296 W art     : b6c9e000-b6d11000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-22 12:04:51.130  6296  6296 W art     : b6d11000-b6d15000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-22 12:04:51.130  6296  6296 W art     : b6d15000-b6d18000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-22 12:04:51.130  6296  6296 W art     : b6d18000-b6d22000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6d22000-b6daa000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-22 12:04:51.130  6296  6296 W art     : b6daa000-b6dab000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6dab000-b6daf000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
,08-22 12:04:51.130  6296  6296 W art     : b6daf000-b6db0000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-22 12:04:51.130  6296  6296 W art     : b6db0000-b6db1000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6db1000-b6dda000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-22 12:04:51.130  6296  6296 W art     : b6dda000-b6ddb000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6ddb000-b6dde000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-22 12:04:51.130  6296  6296 W art     : b6dde000-b6ddf000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
,08-22 12:04:51.130  6296  6296 W art     : b6ddf000-b6eb9000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-22 12:04:51.130  6296  6296 W art     : b6eb9000-b6ec0000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-22 12:04:51.130  6296  6296 W art     : b6ec0000-b6ec8000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-22 12:04:51.130  6296  6296 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6ec9000-b6eca000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:51.130  6296  6296 W art     : b6eca000-b6ecb000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-22 12:04:51.130  6296  6296 W art     : b6ecb000-b6ecc000 rw-p 00000000 00:00 0          [anon:linker_alloc]
,08-22 12:04:51.130  6296  6296 W art     : b6ecc000-b6ecf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6ecf000-b6ef4000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-22 12:04:51.130  6296  6296 W art     : b6ef4000-b6ef5000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6ef5000-b6efc000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
,08-22 12:04:51.130  6296  6296 W art     : b6efc000-b6efd000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-22 12:04:51.130  6296  6296 W art     : b6efd000-b6f04000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-22 12:04:51.130  6296  6296 W art     : b6f04000-b6f05000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-22 12:04:51.130  6296  6296 W art     : b6f05000-b6f06000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-22 12:04:51.130  6296  6296 W art     : b6f06000-b6f07000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6f07000-b6f1f000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-22 12:04:51.130  6296  6296 W art     : b6f1f000-b6f20000 ---p 00000000 00:00 0 
,08-22 12:04:51.130  6296  6296 W art     : b6f20000-b6f21000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-22 12:04:51.130  6296  6296 W art     : b6f21000-b6f22000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-22 12:04:51.130  6296  6296 W art     : b6f22000-b6f30000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-22 12:04:51.130  6296  6296 W art     : b6f30000-b6f31000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6f31000-b6f32000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-22 12:04:51.130  6296  6296 W art     : b6f32000-b6f33000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-22 12:04:51.130  6296  6296 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-22 12:04:51.130  6296  6296 W art     : b6f34000-b6f36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6f36000-b6f37000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6f37000-b6f38000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-22 12:04:51.130  6296  6296 W art     : b6f38000-b6f39000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-22 12:04:51.130  6296  6296 W art     : b6f39000-b6f3a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-22 12:04:51.130  6296  6296 W art     : b6f3a000-b6f5a000 r--s 00000000 00:0b 8200       /dev/__properties__
08-22 12:04:51.130  6296  6296 W art     : b6f5a000-b6f5b000 r--p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6f5b000-b6f5c000 ---p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6f5c000-b6f5e000 rw-p 00000000 00:00 0          [anon:thread signal stack]
,08-22 12:04:51.130  6296  6296 W art     : b6f5e000-b6f5f000 r-xp 00000000 00:00 0          [sigpage]
08-22 12:04:51.130  6296  6296 W art     : b6f5f000-b6f7a000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-22 12:04:51.130  6296  6296 W art     : b6f7a000-b6f7b000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-22 12:04:51.130  6296  6296 W art     : b6f7b000-b6f7d000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-22 12:04:51.130  6296  6296 W art     : b6f7d000-b6f7f000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : b6f7f000-b6f84000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-22 12:04:51.130  6296  6296 W art     : b6f84000-b6f85000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-22 12:04:51.130  6296  6296 W art     : b6f85000-b6f86000 rw-p 00000000 00:00 0 
08-22 12:04:51.130  6296  6296 W art     : bed67000-bed88000 rw-p 00000000 00:00 0          [stack]
,08-22 12:04:51.130  6296  6296 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-22 12:04:51.190  6296  6296 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat,
,08-22 12:04:51.240  6296  6296 I Radio-JNI: register_android_hardware_Radio DONE
,08-22 12:04:51.250  6296  6296 E AffinityControl: AffinityControl: registerfunction enter
,08-22 12:04:51.270  6296  6296 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 12:04:51.280   758  2209 D PackageManager: START PACKAGE DELETE: observer{96659937}
08-22 12:04:51.280   758  2209 D PackageManager: pkg{<packageName>}
08-22 12:04:51.280   758  2209 D PackageManager: user{0}
08-22 12:04:51.280   758  2209 D PackageManager: caller{2000}
08-22 12:04:51.280   758  2209 D PackageManager: flags{2}
08-22 12:04:51.280   758  2209 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-22 12:04:51.280   758  2209 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-22 12:04:51.280   758  2209 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-22 12:04:51.280   758  2209 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 12:04:51.280   758  2209 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-22 12:04:51.280   758   901 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 12:04:51.280   758   901 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-22 12:04:51.280   758   901 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-22 12:04:51.280   758   901 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 12:04:51.280   758   901 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-22 12:04:51.280   758   901 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-22 12:04:51.280   758   901 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-22 12:04:51.280   758   901 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-22 12:04:51.280   758   822 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-22 12:04:51.280   758   822 I ActivityManager: Killing 6170:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-22 12:04:51.290   758   822 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-22 12:04:51.290   758   822 D ActivityManager: mDVFSHelper.acquire()
,08-22 12:04:51.290   758   865 D SecWifiDisplayUtil: Metadata value : none
,08-22 12:04:51.290   758   865 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a8c0f63 V.E...... R.....ID 0,0-0,0}
08-22 12:04:51.290   758   865 W WindowManager: view not successfully added to wm, removing view
,08-22 12:04:51.290   758   865 D ViewRootImpl: #3 mView = null
08-22 12:04:51.300   758   901 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-22 12:04:51.300   758   901 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-22 12:04:51.310  6305  6305 E Zygote  : v2
08-22 12:04:51.310  6305  6305 I libpersona: KNOX_SDCARD checking this for 10004
08-22 12:04:51.310  6305  6305 I libpersona: KNOX_SDCARD not a persona
,08-22 12:04:51.310  6305  6305 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-22 12:04:51.310  6305  6305 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-22 12:04:51.310   758   822 I ActivityManager: Start proc 6305:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-22 12:04:51.310  6305  6305 E Zygote  : accessInfo : 0
08-22 12:04:51.310  6305  6305 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-22 12:04:51.310   758   822 I ActivityManager:   Force finishing activity ActivityRecord{f0d0d04 u0 com.test.thalitest/.MainActivity t168}
,08-22 12:04:51.340  6305  6305 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:04:51.340  6305  6305 D ActivityThread: Added TimaKeyStore provider
,08-22 12:04:51.340  1656  1656 D Launcher: onRestart, Launcher: 10534945
,08-22 12:04:51.350   758   822 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-22 12:04:51.350   758  2209 D GraphicsStats: Buffer count: 4
,08-22 12:04:51.350   758  1410 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b35f419)
,08-22 12:04:51.350   758  1329 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 12:04:51.360   758  1664 I WindowState: WIN DEATH: Window{cbf4785 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 12:04:51.360   293  1502 I SurfaceFlinger: id=16 Removed NainActivit (6/8)
,08-22 12:04:51.360   758  1329 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 12:04:51.360   293  1503 I SurfaceFlinger: id=16 Removed NainActivit (-2/8)
,08-22 12:04:51.360   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4
,08-22 12:04:51.360   758  1664 D InputDispatcher: Focus left window: 6170
,08-22 12:04:51.360   758  1329 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 12:04:51.370   293   293 I SurfaceFlinger: id=17 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-22 12:04:51.370   758   901 D AASAinstall: there is not AASApackages.xml file
,08-22 12:04:51.650   758   901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-22 12:04:51.670   758  3303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 12:04:51.740   758   901 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-22 12:04:51.740   758  1661 I ActivityManager: Killing 4868:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-22 12:04:51.750   328   328 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-22 12:04:51.750   758   901 I art     : Starting a blocking GC Explicit
,08-22 12:04:51.750  1656  1656 D Launcher: onStart, Launcher: 10534945
,08-22 12:04:51.760  1656  1656 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-22 12:04:51.760  6305  6305 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-22 12:04:51.760  1656  1656 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-22 12:04:51.760  1656  1656 D Launcher.HomeView: onStart
,08-22 12:04:51.770  1656  1656 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-22 12:04:51.770   758   822 D InputDispatcher: Focus entered window: 3503
08-22 12:04:51.770   758   822 D InputDispatcher: Focused application released
,08-22 12:04:51.770  1656  1656 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-22 12:04:51.770  2053  2063 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-22 12:04:51.770  6305  6305 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-22 12:04:51.770  1656  1656 V ActivityThread: updateVisibility : ActivityRecord{cc5bdee token=android.os.BinderProxy@69d326a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-22 12:04:51.770  6305  6305 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
08-22 12:04:51.770  6305  6305 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-22 12:04:51.770  6305  6305 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-22 12:04:51.780   758   865 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:758 uid:1000
08-22 12:04:51.780   758   823 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2fdfe4b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-22 12:04:51.780  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-22 12:04:51.780   758   865 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:04:51.780   758   865 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:758 uid:1000
,08-22 12:04:51.780   758   865 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-22 12:04:51.780   758  3286 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-22 12:04:51.780   758  2073 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-22 12:04:51.780   758  2073 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-22 12:04:51.780   758   758 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-22 12:04:51.780   293   293 I SurfaceFlinger: id=18 createSurf (1080x1920),1 flag=4, Mauncher
,08-22 12:04:51.790   758  3575 V WindowOrientationListener: setCurrentAppOrientation :1
08-22 12:04:51.790   758  3575 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-22 12:04:51.790   758  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 12:04:51.790   758  1410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 336, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-22 12:04:51.790   758  1410 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-22 12:04:51.800   758  1410 D BatteryService: stay LED for fully charged
,08-22 12:04:51.800   758   758 I KnoxTimeoutHandler: Shared devices show user statefalse
08-22 12:04:51.800   758   758 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-22 12:04:51.800   758   758 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 12:04:51.800   758   758 I MotionRecognitionService: Plugged
08-22 12:04:51.800   758   758 D MotionRecognitionService:   cableConnection= 1
08-22 12:04:51.800   758   758 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-22 12:04:51.800   758   758 D MotionRecognitionService: skip setTransmitPower. 
,08-22 12:04:51.800  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 12:04:51.800  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-22 12:04:51.800  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 12:04:51.810  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 12:04:51.810  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 12:04:51.810   758  1217 V WindowStateAnimator: Finishing drawing window Window{2fdfe4b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-22 12:04:51.820   293   293 I SurfaceFlinger: id=19 createSurf (1194x288),1 flag=4, VSBConnecti
,08-22 12:04:51.820   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe84b364
,08-22 12:04:51.830   758   865 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-22 12:04:51.830   758   865 D ActivityManager: mDVFSHelper.release()
08-22 12:04:51.830   758   865 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{69e6a0d u0 com.samsung.android.MtpApplication/.USBConnection t167} time:188501
,08-22 12:04:51.830   758   758 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-22 12:04:51.830   758   758 I KnoxTimeoutHandler: SD activityfalse
,08-22 12:04:51.830  3503  3503 V ActivityThread: updateVisibility : ActivityRecord{bf99869 token=android.os.BinderProxy@f98bbbb {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-22 12:04:51.840  6305  6305 D AndroidRuntime: Shutting down VM
,08-22 12:04:51.840  6305  6305 E AndroidRuntime: FATAL EXCEPTION: main
08-22 12:04:51.840  6305  6305 E AndroidRuntime: Process: com.test.thalitest, PID: 6305
08-22 12:04:51.840  6305  6305 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-22 12:04:51.840  6305  6305 E AndroidRuntime: 	... 9 more
,08-22 12:04:51.840   758   772 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-22 12:04:51.850  6305  6305 I Process : Sending signal. PID: 6305 SIG: 9
,08-22 12:04:51.850  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 12:04:51.860   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe84b364
,08-22 12:04:51.860   758  1217 V WindowStateAnimator: Finishing drawing window Window{a788141 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-22 12:04:51.870  3503  3503 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f98bbbb time:188540
,08-22 12:04:51.870  6341  6341 E Zygote  : v2
08-22 12:04:51.870  6341  6341 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:04:51.870  6341  6341 I libpersona: KNOX_SDCARD not a persona
,08-22 12:04:51.870  6341  6341 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-22 12:04:51.870  6341  6341 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-22 12:04:51.870  6341  6341 E Zygote  : accessInfo : 0
,08-22 12:04:51.880   758   822 I ActivityManager: Start proc 6341:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-22 12:04:51.880   758   865 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-22 12:04:51.880   758   758 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-22 12:04:51.880   758   758 I KnoxTimeoutHandler: SD activityfalse
,08-22 12:04:51.890   758  1664 I ActivityManager: Process com.test.thalitest (pid 6305)(adj 9) has died(107,749)
,08-22 12:04:51.890   758  1664 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-22 12:04:51.890   758  1664 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-22 12:04:51.890   758  1664 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-22 12:04:51.900   758   822 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
08-22 12:04:51.900   758   822 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-22 12:04:51.910   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe84b364
,08-22 12:04:51.910   758  2175 V WindowStateAnimator: Finishing drawing window Window{4878ba4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-22 12:04:51.910  1656  1656 D Launcher.HomeView: onStop
,08-22 12:04:51.910  6341  6341 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:04:51.910  6341  6341 D ActivityThread: Added TimaKeyStore provider
,08-22 12:04:51.920   758  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aaebcde u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba63ebf 6341:com.samsung.android.sm/1000}
,08-22 12:04:51.920   758   865 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-22 12:04:51.920   758   865 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{73cfc63 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t165} time:188596
08-22 12:04:51.920   758   758 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-22 12:04:51.920   758   758 I KnoxTimeoutHandler: SD activityfalse
,08-22 12:04:51.930  6341  6341 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-22 12:04:51.960  6341  6341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-22 12:04:51.970   758  1661 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aaebcde u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{219c0c 3878:com.google.android.gms/u0a11}
,08-22 12:04:51.990   758   901 I art     : Explicit concurrent mark sweep GC freed 92689(4MB) AllocSpace objects, 20(400KB) LOS objects, 27% free, 41MB/57MB, paused 1.544ms total 241.341ms
,08-22 12:04:52.020   758   901 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-22 12:04:52.020   758   901 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-22 12:04:52.020   758   901 D AASAinstall: there is not AASApackages.xml file
,08-22 12:04:52.020   758   901 D PackageManager: result of delete: 1{96659937}
,08-22 12:04:52.030   758   901 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 12:04:52.030   758   901 D PackageManager: userId{-1}
08-22 12:04:52.030   758   901 D PackageManager: andCode{true}
08-22 12:04:52.030  6296  6296 I art     : System.exit called, status: 0
08-22 12:04:52.030  6296  6296 I AndroidRuntime: VM exiting with result code 0.
08-22 12:04:52.040   758   901 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-22 12:04:52.070  5343  6357 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-22 12:04:52.080  5343  6357 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-22 12:04:52.080  5343  6357 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-22 12:04:52.080   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.090  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-22 12:04:52.090  1380  1380 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-22 12:04:52.090   758   758 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.090   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.090   758   865 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.100   758   865 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.100   758  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 12:04:52.110  1910  1910 E SamsungIME: mOCRHelper is null
,08-22 12:04:52.110   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.110   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.110   758   822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bff0e24 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8a690a 4045:com.samsung.klmsagent/u0a18}
08-22 12:04:52.110  1986  2338 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.120   758   758 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.130   758   758 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.130   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.130  1641  1641 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-22 12:04:52.140  4045  4045 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Mon Aug 22 12:04:52 GMT+02:00 2016
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.140   758  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/168_task.xml
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.140   758   758 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.140   758  1362 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/168_task_thumbnail.png
,08-22 12:04:52.150   758   809 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.160   758   758 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.170   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.170  4045  4045 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-22 12:04:52.170  3068  3097 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-22 12:04:52.170   758  1664 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bff0e24 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d3487b5 758:system/1000}
,08-22 12:04:52.170  3068  3097 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-22 12:04:52.180  3068  3097 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-22 12:04:52.180  3068  3097 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-22 12:04:52.180   758  1217 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-22 12:04:52.180  4045  4045 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-22 12:04:52.180  4045  4045 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-22 12:04:52.180   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.180   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.180  4045  4045 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 12:04:52.180  4045  6364 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-22 12:04:52.180  4045  6364 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-22 12:04:52.180  4045  6364 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-22 12:04:52.190   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.190  4045  6364 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-22 12:04:52.190  4045  6364 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-22 12:04:52.190   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.190  4045  6364 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-22 12:04:52.190   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.190   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.190  4045  6364 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 12:04:52.200  4045  6364 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 12:04:52.200   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.200  1631  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
08-22 12:04:52.200   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.200  1631  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-22 12:04:52.200  1631  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-22 12:04:52.200  1631  6361 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-22 12:04:52.200  1631  6361 D RegisteredComponentCache: Collect Tech packages for Knox
08-22 12:04:52.200   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.200   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.200   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210   758  1319 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-22 12:04:52.210   758  1319 V NetworkStats: performPollLocked(flags=0x3)
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.210   758  1320 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-22 12:04:52.210   758  1320 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210  4045  6364 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-22 12:04:52.210   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.210  4045  6364 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-22 12:04:52.220   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.220   758   758 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-22 12:04:52.220   758  1319 V NetworkStats: performPollLocked() took 14ms
,08-22 12:04:52.220   758  1319 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x74328044 in tid 1319 (NetworkStats)
,08-22 12:04:52.220  4045  6364 W System.err: mkdir failed: EROFS (Read-only file system) : /data/user/0/com.samsung.klmsagent/databases
,08-22 12:04:52.220  4045  6364 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (2)
08-22 12:04:52.220  4045  6364 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131072) and mode_t (0) due to error (2)
08-22 12:04:52.220  4045  6364 E SQLiteLog: (14) cannot open file at line 31517 of [2ef4f3a5b1]
,08-22 12:04:52.220  2114  2114 E audit_log: File locking failed. error= Bad file descriptor
,08-22 12:04:52.220  4045  6364 E SQLiteLog: (14) os_unix.c:31517: (2) open(/data/user/0/com.samsung.klmsagent/databases/klms.db) - 
08-22 12:04:52.230  2114  2114 E audit_log: File locking failed. error= Bad file descriptor
08-22 12:04:52.230  4045  6364 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x710d107e in tid 6364 (IntentService[K)
,08-22 12:04:52.230  4045  6364 F libc    : Unable to open connection to debuggerd: Connection refused
08-22 12:04:52.230  2114  2114 E audit_log: File locking failed. error= Bad file descriptor
,08-22 12:04:52.270   351   351 I Zygote  : Process 4045 exited due to signal (7)
,08-22 12:04:52.300   326   326 E installd: eof
08-22 12:04:52.300   326   326 E installd: failed to read size
08-22 12:04:52.300   326   326 I installd: closing connection
,08-22 12:04:52.300   292   292 I ServiceManager: service 'sec_analytics' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'telecom' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'statusbar' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'clipboard' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'clipboardEx' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'network_management' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'jobscheduler' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'textservices' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'network_score' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'netstats' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'netpolicy' died
08-22 12:04:52.300   323   323 W AudioFlinger: power manager service died !!!
08-22 12:04:52.300   292   292 I ServiceManager: service 'wifip2p' died
08-22 12:04:52.300   323   323 W AudioFlinger: power manager service died !!!
08-22 12:04:52.300   292   292 I ServiceManager: service 'wifi' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'wifihs20' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'wifiscanner' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'rttmanager' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'ethernet' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'connectivity' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'sb_service' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'servicediscovery' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'updatelock' died
08-22 12:04:52.300  2720  2733 W Sensors : sensorservice died [0xa98aab80]
08-22 12:04:52.300   292   292 I ServiceManager: service 'notification' died
08-22 12:04:52.300  1986  4950 W Sensors : sensorservice died [0xace70700]
08-22 12:04:52.300   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'location' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'country_detector' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'sec_location' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'search' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'execute' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'dropbox' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'wallpaper' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'audio' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'DockObserver' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'midi' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'usb' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'serial' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'kiesusb' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'backup' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'appwidget' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'voiceinteraction' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'diskstats' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'mDNIe' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'AAS' died,
08-22 12:04:52.300   292   292 I ServiceManager: service 'MSCS' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'spengestureservice' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'quickconnect' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'samplingprofiler' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'commontime_management' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'dreams' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'graphicsstats' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'print' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'restrictions' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'media_session' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'media_router' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'trust' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'fingerprint' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'launcherapps' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'voip' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'media_projection' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'lpnet' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'imms' died
08-22 12:04:52.310  2114  2114 E audit_log: File locking failed. error= Bad file descriptor
08-22 12:04:52.300   292   292 I ServiceManager: service 'persona_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'package' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'activity' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'user' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'procstats' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'meminfo' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'gfxinfo' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'dbinfo' died,
,08-22 12:04:52.300   292   292 I ServiceManager: service 'cpuinfo' died
08-22 12:04:52.310  2114  2114 E audit_log: File locking failed. error= Bad file descriptor
08-22 12:04:52.300   292   292 I ServiceManager: service 'permission' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'processinfo' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'sensorservice' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'mdm.remotedesktop' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'battery' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'usagestats' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'webviewupdate' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'scheduling_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'telephony.registry' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'persona' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'context_aware' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'scontext' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'barbeam' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'multiwindow_facade' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'window' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'input' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'bluetooth_manager' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'rcp' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'input_method' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'accessibility' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'cover' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'mount' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'lock_settings' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'deviceidle' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'device_policy' died
08-22 12:04:52.300  1380  1839 W Sensors : sensorservice died [0xa98abe00]
08-22 12:04:52.300   292   292 I ServiceManager: service 'harmony_eas_service' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'sdp' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'sdp_log' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'dlp' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'log_manager_service' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'SEAMService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'media.camera.proxy' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'account' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'content' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'DirEncryptService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'LSManager' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'ReactiveService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'DeviceRootKeyService' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'EngineeringModeService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'SatsService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'sedenial' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'vibrator' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'tw_toolbox' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'tima' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'iccc' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'cepproxyks' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'emailksproxy' died,
,08-22 12:04:52.300   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'consumer_ir' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'alarm' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'edmnativehelper' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'enterprise_license_policy' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'application_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'wifi_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'remoteinjection' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'edm_proxy' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'mum_container_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'otp_service' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'enterprise_policy' died
,08-22 12:04:52.300   292   292 I ServiceManager: service 'uimode' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'batterystats' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'appops' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'power' died
08-22 12:04:52.300   292   292 I ServiceManager: service 'display' died
08-22 12:04:52.310  1641  1641 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-22 12:04:52.310  1641  2323 E WifiManager: Channel connection lost
08-22 12:04:52.310  1631  1631 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2c18203 in tid 1631 (com.android.nfc)
08-22 12:04:52.310  1631  1631 F libc    : Unable to open connection to debuggerd: Connection refused
08-22 12:04:52.310  1902  1924 W Sensors : sensorservice died [0xb3a73dc0]
08-22 12:04:52.310  2165  2202 W Sensors : sensorservice died [0xad73ec80]
08-22 12:04:52.310  3068  3097 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e5c0cf7 in tid 3097 (AccountChangeLi)
,08-22 12:04:52.310   293   365 I SurfaceFlinger: id=5 Removed TtatusBar (9/10)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=19 Removed VSBConnecti (5/9)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=17 Removed VSBConnecti (6/8)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=5 Removed TtatusBar (-2/8)
08-22 12:04:52.310  3068  3097 F libc    : Unable to open connection to debuggerd: Connection refused
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=8 Removed EimLayer(Di (5/7)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=6 Removed JmageWallpa (3/6)
,08-22 12:04:52.310   293   365 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/6)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=9 Removed EimLayer(An (2/5)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=18 Removed Mauncher (2/4)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=12 Removed DolorFade (3/3)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=12 Removed DolorFade (-2/3)
08-22 12:04:52.310  1986  2332 E WifiManager: Channel connection lost
,08-22 12:04:52.310   293   365 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/3)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=18 Removed Mauncher (-2/3)
08-22 12:04:52.310   293   365 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/3)
08-22 12:04:52.310  1656  1669 W Sensors : sensorservice died [0xad6ed100]
08-22 12:04:52.320  1380  1673 E WifiManager: Channel connection lost
08-22 12:04:52.320  1824  1956 E WifiManager: Channel connection lost
,08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
,08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
,08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
,08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
,08-22 12:04:52.320   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b38c
,08-22 12:04:52.320   293   383 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
,08-22 12:04:52.330   293  1502 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-22 12:04:52.330   293   383 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
,08-22 12:04:52.330   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4
,08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=8 Removed EimLayer(Di (-2/3)
08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
,08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
08-22 12:04:52.330   293  1503 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-22 12:04:52.330   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-22 12:04:52.330   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-22 12:04:52.330  3878  6354 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x732ffe68 in tid 6354 (IntentService[D)
08-22 12:04:52.340  2720  4176 E WifiManager: Channel connection lost
,08-22 12:04:52.340  3878  6354 F libc    : Unable to open connection to debuggerd: Connection refused
,08-22 12:04:52.340  2114  2114 E audit_log: File locking failed. error= Bad file descriptor
,08-22 12:04:52.360   292   292 I ServiceManager: service 'nfccontroller' died
08-22 12:04:52.360   292   292 I ServiceManager: service 'secontroller' died
08-22 12:04:52.360   292   292 I ServiceManager: service 'nfc' died
,08-22 12:04:52.390   351   351 I Zygote  : Process 3068 exited due to signal (7)
,08-22 12:04:52.390   351   351 I Zygote  : Process 1631 exited due to signal (7)
,08-22 12:04:52.400   351   351 I Zygote  : Process 3878 exited due to signal (7)
,08-22 12:04:52.500   291   291 I lowmemorykiller: ActivityManager disconnected
08-22 12:04:52.500   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-22 12:04:52.580   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-22 12:04:52.580   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-22 12:04:52.840   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-22 12:04:52.860   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-22 12:04:52.860   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe84b3a4

```
