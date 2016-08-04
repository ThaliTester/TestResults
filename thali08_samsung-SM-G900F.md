#### Test 79426650eeb77ae_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
08-05 01:32:32.004   305  1180 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-05 01:32:32.004   305  1180 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-05 01:32:32.004   305  1180 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,--------- beginning of main
08-05 01:32:32.974  2439  2439 E audit   : type=1400 msg=audit(1470353552.974:285): avc:  denied  { execmod } for  pid=7058 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 01:32:32.974  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:32.974  2439  2439 E audit   : type=1300 msg=audit(1470353552.974:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f60000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7058 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 01:32:32.974  2439  2439 E audit   : type=1327 msg=audit(1470353552.974:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-05 01:32:32.974  2439  2439 E audit   : type=1320 msg=audit(1470353552.974:285): 
08-05 01:32:33.024  2439  2439 E audit   : type=1400 msg=audit(1470353553.024:286): avc:  denied  { execmod } for  pid=7058 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 01:32:33.034  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:33.034  2439  2439 E audit   : type=1300 msg=audit(1470353553.024:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f20000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7058 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 01:32:33.034  2439  2439 E audit   : type=1327 msg=audit(1470353553.024:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-05 01:32:33.034  2439  2439 E audit   : type=1320 msg=audit(1470353553.024:286): 
08-05 01:32:33.074  2439  2439 E audit   : type=1400 msg=audit(1470353553.074:287): avc:  denied  { execmod } for  pid=7058 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 01:32:33.074  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:33.074  7058  7058 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 01:32:33.074  2439  2439 E audit   : type=1300 msg=audit(1470353553.074:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f20000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7058 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 01:32:33.074  2439  2439 E audit   : type=1327 msg=audit(1470353553.074:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-05 01:32:33.074  2439  2439 E audit   : type=1320 msg=audit(1470353553.074:287): 
08-05 01:32:33.074  7058  7058 D AndroidRuntime: CheckJNI is OFF
08-05 01:32:33.074  7058  7058 D AndroidRuntime: readGMSProperty: start
08-05 01:32:33.074  7058  7058 D AndroidRuntime: readGMSProperty: already setted!!
08-05 01:32:33.074  7058  7058 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 01:32:33.074  7058  7058 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 01:32:33.074  7058  7058 D AndroidRuntime: readGMSProperty: end
08-05 01:32:33.074  7058  7058 D AndroidRuntime: addProductProperty: start
08-05 01:32:33.084  7058  7058 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-05 01:32:33.084  7058  7058 W art     : af0ce000-b1ff4000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-05 01:32:33.084  7058  7058 W art     : b1ff4000-b4263000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-05 01:32:33.084  7058  7058 W art     : b4263000-b4264000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-05 01:32:33.084  7058  7058 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-05 01:32:33.084  7058  7058 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-05 01:32:33.084  7058  7058 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-05 01:32:33.084  7058  7058 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-05 01:32:33.084  7058  7058 W art     : b47c5000-b47ee000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-05 01:32:33.084  7058  7058 W art     : b47ee000-b47f1000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-05 01:32:33.084  7058  7058 W art     : b47f1000-b47f2000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-05 01:32:33.084  7058  7058 W art     : b47f2000-b47f3000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-05 01:32:33.084  7058  7058 W art     : b47f3000-b47f4000 r--p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b47f4000-b4814000 r--s 00000000 00:0b 6712       /dev/__properties__
08-05 01:32:33.084  7058  7058 W art     : b4814000-b5225000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-05 01:32:33.084  7058  7058 W art     : b5225000-b5226000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b5226000-b526f000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-05 01:32:33.084  7058  7058 W art     : b526f000-b5270000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-05 01:32:33.084  7058  7058 W art     : b5270000-b5278000 rw-p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b5278000-b5279000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.084  7058  7058 W art     : b5279000-b52ae000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-05 01:32:33.084  7058  7058 W art     : b52ae000-b52af000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b52af000-b52b0000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-05 01:32:33.084  7058  7058 W art     : b52b0000-b52b1000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-05 01:32:33.084  7058  7058 W art     : b52b1000-b5309000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-05 01:32:33.084  7058  7058 W art     : b5309000-b530a000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b530a000-b530b000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-05 01:32:33.084  7058  7058 W art     : b530b000-b530c000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-05 01:32:33.084  7058  7058 W art     : b530d000-b5313000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 01:32:33.084  7058  7058 W art     : b5313000-b5314000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 01:32:33.084  7058  7058 W art     : b5314000-b5315000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 01:32:33.084  7058  7058 W art     : b5315000-b5317000 rw-p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b5318000-b5322000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 01:32:33.084  7058  7058 W art     : b5322000-b5325000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 01:32:33.084  7058  7058 W art     : b5325000-b5326000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 01:32:33.084  7058  7058 W art     : b5327000-b533e000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 01:32:33.084  7058  7058 W art     : b533e000-b533f000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b533f000-b5340000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 01:32:33.084  7058  7058 W art     : b5340000-b5341000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 01:32:33.084  7058  7058 W art     : b5342000-b534c000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-05 01:32:33.084  7058  7058 W art     : b534c000-b534d000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-05 01:32:33.084  7058  7058 W art     : b534d000-b534e000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-05 01:32:33.084  7058  7058 W art     : b534e000-b5352000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 01:32:33.084  7058  7058 W art     : b5352000-b5353000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 01:32:33.084  7058  7058 W art     : b5353000-b5354000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 01:32:33.084  7058  7058 W art     : b5354000-b536a000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-05 01:32:33.084  7058  7058 W art     : b536a000-b536b000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-05 01:32:33.084  7058  7058 W art     : b536b000-b536c000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-05 01:32:33.084  7058  7058 W art     : b536c000-b5379000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-05 01:32:33.084  7058  7058 W art     : b5379000-b537a000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-05 01:32:33.084  7058  7058 W art     : b537a000-b537b000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-05 01:32:33.084  7058  7058 W art     : b537b000-b53db000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-05 01:32:33.084  7058  7058 W art     : b53db000-b53de000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-05 01:32:33.084  7058  7058 W art     : b53de000-b53e2000 rw-p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b53e2000-b5443000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-05 01:32:33.084  7058  7058 W art     : b5443000-b5444000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-05 01:32:33.084  7058  7058 W art     : b5444000-b5493000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-05 01:32:33.084  7058  7058 W art     : b5493000-b5495000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-05 01:32:33.084  7058  7058 W art     : b5495000-b5496000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-05 01:32:33.084  7058  7058 W art     : b5496000-b5497000 rw-p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b5497000-b549e000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 01:32:33.084  7058  7058 W art     : b549e000-b549f000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 01:32:33.084  7058  7058 W art     : b549f000-b54a0000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 01:32:33.084  7058  7058 W art     : b54a1000-b54a4000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 01:32:33.084  7058  7058 W art     : b54a4000-b54a5000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 01:32:33.084  7058  7058 W art     : b54a5000-b54a6000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 01:32:33.084  7058  7058 W art     : b54a7000-b54ab000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-05 01:32:33.084  7058  7058 W art     : b54ab000-b54ac000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b54ac000-b54ad000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-05 01:32:33.084  7058  7058 W art     : b54ad000-b54ae000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-05 01:32:33.084  7058  7058 W art     : b54af000-b54cc000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 01:32:33.084  7058  7058 W art     : b54cc000-b54cd000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 01:32:33.084  7058  7058 W art     : b54cd000-b54ce000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 01:32:33.084  7058  7058 W art     : b54cf000-b54d4000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 01:32:33.084  7058  7058 W art     : b54d4000-b54d5000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 01:32:33.084  7058  7058 W art     : b54d5000-b54d6000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 01:32:33.084  7058  7058 W art     : b54d7000-b5508000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 01:32:33.084  7058  7058 W art     : b5508000-b550b000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 01:32:33.084  7058  7058 W art     : b550b000-b550c000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 01:32:33.084  7058  7058 W art     : b550d000-b5548000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-05 01:32:33.084  7058  7058 W art     : b5548000-b5549000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-05 01:32:33.084  7058  7058 W art     : b5549000-b554a000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-05 01:32:33.084  7058  7058 W art     : b554b000-b5552000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-05 01:32:33.084  7058  7058 W art     : b5552000-b5553000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b5553000-b5554000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-05 01:32:33.084  7058  7058 W art     : b5554000-b5555000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-05 01:32:33.084  7058  7058 W art     : b5555000-b5556000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.084  7058  7058 W art     : b5556000-b556d000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-05 01:32:33.084  7058  7058 W art     : b556d000-b556e000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b556e000-b5571000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-05 01:32:33.084  7058  7058 W art     : b5571000-b5572000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-05 01:32:33.084  7058  7058 W art     : b5572000-b5591000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-05 01:32:33.084  7058  7058 W art     : b5591000-b5592000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-05 01:32:33.084  7058  7058 W art     : b5592000-b5593000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-05 01:32:33.084  7058  7058 W art     : b5593000-b55d1000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-05 01:32:33.084  7058  7058 W art     : b55d1000-b55d2000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b55d2000-b55d4000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-05 01:32:33.084  7058  7058 W art     : b55d4000-b55d5000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-05 01:32:33.084  7058  7058 W art     : b55d6000-b55dd000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 01:32:33.084  7058  7058 W art     : b55dd000-b55de000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 01:32:33.084  7058  7058 W art     : b55de000-b55df000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 01:32:33.084  7058  7058 W art     : b55e0000-b55e3000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 01:32:33.084  7058  7058 W art     : b55e3000-b55e4000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 01:32:33.084  7058  7058 W art     : b55e4000-b55e5000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 01:32:33.084  7058  7058 W art     : b55e5000-b55eb000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 01:32:33.084  7058  7058 W art     : b55eb000-b55ec000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b55ec000-b55ed000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 01:32:33.084  7058  7058 W art     : b55ed000-b55ee000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 01:32:33.084  7058  7058 W art     : b55ee000-b55f7000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-05 01:32:33.084  7058  7058 W art     : b55f7000-b55f8000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-05 01:32:33.084  7058  7058 W art     : b55f8000-b55f9000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-05 01:32:33.084  7058  7058 W art     : b55f9000-b568a000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 01:32:33.084  7058  7058 W art     : b568a000-b568b000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b568b000-b5696000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 01:32:33.084  7058  7058 W art     : b5696000-b5697000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 01:32:33.084  7058  7058 W art     : b5698000-b56aa000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-05 01:32:33.084  7058  7058 W art     : b56aa000-b56ab000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-05 01:32:33.084  7058  7058 W art     : b56ab000-b56ac000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-05 01:32:33.084  7058  7058 W art     : b56ad000-b56b2000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-05 01:32:33.084  7058  7058 W art     : b56b2000-b56b3000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-05 01:32:33.084  7058  7058 W art     : b56b3000-b56b4000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-05 01:32:33.084  7058  7058 W art     : b56b5000-b5722000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-05 01:32:33.084  7058  7058 W art     : b5722000-b5723000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b5723000-b5725000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-05 01:32:33.084  7058  7058 W art     : b5725000-b5726000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-05 01:32:33.084  7058  7058 W art     : b5726000-b5727000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.084  7058  7058 W art     : b5727000-b572e000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 01:32:33.084  7058  7058 W art     : b572e000-b572f000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 01:32:33.084  7058  7058 W art     : b572f000-b5730000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 01:32:33.084  7058  7058 W art     : b5731000-b57b1000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 01:32:33.084  7058  7058 W art     : b57b1000-b57b2000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b57b2000-b57b3000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 01:32:33.084  7058  7058 W art     : b57b3000-b57b4000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 01:32:33.084  7058  7058 W art     : b57b4000-b57cb000 rw-p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b57cb000-b5802000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-05 01:32:33.084  7058  7058 W art     : ib/libqc-opt.so
08-05 01:32:33.084  7058  7058 W art     : b5802000-b5803000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 01:32:33.084  7058  7058 W art     : b5803000-b5804000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 01:32:33.084  7058  7058 W art     : b5804000-b5820000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 01:32:33.084  7058  7058 W art     : b5820000-b5821000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 01:32:33.084  7058  7058 W art     : b5821000-b5822000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 01:32:33.084  7058  7058 W art     : b5823000-b5884000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-05 01:32:33.084  7058  7058 W art     : b5884000-b5886000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-05 01:32:33.084  7058  7058 W art     : b5886000-b5887000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-05 01:32:33.084  7058  7058 W art     : b5888000-b58af000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-05 01:32:33.084  7058  7058 W art     : b58af000-b58b0000 ---p 00000000 00:00 0 
08-05 01:32:33.084  7058  7058 W art     : b58b0000-b58b1000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-05 01:32:33.084  7058  7058 W art     : b58b1000-b58b2000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-05 01:32:33.084  7058  7058 W art     : b58b3000-b58bb000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 01:32:33.084  7058  7058 W art     : b58bb000-b58bd000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 01:32:33.084  7058  7058 W art     : b58bd000-b58be000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 01:32:33.094  7058  7058 W art     : b58bf000-b58c2000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-05 01:32:33.094  7058  7058 W art     : b58c2000-b58c3000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-05 01:32:33.094  7058  7058 W art     : b58c3000-b58c4000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-05 01:32:33.094  7058  7058 W art     : b58c4000-b58c8000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-05 01:32:33.094  7058  7058 W art     : b58c8000-b58c9000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b58c9000-b58ca000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-05 01:32:33.094  7058  7058 W art     : b58ca000-b58cb000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-05 01:32:33.094  7058  7058 W art     : b58cb000-b58db000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-05 01:32:33.094  7058  7058 W art     : b58db000-b58dc000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-05 01:32:33.094  7058  7058 W art     : b58dc000-b58dd000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-05 01:32:33.094  7058  7058 W art     : b58dd000-b5923000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5923000-b592c000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-05 01:32:33.094  7058  7058 W art     : b592c000-b592d000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-05 01:32:33.094  7058  7058 W art     : b592d000-b592e000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-05 01:32:33.094  7058  7058 W art     : b592f000-b5934000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-05 01:32:33.094  7058  7058 W art     : b5934000-b5935000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-05 01:32:33.094  7058  7058 W art     : b5935000-b5936000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-05 01:32:33.094  7058  7058 W art     : b5936000-b5939000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 01:32:33.094  7058  7058 W art     : b5939000-b593a000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b593a000-b593b000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 01:32:33.094  7058  7058 W art     : b593b000-b593c000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 01:32:33.094  7058  7058 W art     : b593d000-b5955000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 01:32:33.094  7058  7058 W art     : b5955000-b5956000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5956000-b5957000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 01:32:33.094  7058  7058 W art     : b5957000-b5958000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 01:32:33.094  7058  7058 W art     : b5958000-b5959000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:33.094  7058  7058 W art     : b5959000-b5af3000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-05 01:32:33.094  7058  7058 W art     : b5af3000-b5af4000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5af4000-b5b01000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-05 01:32:33.094  7058  7058 W art     : b5b01000-b5b02000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-05 01:32:33.094  7058  7058 W art     : b5b02000-b5b06000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-05 01:32:33.094  7058  7058 W art     : b5b06000-b5b07000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5b07000-b5b08000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-05 01:32:33.094  7058  7058 W art     : b5b08000-b5b09000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-05 01:32:33.094  7058  7058 W art     : b5b09000-b5b1c000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-05 01:32:33.094  7058  7058 W art     : b5b1c000-b5b1d000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-05 01:32:33.094  7058  7058 W art     : b5b1d000-b5b1e000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-05 01:32:33.094  7058  7058 W art     : b5b1f000-b5b6a000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-05 01:32:33.094  7058  7058 W art     : b5b6a000-b5b6b000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-05 01:32:33.094  7058  7058 W art     : b5b6b000-b5b6c000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-05 01:32:33.094  7058  7058 W art     : b5b6c000-b5b6e000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5b6f000-b5b80000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 01:32:33.094  7058  7058 W art     : b5b80000-b5b81000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5b81000-b5b82000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 01:32:33.094  7058  7058 W art     : b5b82000-b5b83000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 01:32:33.094  7058  7058 W art     : b5b83000-b5b84000 r--p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5b84000-b5b8e000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-05 01:32:33.094  7058  7058 W art     : b5b8e000-b5b90000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-05 01:32:33.094  7058  7058 W art     : b5b90000-b5b91000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-05 01:32:33.094  7058  7058 W art     : b5b91000-b5baa000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-05 01:32:33.094  7058  7058 W art     : b5baa000-b5bab000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-05 01:32:33.094  7058  7058 W art     : b5bab000-b5bae000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-05 01:32:33.094  7058  7058 W art     : b5bae000-b5bb2000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5bb2000-b5c26000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-05 01:32:33.094  7058  7058 W art     : b5c26000-b5c27000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5c27000-b5c2a000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-05 01:32:33.094  7058  7058 W art     : b5c2a000-b5c2b000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-05 01:32:33.094  7058  7058 W art     : b5c2b000-b5c2c000 r--p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5c2c000-b5c2f000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-05 01:32:33.094  7058  7058 W art     : b5c2f000-b5c30000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-05 01:32:33.094  7058  7058 W art     : b5c30000-b5c31000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-05 01:32:33.094  7058  7058 W art     : b5c31000-b5c32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b5c32000-b5c37000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 01:32:33.094  7058  7058 W art     : b5c37000-b5c38000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 01:32:33.094  7058  7058 W art     : b5c38000-b5c39000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 01:32:33.094  7058  7058 W art     : b5c39000-b5c3a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b5c3a000-b5c3d000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 01:32:33.094  7058  7058 W art     : b5c3d000-b5c3e000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 01:32:33.094  7058  7058 W art     : b5c3e000-b5c3f000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 01:32:33.094  7058  7058 W art     : b5c3f000-b5c40000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b5c40000-b5c44000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-05 01:32:33.094  7058  7058 W art     : b5c44000-b5c45000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-05 01:32:33.094  7058  7058 W art     : b5c45000-b5c46000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-05 01:32:33.094  7058  7058 W art     : b5c46000-b5c47000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:33.094  7058  7058 W art     : b5c47000-b5c4b000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 01:32:33.094  7058  7058 W art     : b5c4b000-b5c4c000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 01:32:33.094  7058  7058 W art     : b5c4c000-b5c4d000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 01:32:33.094  7058  7058 W art     : b5c4d000-b5c4e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b5c4e000-b5c5c000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-05 01:32:33.094  7058  7058 W art     : b5c5c000-b5c5d000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b5c5d000-b5c5e000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-05 01:32:33.094  7058  7058 W art     : b5c5e000-b5c5f000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-05 01:32:33.094  7058  7058 W art     : b5c5f000-b5c69000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 01:32:33.094  7058  7058 W art     : b5c69000-b5c6c000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 01:32:33.094  7058  7058 W art     : b5c6c000-b5c6d000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 01:32:33.094  7058  7058 W art     : b5c6d000-b5c6e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b5c6e000-b5c78000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-05 01:32:33.094  7058  7058 W art     : b5c78000-b5c7b000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-05 01:32:33.094  7058  7058 W art     : b5c7b000-b5c7c000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-05 01:32:33.094  7058  7058 W art     : b5c7c000-b5c80000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-05 01:32:33.094  7058  7058 W art     : b5c80000-b5c81000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-05 01:32:33.094  7058  7058 W art     : b5c81000-b5c82000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-05 01:32:33.094  7058  7058 W art     : b5c82000-b5c83000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b5c83000-b5c90000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-05 01:32:33.094  7058  7058 W art     : b5c90000-b5c92000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-05 01:32:33.094  7058  7058 W art     : b5c92000-b5c93000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-05 01:32:33.094  7058  7058 W art     : b5c93000-b60a5000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-05 01:32:33.094  7058  7058 W art     : b60a5000-b60a6000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b60a6000-b60af000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-05 01:32:33.094  7058  7058 W art     : b60af000-b60b3000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-05 01:32:33.094  7058  7058 W art     : b60b3000-b60b4000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b60b4000-b60bb000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-05 01:32:33.094  7058  7058 W art     : b60bb000-b60bc000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-05 01:32:33.094  7058  7058 W art     : b60bc000-b60bd000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-05 01:32:33.094  7058  7058 W art     : b60bd000-b60be000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b60be000-b60d9000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-05 01:32:33.094  7058  7058 W art     : b60d9000-b60da000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-05 01:32:33.094  7058  7058 W art     : b60da000-b60db000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-05 01:32:33.094  7058  7058 W art     : b60db000-b60dc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b60dc000-b6128000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 01:32:33.094  7058  7058 W art     : b6128000-b6129000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6129000-b612a000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 01:32:33.094  7058  7058 W art     : b612a000-b612b000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 01:32:33.094  7058  7058 W art     : b612b000-b612c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b612c000-b6130000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-05 01:32:33.094  7058  7058 W art     : b6130000-b6131000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6131000-b6132000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-05 01:32:33.094  7058  7058 W art     : b6132000-b6133000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-05 01:32:33.094  7058  7058 W art     : b6133000-b616b000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-05 01:32:33.094  7058  7058 W art     : b616b000-b616c000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-05 01:32:33.094  7058  7058 W art     : b616c000-b616d000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-05 01:32:33.094  7058  7058 W art     : b616d000-b616e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b616e000-b620c000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-05 01:32:33.094  7058  7058 W art     : b620c000-b620d000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b620d000-b622b000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-05 01:32:33.094  7058  7058 W art     : b622b000-b622c000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-05 01:32:33.094  7058  7058 W art     : b622c000-b639f000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-05 01:32:33.094  7058  7058 W art     : b639f000-b63aa000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-05 01:32:33.094  7058  7058 W art     : b63aa000-b63ab000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-05 01:32:33.094  7058  7058 W art     : b63ab000-b64c2000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-05 01:32:33.094  7058  7058 W art     : b64c2000-b64cd000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-05 01:32:33.094  7058  7058 W art     : b64cd000-b64ce000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-05 01:32:33.094  7058  7058 W art     : b64ce000-b64d2000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b64d2000-b64f6000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-05 01:32:33.094  7058  7058 W art     : b64f6000-b64f8000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-05 01:32:33.094  7058  7058 W art     : b64f8000-b64f9000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-05 01:32:33.094  7058  7058 W art     : b64f9000-b659f000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-05 01:32:33.094  7058  7058 W art     : b659f000-b65ac000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-05 01:32:33.094  7058  7058 W art     : b65ac000-b65ad000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-05 01:32:33.094  7058  7058 W art     : b65ad000-b65ae000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b65ae000-b6601000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-05 01:32:33.094  7058  7058 W art     : b6601000-b6602000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6602000-b6603000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-05 01:32:33.094  7058  7058 W art     : b6603000-b6604000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-05 01:32:33.094  7058  7058 W art     : b6604000-b6609000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6609000-b661b000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-05 01:32:33.094  7058  7058 W art     : b661b000-b661c000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b661c000-b661d000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-05 01:32:33.094  7058  7058 W art     : b661d000-b661e000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-05 01:32:33.094  7058  7058 W art     : b661e000-b6625000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 01:32:33.094  7058  7058 W art     : b6625000-b6626000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 01:32:33.094  7058  7058 W art     : b6626000-b6627000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 01:32:33.094  7058  7058 W art     : b6627000-b6628000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6628000-b662b000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-05 01:32:33.094  7058  7058 W art     : b662b000-b662c000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-05 01:32:33.094  7058  7058 W art     : b662c000-b662d000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-05 01:32:33.094  7058  7058 W art     : b662d000-b6631000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-05 01:32:33.094  7058  7058 W art     : b6631000-b6632000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-05 01:32:33.094  7058  7058 W art     : b6632000-b6633000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-05 01:32:33.094  7058  7058 W art     : b6633000-b6641000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-05 01:32:33.094  7058  7058 W art     : b6641000-b6642000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6642000-b6643000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-05 01:32:33.094  7058  7058 W art     : b6643000-b6644000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-05 01:32:33.094  7058  7058 W art     : b6644000-b664d000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 01:32:33.094  7058  7058 W art     : b664d000-b664e000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 01:32:33.094  7058  7058 W art     : b664e000-b664f000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 01:32:33.094  7058  7058 W art     : b664f000-b66b5000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-05 01:32:33.094  7058  7058 W art     : b66b5000-b66b6000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b66b6000-b66b8000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-05 01:32:33.094  7058  7058 W art     : b66b8000-b66c1000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-05 01:32:33.094  7058  7058 W art     : b66c1000-b66c4000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b66c4000-b675b000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-05 01:32:33.094  7058  7058 W art     : b675b000-b675d000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-05 01:32:33.094  7058  7058 W art     : b675d000-b675e000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-05 01:32:33.094  7058  7058 W art     : b675e000-b675f000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b675f000-b6a80000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-05 01:32:33.094  7058  7058 W art     : b6a80000-b6a81000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6a81000-b6a9c000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-05 01:32:33.094  7058  7058 W art     : b6a9c000-b6aa0000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-05 01:32:33.094  7058  7058 W art     : b6aa0000-b6aa5000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6aa5000-b6aad000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 01:32:33.094  7058  7058 W art     : b6aad000-b6aae000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 01:32:33.094  7058  7058 W art     : b6aae000-b6aaf000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 01:32:33.094  7058  7058 W art     : b6aaf000-b6add000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-05 01:32:33.094  7058  7058 W art     : b6add000-b6ade000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6ade000-b6ae5000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-05 01:32:33.094  7058  7058 W art     : b6ae5000-b6ae6000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-05 01:32:33.094  7058  7058 W art     : b6ae6000-b6b2c000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-05 01:32:33.094  7058  7058 W art     : b6b2c000-b6b2d000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6b2d000-b6b30000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-05 01:32:33.094  7058  7058 W art     : b6b30000-b6b31000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-05 01:32:33.094  7058  7058 W art     : b6b31000-b6b4c000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-05 01:32:33.094  7058  7058 W art     : b6b4c000-b6b50000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-05 01:32:33.094  7058  7058 W art     : b6b50000-b6b51000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-05 01:32:33.094  7058  7058 W art     : b6b51000-b6b9e000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-05 01:32:33.094  7058  7058 W art     : b6b9e000-b6b9f000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6b9f000-b6bab000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-05 01:32:33.094  7058  7058 W art     : b6bab000-b6bac000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-05 01:32:33.094  7058  7058 W art     : b6bac000-b6bb9000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-05 01:32:33.094  7058  7058 W art     : b6bb9000-b6bba000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6bba000-b6bbb000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-05 01:32:33.094  7058  7058 W art     : b6bbb000-b6bbc000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-05 01:32:33.094  7058  7058 W art     : b6bbc000-b6bc4000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-05 01:32:33.094  7058  7058 W art     : b6bc4000-b6bc5000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6bc5000-b6bc6000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-05 01:32:33.094  7058  7058 W art     : b6bc6000-b6bc7000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-05 01:32:33.094  7058  7058 W art     : b6bc7000-b6bce000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-05 01:32:33.094  7058  7058 W art     : b6bce000-b6bcf000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-05 01:32:33.094  7058  7058 W art     : b6bcf000-b6bd0000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-05 01:32:33.094  7058  7058 W art     : b6bd0000-b6be4000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-05 01:32:33.094  7058  7058 W art     : b6be4000-b6be6000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-05 01:32:33.094  7058  7058 W art     : b6be6000-b6be7000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-05 01:32:33.094  7058  7058 W art     : b6be7000-b6c0f000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-05 01:32:33.094  7058  7058 W art     : b6c0f000-b6c11000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-05 01:32:33.094  7058  7058 W art     : b6c11000-b6c12000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-05 01:32:33.094  7058  7058 W art     : b6c12000-b6c15000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-05 01:32:33.094  7058  7058 W art     : b6c15000-b6c16000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-05 01:32:33.094  7058  7058 W art     : b6c16000-b6c17000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-05 01:32:33.094  7058  7058 W art     : b6c17000-b6c20000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-05 01:32:33.094  7058  7058 W art     : b6c20000-b6c21000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-05 01:32:33.094  7058  7058 W art     : b6c21000-b6c22000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-05 01:32:33.094  7058  7058 W art     : b6c22000-b6c42000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-05 01:32:33.094  7058  7058 W art     : b6c42000-b6c43000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-05 01:32:33.094  7058  7058 W art     : b6c43000-b6c44000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-05 01:32:33.094  7058  7058 W art     : b6c44000-b6cb7000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-05 01:32:33.094  7058  7058 W art     : b6cb7000-b6cbb000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-05 01:32:33.094  7058  7058 W art     : b6cbb000-b6cbe000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-05 01:32:33.094  7058  7058 W art     : b6cbe000-b6cc8000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6cc8000-b6d50000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-05 01:32:33.094  7058  7058 W art     : b6d50000-b6d51000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6d51000-b6d55000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-05 01:32:33.094  7058  7058 W art     : b6d55000-b6d56000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-05 01:32:33.094  7058  7058 W art     : b6d56000-b6d57000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6d57000-b6d80000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-05 01:32:33.094  7058  7058 W art     : b6d80000-b6d81000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6d81000-b6d84000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-05 01:32:33.094  7058  7058 W art     : b6d84000-b6d85000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-05 01:32:33.094  7058  7058 W art     : b6d85000-b6e5f000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 01:32:33.094  7058  7058 W art     : b6e5f000-b6e66000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 01:32:33.094  7058  7058 W art     : b6e66000-b6e6e000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 01:32:33.094  7058  7058 W art     : b6e6e000-b6e6f000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6e6f000-b6e70000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:33.094  7058  7058 W art     : b6e70000-b6e71000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-05 01:32:33.094  7058  7058 W art     : b6e71000-b6e72000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b6e72000-b6e75000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b6e75000-b6e9a000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-05 01:32:33.094  7058  7058 W art     : b6e9a000-b6e9b000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6e9b000-b6ea2000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-05 01:32:33.094  7058  7058 W art     : b6ea2000-b6ea3000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-05 01:32:33.094  7058  7058 W art     : b6ea3000-b6eaa000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-05 01:32:33.094  7058  7058 W art     : b6eaa000-b6eab000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-05 01:32:33.094  7058  7058 W art     : b6eab000-b6eac000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-05 01:32:33.094  7058  7058 W art     : b6eac000-b6ead000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b6ead000-b6ec5000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-05 01:32:33.094  7058  7058 W art     : b6ec5000-b6ec6000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6ec6000-b6ec7000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-05 01:32:33.094  7058  7058 W art     : b6ec7000-b6ec8000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-05 01:32:33.094  7058  7058 W art     : b6ec8000-b6ed6000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-05 01:32:33.094  7058  7058 W art     : b6ed6000-b6ed7000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6ed7000-b6ed8000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-05 01:32:33.094  7058  7058 W art     : b6ed8000-b6ed9000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-05 01:32:33.094  7058  7058 W art     : b6ed9000-b6eda000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:33.094  7058  7058 W art     : b6eda000-b6edc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b6edc000-b6edd000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b6edd000-b6ede000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:33.094  7058  7058 W art     : b6ede000-b6edf000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-05 01:32:33.094  7058  7058 W art     : b6edf000-b6ee0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:33.094  7058  7058 W art     : b6ee0000-b6f00000 r--s 00000000 00:0b 6712       /dev/__properties__
08-05 01:32:33.094  7058  7058 W art     : b6f00000-b6f01000 r--p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6f01000-b6f02000 ---p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6f02000-b6f04000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-05 01:32:33.094  7058  7058 W art     : b6f04000-b6f05000 r-xp 00000000 00:00 0          [sigpage]
08-05 01:32:33.094  7058  7058 W art     : b6f05000-b6f20000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-05 01:32:33.094  7058  7058 W art     : b6f20000-b6f21000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-05 01:32:33.094  7058  7058 W art     : b6f21000-b6f23000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-05 01:32:33.094  7058  7058 W art     : b6f23000-b6f25000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : b6f25000-b6f2a000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-05 01:32:33.094  7058  7058 W art     : b6f2a000-b6f2b000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-05 01:32:33.094  7058  7058 W art     : b6f2b000-b6f2c000 rw-p 00000000 00:00 0 
08-05 01:32:33.094  7058  7058 W art     : bed40000-bed61000 rw-p 00000000 00:00 0          [stack]
08-05 01:32:33.094  7058  7058 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-05 01:32:33.134  7058  7058 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 01:32:33.184  7058  7058 I Radio-JNI: register_android_hardware_Radio DONE
08-05 01:32:33.194  7058  7058 E AffinityControl: AffinityControl: registerfunction enter
08-05 01:32:33.214  7058  7058 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 01:32:33.224   769  1745 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-05 01:32:33.234   769  1745 D ActivityManager: mDVFSHelper.acquire()
08-05 01:32:33.244   769  1745 V WindowManager: addAppToken: AppWindowToken{c6c30fa token=Token{4c67725 ActivityRecord{de09f1c u0 com.test.thalitest/.MainActivity t115}}} to stack=1 task=115 at 0
08-05 01:32:33.244   769   908 D SecWifiDisplayUtil: Metadata value : none
08-05 01:32:33.244   769   908 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{38be552 V.E...... R.....ID 0,0-0,0}
08-05 01:32:33.244   769   908 D ISSUE_DEBUG: InputChannelName : 2147920 Starting com.test.thalitest
08-05 01:32:33.264   769  1745 I ActivityManager: Start proc 7073:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-05 01:32:33.264  7073  7073 E Zygote  : v2
08-05 01:32:33.264  7073  7073 I libpersona: KNOX_SDCARD checking this for 10004
08-05 01:32:33.264  7073  7073 I libpersona: KNOX_SDCARD not a persona
08-05 01:32:33.264  7073  7073 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-05 01:32:33.264   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-05 01:32:33.264  7073  7073 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:33.274  7073  7073 E Zygote  : accessInfo : 0
08-05 01:32:33.274  7073  7073 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-05 01:32:33.284   769   908 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-05 01:32:33.284   769  1745 D InputDispatcher: Focused application set to: xxxx
08-05 01:32:33.284   769  1745 D InputDispatcher: Focus left window: 3571
08-05 01:32:33.284  7058  7058 D AndroidRuntime: Shutting down VM
08-05 01:32:33.284   769  1325 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-05 01:32:33.284   769   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5657bfd u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-05 01:32:33.284  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-05 01:32:33.304  7073  7073 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 01:32:33.304  7073  7073 D ActivityThread: Added TimaKeyStore provider
08-05 01:32:33.314   769  1732 V WindowOrientationListener: setCurrentAppOrientation :-1
08-05 01:32:33.314   769  1732 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-05 01:32:33.314   769   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2147920 u0 d0 Starting com.test.thalitest}
08-05 01:32:33.314  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-05 01:32:33.324   769   908 V WindowStateAnimator: Finishing drawing window Window{2147920 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-05 01:32:33.324   769   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:769 uid:1000
08-05 01:32:33.324   769   908 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:33.324   769   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:769 uid:1000
08-05 01:32:33.324   769   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 01:32:33.324   769  1732 D ActivityManager:  Launching com.test.thalitest, updated priority
08-05 01:32:33.324   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec68364
08-05 01:32:33.334   769   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-05 01:32:33.354  1735  1898 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-05 01:32:33.354  1735  1735 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-05 01:32:33.354   294   378 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
08-05 01:32:33.354   294  1821 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
08-05 01:32:33.354   294   378 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
08-05 01:32:33.364   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec683a4
08-05 01:32:33.364  3571  3571 V ActivityThread: updateVisibility : ActivityRecord{56a4597 token=android.os.BinderProxy@cea43f9 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-05 01:32:33.364   294   382 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
08-05 01:32:33.364   294   382 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
08-05 01:32:33.364   294  1821 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-05 01:32:33.364   294   378 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-05 01:32:33.374   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec683a4
08-05 01:32:33.374  2209  2225 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-05 01:32:33.374  1735  1735 V ActivityThread: updateVisibility : ActivityRecord{8095229 token=android.os.BinderProxy@b4207e3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 01:32:33.374  1735  1735 D Launcher: onTrimMemory. Level: 20
,08-05 01:32:33.394   294   382 I SurfaceFlinger: id=20 Removed VSBConnecti (4/9)
08-05 01:32:33.394   294  1821 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/9)
08-05 01:32:33.394   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec683a4
08-05 01:32:33.504   769  1325 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-05 01:32:33.514  7073  7073 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 01:32:33.534   769  3494 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,08-05 01:32:33.534  7073  7073 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 01:32:33.544  7073  7073 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 01:32:33.554   769  3494 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:33.554  7073  7073 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-05 01:32:33.574  7073  7073 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 01:32:33.584  7073  7073 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-05 01:32:33.584  7073  7073 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1346-1349)
,08-05 01:32:33.594  7073  7073 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-05 01:32:33.594   769   779 I art     : Background partial concurrent mark sweep GC freed 51412(3MB) AllocSpace objects, 90(1800KB) LOS objects, 27% free, 42MB/58MB, paused 2.534ms total 128.187ms
,08-05 01:32:33.604  7073  7073 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11fb4b3}
,08-05 01:32:33.604  7073  7073 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-05 01:32:33.604  7073  7073 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 01:32:33.614  7073  7073 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-05 01:32:33.624  7073  7094 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-05 01:32:33.634  7073  7073 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-05 01:32:33.634  7073  7073 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-05 01:32:33.634  7073  7073 I Adreno-EGL: Build Date: 01/28/16 Thu
08-05 01:32:33.634  7073  7073 I Adreno-EGL: Local Branch: ss
08-05 01:32:33.634  7073  7073 I Adreno-EGL: Remote Branch: 
08-05 01:32:33.634  7073  7073 I Adreno-EGL: Local Patches: 
08-05 01:32:33.634  7073  7073 I Adreno-EGL: Reconstruct Branch: 
,08-05 01:32:33.644  7073  7073 D libEGL  : eglInitialize EGLDisplay = 0xbeb33dac
,08-05 01:32:33.674   769  1422 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-05 01:32:33.674   769  1422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-05 01:32:33.684   769  3527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 01:32:33.724  7073  7073 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-05 01:32:33.734  7073  7073 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 01:32:33.734  7073  7073 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-05 01:32:33.734  7073  7073 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-05 01:32:33.734  7073  7073 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-05 01:32:33.754  7073  7073 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-05 01:32:33.754  7073  7073 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-05 01:32:33.844  7073  7073 D SecWifiDisplayUtil: Metadata value : none
,08-05 01:32:33.854  7073  7073 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ff788c9 I.E...... R.....ID 0,0-0,0}
,08-05 01:32:33.854  7073  7118 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 01:32:33.854   769  1723 D ISSUE_DEBUG: InputChannelName : 5f716bd com.test.thalitest/com.test.thalitest.MainActivity
,08-05 01:32:33.864   769   785 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-05 01:32:33.864   769   785 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:33.864   769   769 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 01:32:33.864   769   769 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-05 01:32:33.874  7073  7073 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7073
,08-05 01:32:33.884   769  1422 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7073 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:33.884   769  1334 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-05 01:32:33.884   769  1334 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-05 01:32:33.884   769  1334 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-05 01:32:33.884   769  1334 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-05 01:32:33.884   769  1334 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:33.894  7073  7094 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-05 01:32:33.894  7073  7073 D SecWifiDisplayUtil: Metadata value : none
,08-05 01:32:33.904   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-05 01:32:33.924   769  1222 D InputDispatcher: Focus entered window: 7073
,08-05 01:32:33.924   769   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:769 uid:1000
08-05 01:32:33.924   769   908 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:33.924   769   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:769 uid:1000
08-05 01:32:33.924   769   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:32:33.924  7073  7118 D libEGL  : eglInitialize EGLDisplay = 0x9d7397c4
08-05 01:32:33.924  7073  7118 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 01:32:33.974  7073  7073 V ActivityThread: updateVisibility : ActivityRecord{47939e8 token=android.os.BinderProxy@af220d0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 01:32:33.984  7073  7073 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-05 01:32:34.024   769  1222 V WindowStateAnimator: Finishing drawing window Window{5f716bd u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-05 01:32:34.034  7073  7073 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-05 01:32:34.034  7073  7073 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 01:32:34.034   769  1693 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 01:32:34.034   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec68364
,08-05 01:32:34.044   769   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 01:32:34.044   769   769 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 01:32:34.044   769   908 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +561ms (total +792ms)
,08-05 01:32:34.044   769   908 D ActivityManager: mDVFSHelper.release()
,08-05 01:32:34.044   769   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{de09f1c u0 com.test.thalitest/.MainActivity t115} time:311805
08-05 01:32:34.044   769   769 I KnoxTimeoutHandler: SD activityfalse
,08-05 01:32:34.044   769   908 D ViewRootImpl: #3 mView = null
,08-05 01:32:34.044   294  1821 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,08-05 01:32:34.044   294  1303 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,08-05 01:32:34.054   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec683a4
,08-05 01:32:34.074   769   785 V WindowStateAnimator: Finishing drawing window Window{5f716bd u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-05 01:32:34.074  7073  7073 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 01:32:34.074  7073  7133 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-05 01:32:34.084  7073  7133 D libEGL  : eglInitialize EGLDisplay = 0x9c02f3ec
,08-05 01:32:34.084  7073  7073 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@af220d0 time:311843
,08-05 01:32:34.084   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec68364
,08-05 01:32:34.124  7073  7073 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7073
,08-05 01:32:34.284  7073  7073 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 01:32:34.394  7073  7148 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1694500560
,08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65da47e added. We now have 1 listener(s)
,08-05 01:32:34.404  7073  7148 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-05 01:32:34.404  7073  7148 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-05 01:32:34.404  7073  7148 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 01:32:34.404  7073  7148 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 01:32:34.404  7073  7148 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8bfcf5 added. We now have 1 listener(s)
08-05 01:32:34.404  7073  7148 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 01:32:34.414  7073  7148 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-05 01:32:34.414  7073  7148 D BluetoothAdapter: STATE_ON
,08-05 01:32:34.424  7073  7148 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 01:32:34.424  7073  7148 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 01:32:34.424  7073  7148 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-05 01:32:34.424  7073  7148 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 01:32:34.424  7073  7148 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 01:32:34.424  7073  7073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:32:34.434  7073  7073 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:32:34.444  7073  7073 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 01:32:34.504   769  3498 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-05 01:32:34.864  1452  1452 D Recents : onTaskStackChanged
,08-05 01:32:34.874  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-05 01:32:35.434  7073  7149 W jxcore-log: Initializing JXcore engine
,08-05 01:32:35.434  7073  7149 W jxcore-log: JXcore engine is ready
,08-05 01:32:35.484  2439  2439 E audit   : type=1400 msg=audit(1470353555.484:288): avc:  denied  { ioctl } for  pid=7149 comm="Thread-963" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-05 01:32:35.484  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 01:32:35.484  2439  2439 E audit   : type=1300 msg=audit(1470353555.484:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9adef3c8 items=0 ppid=351 ppcomm=main pid=7149 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-963" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 01:32:35.484  2439  2439 E audit   : type=1327 msg=audit(1470353555.484:288): proctitle="com.test.thalitest"
08-05 01:32:35.484  2439  2439 E audit   : type=1320 msg=audit(1470353555.484:288): 
08-05 01:32:35.484  2439  2439 E audit   : type=1400 msg=audit(1470353555.484:289): avc:  denied  { ioctl } for  pid=7149 comm="Thread-963" path="socket:[44506]" dev="sockfs" ino=44506 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-05 01:32:35.484  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 01:32:35.484  2439  2439 E audit   : type=1300 msg=audit(1470353555.484:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=1 a3=9adef3c8 items=0 ppid=351 ppcomm=main pid=7149 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-963" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 01:32:35.484  2439  2439 E audit   : type=1327 msg=audit(1470353555.484:289): proctitle="com.test.thalitest"
08-05 01:32:35.484  2439  2439 E audit   : type=1320 msg=audit(1470353555.484:289): 
,08-05 01:32:35.494  7073  7149 W jxcore-log: Starting JXcore engine
,08-05 01:32:35.574  7073  7149 W jxcore-log: Platform android
08-05 01:32:35.574  7073  7149 W jxcore-log: 
,08-05 01:32:35.574  7073  7149 W jxcore-log: Process ARCH arm
08-05 01:32:35.574  7073  7149 W jxcore-log: 
,08-05 01:32:35.784  7073  7149 I jxcore-log: JXcore Cordova bridge is ready!
08-05 01:32:35.784  7073  7149 I jxcore-log: 
,08-05 01:32:35.784  7073  7149 W jxcore-log: JXcore engine is started
,08-05 01:32:35.784  7073  7148 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 01:32:35.784  7073  7073 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 01:32:36.294   769  1367 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/115_task.xml.bak
,08-05 01:32:37.884   769  1233 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-05 01:32:37.884   769  1233 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-05 01:32:37.884   769  1232 D TimaService: TimaServiceHandler.handleMessage what =1
,08-05 01:32:37.884   769  1233 I TLC_TIMA_PKM_initialize: initializing...
,08-05 01:32:37.884   769  1233 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-05 01:32:37.884   769  1233 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-05 01:32:37.884   769  1233 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-05 01:32:37.884   769  1233 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-05 01:32:37.884   769  1233 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
08-05 01:32:37.884   769  1233 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-05 01:32:37.884   769  1233 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-05 01:32:37.884   769  1233 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-05 01:32:37.894   769  1233 D QSEECOMAPI: : App is not loaded in QSEE
,08-05 01:32:37.904   769  1233 D QSEECOMAPI: : Loaded image: APP id = 4
,08-05 01:32:37.904   769  1233 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-05 01:32:37.914   769  1233 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-05 01:32:39.564   769  3494 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:40.234   769  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-05 01:32:40.234   769  1233 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-05 01:32:40.244   769  1233 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-05 01:32:40.244   769  1233 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-05 01:32:43.304   769   931 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 01:32:43.334   769   931 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 01:32:43.574   769  3494 D SSRM:n  : SIOP:: AP = 340, PST = 307, CUR = 450, LCD = 0
,08-05 01:32:49.034  7073  7149 E jxcore  : Error!: Cannot find module '../thalilogger'
08-05 01:32:49.034  7073  7149 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-05 01:32:49.044  7073  7073 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-05 01:32:49.044  7073  7073 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-05 01:32:49.044   769  1726 D InputDispatcher: Focused application set to: xxxx
08-05 01:32:49.054   769  1726 I ActivityManager: Killing 5942:com.android.email/u0a162 (adj 15): DHA:empty #37
,08-05 01:32:49.054  7073  7073 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 01:32:49.054  7073  7073 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-05 01:32:49.054  7073  7073 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 01:32:49.054  7073  7073 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 01:32:49.054  7073  7073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 01:32:49.054  7073  7073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 01:32:49.054  7073  7073 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65da47e removed from the list
08-05 01:32:49.054  7073  7073 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 01:32:49.054  7073  7073 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8bfcf5 removed from the list
08-05 01:32:49.054  7073  7073 D io.jxcore.node.ConnectivityMonitor: stop
08-05 01:32:49.054  7073  7073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-05 01:32:49.064  7073  7073 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 01:32:49.074  7073  7073 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-05 01:32:49.094   769  3494 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:49.094   294  1303 D libEGL  : eglTerminate EGLDisplay = 0xb473d64c
08-05 01:32:49.094  7073  7073 D ViewRootImpl: #3 mView = null
08-05 01:32:49.094   294   382 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
,08-05 01:32:49.094   294   378 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-05 01:32:49.094   769  1716 D InputDispatcher: Focus left window: 7073
,08-05 01:32:49.094   769   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:769 uid:1000
,08-05 01:32:49.094   769   908 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:49.094   769   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:769 uid:1000
08-05 01:32:49.094   769   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:32:49.104   769  1551 D ActivityManager: mDVFSHelper.acquire()
,08-05 01:32:49.114   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec683a4
,08-05 01:32:49.114   769   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-05 01:32:49.124   769  1551 V WindowOrientationListener: setCurrentAppOrientation :1
08-05 01:32:49.124   769  1551 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-05 01:32:49.124  7073  7073 D cr_Ime  : [ImeAdapter.java:587] detach
,08-05 01:32:49.124  7073  7073 E ViewRootImpl: sendUserActionEvent() mView == null
,08-05 01:32:49.134   769   784 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,08-05 01:32:49.144  1735  1735 D Launcher: onRestart, Launcher: 240509081
,08-05 01:32:49.144   294   294 I SurfaceFlinger: id=23 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-05 01:32:49.144   769   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2d49488 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-05 01:32:49.144  1735  1735 D Launcher: onStart, Launcher: 240509081
08-05 01:32:49.144  1384  1384 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-05 01:32:49.144  1735  1735 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
08-05 01:32:49.144  1735  1735 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-05 01:32:49.144  1735  1735 D Launcher.HomeView: onStart
08-05 01:32:49.144   769   785 D InputDispatcher: Focus entered window: 3571
,08-05 01:32:49.154   769   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:769 uid:1000
08-05 01:32:49.154   769   908 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:49.154   769   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:769 uid:1000
08-05 01:32:49.154   769   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:32:49.154  1735  1735 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
08-05 01:32:49.154  1735  1735 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
08-05 01:32:49.154  1735  1735 V ActivityThread: updateVisibility : ActivityRecord{8095229 token=android.os.BinderProxy@b4207e3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-05 01:32:49.154  2209  5626 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-05 01:32:49.154   769  1551 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-05 01:32:49.154   769  1551 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:49.154   769   769 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-05 01:32:49.164   769   769 I KnoxTimeoutHandler: Shared devices show user statefalse
08-05 01:32:49.164   769   769 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-05 01:32:49.164   294   294 I SurfaceFlinger: id=24 createSurf (1080x1920),1 flag=4, Mauncher
,08-05 01:32:49.174   769  1716 V WindowStateAnimator: Finishing drawing window Window{2d49488 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-05 01:32:49.174   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec68364
,08-05 01:32:49.184   294   294 I SurfaceFlinger: id=25 createSurf (1194x288),1 flag=4, VSBConnecti
,08-05 01:32:49.194   769   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:49.194   769   769 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-05 01:32:49.194   769   769 I KnoxTimeoutHandler: SD activityfalse
08-05 01:32:49.194   769   908 D ActivityManager: mDVFSHelper.release()
08-05 01:32:49.194   769   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e2d5722 u0 com.samsung.android.MtpApplication/.USBConnection t114} time:326954
,08-05 01:32:49.194  3571  3571 V ActivityThread: updateVisibility : ActivityRecord{56a4597 token=android.os.BinderProxy@cea43f9 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-05 01:32:49.224   769   785 V WindowStateAnimator: Finishing drawing window Window{c76d246 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-05 01:32:49.224  3571  3571 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cea43f9 time:326981
,08-05 01:32:49.224   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec68364
,08-05 01:32:49.234   769   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:49.234   769   769 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:49.234   769   769 I KnoxTimeoutHandler: SD activityfalse
,08-05 01:32:49.334   769  1716 V WindowStateAnimator: Finishing drawing window Window{5657bfd u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-05 01:32:49.334  1735  1735 D Launcher.HomeView: onStop
08-05 01:32:49.334   769   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:49.344   769   769 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:49.344   769   769 I KnoxTimeoutHandler: SD activityfalse
08-05 01:32:49.344   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec68364
08-05 01:32:49.344   769   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e5c9d0a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t112} time:327102
,08-05 01:32:49.914  2439  2439 E audit   : type=1400 msg=audit(1470353569.914:290): avc:  denied  { execmod } for  pid=7167 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 01:32:49.914  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 01:32:49.914  2439  2439 E audit   : type=1300 msg=audit(1470353569.914:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbe000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7167 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-05 01:32:49.914  2439  2439 E audit   : type=1327 msg=audit(1470353569.914:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-05 01:32:49.924  2439  2439 E audit   : type=1320 msg=audit(1470353569.914:290): 
,08-05 01:32:49.974  2439  2439 E audit   : type=1400 msg=audit(1470353569.974:291): avc:  denied  { execmod } for  pid=7167 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-05 01:32:49.974  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:49.974  2439  2439 E audit   : type=1300 msg=audit(1470353569.974:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f80000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7167 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 01:32:49.974  2439  2439 E audit   : type=1327 msg=audit(1470353569.974:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-05 01:32:49.974  2439  2439 E audit   : type=1320 msg=audit(1470353569.974:291): 
,08-05 01:32:50.024  2439  2439 E audit   : type=1400 msg=audit(1470353570.024:292): avc:  denied  { execmod } for  pid=7167 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-05 01:32:50.024  7167  7167 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 01:32:50.024  2439  2439 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 01:32:50.024  2439  2439 E audit   : type=1300 msg=audit(1470353570.024:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3df2000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7167 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-05 01:32:50.024  2439  2439 E audit   : type=1327 msg=audit(1470353570.024:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-05 01:32:50.024  7167  7167 D AndroidRuntime: CheckJNI is OFF
,08-05 01:32:50.024  7167  7167 D AndroidRuntime: readGMSProperty: start
08-05 01:32:50.034  7167  7167 D AndroidRuntime: readGMSProperty: already setted!!
08-05 01:32:50.034  7167  7167 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 01:32:50.034  7167  7167 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 01:32:50.034  7167  7167 D AndroidRuntime: readGMSProperty: end
08-05 01:32:50.034  7167  7167 D AndroidRuntime: addProductProperty: start
,08-05 01:32:50.034  2439  2439 E audit   : type=1320 msg=audit(1470353570.024:292): 
,08-05 01:32:50.034  7167  7167 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-05 01:32:50.034  7167  7167 W art     : aede5000-b1d0b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-05 01:32:50.034  7167  7167 W art     : b1d0b000-b3f7a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-05 01:32:50.034  7167  7167 W art     : b3f7a000-b3f7b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-05 01:32:50.034  7167  7167 W art     : b3f7b000-b3f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.034  7167  7167 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-05 01:32:50.034  7167  7167 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-05 01:32:50.034  7167  7167 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-05 01:32:50.034  7167  7167 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-05 01:32:50.034  7167  7167 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-05 01:32:50.034  7167  7167 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-05 01:32:50.034  7167  7167 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
,08-05 01:32:50.034  7167  7167 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-05 01:32:50.034  7167  7167 W art     : b484c000-b484f000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-05 01:32:50.034  7167  7167 W art     : b484f000-b4850000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-05 01:32:50.044  7167  7167 W art     : b4850000-b4851000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-05 01:32:50.044  7167  7167 W art     : b4851000-b4852000 r--p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b4852000-b4872000 r--s 00000000 00:0b 6712       /dev/__properties__
08-05 01:32:50.044  7167  7167 W art     : b4872000-b5283000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-05 01:32:50.044  7167  7167 W art     : b5283000-b5284000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5284000-b52cd000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-05 01:32:50.044  7167  7167 W art     : b52cd000-b52ce000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-05 01:32:50.044  7167  7167 W art     : b52ce000-b52d6000 rw-p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b52d6000-b52d7000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-05 01:32:50.044  7167  7167 W art     : b52d7000-b530c000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-05 01:32:50.044  7167  7167 W art     : b530c000-b530d000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b530d000-b530e000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-05 01:32:50.044  7167  7167 W art     : b530e000-b530f000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-05 01:32:50.044  7167  7167 W art     : b530f000-b5367000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-05 01:32:50.044  7167  7167 W art     : b5367000-b5368000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5368000-b5369000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-05 01:32:50.044  7167  7167 W art     : b5369000-b536a000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-05 01:32:50.044  7167  7167 W art     : b536b000-b5371000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-05 01:32:50.044  7167  7167 W art     : b5371000-b5372000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 01:32:50.044  7167  7167 W art     : b5372000-b5373000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 01:32:50.044  7167  7167 W art     : b5373000-b5375000 rw-p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5376000-b5380000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 01:32:50.044  7167  7167 W art     : b5380000-b5383000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 01:32:50.044  7167  7167 W art     : b5383000-b5384000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 01:32:50.044  7167  7167 W art     : b5385000-b539c000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 01:32:50.044  7167  7167 W art     : b539c000-b539d000 ---p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b539d000-b539e000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 01:32:50.044  7167  7167 W art     : b539e000-b539f000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 01:32:50.044  7167  7167 W art     : b53a0000-b53aa000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-05 01:32:50.044  7167  7167 W art     : b53aa000-b53ab000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-05 01:32:50.044  7167  7167 W art     : b53ab000-b53ac000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-05 01:32:50.044  7167  7167 W art     : b53ac000-b53b0000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 01:32:50.044  7167  7167 W art     : b53b0000-b53b1000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-05 01:32:50.044  7167  7167 W art     : b53b1000-b53b2000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 01:32:50.044  7167  7167 W art     : b53b2000-b53c8000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-05 01:32:50.044  7167  7167 W art     : b53c8000-b53c9000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-05 01:32:50.044  7167  7167 W art     : b53c9000-b53ca000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-05 01:32:50.044  7167  7167 W art     : b53ca000-b53d7000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-05 01:32:50.044  7167  7167 W art     : b53d7000-b53d8000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-05 01:32:50.044  7167  7167 W art     : b53d8000-b53d9000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-05 01:32:50.044  7167  7167 W art     : b53d9000-b5439000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-05 01:32:50.044  7167  7167 W art     : b5439000-b543c000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-05 01:32:50.044  7167  7167 W art     : b543c000-b5440000 rw-p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5440000-b54a1000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-05 01:32:50.044  7167  7167 W art     : b54a1000-b54a2000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
,08-05 01:32:50.044  7167  7167 W art     : b54a2000-b54f1000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-05 01:32:50.044  7167  7167 W art     : b54f1000-b54f3000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so,
08-05 01:32:50.044  7167  7167 W art     : b54f3000-b54f4000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-05 01:32:50.044  7167  7167 W art     : b54f4000-b54f5000 rw-p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b54f5000-b54fc000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-05 01:32:50.044  7167  7167 W art     : b54fc000-b54fd000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so,
08-05 01:32:50.044  7167  7167 W art     : b54fd000-b54fe000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so,
08-05 01:32:50.044  7167  7167 W art     : b54ff000-b5502000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so,
,08-05 01:32:50.044  7167  7167 W art     : b5502000-b5503000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-05 01:32:50.044  7167  7167 W art     : b5503000-b5504000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so,
08-05 01:32:50.044  7167  7167 W art     : b5505000-b5509000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-05 01:32:50.044  7167  7167 W art     : b5509000-b550a000 ---p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b550a000-b550b000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-05 01:32:50.044  7167  7167 W art     : b550b000-b550c000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
,08-05 01:32:50.044  7167  7167 W art     : b550d000-b552a000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
,08-05 01:32:50.044  7167  7167 W art     : b552a000-b552b000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so,
08-05 01:32:50.044  7167  7167 W art     : b552b000-b552c000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
,08-05 01:32:50.044  7167  7167 W art     : b552d000-b5532000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 01:32:50.044  7167  7167 W art     : b5532000-b5533000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
,08-05 01:32:50.044  7167  7167 W art     : b5533000-b5534000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 01:32:50.044  7167  7167 W art     : b5535000-b5566000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 01:32:50.044  7167  7167 W art     : b5566000-b5569000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 01:32:50.044  7167  7167 W art     : b5569000-b556a000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-05 01:32:50.044  7167  7167 W art     : b556b000-b55a6000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-05 01:32:50.044  7167  7167 W art     : b55a6000-b55a7000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-05 01:32:50.044  7167  7167 W art     : b55a7000-b55a8000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-05 01:32:50.044  7167  7167 W art     : b55a9000-b55b0000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
,08-05 01:32:50.044  7167  7167 W art     : b55b0000-b55b1000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b55b1000-b55b2000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-05 01:32:50.044  7167  7167 W art     : b55b2000-b55b3000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
,08-05 01:32:50.044  7167  7167 W art     : b55b3000-b55b4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b55b4000-b55cb000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so,
08-05 01:32:50.044  7167  7167 W art     : b55cb000-b55cc000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b55cc000-b55cf000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so,
08-05 01:32:50.044  7167  7167 W art     : b55cf000-b55d0000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
,08-05 01:32:50.044  7167  7167 W art     : b55d0000-b55ef000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-05 01:32:50.044  7167  7167 W art     : b55ef000-b55f0000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-05 01:32:50.044  7167  7167 W art     : b55f0000-b55f1000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
,08-05 01:32:50.044  7167  7167 W art     : b55f1000-b562f000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-05 01:32:50.044  7167  7167 W art     : b562f000-b5630000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5630000-b5632000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-05 01:32:50.044  7167  7167 W art     : b5632000-b5633000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-05 01:32:50.044  7167  7167 W art     : b5634000-b563b000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 01:32:50.044  7167  7167 W art     : b563b000-b563c000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 01:32:50.044  7167  7167 W art     : b563c000-b563d000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so,
08-05 01:32:50.044  7167  7167 W art     : b563e000-b5641000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 01:32:50.044  7167  7167 W art     : b5641000-b5642000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 01:32:50.044  7167  7167 W art     : b5642000-b5643000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 01:32:50.044  7167  7167 W art     : b5643000-b5649000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 01:32:50.044  7167  7167 W art     : b5649000-b564a000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b564a000-b564b000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-05 01:32:50.044  7167  7167 W art     : b564b000-b564c000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 01:32:50.044  7167  7167 W art     : b564c000-b5655000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-05 01:32:50.044  7167  7167 W art     : b5655000-b5656000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-05 01:32:50.044  7167  7167 W art     : b5656000-b5657000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-05 01:32:50.044  7167  7167 W art     : b5657000-b56e8000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 01:32:50.044  7167  7167 W art     : b56e8000-b56e9000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b56e9000-b56f4000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 01:32:50.044  7167  7167 W art     : b56f4000-b56f5000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 01:32:50.044  7167  7167 W art     : b56f6000-b5708000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-05 01:32:50.044  7167  7167 W art     : b5708000-b5709000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-05 01:32:50.044  7167  7167 W art     : b5709000-b570a000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-05 01:32:50.044  7167  7167 W art     : b570b000-b5710000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-05 01:32:50.044  7167  7167 W art     : b5710000-b5711000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
,08-05 01:32:50.044  7167  7167 W art     : b5711000-b5712000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-05 01:32:50.044  7167  7167 W art     : b5713000-b5780000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-05 01:32:50.044  7167  7167 W art     : b5780000-b5781000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5781000-b5783000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-05 01:32:50.044  7167  7167 W art     : b5783000-b5784000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-05 01:32:50.044  7167  7167 W art     : b5784000-b5785000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b5785000-b578c000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 01:32:50.044  7167  7167 W art     : b578c000-b578d000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 01:32:50.044  7167  7167 W art     : b578d000-b578e000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 01:32:50.044  7167  7167 W art     : b578f000-b580f000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
,08-05 01:32:50.044  7167  7167 W art     : b580f000-b5810000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5810000-b5811000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 01:32:50.044  7167  7167 W art     : b5811000-b5812000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 01:32:50.044  7167  7167 W art     : b5812000-b5829000 rw-p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5829000-b5860000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-05 01:32:50.044  7167  7167 W art     : ib/libqc-opt.so
08-05 01:32:50.044  7167  7167 W art     : b5860000-b5861000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so,
08-05 01:32:50.044  7167  7167 W art     : b5861000-b5862000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 01:32:50.044  7167  7167 W art     : b5862000-b587e000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 01:32:50.044  7167  7167 W art     : b587e000-b587f000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 01:32:50.044  7167  7167 W art     : b587f000-b5880000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 01:32:50.044  7167  7167 W art     : b5881000-b58e2000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
,08-05 01:32:50.044  7167  7167 W art     : b58e2000-b58e4000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-05 01:32:50.044  7167  7167 W art     : b58e4000-b58e5000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-05 01:32:50.044  7167  7167 W art     : b58e6000-b590d000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-05 01:32:50.044  7167  7167 W art     : b590d000-b590e000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b590e000-b590f000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-05 01:32:50.044  7167  7167 W art     : b590f000-b5910000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
,08-05 01:32:50.044  7167  7167 W art     : b5911000-b5919000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 01:32:50.044  7167  7167 W art     : b5919000-b591b000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 01:32:50.044  7167  7167 W art     : b591b000-b591c000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-05 01:32:50.044  7167  7167 W art     : b591d000-b5920000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-05 01:32:50.044  7167  7167 W art     : b5920000-b5921000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-05 01:32:50.044  7167  7167 W art     : b5921000-b5922000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-05 01:32:50.044  7167  7167 W art     : b5922000-b5926000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-05 01:32:50.044  7167  7167 W art     : b5926000-b5927000 ---p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b5927000-b5928000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-05 01:32:50.044  7167  7167 W art     : b5928000-b5929000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-05 01:32:50.044  7167  7167 W art     : b5929000-b5939000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
,08-05 01:32:50.044  7167  7167 W art     : b5939000-b593a000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-05 01:32:50.044  7167  7167 W art     : b593a000-b593b000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-05 01:32:50.044  7167  7167 W art     : b593b000-b5981000 rw-p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5981000-b598a000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so,
08-05 01:32:50.044  7167  7167 W art     : b598a000-b598b000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-05 01:32:50.044  7167  7167 W art     : b598b000-b598c000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-05 01:32:50.044  7167  7167 W art     : b598d000-b5992000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
,08-05 01:32:50.044  7167  7167 W art     : b5992000-b5993000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-05 01:32:50.044  7167  7167 W art     : b5993000-b5994000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-05 01:32:50.044  7167  7167 W art     : b5994000-b5997000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-05 01:32:50.044  7167  7167 W art     : b5997000-b5998000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5998000-b5999000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 01:32:50.044  7167  7167 W art     : b5999000-b599a000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 01:32:50.044  7167  7167 W art     : b599b000-b59b3000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
,08-05 01:32:50.044  7167  7167 W art     : b59b3000-b59b4000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b59b4000-b59b5000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 01:32:50.044  7167  7167 W art     : b59b5000-b59b6000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 01:32:50.044  7167  7167 W art     : b59b7000-b5b51000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
,08-05 01:32:50.044  7167  7167 W art     : b5b51000-b5b52000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5b52000-b5b5f000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-05 01:32:50.044  7167  7167 W art     : b5b5f000-b5b60000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-05 01:32:50.044  7167  7167 W art     : b5b60000-b5b64000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
,08-05 01:32:50.044  7167  7167 W art     : b5b64000-b5b65000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5b65000-b5b66000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-05 01:32:50.044  7167  7167 W art     : b5b66000-b5b67000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
,08-05 01:32:50.044  7167  7167 W art     : b5b67000-b5b7a000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-05 01:32:50.044  7167  7167 W art     : b5b7a000-b5b7b000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-05 01:32:50.044  7167  7167 W art     : b5b7b000-b5b7c000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-05 01:32:50.044  7167  7167 W art     : b5b7d000-b5bc8000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-05 01:32:50.044  7167  7167 W art     : b5bc8000-b5bc9000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so,
08-05 01:32:50.044  7167  7167 W art     : b5bc9000-b5bca000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-05 01:32:50.044  7167  7167 W art     : b5bca000-b5bcc000 rw-p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5bcc000-b5bcd000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:50.044  7167  7167 W art     : b5bcd000-b5bde000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 01:32:50.044  7167  7167 W art     : b5bde000-b5bdf000 ---p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b5bdf000-b5be0000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 01:32:50.044  7167  7167 W art     : b5be0000-b5be1000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 01:32:50.044  7167  7167 W art     : b5be2000-b5bec000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-05 01:32:50.044  7167  7167 W art     : b5bec000-b5bee000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-05 01:32:50.044  7167  7167 W art     : b5bee000-b5bef000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so,
08-05 01:32:50.044  7167  7167 W art     : b5bef000-b5c08000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-05 01:32:50.044  7167  7167 W art     : b5c08000-b5c09000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-05 01:32:50.044  7167  7167 W art     : b5c09000-b5c0c000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-05 01:32:50.044  7167  7167 W art     : b5c0c000-b5c10000 rw-p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b5c10000-b5c84000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-05 01:32:50.044  7167  7167 W art     : b5c84000-b5c85000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5c85000-b5c88000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-05 01:32:50.044  7167  7167 W art     : b5c88000-b5c89000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-05 01:32:50.044  7167  7167 W art     : b5c8a000-b5c8d000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
,08-05 01:32:50.044  7167  7167 W art     : b5c8d000-b5c8e000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-05 01:32:50.044  7167  7167 W art     : b5c8e000-b5c8f000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-05 01:32:50.044  7167  7167 W art     : b5c8f000-b5c90000 r--p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5c90000-b5c95000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 01:32:50.044  7167  7167 W art     : b5c95000-b5c96000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so,
08-05 01:32:50.044  7167  7167 W art     : b5c96000-b5c97000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 01:32:50.044  7167  7167 W art     : b5c97000-b5c98000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b5c98000-b5c9b000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 01:32:50.044  7167  7167 W art     : b5c9b000-b5c9c000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
,08-05 01:32:50.044  7167  7167 W art     : b5c9c000-b5c9d000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 01:32:50.044  7167  7167 W art     : b5c9d000-b5c9e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b5c9e000-b5ca2000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-05 01:32:50.044  7167  7167 W art     : b5ca2000-b5ca3000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
,08-05 01:32:50.044  7167  7167 W art     : b5ca3000-b5ca4000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-05 01:32:50.044  7167  7167 W art     : b5ca4000-b5ca5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:50.044  7167  7167 W art     : b5ca5000-b5ca9000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 01:32:50.044  7167  7167 W art     : b5ca9000-b5caa000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 01:32:50.044  7167  7167 W art     : b5caa000-b5cab000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
,08-05 01:32:50.044  7167  7167 W art     : b5cab000-b5cac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b5cac000-b5cba000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-05 01:32:50.044  7167  7167 W art     : b5cba000-b5cbb000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b5cbb000-b5cbc000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-05 01:32:50.044  7167  7167 W art     : b5cbc000-b5cbd000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so,
08-05 01:32:50.044  7167  7167 W art     : b5cbd000-b5cc7000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 01:32:50.044  7167  7167 W art     : b5cc7000-b5cca000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 01:32:50.044  7167  7167 W art     : b5cca000-b5ccb000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 01:32:50.044  7167  7167 W art     : b5ccb000-b5ccc000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-05 01:32:50.044  7167  7167 W art     : b5ccc000-b5cd6000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-05 01:32:50.044  7167  7167 W art     : b5cd6000-b5cd9000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-05 01:32:50.044  7167  7167 W art     : b5cd9000-b5cda000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-05 01:32:50.044  7167  7167 W art     : b5cda000-b5cde000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
,08-05 01:32:50.044  7167  7167 W art     : b5cde000-b5cdf000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-05 01:32:50.044  7167  7167 W art     : b5cdf000-b5ce0000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-05 01:32:50.044  7167  7167 W art     : b5ce0000-b5ce1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b5ce1000-b5cee000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
,08-05 01:32:50.044  7167  7167 W art     : b5cee000-b5cf0000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-05 01:32:50.044  7167  7167 W art     : b5cf0000-b5cf1000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-05 01:32:50.044  7167  7167 W art     : b5cf1000-b6103000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-05 01:32:50.044  7167  7167 W art     : b6103000-b6104000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b6104000-b610d000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so,
08-05 01:32:50.044  7167  7167 W art     : b610d000-b6111000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-05 01:32:50.044  7167  7167 W art     : b6111000-b6112000 rw-p 00000000 00:00 0 
,08-05 01:32:50.044  7167  7167 W art     : b6112000-b6119000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-05 01:32:50.044  7167  7167 W art     : ioutils.so
08-05 01:32:50.044  7167  7167 W art     : b6119000-b611a000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-05 01:32:50.044  7167  7167 W art     : b611a000-b611b000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-05 01:32:50.044  7167  7167 W art     : b611b000-b611c000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-05 01:32:50.044  7167  7167 W art     : b611c000-b6137000 r-xp 00000000
08-05 01:32:50.044  7167  7167 W art     :  b3:17 1184       /system/lib/libz.so
08-05 01:32:50.044  7167  7167 W art     : b6137000-b6138000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-05 01:32:50.044  7167  7167 W art     : b6138000-b6139000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
,08-05 01:32:50.044  7167  7167 W art     : b6139000-b613a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.044  7167  7167 W art     : b613a000-b6186000 r-xp 00000000 b3:17 994        
08-05 01:32:50.044  7167  7167 W art     : /system/lib/libharfbuzz_ng.so,
08-05 01:32:50.044  7167  7167 W art     : b6186000-b6187000 ---p 00000000 00:00 0 ,
08-05 01:32:50.044  7167  7167 W art     : b6187000-b6188000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 01:32:50.044  7167  7167 W art     : b6188000-b6189000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 01:32:50.044  7167  7167 W art     : b6189000-b618a000 r--p 00000000 00:00 0          [anon:li
08-05 01:32:50.044  7167  7167 W art     : nker_alloc]
,08-05 01:32:50.044  7167  7167 W art     : b618a000-b618e000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-05 01:32:50.044  7167  7167 W art     : b618e000-b618f000 ---p 00000000 00:00 0 
08-05 01:32:50.044  7167  7167 W art     : b618f000-b6190000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-05 01:32:50.054  7167  7167 W art     : b6190000-b6191000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-05 01:32:50.054  7167  7167 W art     : sbhost.so,
08-05 01:32:50.054  7167  7167 W art     : b6191000-b61c9000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-05 01:32:50.054  7167  7167 W art     : b61c9000-b61ca000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-05 01:32:50.054  7167  7167 W art     : b61ca000-b61cb000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-05 01:32:50.054  7167  7167 W art     : b61cb000-b61cc000 r--p 00000000 00:00 0 
,08-05 01:32:50.054  7167  7167 W art     :          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b61cc000-b626a000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-05 01:32:50.054  7167  7167 W art     : b626a000-b626b000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b626b000-b6289000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
,08-05 01:32:50.054  7167  7167 W art     : b6289000-b628a000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-05 01:32:50.054  7167  7167 W art     : .so
08-05 01:32:50.054  7167  7167 W art     : b628a000-b63fd000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-05 01:32:50.054  7167  7167 W art     : b63fd000-b6408000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
,08-05 01:32:50.054  7167  7167 W art     : b6408000-b6409000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-05 01:32:50.054  7167  7167 W art     : b6409000-b6520000 r-xp 00000000
08-05 01:32:50.054  7167  7167 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-05 01:32:50.054  7167  7167 W art     : b6520000-b652b000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
,08-05 01:32:50.054  7167  7167 W art     : b652b000-b652c000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-05 01:32:50.054  7167  7167 W art     : b652c000-b6530000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6530000-b6554000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-05 01:32:50.054  7167  7167 W art     : o
08-05 01:32:50.054  7167  7167 W art     : b6554000-b6556000 r--p 00023000 b3:17 400        /system/lib/libssl.so
,08-05 01:32:50.054  7167  7167 W art     : b6556000-b6557000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-05 01:32:50.054  7167  7167 W art     : b6557000-b65fd000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-05 01:32:50.054  7167  7167 W art     : b65fd000-b660a000 r--p 000a5000 b3:17 13
08-05 01:32:50.054  7167  7167 W art     : 2        /system/lib/libcrypto.so
,08-05 01:32:50.054  7167  7167 W art     : b660a000-b660b000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-05 01:32:50.054  7167  7167 W art     : b660b000-b660c000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b660c000-b665f000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-05 01:32:50.054  7167  7167 W art     : b665f000-b6660000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6660000-b6661000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-05 01:32:50.054  7167  7167 W art     : b6661000-b6662000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
,08-05 01:32:50.054  7167  7167 W art     : b6662000-b6667000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6667000-b6679000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-05 01:32:50.054  7167  7167 W art     : b6679000-b667a000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b667a000-b667b000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-05 01:32:50.054  7167  7167 W art     : b667b000-b667c000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
,08-05 01:32:50.054  7167  7167 W art     : b667c000-b6683000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 01:32:50.054  7167  7167 W art     : b6683000-b6684000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-05 01:32:50.054  7167  7167 W art     : b6684000-b6685000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 01:32:50.054  7167  7167 W art     : b6685000-b6686000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6686000-b6689000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-05 01:32:50.054  7167  7167 W art     : b6689000-b668a000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
,08-05 01:32:50.054  7167  7167 W art     : b668a000-b668b000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-05 01:32:50.054  7167  7167 W art     : b668b000-b668f000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-05 01:32:50.054  7167  7167 W art     : b668f000-b6690000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-05 01:32:50.054  7167  7167 W art     : b6690000-b6691000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-05 01:32:50.054  7167  7167 W art     : b6691000-b669f000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
,08-05 01:32:50.054  7167  7167 W art     : b669f000-b66a0000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b66a0000-b66a1000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-05 01:32:50.054  7167  7167 W art     : b66a1000-b66a2000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-05 01:32:50.054  7167  7167 W art     : b66a2000-b66ab000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 01:32:50.054  7167  7167 W art     : b66ab000-b66ac000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 01:32:50.054  7167  7167 W art     : b66ac000-b66ad000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so,
08-05 01:32:50.054  7167  7167 W art     : b66ad000-b6713000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-05 01:32:50.054  7167  7167 W art     : b6713000-b6714000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6714000-b6716000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-05 01:32:50.054  7167  7167 W art     : b6716000-b671f000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
,08-05 01:32:50.054  7167  7167 W art     : b671f000-b6722000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6722000-b67b9000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-05 01:32:50.054  7167  7167 W art     : b67b9000-b67bb000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-05 01:32:50.054  7167  7167 W art     : b67bb000-b67bc000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-05 01:32:50.054  7167  7167 W art     : b67bc000-b67bd000 rw-p 00000000 00:00 0 ,
08-05 01:32:50.054  7167  7167 W art     : b67bd000-b6ade000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-05 01:32:50.054  7167  7167 W art     : b6ade000-b6adf000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6adf000-b6afa000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-05 01:32:50.054  7167  7167 W art     : b6afa000-b6afe000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-05 01:32:50.054  7167  7167 W art     : b6afe000-b6b03000 rw-p 00000000 00:00 0 
,08-05 01:32:50.054  7167  7167 W art     : b6b03000-b6b0b000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 01:32:50.054  7167  7167 W art     : b6b0b000-b6b0c000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 01:32:50.054  7167  7167 W art     : b6b0c000-b6b0d000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 01:32:50.054  7167  7167 W art     : b6b0d000-b6b3b000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-05 01:32:50.054  7167  7167 W art     : b6b3b000-b6b3c000 ---p 00000000 00:00 0 
,08-05 01:32:50.054  7167  7167 W art     : b6b3c000-b6b43000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-05 01:32:50.054  7167  7167 W art     : b6b43000-b6b44000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-05 01:32:50.054  7167  7167 W art     : b6b44000-b6b8a000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-05 01:32:50.054  7167  7167 W art     : b6b8a000-b6b8b000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6b8b000-b6b8e000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
,08-05 01:32:50.054  7167  7167 W art     : b6b8e000-b6b8f000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-05 01:32:50.054  7167  7167 W art     : b6b8f000-b6baa000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-05 01:32:50.054  7167  7167 W art     : b6baa000-b6bae000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-05 01:32:50.054  7167  7167 W art     : b6bae000-b6baf000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-05 01:32:50.054  7167  7167 W art     : b6baf000-b6bfc000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-05 01:32:50.054  7167  7167 W art     : b6bfc000-b6bfd000 ---p 00000000 00:00 0 
,08-05 01:32:50.054  7167  7167 W art     : b6bfd000-b6c09000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-05 01:32:50.054  7167  7167 W art     : b6c09000-b6c0a000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-05 01:32:50.054  7167  7167 W art     : b6c0a000-b6c17000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-05 01:32:50.054  7167  7167 W art     : b6c17000-b6c18000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6c18000-b6c19000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
,08-05 01:32:50.054  7167  7167 W art     : b6c19000-b6c1a000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-05 01:32:50.054  7167  7167 W art     : b6c1a000-b6c22000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-05 01:32:50.054  7167  7167 W art     : b6c22000-b6c23000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6c23000-b6c24000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-05 01:32:50.054  7167  7167 W art     : b6c24000-b6c25000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
,08-05 01:32:50.054  7167  7167 W art     : b6c25000-b6c2c000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-05 01:32:50.054  7167  7167 W art     : b6c2c000-b6c2d000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-05 01:32:50.054  7167  7167 W art     : b6c2d000-b6c2e000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-05 01:32:50.054  7167  7167 W art     : b6c2e000-b6c42000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-05 01:32:50.054  7167  7167 W art     : b6c42000-b6c44000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-05 01:32:50.054  7167  7167 W art     : b6c44000-b6c45000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
,08-05 01:32:50.054  7167  7167 W art     : b6c45000-b6c6d000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-05 01:32:50.054  7167  7167 W art     : b6c6d000-b6c6f000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-05 01:32:50.054  7167  7167 W art     : b6c6f000-b6c70000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-05 01:32:50.054  7167  7167 W art     : b6c70000-b6c73000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-05 01:32:50.054  7167  7167 W art     : b6c73000-b6c74000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
,08-05 01:32:50.054  7167  7167 W art     : b6c74000-b6c75000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-05 01:32:50.054  7167  7167 W art     : b6c75000-b6c7e000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-05 01:32:50.054  7167  7167 W art     : b6c7e000-b6c7f000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-05 01:32:50.054  7167  7167 W art     : b6c7f000-b6c80000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-05 01:32:50.054  7167  7167 W art     : b6c80000-b6ca0000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
,08-05 01:32:50.054  7167  7167 W art     : b6ca0000-b6ca1000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-05 01:32:50.054  7167  7167 W art     : b6ca1000-b6ca2000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-05 01:32:50.054  7167  7167 W art     : b6ca2000-b6d15000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-05 01:32:50.054  7167  7167 W art     : b6d15000-b6d19000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-05 01:32:50.054  7167  7167 W art     : b6d19000-b6d1c000 rw-p 00076000 b3:17 860        /system/lib/libc.so
,08-05 01:32:50.054  7167  7167 W art     : b6d1c000-b6d26000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6d26000-b6dae000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-05 01:32:50.054  7167  7167 W art     : b6dae000-b6daf000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6daf000-b6db3000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-05 01:32:50.054  7167  7167 W art     : b6db3000-b6db4000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
,08-05 01:32:50.054  7167  7167 W art     : b6db4000-b6db5000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6db5000-b6dde000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-05 01:32:50.054  7167  7167 W art     : b6dde000-b6ddf000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6ddf000-b6de2000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-05 01:32:50.054  7167  7167 W art     : b6de2000-b6de3000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
,08-05 01:32:50.054  7167  7167 W art     : b6de3000-b6ebd000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 01:32:50.054  7167  7167 W art     : b6ebd000-b6ec4000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 01:32:50.054  7167  7167 W art     : b6ec4000-b6ecc000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 01:32:50.054  7167  7167 W art     : b6ecc000-b6ecd000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-05 01:32:50.054  7167  7167 W art     : b6ece000-b6ecf000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-05 01:32:50.054  7167  7167 W art     : b6ecf000-b6ed0000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b6ed0000-b6ed3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b6ed3000-b6ef8000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-05 01:32:50.054  7167  7167 W art     : b6ef8000-b6ef9000 ---p 00000000 00:00 0 
,08-05 01:32:50.054  7167  7167 W art     : b6ef9000-b6f00000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-05 01:32:50.054  7167  7167 W art     : b6f00000-b6f01000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-05 01:32:50.054  7167  7167 W art     : b6f01000-b6f08000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-05 01:32:50.054  7167  7167 W art     : b6f08000-b6f09000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-05 01:32:50.054  7167  7167 W art     : b6f09000-b6f0a000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
,08-05 01:32:50.054  7167  7167 W art     : b6f0a000-b6f0b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b6f0b000-b6f23000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-05 01:32:50.054  7167  7167 W art     : b6f23000-b6f24000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6f24000-b6f25000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-05 01:32:50.054  7167  7167 W art     : b6f25000-b6f26000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
,08-05 01:32:50.054  7167  7167 W art     : b6f26000-b6f34000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-05 01:32:50.054  7167  7167 W art     : b6f34000-b6f35000 ---p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6f35000-b6f36000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-05 01:32:50.054  7167  7167 W art     : b6f36000-b6f37000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
,08-05 01:32:50.054  7167  7167 W art     : b6f37000-b6f38000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 01:32:50.054  7167  7167 W art     : b6f38000-b6f3a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b6f3a000-b6f3b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b6f3b000-b6f3c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-05 01:32:50.054  7167  7167 W art     : b6f3c000-b6f3d000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-05 01:32:50.054  7167  7167 W art     : b6f3d000-b6f3e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 01:32:50.054  7167  7167 W art     : b6f3e000-b6f5e000 r--s 00000000 00:0b 6712       /dev/__properties__
08-05 01:32:50.054  7167  7167 W art     : b6f5e000-b6f5f000 r--p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6f5f000-b6f60000 ---p 00000000 00:00 0 
,08-05 01:32:50.054  7167  7167 W art     : b6f60000-b6f62000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-05 01:32:50.054  7167  7167 W art     : b6f62000-b6f63000 r-xp 00000000 00:00 0          [sigpage]
08-05 01:32:50.054  7167  7167 W art     : b6f63000-b6f7e000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-05 01:32:50.054  7167  7167 W art     : b6f7e000-b6f7f000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-05 01:32:50.054  7167  7167 W art     : b6f7f000-b6f81000 rw-p 0001b000 b3:17 2770       /system/bin/linker
,08-05 01:32:50.054  7167  7167 W art     : b6f81000-b6f83000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : b6f83000-b6f88000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-05 01:32:50.054  7167  7167 W art     : b6f88000-b6f89000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-05 01:32:50.054  7167  7167 W art     : b6f89000-b6f8a000 rw-p 00000000 00:00 0 
08-05 01:32:50.054  7167  7167 W art     : be850000-be871000 rw-p 00000000 00:00 0          [stack]
08-05 01:32:50.054  7167  7167 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-05 01:32:50.094  7167  7167 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-05 01:32:50.134  7167  7167 I Radio-JNI: register_android_hardware_Radio DONE
,08-05 01:32:50.144  7167  7167 E AffinityControl: AffinityControl: registerfunction enter,
,08-05 01:32:50.164  7167  7167 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
08-05 01:32:50.164  1452  1452 D Recents : onTaskStackChanged
,08-05 01:32:50.174  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-05 01:32:50.184   769  1716 D PackageManager: START PACKAGE DELETE: observer{172470615}
08-05 01:32:50.184   769  1716 D PackageManager: pkg{<packageName>}
08-05 01:32:50.184   769  1716 D PackageManager: user{0}
08-05 01:32:50.184   769  1716 D PackageManager: caller{2000}
08-05 01:32:50.184   769  1716 D PackageManager: flags{2}
,08-05 01:32:50.184   769  1716 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 01:32:50.184   769  1716 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-05 01:32:50.184   769  1716 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-05 01:32:50.184   769  1716 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-05 01:32:50.184   769  1716 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 01:32:50.184   769   931 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-05 01:32:50.184   769   931 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-05 01:32:50.184   769   931 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-05 01:32:50.184   769   931 D ApplicationPolicy: getApplicationUninstallationEnabled
08-05 01:32:50.184   769   931 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 01:32:50.184   769   931 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-05 01:32:50.194   769   931 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-05 01:32:50.194   769   931 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-05 01:32:50.194   769   846 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-05 01:32:50.194   769   846 I ActivityManager: Killing 7073:com.test.thalitest/u0a4 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-05 01:32:50.194   769   846 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-05 01:32:50.204   769   931 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-05 01:32:50.204   769   931 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-05 01:32:50.234   769   931 D AASAinstall: there is not AASApackages.xml file
,08-05 01:32:50.244   769  1222 D GraphicsStats: Buffer count: 4
,08-05 01:32:50.244   769  1222 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@8d93444)
,08-05 01:32:50.244   769  1334 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:50.244   769  1334 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:50.244   769  1334 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:50.504   769   931 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-05 01:32:50.534   769   931 W PackageSettings: Skipping PackageSetting{a818d57 com.example.hello/10192} due to missing metadata
,08-05 01:32:50.614   769   931 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 01:32:50.614   327   327 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-05 01:32:50.614   769   931 I art     : Starting a blocking GC Explicit
,08-05 01:32:50.734   769   931 I art     : Explicit concurrent mark sweep GC freed 91396(4MB) AllocSpace objects, 15(300KB) LOS objects, 27% free, 42MB/58MB, paused 1.346ms total 117.162ms
,08-05 01:32:50.764   769   931 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-05 01:32:50.764   769   931 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-05 01:32:50.764   769   931 D AASAinstall: there is not AASApackages.xml file
08-05 01:32:50.764   769   931 D PackageManager: result of delete: 1{172470615}
,08-05 01:32:50.774  7167  7167 I art     : System.exit called, status: 0
08-05 01:32:50.774  7167  7167 I AndroidRuntime: VM exiting with result code 0.
,08-05 01:32:50.774   769   931 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 01:32:50.774   769   931 D PackageManager: userId{-1}
08-05 01:32:50.774   769   931 D PackageManager: andCode{true}
,08-05 01:32:50.784   769   931 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-05 01:32:50.804  6341  7196 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-05 01:32:50.814  6341  7196 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-05 01:32:50.814  6341  7196 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-05 01:32:50.864   769   841 W System.err: remove failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml
,08-05 01:32:50.864   769   841 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml.bak -> /data/system/users/0/runtime-permissions.xml
,08-05 01:32:50.864   769   769 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.874   769   769 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.874   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.884  1384  1384 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-05 01:32:50.884  1384  1384 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-05 01:32:50.884   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.884   769   908 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.884   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.894  2000  2000 E SamsungIME: mOCRHelper is null
,08-05 01:32:50.904  2233  2542 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 01:32:50.904   769   908 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
08-05 01:32:50.904   769   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4960eae u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77e5d4b 4339:com.samsung.klmsagent/u0a18}
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.914  4339  4339 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 05 01:32:50 GMT+02:00 2016
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.914   769  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.914   769   769 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.924   769   841 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.924  3256  3274 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-05 01:32:50.924   769   769 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.924   769   769 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-05 01:32:50.924  3256  3274 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-05 01:32:50.934  3256  3274 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-05 01:32:50.934  3256  3274 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-05 01:32:50.934   769   769 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-05 01:32:50.934   769   769 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-05 01:32:50.934   769   769 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.934  4339  4339 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-05 01:32:50.934   769   769 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.934   769  1422 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-05 01:32:50.944  1717  1717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-05 01:32:50.944   769  1324 V NetworkStats: removeUidsLocked() for UIDs [10004]
,08-05 01:32:50.944   769  1324 V NetworkStats: performPollLocked(flags=0x3)
08-05 01:32:50.944   769  1324 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 01:32:50.944   769  1325 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-05 01:32:50.944   769  1325 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-05 01:32:50.944   769   769 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.944   769   784 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4960eae u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2a64a43 769:system/1000}
,08-05 01:32:50.944   769   769 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.944   769   769 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.954   769   769 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-05 01:32:50.954   769   769 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.954   769   769 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.954   769  1367 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/115_task.xml
,08-05 01:32:50.954  4339  4339 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-05 01:32:50.954  4339  4339 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 01:32:50.954   769   769 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.954  4339  4339 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2cfe2af in tid 4339 (msung.klmsagent)
,08-05 01:32:50.954  2439  2439 E audit_log: File locking failed. error= Bad file descriptor
,08-05 01:32:50.964  2439  2439 E audit_log: File locking failed. error= Bad file descriptor
,08-05 01:32:50.964   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.964   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.964  1706  7213 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-05 01:32:50.964   769  1300 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-05 01:32:50.964  1706  7213 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-05 01:32:50.964  1706  7213 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-05 01:32:50.974   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.974  1706  7213 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-05 01:32:50.974  1706  7213 D RegisteredComponentCache: Collect Tech packages for Knox
,08-05 01:32:50.974   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.974   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.974   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.974   769   769 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-05 01:32:50.984   769  1716 I ActivityManager: Process com.samsung.klmsagent (pid 4339)(adj 0) has died(188,700)
,08-05 01:32:50.984   769  1716 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x71b8acd8 in tid 1716 (Binder_7)
08-05 01:32:50.984   769  1716 F libc    : Unable to open connection to debuggerd: Connection refused
,08-05 01:32:50.984  2439  2439 E audit_log: File locking failed. error= Bad file descriptor
,08-05 01:32:51.024   351   351 I Zygote  : Process 4339 exited due to signal (7)
,08-05 01:32:51.424   294   548 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
