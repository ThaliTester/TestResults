#### Test 757892682551a10_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
06-30 13:52:43.949   741  3359 D SSRM:n  : SIOP:: AP = 330, PST = 392, CUR = 450, LCD = 0
,--------- beginning of main
06-30 13:52:45.109  2014  2014 E audit   : type=1400 msg=audit(1467287565.109:275): avc:  denied  { execmod } for  pid=6394 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:52:45.109  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:45.119  2014  2014 E audit   : type=1300 msg=audit(1467287565.109:275): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7b000 a1=51000 a2=5 a3=4 items=0 ppid=3508 ppcomm=adbd pid=6394 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:52:45.119  2014  2014 E audit   : type=1327 msg=audit(1467287565.109:275): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 13:52:45.119  2014  2014 E audit   : type=1320 msg=audit(1467287565.109:275): 
06-30 13:52:45.179  2014  2014 E audit   : type=1400 msg=audit(1467287565.179:276): avc:  denied  { execmod } for  pid=6394 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:52:45.179  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:45.179  2014  2014 E audit   : type=1300 msg=audit(1467287565.179:276): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3a000 a1=51000 a2=5 a3=4 items=0 ppid=3508 ppcomm=adbd pid=6394 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:52:45.179  2014  2014 E audit   : type=1327 msg=audit(1467287565.179:276): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 13:52:45.179  2014  2014 E audit   : type=1320 msg=audit(1467287565.179:276): 
06-30 13:52:45.219  2014  2014 E audit   : type=1400 msg=audit(1467287565.219:277): avc:  denied  { execmod } for  pid=6394 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 13:52:45.219  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:45.219  2014  2014 E audit   : type=1300 msg=audit(1467287565.219:277): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f38000 a1=51000 a2=5 a3=4 items=0 ppid=3508 ppcomm=adbd pid=6394 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 13:52:45.229  2014  2014 E audit   : type=1327 msg=audit(1467287565.219:277): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 13:52:45.229  2014  2014 E audit   : type=1320 msg=audit(1467287565.219:277): 
06-30 13:52:45.229  6394  6394 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:52:45.229  6394  6394 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:45.229  6394  6394 D AndroidRuntime: readGMSProperty: start
06-30 13:52:45.229  6394  6394 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:52:45.229  6394  6394 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:52:45.229  6394  6394 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:52:45.229  6394  6394 D AndroidRuntime: readGMSProperty: end
06-30 13:52:45.229  6394  6394 D AndroidRuntime: addProductProperty: start
06-30 13:52:45.239  6394  6394 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 13:52:45.239  6394  6394 W art     : af0e4000-b200a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:52:45.239  6394  6394 W art     : b200a000-b4279000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:52:45.239  6394  6394 W art     : b4279000-b427a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 13:52:45.239  6394  6394 W art     : b427a000-b42a3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 13:52:45.239  6394  6394 W art     : b42a3000-b46f1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
06-30 13:52:45.239  6394  6394 W art     : b46f1000-b46f2000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b46f2000-b46fc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
06-30 13:52:45.239  6394  6394 W art     : b46fc000-b46fd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
06-30 13:52:45.239  6394  6394 W art     : b46fd000-b46ff000 rw-p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b46ff000-b4700000 r--p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 13:52:45.239  6394  6394 W art     : b4809000-b480c000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
06-30 13:52:45.239  6394  6394 W art     : b480c000-b480d000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
06-30 13:52:45.239  6394  6394 W art     : b480d000-b480e000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
06-30 13:52:45.239  6394  6394 W art     : b480e000-b480f000 r--p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b480f000-b482f000 r--s 00000000 00:0b 8200       /dev/__properties__
06-30 13:52:45.239  6394  6394 W art     : b482f000-b5240000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
06-30 13:52:45.239  6394  6394 W art     : b5240000-b5241000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b5241000-b528a000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
06-30 13:52:45.239  6394  6394 W art     : b528a000-b528b000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
06-30 13:52:45.239  6394  6394 W art     : b528b000-b5293000 rw-p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b5293000-b5294000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.239  6394  6394 W art     : b5294000-b52c9000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
06-30 13:52:45.239  6394  6394 W art     : b52c9000-b52ca000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b52ca000-b52cb000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
06-30 13:52:45.239  6394  6394 W art     : b52cb000-b52cc000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
06-30 13:52:45.239  6394  6394 W art     : b52cc000-b5324000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
06-30 13:52:45.239  6394  6394 W art     : b5324000-b5325000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b5325000-b5326000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
06-30 13:52:45.239  6394  6394 W art     : b5326000-b5327000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
06-30 13:52:45.239  6394  6394 W art     : b5328000-b532e000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:52:45.239  6394  6394 W art     : b532e000-b532f000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:52:45.239  6394  6394 W art     : b532f000-b5330000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 13:52:45.239  6394  6394 W art     : b5330000-b5332000 rw-p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b5333000-b533d000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 13:52:45.239  6394  6394 W art     : b533d000-b5340000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 13:52:45.239  6394  6394 W art     : b5340000-b5341000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 13:52:45.239  6394  6394 W art     : b5342000-b5359000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 13:52:45.239  6394  6394 W art     : b5359000-b535a000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b535a000-b535b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 13:52:45.239  6394  6394 W art     : b535b000-b535c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 13:52:45.239  6394  6394 W art     : b535d000-b5367000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
06-30 13:52:45.239  6394  6394 W art     : b5367000-b5368000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
06-30 13:52:45.239  6394  6394 W art     : b5368000-b5369000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
06-30 13:52:45.239  6394  6394 W art     : b5369000-b536d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 13:52:45.239  6394  6394 W art     : b536d000-b536e000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 13:52:45.239  6394  6394 W art     : b536e000-b536f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 13:52:45.239  6394  6394 W art     : b536f000-b5385000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
06-30 13:52:45.239  6394  6394 W art     : b5385000-b5386000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
06-30 13:52:45.239  6394  6394 W art     : b5386000-b5387000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
06-30 13:52:45.239  6394  6394 W art     : b5387000-b5394000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
06-30 13:52:45.239  6394  6394 W art     : b5394000-b5395000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
06-30 13:52:45.239  6394  6394 W art     : b5395000-b5396000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
06-30 13:52:45.239  6394  6394 W art     : b5396000-b53f6000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
06-30 13:52:45.239  6394  6394 W art     : b53f6000-b53f9000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
06-30 13:52:45.239  6394  6394 W art     : b53f9000-b53fd000 rw-p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b53fd000-b545e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
06-30 13:52:45.239  6394  6394 W art     : b545e000-b545f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
06-30 13:52:45.239  6394  6394 W art     : b545f000-b54ae000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
06-30 13:52:45.239  6394  6394 W art     : b54ae000-b54b0000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
06-30 13:52:45.239  6394  6394 W art     : b54b0000-b54b1000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
06-30 13:52:45.239  6394  6394 W art     : b54b1000-b54b2000 rw-p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b54b2000-b54b9000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 13:52:45.239  6394  6394 W art     : b54b9000-b54ba000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 13:52:45.239  6394  6394 W art     : b54ba000-b54bb000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
06-30 13:52:45.239  6394  6394 W art     : avc_common.so
06-30 13:52:45.239  6394  6394 W art     : b54bc000-b54bf000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 13:52:45.239  6394  6394 W art     : b54bf000-b54c0000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 13:52:45.239  6394  6394 W art     : b54c0000-b54c1000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
06-30 13:52:45.239  6394  6394 W art     : enc_common.so
06-30 13:52:45.239  6394  6394 W art     : b54c2000-b54c6000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
06-30 13:52:45.239  6394  6394 W art     : b54c6000-b54c7000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b54c7000-b54c8000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
06-30 13:52:45.239  6394  6394 W art     : b54c8000-b54c9000 rw-p 00005000 b3:17 2510       /syste
06-30 13:52:45.239  6394  6394 W art     : m/lib/libpowermanager.so
06-30 13:52:45.239  6394  6394 W art     : b54ca000-b54e7000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 13:52:45.239  6394  6394 W art     : b54e7000-b54e8000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 13:52:45.239  6394  6394 W art     : b54e8000-b54e9000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 13:52:45.239  6394  6394 W art     : b54ea000-b54ef000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 13:52:45.239  6394  6394 W art     : b54ef000-b54f0000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 13:52:45.239  6394  6394 W art     : b54f0000-b54f1000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 13:52:45.239  6394  6394 W art     : b54f2000-b5523000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 13:52:45.239  6394  6394 W art     : b5523000-b5526000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 13:52:45.239  6394  6394 W art     : b5526000-b5527000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 13:52:45.239  6394  6394 W art     : b5528000-b5563000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
06-30 13:52:45.239  6394  6394 W art     : b5563000-b5564000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
06-30 13:52:45.239  6394  6394 W art     : b5564000-b5565000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
06-30 13:52:45.239  6394  6394 W art     : b5566000-b556d000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
06-30 13:52:45.239  6394  6394 W art     : b556d000-b556e000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b556e000-b556f000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
06-30 13:52:45.239  6394  6394 W art     : b556f000-b5570000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
06-30 13:52:45.239  6394  6394 W art     : b5570000-b5571000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.239  6394  6394 W art     : b5571000-b5588000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
06-30 13:52:45.239  6394  6394 W art     : b5588000-b5589000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b5589000-b558c000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
06-30 13:52:45.239  6394  6394 W art     : b558c000-b558d000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
06-30 13:52:45.239  6394  6394 W art     : b558d000-b55ac000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
06-30 13:52:45.239  6394  6394 W art     : b55ac000-b55ad000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
06-30 13:52:45.239  6394  6394 W art     : b55ad000-b55ae000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
06-30 13:52:45.239  6394  6394 W art     : b55ae000-b55ec000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 13:52:45.239  6394  6394 W art     : b55ec000-b55ed000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b55ed000-b55ef000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 13:52:45.239  6394  6394 W art     : b55ef000-b55f0000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 13:52:45.239  6394  6394 W art     : b55f1000-b55f8000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 13:52:45.239  6394  6394 W art     : b55f8000-b55f9000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 13:52:45.239  6394  6394 W art     : b55f9000-b55fa000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 13:52:45.239  6394  6394 W art     : b55fb000-b55fe000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 13:52:45.239  6394  6394 W art     : b55fe000-b55ff000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 13:52:45.239  6394  6394 W art     : b55ff000-b5600000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 13:52:45.239  6394  6394 W art     : b5600000-b5606000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:52:45.239  6394  6394 W art     : b5606000-b5607000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b5607000-b5608000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:52:45.239  6394  6394 W art     : b5608000-b5609000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 13:52:45.239  6394  6394 W art     : b5609000-b5612000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
06-30 13:52:45.239  6394  6394 W art     : b5612000-b5613000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
06-30 13:52:45.239  6394  6394 W art     : b5613000-b5614000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
06-30 13:52:45.239  6394  6394 W art     : b5614000-b56a5000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 13:52:45.239  6394  6394 W art     : b56a5000-b56a6000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b56a6000-b56b1000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 13:52:45.239  6394  6394 W art     : b56b1000-b56b2000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 13:52:45.239  6394  6394 W art     : b56b3000-b56c5000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
06-30 13:52:45.239  6394  6394 W art     : b56c5000-b56c6000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
06-30 13:52:45.239  6394  6394 W art     : b56c6000-b56c7000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
06-30 13:52:45.239  6394  6394 W art     : b56c8000-b56cd000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
06-30 13:52:45.239  6394  6394 W art     : b56cd000-b56ce000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
06-30 13:52:45.239  6394  6394 W art     : b56ce000-b56cf000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
06-30 13:52:45.239  6394  6394 W art     : b56d0000-b573d000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
06-30 13:52:45.239  6394  6394 W art     : b573d000-b573e000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b573e000-b5740000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
06-30 13:52:45.239  6394  6394 W art     : b5740000-b5741000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
06-30 13:52:45.239  6394  6394 W art     : b5741000-b5742000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.239  6394  6394 W art     : b5742000-b5749000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:52:45.239  6394  6394 W art     : b5749000-b574a000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:52:45.239  6394  6394 W art     : b574a000-b574b000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 13:52:45.239  6394  6394 W art     : b574c000-b57cc000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 13:52:45.239  6394  6394 W art     : b57cc000-b57cd000 ---p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b57cd000-b57ce000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 13:52:45.239  6394  6394 W art     : b57ce000-b57cf000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 13:52:45.239  6394  6394 W art     : b57cf000-b57e6000 rw-p 00000000 00:00 0 
06-30 13:52:45.239  6394  6394 W art     : b57e6000-b581d000 r-xp 00000000 b3:17 3244       /system/vendor/l
06-30 13:52:45.249  6394  6394 W art     : ib/libqc-opt.so
06-30 13:52:45.249  6394  6394 W art     : b581d000-b581e000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 13:52:45.249  6394  6394 W art     : b581e000-b581f000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 13:52:45.249  6394  6394 W art     : b581f000-b583b000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 13:52:45.249  6394  6394 W art     : b583b000-b583c000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 13:52:45.249  6394  6394 W art     : b583c000-b583d000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 13:52:45.249  6394  6394 W art     : b583e000-b589f000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 13:52:45.249  6394  6394 W art     : b589f000-b58a1000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 13:52:45.249  6394  6394 W art     : b58a1000-b58a2000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 13:52:45.249  6394  6394 W art     : b58a3000-b58ca000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
06-30 13:52:45.249  6394  6394 W art     : b58ca000-b58cb000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b58cb000-b58cc000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
06-30 13:52:45.249  6394  6394 W art     : b58cc000-b58cd000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
06-30 13:52:45.249  6394  6394 W art     : b58ce000-b58d6000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 13:52:45.249  6394  6394 W art     : b58d6000-b58d8000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 13:52:45.249  6394  6394 W art     : b58d8000-b58d9000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 13:52:45.249  6394  6394 W art     : b58da000-b58dd000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
06-30 13:52:45.249  6394  6394 W art     : b58dd000-b58de000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
06-30 13:52:45.249  6394  6394 W art     : b58de000-b58df000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
06-30 13:52:45.249  6394  6394 W art     : b58df000-b58e3000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
06-30 13:52:45.249  6394  6394 W art     : b58e3000-b58e4000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b58e4000-b58e5000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
06-30 13:52:45.249  6394  6394 W art     : b58e5000-b58e6000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
06-30 13:52:45.249  6394  6394 W art     : b58e6000-b58f6000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
06-30 13:52:45.249  6394  6394 W art     : b58f6000-b58f7000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
06-30 13:52:45.249  6394  6394 W art     : b58f7000-b58f8000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
06-30 13:52:45.249  6394  6394 W art     : b58f8000-b593e000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b593e000-b5947000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
06-30 13:52:45.249  6394  6394 W art     : b5947000-b5948000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
06-30 13:52:45.249  6394  6394 W art     : b5948000-b5949000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
06-30 13:52:45.249  6394  6394 W art     : b594a000-b594f000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
06-30 13:52:45.249  6394  6394 W art     : b594f000-b5950000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
06-30 13:52:45.249  6394  6394 W art     : b5950000-b5951000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
06-30 13:52:45.249  6394  6394 W art     : b5951000-b5954000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 13:52:45.249  6394  6394 W art     : b5954000-b5955000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5955000-b5956000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 13:52:45.249  6394  6394 W art     : b5956000-b5957000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 13:52:45.249  6394  6394 W art     : b5958000-b5970000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:52:45.249  6394  6394 W art     : b5970000-b5971000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5971000-b5972000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:52:45.249  6394  6394 W art     : b5972000-b5973000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 13:52:45.249  6394  6394 W art     : b5974000-b5b0e000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
06-30 13:52:45.249  6394  6394 W art     : b5b0e000-b5b0f000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5b0f000-b5b1c000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
06-30 13:52:45.249  6394  6394 W art     : b5b1c000-b5b1d000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
06-30 13:52:45.249  6394  6394 W art     : b5b1d000-b5b21000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
06-30 13:52:45.249  6394  6394 W art     : b5b21000-b5b22000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5b22000-b5b23000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
06-30 13:52:45.249  6394  6394 W art     : b5b23000-b5b24000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
06-30 13:52:45.249  6394  6394 W art     : b5b24000-b5b37000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
06-30 13:52:45.249  6394  6394 W art     : b5b37000-b5b38000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
06-30 13:52:45.249  6394  6394 W art     : b5b38000-b5b39000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
06-30 13:52:45.249  6394  6394 W art     : b5b39000-b5b3a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:45.249  6394  6394 W art     : b5b3a000-b5b85000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
06-30 13:52:45.249  6394  6394 W art     : b5b85000-b5b86000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
06-30 13:52:45.249  6394  6394 W art     : b5b86000-b5b87000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
06-30 13:52:45.249  6394  6394 W art     : b5b87000-b5b89000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5b8a000-b5b9b000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 13:52:45.249  6394  6394 W art     : b5b9b000-b5b9c000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5b9c000-b5b9d000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 13:52:45.249  6394  6394 W art     : b5b9d000-b5b9e000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 13:52:45.249  6394  6394 W art     : b5b9f000-b5ba9000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
06-30 13:52:45.249  6394  6394 W art     : b5ba9000-b5bab000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
06-30 13:52:45.249  6394  6394 W art     : b5bab000-b5bac000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
06-30 13:52:45.249  6394  6394 W art     : b5bac000-b5bc5000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
06-30 13:52:45.249  6394  6394 W art     : b5bc5000-b5bc6000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
06-30 13:52:45.249  6394  6394 W art     : b5bc6000-b5bc9000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
06-30 13:52:45.249  6394  6394 W art     : b5bc9000-b5bcd000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5bcd000-b5c41000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
06-30 13:52:45.249  6394  6394 W art     : b5c41000-b5c42000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5c42000-b5c45000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
06-30 13:52:45.249  6394  6394 W art     : b5c45000-b5c46000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
06-30 13:52:45.249  6394  6394 W art     : b5c46000-b5c47000 r--p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5c47000-b5c4a000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
06-30 13:52:45.249  6394  6394 W art     : b5c4a000-b5c4b000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
06-30 13:52:45.249  6394  6394 W art     : b5c4b000-b5c4c000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
06-30 13:52:45.249  6394  6394 W art     : b5c4c000-b5c4d000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b5c4d000-b5c52000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 13:52:45.249  6394  6394 W art     : b5c52000-b5c53000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 13:52:45.249  6394  6394 W art     : b5c53000-b5c54000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 13:52:45.249  6394  6394 W art     : b5c54000-b5c55000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b5c55000-b5c58000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 13:52:45.249  6394  6394 W art     : b5c58000-b5c59000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 13:52:45.249  6394  6394 W art     : b5c59000-b5c5a000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 13:52:45.249  6394  6394 W art     : b5c5a000-b5c5b000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b5c5b000-b5c5f000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
06-30 13:52:45.249  6394  6394 W art     : b5c5f000-b5c60000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
06-30 13:52:45.249  6394  6394 W art     : b5c60000-b5c61000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
06-30 13:52:45.249  6394  6394 W art     : b5c61000-b5c62000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:45.249  6394  6394 W art     : b5c62000-b5c66000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 13:52:45.249  6394  6394 W art     : b5c66000-b5c67000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 13:52:45.249  6394  6394 W art     : b5c67000-b5c68000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 13:52:45.249  6394  6394 W art     : b5c68000-b5c69000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b5c69000-b5c77000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 13:52:45.249  6394  6394 W art     : b5c77000-b5c78000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b5c78000-b5c79000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 13:52:45.249  6394  6394 W art     : b5c79000-b5c7a000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 13:52:45.249  6394  6394 W art     : b5c7a000-b5c84000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 13:52:45.249  6394  6394 W art     : b5c84000-b5c87000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 13:52:45.249  6394  6394 W art     : b5c87000-b5c88000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 13:52:45.249  6394  6394 W art     : b5c88000-b5c89000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b5c89000-b5c93000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
06-30 13:52:45.249  6394  6394 W art     : b5c93000-b5c96000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
06-30 13:52:45.249  6394  6394 W art     : b5c96000-b5c97000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
06-30 13:52:45.249  6394  6394 W art     : b5c97000-b5c9b000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
06-30 13:52:45.249  6394  6394 W art     : b5c9b000-b5c9c000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
06-30 13:52:45.249  6394  6394 W art     : b5c9c000-b5c9d000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
06-30 13:52:45.249  6394  6394 W art     : b5c9d000-b5c9e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b5c9e000-b5cab000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:52:45.249  6394  6394 W art     : b5cab000-b5cad000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:52:45.249  6394  6394 W art     : b5cad000-b5cae000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 13:52:45.249  6394  6394 W art     : b5cae000-b60c0000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
06-30 13:52:45.249  6394  6394 W art     : b60c0000-b60c1000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b60c1000-b60ca000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
06-30 13:52:45.249  6394  6394 W art     : b60ca000-b60ce000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
06-30 13:52:45.249  6394  6394 W art     : b60ce000-b60cf000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b60cf000-b60d6000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:52:45.249  6394  6394 W art     : b60d6000-b60d7000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:52:45.249  6394  6394 W art     : b60d7000-b60d8000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 13:52:45.249  6394  6394 W art     : b60d8000-b60d9000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b60d9000-b60f4000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 13:52:45.249  6394  6394 W art     : b60f4000-b60f5000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 13:52:45.249  6394  6394 W art     : b60f5000-b60f6000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 13:52:45.249  6394  6394 W art     : b60f6000-b60f7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b60f7000-b6143000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 13:52:45.249  6394  6394 W art     : b6143000-b6144000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6144000-b6145000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 13:52:45.249  6394  6394 W art     : b6145000-b6146000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 13:52:45.249  6394  6394 W art     : b6146000-b6147000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6147000-b614b000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
06-30 13:52:45.249  6394  6394 W art     : b614b000-b614c000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b614c000-b614d000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
06-30 13:52:45.249  6394  6394 W art     : b614d000-b614e000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
06-30 13:52:45.249  6394  6394 W art     : b614e000-b6186000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
06-30 13:52:45.249  6394  6394 W art     : b6186000-b6187000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
06-30 13:52:45.249  6394  6394 W art     : b6187000-b6188000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
06-30 13:52:45.249  6394  6394 W art     : b6188000-b6189000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6189000-b6227000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
06-30 13:52:45.249  6394  6394 W art     : b6227000-b6228000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6228000-b6246000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
06-30 13:52:45.249  6394  6394 W art     : b6246000-b6247000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
06-30 13:52:45.249  6394  6394 W art     : b6247000-b63ba000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
06-30 13:52:45.249  6394  6394 W art     : b63ba000-b63c5000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
06-30 13:52:45.249  6394  6394 W art     : b63c5000-b63c6000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
06-30 13:52:45.249  6394  6394 W art     : b63c6000-b64dd000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:52:45.249  6394  6394 W art     : b64dd000-b64e8000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:52:45.249  6394  6394 W art     : b64e8000-b64e9000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 13:52:45.249  6394  6394 W art     : b64e9000-b64ed000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b64ed000-b6511000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
06-30 13:52:45.249  6394  6394 W art     : b6511000-b6513000 r--p 00023000 b3:17 400        /system/lib/libssl.so
06-30 13:52:45.249  6394  6394 W art     : b6513000-b6514000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
06-30 13:52:45.249  6394  6394 W art     : b6514000-b65ba000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
06-30 13:52:45.249  6394  6394 W art     : b65ba000-b65c7000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
06-30 13:52:45.249  6394  6394 W art     : b65c7000-b65c8000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
06-30 13:52:45.249  6394  6394 W art     : b65c8000-b65c9000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b65c9000-b661c000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
06-30 13:52:45.249  6394  6394 W art     : b661c000-b661d000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b661d000-b661e000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
06-30 13:52:45.249  6394  6394 W art     : b661e000-b661f000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
06-30 13:52:45.249  6394  6394 W art     : b661f000-b6624000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6624000-b6636000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
06-30 13:52:45.249  6394  6394 W art     : b6636000-b6637000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6637000-b6638000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
06-30 13:52:45.249  6394  6394 W art     : b6638000-b6639000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
06-30 13:52:45.249  6394  6394 W art     : b6639000-b6640000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 13:52:45.249  6394  6394 W art     : b6640000-b6641000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 13:52:45.249  6394  6394 W art     : b6641000-b6642000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 13:52:45.249  6394  6394 W art     : b6642000-b6643000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6643000-b6646000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
06-30 13:52:45.249  6394  6394 W art     : b6646000-b6647000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
06-30 13:52:45.249  6394  6394 W art     : b6647000-b6648000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
06-30 13:52:45.249  6394  6394 W art     : b6648000-b664c000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
06-30 13:52:45.249  6394  6394 W art     : b664c000-b664d000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
06-30 13:52:45.249  6394  6394 W art     : b664d000-b664e000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
06-30 13:52:45.249  6394  6394 W art     : b664e000-b665c000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
06-30 13:52:45.249  6394  6394 W art     : b665c000-b665d000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b665d000-b665e000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
06-30 13:52:45.249  6394  6394 W art     : b665e000-b665f000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
06-30 13:52:45.249  6394  6394 W art     : b665f000-b6668000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 13:52:45.249  6394  6394 W art     : b6668000-b6669000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 13:52:45.249  6394  6394 W art     : b6669000-b666a000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 13:52:45.249  6394  6394 W art     : b666a000-b66d0000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
06-30 13:52:45.249  6394  6394 W art     : b66d0000-b66d1000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b66d1000-b66d3000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
06-30 13:52:45.249  6394  6394 W art     : b66d3000-b66dc000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
06-30 13:52:45.249  6394  6394 W art     : b66dc000-b66df000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b66df000-b6776000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 13:52:45.249  6394  6394 W art     : b6776000-b6778000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 13:52:45.249  6394  6394 W art     : b6778000-b6779000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 13:52:45.249  6394  6394 W art     : b6779000-b677a000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b677a000-b6a9b000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
06-30 13:52:45.249  6394  6394 W art     : b6a9b000-b6a9c000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6a9c000-b6ab7000 r--p 00321000 b3:17 377        /system/lib/libskia.so
06-30 13:52:45.249  6394  6394 W art     : b6ab7000-b6abb000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
06-30 13:52:45.249  6394  6394 W art     : b6abb000-b6ac0000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6ac0000-b6ac8000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 13:52:45.249  6394  6394 W art     : b6ac8000-b6ac9000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 13:52:45.249  6394  6394 W art     : b6ac9000-b6aca000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 13:52:45.249  6394  6394 W art     : b6aca000-b6af8000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:52:45.249  6394  6394 W art     : b6af8000-b6af9000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6af9000-b6b00000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:52:45.249  6394  6394 W art     : b6b00000-b6b01000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 13:52:45.249  6394  6394 W art     : b6b01000-b6b47000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:52:45.249  6394  6394 W art     : b6b47000-b6b48000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6b48000-b6b4b000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:52:45.249  6394  6394 W art     : b6b4b000-b6b4c000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 13:52:45.249  6394  6394 W art     : b6b4c000-b6b67000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
06-30 13:52:45.249  6394  6394 W art     : b6b67000-b6b6b000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
06-30 13:52:45.249  6394  6394 W art     : b6b6b000-b6b6c000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
06-30 13:52:45.249  6394  6394 W art     : b6b6c000-b6bb9000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
06-30 13:52:45.249  6394  6394 W art     : b6bb9000-b6bba000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6bba000-b6bc6000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
06-30 13:52:45.249  6394  6394 W art     : b6bc6000-b6bc7000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
06-30 13:52:45.249  6394  6394 W art     : b6bc7000-b6bd4000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
06-30 13:52:45.249  6394  6394 W art     : b6bd4000-b6bd5000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6bd5000-b6bd6000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
06-30 13:52:45.249  6394  6394 W art     : b6bd6000-b6bd7000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
06-30 13:52:45.249  6394  6394 W art     : b6bd7000-b6bdf000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
06-30 13:52:45.249  6394  6394 W art     : b6bdf000-b6be0000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6be0000-b6be1000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
06-30 13:52:45.249  6394  6394 W art     : b6be1000-b6be2000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
06-30 13:52:45.249  6394  6394 W art     : b6be2000-b6be9000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:52:45.249  6394  6394 W art     : b6be9000-b6bea000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:52:45.249  6394  6394 W art     : b6bea000-b6beb000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 13:52:45.249  6394  6394 W art     : b6beb000-b6bff000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
06-30 13:52:45.249  6394  6394 W art     : b6bff000-b6c01000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
06-30 13:52:45.249  6394  6394 W art     : b6c01000-b6c02000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
06-30 13:52:45.249  6394  6394 W art     : b6c02000-b6c2a000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
06-30 13:52:45.249  6394  6394 W art     : b6c2a000-b6c2c000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
06-30 13:52:45.249  6394  6394 W art     : b6c2c000-b6c2d000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
06-30 13:52:45.249  6394  6394 W art     : b6c2d000-b6c30000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
06-30 13:52:45.249  6394  6394 W art     : b6c30000-b6c31000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
06-30 13:52:45.249  6394  6394 W art     : b6c31000-b6c32000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
06-30 13:52:45.249  6394  6394 W art     : b6c32000-b6c3b000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:52:45.249  6394  6394 W art     : b6c3b000-b6c3c000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:52:45.249  6394  6394 W art     : b6c3c000-b6c3d000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 13:52:45.249  6394  6394 W art     : b6c3d000-b6c5d000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 13:52:45.249  6394  6394 W art     : b6c5d000-b6c5e000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 13:52:45.249  6394  6394 W art     : b6c5e000-b6c5f000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 13:52:45.249  6394  6394 W art     : b6c5f000-b6cd2000 r-xp 00000000 b3:17 860        /system/lib/libc.so
06-30 13:52:45.249  6394  6394 W art     : b6cd2000-b6cd6000 r--p 00072000 b3:17 860        /system/lib/libc.so
06-30 13:52:45.249  6394  6394 W art     : b6cd6000-b6cd9000 rw-p 00076000 b3:17 860        /system/lib/libc.so
06-30 13:52:45.249  6394  6394 W art     : b6cd9000-b6ce3000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6ce3000-b6d6b000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 13:52:45.249  6394  6394 W art     : b6d6b000-b6d6c000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6d6c000-b6d70000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 13:52:45.249  6394  6394 W art     : b6d70000-b6d71000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 13:52:45.249  6394  6394 W art     : b6d71000-b6d72000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6d72000-b6d9b000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:52:45.249  6394  6394 W art     : b6d9b000-b6d9c000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6d9c000-b6d9f000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:52:45.249  6394  6394 W art     : b6d9f000-b6da0000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 13:52:45.249  6394  6394 W art     : b6da0000-b6e7a000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 13:52:45.249  6394  6394 W art     : b6e7a000-b6e81000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 13:52:45.249  6394  6394 W art     : b6e81000-b6e89000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 13:52:45.249  6394  6394 W art     : b6e89000-b6e8a000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6e8a000-b6e8b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:45.249  6394  6394 W art     : b6e8b000-b6e8c000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 13:52:45.249  6394  6394 W art     : b6e8c000-b6e8d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6e8d000-b6e90000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6e90000-b6eb5000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
06-30 13:52:45.249  6394  6394 W art     : b6eb5000-b6eb6000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6eb6000-b6ebd000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
06-30 13:52:45.249  6394  6394 W art     : b6ebd000-b6ebe000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
06-30 13:52:45.249  6394  6394 W art     : b6ebe000-b6ec5000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 13:52:45.249  6394  6394 W art     : b6ec5000-b6ec6000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 13:52:45.249  6394  6394 W art     : b6ec6000-b6ec7000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 13:52:45.249  6394  6394 W art     : b6ec7000-b6ec8000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6ec8000-b6ee0000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
06-30 13:52:45.249  6394  6394 W art     : b6ee0000-b6ee1000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6ee1000-b6ee2000 r--p 00018000 b3:17 918        /system/lib/libutils.so
06-30 13:52:45.249  6394  6394 W art     : b6ee2000-b6ee3000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
06-30 13:52:45.249  6394  6394 W art     : b6ee3000-b6ef1000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
06-30 13:52:45.249  6394  6394 W art     : b6ef1000-b6ef2000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6ef2000-b6ef3000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
06-30 13:52:45.249  6394  6394 W art     : b6ef3000-b6ef4000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
06-30 13:52:45.249  6394  6394 W art     : b6ef4000-b6ef5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:45.249  6394  6394 W art     : b6ef5000-b6ef7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6ef7000-b6ef8000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6ef8000-b6ef9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 13:52:45.249  6394  6394 W art     : b6ef9000-b6efa000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 13:52:45.249  6394  6394 W art     : b6efa000-b6efb000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 13:52:45.249  6394  6394 W art     : b6efb000-b6f1b000 r--s 00000000 00:0b 8200       /dev/__properties__
06-30 13:52:45.249  6394  6394 W art     : b6f1b000-b6f1c000 r--p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6f1c000-b6f1d000 ---p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6f1d000-b6f1f000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 13:52:45.249  6394  6394 W art     : b6f1f000-b6f20000 r-xp 00000000 00:00 0          [sigpage]
06-30 13:52:45.249  6394  6394 W art     : b6f20000-b6f3b000 r-xp 00000000 b3:17 2770       /system/bin/linker
06-30 13:52:45.249  6394  6394 W art     : b6f3b000-b6f3c000 r--p 0001a000 b3:17 2770       /system/bin/linker
06-30 13:52:45.249  6394  6394 W art     : b6f3c000-b6f3e000 rw-p 0001b000 b3:17 2770       /system/bin/linker
06-30 13:52:45.249  6394  6394 W art     : b6f3e000-b6f40000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : b6f40000-b6f45000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 13:52:45.249  6394  6394 W art     : b6f45000-b6f46000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 13:52:45.249  6394  6394 W art     : b6f46000-b6f47000 rw-p 00000000 00:00 0 
06-30 13:52:45.249  6394  6394 W art     : bee0a000-bee2b000 rw-p 00000000 00:00 0          [stack]
06-30 13:52:45.249  6394  6394 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 13:52:45.309  6394  6394 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:52:45.359  6394  6394 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:52:45.369  6394  6394 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:52:45.399  6394  6394 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:52:45.409   741  2064 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
06-30 13:52:45.419   741  2064 D ActivityManager: mDVFSHelper.acquire()
06-30 13:52:45.429   741  2064 V WindowManager: addAppToken: AppWindowToken{c582593 token=Token{6f76a82 ActivityRecord{ecc01cd u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
06-30 13:52:45.429   741   883 D SecWifiDisplayUtil: Metadata value : none
06-30 13:52:45.429   741   883 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a1cb40b V.E...... R.....ID 0,0-0,0}
06-30 13:52:45.439   741   883 D ISSUE_DEBUG: InputChannelName : 2e68d01 Starting com.test.thalitest
06-30 13:52:45.449  6409  6409 E Zygote  : v2
06-30 13:52:45.449  6409  6409 I libpersona: KNOX_SDCARD checking this for 10004
06-30 13:52:45.449  6409  6409 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:45.449   741  2064 D InputDispatcher: Focused application set to: xxxx
06-30 13:52:45.449   741  2064 I ActivityManager: Start proc 6409:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 13:52:45.449   741  2064 D InputDispatcher: Focus left window: 3426
06-30 13:52:45.449   741   836 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{36b7199 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 13:52:45.449   741  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 13:52:45.449  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 13:52:45.459  6394  6394 D AndroidRuntime: Shutting down VM
06-30 13:52:45.459  6409  6409 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:52:45.459  6409  6409 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:45.459  6409  6409 E Zygote  : accessInfo : 0
06-30 13:52:45.459  6409  6409 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 13:52:45.459   295   295 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
06-30 13:52:45.469   741   883 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:741 uid:1000
06-30 13:52:45.469   741   883 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:45.469   741   883 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:741 uid:1000
06-30 13:52:45.469   741   883 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:45.469   741   883 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 13:52:45.499  6409  6409 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:45.499  6409  6409 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:45.499   741  1406 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 13:52:45.499   741  1406 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 13:52:45.509   741   836 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2e68d01 u0 d0 Starting com.test.thalitest}
06-30 13:52:45.509  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 13:52:45.509   741   883 V WindowStateAnimator: Finishing drawing window Window{2e68d01 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 13:52:45.509   741  1406 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 13:52:45.519   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbee3f364
06-30 13:52:45.529   741   834 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 13:52:45.539  1705  1864 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
06-30 13:52:45.539  1705  1705 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
06-30 13:52:45.539   295  5120 D libEGL  : eglTerminate EGLDisplay = 0xb45ff64c
06-30 13:52:45.549   295  1355 I SurfaceFlinger: id=13 Removed VSBConnecti (7/11)
06-30 13:52:45.549   295   367 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
06-30 13:52:45.549   295   367 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
06-30 13:52:45.549   295   367 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
06-30 13:52:45.559   295  5120 I SurfaceFlinger: id=14 Removed VSBConnecti (5/10)
06-30 13:52:45.559   295  1355 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/10)
06-30 13:52:45.569   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbee3f3a4
06-30 13:52:45.569   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbee3f3a4
06-30 13:52:45.579   741  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
06-30 13:52:45.589   295  5120 I SurfaceFlinger: id=7 Removed Mauncher (4/9)
06-30 13:52:45.589  3426  3426 V ActivityThread: updateVisibility : ActivityRecord{45075fd token=android.os.BinderProxy@8b6a7af {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 13:52:45.589   295   367 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
06-30 13:52:45.589  6409  6409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 13:52:45.589   741  3359 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 13:52:45.599  1705  1705 V ActivityThread: updateVisibility : ActivityRecord{8492bf9 token=android.os.BinderProxy@6fd4c29 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 13:52:45.599   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbee3f3a4
06-30 13:52:45.599  1705  1705 D Launcher: onTrimMemory. Level: 20
06-30 13:52:45.599  2341  2353 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
06-30 13:52:45.629  6409  6409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 13:52:45.629  6409  6409 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 13:52:45.649  6409  6409 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
06-30 13:52:45.679   741   752 I art     : Background partial concurrent mark sweep GC freed 16150(1166KB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 42MB/58MB, paused 1.681ms total 117.844ms
06-30 13:52:45.679  6409  6409 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 13:52:45.689  6409  6409 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 13:52:45.699  6409  6409 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 7213-7217)
06-30 13:52:45.699  6409  6409 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 13:52:45.719  6409  6409 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aff1979}
06-30 13:52:45.719  6409  6409 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 13:52:45.719  6409  6409 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:45.729  6409  6434 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
06-30 13:52:45.729  6409  6409 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 13:52:45.749  6409  6435 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
06-30 13:52:45.759  6409  6409 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 13:52:45.759  6409  6409 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 13:52:45.759  6409  6409 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 13:52:45.759  6409  6409 I Adreno-EGL: Local Branch: ss
06-30 13:52:45.759  6409  6409 I Adreno-EGL: Remote Branch: 
06-30 13:52:45.759  6409  6409 I Adreno-EGL: Local Patches: 
06-30 13:52:45.759  6409  6409 I Adreno-EGL: Reconstruct Branch: 
06-30 13:52:45.759  6409  6409 D libEGL  : eglInitialize EGLDisplay = 0xbea3fdac
06-30 13:52:45.789   741  1406 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
06-30 13:52:45.789   741  1406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
06-30 13:52:45.849  6409  6409 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
06-30 13:52:45.859  6409  6409 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 13:52:45.859  6409  6409 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
06-30 13:52:45.859  6409  6409 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
06-30 13:52:45.859  6409  6409 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
06-30 13:52:45.879  6409  6409 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
06-30 13:52:45.879  6409  6409 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 13:52:45.979  6409  6409 D SecWifiDisplayUtil: Metadata value : none
06-30 13:52:45.979  6409  6409 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4c7ccff I.E...... R.....ID 0,0-0,0}
06-30 13:52:45.979  6409  6460 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 13:52:45.989   741  1720 D ISSUE_DEBUG: InputChannelName : 1dc3b3a com.test.thalitest/com.test.thalitest.MainActivity
06-30 13:52:45.989   741  1715 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 13:52:45.989   741  1715 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:45.989   741   741 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:45.989   741   741 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 13:52:45.999  6409  6409 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6409
06-30 13:52:46.009   741  1487 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6409 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:52:46.019  6409  6409 D SecWifiDisplayUtil: Metadata value : none
06-30 13:52:46.019  6409  6434 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
06-30 13:52:46.019   295   295 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
06-30 13:52:46.029   741  2065 D InputDispatcher: Focus entered window: 6409
06-30 13:52:46.029   741   883 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:741 uid:1000
06-30 13:52:46.029   741   883 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:46.029   741   883 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:741 uid:1000
06-30 13:52:46.029   741   883 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:46.029  6409  6460 D libEGL  : eglInitialize EGLDisplay = 0x9c97f7c4
06-30 13:52:46.029  6409  6460 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:52:46.079  6409  6409 V ActivityThread: updateVisibility : ActivityRecord{44d27b8 token=android.os.BinderProxy@ec09c1e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 13:52:46.079  6409  6409 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 13:52:46.079  6409  6409 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 13:52:46.079   741  1715 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 13:52:46.089  6409  6409 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
06-30 13:52:46.109   741  2065 V WindowStateAnimator: Finishing drawing window Window{1dc3b3a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
06-30 13:52:46.109  6409  6409 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 13:52:46.109   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbee3f364
06-30 13:52:46.109  6409  6409 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ec09c1e time:157627
06-30 13:52:46.119   741   883 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:46.119   741   883 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +539ms (total +692ms)
06-30 13:52:46.119   741   741 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:46.119   741   741 I KnoxTimeoutHandler: SD activityfalse
06-30 13:52:46.119   741   883 D ActivityManager: mDVFSHelper.release()
06-30 13:52:46.119   741   883 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ecc01cd u0 com.test.thalitest/.MainActivity t64} time:157637
06-30 13:52:46.129   741   883 D ViewRootImpl: #3 mView = null
06-30 13:52:46.129   295  5120 I SurfaceFlinger: id=15 Removed uhalitest (7/9)
06-30 13:52:46.129   295  5120 I SurfaceFlinger: id=15 Removed uhalitest (-2/9)
06-30 13:52:46.129   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbee3f3a4
06-30 13:52:46.139  6409  6471 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:46.139  6409  6471 D libEGL  : eglInitialize EGLDisplay = 0x9b33f3ec
06-30 13:52:46.169  6409  6409 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6409
06-30 13:52:46.299  6409  6409 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 13:52:46.399  6409  6476 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1697908432
06-30 13:52:46.399  6409  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:46.399  6409  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:46.399  6409  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:46.399  6409  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:46.399  6409  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:46.399  6409  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da48ce added. We now have 1 listener(s)
06-30 13:52:46.409  6409  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
06-30 13:52:46.409  6409  6476 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
06-30 13:52:46.409  6409  6476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:46.409  6409  6476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:46.409  6409  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@566e985 added. We now have 1 listener(s)
06-30 13:52:46.409  6409  6476 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:52:46.419  6409  6476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:46.419  6409  6476 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 13:52:46.419  6409  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:46.419  6409  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 13:52:46.419  6409  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:46.419  6409  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 13:52:46.419  6409  6476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:52:46.419  6409  6476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
06-30 13:52:46.419  6409  6476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:46.419  6409  6476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:46.419  6409  6476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:46.419  6409  6476 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:46.419  6409  6476 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:52:46.439  6409  6409 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-30 13:52:46.579   741  3362 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,06-30 13:52:46.989  1451  1451 D Recents : onTaskStackChanged
,06-30 13:52:46.999  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,06-30 13:52:47.249  6409  6477 W jxcore-log: Initializing JXcore engine
06-30 13:52:47.249  6409  6477 W jxcore-log: JXcore engine is ready
,06-30 13:52:47.289  2014  2014 E audit   : type=1400 msg=audit(1467287567.289:278): avc:  denied  { ioctl } for  pid=6477 comm="Thread-903" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 13:52:47.289  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,06-30 13:52:47.299  2014  2014 E audit   : type=1300 msg=audit(1467287567.289:278): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a47f3c8 items=0 ppid=356 ppcomm=main pid=6477 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-903" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 13:52:47.299  2014  2014 E audit   : type=1327 msg=audit(1467287567.289:278): proctitle="com.test.thalitest"
06-30 13:52:47.299  2014  2014 E audit   : type=1320 msg=audit(1467287567.289:278): 
06-30 13:52:47.299  2014  2014 E audit   : type=1400 msg=audit(1467287567.289:279): avc:  denied  { ioctl } for  pid=6477 comm="Thread-903" path="socket:[39522]" dev="sockfs" ino=39522 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 13:52:47.299  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:47.299  2014  2014 E audit   : type=1300 msg=audit(1467287567.289:279): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=2 a3=9a47f3c8 items=0 ppid=356 ppcomm=main pid=6477 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-903" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 13:52:47.299  2014  2014 E audit   : type=1327 msg=audit(1467287567.289:279): proctitle="com.test.thalitest"
06-30 13:52:47.299  2014  2014 E audit   : type=1320 msg=audit(1467287567.289:279): 
,06-30 13:52:47.299  6409  6477 W jxcore-log: Starting JXcore engine
,06-30 13:52:47.349   741  1717 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:47.349   741  1717 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 13:52:47.359   741  1717 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:52:47.359   741  1717 D BatteryService: stay LED for fully charged
06-30 13:52:47.359   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:47.359   741   741 I MotionRecognitionService: Plugged
,06-30 13:52:47.359   741   741 D MotionRecognitionService:   cableConnection= 1
06-30 13:52:47.359   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:52:47.359   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:47.359  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:52:47.359  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:47.359  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:52:47.359  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:52:47.359  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:52:47.379  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:47.379  6409  6477 W jxcore-log: Platform android
06-30 13:52:47.379  6409  6477 W jxcore-log: 
06-30 13:52:47.379  6409  6477 W jxcore-log: Process ARCH arm
06-30 13:52:47.379  6409  6477 W jxcore-log: 
,06-30 13:52:47.579  6409  6477 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:47.579  6409  6477 I jxcore-log: 
,06-30 13:52:47.579  6409  6477 W jxcore-log: JXcore engine is started
,06-30 13:52:47.589  6409  6476 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:47.599   741  2065 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package null
,06-30 13:52:47.609   741  2065 D ActivityManager: mDVFSHelper.acquire()
,06-30 13:52:47.609   741  2065 V WindowManager: addAppToken: AppWindowToken{59e6ea token=Token{2028ed5 ActivityRecord{e84878c u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}}} to stack=1 task=64 at 1
,06-30 13:52:47.629  6481  6481 E Zygote  : v2
06-30 13:52:47.629  6481  6481 I libpersona: KNOX_SDCARD checking this for 10129
06-30 13:52:47.629  6481  6481 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:47.629  6481  6481 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 13:52:47.629  6481  6481 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:52:47.629   741  2065 I ActivityManager: Start proc 6481:com.android.packageinstaller/u0a129 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 13:52:47.629   741  2065 D InputDispatcher: Focused application set to: xxxx
,06-30 13:52:47.629   741  2065 D InputDispatcher: Focus left window: 6409
,06-30 13:52:47.629  6481  6481 E Zygote  : accessInfo : 0
,06-30 13:52:47.629  6481  6481 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-30 13:52:47.629   741   883 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:741 uid:1000
06-30 13:52:47.629   741   883 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:47.629   741   883 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:741 uid:1000
06-30 13:52:47.629   741   883 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:47.629  6409  6476 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 13:52:47.649  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:47.649  6481  6481 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:47.659   741  1407 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 13:52:47.659   741   834 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 13:52:47.969   741  1407 I WindowManager: Screenshot max retries 4 of Token{2028ed5 ActivityRecord{e84878c u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}} appWin=Window{1dc3b3a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
06-30 13:52:47.989  6481  6481 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:47.999  6481  6481 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
06-30 13:52:48.029  6481  6481 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.039  6481  6481 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.079  6481  6481 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.109  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.119  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.129  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.129  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.129  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.129  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.199  6481  6481 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
06-30 13:52:48.209  6481  6481 D SecWifiDisplayUtil: Metadata value : none
06-30 13:52:48.209  6481  6481 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{54babe1 I.E...... R.....I. 0,0-0,0}
06-30 13:52:48.219  6481  6500 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 13:52:48.219   741  1487 D ISSUE_DEBUG: InputChannelName : 3326cb7 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
06-30 13:52:48.229   741  2064 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 13:52:48.229   741  2064 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:48.229   741   741 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:48.229   741   741 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 13:52:48.229   741   741 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
06-30 13:52:48.249   295   295 I SurfaceFlinger: id=17 createSurf (145x145),1 flag=4, HrantPermis
06-30 13:52:48.249   741   836 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3326cb7 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
06-30 13:52:48.259  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
06-30 13:52:48.259   741  1720 D InputDispatcher: Focus entered window: 6481
06-30 13:52:48.269   741   883 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:741 uid:1000
06-30 13:52:48.269   741   883 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:48.269   741   883 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:741 uid:1000
06-30 13:52:48.269   741   883 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:48.269  6481  6500 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 13:52:48.269  6481  6500 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 13:52:48.269  6481  6500 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 13:52:48.269  6481  6500 I Adreno-EGL: Local Branch: ss
06-30 13:52:48.269  6481  6500 I Adreno-EGL: Remote Branch: 
06-30 13:52:48.269  6481  6500 I Adreno-EGL: Local Patches: 
06-30 13:52:48.269  6481  6500 I Adreno-EGL: Reconstruct Branch: 
06-30 13:52:48.269  6481  6500 D libEGL  : eglInitialize EGLDisplay = 0xae2187c4
06-30 13:52:48.269  6481  6500 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:52:48.319  6481  6481 V ActivityThread: updateVisibility : ActivityRecord{276b160 token=android.os.BinderProxy@db30148 {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
06-30 13:52:48.319  6481  6481 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
06-30 13:52:48.319   741  1717 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 13:52:48.329  1945  1945 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
06-30 13:52:48.339  6481  6481 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
06-30 13:52:48.369   741  1406 V WindowStateAnimator: Finishing drawing window Window{3326cb7 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
06-30 13:52:48.369  6481  6481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@db30148 time:159884
06-30 13:52:48.379   741   883 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:48.379   741   741 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:48.379   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbee3f364
06-30 13:52:48.379   741   741 I KnoxTimeoutHandler: SD activityfalse
06-30 13:52:48.379   741   883 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +406ms (total +765ms)
06-30 13:52:48.389   741   883 D ActivityManager: mDVFSHelper.release()
06-30 13:52:48.389   741   883 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e84878c u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64} time:159900
06-30 13:52:48.469   741  1361 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,06-30 13:52:49.229  1451  1451 D Recents : onTaskStackChanged
,06-30 13:52:53.999   741  3359 D SSRM:n  : SIOP:: AP = 340, PST = 381, CUR = 450, LCD = 0
,06-30 13:52:54.049   741  3359 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:55.429   741   909 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 13:52:55.469   741   909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 13:52:57.039   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:52:59.989   741  1235 V AlarmManager: Expired Alarm result :8
,06-30 13:53:04.069   741  3359 D SSRM:n  : SIOP:: AP = 320, PST = 372, CUR = 450, LCD = 0
,06-30 13:53:04.079  2008  3242 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:06.839   741  1235 V AlarmManager: Expired Alarm result :4
,06-30 13:53:06.859   741  1637 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 13:53:06.869   741  1637 V AlarmManager:  remove PendingIntent] PendingIntent{67bf9a9: PendingIntentRecord{a90fb2e android broadcastIntent}}
,06-30 13:53:06.909   741  1235 I ActivityManager: Start proc 6524:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 13:53:06.919  6524  6524 E Zygote  : v2
,06-30 13:53:06.929  6524  6524 I libpersona: KNOX_SDCARD checking this for 1000
,06-30 13:53:06.929  6524  6524 I libpersona: KNOX_SDCARD not a persona
,06-30 13:53:06.929  6524  6524 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 13:53:06.929  6524  6524 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:53:06.929  6524  6524 E Zygote  : accessInfo : 0
,06-30 13:53:06.939   741  2064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:06.939   741  2064 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 13:53:06.939   741  2064 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:53:06.939   741  2064 D BatteryService: stay LED for fully charged
,06-30 13:53:06.949   741   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3610b89 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef42c6c 2008:com.google.android.gms.persistent/u0a11}
,06-30 13:53:06.949  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:53:06.949  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 13:53:06.949  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:53:06.969   741  1717 V AlarmManager:  remove PendingIntent] PendingIntent{6cbd78e: PendingIntentRecord{902b13c com.google.android.gms broadcastIntent}}
,06-30 13:53:06.979  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:53:06.979  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:53:06.979   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:06.979   741   741 I MotionRecognitionService: Plugged
,06-30 13:53:06.989   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:53:06.989   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:53:06.989   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:06.989  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:06.989  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:06.989  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 13:53:06.989  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:06.999  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:06.999  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 13:53:06.999  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:06.999  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:06.999  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:06.999  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:07.019  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:07.019  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:07.019  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:07.039  6524  6524 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:53:07.039  6524  6524 D ActivityThread: Added TimaKeyStore provider
,06-30 13:53:07.069  6524  6524 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,06-30 13:53:07.079  6524  6524 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,06-30 13:53:07.089  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:07.109   741  2064 I ActivityManager: Killing 5066:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,06-30 13:53:07.139   741  1720 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,06-30 13:53:09.209   741  1576 E Watchdog: !@Sync 5 [06-30 13:53:09.216]
,06-30 13:53:09.649   741  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 13:53:09.659   741   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5bf4a66 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f98dba 5976:com.samsung.android.sm.provider/1000}
,06-30 13:53:09.689   741  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 13:53:09.689   741   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{29ef654 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f98dba 5976:com.samsung.android.sm.provider/1000}
,06-30 13:53:14.119   741  3359 D SSRM:n  : SIOP:: AP = 320, PST = 367, CUR = 450, LCD = 0
,06-30 13:53:16.999   741  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:16.999   741  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:53:16.999   741  1565 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:53:17.009   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:17.019   741   741 I MotionRecognitionService: Plugged
,06-30 13:53:17.019   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:53:17.019   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:53:17.019   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:17.029   741  1565 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 13:53:17.029   741  1565 D BatteryService: stay LED for fully charged
,06-30 13:53:17.039  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:17.049  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:17.049  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:53:17.049   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:17.069  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:17.069  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:17.069  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:24.179   741  3359 D SSRM:n  : SIOP:: AP = 310, PST = 360, CUR = 450, LCD = 0
,06-30 13:53:34.239   741  3359 D SSRM:n  : SIOP:: AP = 310, PST = 347, CUR = 450, LCD = 0
,06-30 13:53:36.959   741  1235 V AlarmManager: Expired Alarm result :4
,06-30 13:53:36.999   741   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5520143 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef42c6c 2008:com.google.android.gms.persistent/u0a11}
,06-30 13:53:37.009   741  1487 V AlarmManager:  remove PendingIntent] PendingIntent{d1f23c0: PendingIntentRecord{902b13c com.google.android.gms broadcastIntent}}
,06-30 13:53:37.029   741  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:37.029   741  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:53:37.029   741  1487 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
06-30 13:53:37.029   741  1487 D BatteryService: stay LED for fully charged
,06-30 13:53:37.029   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:37.039   741   741 I MotionRecognitionService: Plugged
,06-30 13:53:37.039   741   741 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:37.039   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:53:37.039   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:37.039  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:37.039  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:37.039  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:37.059   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:37.069  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 13:53:37.069  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:37.069  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:37.749  2008  2008 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a29f0c11-fad4-4bbe-953f-c30c2fbcf3d6
,06-30 13:53:37.769  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:37.769  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:37.939  2008  2364 W GCoreFlp: No location to return for getLastLocation()
,06-30 13:53:38.029  4237  6581 D UdcContextInitService: registered all accounts: true
,06-30 13:53:38.039  2008  2477 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:53:38.059  2008  2531 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 13:53:38.159  2008  2531 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:53:38.209   741  1720 V AlarmManager:  remove PendingIntent] PendingIntent{829454d: PendingIntentRecord{902b13c com.google.android.gms broadcastIntent}}
,06-30 13:53:38.219  2008  2531 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 13:53:38.349  4237  5024 I Icing   : Performing maintenance.
,06-30 13:53:38.379   741  2110 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,06-30 13:53:38.429   741  1487 V AlarmManager:  remove PendingIntent] PendingIntent{446d105: PendingIntentRecord{902b13c com.google.android.gms broadcastIntent}}
,06-30 13:53:38.489  4237  6598 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 13:53:38.529  2008  2523 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:53:38.529  2008  2523 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:53:38.529   306  1196 D EnterpriseController: netId is 0
06-30 13:53:38.529   306  1196 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,06-30 13:53:38.539  2008  2523 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/webhistory
,06-30 13:53:38.549  4237  5024 W Icing   : Failed to get auth token for account:<redacted>, error:NetworkError
,06-30 13:53:38.609  2008  2048 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:53:38.609  2008  2048 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:53:38.609  2008  2048 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/webhistory
,06-30 13:53:38.609  4237  5024 W Icing   : Failed to get auth token for account:<redacted>, error:NetworkError
,06-30 13:53:38.679   741   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{71495b2 u0 com.google.android.gms.udc.action.SETTING_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d2e2c2 1798:com.google.android.googlequicksearchbox:search/u0a61}
,06-30 13:53:38.939  4237  5024 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,06-30 13:53:38.939  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
06-30 13:53:38.939  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:38.969  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:39.009  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:39.079  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:39.119  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:39.129  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:39.139  4237  5024 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,06-30 13:53:39.219   741  1576 E Watchdog: !@Sync 6 [06-30 13:53:39.222]
,06-30 13:53:39.239  4237  5024 I Icing   : Performing maintenance usage 1853706 budget 4712893573 free 99.961% index free 99.973% purge? false target 3299025501
,06-30 13:53:39.269  4237  5024 I Icing   : Starting compaction min disk 99.961% min index 99.973%
,06-30 13:53:39.359  4237  5024 I Icing   : Usage reports aged/total 0/0
,06-30 13:53:39.569  4237  5024 I Icing   : Done compaction min disk 99.961% min index 99.973% num docs 85 old 145 trimmed 0 err 0
,06-30 13:53:39.739  4237  4955 I Icing   : Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,06-30 13:53:39.909   741   752 I art     : Background partial concurrent mark sweep GC freed 30096(1979KB) AllocSpace objects, 30(600KB) LOS objects, 27% free, 42MB/58MB, paused 2.091ms total 134.049ms
,06-30 13:53:40.339  2008  2531 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:53:40.339  2008  2531 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 13:53:40.449  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:53:44.299   741  3359 D SSRM:n  : SIOP:: AP = 310, PST = 333, CUR = 450, LCD = 0
,06-30 13:53:47.119   741   758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:54.359   741  3359 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450, LCD = 0
,06-30 13:53:57.069   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:57.209   741  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:57.209   741  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:53:57.209   741  1565 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:53:57.219   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:57.229   741   741 I MotionRecognitionService: Plugged
,06-30 13:53:57.229   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:53:57.229   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:53:57.229   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:57.239   741  1565 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:53:57.239   741  1565 D BatteryService: stay LED for fully charged
,06-30 13:53:57.249  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:57.249  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:57.249  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:57.279  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:57.279  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:57.279  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:59.989   741  1235 V AlarmManager: Expired Alarm result :8
,06-30 13:54:04.419   741  3359 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 450, LCD = 0
,06-30 13:54:06.919   741  1235 V AlarmManager: Expired Alarm result :8
,06-30 13:54:07.289   741  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:07.299   741  1407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:07.299   741  1407 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:54:07.299   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:07.309   741   741 I MotionRecognitionService: Plugged
,06-30 13:54:07.319   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:07.319   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:07.319   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:07.319   741  1407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:54:07.329   741  1407 D BatteryService: stay LED for fully charged
,06-30 13:54:07.329  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:07.329  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:07.329  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:07.359  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:07.359  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:07.359  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:09.219   741  1576 E Watchdog: !@Sync 7 [06-30 13:54:09.224]
,06-30 13:54:14.479   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 316, CUR = 450, LCD = 0
,06-30 13:54:17.069   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:17.379   741  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:17.379   741  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:17.379   741  1487 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:54:17.379   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:17.399   741   741 I MotionRecognitionService: Plugged
,06-30 13:54:17.399   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:17.399   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:17.399   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:17.409   741  1487 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:54:17.409   741  1487 D BatteryService: stay LED for fully charged
,06-30 13:54:17.419  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:17.419  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:17.429  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:17.449  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:17.449  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:17.449  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:24.539   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 313, CUR = 450, LCD = 0
,06-30 13:54:27.479   741  1717 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:27.479   741  1717 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:27.489   741  1717 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:54:27.489   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:27.499   741   741 I MotionRecognitionService: Plugged
,06-30 13:54:27.499   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:27.499   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:27.509   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:27.509   741  1717 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:54:27.509   741  1717 D BatteryService: stay LED for fully charged
,06-30 13:54:27.529  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:27.529  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:27.529  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:27.549  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:27.549  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:27.549  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:34.599   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450, LCD = 0
,06-30 13:54:37.069   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:39.219   741  1576 E Watchdog: !@Sync 8 [06-30 13:54:39.228]
,06-30 13:54:40.469  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:54:44.659   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,06-30 13:54:54.709   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,06-30 13:54:57.079   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:57.549   741  2065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:54:57.549   741  2065 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:54:57.549   741  2065 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:54:57.559   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:57.569   741   741 I MotionRecognitionService: Plugged
,06-30 13:54:57.569   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:54:57.569   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:54:57.569   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:57.579   741  2065 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:54:57.579   741  2065 D BatteryService: stay LED for fully charged
,06-30 13:54:57.589  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:57.589  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:57.589  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:57.619  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:57.629  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:57.629  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:04.769   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,06-30 13:55:09.229   741  1576 E Watchdog: !@Sync 9 [06-30 13:55:09.232]
,06-30 13:55:14.829   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,06-30 13:55:17.079   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:24.109   741  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:55:24.119   741  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:55:24.119   741  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:55:24.129   741  1229 I TLC_TIMA_PKM_initialize: initializing...
,06-30 13:55:24.129   741  1229 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 13:55:24.129   741  1229 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,06-30 13:55:24.139   741  1229 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 13:55:24.139   741  1229 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 13:55:24.139   741  1229 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,06-30 13:55:24.139   741  1229 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 13:55:24.139   741  1229 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 13:55:24.149   741  1229 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 13:55:24.149   741  1229 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 13:55:24.199   741  1229 D QSEECOMAPI: : Loaded image: APP id = 3
,06-30 13:55:24.219   741  1229 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 13:55:24.239   741  1229 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 13:55:24.909   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,06-30 13:55:27.269   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:55:27.269   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:55:27.279   741  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:27.289   741  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:27.629   741  2064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:27.629   741  2064 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:55:27.629   741  2064 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:55:27.639   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:27.649   741   741 I MotionRecognitionService: Plugged
,06-30 13:55:27.649   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:55:27.649   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:55:27.649   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:27.659   741  2064 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:55:27.659   741  2064 D BatteryService: stay LED for fully charged
,06-30 13:55:27.669  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:27.669  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:27.679  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:27.699  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:27.699  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:27.699  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:34.969   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 13:55:37.079   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:38.559  2008  3242 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:55:39.229   741  1576 E Watchdog: !@Sync 10 [06-30 13:55:39.237]
,06-30 13:55:40.479  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:55:40.709  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 233ms lastUpdatedAfter : 122239ms
,06-30 13:55:45.029   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:55:55.089   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:55:57.089   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:57.709   741  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:55:57.709   741  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:55:57.719   741  1487 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:55:57.719   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:57.729   741   741 I MotionRecognitionService: Plugged
,06-30 13:55:57.729   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:55:57.729   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:55:57.739   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:57.739   741  1487 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 13:55:57.739   741  1487 D BatteryService: stay LED for fully charged
,06-30 13:55:57.759  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:57.759  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:55:57.759  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:57.799  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:57.799  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:57.799  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:01.359  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:01.389  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:01.389  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:01.459  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:56:01.459  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:56:01.459   306  1196 D EnterpriseController: netId is 0
06-30 13:56:01.459   306  1196 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 13:56:05.139   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:56:09.229   741  1576 E Watchdog: !@Sync 11 [06-30 13:56:09.240]
,06-30 13:56:12.439   741  1235 V AlarmManager: Expired Alarm result :4
,06-30 13:56:12.469  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:56:12.469  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 13:56:12.469  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:56:12.499  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:56:12.539  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:56:12.539   741  1637 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 13:56:12.539   741  1637 V AlarmManager:  remove PendingIntent] PendingIntent{67bf9a9: PendingIntentRecord{a90fb2e android broadcastIntent}}
,06-30 13:56:12.559   741  1637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 13:56:12.569  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.569  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.569  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.569  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.579  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.579  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.579  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:12.629  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:15.199   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:56:17.089   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:25.249   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:56:27.789   741   758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:27.789   741   758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:56:27.799   741   758 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:56:27.799   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:56:27.809   741   741 I MotionRecognitionService: Plugged
,06-30 13:56:27.809   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:56:27.819   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:56:27.819   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:56:27.819   741   758 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 13:56:27.819   741   758 D BatteryService: stay LED for fully charged
,06-30 13:56:27.829  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:27.829  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:56:27.829  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:27.849  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:27.849  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:27.859  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:35.309   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:56:37.089   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:39.239   741  1576 E Watchdog: !@Sync 12 [06-30 13:56:39.245]
,06-30 13:56:40.719  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:56:45.359   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 13:56:55.419   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,06-30 13:56:57.099   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:57.869   741  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:59.989   741  1235 V AlarmManager: Expired Alarm result :8
,06-30 13:57:05.519   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,06-30 13:57:09.239   741  1576 E Watchdog: !@Sync 13 [06-30 13:57:09.249]
,06-30 13:57:15.579   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,06-30 13:57:17.099   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:25.639   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,06-30 13:57:27.949   741  1717 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:27.949   741  1717 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:57:27.949   741  1717 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:57:27.959   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:27.969   741   741 I MotionRecognitionService: Plugged
,06-30 13:57:27.969   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:57:27.969   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:57:27.969   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:57:27.979   741  1717 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 13:57:27.979   741  1717 D BatteryService: stay LED for fully charged
,06-30 13:57:27.989  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:27.989  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:27.989  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:28.029  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:28.029  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:28.029  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:35.719   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,06-30 13:57:37.109   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:39.249   741  1576 E Watchdog: !@Sync 14 [06-30 13:57:39.254]
,06-30 13:57:40.749  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:57:45.769   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,06-30 13:57:55.829   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,06-30 13:57:57.109   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:58.029   741  1720 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:57:58.029   741  1720 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:57:58.029   741  1720 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:57:58.039   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:58.049   741   741 I MotionRecognitionService: Plugged
,06-30 13:57:58.049   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:57:58.049   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:57:58.059   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:57:58.059   741  1720 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 13:57:58.059   741  1720 D BatteryService: stay LED for fully charged
,06-30 13:57:58.079  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:57:58.079  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:57:58.079  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:58.099  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:58.099  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:58.099  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:05.889   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,06-30 13:58:09.249   741  1576 E Watchdog: !@Sync 15 [06-30 13:58:09.258]
,06-30 13:58:13.989   362   362 I bootchecker: bootchecker wake up!!
,06-30 13:58:15.939   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 13:58:17.109   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:25.999   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:58:28.109   741  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:28.109   741  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:58:28.109   741  1565 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:58:28.119   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:28.129   741   741 I MotionRecognitionService: Plugged
,06-30 13:58:28.129   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:58:28.129   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:58:28.129   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:58:28.139   741  1565 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 13:58:28.139   741  1565 D BatteryService: stay LED for fully charged
,06-30 13:58:28.159  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:28.159  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:28.159  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:28.189  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:28.199  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:28.199  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:36.059   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:58:37.119   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:39.259   741  1576 E Watchdog: !@Sync 16 [06-30 13:58:39.262]
,06-30 13:58:40.769  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:58:40.929  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 147ms lastUpdatedAfter : 180214ms
,06-30 13:58:46.109   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:58:56.159   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:58:57.119   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:58.189   741  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:58.189   741  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:58:58.189   741  2110 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:58:58.199   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:58:58.209   741   741 I MotionRecognitionService: Plugged
,06-30 13:58:58.209   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:58:58.209   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:58:58.209   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:58:58.219   741  2110 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 13:58:58.219   741  2110 D BatteryService: stay LED for fully charged
,06-30 13:58:58.229  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:58:58.229  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:58:58.229  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:58.249  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:58.249  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:58.249  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:06.209   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:59:09.259   741  1576 E Watchdog: !@Sync 17 [06-30 13:59:09.266]
,06-30 13:59:16.269   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:59:17.119   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:26.319   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:59:28.269   741  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:36.369   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:59:37.129   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:39.259   741  1576 E Watchdog: !@Sync 18 [06-30 13:59:39.270]
,06-30 13:59:40.939  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 13:59:46.429   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:59:56.479   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 13:59:57.129   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:58.349   741  1734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:59:58.349   741  1734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 13:59:58.359   741  1734 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 13:59:58.359   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:58.369   741   741 I MotionRecognitionService: Plugged
,06-30 13:59:58.369   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 13:59:58.369   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:59:58.379   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:59:58.379   741  1734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 13:59:58.379   741  1734 D BatteryService: stay LED for fully charged
,06-30 13:59:58.389  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:58.389  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:59:58.389  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:59:58.419  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:58.429  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:58.429  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:06.529   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:00:09.269   741  1576 E Watchdog: !@Sync 19 [06-30 14:00:09.275]
,06-30 14:00:16.589   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:00:17.139   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:24.099   741  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:00:24.109   741  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:00:24.109   741  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:00:25.439   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:00:25.439   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:00:25.449   741  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:25.459   741  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:26.639   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:00:28.429   741  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:28.429   741  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:00:28.439   741  2110 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:00:28.439   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:00:28.449   741   741 I MotionRecognitionService: Plugged
,06-30 14:00:28.449   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:00:28.449   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:00:28.459   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:00:28.459   741  2110 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:00:28.459   741  2110 D BatteryService: stay LED for fully charged
,06-30 14:00:28.479  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:00:28.479  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:00:28.479  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:00:28.499  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:28.499  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:00:28.499  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:36.699   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:00:37.139   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:39.269   741  1576 E Watchdog: !@Sync 20 [06-30 14:00:39.279]
,06-30 14:00:40.969  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.619   741   821 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.629   741   821 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:41.639   741   821 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:41.749   741   883 I ActivityManager: setMaxStartingBackgroundTimer onfinish,
,06-30 14:00:41.749   741   883 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 14:00:46.799   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:00:56.849   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:00:57.139   741  3395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:58.509   741  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:01.589   741  2094 I ActivityManager: Killing 4504:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 603s, lastActivityTime 603s
,06-30 14:01:01.589   741  2094 I ActivityManager: Killing 3772:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 607s, lastActivityTime 607s
,06-30 14:01:01.629  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:01.649   294   294 I ServiceManager: service 'AtCmdFwd' died
,06-30 14:01:01.659   373  5019 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 14:01:01.659   373  5019 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 14:01:01.659   741  1735 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 14:01:01.659   741  1735 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 14:01:01.659   741  1735 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 14:01:01.689  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:01.689  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:01.749  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:01:01.749  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:01:01.759   306  1196 D EnterpriseController: netId is 0
06-30 14:01:01.759   306  1196 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 14:01:01.769   741  1720 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 14:01:01.769   741  1720 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 14:01:01.769   741  1720 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10892ms
,06-30 14:01:02.659   373  5019 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 14:01:02.729   741   834 I ActivityManager: Start proc 6686:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 14:01:02.739  6686  6686 E Zygote  : v2
,06-30 14:01:02.739  6686  6686 I libpersona: KNOX_SDCARD checking this for 1000
06-30 14:01:02.739  6686  6686 I libpersona: KNOX_SDCARD not a persona
,06-30 14:01:02.739  6686  6686 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:01:02.739  6686  6686 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:01:02.749  6686  6686 E Zygote  : accessInfo : 0
,06-30 14:01:02.789  6686  6686 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:01:02.789  6686  6686 D ActivityThread: Added TimaKeyStore provider
,06-30 14:01:02.809  6686  6686 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 14:01:02.819  6686  6686 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 14:01:02.829  6686  6686 D AtFwdService: onCreate method
,06-30 14:01:02.829  6686  6686 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 14:01:02.839  6686  6698 D AtCkpdCmdHandler: De-queing command
,06-30 14:01:06.919   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:01:09.279   741  1576 E Watchdog: !@Sync 21 [06-30 14:01:09.285]
,06-30 14:01:12.729   741   834 I ActivityManager: Start proc 6700:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 14:01:12.729  6700  6700 E Zygote  : v2
,06-30 14:01:12.729  6700  6700 I libpersona: KNOX_SDCARD checking this for 10026
06-30 14:01:12.729  6700  6700 I libpersona: KNOX_SDCARD not a persona
,06-30 14:01:12.739  6700  6700 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:01:12.739  6700  6700 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:01:12.739  6700  6700 E Zygote  : accessInfo : 0
,06-30 14:01:12.739  6700  6700 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 14:01:12.789  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:01:12.789  6700  6700 D ActivityThread: Added TimaKeyStore provider
,06-30 14:01:12.799   741  1720 I ActivityManager: Killing 3725:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 618s, lastActivityTime 608s
,06-30 14:01:12.829   741  1734 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,06-30 14:01:12.829   741  1734 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
06-30 14:01:12.829  6700  6700 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 14:01:12.859  6700  6700 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 14:01:12.869  6700  6700 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 14:01:12.869  6700  6700 D ContextualPageNotification: resetAllNotification : all clear!!!
,06-30 14:01:13.039   741  1235 V AlarmManager: Expired Alarm result :8
,06-30 14:01:17.009   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:01:27.069   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:01:28.589   741  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:37.119   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:01:39.279   741  1576 E Watchdog: !@Sync 22 [06-30 14:01:39.289]
,06-30 14:01:40.989  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:01:41.149  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 147ms lastUpdatedAfter : 180220ms
,06-30 14:01:47.179   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:01:57.229   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:01:58.669   741  1734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:01:58.669   741  1734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:01:58.669   741  1734 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:01:58.679   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:01:58.689   741   741 I MotionRecognitionService: Plugged
,06-30 14:01:58.689   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:01:58.689   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:01:58.689   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:01:58.699   741  1734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:01:58.699   741  1734 D BatteryService: stay LED for fully charged
,06-30 14:01:58.719  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:58.719  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:58.729  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:58.749  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:58.749  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:58.749  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:07.279   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:02:09.289   741  1576 E Watchdog: !@Sync 23 [06-30 14:02:09.295]
,06-30 14:02:17.359   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:02:27.419   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:02:28.749   741  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:28.749   741  1565 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:02:28.759   741  1565 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:02:28.759   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:02:28.769   741   741 I MotionRecognitionService: Plugged
,06-30 14:02:28.769   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:02:28.769   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:02:28.779   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:02:28.779   741  1565 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:02:28.779   741  1565 D BatteryService: stay LED for fully charged
,06-30 14:02:28.789  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:02:28.789  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:02:28.799  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:02:28.829  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:28.829  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:28.829  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:37.469   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:02:39.289   741  1576 E Watchdog: !@Sync 24 [06-30 14:02:39.299]
,06-30 14:02:41.159  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:02:47.519   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:02:57.579   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:02:58.829   741  2064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:07.639   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:03:09.299   741  1576 E Watchdog: !@Sync 25 [06-30 14:03:09.306]
,06-30 14:03:17.719   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:03:27.769   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:03:28.909   741  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:28.909   741  1406 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:03:28.919   741  1406 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:03:28.919   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:28.929   741   741 I MotionRecognitionService: Plugged
,06-30 14:03:28.929   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:03:28.939   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:03:28.939   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:03:28.939   741  1406 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 14:03:28.949   741  1406 D BatteryService: stay LED for fully charged
,06-30 14:03:28.959  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:28.959  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:28.959  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:28.999  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:28.999  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:28.999  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:37.829   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:03:39.299   741  1576 E Watchdog: !@Sync 26 [06-30 14:03:39.310]
,06-30 14:03:41.209  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:03:41.899   741  2150 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 14:03:41.899   741  2150 V MARsPolicyManager: updateSMDBValues
,06-30 14:03:41.909   741   881 E MARsDBManager: updateDBAll : begin --size 1
,06-30 14:03:41.929   741   881 I ActivityManager: Killing 1829:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 781s, lastActivityTime 700s
,06-30 14:03:41.939   741   881 I ActivityManager: Killing 1511:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 758s, lastActivityTime 748s
,06-30 14:03:41.989   741   881 E MARsDBManager: updateDBAll : end
,06-30 14:03:41.989   741   881 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 14:03:42.039   741   758 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,06-30 14:03:42.039   741   758 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
,06-30 14:03:42.039   741   758 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,06-30 14:03:42.059   741  1406 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,06-30 14:03:42.059   741  1406 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 14:03:42.059   741  1406 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 10981ms
,06-30 14:03:42.059   741  1406 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 14:03:42.059   741  1406 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 20981ms
,06-30 14:03:42.059  5686  5686 D HealthConsole: Service for HealthDataStore is disconnected
,06-30 14:03:42.089  6726  6726 E Zygote  : v2
,06-30 14:03:42.099  6726  6726 I libpersona: KNOX_SDCARD checking this for 10034
,06-30 14:03:42.099  6726  6726 I libpersona: KNOX_SDCARD not a persona
,06-30 14:03:42.099  6726  6726 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:03:42.099  6726  6726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:03:42.099  6726  6726 E Zygote  : accessInfo : 0
,06-30 14:03:42.099  6726  6726 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,06-30 14:03:42.099   741  2064 I ActivityManager: Start proc 6726:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,06-30 14:03:42.149  6726  6726 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 14:03:42.149  6726  6726 D ActivityThread: Added TimaKeyStore provider
,06-30 14:03:42.169  6726  6726 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,06-30 14:03:42.209  6726  6726 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,06-30 14:03:42.219  6726  6726 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 14:03:42.219  6726  6726 I MultiDex: install
,06-30 14:03:42.219  6726  6726 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 14:03:42.219  6726  6726 I MultiDex: install
,06-30 14:03:42.219  6726  6726 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 14:03:42.429   741   759 I ActivityManager: Start proc 6759:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,06-30 14:03:42.429  6759  6759 E Zygote  : v2
06-30 14:03:42.429  6759  6759 I libpersona: KNOX_SDCARD checking this for 10016
06-30 14:03:42.429  6759  6759 I libpersona: KNOX_SDCARD not a persona
,06-30 14:03:42.429  6759  6759 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:03:42.429  6759  6759 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:03:42.439  6759  6759 E Zygote  : accessInfo : 0
,06-30 14:03:42.439  6759  6759 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,06-30 14:03:42.469  6759  6759 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:03:42.469  6759  6759 D ActivityThread: Added TimaKeyStore provider
,06-30 14:03:42.499  6759  6759 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,06-30 14:03:42.549  6726  6726 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 14:03:42.549  6726  6726 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 14:03:42.629  1376  1376 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,06-30 14:03:42.639   741  2064 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,06-30 14:03:42.659   741  1715 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,06-30 14:03:42.669   741  1735 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,06-30 14:03:42.679  1376  1376 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{36e0a33 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,06-30 14:03:42.679  1376  1376 D AdaptiveEventManager: M updateContainers()
06-30 14:03:42.679  1376  1376 D AdaptiveEventContainerSmall: C updatePedoContainer()
06-30 14:03:42.679  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate()
,06-30 14:03:42.689   741  2065 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,06-30 14:03:42.689  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,06-30 14:03:42.749  6726  6726 I Health.HealthService: HealthService: onCreate() start (6726)
,06-30 14:03:42.909  5686  5686 D HealthDataStore: Service for HealthDataStore is connected
,06-30 14:03:42.919  5686  5686 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 14:03:42.939   741  1735 I ActivityManager: Killing 5083:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,06-30 14:03:42.959  5686  5686 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 14:03:42.959  5686  5686 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 14:03:42.989   741  1720 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,06-30 14:03:42.999  6726  6726 D HealthDataStore: Service for HealthDataStore is connected
,06-30 14:03:42.999  6726  6726 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 14:03:42.999  6726  6726 D HealthConsole: Service for HealthDataConsole is connected
,06-30 14:03:43.009  6726  6726 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 14:03:43.009  6726  6726 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 14:03:43.059   741   834 I ActivityManager: Start proc 6788:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,06-30 14:03:43.059   741  1318 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 14:03:43.059  6788  6788 E Zygote  : v2
,06-30 14:03:43.059  6788  6788 I libpersona: KNOX_SDCARD checking this for 10181
06-30 14:03:43.059  6788  6788 I libpersona: KNOX_SDCARD not a persona
,06-30 14:03:43.059  6788  6788 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:03:43.059  6788  6788 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:03:43.069  6788  6788 E Zygote  : accessInfo : 0
,06-30 14:03:43.069  6788  6788 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,06-30 14:03:43.109  6788  6788 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:03:43.109  6788  6788 D ActivityThread: Added TimaKeyStore provider
,06-30 14:03:43.129   741  1318 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 14:03:43.139  6788  6788 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,06-30 14:03:43.159  6788  6788 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,06-30 14:03:43.189  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,06-30 14:03:43.199  6788  6788 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:03:43.199   741   834 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc8834b u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d62f128 6788:com.sec.android.daemonapp/u0a181}
,06-30 14:03:43.199  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,06-30 14:03:43.199  6788  6788 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:03:43.209  6788  6788 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,06-30 14:03:43.209  6788  6788 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:03:43.209  6788  6788 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,06-30 14:03:43.209  6788  6788 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 14:03:43.229  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:03:43.229  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 14:03:43.229  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,06-30 14:03:43.229  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:03:43.229  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 14:03:43.229  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,06-30 14:03:43.239  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 14:03:43.239  6726  6780 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,06-30 14:03:43.259  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,06-30 14:03:43.259  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:03:43.269  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 14:03:43.269  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,06-30 14:03:43.269  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 14:03:43.269  6788  6788 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:03:43.279  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:03:43.279  6788  6788 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 14:03:43.279  6788  6788 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,06-30 14:03:43.279  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:03:43.279  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 14:03:43.279  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 14:03:43.279  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:03:43.279  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 14:03:43.279  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 14:03:43.279  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.289  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:03:43.289   741  2064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{689f7d4 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d62f128 6788:com.sec.android.daemonapp/u0a181}
,06-30 14:03:43.299  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:03:43.299  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 14:03:43.299  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 14:03:43.299  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:03:43.309  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:03:43.309  6788  6788 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 14:03:43.309  6788  6788 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 14:03:43.309  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 14:03:43.309  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.309  6726  6801 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,06-30 14:03:43.319  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:03:43.319   741  2064 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4394d7d u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d62f128 6788:com.sec.android.daemonapp/u0a181}
,06-30 14:03:43.329  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:03:43.329  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 14:03:43.329  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 14:03:43.339  6759  6773 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 14:03:43.339  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.339  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:03:43.339   413   413 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 10016, gid 10016, pid 6759
06-30 14:03:43.339   413   413 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,06-30 14:03:43.349  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:03:43.349  6788  6788 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 14:03:43.349  6788  6788 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,06-30 14:03:43.349  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.349  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:03:43.359   741  1564 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db04472 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d62f128 6788:com.sec.android.daemonapp/u0a181}
,06-30 14:03:43.379  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 14:03:43.379  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 14:03:43.379  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 14:03:43.379  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 14:03:43.389  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:03:43.389  6788  6788 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 14:03:43.389  6788  6788 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 14:03:43.389  6788  6788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 14:03:43.389  6788  6788 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 14:03:43.399  6788  6788 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 14:03:43.569  6759  6773 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,06-30 14:03:43.599  6726  6801 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,06-30 14:03:43.789  6726  6801 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
06-30 14:03:43.789  6726  6801 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 14:03:44.049   413   413 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,06-30 14:03:44.089  6759  6773 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,06-30 14:03:44.089  6759  6773 I SecureStorage: [INFO]: SPID(0x00000007)Skip using SecureStorageExceptionJNI
,06-30 14:03:44.089  6759  6773 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,06-30 14:03:47.929   741  3359 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 450, LCD = 0
,06-30 14:03:57.989   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:03:58.989   741  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:03:58.999   741  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:03:58.999   741  2110 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:03:58.999   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:59.009   741   741 I MotionRecognitionService: Plugged
,06-30 14:03:59.019   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:03:59.019   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:03:59.019   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:03:59.029   741  2110 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 14:03:59.029   741  2110 D BatteryService: stay LED for fully charged
,06-30 14:03:59.039  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:59.039  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:03:59.039  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:59.059  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:59.059  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:59.059  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:08.039   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:04:09.309   741  1576 E Watchdog: !@Sync 27 [06-30 14:04:09.314]
,06-30 14:04:18.099   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:04:28.149   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:04:29.069   741  2065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:38.199   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:04:39.309   741  1576 E Watchdog: !@Sync 28 [06-30 14:04:39.318]
,06-30 14:04:41.239  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:04:41.389  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 144ms lastUpdatedAfter : 180239ms
,06-30 14:04:48.259   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:04:58.309   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:04:59.149   741  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:08.399   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:05:09.319   741  1576 E Watchdog: !@Sync 29 [06-30 14:05:09.322]
,06-30 14:05:18.459   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 14:05:24.099   741  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:05:24.109   741  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:05:24.109   741  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:05:27.149   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:05:27.149   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:05:27.159   741  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:27.169   741  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:28.509   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:05:29.229   741  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:29.239   741  1406 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:05:29.239   741  1406 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:05:29.239   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:05:29.249   741   741 I MotionRecognitionService: Plugged
,06-30 14:05:29.249   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:05:29.259   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:05:29.259   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:05:29.259   741  1406 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:05:29.269   741  1406 D BatteryService: stay LED for fully charged
,06-30 14:05:29.279  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:29.279  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:29.279  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:05:29.309  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:29.309  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:05:29.309  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:38.599   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:05:39.319   741  1576 E Watchdog: !@Sync 30 [06-30 14:05:39.326]
,06-30 14:05:41.399  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:05:48.659   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:05:58.709   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:05:59.459   741  1235 V AlarmManager: Expired Alarm result :8
,06-30 14:05:59.529   741  2064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:59.539   741  2064 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:05:59.539   741  2064 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
06-30 14:05:59.539   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:05:59.549   741   741 I MotionRecognitionService: Plugged
,06-30 14:05:59.549   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:05:59.549   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:05:59.559   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:05:59.559   741  2064 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 14:05:59.559   741  2064 D BatteryService: stay LED for fully charged
,06-30 14:05:59.579  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:59.579  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:05:59.579  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:05:59.609  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:59.609  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:59.609  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:01.879  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:01.899  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:01.909  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:01.969  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:06:01.969  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:06:01.979   306  1196 D EnterpriseController: netId is 0
06-30 14:06:01.979   306  1196 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 14:06:08.759   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:06:09.319   741  1576 E Watchdog: !@Sync 31 [06-30 14:06:09.330]
,06-30 14:06:18.819   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:06:28.869   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:06:29.619   741  2094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:38.929   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:06:39.329   741  1576 E Watchdog: !@Sync 32 [06-30 14:06:39.335]
,06-30 14:06:41.419  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:06:48.979   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:06:49.109   741   752 I art     : Background sticky concurrent mark sweep GC freed 50303(7MB) AllocSpace objects, 395(7MB) LOS objects, 26% free, 42MB/58MB, paused 2.431ms total 115.057ms
,06-30 14:06:59.069   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:06:59.689   741  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:06:59.689   741  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:06:59.689   741  1487 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:06:59.699   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:59.709   741   741 I MotionRecognitionService: Plugged
,06-30 14:06:59.709   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:06:59.709   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:06:59.719   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:06:59.719   741  1487 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,06-30 14:06:59.729   741  1487 D BatteryService: stay LED for fully charged
,06-30 14:06:59.739  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:59.739  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:06:59.739  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:59.759  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:59.759  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:59.759  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:09.149   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:07:09.329   741  1576 E Watchdog: !@Sync 33 [06-30 14:07:09.340]
,06-30 14:07:19.199   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:07:29.259   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:07:29.769   741  2064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:29.769   741  2064 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:07:29.769   741  2064 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:07:29.779   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:07:29.789   741   741 I MotionRecognitionService: Plugged
,06-30 14:07:29.789   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:07:29.789   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:07:29.789   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:07:29.799   741  2064 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 14:07:29.799   741  2064 D BatteryService: stay LED for fully charged
,06-30 14:07:29.819  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:29.819  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:07:29.819  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:07:29.849  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:29.859  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:29.859  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:39.309   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:07:39.339   741  1576 E Watchdog: !@Sync 34 [06-30 14:07:39.345]
,06-30 14:07:41.459  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:07:41.619  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 152ms lastUpdatedAfter : 180228ms
,06-30 14:07:49.369   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:07:59.449   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:07:59.849   741  1564 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:09.339   741  1576 E Watchdog: !@Sync 35 [06-30 14:08:09.350]
,06-30 14:08:09.499   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:08:19.549   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:08:29.609   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:08:29.929   741  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:29.929   741  1406 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:08:29.939   741  1406 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:08:29.939   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:29.949   741   741 I MotionRecognitionService: Plugged
,06-30 14:08:29.949   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:08:29.949   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:08:29.959   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:08:29.959   741  1406 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 14:08:29.969   741  1406 D BatteryService: stay LED for fully charged
,06-30 14:08:29.979  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:29.979  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:08:29.979  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:30.009  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:30.009  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:30.009  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:39.349   741  1576 E Watchdog: !@Sync 36 [06-30 14:08:39.356]
,06-30 14:08:39.699   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:08:41.669  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:08:49.789   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:08:59.839   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:09:00.009   741  2064 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:00.009   741  2064 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:09:00.009   741  2064 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:09:00.019   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:00.029   741   741 I MotionRecognitionService: Plugged
,06-30 14:09:00.029   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:09:00.029   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:09:00.029   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:09:00.039   741  2064 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 14:09:00.039   741  2064 D BatteryService: stay LED for fully charged
,06-30 14:09:00.049  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:00.049  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:00.049  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:00.079  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:00.089  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:00.089  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:09.349   741  1576 E Watchdog: !@Sync 37 [06-30 14:09:09.360]
,06-30 14:09:09.899   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:09:19.949   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:09:30.009   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:09:30.089   741   759 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:30.099   741   759 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:09:30.099   741   759 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:09:30.099   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:09:30.109   741   741 I MotionRecognitionService: Plugged
,06-30 14:09:30.119   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:09:30.119   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:09:30.119   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:09:30.119   741   759 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:09:30.129   741   759 D BatteryService: stay LED for fully charged
,06-30 14:09:30.139  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:09:30.139  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:09:30.139  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:30.159  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:30.159  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:30.159  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:39.359   741  1576 E Watchdog: !@Sync 38 [06-30 14:09:39.364]
,06-30 14:09:40.079   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:09:41.779  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:09:50.129   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:10:00.169   741  2110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:00.169   741  2110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:10:00.169   741  2110 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:10:00.179   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:10:00.189   741   741 I MotionRecognitionService: Plugged
,06-30 14:10:00.189   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:10:00.199   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:10:00.199   741  2110 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:10:00.199   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:10:00.199   741  2110 D BatteryService: stay LED for fully charged
,06-30 14:10:00.219  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:00.219  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:10:00.219  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:10:00.249   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:10:00.259  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:00.259  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:10:00.259  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:09.359   741  1576 E Watchdog: !@Sync 39 [06-30 14:10:09.368]
,06-30 14:10:10.299   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:10:20.349   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:10:24.099   741  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:10:24.109   741  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:10:24.109   741  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:10:25.449   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:10:25.449   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:10:25.459   741  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:25.459   741  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:30.249   741  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:30.409   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:10:36.159   741   821 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:39.369   741  1576 E Watchdog: !@Sync 40 [06-30 14:10:39.373]
,06-30 14:10:40.459   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:10:41.799  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:10:41.959  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 147ms lastUpdatedAfter : 180336ms
,06-30 14:10:50.509   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:11:00.329   741  2065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:00.559   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:11:02.179  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:02.199  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:02.209  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:02.269  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:11:02.269  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:11:02.279   306  1196 D EnterpriseController: netId is 0
06-30 14:11:02.279   306  1196 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 14:11:09.369   741  1576 E Watchdog: !@Sync 41 [06-30 14:11:09.377]
,06-30 14:11:10.619   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:11:20.669   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:11:30.409   741  1564 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:11:30.729   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:11:39.379   741  1576 E Watchdog: !@Sync 42 [06-30 14:11:39.382]
,06-30 14:11:40.779   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:11:41.979  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:11:50.829   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:12:00.489   741  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:00.489   741  1487 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:12:00.489   741  1487 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:12:00.489   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:12:00.509   741   741 I MotionRecognitionService: Plugged
,06-30 14:12:00.509   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:12:00.509   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:12:00.509   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:12:00.519   741  1487 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:12:00.519   741  1487 D BatteryService: stay LED for fully charged
,06-30 14:12:00.529  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:00.529  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:00.539  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:12:00.569  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:00.569  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:00.569  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:00.889   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:12:09.379   741  1576 E Watchdog: !@Sync 43 [06-30 14:12:09.387]
,06-30 14:12:10.939   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:12:20.989   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:12:30.569   741  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:12:30.569   741  1715 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:12:30.579   741  1715 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:12:30.579   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:12:30.589   741   741 I MotionRecognitionService: Plugged
,06-30 14:12:30.589   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:12:30.589   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024,
06-30 14:12:30.599   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:12:30.599   741  1715 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:12:30.599   741  1715 D BatteryService: stay LED for fully charged
,06-30 14:12:30.609  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:30.609  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:12:30.619  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:12:30.649  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:30.649  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:30.649  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:31.039   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:12:39.389   741  1576 E Watchdog: !@Sync 44 [06-30 14:12:39.391]
,06-30 14:12:41.089   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:12:42.089  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:12:51.149   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:13:00.649   741  2065 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:01.199   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:13:09.389   741  1576 E Watchdog: !@Sync 45 [06-30 14:13:09.396]
,06-30 14:13:11.259   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:13:21.309   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:13:30.729   741  1720 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:30.729   741  1720 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:13:30.729   741  1720 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:13:30.729   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:13:30.739   741   741 I MotionRecognitionService: Plugged
,06-30 14:13:30.749   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:13:30.749   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:13:30.749   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:13:30.759   741  1720 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:13:30.759   741  1720 D BatteryService: stay LED for fully charged
,06-30 14:13:30.769  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:30.769  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:13:30.779  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:13:30.809  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:30.809  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:30.809  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:13:31.369   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:13:39.389   741  1576 E Watchdog: !@Sync 46 [06-30 14:13:39.400]
,06-30 14:13:41.419   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:13:42.109  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:13:42.269  1765  1791 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 150ms lastUpdatedAfter : 180312ms
,06-30 14:13:51.479   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:14:00.809   741  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:00.809   741  1715 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:14:00.809   741  1715 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:14:00.819   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:00.829   741   741 I MotionRecognitionService: Plugged
,06-30 14:14:00.829   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:14:00.829   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:14:00.839   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:14:00.839   741  1715 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 14:14:00.839   741  1715 D BatteryService: stay LED for fully charged
,06-30 14:14:00.849  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:14:00.849  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:14:00.849  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:00.869  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:00.869  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:14:00.869  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:01.529   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:14:09.399   741  1576 E Watchdog: !@Sync 47 [06-30 14:14:09.404]
,06-30 14:14:11.579   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:14:21.639   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:14:30.889   741  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:14:31.719   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:14:39.399   741  1576 E Watchdog: !@Sync 48 [06-30 14:14:39.408]
,06-30 14:14:41.799   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:14:42.279  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:14:51.889   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:15:00.969   741  1564 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:01.949   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:15:09.409   741  1576 E Watchdog: !@Sync 49 [06-30 14:15:09.412]
,06-30 14:15:11.999   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:15:22.049   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:15:24.109   741  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 14:15:24.109   741  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:15:24.109   741  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:15:27.159   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 14:15:27.159   741  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:15:27.169   741  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:27.179   741  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:31.049   741  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:31.049   741  1407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 14:15:31.049   741  1407 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 14:15:31.059   741   741 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:15:31.069   741   741 I MotionRecognitionService: Plugged
,06-30 14:15:31.069   741   741 D MotionRecognitionService:   cableConnection= 1
,06-30 14:15:31.069   741   741 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:15:31.069   741   741 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:15:31.079   741  1407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 14:15:31.079   741  1407 D BatteryService: stay LED for fully charged
,06-30 14:15:31.089  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:15:31.099  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:15:31.099  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:15:31.119  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:31.119  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:15:31.119  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:32.099   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:15:39.409   741  1576 E Watchdog: !@Sync 50 [06-30 14:15:39.416]
,06-30 14:15:41.909   741  2150 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 14:15:41.919   741  2150 V MARsPolicyManager: updateSMDBValues
,06-30 14:15:41.919   741   881 E MARsDBManager: updateDBAll : begin --size 0
,06-30 14:15:41.919   741   881 E MARsDBManager: updateDBAll : end
,06-30 14:15:42.159   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:15:42.309  1765  1791 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 14:15:52.209   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:16:01.129   741  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:02.259   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:16:02.349   741  1564 I ActivityManager: Killing 6788:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 739s, lastActivityTime 738s
,06-30 14:16:02.359   741  1564 I ActivityManager: Killing 6726:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 740s, lastActivityTime 739s
,06-30 14:16:02.359   741  1564 I ActivityManager: Killing 6700:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 889s, lastActivityTime 889s
,06-30 14:16:02.359   741  1564 I ActivityManager: Killing 6686:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 899s, lastActivityTime 899s
,06-30 14:16:02.399  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:16:02.419  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:16:02.419  2008  2008 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:16:02.459   294   294 I ServiceManager: service 'AtCmdFwd' died
,06-30 14:16:02.459   373  5020 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 14:16:02.469   373  5020 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 14:16:02.469   741  1720 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 14:16:02.469   741  1720 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 14:16:02.469   741  1720 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 14:16:02.539   741  1735 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 14:16:02.539   741  1735 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 14:16:02.539   741  1735 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10932ms
,06-30 14:16:02.549   741  1565 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
06-30 14:16:02.549   741  1565 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 14:16:02.549   741  1565 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20920ms
,06-30 14:16:02.559   741  1720 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
06-30 14:16:02.559   741  1720 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 14:16:02.559   741  1720 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 30908ms
,06-30 14:16:02.589  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:16:02.589  4852  4886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:16:02.589   306  1196 D EnterpriseController: netId is 0
06-30 14:16:02.589   306  1196 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 14:16:03.469   373  5020 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 14:16:03.529   741   834 I ActivityManager: Start proc 6889:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 14:16:03.539  6889  6889 E Zygote  : v2
,06-30 14:16:03.539  6889  6889 I libpersona: KNOX_SDCARD checking this for 1000
06-30 14:16:03.539  6889  6889 I libpersona: KNOX_SDCARD not a persona
,06-30 14:16:03.549  6889  6889 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:16:03.549  6889  6889 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:16:03.549  6889  6889 E Zygote  : accessInfo : 0
,06-30 14:16:03.589  6889  6889 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:16:03.589  6889  6889 D ActivityThread: Added TimaKeyStore provider
,06-30 14:16:03.609  6889  6889 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 14:16:03.619  6889  6889 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 14:16:03.629  6889  6889 D AtFwdService: onCreate method
,06-30 14:16:03.629  6889  6889 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 14:16:03.639  6889  6901 D AtCkpdCmdHandler: De-queing command
,06-30 14:16:09.409   741  1576 E Watchdog: !@Sync 51 [06-30 14:16:09.420]
,06-30 14:16:12.309   741  3359 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 14:16:13.529   741   834 I ActivityManager: Start proc 6903:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 14:16:13.539  6903  6903 E Zygote  : v2
,06-30 14:16:13.539  6903  6903 I libpersona: KNOX_SDCARD checking this for 10026
06-30 14:16:13.539  6903  6903 I libpersona: KNOX_SDCARD not a persona
,06-30 14:16:13.539  6903  6903 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 14:16:13.539  6903  6903 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 14:16:13.539  6903  6903 E Zygote  : accessInfo : 0
,06-30 14:16:13.549  6903  6903 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 14:16:13.589  6903  6903 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 14:16:13.589  6903  6903 D ActivityThread: Added TimaKeyStore provider
,06-30 14:16:13.619  6903  6903 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 14:16:13.629  6903  6903 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 14:16:13.639  6903  6903 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 14:16:13.639  6903  6903 D ContextualPageNotification: resetAllNotification : all clear!!!
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:16:19.929  2014  2014 E audit   : type=1400 msg=audit(1467288979.919:284): avc:  denied  { execmod } for  pid=6917 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 14:16:19.929  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 14:16:19.929  2014  2014 E audit   : type=1300 msg=audit(1467288979.919:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb5000 a1=51000 a2=5 a3=4 items=0 ppid=3508 ppcomm=adbd pid=6917 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 14:16:19.939  2014  2014 E audit   : type=1327 msg=audit(1467288979.919:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 14:16:19.939  2014  2014 E audit   : type=1320 msg=audit(1467288979.919:284): 
06-30 14:16:19.979  2014  2014 E audit   : type=1400 msg=audit(1467288979.979:285): avc:  denied  { execmod } for  pid=6917 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 14:16:19.979  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 14:16:19.979  2014  2014 E audit   : type=1300 msg=audit(1467288979.979:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f7a000 a1=51000 a2=5 a3=4 items=0 ppid=3508 ppcomm=adbd pid=6917 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 14:16:19.979  2014  2014 E audit   : type=1327 msg=audit(1467288979.979:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 14:16:19.989  2014  2014 E audit   : type=1320 msg=audit(1467288979.979:285): 
06-30 14:16:20.019  2014  2014 E audit   : type=1400 msg=audit(1467288980.019:286): avc:  denied  { execmod } for  pid=6917 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 14:16:20.019  6917  6917 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 14:16:20.019  2014  2014 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 14:16:20.029  2014  2014 E audit   : type=1300 msg=audit(1467288980.019:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f78000 a1=51000 a2=5 a3=4 items=0 ppid=3508 ppcomm=adbd pid=6917 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 14:16:20.029  2014  2014 E audit   : type=1327 msg=audit(1467288980.019:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 14:16:20.029  2014  2014 E audit   : type=1320 msg=audit(1467288980.019:286): 
06-30 14:16:20.029  6917  6917 D AndroidRuntime: CheckJNI is OFF
06-30 14:16:20.029  6917  6917 D AndroidRuntime: readGMSProperty: start
06-30 14:16:20.029  6917  6917 D AndroidRuntime: readGMSProperty: already setted!!
06-30 14:16:20.029  6917  6917 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 14:16:20.029  6917  6917 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 14:16:20.029  6917  6917 D AndroidRuntime: readGMSProperty: end
06-30 14:16:20.029  6917  6917 D AndroidRuntime: addProductProperty: start
06-30 14:16:20.039  6917  6917 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 14:16:20.039  6917  6917 W art     : aeddc000-b1d02000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 14:16:20.039  6917  6917 W art     : b1d02000-b3f71000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 14:16:20.039  6917  6917 W art     : b3f71000-b3f72000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 14:16:20.039  6917  6917 W art     : b3f72000-b3f73000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 14:16:20.039  6917  6917 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
06-30 14:16:20.039  6917  6917 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
06-30 14:16:20.039  6917  6917 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
06-30 14:16:20.039  6917  6917 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 14:16:20.039  6917  6917 W art     : b4846000-b4849000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
06-30 14:16:20.039  6917  6917 W art     : b4849000-b484a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
06-30 14:16:20.039  6917  6917 W art     : b484a000-b484b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
06-30 14:16:20.039  6917  6917 W art     : b484b000-b484c000 r--p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b484c000-b486c000 r--s 00000000 00:0b 8200       /dev/__properties__
06-30 14:16:20.039  6917  6917 W art     : b486c000-b527d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
06-30 14:16:20.039  6917  6917 W art     : b527d000-b527e000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b527e000-b52c7000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
06-30 14:16:20.039  6917  6917 W art     : b52c7000-b52c8000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
06-30 14:16:20.039  6917  6917 W art     : b52c8000-b52d0000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b52d0000-b52d1000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b52d1000-b5306000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
06-30 14:16:20.039  6917  6917 W art     : b5306000-b5307000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5307000-b5308000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
06-30 14:16:20.039  6917  6917 W art     : b5308000-b5309000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
06-30 14:16:20.039  6917  6917 W art     : b5309000-b5361000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
06-30 14:16:20.039  6917  6917 W art     : b5361000-b5362000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5362000-b5363000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
06-30 14:16:20.039  6917  6917 W art     : b5363000-b5364000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
06-30 14:16:20.039  6917  6917 W art     : b5365000-b536b000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 14:16:20.039  6917  6917 W art     : b536b000-b536c000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 14:16:20.039  6917  6917 W art     : b536c000-b536d000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 14:16:20.039  6917  6917 W art     : b536d000-b536f000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5370000-b537a000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 14:16:20.039  6917  6917 W art     : b537a000-b537d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 14:16:20.039  6917  6917 W art     : b537d000-b537e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 14:16:20.039  6917  6917 W art     : b537f000-b5396000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 14:16:20.039  6917  6917 W art     : b5396000-b5397000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5397000-b5398000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 14:16:20.039  6917  6917 W art     : b5398000-b5399000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 14:16:20.039  6917  6917 W art     : b539a000-b53a4000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
06-30 14:16:20.039  6917  6917 W art     : b53a4000-b53a5000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
06-30 14:16:20.039  6917  6917 W art     : b53a5000-b53a6000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
06-30 14:16:20.039  6917  6917 W art     : b53a6000-b53aa000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 14:16:20.039  6917  6917 W art     : b53aa000-b53ab000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 14:16:20.039  6917  6917 W art     : b53ab000-b53ac000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 14:16:20.039  6917  6917 W art     : b53ac000-b53c2000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
06-30 14:16:20.039  6917  6917 W art     : b53c2000-b53c3000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
06-30 14:16:20.039  6917  6917 W art     : b53c3000-b53c4000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
06-30 14:16:20.039  6917  6917 W art     : b53c4000-b53d1000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
06-30 14:16:20.039  6917  6917 W art     : b53d1000-b53d2000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
06-30 14:16:20.039  6917  6917 W art     : b53d2000-b53d3000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
06-30 14:16:20.039  6917  6917 W art     : b53d3000-b5433000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
06-30 14:16:20.039  6917  6917 W art     : b5433000-b5436000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
06-30 14:16:20.039  6917  6917 W art     : b5436000-b543a000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b543a000-b549b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
06-30 14:16:20.039  6917  6917 W art     : b549b000-b549c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
06-30 14:16:20.039  6917  6917 W art     : b549c000-b54eb000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
06-30 14:16:20.039  6917  6917 W art     : b54eb000-b54ed000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
06-30 14:16:20.039  6917  6917 W art     : b54ed000-b54ee000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
06-30 14:16:20.039  6917  6917 W art     : b54ee000-b54ef000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b54ef000-b54f6000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 14:16:20.039  6917  6917 W art     : b54f6000-b54f7000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 14:16:20.039  6917  6917 W art     : b54f7000-b54f8000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 14:16:20.039  6917  6917 W art     : b54f9000-b54fc000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 14:16:20.039  6917  6917 W art     : b54fc000-b54fd000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 14:16:20.039  6917  6917 W art     : b54fd000-b54fe000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 14:16:20.039  6917  6917 W art     : b54ff000-b5503000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
06-30 14:16:20.039  6917  6917 W art     : b5503000-b5504000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5504000-b5505000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
06-30 14:16:20.039  6917  6917 W art     : b5505000-b5506000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
06-30 14:16:20.039  6917  6917 W art     : b5507000-b5524000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 14:16:20.039  6917  6917 W art     : b5524000-b5525000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 14:16:20.039  6917  6917 W art     : b5525000-b5526000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 14:16:20.039  6917  6917 W art     : b5527000-b552c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 14:16:20.039  6917  6917 W art     : b552c000-b552d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 14:16:20.039  6917  6917 W art     : b552d000-b552e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 14:16:20.039  6917  6917 W art     : b552f000-b5560000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 14:16:20.039  6917  6917 W art     : b5560000-b5563000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 14:16:20.039  6917  6917 W art     : b5563000-b5564000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 14:16:20.039  6917  6917 W art     : b5565000-b55a0000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
06-30 14:16:20.039  6917  6917 W art     : b55a0000-b55a1000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
06-30 14:16:20.039  6917  6917 W art     : b55a1000-b55a2000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
06-30 14:16:20.039  6917  6917 W art     : b55a3000-b55aa000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
06-30 14:16:20.039  6917  6917 W art     : b55aa000-b55ab000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b55ab000-b55ac000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
06-30 14:16:20.039  6917  6917 W art     : b55ac000-b55ad000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
06-30 14:16:20.039  6917  6917 W art     : b55ad000-b55ae000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b55ae000-b55c5000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
06-30 14:16:20.039  6917  6917 W art     : b55c5000-b55c6000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b55c6000-b55c9000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
06-30 14:16:20.039  6917  6917 W art     : b55c9000-b55ca000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
06-30 14:16:20.039  6917  6917 W art     : b55ca000-b55e9000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
06-30 14:16:20.039  6917  6917 W art     : b55e9000-b55ea000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
06-30 14:16:20.039  6917  6917 W art     : b55ea000-b55eb000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
06-30 14:16:20.039  6917  6917 W art     : b55eb000-b5629000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 14:16:20.039  6917  6917 W art     : b5629000-b562a000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b562a000-b562c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 14:16:20.039  6917  6917 W art     : b562c000-b562d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 14:16:20.039  6917  6917 W art     : b562e000-b5635000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 14:16:20.039  6917  6917 W art     : b5635000-b5636000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 14:16:20.039  6917  6917 W art     : b5636000-b5637000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 14:16:20.039  6917  6917 W art     : b5638000-b563b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 14:16:20.039  6917  6917 W art     : b563b000-b563c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 14:16:20.039  6917  6917 W art     : b563c000-b563d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 14:16:20.039  6917  6917 W art     : b563d000-b5643000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 14:16:20.039  6917  6917 W art     : b5643000-b5644000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5644000-b5645000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 14:16:20.039  6917  6917 W art     : b5645000-b5646000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 14:16:20.039  6917  6917 W art     : b5646000-b564f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
06-30 14:16:20.039  6917  6917 W art     : b564f000-b5650000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
06-30 14:16:20.039  6917  6917 W art     : b5650000-b5651000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
06-30 14:16:20.039  6917  6917 W art     : b5651000-b56e2000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 14:16:20.039  6917  6917 W art     : b56e2000-b56e3000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b56e3000-b56ee000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 14:16:20.039  6917  6917 W art     : b56ee000-b56ef000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 14:16:20.039  6917  6917 W art     : b56f0000-b5702000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
06-30 14:16:20.039  6917  6917 W art     : b5702000-b5703000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
06-30 14:16:20.039  6917  6917 W art     : b5703000-b5704000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
06-30 14:16:20.039  6917  6917 W art     : b5705000-b570a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
06-30 14:16:20.039  6917  6917 W art     : b570a000-b570b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
06-30 14:16:20.039  6917  6917 W art     : b570b000-b570c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
06-30 14:16:20.039  6917  6917 W art     : b570d000-b577a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
06-30 14:16:20.039  6917  6917 W art     : b577a000-b577b000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b577b000-b577d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
06-30 14:16:20.039  6917  6917 W art     : b577d000-b577e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
06-30 14:16:20.039  6917  6917 W art     : b577e000-b577f000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b577f000-b5786000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 14:16:20.039  6917  6917 W art     : b5786000-b5787000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 14:16:20.039  6917  6917 W art     : b5787000-b5788000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 14:16:20.039  6917  6917 W art     : b5789000-b5809000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 14:16:20.039  6917  6917 W art     : b5809000-b580a000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b580a000-b580b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 14:16:20.039  6917  6917 W art     : b580b000-b580c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 14:16:20.039  6917  6917 W art     : b580c000-b5823000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5823000-b585a000 r-xp 00000000 b3:17 3244       /system/vendor/l
06-30 14:16:20.039  6917  6917 W art     : ib/libqc-opt.so
06-30 14:16:20.039  6917  6917 W art     : b585a000-b585b000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 14:16:20.039  6917  6917 W art     : b585b000-b585c000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 14:16:20.039  6917  6917 W art     : b585c000-b5878000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 14:16:20.039  6917  6917 W art     : b5878000-b5879000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 14:16:20.039  6917  6917 W art     : b5879000-b587a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 14:16:20.039  6917  6917 W art     : b587b000-b58dc000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 14:16:20.039  6917  6917 W art     : b58dc000-b58de000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 14:16:20.039  6917  6917 W art     : b58de000-b58df000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 14:16:20.039  6917  6917 W art     : b58e0000-b5907000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
06-30 14:16:20.039  6917  6917 W art     : b5907000-b5908000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5908000-b5909000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
06-30 14:16:20.039  6917  6917 W art     : b5909000-b590a000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
06-30 14:16:20.039  6917  6917 W art     : b590b000-b5913000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 14:16:20.039  6917  6917 W art     : b5913000-b5915000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 14:16:20.039  6917  6917 W art     : b5915000-b5916000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 14:16:20.039  6917  6917 W art     : b5917000-b591a000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
06-30 14:16:20.039  6917  6917 W art     : b591a000-b591b000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
06-30 14:16:20.039  6917  6917 W art     : b591b000-b591c000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
06-30 14:16:20.039  6917  6917 W art     : b591c000-b5920000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
06-30 14:16:20.039  6917  6917 W art     : b5920000-b5921000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5921000-b5922000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
06-30 14:16:20.039  6917  6917 W art     : b5922000-b5923000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
06-30 14:16:20.039  6917  6917 W art     : b5923000-b5933000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
06-30 14:16:20.039  6917  6917 W art     : b5933000-b5934000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
06-30 14:16:20.039  6917  6917 W art     : b5934000-b5935000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
06-30 14:16:20.039  6917  6917 W art     : b5935000-b597b000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b597b000-b5984000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
06-30 14:16:20.039  6917  6917 W art     : b5984000-b5985000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
06-30 14:16:20.039  6917  6917 W art     : b5985000-b5986000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
06-30 14:16:20.039  6917  6917 W art     : b5987000-b598c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
06-30 14:16:20.039  6917  6917 W art     : b598c000-b598d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
06-30 14:16:20.039  6917  6917 W art     : b598d000-b598e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
06-30 14:16:20.039  6917  6917 W art     : b598e000-b5991000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 14:16:20.039  6917  6917 W art     : b5991000-b5992000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5992000-b5993000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 14:16:20.039  6917  6917 W art     : b5993000-b5994000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 14:16:20.039  6917  6917 W art     : b5995000-b59ad000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 14:16:20.039  6917  6917 W art     : b59ad000-b59ae000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b59ae000-b59af000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 14:16:20.039  6917  6917 W art     : b59af000-b59b0000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 14:16:20.039  6917  6917 W art     : b59b1000-b5b4b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
06-30 14:16:20.039  6917  6917 W art     : b5b4b000-b5b4c000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5b4c000-b5b59000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
06-30 14:16:20.039  6917  6917 W art     : b5b59000-b5b5a000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
06-30 14:16:20.039  6917  6917 W art     : b5b5a000-b5b5e000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
06-30 14:16:20.039  6917  6917 W art     : b5b5e000-b5b5f000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5b5f000-b5b60000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
06-30 14:16:20.039  6917  6917 W art     : b5b60000-b5b61000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
06-30 14:16:20.039  6917  6917 W art     : b5b61000-b5b74000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
06-30 14:16:20.039  6917  6917 W art     : b5b74000-b5b75000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
06-30 14:16:20.039  6917  6917 W art     : b5b75000-b5b76000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
06-30 14:16:20.039  6917  6917 W art     : b5b77000-b5bc2000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
06-30 14:16:20.039  6917  6917 W art     : b5bc2000-b5bc3000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
06-30 14:16:20.039  6917  6917 W art     : b5bc3000-b5bc4000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
06-30 14:16:20.039  6917  6917 W art     : b5bc4000-b5bc6000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5bc6000-b5bc7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:16:20.039  6917  6917 W art     : b5bc7000-b5bd8000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 14:16:20.039  6917  6917 W art     : b5bd8000-b5bd9000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5bd9000-b5bda000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 14:16:20.039  6917  6917 W art     : b5bda000-b5bdb000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 14:16:20.039  6917  6917 W art     : b5bdc000-b5be6000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
06-30 14:16:20.039  6917  6917 W art     : b5be6000-b5be8000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
06-30 14:16:20.039  6917  6917 W art     : b5be8000-b5be9000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
06-30 14:16:20.039  6917  6917 W art     : b5be9000-b5c02000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
06-30 14:16:20.039  6917  6917 W art     : b5c02000-b5c03000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
06-30 14:16:20.039  6917  6917 W art     : b5c03000-b5c06000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
06-30 14:16:20.039  6917  6917 W art     : b5c06000-b5c0a000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5c0a000-b5c7e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
06-30 14:16:20.039  6917  6917 W art     : b5c7e000-b5c7f000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5c7f000-b5c82000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
06-30 14:16:20.039  6917  6917 W art     : b5c82000-b5c83000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
06-30 14:16:20.039  6917  6917 W art     : b5c84000-b5c87000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
06-30 14:16:20.039  6917  6917 W art     : b5c87000-b5c88000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
06-30 14:16:20.039  6917  6917 W art     : b5c88000-b5c89000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
06-30 14:16:20.039  6917  6917 W art     : b5c89000-b5c8a000 r--p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5c8a000-b5c8f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 14:16:20.039  6917  6917 W art     : b5c8f000-b5c90000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 14:16:20.039  6917  6917 W art     : b5c90000-b5c91000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 14:16:20.039  6917  6917 W art     : b5c91000-b5c92000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b5c92000-b5c95000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 14:16:20.039  6917  6917 W art     : b5c95000-b5c96000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 14:16:20.039  6917  6917 W art     : b5c96000-b5c97000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 14:16:20.039  6917  6917 W art     : b5c97000-b5c98000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b5c98000-b5c9c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
06-30 14:16:20.039  6917  6917 W art     : b5c9c000-b5c9d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
06-30 14:16:20.039  6917  6917 W art     : b5c9d000-b5c9e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
06-30 14:16:20.039  6917  6917 W art     : b5c9e000-b5c9f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:16:20.039  6917  6917 W art     : b5c9f000-b5ca3000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 14:16:20.039  6917  6917 W art     : b5ca3000-b5ca4000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 14:16:20.039  6917  6917 W art     : b5ca4000-b5ca5000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 14:16:20.039  6917  6917 W art     : b5ca5000-b5ca6000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b5ca6000-b5cb4000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 14:16:20.039  6917  6917 W art     : b5cb4000-b5cb5000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b5cb5000-b5cb6000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 14:16:20.039  6917  6917 W art     : b5cb6000-b5cb7000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 14:16:20.039  6917  6917 W art     : b5cb7000-b5cc1000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 14:16:20.039  6917  6917 W art     : b5cc1000-b5cc4000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 14:16:20.039  6917  6917 W art     : b5cc4000-b5cc5000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 14:16:20.039  6917  6917 W art     : b5cc5000-b5cc6000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b5cc6000-b5cd0000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
06-30 14:16:20.039  6917  6917 W art     : b5cd0000-b5cd3000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
06-30 14:16:20.039  6917  6917 W art     : b5cd3000-b5cd4000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
06-30 14:16:20.039  6917  6917 W art     : b5cd4000-b5cd8000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
06-30 14:16:20.039  6917  6917 W art     : b5cd8000-b5cd9000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
06-30 14:16:20.039  6917  6917 W art     : b5cd9000-b5cda000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
06-30 14:16:20.039  6917  6917 W art     : b5cda000-b5cdb000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b5cdb000-b5ce8000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 14:16:20.039  6917  6917 W art     : b5ce8000-b5cea000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 14:16:20.039  6917  6917 W art     : b5cea000-b5ceb000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 14:16:20.039  6917  6917 W art     : b5ceb000-b60fd000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
06-30 14:16:20.039  6917  6917 W art     : b60fd000-b60fe000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b60fe000-b6107000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
06-30 14:16:20.039  6917  6917 W art     : b6107000-b610b000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
06-30 14:16:20.039  6917  6917 W art     : b610b000-b610c000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b610c000-b6113000 r-xp 00000000 b3:17 2571       /system/lib/libaud
06-30 14:16:20.039  6917  6917 W art     : ioutils.so
06-30 14:16:20.039  6917  6917 W art     : b6113000-b6114000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 14:16:20.039  6917  6917 W art     : b6114000-b6115000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 14:16:20.039  6917  6917 W art     : b6115000-b6116000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6116000-b6131000 r-xp 00000000
06-30 14:16:20.039  6917  6917 W art     :  b3:17 1184       /system/lib/libz.so
06-30 14:16:20.039  6917  6917 W art     : b6131000-b6132000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 14:16:20.039  6917  6917 W art     : b6132000-b6133000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 14:16:20.039  6917  6917 W art     : b6133000-b6134000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6134000-b6180000 r-xp 00000000 b3:17 994        
06-30 14:16:20.039  6917  6917 W art     : /system/lib/libharfbuzz_ng.so
06-30 14:16:20.039  6917  6917 W art     : b6180000-b6181000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6181000-b6182000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 14:16:20.039  6917  6917 W art     : b6182000-b6183000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 14:16:20.039  6917  6917 W art     : b6183000-b6184000 r--p 00000000 00:00 0          [anon:li
06-30 14:16:20.039  6917  6917 W art     : nker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6184000-b6188000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
06-30 14:16:20.039  6917  6917 W art     : b6188000-b6189000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6189000-b618a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
06-30 14:16:20.039  6917  6917 W art     : b618a000-b618b000 rw-p 00005000 b3:17 2681       /system/lib/libu
06-30 14:16:20.039  6917  6917 W art     : sbhost.so
06-30 14:16:20.039  6917  6917 W art     : b618b000-b61c3000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
06-30 14:16:20.039  6917  6917 W art     : b61c3000-b61c4000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
06-30 14:16:20.039  6917  6917 W art     : b61c4000-b61c5000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
06-30 14:16:20.039  6917  6917 W art     : b61c5000-b61c6000 r--p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     :          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b61c6000-b6264000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
06-30 14:16:20.039  6917  6917 W art     : b6264000-b6265000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6265000-b6283000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
06-30 14:16:20.039  6917  6917 W art     : b6283000-b6284000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
06-30 14:16:20.039  6917  6917 W art     : .so
06-30 14:16:20.039  6917  6917 W art     : b6284000-b63f7000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
06-30 14:16:20.039  6917  6917 W art     : b63f7000-b6402000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
06-30 14:16:20.039  6917  6917 W art     : b6402000-b6403000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
06-30 14:16:20.039  6917  6917 W art     : b6403000-b651a000 r-xp 00000000
06-30 14:16:20.039  6917  6917 W art     :  b3:17 2041       /system/lib/libicuuc.so
06-30 14:16:20.039  6917  6917 W art     : b651a000-b6525000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 14:16:20.039  6917  6917 W art     : b6525000-b6526000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 14:16:20.039  6917  6917 W art     : b6526000-b652a000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b652a000-b654e000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
06-30 14:16:20.039  6917  6917 W art     : o
06-30 14:16:20.039  6917  6917 W art     : b654e000-b6550000 r--p 00023000 b3:17 400        /system/lib/libssl.so
06-30 14:16:20.039  6917  6917 W art     : b6550000-b6551000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
06-30 14:16:20.039  6917  6917 W art     : b6551000-b65f7000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
06-30 14:16:20.039  6917  6917 W art     : b65f7000-b6604000 r--p 000a5000 b3:17 13
06-30 14:16:20.039  6917  6917 W art     : 2        /system/lib/libcrypto.so
06-30 14:16:20.039  6917  6917 W art     : b6604000-b6605000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
06-30 14:16:20.039  6917  6917 W art     : b6605000-b6606000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6606000-b6659000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
06-30 14:16:20.039  6917  6917 W art     : b6659000-b665a000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b665a000-b665b000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
06-30 14:16:20.039  6917  6917 W art     : b665b000-b665c000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
06-30 14:16:20.039  6917  6917 W art     : b665c000-b6661000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6661000-b6673000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
06-30 14:16:20.039  6917  6917 W art     : b6673000-b6674000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6674000-b6675000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
06-30 14:16:20.039  6917  6917 W art     : b6675000-b6676000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
06-30 14:16:20.039  6917  6917 W art     : b6676000-b667d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 14:16:20.039  6917  6917 W art     : b667d000-b667e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 14:16:20.039  6917  6917 W art     : b667e000-b667f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 14:16:20.039  6917  6917 W art     : b667f000-b6680000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6680000-b6683000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
06-30 14:16:20.039  6917  6917 W art     : b6683000-b6684000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
06-30 14:16:20.039  6917  6917 W art     : b6684000-b6685000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
06-30 14:16:20.039  6917  6917 W art     : b6685000-b6689000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
06-30 14:16:20.039  6917  6917 W art     : b6689000-b668a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
06-30 14:16:20.039  6917  6917 W art     : b668a000-b668b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
06-30 14:16:20.039  6917  6917 W art     : b668b000-b6699000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
06-30 14:16:20.039  6917  6917 W art     : b6699000-b669a000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b669a000-b669b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
06-30 14:16:20.039  6917  6917 W art     : b669b000-b669c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
06-30 14:16:20.039  6917  6917 W art     : b669c000-b66a5000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 14:16:20.039  6917  6917 W art     : b66a5000-b66a6000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 14:16:20.039  6917  6917 W art     : b66a6000-b66a7000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 14:16:20.039  6917  6917 W art     : b66a7000-b670d000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
06-30 14:16:20.039  6917  6917 W art     : b670d000-b670e000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b670e000-b6710000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
06-30 14:16:20.039  6917  6917 W art     : b6710000-b6719000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
06-30 14:16:20.039  6917  6917 W art     : b6719000-b671c000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b671c000-b67b3000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 14:16:20.039  6917  6917 W art     : b67b3000-b67b5000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 14:16:20.039  6917  6917 W art     : b67b5000-b67b6000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 14:16:20.039  6917  6917 W art     : b67b6000-b67b7000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b67b7000-b6ad8000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
06-30 14:16:20.039  6917  6917 W art     : b6ad8000-b6ad9000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6ad9000-b6af4000 r--p 00321000 b3:17 377        /system/lib/libskia.so
06-30 14:16:20.039  6917  6917 W art     : b6af4000-b6af8000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
06-30 14:16:20.039  6917  6917 W art     : b6af8000-b6afd000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6afd000-b6b05000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 14:16:20.039  6917  6917 W art     : b6b05000-b6b06000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 14:16:20.039  6917  6917 W art     : b6b06000-b6b07000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 14:16:20.039  6917  6917 W art     : b6b07000-b6b35000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 14:16:20.039  6917  6917 W art     : b6b35000-b6b36000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6b36000-b6b3d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 14:16:20.039  6917  6917 W art     : b6b3d000-b6b3e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 14:16:20.039  6917  6917 W art     : b6b3e000-b6b84000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 14:16:20.039  6917  6917 W art     : b6b84000-b6b85000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6b85000-b6b88000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 14:16:20.039  6917  6917 W art     : b6b88000-b6b89000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 14:16:20.039  6917  6917 W art     : b6b89000-b6ba4000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
06-30 14:16:20.039  6917  6917 W art     : b6ba4000-b6ba8000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
06-30 14:16:20.039  6917  6917 W art     : b6ba8000-b6ba9000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
06-30 14:16:20.039  6917  6917 W art     : b6ba9000-b6bf6000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
06-30 14:16:20.039  6917  6917 W art     : b6bf6000-b6bf7000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6bf7000-b6c03000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
06-30 14:16:20.039  6917  6917 W art     : b6c03000-b6c04000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
06-30 14:16:20.039  6917  6917 W art     : b6c04000-b6c11000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
06-30 14:16:20.039  6917  6917 W art     : b6c11000-b6c12000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6c12000-b6c13000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
06-30 14:16:20.039  6917  6917 W art     : b6c13000-b6c14000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
06-30 14:16:20.039  6917  6917 W art     : b6c14000-b6c1c000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
06-30 14:16:20.039  6917  6917 W art     : b6c1c000-b6c1d000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6c1d000-b6c1e000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
06-30 14:16:20.039  6917  6917 W art     : b6c1e000-b6c1f000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
06-30 14:16:20.039  6917  6917 W art     : b6c1f000-b6c26000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 14:16:20.039  6917  6917 W art     : b6c26000-b6c27000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 14:16:20.039  6917  6917 W art     : b6c27000-b6c28000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 14:16:20.039  6917  6917 W art     : b6c28000-b6c3c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
06-30 14:16:20.039  6917  6917 W art     : b6c3c000-b6c3e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
06-30 14:16:20.039  6917  6917 W art     : b6c3e000-b6c3f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
06-30 14:16:20.039  6917  6917 W art     : b6c3f000-b6c67000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
06-30 14:16:20.039  6917  6917 W art     : b6c67000-b6c69000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
06-30 14:16:20.039  6917  6917 W art     : b6c69000-b6c6a000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
06-30 14:16:20.039  6917  6917 W art     : b6c6a000-b6c6d000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
06-30 14:16:20.039  6917  6917 W art     : b6c6d000-b6c6e000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
06-30 14:16:20.039  6917  6917 W art     : b6c6e000-b6c6f000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
06-30 14:16:20.039  6917  6917 W art     : b6c6f000-b6c78000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 14:16:20.039  6917  6917 W art     : b6c78000-b6c79000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 14:16:20.039  6917  6917 W art     : b6c79000-b6c7a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 14:16:20.039  6917  6917 W art     : b6c7a000-b6c9a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 14:16:20.039  6917  6917 W art     : b6c9a000-b6c9b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 14:16:20.039  6917  6917 W art     : b6c9b000-b6c9c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 14:16:20.039  6917  6917 W art     : b6c9c000-b6d0f000 r-xp 00000000 b3:17 860        /system/lib/libc.so
06-30 14:16:20.039  6917  6917 W art     : b6d0f000-b6d13000 r--p 00072000 b3:17 860        /system/lib/libc.so
06-30 14:16:20.039  6917  6917 W art     : b6d13000-b6d16000 rw-p 00076000 b3:17 860        /system/lib/libc.so
06-30 14:16:20.039  6917  6917 W art     : b6d16000-b6d20000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6d20000-b6da8000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 14:16:20.039  6917  6917 W art     : b6da8000-b6da9000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6da9000-b6dad000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 14:16:20.039  6917  6917 W art     : b6dad000-b6dae000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 14:16:20.039  6917  6917 W art     : b6dae000-b6daf000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6daf000-b6dd8000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 14:16:20.039  6917  6917 W art     : b6dd8000-b6dd9000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6dd9000-b6ddc000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 14:16:20.039  6917  6917 W art     : b6ddc000-b6ddd000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 14:16:20.039  6917  6917 W art     : b6ddd000-b6eb7000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 14:16:20.039  6917  6917 W art     : b6eb7000-b6ebe000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 14:16:20.039  6917  6917 W art     : b6ebe000-b6ec6000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 14:16:20.039  6917  6917 W art     : b6ec6000-b6ec7000 rw-p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6ec7000-b6ec8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:16:20.039  6917  6917 W art     : b6ec8000-b6ec9000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 14:16:20.039  6917  6917 W art     : b6ec9000-b6eca000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6eca000-b6ecd000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6ecd000-b6ef2000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
06-30 14:16:20.039  6917  6917 W art     : b6ef2000-b6ef3000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6ef3000-b6efa000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
06-30 14:16:20.039  6917  6917 W art     : b6efa000-b6efb000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
06-30 14:16:20.039  6917  6917 W art     : b6efb000-b6f02000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 14:16:20.039  6917  6917 W art     : b6f02000-b6f03000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 14:16:20.039  6917  6917 W art     : b6f03000-b6f04000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 14:16:20.039  6917  6917 W art     : b6f04000-b6f05000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6f05000-b6f1d000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
06-30 14:16:20.039  6917  6917 W art     : b6f1d000-b6f1e000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6f1e000-b6f1f000 r--p 00018000 b3:17 918        /system/lib/libutils.so
06-30 14:16:20.039  6917  6917 W art     : b6f1f000-b6f20000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
06-30 14:16:20.039  6917  6917 W art     : b6f20000-b6f2e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
06-30 14:16:20.039  6917  6917 W art     : b6f2e000-b6f2f000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6f2f000-b6f30000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
06-30 14:16:20.039  6917  6917 W art     : b6f30000-b6f31000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
06-30 14:16:20.039  6917  6917 W art     : b6f31000-b6f32000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:16:20.039  6917  6917 W art     : b6f32000-b6f34000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6f34000-b6f35000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6f35000-b6f36000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 14:16:20.039  6917  6917 W art     : b6f36000-b6f37000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 14:16:20.039  6917  6917 W art     : b6f37000-b6f38000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 14:16:20.039  6917  6917 W art     : b6f38000-b6f58000 r--s 00000000 00:0b 8200       /dev/__properties__
06-30 14:16:20.039  6917  6917 W art     : b6f58000-b6f59000 r--p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6f59000-b6f5a000 ---p 00000000 00:00 0 
06-30 14:16:20.039  6917  6917 W art     : b6f5a000-b6f5c000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 14:16:20.049  6917  6917 W art     : b6f5c000-b6f5d000 r-xp 00000000 00:00 0          [sigpage]
06-30 14:16:20.049  6917  6917 W art     : b6f5d000-b6f78000 r-xp 00000000 b3:17 2770       /system/bin/linker
06-30 14:16:20.049  6917  6917 W art     : b6f78000-b6f79000 r--p 0001a000 b3:17 2770       /system/bin/linker
06-30 14:16:20.049  6917  6917 W art     : b6f79000-b6f7b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
06-30 14:16:20.049  6917  6917 W art     : b6f7b000-b6f7d000 rw-p 00000000 00:00 0 
06-30 14:16:20.049  6917  6917 W art     : b6f7d000-b6f82000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 14:16:20.049  6917  6917 W art     : b6f82000-b6f83000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 14:16:20.049  6917  6917 W art     : b6f83000-b6f84000 rw-p 00000000 00:00 0 
06-30 14:16:20.049  6917  6917 W art     : beefb000-bef1c000 rw-p 00000000 00:00 0          [stack]
06-30 14:16:20.049  6917  6917 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]

```
