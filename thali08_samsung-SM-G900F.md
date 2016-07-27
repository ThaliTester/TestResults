#### Test 78968685940d272_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
07-27 09:40:17.387   748  3604 D SSRM:n  : SIOP:: AP = 370, PST = 419, CUR = 450, LCD = 0
,--------- beginning of main
07-27 09:40:18.336  2417  2417 E audit   : type=1400 msg=audit(1469605218.336:284): avc:  denied  { execmod } for  pid=7062 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 09:40:18.336  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:18.346  2417  2417 E audit   : type=1300 msg=audit(1469605218.336:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4030000 a1=51000 a2=5 a3=4 items=0 ppid=3787 ppcomm=adbd pid=7062 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 09:40:18.346  2417  2417 E audit   : type=1327 msg=audit(1469605218.336:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 09:40:18.346  2417  2417 E audit   : type=1320 msg=audit(1469605218.336:284): 
07-27 09:40:18.416  2417  2417 E audit   : type=1400 msg=audit(1469605218.416:285): avc:  denied  { execmod } for  pid=7062 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 09:40:18.416  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:18.416  2417  2417 E audit   : type=1300 msg=audit(1469605218.416:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fef000 a1=51000 a2=5 a3=4 items=0 ppid=3787 ppcomm=adbd pid=7062 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 09:40:18.426  2417  2417 E audit   : type=1327 msg=audit(1469605218.416:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 09:40:18.426  2417  2417 E audit   : type=1320 msg=audit(1469605218.416:285): 
07-27 09:40:18.466  2417  2417 E audit   : type=1400 msg=audit(1469605218.466:286): avc:  denied  { execmod } for  pid=7062 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 09:40:18.466  7062  7062 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 09:40:18.466  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:18.466  2417  2417 E audit   : type=1300 msg=audit(1469605218.466:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff0000 a1=51000 a2=5 a3=4 items=0 ppid=3787 ppcomm=adbd pid=7062 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 09:40:18.466  2417  2417 E audit   : type=1327 msg=audit(1469605218.466:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-27 09:40:18.466  2417  2417 E audit   : type=1320 msg=audit(1469605218.466:286): 
07-27 09:40:18.466  7062  7062 D AndroidRuntime: CheckJNI is OFF
07-27 09:40:18.476  7062  7062 D AndroidRuntime: readGMSProperty: start
07-27 09:40:18.476  7062  7062 D AndroidRuntime: readGMSProperty: already setted!!
07-27 09:40:18.476  7062  7062 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 09:40:18.476  7062  7062 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 09:40:18.476  7062  7062 D AndroidRuntime: readGMSProperty: end
07-27 09:40:18.476  7062  7062 D AndroidRuntime: addProductProperty: start
07-27 09:40:18.476  7062  7062 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 09:40:18.476  7062  7062 W art     : af19f000-b20c5000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-27 09:40:18.476  7062  7062 W art     : b20c5000-b4334000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-27 09:40:18.476  7062  7062 W art     : b4334000-b4335000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-27 09:40:18.476  7062  7062 W art     : b4335000-b435e000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 09:40:18.476  7062  7062 W art     : b435e000-b4361000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-27 09:40:18.476  7062  7062 W art     : b4361000-b4362000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-27 09:40:18.476  7062  7062 W art     : b4362000-b4363000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-27 09:40:18.476  7062  7062 W art     : b4363000-b47b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-27 09:40:18.476  7062  7062 W art     : b47b1000-b47b2000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b47b2000-b47bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-27 09:40:18.476  7062  7062 W art     : b47bc000-b47bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-27 09:40:18.476  7062  7062 W art     : b47bd000-b47bf000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b47bf000-b47c0000 r--p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b47c0000-b48c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-27 09:40:18.476  7062  7062 W art     : b48c2000-b48c3000 r--p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b48c3000-b48e3000 r--s 00000000 00:0b 8198       /dev/__properties__
07-27 09:40:18.476  7062  7062 W art     : b48e3000-b52f4000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-27 09:40:18.476  7062  7062 W art     : b52f4000-b52f5000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b52f5000-b533e000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-27 09:40:18.476  7062  7062 W art     : b533e000-b533f000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-27 09:40:18.476  7062  7062 W art     : b533f000-b5347000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b5347000-b5348000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.476  7062  7062 W art     : b5348000-b537d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-27 09:40:18.476  7062  7062 W art     : b537d000-b537e000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b537e000-b537f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-27 09:40:18.476  7062  7062 W art     : b537f000-b5380000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-27 09:40:18.476  7062  7062 W art     : b5380000-b53d8000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-27 09:40:18.476  7062  7062 W art     : b53d8000-b53d9000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b53d9000-b53da000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-27 09:40:18.476  7062  7062 W art     : b53da000-b53db000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-27 09:40:18.476  7062  7062 W art     : b53dc000-b53e2000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 09:40:18.476  7062  7062 W art     : b53e2000-b53e3000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 09:40:18.476  7062  7062 W art     : b53e3000-b53e4000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 09:40:18.476  7062  7062 W art     : b53e4000-b53e6000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b53e7000-b53f1000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 09:40:18.476  7062  7062 W art     : b53f1000-b53f4000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 09:40:18.476  7062  7062 W art     : b53f4000-b53f5000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 09:40:18.476  7062  7062 W art     : b53f6000-b540d000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 09:40:18.476  7062  7062 W art     : b540d000-b540e000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b540e000-b540f000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 09:40:18.476  7062  7062 W art     : b540f000-b5410000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 09:40:18.476  7062  7062 W art     : b5411000-b541b000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-27 09:40:18.476  7062  7062 W art     : b541b000-b541c000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-27 09:40:18.476  7062  7062 W art     : b541c000-b541d000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-27 09:40:18.476  7062  7062 W art     : b541d000-b5421000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 09:40:18.476  7062  7062 W art     : b5421000-b5422000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 09:40:18.476  7062  7062 W art     : b5422000-b5423000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 09:40:18.476  7062  7062 W art     : b5423000-b5439000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-27 09:40:18.476  7062  7062 W art     : b5439000-b543a000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-27 09:40:18.476  7062  7062 W art     : b543a000-b543b000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-27 09:40:18.476  7062  7062 W art     : b543b000-b5448000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-27 09:40:18.476  7062  7062 W art     : b5448000-b5449000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-27 09:40:18.476  7062  7062 W art     : b5449000-b544a000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-27 09:40:18.476  7062  7062 W art     : b544a000-b54aa000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-27 09:40:18.476  7062  7062 W art     : b54aa000-b54ad000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-27 09:40:18.476  7062  7062 W art     : b54ad000-b54b1000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b54b1000-b5512000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-27 09:40:18.476  7062  7062 W art     : b5512000-b5513000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-27 09:40:18.476  7062  7062 W art     : b5513000-b5562000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-27 09:40:18.476  7062  7062 W art     : b5562000-b5564000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-27 09:40:18.476  7062  7062 W art     : b5564000-b5565000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-27 09:40:18.476  7062  7062 W art     : b5565000-b5566000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b5566000-b556d000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 09:40:18.476  7062  7062 W art     : b556d000-b556e000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 09:40:18.476  7062  7062 W art     : b556e000-b556f000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
07-27 09:40:18.476  7062  7062 W art     : avc_common.so
07-27 09:40:18.476  7062  7062 W art     : b5570000-b5573000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 09:40:18.476  7062  7062 W art     : b5573000-b5574000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 09:40:18.476  7062  7062 W art     : b5574000-b5575000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
07-27 09:40:18.476  7062  7062 W art     : enc_common.so
07-27 09:40:18.476  7062  7062 W art     : b5576000-b557a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-27 09:40:18.476  7062  7062 W art     : b557a000-b557b000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b557b000-b557c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-27 09:40:18.476  7062  7062 W art     : b557c000-b557d000 rw-p 00005000 b3:17 2510       /syste
07-27 09:40:18.476  7062  7062 W art     : m/lib/libpowermanager.so
07-27 09:40:18.476  7062  7062 W art     : b557e000-b559b000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 09:40:18.476  7062  7062 W art     : b559b000-b559c000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 09:40:18.476  7062  7062 W art     : b559c000-b559d000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 09:40:18.476  7062  7062 W art     : b559e000-b55a3000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 09:40:18.476  7062  7062 W art     : b55a3000-b55a4000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 09:40:18.476  7062  7062 W art     : b55a4000-b55a5000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 09:40:18.476  7062  7062 W art     : b55a6000-b55d7000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 09:40:18.476  7062  7062 W art     : b55d7000-b55da000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 09:40:18.476  7062  7062 W art     : b55da000-b55db000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 09:40:18.476  7062  7062 W art     : b55dc000-b5617000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-27 09:40:18.476  7062  7062 W art     : b5617000-b5618000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-27 09:40:18.476  7062  7062 W art     : b5618000-b5619000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-27 09:40:18.476  7062  7062 W art     : b561a000-b5621000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-27 09:40:18.476  7062  7062 W art     : b5621000-b5622000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b5622000-b5623000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-27 09:40:18.476  7062  7062 W art     : b5623000-b5624000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-27 09:40:18.476  7062  7062 W art     : b5624000-b5625000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.476  7062  7062 W art     : b5625000-b563c000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-27 09:40:18.476  7062  7062 W art     : b563c000-b563d000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b563d000-b5640000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-27 09:40:18.476  7062  7062 W art     : b5640000-b5641000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-27 09:40:18.476  7062  7062 W art     : b5641000-b5660000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-27 09:40:18.476  7062  7062 W art     : b5660000-b5661000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-27 09:40:18.476  7062  7062 W art     : b5661000-b5662000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-27 09:40:18.476  7062  7062 W art     : b5662000-b56a0000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-27 09:40:18.476  7062  7062 W art     : b56a0000-b56a1000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b56a1000-b56a3000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-27 09:40:18.476  7062  7062 W art     : b56a3000-b56a4000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-27 09:40:18.476  7062  7062 W art     : b56a5000-b56ac000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 09:40:18.476  7062  7062 W art     : b56ac000-b56ad000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 09:40:18.476  7062  7062 W art     : b56ad000-b56ae000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 09:40:18.476  7062  7062 W art     : b56af000-b56b2000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 09:40:18.476  7062  7062 W art     : b56b2000-b56b3000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 09:40:18.476  7062  7062 W art     : b56b3000-b56b4000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 09:40:18.476  7062  7062 W art     : b56b4000-b56ba000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 09:40:18.476  7062  7062 W art     : b56ba000-b56bb000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b56bb000-b56bc000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 09:40:18.476  7062  7062 W art     : b56bc000-b56bd000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 09:40:18.476  7062  7062 W art     : b56bd000-b56c6000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-27 09:40:18.476  7062  7062 W art     : b56c6000-b56c7000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-27 09:40:18.476  7062  7062 W art     : b56c7000-b56c8000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-27 09:40:18.476  7062  7062 W art     : b56c8000-b5759000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 09:40:18.476  7062  7062 W art     : b5759000-b575a000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b575a000-b5765000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 09:40:18.476  7062  7062 W art     : b5765000-b5766000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 09:40:18.476  7062  7062 W art     : b5767000-b5779000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-27 09:40:18.476  7062  7062 W art     : b5779000-b577a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-27 09:40:18.476  7062  7062 W art     : b577a000-b577b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-27 09:40:18.476  7062  7062 W art     : b577c000-b5781000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-27 09:40:18.476  7062  7062 W art     : b5781000-b5782000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-27 09:40:18.476  7062  7062 W art     : b5782000-b5783000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-27 09:40:18.476  7062  7062 W art     : b5784000-b57f1000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-27 09:40:18.476  7062  7062 W art     : b57f1000-b57f2000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b57f2000-b57f4000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-27 09:40:18.476  7062  7062 W art     : b57f4000-b57f5000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-27 09:40:18.476  7062  7062 W art     : b57f5000-b57f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.476  7062  7062 W art     : b57f6000-b57fd000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 09:40:18.476  7062  7062 W art     : b57fd000-b57fe000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 09:40:18.476  7062  7062 W art     : b57fe000-b57ff000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 09:40:18.476  7062  7062 W art     : b5800000-b5880000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 09:40:18.476  7062  7062 W art     : b5880000-b5881000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b5881000-b5882000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 09:40:18.476  7062  7062 W art     : b5882000-b5883000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 09:40:18.476  7062  7062 W art     : b5883000-b589a000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b589a000-b58d1000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-27 09:40:18.476  7062  7062 W art     : ib/libqc-opt.so
07-27 09:40:18.476  7062  7062 W art     : b58d1000-b58d2000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 09:40:18.476  7062  7062 W art     : b58d2000-b58d3000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 09:40:18.476  7062  7062 W art     : b58d3000-b58ef000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 09:40:18.476  7062  7062 W art     : b58ef000-b58f0000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 09:40:18.476  7062  7062 W art     : b58f0000-b58f1000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 09:40:18.476  7062  7062 W art     : b58f2000-b5953000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-27 09:40:18.476  7062  7062 W art     : b5953000-b5955000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-27 09:40:18.476  7062  7062 W art     : b5955000-b5956000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-27 09:40:18.476  7062  7062 W art     : b5957000-b597e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-27 09:40:18.476  7062  7062 W art     : b597e000-b597f000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b597f000-b5980000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-27 09:40:18.476  7062  7062 W art     : b5980000-b5981000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-27 09:40:18.476  7062  7062 W art     : b5982000-b598a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 09:40:18.476  7062  7062 W art     : b598a000-b598c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 09:40:18.476  7062  7062 W art     : b598c000-b598d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 09:40:18.476  7062  7062 W art     : b598e000-b5991000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-27 09:40:18.476  7062  7062 W art     : b5991000-b5992000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-27 09:40:18.476  7062  7062 W art     : b5992000-b5993000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-27 09:40:18.476  7062  7062 W art     : b5993000-b5997000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-27 09:40:18.476  7062  7062 W art     : b5997000-b5998000 ---p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b5998000-b5999000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-27 09:40:18.476  7062  7062 W art     : b5999000-b599a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-27 09:40:18.476  7062  7062 W art     : b599a000-b59aa000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-27 09:40:18.476  7062  7062 W art     : b59aa000-b59ab000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-27 09:40:18.476  7062  7062 W art     : b59ab000-b59ac000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-27 09:40:18.476  7062  7062 W art     : b59ac000-b59f2000 rw-p 00000000 00:00 0 
07-27 09:40:18.476  7062  7062 W art     : b59f2000-b59fb000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-27 09:40:18.476  7062  7062 W art     : b59fb000-b59fc000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-27 09:40:18.476  7062  7062 W art     : b59fc000-b59fd000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-27 09:40:18.486  7062  7062 W art     : b59fe000-b5a03000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-27 09:40:18.486  7062  7062 W art     : b5a03000-b5a04000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-27 09:40:18.486  7062  7062 W art     : b5a04000-b5a05000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-27 09:40:18.486  7062  7062 W art     : b5a05000-b5a08000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 09:40:18.486  7062  7062 W art     : b5a08000-b5a09000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5a09000-b5a0a000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 09:40:18.486  7062  7062 W art     : b5a0a000-b5a0b000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 09:40:18.486  7062  7062 W art     : b5a0c000-b5a24000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 09:40:18.486  7062  7062 W art     : b5a24000-b5a25000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5a25000-b5a26000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 09:40:18.486  7062  7062 W art     : b5a26000-b5a27000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 09:40:18.486  7062  7062 W art     : b5a28000-b5bc2000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-27 09:40:18.486  7062  7062 W art     : b5bc2000-b5bc3000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5bc3000-b5bd0000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-27 09:40:18.486  7062  7062 W art     : b5bd0000-b5bd1000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-27 09:40:18.486  7062  7062 W art     : b5bd1000-b5bd5000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-27 09:40:18.486  7062  7062 W art     : b5bd5000-b5bd6000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5bd6000-b5bd7000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-27 09:40:18.486  7062  7062 W art     : b5bd7000-b5bd8000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-27 09:40:18.486  7062  7062 W art     : b5bd8000-b5beb000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-27 09:40:18.486  7062  7062 W art     : b5beb000-b5bec000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-27 09:40:18.486  7062  7062 W art     : b5bec000-b5bed000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-27 09:40:18.486  7062  7062 W art     : b5bed000-b5bee000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:40:18.486  7062  7062 W art     : b5bee000-b5c39000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-27 09:40:18.486  7062  7062 W art     : b5c39000-b5c3a000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-27 09:40:18.486  7062  7062 W art     : b5c3a000-b5c3b000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-27 09:40:18.486  7062  7062 W art     : b5c3b000-b5c3d000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5c3e000-b5c4f000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 09:40:18.486  7062  7062 W art     : b5c4f000-b5c50000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5c50000-b5c51000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 09:40:18.486  7062  7062 W art     : b5c51000-b5c52000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 09:40:18.486  7062  7062 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-27 09:40:18.486  7062  7062 W art     : b5c5d000-b5c5f000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-27 09:40:18.486  7062  7062 W art     : b5c5f000-b5c60000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-27 09:40:18.486  7062  7062 W art     : b5c60000-b5c79000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-27 09:40:18.486  7062  7062 W art     : b5c79000-b5c7a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-27 09:40:18.486  7062  7062 W art     : b5c7a000-b5c7d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-27 09:40:18.486  7062  7062 W art     : b5c7d000-b5c81000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5c81000-b5cf5000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-27 09:40:18.486  7062  7062 W art     : b5cf5000-b5cf6000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5cf6000-b5cf9000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-27 09:40:18.486  7062  7062 W art     : b5cf9000-b5cfa000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-27 09:40:18.486  7062  7062 W art     : b5cfa000-b5cfb000 r--p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5cfb000-b5cfe000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-27 09:40:18.486  7062  7062 W art     : b5cfe000-b5cff000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-27 09:40:18.486  7062  7062 W art     : b5cff000-b5d00000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-27 09:40:18.486  7062  7062 W art     : b5d00000-b5d01000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b5d01000-b5d06000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 09:40:18.486  7062  7062 W art     : b5d06000-b5d07000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 09:40:18.486  7062  7062 W art     : b5d07000-b5d08000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 09:40:18.486  7062  7062 W art     : b5d08000-b5d09000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b5d09000-b5d0c000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 09:40:18.486  7062  7062 W art     : b5d0c000-b5d0d000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 09:40:18.486  7062  7062 W art     : b5d0d000-b5d0e000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 09:40:18.486  7062  7062 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b5d0f000-b5d13000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-27 09:40:18.486  7062  7062 W art     : b5d13000-b5d14000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-27 09:40:18.486  7062  7062 W art     : b5d14000-b5d15000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-27 09:40:18.486  7062  7062 W art     : b5d15000-b5d16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:40:18.486  7062  7062 W art     : b5d16000-b5d1a000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 09:40:18.486  7062  7062 W art     : b5d1a000-b5d1b000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 09:40:18.486  7062  7062 W art     : b5d1b000-b5d1c000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 09:40:18.486  7062  7062 W art     : b5d1c000-b5d1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b5d1d000-b5d2b000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-27 09:40:18.486  7062  7062 W art     : b5d2b000-b5d2c000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b5d2c000-b5d2d000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-27 09:40:18.486  7062  7062 W art     : b5d2d000-b5d2e000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-27 09:40:18.486  7062  7062 W art     : b5d2e000-b5d38000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 09:40:18.486  7062  7062 W art     : b5d38000-b5d3b000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 09:40:18.486  7062  7062 W art     : b5d3b000-b5d3c000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 09:40:18.486  7062  7062 W art     : b5d3c000-b5d3d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b5d3d000-b5d47000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-27 09:40:18.486  7062  7062 W art     : b5d47000-b5d4a000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-27 09:40:18.486  7062  7062 W art     : b5d4a000-b5d4b000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-27 09:40:18.486  7062  7062 W art     : b5d4b000-b5d4f000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-27 09:40:18.486  7062  7062 W art     : b5d4f000-b5d50000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-27 09:40:18.486  7062  7062 W art     : b5d50000-b5d51000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-27 09:40:18.486  7062  7062 W art     : b5d51000-b5d52000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b5d52000-b5d5f000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-27 09:40:18.486  7062  7062 W art     : b5d5f000-b5d61000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-27 09:40:18.486  7062  7062 W art     : b5d61000-b5d62000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-27 09:40:18.486  7062  7062 W art     : b5d62000-b6174000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-27 09:40:18.486  7062  7062 W art     : b6174000-b6175000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6175000-b617e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-27 09:40:18.486  7062  7062 W art     : b617e000-b6182000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-27 09:40:18.486  7062  7062 W art     : b6182000-b6183000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6183000-b618a000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-27 09:40:18.486  7062  7062 W art     : b618a000-b618b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-27 09:40:18.486  7062  7062 W art     : b618b000-b618c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-27 09:40:18.486  7062  7062 W art     : b618c000-b618d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b618d000-b61a8000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-27 09:40:18.486  7062  7062 W art     : b61a8000-b61a9000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-27 09:40:18.486  7062  7062 W art     : b61a9000-b61aa000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-27 09:40:18.486  7062  7062 W art     : b61aa000-b61ab000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b61ab000-b61f7000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 09:40:18.486  7062  7062 W art     : b61f7000-b61f8000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b61f8000-b61f9000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 09:40:18.486  7062  7062 W art     : b61f9000-b61fa000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 09:40:18.486  7062  7062 W art     : b61fa000-b61fb000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b61fb000-b61ff000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-27 09:40:18.486  7062  7062 W art     : b61ff000-b6200000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6200000-b6201000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-27 09:40:18.486  7062  7062 W art     : b6201000-b6202000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-27 09:40:18.486  7062  7062 W art     : b6202000-b623a000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-27 09:40:18.486  7062  7062 W art     : b623a000-b623b000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-27 09:40:18.486  7062  7062 W art     : b623b000-b623c000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-27 09:40:18.486  7062  7062 W art     : b623c000-b623d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b623d000-b62db000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-27 09:40:18.486  7062  7062 W art     : b62db000-b62dc000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b62dc000-b62fa000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-27 09:40:18.486  7062  7062 W art     : b62fa000-b62fb000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-27 09:40:18.486  7062  7062 W art     : b62fb000-b646e000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-27 09:40:18.486  7062  7062 W art     : b646e000-b6479000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-27 09:40:18.486  7062  7062 W art     : b6479000-b647a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-27 09:40:18.486  7062  7062 W art     : b647a000-b6591000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-27 09:40:18.486  7062  7062 W art     : b6591000-b659c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-27 09:40:18.486  7062  7062 W art     : b659c000-b659d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-27 09:40:18.486  7062  7062 W art     : b659d000-b65a1000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b65a1000-b65c5000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-27 09:40:18.486  7062  7062 W art     : b65c5000-b65c7000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-27 09:40:18.486  7062  7062 W art     : b65c7000-b65c8000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-27 09:40:18.486  7062  7062 W art     : b65c8000-b666e000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-27 09:40:18.486  7062  7062 W art     : b666e000-b667b000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-27 09:40:18.486  7062  7062 W art     : b667b000-b667c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-27 09:40:18.486  7062  7062 W art     : b667c000-b667d000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b667d000-b66d0000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-27 09:40:18.486  7062  7062 W art     : b66d0000-b66d1000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b66d1000-b66d2000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-27 09:40:18.486  7062  7062 W art     : b66d2000-b66d3000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-27 09:40:18.486  7062  7062 W art     : b66d3000-b66d8000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b66d8000-b66ea000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-27 09:40:18.486  7062  7062 W art     : b66ea000-b66eb000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b66eb000-b66ec000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-27 09:40:18.486  7062  7062 W art     : b66ec000-b66ed000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-27 09:40:18.486  7062  7062 W art     : b66ed000-b66f4000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 09:40:18.486  7062  7062 W art     : b66f4000-b66f5000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 09:40:18.486  7062  7062 W art     : b66f5000-b66f6000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 09:40:18.486  7062  7062 W art     : b66f6000-b66f7000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b66f7000-b66fa000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-27 09:40:18.486  7062  7062 W art     : b66fa000-b66fb000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-27 09:40:18.486  7062  7062 W art     : b66fb000-b66fc000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-27 09:40:18.486  7062  7062 W art     : b66fc000-b6700000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-27 09:40:18.486  7062  7062 W art     : b6700000-b6701000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-27 09:40:18.486  7062  7062 W art     : b6701000-b6702000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-27 09:40:18.486  7062  7062 W art     : b6702000-b6710000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-27 09:40:18.486  7062  7062 W art     : b6710000-b6711000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6711000-b6712000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-27 09:40:18.486  7062  7062 W art     : b6712000-b6713000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-27 09:40:18.486  7062  7062 W art     : b6713000-b671c000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 09:40:18.486  7062  7062 W art     : b671c000-b671d000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 09:40:18.486  7062  7062 W art     : b671d000-b671e000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 09:40:18.486  7062  7062 W art     : b671e000-b6784000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-27 09:40:18.486  7062  7062 W art     : b6784000-b6785000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6785000-b6787000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-27 09:40:18.486  7062  7062 W art     : b6787000-b6790000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-27 09:40:18.486  7062  7062 W art     : b6790000-b6793000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6793000-b682a000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-27 09:40:18.486  7062  7062 W art     : b682a000-b682c000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-27 09:40:18.486  7062  7062 W art     : b682c000-b682d000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-27 09:40:18.486  7062  7062 W art     : b682d000-b682e000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b682e000-b6b4f000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-27 09:40:18.486  7062  7062 W art     : b6b4f000-b6b50000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6b50000-b6b6b000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-27 09:40:18.486  7062  7062 W art     : b6b6b000-b6b6f000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-27 09:40:18.486  7062  7062 W art     : b6b6f000-b6b74000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6b74000-b6b7c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 09:40:18.486  7062  7062 W art     : b6b7c000-b6b7d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 09:40:18.486  7062  7062 W art     : b6b7d000-b6b7e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 09:40:18.486  7062  7062 W art     : b6b7e000-b6bac000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-27 09:40:18.486  7062  7062 W art     : b6bac000-b6bad000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6bad000-b6bb4000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-27 09:40:18.486  7062  7062 W art     : b6bb4000-b6bb5000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-27 09:40:18.486  7062  7062 W art     : b6bb5000-b6bfb000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-27 09:40:18.486  7062  7062 W art     : b6bfb000-b6bfc000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6bfc000-b6bff000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-27 09:40:18.486  7062  7062 W art     : b6bff000-b6c00000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-27 09:40:18.486  7062  7062 W art     : b6c00000-b6c1b000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-27 09:40:18.486  7062  7062 W art     : b6c1b000-b6c1f000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-27 09:40:18.486  7062  7062 W art     : b6c1f000-b6c20000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-27 09:40:18.486  7062  7062 W art     : b6c20000-b6c6d000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-27 09:40:18.486  7062  7062 W art     : b6c6d000-b6c6e000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6c6e000-b6c7a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-27 09:40:18.486  7062  7062 W art     : b6c7a000-b6c7b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-27 09:40:18.486  7062  7062 W art     : b6c7b000-b6c88000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-27 09:40:18.486  7062  7062 W art     : b6c88000-b6c89000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6c89000-b6c8a000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-27 09:40:18.486  7062  7062 W art     : b6c8a000-b6c8b000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-27 09:40:18.486  7062  7062 W art     : b6c8b000-b6c93000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-27 09:40:18.486  7062  7062 W art     : b6c93000-b6c94000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6c94000-b6c95000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-27 09:40:18.486  7062  7062 W art     : b6c95000-b6c96000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-27 09:40:18.486  7062  7062 W art     : b6c96000-b6c9d000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-27 09:40:18.486  7062  7062 W art     : b6c9d000-b6c9e000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-27 09:40:18.486  7062  7062 W art     : b6c9e000-b6c9f000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-27 09:40:18.486  7062  7062 W art     : b6c9f000-b6cb3000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-27 09:40:18.486  7062  7062 W art     : b6cb3000-b6cb5000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-27 09:40:18.486  7062  7062 W art     : b6cb5000-b6cb6000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-27 09:40:18.486  7062  7062 W art     : b6cb6000-b6cde000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-27 09:40:18.486  7062  7062 W art     : b6cde000-b6ce0000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-27 09:40:18.486  7062  7062 W art     : b6ce0000-b6ce1000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-27 09:40:18.486  7062  7062 W art     : b6ce1000-b6ce4000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-27 09:40:18.486  7062  7062 W art     : b6ce4000-b6ce5000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-27 09:40:18.486  7062  7062 W art     : b6ce5000-b6ce6000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-27 09:40:18.486  7062  7062 W art     : b6ce6000-b6cef000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-27 09:40:18.486  7062  7062 W art     : b6cef000-b6cf0000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-27 09:40:18.486  7062  7062 W art     : b6cf0000-b6cf1000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-27 09:40:18.486  7062  7062 W art     : b6cf1000-b6d11000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-27 09:40:18.486  7062  7062 W art     : b6d11000-b6d12000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-27 09:40:18.486  7062  7062 W art     : b6d12000-b6d13000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-27 09:40:18.486  7062  7062 W art     : b6d13000-b6d86000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-27 09:40:18.486  7062  7062 W art     : b6d86000-b6d8a000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-27 09:40:18.486  7062  7062 W art     : b6d8a000-b6d8d000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-27 09:40:18.486  7062  7062 W art     : b6d8d000-b6d97000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6d97000-b6e1f000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-27 09:40:18.486  7062  7062 W art     : b6e1f000-b6e20000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6e20000-b6e24000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-27 09:40:18.486  7062  7062 W art     : b6e24000-b6e25000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-27 09:40:18.486  7062  7062 W art     : b6e25000-b6e26000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6e26000-b6e4f000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-27 09:40:18.486  7062  7062 W art     : b6e4f000-b6e50000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6e50000-b6e53000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-27 09:40:18.486  7062  7062 W art     : b6e53000-b6e54000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-27 09:40:18.486  7062  7062 W art     : b6e54000-b6f2e000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 09:40:18.486  7062  7062 W art     : b6f2e000-b6f35000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 09:40:18.486  7062  7062 W art     : b6f35000-b6f3d000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 09:40:18.486  7062  7062 W art     : b6f3d000-b6f3e000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6f3e000-b6f3f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:40:18.486  7062  7062 W art     : b6f3f000-b6f40000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-27 09:40:18.486  7062  7062 W art     : b6f40000-b6f41000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b6f41000-b6f44000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b6f44000-b6f69000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-27 09:40:18.486  7062  7062 W art     : b6f69000-b6f6a000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6f6a000-b6f71000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-27 09:40:18.486  7062  7062 W art     : b6f71000-b6f72000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-27 09:40:18.486  7062  7062 W art     : b6f72000-b6f79000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-27 09:40:18.486  7062  7062 W art     : b6f79000-b6f7a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-27 09:40:18.486  7062  7062 W art     : b6f7a000-b6f7b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-27 09:40:18.486  7062  7062 W art     : b6f7b000-b6f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b6f7c000-b6f94000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-27 09:40:18.486  7062  7062 W art     : b6f94000-b6f95000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6f95000-b6f96000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-27 09:40:18.486  7062  7062 W art     : b6f96000-b6f97000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-27 09:40:18.486  7062  7062 W art     : b6f97000-b6fa5000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-27 09:40:18.486  7062  7062 W art     : b6fa5000-b6fa6000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6fa6000-b6fa7000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-27 09:40:18.486  7062  7062 W art     : b6fa7000-b6fa8000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-27 09:40:18.486  7062  7062 W art     : b6fa8000-b6fa9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:40:18.486  7062  7062 W art     : b6fa9000-b6fab000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b6fab000-b6fac000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b6fac000-b6fad000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 09:40:18.486  7062  7062 W art     : b6fad000-b6fae000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-27 09:40:18.486  7062  7062 W art     : b6fae000-b6faf000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 09:40:18.486  7062  7062 W art     : b6faf000-b6fcf000 r--s 00000000 00:0b 8198       /dev/__properties__
07-27 09:40:18.486  7062  7062 W art     : b6fcf000-b6fd0000 r--p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6fd0000-b6fd1000 ---p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6fd1000-b6fd3000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-27 09:40:18.486  7062  7062 W art     : b6fd3000-b6fd4000 r-xp 00000000 00:00 0          [sigpage]
07-27 09:40:18.486  7062  7062 W art     : b6fd4000-b6fef000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-27 09:40:18.486  7062  7062 W art     : b6fef000-b6ff0000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-27 09:40:18.486  7062  7062 W art     : b6ff0000-b6ff2000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-27 09:40:18.486  7062  7062 W art     : b6ff2000-b6ff4000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : b6ff4000-b6ff9000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-27 09:40:18.486  7062  7062 W art     : b6ff9000-b6ffa000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-27 09:40:18.486  7062  7062 W art     : b6ffa000-b6ffb000 rw-p 00000000 00:00 0 
07-27 09:40:18.486  7062  7062 W art     : becd9000-becfa000 rw-p 00000000 00:00 0          [stack]
07-27 09:40:18.486  7062  7062 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-27 09:40:18.526  7062  7062 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 09:40:18.576  7062  7062 I Radio-JNI: register_android_hardware_Radio DONE
07-27 09:40:18.586  7062  7062 E AffinityControl: AffinityControl: registerfunction enter
07-27 09:40:18.606  7062  7062 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 09:40:18.616   748  2105 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-27 09:40:18.626   748  2105 D ActivityManager: mDVFSHelper.acquire()
07-27 09:40:18.636   748  2105 V WindowManager: addAppToken: AppWindowToken{4c4f598 token=Token{677137b ActivityRecord{6373f0a u0 com.test.thalitest/.MainActivity t115}}} to stack=1 task=115 at 0
07-27 09:40:18.636   748   899 D SecWifiDisplayUtil: Metadata value : none
07-27 09:40:18.646   748   899 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8a8dfb0 V.E...... R.....ID 0,0-0,0}
07-27 09:40:18.646   748   899 D ISSUE_DEBUG: InputChannelName : 50fb5ae Starting com.test.thalitest
07-27 09:40:18.656   748  2105 I ActivityManager: Start proc 7077:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-27 09:40:18.656  7077  7077 E Zygote  : v2
07-27 09:40:18.656   748  2105 D InputDispatcher: Focused application set to: xxxx
07-27 09:40:18.656  7077  7077 I libpersona: KNOX_SDCARD checking this for 10004
07-27 09:40:18.656  7077  7077 I libpersona: KNOX_SDCARD not a persona
07-27 09:40:18.656   748  2105 D InputDispatcher: Focus left window: 3682
07-27 09:40:18.666   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
07-27 09:40:18.666  7077  7077 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:40:18.666  7077  7077 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:18.666   748  1316 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 09:40:18.666   748   859 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6d5820f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-27 09:40:18.666  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-27 09:40:18.666  7077  7077 E Zygote  : accessInfo : 0
07-27 09:40:18.666  7077  7077 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-27 09:40:18.666  7062  7062 D AndroidRuntime: Shutting down VM
07-27 09:40:18.686   748   899 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:748 uid:1000
07-27 09:40:18.686   748   899 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:40:18.686   748   899 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:748 uid:1000
07-27 09:40:18.686   748   899 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 09:40:18.686   748   899 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-27 09:40:18.696  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:40:18.696  7077  7077 D ActivityThread: Added TimaKeyStore provider
07-27 09:40:18.706   748  1758 V WindowOrientationListener: setCurrentAppOrientation :-1
07-27 09:40:18.706   748  1758 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-27 09:40:18.706   748   859 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{50fb5ae u0 d0 Starting com.test.thalitest}
07-27 09:40:18.716  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-27 09:40:18.716   748  1758 D ActivityManager:  Launching com.test.thalitest, updated priority
07-27 09:40:18.726   748   899 V WindowStateAnimator: Finishing drawing window Window{50fb5ae u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-27 09:40:18.736   748   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-27 09:40:18.736  2205  2219 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-27 09:40:18.736  1695  1695 V ActivityThread: updateVisibility : ActivityRecord{6f041fb token=android.os.BinderProxy@1309851 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 09:40:18.746   293  4832 D libEGL  : eglTerminate EGLDisplay = 0xb1d4064c
07-27 09:40:18.746   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbeeec364
07-27 09:40:18.746  1695  1875 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-27 09:40:18.746  1695  1695 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-27 09:40:18.756   293  4832 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
07-27 09:40:18.756   293   347 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
07-27 09:40:18.766   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb66ff64c
,07-27 09:40:18.766   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb66ff64c
07-27 09:40:18.766   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeeec3a4
07-27 09:40:18.776   293   347 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
07-27 09:40:18.776  3682  3682 V ActivityThread: updateVisibility : ActivityRecord{d4ada5 token=android.os.BinderProxy@3d1f817 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-27 09:40:18.776   293  4832 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
07-27 09:40:18.786   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeeec3a4
07-27 09:40:18.806   748  1316 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-27 09:40:18.806   293  1359 I SurfaceFlinger: id=20 Removed VSBConnecti (4/9)
07-27 09:40:18.806   293   357 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/9)
07-27 09:40:18.816  7077  7077 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-27 09:40:18.816  1695  1695 D Launcher: onTrimMemory. Level: 20
07-27 09:40:18.816   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeeec3a4
07-27 09:40:18.826   748  3604 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 09:40:18.836  7077  7077 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-27 09:40:18.836  7077  7077 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-27 09:40:18.856  7077  7077 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
07-27 09:40:18.886  7077  7077 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-27 09:40:18.896  7077  7077 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 09:40:18.906  7077  7077 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 2391-2394)
07-27 09:40:18.906  7077  7077 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 09:40:18.916   748   758 I art     : Background partial concurrent mark sweep GC freed 27697(1860KB) AllocSpace objects, 27(540KB) LOS objects, 27% free, 41MB/57MB, paused 2.361ms total 138.129ms
,07-27 09:40:18.926  7077  7077 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f653a1}
07-27 09:40:18.926  7077  7077 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 09:40:18.926  7077  7077 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 09:40:18.926  7077  7097 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-27 09:40:18.936  7077  7077 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-27 09:40:18.956  7077  7077 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-27 09:40:18.956  7077  7077 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-27 09:40:18.956  7077  7077 I Adreno-EGL: Build Date: 01/28/16 Thu
07-27 09:40:18.956  7077  7077 I Adreno-EGL: Local Branch: ss
07-27 09:40:18.956  7077  7077 I Adreno-EGL: Remote Branch: 
07-27 09:40:18.956  7077  7077 I Adreno-EGL: Local Patches: 
07-27 09:40:18.956  7077  7077 I Adreno-EGL: Reconstruct Branch: 
,07-27 09:40:18.956  7077  7077 D libEGL  : eglInitialize EGLDisplay = 0xbeaaedac
,07-27 09:40:18.986   748  1761 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,07-27 09:40:18.986   748  1761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-27 09:40:19.036  7077  7077 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 09:40:19.046  7077  7077 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 09:40:19.046  7077  7077 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-27 09:40:19.046  7077  7077 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 09:40:19.046  7077  7077 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 09:40:19.066  7077  7077 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-27 09:40:19.066  7077  7077 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-27 09:40:19.166  7077  7077 D SecWifiDisplayUtil: Metadata value : none
,07-27 09:40:19.166  7077  7077 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9f00b67 I.E...... R.....ID 0,0-0,0}
,07-27 09:40:19.176  7077  7121 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 09:40:19.176   748  1648 D ISSUE_DEBUG: InputChannelName : 7fa6ad3 com.test.thalitest/com.test.thalitest.MainActivity
,07-27 09:40:19.176   748  1693 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-27 09:40:19.176   748  1693 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 09:40:19.176   748   748 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 09:40:19.186   748   748 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-27 09:40:19.196  7077  7077 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7077
,07-27 09:40:19.196   748  2479 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7077 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 09:40:19.206   748  1325 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 09:40:19.206   748  1325 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 09:40:19.206   748  1325 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,07-27 09:40:19.206   748  1325 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:19.206   748  1325 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:19.206   748  1325 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:19.206   748  1325 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-27 09:40:19.206   748  1325 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:19.206   748  1325 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-27 09:40:19.206   748  1325 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 09:40:19.216  7077  7077 D SecWifiDisplayUtil: Metadata value : none
,07-27 09:40:19.216  7077  7097 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-27 09:40:19.226   293   293 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,07-27 09:40:19.236   748  1409 D InputDispatcher: Focus entered window: 7077
,07-27 09:40:19.236   748   899 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:748 uid:1000
07-27 09:40:19.236   748   899 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:40:19.236   748   899 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:748 uid:1000
07-27 09:40:19.236   748   899 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 09:40:19.236  7077  7121 D libEGL  : eglInitialize EGLDisplay = 0x9d7f27c4
07-27 09:40:19.236  7077  7121 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 09:40:19.276  7077  7077 V ActivityThread: updateVisibility : ActivityRecord{d6300fe token=android.os.BinderProxy@212b326 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-27 09:40:19.286  7077  7077 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-27 09:40:19.286  7077  7077 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 09:40:19.306   748  2105 V WindowStateAnimator: Finishing drawing window Window{7fa6ad3 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-27 09:40:19.306  7077  7077 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-27 09:40:19.306   748  1758 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-27 09:40:19.306   748   899 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 09:40:19.306   748   899 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms (total +665ms)
07-27 09:40:19.306   748   748 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 09:40:19.316   748   899 D ActivityManager: mDVFSHelper.release()
07-27 09:40:19.316   748   899 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6373f0a u0 com.test.thalitest/.MainActivity t115} time:162801
,07-27 09:40:19.316   748   899 D ViewRootImpl: #3 mView = null
,07-27 09:40:19.316   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbeeec364
,07-27 09:40:19.316   293   347 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
07-27 09:40:19.316   293   357 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,07-27 09:40:19.326  7077  7077 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 09:40:19.326   748   748 I KnoxTimeoutHandler: SD activityfalse
,07-27 09:40:19.326  7077  7077 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@212b326 time:162818
,07-27 09:40:19.336   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbeeec3a4
,07-27 09:40:19.356  7077  7129 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-27 09:40:19.356  7077  7129 D libEGL  : eglInitialize EGLDisplay = 0x9c2183ec
,07-27 09:40:19.396  7077  7077 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7077
,07-27 09:40:19.536  7077  7077 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 09:40:19.636  7077  7135 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1701971664
,07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb4344 added. We now have 1 listener(s)
,07-27 09:40:19.646  7077  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,07-27 09:40:19.646  7077  7135 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
07-27 09:40:19.646  7077  7135 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 09:40:19.646  7077  7135 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 09:40:19.646  7077  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44a6f3 added. We now have 1 listener(s)
07-27 09:40:19.646  7077  7135 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 09:40:19.656  7077  7135 D BluetoothAdapter: STATE_ON
,07-27 09:40:19.656  7077  7135 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-27 09:40:19.656  7077  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 09:40:19.656  7077  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 09:40:19.656  7077  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 09:40:19.656  7077  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 09:40:19.656  7077  7135 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 09:40:19.656  7077  7135 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,07-27 09:40:19.666  7077  7135 D BluetoothAdapter: STATE_ON
,07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:40:19.666  7077  7135 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 09:40:19.666  7077  7135 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-27 09:40:19.666  7077  7135 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 09:40:19.666  7077  7135 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 09:40:19.666  7077  7077 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:40:19.676  7077  7077 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:40:19.696  7077  7077 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 09:40:19.806   748  3607 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-27 09:40:20.186  1444  1444 D Recents : onTaskStackChanged
07-27 09:40:20.196  1444  1444 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
07-27 09:40:20.346  7077  7139 W jxcore-log: Initializing JXcore engine
07-27 09:40:20.346  7077  7139 W jxcore-log: JXcore engine is ready
07-27 09:40:20.396  2417  2417 E audit   : type=1400 msg=audit(1469605220.396:287): avc:  denied  { ioctl } for  pid=7139 comm="Thread-994" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 09:40:20.396  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:20.396  2417  2417 E audit   : type=1300 msg=audit(1469605220.396:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=99cdf3c8 items=0 ppid=353 ppcomm=main pid=7139 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-994" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 09:40:20.396  2417  2417 E audit   : type=1327 msg=audit(1469605220.396:287): proctitle="com.test.thalitest"
07-27 09:40:20.396  2417  2417 E audit   : type=1320 msg=audit(1469605220.396:287): 
07-27 09:40:20.396  2417  2417 E audit   : type=1400 msg=audit(1469605220.396:288): avc:  denied  { ioctl } for  pid=7139 comm="Thread-994" path="socket:[40628]" dev="sockfs" ino=40628 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-27 09:40:20.396  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:20.396  2417  2417 E audit   : type=1300 msg=audit(1469605220.396:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=2 a3=99cdf3c8 items=0 ppid=353 ppcomm=main pid=7139 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-994" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 09:40:20.396  2417  2417 E audit   : type=1327 msg=audit(1469605220.396:288): proctitle="com.test.thalitest"
07-27 09:40:20.396  2417  2417 E audit   : type=1320 msg=audit(1469605220.396:288): 
07-27 09:40:20.416  7077  7139 W jxcore-log: Starting JXcore engine
07-27 09:40:20.496  7077  7139 W jxcore-log: Platform android
07-27 09:40:20.496  7077  7139 W jxcore-log: 
07-27 09:40:20.496  7077  7139 W jxcore-log: Process ARCH arm
07-27 09:40:20.496  7077  7139 W jxcore-log: 
07-27 09:40:20.656  7077  7139 I jxcore-log: JXcore Cordova bridge is ready!
07-27 09:40:20.656  7077  7139 I jxcore-log: 
07-27 09:40:20.656  7077  7139 W jxcore-log: JXcore engine is started
07-27 09:40:20.666  7077  7135 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 09:40:20.666  7077  7077 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 09:40:21.686   748  1358 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/115_task.xml.bak
,07-27 09:40:23.776   748  3604 D PowerManagerService: [api] setMasterBrightnessLimit : minBrightnss : -1  maxBrightness : 255 (uid: 1000 pid: 748)
,07-27 09:40:23.776   748  3604 D PowerManagerService: mDisplayReady: false
07-27 09:40:23.776   748   903 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-27 09:40:23.776   748   903 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-27 09:40:23.776   748   903 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,07-27 09:40:23.776   748   903 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ 255))
07-27 09:40:23.776   748   903 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,07-27 09:40:23.776   748  3604 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1096 com.android.server.ssrm.R.c:-1 com.android.server.ssrm.at.dT:-1 com.android.server.ssrm.at.dS:-1 com.android.server.ssrm.at.run:-1 
07-27 09:40:23.776   748   903 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-27 09:40:23.776   748   903 D PowerManagerService: mDisplayReady: true
07-27 09:40:23.776   748   903 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,07-27 09:40:23.786   748   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8cc3b7d u0 com.sec.intent.action.MAX_BRIGHTNESS_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8864ee6 5071:com.android.settings/1000}
,07-27 09:40:24.376   748  1404 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:40:24.376   748  1404 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 328, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 09:40:24.376   748  1404 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-27 09:40:24.376   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:40:24.376   748  1404 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 748) 
07-27 09:40:24.376   748  1404 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
07-27 09:40:24.376   748   748 I MotionRecognitionService: Plugged
07-27 09:40:24.376   748   748 D MotionRecognitionService:   cableConnection= 1
07-27 09:40:24.376   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:40:24.376   748   748 D MotionRecognitionService: skip setTransmitPower. 
07-27 09:40:24.376  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:24.376  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:24.376  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:40:24.376   748  1404 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
07-27 09:40:24.376   748  1404 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
07-27 09:40:24.376  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:40:24.386  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:40:24.386  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:40:24.396   748  1404 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-27 09:40:24.396   748  1404 D BatteryService: turn on LED for fully charged
07-27 09:40:24.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:24.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:24.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:24.756   748  1216 E LightSensor: RED : 1, GREEN : 1, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 8282.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=2, cp1=4, cpl=3202560
07-27 09:40:24.766   748   911 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-27 09:40:24.766   748   911 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
07-27 09:40:24.766   748   911 D SensorManager: unregisterListener ::   
07-27 09:40:24.766   748   911 D lights  : led_pattern : 5 +
07-27 09:40:24.776   748   911 D lights  : led_pattern : 5 -
07-27 09:40:24.776   748   911 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:40:24.776   748   911 V AlarmManager:  remove PendingIntent] PendingIntent{74e4d44: PendingIntentRecord{a7caf62 android broadcastIntent}}
07-27 09:40:24.836   748  3604 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:40:27.436   748  3604 D SSRM:n  : SIOP:: AP = 410, PST = 414, CUR = 450, LCD = 0
,07-27 09:40:28.696   748   941 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 09:40:28.716   748   941 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-27 09:40:29.236   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:40:29.236   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:40:29.236   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:40:29.256   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:40:30.866  7077  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 09:40:30.866  7077  7139 I jxcore-log: 
,07-27 09:40:30.876  7077  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 09:40:30.876  7077  7139 I jxcore-log: 
,07-27 09:40:30.876  7077  7139 D BluetoothAdapter: STATE_ON
,07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:40:30.876  7077  7139 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 09:40:30.876  7077  7139 D BluetoothAdapter: STATE_ON
,07-27 09:40:30.886  7077  7139 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 09:40:30.886  7077  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 09:40:30.886  7077  7139 I jxcore-log: 
,07-27 09:40:30.886  7077  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 09:40:30.886  7077  7139 I jxcore-log: 
,07-27 09:40:31.246  7077  7139 I jxcore-log: Unit Test app is loaded
07-27 09:40:31.246  7077  7139 I jxcore-log: 
,07-27 09:40:31.246  7077  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 09:40:31.246  7077  7139 I jxcore-log: 
,07-27 09:40:31.256  7077  7139 I jxcore-log: My device name is: samsung-SM-G900F
07-27 09:40:31.256  7077  7139 I jxcore-log: 
,07-27 09:40:31.256  7077  7077 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 09:40:31.256  7077  7139 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 09:40:31.256  7077  7139 I jxcore-log: 
,07-27 09:40:34.446   748  1404 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:40:34.446   748  1404 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 328, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-27 09:40:34.446   748  1404 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-27 09:40:34.446   748  1404 D BatteryService: stay LED for fully charged
07-27 09:40:34.446   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:40:34.446   748   748 I MotionRecognitionService: Plugged
07-27 09:40:34.446   748   748 D MotionRecognitionService:   cableConnection= 1
07-27 09:40:34.446   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:40:34.446   748   748 D MotionRecognitionService: skip setTransmitPower. 
07-27 09:40:34.446  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:34.446  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:34.446  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:40:34.456  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:40:34.456  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:34.466  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:34.466  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:34.466  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:35.256  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 09:40:35.256  7077  7139 I jxcore-log: 
,07-27 09:40:35.666  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 09:40:35.666  7077  7139 I jxcore-log: 
,07-27 09:40:35.686  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 09:40:35.686  7077  7139 I jxcore-log: 
,07-27 09:40:35.696  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 09:40:35.696  7077  7139 I jxcore-log: 
,07-27 09:40:35.706  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 09:40:35.706  7077  7139 I jxcore-log: 
,07-27 09:40:35.716  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 09:40:35.716  7077  7139 I jxcore-log: 
,07-27 09:40:36.756  2011  3284 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:40:37.306   748  1551 E Watchdog: !@Sync 5 [07-27 09:40:37.322]
,07-27 09:40:37.486   748  3604 D SSRM:n  : SIOP:: AP = 410, PST = 409, CUR = 450, LCD = 0
,07-27 09:40:37.486   748  3604 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,07-27 09:40:37.496  2720  2720 D ContentApp:  LEVEL : -1
,07-27 09:40:37.516   748   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c39a72 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3389de9 6373:com.sec.android.app.videoplayer/u0a53}
,07-27 09:40:37.516  6373  6373 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-27 09:40:37.516  6373  6373 D TranscodeReceiver:  SIOP_LEVEL: -1
,07-27 09:40:37.586   748  3607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-27 09:40:37.586   748   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{52c5d35 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b265b79 6507:com.samsung.android.sm.provider/1000}
,07-27 09:40:37.676   748  3607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-27 09:40:37.676   748   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8aa333b u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b265b79 6507:com.samsung.android.sm.provider/1000}
,07-27 09:40:37.736  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 09:40:37.736  7077  7139 I jxcore-log: 
,07-27 09:40:37.746  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 09:40:37.746  7077  7139 I jxcore-log: 
,07-27 09:40:37.746  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 09:40:37.746  7077  7139 I jxcore-log: 
,07-27 09:40:37.906  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 09:40:37.906  7077  7139 I jxcore-log: 
,07-27 09:40:38.736  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 09:40:38.736  7077  7139 I jxcore-log: 
,07-27 09:40:38.786  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 09:40:38.786  7077  7139 I jxcore-log: 
,07-27 09:40:38.796  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 09:40:38.796  7077  7139 I jxcore-log: 
,07-27 09:40:38.996  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 09:40:38.996  7077  7139 I jxcore-log: 
,07-27 09:40:39.016  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 09:40:39.016  7077  7139 I jxcore-log: 
,07-27 09:40:39.026  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 09:40:39.026  7077  7139 I jxcore-log: 
,07-27 09:40:39.026  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 09:40:39.026  7077  7139 I jxcore-log: 
,07-27 09:40:39.046  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 09:40:39.046  7077  7139 I jxcore-log: 
,07-27 09:40:39.066  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 09:40:39.066  7077  7139 I jxcore-log: 
,07-27 09:40:39.156  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 09:40:39.156  7077  7139 I jxcore-log: 
,07-27 09:40:39.156  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 09:40:39.156  7077  7139 I jxcore-log: 
,07-27 09:40:39.186  7077  7139 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 09:40:39.186  7077  7139 I jxcore-log: 
,07-27 09:40:39.196  7077  7139 D BluetoothAdapter: STATE_ON
,07-27 09:40:39.196  7077  7139 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 09:40:39.196  7077  7139 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 09:40:39.196  7077  7139 I jxcore-log: 
,07-27 09:40:44.536   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:40:44.546   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 328, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:40:44.546   748  2105 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:40:44.546   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:40:44.566   748   748 I MotionRecognitionService: Plugged
,07-27 09:40:44.566   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:40:44.566   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:40:44.566   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:40:44.576   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:40:44.576   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:40:44.576  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:40:44.576  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:40:44.576  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:40:44.596  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:40:44.596  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:44.606  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:44.606  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:44.606  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:47.566   748  3604 D SSRM:n  : SIOP:: AP = 390, PST = 405, CUR = 450, LCD = 0
,07-27 09:40:49.256   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:40:54.626   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:40:54.626   748  2476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 328, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:40:54.636   748  2476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:40:54.636   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:40:54.646   748   748 I MotionRecognitionService: Plugged
,07-27 09:40:54.646   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:40:54.656   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:40:54.656   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:40:54.656   748  2476 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:40:54.666   748  2476 D BatteryService: stay LED for fully charged
,07-27 09:40:54.676  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:40:54.676  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:40:54.676  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:40:54.686  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:40:54.686  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:54.706  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:54.706  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:54.706  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:57.636   748  3604 D SSRM:n  : SIOP:: AP = 370, PST = 399, CUR = 450, LCD = 0
,07-27 09:41:04.706   748  1486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:41:04.716   748  1486 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 327, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:41:04.726   748  1486 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:41:04.726   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:41:04.736   748   748 I MotionRecognitionService: Plugged
,07-27 09:41:04.736   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:41:04.746   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:41:04.746   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:04.756   748  1486 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 40ms
,07-27 09:41:04.756   748  1486 D BatteryService: stay LED for fully charged
,07-27 09:41:04.766  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:04.766  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:04.776  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:04.786  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:41:04.786  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:04.796  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:04.796  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:04.796  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:07.306   748  1551 E Watchdog: !@Sync 6 [07-27 09:41:07.324]
,07-27 09:41:07.696   748  3604 D SSRM:n  : SIOP:: AP = 350, PST = 391, CUR = 450, LCD = 0
,07-27 09:41:08.046  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:41:09.266   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:41:14.806   748  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:41:17.756   748  3604 D SSRM:n  : SIOP:: AP = 340, PST = 383, CUR = 450, LCD = 0
,07-27 09:41:24.896   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:41:24.896   748  1598 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 327, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:41:24.906   748  1598 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:41:24.906   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:41:24.916   748   748 I MotionRecognitionService: Plugged
,07-27 09:41:24.916   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:41:24.926   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:41:24.926   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:24.926  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:24.926  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:24.926  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:24.926   748  1598 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:41:24.936   748  1598 D BatteryService: stay LED for fully charged
,07-27 09:41:24.946  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:41:24.946  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:24.956  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:24.956  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:24.956  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:27.816   748  3604 D SSRM:n  : SIOP:: AP = 340, PST = 376, CUR = 450, LCD = 0
,07-27 09:41:29.276   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:41:34.986   748  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:41:34.996   748  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:41:34.996   748  1693 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:41:34.996   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:41:35.006   748   748 I MotionRecognitionService: Plugged
,07-27 09:41:35.016   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:41:35.016   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:41:35.016   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:35.026   748  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:41:35.026   748  1693 D BatteryService: stay LED for fully charged
,07-27 09:41:35.026  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:35.026  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:35.026  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:35.046  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:41:35.046  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:35.056  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:35.056  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:35.056  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:37.316   748  1551 E Watchdog: !@Sync 7 [07-27 09:41:37.331]
,07-27 09:41:37.876   748  3604 D SSRM:n  : SIOP:: AP = 340, PST = 370, CUR = 450, LCD = 0
,07-27 09:41:45.056   748  1409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:41:45.056   748  1409 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:41:45.056   748  1409 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:41:45.056   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:41:45.066   748   748 I MotionRecognitionService: Plugged
,07-27 09:41:45.066   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:41:45.066   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:41:45.066   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:45.066   748  1409 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
,07-27 09:41:45.076   748  1409 D BatteryService: stay LED for fully charged
,07-27 09:41:45.076  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:45.076  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:45.076  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:45.106  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:41:45.106  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:45.106  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:45.106  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:45.106  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:47.926   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 365, CUR = 450, LCD = 0
,07-27 09:41:49.276   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:41:55.146   748  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:41:55.156   748  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:41:55.156   748  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:41:55.156   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:41:55.176   748   748 I MotionRecognitionService: Plugged
,07-27 09:41:55.176   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:41:55.176   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:41:55.176   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:55.186   748  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:41:55.186   748  1648 D BatteryService: stay LED for fully charged
,07-27 09:41:55.196  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:55.196  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:41:55.196  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:55.226  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:41:55.226  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:55.226  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:55.226  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:55.226  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:57.986   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 361, CUR = 450, LCD = 0
,07-27 09:42:05.236   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:42:07.326   748  1551 E Watchdog: !@Sync 8 [07-27 09:42:07.337]
,07-27 09:42:08.046   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 353, CUR = 450, LCD = 0
,07-27 09:42:08.076  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:42:08.246  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 8 size : 2Kb duration : 164ms lastUpdatedAfter : 161507ms
,07-27 09:42:09.276   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:42:15.326   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:42:15.326   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:42:15.336   748  2105 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:42:15.336   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:42:15.346   748   748 I MotionRecognitionService: Plugged
,07-27 09:42:15.346   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:42:15.356   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:42:15.356   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:15.356   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:42:15.366   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:42:15.376  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:42:15.376  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:15.376  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:15.386  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:42:15.386  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:15.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:15.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:15.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:18.106   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 345, CUR = 450, LCD = 0
,07-27 09:42:25.416   748   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:42:25.416   748   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:42:25.426   748   762 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:42:25.426   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:42:25.436   748   748 I MotionRecognitionService: Plugged
,07-27 09:42:25.436   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:42:25.446   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:42:25.446   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:25.456   748   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:42:25.456   748   762 D BatteryService: stay LED for fully charged
,07-27 09:42:25.466  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:42:25.466  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:42:25.476  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:25.486  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:42:25.486  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:25.496  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:25.496  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:25.496  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:28.166   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 339, CUR = 450, LCD = 0
,07-27 09:42:29.286   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:42:35.496   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:42:37.326   748  1551 E Watchdog: !@Sync 9 [07-27 09:42:37.341]
,07-27 09:42:38.226   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 335, CUR = 450, LCD = 0
,07-27 09:42:45.586   748  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:42:45.596   748  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:42:45.596   748  1648 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:42:45.596   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:42:45.616   748   748 I MotionRecognitionService: Plugged
,07-27 09:42:45.616   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:42:45.616   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:42:45.616   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:45.626   748  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:42:45.626   748  1648 D BatteryService: stay LED for fully charged
,07-27 09:42:45.626  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:42:45.626  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:45.626  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:45.646  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:42:45.646  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:45.656  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:45.656  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:45.656  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:48.286   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 333, CUR = 450, LCD = 0
,07-27 09:42:49.296   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:42:52.096   748  1227 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:42:52.116   748  1226 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:42:52.116   748  1227 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:42:52.126   748  1227 I TLC_TIMA_PKM_initialize: initializing...
,07-27 09:42:52.126   748  1227 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-27 09:42:52.126   748  1227 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-27 09:42:52.136   748  1227 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-27 09:42:52.136   748  1227 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-27 09:42:52.136   748  1227 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-27 09:42:52.136   748  1227 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-27 09:42:52.136   748  1227 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-27 09:42:52.146   748  1227 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-27 09:42:52.146   748  1227 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 09:42:52.186   748  1227 D QSEECOMAPI: : Loaded image: APP id = 4
,07-27 09:42:52.196   748  1227 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-27 09:42:52.206   748  1227 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-27 09:42:55.536   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:42:55.546   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:42:55.556   748  1227 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:42:55.556   748  1227 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:42:55.676   748  2479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:42:55.686   748  2479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:42:55.686   748  2479 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:42:55.686   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:42:55.706   748   748 I MotionRecognitionService: Plugged
,07-27 09:42:55.706   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:42:55.706   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:42:55.706   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:55.716   748  2479 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-27 09:42:55.716   748  2479 D BatteryService: stay LED for fully charged
,07-27 09:42:55.726  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:42:55.726  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:42:55.726  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:55.736  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:42:55.736  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:55.746  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:55.746  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:55.746  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:58.346   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 332, CUR = 450, LCD = 0
,07-27 09:42:59.986   748  1233 V AlarmManager: Expired Alarm result :8
,07-27 09:42:59.986   748  1233 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=323464 batch.start=331282
,07-27 09:43:00.006  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:43:00.006  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 09:43:00.006  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:43:00.076  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:43:00.086  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:43:00.096  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.096  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.096  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.096  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.106  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.106  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.116  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.166  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:07.336   748  1551 E Watchdog: !@Sync 10 [07-27 09:43:07.351]
,07-27 09:43:07.816   748  1233 V AlarmManager: Expired Alarm result :4
,07-27 09:43:07.876  1540  1540 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 09:43:07.876  1540  1540 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-27 09:43:07.896   748  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:07.896   748  1758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:43:07.896   748  1758 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-27 09:43:07.896   748  1758 D BatteryService: stay LED for fully charged
,07-27 09:43:07.906  1540  1540 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 09:43:07.926   748  1233 I ActivityManager: Start proc 7190:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-27 09:43:07.936   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:07.946  7190  7190 E Zygote  : v2
,07-27 09:43:07.946  7190  7190 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:43:07.946  7190  7190 I libpersona: KNOX_SDCARD not a persona
,07-27 09:43:07.946  7190  7190 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:43:07.946  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:43:07.946  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:07.946  7190  7190 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:43:07.946  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:07.956  7190  7190 E Zygote  : accessInfo : 0
,07-27 09:43:07.966  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:43:07.966  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:07.966   748   748 I MotionRecognitionService: Plugged
,07-27 09:43:07.966   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:43:07.966   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:07.966   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:07.976  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:07.976  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:07.976  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:07.996   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:43:07.996   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:43:07.996   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:43:08.006  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:43:08.006  7190  7190 D ActivityThread: Added TimaKeyStore provider
,07-27 09:43:08.026  7190  7190 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-27 09:43:08.036  7190  7190 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-27 09:43:08.076   748  1409 I ActivityManager: Killing 5582:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,07-27 09:43:08.096   748  2105 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,07-27 09:43:08.346  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:43:08.406   748  3604 D SSRM:n  : SIOP:: AP = 330, PST = 331, CUR = 450, LCD = 0
,07-27 09:43:09.296   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:43:11.686  1540  1540 I wpa_supplicant: nl80211: Received scan results (31 BSSes)
,07-27 09:43:11.686   310  1192 D Netd    : Iface wlan0 link up
,07-27 09:43:11.706  1540  1540 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-27 09:43:11.736   748   861 D Tethering: interfaceLinkStateChanged wlan0, true
,07-27 09:43:11.736   748   861 D Tethering: interfaceStatusChanged wlan0, true
,07-27 09:43:11.746   748  1317 D WifiP2pService: InactiveState{ what=147461 }
,07-27 09:43:11.746   748  1317 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-27 09:43:11.746   748  1317 D WifiP2pService: DefaultState{ what=147461 }
,07-27 09:43:11.806   748   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ec7fded u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f194078 1376:com.android.systemui/u0a58}
,07-27 09:43:17.976   748   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:17.986   748   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:43:17.986   748   762 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:43:17.996   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:18.006   748   748 I MotionRecognitionService: Plugged
,07-27 09:43:18.006   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:43:18.006   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:43:18.006   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:18.016   748   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:43:18.016   748   762 D BatteryService: stay LED for fully charged
,07-27 09:43:18.016  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:43:18.016  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:18.016  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:18.036  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:43:18.036  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:18.046  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:18.046  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:18.046  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:18.466   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 450, LCD = 0
,07-27 09:43:28.066   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:28.066   748  2476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:43:28.066   748  2476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:43:28.076   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:28.086   748   748 I MotionRecognitionService: Plugged
,07-27 09:43:28.086   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:43:28.096   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:43:28.096   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:28.106   748  2476 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-27 09:43:28.106   748  2476 D BatteryService: stay LED for fully charged
,07-27 09:43:28.116  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:43:28.116  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:28.116  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:28.126  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:43:28.126  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:28.136  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:28.146  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:28.146  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:28.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:43:28.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:43:28.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:43:28.546   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 328, CUR = 450, LCD = 0
,07-27 09:43:29.296   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:43:37.346   748  1551 E Watchdog: !@Sync 11 [07-27 09:43:37.355]
,07-27 09:43:38.156   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:38.156   748  1598 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:43:38.156   748  1598 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:43:38.166   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:38.176   748   748 I MotionRecognitionService: Plugged
,07-27 09:43:38.186   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:43:38.186   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:43:38.186   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:38.196   748  1598 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,07-27 09:43:38.196   748  1598 D BatteryService: stay LED for fully charged
,07-27 09:43:38.216  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:43:38.216  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:38.216  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:38.226  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:43:38.226  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:38.236  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:38.236  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:38.236  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:38.606   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450, LCD = 0
,07-27 09:43:46.356   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:43:46.356   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:43:46.356   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:43:46.966  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:43:47.016  2011  2011 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:43:47.036  2011  2011 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:43:47.036  2011  2011 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:43:47.096  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:43:47.096  5903  5937 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:43:47.096  5903  5937 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:43:47.116   310  1195 D EnterpriseController: netId is 0
07-27 09:43:47.116   310  1195 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-27 09:43:47.356  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,07-27 09:43:48.236   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:48.236   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:43:48.236   748  2105 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:43:48.246   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:48.256   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-27 09:43:48.266   748   748 I MotionRecognitionService: Plugged
,07-27 09:43:48.266   748   748 D MotionRecognitionService:   cableConnection= 1
07-27 09:43:48.266   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:48.266   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:48.266   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:43:48.266  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:43:48.276  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:48.276  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:48.286  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:43:48.286  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:48.296  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:48.296  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:48.296  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:48.666   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 450, LCD = 0
,07-27 09:43:49.306   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:43:58.316   748  1486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:58.726   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450, LCD = 0
,07-27 09:43:59.986   748  1233 V AlarmManager: Expired Alarm result :8
,07-27 09:44:05.596   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:44:05.596   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:44:05.596   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:44:07.346   748  1551 E Watchdog: !@Sync 12 [07-27 09:44:07.364]
,07-27 09:44:08.406   748   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:08.406   748   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:44:08.406   748   762 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:44:08.416   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:44:08.426   748   748 I MotionRecognitionService: Plugged
,07-27 09:44:08.426   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:44:08.426   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:44:08.426   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:08.436   748   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 09:44:08.436   748   762 D BatteryService: stay LED for fully charged
,07-27 09:44:08.446  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:08.446  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:08.446  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:08.466  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:44:08.466  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:08.476  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:08.486  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:08.486  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:08.486  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:44:08.786   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450, LCD = 0
,07-27 09:44:09.306   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:44:18.486   748  1404 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:18.486   748  1404 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:44:18.486   748  1404 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:44:18.496   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:44:18.506   748   748 I MotionRecognitionService: Plugged
,07-27 09:44:18.506   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:44:18.516   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:44:18.516   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:18.516   748  1404 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:44:18.516   748  1404 D BatteryService: stay LED for fully charged
,07-27 09:44:18.526  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:18.536  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:18.536  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:18.566  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:44:18.566  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:18.566  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:18.566  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:18.566  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:18.846   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450, LCD = 0
,07-27 09:44:28.576   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:28.906   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-27 09:44:29.316   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:44:37.356   748  1551 E Watchdog: !@Sync 13 [07-27 09:44:37.369]
,07-27 09:44:38.666   748  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:38.666   748  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:44:38.666   748  1693 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:44:38.676   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:44:38.686   748   748 I MotionRecognitionService: Plugged
,07-27 09:44:38.686   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:44:38.686   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:44:38.686   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:38.696   748  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:44:38.696   748  1693 D BatteryService: stay LED for fully charged
,07-27 09:44:38.716  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:38.716  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:38.716  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:38.726  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:44:38.726  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:38.736  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:38.736  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:38.736  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:38.976   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450, LCD = 0
,07-27 09:44:45.816   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:44:45.816   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:44:45.816   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:44:48.736   748  1409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:49.036   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450, LCD = 0
,07-27 09:44:49.316   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:44:58.836   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:58.846   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4391, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:44:58.846   748  2105 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:44:58.846   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:44:58.856   748   748 I MotionRecognitionService: Plugged
,07-27 09:44:58.866   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:44:58.866   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:44:58.866   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:58.866  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:58.866  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:58.866  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:58.866   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:44:58.876   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:44:58.886  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:44:58.886  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:58.896  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:58.896  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:58.896  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:59.096   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450, LCD = 0
,07-27 09:45:05.156   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:45:05.156   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:45:05.156   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:45:07.356   748  1551 E Watchdog: !@Sync 14 [07-27 09:45:07.373]
,07-27 09:45:08.586  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:45:08.746  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 134ms lastUpdatedAfter : 180498ms
,07-27 09:45:09.146   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450, LCD = 0
,07-27 09:45:09.316   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:45:19.206   748  3604 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450, LCD = 0
,07-27 09:45:28.906   748  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:45:28.906   748  1758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:45:28.906   748  1758 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:45:28.916   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:45:28.926   748   748 I MotionRecognitionService: Plugged
,07-27 09:45:28.926   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:45:28.926   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:45:28.936   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:45:28.936   748  1758 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:45:28.936   748  1758 D BatteryService: stay LED for fully charged
,07-27 09:45:28.956  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:45:28.956  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:45:28.956  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:45:28.976  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:45:28.976  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:45:28.986  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:28.986  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:28.986  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:29.256   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450, LCD = 0
,07-27 09:45:29.326   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:45:37.366   748  1551 E Watchdog: !@Sync 15 [07-27 09:45:37.379]
,07-27 09:45:39.316   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450, LCD = 0
,07-27 09:45:41.866   363   363 I bootchecker: bootchecker wake up!!
,07-27 09:45:49.326   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:45:49.376   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450, LCD = 0
,07-27 09:45:58.976   748   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:45:58.986   748   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:45:58.986   748   762 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:45:58.986   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:45:59.006   748   748 I MotionRecognitionService: Plugged
,07-27 09:45:59.006   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:45:59.006   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:45:59.006   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:45:59.016   748   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:45:59.016   748   762 D BatteryService: stay LED for fully charged
,07-27 09:45:59.016  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:45:59.016  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:45:59.016  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:45:59.036  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:45:59.036  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:45:59.046  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:59.046  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:59.046  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:59.436   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450, LCD = 0
,07-27 09:46:07.366   748  1551 E Watchdog: !@Sync 16 [07-27 09:46:07.384]
,07-27 09:46:08.846  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:46:09.336   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:46:09.496   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450, LCD = 0
,07-27 09:46:19.556   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450, LCD = 0
,07-27 09:46:29.046   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:46:29.046   748  1598 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:46:29.056   748  1598 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:46:29.056   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:46:29.076   748   748 I MotionRecognitionService: Plugged
,07-27 09:46:29.076   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:46:29.076   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:46:29.086   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:46:29.086   748  1598 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 42ms
,07-27 09:46:29.096   748  1598 D BatteryService: stay LED for fully charged
,07-27 09:46:29.106  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:46:29.106  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:46:29.116  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:46:29.126  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:46:29.126  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:46:29.136  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:29.136  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:46:29.136  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:29.336   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:46:29.616   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450, LCD = 0
,07-27 09:46:37.376   748  1551 E Watchdog: !@Sync 17 [07-27 09:46:37.389]
,07-27 09:46:39.666   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450, LCD = 0
,07-27 09:46:49.336   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:46:49.726   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450, LCD = 0
,07-27 09:46:59.116   748  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:46:59.126   748  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:46:59.126   748  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:46:59.126   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:46:59.146   748   748 I MotionRecognitionService: Plugged
,07-27 09:46:59.146   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:46:59.146   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:46:59.146   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:46:59.156   748  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-27 09:46:59.156   748  1693 D BatteryService: stay LED for fully charged
,07-27 09:46:59.166  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:46:59.166  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:46:59.166  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:46:59.176  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:46:59.176  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:46:59.186  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:59.186  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:59.196  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:59.776   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:47:07.376   748  1551 E Watchdog: !@Sync 18 [07-27 09:47:07.393]
,07-27 09:47:08.886  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:47:09.346   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:47:09.836   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:47:19.896   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:47:29.186   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:47:29.186   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:47:29.196   748  2105 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:47:29.196   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:47:29.206   748   748 I MotionRecognitionService: Plugged
,07-27 09:47:29.206   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:47:29.216   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:47:29.216   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:47:29.216   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:47:29.216   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:47:29.236  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:47:29.236  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:47:29.236  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:47:29.266  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:47:29.266  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:47:29.266  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:47:29.266  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:47:29.276  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:47:29.346   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:47:29.946   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:47:37.386   748  1551 E Watchdog: !@Sync 19 [07-27 09:47:37.399]
,07-27 09:47:40.006   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:47:48.126   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:47:48.126   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:47:48.126   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:47:49.346   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:47:50.066   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:47:52.096   748  1227 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:47:52.096   748  1227 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:47:52.096   748  1226 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:47:53.606   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:47:53.616   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:47:53.626   748  1227 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:47:53.626   748  1227 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:47:59.256   748  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:47:59.266   748  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:47:59.266   748  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:47:59.276   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:47:59.286   748   748 I MotionRecognitionService: Plugged
,07-27 09:47:59.286   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:47:59.286   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:47:59.296   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:47:59.296   748  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 38ms
,07-27 09:47:59.306   748  1693 D BatteryService: stay LED for fully charged
,07-27 09:47:59.316  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:47:59.316  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:47:59.316  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:47:59.326  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:47:59.326  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:47:59.336  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:47:59.336  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:47:59.336  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:48:00.116   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:48:03.156   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:48:03.156   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:48:03.156   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:48:07.396   748  1551 E Watchdog: !@Sync 20 [07-27 09:48:07.408]
,07-27 09:48:08.996  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:48:09.156  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 143ms lastUpdatedAfter : 180416ms
,07-27 09:48:09.356   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:48:10.166   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.556   748   843 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLoc,ked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.566   748   843 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.576   748   843 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.586   748   843 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:12.596   748   843 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:12.676   748   899 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-27 09:48:12.676   748   899 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-27 09:48:20.226   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:48:29.336   748   763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:48:29.336   748   763 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:48:29.336   748   763 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:48:29.346   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:48:29.356   748   748 I MotionRecognitionService: Plugged
,07-27 09:48:29.356   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:48:29.356   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:48:29.356   748  3651 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:48:29.366   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:48:29.366   748   763 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:48:29.366   748   763 D BatteryService: stay LED for fully charged
,07-27 09:48:29.376  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:48:29.376  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:48:29.386  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:48:29.406  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:48:29.406  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:48:29.416  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:48:29.416  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:48:29.416  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:48:30.286   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:48:37.396   748  1551 E Watchdog: !@Sync 21 [07-27 09:48:37.413]
,07-27 09:48:40.336   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:48:47.396   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:48:47.396   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:48:47.396   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:48:47.406   748  2105 I ActivityManager: Killing 4711:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 616s, lastActivityTime 616s
,07-27 09:48:47.416   748  2105 I ActivityManager: Killing 4119:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 620s
,07-27 09:48:47.476   292   292 I ServiceManager: service 'AtCmdFwd' died
,07-27 09:48:47.486   367  4700 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-27 09:48:47.486   367  4700 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:48:47.486   748  1761 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-27 09:48:47.486   748  1761 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-27 09:48:47.486   748  1761 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-27 09:48:47.516   748   763 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-27 09:48:47.516   748   763 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-27 09:48:47.516   748   763 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10974ms
,07-27 09:48:48.486   367  4700 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 09:48:48.556   748   856 I ActivityManager: Start proc 7260:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-27 09:48:48.566  7260  7260 E Zygote  : v2
,07-27 09:48:48.566  7260  7260 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:48:48.566  7260  7260 I libpersona: KNOX_SDCARD not a persona
,07-27 09:48:48.566  7260  7260 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:48:48.566  7260  7260 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:48:48.576  7260  7260 E Zygote  : accessInfo : 0
,07-27 09:48:48.616  7260  7260 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:48:48.616  7260  7260 D ActivityThread: Added TimaKeyStore provider
,07-27 09:48:48.636  7260  7260 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-27 09:48:48.656  7260  7260 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-27 09:48:48.656  7260  7260 D AtFwdService: onCreate method
07-27 09:48:48.656  7260  7260 I AtFwdService: Instantiate AtCmdFwd Service
,07-27 09:48:48.666  7260  7277 D AtCkpdCmdHandler: De-queing command
,07-27 09:48:50.396   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:48:56.566   748  1233 V AlarmManager: Expired Alarm result :8
,07-27 09:48:58.556   748   856 I ActivityManager: Start proc 7282:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-27 09:48:58.566  7282  7282 E Zygote  : v2
,07-27 09:48:58.566  7282  7282 I libpersona: KNOX_SDCARD checking this for 10026
,07-27 09:48:58.566  7282  7282 I libpersona: KNOX_SDCARD not a persona
,07-27 09:48:58.566  7282  7282 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:48:58.566  7282  7282 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:48:58.576  7282  7282 E Zygote  : accessInfo : 0
,07-27 09:48:58.576  7282  7282 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-27 09:48:58.616  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:48:58.616  7282  7282 D ActivityThread: Added TimaKeyStore provider
,07-27 09:48:58.626   748   763 I ActivityManager: Killing 1505:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 622s, lastActivityTime 602s
,07-27 09:48:58.626   748   763 I ActivityManager: Killing 3814:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 633s, lastActivityTime 605s
,07-27 09:48:58.656  7282  7282 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-27 09:48:58.666   748  1648 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
07-27 09:48:58.666   748  1648 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-27 09:48:58.676   748  2476 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-27 09:48:58.676   748  2476 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
,07-27 09:48:58.676   748  2476 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-27 09:48:58.676  7282  7282 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-27 09:48:58.686  7282  7282 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-27 09:48:58.696  7282  7282 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-27 09:48:59.416   748  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:48:59.756   748   856 I ActivityManager: Start proc 7312:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
07-27 09:48:59.756   748  1316 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 09:48:59.756  7312  7312 E Zygote  : v2
,07-27 09:48:59.756  7312  7312 I libpersona: KNOX_SDCARD checking this for 10181
07-27 09:48:59.766  7312  7312 I libpersona: KNOX_SDCARD not a persona
,07-27 09:48:59.766  7312  7312 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:48:59.766  7312  7312 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:48:59.766  7312  7312 E Zygote  : accessInfo : 0
,07-27 09:48:59.766  7312  7312 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-27 09:48:59.816  7312  7312 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:48:59.816  7312  7312 D ActivityThread: Added TimaKeyStore provider
,07-27 09:48:59.826   748  1316 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-27 09:48:59.836  7312  7312 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-27 09:48:59.866  7312  7312 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-27 09:48:59.886  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-27 09:48:59.896  7312  7312 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:48:59.906   748   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4be507 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a82d634 7312:com.sec.android.daemonapp/u0a181}
,07-27 09:48:59.916  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-27 09:48:59.916  7312  7312 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:48:59.916  7312  7312 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-27 09:48:59.916  7312  7312 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:48:59.916  7312  7312 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-27 09:48:59.916  7312  7312 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-27 09:48:59.936  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:48:59.936  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-27 09:48:59.936  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-27 09:48:59.946  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:48:59.946  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:48:59.946  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-27 09:48:59.946  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-27 09:48:59.966  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-27 09:48:59.966  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:48:59.966  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:48:59.976  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-27 09:48:59.976  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-27 09:48:59.976  7312  7312 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:48:59.976  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-27 09:48:59.976  7312  7312 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-27 09:48:59.976  7312  7312 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:48:59.986  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:48:59.986  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:48:59.996   748   763 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e9121a0 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a82d634 7312:com.sec.android.daemonapp/u0a181}
,07-27 09:48:59.996  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:49:00.006  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:49:00.006  7312  7312 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:49:00.006  7312  7312 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:49:00.006  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:49:00.006  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:49:00.016  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:49:00.016  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:49:00.016   748  1486 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca4159 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a82d634 7312:com.sec.android.daemonapp/u0a181}
,07-27 09:49:00.026  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:49:00.026  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:49:00.026  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:49:00.026  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:49:00.026  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:49:00.036  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:49:00.036  7312  7312 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:49:00.036  7312  7312 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:49:00.036  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:49:00.036  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:49:00.046   748   762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2dd211e u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a82d634 7312:com.sec.android.daemonapp/u0a181}
,07-27 09:49:00.046  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-27 09:49:00.046  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-27 09:49:00.046  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-27 09:49:00.056  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:49:00.056  7312  7312 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:49:00.056  7312  7312 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:49:00.056  7312  7312 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-27 09:49:00.056  7312  7312 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:49:00.066  7312  7312 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-27 09:49:00.456   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:49:02.516   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:49:02.516   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:49:02.516   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:49:07.406   748  1551 E Watchdog: !@Sync 22 [07-27 09:49:07.420]
,07-27 09:49:09.236  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:49:10.506   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:49:20.566   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:49:29.496   748  1404 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:49:29.496   748  1404 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:49:29.496   748  1404 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:49:29.506   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:49:29.516   748   748 I MotionRecognitionService: Plugged
,07-27 09:49:29.516   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:49:29.516   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:49:29.516   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:49:29.526   748  1404 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:49:29.526   748  1404 D BatteryService: stay LED for fully charged
,07-27 09:49:29.546  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:49:29.546  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:49:29.546  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:49:29.566  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:49:29.566  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:49:29.576  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:49:29.576  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:49:29.576  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:49:30.616   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:49:37.406   748  1551 E Watchdog: !@Sync 23 [07-27 09:49:37.424]
,07-27 09:49:40.676   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:49:50.726   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:49:59.556   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:49:59.566   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:49:59.566   748  2105 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:49:59.576   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:49:59.586   748   748 I MotionRecognitionService: Plugged
,07-27 09:49:59.586   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:49:59.586   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:49:59.586   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:49:59.596   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:49:59.596   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:49:59.606  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:49:59.606  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:49:59.606  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:49:59.616  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:49:59.616  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:49:59.626  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:49:59.626  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:49:59.626  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:50:00.786   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-27 09:50:07.416   748  1551 E Watchdog: !@Sync 24 [07-27 09:50:07.434]
,07-27 09:50:09.326  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:50:10.836   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450, LCD = 0
,07-27 09:50:20.896   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450, LCD = 0
,07-27 09:50:24.776   748  1233 V AlarmManager: Expired Alarm result :8
,07-27 09:50:29.636   748   763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:50:29.636   748   763 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:50:29.636   748   763 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:50:29.646   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:50:29.656   748   748 I MotionRecognitionService: Plugged
,07-27 09:50:29.656   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:50:29.666   748   763 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 09:50:29.666   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:50:29.666   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:50:29.666   748   763 D BatteryService: stay LED for fully charged
,07-27 09:50:29.696  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:50:29.696  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:50:29.706  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:50:29.716  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:50:29.716  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:50:29.726  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:50:29.726  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:50:29.726  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:50:30.946   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-27 09:50:37.426   748  1551 E Watchdog: !@Sync 25 [07-27 09:50:37.438]
,07-27 09:50:41.006   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450, LCD = 0
,07-27 09:50:51.066   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-27 09:50:59.716   748   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:50:59.726   748   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:50:59.726   748   762 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:50:59.726   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:50:59.736   748   748 I MotionRecognitionService: Plugged
,07-27 09:50:59.746   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:50:59.746   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:50:59.746   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:50:59.756   748   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-27 09:50:59.756   748   762 D BatteryService: stay LED for fully charged
,07-27 09:50:59.756  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:50:59.756  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:50:59.756  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:50:59.776  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:50:59.776  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:50:59.786  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:50:59.786  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:50:59.786  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:01.116   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,07-27 09:51:07.426   748  1551 E Watchdog: !@Sync 26 [07-27 09:51:07.442]
,07-27 09:51:09.456  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:51:09.596  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 112ms lastUpdatedAfter : 180429ms
,07-27 09:51:11.176   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,07-27 09:51:12.666   748  2517 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 09:51:12.676   748  2517 V MARsPolicyManager: updateSMDBValues
,07-27 09:51:12.676   748   895 E MARsDBManager: updateDBAll : begin --size 1
,07-27 09:51:12.706   748   895 I ActivityManager: Killing 1956:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 781s, lastActivityTime 703s
,07-27 09:51:12.766   748   895 E MARsDBManager: updateDBAll : end
,07-27 09:51:12.776   748   895 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-27 09:51:12.806   748  2479 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-27 09:51:12.806   748  2479 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth no widget is using.
07-27 09:51:12.806   748  2479 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 1000ms
07-27 09:51:12.816   748  2479 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth no widget is using.
,07-27 09:51:12.816   748  2479 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10999ms
,07-27 09:51:12.816  6885  6885 D HealthConsole: Service for HealthDataStore is disconnected
,07-27 09:51:12.836   748  1409 I ActivityManager: Start proc 7337:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,07-27 09:51:12.846  7337  7337 E Zygote  : v2
,07-27 09:51:12.846  7337  7337 I libpersona: KNOX_SDCARD checking this for 10034
07-27 09:51:12.846  7337  7337 I libpersona: KNOX_SDCARD not a persona
,07-27 09:51:12.846  7337  7337 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-27 09:51:12.846  7337  7337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:51:12.856  7337  7337 E Zygote  : accessInfo : 0
,07-27 09:51:12.856  7337  7337 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-27 09:51:12.886  7337  7337 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:51:12.886  7337  7337 D ActivityThread: Added TimaKeyStore provider
,07-27 09:51:12.916  7337  7337 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-27 09:51:12.936  7337  7337 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-27 09:51:12.946  7337  7337 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 09:51:12.946  7337  7337 I MultiDex: install
07-27 09:51:12.946  7337  7337 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-27 09:51:12.946  7337  7337 I MultiDex: install
07-27 09:51:12.946  7337  7337 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 09:51:13.076  7367  7367 E Zygote  : v2
,07-27 09:51:13.076  7367  7367 I libpersona: KNOX_SDCARD checking this for 10016
07-27 09:51:13.086  7367  7367 I libpersona: KNOX_SDCARD not a persona
,07-27 09:51:13.086  7367  7367 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-27 09:51:13.086   748  1598 I ActivityManager: Start proc 7367:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
07-27 09:51:13.086  7367  7367 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:51:13.086  7367  7367 E Zygote  : accessInfo : 0
,07-27 09:51:13.096  7367  7367 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-27 09:51:13.146  7367  7367 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:51:13.146  7367  7367 D ActivityThread: Added TimaKeyStore provider
,07-27 09:51:13.176  7367  7367 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-27 09:51:13.236  7337  7337 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-27 09:51:13.236  7337  7337 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-27 09:51:13.286  1376  1376 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-27 09:51:13.296   748  1404 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-27 09:51:13.316   748  2479 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-27 09:51:13.316  1376  1376 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{396ebf5 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
07-27 09:51:13.316  1376  1376 D AdaptiveEventManager: M updateContainers()
07-27 09:51:13.316  1376  1376 D AdaptiveEventContainerSmall: C updatePedoContainer()
,07-27 09:51:13.316  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-27 09:51:13.326  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-27 09:51:13.326   748  1598 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-27 09:51:13.336   748  1693 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-27 09:51:13.376  7337  7337 I Health.HealthService: HealthService: onCreate() start (7337)
,07-27 09:51:13.516  6885  6885 D HealthDataStore: Service for HealthDataStore is connected
,07-27 09:51:13.516  6885  6885 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 09:51:13.526   748  1693 I ActivityManager: Killing 6166:com.android.email/u0a162 (adj 15): DHA:empty #37
,07-27 09:51:13.566  6885  6885 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-27 09:51:13.566  6885  6885 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 09:51:13.586   748  1486 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,07-27 09:51:13.616  7337  7337 D HealthDataStore: Service for HealthDataStore is connected
,07-27 09:51:13.616  7337  7337 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 09:51:13.616  7337  7337 D HealthConsole: Service for HealthDataConsole is connected
,07-27 09:51:13.616  7337  7337 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-27 09:51:13.616  7337  7337 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 09:51:13.756   748   758 I art     : Background partial concurrent mark sweep GC freed 80362(8MB) AllocSpace objects, 334(6MB) LOS objects, 27% free, 42MB/58MB, paused 1.487ms total 125.518ms
,07-27 09:51:13.776  7337  7388 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-27 09:51:13.806  7337  7393 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-27 09:51:13.826  7367  7381 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 09:51:13.836   382   382 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7367
07-27 09:51:13.836   382   382 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-27 09:51:13.956  7367  7381 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-27 09:51:14.086  7337  7393 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-27 09:51:14.196  7337  7393 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-27 09:51:14.196  7337  7393 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-27 09:51:14.256   382   382 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-27 09:51:14.286  7367  7381 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-27 09:51:14.286  7367  7381 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-27 09:51:14.286  7367  7381 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-27 09:51:21.246   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 303, CUR = 450, LCD = 0
,07-27 09:51:29.796   748  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:51:29.796   748  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:51:29.796   748  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:51:29.806   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:51:29.816   748   748 I MotionRecognitionService: Plugged
,07-27 09:51:29.816   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:51:29.816   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:51:29.826   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:51:29.826   748  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:51:29.826   748  1693 D BatteryService: stay LED for fully charged
,07-27 09:51:29.846  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:51:29.846  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:51:29.856  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:51:29.876  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:51:29.876  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:51:29.886  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:29.886  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:29.886  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:31.306   748  3604 D SSRM:n  : SIOP:: AP = 310, PST = 303, CUR = 450, LCD = 0
,07-27 09:51:37.436   748  1551 E Watchdog: !@Sync 27 [07-27 09:51:37.446]
,07-27 09:51:41.366   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:51:51.426   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:51:59.866   748  2105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:51:59.866   748  2105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:51:59.876   748  2105 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:51:59.876   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:51:59.886   748   748 I MotionRecognitionService: Plugged
,07-27 09:51:59.886   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:51:59.896   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:51:59.896   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:51:59.896   748  2105 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 09:51:59.906   748  2105 D BatteryService: stay LED for fully charged
,07-27 09:51:59.916  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:51:59.916  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:51:59.916  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:51:59.926  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:51:59.926  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:51:59.936  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:59.936  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:59.936  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:52:01.486   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:52:07.436   748  1551 E Watchdog: !@Sync 28 [07-27 09:52:07.450]
,07-27 09:52:09.616  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:52:11.536   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:52:21.596   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:52:29.936   748  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:52:31.646   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:52:37.446   748  1551 E Watchdog: !@Sync 29 [07-27 09:52:37.455]
,07-27 09:52:41.706   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:52:51.766   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-27 09:52:52.096   748  1227 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:52:52.096   748  1227 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:52:52.096   748  1226 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:52:55.496   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:52:55.506   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:52:55.516   748  1227 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:52:55.516   748  1227 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:52:56.446   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:52:56.446   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:52:56.446   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:53:00.016   748  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:53:00.026   748  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:53:00.026   748  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:53:00.026   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:53:00.046   748   748 I MotionRecognitionService: Plugged
,07-27 09:53:00.046   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:53:00.046   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:53:00.046   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:53:00.056   748  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,07-27 09:53:00.056   748  1693 D BatteryService: stay LED for fully charged
,07-27 09:53:00.066  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:53:00.066  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:53:00.066  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:53:00.076  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:53:00.076  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:53:00.086  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:00.096  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:00.096  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:01.816   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-27 09:53:07.446   748  1551 E Watchdog: !@Sync 30 [07-27 09:53:07.462]
,07-27 09:53:09.736  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:53:11.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:53:11.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:53:11.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:53:11.876   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:53:14.766   748  1233 V AlarmManager: Expired Alarm result :4
,07-27 09:53:14.816  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:53:14.816  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 09:53:14.826  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:53:14.836   748   856 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-27 09:53:14.836  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:53:14.846  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:53:14.856  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.856  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.856  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.866   748   748 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-27 09:53:14.866   748   748 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:53:14.866  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.866  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.866   748   748 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-27 09:53:14.876  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.876  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.886   748   748 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-27 09:53:14.896  2411  2582 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:53:14.896  2411  2582 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-27 09:53:14.896  2411  2582 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-27 09:53:14.896  2411  2582 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-27 09:53:14.896  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.896  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:53:14.906  2411  2611 D bt_upio : upio_start_stop_timer : timer_settime success
,07-27 09:53:14.906  2411  2611 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-27 09:53:14.906  2411  2611 D bt_vendor: op for 7
,07-27 09:53:14.906  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.906  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.906  2411  2611 D bt_vendor: op for 7
,07-27 09:53:14.916  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:53:14.916  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.916  2411  2611 D bt_vendor: op for 7
,07-27 09:53:14.916  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.916  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.916  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.916  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.916  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
,07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.926  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.926  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.926  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:53:14.926  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.926  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.926  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.926  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.926  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.936  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.936  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.936  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.936  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.936  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.936  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
07-27 09:53:14.936   748  1648 V AlarmManager:  remove PendingIntent] PendingIntent{399bf18: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:14.936  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.936  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.936  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.936  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.936  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.936  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.936  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.946  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.946  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-27 09:53:14.946  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.946  2411  2611 D bt_vendor: op for 7
07-27 09:53:14.946  2411  2611 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-27 09:53:14.946  2411  2611 D bt_upio : BT_WAKE is asserted already
,07-27 09:53:14.946   748   762 V AlarmManager:  remove PendingIntent] PendingIntent{53fdd71: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:14.956  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:14.966   748  1409 V AlarmManager:  remove PendingIntent] PendingIntent{80fe756: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:14.976   748  1404 V AlarmManager:  remove PendingIntent] PendingIntent{9c5e3d7: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:14.986   748  1486 V AlarmManager:  remove PendingIntent] PendingIntent{3f7b4c4: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:14.996   748  1761 V AlarmManager:  remove PendingIntent] PendingIntent{d23dfad: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:14.996   748  1598 V AlarmManager:  remove PendingIntent] PendingIntent{33b22e2: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.006   748  1758 V AlarmManager:  remove PendingIntent] PendingIntent{19ae673: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.006   748  2479 V AlarmManager:  remove PendingIntent] PendingIntent{11d5930: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.006   748  2105 V AlarmManager:  remove PendingIntent] PendingIntent{5cbc9a9: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.016   748   762 V AlarmManager:  remove PendingIntent] PendingIntent{ec8b2e: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.016   748  1648 V AlarmManager:  remove PendingIntent] PendingIntent{ab376cf: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.016   748  1693 V AlarmManager:  remove PendingIntent] PendingIntent{fb6d85c: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.016   748  2476 V AlarmManager:  remove PendingIntent] PendingIntent{9ee5765: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.026   748   763 V AlarmManager:  remove PendingIntent] PendingIntent{63a2c3a: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.026   748  1404 V AlarmManager:  remove PendingIntent] PendingIntent{f1ab0eb: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.026   748  1409 V AlarmManager:  remove PendingIntent] PendingIntent{1071e48: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.036   748  1486 V AlarmManager:  remove PendingIntent] PendingIntent{ef204e1: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.036   748  1761 V AlarmManager:  remove PendingIntent] PendingIntent{18ed206: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.036   748  1598 V AlarmManager:  remove PendingIntent] PendingIntent{47170c7: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.036   748  1758 V AlarmManager:  remove PendingIntent] PendingIntent{593d6f4: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.046   748  1648 V AlarmManager:  remove PendingIntent] PendingIntent{290e1d: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.046   748  1693 V AlarmManager:  remove PendingIntent] PendingIntent{b360892: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.046   748  1409 V AlarmManager:  remove PendingIntent] PendingIntent{f8a5263: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.056   748  1758 V AlarmManager:  remove PendingIntent] PendingIntent{e916e60: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.056   748  2479 V AlarmManager:  remove PendingIntent] PendingIntent{1cd6f19: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.056   748  1404 V AlarmManager:  remove PendingIntent] PendingIntent{2a81bde: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.056   748  1598 V AlarmManager:  remove PendingIntent] PendingIntent{5c5b1bf: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.056   748   762 V AlarmManager:  remove PendingIntent] PendingIntent{a0f108c: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.066   748   763 V AlarmManager:  remove PendingIntent] PendingIntent{7bce3d5: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.066   748  1761 V AlarmManager:  remove PendingIntent] PendingIntent{49617ea: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.076   748  2105 V AlarmManager:  remove PendingIntent] PendingIntent{82daadb: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}},
,07-27 09:53:15.076   748  2476 V AlarmManager:  remove PendingIntent] PendingIntent{5e2a978: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.076   748  1486 V AlarmManager:  remove PendingIntent] PendingIntent{bf4e851: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.076   748  1648 V AlarmManager:  remove PendingIntent] PendingIntent{5b5c8b6: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.086   748  1693 V AlarmManager:  remove PendingIntent] PendingIntent{45219b7: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.086   748  1409 V AlarmManager:  remove PendingIntent] PendingIntent{554e524: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.086   748  1758 V AlarmManager:  remove PendingIntent] PendingIntent{ceb88d: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.086   748  2479 V AlarmManager:  remove PendingIntent] PendingIntent{e4dba42: PendingIntentRecord{2e312fb com.android.bluetooth broadcastIntent}}
,07-27 09:53:15.256   748  1216 E LightSensor: RED : 0, GREEN : 1, BLUE : 2, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 8282.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=2, cp1=3, cpl=3202560
07-27 09:53:15.256   748   911 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-27 09:53:15.256   748   911 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-27 09:53:15.266   748   911 D SensorManager: unregisterListener ::   
07-27 09:53:15.266   748   911 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:53:15.266   748   911 V AlarmManager:  remove PendingIntent] PendingIntent{74e4d44: PendingIntentRecord{a7caf62 android broadcastIntent}}
,07-27 09:53:15.706  2411  2851 D bt_upio : ..proc_btwrite_timeout..
,07-27 09:53:15.706  2411  2851 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-27 09:53:21.936   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:53:31.996   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:53:34.116   748  1233 V AlarmManager: Expired Alarm result :4
,07-27 09:53:34.186   748  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:53:34.196   748  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:53:34.196   748  1648 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:53:34.196   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:53:34.206   748   748 I MotionRecognitionService: Plugged
,07-27 09:53:34.206   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:53:34.206   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:53:34.206   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:53:34.206  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:53:34.206  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:53:34.206  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:53:34.226   748  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-27 09:53:34.226   748  1648 D BatteryService: stay LED for fully charged
,07-27 09:53:34.226  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:53:34.226  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:53:34.236  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:34.236  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:53:34.236  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:34.246   748   843 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 09:53:34.246   748   843 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 09:53:34.966   748  1693 V AlarmManager:  remove PendingIntent] PendingIntent{49fcb66: PendingIntentRecord{1e112f6 com.google.android.apps.plus broadcastIntent}}
,07-27 09:53:34.976   748  1648 V AlarmManager:  remove PendingIntent] PendingIntent{ee6dea7: PendingIntentRecord{c4ddf54 com.google.android.apps.plus broadcastIntent}}
,07-27 09:53:37.456   748  1551 E Watchdog: !@Sync 31 [07-27 09:53:37.467]
,07-27 09:53:42.066   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:53:52.116   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:53:59.986   748  1233 V AlarmManager: Expired Alarm result :8
,07-27 09:54:02.186   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:54:04.276   748  2479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:54:04.276   748  2479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:54:04.276   748  2479 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:54:04.286   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:54:04.296   748   748 I MotionRecognitionService: Plugged
,07-27 09:54:04.296   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:54:04.296   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:54:04.306   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:54:04.306   748  2479 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:54:04.306   748  2479 D BatteryService: stay LED for fully charged
,07-27 09:54:04.326  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:54:04.326  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:54:04.326  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:54:04.336  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:54:04.346  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:54:04.346  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:54:04.346  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:54:04.356  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:54:07.456   748  1551 E Watchdog: !@Sync 32 [07-27 09:54:07.471]
,07-27 09:54:09.826  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:54:09.956  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 114ms lastUpdatedAfter : 180365ms
,07-27 09:54:12.246   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:54:22.296   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:54:32.356   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:54:34.336   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:54:34.346   748  2476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:54:34.346   748  2476 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:54:34.346   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:54:34.356   748   748 I MotionRecognitionService: Plugged
,07-27 09:54:34.366   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:54:34.366   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:54:34.366   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:54:34.376   748  2476 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:54:34.376   748  2476 D BatteryService: stay LED for fully charged
,07-27 09:54:34.376  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:54:34.376  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:54:34.376  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:54:34.396  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:54:34.396  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:54:34.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:54:34.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:54:34.406  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:54:37.466   748  1551 E Watchdog: !@Sync 33 [07-27 09:54:37.475]
,07-27 09:54:42.406   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:54:52.466   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:55:01.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:55:01.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:55:01.476   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:55:02.516   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:55:04.416   748  2479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:55:07.466   748  1551 E Watchdog: !@Sync 34 [07-27 09:55:07.482]
,07-27 09:55:09.966  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:55:12.576   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:55:16.516   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-27 09:55:16.516   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:55:16.516   310  1191 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:55:22.636   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:55:32.686   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:55:34.486   748   763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:55:34.496   748   763 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:55:34.496   748   763 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:55:34.496   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:55:34.516   748   748 I MotionRecognitionService: Plugged
,07-27 09:55:34.516   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:55:34.516   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:55:34.526   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:55:34.526   748   763 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-27 09:55:34.526   748   763 D BatteryService: stay LED for fully charged
,07-27 09:55:34.526  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:55:34.526  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:55:34.526  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:55:34.546  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:55:34.546  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:55:34.556  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:55:34.556  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:55:34.556  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:55:37.476   748  1551 E Watchdog: !@Sync 35 [07-27 09:55:37.490]
,07-27 09:55:42.746   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:55:52.796   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:56:02.856   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:56:04.566   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:56:07.476   748  1551 E Watchdog: !@Sync 36 [07-27 09:56:07.494]
,07-27 09:56:09.996  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:56:12.906   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:56:22.966   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:56:33.016   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:56:34.646   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:56:34.646   748  2476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:56:34.656   748  2476 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:56:34.656   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:56:34.666   748   748 I MotionRecognitionService: Plugged
,07-27 09:56:34.666   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:56:34.676   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:56:34.676   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:56:34.676   748  2476 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-27 09:56:34.676   748  2476 D BatteryService: stay LED for fully charged
,07-27 09:56:34.696  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:56:34.696  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:56:34.696  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:56:34.726  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:56:34.726  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:56:34.726  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:56:34.726  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:56:34.726  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:56:37.486   748  1551 E Watchdog: !@Sync 37 [07-27 09:56:37.498]
,07-27 09:56:43.076   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:56:53.126   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:03.186   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:04.726   748  2479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:57:04.726   748  2479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:57:04.736   748  2479 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:57:04.736   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:57:04.746   748   748 I MotionRecognitionService: Plugged
,07-27 09:57:04.746   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:57:04.756   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:57:04.756   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:57:04.756   748  2479 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-27 09:57:04.766   748  2479 D BatteryService: stay LED for fully charged
,07-27 09:57:04.776  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:57:04.776  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:57:04.776  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:57:04.786  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:57:04.786  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:57:04.796  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:04.796  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:04.796  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:07.486   748  1551 E Watchdog: !@Sync 38 [07-27 09:57:07.502]
,07-27 09:57:10.016  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:57:10.166  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 125ms lastUpdatedAfter : 180209ms
,07-27 09:57:13.246   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:23.296   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:33.346   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:34.796   748   762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:57:34.806   748   762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:57:34.806   748   762 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:57:34.806   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:57:34.826   748   762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-27 09:57:34.826   748   762 D BatteryService: stay LED for fully charged
,07-27 09:57:34.836   748   748 I MotionRecognitionService: Plugged
,07-27 09:57:34.836  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:57:34.836  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:57:34.836  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:57:34.836   748   748 D MotionRecognitionService:   cableConnection= 1
07-27 09:57:34.836   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:57:34.836   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:57:34.856  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:57:34.856  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:57:34.866  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:34.866  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:34.866  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:37.496   748  1551 E Watchdog: !@Sync 39 [07-27 09:57:37.508]
,07-27 09:57:43.406   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:52.096   748  1227 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:57:52.096   748  1227 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:57:52.096   748  1226 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:57:53.456   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:57:53.566   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:57:53.566   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:57:53.576   748  1227 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:57:53.576   748  1227 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:58:03.516   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:58:04.146   748   843 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:58:04.876   748  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:58:04.876   748  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:58:04.886   748  1648 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:58:04.886   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:58:04.896   748   748 I MotionRecognitionService: Plugged
,07-27 09:58:04.906   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:58:04.906   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:58:04.906   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:58:04.916   748  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 09:58:04.916   748  1648 D BatteryService: stay LED for fully charged
,07-27 09:58:04.926  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:58:04.926  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:58:04.936  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:58:04.946  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:58:04.946  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:58:04.956  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:58:04.956  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:58:04.956  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:58:07.506   748  1551 E Watchdog: !@Sync 40 [07-27 09:58:07.516]
,07-27 09:58:10.206  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:58:13.576   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:58:23.626   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:58:33.696   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:58:34.956   748   763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:58:37.506   748  1551 E Watchdog: !@Sync 41 [07-27 09:58:37.520]
,07-27 09:58:43.756   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:58:47.376  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:58:47.376  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:58:53.816   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:59:03.876   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:59:05.036   748   763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:59:05.046   748   763 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:59:05.046   748   763 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:59:05.046   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:59:05.056   748   748 I MotionRecognitionService: Plugged
,07-27 09:59:05.066   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:59:05.066   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:59:05.066   748   763 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 09:59:05.066   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:59:05.076   748   763 D BatteryService: stay LED for fully charged
,07-27 09:59:05.086  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:59:05.086  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:59:05.086  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:59:05.096  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:59:05.096  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:59:05.106  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:05.106  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:05.106  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:07.516   748  1551 E Watchdog: !@Sync 42 [07-27 09:59:07.524]
,07-27 09:59:10.306  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 09:59:13.936   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:59:23.996   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:59:34.046   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:59:35.126   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:59:35.126   748  2476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 09:59:35.126   748  2476 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 09:59:35.136   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:59:35.146   748   748 I MotionRecognitionService: Plugged
,07-27 09:59:35.146   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 09:59:35.146   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:59:35.146   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:59:35.156   748  2476 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-27 09:59:35.156   748  2476 D BatteryService: stay LED for fully charged
,07-27 09:59:35.176  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:59:35.176  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:59:35.176  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:59:35.196  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:59:35.196  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:59:35.206  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:35.206  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:59:35.206  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:37.516   748  1551 E Watchdog: !@Sync 43 [07-27 09:59:37.529]
,07-27 09:59:44.106   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-27 09:59:54.166   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,07-27 10:00:04.226   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-27 10:00:05.196   748  1758 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:00:05.206   748  1758 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 10:00:05.206   748  1758 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 10:00:05.206   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 10:00:05.226   748   748 I MotionRecognitionService: Plugged
,07-27 10:00:05.226   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 10:00:05.226   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 10:00:05.226   748  1758 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-27 10:00:05.236   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:00:05.236   748  1758 D BatteryService: stay LED for fully charged
,07-27 10:00:05.246  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:00:05.246  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:00:05.256  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:00:05.286  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:05.286  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:00:05.286  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:05.286  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:00:05.286  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:00:07.516   748  1551 E Watchdog: !@Sync 44 [07-27 10:00:07.534]
,07-27 10:00:10.336  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 10:00:10.466  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 111ms lastUpdatedAfter : 180300ms
,07-27 10:00:14.286   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,07-27 10:00:24.346   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-27 10:00:34.396   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-27 10:00:35.266   748  1761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:00:35.276   748  1761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 10:00:35.276   748  1761 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 10:00:35.286   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 10:00:35.296   748   748 I MotionRecognitionService: Plugged
,07-27 10:00:35.296   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 10:00:35.296   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 10:00:35.296   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:00:35.306   748  1761 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-27 10:00:35.306   748  1761 D BatteryService: stay LED for fully charged
,07-27 10:00:35.326  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:00:35.326  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 10:00:35.336  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:00:35.346  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:00:35.346  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:00:35.356  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:35.356  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:00:35.356  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:37.526   748  1551 E Watchdog: !@Sync 45 [07-27 10:00:37.539]
,07-27 10:00:44.456   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-27 10:00:54.516   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-27 10:01:04.576   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 10:01:05.346   748  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:01:05.356   748  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 10:01:05.356   748  1648 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 10:01:05.356   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 10:01:05.366   748   748 I MotionRecognitionService: Plugged
,07-27 10:01:05.366   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 10:01:05.376   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 10:01:05.376   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:01:05.386   748  1648 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-27 10:01:05.386   748  1648 D BatteryService: stay LED for fully charged
,07-27 10:01:05.386  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:01:05.386  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:01:05.386  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:01:05.396  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:01:05.406  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:01:05.416  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:01:05.416  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:01:05.416  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:01:07.526   748  1551 E Watchdog: !@Sync 46 [07-27 10:01:07.543]
,07-27 10:01:10.546  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 10:01:14.636   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-27 10:01:24.686   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:01:34.746   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:01:35.426   748  2479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:01:37.536   748  1551 E Watchdog: !@Sync 47 [07-27 10:01:37.548]
,07-27 10:01:44.806   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:01:54.856   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:02:04.906   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:02:05.506   748  2479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:02:05.516   748  2479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 10:02:05.516   748  2479 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 10:02:05.516   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 10:02:05.536   748   748 I MotionRecognitionService: Plugged
,07-27 10:02:05.536   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 10:02:05.536   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 10:02:05.536   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:02:05.546   748  2479 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-27 10:02:05.546   748  2479 D BatteryService: stay LED for fully charged
,07-27 10:02:05.556  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:02:05.556  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:02:05.556  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:02:05.586  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:02:05.586  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:02:05.586  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:02:05.586  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:02:05.586  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:02:07.536   748  1551 E Watchdog: !@Sync 48 [07-27 10:02:07.551]
,07-27 10:02:10.586  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 10:02:14.966   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:02:25.016   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:02:35.066   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:02:35.586   748  2476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:02:35.596   748  2476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-27 10:02:35.596   748  2476 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-27 10:02:35.596   748   748 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 10:02:35.606   748   748 I MotionRecognitionService: Plugged
,07-27 10:02:35.616   748   748 D MotionRecognitionService:   cableConnection= 1
,07-27 10:02:35.616   748   748 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 10:02:35.616   748   748 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:02:35.626   748  2476 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-27 10:02:35.626   748  2476 D BatteryService: stay LED for fully charged
,07-27 10:02:35.636  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:02:35.636  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:02:35.636  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:02:35.646  2411  2411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:02:35.656  2411  2855 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:02:35.656  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:02:35.666  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:02:35.666  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:02:37.546   748  1551 E Watchdog: !@Sync 49 [07-27 10:02:37.555]
,07-27 10:02:45.126   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-27 10:02:52.096   748  1227 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 10:02:52.096   748  1227 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 10:02:52.096   748  1226 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 10:02:55.186   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 450, LCD = 0
,07-27 10:02:55.526   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 10:02:55.526   748  1227 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 10:02:55.536   748  1227 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 10:02:55.546   748  1227 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 10:03:05.246   748  3604 D SSRM:n  : SIOP:: AP = 300, PST = 292, CUR = 450, LCD = 0
,07-27 10:03:05.676   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:03:07.546   748  1551 E Watchdog: !@Sync 50 [07-27 10:03:07.559]
,07-27 10:03:10.606  1611  1684 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-27 10:03:10.766  1611  1684 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 137ms lastUpdatedAfter : 180297ms
,07-27 10:03:12.686   748  2517 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 10:03:12.686   748  2517 V MARsPolicyManager: updateSMDBValues
,07-27 10:03:12.696   748   895 E MARsDBManager: updateDBAll : begin --size 0
,07-27 10:03:12.696   748   895 E MARsDBManager: updateDBAll : end
,07-27 10:03:15.266   748  1233 V AlarmManager: Expired Alarm result :8
,07-27 10:03:15.316   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 10:03:25.366   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 10:03:35.426   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 10:03:35.746   748  1598 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:03:37.546   748  1551 E Watchdog: !@Sync 51 [07-27 10:03:37.563]
,07-27 10:03:45.476   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-27 10:03:47.386  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 10:03:47.386  5903  5937 I PlayCommon: [837] com.google.android.play.a.al.e(732): No file ready to send
,TIME-OUT KILL (timeout was 1400000ms),07-27 10:03:55.526   748  3604 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
07-27 10:03:56.836  2417  2417 E audit   : type=1400 msg=audit(1469606636.836:293): avc:  denied  { execmod } for  pid=7494 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 10:03:56.836  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 10:03:56.836  2417  2417 E audit   : type=1300 msg=audit(1469606636.836:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f93000 a1=51000 a2=5 a3=4 items=0 ppid=3787 ppcomm=adbd pid=7494 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 10:03:56.836  2417  2417 E audit   : type=1327 msg=audit(1469606636.836:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-27 10:03:56.836  2417  2417 E audit   : type=1320 msg=audit(1469606636.836:293): 
07-27 10:03:56.906  2417  2417 E audit   : type=1400 msg=audit(1469606636.906:294): avc:  denied  { execmod } for  pid=7494 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 10:03:56.906  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 10:03:56.906  2417  2417 E audit   : type=1300 msg=audit(1469606636.906:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3787 ppcomm=adbd pid=7494 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 10:03:56.906  2417  2417 E audit   : type=1327 msg=audit(1469606636.906:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-27 10:03:56.906  2417  2417 E audit   : type=1320 msg=audit(1469606636.906:294): 
07-27 10:03:56.956  7494  7494 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 10:03:56.956  2417  2417 E audit   : type=1400 msg=audit(1469606636.956:295): avc:  denied  { execmod } for  pid=7494 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-27 10:03:56.956  2417  2417 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 10:03:56.956  2417  2417 E audit   : type=1300 msg=audit(1469606636.956:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3787 ppcomm=adbd pid=7494 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-27 10:03:56.956  2417  2417 E audit   : type=1327 msg=audit(1469606636.956:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-27 10:03:56.966  2417  2417 E audit   : type=1320 msg=audit(1469606636.956:295): 
07-27 10:03:56.966  7494  7494 D AndroidRuntime: CheckJNI is OFF
07-27 10:03:56.966  7494  7494 D AndroidRuntime: readGMSProperty: start
07-27 10:03:56.966  7494  7494 D AndroidRuntime: readGMSProperty: already setted!!
07-27 10:03:56.966  7494  7494 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 10:03:56.966  7494  7494 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 10:03:56.966  7494  7494 D AndroidRuntime: readGMSProperty: end
07-27 10:03:56.966  7494  7494 D AndroidRuntime: addProductProperty: start
07-27 10:03:56.976  7494  7494 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 10:03:56.976  7494  7494 W art     : af0e5000-b200b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-27 10:03:56.976  7494  7494 W art     : b200b000-b427a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-27 10:03:56.976  7494  7494 W art     : b427a000-b427b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-27 10:03:56.976  7494  7494 W art     : b427b000-b42a4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-27 10:03:56.976  7494  7494 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-27 10:03:56.976  7494  7494 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-27 10:03:56.976  7494  7494 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-27 10:03:56.976  7494  7494 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-27 10:03:56.976  7494  7494 W art     : b4822000-b4825000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-27 10:03:56.976  7494  7494 W art     : b4825000-b4826000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-27 10:03:56.976  7494  7494 W art     : b4826000-b4827000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-27 10:03:56.976  7494  7494 W art     : b4827000-b4828000 r--p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b4828000-b4848000 r--s 00000000 00:0b 8198       /dev/__properties__
07-27 10:03:56.976  7494  7494 W art     : b4848000-b5259000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-27 10:03:56.976  7494  7494 W art     : b5259000-b525a000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b525a000-b52a3000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-27 10:03:56.976  7494  7494 W art     : b52a3000-b52a4000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-27 10:03:56.976  7494  7494 W art     : b52a4000-b52ac000 rw-p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b52ac000-b52ad000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.976  7494  7494 W art     : b52ad000-b52e2000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-27 10:03:56.976  7494  7494 W art     : b52e2000-b52e3000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b52e3000-b52e4000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-27 10:03:56.976  7494  7494 W art     : b52e4000-b52e5000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-27 10:03:56.976  7494  7494 W art     : b52e5000-b533d000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-27 10:03:56.976  7494  7494 W art     : b533d000-b533e000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b533e000-b533f000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-27 10:03:56.976  7494  7494 W art     : b533f000-b5340000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-27 10:03:56.976  7494  7494 W art     : b5341000-b5347000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 10:03:56.976  7494  7494 W art     : b5347000-b5348000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 10:03:56.976  7494  7494 W art     : b5348000-b5349000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-27 10:03:56.976  7494  7494 W art     : b5349000-b534b000 rw-p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b534c000-b5356000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 10:03:56.976  7494  7494 W art     : b5356000-b5359000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 10:03:56.976  7494  7494 W art     : b5359000-b535a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-27 10:03:56.976  7494  7494 W art     : b535b000-b5372000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 10:03:56.976  7494  7494 W art     : b5372000-b5373000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b5373000-b5374000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 10:03:56.976  7494  7494 W art     : b5374000-b5375000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-27 10:03:56.976  7494  7494 W art     : b5376000-b5380000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-27 10:03:56.976  7494  7494 W art     : b5380000-b5381000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-27 10:03:56.976  7494  7494 W art     : b5381000-b5382000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-27 10:03:56.976  7494  7494 W art     : b5382000-b5386000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 10:03:56.976  7494  7494 W art     : b5386000-b5387000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 10:03:56.976  7494  7494 W art     : b5387000-b5388000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-27 10:03:56.976  7494  7494 W art     : b5388000-b539e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-27 10:03:56.976  7494  7494 W art     : b539e000-b539f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-27 10:03:56.976  7494  7494 W art     : b539f000-b53a0000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-27 10:03:56.976  7494  7494 W art     : b53a0000-b53ad000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-27 10:03:56.976  7494  7494 W art     : b53ad000-b53ae000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-27 10:03:56.976  7494  7494 W art     : b53ae000-b53af000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-27 10:03:56.976  7494  7494 W art     : b53af000-b540f000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-27 10:03:56.976  7494  7494 W art     : b540f000-b5412000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-27 10:03:56.976  7494  7494 W art     : b5412000-b5416000 rw-p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b5416000-b5477000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-27 10:03:56.976  7494  7494 W art     : b5477000-b5478000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-27 10:03:56.976  7494  7494 W art     : b5478000-b54c7000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-27 10:03:56.976  7494  7494 W art     : b54c7000-b54c9000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-27 10:03:56.976  7494  7494 W art     : b54c9000-b54ca000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-27 10:03:56.976  7494  7494 W art     : b54ca000-b54cb000 rw-p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b54cb000-b54d2000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 10:03:56.976  7494  7494 W art     : b54d2000-b54d3000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 10:03:56.976  7494  7494 W art     : b54d3000-b54d4000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-27 10:03:56.976  7494  7494 W art     : b54d5000-b54d8000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 10:03:56.976  7494  7494 W art     : b54d8000-b54d9000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 10:03:56.976  7494  7494 W art     : b54d9000-b54da000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-27 10:03:56.976  7494  7494 W art     : b54db000-b54df000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-27 10:03:56.976  7494  7494 W art     : b54df000-b54e0000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b54e0000-b54e1000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-27 10:03:56.976  7494  7494 W art     : b54e1000-b54e2000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-27 10:03:56.976  7494  7494 W art     : b54e3000-b5500000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 10:03:56.976  7494  7494 W art     : b5500000-b5501000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 10:03:56.976  7494  7494 W art     : b5501000-b5502000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-27 10:03:56.976  7494  7494 W art     : b5503000-b5508000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 10:03:56.976  7494  7494 W art     : b5508000-b5509000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 10:03:56.976  7494  7494 W art     : b5509000-b550a000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-27 10:03:56.976  7494  7494 W art     : b550b000-b553c000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 10:03:56.976  7494  7494 W art     : b553c000-b553f000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 10:03:56.976  7494  7494 W art     : b553f000-b5540000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-27 10:03:56.976  7494  7494 W art     : b5541000-b557c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-27 10:03:56.976  7494  7494 W art     : b557c000-b557d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-27 10:03:56.976  7494  7494 W art     : b557d000-b557e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-27 10:03:56.976  7494  7494 W art     : b557f000-b5586000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-27 10:03:56.976  7494  7494 W art     : b5586000-b5587000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b5587000-b5588000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-27 10:03:56.976  7494  7494 W art     : b5588000-b5589000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-27 10:03:56.976  7494  7494 W art     : b5589000-b558a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.976  7494  7494 W art     : b558a000-b55a1000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-27 10:03:56.976  7494  7494 W art     : b55a1000-b55a2000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b55a2000-b55a5000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-27 10:03:56.976  7494  7494 W art     : b55a5000-b55a6000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-27 10:03:56.976  7494  7494 W art     : b55a6000-b55c5000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-27 10:03:56.976  7494  7494 W art     : b55c5000-b55c6000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-27 10:03:56.976  7494  7494 W art     : b55c6000-b55c7000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-27 10:03:56.976  7494  7494 W art     : b55c7000-b5605000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-27 10:03:56.976  7494  7494 W art     : b5605000-b5606000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b5606000-b5608000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-27 10:03:56.976  7494  7494 W art     : b5608000-b5609000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-27 10:03:56.976  7494  7494 W art     : b560a000-b5611000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 10:03:56.976  7494  7494 W art     : b5611000-b5612000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 10:03:56.976  7494  7494 W art     : b5612000-b5613000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-27 10:03:56.976  7494  7494 W art     : b5614000-b5617000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 10:03:56.976  7494  7494 W art     : b5617000-b5618000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 10:03:56.976  7494  7494 W art     : b5618000-b5619000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-27 10:03:56.976  7494  7494 W art     : b5619000-b561f000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 10:03:56.976  7494  7494 W art     : b561f000-b5620000 ---p 00000000 00:00 0 
07-27 10:03:56.976  7494  7494 W art     : b5620000-b5621000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 10:03:56.986  7494  7494 W art     : b5621000-b5622000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-27 10:03:56.986  7494  7494 W art     : b5622000-b562b000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-27 10:03:56.986  7494  7494 W art     : b562b000-b562c000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-27 10:03:56.986  7494  7494 W art     : b562c000-b562d000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-27 10:03:56.986  7494  7494 W art     : b562d000-b56be000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 10:03:56.986  7494  7494 W art     : b56be000-b56bf000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b56bf000-b56ca000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 10:03:56.986  7494  7494 W art     : b56ca000-b56cb000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-27 10:03:56.986  7494  7494 W art     : b56cc000-b56de000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-27 10:03:56.986  7494  7494 W art     : b56de000-b56df000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-27 10:03:56.986  7494  7494 W art     : b56df000-b56e0000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-27 10:03:56.986  7494  7494 W art     : b56e1000-b56e6000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-27 10:03:56.986  7494  7494 W art     : b56e6000-b56e7000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-27 10:03:56.986  7494  7494 W art     : b56e7000-b56e8000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-27 10:03:56.986  7494  7494 W art     : b56e9000-b5756000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-27 10:03:56.986  7494  7494 W art     : b5756000-b5757000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5757000-b5759000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-27 10:03:56.986  7494  7494 W art     : b5759000-b575a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-27 10:03:56.986  7494  7494 W art     : b575a000-b575b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b575b000-b5762000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 10:03:56.986  7494  7494 W art     : b5762000-b5763000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 10:03:56.986  7494  7494 W art     : b5763000-b5764000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-27 10:03:56.986  7494  7494 W art     : b5765000-b57e5000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 10:03:56.986  7494  7494 W art     : b57e5000-b57e6000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b57e6000-b57e7000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 10:03:56.986  7494  7494 W art     : b57e7000-b57e8000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-27 10:03:56.986  7494  7494 W art     : b57e8000-b57ff000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b57ff000-b5836000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-27 10:03:56.986  7494  7494 W art     : ib/libqc-opt.so
07-27 10:03:56.986  7494  7494 W art     : b5836000-b5837000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 10:03:56.986  7494  7494 W art     : b5837000-b5838000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-27 10:03:56.986  7494  7494 W art     : b5838000-b5854000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 10:03:56.986  7494  7494 W art     : b5854000-b5855000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 10:03:56.986  7494  7494 W art     : b5855000-b5856000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-27 10:03:56.986  7494  7494 W art     : b5857000-b58b8000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-27 10:03:56.986  7494  7494 W art     : b58b8000-b58ba000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-27 10:03:56.986  7494  7494 W art     : b58ba000-b58bb000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-27 10:03:56.986  7494  7494 W art     : b58bc000-b58e3000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-27 10:03:56.986  7494  7494 W art     : b58e3000-b58e4000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b58e4000-b58e5000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-27 10:03:56.986  7494  7494 W art     : b58e5000-b58e6000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-27 10:03:56.986  7494  7494 W art     : b58e7000-b58ef000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 10:03:56.986  7494  7494 W art     : b58ef000-b58f1000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 10:03:56.986  7494  7494 W art     : b58f1000-b58f2000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-27 10:03:56.986  7494  7494 W art     : b58f3000-b58f6000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-27 10:03:56.986  7494  7494 W art     : b58f6000-b58f7000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-27 10:03:56.986  7494  7494 W art     : b58f7000-b58f8000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-27 10:03:56.986  7494  7494 W art     : b58f8000-b58fc000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-27 10:03:56.986  7494  7494 W art     : b58fc000-b58fd000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b58fd000-b58fe000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-27 10:03:56.986  7494  7494 W art     : b58fe000-b58ff000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-27 10:03:56.986  7494  7494 W art     : b58ff000-b590f000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-27 10:03:56.986  7494  7494 W art     : b590f000-b5910000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-27 10:03:56.986  7494  7494 W art     : b5910000-b5911000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-27 10:03:56.986  7494  7494 W art     : b5911000-b5957000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5957000-b5960000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-27 10:03:56.986  7494  7494 W art     : b5960000-b5961000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-27 10:03:56.986  7494  7494 W art     : b5961000-b5962000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-27 10:03:56.986  7494  7494 W art     : b5963000-b5968000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-27 10:03:56.986  7494  7494 W art     : b5968000-b5969000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-27 10:03:56.986  7494  7494 W art     : b5969000-b596a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-27 10:03:56.986  7494  7494 W art     : b596a000-b596d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 10:03:56.986  7494  7494 W art     : b596d000-b596e000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b596e000-b596f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 10:03:56.986  7494  7494 W art     : b596f000-b5970000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-27 10:03:56.986  7494  7494 W art     : b5971000-b5989000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 10:03:56.986  7494  7494 W art     : b5989000-b598a000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b598a000-b598b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 10:03:56.986  7494  7494 W art     : b598b000-b598c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-27 10:03:56.986  7494  7494 W art     : b598c000-b598d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 10:03:56.986  7494  7494 W art     : b598d000-b5b27000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-27 10:03:56.986  7494  7494 W art     : b5b27000-b5b28000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5b28000-b5b35000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-27 10:03:56.986  7494  7494 W art     : b5b35000-b5b36000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-27 10:03:56.986  7494  7494 W art     : b5b36000-b5b3a000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-27 10:03:56.986  7494  7494 W art     : b5b3a000-b5b3b000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5b3b000-b5b3c000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-27 10:03:56.986  7494  7494 W art     : b5b3c000-b5b3d000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-27 10:03:56.986  7494  7494 W art     : b5b3d000-b5b50000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-27 10:03:56.986  7494  7494 W art     : b5b50000-b5b51000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-27 10:03:56.986  7494  7494 W art     : b5b51000-b5b52000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-27 10:03:56.986  7494  7494 W art     : b5b53000-b5b9e000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-27 10:03:56.986  7494  7494 W art     : b5b9e000-b5b9f000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-27 10:03:56.986  7494  7494 W art     : b5b9f000-b5ba0000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-27 10:03:56.986  7494  7494 W art     : b5ba0000-b5ba2000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5ba3000-b5bb4000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 10:03:56.986  7494  7494 W art     : b5bb4000-b5bb5000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5bb5000-b5bb6000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 10:03:56.986  7494  7494 W art     : b5bb6000-b5bb7000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-27 10:03:56.986  7494  7494 W art     : b5bb7000-b5bb8000 r--p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5bb8000-b5bc2000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-27 10:03:56.986  7494  7494 W art     : b5bc2000-b5bc4000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-27 10:03:56.986  7494  7494 W art     : b5bc4000-b5bc5000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-27 10:03:56.986  7494  7494 W art     : b5bc5000-b5bde000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-27 10:03:56.986  7494  7494 W art     : b5bde000-b5bdf000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-27 10:03:56.986  7494  7494 W art     : b5bdf000-b5be2000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-27 10:03:56.986  7494  7494 W art     : b5be2000-b5be6000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5be6000-b5c5a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-27 10:03:56.986  7494  7494 W art     : b5c5a000-b5c5b000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5c5b000-b5c5e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-27 10:03:56.986  7494  7494 W art     : b5c5e000-b5c5f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-27 10:03:56.986  7494  7494 W art     : b5c5f000-b5c60000 r--p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5c60000-b5c63000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-27 10:03:56.986  7494  7494 W art     : b5c63000-b5c64000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-27 10:03:56.986  7494  7494 W art     : b5c64000-b5c65000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-27 10:03:56.986  7494  7494 W art     : b5c65000-b5c66000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b5c66000-b5c6b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 10:03:56.986  7494  7494 W art     : b5c6b000-b5c6c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 10:03:56.986  7494  7494 W art     : b5c6c000-b5c6d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-27 10:03:56.986  7494  7494 W art     : b5c6d000-b5c6e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b5c6e000-b5c71000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 10:03:56.986  7494  7494 W art     : b5c71000-b5c72000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 10:03:56.986  7494  7494 W art     : b5c72000-b5c73000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-27 10:03:56.986  7494  7494 W art     : b5c73000-b5c74000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b5c74000-b5c78000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-27 10:03:56.986  7494  7494 W art     : b5c78000-b5c79000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-27 10:03:56.986  7494  7494 W art     : b5c79000-b5c7a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-27 10:03:56.986  7494  7494 W art     : b5c7a000-b5c7b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 10:03:56.986  7494  7494 W art     : b5c7b000-b5c7f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 10:03:56.986  7494  7494 W art     : b5c7f000-b5c80000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 10:03:56.986  7494  7494 W art     : b5c80000-b5c81000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-27 10:03:56.986  7494  7494 W art     : b5c81000-b5c82000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b5c82000-b5c90000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-27 10:03:56.986  7494  7494 W art     : b5c90000-b5c91000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b5c91000-b5c92000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-27 10:03:56.986  7494  7494 W art     : b5c92000-b5c93000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-27 10:03:56.986  7494  7494 W art     : b5c93000-b5c9d000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 10:03:56.986  7494  7494 W art     : b5c9d000-b5ca0000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 10:03:56.986  7494  7494 W art     : b5ca0000-b5ca1000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-27 10:03:56.986  7494  7494 W art     : b5ca1000-b5ca2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b5ca2000-b5cac000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-27 10:03:56.986  7494  7494 W art     : b5cac000-b5caf000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-27 10:03:56.986  7494  7494 W art     : b5caf000-b5cb0000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-27 10:03:56.986  7494  7494 W art     : b5cb0000-b5cb4000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-27 10:03:56.986  7494  7494 W art     : b5cb4000-b5cb5000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-27 10:03:56.986  7494  7494 W art     : b5cb5000-b5cb6000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-27 10:03:56.986  7494  7494 W art     : b5cb6000-b5cb7000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b5cb7000-b5cc4000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-27 10:03:56.986  7494  7494 W art     : b5cc4000-b5cc6000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-27 10:03:56.986  7494  7494 W art     : b5cc6000-b5cc7000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-27 10:03:56.986  7494  7494 W art     : b5cc7000-b60d9000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-27 10:03:56.986  7494  7494 W art     : b60d9000-b60da000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b60da000-b60e3000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-27 10:03:56.986  7494  7494 W art     : b60e3000-b60e7000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-27 10:03:56.986  7494  7494 W art     : b60e7000-b60e8000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b60e8000-b60ef000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-27 10:03:56.986  7494  7494 W art     : b60ef000-b60f0000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-27 10:03:56.986  7494  7494 W art     : b60f0000-b60f1000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-27 10:03:56.986  7494  7494 W art     : b60f1000-b60f2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b60f2000-b610d000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-27 10:03:56.986  7494  7494 W art     : b610d000-b610e000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-27 10:03:56.986  7494  7494 W art     : b610e000-b610f000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-27 10:03:56.986  7494  7494 W art     : b610f000-b6110000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6110000-b615c000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 10:03:56.986  7494  7494 W art     : b615c000-b615d000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b615d000-b615e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 10:03:56.986  7494  7494 W art     : b615e000-b615f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-27 10:03:56.986  7494  7494 W art     : b615f000-b6160000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6160000-b6164000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-27 10:03:56.986  7494  7494 W art     : b6164000-b6165000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6165000-b6166000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-27 10:03:56.986  7494  7494 W art     : b6166000-b6167000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-27 10:03:56.986  7494  7494 W art     : b6167000-b619f000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-27 10:03:56.986  7494  7494 W art     : b619f000-b61a0000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-27 10:03:56.986  7494  7494 W art     : b61a0000-b61a1000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-27 10:03:56.986  7494  7494 W art     : b61a1000-b61a2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b61a2000-b6240000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-27 10:03:56.986  7494  7494 W art     : b6240000-b6241000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6241000-b625f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-27 10:03:56.986  7494  7494 W art     : b625f000-b6260000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-27 10:03:56.986  7494  7494 W art     : b6260000-b63d3000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-27 10:03:56.986  7494  7494 W art     : b63d3000-b63de000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-27 10:03:56.986  7494  7494 W art     : b63de000-b63df000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-27 10:03:56.986  7494  7494 W art     : b63df000-b64f6000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-27 10:03:56.986  7494  7494 W art     : b64f6000-b6501000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-27 10:03:56.986  7494  7494 W art     : b6501000-b6502000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-27 10:03:56.986  7494  7494 W art     : b6502000-b6506000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6506000-b652a000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-27 10:03:56.986  7494  7494 W art     : b652a000-b652c000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-27 10:03:56.986  7494  7494 W art     : b652c000-b652d000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-27 10:03:56.986  7494  7494 W art     : b652d000-b65d3000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-27 10:03:56.986  7494  7494 W art     : b65d3000-b65e0000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-27 10:03:56.986  7494  7494 W art     : b65e0000-b65e1000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-27 10:03:56.986  7494  7494 W art     : b65e1000-b65e2000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b65e2000-b6635000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-27 10:03:56.986  7494  7494 W art     : b6635000-b6636000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6636000-b6637000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-27 10:03:56.986  7494  7494 W art     : b6637000-b6638000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-27 10:03:56.986  7494  7494 W art     : b6638000-b663d000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b663d000-b664f000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-27 10:03:56.986  7494  7494 W art     : b664f000-b6650000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6650000-b6651000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-27 10:03:56.986  7494  7494 W art     : b6651000-b6652000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-27 10:03:56.986  7494  7494 W art     : b6652000-b6659000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 10:03:56.986  7494  7494 W art     : b6659000-b665a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 10:03:56.986  7494  7494 W art     : b665a000-b665b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-27 10:03:56.986  7494  7494 W art     : b665b000-b665c000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b665c000-b665f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-27 10:03:56.986  7494  7494 W art     : b665f000-b6660000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-27 10:03:56.986  7494  7494 W art     : b6660000-b6661000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-27 10:03:56.986  7494  7494 W art     : b6661000-b6665000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-27 10:03:56.986  7494  7494 W art     : b6665000-b6666000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-27 10:03:56.986  7494  7494 W art     : b6666000-b6667000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-27 10:03:56.986  7494  7494 W art     : b6667000-b6675000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-27 10:03:56.986  7494  7494 W art     : b6675000-b6676000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6676000-b6677000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-27 10:03:56.986  7494  7494 W art     : b6677000-b6678000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-27 10:03:56.986  7494  7494 W art     : b6678000-b6681000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 10:03:56.986  7494  7494 W art     : b6681000-b6682000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 10:03:56.986  7494  7494 W art     : b6682000-b6683000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-27 10:03:56.986  7494  7494 W art     : b6683000-b66e9000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-27 10:03:56.986  7494  7494 W art     : b66e9000-b66ea000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b66ea000-b66ec000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-27 10:03:56.986  7494  7494 W art     : b66ec000-b66f5000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-27 10:03:56.986  7494  7494 W art     : b66f5000-b66f8000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b66f8000-b678f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-27 10:03:56.986  7494  7494 W art     : b678f000-b6791000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-27 10:03:56.986  7494  7494 W art     : b6791000-b6792000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-27 10:03:56.986  7494  7494 W art     : b6792000-b6793000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6793000-b6ab4000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-27 10:03:56.986  7494  7494 W art     : b6ab4000-b6ab5000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6ab5000-b6ad0000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-27 10:03:56.986  7494  7494 W art     : b6ad0000-b6ad4000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-27 10:03:56.986  7494  7494 W art     : b6ad4000-b6ad9000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6ad9000-b6ae1000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 10:03:56.986  7494  7494 W art     : b6ae1000-b6ae2000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 10:03:56.986  7494  7494 W art     : b6ae2000-b6ae3000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-27 10:03:56.986  7494  7494 W art     : b6ae3000-b6b11000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-27 10:03:56.986  7494  7494 W art     : b6b11000-b6b12000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6b12000-b6b19000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-27 10:03:56.986  7494  7494 W art     : b6b19000-b6b1a000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-27 10:03:56.986  7494  7494 W art     : b6b1a000-b6b60000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-27 10:03:56.986  7494  7494 W art     : b6b60000-b6b61000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6b61000-b6b64000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-27 10:03:56.986  7494  7494 W art     : b6b64000-b6b65000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-27 10:03:56.986  7494  7494 W art     : b6b65000-b6b80000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-27 10:03:56.986  7494  7494 W art     : b6b80000-b6b84000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-27 10:03:56.986  7494  7494 W art     : b6b84000-b6b85000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-27 10:03:56.986  7494  7494 W art     : b6b85000-b6bd2000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-27 10:03:56.986  7494  7494 W art     : b6bd2000-b6bd3000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6bd3000-b6bdf000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-27 10:03:56.986  7494  7494 W art     : b6bdf000-b6be0000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-27 10:03:56.986  7494  7494 W art     : b6be0000-b6bed000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-27 10:03:56.986  7494  7494 W art     : b6bed000-b6bee000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6bee000-b6bef000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-27 10:03:56.986  7494  7494 W art     : b6bef000-b6bf0000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-27 10:03:56.986  7494  7494 W art     : b6bf0000-b6bf8000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-27 10:03:56.986  7494  7494 W art     : b6bf8000-b6bf9000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6bf9000-b6bfa000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-27 10:03:56.986  7494  7494 W art     : b6bfa000-b6bfb000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-27 10:03:56.986  7494  7494 W art     : b6bfb000-b6c02000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-27 10:03:56.986  7494  7494 W art     : b6c02000-b6c03000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-27 10:03:56.986  7494  7494 W art     : b6c03000-b6c04000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-27 10:03:56.986  7494  7494 W art     : b6c04000-b6c18000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-27 10:03:56.986  7494  7494 W art     : b6c18000-b6c1a000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-27 10:03:56.986  7494  7494 W art     : b6c1a000-b6c1b000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-27 10:03:56.986  7494  7494 W art     : b6c1b000-b6c43000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-27 10:03:56.986  7494  7494 W art     : b6c43000-b6c45000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-27 10:03:56.986  7494  7494 W art     : b6c45000-b6c46000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-27 10:03:56.986  7494  7494 W art     : b6c46000-b6c49000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-27 10:03:56.986  7494  7494 W art     : b6c49000-b6c4a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-27 10:03:56.986  7494  7494 W art     : b6c4a000-b6c4b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-27 10:03:56.986  7494  7494 W art     : b6c4b000-b6c54000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-27 10:03:56.986  7494  7494 W art     : b6c54000-b6c55000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-27 10:03:56.986  7494  7494 W art     : b6c55000-b6c56000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-27 10:03:56.986  7494  7494 W art     : b6c56000-b6c76000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-27 10:03:56.986  7494  7494 W art     : b6c76000-b6c77000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-27 10:03:56.986  7494  7494 W art     : b6c77000-b6c78000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-27 10:03:56.986  7494  7494 W art     : b6c78000-b6ceb000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-27 10:03:56.986  7494  7494 W art     : b6ceb000-b6cef000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-27 10:03:56.986  7494  7494 W art     : b6cef000-b6cf2000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-27 10:03:56.986  7494  7494 W art     : b6cf2000-b6cfc000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6cfc000-b6d84000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-27 10:03:56.986  7494  7494 W art     : b6d84000-b6d85000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6d85000-b6d89000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-27 10:03:56.986  7494  7494 W art     : b6d89000-b6d8a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-27 10:03:56.986  7494  7494 W art     : b6d8a000-b6d8b000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6d8b000-b6db4000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-27 10:03:56.986  7494  7494 W art     : b6db4000-b6db5000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6db5000-b6db8000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-27 10:03:56.986  7494  7494 W art     : b6db8000-b6db9000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-27 10:03:56.986  7494  7494 W art     : b6db9000-b6e93000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 10:03:56.986  7494  7494 W art     : b6e93000-b6e9a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 10:03:56.986  7494  7494 W art     : b6e9a000-b6ea2000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-27 10:03:56.986  7494  7494 W art     : b6ea2000-b6ea3000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6ea3000-b6ea4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 10:03:56.986  7494  7494 W art     : b6ea4000-b6ea5000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-27 10:03:56.986  7494  7494 W art     : b6ea5000-b6ea6000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6ea6000-b6ea9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6ea9000-b6ece000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-27 10:03:56.986  7494  7494 W art     : b6ece000-b6ecf000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6ecf000-b6ed6000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-27 10:03:56.986  7494  7494 W art     : b6ed6000-b6ed7000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-27 10:03:56.986  7494  7494 W art     : b6ed7000-b6ede000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-27 10:03:56.986  7494  7494 W art     : b6ede000-b6edf000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-27 10:03:56.986  7494  7494 W art     : b6edf000-b6ee0000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-27 10:03:56.986  7494  7494 W art     : b6ee0000-b6ee1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6ee1000-b6ef9000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-27 10:03:56.986  7494  7494 W art     : b6ef9000-b6efa000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6efa000-b6efb000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-27 10:03:56.986  7494  7494 W art     : b6efb000-b6efc000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-27 10:03:56.986  7494  7494 W art     : b6efc000-b6f0a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-27 10:03:56.986  7494  7494 W art     : b6f0a000-b6f0b000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6f0b000-b6f0c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-27 10:03:56.986  7494  7494 W art     : b6f0c000-b6f0d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-27 10:03:56.986  7494  7494 W art     : b6f0d000-b6f0e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 10:03:56.986  7494  7494 W art     : b6f0e000-b6f10000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6f10000-b6f11000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6f11000-b6f12000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-27 10:03:56.986  7494  7494 W art     : b6f12000-b6f13000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-27 10:03:56.986  7494  7494 W art     : b6f13000-b6f14000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-27 10:03:56.986  7494  7494 W art     : b6f14000-b6f34000 r--s 00000000 00:0b 8198       /dev/__properties__
07-27 10:03:56.986  7494  7494 W art     : b6f34000-b6f35000 r--p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6f35000-b6f36000 ---p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6f36000-b6f38000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-27 10:03:56.986  7494  7494 W art     : b6f38000-b6f39000 r-xp 00000000 00:00 0          [sigpage]
07-27 10:03:56.986  7494  7494 W art     : b6f39000-b6f54000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-27 10:03:56.986  7494  7494 W art     : b6f54000-b6f55000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-27 10:03:56.986  7494  7494 W art     : b6f55000-b6f57000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-27 10:03:56.986  7494  7494 W art     : b6f57000-b6f59000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : b6f59000-b6f5e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-27 10:03:56.986  7494  7494 W art     : b6f5e000-b6f5f000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-27 10:03:56.986  7494  7494 W art     : b6f5f000-b6f60000 rw-p 00000000 00:00 0 
07-27 10:03:56.986  7494  7494 W art     : bef04000-bef25000 rw-p 00000000 00:00 0          [stack]
07-27 10:03:56.986  7494  7494 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-27 10:03:57.046  7494  7494 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 10:03:57.086  7494  7494 I Radio-JNI: register_android_hardware_Radio DONE
```
