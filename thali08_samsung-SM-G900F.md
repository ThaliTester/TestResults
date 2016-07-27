#### Test 78968685da35147_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
07-27 08:56:56.827   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,--------- beginning of main
07-27 08:56:57.777  2045  2045 E audit   : type=1400 msg=audit(1469602617.777:278): avc:  denied  { execmod } for  pid=6344 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 08:56:57.777  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:57.777  2045  2045 E audit   : type=1300 msg=audit(1469602617.777:278): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f89000 a1=51000 a2=5 a3=4 items=0 ppid=3433 ppcomm=adbd pid=6344 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 08:56:57.777  2045  2045 E audit   : type=1327 msg=audit(1469602617.777:278): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 08:56:57.787  2045  2045 E audit   : type=1320 msg=audit(1469602617.777:278): 
07-27 08:56:57.837  2045  2045 E audit   : type=1400 msg=audit(1469602617.837:279): avc:  denied  { execmod } for  pid=6344 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 08:56:57.837  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:57.837  2045  2045 E audit   : type=1300 msg=audit(1469602617.837:279): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f49000 a1=51000 a2=5 a3=4 items=0 ppid=3433 ppcomm=adbd pid=6344 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 08:56:57.837  2045  2045 E audit   : type=1327 msg=audit(1469602617.837:279): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 08:56:57.847  2045  2045 E audit   : type=1320 msg=audit(1469602617.837:279): 
07-27 08:56:57.887  6344  6344 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:56:57.887  2045  2045 E audit   : type=1400 msg=audit(1469602617.887:280): avc:  denied  { execmod } for  pid=6344 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 08:56:57.887  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:57.887  2045  2045 E audit   : type=1300 msg=audit(1469602617.887:280): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f49000 a1=51000 a2=5 a3=4 items=0 ppid=3433 ppcomm=adbd pid=6344 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 08:56:57.887  2045  2045 E audit   : type=1327 msg=audit(1469602617.887:280): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 08:56:57.887  2045  2045 E audit   : type=1320 msg=audit(1469602617.887:280): 
07-27 08:56:57.897  6344  6344 D AndroidRuntime: CheckJNI is OFF
07-27 08:56:57.897  6344  6344 D AndroidRuntime: readGMSProperty: start
07-27 08:56:57.897  6344  6344 D AndroidRuntime: readGMSProperty: already setted!!
07-27 08:56:57.897  6344  6344 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 08:56:57.897  6344  6344 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 08:56:57.897  6344  6344 D AndroidRuntime: readGMSProperty: end
07-27 08:56:57.897  6344  6344 D AndroidRuntime: addProductProperty: start
07-27 08:56:57.907  6344  6344 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 08:56:57.907  6344  6344 W art     : af0e5000-b200b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-27 08:56:57.907  6344  6344 W art     : b200b000-b427a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-27 08:56:57.907  6344  6344 W art     : b427a000-b427b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-27 08:56:57.907  6344  6344 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 08:56:57.907  6344  6344 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-27 08:56:57.907  6344  6344 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-27 08:56:57.907  6344  6344 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-27 08:56:57.907  6344  6344 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-27 08:56:57.907  6344  6344 W art     : b481a000-b481d000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-27 08:56:57.907  6344  6344 W art     : b481d000-b481e000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-27 08:56:57.907  6344  6344 W art     : b481e000-b481f000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-27 08:56:57.907  6344  6344 W art     : b481f000-b4820000 r--p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b4820000-b4840000 r--s 00000000 00:0b 6714       /dev/__properties__
07-27 08:56:57.907  6344  6344 W art     : b4840000-b5251000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-27 08:56:57.907  6344  6344 W art     : b5251000-b5252000 ---p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b5252000-b529b000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-27 08:56:57.907  6344  6344 W art     : b529b000-b529c000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-27 08:56:57.907  6344  6344 W art     : b529c000-b52a4000 rw-p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b52a4000-b52a5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.907  6344  6344 W art     : b52a5000-b52da000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-27 08:56:57.907  6344  6344 W art     : b52da000-b52db000 ---p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b52db000-b52dc000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-27 08:56:57.907  6344  6344 W art     : b52dc000-b52dd000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-27 08:56:57.907  6344  6344 W art     : b52dd000-b5335000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-27 08:56:57.907  6344  6344 W art     : b5335000-b5336000 ---p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b5336000-b5337000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-27 08:56:57.907  6344  6344 W art     : b5337000-b5338000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-27 08:56:57.907  6344  6344 W art     : b5339000-b533f000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 08:56:57.907  6344  6344 W art     : b533f000-b5340000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 08:56:57.907  6344  6344 W art     : b5340000-b5341000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 08:56:57.907  6344  6344 W art     : b5341000-b5343000 rw-p 00000000 00:00 0 
07-27 08:56:57.907  6344  6344 W art     : b5344000-b534e000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 08:56:57.917  6344  6344 W art     : b534e000-b5351000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 08:56:57.917  6344  6344 W art     : b5351000-b5352000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 08:56:57.917  6344  6344 W art     : b5353000-b536a000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 08:56:57.917  6344  6344 W art     : b536a000-b536b000 ---p 00000000 00:00 0 
07-27 08:56:57.917  6344  6344 W art     : b536b000-b536c000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 08:56:57.917  6344  6344 W art     : b536c000-b536d000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 08:56:57.917  6344  6344 W art     : b536e000-b5378000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-27 08:56:57.917  6344  6344 W art     : b5378000-b5379000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-27 08:56:57.917  6344  6344 W art     : b5379000-b537a000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-27 08:56:57.917  6344  6344 W art     : b537a000-b537e000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 08:56:57.917  6344  6344 W art     : b537e000-b537f000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 08:56:57.917  6344  6344 W art     : b537f000-b5380000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 08:56:57.917  6344  6344 W art     : b5380000-b5396000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-27 08:56:57.917  6344  6344 W art     : b5396000-b5397000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-27 08:56:57.917  6344  6344 W art     : b5397000-b5398000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-27 08:56:57.917  6344  6344 W art     : b5398000-b53a5000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-27 08:56:57.917  6344  6344 W art     : b53a5000-b53a6000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-27 08:56:57.917  6344  6344 W art     : b53a6000-b53a7000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-27 08:56:57.917  6344  6344 W art     : b53a7000-b5407000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-27 08:56:57.917  6344  6344 W art     : b5407000-b540a000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-27 08:56:57.917  6344  6344 W art     : b540a000-b540e000 rw-p 00000000 00:00 0 
07-27 08:56:57.917  6344  6344 W art     : b540e000-b546f000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-27 08:56:57.917  6344  6344 W art     : b546f000-b5470000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-27 08:56:57.917  6344  6344 W art     : b5470000-b54bf000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-27 08:56:57.917  6344  6344 W art     : b54bf000-b54c1000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-27 08:56:57.917  6344  6344 W art     : b54c1000-b54c2000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-27 08:56:57.917  6344  6344 W art     : b54c2000-b54c3000 rw-p 00000000 00:00 0 
07-27 08:56:57.917  6344  6344 W art     : b54c3000-b54ca000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 08:56:57.917  6344  6344 W art     : b54ca000-b54cb000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 08:56:57.917  6344  6344 W art     : b54cb000-b54cc000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 08:56:57.917  6344  6344 W art     : b54cd000-b54d0000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 08:56:57.917  6344  6344 W art     : b54d0000-b54d1000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 08:56:57.917  6344  6344 W art     : b54d1000-b54d2000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 08:56:57.917  6344  6344 W art     : b54d3000-b54d7000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-27 08:56:57.917  6344  6344 W art     : b54d7000-b54d8000 ---p 00000000 00:00 0 
07-27 08:56:57.917  6344  6344 W art     : b54d8000-b54d9000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-27 08:56:57.917  6344  6344 W art     : b54d9000-b54da000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-27 08:56:57.917  6344  6344 W art     : b54db000-b54f8000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 08:56:57.917  6344  6344 W art     : b54f8000-b54f9000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 08:56:57.917  6344  6344 W art     : b54f9000-b54fa000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 08:56:57.917  6344  6344 W art     : b54fb000-b5500000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 08:56:57.917  6344  6344 W art     : b5500000-b5501000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 08:56:57.917  6344  6344 W art     : b5501000-b5502000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 08:56:57.917  6344  6344 W art     : b5503000-b5534000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 08:56:57.917  6344  6344 W art     : b5534000-b5537000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 08:56:57.917  6344  6344 W art     : b5537000-b5538000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 08:56:57.917  6344  6344 W art     : b5539000-b5574000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-27 08:56:57.917  6344  6344 W art     : b5574000-b5575000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-27 08:56:57.917  6344  6344 W art     : b5575000-b5576000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-27 08:56:57.917  6344  6344 W art     : b5577000-b557e000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-27 08:56:57.917  6344  6344 W art     : b557e000-b557f000 ---p 00000000 00:00 0 
07-27 08:56:57.917  6344  6344 W art     : b557f000-b5580000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-27 08:56:57.927  6344  6344 W art     : b5580000-b5581000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-27 08:56:57.927  6344  6344 W art     : b5581000-b5582000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.927  6344  6344 W art     : b5582000-b5599000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-27 08:56:57.927  6344  6344 W art     : b5599000-b559a000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b559a000-b559d000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-27 08:56:57.927  6344  6344 W art     : b559d000-b559e000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-27 08:56:57.927  6344  6344 W art     : b559e000-b55bd000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-27 08:56:57.927  6344  6344 W art     : b55bd000-b55be000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-27 08:56:57.927  6344  6344 W art     : b55be000-b55bf000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-27 08:56:57.927  6344  6344 W art     : b55bf000-b55fd000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-27 08:56:57.927  6344  6344 W art     : b55fd000-b55fe000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b55fe000-b5600000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-27 08:56:57.927  6344  6344 W art     : b5600000-b5601000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-27 08:56:57.927  6344  6344 W art     : b5602000-b5609000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 08:56:57.927  6344  6344 W art     : b5609000-b560a000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 08:56:57.927  6344  6344 W art     : b560a000-b560b000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 08:56:57.927  6344  6344 W art     : b560c000-b560f000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 08:56:57.927  6344  6344 W art     : b560f000-b5610000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 08:56:57.927  6344  6344 W art     : b5610000-b5611000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 08:56:57.927  6344  6344 W art     : b5611000-b5617000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 08:56:57.927  6344  6344 W art     : b5617000-b5618000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5618000-b5619000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 08:56:57.927  6344  6344 W art     : b5619000-b561a000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 08:56:57.927  6344  6344 W art     : b561a000-b5623000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-27 08:56:57.927  6344  6344 W art     : b5623000-b5624000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-27 08:56:57.927  6344  6344 W art     : b5624000-b5625000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-27 08:56:57.927  6344  6344 W art     : b5625000-b56b6000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 08:56:57.927  6344  6344 W art     : b56b6000-b56b7000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b56b7000-b56c2000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 08:56:57.927  6344  6344 W art     : b56c2000-b56c3000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 08:56:57.927  6344  6344 W art     : b56c4000-b56d6000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-27 08:56:57.927  6344  6344 W art     : b56d6000-b56d7000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-27 08:56:57.927  6344  6344 W art     : b56d7000-b56d8000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-27 08:56:57.927  6344  6344 W art     : b56d9000-b56de000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-27 08:56:57.927  6344  6344 W art     : b56de000-b56df000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-27 08:56:57.927  6344  6344 W art     : b56df000-b56e0000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-27 08:56:57.927  6344  6344 W art     : b56e1000-b574e000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-27 08:56:57.927  6344  6344 W art     : b574e000-b574f000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b574f000-b5751000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-27 08:56:57.927  6344  6344 W art     : b5751000-b5752000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-27 08:56:57.927  6344  6344 W art     : b5752000-b5753000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.927  6344  6344 W art     : b5753000-b575a000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 08:56:57.927  6344  6344 W art     : b575a000-b575b000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 08:56:57.927  6344  6344 W art     : b575b000-b575c000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 08:56:57.927  6344  6344 W art     : b575d000-b57dd000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 08:56:57.927  6344  6344 W art     : b57dd000-b57de000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b57de000-b57df000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 08:56:57.927  6344  6344 W art     : b57df000-b57e0000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 08:56:57.927  6344  6344 W art     : b57e0000-b57f7000 rw-p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b57f7000-b582e000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-27 08:56:57.927  6344  6344 W art     : ib/libqc-opt.so
07-27 08:56:57.927  6344  6344 W art     : b582e000-b582f000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 08:56:57.927  6344  6344 W art     : b582f000-b5830000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 08:56:57.927  6344  6344 W art     : b5830000-b584c000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 08:56:57.927  6344  6344 W art     : b584c000-b584d000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 08:56:57.927  6344  6344 W art     : b584d000-b584e000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 08:56:57.927  6344  6344 W art     : b584f000-b58b0000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-27 08:56:57.927  6344  6344 W art     : b58b0000-b58b2000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-27 08:56:57.927  6344  6344 W art     : b58b2000-b58b3000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-27 08:56:57.927  6344  6344 W art     : b58b4000-b58db000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-27 08:56:57.927  6344  6344 W art     : b58db000-b58dc000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b58dc000-b58dd000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-27 08:56:57.927  6344  6344 W art     : b58dd000-b58de000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-27 08:56:57.927  6344  6344 W art     : b58df000-b58e7000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 08:56:57.927  6344  6344 W art     : b58e7000-b58e9000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 08:56:57.927  6344  6344 W art     : b58e9000-b58ea000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 08:56:57.927  6344  6344 W art     : b58eb000-b58ee000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-27 08:56:57.927  6344  6344 W art     : b58ee000-b58ef000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-27 08:56:57.927  6344  6344 W art     : b58ef000-b58f0000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-27 08:56:57.927  6344  6344 W art     : b58f0000-b58f4000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-27 08:56:57.927  6344  6344 W art     : b58f4000-b58f5000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b58f5000-b58f6000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-27 08:56:57.927  6344  6344 W art     : b58f6000-b58f7000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-27 08:56:57.927  6344  6344 W art     : b58f7000-b5907000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-27 08:56:57.927  6344  6344 W art     : b5907000-b5908000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-27 08:56:57.927  6344  6344 W art     : b5908000-b5909000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-27 08:56:57.927  6344  6344 W art     : b5909000-b594f000 rw-p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b594f000-b5958000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-27 08:56:57.927  6344  6344 W art     : b5958000-b5959000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-27 08:56:57.927  6344  6344 W art     : b5959000-b595a000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-27 08:56:57.927  6344  6344 W art     : b595b000-b5960000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-27 08:56:57.927  6344  6344 W art     : b5960000-b5961000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-27 08:56:57.927  6344  6344 W art     : b5961000-b5962000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-27 08:56:57.927  6344  6344 W art     : b5962000-b5965000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 08:56:57.927  6344  6344 W art     : b5965000-b5966000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5966000-b5967000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 08:56:57.927  6344  6344 W art     : b5967000-b5968000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 08:56:57.927  6344  6344 W art     : b5969000-b5981000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 08:56:57.927  6344  6344 W art     : b5981000-b5982000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5982000-b5983000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 08:56:57.927  6344  6344 W art     : b5983000-b5984000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 08:56:57.927  6344  6344 W art     : b5984000-b5985000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:56:57.927  6344  6344 W art     : b5985000-b5b1f000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-27 08:56:57.927  6344  6344 W art     : b5b1f000-b5b20000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5b20000-b5b2d000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-27 08:56:57.927  6344  6344 W art     : b5b2d000-b5b2e000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-27 08:56:57.927  6344  6344 W art     : b5b2e000-b5b32000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-27 08:56:57.927  6344  6344 W art     : b5b32000-b5b33000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5b33000-b5b34000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-27 08:56:57.927  6344  6344 W art     : b5b34000-b5b35000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-27 08:56:57.927  6344  6344 W art     : b5b35000-b5b48000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-27 08:56:57.927  6344  6344 W art     : b5b48000-b5b49000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-27 08:56:57.927  6344  6344 W art     : b5b49000-b5b4a000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-27 08:56:57.927  6344  6344 W art     : b5b4b000-b5b96000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-27 08:56:57.927  6344  6344 W art     : b5b96000-b5b97000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-27 08:56:57.927  6344  6344 W art     : b5b97000-b5b98000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-27 08:56:57.927  6344  6344 W art     : b5b98000-b5b9a000 rw-p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5b9b000-b5bac000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 08:56:57.927  6344  6344 W art     : b5bac000-b5bad000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5bad000-b5bae000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 08:56:57.927  6344  6344 W art     : b5bae000-b5baf000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 08:56:57.927  6344  6344 W art     : b5baf000-b5bb0000 r--p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5bb0000-b5bba000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-27 08:56:57.927  6344  6344 W art     : b5bba000-b5bbc000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-27 08:56:57.927  6344  6344 W art     : b5bbc000-b5bbd000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-27 08:56:57.927  6344  6344 W art     : b5bbd000-b5bd6000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-27 08:56:57.927  6344  6344 W art     : b5bd6000-b5bd7000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-27 08:56:57.927  6344  6344 W art     : b5bd7000-b5bda000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-27 08:56:57.927  6344  6344 W art     : b5bda000-b5bde000 rw-p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5bde000-b5c52000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-27 08:56:57.927  6344  6344 W art     : b5c52000-b5c53000 ---p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5c53000-b5c56000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-27 08:56:57.927  6344  6344 W art     : b5c56000-b5c57000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-27 08:56:57.927  6344  6344 W art     : b5c57000-b5c58000 r--p 00000000 00:00 0 
07-27 08:56:57.927  6344  6344 W art     : b5c58000-b5c5b000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-27 08:56:57.927  6344  6344 W art     : b5c5b000-b5c5c000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-27 08:56:57.927  6344  6344 W art     : b5c5c000-b5c5d000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-27 08:56:57.937  6344  6344 W art     : b5c5d000-b5c5e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b5c5e000-b5c63000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 08:56:57.937  6344  6344 W art     : b5c63000-b5c64000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 08:56:57.937  6344  6344 W art     : b5c64000-b5c65000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 08:56:57.937  6344  6344 W art     : b5c65000-b5c66000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b5c66000-b5c69000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 08:56:57.937  6344  6344 W art     : b5c69000-b5c6a000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 08:56:57.937  6344  6344 W art     : b5c6a000-b5c6b000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 08:56:57.937  6344  6344 W art     : b5c6b000-b5c6c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b5c6c000-b5c70000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-27 08:56:57.937  6344  6344 W art     : b5c70000-b5c71000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-27 08:56:57.937  6344  6344 W art     : b5c71000-b5c72000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-27 08:56:57.937  6344  6344 W art     : b5c72000-b5c73000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:56:57.937  6344  6344 W art     : b5c73000-b5c77000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 08:56:57.937  6344  6344 W art     : b5c77000-b5c78000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 08:56:57.937  6344  6344 W art     : b5c78000-b5c79000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 08:56:57.937  6344  6344 W art     : b5c79000-b5c7a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b5c7a000-b5c88000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-27 08:56:57.937  6344  6344 W art     : b5c88000-b5c89000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b5c89000-b5c8a000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-27 08:56:57.937  6344  6344 W art     : b5c8a000-b5c8b000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-27 08:56:57.937  6344  6344 W art     : b5c8b000-b5c95000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 08:56:57.937  6344  6344 W art     : b5c95000-b5c98000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 08:56:57.937  6344  6344 W art     : b5c98000-b5c99000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 08:56:57.937  6344  6344 W art     : b5c99000-b5c9a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b5c9a000-b5ca4000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-27 08:56:57.937  6344  6344 W art     : b5ca4000-b5ca7000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-27 08:56:57.937  6344  6344 W art     : b5ca7000-b5ca8000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-27 08:56:57.937  6344  6344 W art     : b5ca8000-b5cac000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-27 08:56:57.937  6344  6344 W art     : b5cac000-b5cad000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-27 08:56:57.937  6344  6344 W art     : b5cad000-b5cae000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-27 08:56:57.937  6344  6344 W art     : b5cae000-b5caf000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b5caf000-b5cbc000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-27 08:56:57.937  6344  6344 W art     : b5cbc000-b5cbe000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-27 08:56:57.937  6344  6344 W art     : b5cbe000-b5cbf000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-27 08:56:57.937  6344  6344 W art     : b5cbf000-b60d1000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-27 08:56:57.937  6344  6344 W art     : b60d1000-b60d2000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b60d2000-b60db000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-27 08:56:57.937  6344  6344 W art     : b60db000-b60df000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-27 08:56:57.937  6344  6344 W art     : b60df000-b60e0000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b60e0000-b60e7000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-27 08:56:57.937  6344  6344 W art     : b60e7000-b60e8000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-27 08:56:57.937  6344  6344 W art     : b60e8000-b60e9000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-27 08:56:57.937  6344  6344 W art     : b60e9000-b60ea000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b60ea000-b6105000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-27 08:56:57.937  6344  6344 W art     : b6105000-b6106000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-27 08:56:57.937  6344  6344 W art     : b6106000-b6107000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-27 08:56:57.937  6344  6344 W art     : b6107000-b6108000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6108000-b6154000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 08:56:57.937  6344  6344 W art     : b6154000-b6155000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6155000-b6156000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 08:56:57.937  6344  6344 W art     : b6156000-b6157000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 08:56:57.937  6344  6344 W art     : b6157000-b6158000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6158000-b615c000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-27 08:56:57.937  6344  6344 W art     : b615c000-b615d000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b615d000-b615e000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-27 08:56:57.937  6344  6344 W art     : b615e000-b615f000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-27 08:56:57.937  6344  6344 W art     : b615f000-b6197000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-27 08:56:57.937  6344  6344 W art     : b6197000-b6198000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-27 08:56:57.937  6344  6344 W art     : b6198000-b6199000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-27 08:56:57.937  6344  6344 W art     : b6199000-b619a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b619a000-b6238000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-27 08:56:57.937  6344  6344 W art     : b6238000-b6239000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6239000-b6257000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-27 08:56:57.937  6344  6344 W art     : b6257000-b6258000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-27 08:56:57.937  6344  6344 W art     : b6258000-b63cb000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-27 08:56:57.937  6344  6344 W art     : b63cb000-b63d6000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-27 08:56:57.937  6344  6344 W art     : b63d6000-b63d7000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-27 08:56:57.937  6344  6344 W art     : b63d7000-b64ee000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-27 08:56:57.937  6344  6344 W art     : b64ee000-b64f9000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-27 08:56:57.937  6344  6344 W art     : b64f9000-b64fa000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-27 08:56:57.937  6344  6344 W art     : b64fa000-b64fe000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b64fe000-b6522000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-27 08:56:57.937  6344  6344 W art     : b6522000-b6524000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-27 08:56:57.937  6344  6344 W art     : b6524000-b6525000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-27 08:56:57.937  6344  6344 W art     : b6525000-b65cb000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-27 08:56:57.937  6344  6344 W art     : b65cb000-b65d8000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-27 08:56:57.937  6344  6344 W art     : b65d8000-b65d9000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-27 08:56:57.937  6344  6344 W art     : b65d9000-b65da000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b65da000-b662d000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-27 08:56:57.937  6344  6344 W art     : b662d000-b662e000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b662e000-b662f000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-27 08:56:57.937  6344  6344 W art     : b662f000-b6630000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-27 08:56:57.937  6344  6344 W art     : b6630000-b6635000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6635000-b6647000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-27 08:56:57.937  6344  6344 W art     : b6647000-b6648000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6648000-b6649000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-27 08:56:57.937  6344  6344 W art     : b6649000-b664a000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-27 08:56:57.937  6344  6344 W art     : b664a000-b6651000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 08:56:57.937  6344  6344 W art     : b6651000-b6652000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 08:56:57.937  6344  6344 W art     : b6652000-b6653000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 08:56:57.937  6344  6344 W art     : b6653000-b6654000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6654000-b6657000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-27 08:56:57.937  6344  6344 W art     : b6657000-b6658000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-27 08:56:57.937  6344  6344 W art     : b6658000-b6659000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-27 08:56:57.937  6344  6344 W art     : b6659000-b665d000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-27 08:56:57.937  6344  6344 W art     : b665d000-b665e000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-27 08:56:57.937  6344  6344 W art     : b665e000-b665f000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-27 08:56:57.937  6344  6344 W art     : b665f000-b666d000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-27 08:56:57.937  6344  6344 W art     : b666d000-b666e000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b666e000-b666f000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-27 08:56:57.937  6344  6344 W art     : b666f000-b6670000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-27 08:56:57.937  6344  6344 W art     : b6670000-b6679000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 08:56:57.937  6344  6344 W art     : b6679000-b667a000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 08:56:57.937  6344  6344 W art     : b667a000-b667b000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 08:56:57.937  6344  6344 W art     : b667b000-b66e1000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-27 08:56:57.937  6344  6344 W art     : b66e1000-b66e2000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b66e2000-b66e4000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-27 08:56:57.937  6344  6344 W art     : b66e4000-b66ed000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-27 08:56:57.937  6344  6344 W art     : b66ed000-b66f0000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b66f0000-b6787000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-27 08:56:57.937  6344  6344 W art     : b6787000-b6789000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-27 08:56:57.937  6344  6344 W art     : b6789000-b678a000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-27 08:56:57.937  6344  6344 W art     : b678a000-b678b000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b678b000-b6aac000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-27 08:56:57.937  6344  6344 W art     : b6aac000-b6aad000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6aad000-b6ac8000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-27 08:56:57.937  6344  6344 W art     : b6ac8000-b6acc000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-27 08:56:57.937  6344  6344 W art     : b6acc000-b6ad1000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6ad1000-b6ad9000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 08:56:57.937  6344  6344 W art     : b6ad9000-b6ada000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 08:56:57.937  6344  6344 W art     : b6ada000-b6adb000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 08:56:57.937  6344  6344 W art     : b6adb000-b6b09000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-27 08:56:57.937  6344  6344 W art     : b6b09000-b6b0a000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6b0a000-b6b11000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-27 08:56:57.937  6344  6344 W art     : b6b11000-b6b12000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-27 08:56:57.937  6344  6344 W art     : b6b12000-b6b58000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-27 08:56:57.937  6344  6344 W art     : b6b58000-b6b59000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6b59000-b6b5c000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-27 08:56:57.937  6344  6344 W art     : b6b5c000-b6b5d000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-27 08:56:57.937  6344  6344 W art     : b6b5d000-b6b78000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-27 08:56:57.937  6344  6344 W art     : b6b78000-b6b7c000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-27 08:56:57.937  6344  6344 W art     : b6b7c000-b6b7d000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-27 08:56:57.937  6344  6344 W art     : b6b7d000-b6bca000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-27 08:56:57.937  6344  6344 W art     : b6bca000-b6bcb000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6bcb000-b6bd7000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-27 08:56:57.937  6344  6344 W art     : b6bd7000-b6bd8000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-27 08:56:57.937  6344  6344 W art     : b6bd8000-b6be5000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-27 08:56:57.937  6344  6344 W art     : b6be5000-b6be6000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6be6000-b6be7000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-27 08:56:57.937  6344  6344 W art     : b6be7000-b6be8000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-27 08:56:57.937  6344  6344 W art     : b6be8000-b6bf0000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-27 08:56:57.937  6344  6344 W art     : b6bf0000-b6bf1000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6bf1000-b6bf2000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-27 08:56:57.937  6344  6344 W art     : b6bf2000-b6bf3000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-27 08:56:57.937  6344  6344 W art     : b6bf3000-b6bfa000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-27 08:56:57.937  6344  6344 W art     : b6bfa000-b6bfb000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-27 08:56:57.937  6344  6344 W art     : b6bfb000-b6bfc000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-27 08:56:57.937  6344  6344 W art     : b6bfc000-b6c10000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-27 08:56:57.937  6344  6344 W art     : b6c10000-b6c12000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-27 08:56:57.937  6344  6344 W art     : b6c12000-b6c13000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-27 08:56:57.937  6344  6344 W art     : b6c13000-b6c3b000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-27 08:56:57.937  6344  6344 W art     : b6c3b000-b6c3d000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-27 08:56:57.937  6344  6344 W art     : b6c3d000-b6c3e000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-27 08:56:57.937  6344  6344 W art     : b6c3e000-b6c41000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-27 08:56:57.937  6344  6344 W art     : b6c41000-b6c42000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-27 08:56:57.937  6344  6344 W art     : b6c42000-b6c43000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-27 08:56:57.937  6344  6344 W art     : b6c43000-b6c4c000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-27 08:56:57.937  6344  6344 W art     : b6c4c000-b6c4d000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-27 08:56:57.937  6344  6344 W art     : b6c4d000-b6c4e000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-27 08:56:57.937  6344  6344 W art     : b6c4e000-b6c6e000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-27 08:56:57.937  6344  6344 W art     : b6c6e000-b6c6f000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-27 08:56:57.937  6344  6344 W art     : b6c6f000-b6c70000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-27 08:56:57.937  6344  6344 W art     : b6c70000-b6ce3000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-27 08:56:57.937  6344  6344 W art     : b6ce3000-b6ce7000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-27 08:56:57.937  6344  6344 W art     : b6ce7000-b6cea000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-27 08:56:57.937  6344  6344 W art     : b6cea000-b6cf4000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6cf4000-b6d7c000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-27 08:56:57.937  6344  6344 W art     : b6d7c000-b6d7d000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6d7d000-b6d81000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-27 08:56:57.937  6344  6344 W art     : b6d81000-b6d82000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-27 08:56:57.937  6344  6344 W art     : b6d82000-b6d83000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6d83000-b6dac000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-27 08:56:57.937  6344  6344 W art     : b6dac000-b6dad000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6dad000-b6db0000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-27 08:56:57.937  6344  6344 W art     : b6db0000-b6db1000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-27 08:56:57.937  6344  6344 W art     : b6db1000-b6e8b000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 08:56:57.937  6344  6344 W art     : b6e8b000-b6e92000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 08:56:57.937  6344  6344 W art     : b6e92000-b6e9a000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 08:56:57.937  6344  6344 W art     : b6e9a000-b6e9b000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6e9b000-b6e9c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:56:57.937  6344  6344 W art     : b6e9c000-b6e9d000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-27 08:56:57.937  6344  6344 W art     : b6e9d000-b6e9e000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6e9e000-b6ea1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6ea1000-b6ec6000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-27 08:56:57.937  6344  6344 W art     : b6ec6000-b6ec7000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6ec7000-b6ece000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-27 08:56:57.937  6344  6344 W art     : b6ece000-b6ecf000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-27 08:56:57.937  6344  6344 W art     : b6ecf000-b6ed6000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-27 08:56:57.937  6344  6344 W art     : b6ed6000-b6ed7000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-27 08:56:57.937  6344  6344 W art     : b6ed7000-b6ed8000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-27 08:56:57.937  6344  6344 W art     : b6ed8000-b6ed9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6ed9000-b6ef1000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-27 08:56:57.937  6344  6344 W art     : b6ef1000-b6ef2000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6ef2000-b6ef3000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-27 08:56:57.937  6344  6344 W art     : b6ef3000-b6ef4000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-27 08:56:57.937  6344  6344 W art     : b6ef4000-b6f02000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-27 08:56:57.937  6344  6344 W art     : b6f02000-b6f03000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6f03000-b6f04000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-27 08:56:57.937  6344  6344 W art     : b6f04000-b6f05000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-27 08:56:57.937  6344  6344 W art     : b6f05000-b6f06000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:56:57.937  6344  6344 W art     : b6f06000-b6f08000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6f08000-b6f09000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6f09000-b6f0a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 08:56:57.937  6344  6344 W art     : b6f0a000-b6f0b000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-27 08:56:57.937  6344  6344 W art     : b6f0b000-b6f0c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 08:56:57.937  6344  6344 W art     : b6f0c000-b6f2c000 r--s 00000000 00:0b 6714       /dev/__properties__
07-27 08:56:57.937  6344  6344 W art     : b6f2c000-b6f2d000 r--p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6f2d000-b6f2e000 ---p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6f2e000-b6f30000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-27 08:56:57.937  6344  6344 W art     : b6f30000-b6f31000 r-xp 00000000 00:00 0          [sigpage]
07-27 08:56:57.937  6344  6344 W art     : b6f31000-b6f4c000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-27 08:56:57.937  6344  6344 W art     : b6f4c000-b6f4d000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-27 08:56:57.937  6344  6344 W art     : b6f4d000-b6f4f000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-27 08:56:57.937  6344  6344 W art     : b6f4f000-b6f51000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : b6f51000-b6f56000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-27 08:56:57.937  6344  6344 W art     : b6f56000-b6f57000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-27 08:56:57.937  6344  6344 W art     : b6f57000-b6f58000 rw-p 00000000 00:00 0 
07-27 08:56:57.937  6344  6344 W art     : bee63000-bee84000 rw-p 00000000 00:00 0          [stack]
07-27 08:56:57.937  6344  6344 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-27 08:56:57.997  6344  6344 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:56:58.057  6344  6344 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:56:58.057  6344  6344 E AffinityControl: AffinityControl: registerfunction enter
07-27 08:56:58.077  6344  6344 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:56:58.097   753  2013 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-27 08:56:58.107   753  2013 D ActivityManager: mDVFSHelper.acquire()
07-27 08:56:58.107   753  2013 V WindowManager: addAppToken: AppWindowToken{e905545 token=Token{e8ca1bc ActivityRecord{b4709af u0 com.test.thalitest/.MainActivity t115}}} to stack=1 task=115 at 0
07-27 08:56:58.117   753   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f90e7fd V.E...... R.....ID 0,0-0,0}
07-27 08:56:58.117   753   891 D SecWifiDisplayUtil: Metadata value : none
07-27 08:56:58.117   753   891 D ISSUE_DEBUG: InputChannelName : 9f36f43 Starting com.test.thalitest
07-27 08:56:58.127  6359  6359 E Zygote  : v2
07-27 08:56:58.127  6359  6359 I libpersona: KNOX_SDCARD checking this for 10004
07-27 08:56:58.127  6359  6359 I libpersona: KNOX_SDCARD not a persona
07-27 08:56:58.127   753  2013 I ActivityManager: Start proc 6359:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-27 08:56:58.127   753  2013 D InputDispatcher: Focused application set to: xxxx
07-27 08:56:58.137   753  2013 D InputDispatcher: Focus left window: 3343
07-27 08:56:58.137   753   831 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2d320c4 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-27 08:56:58.137  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-27 08:56:58.137   753  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 08:56:58.137  6344  6344 D AndroidRuntime: Shutting down VM
07-27 08:56:58.137  6359  6359 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:56:58.137  6359  6359 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:58.137  6359  6359 E Zygote  : accessInfo : 0
07-27 08:56:58.137  6359  6359 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-27 08:56:58.147   294   294 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
07-27 08:56:58.157   753   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:753 uid:1000
07-27 08:56:58.157   753   891 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:56:58.157   753   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:753 uid:1000
07-27 08:56:58.157   753   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 08:56:58.157   753   891 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-27 08:56:58.167  6359  6359 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:58.167  6359  6359 D ActivityThread: Added TimaKeyStore provider
07-27 08:56:58.177   753  1417 V WindowOrientationListener: setCurrentAppOrientation :-1
07-27 08:56:58.177   753  1417 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-27 08:56:58.177   753   831 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9f36f43 u0 d0 Starting com.test.thalitest}
07-27 08:56:58.177  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-27 08:56:58.197   753  1417 D ActivityManager:  Launching com.test.thalitest, updated priority
07-27 08:56:58.197   753   891 V WindowStateAnimator: Finishing drawing window Window{9f36f43 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-27 08:56:58.207   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8b2364
07-27 08:56:58.207   753   827 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-27 08:56:58.217  1732  1883 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-27 08:56:58.217  1732  1732 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-27 08:56:58.227   294   328 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
07-27 08:56:58.227   294  1507 I SurfaceFlinger: id=18 Removed VSBConnecti (7/11)
07-27 08:56:58.237   294   331 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
,07-27 08:56:58.237   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8b23a4
07-27 08:56:58.237   294  1507 D libEGL  : eglTerminate EGLDisplay = 0xb47ef64c
07-27 08:56:58.237   294  1507 D libEGL  : eglTerminate EGLDisplay = 0xb47ef64c
07-27 08:56:58.237   294  1299 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
07-27 08:56:58.247   294   331 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
07-27 08:56:58.247   294   331 I SurfaceFlinger: id=19 Removed VSBConnecti (4/9)
07-27 08:56:58.247   294  1299 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/9)
07-27 08:56:58.247  2291  2311 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-27 08:56:58.247  1732  1732 D Launcher: onTrimMemory. Level: 20
07-27 08:56:58.247  1732  1732 V ActivityThread: updateVisibility : ActivityRecord{57f50ec token=android.os.BinderProxy@fe516ee {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 08:56:58.247  3343  3343 V ActivityThread: updateVisibility : ActivityRecord{e6c023d token=android.os.BinderProxy@450c1ef {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-27 08:56:58.247   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8b23a4
07-27 08:56:58.257   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8b23a4
07-27 08:56:58.347   753  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-27 08:56:58.367   753  3282 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:58.377  6359  6359 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:56:58.407  6359  6359 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:56:58.407  6359  6359 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:56:58.427  6359  6359 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-27 08:56:58.457   753   764 I art     : Background partial concurrent mark sweep GC freed 44659(3MB) AllocSpace objects, 77(1540KB) LOS objects, 27% free, 41MB/57MB, paused 1.745ms total 130.856ms
,07-27 08:56:58.457  6359  6359 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 08:56:58.467  6359  6359 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 08:56:58.477  6359  6359 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 8379-8383)
,07-27 08:56:58.477  6359  6359 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 08:56:58.497  6359  6359 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a52a9b9}
,07-27 08:56:58.497  6359  6359 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-27 08:56:58.497  6359  6359 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:56:58.497  6359  6384 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-27 08:56:58.507  6359  6359 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-27 08:56:58.527  6359  6385 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-27 08:56:58.537  6359  6359 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:56:58.537  6359  6359 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:56:58.537  6359  6359 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:56:58.537  6359  6359 I Adreno-EGL: Local Branch: ss
07-27 08:56:58.537  6359  6359 I Adreno-EGL: Remote Branch: 
07-27 08:56:58.537  6359  6359 I Adreno-EGL: Local Patches: 
07-27 08:56:58.537  6359  6359 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:56:58.537  6359  6359 D libEGL  : eglInitialize EGLDisplay = 0xbef7adac
,07-27 08:56:58.567   753  1320 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,07-27 08:56:58.567   753  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-27 08:56:58.617  6359  6359 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 08:56:58.627  6359  6359 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:56:58.627  6359  6359 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-27 08:56:58.627  6359  6359 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 08:56:58.627  6359  6359 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 08:56:58.647  6359  6359 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-27 08:56:58.657  6359  6359 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-27 08:56:58.747  6359  6359 D SecWifiDisplayUtil: Metadata value : none
,07-27 08:56:58.747  6359  6359 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{676973f I.E...... R.....ID 0,0-0,0}
,07-27 08:56:58.747  6359  6413 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 08:56:58.757   753  1677 D ISSUE_DEBUG: InputChannelName : bdda4b4 com.test.thalitest/com.test.thalitest.MainActivity
,07-27 08:56:58.757   753  2167 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,07-27 08:56:58.757   753  2167 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:56:58.757   753   753 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 08:56:58.757   753   753 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-27 08:56:58.767  6359  6359 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6359
,07-27 08:56:58.767   753  1747 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6359 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:56:58.777  6359  6359 D SecWifiDisplayUtil: Metadata value : none
,07-27 08:56:58.787  6359  6384 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-27 08:56:58.787   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,07-27 08:56:58.797   753  1677 D InputDispatcher: Focus entered window: 6359
,07-27 08:56:58.807   753   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:753 uid:1000
,07-27 08:56:58.807  6359  6413 D libEGL  : eglInitialize EGLDisplay = 0x9d6d47c4
07-27 08:56:58.807  6359  6413 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:56:58.807   753   891 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:56:58.807   753   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:753 uid:1000
07-27 08:56:58.807   753   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 08:56:58.847  6359  6359 V ActivityThread: updateVisibility : ActivityRecord{61558f8 token=android.os.BinderProxy@49f275e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-27 08:56:58.847  6359  6359 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-27 08:56:58.857  6359  6359 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 08:56:58.857   753   769 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 08:56:58.867  6359  6359 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 08:56:58.887   753  1623 V WindowStateAnimator: Finishing drawing window Window{bdda4b4 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-27 08:56:58.887  6359  6359 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 08:56:58.897   753   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 08:56:58.897   753   753 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:56:58.897   753   753 I KnoxTimeoutHandler: SD activityfalse
,07-27 08:56:58.897  6359  6359 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@49f275e time:258803
,07-27 08:56:58.897   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8b2364
,07-27 08:56:58.897   753   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +555ms (total +791ms)
,07-27 08:56:58.897   753   891 D ActivityManager: mDVFSHelper.release()
07-27 08:56:58.897   753   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b4709af u0 com.test.thalitest/.MainActivity t115} time:258808
07-27 08:56:58.897   753   891 D ViewRootImpl: #3 mView = null
,07-27 08:56:58.897   294   331 I SurfaceFlinger: id=20 Removed uhalitest (7/9)
,07-27 08:56:58.907   294  1299 I SurfaceFlinger: id=20 Removed uhalitest (-2/9)
,07-27 08:56:58.907  6359  6421 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-27 08:56:58.907  6359  6421 D libEGL  : eglInitialize EGLDisplay = 0x9baff3ec
,07-27 08:56:58.917   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8b23a4
,07-27 08:56:58.947  6359  6359 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6359
,07-27 08:56:59.077  6359  6359 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:56:59.167  6359  6426 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1689519824
,07-27 08:56:59.167  6359  6426 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:56:59.167  6359  6426 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:56:59.167  6359  6426 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:56:59.167  6359  6426 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:56:59.167  6359  6426 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:56:59.167  6359  6426 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c12240e added. We now have 1 listener(s)
,07-27 08:56:59.177  6359  6426 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,07-27 08:56:59.177  6359  6426 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,07-27 08:56:59.177  6359  6426 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:56:59.177  6359  6426 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 08:56:59.177  6359  6426 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d27edc5 added. We now have 1 listener(s)
07-27 08:56:59.177  6359  6426 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:56:59.177  6359  6426 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:56:59.177  6359  6426 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-27 08:56:59.177  6359  6426 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 08:56:59.187  6359  6426 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:56:59.187  6359  6426 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:56:59.187  6359  6426 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 08:56:59.187  6359  6426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 08:56:59.187  6359  6426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,07-27 08:56:59.187  6359  6426 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:56:59.187  6359  6426 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:56:59.187  6359  6426 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-27 08:56:59.187  6359  6426 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:56:59.187  6359  6426 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 08:56:59.207  6359  6359 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:56:59.347   753  3288 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-27 08:56:59.757  1454  1454 D Recents : onTaskStackChanged
,07-27 08:56:59.767  1454  1454 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-27 08:56:59.817  6359  6430 W jxcore-log: Initializing JXcore engine
07-27 08:56:59.817  6359  6430 W jxcore-log: JXcore engine is ready
,07-27 08:56:59.867  2045  2045 E audit   : type=1400 msg=audit(1469602619.867:281): avc:  denied  { ioctl } for  pid=6430 comm="Thread-899" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 08:56:59.867  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:59.867  2045  2045 E audit   : type=1300 msg=audit(1469602619.867:281): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9b3b73c8 items=0 ppid=353 ppcomm=main pid=6430 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:56:59.867  2045  2045 E audit   : type=1327 msg=audit(1469602619.867:281): proctitle="com.test.thalitest"
07-27 08:56:59.867  2045  2045 E audit   : type=1320 msg=audit(1469602619.867:281): 
,07-27 08:56:59.867  2045  2045 E audit   : type=1400 msg=audit(1469602619.867:282): avc:  denied  { ioctl } for  pid=6430 comm="Thread-899" path="socket:[37876]" dev="sockfs" ino=37876 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-27 08:56:59.867  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:59.867  2045  2045 E audit   : type=1300 msg=audit(1469602619.867:282): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=2 a3=9b3b73c8 items=0 ppid=353 ppcomm=main pid=6430 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:56:59.867  2045  2045 E audit   : type=1327 msg=audit(1469602619.867:282): proctitle="com.test.thalitest"
07-27 08:56:59.867  2045  2045 E audit   : type=1320 msg=audit(1469602619.867:282): 
,07-27 08:56:59.877  6359  6430 W jxcore-log: Starting JXcore engine
,07-27 08:56:59.957  6359  6430 W jxcore-log: Platform android
07-27 08:56:59.957  6359  6430 W jxcore-log: 
,07-27 08:56:59.957  6359  6430 W jxcore-log: Process ARCH arm
07-27 08:56:59.957  6359  6430 W jxcore-log: 
,07-27 08:57:00.117  6359  6430 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:57:00.117  6359  6430 I jxcore-log: 
,07-27 08:57:00.117  6359  6430 W jxcore-log: JXcore engine is started
,07-27 08:57:00.127  6359  6426 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:57:00.127  6359  6359 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:57:01.157   753  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/115_task.xml.bak
,07-27 08:57:03.597   753  1417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:03.607   753  1417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 08:57:03.607   753  1417 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-27 08:57:03.607   753  1417 D BatteryService: stay LED for fully charged
07-27 08:57:03.607   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:03.607   753   753 I MotionRecognitionService: Plugged
07-27 08:57:03.607   753   753 D MotionRecognitionService:   cableConnection= 1
07-27 08:57:03.607   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:57:03.607   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:57:03.607  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:03.607  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:03.607  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:03.607  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:03.607  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:03.627  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:04.397   753  3282 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:06.877   753  3282 D SSRM:n  : SIOP:: AP = 330, PST = 305, CUR = 450, LCD = 0
,07-27 08:57:08.137   753   917 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 08:57:08.157   753   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-27 08:57:08.797   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:10.367  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:57:10.367  6359  6430 I jxcore-log: 
,07-27 08:57:10.367  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:57:10.367  6359  6430 I jxcore-log: 
,07-27 08:57:10.367  6359  6430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:10.367  6359  6430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:57:10.367  6359  6430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:57:10.367  6359  6430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:57:10.377  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:57:10.377  6359  6430 I jxcore-log: 
,07-27 08:57:10.377  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:57:10.377  6359  6430 I jxcore-log: 
,07-27 08:57:10.717  6359  6430 I jxcore-log: Unit Test app is loaded
07-27 08:57:10.717  6359  6430 I jxcore-log: 
,07-27 08:57:10.717  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:57:10.717  6359  6430 I jxcore-log: 
,07-27 08:57:10.727  6359  6359 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:57:10.727  6359  6430 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-27 08:57:10.737   753  2167 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-27 08:57:10.737   753  2167 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-27 08:57:10.747   753  2167 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-27 08:57:10.747   753  2167 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-27 08:57:10.747   753  2167 V CAE     : start(ContextProvider.java:128)
,07-27 08:57:10.757   753  2167 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-27 08:57:10.757   753  2167 V CAE     : enable(ActivityTrackerRunner.java:84)
07-27 08:57:10.757   753  2167 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 57, 10,
,07-27 08:57:10.757   753  2167 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 57, 10
,07-27 08:57:10.757   332   576 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 57, 10
,07-27 08:57:10.767   753  2167 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-27 08:57:10.767   753  2167 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 08:57:10.777   753  2167 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-27 08:57:10.777   753  2167 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-27 08:57:10.777   753  2167 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-27 08:57:10.777   753  2167 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@73f6076, Service : ACTIVITY_TRACKER(1)
,07-27 08:57:10.777   753  2167 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-27 08:57:10.777   753  2167 D SContextService: 	.registerCallback : 1, client=
07-27 08:57:10.777   753  2167 D SContextService: ===== SContext Service List =====
07-27 08:57:10.777   753  2167 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@38da2e4, Service : Activity Tracker
07-27 08:57:10.777   753  2167 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@6a43677, service=Activity Tracker
07-27 08:57:10.777   753  2167 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,07-27 08:57:10.777   753  2167 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
07-27 08:57:10.777   753  2167 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-27 08:57:10.777   753  2167 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-27 08:57:10.777   753  2167 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
07-27 08:57:10.777   332   332 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-27 08:57:10.787   753  2167 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-27 08:57:10.787   753  2167 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 08:57:10.797   753  2167 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
,07-27 08:57:10.797   753  2167 D SContextService: requestToUpdate() : service = Activity Tracker
07-27 08:57:10.797   753  2167 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@6a43677, service=Activity Tracker
07-27 08:57:10.797   753  2167 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
07-27 08:57:10.797   753  2167 D WifiService: setWifiEnabled: true pid=6359, uid=10004
,07-27 08:57:10.797   753  1325 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,07-27 08:57:10.807   753  2167 W ActivityManager: Permission Denial: getCurrentUser() from pid=6359, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,07-27 08:57:10.807   753  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18701 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8638 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-27 08:57:10.807   753  1325 D WifiBigDataLog: init : 
,07-27 08:57:10.807   753  2167 W WifiService: Failed getting userId using ActivityManagerNative
07-27 08:57:10.807   753  2167 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6359, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:57:10.807   753  2167 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28165)
07-27 08:57:10.807   753  2167 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2437)
07-27 08:57:10.807   753  2167 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2425)
07-27 08:57:10.807   753  2167 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-27 08:57:10.807   753  2167 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:57:10.807   753  2167 D SettingsProvider: isChangeAllowed() : name = wifi_on
,07-27 08:57:10.807   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b48034d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68eb49d 2085:com.samsung.android.providers.context/u0a174}
,07-27 08:57:10.817   753  1326 D WifiController: [FCC]setFccChannel() is called !!!
07-27 08:57:10.817   753  1326 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-27 08:57:10.817   753  1326 D WifiStateMachine: setFccChannel: channel = 0
,07-27 08:57:10.817   753  1326 D SecContentProvider: insert(), uri = 2
,07-27 08:57:10.817   753  1325 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 08:57:10.827   306  1186 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-27 08:57:10.827   753   769 I WifiService: disconnect: pid=6359, uid=10004
07-27 08:57:10.827   753  1574 E Watchdog: !@Sync 8 [07-27 08:57:10.839]
07-27 08:57:10.827   306  1186 I WifiHW  : module is semco 3RD
07-27 08:57:10.827   306  1186 E WifiHW  : ==========[WIFI] SEMCO 3RD MODULE ===========
07-27 08:57:10.827   306  1186 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_semco3rd
07-27 08:57:10.827   306  1186 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 08:57:10.827   306  1186 D SoftapController: Softap fwReload - Ok
,07-27 08:57:10.827   332   575 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 1, 125, -19, 69, 0, 0
07-27 08:57:10.827  6359  6430 D BluetoothAdapter: enable()
,07-27 08:57:10.837   306  1186 D CommandListener: Setting iface cfg
07-27 08:57:10.837   306  1186 D CommandListener: Trying to bring down wlan0
,07-27 08:57:10.837   753  1239 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 1, 125, -19, 69, 0, 0
,07-27 08:57:10.837   753  1238 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 6, 57, 10,
07-27 08:57:10.837   753  1238 D SensorHubManager: SendSensorHubData: send data = -63, 14, 6, 57, 10
07-27 08:57:10.837   332   576 D Sensorhubs: sendContextData: -63, 14, 6, 57, 10
,07-27 08:57:10.847   306  1186 D CommandListener: Clearing all IP addresses on wlan0
,07-27 08:57:10.847   753  1325 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-27 08:57:10.847   753  1789 W ActivityManager: Permission Denial: getCurrentUser() from pid=6359, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,07-27 08:57:10.847   753  1238 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_SLEEP
07-27 08:57:10.847   753  1238 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
07-27 08:57:10.847   753  1238 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 1, 125, -19, 69, 0, 0,
,07-27 08:57:10.847   753  1238 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-27 08:57:10.847   753  1238 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1469602629957]
,07-27 08:57:10.847   753  1789 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 08:57:10.847   753  1789 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6359, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:57:10.847   753  1789 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28165)
07-27 08:57:10.847   753  1789 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2848)
07-27 08:57:10.847   753  1789 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2838)
07-27 08:57:10.847   753  1789 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1218)
07-27 08:57:10.847   753  1789 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
07-27 08:57:10.847   753  1789 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:57:10.847   753  1789 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:57:10.847   753  1789 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-27 08:57:10.857   753  1241 D SContextService: updateSContext() : event = Activity Tracker
07-27 08:57:10.857   753   753 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,07-27 08:57:10.857   753   753 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-27 08:57:10.857   753   753 D WifiService: setWifiScanWithSensor bMove = 0
07-27 08:57:10.857   753   753 D WifiStateMachine: setWifiScanMove bMove = 0
07-27 08:57:10.857   753   753 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-27 08:57:10.857   753  1789 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,07-27 08:57:10.877  6359  6430 I jxcore-log: My device name is: samsung-SM-G900F
07-27 08:57:10.877  6359  6430 I jxcore-log: 
,07-27 08:57:10.877   753   889 I ActivityManager: Start proc 6448:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 08:57:10.877  6448  6448 E Zygote  : v2
07-27 08:57:10.877  6448  6448 I libpersona: KNOX_SDCARD checking this for 1002
07-27 08:57:10.877  6448  6448 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:10.877  6448  6448 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:10.877  6448  6448 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:10.877  6448  6448 E Zygote  : accessInfo : 0
,07-27 08:57:10.887  6359  6430 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 08:57:10.887  6359  6430 I jxcore-log: 
,07-27 08:57:10.917  6448  6448 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:10.917  6448  6448 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:10.927  6448  6448 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:57:10.947   753  1325 D wifi    : Can not initialize the vendor function pointer table
,07-27 08:57:10.947   753  1325 E WifiNative-HAL: Could not start hal
07-27 08:57:10.947   753  1325 E WifiStateMachine: Failed to start HAL
,07-27 08:57:10.947   753  1325 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 08:57:10.967  6448  6448 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 08:57:11.007  6448  6448 D BtSettings.ProfileConfig: Adding GattService
,07-27 08:57:11.007  6448  6448 D BtSettings.ProfileConfig: Adding HeadsetService
,07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding A2dpService
07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding HidService
07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding HealthService
,07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding PanService
07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding SapService
07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-27 08:57:11.017  6448  6448 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-27 08:57:11.017  6448  6448 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 08:57:11.017   753  1898 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
07-27 08:57:11.017   753  1898 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.017   753  1898 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.017   753  1898 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.017   753  1898 D SettingsProvider: selectionArgs: false
07-27 08:57:11.017   753  1898 D SettingsProvider: selectionArgs: 1002
,07-27 08:57:11.017   753  1898 D SettingsProvider: ret = -1
07-27 08:57:11.017   753  1677 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 08:57:11.017   753  1677 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.017   753  1677 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.017   753  1677 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.017   753  1677 D SettingsProvider: selectionArgs: false
07-27 08:57:11.017   753  1677 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.017   753  1677 D SettingsProvider: ret = -1
,07-27 08:57:11.017   753  1623 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-27 08:57:11.017   753  1623 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.017   753  1623 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.017   753  1623 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.017   753  1623 D SettingsProvider: selectionArgs: false
07-27 08:57:11.017   753  1623 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.017   753  1623 D SettingsProvider: ret = -1
,07-27 08:57:11.017   753  1417 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
07-27 08:57:11.017   753  1417 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.017   753  1417 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.017   753  1417 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.017   753  1417 D SettingsProvider: selectionArgs: false
07-27 08:57:11.017   753  1417 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.017   753  1417 D SettingsProvider: ret = -1
07-27 08:57:11.017   753  2163 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 08:57:11.017   753  2163 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.017   753  2163 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.017   753  2163 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.017   753  2163 D SettingsProvider: selectionArgs: false
07-27 08:57:11.017   753  2163 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.017   753  2163 D SettingsProvider: ret = -1
,07-27 08:57:11.027   753  2167 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
07-27 08:57:11.027   753  2167 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.027   753  2167 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.027   753  2167 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.027   753  2167 D SettingsProvider: selectionArgs: false
07-27 08:57:11.027   753  2167 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.027   753  2167 D SettingsProvider: ret = -1
07-27 08:57:11.027   753  1650 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-27 08:57:11.027   753  1650 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.027   753  1650 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.027   753  1650 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.027   753  1650 D SettingsProvider: selectionArgs: false
07-27 08:57:11.027   753  1650 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.027   753  1650 D SettingsProvider: ret = -1
,07-27 08:57:11.027   753   769 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
07-27 08:57:11.027   753   769 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.027   753   769 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.027   753   769 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.027   753   769 D SettingsProvider: selectionArgs: false
07-27 08:57:11.027  6464  6464 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-27 08:57:11.027   753   769 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.027  6464  6464 I wpa_supplicant: Successfully initialized wpa_supplicant
07-27 08:57:11.027   753   769 D SettingsProvider: ret = -1
07-27 08:57:11.027  6464  6464 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
07-27 08:57:11.027   753  1485 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:11.027   753  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.027   753  1485 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.027   753  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.027   753  1485 D SettingsProvider: selectionArgs: false
07-27 08:57:11.027   753  1485 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.027   753  1485 D SettingsProvider: ret = -1
07-27 08:57:11.027  6464  6464 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 08:57:11.027   753  1320 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:57:11.027   753  1320 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:11.027   753  1320 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:11.027   753  1320 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:11.027   753  1320 D SettingsProvider: selectionArgs: false
07-27 08:57:11.027   753  1320 D SettingsProvider: selectionArgs: 1002
07-27 08:57:11.027   753  1320 D SettingsProvider: ret = -1
07-27 08:57:11.047  6464  6464 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-27 08:57:11.057   385   385 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6464
07-27 08:57:11.057   385   385 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
07-27 08:57:11.057  6464  6464 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:57:11.057  6464  6464 I wpa_supplicant: ssSupport state is = 1
07-27 08:57:11.057  6464  6464 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-27 08:57:11.057  6464  6464 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-27 08:57:11.057   385   385 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6464
07-27 08:57:11.057   385   385 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
07-27 08:57:11.057   753  1325 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 08:57:11.067  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,07-27 08:57:11.067   753   753 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:11.067   753   753 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:11.067   753  1330 I WifiHs20Service: Message received 5011
07-27 08:57:11.067   753  1333 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:57:11.077  1717  1730 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:57:11.077  1717  1730 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:57:11.077   753  1333 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-27 08:57:11.077  1378  1378 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:11.077  1378  1378 D STATUSBAR-WifiTile: Wifi onReceive(2)
07-27 08:57:11.077  6359  6359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:57:11.087  1378  1378 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=2
07-27 08:57:11.087  1378  1378 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:11.087   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1757d6f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e186a7c 6359:com.test.thalitest/u0a4}
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087  1378  1378 D HotspotTile: onReceive : 2, 0
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.087   753  1677 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.097   753  1677 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.097   753  1677 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.097  1378  2934 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 08:57:11.107  6448  6448 D BluetoothAdapterState: make() - Creating AdapterState
07-27 08:57:11.107  1378  1378 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
07-27 08:57:11.117  6469  6469 E Zygote  : v2
07-27 08:57:11.117  6469  6469 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:11.117  6469  6469 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:11.117  6469  6469 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:11.117  6469  6469 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:11.117  6469  6469 E Zygote  : accessInfo : 0
07-27 08:57:11.117  6448  6448 I bt_bluedroid: init
07-27 08:57:11.117  6448  6468 I BluetoothAdapterState: Entering OffState
07-27 08:57:11.127   753   827 I ActivityManager: Start proc 6469:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
07-27 08:57:11.147  6448  6474 E bt_core_counter: counter_init unable to open counter port
07-27 08:57:11.147  6448  6474 E bt_core_module: module_init failed to initialize "counter_module"
07-27 08:57:11.147  6448  6474 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 08:57:11.147  6448  6474 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 08:57:11.147  6448  6474 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-27 08:57:11.147  6448  6474 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 08:57:11.147  6448  6448 I bt_bluedroid: get_profile_interface socket
,07-27 08:57:11.147  6448  6448 W bt_btif : btif_get_adapter_property 2
07-27 08:57:11.147  6448  6448 W bt_btif : btif_get_adapter_property 1
,07-27 08:57:11.147  6448  6448 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-27 08:57:11.157  6469  6469 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:11.157  6469  6469 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:11.157  6448  6448 I bt_bluedroid: get_profile_interface sdp
,07-27 08:57:11.157  6448  6490 D BluetoothAdapterProperties: Address is:7C:F9:0E:34:8A:A0
,07-27 08:57:11.157  6448  6490 E BluetoothServiceJni: populateRssiValuesNative
07-27 08:57:11.157  6448  6490 I bt_bluedroid: getModelRssiValues
07-27 08:57:11.157  6448  6490 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-27 08:57:11.157  6448  6490 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 08:57:11.157   753  2013 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1757d6f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9ed326 6469:com.samsung.android.securitylogagent/1000}
,07-27 08:57:11.157  6448  6490 D BluetoothAdapterProperties: Name is: S5-1
,07-27 08:57:11.167   753   753 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-27 08:57:11.167  6448  6463 I bt_bluedroid: config_hci_snoop_log
,07-27 08:57:11.167  6469  6469 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package null
,07-27 08:57:11.167   753   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-27 08:57:11.177  1378  1378 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:11.177  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:11.177  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:11.177  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:11.177  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:11.177  6448  6468 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-27 08:57:11.177  6448  6468 D BluetoothAdapterProperties: Setting state to 14
07-27 08:57:11.177  6448  6468 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-27 08:57:11.177  6448  6468 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:57:11.177  6448  6468 D BluetoothAdapterService: updateAdapterState state is 14
,07-27 08:57:11.177  6448  6468 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:11.177  6448  6468 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,07-27 08:57:11.187  6469  6469 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm
,07-27 08:57:11.187   753   889 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
07-27 08:57:11.187  6448  6468 D BluetoothSecureManager: getInstant: null
07-27 08:57:11.187  6448  6468 D BluetoothSecureManager: calling getMethod for getService
07-27 08:57:11.187  6448  6468 D BluetoothSecureManager: calling getService
,07-27 08:57:11.187  6448  6468 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@59eae98
,07-27 08:57:11.187   753  1898 D BluetoothSecureManagerService: isSecureModeEnabled
,07-27 08:57:11.187   753  1898 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-27 08:57:11.187  6448  6468 D BtConfig.SecureMode: isSecureModeOn:false
07-27 08:57:11.187  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 08:57:11.187  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-27 08:57:11.187  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 08:57:11.187  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 08:57:11.187  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 08:57:11.187  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-27 08:57:11.187  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-27 08:57:11.197  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 08:57:11.197   753   769 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-27 08:57:11.197  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 08:57:11.197  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 08:57:11.197  6469  6469 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 08:57:11.197  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
07-27 08:57:11.197  6469  6469 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:57:11.197  6469  6469 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
,07-27 08:57:11.197  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:11.197  6469  6469 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:11.197  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:57:11.197  6448  6468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:57:11.197  6448  6468 D BluetoothBondStateMachine: make
,07-27 08:57:11.197  6448  6492 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 08:57:11.207   753  2167 I ActivityManager: Start proc 6493:tv.peel.smartremote/u0a170 for broadcast-5 tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver
07-27 08:57:11.207  6493  6493 E Zygote  : v2
07-27 08:57:11.207  6493  6493 I libpersona: KNOX_SDCARD checking this for 10170
07-27 08:57:11.207  6493  6493 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:11.207  6493  6493 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:11.207  6493  6493 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:11.207  6493  6493 E Zygote  : accessInfo : 0
07-27 08:57:11.207  6493  6493 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=tv.peel.smartremote 
,07-27 08:57:11.207   753  2167 I ActivityManager: Killing 4966:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,07-27 08:57:11.217  6448  6468 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:57:11.227  6448  6448 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,07-27 08:57:11.227  6448  6448 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 08:57:11.227  6448  6448 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:57:11.227  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
07-27 08:57:11.227  6448  6448 D BtGatt.GattService: start()
07-27 08:57:11.227  6448  6448 I bt_bluedroid: get_profile_interface gatt
07-27 08:57:11.227  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
,07-27 08:57:11.227  6448  6448 D BtGatt.AdvertiseManager: advertise manager created
07-27 08:57:11.227  6448  6448 D BtGatt.AdvertiseManager: start
,07-27 08:57:11.237  6448  6448 D BtGatt.ScanManager: start
,07-27 08:57:11.237  6448  6448 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,07-27 08:57:11.247   753  1898 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,07-27 08:57:11.247  6493  6493 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:11.247  6493  6493 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:11.257   753  2167 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1757d6f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0b0375 6493:tv.peel.smartremote/u0a170}
,07-27 08:57:11.267  6493  6493 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-27 08:57:11.277  6448  6448 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,07-27 08:57:11.277  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-27 08:57:11.277  6448  6448 E BtGatt.GattService: notifyProfileServiceStateChanged
,07-27 08:57:11.277  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:11.277  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
07-27 08:57:11.277  6448  6448 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:57:11.277  6448  6448 V BluetoothAdapterState: isTurningOn()=false
07-27 08:57:11.277  6448  6448 V BluetoothAdapterState: isBleTurningOn()=true
07-27 08:57:11.277  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:11.277  6448  6468 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-27 08:57:11.287  6448  6468 I bt_bluedroid: enable
07-27 08:57:11.287  6448  6474 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-27 08:57:11.287  6448  6474 I bt_hci  : start_up
,07-27 08:57:11.287  6448  6474 I bt_vendor: alloc value 0xb2b5d979
07-27 08:57:11.287  6448  6474 I bt_vendor: init
07-27 08:57:11.287  6448  6474 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:57:11.287  6448  6474 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 08:57:11.287  6448  6474 D bt_vendor: op for 5
07-27 08:57:11.287  6448  6474 D bt_vendor: op for 0
,07-27 08:57:11.297  6448  6474 I bt_upio : upio_set_bluetooth_power(on: 0)
07-27 08:57:11.297  6448  6474 D bt_upio : is_emulator_context : 0
07-27 08:57:11.297  6448  6474 D bt_upio : is_rfkill_disabled ? [0]
07-27 08:57:11.297  6448  6474 D bt_upio : is_rfkill_disabled ? [0]
,07-27 08:57:11.297  6448  6474 D bt_vendor: op for 0
07-27 08:57:11.297  6448  6474 I bt_upio : upio_set_bluetooth_power(on: 1)
07-27 08:57:11.297  6448  6474 D bt_upio : is_emulator_context : 0
07-27 08:57:11.297  6448  6474 D bt_upio : is_rfkill_disabled ? [0]
,07-27 08:57:11.297  6448  6474 D bt_hci  : start_up starting async portion
07-27 08:57:11.297  6448  6518 I bt_hci  : event_finish_startup
07-27 08:57:11.297  6448  6518 I bt_hci_h4: hal_open
07-27 08:57:11.297  6448  6518 D bt_vendor: op for 3
07-27 08:57:11.297  6448  6518 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 08:57:11.297  6448  6518 I bt_userial_vendor: userial_vendor_open():UART is setup
07-27 08:57:11.297  6448  6518 I bt_userial_vendor: device fd = 60 open
,07-27 08:57:11.307  6448  6518 D bt_vendor: op for 1
07-27 08:57:11.307  6448  6518 E bt_hwcfg: Start CFG HW, HCI reset
,07-27 08:57:11.317  6493  6493 W System  : ClassLoader referenced unknown path: /system/app/SmartRemote_KL/lib/arm
,07-27 08:57:11.327   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,07-27 08:57:11.327  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,07-27 08:57:11.357  6464  6464 I wpa_supplicant: Ctrl_iface: loading system cred
07-27 08:57:11.357  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,07-27 08:57:11.357  6493  6493 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:57:11.357  6493  6493 I MultiDex: install
07-27 08:57:11.357  6493  6493 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:11.377  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
07-27 08:57:11.377   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6464
07-27 08:57:11.377   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
07-27 08:57:11.377  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
07-27 08:57:11.377  6464  6464 I wpa_supplicant: ssSupport state is = 1
,07-27 08:57:11.377  6448  6518 E bt_hwcfg: Read Local Name after HCI reset
07-27 08:57:11.377  6464  6464 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:57:11.377  6464  6464 E wpa_supplicant: SIM READ ERROR
07-27 08:57:11.377  6464  6464 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:57:11.377  6464  6464 E wpa_supplicant: SIM READ ERROR
07-27 08:57:11.377  6464  6464 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:57:11.377  6464  6464 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:57:11.377  6464  6464 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:57:11.377   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{5d851d6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.387  6464  6464 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:57:11.407  6448  6518 D bt_hwcfg: Chipset BCM4350C0
,07-27 08:57:11.407  6448  6518 D bt_hwcfg: Target name = [BCM4350C0]
07-27 08:57:11.407  6448  6518 I bt_hwcfg: module_type[semco3rd].
07-27 08:57:11.407  6448  6518 I bt_hwcfg: module_type[semco3rd] is invalid.
,07-27 08:57:11.407  6448  6518 E bt_hwcfg: patchram path ORG . BCM4350C0
07-27 08:57:11.407  6448  6518 E bt_hwcfg: patchram path ORG .. BCM4350C0
07-27 08:57:11.407  6448  6518 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350C0
07-27 08:57:11.407  6448  6518 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350C0
07-27 08:57:11.407  6448  6518 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350C0
07-27 08:57:11.407  6448  6518 E bt_hwcfg: fw ver (org)0.0
,07-27 08:57:11.417  6448  6518 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
,07-27 08:57:11.417  6448  6518 E bt_hwcfg: Remove module rev, try again BCM4350
07-27 08:57:11.417  6448  6518 D bt_hwcfg: Target name = [BCM4350]
07-27 08:57:11.417  6448  6518 I bt_hwcfg: module_type[semco3rd].
07-27 08:57:11.417  6448  6518 I bt_hwcfg: module_type[semco3rd] is invalid.
07-27 08:57:11.417  6448  6518 E bt_hwcfg: patchram path ORG . BCM4350
07-27 08:57:11.417  6448  6518 E bt_hwcfg: patchram path ORG .. BCM4350
07-27 08:57:11.417  6448  6518 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350
07-27 08:57:11.427  6448  6518 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350
07-27 08:57:11.427  6448  6518 I bt_hwcfg: patch(org) : bcm4350_V0353.0733_wisol.hcd
07-27 08:57:11.427  6448  6518 E bt_hwcfg: Module type exists. Skip
07-27 08:57:11.427  6448  6518 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350
07-27 08:57:11.427  6448  6518 I bt_hwcfg: patch(org) : bcm4350_V0353.0727.hcd
,07-27 08:57:11.427  6448  6518 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4350_V0353.0727.hcd
07-27 08:57:11.427  6448  6518 E bt_hwcfg: ORG patchram base 0353
07-27 08:57:11.427  6448  6518 E bt_hwcfg: ORG patchram minor 0727
07-27 08:57:11.427  6448  6518 E bt_hwcfg: fw ver (org)353.727
07-27 08:57:11.427  6448  6518 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4350_V0353.0727.hcd
,07-27 08:57:11.427  6448  6518 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 08:57:11.427   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{78e3c57: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.427   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{3c6344: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.437  6448  6518 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-27 08:57:11.517  6493  6493 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-27 08:57:11.537   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{a8d2c2d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.537   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{95fb562: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.537  6493  6493 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-27 08:57:11.547  6493  6493 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 08:57:11.557  6493  6493 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1456-1459)
,07-27 08:57:11.557  6493  6493 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 08:57:11.567  6493  6493 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {49f275e}
,07-27 08:57:11.567  6493  6493 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-27 08:57:11.567  6493  6493 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:57:11.577  6493  6493 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-27 08:57:11.577  6493  6493 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,07-27 08:57:11.587   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{b3e6fb0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.587   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{1bd5e29: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.587   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{d07c5ae: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.597   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{d1e5f4f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.597   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d12d6dc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.597   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{8a4b3e5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.597   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{50e8eba: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.597   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{48ba16b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.607   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{e6484c8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.607   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{bf1a961: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.607   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{986dc86: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.607   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{b40e947: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.607   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{5a12574: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.617   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{abe7a9d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.617   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{ee43b12: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.617   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{318d2e3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.617   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{6524e0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.627   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{18d2399: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.627   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{b46f65e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:11.627   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{6fbba3f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.637   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{7a7af0c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.637   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{9036055: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.637   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{4881a6a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.647   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{dfbbb5b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.647   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{aa6aff8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.647   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{466acd1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.647   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{3057336: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.647   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{430b237: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.657   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{c92d3a4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.657   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{bd8450d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.657   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{52d8cc2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.657   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{5543ad3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.667   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{fb8610: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.667   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{e512509: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.667   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{fcbb30e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.667   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{51db12f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.667   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{2faf33c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.677   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{75e08c5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.677   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{713f21a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.677   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{15e314b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.677   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{3220728: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.677   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{49b6c41: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.687   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{c6f15e6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.687   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{9dc9727: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.687   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{8246dd4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.687   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{6f18b7d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.687   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d06aa72: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.697   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{9f17ec3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.697   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{e449340: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.697   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{b906279: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.697   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{d10fbbe: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.697   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{fe3441f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.707   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{17fa36c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.707   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{8abad35: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.707   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{bdd15ca: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.707   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{e02033b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.707   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{e798a58: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.717   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{9f6e7b1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.717   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{c9ec496: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.717   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{1839817: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.717   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{628f404: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.717   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{8e14ded: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.727   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{ffa9422: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.727   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{b1f9eb3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.727   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{434c70: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.727   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{c91dbe9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.737   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{a51d06e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.737   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{56b730f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.737   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{868bf9c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:11.737   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{da34da5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.737   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{2ce857a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.737   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{4f6312b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.747   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{2103988: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.747   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{9a01f21: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.747   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{72f7f46: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.747   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{e24b507: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.747   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{f336634: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.757   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{23e8c5d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:11.757   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{5449d2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.757   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{ccd9aa3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.757   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{5bab1a0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.757   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{45c9159: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.767   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{389311e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.767   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{9953dff: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.767   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{fa947cc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.767   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{2bbea15: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.767   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{c93412a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.767   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{909bb1b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.777   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{20914b8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.777   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{7e1291: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.777   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{c7c45f6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.777   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{7eedf7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.777   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{696c464: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.787   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{76046cd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.787   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{91ecb82: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.787   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{caa7293: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.787   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{42dc2d0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.787   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{5b782c9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.797   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{9721dce: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.797   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{5ffa4ef: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.797   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{1f43bfc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.797   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{2c8285: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.797   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{a9648da: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.807   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{ecba10b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.807   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{1471be8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.807   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{337c201: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.807   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{9a018a6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.807   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{71142e7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.817   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{a660e94: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.817   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{5d7d3d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.817   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{e251932: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.817   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{2252683: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.817   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{7df8000: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.827   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{329b039: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.827   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{187967e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.827   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{a09a7df: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.827   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{cbc9c2c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.827   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{9ec16f5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.837   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{f029c8a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.837   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{c8ae2fb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.837   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{16d4f18: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.837   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{e342d71: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.837   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{875f756: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.837   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e1ab3d7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.847   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{37444c4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.847   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{90d2fad: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.847   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{bf232e2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.847   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{e6cb673: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.847   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{3d2e930: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.857   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{efa19a9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.857   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{6049b2e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.857   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{ad246cf: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.857   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{35685c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.857   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{fb1a765: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.867   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{cc33c3a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.867   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{a5680eb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.867   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{2deae48: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.867   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{59a54e1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.867   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{f98e206: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.877   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{f9a40c7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.877   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{55466f4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.877   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{1065e1d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.877   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{7d11892: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.877   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{c702263: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.887   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{1cafe60: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.887   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{b2fbf19: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.887   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{5e42bde: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.887   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{33881bf: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.887   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{f51a08c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.887   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{cf433d5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.897   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{78327ea: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.897   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{1fd7adb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.897   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{4be3978: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.897   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{5513851: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.897   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{263d8b6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.907   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{34ee9b7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.907   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{e597524: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.907   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{ba0088d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.907   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{fccca42: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.907   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{de6a53: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.917   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{24abf90: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.917   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{991a089: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.917   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{4e1488e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.917   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{3db58af: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.917   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{fc444bc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.927   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{8eabc45: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.927   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{3ad5f9a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.927   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{f0ed0cb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.927   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{4eef0a8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.937   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{ffd7c1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.937   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{f1db66: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.937   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{eb7aea7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.937   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{7966f54: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.937   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{ff12efd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.937   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{ab047f2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.947   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a268e43: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.947   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{c952cc0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.947   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{ba6bdf9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.947   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{b76f13e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.947   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{319cb9f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.957   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{a0054ec: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.957   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{68c40b5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.957   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{66ce34a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.957   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{ed982bb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.957   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{13d3d8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.967   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{40d3331: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.967   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{81dea16: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.967   306  1179 D Netd    : Iface wlan0 link up
,07-27 08:57:11.967   306  1179 D Netd    : Iface wlan0 link up
07-27 08:57:11.967   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{5138f97: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.967   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:11.967   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:11.967   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{4de5584: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.977   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{2b61769: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.977   753   889 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
07-27 08:57:11.977   753   889 D Tethering: NAP Supported and not Wifi Model
,07-27 08:57:11.977  6493  6532 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-27 08:57:11.977   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:11.977   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:11.977   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{938d11c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.977   753   889 E Tethering: No numeric data
,07-27 08:57:11.977   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{48fc125: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.977   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{5acb2fa: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.987   753   889 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 08:57:11.987   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{6c90ab: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.987  1378  1378 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-27 08:57:11.987  1378  1378 D HotspotTile: updateTetherState():false, false
,07-27 08:57:11.987   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18fe308 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d6c7ef 753:system/1000}
,07-27 08:57:11.997   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{1a04aa1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.997   753  1322 D NtpTrustedTime: forceRefresh: no connectivity
07-27 08:57:11.997  6493  6493 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:57:11.997  6493  6493 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:57:11.997  6493  6493 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:57:11.997  6493  6493 I Adreno-EGL: Local Branch: ss
07-27 08:57:11.997  6493  6493 I Adreno-EGL: Remote Branch: 
07-27 08:57:11.997  6493  6493 I Adreno-EGL: Local Patches: 
07-27 08:57:11.997  6493  6493 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:57:11.997   753  1322 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:11.997   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{18304c6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:11.997   753  1322 V NetworkStats: performPollLocked() took 5ms
,07-27 08:57:12.007   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{7618c87: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.007   753  1323 D NtpTrustedTime: forceRefresh: no connectivity
,07-27 08:57:12.007   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{4c427b4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.007  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:57:12.007   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{4d5efdd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.007   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{1aa752: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.007   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{5c06a23: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.017   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{d560b20: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.017  6493  6493 D libEGL  : eglInitialize EGLDisplay = 0xbef7b23c
,07-27 08:57:12.017   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{fc6acd9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.017   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{917e69e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.017   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{3a5857f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.017   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{b60b94c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.027   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{d6c3d95: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.027   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{817ceaa: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.027   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{496fa9b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.027   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{3861e38: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.027   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{4a01e11: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.037   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{37c2b76: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.037   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{460a577: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.037   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{9ae5e4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.037   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{6578a4d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.037   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{3f78902: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.047   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{5b02213: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.047   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{4127c50: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.047   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{39f7e49: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.047   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{8d9334e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.047   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{e70cc6f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.057   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{12b0d7c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.057   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{758b605: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.057   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{519365a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.057   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{de7c08b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.057   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{ed98568: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.067   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{fb3ad81: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.067   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{1245e26: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.067   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{88fda67: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.067   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{c759014: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.067   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{36ca0bd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.077  6464  6464 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-27 08:57:12.077  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,07-27 08:57:12.077   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{d6836b2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.077   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{5b5b603: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.077   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{5259980: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.077   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{ec78bb9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.087   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{19f0bfe: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.087   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{ad3af5f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.087   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e0acdac: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.087   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{44c2a75: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.087   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{4dbea0a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.097   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{ade27b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.097  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
,07-27 08:57:12.097   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6464
07-27 08:57:12.097   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
07-27 08:57:12.097  6464  6464 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
07-27 08:57:12.097  6464  6464 I wpa_supplicant: ssSupport state is = 1
,07-27 08:57:12.097   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{b2d1898: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.097  6464  6464 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:57:12.097   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{d41f8f1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.097   306  1179 D Netd    : Iface p2p0 link up
07-27 08:57:12.097   306  1179 D Netd    : Iface p2p0 link up
,07-27 08:57:12.097   753   851 D Tethering: interfaceLinkStateChanged p2p0, true
07-27 08:57:12.097   753   851 D Tethering: interfaceStatusChanged p2p0, true
,07-27 08:57:12.097   753   851 D Tethering: interfaceLinkStateChanged p2p0, true
,07-27 08:57:12.097   753   851 D Tethering: interfaceStatusChanged p2p0, true
,07-27 08:57:12.107   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{5ec332d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.107   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{ef7b062: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.107   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{50025f3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.107   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{99262b0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.117   753  1789 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10170
,07-27 08:57:12.117   753  1789 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-27 08:57:12.117   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{832f9dc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.117   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{1fd9ae5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.117   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{4ae9ba: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.117   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{2f8606b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.127   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{ee3d7c8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.127   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{bade786: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.127  6448  6518 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-27 08:57:12.127  6448  6518 I bt_hwcfg: FW Download delta = 746362
07-27 08:57:12.127  6448  6518 D bt_hwcfg: Settlement delay -- 100 ms
07-27 08:57:12.127  6448  6518 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 08:57:12.127   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{b6d419d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.137   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{3f0f612: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.137   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{3e4615e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.137   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{111356a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.137   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e853e36: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.147   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{b742137: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.147   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{a1b16a4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.157   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{244f910: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.157   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{da11c09: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.167   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{c19de0e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.167   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{580002f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.167   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{ae8963c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.167   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{1366fc5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.177   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{199cd1a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.177   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{716704b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.177   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{fc6da28: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.177  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 175ms lastUpdatedAfter : 168162ms
07-27 08:57:12.177   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{1134341: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.177   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{8f7a0e6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.187   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{c59c627: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.187  6493  6493 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
07-27 08:57:12.187   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{5c370d4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.187   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{88fd27d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.187   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{10ce572: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.187   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{8929dc3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.197  6464  6464 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-27 08:57:12.197   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a50c640: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.197   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{64c1979: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.197   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{abfe6be: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.197   753  1325 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-27 08:57:12.197   753  1325 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,07-27 08:57:12.207   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{f7531f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.207   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{d9c066c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.207   753  1325 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,07-27 08:57:12.207  6464  6464 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-27 08:57:12.207  6464  6464 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 08:57:12.207  6464  6464 E wpa_supplicant: SIM READ ERROR
07-27 08:57:12.207  6464  6464 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:57:12.207   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{8ebd435: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.207   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{d0fb0ca: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.207  6493  6493 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:57:12.207  6493  6493 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-27 08:57:12.207   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{dc8023b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.217  6493  6493 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 08:57:12.217   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{3791d58: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.217  6493  6493 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 08:57:12.217  6464  6464 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 08:57:12.217   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{b927eb1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.217  6464  6464 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,07-27 08:57:12.217   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{de00f96: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.217   753  1325 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-27 08:57:12.227   753   753 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:57:12.227   753   753 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:57:12.227  1378  1378 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:12.227  1378  1378 D STATUSBAR-WifiTile: Wifi onReceive(3)
07-27 08:57:12.227  1378  1378 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=3
,07-27 08:57:12.227   753  1327 D HS20StateMachine: WIFI_STATE_ENABLED
07-27 08:57:12.227  1378  1378 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:57:12.227  1378  1378 D HotspotTile: onReceive : 3, 0
07-27 08:57:12.227  1378  2934 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 08:57:12.227  1378  1378 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
07-27 08:57:12.227   753  1327 D HS20StateMachine: reloadCredentialsToSupplicant
,07-27 08:57:12.227   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12a8717 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e186a7c 6359:com.test.thalitest/u0a4}
,07-27 08:57:12.237  6359  6359 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:12.237  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:57:12.237  6359  6359 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:12.237  6359  6359 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:57:12.237  6448  6518 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.237   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{70eb704: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.237   753  1333 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:57:12.237  1717  2543 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:57:12.237  1717  2543 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:57:12.237   753  1333 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.237   753  2013 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.237   753  1327 D HotspotDBHandler: getCredentialIds
,07-27 08:57:12.237   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{e1f54ed: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.247  6493  6493 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 08:57:12.247  6493  6493 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:57:12.247  6493  6493 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-27 08:57:12.247  6493  6493 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 08:57:12.247  6493  6493 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 08:57:12.247   753  1898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12a8717 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9ed326 6469:com.samsung.android.securitylogagent/1000}
,07-27 08:57:12.247   753  1330 I WifiHs20Service: Message received 5011
07-27 08:57:12.247  6464  6464 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 08:57:12.247   753  1325 D WifiConfigStore: Loading config and enabling all networks 
,07-27 08:57:12.257   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{b858f22: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.267   753  1320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.267  6469  6469 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:57:12.267  6469  6469 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:57:12.267  6469  6469 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:57:12.267  6469  6469 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:57:12.267   753  1325 I WifiConfigStore: "NG700" is a verified password AP: true
07-27 08:57:12.267   753  1325 E WifiConfigStore: Not a HS20
,07-27 08:57:12.267  6566  6566 E Zygote  : v2
,07-27 08:57:12.267  6566  6566 I libpersona: KNOX_SDCARD checking this for 10202
07-27 08:57:12.267  6566  6566 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:12.267   753  1327 I ActivityManager: Start proc 6566:com.samsung.hs20provider/u0a202 for content provider com.samsung.hs20provider/.Hs20Provider
07-27 08:57:12.267  6566  6566 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:12.267  6566  6566 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:12.267   753  1325 D WifiConfigStore: loaded 0 passpoint configs
,07-27 08:57:12.267   753  1325 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:57:12.267  6566  6566 E Zygote  : accessInfo : 0
,07-27 08:57:12.277  6566  6566 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-27 08:57:12.277   753   769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12a8717 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0b0375 6493:tv.peel.smartremote/u0a170}
07-27 08:57:12.277   753  1325 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-27 08:57:12.277   753  1325 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-27 08:57:12.277   753  1325 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 08:57:12.277   753   753 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-27 08:57:12.277   753   753 D WifiHs20Service: reason: 2
07-27 08:57:12.277   753  1330 I WifiHs20Service: Message received 5014
07-27 08:57:12.277   753  1330 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-27 08:57:12.277   753  1330 E WifiHs20Service: The changed config is NULL
,07-27 08:57:12.277   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{fc67db3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.277   753  1325 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,07-27 08:57:12.277   753  1325 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-27 08:57:12.277   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{d423f70: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.287   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{52952e9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.287   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{3117b6e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.287   753  1325 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,07-27 08:57:12.287  6464  6464 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 08:57:12.287  6464  6464 I wpa_supplicant: resume autoscan
07-27 08:57:12.287  6464  6464 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-27 08:57:12.287  6464  6464 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-27 08:57:12.287  6464  6464 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 08:57:12.287  6464  6464 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 08:57:12.287  6464  6464 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 08:57:12.287  6464  6464 I wpa_supplicant: First Scan Start
,07-27 08:57:12.287   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{721420f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.287  6464  6464 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:57:12.297   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{1e3e29c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.297   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{dbb34a5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.297   753  1325 D WifiNative-wlan0: Setting external_sim to 1
,07-27 08:57:12.297   753  1325 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
07-27 08:57:12.297   753  1325 D WifiStateMachine: Setting OUI to DA-A1-19
,07-27 08:57:12.297   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{f5de07a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.297  6464  6464 I wpa_supplicant: bt_status is set be DISCONNECTED
,07-27 08:57:12.297   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{db9f02b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.307  6566  6566 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:12.307  6566  6566 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:12.307   753  1325 E WifiNative-wlan0: do suspend true
,07-27 08:57:12.307   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{b9a8c88: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.307   753  1324 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 08:57:12.317   306  1186 D CommandListener: Setting iface cfg
07-27 08:57:12.317   306  1186 D CommandListener: Trying to bring up p2p0
,07-27 08:57:12.317   753  1324 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 08:57:12.317   753  1324 D SecContentProvider: insert(), uri = 2
07-27 08:57:12.317   753  1325 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
07-27 08:57:12.317   753  1324 D WifiP2pService: P2pEnablingState
07-27 08:57:12.317   753   753 D RttService: SCAN_AVAILABLE : 3
,07-27 08:57:12.317   753  1352 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:57:12.317   753  1351 E WifiScanningService: could not start HAL
,07-27 08:57:12.317   753  1324 D WifiP2pService: P2pEnablingState{ what=147457 }
07-27 08:57:12.317   753  1324 D WifiP2pService: P2p socket connection successful
,07-27 08:57:12.317   753  1324 D WifiP2pService: P2pEnabledState
07-27 08:57:12.317   753  1324 D SecContentProvider: insert(), uri = 2
,07-27 08:57:12.317   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{cf7621: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.317   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{cd98a46: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.317  6566  6566 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package null
,07-27 08:57:12.327   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{8e56407: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.327   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{28fe934: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.327   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{28c535d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.327   753  1325 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-27 08:57:12.327   753  1325 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
07-27 08:57:12.327   753  1325 D WifiStateMachine: setFccChannelNative: channel = 0
07-27 08:57:12.327   753  1325 D WifiNative-wlan0: callSECApiInt - ID [230]
07-27 08:57:12.327   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{46a39a3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.327  1378  1378 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:12.327  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:12.337   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{5dc64a0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.337  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:12.337  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:12.337   753   753 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-27 08:57:12.337   753   891 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-27 08:57:12.337  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:12.337   753  1324 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,07-27 08:57:12.337  6448  6518 I bt_hwcfg: vendor lib fwcfg completed
,07-27 08:57:12.337   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{93fc859: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.337  6448  6518 I bt_vendor: firmware callback
07-27 08:57:12.337  6448  6518 I bt_hci  : firmware_config_callback
07-27 08:57:12.337   753   891 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-27 08:57:12.337   753   891 D WifiDisplayController: disconnect
,07-27 08:57:12.337   753   891 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:57:12.337  6493  6493 I ClientConfig: Set OkHttp cache (max size: 52MB) to /data/user/0/tv.peel.smartremote/cache/peel-cache
,07-27 08:57:12.337   753  1324 D WifiP2pService: create mNetworkAgent
,07-27 08:57:12.347  1378  1378 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 08:57:12.347   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{d099c1e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.347   753  1324 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
07-27 08:57:12.347  6566  6566 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm
,07-27 08:57:12.347   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:12.347  6448  6579 I bt_btu_task: Bluetooth chip preload is complete
,07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_PAN
,07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 08:57:12.347   753   768 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:57:12.347  6448  6579 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
07-27 08:57:12.347  1378  1378 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 08:57:12.347   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{7dcccff: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.347   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:12.357   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{bb32acc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.357   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{84e27b8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.357   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{9b12991: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.367   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{5a235d0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.367   753  1324 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:12.367   753  1332 D ConnectivityService: Got NetworkAgent Messenger
,07-27 08:57:12.367   753  1332 E ConnectivityService: updateNetworkInfo()
,07-27 08:57:12.367   753   891 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.367  6464  6464 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-27 08:57:12.367   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{56348ce: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.367   753  1332 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:12.367   753  1332 D ConnectivityService: NetworkAgent connected
,07-27 08:57:12.367   753  1332 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
,07-27 08:57:12.367   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{8c8f3ef: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.367  6464  6464 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-27 08:57:12.377   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{1bcdefc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.377  6566  6576 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:12.377  6566  6576 D HotspotProvider: CREDENTIAL
,07-27 08:57:12.377  6566  6576 D HotspotProvider: No prepend tags
,07-27 08:57:12.377   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{c43e985: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.377   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{bef23da: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.377  1717  2543 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-27 08:57:12.377   753  1327 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-27 08:57:12.377   753  1327 D HS20StateMachine: enter : DiscoveringState
,07-27 08:57:12.387   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{65ae00b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.397   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{6de9901: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.397   753  3282 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.397   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{72ba3a6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.397   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{1d571e7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.407   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{401194: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.407   753  1324 E WifiP2pService: Failed to set my phone number info into probe response
,07-27 08:57:12.407   753  1324 D WifiNative-p2p0: p2pGetDeviceAddress
,07-27 08:57:12.407   753  1324 D WifiNative-p2p0: p2pGetDeviceAddress returning ee:1f:72:63:11:86
,07-27 08:57:12.417   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d1ac43d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.417   753  1324 D WifiP2pService: DeviceAddress: ee:11:86
,07-27 08:57:12.417   753   891 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] S5-1
07-27 08:57:12.417   753   891 D WifiDisplayController:  deviceAddress: ee:1f:72:63:11:86
07-27 08:57:12.417   753   891 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 08:57:12.417   753   891 D WifiDisplayController:  secondary type: null
07-27 08:57:12.417   753   891 D WifiDisplayController:  wps: 0
07-27 08:57:12.417   753   891 D WifiDisplayController:  grpcapab: 0
07-27 08:57:12.417   753   891 D WifiDisplayController:  devcapab: 0
07-27 08:57:12.417   753   891 D WifiDisplayController:  status: 3
07-27 08:57:12.417   753   891 D WifiDisplayController:  wfdInfo: null
07-27 08:57:12.417   753   891 D WifiDisplayController:  groupownerAddress: null
07-27 08:57:12.417   753   891 D WifiDisplayController:  GOdeviceName: null
07-27 08:57:12.417   753   891 D WifiDisplayController:  interfaceAddress: 
07-27 08:57:12.417   753   891 D WifiDisplayController:  SConnectInfo : null
07-27 08:57:12.417   753   891 D WifiDisplayController:  contactInfoHash : null
07-27 08:57:12.417   753   891 D WifiDisplayController:  ssDevInfo : 0
07-27 08:57:12.417   753   891 D WifiDisplayController:  iconIdx : 0
,07-27 08:57:12.417   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{5e5432: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.417   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{67d4583: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.427   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{4d6b300: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.427   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{bf46739: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.427   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{d99817e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.427   753  1324 D WifiP2pService: sending p2p persistent groups changed broadcast
07-27 08:57:12.427   753  1324 D WifiP2pService: InactiveState
07-27 08:57:12.427   753  1324 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-27 08:57:12.427   753  1332 E ConnectivityService: updateNetworkInfo()
07-27 08:57:12.427   753  1332 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,07-27 08:57:12.427   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{544b6df: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.427   753  1324 D WifiP2pService: InactiveState{ what=143376 }
07-27 08:57:12.427   753  1324 D WifiP2pService: P2pEnabledState{ what=143376 }
07-27 08:57:12.427   753  1324 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-27 08:57:12.437   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{d73ff2c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.437  6493  6493 I Fabric  : Initializing Crashlytics 2.3.2.56
,07-27 08:57:12.437   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{a2b3df5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.437   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{1c8378a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.437   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{1e7e1fb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.437   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{9b7e218: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.447   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{bec471: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.447   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{17a4256: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.447   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{5c8a2d7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.447   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{15507c4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.447   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{f2a36ad: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.457   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{76090a9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.457   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{d888e65: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.457   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{5a5973a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.457   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{c713feb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.457   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{8740148: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.457   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{778abe1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.467   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{3c5ed06: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.467   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{221efc7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.467   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{a6be9f4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.467   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{7f3251d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.467   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{943d392: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.477   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{143c163: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.487   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{457b160: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.487   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{1a1f619: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.487   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{b4796de: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.487   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{b2710bf: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.497   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{976838c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.497   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{dd2dad5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.497  6493  6493 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10170, CallingPid : 6493
,07-27 08:57:12.497   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2f34f51: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.507   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{d69a3b6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.507   753   768 D ConnectivityService: listenForNetwork for Listen from uid/pid:10170/6493 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:12.507   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{aa058b7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.507   753  2163 I ActivityManager: Killing 4494:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,07-27 08:57:12.517   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{5d7b824: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.517   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{6cc8f8d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.517   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{ce44542: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.517   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{d57c953: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.527   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{6ea3290: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.527   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{87f9789: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.527   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{b75738e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.527   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{80ba7af: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.527   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{a67e7bc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.537   753  2013 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e412345 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:12.537   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{6d93a9a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.547   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{7750fcb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.547  5020  5020 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
,07-27 08:57:12.547   753  2167 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
07-27 08:57:12.547  5020  5020 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
,07-27 08:57:12.547  5020  5020 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,07-27 08:57:12.557  5020  5020 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 08:57:12.557   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{9a9c3a8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.557  5020  5020 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:57:12.557   753  1898 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.557  5020  5020 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:57:12.567   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{2d5aec1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.567   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{a806666: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.567   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{c2dda7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.567  6448  6579 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,07-27 08:57:12.567  6448  6579 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb2ab1269
07-27 08:57:12.567  6448  6579 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb2ab1269 
07-27 08:57:12.567  6448  6579 E bt_btm  : btm_ble_set_search_if search_if=4
,07-27 08:57:12.567   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{8ab7254: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.577   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{ecd75fd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.577  6448  6490 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 28928 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 1024 mIsExtendedScanSupported = false mIsDebugLogSupported = false mAobleSupported = 0
,07-27 08:57:12.577   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{61c82f2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.577   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{335ad43: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.587   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{d775fc0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.587   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{98074f9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.587  6493  6583 E Fabric  : Error performing auto configuration.
07-27 08:57:12.587  6493  6583 E Fabric  : java.util.concurrent.ExecutionException: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.FutureTask.report(FutureTask.java:94)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.FutureTask.get(FutureTask.java:164)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.u.c(Onboarding.java:105)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.u.f(Onboarding.java:45)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:63)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:28)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.a.c.c.call(AsyncTask.java:311)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at java.lang.Thread.run(Thread.java:818)
07-27 08:57:12.587  6493  6583 E Fabric  : Caused by: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:91)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:58)
07-27 08:57:12.587  6493  6583 E Fabric  : 	at a.a.a.a.k.call(FabricKitsFinder.java:35)
07-27 08:57:12.587  6493  6583 E Fabric  : 	... 4 more
,07-27 08:57:12.587   753  2013 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:12.587  5020  5020 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-27 08:57:12.587  5020  5020 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:57:12.587  5020  5020 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 08:57:12.587   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{ebdc3e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.597  6448  6490 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-27 08:57:12.597  5020  6595 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:57:12.597   753  1650 I ActivityManager: Killing 4856:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,07-27 08:57:12.607   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e412345 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e41dbb8 5455:com.samsung.android.app.FileShareServer/5005}
,07-27 08:57:12.607  6448  6490 D bt_hci  : do_postload posting postload work item
07-27 08:57:12.607  6448  6490 E bt_btif_sock: btif_sock_init: !vhci_init
07-27 08:57:12.607  6448  6490 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
07-27 08:57:12.607  6448  6518 I bt_hci  : event_postload
07-27 08:57:12.607  6448  6518 D bt_vendor: op for 2
,07-27 08:57:12.607  6448  6518 D bt_hwcfg: hw_sco_config
07-27 08:57:12.607  6448  6518 I bt_vendor: sco_config_cb
07-27 08:57:12.607  6448  6518 I bt_hci  : sco_config_callback postload finished.
07-27 08:57:12.607  6448  6518 D bt_vendor: op for 6
07-27 08:57:12.607  6448  6518 D bt_upio : upio_set : pio 2 action 2, polarity 0
07-27 08:57:12.607  6448  6490 D bt_bte_conf: Device ID record 1 : primary
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   vendorId            = 0075
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   vendorIdSource      = 0001
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   product             = 0100
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   version             = 0200
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   clientExecutableURL = 
07-27 08:57:12.607   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{77bda9f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   serviceDescription  = 
07-27 08:57:12.607  6448  6490 D bt_bte_conf:   documentationURL    = 
07-27 08:57:12.607  6448  6490 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 08:57:12.607  6448  6490 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-27 08:57:12.607  6448  6490 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 7
07-27 08:57:12.607  6448  6490 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24844
07-27 08:57:12.607  6448  6490 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4354 37.4MHz SEMCO-B80 K-LTE-0353
07-27 08:57:12.607  6448  6490 D BluetoothDataManager: firmwareVersion from Property : bcm4350_V0353.0727.hcd
07-27 08:57:12.607  6448  6474 D bt_stack_manager: event_start_up_stack finished
07-27 08:57:12.607  5455  5455 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-27 08:57:12.607  6448  6490 E BluetoothAdapterState: stateChangeCallback : 1
07-27 08:57:12.607  6448  6468 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-27 08:57:12.607  6448  6518 D bt_vendor: op for 7
07-27 08:57:12.607  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 08:57:12.607  6448  6518 D bt_upio : upio_start_stop_timer : timer_settime success
07-27 08:57:12.607  6448  6518 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
07-27 08:57:12.607  6448  6468 D BluetoothAdapterProperties: Setting state to 15
07-27 08:57:12.607  6448  6468 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 08:57:12.607   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{252b7ec: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.607  6448  6518 D bt_vendor: op for 7
,07-27 08:57:12.607  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:12.607  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:12.607  6448  6518 D bt_vendor: op for 7
07-27 08:57:12.607  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 08:57:12.607  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:12.607  6448  6468 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-27 08:57:12.607  6448  6518 D bt_vendor: op for 7
07-27 08:57:12.607  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 08:57:12.607  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:12.617  6448  6468 D BluetoothAdapterService: updateAdapterState state is 15
,07-27 08:57:12.617  6448  6518 I bt_vendor: low_power_mode_cb
07-27 08:57:12.617  6448  6468 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:12.617  6448  6468 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-27 08:57:12.617  6448  6468 I BluetoothAdapterState: Entering BleOnState
,07-27 08:57:12.617   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{5c57e4a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.617   753  1747 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
07-27 08:57:12.617   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{8cd81bb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.627  5455  5455 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:57:12.627  5455  5455 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,07-27 08:57:12.627  5455  5455 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:12.627  5455  5455 W System.err: 	at com.samsung.android.app.FileShareServer.ServerBroadcastReceiver.onReceive(ServerBroadcastReceiver.java:34)
,07-27 08:57:12.627  5455  5455 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3634)
07-27 08:57:12.627  5455  5455 W System.err: 	at android.app.ActivityThread.access$2000(ActivityThread.java:221)
07-27 08:57:12.627  5455  5455 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1876)
07-27 08:57:12.627  5455  5455 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-27 08:57:12.627  5455  5455 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:57:12.627   753   889 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 08:57:12.627  5455  5455 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-27 08:57:12.627  5455  5455 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,07-27 08:57:12.627  5455  5455 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:57:12.627  5455  5455 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-27 08:57:12.627   753   889 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-27 08:57:12.627  6448  6468 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-27 08:57:12.627   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{ea966d8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.627  6448  6468 D BluetoothAdapterProperties: Setting state to 11
07-27 08:57:12.627  6448  6468 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-27 08:57:12.627  6448  6468 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:57:12.627  6448  6468 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 08:57:12.637  6448  6468 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:12.637  6448  6468 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-27 08:57:12.637  6448  6468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:12.637  6448  6468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:57:12.637  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 08:57:12.637   753   889 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,07-27 08:57:12.637  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:57:12.647  6448  6448 D HeadsetService: Received start request. Starting profile...
07-27 08:57:12.647  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
,07-27 08:57:12.647  6448  6448 D HeadsetProvider: make
07-27 08:57:12.647  6448  6448 D HeadsetProvider: HeadsetProvider
07-27 08:57:12.647  6448  6448 I HeadsetProvider: clearAllHeadsetSettings(0)
,07-27 08:57:12.647  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 08:57:12.657  6448  6448 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 08:57:12.657  6448  6448 D HeadsetStateMachine: make
,07-27 08:57:12.657  6448  6448 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 08:57:12.667   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{70c6d33: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.667  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 08:57:12.677  6603  6603 E Zygote  : v2
07-27 08:57:12.677  6603  6603 I libpersona: KNOX_SDCARD checking this for 5005
07-27 08:57:12.677  6603  6603 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:12.677   753   827 I ActivityManager: Start proc 6603:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
07-27 08:57:12.677  6603  6603 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:12.677  6603  6603 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:12.677  6603  6603 E Zygote  : accessInfo : 0
,07-27 08:57:12.677  6603  6603 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,07-27 08:57:12.677   753   753 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:12.677   753   753 I InputMethodManagerService: [BT Setting State] State =11
,07-27 08:57:12.687  1764  1764 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:12.687   753   753 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-27 08:57:12.687   753   753 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:12.687   753   753 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-27 08:57:12.697  1983  1983 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:57:12.697  1378  1378 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 08:57:12.707   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:12.707   753  1677 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-27 08:57:12.707   753  1623 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 08:57:12.707  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 08:57:12.717  1378  1378 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:12.717  1378  1378 D BluetoothTile:  getBluetoothState : 11
07-27 08:57:12.717  1378  1378 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 )
,07-27 08:57:12.717  6603  6603 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:12.717  6603  6603 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:12.717  1378  2934 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:57:12.717  1378  2934 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 08:57:12.717  1378  1378 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-27 08:57:12.727   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68eb49d 2085:com.samsung.android.providers.context/u0a174}
,07-27 08:57:12.727  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 08:57:12.727  6448  6448 I bt_bluedroid: get_profile_interface handsfree
,07-27 08:57:12.747   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a0134c5 1860:com.sec.android.app.shealth:remote/u0a34}
,07-27 08:57:12.757  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-27 08:57:12.757   753  1623 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{e412345 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{406252 6603:com.samsung.android.app.FileShareClient/5005}
,07-27 08:57:12.757   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{6cb0923: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.767  6603  6603 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package null
,07-27 08:57:12.777  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:12.777  6448  6468 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:12.777  6448  6468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:57:12.777  6448  6468 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:57:12.777  6448  6468 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:57:12.777  6448  6448 I DualScoManager: Instantiating Dual Sco Manager
07-27 08:57:12.777  6448  6448 I DualScoManager: Set HeadsetServiceHelper
,07-27 08:57:12.787  6448  6448 D BluetoothAtMessage: createCMTIContentObservers
,07-27 08:57:12.787   753  2163 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:12.787  5020  5020 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:57:12.787   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{6613138: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.797   753  2013 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:12.797   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{db13511: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.797   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{ec4f676: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.797  1378  1378 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:12.807  1378  1378 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-27 08:57:12.807   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{2391477: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.807  6603  6603 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm
,07-27 08:57:12.807  6448  6448 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@cabade0
,07-27 08:57:12.817  6448  6448 D HeadsetProvider: setHeadsetDB - Can't find 300 for 7C:F9:0E:34:8A:XX
,07-27 08:57:12.817  6603  6603 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 08:57:12.817  6603  6603 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,07-27 08:57:12.817   753  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4e5d0ee 6448:com.android.bluetooth/1002}
,07-27 08:57:12.827   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{19428e4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.827  6448  6448 I HeadsetProvider: setHeadsetDB - 7C:F9:0E:34:8A:XX, 300, 1, true
,07-27 08:57:12.827   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{4e3114d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.837   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{2820402: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.837  6448  6448 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@676973f
,07-27 08:57:12.837   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a208113: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.837  6448  6448 D HeadsetProvider: setHeadsetDB - Can't find 400 for 7C:F9:0E:34:8A:XX
,07-27 08:57:12.837   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{edcef50: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.837   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{cdc7549: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.837   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{5105e4e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.847   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{3081b6f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.847  6448  6448 I HeadsetProvider: setHeadsetDB - 7C:F9:0E:34:8A:XX, 400, 1, true
,07-27 08:57:12.847   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{9a9b07c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.847  6448  6602 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-27 08:57:12.847  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-27 08:57:12.847  6448  6448 E HeadsetService: notifyProfileServiceStateChanged
,07-27 08:57:12.847   753   753 D BluetoothA2dp: Proxy object connected
,07-27 08:57:12.847  6448  6448 D A2dpService: Received start request. Starting profile...
07-27 08:57:12.847  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
,07-27 08:57:12.847  2085  2085 D BluetoothA2dp: Proxy object connected
,07-27 08:57:12.847  6448  6448 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-27 08:57:12.847  6448  6602 D HeadsetStateMachine: Clear mHeadsetBrsf
07-27 08:57:12.847  6448  6602 D HeadsetStateMachine: map size, before remove : 0
07-27 08:57:12.847  6448  6602 D HeadsetStateMachine: map size, after remove: 0
,07-27 08:57:12.857  6448  6448 I bt_bluedroid: get_profile_interface avrcp
,07-27 08:57:12.857   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{41f5868: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.857  6603  6603 D FileShare-Client: Outbound.stopDelayTimer - 
,07-27 08:57:12.857  6464  6464 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
,07-27 08:57:12.857  6464  6464 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-27 08:57:12.857  6464  6464 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-27 08:57:12.857  6464  6464 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 08:57:12.857  6464  6464 I wpa_supplicant:    allow  - level is under -85dBm [-41] or selected nid [-1] [0]
,07-27 08:57:12.857  6464  6464 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
07-27 08:57:12.857  6464  6464 I wpa_supplicant:    allow  - level is under -85dBm [-41] or selected nid [-1] [0]
07-27 08:57:12.857  6464  6464 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz level=-41) 
,07-27 08:57:12.867   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{bc59314: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.867  6448  6448 I Avrcp   : No of Audio players :: 2
,07-27 08:57:12.867  6448  6448 I Avrcp   : App Package name is GM
,07-27 08:57:12.867   306  1179 D Netd    : Iface wlan0 link up
,07-27 08:57:12.867   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:12.867   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:12.867   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{b67e7bd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.867  6448  6448 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:57:12.877   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{d0771b2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.877   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{27bd503: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.877  6448  6448 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 08:57:12.877  6448  6448 I Avrcp   : App Package name is SM
,07-27 08:57:12.877   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{cf2cc80: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.877  6448  6448 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:57:12.887   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{8b042b9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.887   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{b76f6fe: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.887  6448  6448 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-27 08:57:12.887   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{75cbe5f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.887  6448  6448 I Avrcp   : No of Video players :: 2
,07-27 08:57:12.887  6448  6448 I Avrcp   : Video App Package name is others
,07-27 08:57:12.887   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{f830ac: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.897  6448  6448 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:57:12.897   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{9895175: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.897   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:12.907   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{bc7850a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.907  6448  6448 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,07-27 08:57:12.907  6448  6448 I Avrcp   : Video App Package name is others
,07-27 08:57:12.907   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{e38e17b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.907  6448  6448 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package null
,07-27 08:57:12.907   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{30dab98: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.907   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{6aa8ff1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.907  6448  6448 V Avrcp   : MediaPlayerInfo: mPlayerId=4
,07-27 08:57:12.917  6448  6448 I Avrcp   : Add tempPlayer
07-27 08:57:12.917  6448  6448 V Avrcp   : MediaPlayerInfo: mPlayerId=5
07-27 08:57:12.917  6448  6448 V Avrcp   : no_of_players : 5
07-27 08:57:12.917  6448  6448 I Avrcp   : Total no of players: 5
,07-27 08:57:12.917  6448  6448 V Avrcp   : swapping the samsung player with 1st player
07-27 08:57:12.917  6448  6448 D Avrcp   : Compose Browsing Service Candidate
,07-27 08:57:12.917   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{3e0e7d6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.917  6448  6448 D Avrcp   : ResolveInfo info ResolveInfo{61558f8 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-27 08:57:12.917  6448  6448 D Avrcp   : Initialize Media Controller
,07-27 08:57:12.917  6448  6448 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-27 08:57:12.917   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{2ea1a57: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.917  6448  6448 E Avrcp   : getActiveSessions
07-27 08:57:12.917  6448  6448 D Avrcp   : pick active media Controller
07-27 08:57:12.917  6448  6448 D Avrcp   : Get the active Media Controller 
,07-27 08:57:12.917   753  2163 I ActivityManager: Killing 5471:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
07-27 08:57:12.917  6448  6448 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:57:12.917  6448  6448 D A2dpStateMachine: make
,07-27 08:57:12.917  6448  6448 I bt_bluedroid: get_profile_interface a2dp
,07-27 08:57:12.917  6448  6448 E bt_btif : warning : media task started media_task_refcnt 1 
,07-27 08:57:12.917  6448  6448 E bt_btif : warning : no command pending, ignore ack
,07-27 08:57:12.927  6448  6625 D A2dpStateMachine: Enter Disconnected: -2
,07-27 08:57:12.937  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-27 08:57:12.937   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{b0c04f3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.937  6448  6448 E A2dpService: notifyProfileServiceStateChanged
,07-27 08:57:12.937  6448  6448 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 08:57:12.937   753   769 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,07-27 08:57:12.937  6448  6448 D HidService: Received start request. Starting profile...
,07-27 08:57:12.937  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
07-27 08:57:12.937  6448  6448 I bt_bluedroid: get_profile_interface hidhost
07-27 08:57:12.937  6448  6448 D HidService: setHidService(): set to: null
07-27 08:57:12.937  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
,07-27 08:57:12.937  6448  6448 E HidService: notifyProfileServiceStateChanged
,07-27 08:57:12.947   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{49255b0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.947   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{e8a4c29: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.947  6448  6448 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 08:57:12.947   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{4cd1bae: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.947  6448  6448 D HealthService: Received start request. Starting profile...
,07-27 08:57:12.947  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
,07-27 08:57:12.947  6448  6448 I bt_bluedroid: get_profile_interface health
,07-27 08:57:12.947  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-27 08:57:12.957  6448  6448 E HealthService: notifyProfileServiceStateChanged
,07-27 08:57:12.957  6448  6448 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,07-27 08:57:12.957   753   753 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:57:12.957  6448  6448 D PanService: Received start request. Starting profile...
07-27 08:57:12.957   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{57fd4f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.957  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
07-27 08:57:12.957  6448  6448 D BluetoothPanServiceJni: initializeNative(L118): pan
07-27 08:57:12.957  6448  6448 I bt_bluedroid: get_profile_interface pan
,07-27 08:57:12.957  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
,07-27 08:57:12.957  6448  6448 E PanService: notifyProfileServiceStateChanged
07-27 08:57:12.957  6448  6448 D HeadsetStateMachine: Proxy object connected
,07-27 08:57:12.957   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{ebf1cdc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.967   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{5281e5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.967  6448  6448 D HeadsetStateMachine: Try to query the phonestate on bind
,07-27 08:57:12.967   753  1650 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 08:57:12.967   753  1650 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-27 08:57:12.967  6448  6448 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-27 08:57:12.967  6448  6602 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:57:12.967  6448  6602 E HeadsetStateMachine: Unknown message: 11
,07-27 08:57:12.967   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{2d344ba: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.967   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{4c11f6b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.967  6448  6448 D BluetoothMapService: Received start request. Starting profile...
07-27 08:57:12.967  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
,07-27 08:57:12.967  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-27 08:57:12.967  6448  6448 E BluetoothMapService: notifyProfileServiceStateChanged
,07-27 08:57:12.967   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{bd02b74: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.967  6448  6448 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 08:57:12.967  6448  6602 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-27 08:57:12.967  6448  6602 E HeadsetStateMachine: Unknown message: 19
07-27 08:57:12.967  6448  6448 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-27 08:57:12.967  6448  6448 V SapService: SapBinder()
,07-27 08:57:12.967  6448  6448 D SapService: Received start request. Starting profile...
07-27 08:57:12.967   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{498089d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.967  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
07-27 08:57:12.967  6448  6448 V SapService: start()
,07-27 08:57:12.977  6448  6448 D SapService: Disable sap : false
,07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-27 08:57:12.977  6448  6448 E SapService: notifyProfileServiceStateChanged
,07-27 08:57:12.977   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{a719199: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:12.977  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:12.977  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:57:12.977  6448  6602 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:57:12.977  6448  6602 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:57:12.977  6448  6602 E HeadsetStateMachine: Unknown message: 11
07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:12.977  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:12.977  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:12.977  6448  6448 D BluetoothAdapterService: HID Host service started
,07-27 08:57:12.987  6630  6630 E Zygote  : v2
07-27 08:57:12.987  6630  6630 I libpersona: KNOX_SDCARD checking this for 10121
07-27 08:57:12.987  6630  6630 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:12.987  6630  6630 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:12.987  6630  6630 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:12.987   753  1677 I ActivityManager: Start proc 6630:com.google.android.apps.maps/u0a121 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-27 08:57:12.987  6630  6630 E Zygote  : accessInfo : 0
,07-27 08:57:12.987  6630  6630 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,07-27 08:57:12.997   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{20dcc5e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.997   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2d8d83f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:12.997  6448  6448 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:57:12.997  6448  6448 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:57:12.997  6448  6448 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 08:57:12.997  6448  6602 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:57:12.997  6448  6602 E HeadsetStateMachine: Unknown message: 11
,07-27 08:57:12.997  6448  6448 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:12.997  6448  6602 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-27 08:57:12.997  6448  6602 E HeadsetStateMachine: Unknown message: 19
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:12.997   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{7f1750c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
,07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,07-27 08:57:12.997   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{6c0ae55: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:12.997  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:57:12.997  6448  6448 E BluetoothAdapterService: handleMessage() - Message: 1
,07-27 08:57:13.007  6448  6448 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-27 08:57:13.007   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{fe6506a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.007  6448  6448 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:57:13.007  6448  6448 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:13.007  6448  6448 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:13.007  6448  6448 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:57:13.007  6448  6468 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-27 08:57:13.007   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{d8cb95b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.007  6448  6468 E BluetoothServiceJni: enableBrEdrNative:
07-27 08:57:13.007  6448  6468 I bt_bluedroid: enable_bredr
,07-27 08:57:13.007   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{cc6d5f8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.007  6448  6579 D         : Codec ==> copy capability info [bta_av_co_audio_init:584]
,07-27 08:57:13.007  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.007  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.007  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.007   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{baadad1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.007  6448  6518 D bt_vendor: op for 7
,07-27 08:57:13.007  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.007  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.007   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{5110936: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.017  6448  6490 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xb2a86929
07-27 08:57:13.017  6448  6490 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
,07-27 08:57:13.017  6448  6490 D BluetoothAdapterProperties: Address is:7C:F9:0E:34:8A:A0
07-27 08:57:13.017  6448  6490 E BluetoothServiceJni: populateRssiValuesNative
07-27 08:57:13.017  6448  6490 I bt_bluedroid: getModelRssiValues
07-27 08:57:13.017  6448  6490 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 08:57:13.017  6448  6490 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 08:57:13.017  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.017   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{ed39037: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.017  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.017  6448  6490 D BluetoothAdapterProperties: Name is: S5-1
07-27 08:57:13.017  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.017   753   753 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-27 08:57:13.017  6448  6518 D bt_vendor: op for 7
,07-27 08:57:13.017  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.017  6448  6490 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:57:13.017  6448  6490 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:57:13.017  6448  6490 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:57:13.017  6448  6490 E bt_btif : btif_handle_bluetooth_enable_evt
07-27 08:57:13.017  6448  6490 E bt_btif : ANT+ socket does not initialize.
07-27 08:57:13.017  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.017  6359  6359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:57:13.017  6448  6518 D bt_vendor: op for 7
,07-27 08:57:13.017  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.017  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.017   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{78f59a4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.017  6448  6490 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-27 08:57:13.017   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{e31530d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.017  6448  6490 D IOP_DB_BT: db_open: db_open : handle 2996969488l, read 17911 bytes onto local cache
07-27 08:57:13.017  6448  6490 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-27 08:57:13.017  6448  6490 D IOP_DB_BT: db_query: result 1
07-27 08:57:13.017  6448  6490 I         : iop_db_open: iop_db_open status 0
,07-27 08:57:13.017  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.017  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.017  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.017  6448  6490 E BluetoothAdapterState: stateChangeCallback : 17
07-27 08:57:13.017  6448  6468 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
07-27 08:57:13.017  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.017  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.017  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.027  6448  6490 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:57:13.027  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.027  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.027  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.027  6448  6468 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:57:13.027  6448  6468 D BluetoothAdapterProperties: State =  11
,07-27 08:57:13.027  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.027  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.027  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.027   753   769 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-27 08:57:13.027   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{b5c82c2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.027  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.027  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.027  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.027   753  2163 D SecContentProvider: insert(), uri = 2
,07-27 08:57:13.027  6359  6359 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:57:13.027  6448  6490 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:57:13.027  6448  6490 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:57:13.027  6448  6468 D BluetoothAdapterProperties: Setting state to 12
07-27 08:57:13.027  6448  6468 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:57:13.027  6448  6490 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 08:57:13.027   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{a46f8d3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.027  6464  6464 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
07-27 08:57:13.027  6359  6359 D BluetoothAdapter: STATE_ON
,07-27 08:57:13.027  6448  6518 D bt_vendor: op for 7
,07-27 08:57:13.027  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.027  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{63a6c10: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.037  6464  6464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-27 08:57:13.037  6464  6464 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.037  6464  6464 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
07-27 08:57:13.037   306  1179 D Netd    : Iface wlan0 link up
07-27 08:57:13.037   306  1179 D Netd    : Iface wlan0 link up
07-27 08:57:13.037   306  1179 D Netd    : Iface wlan0 link up
07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.037   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:13.037   753   851 D Tethering: interfaceStatusChanged wlan0, true
07-27 08:57:13.037   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:13.037   753   851 D Tethering: interfaceStatusChanged wlan0, true
07-27 08:57:13.037   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:13.037   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.037   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{82d1309: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.037  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.037  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.037  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.047  6630  6630 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:13.047  6630  6630 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:13.047  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.047  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.047  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.047  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.047  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.047  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.047  6359  6359 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-27 08:57:13.047   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{8f4090e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:13.047  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:57:13.047  6448  6468 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:57:13.047  6448  6468 D BluetoothAdapterService: updateAdapterState state is 12
07-27 08:57:13.047  6464  6464 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,07-27 08:57:13.047  6464  6464 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,07-27 08:57:13.047  6464  6464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-27 08:57:13.047  6464  6464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:57:13.047  6359  6359 D BluetoothAdapter: STATE_ON
07-27 08:57:13.047  6464  6464 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 08:57:13.047   306  1179 D Netd    : Iface wlan0 link up
07-27 08:57:13.047   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:13.047   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:13.047   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:13.057   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{442393c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.057  6448  6468 V BluetoothAdapterService: start opp service
,07-27 08:57:13.057  6359  6359 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:57:13.057   753  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0ad6c5 6630:com.google.android.apps.maps/u0a121}
,07-27 08:57:13.067  1378  3338 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.067  1378  3338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:13.067  6448  6468 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:13.067  6448  6468 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 08:57:13.067  6448  6468 D BluetoothAdapterService: starting service from this receiver
,07-27 08:57:13.067  6030  6041 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.067  6030  6041 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.067   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{e2aaf4b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.067   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:13.067  6359  6370 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-27 08:57:13.067  6359  6370 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.067  6448  6617 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-27 08:57:13.067  6448  6617 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.067  2085  2126 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.067  6448  6448 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-27 08:57:13.067  2085  2126 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.077  6448  6468 D BluetoothAdapterService: BT on, init HID DEV count : 0
07-27 08:57:13.077  6448  6468 I BluetoothAdapterState: Entering OnState
,07-27 08:57:13.077  1860  1873 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-27 08:57:13.077  1860  1873 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:13.077   753   889 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:57:13.077   753   889 D BluetoothPan: onBluetoothStateChange on: true
07-27 08:57:13.077   753   889 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-27 08:57:13.077   753   889 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:13.077  6493  6503 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.077  6493  6503 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.077   753  1325 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-27 08:57:13.077   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{64e73d4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.077  1706  1719 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.077  1706  1719 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.077  2085  2139 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:57:13.077  1717  1938 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.077  1717  1938 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.077   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{aa197d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.077  1999  2011 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:13.077  1999  2011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:13.077   753   753 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:13.077   753   753 I InputMethodManagerService: [BT Setting State] State =12
07-27 08:57:13.077   753   753 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 08:57:13.087  1378  1378 D BluetoothTile:  onBluetoothStateChange:
,07-27 08:57:13.087  1764  1764 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:13.087  6630  6630 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package null
,07-27 08:57:13.087  1378  1378 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 08:57:13.087   753   753 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 08:57:13.087   753   753 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
07-27 08:57:13.087   753   753 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-27 08:57:13.087   753   753 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:13.087   753   753 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-27 08:57:13.087   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{fdf2072: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.087  1983  1983 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:57:13.097   753  1325 V AlarmManager:  remove PendingIntent] PendingIntent{343d079: PendingIntentRecord{3fad1be android broadcastIntent}}
,07-27 08:57:13.097   753  2163 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-27 08:57:13.097   753  2167 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-27 08:57:13.097  1378  1378 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:13.097  1378  1378 D BluetoothTile:  getBluetoothState : 12
,07-27 08:57:13.097  1378  1378 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,07-27 08:57:13.097   753  1325 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-27 08:57:13.097   753  1325 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 08:57:13.097   753  1332 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:57:13.097   753  1332 E ConnectivityService: updateNetworkInfo()
07-27 08:57:13.097   753  1332 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:13.097   753  1332 D ConnectivityService: NetworkAgent connected
,07-27 08:57:13.107  6448  6448 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:57:13.107  6448  6448 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:13.107  6448  6448 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
,07-27 08:57:13.107  6448  6448 W System.err: 	at com.android.bluetooth.opp.BluetoothOppService.onCreate(BluetoothOppService.java:195)
07-27 08:57:13.107  6448  6448 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3807)
07-27 08:57:13.107  6448  6448 W System.err: 	at android.app.ActivityThread.access$2100(ActivityThread.java:221)
07-27 08:57:13.107  6448  6448 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1882)
07-27 08:57:13.107  6448  6448 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:13.107  6448  6448 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:57:13.107  6448  6448 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-27 08:57:13.107  6448  6448 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:13.107  6448  6448 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:57:13.107  6448  6448 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,07-27 08:57:13.107  1378  2934 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:57:13.107  6448  6448 V BtOppService: isOwner == true
07-27 08:57:13.107   753   753 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:57:13.107   753   753 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:13.107   753   753 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-27 08:57:13.107   306  1186 D CommandListener: Setting iface cfg
,07-27 08:57:13.107   753  1330 I WifiHs20Service: Message received 5007
,07-27 08:57:13.117   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{de07a04: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.117   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{d95bed: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.117  1378  2934 D BluetoothTile:  handleUpdatestate:false name:null
07-27 08:57:13.117   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{cdc8a22: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.127   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{6fcc9e9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.127   753  1325 D WifiStateMachine: Start Dhcp Watchdog 1
,07-27 08:57:13.127  6630  6630 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-27 08:57:13.127  1378  2934 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:57:13.127   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:13.127   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{ed86c34: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.127   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{1aa17a0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.127   753  1325 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-27 08:57:13.137   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{e5eff59: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.137   753  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:57:13.147  6448  6448 I BluetoothPbapService: Handler(): got msg=1
,07-27 08:57:13.147   753  1677 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 08:57:13.147   753  1332 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:13.147   753  1332 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-27 08:57:13.147   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{233c182: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.157   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{18b3093: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.157   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{5c2a8d0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.157  6448  6651 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-27 08:57:13.167   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{43170c9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.177  6652  6652 E Zygote  : v2
,07-27 08:57:13.177  6652  6652 I libpersona: KNOX_SDCARD checking this for 10162
07-27 08:57:13.177  6652  6652 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:13.177  6652  6652 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:13.177  6652  6652 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:13.177   753  2013 I ActivityManager: Start proc 6652:com.android.email/u0a162 for content provider com.android.email/.provider.EmailProvider
,07-27 08:57:13.177   753  1323 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:57:13.177  6652  6652 E Zygote  : accessInfo : 0
,07-27 08:57:13.177  6652  6652 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-27 08:57:13.177   753   753 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@d417001
07-27 08:57:13.177   753   753 D BluetoothHeadset: registerMessageListener
,07-27 08:57:13.187   753  1323 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 08:57:13.187  6448  6462 D HeadsetService: registerMessageListener
,07-27 08:57:13.187  6448  6462 D HeadsetService: registerMessageListener
07-27 08:57:13.187  6448  6602 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-27 08:57:13.187  6448  6602 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@13bd6ca
,07-27 08:57:13.187   753   753 I Telecom : BluetoothManager : register MessageListener
,07-27 08:57:13.187   753   753 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,07-27 08:57:13.187   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{6c32ea6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.187  6448  6651 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:13.187  6448  6651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:13.197  6448  6618 D A2dpStateMachine: getConnectedDevices : size=0
,07-27 08:57:13.197  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.197  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.197  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 08:57:13.197  6448  6651 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 08:57:13.197   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{3b5a0e7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.217   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{5061494: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.217  6652  6652 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:13.217  6652  6652 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:13.217   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{c540b3d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.227   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{9638f32: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.227   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{7b16483: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.227   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{379e600: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.227  6652  6652 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.android.email rsrc of package null
,07-27 08:57:13.237   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{2fb1e39: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.237   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{1376c7e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.237   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{f1bc5df: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.237   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{e97622c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.237   753  1325 E WifiNative-wlan0: do suspend false
,07-27 08:57:13.237   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{6664f5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.247   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{8d9d28a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.247   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{3a0e0fb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.247  1378  1378 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-27 08:57:13.247  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:13.247  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:13.247  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:13.247  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:13.247   753  1324 D WifiP2pService: InactiveState{ what=143375 }
,07-27 08:57:13.247   753  1324 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:57:13.247   753  1325 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:13.247   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{d2e7518: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.257   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{d055b71: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.257   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{78a8d56: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.257   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{39291d7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.257   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{121cac4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.277   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{ec33dad: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.277  6666  6666 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:57:13.277   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{6ba28e2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.277  6666  6666 I dhcpcd  : version 5.5.6 starting
,07-27 08:57:13.277  6666  6666 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:57:13.277   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{6847473: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.287   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{5d2cf30: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.287   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{50307a9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.287   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{455f12e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.287   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{fa7e4cf: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.287   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{94dae5c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.297   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{85b7565: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.297   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{dd3f23a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.297   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{9e7feeb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.297   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{c355448: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.307   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{a1302e1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.307   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{ffef806: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.307   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{9c59ec7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.307   753  1485 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:13.307   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{46f6cf4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.307   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{f5bec1d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.317   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{7828e92: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.317   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{f36063: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.317   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{e906460: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.317   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{4502d19: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.317   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{e3701de: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.337   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{fb19fbf: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.347   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a07668c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.347   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{2ad81d5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.347   753  1320 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:13.347   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{12d5dea: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.347   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{fea78db: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.357   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{c0a5f78: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.357   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{8516651: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.357   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{b7b6eb6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.357   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{60dc7b7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.357   753  1747 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:13.357   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{541fb24: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.367   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{635a590: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.367   753  1485 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:13.367   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{aa98e89: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.367   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{a959e8e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.387   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{7d7f6af: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.387   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{e778abc: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.387  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:57:13.387  6666  6666 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-27 08:57:13.387  6666  6666 I dhcpcd  : bssid match
07-27 08:57:13.387   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{e938a45: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.397  6666  6666 I dhcpcd  : wlan0: rebinding lease of 192.168.1.123
,07-27 08:57:13.397   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{f51159a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.397   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{9374ecb: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.397   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{29096a8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.397   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{36785c1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.407   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{21af166: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.407  6448  6599 D bt_upio : ..proc_btwrite_timeout..
07-27 08:57:13.407  6448  6599 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 08:57:13.407   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{5ea0ca7: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.427   753  1417 I ActivityManager: Start proc 6686:com.sec.android.provider.badge/u0a77 for content provider com.sec.android.provider.badge/.BadgeProvider
07-27 08:57:13.427  6686  6686 E Zygote  : v2
07-27 08:57:13.427  6686  6686 I libpersona: KNOX_SDCARD checking this for 10077
07-27 08:57:13.427  6686  6686 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:13.427  6686  6686 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:13.427  6686  6686 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:13.427   753  1789 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 08:57:13.427  6686  6686 E Zygote  : accessInfo : 0
07-27 08:57:13.427  6686  6686 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-27 08:57:13.427   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{4ac7554: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.427   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{c25bcfd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.427   753  2163 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:13.437   753  1677 I ActivityManager: Killing 5307:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,07-27 08:57:13.437   753  1747 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:13.437   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{454bdf2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.437  6448  6448 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-27 08:57:13.447  6448  6448 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:13.447  6448  6448 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:13.447   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{520cc43: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.447   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{c0592c0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.457  6448  6448 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:13.457  6448  6448 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:13.457   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{1962bf9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.457  6448  6698 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:13.457  6448  6698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:57:13.457  6448  6701 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:13.457  6448  6701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:13.457   753  1650 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,07-27 08:57:13.457  6448  6687 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-27 08:57:13.467  6448  6687 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:13.467  6448  6687 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:13.467  6448  6687 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,07-27 08:57:13.467  6666  6666 I dhcpcd  : wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,07-27 08:57:13.487  6448  6701 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-27 08:57:13.487  6448  6701 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-27 08:57:13.487  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.487  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.487  6448  6518 D bt_upio : upio_start_stop_timer : timer_settime success
07-27 08:57:13.487  6448  6518 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-27 08:57:13.487  6448  6448 D ObexServerSockets: Succeed to create listening sockets 
07-27 08:57:13.487  6448  6448 D ObexServerSockets: startAccept()
,07-27 08:57:13.487  6686  6686 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:13.487  6686  6686 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:13.487  6448  6698 I BtOppRfcommListener: Accept thread started.
07-27 08:57:13.487  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.487  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.487  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.487   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{9ecc73e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.497   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{679e99f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.497   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{7111aec: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.497   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{7048eb5: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.497   753  1623 I ActivityManager: Killing 4582:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,07-27 08:57:13.507  6448  6707 D ObexServerSockets: Accepting socket connection for masId0
,07-27 08:57:13.507  6448  6708 D ObexServerSockets: Accepting socket connection for masId0
,07-27 08:57:13.517  6666  6666 I dhcpcd  : wlan0: leased 192.168.1.123 for 172800 seconds
,07-27 08:57:13.517   753  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:57:13.597   753  1320 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
07-27 08:57:13.597  6686  6686 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package null
,07-27 08:57:13.597  6448  6448 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-27 08:57:13.597  6448  6448 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-27 08:57:13.597  6448  6518 D bt_vendor: op for 7
07-27 08:57:13.597  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 08:57:13.597  6448  6518 D bt_upio : BT_WAKE is asserted already
07-27 08:57:13.597  6448  6448 D BluetoothSdpJni: SDP Create record success - handle: 1
,07-27 08:57:13.607  6686  6686 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm
,07-27 08:57:13.607  6630  6677 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,07-27 08:57:13.617  6630  6677 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,07-27 08:57:13.617  6630  6677 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,07-27 08:57:13.617  6686  6686 D BadgeProvider: onCreate
,07-27 08:57:13.617  6686  6686 D BadgeProvider: DatabaseHelper
,07-27 08:57:13.637  6686  6699 D BaseReflect: null getOwnClass TEST
,07-27 08:57:13.637   753   764 I art     : Background partial concurrent mark sweep GC freed 77678(5MB) AllocSpace objects, 18(360KB) LOS objects, 27% free, 42MB/58MB, paused 1.957ms total 167.368ms
07-27 08:57:13.637  6686  6699 D MethodReflector: android.content.ContentResolver getClass TEST
07-27 08:57:13.637  6686  6699 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,07-27 08:57:13.637  6686  6699 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-27 08:57:13.637  6686  6699 D MethodReflector: notifyChange is called
,07-27 08:57:13.637  6686  6699 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-27 08:57:13.637  6686  6699 D BadgeProvider: sendNotify, [notify] : null
,07-27 08:57:13.637  6686  6699 D BadgeProvider: update, getCallingPackage() : com.android.email
07-27 08:57:13.637  6686  6699 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-27 08:57:13.637  6686  6699 D BadgeProvider: update, [uri.query] : null
07-27 08:57:13.637  6686  6699 D BadgeProvider: update, [BadgeCount] : badgecount=0
,07-27 08:57:13.637  6686  6699 D BadgeProvider: update, [UpdateCount] : 1
,07-27 08:57:13.647  1732  1732 D Launcher.Model: reloadBadges entered.
,07-27 08:57:13.647  1732  1732 D Launcher.Model: reloadBadges entered.
,07-27 08:57:13.687  6686  6699 D BadgeProvider: query, [selection] : null
,07-27 08:57:13.697   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{ebc6131: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.697   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{8b88016: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.707   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{4996d97: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.707  6686  6699 D BadgeProvider: query, [selection] : null
,07-27 08:57:13.707   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{e81db84: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.707   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{a44df6d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.727   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{6b487a2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.727   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{57d4c33: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.747   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{6032bf0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.757   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{25d0569: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.777   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{1777bee: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.777   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{fb6788f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.777   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{707171c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.777   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2b78f25: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:13.777   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{16368fa: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.787   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{cac0eab: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.787   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{4fc8908: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.787   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{576f8a1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.787   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{ef1ac6: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.787   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{b1aea87: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.797   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{9552db4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.797   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{a697ddd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.797   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{9321d52: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.797   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{eb1a823: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.797   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{f17120: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.807   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{6051ad9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.807   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{b30bc9e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.807   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{d6ca37f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.807   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{44c7f4c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.817   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{4238b95: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.817   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{1e804aa: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.817   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{6b1f89b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.817   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{6684438: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.817   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{a7e4c11: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.827   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{919c176: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.827   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{2d8377: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.827   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{6796be4: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.827   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{6ea984d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.827   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{4d87f02: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.837   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{46ce013: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.837   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{536250: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.837   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{5556c49: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.837   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{5d3894e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.837   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{f3b6a6f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.837   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{794537c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.847   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{97f8405: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.847   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{662ec5a: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.847   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{3be3e8b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.847   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{9912b68: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.857   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{8795b81: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.857   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{c537426: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.857   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{8503867: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.857   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{2019614: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.857   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{ddf2ebd: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.867   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{41df403: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.867   753  1325 E WifiNative-wlan0: do suspend true
,07-27 08:57:13.867   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{e6bff80: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.867   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{8d4f9b9: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.867   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{4dae1fe: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.867   753  1324 D WifiP2pService: InactiveState{ what=143375 }
,07-27 08:57:13.877   753  1324 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:57:13.877   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{a81cd5f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.877   753  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:57:13.877   753  1325 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-27 08:57:13.877   753  1325 D WifiStateMachine: VerifyingLinkState enter
07-27 08:57:13.877   753  1332 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:13.877   753  1332 E ConnectivityService: updateNetworkInfo()
,07-27 08:57:13.877   753  1332 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,07-27 08:57:13.877   753  1332 D ConnectivityService: Adding iface wlan0 to network 502
,07-27 08:57:13.887   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{c5193ac: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.887   753   753 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-27 08:57:13.887   753   753 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:13.887   753   753 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-27 08:57:13.887   753  1330 I WifiHs20Service: Message received 5007
07-27 08:57:13.887   753  1344 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-27 08:57:13.887  6652  6680 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:13.887   753  1344 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:13.887  6652  6680 D skia    : ---- fAsset->read(0) returned 0
07-27 08:57:13.887   753  1344 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:13.887   753  1344 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:13.887   753  1344 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:13.897   753  1677 I ActivityManager: Killing 5726:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
07-27 08:57:13.897  1999  1999 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
07-27 08:57:13.897   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
07-27 08:57:13.897   753  1325 D WifiNative-wlan0: callSECApiInt - ID [210]
07-27 08:57:13.897   753  1344 I WifiManager: isCaptivePortalException
07-27 08:57:13.897   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{cc27875: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.907   753  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-27 08:57:13.907   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20238f0 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
07-27 08:57:13.907   753  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-27 08:57:13.907   753  1344 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
07-27 08:57:13.907   753  1344 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {eff200a}
07-27 08:57:13.907   753  1344 I WifiManager: isCaptivePortalException
,07-27 08:57:13.917   753  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-27 08:57:13.917   753  1344 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-27 08:57:13.917   753  1325 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,07-27 08:57:13.917   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{1fe07b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.917   753  1332 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,07-27 08:57:13.917   753  1332 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-27 08:57:13.917   753  1332 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,07-27 08:57:13.927   753  1332 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-27 08:57:13.927   753  1332 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,07-27 08:57:13.927   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{e1a3e98: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:13.927   753  1332 V NetworkStats: updateIfacesLocked()
,07-27 08:57:13.927   753  1332 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:13.927  1999  1999 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:13.927   753  1332 V NetworkStats: performPollLocked() took 3ms
,07-27 08:57:13.927   753  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 08:57:13.937   753  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:13.937   753  1332 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-27 08:57:13.937   753  1332 D ConnectivityService: Not required to send intent.
07-27 08:57:13.937   753  1332 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 08:57:13.937   753  1332 E ConnectivityService: updateNetworkInfo()
07-27 08:57:13.937   753  1332 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:13.937   753  1332 V NetworkStats: updateIfacesLocked()
07-27 08:57:13.937   753  1332 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:13.937   753  1332 V NetworkStats: performPollLocked() took 2ms
,07-27 08:57:13.937   753  1323 D NtpTrustedTime: forceRefresh: no connectivity
,07-27 08:57:13.947   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{27732d6 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:13.947   753  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 08:57:13.947   753  1325 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:57:13.947   753  1325 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:57:13.947   753  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:13.947   753  1332 D ConnectivityService: scheduleUnvalidatedPrompt 502
07-27 08:57:13.947   753  1332 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
07-27 08:57:13.947   753  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 08:57:13.947   753  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:13.947   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,07-27 08:57:13.947   753  6645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:57:13.947   753  6645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
,07-27 08:57:13.947   753  6645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:57:13.947   753  6645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
07-27 08:57:13.947   753  1325 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-27 08:57:13.947   753  1325 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-27 08:57:13.957   753   769 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,07-27 08:57:13.957   753  1332 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-27 08:57:13.957  1717  1731 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:57:13.957  1717  1731 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:57:13.957   753  1332 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-27 08:57:13.957   753   753 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 08:57:13.957   753   753 I WifiTrafficPoller: mBoosterFLAG : 0
07-27 08:57:13.957   753   753 I WifiTrafficPoller: current booster mode : FullMode
07-27 08:57:13.957   753   753 D WifiNative-wlan0: callSECApiVoid - ID [212]
07-27 08:57:13.957   753  1332 D ConnectivityService: currentScore = 0, newScore = 20
07-27 08:57:13.957  6464  6464 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 08:57:13.957  6464  6464 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 08:57:13.957   753  1332 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:13.957   753  1332 D ConnectivityService:    accepting network in place of null
07-27 08:57:13.957   753   753 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:57:13.957   753   753 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:13.957   753   753 D HS20StateMachine: SSID : "NG700"
07-27 08:57:13.957   753   753 D HS20StateMachine: NetId : 0
07-27 08:57:13.957   753   753 D HS20StateMachine: checkifOSUAP  null
,07-27 08:57:13.967   753  1332 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:13.967   753  1325 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:13.967   753  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:13.967   753  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:13.967   753  1325 D WIFI    : evalRequest
07-27 08:57:13.967   753  1325 D WIFI    :   done
,07-27 08:57:13.967   753   753 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-27 08:57:13.967   753  1324 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:13.967   753  1324 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:13.967   753  1324 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:13.967   753  1324 D WIFI_P2P: evalRequest
07-27 08:57:13.967   753  1324 D WIFI_P2P:   done
07-27 08:57:13.967   753  1330 I WifiHs20Service: Message received 5007
,07-27 08:57:13.967   753  1353 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:13.967   753  1325 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:13.967   753  1353 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-27 08:57:13.967   753  1353 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:13.967   753  1353 D Ethernet: evalRequest
07-27 08:57:13.967   753  1353 D Ethernet:   done
07-27 08:57:13.967   753  1325 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:13.967   753  1325 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:13.967   753  1325 D WIFI_UT : evalRequest
07-27 08:57:13.967   753  1325 D WIFI_UT :   done
,07-27 08:57:13.977   753  1323 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:57:13.977  6464  6464 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:13.977   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-27 08:57:13.977   753  1325 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:13.977   753  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:13.977   753  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:13.977   753  1325 D WIFI    : evalRequest
07-27 08:57:13.977   753  1325 D WIFI    :   done
,07-27 08:57:13.977   753  1332 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 08:57:13.977   306  1182 D EnterpriseController: netId is 0
07-27 08:57:13.977   306  1182 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,07-27 08:57:13.977   753  1323 D NtpTrustedTime: forceRefresh Fail.
,07-27 08:57:13.997   306  1186 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:57:14.007   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:14.007   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{2c0ac44: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.007   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{11e412d: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.017   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{78ba662: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.017   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{4f3e3f3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.017   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{c3e48b0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.027  5020  5020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 08:57:14.027   306  1186 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:57:14.027   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{81c6ae: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.027   753  1332 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,07-27 08:57:14.037   753  1417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{68eb49d 2085:com.samsung.android.providers.context/u0a174}
,07-27 08:57:14.037   753   889 D EntConnectivity: Not allowed due to - mEnabled false
,07-27 08:57:14.037  6630  6679 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 08:57:14.037   753  1332 D ConnectivityService: updateTcpDelayedAckSetting - WiFi setting
07-27 08:57:14.037   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{a5ecc4f: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:14.037   753  1332 D ConnectivityService: Setting TCP values: [1] which comes from [net.tcp.usercfg.wifi]
,07-27 08:57:14.037   753  1332 D ConnectivityService: Setting TCP values: [20] which comes from [net.tcp.delack.wifi]
,07-27 08:57:14.047   753  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.047  5020  5020 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
07-27 08:57:14.047   753  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.047   753  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.047   753  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:57:14.047   753  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.047   753  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.047   753  1332 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
07-27 08:57:14.047   753  1332 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,07-27 08:57:14.047   753  1332 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:14.047   753   769 D ConnectivityService: getVpnConfig > userId : 0
,07-27 08:57:14.057   753  1417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a0134c5 1860:com.sec.android.app.shealth:remote/u0a34}
07-27 08:57:14.057   753   889 D EntConnectivity: Not allowed due to - mEnabled false
,07-27 08:57:14.057  5020  5020 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-27 08:57:14.057   753  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:14.057   753  1332 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/753 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.057  5020  5020 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-27 08:57:14.057   753  1323 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:57:14.067   753  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:14.067   753  1332 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:14.067   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.067   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.067   753  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.067   306  1182 D EnterpriseController: netId is 0
07-27 08:57:14.067   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:57:14.067  1378  1378 D StatusBar.NetworkController: EthernetConnected: false
07-27 08:57:14.067  1378  1378 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:57:14.067  1378  1378 D StatusBar.NetworkController: updateDataNetType()
07-27 08:57:14.067  1378  1378 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 08:57:14.067  2291  2291 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-27 08:57:14.067   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:14.067   753  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:57:14.067   753   753 D Tethering: Tethering got CONNECTIVITY_ACTION
07-27 08:57:14.067   753   889 D Tethering: MasterInitialState.processMessage what=3
,07-27 08:57:14.067   753   753 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:14.067   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.067   753  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.067   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.067   753  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.077   753  1333 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-27 08:57:14.077  1717  1938 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:57:14.077  1717  1938 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-27 08:57:14.077   753  1333 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-27 08:57:14.077   753  1647 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:57:14.077  1378  1378 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 08:57:14.077   306  1182 D EnterpriseController: netId is 0
07-27 08:57:14.077   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 1000
07-27 08:57:14.077   753   753 V MARsPolicyManager: DataConnection: true
,07-27 08:57:14.077  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-27 08:57:14.077   753  1485 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:14.077   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.077   753  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.077   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.077   753  1332 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.077   753  1332 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-27 08:57:14.077   753  1332 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
,07-27 08:57:14.087   753  1332 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
07-27 08:57:14.087   753  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 08:57:14.087   753  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:14.087   753  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:14.087   753  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-27 08:57:14.087   753  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:14.087   753  1332 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/753 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:14.087   753  1332 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.087   753  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:57:14.087   753  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.087  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.087   753  1332 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1332 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.087   753  1325 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:14.087   753  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:14.087   753  1325 D WIFI    : evalRequest
07-27 08:57:14.087   753  1325 D WIFI    :   done
07-27 08:57:14.087   753  1324 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1324 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:14.087   753  1325 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1324 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:14.087   753  1324 D WIFI_P2P: evalRequest
07-27 08:57:14.087   753  1324 D WIFI_P2P:   done
07-27 08:57:14.087   753  1325 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:14.087   753  1325 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:14.087   753  1325 D WIFI_UT : evalRequest
07-27 08:57:14.087   753  1325 D WIFI_UT :   done
07-27 08:57:14.087   753  1353 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1353 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-27 08:57:14.087   753  1353 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:14.087   753  1353 D Ethernet: evalRequest
07-27 08:57:14.087   753  1332 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 08:57:14.087   753  1353 D Ethernet:   done
07-27 08:57:14.087   753  1325 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.087   753  1325 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:14.087   753  1325 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:14.087   753  1325 D WIFI    : evalRequest
07-27 08:57:14.087   753  1325 D WIFI    :   done
,07-27 08:57:14.087   753  1417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:14.097   753  1325 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
07-27 08:57:14.097   753  1325 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,07-27 08:57:14.097   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{9e5de6b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.097  6359  6359 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:57:14.097  1378  1378 D StatusBar.NetworkController: EthernetConnected: false
07-27 08:57:14.097  1378  1378 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:57:14.097  1378  1378 D StatusBar.NetworkController: updateDataNetType()
07-27 08:57:14.097  1378  1378 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,07-27 08:57:14.097  6493  6493 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:57:14.107   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{2667dc8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.107   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a6ae61: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.107   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{63ecf9d: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:14.117   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{c6e6c12: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.117  1808  1808 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:57:14.117   753  1332 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,07-27 08:57:14.117  1378  1378 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-27 08:57:14.117  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-27 08:57:14.117   753  1332 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:14.117   753   753 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:14.117   753  1332 D ConnectivityService: identical MTU - not setting
07-27 08:57:14.117  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 08:57:14.117  6359  6359 D BluetoothAdapter: STATE_ON
,07-27 08:57:14.117   753  1332 V NetworkStats: updateIfacesLocked()
07-27 08:57:14.117   753  1332 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:14.117  5020  5020 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 08:57:14.117   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{7ddafe3: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:57:14.117  6359  6359 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 08:57:14.127   753  1332 V NetworkStats: performPollLocked() took 3ms
,07-27 08:57:14.127  6359  6359 D BluetoothAdapter: STATE_ON
,07-27 08:57:14.127   753  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:14.127   753  1332 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:14.127   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{18d3de0: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.127  6359  6359 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 08:57:14.127   753  1332 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:14.127   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.127   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.127   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d3dc899: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.127   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.127   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{5c3375e: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
07-27 08:57:14.127   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.127   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService: Not required to send intent.
07-27 08:57:14.137   753  1332 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:14.137   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.137   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{5b8580c: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.137  5020  5020 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-27 08:57:14.147   753  1332 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.147   753  1332 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:14.147   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{df385b: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.147   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{398e8f8: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.157   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{6e6f1d1: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.157  5020  5020 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-27 08:57:14.157   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{e4eff37: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.167  5020  5020 E BluetoothHeadset: BTStateChangeCB is registed
,07-27 08:57:14.177  5020  5020 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:57:14.187  2045  2045 E audit   : type=1400 msg=audit(1469602634.187:289): avc:  denied  { ioctl } for  pid=4492 comm="ChromiumNet" path="socket:[40526]" dev="sockfs" ino=40526 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
07-27 08:57:14.187  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:14.187  2045  2045 E audit   : type=1300 msg=audit(1469602634.187:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=18 a1=8b1b a2=9ad64468 a3=9ad64460 items=0 ppid=353 ppcomm=main pid=4492 auid=4294967295 uid=10061 gid=10061 euid=10061 suid=10061 fsuid=10061 egid=10061 sgid=10061 fsgid=10061 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:57:14.187  2045  2045 E audit   : type=1327 msg=audit(1469602634.187:289): proctitle="com.google.android.googlequicksearchbox:search"
07-27 08:57:14.187  2045  2045 E audit   : type=1320 msg=audit(1469602634.187:289): 
,07-27 08:57:14.197   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{d948028: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.197   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{97d5b72: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:14.217  5020  5020 D BluetoothSap: Create BluetoothSap proxy object
,07-27 08:57:14.217  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:14.217  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:14.217   753  1348 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,07-27 08:57:14.227  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:14.227  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:14.227  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:14.257  5020  5020 D LocalBluetoothProfileManager: PANU : true
,07-27 08:57:14.267  5020  5020 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
,07-27 08:57:14.267  5020  5020 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 08:57:14.267  5020  5020 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-27 08:57:14.277   753   817 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 08:57:14.277  5020  5020 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:57:14.287   753  2013 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10162
,07-27 08:57:14.287  6448  6599 D bt_upio : ..proc_btwrite_timeout..
07-27 08:57:14.287  6448  6599 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 08:57:14.287  5020  5020 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:57:14.297   753  1789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10162
,07-27 08:57:14.297  5020  5020 D BluetoothA2dp: Proxy object connected
,07-27 08:57:14.297  5020  5020 D A2dpProfile: Bluetooth service connected
,07-27 08:57:14.307   753  1650 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10162
,07-27 08:57:14.307   753  1623 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10162
,07-27 08:57:14.307   753  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:14.307  1378  1378 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:14.307  1378  1378 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-27 08:57:14.317   753  2013 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-27 08:57:14.317  6448  6462 D A2dpStateMachine: getConnectedDevices : size=0
,07-27 08:57:14.317  5020  5020 D BluetoothMap: Proxy object connected
,07-27 08:57:14.327  5020  5020 D MapProfile: Bluetooth service connected
07-27 08:57:14.327  5020  5020 D BluetoothMap: getConnectedDevices()
,07-27 08:57:14.327   753  1650 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4e5d0ee 6448:com.android.bluetooth/1002}
,07-27 08:57:14.327  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2eefd5f
07-27 08:57:14.327  6448  6448 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 08:57:14.327   753   817 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:14.327   753   817 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:14.327  5020  5020 D BluetoothPbap: Proxy object connected
,07-27 08:57:14.337  5020  5020 D PbapServerProfile: Bluetooth service connected
,07-27 08:57:14.337  5020  5020 D BluetoothSap: Proxy object connected
,07-27 08:57:14.337  5020  5020 D SapProfile: Bluetooth service connected
,07-27 08:57:14.337  5020  5020 D BluetoothInputDevice: Proxy object connected
,07-27 08:57:14.337  5020  5020 D HidProfile: Bluetooth service connected
,07-27 08:57:14.337   753  1898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0ad6c5 6630:com.google.android.apps.maps/u0a121}
,07-27 08:57:14.337   753  1348 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,07-27 08:57:14.347   753  1898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 08:57:14.347  5020  5020 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:57:14.347  5020  5020 D PanProfile: Bluetooth service connected
,07-27 08:57:14.357  5020  5020 D HeadsetProfile: Bluetooth service connected
,07-27 08:57:14.357  4114  6763 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:57:14.367  1999  6764 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:14.387  1717  1938 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:57:14.387  1717  1938 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-27 08:57:14.397   753   817 D TelephonyManager: getDataEnabled: retVal=true
,07-27 08:57:14.397  1717  1731 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@c1bb383, selection=nullselectionArgs=null, sort=name ASC
07-27 08:57:14.397  1999  1999 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:14.397  1717  1731 D TelephonyProvider: query: match = 5
,07-27 08:57:14.407   753  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c20957 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 08:57:14.407   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{8323af7: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:14.417  1717  1731 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-27 08:57:14.427   753   817 E GpsLocationProvider: No APN found to select.
,07-27 08:57:14.437  6448  6770 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:57:14.437  6448  6770 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:14.437  6448  6770 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:14.437  6448  6770 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,07-27 08:57:14.447  4114  6762 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
07-27 08:57:14.447   753   817 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38318, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:57:14.457   753   817 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 306833, reason: UserStart
,07-27 08:57:14.477  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:14.487  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:14.487  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:14.487  1999  6764 I GLSUser : Method not found getActionBar
,07-27 08:57:14.487  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:14.487   753  1898 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:57:14.527  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:14.537  1999  6774 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 08:57:14.537  1999  1999 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:14.557   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8d5e0b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:14.577  1999  1999 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:14.577   753  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8d5e0b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:14.577  5020  5020 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:57:14.577  5020  5020 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 08:57:14.587   753  1623 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:14.587  5020  5020 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,07-27 08:57:14.587   753  2167 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:14.587  5020  5020 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-27 08:57:14.587  5020  5020 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
07-27 08:57:14.587  5020  5020 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:57:14.597   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8d5e0b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0b0375 6493:tv.peel.smartremote/u0a170}
,07-27 08:57:14.607  6777  6777 E Zygote  : v2
07-27 08:57:14.607  6777  6777 I libpersona: KNOX_SDCARD checking this for 10163
07-27 08:57:14.607  6777  6777 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:14.607  6777  6777 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:14.607   753  1747 I ActivityManager: Start proc 6777:com.android.exchange/u0a163 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
07-27 08:57:14.607  6777  6777 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:14.607  6777  6777 E Zygote  : accessInfo : 0
07-27 08:57:14.607  6777  6777 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
,07-27 08:57:14.617  1999  6764 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:14.617  1999  6764 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:14.617   306  1182 D EnterpriseController: netId is 0
07-27 08:57:14.617   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-27 08:57:14.627   753   827 I ActivityManager: Start proc 6789:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,07-27 08:57:14.627  6789  6789 E Zygote  : v2
07-27 08:57:14.627  6789  6789 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:14.627  6789  6789 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:14.627  6789  6789 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:14.627  6789  6789 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:14.627  6789  6789 E Zygote  : accessInfo : 0
,07-27 08:57:14.637  6777  6777 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:14.637  6777  6777 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:14.647  1999  6774 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 08:57:14.647   753  2163 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c61577e u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{78ed4df 6777:com.android.exchange/u0a163}
,07-27 08:57:14.667  6789  6789 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:14.667  6789  6789 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:14.667  6777  6777 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in com.android.exchange rsrc of package null
,07-27 08:57:14.677   753  1650 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d8d5e0b u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c9d8bf5 6789:com.sec.android.diagmonagent/1000}
,07-27 08:57:14.677  6777  6777 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,07-27 08:57:14.677  6789  6789 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package null
,07-27 08:57:14.697  6789  6789 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm
,07-27 08:57:14.707   753  1623 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:14.717   753  1417 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b5dffb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c9d8bf5 6789:com.sec.android.diagmonagent/1000}
,07-27 08:57:14.727  6789  6789 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-27 08:57:14.767   753  2013 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:14.777  4930  6805 D PicasaService: start picasa sync
,07-27 08:57:14.777  1999  6764 I qtaguid : Tagging socket 41 with tag 40100000000{1025,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:14.777  4930  6805 D PicasaService: end picasa sync
,07-27 08:57:14.857  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:14.857  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:14.897  1999  6764 I qtaguid : Tagging socket 45 with tag 40100000000{1025,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:14.907  6789  6789 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,07-27 08:57:14.917  6789  6789 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,07-27 08:57:14.927  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:57:14.927  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:14.927  6789  6789 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-27 08:57:14.927  6789  6789 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-27 08:57:14.927  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:57:14.927  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:14.927  6789  6789 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-27 08:57:14.927  6789  6789 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-27 08:57:14.937   753   769 I ActivityManager: Start proc 6807:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,07-27 08:57:14.937  6807  6807 E Zygote  : v2
07-27 08:57:14.937  6807  6807 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:14.937  6807  6807 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:14.937  6807  6807 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:14.937  6807  6807 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:14.947  6807  6807 E Zygote  : accessInfo : 0
,07-27 08:57:14.967   753  1650 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b5dffb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:14.977  6807  6807 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:14.977  6807  6807 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:14.977   753  2163 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b5dffb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:14.987   753  1623 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d8d5e0b u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4440306 6807:com.sec.knox.switcher/1000}
,07-27 08:57:14.997  5020  5020 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 08:57:14.997  5020  5020 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:57:15.017  6807  6807 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package null
,07-27 08:57:15.017   753  1485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b5dffb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4440306 6807:com.sec.knox.switcher/1000}
,07-27 08:57:15.027  6807  6807 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm
,07-27 08:57:15.037  6807  6807 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
,07-27 08:57:15.037  6807  6807 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
07-27 08:57:15.037  1999  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:15.037  1999  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:15.047  1999  6775 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 1999, getuid(): 10011
,07-27 08:57:15.047  6807  6807 I usagelog: received in receiver
,07-27 08:57:15.047  6807  6807 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-27 08:57:15.047  6807  6807 I KnoxUsageLogPro: premStatus:2
,07-27 08:57:15.047  6807  6807 I KnoxUsageLogPro: isEulaShown : false
,07-27 08:57:15.047  6807  6807 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:57:15.057  6807  6807 I usagelog: received in receiver
07-27 08:57:15.057  6807  6807 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-27 08:57:15.057  6807  6807 I KnoxUsageLogPro: premStatus:2
,07-27 08:57:15.057  6807  6807 I KnoxUsageLogPro: isEulaShown : false
,07-27 08:57:15.057  6807  6807 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:57:15.067  6822  6822 E Zygote  : v2
,07-27 08:57:15.067  6822  6822 I libpersona: KNOX_SDCARD checking this for 10203
07-27 08:57:15.067  6822  6822 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:15.067  6822  6822 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 08:57:15.067   753  2167 I ActivityManager: Start proc 6822:com.samsung.android.sm.policy/u0a203 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
07-27 08:57:15.067  6822  6822 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:15.067  6822  6822 E Zygote  : accessInfo : 0
,07-27 08:57:15.067  6822  6822 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-27 08:57:15.077   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b5dffb u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0b0375 6493:tv.peel.smartremote/u0a170}
,07-27 08:57:15.097   753  1485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6854dc7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c9d8bf5 6789:com.sec.android.diagmonagent/1000}
,07-27 08:57:15.097  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:57:15.097  6448  6518 D bt_vendor: op for 7
,07-27 08:57:15.097  6448  6518 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-27 08:57:15.097  6448  6518 D bt_upio : BT_WAKE is de-asserted already
,07-27 08:57:15.097  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:15.097  6822  6822 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:15.107  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:15.107  6789  6789 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-27 08:57:15.107  6789  6789 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3634 
,07-27 08:57:15.107   753  1623 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d8d5e0b u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35eeff4 6822:com.samsung.android.sm.policy/u0a203}
,07-27 08:57:15.107   753  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6854dc7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:15.117   753  1747 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-27 08:57:15.127  6822  6822 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package null
,07-27 08:57:15.137   753  2163 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,07-27 08:57:15.147   753  1789 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,07-27 08:57:15.147   753  1650 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,07-27 08:57:15.167  1378  1378 D ViewRootImpl: #1 mView = android.widget.LinearLayout{650cdd5 V.E...... ......I. 0,0-0,0 #10203a7 android:id/toast_layout_root}
,07-27 08:57:15.167  6822  6822 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm
,07-27 08:57:15.167   753   769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6854dc7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4339c 5020:com.android.settings/1000}
,07-27 08:57:15.167  5020  5020 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 08:57:15.167  5020  5020 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:57:15.167   753  1677 D ISSUE_DEBUG: InputChannelName : 28d4992 Toast
,07-27 08:57:15.177   753  1677 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,07-27 08:57:15.187   753   769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6854dc7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4440306 6807:com.sec.knox.switcher/1000}
07-27 08:57:15.187   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=4, Uoast
,07-27 08:57:15.187  6807  6807 I usagelog: received in receiver
,07-27 08:57:15.187  6807  6807 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-27 08:57:15.187  6807  6807 I KnoxUsageLogPro: premStatus:2
,07-27 08:57:15.197  6807  6807 I KnoxUsageLogPro: isEulaShown : false
07-27 08:57:15.197  6807  6807 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:57:15.197   753   768 I ActivityManager: Killing 5853:com.google.android.partnersetup/u0a14 (adj 15): DHA:empty #37
,07-27 08:57:15.207  1999  6775 I qtaguid : Tagging socket 49 with tag 1000040100000000{268436481,0} uid 10011, pid: 1999, getuid(): 10011
07-27 08:57:15.207   753   768 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6854dc7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35eeff4 6822:com.samsung.android.sm.policy/u0a203}
,07-27 08:57:15.207   753  1650 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=753
,07-27 08:57:15.217   753  1417 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b5dffb u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{35eeff4 6822:com.samsung.android.sm.policy/u0a203}
,07-27 08:57:15.227  1378  1378 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-27 08:57:15.227   753  1650 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-27 08:57:15.237   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{751760: PendingIntentRecord{eae52ac com.google.android.apps.plus broadcastIntent}}
,07-27 08:57:15.237   753  1623 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6854dc7 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0b0375 6493:tv.peel.smartremote/u0a170}
,07-27 08:57:15.247  1378  1378 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 08:57:15.247   753  1650 V WindowStateAnimator: Finishing drawing window Window{28d4992 u0 d0 Toast}: mDrawState=DRAW_PENDING
,07-27 08:57:15.257   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{33a6419: PendingIntentRecord{eb26cde com.google.android.apps.plus broadcastIntent}}
,07-27 08:57:15.257   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8b2364
,07-27 08:57:15.277   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e186a7c 6359:com.test.thalitest/u0a4}
,07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.277   753  2013 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:15.287   753  2013 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.287   753  2013 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.287   753  2013 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:15.287   753  2013 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:15.297   753  1677 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d6c7ef 753:system/1000}
,07-27 08:57:15.307   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 08:57:15.307   753  1677 I ActivityManager: Killing 5878:com.samsung.groupcast/u0a15 (adj 15): DHA:empty #37
,07-27 08:57:15.317   753  2167 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7faba2a 4114:com.google.android.gms/u0a11}
,07-27 08:57:15.327   306  1182 D EnterpriseController: netId is 0
07-27 08:57:15.327   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-27 08:57:15.327  4114  6840 I iu.SyncManager: SYNC; picasa accounts
,07-27 08:57:15.337  4114  4114 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-27 08:57:15.337  4114  4114 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 08:57:15.337   753  1650 D ActivityManager: isAutoRunBlockedApp:: com.samsung.groupcast, Auto Run ON
,07-27 08:57:15.347  4114  6840 I iu.UploadsManager: num queued entries: 0
,07-27 08:57:15.347  4114  6840 I iu.UploadsManager: num updated entries: 0
,07-27 08:57:15.347  4114  6840 I iu.SyncManager: NEXT; no task
,07-27 08:57:15.347   753  1485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7faba2a 4114:com.google.android.gms/u0a11}
,07-27 08:57:15.367   753  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.AccountsChangedReceiver newState = 2 callingPackage = 10011
,07-27 08:57:15.377   753  2167 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{104498c 2291:com.sec.android.widgetapp.ap.hero.accuweather/u0a70}
,07-27 08:57:15.387  2291  2291 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-27 08:57:15.387  2291  2291 D accuweather: [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,07-27 08:57:15.387  2291  2291 D accuweather: [KK AccuPhone]>>> UIMEM:91 [0:0] getInstance
,07-27 08:57:15.387  2291  2291 D accuweather: [KK AccuPhone]>>> UIMEM:79 [0:0] UIManager : create ui manager
,07-27 08:57:15.397  2291  2291 D accuweather: [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,07-27 08:57:15.397  2291  2291 D accuweather: [KK AccuPhone]>>> RM:136 [0:0]  V init 
,07-27 08:57:15.397  1517  1528 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:57:15.407  2291  2291 D accuweather: [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,07-27 08:57:15.407  1517  2416 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 08:57:15.407  2291  2291 D accuweather: [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,07-27 08:57:15.417   753  1647 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1469602635653 mCachedNtpElapsedRealtime : 275308 mCachedNtpCertainty : 144
,07-27 08:57:15.417   753  1323 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1469602635654 mCachedNtpElapsedRealtime : 275308 mCachedNtpCertainty : 144
,07-27 08:57:15.417   753  1647 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:57:15.417  1517  1529 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:57:15.417   753  1647 D AlarmManager: setTime : 1469602635656 calling from uid: 1000 pid :753
,07-27 08:57:15.417   753  1647 D AlarmManagerService: Setting time of day to sec=1469602635
07-27 08:57:15.417   753  1647 D AlarmManagerService: Trying to open a file
07-27 08:57:15.417   753  1647 E AlarmManagerService: File Open Failed
,07-27 08:57:15.656   753  1647 W AlarmManagerService: Unable to set rtc to 1469602635: Invalid argument
07-27 08:57:15.656   753  1647 V AlarmManager:  remove PendingIntent] PendingIntent{8afdf32: PendingIntentRecord{b8f7483 android broadcastIntent}}
,07-27 08:57:15.656   753  1236 V AlarmManager: Expired Alarm result :65536
,07-27 08:57:15.656   753  1320 I ActivityManager: Killing 5916:com.sec.android.app.myfiles/u0a50 (adj 15): DHA:empty #37
,07-27 08:57:15.656   753  1320 I ActivityManager: Killing 5890:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): DHA:empty #37
,07-27 08:57:15.656  2291  2291 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-27 08:57:15.656  2291  2291 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,07-27 08:57:15.666   753  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:15.666   753  1323 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:15.666   753  1323 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,07-27 08:57:15.666   753  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:15.666   753  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:15.666   753  1323 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:15.666   753  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:57:15.666   753  1323 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-27 08:57:15.666   753  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:57:15.676   753  1747 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.myfiles, Auto Run ON
,07-27 08:57:15.686   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e6af7db u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c9d8bf5 6789:com.sec.android.diagmonagent/1000}
,07-27 08:57:15.686  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,07-27 08:57:15.686  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:15.686  6789  6789 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 08:57:15.686   753  1677 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,07-27 08:57:15.686  6789  6789 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(18/llllIIIllIlIIIIllllI)] timeToActivate is not set. Do not anything.
,07-27 08:57:15.706  6846  6846 E Zygote  : v2
07-27 08:57:15.706  6846  6846 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:15.706  6846  6846 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:15.706  6846  6846 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:15.706  6846  6846 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:15.706   753   827 I ActivityManager: Start proc 6846:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,07-27 08:57:15.706  6846  6846 E Zygote  : accessInfo : 0
,07-27 08:57:15.736  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:15.736  6846  6846 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:15.736   753  1485 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9727278 6846:com.policydm/1000}
,07-27 08:57:15.746  6846  6846 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package null
,07-27 08:57:15.756  6846  6846 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,07-27 08:57:15.806  6846  6846 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-27 08:57:15.866  1999  6839 I qtaguid : Tagging socket 50 with tag 1000040700000000{268436487,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:15.866  6846  6846 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
,07-27 08:57:15.866  6846  6846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,07-27 08:57:15.886   753  2163 I ActivityManager: Start proc 6861:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,07-27 08:57:15.886  6861  6861 E Zygote  : v2
07-27 08:57:15.886  6861  6861 I libpersona: KNOX_SDCARD checking this for 10210
07-27 08:57:15.886  6861  6861 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:15.886  6861  6861 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:15.886  6861  6861 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:15.896  6846  6846 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-27 08:57:15.896  6861  6861 E Zygote  : accessInfo : 0
07-27 08:57:15.896  6861  6861 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,07-27 08:57:15.916  6846  6846 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,07-27 08:57:15.916  1999  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:15.916  1999  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:15.916   306  1182 D EnterpriseController: netId is 0
07-27 08:57:15.916   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
07-27 08:57:15.916   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{59736b7 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 08:57:15.936  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:15.936  6846  6846 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
07-27 08:57:15.936  6861  6861 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:15.946   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{3999d8d: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:15.946  6861  6861 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,07-27 08:57:15.946  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:57:15.956  6846  6846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6316 
,07-27 08:57:15.966  6846  6846 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,07-27 08:57:15.966  6861  6861 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-27 08:57:15.966  6861  6861 D AASAservice: onCreate()
,07-27 08:57:15.986  6846  6846 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:57:15.996  6846  6846 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:15.996  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:57:16.006   753  1650 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:16.006  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
,07-27 08:57:16.006  6846  6878 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-27 08:57:16.006  6846  6878 I DBG_POLICYDM: [com.policydm.XDMService(382/lllIlIlIIIllIIlIllIl)] a previous network is 0, current network is 2
,07-27 08:57:16.006  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-27 08:57:16.006  6846  6878 E DBG_POLICYDM: [com.policydm.XDMService(384/lllIlIlIIIllIIlIllIl)] network changed.... 
,07-27 08:57:16.006   753  1789 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9727278 6846:com.policydm/1000}
,07-27 08:57:16.006  6846  6878 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : true
,07-27 08:57:16.006  6846  6846 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-27 08:57:16.016  6846  6878 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(196/llIIIIlllllIIllIIllI)] DM Not Init
,07-27 08:57:16.016  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
,07-27 08:57:16.016  6846  6878 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
07-27 08:57:16.016  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,07-27 08:57:16.026  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:16.026  6846  6878 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:16.036  6846  6878 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,07-27 08:57:16.036  6846  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.XDMService.llllIIIllIlIIIIllllI:288 com.policydm.lllIlIlIIIllIIlIllIl.run:98 
,07-27 08:57:16.036  6846  6846 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
,07-27 08:57:16.036  6846  6879 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:57:16.036  6846  6879 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
07-27 08:57:16.036  6846  6878 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : false
,07-27 08:57:16.036  1999  6775 I qtaguid : Tagging socket 53 with tag 1000120300000000{268440067,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:16.036  6846  6879 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,07-27 08:57:16.036  6846  6879 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:57:16.046  6846  6879 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,07-27 08:57:16.046   753  2163 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:16.046  6846  6879 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-27 08:57:16.046  6846  6879 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:57:16.046  6846  6879 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,07-27 08:57:16.046  6846  6846 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,07-27 08:57:16.046  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
,07-27 08:57:16.046  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
,07-27 08:57:16.056   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bf32dbc u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 08:57:16.056  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
07-27 08:57:16.056  6846  6879 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
,07-27 08:57:16.056  6846  6879 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
,07-27 08:57:16.056  6846  6846 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-27 08:57:16.066  6846  6846 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:16.066  6846  6846 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-27 08:57:16.066   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{9e1f145: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:16.076  6846  6846 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-27 08:57:16.076  6846  6846 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-27 08:57:16.086  6846  6846 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/08/03/01:07:34
,07-27 08:57:16.086  6846  6846 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-27 08:57:16.086  6846  6846 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
,07-27 08:57:16.096  6846  6879 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:16.096  6883  6883 E Zygote  : v2
07-27 08:57:16.096  6883  6883 I libpersona: KNOX_SDCARD checking this for 10044
07-27 08:57:16.096  6883  6883 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:16.106  6883  6883 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 08:57:16.106  6883  6883 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:16.106   753  1320 I ActivityManager: Start proc 6883:com.osp.app.signin/u0a44 for broadcast-5 com.osp.app.signin/.OspReceiver
,07-27 08:57:16.106  6883  6883 E Zygote  : accessInfo : 0
,07-27 08:57:16.106  6883  6883 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-27 08:57:16.106   753  1320 I ActivityManager: Killing 5945:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #37
,07-27 08:57:16.106   753  1320 I ActivityManager: Killing 5930:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): DHA:empty #37
07-27 08:57:16.116  6846  6879 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:57:16.116  6846  6880 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,07-27 08:57:16.116   753  1485 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:16.116  6846  6880 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:57:16.126   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{d14f09a: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:16.136  6883  6883 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:16.136  6883  6883 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:16.136  6846  6879 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,07-27 08:57:16.136  6846  6880 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:57:16.136   753  2013 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4558dcb 6883:com.osp.app.signin/u0a44}
,07-27 08:57:16.146  6846  6880 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,07-27 08:57:16.146  6846  6880 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,07-27 08:57:16.146  6846  6880 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
,07-27 08:57:16.146   753  1417 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,07-27 08:57:16.146  6846  6880 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
,07-27 08:57:16.146  6846  6880 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,07-27 08:57:16.156  6883  6883 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in com.osp.app.signin rsrc of package null
,07-27 08:57:16.156   753  2163 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,07-27 08:57:16.166  6846  6880 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:57:16.166  6846  6880 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
,07-27 08:57:16.186  6846  6880 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
,07-27 08:57:16.186  6846  6879 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
,07-27 08:57:16.186  6846  6879 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,07-27 08:57:16.186  6846  6879 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
,07-27 08:57:16.186  4114  6895 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-27 08:57:16.186  4114  6895 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-27 08:57:16.196  6846  6879 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,07-27 08:57:16.196  6846  6879 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,07-27 08:57:16.196  6846  6879 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,07-27 08:57:16.206  6846  6879 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
,07-27 08:57:16.206  6846  6879 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(235/lllIlIlIIIllIIlIllIl)] Start resumecase for INIT
,07-27 08:57:16.206   753  2167 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:16.206  6846  6879 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:57:16.206  1999  6775 I qtaguid : Tagging socket 58 with tag 1000120300000000{268440067,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:16.216  6896  6896 E Zygote  : v2
07-27 08:57:16.216  6896  6896 I libpersona: KNOX_SDCARD checking this for 10116
07-27 08:57:16.216  6896  6896 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:16.216  6896  6896 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:16.216  6896  6896 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:16.216   753   827 I ActivityManager: Start proc 6896:com.google.android.talk/u0a116 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
07-27 08:57:16.216  6896  6896 E Zygote  : accessInfo : 0
,07-27 08:57:16.216  6896  6896 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-27 08:57:16.216   753  1323 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:57:16.216  6883  6883 W System  : ClassLoader referenced unknown path: /system/priv-app/Samsungservice2_xxhdpi/lib/arm
,07-27 08:57:16.226  6846  6880 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,07-27 08:57:16.226   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{7c17c66: PendingIntentRecord{2b55cc1 com.google.android.gms broadcastIntent}}
,07-27 08:57:16.236  6896  6896 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:16.236  6896  6896 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:16.246  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:57:16.246  6359  6430 I jxcore-log: 
,07-27 08:57:16.246   753  1485 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e2d3ba7 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b997854 6896:com.google.android.talk/u0a116}
,07-27 08:57:16.246   753  1323 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,07-27 08:57:16.246   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{7fa03fd: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:16.256   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{558f8f2: PendingIntentRecord{59561f1 com.android.bluetooth broadcastIntent}}
,07-27 08:57:16.266  6896  6896 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:57:16.266  6846  6879 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:57:16.276  6846  6879 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:16.286  6883  6883 I SA      : [SSP] onCreated
,07-27 08:57:16.296  6883  6883 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@9e1debd
,07-27 08:57:16.296  6896  6896 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-27 08:57:16.316  6883  6883 I SA      : [TPM] There is no property file
,07-27 08:57:16.316  6883  6883 I SA      : [SCU] isHaveSA() - false
,07-27 08:57:16.326  6883  6883 I SA      : [TPM] getModelProperty : null
07-27 08:57:16.326  6883  6883 I SA      : [TPM] getCSCProperty : null
,07-27 08:57:16.326  6883  6883 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-27 08:57:16.326  6883  6883 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-27 08:57:16.326  6883  6883 I SA      : [DM] TFT FEATURE: false
,07-27 08:57:16.326  6883  6883 I SA      : [DM] init START
,07-27 08:57:16.326  6883  6883 I SA      : [DM] This device is not a Vodafone
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:16.336  6883  6883 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,07-27 08:57:16.336  6883  6883 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,07-27 08:57:16.346  6883  6883 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,07-27 08:57:16.346  6883  6883 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,07-27 08:57:16.346  6883  6883 I SA      : [SCU] isHaveSA() - false
07-27 08:57:16.346  6883  6883 I SA      : support phone number id : false
07-27 08:57:16.346  6883  6883 I SA      : [DM] Supports Ref Jpn : true
,07-27 08:57:16.346  6883  6883 I SA      : [DM] init END
,07-27 08:57:16.346  6883  6883 I SA      : [OR] onReceive log=[SA = 2.1.0300 V = 23 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = MMB29M M = SM-G900F OKLEFT false DIS MMB29M.G900FXXU1CPEM PSS = 5.219788042639568  ]
,07-27 08:57:16.356  6883  6883 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-27 08:57:16.356  6883  6883 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 08:57:16.356  6883  6883 I SA      : [SLFUCHKMGR] constructor called
,07-27 08:57:16.376  6883  6883 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-27 08:57:16.376  6883  6883 I SA      : [OR] == isSIMCardReady false ==
,07-27 08:57:16.376  6883  6883 I SA      : [SCU] == networkStateCheck == true
,07-27 08:57:16.376  6883  6883 I SA      : [DM] getCountryCodeFromCSC : PL
07-27 08:57:16.376  6883  6883 I SA      : isChinaCountryCode : false
,07-27 08:57:16.376  6883  6883 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-27 08:57:16.376  6883  6883 I SA      : [OR] == networkStateCheck true ==
,07-27 08:57:16.396  6883  6883 I SA      : [OR] GetMyCountryZoneTask
,07-27 08:57:16.396  6883  6883 I SA      : [OR] onReceive END
,07-27 08:57:16.396  6896  6896 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:57:16.406  6914  6914 E Zygote  : v2
,07-27 08:57:16.406  6914  6914 I libpersona: KNOX_SDCARD checking this for 10002
07-27 08:57:16.406  6914  6914 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:16.406  6914  6914 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 08:57:16.406  6914  6914 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:16.416   753  1320 I ActivityManager: Start proc 6914:com.sec.android.cloudagent/u0a2 for broadcast-5 com.sec.android.cloudagent/.detector.DetectorReceiver
07-27 08:57:16.416  6914  6914 E Zygote  : accessInfo : 0
07-27 08:57:16.416  6914  6914 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.cloudagent 
,07-27 08:57:16.416  6883  6913 I SA      : [SRS_HTTPURLCONNECTION] prepareGetMyCountryZone
,07-27 08:57:16.426  6883  6913 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-27 08:57:16.426  6883  6913 I SA      : [SSP] query invoked
,07-27 08:57:16.446  6914  6914 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:16.446  6914  6914 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:16.456  6883  6913 I SA      : [TPMU] GetMccFromDB : null
,07-27 08:57:16.466  6846  6880 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:57:16.466   753   769 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe7eb43 6914:com.sec.android.cloudagent/u0a2}
,07-27 08:57:16.466  6883  6913 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 08:57:16.466  6883  6913 I SA      : [LBE] isSupportCheckDomainRegion : true
,07-27 08:57:16.476  6883  6913 I SA      : [TPM] isNoProxy(default) : true
,07-27 08:57:16.476  6914  6914 W ResourcesManager: getTopLevelResources: /system/priv-app/CloudAgent/CloudAgent.apk / 1.0 running in com.sec.android.cloudagent rsrc of package null
,07-27 08:57:16.496  6846  6880 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,07-27 08:57:16.496  6914  6914 W System  : ClassLoader referenced unknown path: /system/priv-app/CloudAgent/lib/arm
,07-27 08:57:16.506  6883  6913 E File    : fail readDirectory() errno=2
,07-27 08:57:16.576   753   769 I ActivityManager: Start proc 6930:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
,07-27 08:57:16.576  6930  6930 E Zygote  : v2
07-27 08:57:16.576  6930  6930 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:16.576  6930  6930 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:16.576  6930  6930 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:16.576  6930  6930 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:16.576  6930  6930 E Zygote  : accessInfo : 0
,07-27 08:57:16.586   753   764 I art     : Background partial concurrent mark sweep GC freed 96871(5MB) AllocSpace objects, 13(260KB) LOS objects, 27% free, 41MB/57MB, paused 4.649ms total 143.311ms
,07-27 08:57:16.596   753   769 I ActivityManager: Killing 5036:com.android.mms/u0a49 (adj 15): DHA:empty #37
,07-27 08:57:16.606  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:16.606  6930  6930 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:16.616   753  1320 D CountryDetector: No listener is left
,07-27 08:57:16.616   753  1623 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,07-27 08:57:16.626   753  2013 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{83fc5c0 6930:com.wssyncmldm/1000}
,07-27 08:57:16.636  6930  6930 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,07-27 08:57:16.656  6930  6930 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
,07-27 08:57:16.666  6896  6942 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:57:16.666  6896  6942 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:57:16.686  6896  6896 I Babel_telephony: TeleModule.onApplicationCreate
,07-27 08:57:16.686  6930  6930 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,07-27 08:57:16.716  6896  6950 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-27 08:57:16.716  6896  6950 I Babel_SMS: MmsConfig.loadMmsSettings
,07-27 08:57:16.726  6896  6950 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-27 08:57:16.726  6896  6950 I Babel_SMS: MmsConfig.loadFromDatabase
,07-27 08:57:16.756  6930  6930 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-27 08:57:16.776  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:57:16.776  6359  6430 I jxcore-log: 
07-27 08:57:16.776  6896  6896 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:57:16.776  6896  6950 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-27 08:57:16.776  6896  6950 I Babel_SMS: MmsConfig.loadFromResources
,07-27 08:57:16.776  6896  6896 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:57:16.786  6896  6950 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 08:57:16.786  6896  6950 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,07-27 08:57:16.796  6896  6896 I Babel_Crash: Startup - clean
,07-27 08:57:16.806  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:57:16.806  6359  6430 I jxcore-log: 
,07-27 08:57:16.806  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:57:16.806  6359  6430 I jxcore-log: 
,07-27 08:57:16.816   753  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10116
,07-27 08:57:16.816   753  1417 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10116
,07-27 08:57:16.816   753   769 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10116
,07-27 08:57:16.816   753  2163 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10116
,07-27 08:57:16.826   753  1485 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10116
,07-27 08:57:16.826  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:57:16.826  6359  6430 I jxcore-log: 
,07-27 08:57:16.826  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:57:16.826  6359  6430 I jxcore-log: 
,07-27 08:57:16.846  6930  6930 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,07-27 08:57:16.846  6930  6930 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,07-27 08:57:16.846  6930  6930 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,07-27 08:57:16.866  6930  6930 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-27 08:57:16.876  6930  6930 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-27 08:57:16.886  6930  6930 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,07-27 08:57:16.896  6896  6896 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,07-27 08:57:16.906  6896  6896 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:57:16.916   753  1650 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{829d993 3584:com.sec.spp.push/u0a37}
,07-27 08:57:16.926  3584  3584 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-27 08:57:16.926  3584  3584 E SPPClientService: [SystemStateMoniter] Current Time : 276591
,07-27 08:57:16.926   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{4adf831: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:16.926  6930  6961 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:16.936  3584  3584 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-27 08:57:16.946   753  2163 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3934768 2675:android.process.media/u0a46}
,07-27 08:57:16.956  2675  2675 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:16.976   753  1623 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,07-27 08:57:16.986   753  1485 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a15a96b 3063:com.android.contacts/u0a19}
,07-27 08:57:16.996  6896  6896 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:57:17.016  6963  6963 E Zygote  : v2
07-27 08:57:17.016  6963  6963 I libpersona: KNOX_SDCARD checking this for 10199
07-27 08:57:17.016  6963  6963 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:17.016  6963  6963 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:17.016  6963  6963 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:17.016  6963  6963 E Zygote  : accessInfo : 0
07-27 08:57:17.016  6963  6963 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,07-27 08:57:17.016   753  1677 I ActivityManager: Start proc 6963:com.google.android.apps.photos/u0a199 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-27 08:57:17.026  6896  6896 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-27 08:57:17.026  6896  6896 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:57:17.046  6896  6896 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:57:17.046  6963  6963 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:17.046  6963  6963 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:17.056   753  1898 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8359e84 6963:com.google.android.apps.photos/u0a199}
,07-27 08:57:17.056  6963  6963 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package null
,07-27 08:57:17.076  1999  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:17.076  6963  6963 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-27 08:57:17.076  1999  6775 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:17.076  1999  6775 I qtaguid : Tagging socket 53 with tag 1000120300000000{268440067,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:17.086   753  1747 I ActivityManager: Killing 5964:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #37
,07-27 08:57:17.096  6896  6896 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:57:17.096   753  1623 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,07-27 08:57:17.116   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{772478f: PendingIntentRecord{5103a1c com.google.android.talk startService}}
,07-27 08:57:17.146  6896  6976 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,07-27 08:57:17.146   753  2167 I ActivityManager: Killing 5976:com.google.android.apps.docs/u0a97 (adj 15): DHA:empty #37
,07-27 08:57:17.156   753  3282 D SSRM:n  : SIOP:: AP = 400, PST = 314, CUR = 450, LCD = 0
,07-27 08:57:17.176   753   768 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,07-27 08:57:17.196  6977  6977 E Zygote  : v2
07-27 08:57:17.196  6977  6977 I libpersona: KNOX_SDCARD checking this for 10011
07-27 08:57:17.196  6977  6977 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:17.196  6977  6977 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:17.196  6977  6977 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:17.196  6977  6977 E Zygote  : accessInfo : 0
07-27 08:57:17.196  6977  6977 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,07-27 08:57:17.206   753  1677 I ActivityManager: Start proc 6977:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,07-27 08:57:17.226  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:17.226  6977  6977 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:17.236  6977  6977 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,07-27 08:57:17.266  6977  6977 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:57:17.266  6977  6977 I MultiDex: install
07-27 08:57:17.266  6977  6977 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:17.286  1999  6775 I qtaguid : Untagging socket 53
,07-27 08:57:17.296  6977  6977 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:57:17.306  6977  6977 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-27 08:57:17.306  6977  6977 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:57:17.306  6977  6977 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:57:17.336  6977  6977 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:57:17.366  6977  6977 D ChimeraCfgMgr: Reading stored module config
,07-27 08:57:17.436  6977  6991 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 08:57:17.446  1999  6775 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-27 08:57:17.466  1999  6775 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-27 08:57:17.486   318   958 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6977)
,07-27 08:57:17.516   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{412420 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 08:57:17.546   318   958 D WVCdm   : Instantiating CDM.
,07-27 08:57:17.556   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{464624c: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:17.556   318   972 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6977)
07-27 08:57:17.556   318   972 I WVCdm   : CdmEngine::OpenSession
07-27 08:57:17.556   318   972 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-27 08:57:17.566   318   972 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-27 08:57:17.566   318   972 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-27 08:57:17.566   318   972 D DrmWidevineDash: Service_Initialize: starts!
07-27 08:57:17.566   318   972 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-27 08:57:17.566   318   972 D QSEECOMAPI: : App is not loaded in QSEE
07-27 08:57:17.566   318   972 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-27 08:57:17.566   318   972 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-27 08:57:17.566   318   972 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-27 08:57:17.566   318   972 D QSEECOMAPI: : App is not loaded in QSEE
07-27 08:57:17.566   318   972 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
07-27 08:57:17.566   318   972 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-27 08:57:17.566   318   972 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-27 08:57:17.566   318   972 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 08:57:17.606  6977  6988 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:17.606  6977  6988 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:17.616   306  1182 D EnterpriseController: netId is 0
07-27 08:57:17.616   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-27 08:57:17.616   318   972 D QSEECOMAPI: : Loaded image: APP id = 2
,07-27 08:57:17.616   318   972 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-27 08:57:17.616   318   972 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef1f000
07-27 08:57:17.616   318   972 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef1f000
,07-27 08:57:17.616  6977  6988 I qtaguid : Tagging socket 23 with tag 1000180300000000{268441603,0} uid -1, pid: 6977, getuid(): 10011
,07-27 08:57:17.636   318   972 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-27 08:57:17.636   318   972 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-27 08:57:17.636   318   972 D DrmWidevineDash: hlos api version =  10
07-27 08:57:17.636   318   972 D DrmWidevineDash: tz api version =  10
07-27 08:57:17.636   318   972 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-27 08:57:17.636   318   972 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-27 08:57:17.666   318   972 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-27 08:57:17.666   318   972 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,07-27 08:57:17.666   318   972 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaedbe924
,07-27 08:57:17.666   318   972 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-27 08:57:17.666   318   972 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-27 08:57:17.666   318   972 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e1dfd8, dataLength=8
,07-27 08:57:17.676   318   972 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-27 08:57:17.676   753  3282 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:17.696  6963  6963 W Primes  : Memory instrumentations are turned off.
,07-27 08:57:17.696   318   972 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xad554400, wrapped_rsa_key_length=1280
,07-27 08:57:17.696  6963  6963 W Primes  : Timer instrumentations are turned off.
,07-27 08:57:17.696   318   972 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-27 08:57:17.696   318   972 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 08:57:17.706   318   318 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:57:17.706   318   318 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-27 08:57:17.706   318   318 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xad5623c0, idLength=0xbeab8cbc
,07-27 08:57:17.706  6963  6963 W Primes  : Crash monitoring is turned off.
,07-27 08:57:17.706  6963  6963 W Primes  : Network monitoring is turned off.
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-27 08:57:17.706  6963  6963 W Primes  : Package metrics are turned off by default
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-27 08:57:17.706   318   318 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-27 08:57:17.716   318   318 D DrmWidevineDash: hlos api version =  10
07-27 08:57:17.716   318   318 D DrmWidevineDash: tz api version =  10
07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-27 08:57:17.716   318   318 D WVCdm   : PrepareKeyRequest: nonce=2280089858
,07-27 08:57:17.716   318   318 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d85800
07-27 08:57:17.716   318   318 D DrmWidevineDash: message_length=1631, signature=0xad559180, signature_length=3198913940
,07-27 08:57:17.736   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{39b5738 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8359e84 6963:com.google.android.apps.photos/u0a199}
,07-27 08:57:17.736   753  2167 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8359e84 6963:com.google.android.apps.photos/u0a199}
,07-27 08:57:17.766   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{27a8c76 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8359e84 6963:com.google.android.apps.photos/u0a199}
,07-27 08:57:17.776  7009  7009 E Zygote  : v2
07-27 08:57:17.776  7009  7009 I libpersona: KNOX_SDCARD checking this for 10127
07-27 08:57:17.776  7009  7009 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:17.776   753  1485 I ActivityManager: Start proc 7009:com.google.android.apps.magazines/u0a127 for broadcast-5 com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
07-27 08:57:17.776  7009  7009 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:17.776  7009  7009 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:17.776  7009  7009 E Zygote  : accessInfo : 0
07-27 08:57:17.776  7009  7009 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.magazines 
,07-27 08:57:17.796   318   318 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-27 08:57:17.796   318   958 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6977)
,07-27 08:57:17.796   318   958 I WVCdm   : CdmEngine::CloseSession
07-27 08:57:17.796   318   958 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-27 08:57:17.796   318   958 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-27 08:57:17.796   318   958 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-27 08:57:17.796   318   958 D DrmWidevineDash: Service_Uninitialize: starts!
07-27 08:57:17.796   318   958 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-27 08:57:17.796   318   958 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,07-27 08:57:17.796   318   958 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-27 08:57:17.796   318   958 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-27 08:57:17.816  7009  7009 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:17.816  7009  7009 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:17.826   753  1747 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{afafa02 7009:com.google.android.apps.magazines/u0a127}
,07-27 08:57:17.846   753  1650 I ActivityManager: Killing 6010:com.sec.android.automotive.drivelink/u0a98 (adj 15): DHA:empty #37
,07-27 08:57:17.846  7009  7009 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,07-27 08:57:17.886   753  1789 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.automotive.drivelink, Auto Run ON
,07-27 08:57:17.886  6883  6913 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-27 08:57:17.906  7009  7009 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-27 08:57:17.916  6883  6913 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-27 08:57:17.916  6883  6913 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:17.916  6883  6913 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:17.916   306  1182 D EnterpriseController: netId is 0
07-27 08:57:17.916   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10044
,07-27 08:57:17.946  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:57:17.966  7009  7009 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:57:17.966  7009  7009 I MultiDex: install
07-27 08:57:17.966  7009  7009 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:18.006  6464  6464 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,07-27 08:57:18.016   306  1179 D Netd    : Iface wlan0 link up
,07-27 08:57:18.016   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
,07-27 08:57:18.016   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:18.016   753  1324 D WifiP2pService: InactiveState{ what=147461 }
07-27 08:57:18.016   753  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-27 08:57:18.016   753  1324 D WifiP2pService: DefaultState{ what=147461 }
,07-27 08:57:18.036   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4953f13 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:57:18.036  6977  6988 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6977, getuid(): 10011
,07-27 08:57:18.096  7009  7009 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-27 08:57:18.096  7009  7009 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:57:18.096  7009  7009 I GAv4    :   adb logcat -s GAv4
,07-27 08:57:18.116  7009  7009 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,07-27 08:57:18.116   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{aeaf67c: PendingIntentRecord{d0ceb05 com.google.android.apps.magazines broadcastIntent}}
,07-27 08:57:18.116  7009  7009 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:18.116  7009  7009 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:18.126  7009  7033 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:18.196  6977  6988 I qtaguid : Untagging socket 23
,07-27 08:57:18.226  6977  6988 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
07-27 08:57:18.226  6977  6988 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:57:18.296  7009  7009 I NSApplication: Starting up...
,07-27 08:57:18.306   753  1485 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf95a82 5483:com.google.android.apps.plus/u0a134}
,07-27 08:57:18.346   753  1320 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f1482d 6652:com.android.email/u0a162}
,07-27 08:57:18.366   753  1789 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:18.376  1999  2396 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:57:18.406   753   768 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:18.406   753  2013 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:18.406   753  1320 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0b0375 6493:tv.peel.smartremote/u0a170}
,07-27 08:57:18.446  7061  7061 E Zygote  : v2
07-27 08:57:18.446  7061  7061 I libpersona: KNOX_SDCARD checking this for 10177
07-27 08:57:18.446  7061  7061 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:18.446  7061  7061 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 08:57:18.446  7061  7061 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:18.446  7061  7061 E Zygote  : accessInfo : 0
,07-27 08:57:18.446  7061  7061 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.samsung.android.service.travel 
,07-27 08:57:18.456   753  1485 I ActivityManager: Start proc 7061:com.samsung.android.service.travel/u0a177 for broadcast-5 com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver
,07-27 08:57:18.476  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:18.476  7061  7061 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:18.486  6493  6524 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,07-27 08:57:18.486   753  1623 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a87a162 7061:com.samsung.android.service.travel/u0a177}
,07-27 08:57:18.496  6493  6524 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:57:18.506  7061  7061 W ResourcesManager: getTopLevelResources: /system/app/TravelService_K/TravelService_K.apk / 1.0 running in com.samsung.android.service.travel rsrc of package null
,07-27 08:57:18.516  6493  6524 I System.out: Thread-888(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 08:57:18.516  6493  6524 I System.out: Thread-888(ApacheHTTPLog):isSBSettingEnabled false
07-27 08:57:18.516  6493  6524 I System.out: Thread-888(ApacheHTTPLog):isShipBuild true
07-27 08:57:18.516  6493  6524 I System.out: Thread-888(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 08:57:18.516  6493  6524 I System.out: Thread-888(ApacheHTTPLog):Smart Bonding Setting is false
07-27 08:57:18.516  6493  6524 I System.out: Thread-888(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:57:18.516   306  1182 D EnterpriseController: netId is 0
07-27 08:57:18.516   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10170
,07-27 08:57:18.526  7061  7061 W System  : ClassLoader referenced unknown path: /system/app/TravelService_K/lib/arm
,07-27 08:57:18.526   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{2b7c2f3: PendingIntentRecord{963bb0 com.samsung.android.service.travel broadcastIntent}}
,07-27 08:57:18.536   753  2163 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d82ebf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a5f758 6127:com.sec.android.app.samsungapps/u0a39}
,07-27 08:57:18.556  6127  6127 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-27 08:57:18.626  7073  7073 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-27 08:57:18.696   753  3282 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:18.756  6883  6913 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 840
,07-27 08:57:18.766  6883  6913 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,07-27 08:57:18.766  7073  7073 I dex2oat : ----------------------------------------------------
07-27 08:57:18.766  7073  7073 I dex2oat : <SS>: S T A R T I N G . . .
07-27 08:57:18.766  7073  7073 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,07-27 08:57:18.766  7073  7073 I dex2oat : dex2oat took 139.950ms (threads: 4) arena alloc=208KB java alloc=63KB native alloc=1798KB free=1529KB
,07-27 08:57:18.776  6977  6988 W System  : ClassLoader referenced unknown path: 
,07-27 08:57:18.776  6977  6988 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,07-27 08:57:18.786  6977  6988 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:57:18.786  6977  6988 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:57:18.786  6977  6988 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:57:18.786  6977  6988 I Adreno-EGL: Local Branch: ss
07-27 08:57:18.786  6977  6988 I Adreno-EGL: Remote Branch: 
07-27 08:57:18.786  6977  6988 I Adreno-EGL: Local Patches: 
07-27 08:57:18.786  6977  6988 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:57:18.786  6883  6913 I SA      : [OCP] update openData : PL
,07-27 08:57:18.786  6127  6127 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-27 08:57:18.786  6977  6988 D libEGL  : eglInitialize EGLDisplay = 0xb2eda264
,07-27 08:57:18.786  6883  6913 I SA      : [TPMU] getNetworkMcc : 
,07-27 08:57:18.786  6127  6127 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: exit::IDLE
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-27 08:57:18.786   753  1417 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:18.786   753   768 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-27 08:57:18.786  6127  6127 D InitializeManagerStateMachine: entry::SUCCESS
07-27 08:57:18.786  6127  6127 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-27 08:57:18.796  6883  6913 I SA      : [SCU] saveMccToPreferece Start
07-27 08:57:18.796  6883  6913 I SA      : [SCU] RegionMCC : 260
07-27 08:57:18.796  6883  6913 I SA      : [SSP] query invoked
,07-27 08:57:18.796  6127  6127 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-27 08:57:18.806  6127  6127 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-27 08:57:18.806  6127  6127 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-27 08:57:18.806   753  1747 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:18.806  6127  6127 D InitializeManagerStateMachine: exit::SUCCESS
07-27 08:57:18.806  6127  6127 D InitializeManagerStateMachine: entry::IDLE
,07-27 08:57:18.806  6883  6913 I SA      : [TPMU] GetMccFromDB : null
07-27 08:57:18.806  6883  6913 I SA      : [SCU] getMccFromPreferece mcc = 260
07-27 08:57:18.806  6883  6913 I SA      : [SCU] saveMccToPreferece End
,07-27 08:57:18.806  6883  6913 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 914
07-27 08:57:18.806  6883  6913 I SA_HTTPURLCONNECTION: [RC New] Execute end
,07-27 08:57:18.806  6883  6883 I SA      : [OR] GetMyCountryZoneTask mcc = 260
07-27 08:57:18.806  6883  6883 I SA      : [OR] GetMyCountryZoneTask Success
,07-27 08:57:18.806   753  1650 I ActivityManager: Killing 6030:com.vlingo.midas/u0a32 (adj 15): DHA:empty #37
,07-27 08:57:18.826   753  1677 D ActivityManager: isAutoRunBlockedApp:: com.vlingo.midas, Auto Run ON
,07-27 08:57:18.846  6977  6988 D libEGL  : eglTerminate EGLDisplay = 0xb2eda2bc
,07-27 08:57:18.886  6977  6988 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:57:18.886  6977  6988 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:57:18.886  6977  6988 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:57:18.886  6977  6988 I Adreno-EGL: Local Branch: ss
07-27 08:57:18.886  6977  6988 I Adreno-EGL: Remote Branch: 
07-27 08:57:18.886  6977  6988 I Adreno-EGL: Local Patches: 
07-27 08:57:18.886  6977  6988 I Adreno-EGL: Reconstruct Branch: 
07-27 08:57:18.886  6977  6988 D libEGL  : eglInitialize EGLDisplay = 0xb2eda264
,07-27 08:57:18.896  1378  1378 D ViewRootImpl: #3 mView = null
,07-27 08:57:18.896   294   328 I SurfaceFlinger: id=22 Removed Uoast (8/9)
,07-27 08:57:18.896   294  1299 I SurfaceFlinger: id=22 Removed Uoast (-2/9)
,07-27 08:57:18.906   753   768 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 753) eventTime = 278580
,07-27 08:57:18.906   753   768 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=753 (0x0)
,07-27 08:57:18.906   753   768 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=753, ws=WorkSource{10058}) (elapsedTime=3467)
,07-27 08:57:18.906   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8b23a4
,07-27 08:57:18.936  6977  6988 D libEGL  : eglTerminate EGLDisplay = 0xb2eda2bc
,07-27 08:57:18.936  6977  6988 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 08:57:18.936  6977  6988 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 08:57:18.936  6977  6988 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 08:57:18.936  6977  6988 I Adreno-EGL: Local Branch: ss
07-27 08:57:18.936  6977  6988 I Adreno-EGL: Remote Branch: 
07-27 08:57:18.936  6977  6988 I Adreno-EGL: Local Patches: 
07-27 08:57:18.936  6977  6988 I Adreno-EGL: Reconstruct Branch: 
07-27 08:57:18.936  6977  6988 D libEGL  : eglInitialize EGLDisplay = 0xb2eda264
,07-27 08:57:18.976  6977  6988 D libEGL  : eglTerminate EGLDisplay = 0xb2eda2bc
,07-27 08:57:19.146  6493  6524 I System.out: tr calls detatch()
,07-27 08:57:19.206  1999  6975 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:19.206  1999  6975 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:19.206   306  1182 D EnterpriseController: netId is 0
07-27 08:57:19.206   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-27 08:57:19.216  1999  6975 I qtaguid : Tagging socket 43 with tag 1000040100000000{268436481,0} uid 10011, pid: 1999, getuid(): 10011
,07-27 08:57:19.236  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:57:19.236  6359  6430 I jxcore-log: 
,07-27 08:57:19.246  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:57:19.246  6359  6430 I jxcore-log: 
,07-27 08:57:19.246  1999  6975 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} uid 10011, pid: 1999, getuid(): 10011
,07-27 08:57:19.246  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:57:19.246  6359  6430 I jxcore-log: 
,07-27 08:57:19.386   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{a019b4f: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:19.406  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:57:19.406  6359  6430 I jxcore-log: 
,07-27 08:57:19.476   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{dc7faba: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:19.506   753  1650 I ActivityManager: Killing 6044:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #37
,07-27 08:57:19.516   753  2167 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,07-27 08:57:19.606  1999  7093 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:57:19.606  1999  7089 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:57:19.616  1999  7093 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:57:19.616  1999  7089 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:57:19.636  1999  7093 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:57:19.636  1999  7089 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:57:19.636  1999  7089 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-27 08:57:19.636  1999  7089 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:19.686   753  1650 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:19.726  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:19.726  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:19.726  1999  7089 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10011, pid: 1999, getuid(): 10011
,07-27 08:57:19.766  1999  7089 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} uid 10011, pid: 1999, getuid(): 10011
,07-27 08:57:20.046  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:20.046  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.046   306  1182 D EnterpriseController: netId is 0
07-27 08:57:20.046   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-27 08:57:20.076  1999  7089 I qtaguid : Tagging socket 73 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:20.106  1999  7089 I qtaguid : Tagging socket 76 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:20.206   753  3301 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 08:57:20.216   753  3301 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,07-27 08:57:20.216   753  3301 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,07-27 08:57:20.216   753  3301 I System.out: Thread-174(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 08:57:20.216   753  3301 I System.out: Thread-174(ApacheHTTPLog):isSBSettingEnabled false
07-27 08:57:20.216   753  3301 I System.out: Thread-174(ApacheHTTPLog):isShipBuild true
07-27 08:57:20.216   753  3301 I System.out: Thread-174(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 08:57:20.216   753  3301 I System.out: Thread-174(ApacheHTTPLog):Smart Bonding Setting is false
,07-27 08:57:20.216   753  3301 I System.out: Thread-174(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:57:20.216   306  1182 D EnterpriseController: netId is 0
07-27 08:57:20.216   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:57:20.296  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:57:20.296  6359  6430 I jxcore-log: 
,07-27 08:57:20.356  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:57:20.356  6359  6430 I jxcore-log: 
,07-27 08:57:20.366  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:57:20.366  6359  6430 I jxcore-log: 
,07-27 08:57:20.406   753  1320 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:20.406  1999  7089 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-27 08:57:20.416  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:20.416  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.416  1999  7089 I qtaguid : Tagging socket 73 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:20.466   753  3301 I System.out: Category Thread calls detatch()
,07-27 08:57:20.506   753  1623 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:20.516  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:20.516  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.516  1999  7089 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:20.576  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:57:20.576  6359  6430 I jxcore-log: 
,07-27 08:57:20.596  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:57:20.596  6359  6430 I jxcore-log: 
,07-27 08:57:20.596  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:57:20.596  6359  6430 I jxcore-log: 
,07-27 08:57:20.606  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:57:20.606  6359  6430 I jxcore-log: 
,07-27 08:57:20.616  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:57:20.616  6359  6430 I jxcore-log: 
,07-27 08:57:20.626   753   768 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:20.636  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:20.636  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.636  1999  7089 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:20.636  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:57:20.636  6359  6430 I jxcore-log: 
,07-27 08:57:20.726  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:57:20.726  6359  6430 I jxcore-log: 
,07-27 08:57:20.736  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:57:20.736  6359  6430 I jxcore-log: 
,07-27 08:57:20.756   753  1485 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:20.756  6359  6430 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:57:20.756  6359  6430 I jxcore-log: 
,07-27 08:57:20.766  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.766  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:20.766  1999  7089 I qtaguid : Tagging socket 73 with tag 11065c9100000000{285629585,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:20.766  6359  6430 D BluetoothAdapter: STATE_ON
,07-27 08:57:20.776  6359  6430 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 08:57:20.776  6359  6430 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 08:57:20.776  6359  6430 I jxcore-log: 
,07-27 08:57:20.826  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 08:57:20.826  6359  6430 I jxcore-log: 
,07-27 08:57:20.826  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:57:20.826  6359  6430 I jxcore-log: 
,07-27 08:57:20.826  6359  6430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:57:20.826  6359  6430 I jxcore-log: 
,07-27 08:57:20.866   753  1485 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:20.876  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.876  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:20.886  1999  7089 I qtaguid : Tagging socket 73 with tag fffffca200000000{4294966434,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:21.006   753  1623 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:21.016  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:21.016  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:21.016  1999  7089 I qtaguid : Tagging socket 73 with tag 11065b5800000000{285629272,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:21.116   753   768 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:21.126  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:21.126  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:21.126  1999  7089 I qtaguid : Tagging socket 73 with tag 1106541400000000{285627412,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:21.256   753  1485 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:21.256  1999  7089 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-27 08:57:21.256  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:21.266  1999  7089 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:21.266  1999  7089 I qtaguid : Tagging socket 73 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:21.406   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{672d4b: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 08:57:21.955  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:57:22.185   753  1332 D ConnectivityService: handlePromptUnvalidated 502
,07-27 08:57:22.185  6896  6896 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,07-27 08:57:22.185   753  2167 I ActivityManager: Killing 6060:com.samsung.helphub/1000 (adj 15): DHA:empty #37
,07-27 08:57:22.225   753   769 D ActivityManager: isAutoRunBlockedApp:: com.samsung.helphub, Auto Run ON
,07-27 08:57:23.775   753  3282 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:24.235   753  1898 I ActivityManager: Killing 6073:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #37
,07-27 08:57:24.265   753   769 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,07-27 08:57:25.955  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 08:57:25.955  6666  6666 I dhcpcd  : wlan0: no IPv6 Routers available
,07-27 08:57:27.205   753  3282 D SSRM:n  : SIOP:: AP = 370, PST = 320, CUR = 450, LCD = 0
,07-27 08:57:28.835  6127  6127 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:57:28.845  6127  6127 D PreloadUpdateManagerStateMachine: exit::IDLE
,07-27 08:57:28.845  6127  6127 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:57:28.855  6127  6127 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-27 08:57:28.855  6127  6127 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-27 08:57:28.855  6127  6127 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-27 08:57:28.865  6127  6127 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:57:28.865  6127  6127 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-27 08:57:29.025   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:31.675  6896  6945 W Babel   : aye TOOK TOO LONG! (15002ms > 10000ms)
,07-27 08:57:31.725  6896  6896 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.google.android.talk rsrc of package null
,07-27 08:57:31.755  6896  6947 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,07-27 08:57:31.755   753  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10116
,07-27 08:57:31.775   753  2163 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:57:31.785  6896  6896 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-27 08:57:31.785  6896  6896 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:57:31.785  6896  6896 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:57:31.785  6896  6896 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-27 08:57:31.785   753  1320 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:57:31.865  6896  6956 W Babel   : aye TOOK TOO LONG! (15002ms > 10000ms)
,07-27 08:57:33.925   753  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:57:33.925   753  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:57:33.925   753  1623 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 08:57:33.935   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:33.945   753   753 I MotionRecognitionService: Plugged
,07-27 08:57:33.945   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 08:57:33.945   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:57:33.945   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:57:33.955   753  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 08:57:33.955   753  1623 D BatteryService: stay LED for fully charged
,07-27 08:57:33.965  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:33.965  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:57:33.965  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:34.005  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:34.005  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:34.005  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:34.015  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:34.015  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:57:37.275   753  3282 D SSRM:n  : SIOP:: AP = 330, PST = 323, CUR = 450, LCD = 0
,07-27 08:57:41.055   753  1574 E Watchdog: !@Sync 9 [07-27 08:57:41.067]
,07-27 08:57:42.965   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:57:42.965   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:57:42.965   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:57:47.165   753  1236 V AlarmManager: Expired Alarm result :4
,07-27 08:57:47.225   753  1647 V AlarmManager:  remove PendingIntent] PendingIntent{8afdf32: PendingIntentRecord{b8f7483 android broadcastIntent}}
,07-27 08:57:47.235  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:57:47.235  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 08:57:47.235  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:57:47.265  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:57:47.265  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:57:47.275  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.285  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.285  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.285  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.295  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.295  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.295  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.335  5512  5512 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
07-27 08:57:47.335  5512  5512 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:57:47.335  5512  5512 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:57:47.335   753  3282 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450, LCD = 0
,07-27 08:57:47.365  5512  5512 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-8
,07-27 08:57:47.365  5512  7154 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:57:47.375  5512  7154 V GCMBaseIntentService: Releasing wakelock
,07-27 08:57:47.385  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:47.395  1999  5340 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:57:47.405  1999  5340 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:47.405  1999  5340 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:47.405   306  1182 D EnterpriseController: netId is 0
07-27 08:57:47.405   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,07-27 08:57:47.415  1999  5340 I qtaguid : Tagging socket 39 with tag 1000040700000000{268436487,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:47.415   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:57:47.415   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:57:47.415   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:57:47.455  1999  5340 I qtaguid : Tagging socket 61 with tag 1000040700000000{268436487,0} uid -1, pid: 1999, getuid(): 10011
,07-27 08:57:47.765  1999  5340 I qtaguid : Untagging socket 39
,07-27 08:57:47.775   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{26f81ca u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39a77b6 5512:com.android.vending/u0a29}
,07-27 08:57:47.775  5512  5512 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
07-27 08:57:47.775  5512  5512 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:57:47.775  5512  5512 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:57:47.785  5512  5512 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-9
,07-27 08:57:47.795  5512  7167 D GCMBaseIntentService: handleRegistration: registrationId = APA91bEeG1-reDXY9oMfRln6xvHZgKBxUsVLk6u5o_6ZLsuNWcM6rOsC6OT-W6WzefAh3Wa7Av1MB-FeUuhpIWCi0Tp5cuulSFye-H2e3qR6Yr1kNKvKWAoEMH3cVdkhiyk63X3mOyJz, error = null, unregistered = null
07-27 08:57:47.795  5512  7167 D GCMRegistrar: resetting backoff for com.android.vending
,07-27 08:57:47.805  5512  7167 V GCMRegistrar: Saving regId on app version 80682400
,07-27 08:57:47.815  5512  7167 V GCMBaseIntentService: Releasing wakelock
,07-27 08:57:48.085  4114  7168 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:57:48.095   753   817 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 306833, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:57:48.095   753   817 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 372733, reason: UserStart
,07-27 08:57:48.125  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:48.125  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:48.125  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:48.125  3063  3078 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-27 08:57:48.125   753  2013 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:57:48.265   753   764 I art     : Background partial concurrent mark sweep GC freed 51971(3MB) AllocSpace objects, 44(1060KB) LOS objects, 27% free, 41MB/57MB, paused 1.467ms total 108.196ms
,07-27 08:57:49.025   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:55.875   753  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 08:57:55.885   753  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 08:57:55.885   753  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 08:57:55.895   753  1230 I TLC_TIMA_PKM_initialize: initializing...
,07-27 08:57:55.895   753  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-27 08:57:55.905   753  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-27 08:57:55.905   753  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-27 08:57:55.905   753  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-27 08:57:55.905   753  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-27 08:57:55.915   753  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-27 08:57:55.915   753  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-27 08:57:55.915   753  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-27 08:57:55.925   753  1230 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 08:57:55.965   753  1230 D QSEECOMAPI: : Loaded image: APP id = 2
,07-27 08:57:55.975   753  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-27 08:57:55.985   753  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-27 08:57:57.405   753  3282 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450, LCD = 0
,07-27 08:57:59.275   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 08:57:59.275   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 08:57:59.295   753  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:59.295   753  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:59.985   753  1236 V AlarmManager: Expired Alarm result :8
,07-27 08:58:02.885   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:02.885   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:02.885   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:03.985   753  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:03.985   753  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:58:03.995   753  1320 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 08:58:03.995   753  1320 D BatteryService: stay LED for fully charged
,07-27 08:58:03.995   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:04.005   753   753 I MotionRecognitionService: Plugged
,07-27 08:58:04.015   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 08:58:04.015   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:58:04.015   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:04.035  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:04.035  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:04.045  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:04.065  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:04.065  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:04.065  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:04.065  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:04.065  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:07.485   753  3282 D SSRM:n  : SIOP:: AP = 310, PST = 328, CUR = 450, LCD = 0
,07-27 08:58:09.035   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:11.065   753  1574 E Watchdog: !@Sync 10 [07-27 08:58:11.071]
,07-27 08:58:12.485  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:58:17.555   753  3282 D SSRM:n  : SIOP:: AP = 310, PST = 329, CUR = 450, LCD = 0
,07-27 08:58:19.185   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:19.185   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:19.185   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:27.625   753  3282 D SSRM:n  : SIOP:: AP = 310, PST = 330, CUR = 450, LCD = 0
,07-27 08:58:29.035   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:34.055   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:58:34.065   753  2167 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:58:34.065   753  2167 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 08:58:34.065   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:58:34.075   753   753 I MotionRecognitionService: Plugged
,07-27 08:58:34.085   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 08:58:34.085   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:58:34.085   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:34.095   753  2167 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-27 08:58:34.095   753  2167 D BatteryService: stay LED for fully charged
,07-27 08:58:34.095  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:34.095  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:58:34.095  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:34.115  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:34.115  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:34.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:34.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:34.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:37.685   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 330, CUR = 450, LCD = 0
,07-27 08:58:39.165   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:39.165   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:39.165   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:41.065   753  1574 E Watchdog: !@Sync 11 [07-27 08:58:41.075]
,07-27 08:58:44.655   753  1236 V AlarmManager: Expired Alarm result :4
,07-27 08:58:44.675  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 08:58:44.675  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 08:58:44.675  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:58:44.735  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:58:44.745  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:58:44.765  6464  6464 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 08:58:44.765  6464  6464 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-27 08:58:44.785  6464  6464 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:58:44.795  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.795  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.795  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.795  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.795  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.805  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.805  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:44.855  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:45.175  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 08:58:45.215  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:58:45.235  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:58:45.235  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:58:45.295  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 08:58:45.295  5512  5543 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:58:45.295  5512  5543 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:58:45.305   306  1182 D EnterpriseController: netId is 0
07-27 08:58:45.305   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-27 08:58:45.305   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:58:45.305   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:45.305   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:46.035  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,07-27 08:58:47.745   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 327, CUR = 450, LCD = 0
,07-27 08:58:48.575  6464  6464 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,07-27 08:58:48.575   306  1179 D Netd    : Iface wlan0 link up
,07-27 08:58:48.585  6464  6464 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-27 08:58:48.615   753  1324 D WifiP2pService: InactiveState{ what=147461 },
,07-27 08:58:48.625   753   851 D Tethering: interfaceLinkStateChanged wlan0, true
,07-27 08:58:48.625   753   851 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:58:48.625   753  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-27 08:58:48.635   753  1324 D WifiP2pService: DefaultState{ what=147461 }
,07-27 08:58:48.685   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61fab46 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{556e1a2 1378:com.android.systemui/u0a58}
,07-27 08:58:49.045   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:57.805   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 317, CUR = 450, LCD = 0
,07-27 08:58:59.985   753  1236 V AlarmManager: Expired Alarm result :8
,07-27 08:59:01.445   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 08:59:01.445   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:59:01.445   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:59:04.135   753  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:04.145   753  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:59:04.145   753  1747 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 08:59:04.145   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:04.155   753   753 I MotionRecognitionService: Plugged
,07-27 08:59:04.165   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 08:59:04.165   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:59:04.165   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:59:04.175   753  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-27 08:59:04.175   753  1747 D BatteryService: stay LED for fully charged
,07-27 08:59:04.195  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:04.195  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:04.195  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:04.215  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:04.215  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:59:04.215  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:04.215  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:04.215  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:07.865   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 310, CUR = 450, LCD = 0
,07-27 08:59:09.045   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:11.065   753  1574 E Watchdog: !@Sync 12 [07-27 08:59:11.080]
,07-27 08:59:12.585  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 08:59:17.925   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-27 08:59:27.985   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-27 08:59:29.055   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:34.215   753   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:34.225   753   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 08:59:34.225   753   769 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 08:59:34.225   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:59:34.245   753   753 I MotionRecognitionService: Plugged
,07-27 08:59:34.245   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 08:59:34.245   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 08:59:34.245   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:59:34.255   753   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-27 08:59:34.255   753   769 D BatteryService: stay LED for fully charged
,07-27 08:59:34.265  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:34.265  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:59:34.265  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:59:34.295  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:34.295  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:34.295  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:59:34.305  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:59:34.305  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:59:38.045   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,07-27 08:59:41.075   753  1574 E Watchdog: !@Sync 13 [07-27 08:59:41.085]
,07-27 08:59:48.105   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 08:59:49.055   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:58.165   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-27 09:00:04.305   753  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:04.305   753  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 09:00:04.305   753  1485 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:00:04.305   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:04.315   753   753 I MotionRecognitionService: Plugged
,07-27 09:00:04.315   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:00:04.315   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:00:04.315   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:00:04.315   753  1485 D BatteryService: stay LED for fully charged
,07-27 09:00:04.315  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:04.315  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:00:04.325  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:04.335  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:04.335  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:00:04.345  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:04.345  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:04.345  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:08.225   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:00:09.065   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:11.075   753  1574 E Watchdog: !@Sync 14 [07-27 09:00:11.089]
,07-27 09:00:12.605  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:00:12.735  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 113ms lastUpdatedAfter : 144587ms
,07-27 09:00:18.285   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:00:28.335   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,07-27 09:00:29.065   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:34.365   753  1789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:34.375   753  1789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:00:34.375   753  1789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:00:34.375   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:34.385   753   753 I MotionRecognitionService: Plugged,
,07-27 09:00:34.395   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:00:34.395   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:00:34.395   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:00:34.405   753  1789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-27 09:00:34.405   753  1789 D BatteryService: stay LED for fully charged
,07-27 09:00:34.415  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:34.415  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:34.415  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:34.445  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:34.445  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:34.445  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:34.455  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:00:34.455  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:00:38.405   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-27 09:00:41.085   753  1574 E Watchdog: !@Sync 15 [07-27 09:00:41.095]
,07-27 09:00:45.325  1999  3170 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:00:45.705   361   361 I bootchecker: bootchecker wake up!!
,07-27 09:00:48.465   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,07-27 09:00:49.065   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:58.515   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-27 09:01:04.445   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:08.575   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-27 09:01:09.075   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:11.085   753  1574 E Watchdog: !@Sync 16 [07-27 09:01:11.099]
,07-27 09:01:12.765  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:01:17.465   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:01:17.465   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:01:17.465   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:01:18.635   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-27 09:01:28.695   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-27 09:01:29.075   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:34.515   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:37.005   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:01:37.005   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:01:37.005   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:01:38.755   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:01:41.095   753  1574 E Watchdog: !@Sync 17 [07-27 09:01:41.104]
,07-27 09:01:48.085   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:01:48.085   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:01:48.085   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:01:48.815   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-27 09:01:49.085   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:58.875   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:02:03.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:02:03.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:03.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:04.595   753   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:04.605   753   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:02:04.605   753   768 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:02:04.605   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:02:04.615   753   753 I MotionRecognitionService: Plugged
,07-27 09:02:04.625   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:02:04.625   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:02:04.625   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:02:04.635   753   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:02:04.635   753   768 D BatteryService: stay LED for fully charged
,07-27 09:02:04.645  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:04.645  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:02:04.645  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:04.665  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:04.665  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:02:04.665  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:04.665  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:04.675  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:08.935   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:02:09.085   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:11.095   753  1574 E Watchdog: !@Sync 18 [07-27 09:02:11.109]
,07-27 09:02:12.785  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:02:17.295   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:02:17.295   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:17.295   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:18.995   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:02:29.045   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:02:29.085   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:34.665   753  1650 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:02:34.675   753  1650 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:02:34.675   753  1650 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:02:34.675   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:02:34.685   753   753 I MotionRecognitionService: Plugged
,07-27 09:02:34.695   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:02:34.695   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:02:34.695   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:02:34.705   753  1650 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:02:34.705   753  1650 D BatteryService: stay LED for fully charged
,07-27 09:02:34.715  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:34.715  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:34.715  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:34.745  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:34.745  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:34.745  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:34.755  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:34.755  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:02:38.085   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:02:38.085   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:38.085   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:39.095   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:02:41.105   753  1574 E Watchdog: !@Sync 19 [07-27 09:02:41.114]
,07-27 09:02:46.755   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:02:46.755   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:46.755   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:49.095   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:49.155   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:02:55.865   753  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:02:55.865   753  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:02:55.875   753  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:02:57.355   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:02:57.355   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:02:57.365   753  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:57.375   753  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:59.205   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:03:02.845   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:03:02.845   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:03:02.845   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:03:04.745   753  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:04.755   753  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:03:04.755   753  1485 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:03:04.755   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:04.765   753   753 I MotionRecognitionService: Plugged
,07-27 09:03:04.775   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:03:04.775   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:03:04.775   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:03:04.785   753  1485 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:03:04.785   753  1485 D BatteryService: stay LED for fully charged
,07-27 09:03:04.795  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:04.795  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:03:04.795  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:04.815  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:04.815  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:03:04.815  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:04.815  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:04.815  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:09.095   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:03:09.265   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:03:11.105   753  1574 E Watchdog: !@Sync 20 [07-27 09:03:11.118]
,07-27 09:03:12.815  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:03:12.945  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 115ms lastUpdatedAfter : 180209ms
,07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:13.995   753   817 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.005   753   817 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-27 09:03:14.015   753   817 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:03:14.025   753   817 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:03:14.175   753   891 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-27 09:03:14.175   753   891 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-27 09:03:19.315   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:03:29.105   753  3314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:03:29.375   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:03:34.825   753  1898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:34.835   753  1898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:03:34.835   753  1898 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:03:34.835   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:03:34.855   753   753 I MotionRecognitionService: Plugged
,07-27 09:03:34.855   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:03:34.855   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:03:34.855   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:03:34.865   753  1898 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:03:34.865   753  1898 D BatteryService: stay LED for fully charged
,07-27 09:03:34.885  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:34.885  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:03:34.885  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:34.915  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:03:34.915  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:03:34.915  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:34.915  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:34.915  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:39.435   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:03:41.115   753  1574 E Watchdog: !@Sync 21 [07-27 09:03:41.124]
,07-27 09:03:45.175   753  1236 V AlarmManager: Expired Alarm result :8
,07-27 09:03:46.055   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:03:46.055   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:03:46.055   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:03:46.075   753  2163 I ActivityManager: Killing 4441:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 615s, lastActivityTime 615s
,07-27 09:03:46.085   753  2163 I ActivityManager: Killing 3675:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 620s
,07-27 09:03:46.145   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-27 09:03:46.145   370  4904 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-27 09:03:46.155   370  4904 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:03:46.155   753  1898 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-27 09:03:46.155   753  1898 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-27 09:03:46.155   753  1898 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-27 09:03:46.185   753  2013 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-27 09:03:46.185   753  2013 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-27 09:03:46.185   753  2013 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10973ms
,07-27 09:03:47.155   370  4904 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:03:47.245   753   827 I ActivityManager: Start proc 7200:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-27 09:03:47.245  7200  7200 E Zygote  : v2
,07-27 09:03:47.255  7200  7200 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:03:47.255  7200  7200 I libpersona: KNOX_SDCARD not a persona
,07-27 09:03:47.255  7200  7200 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:03:47.255  7200  7200 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:03:47.255  7200  7200 E Zygote  : accessInfo : 0
,07-27 09:03:47.305  7200  7200 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:03:47.305  7200  7200 D ActivityThread: Added TimaKeyStore provider
,07-27 09:03:47.325  7200  7200 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-27 09:03:47.345  7200  7200 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-27 09:03:47.355  7200  7200 D AtFwdService: onCreate method
,07-27 09:03:47.355  7200  7200 I AtFwdService: Instantiate AtCmdFwd Service
,07-27 09:03:47.365  7200  7212 D AtCkpdCmdHandler: De-queing command
,07-27 09:03:49.485   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:03:57.245   753   827 I ActivityManager: Start proc 7215:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-27 09:03:57.245  7215  7215 E Zygote  : v2
,07-27 09:03:57.245  7215  7215 I libpersona: KNOX_SDCARD checking this for 10026
07-27 09:03:57.245  7215  7215 I libpersona: KNOX_SDCARD not a persona
,07-27 09:03:57.255  7215  7215 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:03:57.255  7215  7215 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:03:57.255  7215  7215 E Zygote  : accessInfo : 0
,07-27 09:03:57.255  7215  7215 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-27 09:03:57.295  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:03:57.305  7215  7215 D ActivityThread: Added TimaKeyStore provider
,07-27 09:03:57.325  7215  7215 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-27 09:03:57.345  7215  7215 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-27 09:03:57.355  7215  7215 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-27 09:03:57.355  7215  7215 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-27 09:03:59.545   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:04:01.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:04:01.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:04:01.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:04:04.905   753   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:04.915   753   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:04:04.915   753   768 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:04:04.925   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:04.935   753   753 I MotionRecognitionService: Plugged
,07-27 09:04:04.935   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:04:04.935   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:04:04.935   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:04:04.945   753   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:04:04.945   753   768 D BatteryService: stay LED for fully charged
,07-27 09:04:04.945  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:04.945  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:04.945  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:04.965  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:04:04.965  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:04:04.975  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:04.975  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:04.975  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:09.595   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:04:11.115   753  1574 E Watchdog: !@Sync 22 [07-27 09:04:11.129]
,07-27 09:04:12.955  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:04:19.655   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:04:29.715   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:04:34.975   753  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:34.985   753  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:04:34.985   753  1320 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:04:34.995   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:04:35.005   753   753 I MotionRecognitionService: Plugged
,07-27 09:04:35.005   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:04:35.005   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:04:35.015   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:04:35.015   753  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:04:35.015   753  1320 D BatteryService: stay LED for fully charged
,07-27 09:04:35.035  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:04:35.045  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:04:35.045  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:35.065  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:04:35.065  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:04:35.065  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:35.065  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:04:35.065  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:39.765   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:04:41.125   753  1574 E Watchdog: !@Sync 23 [07-27 09:04:41.134]
,07-27 09:04:49.825   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:04:59.875   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:05:05.055   753  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:05.065   753  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:05:05.065   753  1485 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:05:05.065   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:05.075   753   753 I MotionRecognitionService: Plugged
,07-27 09:05:05.085   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:05:05.085   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:05:05.085   753  1485 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-27 09:05:05.085   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:05:05.095   753  1485 D BatteryService: stay LED for fully charged
,07-27 09:05:05.095  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:05.095  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:05:05.095  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:05.115  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:05.115  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:05:05.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:05.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:05.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:09.935   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:05:11.125   753  1574 E Watchdog: !@Sync 24 [07-27 09:05:11.139]
,07-27 09:05:13.095  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:05:19.985   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:05:30.035   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:05:35.125   753  1789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:05:35.135   753  1789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:05:35.135   753  1789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:05:35.135   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:05:35.145   753   753 I MotionRecognitionService: Plugged
,07-27 09:05:35.145   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:05:35.155   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:05:35.155   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:05:35.165   753  1789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-27 09:05:35.175   753  1789 D BatteryService: stay LED for fully charged
,07-27 09:05:35.185  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:35.185  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:35.185  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:35.205  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:35.215  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:05:35.215  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:35.215  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:35.215  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:40.095   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:05:41.135   753  1574 E Watchdog: !@Sync 25 [07-27 09:05:41.143]
,07-27 09:05:50.145   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:06:00.205   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:06:05.205   753   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:05.205   753   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:06:05.215   753   769 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:06:05.215   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:05.225   753   753 I MotionRecognitionService: Plugged
,07-27 09:06:05.235   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:06:05.235   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:06:05.235   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:06:05.235   753   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:06:05.245   753   769 D BatteryService: stay LED for fully charged
,07-27 09:06:05.245  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:05.245  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:06:05.245  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:05.265  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:05.265  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:05.265  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:05.275  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:05.275  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:10.255   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:06:11.135   753  1574 E Watchdog: !@Sync 26 [07-27 09:06:11.147]
,07-27 09:06:13.195  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:06:13.305  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 94ms lastUpdatedAfter : 180362ms
,07-27 09:06:14.385   753  2172 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 09:06:14.395   753  2172 V MARsPolicyManager: updateSMDBValues
,07-27 09:06:14.395   753   888 E MARsDBManager: updateDBAll : begin --size 1
,07-27 09:06:14.465   753   888 E MARsDBManager: updateDBAll : end
,07-27 09:06:14.465   753   888 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-27 09:06:20.315   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:06:30.365   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:06:35.285   753  2013 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:06:35.295   753  2013 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:06:35.295   753  2013 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:06:35.295   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:35.315   753   753 I MotionRecognitionService: Plugged
,07-27 09:06:35.315   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:06:35.315   753  2013 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 09:06:35.315   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:06:35.325   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:06:35.325   753  2013 D BatteryService: stay LED for fully charged
,07-27 09:06:35.345  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:06:35.345  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:06:35.345  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:35.365  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:35.365  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:35.365  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:35.365  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:35.365  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:40.425   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:06:41.145   753  1574 E Watchdog: !@Sync 27 [07-27 09:06:41.151]
,07-27 09:06:50.475   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:00.525   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:05.365   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:10.575   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:11.155   753  1574 E Watchdog: !@Sync 28 [07-27 09:07:11.162]
,07-27 09:07:13.335  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:07:20.635   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:30.685   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:35.455   753  1898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:40.745   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:41.155   753  1574 E Watchdog: !@Sync 29 [07-27 09:07:41.166]
,07-27 09:07:50.805   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:07:55.865   753  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:07:55.865   753  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:07:55.875   753  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:07:59.265   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:07:59.265   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:07:59.275   753  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:07:59.285   753  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:08:00.855   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:08:05.525   753  2163 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:05.525   753  2163 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0,
07-27 09:08:05.525   753  2163 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:08:05.535   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:08:05.545   753   753 I MotionRecognitionService: Plugged
,07-27 09:08:05.545   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:08:05.545   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:08:05.555   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:08:05.555   753  2163 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:08:05.565   753  2163 D BatteryService: stay LED for fully charged
,07-27 09:08:05.575  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:05.575  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:05.585  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:08:05.615  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:08:05.615  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:08:05.615  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:05.615  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:08:05.615  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:10.905   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:08:11.155   753  1574 E Watchdog: !@Sync 30 [07-27 09:08:11.170]
,07-27 09:08:13.425  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:08:20.965   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:08:31.015   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:08:31.115   753  1236 V AlarmManager: Expired Alarm result :4
,07-27 09:08:31.155   753  1236 I ActivityManager: Killing 3584:com.sec.spp.push/u0a37 (adj 5): SSR - service for lastStateTime 905s, lastActivityTime 671s
,07-27 09:08:31.165   753  1236 I ActivityManager: Killing 1517:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 895s, lastActivityTime 675s
,07-27 09:08:31.165   753  1236 I ActivityManager: Killing 1860:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 917s, lastActivityTime 676s
,07-27 09:08:31.195  5512  5512 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(22306): Beginning daily hygiene, foreground = false
,07-27 09:08:31.205  5512  5512 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(366): Probe [UVAT3FEWOLBYQGmBHvKHAcB3G_U] for daily hygiene pass
,07-27 09:08:31.235  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:08:31.235  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:08:31.235  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:08:31.245  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:08:31.245   753  2163 W ActivityManager: ProcessRecord{f4c706b 1517:com.sec.android.daemonapp/u0a181} is already killed
,07-27 09:08:31.265  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:08:31.265   753   827 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-27 09:08:31.275  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.275  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.275  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.275  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.285  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.285  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.285   753   753 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-27 09:08:31.285   753   753 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:08:31.285  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.285   753   753 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-27 09:08:31.295   753   753 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-27 09:08:31.305   753  2167 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,07-27 09:08:31.305   753  2167 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-27 09:08:31.305   753  2167 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-27 09:08:31.345  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:31.345   753  1898 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
07-27 09:08:31.345   753  1898 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-27 09:08:31.345  1808  7253 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-27 09:08:31.355  5569  5569 D HealthConsole: Service for HealthDataStore is disconnected
,07-27 09:08:31.365  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:31.365  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:31.365   753  2163 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-27 09:08:31.365   753  2163 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-27 09:08:31.365   753  2163 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 10938ms
07-27 09:08:31.365   753  2163 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-27 09:08:31.365   753  2163 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 20938ms
,07-27 09:08:31.395  7258  7258 E Zygote  : v2
07-27 09:08:31.395  7258  7258 I libpersona: KNOX_SDCARD checking this for 10034
07-27 09:08:31.395  7258  7258 I libpersona: KNOX_SDCARD not a persona
,07-27 09:08:31.395  7258  7258 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:08:31.395  7258  7258 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:08:31.395   753  1898 I ActivityManager: Start proc 7258:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
07-27 09:08:31.395  7258  7258 E Zygote  : accessInfo : 0
07-27 09:08:31.395  7258  7258 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-27 09:08:31.405  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:08:31.415  7258  7258 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:08:31.415  7258  7258 D ActivityThread: Added TimaKeyStore provider
,07-27 09:08:31.425  1808  7237 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-27 09:08:31.435  7258  7258 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-27 09:08:31.465  7258  7258 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-27 09:08:31.465  7258  7258 I MultiDex: VM with version 2.1.0 has multidex support
07-27 09:08:31.465  7258  7258 I MultiDex: install
07-27 09:08:31.465  7258  7258 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-27 09:08:31.465  7258  7258 I MultiDex: install
07-27 09:08:31.465  7258  7258 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 09:08:31.475   306  1182 D EnterpriseController: netId is 0
07-27 09:08:31.475   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-27 09:08:31.475   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:08:31.475   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:08:31.475   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:08:31.535  5512  5550 I qtaguid : Tagging socket 36 with tag e8d195d100000000{3906049489,0} uid -1, pid: 5512, getuid(): 10029
,07-27 09:08:31.585  7276  7276 E Zygote  : v2
07-27 09:08:31.585  7276  7276 I libpersona: KNOX_SDCARD checking this for 10016
07-27 09:08:31.585  7276  7276 I libpersona: KNOX_SDCARD not a persona
,07-27 09:08:31.585  7276  7276 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:08:31.585   753  1747 I ActivityManager: Start proc 7276:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
07-27 09:08:31.585  7276  7276 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:08:31.585  1808  7237 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-27 09:08:31.585  1808  7237 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
07-27 09:08:31.585  7276  7276 E Zygote  : accessInfo : 0
07-27 09:08:31.585  7276  7276 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-27 09:08:31.595  1808  7237 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,07-27 09:08:31.595  1808  7237 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-27 09:08:31.605  7276  7276 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:08:31.605  7276  7276 D ActivityThread: Added TimaKeyStore provider
,07-27 09:08:31.615  7276  7276 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-27 09:08:31.635  1808  7237 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
,07-27 09:08:31.635  1808  7237 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-27 09:08:31.645  7258  7258 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-27 09:08:31.645  7258  7258 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-27 09:08:31.665   753   904 D LightsService: [SvcLED]  onSensorChanged::light value = 26
,07-27 09:08:31.665   753   904 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-27 09:08:31.685   753   904 D SensorManager: unregisterListener ::   
07-27 09:08:31.685   753   904 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
,07-27 09:08:31.685   753   904 D lights  : led_pattern : 5 +
,07-27 09:08:31.685  1378  1378 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-27 09:08:31.685   753  1485 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,07-27 09:08:31.695   753   904 D lights  : led_pattern : 5 -
07-27 09:08:31.695   753   904 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-27 09:08:31.695   753   904 V AlarmManager:  remove PendingIntent] PendingIntent{bae3c6: PendingIntentRecord{21d7f87 android broadcastIntent}}
,07-27 09:08:31.705  1378  1378 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{2c48ab6 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
07-27 09:08:31.705  1378  1378 D AdaptiveEventManager: M updateContainers()
07-27 09:08:31.705  1378  1378 D AdaptiveEventContainerSmall: C updatePedoContainer()
07-27 09:08:31.705  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate()
07-27 09:08:31.705   753  1417 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-27 09:08:31.705  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-27 09:08:31.705   753  2013 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-27 09:08:31.705   753  1898 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-27 09:08:31.715   753  1650 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-27 09:08:31.735  5512  5550 I qtaguid : Tagging socket 45 with tag e8d195d100000000{3906049489,0} uid -1, pid: 5512, getuid(): 10029
,07-27 09:08:31.755  7258  7258 I Health.HealthService: HealthService: onCreate() start (7258)
,07-27 09:08:31.755  4114  7291 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-27 09:08:31.875  5569  5569 D HealthDataStore: Service for HealthDataStore is connected
,07-27 09:08:31.875  4114  4851 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-27 09:08:31.875  5569  5569 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 09:08:31.925  5569  5569 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-27 09:08:31.925  5569  5569 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 09:08:31.925  5512  5512 I Finsky  : [1] com.google.android.finsky.utils.cs.a_(1198): Server requests device config token
,07-27 09:08:31.965  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:32.005  7258  7258 D HealthDataStore: Service for HealthDataStore is connected
,07-27 09:08:32.005  7258  7258 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 09:08:32.015  7258  7258 D HealthConsole: Service for HealthDataConsole is connected
,07-27 09:08:32.015  7258  7258 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-27 09:08:32.015  7258  7258 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 09:08:32.115  7258  7298 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-27 09:08:32.125  5512  5512 I Finsky  : [1] com.google.android.finsky.utils.bb.a_(1261): Received device config token 1469603312152
,07-27 09:08:32.145  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:32.165  7258  7303 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-27 09:08:32.195  7276  7286 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 09:08:32.195   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7276
07-27 09:08:32.195   385   385 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-27 09:08:32.325  7305  7305 E Zygote  : v2
07-27 09:08:32.325  7305  7305 I libpersona: KNOX_SDCARD checking this for 10181
07-27 09:08:32.325  7305  7305 I libpersona: KNOX_SDCARD not a persona
,07-27 09:08:32.325  7305  7305 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:08:32.325  7305  7305 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:08:32.325  7305  7305 E Zygote  : accessInfo : 0
07-27 09:08:32.325  7305  7305 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-27 09:08:32.335   753   827 I ActivityManager: Start proc 7305:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,07-27 09:08:32.335   753  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 09:08:32.355  7305  7305 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:08:32.355  7305  7305 D ActivityThread: Added TimaKeyStore provider
,07-27 09:08:32.365   753  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-27 09:08:32.365  7305  7305 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-27 09:08:32.385  7276  7286 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-27 09:08:32.385  7305  7305 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-27 09:08:32.395  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:32.415  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-27 09:08:32.425  7305  7305 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:08:32.425   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2dad0bc u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c5845 7305:com.sec.android.daemonapp/u0a181}
,07-27 09:08:32.425  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-27 09:08:32.435  7305  7305 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:08:32.435  7305  7305 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
07-27 09:08:32.435  7305  7305 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:08:32.435  7305  7305 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-27 09:08:32.435  7305  7305 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:08:32.445  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:08:32.445  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-27 09:08:32.445  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-27 09:08:32.455  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:08:32.455  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:08:32.455  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-27 09:08:32.455  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-27 09:08:32.475  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-27 09:08:32.475  5512  5512 I Finsky  : [1] com.google.android.finsky.selfupdate.f.a(166): Skipping DFE self-update. Local Version [80682400] >= Server Version [-1]
,07-27 09:08:32.485  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:08:32.485  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-27 09:08:32.485  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-27 09:08:32.495  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:32.495  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-27 09:08:32.505  7305  7305 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:08:32.505  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.505  7305  7305 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:08:32.505  7305  7305 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:08:32.505  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.505  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:08:32.505  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:08:32.505  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-27 09:08:32.505  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:08:32.505  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:08:32.505  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.515  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:08:32.515   753  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{24a4afd u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c5845 7305:com.sec.android.daemonapp/u0a181}
,07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:08:32.525  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.525  7305  7305 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-27 09:08:32.525  7305  7305 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:08:32.525  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-27 09:08:32.525  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.535  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:08:32.535   753  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7599f9 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c5845 7305:com.sec.android.daemonapp/u0a181}
,07-27 09:08:32.545  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:08:32.545  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:08:32.545  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:08:32.545  7258  7303 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-27 09:08:32.545  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.545  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:08:32.555  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.555  7305  7305 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-27 09:08:32.555  7305  7305 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:08:32.555  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.555  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:08:32.555   753  2013 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6929d3e u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c5845 7305:com.sec.android.daemonapp/u0a181}
,07-27 09:08:32.565  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:08:32.565  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:08:32.565  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:08:32.565  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:08:32.575  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.575  7305  7305 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:08:32.575  7305  7305 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:08:32.575  7305  7305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:08:32.575  7305  7305 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:08:32.655  7258  7303 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-27 09:08:32.655  7258  7303 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-27 09:08:32.735   385   385 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-27 09:08:32.745  1808  7237 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-27 09:08:32.755   753   764 I art     : Background partial concurrent mark sweep GC freed 67647(7MB) AllocSpace objects, 324(6MB) LOS objects, 27% free, 41MB/57MB, paused 1.518ms total 108.169ms
,07-27 09:08:32.775  7276  7286 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-27 09:08:32.775  7276  7286 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-27 09:08:32.775  7276  7286 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-27 09:08:32.805  4114  4851 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-27 09:08:32.855  4114  5525 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:08:32.895  4114  4851 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:08:32.915  4114  4851 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:08:32.925  1808  7237 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-27 09:08:33.015  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:33.245   753   769 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  1623 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  1650 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.245   753  1677 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  1320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.245   753  1417 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  1789 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  2163 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.245   753   768 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  1485 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.245   753  2167 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.245   753  2013 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.255   753  1747 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.255   753  1898 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.255   753   769 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.255   753  1623 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.255   753  1650 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.255   753  1677 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.255   753  1320 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.255   753  1417 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:08:33.255   753  1789 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.255   753  2163 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:08:33.275  5512  5512 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(741): Logging device features
,07-27 09:08:33.285  5512  5512 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,07-27 09:08:33.285   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6f3f369 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99cf23c 1999:com.google.android.gms.persistent/u0a11}
,07-27 09:08:33.295   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{63ed1ee: PendingIntentRecord{f6290d com.google.android.gms broadcastIntent}}
,07-27 09:08:33.295   753  1236 V AlarmManager: Expired Alarm result :4
,07-27 09:08:33.305   753   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2855d1c u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39a77b6 5512:com.android.vending/u0a29}
,07-27 09:08:33.315  5512  7330 I Finsky  : [830] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-27 09:08:33.315  5512  5755 I PlayCommon: [813] com.google.android.play.a.w.a(27553): Starting to flush logs
,07-27 09:08:33.335  5512  5755 I PlayCommon: [813] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,07-27 09:08:33.335  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:08:33.345  1999  2011 D DeviceConnectionService: client connected with version: 8487000
,07-27 09:08:33.365  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:33.375  1999  1999 D WearableService: callingUid 10011, callindPid: 1999
,07-27 09:08:33.375  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:08:33.375  5512  5512 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-27 09:08:33.375  5512  5512 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=hygiene due to Gms not connected
07-27 09:08:33.375  5512  5543 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:08:33.385  5512  5543 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:08:33.385   306  1182 D EnterpriseController: netId is 0
07-27 09:08:33.385   306  1182 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-27 09:08:33.545  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,07-27 09:08:33.555  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:08:33.555  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:08:35.595   753  1417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:35.605   753  1417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:08:35.605   753  1417 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:08:35.615   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:08:35.625   753   753 I MotionRecognitionService: Plugged
,07-27 09:08:35.625   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:08:35.625   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:08:35.625   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:08:35.635   753  1417 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:08:35.635   753  1417 D BatteryService: stay LED for fully charged
,07-27 09:08:35.645  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:35.645  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:08:35.655  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:08:35.685  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:35.685  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:35.685  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:08:35.695  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:08:35.695  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:08:37.985   753  1677 I ActivityManager: Killing 6087:com.sec.kidsplat.installer/u0a165 (adj 15): DHA:empty #37
,07-27 09:08:38.045   753  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.kidsplat.installer, Auto Run ON
,07-27 09:08:41.085   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 450, LCD = 0
,07-27 09:08:41.165   753  1574 E Watchdog: !@Sync 31 [07-27 09:08:41.178]
,07-27 09:08:47.755   753  1236 V AlarmManager: Expired Alarm result :4,
,07-27 09:08:47.825  5512  5563 I Finsky  : [801] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-27 09:08:48.115  5512  5563 I Finsky  : [801] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
07-27 09:08:48.115  5512  5512 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-27 09:08:48.565   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:08:48.565   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:08:48.565   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:08:51.145   753  3282 D SSRM:n  : SIOP:: AP = 300, PST = 292, CUR = 450, LCD = 0
,07-27 09:08:59.985   753  1236 V AlarmManager: Expired Alarm result :8
,07-27 09:09:01.195   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:09:05.685   753  1417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:05.685   753  1417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:09:05.695   753  1417 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:09:05.695   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:09:05.705   753   753 I MotionRecognitionService: Plugged
,07-27 09:09:05.715   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:09:05.715   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:09:05.715   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:09:05.725   753  1417 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-27 09:09:05.725   753  1417 D BatteryService: stay LED for fully charged
,07-27 09:09:05.735  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:09:05.735  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:09:05.735  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:09:05.755  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:09:05.755  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:09:05.755  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:05.765  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:05.765  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:11.175   753  1574 E Watchdog: !@Sync 32 [07-27 09:09:11.187]
,07-27 09:09:11.255   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:09:13.525  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:09:21.315   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:09:31.375   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:09:35.745   753  2163 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:35.755   753  2163 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:09:35.755   753  2163 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:09:35.755   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:09:35.775   753   753 I MotionRecognitionService: Plugged
,07-27 09:09:35.775   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:09:35.775   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:09:35.775   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:09:35.785   753  2163 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:09:35.785   753  2163 D BatteryService: stay LED for fully charged
,07-27 09:09:35.785  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:09:35.785  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:09:35.785  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:09:35.805  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:09:35.805  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:09:35.815  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:35.815  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:35.815  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:41.185   753  1574 E Watchdog: !@Sync 33 [07-27 09:09:41.191]
,07-27 09:09:41.425   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:09:51.485   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:10:01.545   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:10:05.815   753  2013 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:10:05.815   753  2013 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:10:05.825   753  2013 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:10:05.825   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:10:05.835   753   753 I MotionRecognitionService: Plugged
,07-27 09:10:05.835   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:10:05.845   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:10:05.845   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:10:05.855   753  2013 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-27 09:10:05.855   753  2013 D BatteryService: stay LED for fully charged
,07-27 09:10:05.875  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:05.875  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:05.885  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:10:05.905  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:10:05.905  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:10:05.905  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:05.905  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:05.905  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:11.185   753  1574 E Watchdog: !@Sync 34 [07-27 09:10:11.197]
,07-27 09:10:11.595   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 09:10:13.585  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:10:21.645   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-27 09:10:31.705   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:10:35.885   753   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:10:35.885   753   769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:10:35.895   753   769 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:10:35.895   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:10:35.915   753   753 I MotionRecognitionService: Plugged
,07-27 09:10:35.915   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:10:35.915   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:10:35.925   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:10:35.925   753   769 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,07-27 09:10:35.925   753   769 D BatteryService: stay LED for fully charged
,07-27 09:10:35.935  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:35.935  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:10:35.935  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:10:35.955  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:10:35.955  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:10:35.955  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:35.965  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:35.965  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:41.195   753  1574 E Watchdog: !@Sync 35 [07-27 09:10:41.203]
,07-27 09:10:41.765   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:10:51.825   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:11:01.885   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:11:05.955   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:11:05.965   753  2167 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:11:05.965   753  2167 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:11:05.965   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:11:05.975   753   753 I MotionRecognitionService: Plugged
,07-27 09:11:05.985   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:11:05.985   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:11:05.985   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:11:05.985   753  2167 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-27 09:11:05.995   753  2167 D BatteryService: stay LED for fully charged
,07-27 09:11:06.005  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:11:06.005  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:11:06.005  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:11:06.045  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:06.045  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:06.045  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:06.045  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:11:06.045  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:11:11.195   753  1574 E Watchdog: !@Sync 36 [07-27 09:11:11.207]
,07-27 09:11:11.935   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:11:13.655  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:11:13.785  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 111ms lastUpdatedAfter : 162043ms
,07-27 09:11:21.995   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:11:32.045   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:11:36.035   753  1417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:11:36.035   753  1417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:11:36.035   753  1417 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:11:36.045   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:11:36.055   753   753 I MotionRecognitionService: Plugged
,07-27 09:11:36.055   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:11:36.055   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:11:36.055   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:11:36.065   753  1417 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:11:36.065   753  1417 D BatteryService: stay LED for fully charged
,07-27 09:11:36.085  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:11:36.085  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:11:36.085  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:11:36.105  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:11:36.105  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:11:36.105  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:36.105  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:36.105  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:41.205   753  1574 E Watchdog: !@Sync 37 [07-27 09:11:41.211]
,07-27 09:11:42.105   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:11:52.155   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:02.205   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:11.205   753  1574 E Watchdog: !@Sync 38 [07-27 09:12:11.216]
,07-27 09:12:12.265   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:12.835   753  1236 V AlarmManager: Expired Alarm result :4
,07-27 09:12:12.885  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:12:12.885  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 09:12:12.895  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:12:12.905  6448  6482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:12:12.905  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.905  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:12:12.905  6448  6482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:12:12.905  6448  6482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:12:12.905  6448  6482 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:12:12.905  6448  6518 D bt_upio : upio_start_stop_timer : timer_settime success
07-27 09:12:12.905  6448  6518 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-27 09:12:12.915  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.915  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.915  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.915  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.915  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:12:12.915  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.915  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.915  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.915  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.925  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.925  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.925  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.925  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.925  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.925  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.925  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.925  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.925  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.925  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.925  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.925  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.925  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.925  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.925  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.935  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.935  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.935  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.935  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.935  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.935  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.935  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.935  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.935  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.935  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.935  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.935  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.935  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.935  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.935  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.935  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.935  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.935  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.945  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.945  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.945  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.945  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.945  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.945  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.945  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.945  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.945  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.945  6448  6518 D bt_vendor: op for 7
,07-27 09:12:12.945  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.945  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.945  6448  6518 D bt_vendor: op for 7
07-27 09:12:12.945  6448  6518 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:12:12.945  6448  6518 D bt_upio : BT_WAKE is asserted already
,07-27 09:12:12.975   753  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:12:12.975   753  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:12:12.975   753  1320 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:12:12.975   753  1320 D BatteryService: stay LED for fully charged
,07-27 09:12:12.985  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:12:12.985   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:12:12.995  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
07-27 09:12:12.995   753   753 I MotionRecognitionService: Plugged
07-27 09:12:12.995   753   753 D MotionRecognitionService:   cableConnection= 1
07-27 09:12:12.995   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:12:12.995   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:12:12.995   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{9a3c17f: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:12.995  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:12.995  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:12:12.995  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:12.995  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:12:12.995  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:12.995  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:12:12.995  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:12:12.995  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:12:12.995  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:12.995  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:12:12.995  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:12:13.005  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:12:13.005  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:12:13.005  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:12:13.005  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:12:13.005   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{6e8454c: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.005   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{acad995: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.015   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{4e83aaa: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.015   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{23cf69b: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.015   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{dfa6a38: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.015   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{f4c7a11: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.025   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{ae75776: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.035   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{c6a6177: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.035  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:13.045   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{c07f1e4: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.055   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{56da64d: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.065   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{4e97502: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.075   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{a999e13: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.075   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{7444850: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.075   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{3fb5a49: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.075   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{4fddf4e: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.085   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{e76086f: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.085   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{3ad997c: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.085   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{7965205: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.095   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{cdca25a: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.095   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{f04bc8b: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.095   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{4f8d168: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.095   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{c2f0981: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.105   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{fb28a26: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.105   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{4809667: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.105   753  1789 V AlarmManager:  remove PendingIntent] PendingIntent{33d9c14: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.105   753  1898 V AlarmManager:  remove PendingIntent] PendingIntent{241bcbd: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.105   753  2013 V AlarmManager:  remove PendingIntent] PendingIntent{4ad22b2: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.115   753   769 V AlarmManager:  remove PendingIntent] PendingIntent{5f63203: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.115   753  1677 V AlarmManager:  remove PendingIntent] PendingIntent{e626580: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.115   753  1485 V AlarmManager:  remove PendingIntent] PendingIntent{bd267b9: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.115   753   768 V AlarmManager:  remove PendingIntent] PendingIntent{646b7fe: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.115   753  1747 V AlarmManager:  remove PendingIntent] PendingIntent{49feb5f: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.125   753  1623 V AlarmManager:  remove PendingIntent] PendingIntent{c4859ac: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.125   753  2167 V AlarmManager:  remove PendingIntent] PendingIntent{d28c675: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.125   753  2163 V AlarmManager:  remove PendingIntent] PendingIntent{a52560a: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.125   753  1417 V AlarmManager:  remove PendingIntent] PendingIntent{101de7b: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.125   753  1650 V AlarmManager:  remove PendingIntent] PendingIntent{db76498: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.135   753  1320 V AlarmManager:  remove PendingIntent] PendingIntent{d4c54f1: PendingIntentRecord{379929e com.android.bluetooth broadcastIntent}}
,07-27 09:12:13.705  6448  6599 D bt_upio : ..proc_btwrite_timeout..
07-27 09:12:13.705  6448  6599 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 09:12:13.885  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:12:22.325   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:32.385   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:33.995   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:12:33.995   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:12:33.995   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:12:41.215   753  1574 E Watchdog: !@Sync 39 [07-27 09:12:41.220]
,07-27 09:12:42.435   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:42.985   753  2163 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:12:49.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:12:49.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:12:49.125   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:12:52.485   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:12:55.865   753  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:12:55.865   753  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:12:55.875   753  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:12:57.355   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:12:57.355   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:12:57.365   753  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:12:57.375   753  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:12:59.985   753  1236 V AlarmManager: Expired Alarm result :8
,07-27 09:13:02.545   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:13:07.905   753   817 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:13:11.215   753  1574 E Watchdog: !@Sync 40 [07-27 09:13:11.225]
,07-27 09:13:12.595   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:13:13.065   753  2163 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:13:13.075   753  2163 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:13:13.075   753  2163 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:13:13.075   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:13:13.095   753   753 I MotionRecognitionService: Plugged
,07-27 09:13:13.095   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:13:13.095   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:13:13.095   753  2163 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 09:13:13.105   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:13:13.105   753  2163 D BatteryService: stay LED for fully charged
,07-27 09:13:13.125  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:13:13.125  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:13:13.125  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:13:13.155  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:13:13.155  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:13:13.165  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:13.165  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:13.165  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:13.915  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:13:22.655   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:13:32.715   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:13:33.555   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:13:33.555   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:13:33.555   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:13:41.215   753  1574 E Watchdog: !@Sync 41 [07-27 09:13:41.229]
,07-27 09:13:42.775   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:13:43.145   753   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:13:46.095  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:13:46.095  5512  5543 I PlayCommon: [785] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:13:48.645   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:13:48.645   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:13:48.645   306  1178 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:13:48.655   753  1789 I ActivityManager: Killing 7200:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 601s, lastActivityTime 601s
,07-27 09:13:48.705   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-27 09:13:48.715   370  4905 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-27 09:13:48.715   370  4905 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:13:48.715   753  1320 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-27 09:13:48.715   753  1320 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-27 09:13:48.715   753  1320 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-27 09:13:49.715   370  4905 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:13:49.745   753   827 I ActivityManager: Start proc 7397:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-27 09:13:49.755  7397  7397 E Zygote  : v2
,07-27 09:13:49.765  7397  7397 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:13:49.765  7397  7397 I libpersona: KNOX_SDCARD not a persona
,07-27 09:13:49.765  7397  7397 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:13:49.765  7397  7397 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:13:49.775  7397  7397 E Zygote  : accessInfo : 0
,07-27 09:13:49.825  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:13:49.825  7397  7397 D ActivityThread: Added TimaKeyStore provider
,07-27 09:13:49.855  7397  7397 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-27 09:13:49.865  7397  7397 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-27 09:13:49.875  7397  7397 D AtFwdService: onCreate method
,07-27 09:13:49.875  7397  7397 I AtFwdService: Instantiate AtCmdFwd Service
,07-27 09:13:49.885  7397  7409 D AtCkpdCmdHandler: De-queing command
,07-27 09:13:52.825   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:14:02.885   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:14:11.225   753  1574 E Watchdog: !@Sync 42 [07-27 09:14:11.234]
,07-27 09:14:12.935   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:14:13.215   753  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:14:13.225   753  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:14:13.225   753  1623 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:14:13.225   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:14:13.245   753   753 I MotionRecognitionService: Plugged
,07-27 09:14:13.245   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:14:13.245   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:14:13.255   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:14:13.255   753  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:14:13.255   753  1623 D BatteryService: stay LED for fully charged
,07-27 09:14:13.285  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:14:13.285  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:14:13.285  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:14:13.315  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:14:13.315  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:14:13.315  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:13.315  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:13.315  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:13.975  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:14:14.095  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 108ms lastUpdatedAfter : 180314ms
,07-27 09:14:22.995   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:14:33.045   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:14:41.225   753  1574 E Watchdog: !@Sync 43 [07-27 09:14:41.239]
,07-27 09:14:43.105   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:14:43.285   753  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:14:53.155   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:15:03.205   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:15:11.235   753  1574 E Watchdog: !@Sync 44 [07-27 09:15:11.243]
,07-27 09:15:13.265   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:15:13.365   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:15:14.105  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:15:23.315   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:15:33.375   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:15:41.235   753  1574 E Watchdog: !@Sync 45 [07-27 09:15:41.247]
,07-27 09:15:43.465   753  1789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:15:43.465   753  1789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:15:43.465   753  1789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:15:43.475   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:15:43.485   753   753 I MotionRecognitionService: Plugged
,07-27 09:15:43.485   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:15:43.495   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:15:43.495   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:15:43.495   753  1789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:15:43.495   753  1789 D BatteryService: stay LED for fully charged
,07-27 09:15:43.515  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:15:43.515  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:15:43.515  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:15:43.545   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:15:43.545  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:43.555  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:43.555  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:43.565  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:15:43.565  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:15:53.615   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:16:03.665   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:16:11.245   753  1574 E Watchdog: !@Sync 46 [07-27 09:16:11.251]
,07-27 09:16:13.535   753  1898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:16:13.725   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:16:14.155  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:16:23.775   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:16:33.835   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:16:41.245   753  1574 E Watchdog: !@Sync 47 [07-27 09:16:41.259]
,07-27 09:16:43.605   753  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:16:43.895   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:16:53.945   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:04.005   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:11.255   753  1574 E Watchdog: !@Sync 48 [07-27 09:17:11.265]
,07-27 09:17:13.675   753  2167 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:17:13.685   753  2167 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:17:13.685   753  2167 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:17:13.685   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:17:13.705   753   753 I MotionRecognitionService: Plugged
,07-27 09:17:13.705   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:17:13.705   753  2167 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-27 09:17:13.705   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:17:13.715   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:17:13.715   753  2167 D BatteryService: stay LED for fully charged
,07-27 09:17:13.725  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:17:13.735  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:17:13.735  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:17:13.755  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:17:13.755  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:17:13.765  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:17:13.765  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:17:13.765  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:17:14.055   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:14.175  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:17:14.295  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 104ms lastUpdatedAfter : 180202ms
,07-27 09:17:24.115   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:34.175   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:41.255   753  1574 E Watchdog: !@Sync 49 [07-27 09:17:41.270]
,07-27 09:17:43.755   753   769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:17:44.225   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:54.275   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:17:55.865   753  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:17:55.875   753  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:17:55.875   753  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:17:59.275   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:17:59.275   753  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:17:59.285   753  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:17:59.285   753  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:18:04.325   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:18:11.265   753  1574 E Watchdog: !@Sync 50 [07-27 09:18:11.274]
,07-27 09:18:13.835   753  1898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:18:13.835   753  1898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:18:13.835   753  1898 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:18:13.845   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:18:13.855   753   753 I MotionRecognitionService: Plugged
,07-27 09:18:13.855   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:18:13.855   753  1898 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,07-27 09:18:13.865   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:18:13.865   753  1898 D BatteryService: stay LED for fully charged
,07-27 09:18:13.865   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:18:13.885  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:18:13.885  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:18:13.895  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:18:13.905  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:18:13.915  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:18:13.915  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:13.915  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:13.915  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:14.385   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:18:14.395   753  2172 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 09:18:14.405   753  2172 V MARsPolicyManager: updateSMDBValues
,07-27 09:18:14.405   753   888 E MARsDBManager: updateDBAll : begin --size 0
,07-27 09:18:14.405   753   888 E MARsDBManager: updateDBAll : end
,07-27 09:18:14.425  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:18:24.445   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:18:34.495   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:18:41.265   753  1574 E Watchdog: !@Sync 51 [07-27 09:18:41.278]
,07-27 09:18:43.905   753  1417 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:18:43.915   753  1417 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:18:43.915   753  1417 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:18:43.915   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:18:43.925   753   753 I MotionRecognitionService: Plugged
,07-27 09:18:43.935   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:18:43.935   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:18:43.945   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:18:43.945   753  1417 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-27 09:18:43.945   753  1417 D BatteryService: stay LED for fully charged
,07-27 09:18:43.955  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:18:43.955  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:18:43.965  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:18:43.995  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:43.995  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:18:43.995  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:44.005  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:18:44.005  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:18:44.545   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:18:54.595   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:19:04.655   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:19:11.275   753  1574 E Watchdog: !@Sync 52 [07-27 09:19:11.284]
,07-27 09:19:13.985   753  1650 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:19:14.475  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:19:14.705   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:19:24.755   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:19:34.815   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:19:41.275   753  1574 E Watchdog: !@Sync 53 [07-27 09:19:41.288]
,07-27 09:19:44.055   753  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:19:44.055   753  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:19:44.065   753  1747 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:19:44.065   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:19:44.075   753   753 I MotionRecognitionService: Plugged
,07-27 09:19:44.075   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:19:44.085   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:19:44.085   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:19:44.085   753  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:19:44.095   753  1747 D BatteryService: stay LED for fully charged
,07-27 09:19:44.095  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:19:44.095  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:19:44.095  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:19:44.115  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:19:44.115  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:19:44.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:19:44.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:19:44.125  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:19:44.865   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:19:54.925   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:20:04.975   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:20:11.285   753  1574 E Watchdog: !@Sync 54 [07-27 09:20:11.294]
,07-27 09:20:14.125   753  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:20:14.585  1661  1745 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:20:14.705  1661  1745 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 106ms lastUpdatedAfter : 180409ms
,07-27 09:20:15.035   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:20:25.085   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:20:35.145   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:20:41.285   753  1574 E Watchdog: !@Sync 55 [07-27 09:20:41.298]
,07-27 09:20:44.205   753  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:20:44.215   753  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:20:44.215   753  1485 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:20:44.215   753   753 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:20:44.235   753   753 I MotionRecognitionService: Plugged
,07-27 09:20:44.235   753   753 D MotionRecognitionService:   cableConnection= 1
,07-27 09:20:44.235   753   753 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:20:44.235   753   753 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:20:44.245   753  1485 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:20:44.245   753  1485 D BatteryService: stay LED for fully charged
,07-27 09:20:44.245  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:20:44.245  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:20:44.245  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:20:44.265  6448  6448 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:20:44.265  6448  6602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:20:44.275  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:20:44.275  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:20:44.275  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:20:45.195   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 09:20:55.255   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),07-27 09:21:05.305   753  3282 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
07-27 09:21:08.745  2045  2045 E audit   : type=1400 msg=audit(1469604068.745:294): avc:  denied  { execmod } for  pid=7435 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 09:21:08.755  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:21:08.755  2045  2045 E audit   : type=1300 msg=audit(1469604068.745:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f43000 a1=51000 a2=5 a3=4 items=0 ppid=3433 ppcomm=adbd pid=7435 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 09:21:08.755  2045  2045 E audit   : type=1327 msg=audit(1469604068.745:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-27 09:21:08.755  2045  2045 E audit   : type=1320 msg=audit(1469604068.745:294): 
07-27 09:21:08.805  2045  2045 E audit   : type=1400 msg=audit(1469604068.795:295): avc:  denied  { execmod } for  pid=7435 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 09:21:08.805  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:21:08.805  2045  2045 E audit   : type=1300 msg=audit(1469604068.795:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f02000 a1=51000 a2=5 a3=4 items=0 ppid=3433 ppcomm=adbd pid=7435 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 09:21:08.815  2045  2045 E audit   : type=1327 msg=audit(1469604068.795:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-27 09:21:08.815  2045  2045 E audit   : type=1320 msg=audit(1469604068.795:295): 
07-27 09:21:08.845  7435  7435 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 09:21:08.845  2045  2045 E audit   : type=1400 msg=audit(1469604068.845:296): avc:  denied  { execmod } for  pid=7435 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 09:21:08.855  7435  7435 D AndroidRuntime: CheckJNI is OFF
07-27 09:21:08.855  7435  7435 D AndroidRuntime: readGMSProperty: start
07-27 09:21:08.855  7435  7435 D AndroidRuntime: readGMSProperty: already setted!!
07-27 09:21:08.855  7435  7435 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 09:21:08.855  7435  7435 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 09:21:08.855  7435  7435 D AndroidRuntime: readGMSProperty: end
07-27 09:21:08.855  7435  7435 D AndroidRuntime: addProductProperty: start
07-27 09:21:08.855  2045  2045 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:21:08.855  2045  2045 E audit   : type=1300 msg=audit(1469604068.845:296): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f03000 a1=51000 a2=5 a3=4 items=0 ppid=3433 ppcomm=adbd pid=7435 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 09:21:08.865  7435  7435 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 09:21:08.865  7435  7435 W art     : af0a4000-b1fca000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-27 09:21:08.865  7435  7435 W art     : b1fca000-b4239000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-27 09:21:08.865  7435  7435 W art     : b4239000-b423a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-27 09:21:08.865  7435  7435 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 09:21:08.865  7435  7435 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-27 09:21:08.865  7435  7435 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-27 09:21:08.865  7435  7435 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-27 09:21:08.865  7435  7435 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-27 09:21:08.865  7435  7435 W art     : b47d5000-b47d8000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-27 09:21:08.865  7435  7435 W art     : b47d8000-b47d9000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-27 09:21:08.865  7435  7435 W art     : b47d9000-b47da000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-27 09:21:08.865  7435  7435 W art     : b47da000-b47db000 r--p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b47db000-b47fb000 r--s 00000000 00:0b 6714       /dev/__properties__
07-27 09:21:08.865  7435  7435 W art     : b47fb000-b520c000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-27 09:21:08.865  7435  7435 W art     : b520c000-b520d000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b520d000-b5256000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-27 09:21:08.865  7435  7435 W art     : b5256000-b5257000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-27 09:21:08.865  7435  7435 W art     : b5257000-b525f000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b525f000-b5260000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5260000-b5295000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-27 09:21:08.865  7435  7435 W art     : b5295000-b5296000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5296000-b5297000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-27 09:21:08.865  7435  7435 W art     : b5297000-b5298000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-27 09:21:08.865  7435  7435 W art     : b5298000-b52f0000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-27 09:21:08.865  7435  7435 W art     : b52f0000-b52f1000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b52f1000-b52f2000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-27 09:21:08.865  7435  7435 W art     : b52f2000-b52f3000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-27 09:21:08.865  7435  7435 W art     : b52f4000-b52fa000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 09:21:08.865  7435  7435 W art     : b52fa000-b52fb000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 09:21:08.865  7435  7435 W art     : b52fb000-b52fc000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 09:21:08.865  7435  7435 W art     : b52fc000-b52fe000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b52ff000-b5309000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 09:21:08.865  7435  7435 W art     : b5309000-b530c000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 09:21:08.865  7435  7435 W art     : b530c000-b530d000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 09:21:08.865  7435  7435 W art     : b530e000-b5325000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 09:21:08.865  7435  7435 W art     : b5325000-b5326000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5326000-b5327000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 09:21:08.865  7435  7435 W art     : b5327000-b5328000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 09:21:08.865  7435  7435 W art     : b5329000-b5333000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-27 09:21:08.865  7435  7435 W art     : b5333000-b5334000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-27 09:21:08.865  7435  7435 W art     : b5334000-b5335000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-27 09:21:08.865  7435  7435 W art     : b5335000-b5339000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 09:21:08.865  7435  7435 W art     : b5339000-b533a000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 09:21:08.865  7435  7435 W art     : b533a000-b533b000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 09:21:08.865  7435  7435 W art     : b533b000-b5351000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-27 09:21:08.865  7435  7435 W art     : b5351000-b5352000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-27 09:21:08.865  7435  7435 W art     : b5352000-b5353000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-27 09:21:08.865  7435  7435 W art     : b5353000-b5360000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-27 09:21:08.865  7435  7435 W art     : b5360000-b5361000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-27 09:21:08.865  7435  7435 W art     : b5361000-b5362000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-27 09:21:08.865  7435  7435 W art     : b5362000-b53c2000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-27 09:21:08.865  7435  7435 W art     : b53c2000-b53c5000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-27 09:21:08.865  7435  7435 W art     : b53c5000-b53c9000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b53c9000-b542a000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-27 09:21:08.865  7435  7435 W art     : b542a000-b542b000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-27 09:21:08.865  7435  7435 W art     : b542b000-b547a000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-27 09:21:08.865  7435  7435 W art     : b547a000-b547c000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-27 09:21:08.865  7435  7435 W art     : b547c000-b547d000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-27 09:21:08.865  7435  7435 W art     : b547d000-b547e000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b547e000-b5485000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 09:21:08.865  7435  7435 W art     : b5485000-b5486000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 09:21:08.865  7435  7435 W art     : b5486000-b5487000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
07-27 09:21:08.865  7435  7435 W art     : avc_common.so
07-27 09:21:08.865  7435  7435 W art     : b5488000-b548b000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 09:21:08.865  7435  7435 W art     : b548b000-b548c000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 09:21:08.865  7435  7435 W art     : b548c000-b548d000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
07-27 09:21:08.865  7435  7435 W art     : enc_common.so
07-27 09:21:08.865  7435  7435 W art     : b548e000-b5492000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-27 09:21:08.865  7435  7435 W art     : b5492000-b5493000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5493000-b5494000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-27 09:21:08.865  7435  7435 W art     : b5494000-b5495000 rw-p 00005000 b3:17 2510       /syste
07-27 09:21:08.865  7435  7435 W art     : m/lib/libpowermanager.so
07-27 09:21:08.865  7435  7435 W art     : b5496000-b54b3000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 09:21:08.865  7435  7435 W art     : b54b3000-b54b4000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 09:21:08.865  7435  7435 W art     : b54b4000-b54b5000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 09:21:08.865  7435  7435 W art     : b54b6000-b54bb000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 09:21:08.865  7435  7435 W art     : b54bb000-b54bc000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 09:21:08.865  7435  7435 W art     : b54bc000-b54bd000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 09:21:08.865  7435  7435 W art     : b54be000-b54ef000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 09:21:08.865  7435  7435 W art     : b54ef000-b54f2000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 09:21:08.865  7435  7435 W art     : b54f2000-b54f3000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 09:21:08.865  7435  7435 W art     : b54f4000-b552f000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-27 09:21:08.865  7435  7435 W art     : b552f000-b5530000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-27 09:21:08.865  7435  7435 W art     : b5530000-b5531000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-27 09:21:08.865  7435  7435 W art     : b5532000-b5539000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-27 09:21:08.865  7435  7435 W art     : b5539000-b553a000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b553a000-b553b000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-27 09:21:08.865  7435  7435 W art     : b553b000-b553c000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-27 09:21:08.865  7435  7435 W art     : b553c000-b553d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b553d000-b5554000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-27 09:21:08.865  7435  7435 W art     : b5554000-b5555000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5555000-b5558000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-27 09:21:08.865  7435  7435 W art     : b5558000-b5559000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-27 09:21:08.865  7435  7435 W art     : b5559000-b5578000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-27 09:21:08.865  7435  7435 W art     : b5578000-b5579000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-27 09:21:08.865  7435  7435 W art     : b5579000-b557a000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-27 09:21:08.865  7435  7435 W art     : b557a000-b55b8000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-27 09:21:08.865  7435  7435 W art     : b55b8000-b55b9000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b55b9000-b55bb000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-27 09:21:08.865  7435  7435 W art     : b55bb000-b55bc000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-27 09:21:08.865  7435  7435 W art     : b55bd000-b55c4000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 09:21:08.865  7435  7435 W art     : b55c4000-b55c5000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 09:21:08.865  7435  7435 W art     : b55c5000-b55c6000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 09:21:08.865  7435  7435 W art     : b55c7000-b55ca000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 09:21:08.865  7435  7435 W art     : b55ca000-b55cb000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 09:21:08.865  7435  7435 W art     : b55cb000-b55cc000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 09:21:08.865  7435  7435 W art     : b55cc000-b55d2000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 09:21:08.865  7435  7435 W art     : b55d2000-b55d3000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b55d3000-b55d4000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 09:21:08.865  7435  7435 W art     : b55d4000-b55d5000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 09:21:08.865  7435  7435 W art     : b55d5000-b55de000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-27 09:21:08.865  7435  7435 W art     : b55de000-b55df000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-27 09:21:08.865  7435  7435 W art     : b55df000-b55e0000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-27 09:21:08.865  7435  7435 W art     : b55e0000-b5671000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 09:21:08.865  7435  7435 W art     : b5671000-b5672000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5672000-b567d000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 09:21:08.865  7435  7435 W art     : b567d000-b567e000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 09:21:08.865  7435  7435 W art     : b567f000-b5691000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-27 09:21:08.865  7435  7435 W art     : b5691000-b5692000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-27 09:21:08.865  7435  7435 W art     : b5692000-b5693000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-27 09:21:08.865  7435  7435 W art     : b5694000-b5699000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-27 09:21:08.865  7435  7435 W art     : b5699000-b569a000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-27 09:21:08.865  7435  7435 W art     : b569a000-b569b000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-27 09:21:08.865  7435  7435 W art     : b569c000-b5709000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-27 09:21:08.865  7435  7435 W art     : b5709000-b570a000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b570a000-b570c000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-27 09:21:08.865  7435  7435 W art     : b570c000-b570d000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-27 09:21:08.865  7435  7435 W art     : b570d000-b570e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b570e000-b5715000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 09:21:08.865  7435  7435 W art     : b5715000-b5716000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 09:21:08.865  7435  7435 W art     : b5716000-b5717000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 09:21:08.865  7435  7435 W art     : b5718000-b5798000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 09:21:08.865  7435  7435 W art     : b5798000-b5799000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5799000-b579a000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 09:21:08.865  7435  7435 W art     : b579a000-b579b000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 09:21:08.865  7435  7435 W art     : b579b000-b57b2000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b57b2000-b57e9000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-27 09:21:08.865  7435  7435 W art     : ib/libqc-opt.so
07-27 09:21:08.865  7435  7435 W art     : b57e9000-b57ea000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 09:21:08.865  7435  7435 W art     : b57ea000-b57eb000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 09:21:08.865  7435  7435 W art     : b57eb000-b5807000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 09:21:08.865  7435  7435 W art     : b5807000-b5808000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 09:21:08.865  7435  7435 W art     : b5808000-b5809000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 09:21:08.865  7435  7435 W art     : b580a000-b586b000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-27 09:21:08.865  7435  7435 W art     : b586b000-b586d000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-27 09:21:08.865  7435  7435 W art     : b586d000-b586e000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-27 09:21:08.865  7435  7435 W art     : b586f000-b5896000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-27 09:21:08.865  7435  7435 W art     : b5896000-b5897000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5897000-b5898000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-27 09:21:08.865  7435  7435 W art     : b5898000-b5899000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-27 09:21:08.865  7435  7435 W art     : b589a000-b58a2000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 09:21:08.865  7435  7435 W art     : b58a2000-b58a4000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 09:21:08.865  7435  7435 W art     : b58a4000-b58a5000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 09:21:08.865  7435  7435 W art     : b58a6000-b58a9000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-27 09:21:08.865  7435  7435 W art     : b58a9000-b58aa000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-27 09:21:08.865  7435  7435 W art     : b58aa000-b58ab000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-27 09:21:08.865  7435  7435 W art     : b58ab000-b58af000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-27 09:21:08.865  7435  7435 W art     : b58af000-b58b0000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b58b0000-b58b1000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-27 09:21:08.865  7435  7435 W art     : b58b1000-b58b2000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-27 09:21:08.865  7435  7435 W art     : b58b2000-b58c2000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-27 09:21:08.865  7435  7435 W art     : b58c2000-b58c3000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-27 09:21:08.865  7435  7435 W art     : b58c3000-b58c4000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-27 09:21:08.865  7435  7435 W art     : b58c4000-b590a000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b590a000-b5913000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-27 09:21:08.865  7435  7435 W art     : b5913000-b5914000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-27 09:21:08.865  7435  7435 W art     : b5914000-b5915000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-27 09:21:08.865  7435  7435 W art     : b5916000-b591b000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-27 09:21:08.865  7435  7435 W art     : b591b000-b591c000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-27 09:21:08.865  7435  7435 W art     : b591c000-b591d000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-27 09:21:08.865  7435  7435 W art     : b591d000-b5920000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 09:21:08.865  7435  7435 W art     : b5920000-b5921000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5921000-b5922000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 09:21:08.865  7435  7435 W art     : b5922000-b5923000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 09:21:08.865  7435  7435 W art     : b5924000-b593c000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 09:21:08.865  7435  7435 W art     : b593c000-b593d000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b593d000-b593e000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 09:21:08.865  7435  7435 W art     : b593e000-b593f000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 09:21:08.865  7435  7435 W art     : b5940000-b5ada000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-27 09:21:08.865  7435  7435 W art     : b5ada000-b5adb000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5adb000-b5ae8000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-27 09:21:08.865  7435  7435 W art     : b5ae8000-b5ae9000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-27 09:21:08.865  7435  7435 W art     : b5ae9000-b5aed000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-27 09:21:08.865  7435  7435 W art     : b5aed000-b5aee000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5aee000-b5aef000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-27 09:21:08.865  7435  7435 W art     : b5aef000-b5af0000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-27 09:21:08.865  7435  7435 W art     : b5af0000-b5b03000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-27 09:21:08.865  7435  7435 W art     : b5b03000-b5b04000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-27 09:21:08.865  7435  7435 W art     : b5b04000-b5b05000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-27 09:21:08.865  7435  7435 W art     : b5b05000-b5b06000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:21:08.865  7435  7435 W art     : b5b06000-b5b51000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-27 09:21:08.865  7435  7435 W art     : b5b51000-b5b52000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-27 09:21:08.865  7435  7435 W art     : b5b52000-b5b53000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-27 09:21:08.865  7435  7435 W art     : b5b53000-b5b55000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5b56000-b5b67000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 09:21:08.865  7435  7435 W art     : b5b67000-b5b68000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5b68000-b5b69000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 09:21:08.865  7435  7435 W art     : b5b69000-b5b6a000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 09:21:08.865  7435  7435 W art     : b5b6b000-b5b75000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-27 09:21:08.865  7435  7435 W art     : b5b75000-b5b77000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-27 09:21:08.865  7435  7435 W art     : b5b77000-b5b78000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-27 09:21:08.865  7435  7435 W art     : b5b78000-b5b91000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-27 09:21:08.865  7435  7435 W art     : b5b91000-b5b92000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-27 09:21:08.865  7435  7435 W art     : b5b92000-b5b95000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-27 09:21:08.865  7435  7435 W art     : b5b95000-b5b99000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5b99000-b5c0d000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-27 09:21:08.865  7435  7435 W art     : b5c0d000-b5c0e000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5c0e000-b5c11000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-27 09:21:08.865  7435  7435 W art     : b5c11000-b5c12000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-27 09:21:08.865  7435  7435 W art     : b5c12000-b5c13000 r--p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5c13000-b5c16000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-27 09:21:08.865  7435  7435 W art     : b5c16000-b5c17000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-27 09:21:08.865  7435  7435 W art     : b5c17000-b5c18000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-27 09:21:08.865  7435  7435 W art     : b5c18000-b5c19000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5c19000-b5c1e000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 09:21:08.865  7435  7435 W art     : b5c1e000-b5c1f000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 09:21:08.865  7435  7435 W art     : b5c1f000-b5c20000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 09:21:08.865  7435  7435 W art     : b5c20000-b5c21000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5c21000-b5c24000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 09:21:08.865  7435  7435 W art     : b5c24000-b5c25000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 09:21:08.865  7435  7435 W art     : b5c25000-b5c26000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 09:21:08.865  7435  7435 W art     : b5c26000-b5c27000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5c27000-b5c2b000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-27 09:21:08.865  7435  7435 W art     : b5c2b000-b5c2c000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-27 09:21:08.865  7435  7435 W art     : b5c2c000-b5c2d000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-27 09:21:08.865  7435  7435 W art     : b5c2d000-b5c2e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:21:08.865  7435  7435 W art     : b5c2e000-b5c32000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 09:21:08.865  7435  7435 W art     : b5c32000-b5c33000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 09:21:08.865  7435  7435 W art     : b5c33000-b5c34000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 09:21:08.865  7435  7435 W art     : b5c34000-b5c35000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5c35000-b5c43000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-27 09:21:08.865  7435  7435 W art     : b5c43000-b5c44000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b5c44000-b5c45000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-27 09:21:08.865  7435  7435 W art     : b5c45000-b5c46000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-27 09:21:08.865  7435  7435 W art     : b5c46000-b5c50000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 09:21:08.865  7435  7435 W art     : b5c50000-b5c53000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 09:21:08.865  7435  7435 W art     : b5c53000-b5c54000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 09:21:08.865  7435  7435 W art     : b5c54000-b5c55000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5c55000-b5c5f000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-27 09:21:08.865  7435  7435 W art     : b5c5f000-b5c62000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-27 09:21:08.865  7435  7435 W art     : b5c62000-b5c63000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-27 09:21:08.865  7435  7435 W art     : b5c63000-b5c67000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-27 09:21:08.865  7435  7435 W art     : b5c67000-b5c68000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-27 09:21:08.865  7435  7435 W art     : b5c68000-b5c69000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-27 09:21:08.865  7435  7435 W art     : b5c69000-b5c6a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b5c6a000-b5c77000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-27 09:21:08.865  7435  7435 W art     : b5c77000-b5c79000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-27 09:21:08.865  7435  7435 W art     : b5c79000-b5c7a000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-27 09:21:08.865  7435  7435 W art     : b5c7a000-b608c000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-27 09:21:08.865  7435  7435 W art     : b608c000-b608d000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b608d000-b6096000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-27 09:21:08.865  7435  7435 W art     : b6096000-b609a000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-27 09:21:08.865  7435  7435 W art     : b609a000-b609b000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b609b000-b60a2000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-27 09:21:08.865  7435  7435 W art     : b60a2000-b60a3000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-27 09:21:08.865  7435  7435 W art     : b60a3000-b60a4000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-27 09:21:08.865  7435  7435 W art     : b60a4000-b60a5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b60a5000-b60c0000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-27 09:21:08.865  7435  7435 W art     : b60c0000-b60c1000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-27 09:21:08.865  7435  7435 W art     : b60c1000-b60c2000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-27 09:21:08.865  7435  7435 W art     : b60c2000-b60c3000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b60c3000-b610f000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 09:21:08.865  7435  7435 W art     : b610f000-b6110000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6110000-b6111000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 09:21:08.865  7435  7435 W art     : b6111000-b6112000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 09:21:08.865  7435  7435 W art     : b6112000-b6113000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6113000-b6117000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-27 09:21:08.865  7435  7435 W art     : b6117000-b6118000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6118000-b6119000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-27 09:21:08.865  7435  7435 W art     : b6119000-b611a000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-27 09:21:08.865  7435  7435 W art     : b611a000-b6152000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-27 09:21:08.865  7435  7435 W art     : b6152000-b6153000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-27 09:21:08.865  7435  7435 W art     : b6153000-b6154000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-27 09:21:08.865  7435  7435 W art     : b6154000-b6155000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6155000-b61f3000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-27 09:21:08.865  7435  7435 W art     : b61f3000-b61f4000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b61f4000-b6212000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-27 09:21:08.865  7435  7435 W art     : b6212000-b6213000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-27 09:21:08.865  7435  7435 W art     : b6213000-b6386000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-27 09:21:08.865  7435  7435 W art     : b6386000-b6391000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-27 09:21:08.865  7435  7435 W art     : b6391000-b6392000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-27 09:21:08.865  7435  7435 W art     : b6392000-b64a9000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-27 09:21:08.865  7435  7435 W art     : b64a9000-b64b4000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-27 09:21:08.865  7435  7435 W art     : b64b4000-b64b5000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-27 09:21:08.865  7435  7435 W art     : b64b5000-b64b9000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b64b9000-b64dd000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-27 09:21:08.865  7435  7435 W art     : b64dd000-b64df000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-27 09:21:08.865  7435  7435 W art     : b64df000-b64e0000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-27 09:21:08.865  7435  7435 W art     : b64e0000-b6586000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-27 09:21:08.865  7435  7435 W art     : b6586000-b6593000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-27 09:21:08.865  7435  7435 W art     : b6593000-b6594000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-27 09:21:08.865  7435  7435 W art     : b6594000-b6595000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6595000-b65e8000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-27 09:21:08.865  7435  7435 W art     : b65e8000-b65e9000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b65e9000-b65ea000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-27 09:21:08.865  7435  7435 W art     : b65ea000-b65eb000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-27 09:21:08.865  7435  7435 W art     : b65eb000-b65f0000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b65f0000-b6602000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-27 09:21:08.865  7435  7435 W art     : b6602000-b6603000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6603000-b6604000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-27 09:21:08.865  7435  7435 W art     : b6604000-b6605000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-27 09:21:08.865  7435  7435 W art     : b6605000-b660c000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 09:21:08.865  7435  7435 W art     : b660c000-b660d000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 09:21:08.865  7435  7435 W art     : b660d000-b660e000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 09:21:08.865  7435  7435 W art     : b660e000-b660f000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b660f000-b6612000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-27 09:21:08.865  7435  7435 W art     : b6612000-b6613000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-27 09:21:08.865  7435  7435 W art     : b6613000-b6614000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-27 09:21:08.865  7435  7435 W art     : b6614000-b6618000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-27 09:21:08.865  7435  7435 W art     : b6618000-b6619000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-27 09:21:08.865  7435  7435 W art     : b6619000-b661a000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-27 09:21:08.865  7435  7435 W art     : b661a000-b6628000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-27 09:21:08.865  7435  7435 W art     : b6628000-b6629000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6629000-b662a000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-27 09:21:08.865  7435  7435 W art     : b662a000-b662b000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-27 09:21:08.865  7435  7435 W art     : b662b000-b6634000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 09:21:08.865  7435  7435 W art     : b6634000-b6635000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 09:21:08.865  7435  7435 W art     : b6635000-b6636000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 09:21:08.865  7435  7435 W art     : b6636000-b669c000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-27 09:21:08.865  7435  7435 W art     : b669c000-b669d000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b669d000-b669f000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-27 09:21:08.865  7435  7435 W art     : b669f000-b66a8000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-27 09:21:08.865  7435  7435 W art     : b66a8000-b66ab000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b66ab000-b6742000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-27 09:21:08.865  7435  7435 W art     : b6742000-b6744000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-27 09:21:08.865  7435  7435 W art     : b6744000-b6745000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-27 09:21:08.865  7435  7435 W art     : b6745000-b6746000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6746000-b6a67000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-27 09:21:08.865  7435  7435 W art     : b6a67000-b6a68000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6a68000-b6a83000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-27 09:21:08.865  7435  7435 W art     : b6a83000-b6a87000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-27 09:21:08.865  7435  7435 W art     : b6a87000-b6a8c000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6a8c000-b6a94000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 09:21:08.865  7435  7435 W art     : b6a94000-b6a95000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 09:21:08.865  7435  7435 W art     : b6a95000-b6a96000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 09:21:08.865  7435  7435 W art     : b6a96000-b6ac4000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-27 09:21:08.865  7435  7435 W art     : b6ac4000-b6ac5000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6ac5000-b6acc000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-27 09:21:08.865  7435  7435 W art     : b6acc000-b6acd000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-27 09:21:08.865  7435  7435 W art     : b6acd000-b6b13000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-27 09:21:08.865  7435  7435 W art     : b6b13000-b6b14000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6b14000-b6b17000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-27 09:21:08.865  7435  7435 W art     : b6b17000-b6b18000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-27 09:21:08.865  7435  7435 W art     : b6b18000-b6b33000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-27 09:21:08.865  7435  7435 W art     : b6b33000-b6b37000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-27 09:21:08.865  7435  7435 W art     : b6b37000-b6b38000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-27 09:21:08.865  7435  7435 W art     : b6b38000-b6b85000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-27 09:21:08.865  7435  7435 W art     : b6b85000-b6b86000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6b86000-b6b92000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-27 09:21:08.865  7435  7435 W art     : b6b92000-b6b93000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-27 09:21:08.865  7435  7435 W art     : b6b93000-b6ba0000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-27 09:21:08.865  7435  7435 W art     : b6ba0000-b6ba1000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6ba1000-b6ba2000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-27 09:21:08.865  7435  7435 W art     : b6ba2000-b6ba3000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-27 09:21:08.865  7435  7435 W art     : b6ba3000-b6bab000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-27 09:21:08.865  7435  7435 W art     : b6bab000-b6bac000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6bac000-b6bad000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-27 09:21:08.865  7435  7435 W art     : b6bad000-b6bae000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-27 09:21:08.865  7435  7435 W art     : b6bae000-b6bb5000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-27 09:21:08.865  7435  7435 W art     : b6bb5000-b6bb6000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-27 09:21:08.865  7435  7435 W art     : b6bb6000-b6bb7000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-27 09:21:08.865  7435  7435 W art     : b6bb7000-b6bcb000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-27 09:21:08.865  7435  7435 W art     : b6bcb000-b6bcd000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-27 09:21:08.865  7435  7435 W art     : b6bcd000-b6bce000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-27 09:21:08.865  7435  7435 W art     : b6bce000-b6bf6000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-27 09:21:08.865  7435  7435 W art     : b6bf6000-b6bf8000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-27 09:21:08.865  7435  7435 W art     : b6bf8000-b6bf9000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-27 09:21:08.865  7435  7435 W art     : b6bf9000-b6bfc000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-27 09:21:08.865  7435  7435 W art     : b6bfc000-b6bfd000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-27 09:21:08.865  7435  7435 W art     : b6bfd000-b6bfe000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-27 09:21:08.865  7435  7435 W art     : b6bfe000-b6c07000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-27 09:21:08.865  7435  7435 W art     : b6c07000-b6c08000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-27 09:21:08.865  7435  7435 W art     : b6c08000-b6c09000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-27 09:21:08.865  7435  7435 W art     : b6c09000-b6c29000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-27 09:21:08.865  7435  7435 W art     : b6c29000-b6c2a000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-27 09:21:08.865  7435  7435 W art     : b6c2a000-b6c2b000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-27 09:21:08.865  7435  7435 W art     : b6c2b000-b6c9e000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-27 09:21:08.865  7435  7435 W art     : b6c9e000-b6ca2000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-27 09:21:08.865  7435  7435 W art     : b6ca2000-b6ca5000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-27 09:21:08.865  7435  7435 W art     : b6ca5000-b6caf000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6caf000-b6d37000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-27 09:21:08.865  7435  7435 W art     : b6d37000-b6d38000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6d38000-b6d3c000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-27 09:21:08.865  7435  7435 W art     : b6d3c000-b6d3d000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-27 09:21:08.865  7435  7435 W art     : b6d3d000-b6d3e000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6d3e000-b6d67000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-27 09:21:08.865  7435  7435 W art     : b6d67000-b6d68000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6d68000-b6d6b000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-27 09:21:08.865  7435  7435 W art     : b6d6b000-b6d6c000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-27 09:21:08.865  7435  7435 W art     : b6d6c000-b6e46000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 09:21:08.865  7435  7435 W art     : b6e46000-b6e4d000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 09:21:08.865  7435  7435 W art     : b6e4d000-b6e55000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 09:21:08.865  7435  7435 W art     : b6e55000-b6e56000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6e56000-b6e57000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:21:08.865  7435  7435 W art     : b6e57000-b6e58000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-27 09:21:08.865  7435  7435 W art     : b6e58000-b6e59000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6e59000-b6e5c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6e5c000-b6e81000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-27 09:21:08.865  7435  7435 W art     : b6e81000-b6e82000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6e82000-b6e89000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-27 09:21:08.865  7435  7435 W art     : b6e89000-b6e8a000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-27 09:21:08.865  7435  7435 W art     : b6e8a000-b6e91000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-27 09:21:08.865  7435  7435 W art     : b6e91000-b6e92000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-27 09:21:08.865  7435  7435 W art     : b6e92000-b6e93000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-27 09:21:08.865  7435  7435 W art     : b6e93000-b6e94000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6e94000-b6eac000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-27 09:21:08.865  7435  7435 W art     : b6eac000-b6ead000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6ead000-b6eae000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-27 09:21:08.865  7435  7435 W art     : b6eae000-b6eaf000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-27 09:21:08.865  7435  7435 W art     : b6eaf000-b6ebd000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-27 09:21:08.865  7435  7435 W art     : b6ebd000-b6ebe000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6ebe000-b6ebf000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-27 09:21:08.865  7435  7435 W art     : b6ebf000-b6ec0000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-27 09:21:08.865  7435  7435 W art     : b6ec0000-b6ec1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:21:08.865  7435  7435 W art     : b6ec1000-b6ec3000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6ec3000-b6ec4000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6ec4000-b6ec5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:21:08.865  7435  7435 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-27 09:21:08.865  7435  7435 W art     : b6ec6000-b6ec7000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:21:08.865  7435  7435 W art     : b6ec7000-b6ee7000 r--s 00000000 00:0b 6714       /dev/__properties__
07-27 09:21:08.865  7435  7435 W art     : b6ee7000-b6ee8000 r--p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6ee8000-b6ee9000 ---p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6ee9000-b6eeb000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-27 09:21:08.865  7435  7435 W art     : b6eeb000-b6eec000 r-xp 00000000 00:00 0          [sigpage]
07-27 09:21:08.865  7435  7435 W art     : b6eec000-b6f07000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-27 09:21:08.865  7435  7435 W art     : b6f07000-b6f08000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-27 09:21:08.865  7435  7435 W art     : b6f08000-b6f0a000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-27 09:21:08.865  7435  7435 W art     : b6f0a000-b6f0c000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : b6f0c000-b6f11000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-27 09:21:08.865  7435  7435 W art     : b6f11000-b6f12000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-27 09:21:08.865  7435  7435 W art     : b6f12000-b6f13000 rw-p 00000000 00:00 0 
07-27 09:21:08.865  7435  7435 W art     : bebc7000-bebe8000 rw-p 00000000 00:00 0          [stack]
07-27 09:21:08.865  7435  7435 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-27 09:21:08.875  2045  2045 E audit   : type=1327 msg=audit(1469604068.845:296): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-27 09:21:08.875  2045  2045 E audit   : type=1320 msg=audit(1469604068.845:296): 
07-27 09:21:08.915  7435  7435 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 09:21:08.955  7435  7435 I Radio-JNI: register_android_hardware_Radio DONE
07-27 09:21:08.965  7435  7435 E AffinityControl: AffinityControl: registerfunction enter
07-27 09:21:08.985  7435  7435 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 09:21:08.995   753   769 D PackageManager: START PACKAGE DELETE: observer{247974102}
07-27 09:21:08.995   753   769 D PackageManager: pkg{<packageName>}
07-27 09:21:08.995   753   769 D PackageManager: user{0}
07-27 09:21:08.995   753   769 D PackageManager: caller{2000}
07-27 09:21:08.995   753   769 D PackageManager: flags{2}
07-27 09:21:08.995   753   769 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-27 09:21:08.995   753   769 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-27 09:21:08.995   753   769 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-27 09:21:08.995   753   769 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-27 09:21:08.995   753   769 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-27 09:21:09.005   753   917 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-27 09:21:09.005   753   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-27 09:21:09.005   753   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-27 09:21:09.005   753   917 D ApplicationPolicy: getApplicationUninstallationEnabled
07-27 09:21:09.005   753   917 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-27 09:21:09.005   753   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-27 09:21:09.005   753   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-27 09:21:09.005   753   917 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-27 09:21:09.005   753   827 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-27 09:21:09.005   753   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-27 09:21:09.005   753   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-27 09:21:09.005   753   827 I ActivityManager: Killing 6359:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-27 09:21:09.005   753   827 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 09:21:09.005   753   827 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-27 09:21:09.015   753   827 D ActivityManager: mDVFSHelper.acquire()
07-27 09:21:09.015   753   917 D AASAinstall: there is not AASApackages.xml file
07-27 09:21:09.055   753  1747 D GraphicsStats: Buffer count: 4
07-27 09:21:09.055   753  1789 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5c5e757)
07-27 09:21:09.055   753  1747 I WindowState: WIN DEATH: Window{bdda4b4 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:21:09.055   294   328 I SurfaceFlinger: id=21 Removed NainActivit (6/8)
07-27 09:21:09.055   294  1507 I SurfaceFlinger: id=21 Removed NainActivit (-2/8)
07-27 09:21:09.065   753  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:21:09.065   753  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:21:09.065   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8b23a4
07-27 09:21:09.065   753  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:21:09.075   753  1747 D InputDispatcher: Focus left window: 6359
07-27 09:21:09.335   753   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-27 09:21:09.365   753   917 W PackageSettings: Skipping PackageSetting{a1a84f2 com.example.hello/10192} due to missing metadata
07-27 09:21:09.415   753   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-27 09:21:09.425   753   827 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-27 09:21:09.425   753   827 W PackageManager: Package com.test.thalitest is missing; assuming frozen

```
