#### Test 72145431aac82a0_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
07-06 08:24:34.562   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-06 08:24:34.622   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,--------- beginning of main
07-06 08:24:35.792  2147  2147 E audit   : type=1400 msg=audit(1467786275.792:285): avc:  denied  { execmod } for  pid=7163 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-06 08:24:35.802  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:35.802  2147  2147 E audit   : type=1300 msg=audit(1467786275.792:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4033000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7163 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-06 08:24:35.802  2147  2147 E audit   : type=1327 msg=audit(1467786275.792:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-06 08:24:35.802  2147  2147 E audit   : type=1320 msg=audit(1467786275.792:285): 
07-06 08:24:35.852  2147  2147 E audit   : type=1400 msg=audit(1467786275.852:286): avc:  denied  { execmod } for  pid=7163 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-06 08:24:35.852  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:35.852  2147  2147 E audit   : type=1300 msg=audit(1467786275.852:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff7000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7163 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-06 08:24:35.852  2147  2147 E audit   : type=1327 msg=audit(1467786275.852:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-06 08:24:35.852  2147  2147 E audit   : type=1320 msg=audit(1467786275.852:286): 
07-06 08:24:35.902  2147  2147 E audit   : type=1400 msg=audit(1467786275.902:287): avc:  denied  { execmod } for  pid=7163 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-06 08:24:35.902  7163  7163 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-06 08:24:35.902  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:35.902  2147  2147 E audit   : type=1300 msg=audit(1467786275.902:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff5000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7163 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-06 08:24:35.902  2147  2147 E audit   : type=1327 msg=audit(1467786275.902:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-06 08:24:35.902  2147  2147 E audit   : type=1320 msg=audit(1467786275.902:287): 
07-06 08:24:35.902  7163  7163 D AndroidRuntime: CheckJNI is OFF
07-06 08:24:35.902  7163  7163 D AndroidRuntime: readGMSProperty: start
07-06 08:24:35.902  7163  7163 D AndroidRuntime: readGMSProperty: already setted!!
07-06 08:24:35.902  7163  7163 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 08:24:35.902  7163  7163 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 08:24:35.902  7163  7163 D AndroidRuntime: readGMSProperty: end
07-06 08:24:35.902  7163  7163 D AndroidRuntime: addProductProperty: start
07-06 08:24:35.912  7163  7163 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-06 08:24:35.912  7163  7163 W art     : aee5a000-b1d80000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-06 08:24:35.912  7163  7163 W art     : b1d80000-b3fef000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-06 08:24:35.912  7163  7163 W art     : b3fef000-b3ff0000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-06 08:24:35.912  7163  7163 W art     : b3ff0000-b3ff1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.912  7163  7163 W art     : b433a000-b4363000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-06 08:24:35.912  7163  7163 W art     : b4363000-b47b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-06 08:24:35.912  7163  7163 W art     : b47b1000-b47b2000 ---p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b47b2000-b47bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-06 08:24:35.912  7163  7163 W art     : b47bc000-b47bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-06 08:24:35.912  7163  7163 W art     : b47bd000-b47bf000 rw-p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b47bf000-b47c0000 r--p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b47c0000-b48c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-06 08:24:35.912  7163  7163 W art     : b48c3000-b48c6000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-06 08:24:35.912  7163  7163 W art     : b48c6000-b48c7000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-06 08:24:35.912  7163  7163 W art     : b48c7000-b48c8000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-06 08:24:35.912  7163  7163 W art     : b48c8000-b48c9000 r--p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b48c9000-b48e9000 r--s 00000000 00:0b 7179       /dev/__properties__
07-06 08:24:35.912  7163  7163 W art     : b48e9000-b52fa000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-06 08:24:35.912  7163  7163 W art     : b52fa000-b52fb000 ---p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b52fb000-b5344000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-06 08:24:35.912  7163  7163 W art     : b5344000-b5345000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-06 08:24:35.912  7163  7163 W art     : b5345000-b534d000 rw-p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b534d000-b534e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.912  7163  7163 W art     : b534e000-b5383000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-06 08:24:35.912  7163  7163 W art     : b5383000-b5384000 ---p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b5384000-b5385000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-06 08:24:35.912  7163  7163 W art     : b5385000-b5386000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-06 08:24:35.912  7163  7163 W art     : b5386000-b53de000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-06 08:24:35.912  7163  7163 W art     : b53de000-b53df000 ---p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b53df000-b53e0000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-06 08:24:35.912  7163  7163 W art     : b53e0000-b53e1000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-06 08:24:35.912  7163  7163 W art     : b53e2000-b53e8000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-06 08:24:35.912  7163  7163 W art     : b53e8000-b53e9000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-06 08:24:35.912  7163  7163 W art     : b53e9000-b53ea000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-06 08:24:35.912  7163  7163 W art     : b53ea000-b53ec000 rw-p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b53ed000-b53f7000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-06 08:24:35.912  7163  7163 W art     : b53f7000-b53fa000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-06 08:24:35.912  7163  7163 W art     : b53fa000-b53fb000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-06 08:24:35.912  7163  7163 W art     : b53fc000-b5413000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-06 08:24:35.912  7163  7163 W art     : b5413000-b5414000 ---p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b5414000-b5415000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-06 08:24:35.912  7163  7163 W art     : b5415000-b5416000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-06 08:24:35.912  7163  7163 W art     : b5417000-b5421000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-06 08:24:35.912  7163  7163 W art     : b5421000-b5422000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-06 08:24:35.912  7163  7163 W art     : b5422000-b5423000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-06 08:24:35.912  7163  7163 W art     : b5423000-b5427000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-06 08:24:35.912  7163  7163 W art     : b5427000-b5428000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-06 08:24:35.912  7163  7163 W art     : b5428000-b5429000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-06 08:24:35.912  7163  7163 W art     : b5429000-b543f000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-06 08:24:35.912  7163  7163 W art     : b543f000-b5440000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-06 08:24:35.912  7163  7163 W art     : b5440000-b5441000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-06 08:24:35.912  7163  7163 W art     : b5441000-b544e000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-06 08:24:35.912  7163  7163 W art     : b544e000-b544f000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-06 08:24:35.912  7163  7163 W art     : b544f000-b5450000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-06 08:24:35.912  7163  7163 W art     : b5450000-b54b0000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-06 08:24:35.912  7163  7163 W art     : b54b0000-b54b3000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-06 08:24:35.912  7163  7163 W art     : b54b3000-b54b7000 rw-p 00000000 00:00 0 
07-06 08:24:35.912  7163  7163 W art     : b54b7000-b5518000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-06 08:24:35.912  7163  7163 W art     : b5518000-b5519000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-06 08:24:35.922  7163  7163 W art     : b5519000-b5568000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-06 08:24:35.922  7163  7163 W art     : b5568000-b556a000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-06 08:24:35.922  7163  7163 W art     : b556a000-b556b000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-06 08:24:35.922  7163  7163 W art     : b556b000-b556c000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b556c000-b5573000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-06 08:24:35.922  7163  7163 W art     : b5573000-b5574000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-06 08:24:35.922  7163  7163 W art     : b5574000-b5575000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-06 08:24:35.922  7163  7163 W art     : b5576000-b5579000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-06 08:24:35.922  7163  7163 W art     : b5579000-b557a000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-06 08:24:35.922  7163  7163 W art     : b557a000-b557b000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-06 08:24:35.922  7163  7163 W art     : b557c000-b5580000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-06 08:24:35.922  7163  7163 W art     : b5580000-b5581000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5581000-b5582000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-06 08:24:35.922  7163  7163 W art     : b5582000-b5583000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-06 08:24:35.922  7163  7163 W art     : b5584000-b55a1000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-06 08:24:35.922  7163  7163 W art     : b55a1000-b55a2000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-06 08:24:35.922  7163  7163 W art     : b55a2000-b55a3000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-06 08:24:35.922  7163  7163 W art     : b55a4000-b55a9000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-06 08:24:35.922  7163  7163 W art     : b55a9000-b55aa000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-06 08:24:35.922  7163  7163 W art     : b55aa000-b55ab000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-06 08:24:35.922  7163  7163 W art     : b55ac000-b55dd000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-06 08:24:35.922  7163  7163 W art     : b55dd000-b55e0000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-06 08:24:35.922  7163  7163 W art     : b55e0000-b55e1000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-06 08:24:35.922  7163  7163 W art     : b55e2000-b561d000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-06 08:24:35.922  7163  7163 W art     : b561d000-b561e000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-06 08:24:35.922  7163  7163 W art     : b561e000-b561f000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-06 08:24:35.922  7163  7163 W art     : b5620000-b5627000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-06 08:24:35.922  7163  7163 W art     : b5627000-b5628000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5628000-b5629000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-06 08:24:35.922  7163  7163 W art     : b5629000-b562a000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-06 08:24:35.922  7163  7163 W art     : b562a000-b562b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b562b000-b5642000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-06 08:24:35.922  7163  7163 W art     : b5642000-b5643000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5643000-b5646000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-06 08:24:35.922  7163  7163 W art     : b5646000-b5647000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-06 08:24:35.922  7163  7163 W art     : b5647000-b5666000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-06 08:24:35.922  7163  7163 W art     : b5666000-b5667000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-06 08:24:35.922  7163  7163 W art     : b5667000-b5668000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-06 08:24:35.922  7163  7163 W art     : b5668000-b56a6000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-06 08:24:35.922  7163  7163 W art     : b56a6000-b56a7000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b56a7000-b56a9000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-06 08:24:35.922  7163  7163 W art     : b56a9000-b56aa000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-06 08:24:35.922  7163  7163 W art     : b56ab000-b56b2000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-06 08:24:35.922  7163  7163 W art     : b56b2000-b56b3000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-06 08:24:35.922  7163  7163 W art     : b56b3000-b56b4000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-06 08:24:35.922  7163  7163 W art     : b56b5000-b56b8000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-06 08:24:35.922  7163  7163 W art     : b56b8000-b56b9000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-06 08:24:35.922  7163  7163 W art     : b56b9000-b56ba000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-06 08:24:35.922  7163  7163 W art     : b56ba000-b56c0000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-06 08:24:35.922  7163  7163 W art     : b56c0000-b56c1000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b56c1000-b56c2000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-06 08:24:35.922  7163  7163 W art     : b56c2000-b56c3000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-06 08:24:35.922  7163  7163 W art     : b56c3000-b56cc000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-06 08:24:35.922  7163  7163 W art     : b56cc000-b56cd000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-06 08:24:35.922  7163  7163 W art     : b56cd000-b56ce000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-06 08:24:35.922  7163  7163 W art     : b56ce000-b575f000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-06 08:24:35.922  7163  7163 W art     : b575f000-b5760000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5760000-b576b000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-06 08:24:35.922  7163  7163 W art     : b576b000-b576c000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-06 08:24:35.922  7163  7163 W art     : b576d000-b577f000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-06 08:24:35.922  7163  7163 W art     : b577f000-b5780000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-06 08:24:35.922  7163  7163 W art     : b5780000-b5781000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-06 08:24:35.922  7163  7163 W art     : b5782000-b5787000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-06 08:24:35.922  7163  7163 W art     : b5787000-b5788000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-06 08:24:35.922  7163  7163 W art     : b5788000-b5789000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-06 08:24:35.922  7163  7163 W art     : b578a000-b57f7000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-06 08:24:35.922  7163  7163 W art     : b57f7000-b57f8000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b57f8000-b57fa000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-06 08:24:35.922  7163  7163 W art     : b57fa000-b57fb000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-06 08:24:35.922  7163  7163 W art     : b57fb000-b57fc000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b57fc000-b5803000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-06 08:24:35.922  7163  7163 W art     : b5803000-b5804000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-06 08:24:35.922  7163  7163 W art     : b5804000-b5805000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-06 08:24:35.922  7163  7163 W art     : b5806000-b5886000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-06 08:24:35.922  7163  7163 W art     : b5886000-b5887000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5887000-b5888000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-06 08:24:35.922  7163  7163 W art     : b5888000-b5889000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-06 08:24:35.922  7163  7163 W art     : b5889000-b58a0000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b58a0000-b58d7000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-06 08:24:35.922  7163  7163 W art     : ib/libqc-opt.so
07-06 08:24:35.922  7163  7163 W art     : b58d7000-b58d8000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-06 08:24:35.922  7163  7163 W art     : b58d8000-b58d9000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-06 08:24:35.922  7163  7163 W art     : b58d9000-b58f5000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-06 08:24:35.922  7163  7163 W art     : b58f5000-b58f6000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-06 08:24:35.922  7163  7163 W art     : b58f6000-b58f7000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-06 08:24:35.922  7163  7163 W art     : b58f8000-b5959000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-06 08:24:35.922  7163  7163 W art     : b5959000-b595b000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-06 08:24:35.922  7163  7163 W art     : b595b000-b595c000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-06 08:24:35.922  7163  7163 W art     : b595d000-b5984000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-06 08:24:35.922  7163  7163 W art     : b5984000-b5985000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5985000-b5986000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-06 08:24:35.922  7163  7163 W art     : b5986000-b5987000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-06 08:24:35.922  7163  7163 W art     : b5988000-b5990000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-06 08:24:35.922  7163  7163 W art     : b5990000-b5992000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-06 08:24:35.922  7163  7163 W art     : b5992000-b5993000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-06 08:24:35.922  7163  7163 W art     : b5994000-b5997000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-06 08:24:35.922  7163  7163 W art     : b5997000-b5998000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-06 08:24:35.922  7163  7163 W art     : b5998000-b5999000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-06 08:24:35.922  7163  7163 W art     : b5999000-b599d000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-06 08:24:35.922  7163  7163 W art     : b599d000-b599e000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b599e000-b599f000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-06 08:24:35.922  7163  7163 W art     : b599f000-b59a0000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-06 08:24:35.922  7163  7163 W art     : b59a0000-b59b0000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-06 08:24:35.922  7163  7163 W art     : b59b0000-b59b1000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-06 08:24:35.922  7163  7163 W art     : b59b1000-b59b2000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-06 08:24:35.922  7163  7163 W art     : b59b2000-b59f8000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b59f8000-b5a01000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-06 08:24:35.922  7163  7163 W art     : b5a01000-b5a02000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-06 08:24:35.922  7163  7163 W art     : b5a02000-b5a03000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-06 08:24:35.922  7163  7163 W art     : b5a04000-b5a09000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-06 08:24:35.922  7163  7163 W art     : b5a09000-b5a0a000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-06 08:24:35.922  7163  7163 W art     : b5a0a000-b5a0b000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-06 08:24:35.922  7163  7163 W art     : b5a0b000-b5a0e000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-06 08:24:35.922  7163  7163 W art     : b5a0e000-b5a0f000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5a0f000-b5a10000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-06 08:24:35.922  7163  7163 W art     : b5a10000-b5a11000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-06 08:24:35.922  7163  7163 W art     : b5a12000-b5a2a000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-06 08:24:35.922  7163  7163 W art     : b5a2a000-b5a2b000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5a2b000-b5a2c000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-06 08:24:35.922  7163  7163 W art     : b5a2c000-b5a2d000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-06 08:24:35.922  7163  7163 W art     : b5a2e000-b5bc8000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-06 08:24:35.922  7163  7163 W art     : b5bc8000-b5bc9000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5bc9000-b5bd6000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-06 08:24:35.922  7163  7163 W art     : b5bd6000-b5bd7000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-06 08:24:35.922  7163  7163 W art     : b5bd7000-b5bdb000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-06 08:24:35.922  7163  7163 W art     : b5bdb000-b5bdc000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5bdc000-b5bdd000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-06 08:24:35.922  7163  7163 W art     : b5bdd000-b5bde000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-06 08:24:35.922  7163  7163 W art     : b5bde000-b5bf1000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-06 08:24:35.922  7163  7163 W art     : b5bf1000-b5bf2000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-06 08:24:35.922  7163  7163 W art     : b5bf2000-b5bf3000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-06 08:24:35.922  7163  7163 W art     : b5bf4000-b5c3f000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-06 08:24:35.922  7163  7163 W art     : b5c3f000-b5c40000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-06 08:24:35.922  7163  7163 W art     : b5c40000-b5c41000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-06 08:24:35.922  7163  7163 W art     : b5c41000-b5c43000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5c43000-b5c44000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:24:35.922  7163  7163 W art     : b5c44000-b5c55000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-06 08:24:35.922  7163  7163 W art     : b5c55000-b5c56000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5c56000-b5c57000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-06 08:24:35.922  7163  7163 W art     : b5c57000-b5c58000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-06 08:24:35.922  7163  7163 W art     : b5c59000-b5c63000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-06 08:24:35.922  7163  7163 W art     : b5c63000-b5c65000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-06 08:24:35.922  7163  7163 W art     : b5c65000-b5c66000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-06 08:24:35.922  7163  7163 W art     : b5c66000-b5c7f000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-06 08:24:35.922  7163  7163 W art     : b5c7f000-b5c80000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-06 08:24:35.922  7163  7163 W art     : b5c80000-b5c83000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-06 08:24:35.922  7163  7163 W art     : b5c83000-b5c87000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5c87000-b5cfb000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-06 08:24:35.922  7163  7163 W art     : b5cfb000-b5cfc000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5cfc000-b5cff000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-06 08:24:35.922  7163  7163 W art     : b5cff000-b5d00000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-06 08:24:35.922  7163  7163 W art     : b5d01000-b5d04000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-06 08:24:35.922  7163  7163 W art     : b5d04000-b5d05000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-06 08:24:35.922  7163  7163 W art     : b5d05000-b5d06000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-06 08:24:35.922  7163  7163 W art     : b5d06000-b5d07000 r--p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5d07000-b5d0c000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-06 08:24:35.922  7163  7163 W art     : b5d0c000-b5d0d000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-06 08:24:35.922  7163  7163 W art     : b5d0d000-b5d0e000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-06 08:24:35.922  7163  7163 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b5d0f000-b5d12000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-06 08:24:35.922  7163  7163 W art     : b5d12000-b5d13000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-06 08:24:35.922  7163  7163 W art     : b5d13000-b5d14000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-06 08:24:35.922  7163  7163 W art     : b5d14000-b5d15000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b5d15000-b5d19000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-06 08:24:35.922  7163  7163 W art     : b5d19000-b5d1a000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-06 08:24:35.922  7163  7163 W art     : b5d1a000-b5d1b000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-06 08:24:35.922  7163  7163 W art     : b5d1b000-b5d1c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:24:35.922  7163  7163 W art     : b5d1c000-b5d20000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-06 08:24:35.922  7163  7163 W art     : b5d20000-b5d21000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-06 08:24:35.922  7163  7163 W art     : b5d21000-b5d22000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-06 08:24:35.922  7163  7163 W art     : b5d22000-b5d23000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b5d23000-b5d31000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-06 08:24:35.922  7163  7163 W art     : b5d31000-b5d32000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b5d32000-b5d33000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-06 08:24:35.922  7163  7163 W art     : b5d33000-b5d34000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-06 08:24:35.922  7163  7163 W art     : b5d34000-b5d3e000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-06 08:24:35.922  7163  7163 W art     : b5d3e000-b5d41000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-06 08:24:35.922  7163  7163 W art     : b5d41000-b5d42000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-06 08:24:35.922  7163  7163 W art     : b5d42000-b5d43000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b5d43000-b5d4d000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-06 08:24:35.922  7163  7163 W art     : b5d4d000-b5d50000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-06 08:24:35.922  7163  7163 W art     : b5d50000-b5d51000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-06 08:24:35.922  7163  7163 W art     : b5d51000-b5d55000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-06 08:24:35.922  7163  7163 W art     : b5d55000-b5d56000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-06 08:24:35.922  7163  7163 W art     : b5d56000-b5d57000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-06 08:24:35.922  7163  7163 W art     : b5d57000-b5d58000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b5d58000-b5d65000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-06 08:24:35.922  7163  7163 W art     : b5d65000-b5d67000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-06 08:24:35.922  7163  7163 W art     : b5d67000-b5d68000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-06 08:24:35.922  7163  7163 W art     : b5d68000-b617a000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-06 08:24:35.922  7163  7163 W art     : b617a000-b617b000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b617b000-b6184000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-06 08:24:35.922  7163  7163 W art     : b6184000-b6188000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-06 08:24:35.922  7163  7163 W art     : b6188000-b6189000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6189000-b6190000 r-xp 00000000 b3:17 2571       /system/lib/libaud
07-06 08:24:35.922  7163  7163 W art     : ioutils.so
07-06 08:24:35.922  7163  7163 W art     : b6190000-b6191000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-06 08:24:35.922  7163  7163 W art     : b6191000-b6192000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-06 08:24:35.922  7163  7163 W art     : b6192000-b6193000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6193000-b61ae000 r-xp 00000000
07-06 08:24:35.922  7163  7163 W art     :  b3:17 1184       /system/lib/libz.so
07-06 08:24:35.922  7163  7163 W art     : b61ae000-b61af000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-06 08:24:35.922  7163  7163 W art     : b61af000-b61b0000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-06 08:24:35.922  7163  7163 W art     : b61b0000-b61b1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b61b1000-b61fd000 r-xp 00000000 b3:17 994        
07-06 08:24:35.922  7163  7163 W art     : /system/lib/libharfbuzz_ng.so
07-06 08:24:35.922  7163  7163 W art     : b61fd000-b61fe000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b61fe000-b61ff000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-06 08:24:35.922  7163  7163 W art     : b61ff000-b6200000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-06 08:24:35.922  7163  7163 W art     : b6200000-b6201000 r--p 00000000 00:00 0          [anon:li
07-06 08:24:35.922  7163  7163 W art     : nker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6201000-b6205000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-06 08:24:35.922  7163  7163 W art     : b6205000-b6206000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6206000-b6207000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-06 08:24:35.922  7163  7163 W art     : b6207000-b6208000 rw-p 00005000 b3:17 2681       /system/lib/libu
07-06 08:24:35.922  7163  7163 W art     : sbhost.so
07-06 08:24:35.922  7163  7163 W art     : b6208000-b6240000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-06 08:24:35.922  7163  7163 W art     : b6240000-b6241000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-06 08:24:35.922  7163  7163 W art     : b6241000-b6242000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-06 08:24:35.922  7163  7163 W art     : b6242000-b6243000 r--p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     :          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6243000-b62e1000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-06 08:24:35.922  7163  7163 W art     : b62e1000-b62e2000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b62e2000-b6300000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-06 08:24:35.922  7163  7163 W art     : b6300000-b6301000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
07-06 08:24:35.922  7163  7163 W art     : .so
07-06 08:24:35.922  7163  7163 W art     : b6301000-b6474000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-06 08:24:35.922  7163  7163 W art     : b6474000-b647f000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-06 08:24:35.922  7163  7163 W art     : b647f000-b6480000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-06 08:24:35.922  7163  7163 W art     : b6480000-b6597000 r-xp 00000000
07-06 08:24:35.922  7163  7163 W art     :  b3:17 2041       /system/lib/libicuuc.so
07-06 08:24:35.922  7163  7163 W art     : b6597000-b65a2000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-06 08:24:35.922  7163  7163 W art     : b65a2000-b65a3000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-06 08:24:35.922  7163  7163 W art     : b65a3000-b65a7000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b65a7000-b65cb000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
07-06 08:24:35.922  7163  7163 W art     : o
07-06 08:24:35.922  7163  7163 W art     : b65cb000-b65cd000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-06 08:24:35.922  7163  7163 W art     : b65cd000-b65ce000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-06 08:24:35.922  7163  7163 W art     : b65ce000-b6674000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-06 08:24:35.922  7163  7163 W art     : b6674000-b6681000 r--p 000a5000 b3:17 13
07-06 08:24:35.922  7163  7163 W art     : 2        /system/lib/libcrypto.so
07-06 08:24:35.922  7163  7163 W art     : b6681000-b6682000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-06 08:24:35.922  7163  7163 W art     : b6682000-b6683000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6683000-b66d6000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-06 08:24:35.922  7163  7163 W art     : b66d6000-b66d7000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b66d7000-b66d8000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-06 08:24:35.922  7163  7163 W art     : b66d8000-b66d9000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-06 08:24:35.922  7163  7163 W art     : b66d9000-b66de000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b66de000-b66f0000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-06 08:24:35.922  7163  7163 W art     : b66f0000-b66f1000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b66f1000-b66f2000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-06 08:24:35.922  7163  7163 W art     : b66f2000-b66f3000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-06 08:24:35.922  7163  7163 W art     : b66f3000-b66fa000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-06 08:24:35.922  7163  7163 W art     : b66fa000-b66fb000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-06 08:24:35.922  7163  7163 W art     : b66fb000-b66fc000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-06 08:24:35.922  7163  7163 W art     : b66fc000-b66fd000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b66fd000-b6700000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-06 08:24:35.922  7163  7163 W art     : b6700000-b6701000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-06 08:24:35.922  7163  7163 W art     : b6701000-b6702000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-06 08:24:35.922  7163  7163 W art     : b6702000-b6706000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-06 08:24:35.922  7163  7163 W art     : b6706000-b6707000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-06 08:24:35.922  7163  7163 W art     : b6707000-b6708000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-06 08:24:35.922  7163  7163 W art     : b6708000-b6716000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-06 08:24:35.922  7163  7163 W art     : b6716000-b6717000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6717000-b6718000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-06 08:24:35.922  7163  7163 W art     : b6718000-b6719000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-06 08:24:35.922  7163  7163 W art     : b6719000-b6722000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-06 08:24:35.922  7163  7163 W art     : b6722000-b6723000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-06 08:24:35.922  7163  7163 W art     : b6723000-b6724000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-06 08:24:35.922  7163  7163 W art     : b6724000-b678a000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-06 08:24:35.922  7163  7163 W art     : b678a000-b678b000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b678b000-b678d000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-06 08:24:35.922  7163  7163 W art     : b678d000-b6796000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-06 08:24:35.922  7163  7163 W art     : b6796000-b6799000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6799000-b6830000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-06 08:24:35.922  7163  7163 W art     : b6830000-b6832000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-06 08:24:35.922  7163  7163 W art     : b6832000-b6833000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-06 08:24:35.922  7163  7163 W art     : b6833000-b6834000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6834000-b6b55000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-06 08:24:35.922  7163  7163 W art     : b6b55000-b6b56000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6b56000-b6b71000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-06 08:24:35.922  7163  7163 W art     : b6b71000-b6b75000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-06 08:24:35.922  7163  7163 W art     : b6b75000-b6b7a000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6b7a000-b6b82000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-06 08:24:35.922  7163  7163 W art     : b6b82000-b6b83000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-06 08:24:35.922  7163  7163 W art     : b6b83000-b6b84000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-06 08:24:35.922  7163  7163 W art     : b6b84000-b6bb2000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-06 08:24:35.922  7163  7163 W art     : b6bb2000-b6bb3000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6bb3000-b6bba000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-06 08:24:35.922  7163  7163 W art     : b6bba000-b6bbb000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-06 08:24:35.922  7163  7163 W art     : b6bbb000-b6c01000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-06 08:24:35.922  7163  7163 W art     : b6c01000-b6c02000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6c02000-b6c05000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-06 08:24:35.922  7163  7163 W art     : b6c05000-b6c06000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-06 08:24:35.922  7163  7163 W art     : b6c06000-b6c21000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-06 08:24:35.922  7163  7163 W art     : b6c21000-b6c25000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-06 08:24:35.922  7163  7163 W art     : b6c25000-b6c26000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-06 08:24:35.922  7163  7163 W art     : b6c26000-b6c73000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-06 08:24:35.922  7163  7163 W art     : b6c73000-b6c74000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6c74000-b6c80000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-06 08:24:35.922  7163  7163 W art     : b6c80000-b6c81000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-06 08:24:35.922  7163  7163 W art     : b6c81000-b6c8e000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-06 08:24:35.922  7163  7163 W art     : b6c8e000-b6c8f000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6c8f000-b6c90000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-06 08:24:35.922  7163  7163 W art     : b6c90000-b6c91000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-06 08:24:35.922  7163  7163 W art     : b6c91000-b6c99000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-06 08:24:35.922  7163  7163 W art     : b6c99000-b6c9a000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6c9a000-b6c9b000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-06 08:24:35.922  7163  7163 W art     : b6c9b000-b6c9c000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-06 08:24:35.922  7163  7163 W art     : b6c9c000-b6ca3000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-06 08:24:35.922  7163  7163 W art     : b6ca3000-b6ca4000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-06 08:24:35.922  7163  7163 W art     : b6ca4000-b6ca5000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-06 08:24:35.922  7163  7163 W art     : b6ca5000-b6cb9000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-06 08:24:35.922  7163  7163 W art     : b6cb9000-b6cbb000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-06 08:24:35.922  7163  7163 W art     : b6cbb000-b6cbc000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-06 08:24:35.922  7163  7163 W art     : b6cbc000-b6ce4000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-06 08:24:35.922  7163  7163 W art     : b6ce4000-b6ce6000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-06 08:24:35.922  7163  7163 W art     : b6ce6000-b6ce7000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-06 08:24:35.922  7163  7163 W art     : b6ce7000-b6cea000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-06 08:24:35.922  7163  7163 W art     : b6cea000-b6ceb000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-06 08:24:35.922  7163  7163 W art     : b6ceb000-b6cec000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-06 08:24:35.922  7163  7163 W art     : b6cec000-b6cf5000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-06 08:24:35.922  7163  7163 W art     : b6cf5000-b6cf6000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-06 08:24:35.922  7163  7163 W art     : b6cf6000-b6cf7000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-06 08:24:35.922  7163  7163 W art     : b6cf7000-b6d17000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-06 08:24:35.922  7163  7163 W art     : b6d17000-b6d18000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-06 08:24:35.922  7163  7163 W art     : b6d18000-b6d19000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-06 08:24:35.922  7163  7163 W art     : b6d19000-b6d8c000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-06 08:24:35.922  7163  7163 W art     : b6d8c000-b6d90000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-06 08:24:35.922  7163  7163 W art     : b6d90000-b6d93000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-06 08:24:35.922  7163  7163 W art     : b6d93000-b6d9d000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6d9d000-b6e25000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-06 08:24:35.922  7163  7163 W art     : b6e25000-b6e26000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6e26000-b6e2a000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-06 08:24:35.922  7163  7163 W art     : b6e2a000-b6e2b000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-06 08:24:35.922  7163  7163 W art     : b6e2b000-b6e2c000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6e2c000-b6e55000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-06 08:24:35.922  7163  7163 W art     : b6e55000-b6e56000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6e56000-b6e59000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-06 08:24:35.922  7163  7163 W art     : b6e59000-b6e5a000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-06 08:24:35.922  7163  7163 W art     : b6e5a000-b6f34000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-06 08:24:35.922  7163  7163 W art     : b6f34000-b6f3b000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-06 08:24:35.922  7163  7163 W art     : b6f3b000-b6f43000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-06 08:24:35.922  7163  7163 W art     : b6f43000-b6f44000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6f44000-b6f45000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:24:35.922  7163  7163 W art     : b6f45000-b6f46000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-06 08:24:35.922  7163  7163 W art     : b6f46000-b6f47000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6f47000-b6f4a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6f4a000-b6f6f000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-06 08:24:35.922  7163  7163 W art     : b6f6f000-b6f70000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6f70000-b6f77000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-06 08:24:35.922  7163  7163 W art     : b6f77000-b6f78000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-06 08:24:35.922  7163  7163 W art     : b6f78000-b6f7f000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-06 08:24:35.922  7163  7163 W art     : b6f7f000-b6f80000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-06 08:24:35.922  7163  7163 W art     : b6f80000-b6f81000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-06 08:24:35.922  7163  7163 W art     : b6f81000-b6f82000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6f82000-b6f9a000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-06 08:24:35.922  7163  7163 W art     : b6f9a000-b6f9b000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6f9b000-b6f9c000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-06 08:24:35.922  7163  7163 W art     : b6f9c000-b6f9d000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-06 08:24:35.922  7163  7163 W art     : b6f9d000-b6fab000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-06 08:24:35.922  7163  7163 W art     : b6fab000-b6fac000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6fac000-b6fad000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-06 08:24:35.922  7163  7163 W art     : b6fad000-b6fae000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-06 08:24:35.922  7163  7163 W art     : b6fae000-b6faf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:24:35.922  7163  7163 W art     : b6faf000-b6fb1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6fb1000-b6fb2000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6fb2000-b6fb3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:24:35.922  7163  7163 W art     : b6fb3000-b6fb4000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-06 08:24:35.922  7163  7163 W art     : b6fb4000-b6fb5000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:24:35.922  7163  7163 W art     : b6fb5000-b6fd5000 r--s 00000000 00:0b 7179       /dev/__properties__
07-06 08:24:35.922  7163  7163 W art     : b6fd5000-b6fd6000 r--p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6fd6000-b6fd7000 ---p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6fd7000-b6fd9000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-06 08:24:35.922  7163  7163 W art     : b6fd9000-b6fda000 r-xp 00000000 00:00 0          [sigpage]
07-06 08:24:35.922  7163  7163 W art     : b6fda000-b6ff5000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-06 08:24:35.922  7163  7163 W art     : b6ff5000-b6ff6000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-06 08:24:35.922  7163  7163 W art     : b6ff6000-b6ff8000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-06 08:24:35.922  7163  7163 W art     : b6ff8000-b6ffa000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : b6ffa000-b6fff000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-06 08:24:35.922  7163  7163 W art     : b6fff000-b7000000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-06 08:24:35.922  7163  7163 W art     : b7000000-b7001000 rw-p 00000000 00:00 0 
07-06 08:24:35.922  7163  7163 W art     : be873000-be894000 rw-p 00000000 00:00 0          [stack]
07-06 08:24:35.922  7163  7163 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-06 08:24:35.992  7163  7163 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-06 08:24:36.042  7163  7163 I Radio-JNI: register_android_hardware_Radio DONE
07-06 08:24:36.052  7163  7163 E AffinityControl: AffinityControl: registerfunction enter
07-06 08:24:36.072  7163  7163 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-06 08:24:36.082   768  2251 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-06 08:24:36.092   768  2251 D ActivityManager: mDVFSHelper.acquire()
07-06 08:24:36.092   768  2251 V WindowManager: addAppToken: AppWindowToken{7c2050d token=Token{30b93a4 ActivityRecord{a147237 u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
07-06 08:24:36.112   768   903 D SecWifiDisplayUtil: Metadata value : none
07-06 08:24:36.112   768   903 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ebfc8c5 V.E...... R.....ID 0,0-0,0}
07-06 08:24:36.112   768   903 D ISSUE_DEBUG: InputChannelName : 5f5f14b Starting com.test.thalitest
07-06 08:24:36.112   768  2251 I ActivityManager: Start proc 7178:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-06 08:24:36.112  7178  7178 E Zygote  : v2
07-06 08:24:36.112  7178  7178 I libpersona: KNOX_SDCARD checking this for 10004
07-06 08:24:36.112  7178  7178 I libpersona: KNOX_SDCARD not a persona
07-06 08:24:36.112  7178  7178 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-06 08:24:36.112  7178  7178 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:36.122  7178  7178 E Zygote  : accessInfo : 0
07-06 08:24:36.122   768  2251 D InputDispatcher: Focused application set to: xxxx
07-06 08:24:36.122  7178  7178 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-06 08:24:36.122   768  2251 D InputDispatcher: Focus left window: 3699
07-06 08:24:36.122   768   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{210fbe1 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-06 08:24:36.122   768  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-06 08:24:36.122  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-06 08:24:36.122  7163  7163 D AndroidRuntime: Shutting down VM
07-06 08:24:36.132   294   294 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
07-06 08:24:36.152  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:24:36.152  7178  7178 D ActivityThread: Added TimaKeyStore provider
07-06 08:24:36.152   768  1220 V WindowOrientationListener: setCurrentAppOrientation :-1
07-06 08:24:36.152   768  1220 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-06 08:24:36.152   768   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:768 uid:1000
07-06 08:24:36.152   768   903 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 08:24:36.152   768   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:768 uid:1000
07-06 08:24:36.152   768   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-06 08:24:36.152   768   903 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-06 08:24:36.162   768   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5f5f14b u0 d0 Starting com.test.thalitest}
07-06 08:24:36.162  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-06 08:24:36.172   768  1220 D ActivityManager:  Launching com.test.thalitest, updated priority
07-06 08:24:36.172   768   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-06 08:24:36.182  1679  1877 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-06 08:24:36.182  1679  1679 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-06 08:24:36.202   768   903 V WindowStateAnimator: Finishing drawing window Window{5f5f14b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-06 08:24:36.212   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
07-06 08:24:36.212   294   338 I SurfaceFlinger: id=15 Removed VSBConnecti (5/11)
07-06 08:24:36.212   294   344 I SurfaceFlinger: id=15 Removed VSBConnecti (-2/11)
07-06 08:24:36.212   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f93a4
07-06 08:24:36.222  3699  3699 V ActivityThread: updateVisibility : ActivityRecord{67720ae token=android.os.BinderProxy@53e4898 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-06 08:24:36.222   294   338 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
07-06 08:24:36.222   294   338 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
07-06 08:24:36.222   294   344 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
07-06 08:24:36.222   294  5129 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
07-06 08:24:36.232  1679  1679 V ActivityThread: updateVisibility : ActivityRecord{ddca95b token=android.os.BinderProxy@40a9991 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-06 08:24:36.232   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f93a4
07-06 08:24:36.232  1679  1679 D Launcher: onTrimMemory. Level: 20
07-06 08:24:36.242  2302  2316 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-06 08:24:36.252   294  5130 D libEGL  : eglTerminate EGLDisplay = 0xb29b664c
07-06 08:24:36.252   294  1362 I SurfaceFlinger: id=14 Removed VSBConnecti (5/9)
07-06 08:24:36.252   294   338 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/9)
07-06 08:24:36.262   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f93a4
,07-06 08:24:36.482   768  1220 I WindowManager: Screenshot max retries 4 of Token{30b93a4 ActivityRecord{a147237 u0 com.test.thalitest/.MainActivity t64}} appWin=Window{5f5f14b u0 d0 Starting com.test.thalitest} drawState=4
07-06 08:24:36.502   768  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-06 08:24:36.512  7178  7178 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-06 08:24:36.522   768  3441 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-06 08:24:36.552  7178  7178 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-06 08:24:36.552  7178  7178 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-06 08:24:36.572  7178  7178 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
07-06 08:24:36.602  7178  7178 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
07-06 08:24:36.602  7178  7178 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-06 08:24:36.612  7178  7178 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 2603-2606)
07-06 08:24:36.612  7178  7178 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-06 08:24:36.632  7178  7178 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7b0ec3a}
07-06 08:24:36.632  7178  7178 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-06 08:24:36.632  7178  7178 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 08:24:36.642  7178  7178 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-06 08:24:36.642  7178  7206 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-06 08:24:36.662  7178  7178 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-06 08:24:36.662  7178  7178 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-06 08:24:36.662  7178  7178 I Adreno-EGL: Build Date: 01/28/16 Thu
07-06 08:24:36.662  7178  7178 I Adreno-EGL: Local Branch: ss
07-06 08:24:36.662  7178  7178 I Adreno-EGL: Remote Branch: 
07-06 08:24:36.662  7178  7178 I Adreno-EGL: Local Patches: 
07-06 08:24:36.662  7178  7178 I Adreno-EGL: Reconstruct Branch: 
07-06 08:24:36.662  7178  7178 D libEGL  : eglInitialize EGLDisplay = 0xbe83ddac
07-06 08:24:36.702   768  1421 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
07-06 08:24:36.702   768  1421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
07-06 08:24:36.742  7178  7178 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
07-06 08:24:36.752  7178  7178 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-06 08:24:36.752  7178  7178 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-06 08:24:36.752  7178  7178 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
07-06 08:24:36.752  7178  7178 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
07-06 08:24:36.772  7178  7178 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
07-06 08:24:36.782  7178  7178 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-06 08:24:36.882  7178  7178 D SecWifiDisplayUtil: Metadata value : none
07-06 08:24:36.882  7178  7178 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2a420a8 I.E...... R.....ID 0,0-0,0}
07-06 08:24:36.892  7178  7232 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-06 08:24:36.892   768  1494 D ISSUE_DEBUG: InputChannelName : 4997f9c com.test.thalitest/com.test.thalitest.MainActivity
07-06 08:24:36.902   768  1421 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-06 08:24:36.902   768  1421 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:24:36.902   768   768 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:24:36.902   768   768 I KnoxTimeoutHandler: Shared devices show user statefalse
07-06 08:24:36.922  7178  7178 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7178
07-06 08:24:36.922   768  1494 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7178 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:24:36.922   768  1329 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-06 08:24:36.922   768  1329 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-06 08:24:36.922   768  1329 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-06 08:24:36.922   768  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:36.922   768  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:36.922   768  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:36.922   768  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-06 08:24:36.922   768  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:36.922   768  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-06 08:24:36.922   768  1329 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:24:36.922  7178  7206 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
07-06 08:24:36.932  7178  7178 D SecWifiDisplayUtil: Metadata value : none
07-06 08:24:36.942   294   294 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
07-06 08:24:36.962   768  1673 D InputDispatcher: Focus entered window: 7178
07-06 08:24:36.962   768   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:768 uid:1000
07-06 08:24:36.962   768   903 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 08:24:36.962   768   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:768 uid:1000
07-06 08:24:36.962   768   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-06 08:24:36.962  7178  7232 D libEGL  : eglInitialize EGLDisplay = 0x9d67f7c4
07-06 08:24:36.962  7178  7232 I OpenGLRenderer: Initialized EGL, version 1.4
07-06 08:24:37.002  7178  7178 V ActivityThread: updateVisibility : ActivityRecord{d407e43 token=android.os.BinderProxy@a9ac0cb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-06 08:24:37.012  7178  7178 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-06 08:24:37.042   768  2239 V WindowStateAnimator: Finishing drawing window Window{4997f9c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-06 08:24:37.042  7178  7178 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-06 08:24:37.042  7178  7178 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-06 08:24:37.042   768  2223 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-06 08:24:37.042   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
07-06 08:24:37.042   768   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:24:37.052   768   768 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:24:37.052   768   768 I KnoxTimeoutHandler: SD activityfalse
07-06 08:24:37.052   768   903 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +567ms (total +955ms)
07-06 08:24:37.062  7178  7178 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-06 08:24:37.062   768   903 D ActivityManager: mDVFSHelper.release()
07-06 08:24:37.062   768   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a147237 u0 com.test.thalitest/.MainActivity t64} time:293056
07-06 08:24:37.062   768   903 D ViewRootImpl: #3 mView = null
07-06 08:24:37.062   294  5130 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
07-06 08:24:37.062   294   344 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
07-06 08:24:37.072   768  1220 V WindowStateAnimator: Finishing drawing window Window{4997f9c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
07-06 08:24:37.072   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f93a4
07-06 08:24:37.072   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
07-06 08:24:37.082  7178  7178 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a9ac0cb time:293074
07-06 08:24:37.082  7178  7239 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-06 08:24:37.082  7178  7239 D libEGL  : eglInitialize EGLDisplay = 0x9bdef3ec
07-06 08:24:37.132  7178  7178 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7178
07-06 08:24:37.262  7178  7178 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-06 08:24:37.352  7178  7250 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1698703056
07-06 08:24:37.352  7178  7250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 08:24:37.352  7178  7250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 08:24:37.352  7178  7250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 08:24:37.352  7178  7250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 08:24:37.352  7178  7250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-06 08:24:37.352  7178  7250 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30ea331 added. We now have 1 listener(s)
07-06 08:24:37.352  7178  7250 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
07-06 08:24:37.352  7178  7250 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
07-06 08:24:37.352  7178  7250 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-06 08:24:37.362  7178  7250 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-06 08:24:37.362   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:24:37.362   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:24:37.362   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 08:24:37.362  7178  7250 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f228584 added. We now have 1 listener(s)
07-06 08:24:37.362  7178  7250 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-06 08:24:37.372  7178  7250 D BluetoothAdapter: STATE_ON
07-06 08:24:37.372  7178  7250 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-06 08:24:37.372  7178  7250 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-06 08:24:37.372  7178  7250 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-06 08:24:37.372  7178  7250 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-06 08:24:37.372  7178  7250 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-06 08:24:37.372  7178  7250 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-06 08:24:37.372  7178  7250 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
07-06 08:24:37.382  7178  7250 D BluetoothAdapter: STATE_ON
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 08:24:37.382  7178  7250 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-06 08:24:37.382  7178  7250 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 08:24:37.382  7178  7250 D io.jxcore.node.ConnectivityMonitor: start: OK
07-06 08:24:37.382  7178  7178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-06 08:24:37.392  7178  7178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-06 08:24:37.392  7178  7250 I io.jxcore.node.LifeCycleMonitor: start: OK
07-06 08:24:37.412  7178  7178 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-06 08:24:37.442   768  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:24:37.442   768  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-06 08:24:37.442   768  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-06 08:24:37.442   768  1693 D BatteryService: stay LED for fully charged
07-06 08:24:37.442   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:24:37.442   768   768 I MotionRecognitionService: Plugged
07-06 08:24:37.442   768   768 D MotionRecognitionService:   cableConnection= 1
07-06 08:24:37.442   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:24:37.442   768   768 D MotionRecognitionService: skip setTransmitPower. 
07-06 08:24:37.442  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:24:37.442  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:24:37.442  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 08:24:37.452  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:24:37.452  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:24:37.462  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:24:37.462  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:24:37.472  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:24:37.502   768  3442 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-06 08:24:37.902  1449  1449 D Recents : onTaskStackChanged
,07-06 08:24:37.902  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-06 08:24:38.232  7178  7254 W jxcore-log: Initializing JXcore engine
,07-06 08:24:38.242  7178  7254 W jxcore-log: JXcore engine is ready
,07-06 08:24:38.282  2147  2147 E audit   : type=1400 msg=audit(1467786278.282:288): avc:  denied  { ioctl } for  pid=7254 comm="Thread-999" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-06 08:24:38.282  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-06 08:24:38.282  2147  2147 E audit   : type=1300 msg=audit(1467786278.282:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=98fe23c8 items=0 ppid=368 ppcomm=main pid=7254 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-999" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-06 08:24:38.282  2147  2147 E audit   : type=1327 msg=audit(1467786278.282:288): proctitle="com.test.thalitest"
07-06 08:24:38.282  2147  2147 E audit   : type=1320 msg=audit(1467786278.282:288): 
07-06 08:24:38.282  2147  2147 E audit   : type=1400 msg=audit(1467786278.282:289): avc:  denied  { ioctl } for  pid=7254 comm="Thread-999" path="socket:[44758]" dev="sockfs" ino=44758 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-06 08:24:38.282  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:38.282  2147  2147 E audit   : type=1300 msg=audit(1467786278.282:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=1 a3=98fe23c8 items=0 ppid=368 ppcomm=main pid=7254 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-999" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-06 08:24:38.282  2147  2147 E audit   : type=1327 msg=audit(1467786278.282:289): proctitle="com.test.thalitest"
07-06 08:24:38.282  2147  2147 E audit   : type=1320 msg=audit(1467786278.282:289): 
07-06 08:24:38.292  7178  7254 W jxcore-log: Starting JXcore engine
,07-06 08:24:38.372  7178  7254 W jxcore-log: Platform android
07-06 08:24:38.372  7178  7254 W jxcore-log: 
,07-06 08:24:38.372  7178  7254 W jxcore-log: Process ARCH arm
07-06 08:24:38.372  7178  7254 W jxcore-log: 
,07-06 08:24:38.562  7178  7254 I jxcore-log: JXcore Cordova bridge is ready!
07-06 08:24:38.562  7178  7254 I jxcore-log: 
,07-06 08:24:38.562  7178  7254 W jxcore-log: JXcore engine is started
,07-06 08:24:38.572  7178  7250 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-06 08:24:38.572  7178  7178 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-06 08:24:39.142   768  1363 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,07-06 08:24:42.542   768  3441 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:24:44.672   768  3441 D SSRM:n  : SIOP:: AP = 330, PST = 301, CUR = 450, LCD = 0
,07-06 08:24:45.092   768  1554 E Watchdog: !@Sync 9 [07-06 08:24:45.098]
,07-06 08:24:46.152   768   931 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-06 08:24:46.172   768   931 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-06 08:24:48.572  7178  7254 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-06 08:24:48.572  7178  7254 I jxcore-log: 
07-06 08:24:48.572  7178  7254 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-06 08:24:48.572  7178  7254 I jxcore-log: 
07-06 08:24:48.582  7178  7254 D BluetoothAdapter: STATE_ON
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 08:24:48.582  7178  7254 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-06 08:24:48.582  7178  7254 D BluetoothAdapter: STATE_ON
07-06 08:24:48.582  7178  7254 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-06 08:24:48.592  7178  7254 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-06 08:24:48.592  7178  7254 I jxcore-log: 
07-06 08:24:48.592  7178  7254 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-06 08:24:48.592  7178  7254 I jxcore-log: 
,07-06 08:24:48.962  7178  7254 I jxcore-log: Unit Test app is loaded
07-06 08:24:48.962  7178  7254 I jxcore-log: 
,07-06 08:24:48.962  7178  7254 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-06 08:24:48.962  7178  7254 I jxcore-log: 
,07-06 08:24:48.972  7178  7254 I jxcore-log: My device name is: samsung-SM-G900F
07-06 08:24:48.972  7178  7254 I jxcore-log: 
,07-06 08:24:48.972  7178  7254 I jxcore-log: WARN testUtils: myNameCallback not set!
07-06 08:24:48.972  7178  7254 I jxcore-log: 
,07-06 08:24:48.992  7178  7178 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-06 08:24:50.542  2102  3315 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-06 08:24:52.842  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-06 08:24:52.842  7178  7254 I jxcore-log: 
,07-06 08:24:53.252  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-06 08:24:53.252  7178  7254 I jxcore-log: 
,07-06 08:24:53.272  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-06 08:24:53.272  7178  7254 I jxcore-log: 
,07-06 08:24:53.282  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-06 08:24:53.282  7178  7254 I jxcore-log: 
,07-06 08:24:53.292  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-06 08:24:53.292  7178  7254 I jxcore-log: 
,07-06 08:24:53.302  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-06 08:24:53.302  7178  7254 I jxcore-log: 
,07-06 08:24:54.562   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:24:54.722   768  3441 D SSRM:n  : SIOP:: AP = 340, PST = 304, CUR = 450, LCD = 0
,07-06 08:24:55.272  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-06 08:24:55.272  7178  7254 I jxcore-log: 
,07-06 08:24:55.282  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-06 08:24:55.282  7178  7254 I jxcore-log: 
,07-06 08:24:55.292  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-06 08:24:55.292  7178  7254 I jxcore-log: 
,07-06 08:24:55.452  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-06 08:24:55.452  7178  7254 I jxcore-log: 
,07-06 08:24:55.532  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-06 08:24:55.532  7178  7254 I jxcore-log: 
,07-06 08:24:55.592  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-06 08:24:55.592  7178  7254 I jxcore-log: 
,07-06 08:24:55.602  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-06 08:24:55.602  7178  7254 I jxcore-log: 
,07-06 08:24:55.792  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-06 08:24:55.792  7178  7254 I jxcore-log: 
,07-06 08:24:55.812  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-06 08:24:55.812  7178  7254 I jxcore-log: 
,07-06 08:24:55.812  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-06 08:24:55.812  7178  7254 I jxcore-log: 
,07-06 08:24:55.822  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-06 08:24:55.822  7178  7254 I jxcore-log: 
,07-06 08:24:55.842  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-06 08:24:55.842  7178  7254 I jxcore-log: 
,07-06 08:24:55.852  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-06 08:24:55.852  7178  7254 I jxcore-log: 
,07-06 08:24:55.942  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-06 08:24:55.942  7178  7254 I jxcore-log: 
,07-06 08:24:55.942  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-06 08:24:55.942  7178  7254 I jxcore-log: 
,07-06 08:24:55.972  7178  7254 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-06 08:24:55.972  7178  7254 I jxcore-log: 
,07-06 08:24:55.982  7178  7254 D BluetoothAdapter: STATE_ON
,07-06 08:24:55.982  7178  7254 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-06 08:24:55.982  7178  7254 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-06 08:24:55.982  7178  7254 I jxcore-log: 
,07-06 08:24:57.212   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:24:57.212   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:24:57.212   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:24:59.832   768  1232 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 08:24:59.842   768  1231 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:24:59.842   768  1232 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:24:59.862   768  1232 I TLC_TIMA_PKM_initialize: initializing...
,07-06 08:24:59.862   768  1232 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-06 08:24:59.862   768  1232 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-06 08:24:59.862   768  1232 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-06 08:24:59.862   768  1232 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-06 08:24:59.872   768  1232 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-06 08:24:59.872   768  1232 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-06 08:24:59.872   768  1232 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-06 08:24:59.882   768  1232 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-06 08:24:59.882   768  1232 D QSEECOMAPI: : App is not loaded in QSEE
,07-06 08:24:59.912   768  1232 D QSEECOMAPI: : Loaded image: APP id = 2
,07-06 08:24:59.922   768  1232 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-06 08:24:59.932   768  1232 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-06 08:25:03.232   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 08:25:03.242   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:25:03.252   768  1232 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:25:03.252   768  1232 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:25:04.772   768  3441 D SSRM:n  : SIOP:: AP = 320, PST = 306, CUR = 450, LCD = 0
,07-06 08:25:07.522   768  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:25:07.532   768  1494 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:25:07.532   768  1494 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:25:07.532   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:25:07.562   768  1494 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-06 08:25:07.562   768  1494 D BatteryService: stay LED for fully charged
,07-06 08:25:07.572  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:25:07.572  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:25:07.582  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:25:07.582   768   768 I MotionRecognitionService: Plugged
,07-06 08:25:07.592   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:25:07.592   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:25:07.592   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:25:07.602  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:25:07.602  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:25:07.612  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:07.612  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:07.612  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:14.562   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:25:14.832   768  3441 D SSRM:n  : SIOP:: AP = 310, PST = 307, CUR = 450, LCD = 0
,07-06 08:25:15.092   768  1554 E Watchdog: !@Sync 10 [07-06 08:25:15.100]
,07-06 08:25:16.342  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:25:20.882   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:25:20.882   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:25:20.882   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:25:24.892   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-06 08:25:34.562   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:25:34.942   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-06 08:25:37.212   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:25:37.212   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:25:37.212   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:25:37.592   768  2223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:25:37.592   768  2223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:25:37.592   768  2223 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:25:37.602   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:25:37.612   768   768 I MotionRecognitionService: Plugged
,07-06 08:25:37.612   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:25:37.622   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:25:37.622   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:25:37.622   768  2223 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-06 08:25:37.622   768  2223 D BatteryService: stay LED for fully charged
,07-06 08:25:37.642  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:25:37.642  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:25:37.642  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:25:37.652  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:25:37.652  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:25:37.662  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:37.662  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:25:37.662  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:41.942   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:25:41.942   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:25:41.942   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:25:45.002   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-06 08:25:45.102   768  1554 E Watchdog: !@Sync 11 [07-06 08:25:45.105]
,07-06 08:25:50.502  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:25:50.542  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:25:50.542  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:25:50.612  5690  5730 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 08:25:50.612  5690  5730 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 08:25:50.612   308  1118 D EnterpriseController: netId is 0
07-06 08:25:50.612   308  1118 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-06 08:25:54.572   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:25:55.052   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450, LCD = 0
,07-06 08:25:59.992   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:25:59.992   768  1238 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=375985 batch.start=543577
,07-06 08:26:00.012  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-06 08:26:00.012  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-06 08:26:00.012  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:26:00.062  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:26:00.082  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:26:00.112  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.112  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.112  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.112  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.112  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.112  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.122  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:00.182  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:26:05.112   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450, LCD = 0
,07-06 08:26:05.852   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:26:05.852   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:26:05.852   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:26:07.662   768  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:26:14.572   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:26:15.102   768  1554 E Watchdog: !@Sync 12 [07-06 08:26:15.110]
,07-06 08:26:15.172   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 310, CUR = 450, LCD = 0
,07-06 08:26:16.412  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:26:25.232   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 306, CUR = 450, LCD = 0
,07-06 08:26:34.572   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:26:35.292   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 301, CUR = 450, LCD = 0
,07-06 08:26:37.722   768  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:26:45.112   768  1554 E Watchdog: !@Sync 13 [07-06 08:26:45.114]
,07-06 08:26:45.342   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-06 08:26:47.202   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:26:47.202   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:26:47.202   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:26:54.582   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:26:55.402   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-06 08:26:59.992   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:27:05.452   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-06 08:27:06.652   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:27:06.652   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:27:06.652   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:27:07.792   768  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:27:07.802   768  1421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:27:07.802   768  1421 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:27:07.802   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:27:07.812   768   768 I MotionRecognitionService: Plugged
,07-06 08:27:07.822   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:27:07.822   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:27:07.822   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:27:07.832   768  1421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-06 08:27:07.832   768  1421 D BatteryService: stay LED for fully charged
,07-06 08:27:07.842  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:27:07.842  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:27:07.842  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:27:07.852  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:27:07.852  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:27:07.862  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:27:07.862  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:27:07.872  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:27:14.582   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:27:15.112   768  1554 E Watchdog: !@Sync 14 [07-06 08:27:15.122]
,07-06 08:27:15.512   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-06 08:27:16.472  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:27:16.592  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 106ms lastUpdatedAfter : 180269ms
,07-06 08:27:25.572   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-06 08:27:34.592   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:27:35.632   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-06 08:27:37.862   768  2223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:27:45.122   768  1554 E Watchdog: !@Sync 15 [07-06 08:27:45.126]
,07-06 08:27:45.682   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-06 08:27:46.962   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:27:46.962   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:27:46.962   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:27:49.602   374   374 I bootchecker: bootchecker wake up!!
,07-06 08:27:54.592   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:27:55.742   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:05.772   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:28:05.772   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:28:05.772   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:28:05.832   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:07.922   768  2223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:28:07.932   768  2223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:28:07.932   768  2223 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:28:07.932   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:28:07.952   768   768 I MotionRecognitionService: Plugged
,07-06 08:28:07.952   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:28:07.952   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:28:07.962   768  2223 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-06 08:28:07.962   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:28:07.962   768  2223 D BatteryService: stay LED for fully charged
,07-06 08:28:07.982  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:28:07.982  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:28:07.982  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:28:08.002  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:28:08.002  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:28:08.012  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:28:08.012  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:08.012  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:28:14.602   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:28:15.122   768  1554 E Watchdog: !@Sync 16 [07-06 08:28:15.130]
,07-06 08:28:15.882   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:16.662  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:28:25.942   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:34.602   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:28:35.992   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:45.132   768  1554 E Watchdog: !@Sync 17 [07-06 08:28:45.134]
,07-06 08:28:46.052   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:47.602   768  1238 V AlarmManager: Expired Alarm result :4
,07-06 08:28:47.652  1540  1540 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-06 08:28:47.652  1540  1540 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-06 08:28:47.662  1540  1540 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-06 08:28:47.672   768  1690 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:28:47.672   768  1690 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-06 08:28:47.672   768  1690 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:28:47.672   768  1690 D BatteryService: stay LED for fully charged
,07-06 08:28:47.692   768   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{23d42c9 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53858b1 2844:com.google.android.gms/u0a11}
,07-06 08:28:47.722  7298  7298 E Zygote  : v2
,07-06 08:28:47.722  7298  7298 I libpersona: KNOX_SDCARD checking this for 1000
07-06 08:28:47.722  7298  7298 I libpersona: KNOX_SDCARD not a persona
,07-06 08:28:47.722  7298  7298 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:28:47.722  7298  7298 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:28:47.722  7298  7298 E Zygote  : accessInfo : 0
,07-06 08:28:47.732   768  1238 I ActivityManager: Start proc 7298:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-06 08:28:47.732   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:28:47.732  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:28:47.732  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:28:47.732  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:28:47.742  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:28:47.742  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:28:47.752   768   768 I MotionRecognitionService: Plugged
07-06 08:28:47.752   768   768 D MotionRecognitionService:   cableConnection= 1
07-06 08:28:47.752   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:28:47.752   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:28:47.762  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:47.762  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:47.762  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-06 08:28:47.762  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:47.762  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
07-06 08:28:47.762  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:28:47.772  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:28:47.772  7298  7298 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 08:28:47.772  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
07-06 08:28:47.772  7298  7298 D ActivityThread: Added TimaKeyStore provider
,07-06 08:28:47.772  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:28:47.782  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:28:47.782  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:28:47.782  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:28:47.782  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:28:47.782  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:28:47.782  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:28:47.792  7298  7298 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-06 08:28:47.812  7298  7298 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-06 08:28:47.832  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:28:47.842  2844  7322 I EventLogChimeraService: Aggregate from 1467784727436 (log), 1467784727436 (data)
,07-06 08:28:47.942   768   778 I art     : Background partial concurrent mark sweep GC freed 66603(5MB) AllocSpace objects, 185(3MB) LOS objects, 27% free, 42MB/58MB, paused 1.396ms total 117.012ms
,07-06 08:28:48.002   768   856 I ActivityManager: Start proc 7330:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,07-06 08:28:48.012  7330  7330 E Zygote  : v2
07-06 08:28:48.012  7330  7330 I libpersona: KNOX_SDCARD checking this for 1000
07-06 08:28:48.012  7330  7330 I libpersona: KNOX_SDCARD not a persona
,07-06 08:28:48.012  7330  7330 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-06 08:28:48.012  7330  7330 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:28:48.012  7330  7330 E Zygote  : accessInfo : 0
,07-06 08:28:48.042  7330  7330 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:28:48.042  7330  7330 D ActivityThread: Added TimaKeyStore provider
,07-06 08:28:48.042   768  1693 I ActivityManager: Killing 6351:com.sec.android.app.taskmanager/u0a175 (adj 15): DHA:empty #37
,07-06 08:28:48.052   768  1684 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{123610b u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23dbe8 7330:com.samsung.android.sm/1000}
,07-06 08:28:48.062   768  1759 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.taskmanager, Auto Run ON
,07-06 08:28:48.062  7330  7330 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,07-06 08:28:48.082   768  2251 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{123610b u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53858b1 2844:com.google.android.gms/u0a11}
,07-06 08:28:48.102   768   782 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2aad8a6 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23dbe8 7330:com.samsung.android.sm/1000}
,07-06 08:28:48.102   768  1684 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2aad8a6 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53858b1 2844:com.google.android.gms/u0a11}
,07-06 08:28:48.212  2844  7342 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-06 08:28:48.242  2844  7342 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-06 08:28:48.242   768  1494 I ActivityManager: Killing 6368:com.qualcomm.timeservice/1000 (adj 15): DHA:empty #37
,07-06 08:28:48.272   768  2229 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.timeservice, Auto Run ON
,07-06 08:28:51.542  1540  1540 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,07-06 08:28:51.552   308  1115 D Netd    : Iface wlan0 link up
,07-06 08:28:51.552  1540  1540 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-06 08:28:51.582   768   861 D Tethering: interfaceLinkStateChanged wlan0, true
,07-06 08:28:51.582   768   861 D Tethering: interfaceStatusChanged wlan0, true
,07-06 08:28:51.592   768  1321 D WifiP2pService: InactiveState{ what=147461 }
,07-06 08:28:51.592   768  1321 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-06 08:28:51.592   768  1321 D WifiP2pService: DefaultState{ what=147461 }
,07-06 08:28:51.642   768   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c9f7039 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6be7eb8 1378:com.android.systemui/u0a58}
,07-06 08:28:54.612   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:28:56.102   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:28:59.992   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:29:06.162   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:29:14.612   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:29:15.132   768  1554 E Watchdog: !@Sync 18 [07-06 08:29:15.140]
,07-06 08:29:16.222   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:29:16.682  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:29:17.752   768  1759 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:29:17.752   768  1759 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:29:17.752   768  1759 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:29:17.762   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:29:17.772   768   768 I MotionRecognitionService: Plugged
,07-06 08:29:17.772   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:29:17.772   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:29:17.772   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:29:17.782   768  1759 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-06 08:29:17.782   768  1759 D BatteryService: stay LED for fully charged
,07-06 08:29:17.792  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:29:17.792  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:29:17.792  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:29:17.822  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:29:17.822  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:29:17.832  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:17.832  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:17.832  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:26.282   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:29:34.612   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:29:36.342   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:29:45.142   768  1554 E Watchdog: !@Sync 19 [07-06 08:29:45.144]
,07-06 08:29:46.402   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:29:47.822   768  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:29:47.822   768  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:29:47.822   768  1694 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:29:47.832   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:29:47.842   768   768 I MotionRecognitionService: Plugged
,07-06 08:29:47.842   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:29:47.852   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:29:47.852   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:29:47.852   768  1694 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-06 08:29:47.862   768  1694 D BatteryService: stay LED for fully charged
,07-06 08:29:47.872  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:29:47.872  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:29:47.872  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:29:47.882  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:29:47.882  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:29:47.892  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:47.892  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:29:47.892  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:50.912   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:29:50.912   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:29:50.912   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:29:54.622   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:29:56.452   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:29:59.822   768  1232 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 08:29:59.822   768  1232 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:29:59.832   768  1231 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:30:01.292   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 08:30:01.292   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:30:01.302   768  1232 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:30:01.302   768  1232 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:30:05.972   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:30:05.972   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:30:05.972   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:30:06.512   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:30:14.622   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:30:15.142   768  1554 E Watchdog: !@Sync 20 [07-06 08:30:15.148]
,07-06 08:30:16.572   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:30:16.712  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:30:16.832  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 105ms lastUpdatedAfter : 180238ms
,07-06 08:30:17.882   768  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.362   768   848 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.372   768   848 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.382   768   848 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.392   768   848 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.572   768   903 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-06 08:30:18.572   768   903 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-06 08:30:26.622   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:30:34.632   768  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:30:36.682   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:30:45.142   768  1554 E Watchdog: !@Sync 21 [07-06 08:30:45.152]
,07-06 08:30:46.732   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:30:47.952   768   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:30:47.962   768   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:30:47.962   768   781 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:30:47.972   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:30:47.982   768   768 I MotionRecognitionService: Plugged
,07-06 08:30:47.982   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:30:47.982   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:30:47.992   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:30:47.992   768   781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-06 08:30:47.992   768   781 D BatteryService: stay LED for fully charged
,07-06 08:30:48.012  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:30:48.012  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:30:48.022  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:30:48.032  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:30:48.032  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:30:48.042  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:30:48.042  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:30:48.042  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:30:50.822   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:30:50.822   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:30:50.822   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:30:50.842   768  1684 I ActivityManager: Killing 4577:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 614s, lastActivityTime 614s
,07-06 08:30:50.842   768  1684 I ActivityManager: Killing 3905:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 618s, lastActivityTime 618s
,07-06 08:30:50.892   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-06 08:30:50.892   385  4856 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-06 08:30:50.892   385  4856 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:30:50.902   768  1494 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-06 08:30:50.902   768  1494 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
,07-06 08:30:50.902   768  1494 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-06 08:30:50.932   768  2239 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-06 08:30:50.932   768  2239 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-06 08:30:50.932   768  2239 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10968ms
,07-06 08:30:51.892   385  4856 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:30:51.982   768   856 I ActivityManager: Start proc 7366:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-06 08:30:51.992  7366  7366 E Zygote  : v2
,07-06 08:30:51.992  7366  7366 I libpersona: KNOX_SDCARD checking this for 1000
,07-06 08:30:51.992  7366  7366 I libpersona: KNOX_SDCARD not a persona
,07-06 08:30:52.002  7366  7366 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:30:52.002  7366  7366 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:30:52.002  7366  7366 E Zygote  : accessInfo : 0
,07-06 08:30:52.042  7366  7366 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 08:30:52.042  7366  7366 D ActivityThread: Added TimaKeyStore provider
,07-06 08:30:52.072  7366  7366 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-06 08:30:52.082  7366  7366 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-06 08:30:52.082  7366  7366 D AtFwdService: onCreate method
,07-06 08:30:52.092  7366  7366 I AtFwdService: Instantiate AtCmdFwd Service
,07-06 08:30:52.102  7366  7378 D AtCkpdCmdHandler: De-queing command
,07-06 08:30:56.792   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:31:01.972   768   856 I ActivityManager: Start proc 7380:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-06 08:31:01.982  7380  7380 E Zygote  : v2
,07-06 08:31:01.982  7380  7380 I libpersona: KNOX_SDCARD checking this for 10026
07-06 08:31:01.982  7380  7380 I libpersona: KNOX_SDCARD not a persona
,07-06 08:31:01.982  7380  7380 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:31:01.982  7380  7380 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:31:01.982  7380  7380 E Zygote  : accessInfo : 0
,07-06 08:31:01.992  7380  7380 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-06 08:31:02.032  7380  7380 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 08:31:02.032  7380  7380 D ActivityThread: Added TimaKeyStore provider
,07-06 08:31:02.042   768  2229 I ActivityManager: Killing 3860:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 630s, lastActivityTime 600s
,07-06 08:31:02.072  7380  7380 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
07-06 08:31:02.072   768  1684 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
07-06 08:31:02.072   768  1684 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-06 08:31:02.092  7380  7380 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-06 08:31:02.102  7380  7380 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-06 08:31:02.102  7380  7380 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-06 08:31:02.532   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:31:05.972   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:31:05.972   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:31:05.972   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:31:06.852   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:31:15.152   768  1554 E Watchdog: !@Sync 22 [07-06 08:31:15.158]
,07-06 08:31:16.882  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:31:16.922   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:31:18.022   768  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:31:18.032   768  1494 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:31:18.032   768  1494 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:31:18.032   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:31:18.042   768   768 I MotionRecognitionService: Plugged
,07-06 08:31:18.052   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:31:18.052   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:31:18.052   768  1494 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-06 08:31:18.052   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:31:18.062   768  1494 D BatteryService: stay LED for fully charged
,07-06 08:31:18.082  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:31:18.082  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:31:18.082  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:31:18.102  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:31:18.102  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:31:18.112  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:31:18.112  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:31:18.112  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:31:26.982   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:31:37.032   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:31:45.152   768  1554 E Watchdog: !@Sync 23 [07-06 08:31:45.162]
,07-06 08:31:47.082   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:31:48.092   768  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:31:48.092   768  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:31:48.102   768  1220 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:31:48.102   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:31:48.122   768   768 I MotionRecognitionService: Plugged
,07-06 08:31:48.122   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:31:48.122   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:31:48.122   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:31:48.132   768  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,07-06 08:31:48.132   768  1220 D BatteryService: stay LED for fully charged
,07-06 08:31:48.142  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:31:48.142  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:31:48.142  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:31:48.152  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:31:48.162  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:31:48.162  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:31:48.172  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:31:48.172  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:31:57.142   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:32:07.192   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:32:15.162   768  1554 E Watchdog: !@Sync 24 [07-06 08:32:15.168]
,07-06 08:32:17.012  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:32:17.242   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:32:18.162   768   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:32:18.162   768   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:32:18.172   768   782 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:32:18.172   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:32:18.182   768   768 I MotionRecognitionService: Plugged
,07-06 08:32:18.182   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:32:18.192   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:32:18.192   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:32:18.192   768   782 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-06 08:32:18.192   768   782 D BatteryService: stay LED for fully charged
,07-06 08:32:18.212  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:32:18.212  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:32:18.212  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:32:18.242  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:32:18.242  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:32:18.242  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:32:18.242  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:32:18.242  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:32:27.302   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:32:37.362   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:32:45.162   768  1554 E Watchdog: !@Sync 25 [07-06 08:32:45.172]
,07-06 08:32:47.412   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:32:48.232   768  2229 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:32:48.242   768  2229 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:32:48.242   768  2229 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:32:48.242   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:32:48.252   768   768 I MotionRecognitionService: Plugged
,07-06 08:32:48.262   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:32:48.262   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:32:48.262   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:32:48.272   768  2229 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-06 08:32:48.272   768  2229 D BatteryService: stay LED for fully charged
,07-06 08:32:48.292  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:32:48.292  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:32:48.292  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:32:48.302  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:32:48.302  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:32:48.312  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:32:48.312  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:32:48.312  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:32:57.472   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:33:07.532   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:33:15.172   768  1554 E Watchdog: !@Sync 26 [07-06 08:33:15.176]
,07-06 08:33:17.082  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:33:17.192  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 100ms lastUpdatedAfter : 180360ms
,07-06 08:33:17.582   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:33:18.302   768  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:33:18.702   768  2270 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-06 08:33:18.702   768  2270 V MARsPolicyManager: updateSMDBValues
,07-06 08:33:18.712   768   901 E MARsDBManager: updateDBAll : begin --size 1
,07-06 08:33:18.742   768   901 I ActivityManager: Killing 1955:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 781s, lastActivityTime 700s
,07-06 08:33:18.752   768   901 I ActivityManager: Killing 1511:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 757s, lastActivityTime 717s
,07-06 08:33:18.802   768   901 E MARsDBManager: updateDBAll : end
,07-06 08:33:18.802   768   901 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-06 08:33:18.852   768  1684 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,07-06 08:33:18.852   768  1684 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-06 08:33:18.852   768  1684 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-06 08:33:18.872   768   782 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-06 08:33:18.872   768   782 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-06 08:33:18.872   768   782 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10984ms
07-06 08:33:18.872   768   782 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,07-06 08:33:18.872   768   782 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 20983ms
,07-06 08:33:18.872  6961  6961 D HealthConsole: Service for HealthDataStore is disconnected
,07-06 08:33:18.902   768  1759 I ActivityManager: Start proc 7406:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,07-06 08:33:18.902  7406  7406 E Zygote  : v2
,07-06 08:33:18.902  7406  7406 I libpersona: KNOX_SDCARD checking this for 10034
,07-06 08:33:18.902  7406  7406 I libpersona: KNOX_SDCARD not a persona
,07-06 08:33:18.902  7406  7406 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-06 08:33:18.902  7406  7406 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:33:18.912  7406  7406 E Zygote  : accessInfo : 0
07-06 08:33:18.912  7406  7406 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-06 08:33:18.942  7406  7406 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:33:18.942  7406  7406 D ActivityThread: Added TimaKeyStore provider
,07-06 08:33:18.962  7406  7406 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-06 08:33:18.982  7406  7406 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-06 08:33:18.982  7406  7406 I MultiDex: VM with version 2.1.0 has multidex support
07-06 08:33:18.982  7406  7406 I MultiDex: install
07-06 08:33:18.982  7406  7406 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-06 08:33:18.982  7406  7406 I MultiDex: install
07-06 08:33:18.982  7406  7406 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-06 08:33:19.082   768  2239 I ActivityManager: Start proc 7431:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,07-06 08:33:19.092  7431  7431 E Zygote  : v2
,07-06 08:33:19.092  7431  7431 I libpersona: KNOX_SDCARD checking this for 10016
07-06 08:33:19.092  7431  7431 I libpersona: KNOX_SDCARD not a persona
,07-06 08:33:19.092  7431  7431 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:33:19.092  7431  7431 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:33:19.102  7431  7431 E Zygote  : accessInfo : 0
,07-06 08:33:19.102  7431  7431 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-06 08:33:19.152  7431  7431 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:33:19.152  7431  7431 D ActivityThread: Added TimaKeyStore provider
,07-06 08:33:19.192  7431  7431 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-06 08:33:19.262  7406  7406 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-06 08:33:19.262  7406  7406 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-06 08:33:19.322  1378  1378 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-06 08:33:19.322   768  1690 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-06 08:33:19.332   768  2251 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-06 08:33:19.342   768  1494 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-06 08:33:19.342  1378  1378 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{3a9f1e6 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,07-06 08:33:19.352  1378  1378 D AdaptiveEventManager: M updateContainers()
07-06 08:33:19.352  1378  1378 D AdaptiveEventContainerSmall: C updatePedoContainer()
,07-06 08:33:19.352  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-06 08:33:19.352  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-06 08:33:19.352   768  1421 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-06 08:33:19.402  7406  7406 I Health.HealthService: HealthService: onCreate() start (7406)
,07-06 08:33:19.522  6961  6961 D HealthDataStore: Service for HealthDataStore is connected
,07-06 08:33:19.522  6961  6961 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-06 08:33:19.532   768  1693 I ActivityManager: Killing 6385:com.sec.android.app.clockpackage/u0a90 (adj 15): DHA:empty #37
,07-06 08:33:19.572  6961  6961 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-06 08:33:19.572  6961  6961 E HealthDataStore: disconnectService: Context instance is invalid
,07-06 08:33:19.572   768  1690 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.clockpackage, Auto Run ON
,07-06 08:33:19.602  7406  7406 D HealthDataStore: Service for HealthDataStore is connected
,07-06 08:33:19.602  7406  7406 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-06 08:33:19.602  7406  7406 D HealthConsole: Service for HealthDataConsole is connected
,07-06 08:33:19.612  7406  7406 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-06 08:33:19.612  7406  7406 E HealthDataStore: disconnectService: Context instance is invalid
,07-06 08:33:19.752  7406  7451 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-06 08:33:19.792  7406  7464 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-06 08:33:19.792  7431  7442 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-06 08:33:19.802   400   400 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7431
07-06 08:33:19.802   400   400 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-06 08:33:19.902   768   856 I ActivityManager: Start proc 7467:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,07-06 08:33:19.902   768  1320 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-06 08:33:19.902  7467  7467 E Zygote  : v2
07-06 08:33:19.902  7467  7467 I libpersona: KNOX_SDCARD checking this for 10181
07-06 08:33:19.902  7467  7467 I libpersona: KNOX_SDCARD not a persona
,07-06 08:33:19.902  7467  7467 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-06 08:33:19.902  7467  7467 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:33:19.912  7467  7467 E Zygote  : accessInfo : 0
,07-06 08:33:19.912  7467  7467 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-06 08:33:19.942  7431  7442 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-06 08:33:19.952  7467  7467 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:33:19.952  7467  7467 D ActivityThread: Added TimaKeyStore provider
,07-06 08:33:19.972   768  1320 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-06 08:33:19.982  7467  7467 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-06 08:33:19.992  7467  7467 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-06 08:33:20.032  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-06 08:33:20.032  7467  7467 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:33:20.042   768   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f2608c u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e5f3d5 7467:com.sec.android.daemonapp/u0a181}
,07-06 08:33:20.042  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-06 08:33:20.042  7467  7467 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:33:20.052  7467  7467 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
07-06 08:33:20.052  7467  7467 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:33:20.052  7467  7467 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-06 08:33:20.052  7467  7467 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:33:20.062  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:33:20.062  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-06 08:33:20.062  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-06 08:33:20.072  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:33:20.072  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:33:20.072  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-06 08:33:20.072  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-06 08:33:20.082  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-06 08:33:20.092  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
07-06 08:33:20.092  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-06 08:33:20.092  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-06 08:33:20.092  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-06 08:33:20.102  7467  7467 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:33:20.102  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.102  7467  7467 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-06 08:33:20.102  7467  7467 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:33:20.102  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.102  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:33:20.112   768  1684 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{99ef851 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e5f3d5 7467:com.sec.android.daemonapp/u0a181}
,07-06 08:33:20.112  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:33:20.112  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:33:20.112  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:33:20.122  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.122  7467  7467 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:33:20.122  7467  7467 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-06 08:33:20.122  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.122  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:33:20.132  7406  7464 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-06 08:33:20.132   768  1220 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fe98b6 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e5f3d5 7467:com.sec.android.daemonapp/u0a181}
,07-06 08:33:20.132  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:33:20.142  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.142  7467  7467 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:33:20.142  7467  7467 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:33:20.142  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-06 08:33:20.142  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.152  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:33:20.152   768  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cb2a9b7 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3e5f3d5 7467:com.sec.android.daemonapp/u0a181}
,07-06 08:33:20.152  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:33:20.152  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:33:20.152  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:33:20.162  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.162  7467  7467 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:33:20.162  7467  7467 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:33:20.162  7467  7467 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:33:20.162  7467  7467 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:33:20.232  7406  7464 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-06 08:33:20.232  7406  7464 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-06 08:33:20.262   400   400 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-06 08:33:20.302  7431  7442 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-06 08:33:20.302  7431  7442 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-06 08:33:20.302  7431  7442 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-06 08:33:27.642   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:33:37.692   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:33:45.172   768  1554 E Watchdog: !@Sync 27 [07-06 08:33:45.180]
,07-06 08:33:47.752   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:33:48.382   768   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:33:48.382   768   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:33:48.392   768   782 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:33:48.392   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:33:48.402   768   768 I MotionRecognitionService: Plugged
,07-06 08:33:48.412   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:33:48.412   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:33:48.412   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:33:48.432   768   782 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 44ms
,07-06 08:33:48.432   768   782 D BatteryService: stay LED for fully charged
,07-06 08:33:48.432  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:33:48.432  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:33:48.432  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:33:48.452  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:33:48.452  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:33:48.462  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:33:48.462  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:33:48.462  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:33:57.802   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:07.862   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:15.182   768  1554 E Watchdog: !@Sync 28 [07-06 08:34:15.186]
,07-06 08:34:17.262  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:34:17.912   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:18.442   768  1759 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:34:18.442   768  1759 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:34:18.442   768  1759 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:34:18.452   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:34:18.462   768   768 I MotionRecognitionService: Plugged
,07-06 08:34:18.462   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:34:18.462   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:34:18.472   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:34:18.472   768  1759 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-06 08:34:18.472   768  1759 D BatteryService: stay LED for fully charged
,07-06 08:34:18.482  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:34:18.482  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:34:18.482  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:34:18.492  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:34:18.492  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:34:18.502  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:18.502  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:18.512  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:27.962   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:38.022   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:45.182   768  1554 E Watchdog: !@Sync 29 [07-06 08:34:45.190]
,07-06 08:34:48.072   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:48.512   768   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:34:48.522   768   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:34:48.522   768   781 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:34:48.522   768   781 D BatteryService: stay LED for fully charged
,07-06 08:34:48.532   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:34:48.542   768   768 I MotionRecognitionService: Plugged
,07-06 08:34:48.552   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:34:48.552   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:34:48.552   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:34:48.562  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:34:48.562  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:34:48.572  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:34:48.592  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:34:48.592  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:34:48.602  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:48.602  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:34:48.602  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:58.132   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:34:59.822   768  1232 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 08:34:59.832   768  1232 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:34:59.832   768  1231 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:35:03.222   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 08:35:03.222   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:35:03.232   768  1232 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:35:03.242   768  1232 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:35:08.182   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:35:15.192   768  1554 E Watchdog: !@Sync 30 [07-06 08:35:15.194]
,07-06 08:35:17.372  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:35:18.232   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:35:20.982   768  1238 V AlarmManager: Expired Alarm result :4
,07-06 08:35:21.032  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-06 08:35:21.032  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-06 08:35:21.032  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:35:21.052   768  2239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:35:21.052   768  2239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:35:21.052   768  2239 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-06 08:35:21.052   768  2239 D BatteryService: stay LED for fully charged
,07-06 08:35:21.052  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:35:21.062  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:35:21.072   768   856 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-06 08:35:21.082  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:21.092  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:21.092  2142  2344 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-06 08:35:21.092  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.092  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-06 08:35:21.092  2142  2344 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-06 08:35:21.092  2142  2344 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-06 08:35:21.092  2142  2344 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-06 08:35:21.102  2142  2427 D bt_upio : upio_start_stop_timer : timer_settime success
,07-06 08:35:21.102  2142  2427 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-06 08:35:21.102  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.102  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.102  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.102  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.102  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.102  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.102  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.102  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.102  2142  2427 D bt_upio : BT_WAKE is asserted already
07-06 08:35:21.102  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.102  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.102  2142  2427 D bt_upio : BT_WAKE is asserted already
07-06 08:35:21.112  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.112  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.112  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.112  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.112  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.112  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.112  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.112  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.112  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.112  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.112  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.112  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.112  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.112  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.112  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.112  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.112  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-06 08:35:21.112  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.122  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.122  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.122  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.122  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.122  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.122  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.122  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.122  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.122  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.122  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.122  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.122  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.122  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.122  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-06 08:35:21.122  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.122  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.122  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-06 08:35:21.122  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.132  2142  2427 D bt_vendor: op for 7
,07-06 08:35:21.132  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.132  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.132  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.132  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.132  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.132  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:35:21.132  2142  2427 D bt_vendor: op for 7
07-06 08:35:21.132  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-06 08:35:21.132  2142  2427 D bt_upio : BT_WAKE is asserted already
,07-06 08:35:21.142  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:35:21.142  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:21.142  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:21.142  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:21.142   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:35:21.152   768   768 I MotionRecognitionService: Plugged
,07-06 08:35:21.152   768   768 D MotionRecognitionService:   cableConnection= 1
07-06 08:35:21.152   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:35:21.152   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:35:21.152  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:35:21.152  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:35:21.162  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:35:21.162  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:35:21.162  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:35:21.162  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:35:21.162  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:35:21.162  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:35:21.172   768  1673 V AlarmManager:  remove PendingIntent] PendingIntent{1d76089: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.172   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{b14088e: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.172   768  2239 V AlarmManager:  remove PendingIntent] PendingIntent{df718af: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.172   768  1494 V AlarmManager:  remove PendingIntent] PendingIntent{21504bc: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.192   768  1421 V AlarmManager:  remove PendingIntent] PendingIntent{fcc7c45: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.202   768  2223 V AlarmManager:  remove PendingIntent] PendingIntent{a4c1f9a: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.202  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:21.212   768  1494 V AlarmManager:  remove PendingIntent] PendingIntent{f2690cb: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.222   768  1421 V AlarmManager:  remove PendingIntent] PendingIntent{b8bb0a8: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.222   768  2229 V AlarmManager:  remove PendingIntent] PendingIntent{43d97c1: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.222   768  1494 V AlarmManager:  remove PendingIntent] PendingIntent{2bc9b66: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.232   768  2251 V AlarmManager:  remove PendingIntent] PendingIntent{88b6ea7: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.232   768  1759 V AlarmManager:  remove PendingIntent] PendingIntent{b3f2f54: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.232   768  2239 V AlarmManager:  remove PendingIntent] PendingIntent{94aeefd: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.242   768  1673 V AlarmManager:  remove PendingIntent] PendingIntent{e6707f2: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.242   768  1693 V AlarmManager:  remove PendingIntent] PendingIntent{d764e43: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.242   768  1220 V AlarmManager:  remove PendingIntent] PendingIntent{209ecc0: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.252   768  1684 V AlarmManager:  remove PendingIntent] PendingIntent{dc7df9: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.252   768   782 V AlarmManager:  remove PendingIntent] PendingIntent{3d9b13e: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.252   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{ba58b9f: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.262   768   781 V AlarmManager:  remove PendingIntent] PendingIntent{20114ec: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.262   768  1690 V AlarmManager:  remove PendingIntent] PendingIntent{95e00b5: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.262   768  2223 V AlarmManager:  remove PendingIntent] PendingIntent{23ba34a: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.262   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{46142bb: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.262   768  1220 V AlarmManager:  remove PendingIntent] PendingIntent{76093d8: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.272   768  2239 V AlarmManager:  remove PendingIntent] PendingIntent{23af331: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.272   768  1494 V AlarmManager:  remove PendingIntent] PendingIntent{218aa16: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.272   768  2223 V AlarmManager:  remove PendingIntent] PendingIntent{b574f97: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.272   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{4371584: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.272   768  1220 V AlarmManager:  remove PendingIntent] PendingIntent{c1a916d: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.272   768  2239 V AlarmManager:  remove PendingIntent] PendingIntent{6ed51a2: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.282   768  1494 V AlarmManager:  remove PendingIntent] PendingIntent{7374e33: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.282   768  2223 V AlarmManager:  remove PendingIntent] PendingIntent{ad205f0: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.282   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{dbd769: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.282   768  1220 V AlarmManager:  remove PendingIntent] PendingIntent{d72e5ee: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.282   768  2239 V AlarmManager:  remove PendingIntent] PendingIntent{e9a8f: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.292   768  1494 V AlarmManager:  remove PendingIntent] PendingIntent{2e9911c: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.292   768  2223 V AlarmManager:  remove PendingIntent] PendingIntent{f518125: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.292   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{2ab72fa: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.292   768  1220 V AlarmManager:  remove PendingIntent] PendingIntent{76450ab: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.902  2142  2700 D bt_upio : ..proc_btwrite_timeout..
,07-06 08:35:21.902  2142  2700 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-06 08:35:28.292   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:35:35.882   768  1238 V AlarmManager: Expired Alarm result :4
,07-06 08:35:35.922   768   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fadc4c6 u0 com.samsung.android.provider.context.action.EXECUTE_TASK qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a3b311 2196:com.samsung.android.providers.context/u0a174}
,07-06 08:35:35.982   768   768 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-06 08:35:35.992   768   768 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:35:35.992   768   768 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-06 08:35:36.002   768   768 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-06 08:35:36.072  1793  7532 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-06 08:35:36.132  1793  7531 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-06 08:35:36.202  1793  7531 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-06 08:35:36.202  1793  7531 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-06 08:35:36.212  1793  7531 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-06 08:35:36.212  1793  7531 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-06 08:35:36.232  1793  7531 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-06 08:35:36.232  1793  7531 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-06 08:35:36.262  1793  7531 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,07-06 08:35:36.262   768  2223 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,07-06 08:35:36.322  2844  7553 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-06 08:35:36.362   768  1219 E LightSensor: RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,07-06 08:35:36.362   768   914 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-06 08:35:36.362   768   914 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-06 08:35:36.372   768   914 D SensorManager: unregisterListener ::   
,07-06 08:35:36.372   768   914 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:35:36.372   768   914 V AlarmManager:  remove PendingIntent] PendingIntent{743655a: PendingIntentRecord{e2fc38b android broadcastIntent}}
,07-06 08:35:36.392  2844  5164 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-06 08:35:36.652  1793  7531 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-06 08:35:36.652  1793  7531 E native  : request_context {
07-06 08:35:36.652  1793  7531 E native  :   type: DYNAMIC_CLASS
07-06 08:35:36.652  1793  7531 E native  :   dynamic_class_context {
07-06 08:35:36.652  1793  7531 E native  :     class_type: APP_NAME
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Maps"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Settings"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Gmail"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "YouTube"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Hangouts"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Google+"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Play Store"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Chrome"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Play Books"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Play Music"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Dropbox"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Play Movies & TV"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Contacts"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Phone"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Flipboard"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Play Newsstand"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Drive"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Player"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "ThaliTest"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "S Health"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Peel Smart Remote"
07-06 08:35:36.652  1793  7531 E n,ative  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Photos"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Music"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Calculator"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Messages"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "S Planner"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Camera"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Clock"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "My Files"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Email"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Smart Manager"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Video"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Memo"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Gallery"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Voice Recorder"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Galaxy Apps"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Play Games"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "S Voice"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Docs"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :     instance {
07-06 08:35:36.652  1793  7531 E native  :       value: "Internet"
07-06 08:35:36.652  1793  7531 E native  :     }
07-06 08:35:36.652  1793  7531 E native  :   }
07-06 08:35:36.652  1793  7531 E native  : }
07-06 08:35:36.652  1793  7531 E native  : 
07-06 08:35:36.652  1793  7531 E ContextCompilationHandl: Compiling recognition context failed for APP_NAMES en-US
,07-06 08:35:36.652  1793  7531 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-06 08:35:36.702  2844  5164 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-06 08:35:36.772  2844  5013 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-06 08:35:36.822  2844  5013 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-06 08:35:36.902  2844  5013 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-06 08:35:36.952  1793  7531 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-06 08:35:36.952  1793  7531 E native  : request_context {
07-06 08:35:36.952  1793  7531 E native  :   type: DYNAMIC_CLASS
07-06 08:35:36.952  1793  7531 E native  :   dynamic_class_context {
07-06 08:35:36.952  1793  7531 E native  :     class_type: SONG_NAME
07-06 08:35:36.952  1793  7531 E native  :     instance {
07-06 08:35:36.952  1793  7531 E native  :       value: "Over the Horizon"
07-06 08:35:36.952  1793  7531 E native  :     }
07-06 08:35:36.952  1793  7531 E native  :   }
07-06 08:35:36.952  1793  7531 E native  : }
07-06 08:35:36.952  1793  7531 E native  : request_context {
07-06 08:35:36.952  1793  7531 E native  :   type: DYNAMIC_CLASS
07-06 08:35:36.952  1793  7531 E native  :   dynamic_class_context {
07-06 08:35:36.952  1793  7531 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
07-06 08:35:36.952  1793  7531 E native  :     instance {
07-06 08:35:36.952  1793  7531 E native  :       value: "Brand Music"
07-06 08:35:36.952  1793  7531 E native  :     }
07-06 08:35:36.952  1793  7531 E native  :   }
07-06 08:35:36.952  1793  7531 E native  : }
07-06 08:35:36.952  1793  7531 E native  : request_context {
07-06 08:35:36.952  1793  7531 E native  :   type: DYNAMIC_CLASS
07-06 08:35:36.952  1793  7531 E native  :   dynamic_class_context {
07-06 08:35:36.952  1793  7531 E native  :     class_type: ARTIST_NAME
07-06 08:35:36.952  1793  7531 E native  :     instance {
07-06 08:35:36.952  1793  7531 E native  :       value: "Samsung"
07-06 08:35:36.952  1793  7531 E native  :     }
07-06 08:35:36.952  1793  7531 E native  :   }
07-06 08:35:36.952  1793  7531 E native  : }
07-06 08:35:36.952  1793  7531 E native  : 
,07-06 08:35:36.952  1793  7531 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
,07-06 08:35:38.352   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:35:45.192   768  1554 E Watchdog: !@Sync 31 [07-06 08:35:45.201]
,07-06 08:35:48.412   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:35:51.122   768  2229 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:35:58.462   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:35:59.992   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:36:08.522   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:36:15.202   768  1554 E Watchdog: !@Sync 32 [07-06 08:36:15.207]
,07-06 08:36:17.402  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:36:18.572   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:36:21.202   768  1673 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:36:28.632   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:36:38.682   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:36:45.202   768  1554 E Watchdog: !@Sync 33 [07-06 08:36:45.211]
,07-06 08:36:48.732   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:36:51.262   768  1684 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:36:58.792   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:37:08.842   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:37:15.212   768  1554 E Watchdog: !@Sync 34 [07-06 08:37:15.217]
,07-06 08:37:17.442  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:37:18.902   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:37:21.322   768  2223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:37:21.332   768  2223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:37:21.332   768  2223 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:37:21.332   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:37:21.352   768   768 I MotionRecognitionService: Plugged
,07-06 08:37:21.352   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:37:21.352   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:37:21.352   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:37:21.362   768  2223 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-06 08:37:21.362   768  2223 D BatteryService: stay LED for fully charged
,07-06 08:37:21.372  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:37:21.372  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:37:21.372  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:37:21.392  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:37:21.392  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:37:21.402  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:37:21.402  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:37:21.402  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:37:28.952   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:37:39.012   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:37:45.212   768  1554 E Watchdog: !@Sync 35 [07-06 08:37:45.221]
,07-06 08:37:49.062   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:37:51.392   768  1673 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:37:59.122   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:38:09.172   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:38:15.222   768  1554 E Watchdog: !@Sync 36 [07-06 08:38:15.228]
,07-06 08:38:17.562  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:38:17.682  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 103ms lastUpdatedAfter : 161374ms
,07-06 08:38:19.242   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:38:21.462   768  1684 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:38:29.292   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:38:39.352   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:38:45.222   768  1554 E Watchdog: !@Sync 37 [07-06 08:38:45.232]
,07-06 08:38:49.402   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:38:51.532   768  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:38:59.462   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:09.522   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:15.232   768  1554 E Watchdog: !@Sync 38 [07-06 08:39:15.239]
,07-06 08:39:17.692  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:39:19.572   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:21.602   768   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:39:21.602   768   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:39:21.602   768   782 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:39:21.612   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:39:21.622   768   768 I MotionRecognitionService: Plugged
,07-06 08:39:21.622   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:39:21.622   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:39:21.632   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:39:21.632   768   782 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-06 08:39:21.632   768   782 D BatteryService: stay LED for fully charged
,07-06 08:39:21.662  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:39:21.662  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:39:21.662  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:39:21.682  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:39:21.682  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:39:21.692  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:21.692  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:21.692  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:29.632   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:39.682   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:45.242   768  1554 E Watchdog: !@Sync 39 [07-06 08:39:45.243]
,07-06 08:39:49.742   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:51.672   768  1684 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:39:51.672   768  1684 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:39:51.672   768  1684 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:39:51.682   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:39:51.692   768   768 I MotionRecognitionService: Plugged
,07-06 08:39:51.692   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:39:51.692   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:39:51.702   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:39:51.702   768  1684 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-06 08:39:51.702   768  1684 D BatteryService: stay LED for fully charged
,07-06 08:39:51.722  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:39:51.722  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:39:51.722  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:39:51.732  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:39:51.732  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:39:51.742  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:51.742  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:51.742  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:59.792   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:39:59.822   768  1232 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 08:39:59.832   768  1232 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:39:59.832   768  1231 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:40:01.312   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 08:40:01.312   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:40:01.322   768  1232 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:40:01.322   768  1232 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:40:09.852   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:40:11.852   768   848 I UsageStatsService: User[0] Flushing usage stats to disk
,07-06 08:40:15.242   768  1554 E Watchdog: !@Sync 40 [07-06 08:40:15.250]
,07-06 08:40:17.792  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:40:19.902   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:40:21.742   768   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:40:21.742   768   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:40:21.742   768   781 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:40:21.752   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:40:21.762   768   768 I MotionRecognitionService: Plugged
,07-06 08:40:21.762   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:40:21.762   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:40:21.762   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:40:21.772   768   781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-06 08:40:21.772   768   781 D BatteryService: stay LED for fully charged
,07-06 08:40:21.772  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:40:21.772  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:40:21.772  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:40:21.792  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:40:21.792  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:40:21.802  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:40:21.802  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:40:21.802  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:40:29.962   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:40:40.012   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:40:45.252   768  1554 E Watchdog: !@Sync 41 [07-06 08:40:45.256]
,07-06 08:40:50.072   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:40:51.802   768  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:41:00.122   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:41:10.182   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:41:15.252   768  1554 E Watchdog: !@Sync 42 [07-06 08:41:15.260]
,07-06 08:41:17.812  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:41:17.942  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 117ms lastUpdatedAfter : 180265ms
,07-06 08:41:20.282   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:41:20.392   768   778 I art     : Background sticky concurrent mark sweep GC freed 61023(7MB) AllocSpace objects, 380(7MB) LOS objects, 26% free, 43MB/58MB, paused 2.636ms total 154.624ms
,07-06 08:41:21.872   768  2229 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:41:21.872   768  2229 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:41:21.872   768  2229 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:41:21.882   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:41:21.892   768   768 I MotionRecognitionService: Plugged
,07-06 08:41:21.892   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:41:21.892   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:41:21.902   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:41:21.902   768  2229 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-06 08:41:21.902   768  2229 D BatteryService: stay LED for fully charged
,07-06 08:41:21.922  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:41:21.922  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:41:21.922  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:41:21.932  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:41:21.932  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:41:21.942  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:41:21.942  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:41:21.952  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:41:30.342   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:41:40.412   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:41:45.262   768  1554 E Watchdog: !@Sync 43 [07-06 08:41:45.264]
,07-06 08:41:50.472   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:41:51.932   768  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:42:00.532   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:42:10.582   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:42:15.262   768  1554 E Watchdog: !@Sync 44 [07-06 08:42:15.272]
,07-06 08:42:18.032  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:42:20.642   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:42:22.002   768  1421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:42:30.692   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:42:40.752   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:42:45.272   768  1554 E Watchdog: !@Sync 45 [07-06 08:42:45.278]
,07-06 08:42:50.812   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:42:52.072   768   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:42:52.072   768   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:42:52.082   768   781 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:42:52.082   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:42:52.092   768   768 I MotionRecognitionService: Plugged
,07-06 08:42:52.102   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:42:52.102   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:42:52.102   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:42:52.112   768   781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,07-06 08:42:52.112   768   781 D BatteryService: stay LED for fully charged
,07-06 08:42:52.122  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:42:52.122  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:42:52.122  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:42:52.132  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:42:52.142  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:42:52.152  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:42:52.152  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:42:52.152  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:00.872   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:43:10.922   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:43:15.272   768  1554 E Watchdog: !@Sync 46 [07-06 08:43:15.282]
,07-06 08:43:18.082  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:43:20.972   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:43:22.152   768  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:43:22.152   768  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:43:22.152   768  1694 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:43:22.162   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:43:22.172   768   768 I MotionRecognitionService: Plugged
,07-06 08:43:22.172   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:43:22.172   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:43:22.172   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:43:22.182   768  1694 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-06 08:43:22.182   768  1694 D BatteryService: stay LED for fully charged
,07-06 08:43:22.192  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:43:22.192  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:43:22.192  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:43:22.222  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:43:22.222  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:43:22.222  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:22.232  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:22.232  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:31.032   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:43:41.082   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:43:45.282   768  1554 E Watchdog: !@Sync 47 [07-06 08:43:45.288]
,07-06 08:43:51.142   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:43:52.212   768   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:43:52.222   768   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:43:52.222   768   782 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:43:52.222   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:43:52.242   768   768 I MotionRecognitionService: Plugged
,07-06 08:43:52.242   768   782 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-06 08:43:52.252   768   782 D BatteryService: stay LED for fully charged
,07-06 08:43:52.262   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:43:52.262   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:43:52.262   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:43:52.272  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:43:52.272  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:43:52.272  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:43:52.282  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:43:52.282  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:43:52.292  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:52.292  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:52.292  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:44:01.202   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:44:11.252   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:44:15.282   768  1554 E Watchdog: !@Sync 48 [07-06 08:44:15.292]
,07-06 08:44:18.152  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:44:18.272  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 106ms lastUpdatedAfter : 180330ms
,07-06 08:44:21.312   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:44:22.282   768  1759 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:44:31.362   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:44:41.422   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:44:45.292   768  1554 E Watchdog: !@Sync 49 [07-06 08:44:45.296]
,07-06 08:44:51.472   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:44:52.352   768  2251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:44:52.362   768  2251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:44:52.362   768  2251 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:44:52.362   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:44:52.372   768   768 I MotionRecognitionService: Plugged
,07-06 08:44:52.382   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:44:52.382   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:44:52.382   768  2251 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-06 08:44:52.392   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:44:52.392   768  2251 D BatteryService: stay LED for fully charged
,07-06 08:44:52.412  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:44:52.412  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:44:52.412  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:44:52.432  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:44:52.432  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:44:52.442  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:44:52.442  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:44:52.442  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:44:59.822   768  1232 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 08:44:59.832   768  1232 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:44:59.832   768  1231 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:45:01.532   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:45:03.202   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 08:45:03.202   768  1232 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:45:03.212   768  1232 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:45:03.212   768  1232 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:45:11.592   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:45:15.292   768  1554 E Watchdog: !@Sync 50 [07-06 08:45:15.300]
,07-06 08:45:18.342  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:45:18.712   768  2270 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-06 08:45:18.722   768  2270 V MARsPolicyManager: updateSMDBValues
,07-06 08:45:18.722   768   901 E MARsDBManager: updateDBAll : begin --size 0
,07-06 08:45:18.722   768   901 E MARsDBManager: updateDBAll : end
,07-06 08:45:21.642   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:45:22.422   768  2223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:45:31.692   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:45:36.372   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:45:41.752   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:45:45.302   768  1554 E Watchdog: !@Sync 51 [07-06 08:45:45.304]
,07-06 08:45:51.802   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:45:52.492   768  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:46:01.872   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:46:11.932   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-06 08:46:15.302   768  1554 E Watchdog: !@Sync 52 [07-06 08:46:15.309]
,07-06 08:46:16.462   768  1296 D InputReader: Input event(7): value=1 when=1592450367000
,07-06 08:46:16.462   768  1296 D InputReader: !@notifyKey(172), action=0
,07-06 08:46:16.462   768  1296 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,07-06 08:46:16.472   768  1296 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 768  pkgName : WAKEUP_BOOSTER@35
,07-06 08:46:16.482   768  1296 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-06 08:46:16.482   768  1296 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 768) eventTime = 1592450 event = 1
,07-06 08:46:16.482   768  1296 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 768) (1)
,07-06 08:46:16.482   768  1296 I PowerManagerService: Waking up from sleep (uid 1000)...
07-06 08:46:16.482   768  1296 D InputManager-JNI: setInteractive(true)
07-06 08:46:16.492   768  1357 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
,07-06 08:46:16.492   768  1296 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-06 08:46:16.492   768  1296 D PowerManagerService: [s] UserActivityState : 0 -> 1
,07-06 08:46:16.492   768  1296 D PowerManagerService: mDisplayReady: false
07-06 08:46:16.492   768  1296 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-06 08:46:16.492   768  1296 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-06 08:46:16.492   768  1296 D InputManager-JNI: Disable repeat for home key when device wake up
07-06 08:46:16.492   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:16.492   768   907 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
,07-06 08:46:16.492   768  1357 V KeyguardServiceDelegate: onStartedWakingUp()
,07-06 08:46:16.492  1378  3008 I PERF    : KeyguardViewMediator - onStartedWakingUp() start
07-06 08:46:16.492   768   907 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-06 08:46:16.492  1378  3008 D KeyguardViewMediator: onStartedWakingUp, seq = 2
07-06 08:46:16.492  1378  3008 D KeyguardViewMediator: notifyStartedWakingUp
,07-06 08:46:16.492  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() start
,07-06 08:46:16.492  1378  1378 D KeyguardViewMediator: handleNotifyWakingUp
07-06 08:46:16.492   768   907 I ActivityManager: Killing 7467:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 776s, lastActivityTime 776s
07-06 08:46:16.502  1378  1378 D PanelView: onScreenTurnedOn 0,1
07-06 08:46:16.502  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() end
,07-06 08:46:16.502  1378  1378 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() start
,07-06 08:46:16.502   768   907 I ActivityManager: Killing 7406:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 777s, lastActivityTime 777s
,07-06 08:46:16.502   768   907 I ActivityManager: Killing 7380:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 914s, lastActivityTime 914s
,07-06 08:46:16.502   768   907 I ActivityManager: Killing 7366:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 924s, lastActivityTime 924s
,07-06 08:46:16.512  1378  1378 D SecKeyguardClockSingleView: onScreenTurnedOn
,07-06 08:46:16.512  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:16.512  1378  1378 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() end
,07-06 08:46:16.522   768   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,07-06 08:46:16.532   768   907 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@d3e4902)
,07-06 08:46:16.532  7178  7178 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-06 08:46:16.532  7178  7178 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-06 08:46:16.532  7178  7178 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-06 08:46:16.532  7178  7178 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-06 08:46:16.532   768   907 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
07-06 08:46:16.532   768   907 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-06 08:46:16.532   768  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 2, mProxSensorScreenOff: false
,07-06 08:46:16.532   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:16.532   768   907 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-06 08:46:16.532   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,07-06 08:46:16.532   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:16.542   768   916 I libsuspend: !@autosuspend_wakeup_count_disable
07-06 08:46:16.542   768   916 I libsuspend: !@autosuspend_wakeup_count_disable done
07-06 08:46:16.542   768   916 D DisplayManagerService: !@display_state: OFF -> ON brightness: 0 -> 0
,07-06 08:46:16.542   768   903 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-06 08:46:16.542   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
,07-06 08:46:16.542   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
07-06 08:46:16.542   768  1359 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
,07-06 08:46:16.552   768  1693 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
07-06 08:46:16.552   768  1693 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-06 08:46:16.552   768  1693 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,07-06 08:46:16.552   768  1359 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:46:16.552   768  1359 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-06 08:46:16.572   768  1359 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 250000, 0,  
,07-06 08:46:16.572   768  1359 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:46:16.572   768  1359 E Sensors : Acc old sensor_state 512, new sensor_state : 513 en : 1
,07-06 08:46:16.582   768  1359 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 250000, 0,  
07-06 08:46:16.582   768  1359 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::registerListener done: 39ms
,07-06 08:46:16.592   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-06 08:46:16.592   385  4857 I Atfwd_Sendcmd: AtCmdFwd : binderDied
07-06 08:46:16.592   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:16.592  1663  1873 I System.out: Broadcasting: Intent { act=com.sec.android.LTE_WIDEBAND_INFO flg=0x10000000 (has extras) }
,07-06 08:46:16.592  1378  1378 D BatteryMeterView: onDraw batteryColor : -1107296257
,07-06 08:46:16.602   768  1421 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,07-06 08:46:16.602   768  1421 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-06 08:46:16.602  1378  1378 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-06 08:46:16.602  2142  2142 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-06 08:46:16.602  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-06 08:46:16.602   768  2251 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
07-06 08:46:16.602   768  2251 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-06 08:46:16.602   768  2251 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 10944ms
,07-06 08:46:16.602  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-06 08:46:16.612  1378  3008 I PERF    : KeyguardViewMediator - onStartedWakingUp() end
,07-06 08:46:16.612  1378  3008 D KeyguardViewMediator: notifyScreenOn
,07-06 08:46:16.612  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() start
07-06 08:46:16.612  1378  1378 D KeyguardViewMediator: handleNotifyScreenTurningOn
07-06 08:46:16.612  1378  1378 D KeyguardViewMediator: onScreenTurnedOn()
,07-06 08:46:16.612   768  2223 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-06 08:46:16.612  1378  1378 D KeyguardViewMediator: callback.onShown()
07-06 08:46:16.612  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() end
,07-06 08:46:16.612  2142  2142 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-06 08:46:16.612  1378  1378 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-06 08:46:16.612  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-06 08:46:16.612  1378  1378 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-06 08:46:16.612   768   781 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-06 08:46:16.612   768   781 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-06 08:46:16.612   768   781 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 20931ms
,07-06 08:46:16.622   768   858 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-06 08:46:16.622   768   858 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-06 08:46:16.622   768   858 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,07-06 08:46:16.622   768   858 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-06 08:46:16.622   768   858 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-06 08:46:16.622   768   858 V CAE     : start(ContextProvider.java:128)
,07-06 08:46:16.622   768  1494 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-06 08:46:16.622   768  1494 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-06 08:46:16.622   768   858 V CAE     : clear(AutoRotationRunner.java:182)
07-06 08:46:16.622   768  1494 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 30924ms
,07-06 08:46:16.622   768   858 V CAE     : enable(AutoRotationRunner.java:158)
,07-06 08:46:16.622   768   858 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
07-06 08:46:16.622   768   858 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-06 08:46:16.632   333   333 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-06 08:46:16.632   768   768 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-06 08:46:16.632   768   768 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-06 08:46:16.632   768   858 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-06 08:46:16.642   768   858 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:16.642   768  1693 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,07-06 08:46:16.652  3699  3699 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
07-06 08:46:16.652  3699  3699 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,07-06 08:46:16.652   768   858 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:16.652   768   858 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-06 08:46:16.652   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:46:16.652   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:46:16.652   768   858 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-06 08:46:16.652   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:46:16.652   768   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a53e49 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23dbe8 7330:com.samsung.android.sm/1000}
,07-06 08:46:16.652   768   858 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3b3aa08, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-06 08:46:16.662   768   858 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fcbf34e, Service : AUTO_ROTATION(1)
07-06 08:46:16.662   768   858 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-06 08:46:16.662   768   858 D SContextService: 	.registerCallback : 1, client=
,07-06 08:46:16.662   768   858 D SContextService: ===== SContext Service List =====
07-06 08:46:16.662   768   858 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a4c8c6f, Service : Auto Rotation
07-06 08:46:16.662   768   858 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@1f8891b, service=Auto Rotation
07-06 08:46:16.662   768   858 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,07-06 08:46:16.662   768   907 I DisplayPowerController: Unblocked screen on after 168 ms
,07-06 08:46:16.662   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:16.662   768   907 D ColorFade: prepare: mode=2
07-06 08:46:16.662   768   907 D ColorFade: ColorFade is already prepared
,07-06 08:46:16.672   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:16.672   768  1296 D InputReader: Input event(7): value=0 when=1592660130000
07-06 08:46:16.672   768  1296 D InputReader: !@notifyKey(172), action=1
07-06 08:46:16.672   768  1296 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
,07-06 08:46:16.672   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:16.672   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:16.672  1651  1827 D NfcService: call the applyRouting
,07-06 08:46:16.672   768  1296 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-06 08:46:16.672  1994  1994 D SamsungIME: showDlgMsgBox : false true true
,07-06 08:46:16.682   768  1295 D VoIPInterfaceManager: isVoIPRinging()...
07-06 08:46:16.682   303   303 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c0a030
,07-06 08:46:16.682   303   303 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-06 08:46:16.682   768  1295 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-06 08:46:16.682   303   303 I rmt_storage: wakelock acquired: 1, error no: 42
07-06 08:46:16.682   303   614 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1230239440)
07-06 08:46:16.682   768  1295 D VoIPInterfaceManager: Not exist call session
,07-06 08:46:16.682   768  1295 I WindowManager: Ignoring HOME; down is not pressed.
,07-06 08:46:16.702  1378  1378 D PanelView: screenCapture for lockscreen preview
,07-06 08:46:16.702  1378  1378 D StatusBar.NetworkController: LTE WIDEBAND with extra : false
,07-06 08:46:16.702  7178  7178 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a9ac0cb time:1592699
,07-06 08:46:16.712  1663  1886 I System.out: Broadcast completed: result=0
,07-06 08:46:16.712  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:16.722  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:16.722   768   768 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
07-06 08:46:16.722  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:16.722   768   768 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
07-06 08:46:16.722  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:16.722  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:16.722   768   768 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-06 08:46:16.722   768   768 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
07-06 08:46:16.722   768   768 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-06 08:46:16.722   768   768 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
07-06 08:46:16.722   768   768 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 768) 
,07-06 08:46:16.722   768   768 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
07-06 08:46:16.722   768   768 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:46:16.722   768   914 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-06 08:46:16.722   768   768 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-06 08:46:16.722   768   914 D SensorManager: unregisterListener ::   
07-06 08:46:16.722   768   914 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-06 08:46:16.722   768   914 V AlarmManager:  remove PendingIntent] PendingIntent{743655a: PendingIntentRecord{e2fc38b android broadcastIntent}}
07-06 08:46:16.722   768   768 D UsbDeviceManager: Keyguard Lock/Unlock
07-06 08:46:16.722   768   768 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
,07-06 08:46:16.722   768   768 D UsbDeviceManager: mps exists
,07-06 08:46:16.732   768   768 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
,07-06 08:46:16.732   768   768 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0210
,07-06 08:46:16.732   768   768 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Transferring media files via USB
,07-06 08:46:16.732   768   768 D UsbDeviceManager: updateUsbNotification : isKeyguardShowingAndNotOccluded = false, isKeyguardSecure = false, mBootCompleted = true
,07-06 08:46:16.732   768   768 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
,07-06 08:46:16.732   768   768 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Transferring media files via USB
,07-06 08:46:16.732   768   768 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
07-06 08:46:16.732   768   768 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
07-06 08:46:16.732   768   768 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
07-06 08:46:16.732   768   768 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 768) 
07-06 08:46:16.732   768   768 D PalmMotion: [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
07-06 08:46:16.732   768   768 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
,07-06 08:46:16.732   768   914 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-06 08:46:16.732   768   914 D lights  : led_pattern : 0 +
,07-06 08:46:16.742   768   914 D lights  : led_pattern : 0 -
,07-06 08:46:16.742   768   914 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:46:16.742   768   768 D BatteryService: turn off LED
,07-06 08:46:16.742   303   614 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-06 08:46:16.742   303   614 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-06 08:46:16.742   303   614 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1230239440) wakelock released: 1, error no: 0
07-06 08:46:16.742   303   614 I rmt_storage: 
,07-06 08:46:16.742   303   303 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c0a030
,07-06 08:46:16.752   768  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a53e49 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81b0cfd 2102:com.google.android.gms.persistent/u0a11}
,07-06 08:46:16.762  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-06 08:46:16.762  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-06 08:46:16.762  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:46:16.772  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:46:16.782   768   781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a53e49 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81b0cfd 2102:com.google.android.gms.persistent/u0a11}
,07-06 08:46:16.782   768   768 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-06 08:46:16.782   768   768 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-06 08:46:16.782   768   768 D UcmService: notifyChangeToPlugin event 16
07-06 08:46:16.782   768   768 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-06 08:46:16.782   768   768 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-06 08:46:16.782   768   768 D UcmService: notifying to unmanaged plugin
,07-06 08:46:16.782  1729  1742 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-06 08:46:16.782   768   768 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-06 08:46:16.782  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
07-06 08:46:16.782   768   768 D UcmService: agentService status-0
,07-06 08:46:16.792   768   768 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
,07-06 08:46:16.792   768   768 D UcmService: notifying to unmanaged plugin
,07-06 08:46:16.792  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:16.792  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:16.792  1745  1757 D BootAgentService: notifyChange eventId-16
,07-06 08:46:16.792  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:16.792  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:16.792  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:16.792  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:16.792   768   768 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
,07-06 08:46:16.802   768   768 D UcmService: agentService status--1
,07-06 08:46:16.802   768   768 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-06 08:46:16.802   768   768 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 768) 
,07-06 08:46:16.802  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:16.802   768   768 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
,07-06 08:46:16.802   768   914 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-06 08:46:16.802   768   914 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:46:16.802   768   768 D EdgeLight: Turning off
,07-06 08:46:16.802   294   565 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
07-06 08:46:16.802   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,07-06 08:46:16.812   768   916 D SurfaceControl: Excessive delay in setPowerMode(): 269ms
07-06 08:46:16.812   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
07-06 08:46:16.812   768   916 D PowerManagerUtil: Excessive delay in !@display_state: ON: 270ms
07-06 08:46:16.812   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:16.812   768   907 D ColorFade: prepare: mode=2
07-06 08:46:16.812   768   907 D ColorFade: ColorFade is already prepared
,07-06 08:46:16.812   768   907 D DisplayPowerState: !@ [0] ColorFade exit
07-06 08:46:16.812   768   907 D PowerManagerService: [input device light] onColorFadeExit(true)
07-06 08:46:16.812   768   907 D DisplayPowerController: ColorFade: onAnimationStart
07-06 08:46:16.812   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:16.812   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:16.812   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-06 08:46:16.812   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:16.812   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:16.812   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:16.822   768  7626 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 1
07-06 08:46:16.822   768  7627 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,07-06 08:46:16.822   768   781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a53e49 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{81b0cfd 2102:com.google.android.gms.persistent/u0a11}
,07-06 08:46:16.832   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:16.832   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:16.832   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:16.832   768   768 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
,07-06 08:46:16.832  2102  2102 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver bqHint=4 }.
07-06 08:46:16.832   768   768 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package null
,07-06 08:46:16.832   768   768 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-C:4
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:16.852  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:16.852  1378  1378 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-06 08:46:16.862   768   768 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-C:4
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:16.862  1378  1378 D PhoneStatusBar: animateCollapse(): mExpandedVisible=false flags=0
07-06 08:46:16.862  1378  1378 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
07-06 08:46:16.862  1378  1378 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
07-06 08:46:16.862  1378  1378 D CoverUI : applyHeight h = 72, oc = false, ex = false, fa = false, ac = false, sc = false
07-06 08:46:16.862  1378  1378 V NotificationStackScrollLayout: start: -201.0stackHeight: 201.0
07-06 08:46:16.862  1378  1378 V NotificationStackScrollLayout: start: -201.0stackHeight: 201.0
,07-06 08:46:16.862   768   768 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
,07-06 08:46:16.862   768   768 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
07-06 08:46:16.862   768   768 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-06 08:46:16.862  1378  1378 V NotificationStackScrollLayout: start: -201.0stackHeight: 201.0
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-C:4
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:16.862  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:16.862   333   558 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-06 08:46:16.882   768   768 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-C:4
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:16.882  1378  1378 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:16.882  1378  1378 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-06 08:46:16.892   768  1244 E MotionRecognitionService:  handler : SCREEN_ON end
,07-06 08:46:16.912   768   768 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
,07-06 08:46:16.912  1378  1378 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,07-06 08:46:16.922   768   768 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-06 08:46:16.922   768   768 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-06 08:46:16.922   768   768 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-06 08:46:16.922   768   768 D UcmService: notifyChangeToPlugin event 16
07-06 08:46:16.922   768   768 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-06 08:46:16.922   768   768 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-06 08:46:16.922   768   768 D UcmService: notifying to unmanaged plugin
,07-06 08:46:16.922  1729  1750 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-06 08:46:16.922   768   768 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
,07-06 08:46:16.922   768   768 D UcmService: agentService status-0
07-06 08:46:16.922   768   768 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-06 08:46:16.922   768   768 D UcmService: notifying to unmanaged plugin
,07-06 08:46:16.922  1745  1758 D BootAgentService: notifyChange eventId-16
07-06 08:46:16.922   768   768 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
,07-06 08:46:16.932   768  7626 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-06 08:46:16.932   768   768 D UcmService: agentService status--1
07-06 08:46:16.932   768   768 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-06 08:46:16.932  1378  1378 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,07-06 08:46:16.932   768  1359 D AutomaticBrightnessController: [DAB] onSensorChanged : 1st lux : 25.0
07-06 08:46:16.932   768  1359 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 42(42.0)    0.0 < 25.0 < 66.0 (0.0)
07-06 08:46:16.932   768  1359 D AutomaticBrightnessController: mCallbacks.updateBrightness()
07-06 08:46:16.932   768  1359 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
,07-06 08:46:16.932   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:16.932   768   907 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 25
07-06 08:46:16.932   768   907 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
,07-06 08:46:16.952   768   768 D NotificationService: ACTION_SCREEN_ON
,07-06 08:46:16.952  1378  1378 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-06 08:46:16.952   768   768 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 768) 
07-06 08:46:16.952   768   907 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
07-06 08:46:16.952   768   768 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-06 08:46:16.952   768   907 D DisplayPowerController: getFinalBrightness : Summary is 42 -> 42
07-06 08:46:16.952   768   907 D DisplayPowerController: Animating brightness: target=42, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:16.952   768   914 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-06 08:46:16.952   768   914 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:46:16.952   768   907 D DisplayPowerState: Requesting new screen state: [0] state=ON, backlight (By colorFade)=42
07-06 08:46:16.952   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:16.952   768   768 D EdgeLight: Turning off
07-06 08:46:16.952   768  1360 D DisplayPowerState: Updating screen state [0]: state=ON, backlight (by ColorFade)=42
07-06 08:46:16.952   768  1360 D lights  : lcd : 42 +
07-06 08:46:16.952   768  1360 D lights  : lcd : 42 -
07-06 08:46:16.952   768   907 D DisplayPowerController: getFinalBrightness : Summary is 42 -> 42
07-06 08:46:16.952   768   907 D DisplayPowerController: Animating brightness: target=42, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:16.962   768  1322 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
07-06 08:46:16.962   768  1322 D WifiNative-wlan0: callSECApiBoolean - ID [11]
07-06 08:46:16.962  1540  1540 I wpa_supplicant: STOP_PERIODIC_SCAN command
,07-06 08:46:16.962  1378  1378 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-06 08:46:16.962   324  2150 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-06 08:46:16.962   324  2150 V voice   : voice_set_parameters: enter: screen_state=on
07-06 08:46:16.962   324  2150 V voice   : voice_set_parameters: exit with code(-2)
07-06 08:46:16.962   324  2150 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-06 08:46:16.962   324  2150 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-06 08:46:16.962   324  2150 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-06 08:46:16.962   324  2150 V audio_hw_primary: adev_set_parameters: exit
,07-06 08:46:16.972   768   768 V AlarmManager:  remove PendingIntent] PendingIntent{da37269: PendingIntentRecord{1a9e4ee android broadcastIntent}}
,07-06 08:46:16.982  1378  1378 D Recents : handleProxyCall type=3
07-06 08:46:16.982   768  1322 E WifiNative-wlan0: do suspend false
,07-06 08:46:16.992   768  1322 D WifiStateMachine: analyze kernel wifi wakelock 
,07-06 08:46:16.992   768  1322 D WifiStateMachine: file not found /proc/wakelocks
07-06 08:46:17.002  1449  1449 D Recents : handleProxyCall type=3
,07-06 08:46:17.012   768  1323 V AlarmManager:  remove PendingIntent] PendingIntent{72b2d8f: PendingIntentRecord{de281c android broadcastIntent}}
,07-06 08:46:17.012   768   768 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
07-06 08:46:17.012   768   768 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-06 08:46:17.012   768   768 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-06 08:46:17.012   768   768 V CAE     : start(ContextProvider.java:128)
,07-06 08:46:17.012   768   768 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-06 08:46:17.012   768   768 V CAE     : enable(ActivityTrackerRunner.java:84)
,07-06 08:46:17.022   768   768 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 46, 17,
,07-06 08:46:17.022   768   768 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 46, 17
07-06 08:46:17.022   333   333 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 46, 17
,07-06 08:46:17.032   768   768 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-06 08:46:17.032   768  7627 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
07-06 08:46:17.032   768   768 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:17.032   768   916 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-06 08:46:17.032   768   916 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-06 08:46:17.032   768   916 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 222ms
,07-06 08:46:17.032   768   916 I QCOM PowerHAL: Got set_interactive hint
,07-06 08:46:17.032   768   916 D PowerManagerUtil: Excessive delay in nativeSetInteractive(true): 225ms
07-06 08:46:17.032   768  1358 D lights  : button : 1 +
,07-06 08:46:17.032   768   916 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 496ms
07-06 08:46:17.032   333   557 D Sensorhubs: readContextData: 1, 1, 26, 1, 1, 115, -12, 28, 0, 0
,07-06 08:46:17.032   768  1241 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 1, 115, -12, 28, 0, 0
07-06 08:46:17.032   768  1240 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
,07-06 08:46:17.032   768  1240 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
07-06 08:46:17.032   768  1240 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 1, 115, -12, 28, 0, 0,
07-06 08:46:17.032   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:17.032   768  1240 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-06 08:46:17.032   768   907 D DisplayPowerController: getFinalBrightness : Summary is 42 -> 42
07-06 08:46:17.032   768  1240 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467787576348]
,07-06 08:46:17.032   768   907 D DisplayPowerController: Animating brightness: target=42, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:17.032   768  1243 D SContextService: updateSContext() : event = Activity Tracker
,07-06 08:46:17.042   768   768 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:17.042   768   768 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-06 08:46:17.042   768   768 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,07-06 08:46:17.042   768   768 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3b3aa08, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-06 08:46:17.042  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:17.042   768   768 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3b3aa08, Service : ACTIVITY_TRACKER(1)
07-06 08:46:17.042   768   768 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fcbf34e, Service : AUTO_ROTATION(1)
,07-06 08:46:17.042   768   768 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-06 08:46:17.042   768   768 D SContextService: 	.registerCallback : 2, client=
07-06 08:46:17.042   768   768 D SContextService: ===== SContext Service List =====
07-06 08:46:17.042   768   768 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@a4c8c6f, Service : Auto Rotation
07-06 08:46:17.042   768   768 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@5def6b2, Service : Activity Tracker
07-06 08:46:17.042   768   768 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@c8660bd, service=Activity Tracker
07-06 08:46:17.052   768   768 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
07-06 08:46:17.052   768   768 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,07-06 08:46:17.052   768   768 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-06 08:46:17.052   768   768 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-06 08:46:17.052   768   768 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
,07-06 08:46:17.052   333   558 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-06 08:46:17.052   768   768 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
07-06 08:46:17.052   768   768 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:17.062   768   781 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{ec57603 u-1 android.intent.action.TIME_TICK qIdx=2}, state= (IDLE) to ReceiverList{f2854c0 1378 com.android.systemui/10058/u0 remote:bed5643}: filter unregistered
,07-06 08:46:17.062   768   856 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{ec57603 u-1 android.intent.action.TIME_TICK qIdx=2}, state= (IDLE) to ReceiverList{8a53adb 7467 com.sec.android.daemonapp/10181/u0 remote:4f1e7ea}: filter unregistered
,07-06 08:46:17.072   768  1358 D lights  : button : 1 -
,07-06 08:46:17.072   768   768 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
07-06 08:46:17.072   768   768 D SContextService: requestToUpdate() : service = Activity Tracker
07-06 08:46:17.072   768   768 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@c8660bd, service=Activity Tracker
,07-06 08:46:17.072   768   768 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,07-06 08:46:17.072   768   768 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-06 08:46:17.072   768   768 D WifiService: setWifiScanWithSensor bMove = 0
07-06 08:46:17.072   768   768 D WifiStateMachine: setWifiScanMove bMove = 0
07-06 08:46:17.072   768   768 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-06 08:46:17.072   768   903 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-06 08:46:17.072   768   903 D IpRemoteDisplayController: Bridge Server is not available
07-06 08:46:17.072   768  1322 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
,07-06 08:46:17.072  1540  1540 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,07-06 08:46:17.072   333   557 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 1, 115, -12, 67, 0, 0
07-06 08:46:17.072   768  1241 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 1, 115, -12, 67, 0, 0
,07-06 08:46:17.072   768  1240 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
07-06 08:46:17.072   768  1240 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
07-06 08:46:17.072   768  1240 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 1, 115, -12, 67, 0, 0,
07-06 08:46:17.072   768  1240 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-06 08:46:17.072   768  1240 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467787576387]
07-06 08:46:17.072   768  1243 D SContextService: updateSContext() : event = Activity Tracker
,07-06 08:46:17.072   768   768 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,07-06 08:46:17.072   768   768 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-06 08:46:17.082   768  1320 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
07-06 08:46:17.082   768  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,07-06 08:46:17.082   768  1320 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,07-06 08:46:17.082  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205dc/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:17.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:17.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:17.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:17.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:17.432   333   557 D Sensorhubs: readContextData: 1, 1, 26, 1, 1, 115, -11, -86, 1, 2
,07-06 08:46:17.432   768  1241 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 1, 115, -11, -86, 1, 2
07-06 08:46:17.432   768  1240 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-06 08:46:17.432   768  1240 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,07-06 08:46:17.432   768  1240 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 1, 115, -11, -86, 1, 2,
07-06 08:46:17.432   768  1240 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-06 08:46:17.432   768  1240 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[1], TimeStamp=[1467787576746]
,07-06 08:46:17.432   768  1243 D SContextService: updateSContext() : event = Activity Tracker
07-06 08:46:17.432   768   768 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-06 08:46:17.432   768   768 D WifiService: ACTIVITY_STATUS_STATIONARY 
,07-06 08:46:17.472   768   768 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 768  tag : WAKEUP_BOOSTER@35
,07-06 08:46:17.562   768   856 I ActivityManager: Start proc 7636:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-06 08:46:17.562  7636  7636 E Zygote  : v2
07-06 08:46:17.562  7636  7636 I libpersona: KNOX_SDCARD checking this for 10026
07-06 08:46:17.562  7636  7636 I libpersona: KNOX_SDCARD not a persona
,07-06 08:46:17.562  7636  7636 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:46:17.562  7636  7636 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:46:17.562  7636  7636 E Zygote  : accessInfo : 0
07-06 08:46:17.562  7636  7636 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-06 08:46:17.592  7636  7636 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:46:17.592  7636  7636 D ActivityThread: Added TimaKeyStore provider
,07-06 08:46:17.592   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:17.602  7636  7636 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-06 08:46:17.622  7636  7636 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-06 08:46:17.632  7636  7636 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-06 08:46:17.632  7636  7636 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-06 08:46:17.642   768   907 D DisplayPowerController: ColorFade: onAnimationEnd
,07-06 08:46:17.642   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:17.652   294   344 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
,07-06 08:46:17.652   294   344 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
07-06 08:46:17.652   768   907 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-06 08:46:17.652   294   338 I SurfaceFlinger: id=13 Removed DolorFade (8/8)
,07-06 08:46:17.652   294  1362 I SurfaceFlinger: id=13 Removed DolorFade (-2/8)
,07-06 08:46:17.662   768   907 D PowerManagerUtil: Excessive delay in ColorFade : dismiss: 18ms
,07-06 08:46:17.662   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f93a4
07-06 08:46:17.662   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:17.662   768   907 D DisplayPowerController: getFinalBrightness : Summary is 42 -> 42
07-06 08:46:17.662   768   907 D DisplayPowerController: Animating brightness: target=42, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:17.662   768   907 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
07-06 08:46:17.662   768   907 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
,07-06 08:46:17.662   768   907 V KeyguardServiceDelegate: onScreenTurnedOn()
07-06 08:46:17.662   768   907 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-06 08:46:17.662  1378  3008 D KeyguardViewMediator: notifyScreenTurnedOn
,07-06 08:46:17.662  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() start
07-06 08:46:17.662  1378  1378 D KeyguardViewMediator: handleNotifyScreenTurnedOn
07-06 08:46:17.662  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() end
07-06 08:46:17.662   768   907 D PowerManagerService: mDisplayReady: true
,07-06 08:46:18.082  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:18.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.082  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.092  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.462  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:46:18.532   768  1358 D lights  : button : 0 +
,07-06 08:46:18.572   768  1358 D lights  : button : 0 -
,07-06 08:46:18.592   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:19.402   768   848 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-06 08:46:19.402   768   768 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-06 08:46:19.402   768   939 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-06 08:46:19.402   768  1694 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
07-06 08:46:19.402  1651  1651 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-06 08:46:19.412  1651  2289 D NfcService: call the applyRouting
,07-06 08:46:19.412  1378  1378 D StatusBar.NetworkController: onDataActivity: direction=0
,07-06 08:46:19.412  1378  1378 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-06 08:46:19.422   768   768 V AlarmManager:  remove PendingIntent] PendingIntent{51f6f5f: PendingIntentRecord{8d50d67 android broadcastIntent}}
07-06 08:46:19.422   768   768 V AlarmManager:  remove PendingIntent] PendingIntent{4cb8dac: PendingIntentRecord{cbe2a53 android broadcastIntent}}
,07-06 08:46:19.432  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,07-06 08:46:19.432  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,07-06 08:46:19.432  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
07-06 08:46:19.432  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
07-06 08:46:19.432  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
07-06 08:46:19.432  2302  2302 D accuweather: [KK AccuPhone]>>> SM:1417 [0:0] setClockLayoutContent
,07-06 08:46:19.442  2302  2302 D accuweather: [KK AccuPhone]>>> U:850 [0:0] Locale format : MMM d, y
,07-06 08:46:19.442  2142  2142 D BtGatt.GattService: LCD turned on
,07-06 08:46:19.442  2142  2390 D BtGatt.ScanManager: handleLcdOnIntent
07-06 08:46:19.442  2142  2390 D BtGatt.ScanManager: handleLcdOnIntent
07-06 08:46:19.442  2142  2390 D BtGatt.ScanManager: ClientIf = 0
,07-06 08:46:19.452  1994  1994 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-06 08:46:19.502  6687  6687 D SystemBroadcastReceiver: [FACE] Received broadcast 
,07-06 08:46:19.502  6687  6687 I SystemBroadcastReceiver: [FACE] onReceive broadcastcompleted  
,07-06 08:46:19.502  6687  7654 I SystemBroadcastReceiver: [FACE] Calling notifyListeners. 
07-06 08:46:19.502  6687  7654 D SystemBroadcastReceiver: [FACE] Event id =  EVENT_SCREEN_ON
07-06 08:46:19.502  6687  7654 D SystemBroadcastReceiver: [FACE] getRegisteredListnersForIntent completed 
07-06 08:46:19.502  6687  7654 I PolicyManager: [FACE] onReceive action = EVENT_SCREEN_ON
,07-06 08:46:19.512   768  1421 W BroadcastQueue: Skipping deliver [sec] BroadcastRecord{d6aaa0a u-1 android.intent.action.SCREEN_ON qIdx=1}, state= (IDLE) to ReceiverList{8a53adb 7467 com.sec.android.daemonapp/10181/u0 remote:4f1e7ea}: filter unregistered
,07-06 08:46:19.512   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 450, LCD = 42
,07-06 08:46:19.512   768  1357 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-06 08:46:19.512  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:19.512  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:19.512  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:19.522  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:19.522  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:19.522   768  3441 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:46:19.542  7655  7655 E Zygote  : v2
07-06 08:46:19.542  7655  7655 I libpersona: KNOX_SDCARD checking this for 10181
07-06 08:46:19.542  7655  7655 I libpersona: KNOX_SDCARD not a persona
,07-06 08:46:19.542  7655  7655 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-06 08:46:19.542  7655  7655 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-06 08:46:19.542   768   856 I ActivityManager: Start proc 7655:com.sec.android.daemonapp/u0a181 for broadcast-3 com.sec.android.daemonapp/.ap.accuweather.AccuWeatherDaemonService
07-06 08:46:19.542   768  1320 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,07-06 08:46:19.542  7655  7655 E Zygote  : accessInfo : 0
07-06 08:46:19.542  7655  7655 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-06 08:46:19.562  7655  7655 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:46:19.562  7655  7655 D ActivityThread: Added TimaKeyStore provider
,07-06 08:46:19.572   768  2239 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3f5a27b u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d39d898 7655:com.sec.android.daemonapp/u0a181}
,07-06 08:46:19.572   768  1320 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: true, uidstate: 10, mProxSensorScreenOff: false
,07-06 08:46:19.582  7655  7655 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-06 08:46:19.582   768  7667 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-06 08:46:19.582   768  7667 D BluetoothAdapter: STATE_ON
,07-06 08:46:19.582  2142  2427 D bt_vendor: op for 7
,07-06 08:46:19.582  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-06 08:46:19.592  2142  2427 D bt_upio : upio_start_stop_timer : timer_settime success
,07-06 08:46:19.592  2142  2427 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-06 08:46:19.592   768  1759 V AlarmManager:  remove PendingIntent] PendingIntent{f2fb8f1: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:46:19.592   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:19.602  7655  7655 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-06 08:46:19.612  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-06 08:46:19.612  7655  7655 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:46:19.632  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-06 08:46:19.632   768  7667 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
07-06 08:46:19.632  7655  7655 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:46:19.632  7655  7655 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-06 08:46:19.632  7655  7655 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:46:19.632  7655  7655 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
07-06 08:46:19.632  7655  7655 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-06 08:46:19.642  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.642  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-06 08:46:19.652  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.652  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.652  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-06 08:46:19.662  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-06 08:46:19.662  7655  7655 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:false
,07-06 08:46:19.672  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.672  7655  7655 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-06 08:46:19.672  7655  7655 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:46:19.672  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:45 [0:0] WeatherClockService start : 
,07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:419 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][NUT] = 1467807600000
07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:424 [0:0] [ASO][CT] = 1467787579680
07-06 08:46:19.672  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-06 08:46:19.682  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1609 [0:0] PakNme size = 5
,07-06 08:46:19.682  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.682  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.682  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1613 [0:0] CP Name cp_eng
,07-06 08:46:19.682  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-06 08:46:19.682  7655  7655 E daemonapp: [MSC_Daemon]>>> WU:1593 [0:0] [NameNotFoundException] !!
,07-06 08:46:19.682  7655  7655 D daemonapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-06 08:46:19.692   768  1693 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d115cd6 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d39d898 7655:com.sec.android.daemonapp/u0a181}
,07-06 08:46:19.692  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.692  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.692  7655  7655 D daemonapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-06 08:46:19.692  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.692  7655  7655 D daemonapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-06 08:46:19.692  7655  7655 D daemonapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-06 08:46:19.702  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.702  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.702  7655  7655 D daemonapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
07-06 08:46:19.702  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.702  7655  7655 D daemonapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-06 08:46:19.702   768  7667 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:46:19.712  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.712  7655  7655 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:46:19.712  7655  7655 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:46:19.712  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-06 08:46:19.712   768  7667 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-06 08:46:19.712  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.722  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:46:19.722   768   781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{17fe5f3 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d39d898 7655:com.sec.android.daemonapp/u0a181}
,07-06 08:46:19.722  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.722  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.722  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:46:19.732  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.732  7655  7655 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:46:19.732  7655  7655 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:46:19.732  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.732  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:46:19.742   768  2223 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{87722b0 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d39d898 7655:com.sec.android.daemonapp/u0a181}
,07-06 08:46:19.742  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.742  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.742  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:19.742  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.742  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:46:19.742  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.742  7655  7655 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:46:19.742  7655  7655 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:46:19.742  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.742  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-06 08:46:19.752  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-06 08:46:19.752  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-06 08:46:19.752  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:46:19.752  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-06 08:46:19.752  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.752  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:46:19.752   768  1694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b6b9529 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d39d898 7655:com.sec.android.daemonapp/u0a181}
,07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-06 08:46:19.762  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.762  7655  7655 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:46:19.762  7655  7655 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-06 08:46:19.762  7655  7655 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-06 08:46:19.762  7655  7655 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:19.772  7655  7655 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-06 08:46:19.892   768  7667 I BatteryStatsDumper: Writing to database completed
,07-06 08:46:20.092  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:20.092  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:20.092  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:20.092  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:20.092  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:20.392  2142  2700 D bt_upio : ..proc_btwrite_timeout..
,07-06 08:46:20.392  2142  2700 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-06 08:46:20.592   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:21.092  2142  2427 D bt_vendor: op for 7
07-06 08:46:21.092  2142  2427 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-06 08:46:21.092  2142  2427 D bt_upio : BT_WAKE is de-asserted already
,07-06 08:46:21.092   768  1694 V AlarmManager:  remove PendingIntent] PendingIntent{af730ae: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:46:21.102  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:21.102  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.102  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.102  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.112  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.592   385  4857 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-06 08:46:22.562   768  2251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:46:24.122  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:24.122  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:24.132  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:24.132  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:24.132  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:26.602   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:27.152  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:27.152  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.152  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.152  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.162  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.602   768   856 I ActivityManager: Start proc 7675:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-06 08:46:27.602   385  4857 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 08:46:27.612  7675  7675 E Zygote  : v2
,07-06 08:46:27.612  7675  7675 I libpersona: KNOX_SDCARD checking this for 1000
07-06 08:46:27.612  7675  7675 I libpersona: KNOX_SDCARD not a persona
,07-06 08:46:27.612  7675  7675 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:46:27.612  7675  7675 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:46:27.622  7675  7675 E Zygote  : accessInfo : 0
,07-06 08:46:27.662  7675  7675 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 08:46:27.662  7675  7675 D ActivityThread: Added TimaKeyStore provider
,07-06 08:46:27.692  7675  7675 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-06 08:46:27.712  7675  7675 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-06 08:46:27.722  7675  7675 D AtFwdService: onCreate method
,07-06 08:46:27.722  7675  7675 I AtFwdService: Instantiate AtCmdFwd Service
,07-06 08:46:27.732  7675  7687 D AtCkpdCmdHandler: De-queing command
,07-06 08:46:29.162  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:29.162  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.172  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.172  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.172  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.562   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 42
,07-06 08:46:30.172  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:30.172  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.182  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.182  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.182  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.192  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:32.192  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.202  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.202  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.202  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.202  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:33.202  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.212  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.212  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.212  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.222  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:35.222  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.232  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.232  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.232  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.232  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:36.232  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.242  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.242  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.242  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.242  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:37.242  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.252  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.252  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.252  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.582   768   856 I ActivityManager: Start proc 7689:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService
,07-06 08:46:37.582  7689  7689 E Zygote  : v2
07-06 08:46:37.592  7689  7689 I libpersona: KNOX_SDCARD checking this for 10034
,07-06 08:46:37.592  7689  7689 I libpersona: KNOX_SDCARD not a persona
,07-06 08:46:37.592  7689  7689 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-06 08:46:37.592  7689  7689 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:46:37.592  7689  7689 E Zygote  : accessInfo : 0
,07-06 08:46:37.592  7689  7689 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-06 08:46:37.622  7689  7689 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:46:37.622  7689  7689 D ActivityThread: Added TimaKeyStore provider
,07-06 08:46:37.642  7689  7689 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-06 08:46:37.662  7689  7689 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-06 08:46:37.672  7689  7689 I MultiDex: VM with version 2.1.0 has multidex support
07-06 08:46:37.672  7689  7689 I MultiDex: install
07-06 08:46:37.672  7689  7689 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-06 08:46:37.672  7689  7689 I MultiDex: install
07-06 08:46:37.672  7689  7689 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-06 08:46:37.742  7689  7689 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-06 08:46:37.742  7689  7689 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-06 08:46:37.762  1378  1378 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-06 08:46:37.772   768  1693 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-06 08:46:37.772  1378  1378 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{7de4417 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,07-06 08:46:37.772  1378  1378 D AdaptiveEventManager: M updateContainers()
07-06 08:46:37.772  1378  1378 D AdaptiveEventContainerSmall: C updatePedoContainer()
07-06 08:46:37.772  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate()
07-06 08:46:37.772   768  1694 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-06 08:46:37.772  1378  1378 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-06 08:46:37.772   768  1421 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-06 08:46:37.782   768  2223 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-06 08:46:37.802  7689  7689 I Health.HealthService: HealthService: onCreate() start (7689)
,07-06 08:46:37.922  7689  7689 D HealthDataStore: Service for HealthDataStore is connected
,07-06 08:46:37.932  7689  7689 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-06 08:46:37.932  7689  7689 D HealthConsole: Service for HealthDataConsole is connected
,07-06 08:46:37.932  7689  7689 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-06 08:46:37.932  7689  7689 E HealthDataStore: disconnectService: Context instance is invalid
,07-06 08:46:38.032  7689  7707 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-06 08:46:38.062  7689  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-06 08:46:38.072  7431  7488 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-06 08:46:38.282  7689  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-06 08:46:38.382  7689  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-06 08:46:38.382  7689  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-06 08:46:39.262  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:39.262  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.272  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.272  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.272  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.622   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 42
,07-06 08:46:40.672   768   907 D PowerManagerService: [s] UserActivityState : 1 -> 2
07-06 08:46:40.672   768   907 D PowerManagerService: mDisplayReady: false
07-06 08:46:40.672   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:40.672   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:40.672   768   907 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:40.672   768   907 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:40.672   768   907 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged(),
07-06 08:46:40.672   768   907 D PowerManagerService: mDisplayReady: true
,07-06 08:46:40.692   768  1360 D lights  : lcd : 32 +
,07-06 08:46:40.702   768  1360 D lights  : lcd : 32 -
,07-06 08:46:40.712   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:40.712   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:40.712   768  1360 D lights  : lcd : 24 +
,07-06 08:46:40.712   768   907 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:40.712   768   907 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:40.722   768  1360 D lights  : lcd : 24 -
,07-06 08:46:40.722   768  1360 D lights  : lcd : 16 +
,07-06 08:46:40.722   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:40.732   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:40.732   768   907 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-06 08:46:40.732   768   907 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:40.742   768  1360 D lights  : lcd : 16 -
,07-06 08:46:40.742   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:40.742   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:40.742   768   907 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:40.742   768   907 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:40.742   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:40.742   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:40.742   768   907 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:40.742   768   907 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:40.742   768  1360 D lights  : lcd : 15 +
,07-06 08:46:40.752   768  1360 D lights  : lcd : 15 -
,07-06 08:46:40.762   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:40.762   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:40.762   768   907 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-06 08:46:40.762   768   907 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:41.282  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:41.282  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:41.292  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:41.292  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:41.292  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.292  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:42.302  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.302  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.302  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.302  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.312  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:44.312  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.322  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.322  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.322  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:45.312   768  1554 E Watchdog: !@Sync 53 [07-06 08:46:45.314]
,07-06 08:46:46.812   768   907 D PowerManagerService: [s] UserActivityState : 2 -> 4
,07-06 08:46:46.812   768   907 I PowerManagerService: Nap time (uid 1000)...
,07-06 08:46:46.812   768   907 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
07-06 08:46:46.812   768   907 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
07-06 08:46:46.812   768   907 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-06 08:46:46.812   768   907 D InputManager-JNI: setInteractive(false)
07-06 08:46:46.812   768  1357 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,07-06 08:46:46.822  1378  1404 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() start
07-06 08:46:46.822  1378  1404 D KeyguardViewMediator: onStartedGoingToSleep(3)
,07-06 08:46:46.822   768   907 D PowerManagerService: mDisplayReady: false
,07-06 08:46:46.822  7178  7178 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-06 08:46:46.832   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=1
,07-06 08:46:46.832   768   907 D ColorFade: prepare: mode=4
,07-06 08:46:46.832   294   294 I SurfaceFlinger: id=18 createSurf (1080x1920),2 flag=404, DolorFade
,07-06 08:46:46.852   768   907 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 16ms
,07-06 08:46:46.852  1378  1404 D KeyguardViewMediator: timeout : 5000
,07-06 08:46:46.862   768   907 D PowerManagerUtil: Excessive delay in ColorFade : createEglSurface: 14ms
,07-06 08:46:46.872  1378  1404 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,07-06 08:46:46.872  1378  1404 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() end
,07-06 08:46:46.892   768   907 D libEGL  : eglInitialize EGLDisplay = 0x9a93c0cc
,07-06 08:46:46.892   768   907 D libEGL  : eglTerminate EGLDisplay = 0x9a93c1d4
,07-06 08:46:46.902   768   907 D ColorFade: ColorFade is ready
,07-06 08:46:46.902   768   907 D DisplayPowerController: ColorFade: onAnimationStart
,07-06 08:46:46.902   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:46.902   768   907 D DisplayPowerController: getFinalBrightness : Summary is 42 -> 42
,07-06 08:46:46.932   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
,07-06 08:46:46.942   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
,07-06 08:46:47.012   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
,07-06 08:46:47.202   768   907 D DisplayPowerState: !@ [0] ColorFade entry
,07-06 08:46:47.202   768   907 D PowerManagerService: [input device light] onColorFadeExit(false)
,07-06 08:46:47.202   768   907 D DisplayPowerController: ColorFade: onAnimationEnd
,07-06 08:46:47.212   768  1360 D lights  : lcd : 0 +
,07-06 08:46:47.212   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=1
,07-06 08:46:47.212   768   907 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,07-06 08:46:47.222   768  1360 D lights  : lcd : 0 -
,07-06 08:46:47.272  7178  7178 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-06 08:46:47.272  7178  7178 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-06 08:46:47.372   768   907 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@a4c8c6f, Service = Auto Rotation, used = 0
,07-06 08:46:47.372   768   907 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-06 08:46:47.372   768  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,07-06 08:46:47.372   768   907 V CAE     : stop(ContextProvider.java:155)
,07-06 08:46:47.382  7178  7178 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d91089 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@70a79f3, 16908290=android.view.AbsSavedState$1@70a79f3}, android:focusedViewId=100}]}]
,07-06 08:46:47.382  7178  7178 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-06 08:46:47.382  7178  7178 V ActivityThread: updateVisibility : ActivityRecord{d407e43 token=android.os.BinderProxy@a9ac0cb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-06 08:46:47.382  7178  7178 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-06 08:46:47.382  7178  7178 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-06 08:46:47.382   768   907 V CAE     : clear(AutoRotationRunner.java:182)
,07-06 08:46:47.382   768   907 V CAE     : disable(AutoRotationRunner.java:171)
,07-06 08:46:47.382   768   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
07-06 08:46:47.382   768   907 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,07-06 08:46:47.382   333   333 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-06 08:46:47.392   768   907 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-06 08:46:47.392   768   907 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:47.412   768   907 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:47.412   768   907 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-06 08:46:47.412   768   907 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,07-06 08:46:47.422   768   907 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3b3aa08, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-06 08:46:47.422   768   907 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3b3aa08, Service : ACTIVITY_TRACKER(1)
,07-06 08:46:47.422   768   907 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-06 08:46:47.422   768   907 D SContextService: 	.unregisterCallback : 2, client=
,07-06 08:46:47.422   768   907 D SContextService: ===== SContext Service List =====
07-06 08:46:47.422   768   907 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@5def6b2, Service : Activity Tracker
07-06 08:46:47.422   768   907 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@1f8891b, service=Auto Rotation
07-06 08:46:47.422   768   907 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-06 08:46:47.422  1378  1952 D KeyguardViewMediator: notifyScreenTurnedOff
,07-06 08:46:47.422  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() start
,07-06 08:46:47.422  1378  1378 D KeyguardViewMediator: handleNotifyScreenTurnedOff
07-06 08:46:47.422  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() end
,07-06 08:46:47.422   768   907 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
,07-06 08:46:47.422   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:47.422   768  1359 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
,07-06 08:46:47.432   768  1359 E LightSensor: Light old sensor_state 513, new sensor_state : 1 en : 0
,07-06 08:46:47.432   768   907 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
,07-06 08:46:47.432   768   907 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
,07-06 08:46:47.432   768  1359 D SensorManager: unregisterListener ::   
,07-06 08:46:47.432   768  1359 E Sensors : Acc old sensor_state 1, new sensor_state : 0 en : 0
,07-06 08:46:47.442   768   907 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
,07-06 08:46:47.442   768   907 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
,07-06 08:46:47.442   768  1359 D SensorManager: unregisterListener ::   
,07-06 08:46:47.442   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:47.442   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:47.442   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:47.442   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:47.442   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:47.442   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:47.442   768  1359 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::unregisterListener done: 21ms
,07-06 08:46:47.452   768  7731 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 0
07-06 08:46:47.452   768  7732 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
,07-06 08:46:47.452   768  7731 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-06 08:46:47.452   768  7732 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,07-06 08:46:47.452   768   916 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-06 08:46:47.452   768   916 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,07-06 08:46:47.452   768   916 I QCOM PowerHAL: Got set_interactive hint
,07-06 08:46:47.452   768   916 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
,07-06 08:46:47.452   768   903 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-06 08:46:47.462   294   294 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a24000
07-06 08:46:47.462   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-06 08:46:47.462   768   778 I art     : Background partial concurrent mark sweep GC freed 97636(7MB) AllocSpace objects, 169(3MB) LOS objects, 27% free, 43MB/59MB, paused 1.841ms total 206.222ms
,07-06 08:46:47.712   294   565 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-06 08:46:47.712   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-06 08:46:47.712   768   916 D SurfaceControl: Excessive delay in setPowerMode(): 251ms
07-06 08:46:47.712   768   916 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 254ms
07-06 08:46:47.712   768   916 I libsuspend: !@autosuspend_wakeup_count_enable
07-06 08:46:47.712   768   916 I libsuspend: !@autosuspend_wakeup_count_enable done
07-06 08:46:47.712   768   916 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 265ms
07-06 08:46:47.712   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:47.712   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:47.712   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:47.712   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:47.712   768   907 I PowerManagerService: [PWL] Off : 0s ago
07-06 08:46:47.712   768   907 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
07-06 08:46:47.712   768   907 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
07-06 08:46:47.712   768   907 I PowerManagerService: [PWL]     mDisplayReady : false
07-06 08:46:47.712   768   907 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:47.712   768   907 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:47.712   768   907 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:47.712   768   907 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:47.712   768   907 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-06 08:46:47.712   768   907 D PowerManagerService: mDisplayReady: true
07-06 08:46:47.712   768   907 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-06 08:46:47.712   768   907 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
07-06 08:46:47.712   768   907 D PowerManagerService: handleSandman : startDream(true)
07-06 08:46:47.712   768   907 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-06 08:46:47.712   768   907 I PowerManagerService: Sleeping (uid 1000)...
07-06 08:46:47.712   768   907 D PowerManagerService: [s] UserActivityState : 4 -> 0
07-06 08:46:47.712   768   907 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-06 08:46:47.712   768  1357 D PersonaManagerService: onfinishedGoingToSleep why = 3
07-06 08:46:47.712   768   939 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-06 08:46:47.712  1378  3008 D KeyguardViewMediator: onFinishedGoingToSleep(3)
07-06 08:46:47.712  1378  3008 D KeyguardViewMediator: onFinishedGoingToSleep: mPendingLock false
07-06 08:46:47.712  1378  3008 D KeyguardViewMediator: notifyFinishedGoingToSleep
07-06 08:46:47.712  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() start
07-06 08:46:47.712  1378  1378 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
07-06 08:46:47.712  1378  1378 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() end
,07-06 08:46:47.722  1378  1378 D SecKeyguardClockSingleView: onScreenTurnedOff
,07-06 08:46:47.722  1378  1378 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOff() end
,07-06 08:46:47.722   768   768 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 768) 
,07-06 08:46:47.722   768   768 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,07-06 08:46:47.722   768   768 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:46:47.732   768   768 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-06 08:46:47.732   768   768 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-06 08:46:47.732   768   768 D BatteryService: turn on LED for fully charged
,07-06 08:46:47.752   768   768 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-06 08:46:47.752   768   768 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
07-06 08:46:47.752   768   768 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
07-06 08:46:47.752   768   768 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
,07-06 08:46:47.752   333   558 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-06 08:46:47.752   768   768 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 6, 46, 47,
07-06 08:46:47.752   768   768 D SensorHubManager: SendSensorHubData: send data = -63, 14, 6, 46, 47
07-06 08:46:47.752   333   333 D Sensorhubs: sendContextData: -63, 14, 6, 46, 47
,07-06 08:46:47.762   768   768 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-06 08:46:47.762   768  1244 D MotionRecognitionService: Screen off setAccIntStatus 
07-06 08:46:47.762   768  1244 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-06 08:46:47.772   768   856 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab9563c u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{818856c 2875:com.android.settings/1000}
,07-06 08:46:47.782   768   768 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,07-06 08:46:47.792   768   768 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-06 08:46:47.792   768   768 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-06 08:46:47.792   768   768 D UcmService: notifyChangeToPlugin event 16
07-06 08:46:47.792   768   768 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
,07-06 08:46:47.792   768   768 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-06 08:46:47.792   768   768 D UcmService: notifying to unmanaged plugin
,07-06 08:46:47.792  1729  1750 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-06 08:46:47.792   768   768 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-06 08:46:47.792   768   768 D UcmService: agentService status-0
07-06 08:46:47.792   768   768 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
,07-06 08:46:47.792   768   768 D UcmService: notifying to unmanaged plugin
,07-06 08:46:47.792  1745  1758 D BootAgentService: notifyChange eventId-16
07-06 08:46:47.792   768   768 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-06 08:46:47.792   768   768 D UcmService: agentService status--1
,07-06 08:46:47.792   768   768 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-06 08:46:47.802   768  1322 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
07-06 08:46:47.802   768  1322 D WifiNative-wlan0: callSECApiVoid - ID [19]
07-06 08:46:47.802  1540  1540 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,07-06 08:46:47.802   768   768 D NotificationService: ACTION_SCREEN_OFF
,07-06 08:46:47.802   768   768 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 768) 
07-06 08:46:47.802   768   768 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,07-06 08:46:47.802   768   768 D EdgeLight: Turning off
07-06 08:46:47.812   768  1322 E WifiNative-wlan0: do suspend true
,07-06 08:46:47.812   324   966 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-06 08:46:47.812   324   966 V voice   : voice_set_parameters: enter: screen_state=off
07-06 08:46:47.812   324   966 V voice   : voice_set_parameters: exit with code(-2)
07-06 08:46:47.812   324   966 V msm8974_platform: platform_set_parameters: enter: screen_state=off
,07-06 08:46:47.812   324   966 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-06 08:46:47.812   324   966 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-06 08:46:47.812   324   966 V audio_hw_primary: adev_set_parameters: exit
,07-06 08:46:47.832   768   768 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,07-06 08:46:47.832   768   768 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-06 08:46:47.842   768   768 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
07-06 08:46:47.842   768   768 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@5def6b2, Service = Activity Tracker, used = 0
,07-06 08:46:47.842   768   768 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
,07-06 08:46:47.842   768   768 V CAE     : stop(ContextProvider.java:155)
07-06 08:46:47.842   768   768 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-06 08:46:47.842   768   768 V CAE     : disable(ActivityTrackerRunner.java:96)
,07-06 08:46:47.842   768   768 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
07-06 08:46:47.842   768   768 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-06 08:46:47.842   333   558 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-06 08:46:47.852   768   768 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-06 08:46:47.852   768   768 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:47.862   768   768 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:47.862   768   768 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-06 08:46:47.862   768   768 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-06 08:46:47.862   768   768 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3b3aa08, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-06 08:46:47.862   768   768 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-06 08:46:47.862   768   768 D SContextService: 	.unregisterCallback : 1, client=
07-06 08:46:47.862   768   768 D SContextService: ===== SContext Service List =====
07-06 08:46:47.862   768   768 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$12@c8660bd, service=Activity Tracker
,07-06 08:46:47.862   768   903 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-06 08:46:47.862   768   903 D IpRemoteDisplayController: Bridge Server is not available
,07-06 08:46:47.862  1378  1378 D vol.SecVolumeDialog: dismissH : false
,07-06 08:46:47.872   768   768 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,07-06 08:46:47.872   768  1320 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
07-06 08:46:47.872   768  1320 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-06 08:46:48.102   768   914 D LightsService: [SvcLED]  onSensorChanged::light value = 26
07-06 08:46:48.102   768   914 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-06 08:46:48.102   768   914 D SensorManager: unregisterListener ::   
07-06 08:46:48.102   768   914 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
,07-06 08:46:48.112   768   914 D lights  : led_pattern : 5 +
,07-06 08:46:48.112   768   914 D lights  : led_pattern : 5 -
07-06 08:46:48.112   768   914 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-06 08:46:48.112   768   914 V AlarmManager:  remove PendingIntent] PendingIntent{743655a: PendingIntentRecord{e2fc38b android broadcastIntent}}
,07-06 08:46:48.372  1449  1449 D Recents : onTaskStackChanged
,07-06 08:46:48.892   768   848 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-06 08:46:48.912  1651  3396 D NfcService: call the applyRouting
,07-06 08:46:48.922  1378  1378 D StatusBar.NetworkController: onDataActivity: direction=0
,07-06 08:46:48.922  1378  1378 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-06 08:46:48.932  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,07-06 08:46:48.932  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
07-06 08:46:48.932  2302  2302 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,07-06 08:46:48.942  2142  2142 D BtGatt.GattService: LCD turned off
,07-06 08:46:48.942  2142  2390 D BtGatt.ScanManager: handleLcdOffIntent
07-06 08:46:48.942  2142  2390 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,07-06 08:46:48.992  6687  6687 D SystemBroadcastReceiver: [FACE] Received broadcast 
,07-06 08:46:48.992  6687  6687 I SystemBroadcastReceiver: [FACE] onReceive broadcastcompleted  
,07-06 08:46:48.992  6687  7745 I SystemBroadcastReceiver: [FACE] Calling notifyListeners. 
07-06 08:46:48.992  6687  7745 D SystemBroadcastReceiver: [FACE] Event id =  EVENT_SCREEN_OFF
07-06 08:46:48.992  6687  7745 D SystemBroadcastReceiver: [FACE] getRegisteredListnersForIntent completed 
07-06 08:46:48.992  6687  7745 I PolicyManager: [FACE] onReceive action = EVENT_SCREEN_OFF
,07-06 08:46:49.002   768  1357 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-06 08:46:49.002   768  3441 D SSRM:n  : SIOP:: AP = 300, PST = 292, CUR = 450, LCD = 0
,07-06 08:46:49.012   768  3441 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:46:49.022  1378  1378 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:49.022  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:49.022  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:49.022  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:49.022  1378  1378 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:49.072   768  7746 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-06 08:46:49.082   768  7746 D BluetoothAdapter: STATE_ON
,07-06 08:46:49.082  2142  2427 D bt_vendor: op for 7
,07-06 08:46:49.082  2142  2427 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-06 08:46:49.082  2142  2427 D bt_upio : upio_start_stop_timer : timer_settime success
07-06 08:46:49.082  2142  2427 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
07-06 08:46:49.092   768  2251 V AlarmManager:  remove PendingIntent] PendingIntent{1b88d1a: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:46:49.122   768  7746 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:49.222   768  7746 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:49.232   768  7746 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-06 08:46:49.402   768  7746 I BatteryStatsDumper: Writing to database completed
,07-06 08:46:49.892  2142  2700 D bt_upio : ..proc_btwrite_timeout..
,07-06 08:46:49.892  2142  2700 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-06 08:46:50.592  2142  2427 D bt_vendor: op for 7
,07-06 08:46:50.592  2142  2427 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-06 08:46:50.592  2142  2427 D bt_upio : BT_WAKE is de-asserted already
,07-06 08:46:50.592   768  1759 V AlarmManager:  remove PendingIntent] PendingIntent{2ae304b: PendingIntentRecord{d0f7f90 com.android.bluetooth broadcastIntent}}
,07-06 08:46:51.862   768  1238 V AlarmManager: Expired Alarm result :4
,07-06 08:46:51.872  1378  1378 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-06 08:46:51.882  1378  1378 D KeyguardViewMediator: doKeyguardLocked: started
,07-06 08:46:51.912  1378  1378 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-06 08:46:51.912  1378  1378 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,07-06 08:46:52.632   768  1690 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:46:52.632   768  1690 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:46:52.642   768  1690 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:46:52.642   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:46:52.652   768   768 I MotionRecognitionService: Plugged
,07-06 08:46:52.652   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:46:52.662   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:46:52.662   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:46:52.662   768  1690 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-06 08:46:52.672   768  1690 D BatteryService: stay LED for fully charged
,07-06 08:46:52.682  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:46:52.682  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:46:52.682  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:46:52.692  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:46:52.692  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:46:52.702  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:46:52.702  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:46:52.702  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:46:59.062   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0,
,07-06 08:46:59.992   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:47:00.832   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:47:01.932   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:47:01.932   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:47:01.932   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:47:09.132   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-06 08:47:15.312   768  1554 E Watchdog: !@Sync 54 [07-06 08:47:15.319]
,07-06 08:47:18.512  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-06 08:47:18.632  1640  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 105ms lastUpdatedAfter : 180358ms
,07-06 08:47:18.962   768  1238 V AlarmManager: Expired Alarm result :4
,07-06 08:47:19.022  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-06 08:47:19.022  1378  1378 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-06 08:47:19.022  1378  1378 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:47:19.042  1378  1378 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:47:19.042  1378  1378 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:47:19.052  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.052  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:47:19.052  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.062  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.072  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.072  1378  1378 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.082   768  1690 V AlarmManager:  remove PendingIntent] PendingIntent{169927d: PendingIntentRecord{67c8bbd com.google.android.gms broadcastIntent}}
,07-06 08:47:19.082   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:47:19.082   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:47:19.082   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:47:19.092  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.112   768  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-06 08:47:19.112   768  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-06 08:47:19.152   768   768 I BackgroundCompactionService: onStart. jobID=801
,07-06 08:47:19.162   768   768 I BackgroundCompactionService: onStart done. jobID=801
,07-06 08:47:19.162   768  7766 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
07-06 08:47:19.162   768  7766 I BackgroundCompactionService: compact_memory command done
,07-06 08:47:19.172  1378  1378 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:19.202   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-06 08:47:22.692   768  2239 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:47:22.702   768  2239 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:47:22.702   768  2239 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:47:22.712   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:47:22.722   768   768 I MotionRecognitionService: Plugged
,07-06 08:47:22.722   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:47:22.722   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:47:22.732   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:47:22.732   768  2239 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
07-06 08:47:22.732   768  2239 D BatteryService: stay LED for fully charged
,07-06 08:47:22.732  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:47:22.732  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:47:22.732  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:47:22.752  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:47:22.752  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:47:22.762  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:22.762  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:22.762  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:29.132   768  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-06 08:47:29.132   768  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-06 08:47:29.252   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-06 08:47:34.172   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-06 08:47:34.172   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:47:34.172   308  1114 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:47:39.342   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-06 08:47:45.322   768  1554 E Watchdog: !@Sync 55 [07-06 08:47:45.325]
,07-06 08:47:49.402   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-06 08:47:52.762   768  1690 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:47:52.762   768  1690 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-06 08:47:52.772   768  1690 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-06 08:47:52.772   768   768 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:47:52.782   768   768 I MotionRecognitionService: Plugged
,07-06 08:47:52.782   768   768 D MotionRecognitionService:   cableConnection= 1
,07-06 08:47:52.792   768   768 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-06 08:47:52.792   768   768 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:47:52.792   768  1690 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-06 08:47:52.802   768  1690 D BatteryService: stay LED for fully charged
,07-06 08:47:52.812  1378  1378 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:47:52.822  1378  1378 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:47:52.822  1378  1378 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:47:52.842  2142  2142 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:47:52.842  2142  2730 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:47:52.852  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:52.852  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:52.852  1378  1378 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:59.462   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-06 08:47:59.992   768  1238 V AlarmManager: Expired Alarm result :8
,07-06 08:48:09.522   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-06 08:48:15.322   768  1554 E Watchdog: !@Sync 56 [07-06 08:48:15.330]
,07-06 08:48:16.902  2102  3315 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-06 08:48:18.732  1640  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,TIME-OUT KILL (timeout was 1400000ms),07-06 08:48:19.602   768  3441 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
07-06 08:48:20.042  2147  2147 E audit   : type=1400 msg=audit(1467787700.032:294): avc:  denied  { execmod } for  pid=7782 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-06 08:48:20.042  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:48:20.042  2147  2147 E audit   : type=1300 msg=audit(1467787700.032:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4030000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7782 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-06 08:48:20.042  2147  2147 E audit   : type=1327 msg=audit(1467787700.032:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-06 08:48:20.042  2147  2147 E audit   : type=1320 msg=audit(1467787700.032:294): 
07-06 08:48:20.092  2147  2147 E audit   : type=1400 msg=audit(1467787700.092:295): avc:  denied  { execmod } for  pid=7782 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-06 08:48:20.092  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:48:20.092  2147  2147 E audit   : type=1300 msg=audit(1467787700.092:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fef000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7782 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-06 08:48:20.092  2147  2147 E audit   : type=1327 msg=audit(1467787700.092:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-06 08:48:20.092  2147  2147 E audit   : type=1320 msg=audit(1467787700.092:295): 
07-06 08:48:20.132  2147  2147 E audit   : type=1400 msg=audit(1467787700.132:296): avc:  denied  { execmod } for  pid=7782 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-06 08:48:20.132  2147  2147 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:48:20.132  7782  7782 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-06 08:48:20.132  2147  2147 E audit   : type=1300 msg=audit(1467787700.132:296): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff0000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7782 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-06 08:48:20.132  2147  2147 E audit   : type=1327 msg=audit(1467787700.132:296): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-06 08:48:20.132  2147  2147 E audit   : type=1320 msg=audit(1467787700.132:296): 
07-06 08:48:20.142  7782  7782 D AndroidRuntime: CheckJNI is OFF
07-06 08:48:20.142  7782  7782 D AndroidRuntime: readGMSProperty: start
07-06 08:48:20.142  7782  7782 D AndroidRuntime: readGMSProperty: already setted!!
07-06 08:48:20.142  7782  7782 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 08:48:20.142  7782  7782 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 08:48:20.142  7782  7782 D AndroidRuntime: readGMSProperty: end
07-06 08:48:20.142  7782  7782 D AndroidRuntime: addProductProperty: start
07-06 08:48:20.152  7782  7782 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-06 08:48:20.152  7782  7782 W art     : af19f000-b20c5000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-06 08:48:20.152  7782  7782 W art     : b20c5000-b4334000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-06 08:48:20.152  7782  7782 W art     : b4334000-b4335000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-06 08:48:20.152  7782  7782 W art     : b4335000-b435e000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-06 08:48:20.152  7782  7782 W art     : b435e000-b4361000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-06 08:48:20.152  7782  7782 W art     : b4361000-b4362000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-06 08:48:20.152  7782  7782 W art     : b4362000-b4363000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-06 08:48:20.152  7782  7782 W art     : b4363000-b47b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-06 08:48:20.152  7782  7782 W art     : b47b1000-b47b2000 ---p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b47b2000-b47bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-06 08:48:20.152  7782  7782 W art     : b47bc000-b47bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-06 08:48:20.152  7782  7782 W art     : b47bd000-b47bf000 rw-p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b47bf000-b47c0000 r--p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b47c0000-b48c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-06 08:48:20.152  7782  7782 W art     : b48c2000-b48c3000 r--p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b48c3000-b48e3000 r--s 00000000 00:0b 7179       /dev/__properties__
07-06 08:48:20.152  7782  7782 W art     : b48e3000-b52f4000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-06 08:48:20.152  7782  7782 W art     : b52f4000-b52f5000 ---p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b52f5000-b533e000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-06 08:48:20.152  7782  7782 W art     : b533e000-b533f000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-06 08:48:20.152  7782  7782 W art     : b533f000-b5347000 rw-p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b5347000-b5348000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.152  7782  7782 W art     : b5348000-b537d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-06 08:48:20.152  7782  7782 W art     : b537d000-b537e000 ---p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b537e000-b537f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-06 08:48:20.152  7782  7782 W art     : b537f000-b5380000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-06 08:48:20.152  7782  7782 W art     : b5380000-b53d8000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-06 08:48:20.152  7782  7782 W art     : b53d8000-b53d9000 ---p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b53d9000-b53da000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-06 08:48:20.152  7782  7782 W art     : b53da000-b53db000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-06 08:48:20.152  7782  7782 W art     : b53dc000-b53e2000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-06 08:48:20.152  7782  7782 W art     : b53e2000-b53e3000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-06 08:48:20.152  7782  7782 W art     : b53e3000-b53e4000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-06 08:48:20.152  7782  7782 W art     : b53e4000-b53e6000 rw-p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b53e7000-b53f1000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-06 08:48:20.152  7782  7782 W art     : b53f1000-b53f4000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-06 08:48:20.152  7782  7782 W art     : b53f4000-b53f5000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-06 08:48:20.152  7782  7782 W art     : b53f6000-b540d000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-06 08:48:20.152  7782  7782 W art     : b540d000-b540e000 ---p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b540e000-b540f000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-06 08:48:20.152  7782  7782 W art     : b540f000-b5410000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-06 08:48:20.152  7782  7782 W art     : b5411000-b541b000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-06 08:48:20.152  7782  7782 W art     : b541b000-b541c000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-06 08:48:20.152  7782  7782 W art     : b541c000-b541d000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-06 08:48:20.152  7782  7782 W art     : b541d000-b5421000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-06 08:48:20.152  7782  7782 W art     : b5421000-b5422000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-06 08:48:20.152  7782  7782 W art     : b5422000-b5423000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-06 08:48:20.152  7782  7782 W art     : b5423000-b5439000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-06 08:48:20.152  7782  7782 W art     : b5439000-b543a000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-06 08:48:20.152  7782  7782 W art     : b543a000-b543b000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-06 08:48:20.152  7782  7782 W art     : b543b000-b5448000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-06 08:48:20.152  7782  7782 W art     : b5448000-b5449000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-06 08:48:20.152  7782  7782 W art     : b5449000-b544a000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-06 08:48:20.152  7782  7782 W art     : b544a000-b54aa000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-06 08:48:20.152  7782  7782 W art     : b54aa000-b54ad000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-06 08:48:20.152  7782  7782 W art     : b54ad000-b54b1000 rw-p 00000000 00:00 0 
07-06 08:48:20.152  7782  7782 W art     : b54b1000-b5512000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-06 08:48:20.152  7782  7782 W art     : b5512000-b5513000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-06 08:48:20.152  7782  7782 W art     : b5513000-b5562000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-06 08:48:20.152  7782  7782 W art     : b5562000-b5564000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-06 08:48:20.162  7782  7782 W art     : b5564000-b5565000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-06 08:48:20.162  7782  7782 W art     : b5565000-b5566000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5566000-b556d000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-06 08:48:20.162  7782  7782 W art     : b556d000-b556e000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-06 08:48:20.162  7782  7782 W art     : b556e000-b556f000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
07-06 08:48:20.162  7782  7782 W art     : avc_common.so
07-06 08:48:20.162  7782  7782 W art     : b5570000-b5573000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-06 08:48:20.162  7782  7782 W art     : b5573000-b5574000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-06 08:48:20.162  7782  7782 W art     : b5574000-b5575000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
07-06 08:48:20.162  7782  7782 W art     : enc_common.so
07-06 08:48:20.162  7782  7782 W art     : b5576000-b557a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-06 08:48:20.162  7782  7782 W art     : b557a000-b557b000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b557b000-b557c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-06 08:48:20.162  7782  7782 W art     : b557c000-b557d000 rw-p 00005000 b3:17 2510       /syste
07-06 08:48:20.162  7782  7782 W art     : m/lib/libpowermanager.so
07-06 08:48:20.162  7782  7782 W art     : b557e000-b559b000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-06 08:48:20.162  7782  7782 W art     : b559b000-b559c000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-06 08:48:20.162  7782  7782 W art     : b559c000-b559d000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-06 08:48:20.162  7782  7782 W art     : b559e000-b55a3000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-06 08:48:20.162  7782  7782 W art     : b55a3000-b55a4000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-06 08:48:20.162  7782  7782 W art     : b55a4000-b55a5000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-06 08:48:20.162  7782  7782 W art     : b55a6000-b55d7000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-06 08:48:20.162  7782  7782 W art     : b55d7000-b55da000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-06 08:48:20.162  7782  7782 W art     : b55da000-b55db000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-06 08:48:20.162  7782  7782 W art     : b55dc000-b5617000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-06 08:48:20.162  7782  7782 W art     : b5617000-b5618000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-06 08:48:20.162  7782  7782 W art     : b5618000-b5619000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-06 08:48:20.162  7782  7782 W art     : b561a000-b5621000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-06 08:48:20.162  7782  7782 W art     : b5621000-b5622000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5622000-b5623000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-06 08:48:20.162  7782  7782 W art     : b5623000-b5624000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-06 08:48:20.162  7782  7782 W art     : b5624000-b5625000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5625000-b563c000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-06 08:48:20.162  7782  7782 W art     : b563c000-b563d000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b563d000-b5640000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-06 08:48:20.162  7782  7782 W art     : b5640000-b5641000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-06 08:48:20.162  7782  7782 W art     : b5641000-b5660000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-06 08:48:20.162  7782  7782 W art     : b5660000-b5661000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-06 08:48:20.162  7782  7782 W art     : b5661000-b5662000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-06 08:48:20.162  7782  7782 W art     : b5662000-b56a0000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-06 08:48:20.162  7782  7782 W art     : b56a0000-b56a1000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b56a1000-b56a3000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-06 08:48:20.162  7782  7782 W art     : b56a3000-b56a4000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-06 08:48:20.162  7782  7782 W art     : b56a5000-b56ac000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-06 08:48:20.162  7782  7782 W art     : b56ac000-b56ad000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-06 08:48:20.162  7782  7782 W art     : b56ad000-b56ae000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-06 08:48:20.162  7782  7782 W art     : b56af000-b56b2000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-06 08:48:20.162  7782  7782 W art     : b56b2000-b56b3000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-06 08:48:20.162  7782  7782 W art     : b56b3000-b56b4000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-06 08:48:20.162  7782  7782 W art     : b56b4000-b56ba000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-06 08:48:20.162  7782  7782 W art     : b56ba000-b56bb000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b56bb000-b56bc000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-06 08:48:20.162  7782  7782 W art     : b56bc000-b56bd000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-06 08:48:20.162  7782  7782 W art     : b56bd000-b56c6000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-06 08:48:20.162  7782  7782 W art     : b56c6000-b56c7000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-06 08:48:20.162  7782  7782 W art     : b56c7000-b56c8000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-06 08:48:20.162  7782  7782 W art     : b56c8000-b5759000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-06 08:48:20.162  7782  7782 W art     : b5759000-b575a000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b575a000-b5765000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-06 08:48:20.162  7782  7782 W art     : b5765000-b5766000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-06 08:48:20.162  7782  7782 W art     : b5767000-b5779000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-06 08:48:20.162  7782  7782 W art     : b5779000-b577a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-06 08:48:20.162  7782  7782 W art     : b577a000-b577b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-06 08:48:20.162  7782  7782 W art     : b577c000-b5781000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-06 08:48:20.162  7782  7782 W art     : b5781000-b5782000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-06 08:48:20.162  7782  7782 W art     : b5782000-b5783000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-06 08:48:20.162  7782  7782 W art     : b5784000-b57f1000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-06 08:48:20.162  7782  7782 W art     : b57f1000-b57f2000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b57f2000-b57f4000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-06 08:48:20.162  7782  7782 W art     : b57f4000-b57f5000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-06 08:48:20.162  7782  7782 W art     : b57f5000-b57f6000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b57f6000-b57fd000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-06 08:48:20.162  7782  7782 W art     : b57fd000-b57fe000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-06 08:48:20.162  7782  7782 W art     : b57fe000-b57ff000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-06 08:48:20.162  7782  7782 W art     : b5800000-b5880000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-06 08:48:20.162  7782  7782 W art     : b5880000-b5881000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5881000-b5882000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-06 08:48:20.162  7782  7782 W art     : b5882000-b5883000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-06 08:48:20.162  7782  7782 W art     : b5883000-b589a000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b589a000-b58d1000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-06 08:48:20.162  7782  7782 W art     : ib/libqc-opt.so
07-06 08:48:20.162  7782  7782 W art     : b58d1000-b58d2000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-06 08:48:20.162  7782  7782 W art     : b58d2000-b58d3000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-06 08:48:20.162  7782  7782 W art     : b58d3000-b58ef000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-06 08:48:20.162  7782  7782 W art     : b58ef000-b58f0000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-06 08:48:20.162  7782  7782 W art     : b58f0000-b58f1000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-06 08:48:20.162  7782  7782 W art     : b58f2000-b5953000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-06 08:48:20.162  7782  7782 W art     : b5953000-b5955000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-06 08:48:20.162  7782  7782 W art     : b5955000-b5956000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-06 08:48:20.162  7782  7782 W art     : b5957000-b597e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-06 08:48:20.162  7782  7782 W art     : b597e000-b597f000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b597f000-b5980000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-06 08:48:20.162  7782  7782 W art     : b5980000-b5981000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-06 08:48:20.162  7782  7782 W art     : b5982000-b598a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-06 08:48:20.162  7782  7782 W art     : b598a000-b598c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-06 08:48:20.162  7782  7782 W art     : b598c000-b598d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-06 08:48:20.162  7782  7782 W art     : b598e000-b5991000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-06 08:48:20.162  7782  7782 W art     : b5991000-b5992000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-06 08:48:20.162  7782  7782 W art     : b5992000-b5993000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-06 08:48:20.162  7782  7782 W art     : b5993000-b5997000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-06 08:48:20.162  7782  7782 W art     : b5997000-b5998000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5998000-b5999000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-06 08:48:20.162  7782  7782 W art     : b5999000-b599a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-06 08:48:20.162  7782  7782 W art     : b599a000-b59aa000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-06 08:48:20.162  7782  7782 W art     : b59aa000-b59ab000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-06 08:48:20.162  7782  7782 W art     : b59ab000-b59ac000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-06 08:48:20.162  7782  7782 W art     : b59ac000-b59f2000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b59f2000-b59fb000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-06 08:48:20.162  7782  7782 W art     : b59fb000-b59fc000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-06 08:48:20.162  7782  7782 W art     : b59fc000-b59fd000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-06 08:48:20.162  7782  7782 W art     : b59fe000-b5a03000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-06 08:48:20.162  7782  7782 W art     : b5a03000-b5a04000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-06 08:48:20.162  7782  7782 W art     : b5a04000-b5a05000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-06 08:48:20.162  7782  7782 W art     : b5a05000-b5a08000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-06 08:48:20.162  7782  7782 W art     : b5a08000-b5a09000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5a09000-b5a0a000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-06 08:48:20.162  7782  7782 W art     : b5a0a000-b5a0b000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-06 08:48:20.162  7782  7782 W art     : b5a0c000-b5a24000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-06 08:48:20.162  7782  7782 W art     : b5a24000-b5a25000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5a25000-b5a26000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-06 08:48:20.162  7782  7782 W art     : b5a26000-b5a27000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-06 08:48:20.162  7782  7782 W art     : b5a28000-b5bc2000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-06 08:48:20.162  7782  7782 W art     : b5bc2000-b5bc3000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5bc3000-b5bd0000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-06 08:48:20.162  7782  7782 W art     : b5bd0000-b5bd1000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-06 08:48:20.162  7782  7782 W art     : b5bd1000-b5bd5000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-06 08:48:20.162  7782  7782 W art     : b5bd5000-b5bd6000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5bd6000-b5bd7000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-06 08:48:20.162  7782  7782 W art     : b5bd7000-b5bd8000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-06 08:48:20.162  7782  7782 W art     : b5bd8000-b5beb000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-06 08:48:20.162  7782  7782 W art     : b5beb000-b5bec000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-06 08:48:20.162  7782  7782 W art     : b5bec000-b5bed000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-06 08:48:20.162  7782  7782 W art     : b5bed000-b5bee000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:48:20.162  7782  7782 W art     : b5bee000-b5c39000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-06 08:48:20.162  7782  7782 W art     : b5c39000-b5c3a000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-06 08:48:20.162  7782  7782 W art     : b5c3a000-b5c3b000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-06 08:48:20.162  7782  7782 W art     : b5c3b000-b5c3d000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5c3e000-b5c4f000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-06 08:48:20.162  7782  7782 W art     : b5c4f000-b5c50000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5c50000-b5c51000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-06 08:48:20.162  7782  7782 W art     : b5c51000-b5c52000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-06 08:48:20.162  7782  7782 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-06 08:48:20.162  7782  7782 W art     : b5c5d000-b5c5f000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-06 08:48:20.162  7782  7782 W art     : b5c5f000-b5c60000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-06 08:48:20.162  7782  7782 W art     : b5c60000-b5c79000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-06 08:48:20.162  7782  7782 W art     : b5c79000-b5c7a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-06 08:48:20.162  7782  7782 W art     : b5c7a000-b5c7d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-06 08:48:20.162  7782  7782 W art     : b5c7d000-b5c81000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5c81000-b5cf5000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-06 08:48:20.162  7782  7782 W art     : b5cf5000-b5cf6000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5cf6000-b5cf9000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-06 08:48:20.162  7782  7782 W art     : b5cf9000-b5cfa000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-06 08:48:20.162  7782  7782 W art     : b5cfa000-b5cfb000 r--p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5cfb000-b5cfe000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-06 08:48:20.162  7782  7782 W art     : b5cfe000-b5cff000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-06 08:48:20.162  7782  7782 W art     : b5cff000-b5d00000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-06 08:48:20.162  7782  7782 W art     : b5d00000-b5d01000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5d01000-b5d06000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-06 08:48:20.162  7782  7782 W art     : b5d06000-b5d07000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-06 08:48:20.162  7782  7782 W art     : b5d07000-b5d08000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-06 08:48:20.162  7782  7782 W art     : b5d08000-b5d09000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5d09000-b5d0c000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-06 08:48:20.162  7782  7782 W art     : b5d0c000-b5d0d000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-06 08:48:20.162  7782  7782 W art     : b5d0d000-b5d0e000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-06 08:48:20.162  7782  7782 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5d0f000-b5d13000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-06 08:48:20.162  7782  7782 W art     : b5d13000-b5d14000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-06 08:48:20.162  7782  7782 W art     : b5d14000-b5d15000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-06 08:48:20.162  7782  7782 W art     : b5d15000-b5d16000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:48:20.162  7782  7782 W art     : b5d16000-b5d1a000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-06 08:48:20.162  7782  7782 W art     : b5d1a000-b5d1b000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-06 08:48:20.162  7782  7782 W art     : b5d1b000-b5d1c000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-06 08:48:20.162  7782  7782 W art     : b5d1c000-b5d1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5d1d000-b5d2b000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-06 08:48:20.162  7782  7782 W art     : b5d2b000-b5d2c000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b5d2c000-b5d2d000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-06 08:48:20.162  7782  7782 W art     : b5d2d000-b5d2e000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-06 08:48:20.162  7782  7782 W art     : b5d2e000-b5d38000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-06 08:48:20.162  7782  7782 W art     : b5d38000-b5d3b000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-06 08:48:20.162  7782  7782 W art     : b5d3b000-b5d3c000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-06 08:48:20.162  7782  7782 W art     : b5d3c000-b5d3d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5d3d000-b5d47000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-06 08:48:20.162  7782  7782 W art     : b5d47000-b5d4a000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-06 08:48:20.162  7782  7782 W art     : b5d4a000-b5d4b000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-06 08:48:20.162  7782  7782 W art     : b5d4b000-b5d4f000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-06 08:48:20.162  7782  7782 W art     : b5d4f000-b5d50000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-06 08:48:20.162  7782  7782 W art     : b5d50000-b5d51000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-06 08:48:20.162  7782  7782 W art     : b5d51000-b5d52000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b5d52000-b5d5f000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-06 08:48:20.162  7782  7782 W art     : b5d5f000-b5d61000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-06 08:48:20.162  7782  7782 W art     : b5d61000-b5d62000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-06 08:48:20.162  7782  7782 W art     : b5d62000-b6174000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-06 08:48:20.162  7782  7782 W art     : b6174000-b6175000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6175000-b617e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-06 08:48:20.162  7782  7782 W art     : b617e000-b6182000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-06 08:48:20.162  7782  7782 W art     : b6182000-b6183000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6183000-b618a000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-06 08:48:20.162  7782  7782 W art     : b618a000-b618b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-06 08:48:20.162  7782  7782 W art     : b618b000-b618c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-06 08:48:20.162  7782  7782 W art     : b618c000-b618d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b618d000-b61a8000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-06 08:48:20.162  7782  7782 W art     : b61a8000-b61a9000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-06 08:48:20.162  7782  7782 W art     : b61a9000-b61aa000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-06 08:48:20.162  7782  7782 W art     : b61aa000-b61ab000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b61ab000-b61f7000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-06 08:48:20.162  7782  7782 W art     : b61f7000-b61f8000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b61f8000-b61f9000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-06 08:48:20.162  7782  7782 W art     : b61f9000-b61fa000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-06 08:48:20.162  7782  7782 W art     : b61fa000-b61fb000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b61fb000-b61ff000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-06 08:48:20.162  7782  7782 W art     : b61ff000-b6200000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6200000-b6201000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-06 08:48:20.162  7782  7782 W art     : b6201000-b6202000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-06 08:48:20.162  7782  7782 W art     : b6202000-b623a000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-06 08:48:20.162  7782  7782 W art     : b623a000-b623b000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-06 08:48:20.162  7782  7782 W art     : b623b000-b623c000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-06 08:48:20.162  7782  7782 W art     : b623c000-b623d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b623d000-b62db000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-06 08:48:20.162  7782  7782 W art     : b62db000-b62dc000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b62dc000-b62fa000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-06 08:48:20.162  7782  7782 W art     : b62fa000-b62fb000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-06 08:48:20.162  7782  7782 W art     : b62fb000-b646e000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-06 08:48:20.162  7782  7782 W art     : b646e000-b6479000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-06 08:48:20.162  7782  7782 W art     : b6479000-b647a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-06 08:48:20.162  7782  7782 W art     : b647a000-b6591000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-06 08:48:20.162  7782  7782 W art     : b6591000-b659c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-06 08:48:20.162  7782  7782 W art     : b659c000-b659d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-06 08:48:20.162  7782  7782 W art     : b659d000-b65a1000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b65a1000-b65c5000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-06 08:48:20.162  7782  7782 W art     : b65c5000-b65c7000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-06 08:48:20.162  7782  7782 W art     : b65c7000-b65c8000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-06 08:48:20.162  7782  7782 W art     : b65c8000-b666e000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-06 08:48:20.162  7782  7782 W art     : b666e000-b667b000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-06 08:48:20.162  7782  7782 W art     : b667b000-b667c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-06 08:48:20.162  7782  7782 W art     : b667c000-b667d000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b667d000-b66d0000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-06 08:48:20.162  7782  7782 W art     : b66d0000-b66d1000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b66d1000-b66d2000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-06 08:48:20.162  7782  7782 W art     : b66d2000-b66d3000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-06 08:48:20.162  7782  7782 W art     : b66d3000-b66d8000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b66d8000-b66ea000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-06 08:48:20.162  7782  7782 W art     : b66ea000-b66eb000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b66eb000-b66ec000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-06 08:48:20.162  7782  7782 W art     : b66ec000-b66ed000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-06 08:48:20.162  7782  7782 W art     : b66ed000-b66f4000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-06 08:48:20.162  7782  7782 W art     : b66f4000-b66f5000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-06 08:48:20.162  7782  7782 W art     : b66f5000-b66f6000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-06 08:48:20.162  7782  7782 W art     : b66f6000-b66f7000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b66f7000-b66fa000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-06 08:48:20.162  7782  7782 W art     : b66fa000-b66fb000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-06 08:48:20.162  7782  7782 W art     : b66fb000-b66fc000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-06 08:48:20.162  7782  7782 W art     : b66fc000-b6700000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-06 08:48:20.162  7782  7782 W art     : b6700000-b6701000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-06 08:48:20.162  7782  7782 W art     : b6701000-b6702000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-06 08:48:20.162  7782  7782 W art     : b6702000-b6710000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-06 08:48:20.162  7782  7782 W art     : b6710000-b6711000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6711000-b6712000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-06 08:48:20.162  7782  7782 W art     : b6712000-b6713000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-06 08:48:20.162  7782  7782 W art     : b6713000-b671c000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-06 08:48:20.162  7782  7782 W art     : b671c000-b671d000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-06 08:48:20.162  7782  7782 W art     : b671d000-b671e000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-06 08:48:20.162  7782  7782 W art     : b671e000-b6784000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-06 08:48:20.162  7782  7782 W art     : b6784000-b6785000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6785000-b6787000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-06 08:48:20.162  7782  7782 W art     : b6787000-b6790000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-06 08:48:20.162  7782  7782 W art     : b6790000-b6793000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6793000-b682a000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-06 08:48:20.162  7782  7782 W art     : b682a000-b682c000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-06 08:48:20.162  7782  7782 W art     : b682c000-b682d000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-06 08:48:20.162  7782  7782 W art     : b682d000-b682e000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b682e000-b6b4f000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-06 08:48:20.162  7782  7782 W art     : b6b4f000-b6b50000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6b50000-b6b6b000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-06 08:48:20.162  7782  7782 W art     : b6b6b000-b6b6f000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-06 08:48:20.162  7782  7782 W art     : b6b6f000-b6b74000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6b74000-b6b7c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-06 08:48:20.162  7782  7782 W art     : b6b7c000-b6b7d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-06 08:48:20.162  7782  7782 W art     : b6b7d000-b6b7e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-06 08:48:20.162  7782  7782 W art     : b6b7e000-b6bac000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-06 08:48:20.162  7782  7782 W art     : b6bac000-b6bad000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6bad000-b6bb4000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-06 08:48:20.162  7782  7782 W art     : b6bb4000-b6bb5000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-06 08:48:20.162  7782  7782 W art     : b6bb5000-b6bfb000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-06 08:48:20.162  7782  7782 W art     : b6bfb000-b6bfc000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6bfc000-b6bff000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-06 08:48:20.162  7782  7782 W art     : b6bff000-b6c00000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-06 08:48:20.162  7782  7782 W art     : b6c00000-b6c1b000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-06 08:48:20.162  7782  7782 W art     : b6c1b000-b6c1f000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-06 08:48:20.162  7782  7782 W art     : b6c1f000-b6c20000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-06 08:48:20.162  7782  7782 W art     : b6c20000-b6c6d000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-06 08:48:20.162  7782  7782 W art     : b6c6d000-b6c6e000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6c6e000-b6c7a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-06 08:48:20.162  7782  7782 W art     : b6c7a000-b6c7b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-06 08:48:20.162  7782  7782 W art     : b6c7b000-b6c88000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-06 08:48:20.162  7782  7782 W art     : b6c88000-b6c89000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6c89000-b6c8a000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-06 08:48:20.162  7782  7782 W art     : b6c8a000-b6c8b000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-06 08:48:20.162  7782  7782 W art     : b6c8b000-b6c93000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-06 08:48:20.162  7782  7782 W art     : b6c93000-b6c94000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6c94000-b6c95000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-06 08:48:20.162  7782  7782 W art     : b6c95000-b6c96000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-06 08:48:20.162  7782  7782 W art     : b6c96000-b6c9d000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-06 08:48:20.162  7782  7782 W art     : b6c9d000-b6c9e000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-06 08:48:20.162  7782  7782 W art     : b6c9e000-b6c9f000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-06 08:48:20.162  7782  7782 W art     : b6c9f000-b6cb3000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-06 08:48:20.162  7782  7782 W art     : b6cb3000-b6cb5000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-06 08:48:20.162  7782  7782 W art     : b6cb5000-b6cb6000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-06 08:48:20.162  7782  7782 W art     : b6cb6000-b6cde000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-06 08:48:20.162  7782  7782 W art     : b6cde000-b6ce0000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-06 08:48:20.162  7782  7782 W art     : b6ce0000-b6ce1000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-06 08:48:20.162  7782  7782 W art     : b6ce1000-b6ce4000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-06 08:48:20.162  7782  7782 W art     : b6ce4000-b6ce5000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-06 08:48:20.162  7782  7782 W art     : b6ce5000-b6ce6000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-06 08:48:20.162  7782  7782 W art     : b6ce6000-b6cef000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-06 08:48:20.162  7782  7782 W art     : b6cef000-b6cf0000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-06 08:48:20.162  7782  7782 W art     : b6cf0000-b6cf1000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-06 08:48:20.162  7782  7782 W art     : b6cf1000-b6d11000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-06 08:48:20.162  7782  7782 W art     : b6d11000-b6d12000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-06 08:48:20.162  7782  7782 W art     : b6d12000-b6d13000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-06 08:48:20.162  7782  7782 W art     : b6d13000-b6d86000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-06 08:48:20.162  7782  7782 W art     : b6d86000-b6d8a000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-06 08:48:20.162  7782  7782 W art     : b6d8a000-b6d8d000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-06 08:48:20.162  7782  7782 W art     : b6d8d000-b6d97000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6d97000-b6e1f000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-06 08:48:20.162  7782  7782 W art     : b6e1f000-b6e20000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6e20000-b6e24000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-06 08:48:20.162  7782  7782 W art     : b6e24000-b6e25000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-06 08:48:20.162  7782  7782 W art     : b6e25000-b6e26000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6e26000-b6e4f000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-06 08:48:20.162  7782  7782 W art     : b6e4f000-b6e50000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6e50000-b6e53000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-06 08:48:20.162  7782  7782 W art     : b6e53000-b6e54000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-06 08:48:20.162  7782  7782 W art     : b6e54000-b6f2e000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-06 08:48:20.162  7782  7782 W art     : b6f2e000-b6f35000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-06 08:48:20.162  7782  7782 W art     : b6f35000-b6f3d000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-06 08:48:20.162  7782  7782 W art     : b6f3d000-b6f3e000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6f3e000-b6f3f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:48:20.162  7782  7782 W art     : b6f3f000-b6f40000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-06 08:48:20.162  7782  7782 W art     : b6f40000-b6f41000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b6f41000-b6f44000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b6f44000-b6f69000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-06 08:48:20.162  7782  7782 W art     : b6f69000-b6f6a000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6f6a000-b6f71000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-06 08:48:20.162  7782  7782 W art     : b6f71000-b6f72000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-06 08:48:20.162  7782  7782 W art     : b6f72000-b6f79000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-06 08:48:20.162  7782  7782 W art     : b6f79000-b6f7a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-06 08:48:20.162  7782  7782 W art     : b6f7a000-b6f7b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-06 08:48:20.162  7782  7782 W art     : b6f7b000-b6f7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b6f7c000-b6f94000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-06 08:48:20.162  7782  7782 W art     : b6f94000-b6f95000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6f95000-b6f96000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-06 08:48:20.162  7782  7782 W art     : b6f96000-b6f97000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-06 08:48:20.162  7782  7782 W art     : b6f97000-b6fa5000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-06 08:48:20.162  7782  7782 W art     : b6fa5000-b6fa6000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6fa6000-b6fa7000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-06 08:48:20.162  7782  7782 W art     : b6fa7000-b6fa8000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-06 08:48:20.162  7782  7782 W art     : b6fa8000-b6fa9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:48:20.162  7782  7782 W art     : b6fa9000-b6fab000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b6fab000-b6fac000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b6fac000-b6fad000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-06 08:48:20.162  7782  7782 W art     : b6fad000-b6fae000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-06 08:48:20.162  7782  7782 W art     : b6fae000-b6faf000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-06 08:48:20.162  7782  7782 W art     : b6faf000-b6fcf000 r--s 00000000 00:0b 7179       /dev/__properties__
07-06 08:48:20.162  7782  7782 W art     : b6fcf000-b6fd0000 r--p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6fd0000-b6fd1000 ---p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6fd1000-b6fd3000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-06 08:48:20.162  7782  7782 W art     : b6fd3000-b6fd4000 r-xp 00000000 00:00 0          [sigpage]
07-06 08:48:20.162  7782  7782 W art     : b6fd4000-b6fef000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-06 08:48:20.162  7782  7782 W art     : b6fef000-b6ff0000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-06 08:48:20.162  7782  7782 W art     : b6ff0000-b6ff2000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-06 08:48:20.162  7782  7782 W art     : b6ff2000-b6ff4000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : b6ff4000-b6ff9000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-06 08:48:20.162  7782  7782 W art     : b6ff9000-b6ffa000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-06 08:48:20.162  7782  7782 W art     : b6ffa000-b6ffb000 rw-p 00000000 00:00 0 
07-06 08:48:20.162  7782  7782 W art     : be97a000-be99b000 rw-p 00000000 00:00 0          [stack]
07-06 08:48:20.162  7782  7782 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-06 08:48:20.252  7782  7782 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-06 08:48:20.302  7782  7782 I Radio-JNI: register_android_hardware_Radio DONE
07-06 08:48:20.312  7782  7782 E AffinityControl: AffinityControl: registerfunction enter
07-06 08:48:20.322  7782  7782 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-06 08:48:20.332   768  2223 D PackageManager: START PACKAGE DELETE: observer{77768382}
07-06 08:48:20.332   768  2223 D PackageManager: pkg{<packageName>}
07-06 08:48:20.332   768  2223 D PackageManager: user{0}
07-06 08:48:20.332   768  2223 D PackageManager: caller{2000}
07-06 08:48:20.332   768  2223 D PackageManager: flags{2}
07-06 08:48:20.332   768  2223 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-06 08:48:20.332   768  2223 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-06 08:48:20.332   768  2223 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-06 08:48:20.332   768  2223 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 08:48:20.332   768  2223 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 08:48:20.332   768   931 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-06 08:48:20.332   768   931 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-06 08:48:20.332   768   931 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-06 08:48:20.332   768   931 D ApplicationPolicy: getApplicationUninstallationEnabled
07-06 08:48:20.332   768   931 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-06 08:48:20.342   768   931 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-06 08:48:20.342   768   931 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-06 08:48:20.342   768   931 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-06 08:48:20.342   768   856 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-06 08:48:20.342   768   856 I ActivityManager: Killing 7178:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-06 08:48:20.342   768   856 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-06 08:48:20.342   768   856 D ActivityManager: mDVFSHelper.acquire()
07-06 08:48:20.352   768   903 D SecWifiDisplayUtil: Metadata value : none
07-06 08:48:20.352   768   903 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{95acf96 V.E...... R.....ID 0,0-0,0}
07-06 08:48:20.352   768   931 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-06 08:48:20.352   768   931 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-06 08:48:20.352   768   903 W WindowManager: view not successfully added to wm, removing view
07-06 08:48:20.352   768   903 D ViewRootImpl: #3 mView = null
07-06 08:48:20.372  7797  7797 E Zygote  : v2
07-06 08:48:20.372  7797  7797 I libpersona: KNOX_SDCARD checking this for 10004
07-06 08:48:20.372  7797  7797 I libpersona: KNOX_SDCARD not a persona
07-06 08:48:20.372   768   856 I ActivityManager: Start proc 7797:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-06 08:48:20.372  7797  7797 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-06 08:48:20.372  7797  7797 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-06 08:48:20.372  7797  7797 E Zygote  : accessInfo : 0
07-06 08:48:20.372  7797  7797 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-06 08:48:20.372   768   856 I ActivityManager:   Force finishing activity ActivityRecord{a147237 u0 com.test.thalitest/.MainActivity t64}
07-06 08:48:20.402   768   931 D AASAinstall: there is not AASApackages.xml file
07-06 08:48:20.412   768   856 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
07-06 08:48:20.422   294   294 I SurfaceFlinger: id=19 createSurf (1146x1876),1 flag=4, VSBConnecti
07-06 08:48:20.422  7797  7797 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:48:20.422  7797  7797 D ActivityThread: Added TimaKeyStore provider
07-06 08:48:20.422   768   856 D InputDispatcher: Focus left window: 7178
07-06 08:48:20.422   294  1362 I SurfaceFlinger: id=17 Removed NainActivit (7/9)
07-06 08:48:20.432   294   344 I SurfaceFlinger: id=17 Removed NainActivit (-2/9)
07-06 08:48:20.432   768   856 D InputDispatcher: Focus entered window: 3699
07-06 08:48:20.432   768   856 D InputDispatcher: Focused application released
07-06 08:48:20.432   768   903 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:768 uid:1000
07-06 08:48:20.432   768   903 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 08:48:20.432   768   903 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:768 uid:1000
07-06 08:48:20.432   768   903 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-06 08:48:20.442   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f938c
07-06 08:48:20.442   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f938c
07-06 08:48:20.442   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8f938c
07-06 08:48:20.452   768  1759 D GraphicsStats: Buffer count: 4
07-06 08:48:20.452   768  1684 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3e77704)
07-06 08:48:20.452   768  1329 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:48:20.452   768  1329 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:48:20.452   768  1329 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:48:20.732   768   931 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-06 08:48:20.752   768   931 W PackageSettings: Skipping PackageSetting{114ce9c com.example.hello/10192} due to missing metadata
07-06 08:48:20.812   768   931 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-06 08:48:20.822   768  2251 V WindowOrientationListener: setCurrentAppOrientation :1
07-06 08:48:20.822   768  2251 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-06 08:48:20.822  1679  1679 D Launcher: onRestart, Launcher: 61968902
07-06 08:48:20.822   768   781 I ActivityManager: Killing 6326:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
07-06 08:48:20.822   332   332 W keystore: ENTER clear_uid from uid 1000 for 10004
07-06 08:48:20.832   768   931 I art     : Starting a blocking GC Explicit
07-06 08:48:20.832   768  1421 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-06 08:48:20.832   768  1421 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:20.832   768   768 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:20.842  1679  1679 D Launcher: onStart, Launcher: 61968902
07-06 08:48:20.842   768   768 I KnoxTimeoutHandler: Shared devices show user statefalse
07-06 08:48:20.842   768   768 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
07-06 08:48:20.842  1679  1679 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
07-06 08:48:20.852   768   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1cf2827 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
07-06 08:48:20.852  1378  1378 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
07-06 08:48:20.852  1679  1679 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-06 08:48:20.852  1679  1679 D Launcher.HomeView: onStart
07-06 08:48:20.852   768  1759 V WindowStateAnimator: Finishing drawing window Window{1cf2827 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-06 08:48:20.862   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8f9364
07-06 08:48:20.862   768   903 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:20.862   294   294 I SurfaceFlinger: id=20 createSurf (1194x288),1 flag=4, VSBConnecti
07-06 08:48:20.862   768   768 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:20.862   768   768 I KnoxTimeoutHandler: SD activityfalse
07-06 08:48:20.872   768   903 D ActivityManager: mDVFSHelper.release()
07-06 08:48:20.872   768   903 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c02ee09 u0 com.samsung.android.MtpApplication/.USBConnection t63} time:1716861
07-06 08:48:20.872  3699  3699 V ActivityThread: updateVisibility : ActivityRecord{67720ae token=android.os.BinderProxy@53e4898 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
07-06 08:48:20.872  1679  1679 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
07-06 08:48:20.872  1679  1679 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
07-06 08:48:20.882  1679  1679 V ActivityThread: updateVisibility : ActivityRecord{ddca95b token=android.os.BinderProxy@40a9991 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-06 08:48:20.882  2302  2316 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1

```
