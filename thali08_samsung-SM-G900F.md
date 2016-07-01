#### Test 757892686fd65a6_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
07-01 08:58:47.439   770  3348 D SSRM:n  : SIOP:: AP = 320, PST = 377, CUR = 450, LCD = 0
,--------- beginning of main
07-01 08:58:49.369  2238  2238 E audit   : type=1400 msg=audit(1467356329.359:275): avc:  denied  { execmod } for  pid=6280 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-01 08:58:49.369  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 08:58:49.369  2238  2238 E audit   : type=1300 msg=audit(1467356329.359:275): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4005000 a1=51000 a2=5 a3=4 items=0 ppid=3489 ppcomm=adbd pid=6280 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-01 08:58:49.369  2238  2238 E audit   : type=1327 msg=audit(1467356329.359:275): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-01 08:58:49.369  2238  2238 E audit   : type=1320 msg=audit(1467356329.359:275): 
07-01 08:58:49.419  2238  2238 E audit   : type=1400 msg=audit(1467356329.419:276): avc:  denied  { execmod } for  pid=6280 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-01 08:58:49.419  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 08:58:49.429  2238  2238 E audit   : type=1300 msg=audit(1467356329.419:276): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc8000 a1=51000 a2=5 a3=4 items=0 ppid=3489 ppcomm=adbd pid=6280 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-01 08:58:49.429  2238  2238 E audit   : type=1327 msg=audit(1467356329.419:276): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-01 08:58:49.429  2238  2238 E audit   : type=1320 msg=audit(1467356329.419:276): 
07-01 08:58:49.469  6280  6280 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-01 08:58:49.469  2238  2238 E audit   : type=1400 msg=audit(1467356329.469:277): avc:  denied  { execmod } for  pid=6280 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-01 08:58:49.469  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 08:58:49.469  2238  2238 E audit   : type=1300 msg=audit(1467356329.469:277): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc8000 a1=51000 a2=5 a3=4 items=0 ppid=3489 ppcomm=adbd pid=6280 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-01 08:58:49.479  2238  2238 E audit   : type=1327 msg=audit(1467356329.469:277): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-01 08:58:49.479  6280  6280 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:49.479  2238  2238 E audit   : type=1320 msg=audit(1467356329.469:277): 
07-01 08:58:49.479  6280  6280 D AndroidRuntime: readGMSProperty: start
07-01 08:58:49.479  6280  6280 D AndroidRuntime: readGMSProperty: already setted!!
07-01 08:58:49.479  6280  6280 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 08:58:49.479  6280  6280 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 08:58:49.479  6280  6280 D AndroidRuntime: readGMSProperty: end
07-01 08:58:49.479  6280  6280 D AndroidRuntime: addProductProperty: start
07-01 08:58:49.489  6280  6280 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-01 08:58:49.489  6280  6280 W art     : aee2c000-b1d52000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-01 08:58:49.489  6280  6280 W art     : b1d52000-b3fc1000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-01 08:58:49.489  6280  6280 W art     : b3fc1000-b3fc2000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-01 08:58:49.489  6280  6280 W art     : b3fc2000-b3fc3000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.489  6280  6280 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-01 08:58:49.489  6280  6280 W art     : b4323000-b4771000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-01 08:58:49.489  6280  6280 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b4772000-b477c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-01 08:58:49.489  6280  6280 W art     : b477c000-b477d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-01 08:58:49.489  6280  6280 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-01 08:58:49.489  6280  6280 W art     : b4896000-b4899000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-01 08:58:49.489  6280  6280 W art     : b4899000-b489a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-01 08:58:49.489  6280  6280 W art     : b489a000-b489b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-01 08:58:49.489  6280  6280 W art     : b489b000-b489c000 r--p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b489c000-b48bc000 r--s 00000000 00:0b 8200       /dev/__properties__
07-01 08:58:49.489  6280  6280 W art     : b48bc000-b52cd000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-01 08:58:49.489  6280  6280 W art     : b52cd000-b52ce000 ---p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b52ce000-b5317000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-01 08:58:49.489  6280  6280 W art     : b5317000-b5318000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-01 08:58:49.489  6280  6280 W art     : b5318000-b5320000 rw-p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b5320000-b5321000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.489  6280  6280 W art     : b5321000-b5356000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-01 08:58:49.489  6280  6280 W art     : b5356000-b5357000 ---p 00000000 00:00 0 
07-01 08:58:49.489  6280  6280 W art     : b5357000-b5358000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-01 08:58:49.499  6280  6280 W art     : b5358000-b5359000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-01 08:58:49.499  6280  6280 W art     : b5359000-b53b1000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-01 08:58:49.499  6280  6280 W art     : b53b1000-b53b2000 ---p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b53b2000-b53b3000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-01 08:58:49.499  6280  6280 W art     : b53b3000-b53b4000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-01 08:58:49.499  6280  6280 W art     : b53b5000-b53bb000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-01 08:58:49.499  6280  6280 W art     : b53bb000-b53bc000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-01 08:58:49.499  6280  6280 W art     : b53bc000-b53bd000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-01 08:58:49.499  6280  6280 W art     : b53bd000-b53bf000 rw-p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b53c0000-b53ca000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-01 08:58:49.499  6280  6280 W art     : b53ca000-b53cd000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-01 08:58:49.499  6280  6280 W art     : b53cd000-b53ce000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-01 08:58:49.499  6280  6280 W art     : b53cf000-b53e6000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-01 08:58:49.499  6280  6280 W art     : b53e6000-b53e7000 ---p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b53e7000-b53e8000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-01 08:58:49.499  6280  6280 W art     : b53e8000-b53e9000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-01 08:58:49.499  6280  6280 W art     : b53ea000-b53f4000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-01 08:58:49.499  6280  6280 W art     : b53f4000-b53f5000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-01 08:58:49.499  6280  6280 W art     : b53f5000-b53f6000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-01 08:58:49.499  6280  6280 W art     : b53f6000-b53fa000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-01 08:58:49.499  6280  6280 W art     : b53fa000-b53fb000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-01 08:58:49.499  6280  6280 W art     : b53fb000-b53fc000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-01 08:58:49.499  6280  6280 W art     : b53fc000-b5412000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-01 08:58:49.499  6280  6280 W art     : b5412000-b5413000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-01 08:58:49.499  6280  6280 W art     : b5413000-b5414000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-01 08:58:49.499  6280  6280 W art     : b5414000-b5421000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-01 08:58:49.499  6280  6280 W art     : b5421000-b5422000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-01 08:58:49.499  6280  6280 W art     : b5422000-b5423000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-01 08:58:49.499  6280  6280 W art     : b5423000-b5483000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-01 08:58:49.499  6280  6280 W art     : b5483000-b5486000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-01 08:58:49.499  6280  6280 W art     : b5486000-b548a000 rw-p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b548a000-b54eb000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-01 08:58:49.499  6280  6280 W art     : b54eb000-b54ec000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-01 08:58:49.499  6280  6280 W art     : b54ec000-b553b000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-01 08:58:49.499  6280  6280 W art     : b553b000-b553d000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-01 08:58:49.499  6280  6280 W art     : b553d000-b553e000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-01 08:58:49.499  6280  6280 W art     : b553e000-b553f000 rw-p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b553f000-b5546000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-01 08:58:49.499  6280  6280 W art     : b5546000-b5547000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-01 08:58:49.499  6280  6280 W art     : b5547000-b5548000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-01 08:58:49.499  6280  6280 W art     : b5549000-b554c000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-01 08:58:49.499  6280  6280 W art     : b554c000-b554d000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-01 08:58:49.499  6280  6280 W art     : b554d000-b554e000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-01 08:58:49.499  6280  6280 W art     : b554f000-b5553000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-01 08:58:49.499  6280  6280 W art     : b5553000-b5554000 ---p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b5554000-b5555000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-01 08:58:49.499  6280  6280 W art     : b5555000-b5556000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-01 08:58:49.499  6280  6280 W art     : b5557000-b5574000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-01 08:58:49.499  6280  6280 W art     : b5574000-b5575000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-01 08:58:49.499  6280  6280 W art     : b5575000-b5576000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-01 08:58:49.499  6280  6280 W art     : b5577000-b557c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-01 08:58:49.499  6280  6280 W art     : b557c000-b557d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-01 08:58:49.499  6280  6280 W art     : b557d000-b557e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-01 08:58:49.499  6280  6280 W art     : b557f000-b55b0000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-01 08:58:49.499  6280  6280 W art     : b55b0000-b55b3000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-01 08:58:49.499  6280  6280 W art     : b55b3000-b55b4000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-01 08:58:49.499  6280  6280 W art     : b55b5000-b55f0000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-01 08:58:49.499  6280  6280 W art     : b55f0000-b55f1000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-01 08:58:49.499  6280  6280 W art     : b55f1000-b55f2000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-01 08:58:49.499  6280  6280 W art     : b55f3000-b55fa000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-01 08:58:49.499  6280  6280 W art     : b55fa000-b55fb000 ---p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b55fb000-b55fc000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-01 08:58:49.499  6280  6280 W art     : b55fc000-b55fd000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-01 08:58:49.499  6280  6280 W art     : b55fd000-b55fe000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.499  6280  6280 W art     : b55fe000-b5615000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-01 08:58:49.499  6280  6280 W art     : b5615000-b5616000 ---p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b5616000-b5619000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-01 08:58:49.499  6280  6280 W art     : b5619000-b561a000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-01 08:58:49.499  6280  6280 W art     : b561a000-b5639000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-01 08:58:49.499  6280  6280 W art     : b5639000-b563a000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-01 08:58:49.499  6280  6280 W art     : b563a000-b563b000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-01 08:58:49.499  6280  6280 W art     : b563b000-b5679000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-01 08:58:49.499  6280  6280 W art     : b5679000-b567a000 ---p 00000000 00:00 0 
07-01 08:58:49.499  6280  6280 W art     : b567a000-b567c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-01 08:58:49.499  6280  6280 W art     : b567c000-b567d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-01 08:58:49.499  6280  6280 W art     : b567e000-b5685000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-01 08:58:49.499  6280  6280 W art     : b5685000-b5686000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-01 08:58:49.499  6280  6280 W art     : b5686000-b5687000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-01 08:58:49.499  6280  6280 W art     : b5688000-b568b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-01 08:58:49.499  6280  6280 W art     : b568b000-b568c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-01 08:58:49.509  6280  6280 W art     : b568c000-b568d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-01 08:58:49.509  6280  6280 W art     : b568d000-b5693000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-01 08:58:49.509  6280  6280 W art     : b5693000-b5694000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b5694000-b5695000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-01 08:58:49.509  6280  6280 W art     : b5695000-b5696000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-01 08:58:49.509  6280  6280 W art     : b5696000-b569f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-01 08:58:49.509  6280  6280 W art     : b569f000-b56a0000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-01 08:58:49.509  6280  6280 W art     : b56a0000-b56a1000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-01 08:58:49.509  6280  6280 W art     : b56a1000-b5732000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-01 08:58:49.509  6280  6280 W art     : b5732000-b5733000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b5733000-b573e000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-01 08:58:49.509  6280  6280 W art     : b573e000-b573f000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-01 08:58:49.509  6280  6280 W art     : b5740000-b5752000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-01 08:58:49.509  6280  6280 W art     : b5752000-b5753000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-01 08:58:49.509  6280  6280 W art     : b5753000-b5754000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-01 08:58:49.509  6280  6280 W art     : b5755000-b575a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-01 08:58:49.509  6280  6280 W art     : b575a000-b575b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-01 08:58:49.509  6280  6280 W art     : b575b000-b575c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-01 08:58:49.509  6280  6280 W art     : b575d000-b57ca000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-01 08:58:49.509  6280  6280 W art     : b57ca000-b57cb000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b57cb000-b57cd000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-01 08:58:49.509  6280  6280 W art     : b57cd000-b57ce000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-01 08:58:49.509  6280  6280 W art     : b57ce000-b57cf000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.509  6280  6280 W art     : b57cf000-b57d6000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-01 08:58:49.509  6280  6280 W art     : b57d6000-b57d7000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-01 08:58:49.509  6280  6280 W art     : b57d7000-b57d8000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-01 08:58:49.509  6280  6280 W art     : b57d9000-b5859000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-01 08:58:49.509  6280  6280 W art     : b5859000-b585a000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b585a000-b585b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-01 08:58:49.509  6280  6280 W art     : b585b000-b585c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-01 08:58:49.509  6280  6280 W art     : b585c000-b5873000 rw-p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b5873000-b58aa000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-01 08:58:49.509  6280  6280 W art     : ib/libqc-opt.so
07-01 08:58:49.509  6280  6280 W art     : b58aa000-b58ab000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-01 08:58:49.509  6280  6280 W art     : b58ab000-b58ac000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-01 08:58:49.509  6280  6280 W art     : b58ac000-b58c8000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-01 08:58:49.509  6280  6280 W art     : b58c8000-b58c9000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-01 08:58:49.509  6280  6280 W art     : b58c9000-b58ca000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-01 08:58:49.509  6280  6280 W art     : b58cb000-b592c000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-01 08:58:49.509  6280  6280 W art     : b592c000-b592e000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-01 08:58:49.509  6280  6280 W art     : b592e000-b592f000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-01 08:58:49.509  6280  6280 W art     : b5930000-b5957000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-01 08:58:49.509  6280  6280 W art     : b5957000-b5958000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b5958000-b5959000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-01 08:58:49.509  6280  6280 W art     : b5959000-b595a000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-01 08:58:49.509  6280  6280 W art     : b595b000-b5963000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-01 08:58:49.509  6280  6280 W art     : b5963000-b5965000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-01 08:58:49.509  6280  6280 W art     : b5965000-b5966000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-01 08:58:49.509  6280  6280 W art     : b5967000-b596a000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-01 08:58:49.509  6280  6280 W art     : b596a000-b596b000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-01 08:58:49.509  6280  6280 W art     : b596b000-b596c000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-01 08:58:49.509  6280  6280 W art     : b596c000-b5970000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-01 08:58:49.509  6280  6280 W art     : b5970000-b5971000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b5971000-b5972000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-01 08:58:49.509  6280  6280 W art     : b5972000-b5973000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-01 08:58:49.509  6280  6280 W art     : b5973000-b5983000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-01 08:58:49.509  6280  6280 W art     : b5983000-b5984000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-01 08:58:49.509  6280  6280 W art     : b5984000-b5985000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-01 08:58:49.509  6280  6280 W art     : b5985000-b59cb000 rw-p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b59cb000-b59d4000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-01 08:58:49.509  6280  6280 W art     : b59d4000-b59d5000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-01 08:58:49.509  6280  6280 W art     : b59d5000-b59d6000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-01 08:58:49.509  6280  6280 W art     : b59d7000-b59dc000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-01 08:58:49.509  6280  6280 W art     : b59dc000-b59dd000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-01 08:58:49.509  6280  6280 W art     : b59dd000-b59de000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-01 08:58:49.509  6280  6280 W art     : b59de000-b59e1000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-01 08:58:49.509  6280  6280 W art     : b59e1000-b59e2000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b59e2000-b59e3000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-01 08:58:49.509  6280  6280 W art     : b59e3000-b59e4000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-01 08:58:49.509  6280  6280 W art     : b59e5000-b59fd000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-01 08:58:49.509  6280  6280 W art     : b59fd000-b59fe000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b59fe000-b59ff000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-01 08:58:49.509  6280  6280 W art     : b59ff000-b5a00000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-01 08:58:49.509  6280  6280 W art     : b5a01000-b5b9b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-01 08:58:49.509  6280  6280 W art     : b5b9b000-b5b9c000 ---p 00000000 00:00 0 
07-01 08:58:49.509  6280  6280 W art     : b5b9c000-b5ba9000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-01 08:58:49.509  6280  6280 W art     : b5ba9000-b5baa000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-01 08:58:49.519  6280  6280 W art     : b5baa000-b5bae000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-01 08:58:49.519  6280  6280 W art     : b5bae000-b5baf000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5baf000-b5bb0000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-01 08:58:49.519  6280  6280 W art     : b5bb0000-b5bb1000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-01 08:58:49.519  6280  6280 W art     : b5bb1000-b5bc4000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-01 08:58:49.519  6280  6280 W art     : b5bc4000-b5bc5000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-01 08:58:49.519  6280  6280 W art     : b5bc5000-b5bc6000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-01 08:58:49.519  6280  6280 W art     : b5bc7000-b5c12000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-01 08:58:49.519  6280  6280 W art     : b5c12000-b5c13000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-01 08:58:49.519  6280  6280 W art     : b5c13000-b5c14000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-01 08:58:49.519  6280  6280 W art     : b5c14000-b5c16000 rw-p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5c16000-b5c17000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 08:58:49.519  6280  6280 W art     : b5c17000-b5c28000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-01 08:58:49.519  6280  6280 W art     : b5c28000-b5c29000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5c29000-b5c2a000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-01 08:58:49.519  6280  6280 W art     : b5c2a000-b5c2b000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-01 08:58:49.519  6280  6280 W art     : b5c2c000-b5c36000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-01 08:58:49.519  6280  6280 W art     : b5c36000-b5c38000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-01 08:58:49.519  6280  6280 W art     : b5c38000-b5c39000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-01 08:58:49.519  6280  6280 W art     : b5c39000-b5c52000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-01 08:58:49.519  6280  6280 W art     : b5c52000-b5c53000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-01 08:58:49.519  6280  6280 W art     : b5c53000-b5c56000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-01 08:58:49.519  6280  6280 W art     : b5c56000-b5c5a000 rw-p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5c5a000-b5cce000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-01 08:58:49.519  6280  6280 W art     : b5cce000-b5ccf000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5ccf000-b5cd2000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-01 08:58:49.519  6280  6280 W art     : b5cd2000-b5cd3000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-01 08:58:49.519  6280  6280 W art     : b5cd4000-b5cd7000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-01 08:58:49.519  6280  6280 W art     : b5cd7000-b5cd8000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-01 08:58:49.519  6280  6280 W art     : b5cd8000-b5cd9000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-01 08:58:49.519  6280  6280 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5cda000-b5cdf000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-01 08:58:49.519  6280  6280 W art     : b5cdf000-b5ce0000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-01 08:58:49.519  6280  6280 W art     : b5ce0000-b5ce1000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-01 08:58:49.519  6280  6280 W art     : b5ce1000-b5ce2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b5ce2000-b5ce5000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-01 08:58:49.519  6280  6280 W art     : b5ce5000-b5ce6000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-01 08:58:49.519  6280  6280 W art     : b5ce6000-b5ce7000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-01 08:58:49.519  6280  6280 W art     : b5ce7000-b5ce8000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b5ce8000-b5cec000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-01 08:58:49.519  6280  6280 W art     : b5cec000-b5ced000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-01 08:58:49.519  6280  6280 W art     : b5ced000-b5cee000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-01 08:58:49.519  6280  6280 W art     : b5cee000-b5cef000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 08:58:49.519  6280  6280 W art     : b5cef000-b5cf3000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-01 08:58:49.519  6280  6280 W art     : b5cf3000-b5cf4000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-01 08:58:49.519  6280  6280 W art     : b5cf4000-b5cf5000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-01 08:58:49.519  6280  6280 W art     : b5cf5000-b5cf6000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b5cf6000-b5d04000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-01 08:58:49.519  6280  6280 W art     : b5d04000-b5d05000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b5d05000-b5d06000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-01 08:58:49.519  6280  6280 W art     : b5d06000-b5d07000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-01 08:58:49.519  6280  6280 W art     : b5d07000-b5d11000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-01 08:58:49.519  6280  6280 W art     : b5d11000-b5d14000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-01 08:58:49.519  6280  6280 W art     : b5d14000-b5d15000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-01 08:58:49.519  6280  6280 W art     : b5d15000-b5d16000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b5d16000-b5d20000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-01 08:58:49.519  6280  6280 W art     : b5d20000-b5d23000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-01 08:58:49.519  6280  6280 W art     : b5d23000-b5d24000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-01 08:58:49.519  6280  6280 W art     : b5d24000-b5d28000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-01 08:58:49.519  6280  6280 W art     : b5d28000-b5d29000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-01 08:58:49.519  6280  6280 W art     : b5d29000-b5d2a000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-01 08:58:49.519  6280  6280 W art     : b5d2a000-b5d2b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b5d2b000-b5d38000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-01 08:58:49.519  6280  6280 W art     : b5d38000-b5d3a000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-01 08:58:49.519  6280  6280 W art     : b5d3a000-b5d3b000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-01 08:58:49.519  6280  6280 W art     : b5d3b000-b614d000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-01 08:58:49.519  6280  6280 W art     : b614d000-b614e000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b614e000-b6157000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-01 08:58:49.519  6280  6280 W art     : b6157000-b615b000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-01 08:58:49.519  6280  6280 W art     : b615b000-b615c000 rw-p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b615c000-b6163000 r-xp 00000000 b3:17 2571       /system/lib/libaud
07-01 08:58:49.519  6280  6280 W art     : ioutils.so
07-01 08:58:49.519  6280  6280 W art     : b6163000-b6164000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-01 08:58:49.519  6280  6280 W art     : b6164000-b6165000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-01 08:58:49.519  6280  6280 W art     : b6165000-b6166000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b6166000-b6181000 r-xp 00000000
07-01 08:58:49.519  6280  6280 W art     :  b3:17 1184       /system/lib/libz.so
07-01 08:58:49.519  6280  6280 W art     : b6181000-b6182000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-01 08:58:49.519  6280  6280 W art     : b6182000-b6183000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-01 08:58:49.519  6280  6280 W art     : b6183000-b6184000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b6184000-b61d0000 r-xp 00000000 b3:17 994        
07-01 08:58:49.519  6280  6280 W art     : /system/lib/libharfbuzz_ng.so
07-01 08:58:49.519  6280  6280 W art     : b61d0000-b61d1000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b61d1000-b61d2000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-01 08:58:49.519  6280  6280 W art     : b61d2000-b61d3000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-01 08:58:49.519  6280  6280 W art     : b61d3000-b61d4000 r--p 00000000 00:00 0          [anon:li
07-01 08:58:49.519  6280  6280 W art     : nker_alloc]
07-01 08:58:49.519  6280  6280 W art     : b61d4000-b61d8000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-01 08:58:49.519  6280  6280 W art     : b61d8000-b61d9000 ---p 00000000 00:00 0 
07-01 08:58:49.519  6280  6280 W art     : b61d9000-b61da000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-01 08:58:49.519  6280  6280 W art     : b61da000-b61db000 rw-p 00005000 b3:17 2681       /system/lib/libu
07-01 08:58:49.519  6280  6280 W art     : sbhost.so
07-01 08:58:49.519  6280  6280 W art     : b61db000-b6213000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-01 08:58:49.529  6280  6280 W art     : b6213000-b6214000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-01 08:58:49.529  6280  6280 W art     : b6214000-b6215000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-01 08:58:49.529  6280  6280 W art     : b6215000-b6216000 r--p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     :          [anon:linker_alloc]
07-01 08:58:49.529  6280  6280 W art     : b6216000-b62b4000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-01 08:58:49.529  6280  6280 W art     : b62b4000-b62b5000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b62b5000-b62d3000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-01 08:58:49.529  6280  6280 W art     : b62d3000-b62d4000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
07-01 08:58:49.529  6280  6280 W art     : .so
07-01 08:58:49.529  6280  6280 W art     : b62d4000-b6447000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-01 08:58:49.529  6280  6280 W art     : b6447000-b6452000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-01 08:58:49.529  6280  6280 W art     : b6452000-b6453000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-01 08:58:49.529  6280  6280 W art     : b6453000-b656a000 r-xp 00000000
07-01 08:58:49.529  6280  6280 W art     :  b3:17 2041       /system/lib/libicuuc.so
07-01 08:58:49.529  6280  6280 W art     : b656a000-b6575000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-01 08:58:49.529  6280  6280 W art     : b6575000-b6576000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-01 08:58:49.529  6280  6280 W art     : b6576000-b657a000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b657a000-b659e000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
07-01 08:58:49.529  6280  6280 W art     : o
07-01 08:58:49.529  6280  6280 W art     : b659e000-b65a0000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-01 08:58:49.529  6280  6280 W art     : b65a0000-b65a1000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-01 08:58:49.529  6280  6280 W art     : b65a1000-b6647000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-01 08:58:49.529  6280  6280 W art     : b6647000-b6654000 r--p 000a5000 b3:17 13
07-01 08:58:49.529  6280  6280 W art     : 2        /system/lib/libcrypto.so
07-01 08:58:49.529  6280  6280 W art     : b6654000-b6655000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-01 08:58:49.529  6280  6280 W art     : b6655000-b6656000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6656000-b66a9000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-01 08:58:49.529  6280  6280 W art     : b66a9000-b66aa000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b66aa000-b66ab000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-01 08:58:49.529  6280  6280 W art     : b66ab000-b66ac000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-01 08:58:49.529  6280  6280 W art     : b66ac000-b66b1000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b66b1000-b66c3000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-01 08:58:49.529  6280  6280 W art     : b66c3000-b66c4000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b66c4000-b66c5000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-01 08:58:49.529  6280  6280 W art     : b66c5000-b66c6000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-01 08:58:49.529  6280  6280 W art     : b66c6000-b66cd000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-01 08:58:49.529  6280  6280 W art     : b66cd000-b66ce000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-01 08:58:49.529  6280  6280 W art     : b66ce000-b66cf000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-01 08:58:49.529  6280  6280 W art     : b66cf000-b66d0000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b66d0000-b66d3000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-01 08:58:49.529  6280  6280 W art     : b66d3000-b66d4000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-01 08:58:49.529  6280  6280 W art     : b66d4000-b66d5000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-01 08:58:49.529  6280  6280 W art     : b66d5000-b66d9000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-01 08:58:49.529  6280  6280 W art     : b66d9000-b66da000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-01 08:58:49.529  6280  6280 W art     : b66da000-b66db000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-01 08:58:49.529  6280  6280 W art     : b66db000-b66e9000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-01 08:58:49.529  6280  6280 W art     : b66e9000-b66ea000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b66ea000-b66eb000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-01 08:58:49.529  6280  6280 W art     : b66eb000-b66ec000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-01 08:58:49.529  6280  6280 W art     : b66ec000-b66f5000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-01 08:58:49.529  6280  6280 W art     : b66f5000-b66f6000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-01 08:58:49.529  6280  6280 W art     : b66f6000-b66f7000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-01 08:58:49.529  6280  6280 W art     : b66f7000-b675d000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-01 08:58:49.529  6280  6280 W art     : b675d000-b675e000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b675e000-b6760000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-01 08:58:49.529  6280  6280 W art     : b6760000-b6769000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-01 08:58:49.529  6280  6280 W art     : b6769000-b676c000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b676c000-b6803000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-01 08:58:49.529  6280  6280 W art     : b6803000-b6805000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-01 08:58:49.529  6280  6280 W art     : b6805000-b6806000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-01 08:58:49.529  6280  6280 W art     : b6806000-b6807000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6807000-b6b28000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-01 08:58:49.529  6280  6280 W art     : b6b28000-b6b29000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6b29000-b6b44000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-01 08:58:49.529  6280  6280 W art     : b6b44000-b6b48000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-01 08:58:49.529  6280  6280 W art     : b6b48000-b6b4d000 rw-p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6b4d000-b6b55000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-01 08:58:49.529  6280  6280 W art     : b6b55000-b6b56000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-01 08:58:49.529  6280  6280 W art     : b6b56000-b6b57000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-01 08:58:49.529  6280  6280 W art     : b6b57000-b6b85000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-01 08:58:49.529  6280  6280 W art     : b6b85000-b6b86000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6b86000-b6b8d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-01 08:58:49.529  6280  6280 W art     : b6b8d000-b6b8e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-01 08:58:49.529  6280  6280 W art     : b6b8e000-b6bd4000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-01 08:58:49.529  6280  6280 W art     : b6bd4000-b6bd5000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6bd5000-b6bd8000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-01 08:58:49.529  6280  6280 W art     : b6bd8000-b6bd9000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-01 08:58:49.529  6280  6280 W art     : b6bd9000-b6bf4000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-01 08:58:49.529  6280  6280 W art     : b6bf4000-b6bf8000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-01 08:58:49.529  6280  6280 W art     : b6bf8000-b6bf9000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-01 08:58:49.529  6280  6280 W art     : b6bf9000-b6c46000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-01 08:58:49.529  6280  6280 W art     : b6c46000-b6c47000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6c47000-b6c53000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-01 08:58:49.529  6280  6280 W art     : b6c53000-b6c54000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-01 08:58:49.529  6280  6280 W art     : b6c54000-b6c61000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-01 08:58:49.529  6280  6280 W art     : b6c61000-b6c62000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6c62000-b6c63000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-01 08:58:49.529  6280  6280 W art     : b6c63000-b6c64000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-01 08:58:49.529  6280  6280 W art     : b6c64000-b6c6c000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-01 08:58:49.529  6280  6280 W art     : b6c6c000-b6c6d000 ---p 00000000 00:00 0 
07-01 08:58:49.529  6280  6280 W art     : b6c6d000-b6c6e000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-01 08:58:49.529  6280  6280 W art     : b6c6e000-b6c6f000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-01 08:58:49.529  6280  6280 W art     : b6c6f000-b6c76000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-01 08:58:49.529  6280  6280 W art     : b6c76000-b6c77000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-01 08:58:49.529  6280  6280 W art     : b6c77000-b6c78000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-01 08:58:49.539  6280  6280 W art     : b6c78000-b6c8c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-01 08:58:49.539  6280  6280 W art     : b6c8c000-b6c8e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-01 08:58:49.539  6280  6280 W art     : b6c8e000-b6c8f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-01 08:58:49.539  6280  6280 W art     : b6c8f000-b6cb7000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-01 08:58:49.539  6280  6280 W art     : b6cb7000-b6cb9000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-01 08:58:49.539  6280  6280 W art     : b6cb9000-b6cba000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-01 08:58:49.539  6280  6280 W art     : b6cba000-b6cbd000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-01 08:58:49.539  6280  6280 W art     : b6cbd000-b6cbe000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-01 08:58:49.539  6280  6280 W art     : b6cbe000-b6cbf000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-01 08:58:49.539  6280  6280 W art     : b6cbf000-b6cc8000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-01 08:58:49.539  6280  6280 W art     : b6cc8000-b6cc9000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-01 08:58:49.539  6280  6280 W art     : b6cc9000-b6cca000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-01 08:58:49.539  6280  6280 W art     : b6cca000-b6cea000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-01 08:58:49.539  6280  6280 W art     : b6cea000-b6ceb000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-01 08:58:49.539  6280  6280 W art     : b6ceb000-b6cec000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-01 08:58:49.539  6280  6280 W art     : b6cec000-b6d5f000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-01 08:58:49.539  6280  6280 W art     : b6d5f000-b6d63000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-01 08:58:49.539  6280  6280 W art     : b6d63000-b6d66000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-01 08:58:49.539  6280  6280 W art     : b6d66000-b6d70000 rw-p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6d70000-b6df8000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-01 08:58:49.539  6280  6280 W art     : b6df8000-b6df9000 ---p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6df9000-b6dfd000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-01 08:58:49.539  6280  6280 W art     : b6dfd000-b6dfe000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-01 08:58:49.539  6280  6280 W art     : b6dfe000-b6dff000 rw-p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6dff000-b6e28000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-01 08:58:49.539  6280  6280 W art     : b6e28000-b6e29000 ---p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6e29000-b6e2c000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-01 08:58:49.539  6280  6280 W art     : b6e2c000-b6e2d000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-01 08:58:49.539  6280  6280 W art     : b6e2d000-b6f07000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-01 08:58:49.539  6280  6280 W art     : b6f07000-b6f0e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-01 08:58:49.539  6280  6280 W art     : b6f0e000-b6f16000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-01 08:58:49.539  6280  6280 W art     : b6f16000-b6f17000 rw-p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6f17000-b6f18000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 08:58:49.539  6280  6280 W art     : b6f18000-b6f19000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-01 08:58:49.539  6280  6280 W art     : b6f19000-b6f1a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.539  6280  6280 W art     : b6f1a000-b6f1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.539  6280  6280 W art     : b6f1d000-b6f42000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-01 08:58:49.539  6280  6280 W art     : b6f42000-b6f43000 ---p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6f43000-b6f4a000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-01 08:58:49.539  6280  6280 W art     : b6f4a000-b6f4b000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-01 08:58:49.539  6280  6280 W art     : b6f4b000-b6f52000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-01 08:58:49.539  6280  6280 W art     : b6f52000-b6f53000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-01 08:58:49.539  6280  6280 W art     : b6f53000-b6f54000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-01 08:58:49.539  6280  6280 W art     : b6f54000-b6f55000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.539  6280  6280 W art     : b6f55000-b6f6d000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-01 08:58:49.539  6280  6280 W art     : b6f6d000-b6f6e000 ---p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6f6e000-b6f6f000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-01 08:58:49.539  6280  6280 W art     : b6f6f000-b6f70000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-01 08:58:49.539  6280  6280 W art     : b6f70000-b6f7e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-01 08:58:49.539  6280  6280 W art     : b6f7e000-b6f7f000 ---p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6f7f000-b6f80000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-01 08:58:49.539  6280  6280 W art     : b6f80000-b6f81000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-01 08:58:49.539  6280  6280 W art     : b6f81000-b6f82000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 08:58:49.539  6280  6280 W art     : b6f82000-b6f84000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.539  6280  6280 W art     : b6f84000-b6f85000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.539  6280  6280 W art     : b6f85000-b6f86000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 08:58:49.539  6280  6280 W art     : b6f86000-b6f87000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-01 08:58:49.539  6280  6280 W art     : b6f87000-b6f88000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 08:58:49.539  6280  6280 W art     : b6f88000-b6fa8000 r--s 00000000 00:0b 8200       /dev/__properties__
07-01 08:58:49.539  6280  6280 W art     : b6fa8000-b6fa9000 r--p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6fa9000-b6faa000 ---p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6faa000-b6fac000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-01 08:58:49.539  6280  6280 W art     : b6fac000-b6fad000 r-xp 00000000 00:00 0          [sigpage]
07-01 08:58:49.539  6280  6280 W art     : b6fad000-b6fc8000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-01 08:58:49.539  6280  6280 W art     : b6fc8000-b6fc9000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-01 08:58:49.539  6280  6280 W art     : b6fc9000-b6fcb000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-01 08:58:49.539  6280  6280 W art     : b6fcb000-b6fcd000 rw-p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : b6fcd000-b6fd2000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-01 08:58:49.539  6280  6280 W art     : b6fd2000-b6fd3000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-01 08:58:49.539  6280  6280 W art     : b6fd3000-b6fd4000 rw-p 00000000 00:00 0 
07-01 08:58:49.539  6280  6280 W art     : bea1d000-bea3e000 rw-p 00000000 00:00 0          [stack]
07-01 08:58:49.539  6280  6280 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-01 08:58:49.579  6280  6280 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-01 08:58:49.639  6280  6280 I Radio-JNI: register_android_hardware_Radio DONE
07-01 08:58:49.649  6280  6280 E AffinityControl: AffinityControl: registerfunction enter
07-01 08:58:49.669  6280  6280 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 08:58:49.679   770  1721 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-01 08:58:49.689   770  1721 D ActivityManager: mDVFSHelper.acquire()
07-01 08:58:49.689   770  1721 V WindowManager: addAppToken: AppWindowToken{84aa8c1 token=Token{c4e65a8 ActivityRecord{51ef9cb u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
07-01 08:58:49.699   770   908 D SecWifiDisplayUtil: Metadata value : none
07-01 08:58:49.699   770   908 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{55aaef9 V.E...... R.....ID 0,0-0,0}
07-01 08:58:49.709   770  1721 I ActivityManager: Start proc 6295:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-01 08:58:49.709   770  1721 D InputDispatcher: Focused application set to: xxxx
07-01 08:58:49.709   770  1721 D InputDispatcher: Focus left window: 3415
07-01 08:58:49.709   770   908 D ISSUE_DEBUG: InputChannelName : ee1a49f Starting com.test.thalitest
07-01 08:58:49.709   770   872 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{19ad319 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-01 08:58:49.709   770  1321 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-01 08:58:49.709  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-01 08:58:49.709  6280  6280 D AndroidRuntime: Shutting down VM
07-01 08:58:49.719  6295  6295 E Zygote  : v2
07-01 08:58:49.719  6295  6295 I libpersona: KNOX_SDCARD checking this for 10004
07-01 08:58:49.719  6295  6295 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.719  6295  6295 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 08:58:49.719  6295  6295 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-01 08:58:49.719  6295  6295 E Zygote  : accessInfo : 0
07-01 08:58:49.719  6295  6295 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-01 08:58:49.719   294   294 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-01 08:58:49.739   770   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
07-01 08:58:49.739   770   908 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:49.739   770   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-01 08:58:49.739   770   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-01 08:58:49.739   770   908 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-01 08:58:49.749  6295  6295 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:49.749  6295  6295 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:49.759   770  1735 V WindowOrientationListener: setCurrentAppOrientation :-1
07-01 08:58:49.759   770  1735 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-01 08:58:49.759   770   872 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ee1a49f u0 d0 Starting com.test.thalitest}
07-01 08:58:49.759  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-01 08:58:49.769   770  1735 D ActivityManager:  Launching com.test.thalitest, updated priority
07-01 08:58:49.779   770   908 V WindowStateAnimator: Finishing drawing window Window{ee1a49f u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-01 08:58:49.779   770   865 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-01 08:58:49.789   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe825364
07-01 08:58:49.799  1723  1865 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-01 08:58:49.799  1723  1723 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-01 08:58:49.809   294   361 D libEGL  : eglTerminate EGLDisplay = 0xb698164c
07-01 08:58:49.809   294  1790 I SurfaceFlinger: id=13 Removed VSBConnecti (7/11)
07-01 08:58:49.809   294  1298 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
07-01 08:58:49.809   294   365 I SurfaceFlinger: id=14 Removed VSBConnecti (5/10)
07-01 08:58:49.809   294   361 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/10)
07-01 08:58:49.819  3415  3415 V ActivityThread: updateVisibility : ActivityRecord{2740b28 token=android.os.BinderProxy@f4e70c2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-01 08:58:49.819   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8253a4
07-01 08:58:49.819   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8253a4
07-01 08:58:49.819   294   365 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
07-01 08:58:49.819   294   365 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
07-01 08:58:49.819   294  1790 I SurfaceFlinger: id=7 Removed Mauncher (4/9)
07-01 08:58:49.819   294   361 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
07-01 08:58:49.829  2127  2138 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-01 08:58:49.829  1723  1723 V ActivityThread: updateVisibility : ActivityRecord{4169a27 token=android.os.BinderProxy@4df88c4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 08:58:49.829  1723  1723 D Launcher: onTrimMemory. Level: 20
07-01 08:58:49.839   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8253a4
07-01 08:58:49.919   770  1321 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-01 08:58:49.939  6295  6295 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-01 08:58:49.939   770  3348 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-01 08:58:49.959  6295  6295 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-01 08:58:49.969  6295  6295 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-01 08:58:49.979  6295  6295 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-01 08:58:50.009  6295  6295 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-01 08:58:50.019  6295  6295 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-01 08:58:50.019   770   779 I art     : Background partial concurrent mark sweep GC freed 16261(1175KB) AllocSpace objects, 16(320KB) LOS objects, 27% free, 42MB/58MB, paused 1.550ms total 118.684ms
,07-01 08:58:50.029  6295  6295 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 8570-8573)
,07-01 08:58:50.029  6295  6295 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-01 08:58:50.049   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 08:58:50.049   770  1735 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-01 08:58:50.049  6295  6319 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-01 08:58:50.049   770  1735 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-01 08:58:50.049   770  1735 D BatteryService: stay LED for fully charged
,07-01 08:58:50.049   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-01 08:58:50.049  6295  6295 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {613b054}
07-01 08:58:50.049  6295  6295 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-01 08:58:50.049  6295  6295 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 08:58:50.049   770   770 I MotionRecognitionService: Plugged
,07-01 08:58:50.049   770   770 D MotionRecognitionService:   cableConnection= 1
07-01 08:58:50.049   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-01 08:58:50.049   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 08:58:50.049  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 08:58:50.059  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 08:58:50.059  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 08:58:50.059  6295  6295 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-01 08:58:50.079  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:58:50.079  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:58:50.079  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:58:50.079  6295  6320 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-01 08:58:50.089  6295  6295 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-01 08:58:50.089  6295  6295 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-01 08:58:50.089  6295  6295 I Adreno-EGL: Build Date: 01/28/16 Thu
07-01 08:58:50.089  6295  6295 I Adreno-EGL: Local Branch: ss
07-01 08:58:50.089  6295  6295 I Adreno-EGL: Remote Branch: 
07-01 08:58:50.089  6295  6295 I Adreno-EGL: Local Patches: 
07-01 08:58:50.089  6295  6295 I Adreno-EGL: Reconstruct Branch: 
,07-01 08:58:50.089  6295  6295 D libEGL  : eglInitialize EGLDisplay = 0xbedd6dac
,07-01 08:58:50.149   770   788 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,07-01 08:58:50.149   770   788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-01 08:58:50.199  6295  6295 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-01 08:58:50.209  6295  6295 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 08:58:50.219  6295  6295 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-01 08:58:50.219  6295  6295 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-01 08:58:50.219  6295  6295 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-01 08:58:50.229  6295  6295 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-01 08:58:50.239  6295  6295 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-01 08:58:50.309  6295  6295 D SecWifiDisplayUtil: Metadata value : none
,07-01 08:58:50.319  6295  6295 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{89cd052 I.E...... R.....ID 0,0-0,0}
,07-01 08:58:50.319  6295  6346 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:58:50.329   770  1410 D ISSUE_DEBUG: InputChannelName : bda020 com.test.thalitest/com.test.thalitest.MainActivity
,07-01 08:58:50.329   770  1252 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-01 08:58:50.329   770  1252 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-01 08:58:50.329   770   770 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-01 08:58:50.329   770   770 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-01 08:58:50.339  6295  6295 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6295
,07-01 08:58:50.339   770   788 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6295 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 08:58:50.349  6295  6319 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
07-01 08:58:50.349  6295  6295 D SecWifiDisplayUtil: Metadata value : none
,07-01 08:58:50.359   294   294 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-01 08:58:50.369   770  1410 D InputDispatcher: Focus entered window: 6295
07-01 08:58:50.369   770   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
,07-01 08:58:50.369   770   908 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:50.369   770   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-01 08:58:50.369   770   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-01 08:58:50.369  6295  6346 D libEGL  : eglInitialize EGLDisplay = 0x9cb7f7c4
07-01 08:58:50.369  6295  6346 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:50.419  6295  6295 V ActivityThread: updateVisibility : ActivityRecord{f314a7f token=android.os.BinderProxy@cd31cdd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-01 08:58:50.419  6295  6295 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-01 08:58:50.419  6295  6295 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-01 08:58:50.419   770  1721 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-01 08:58:50.429  6295  6295 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-01 08:58:50.439   770  1722 V WindowStateAnimator: Finishing drawing window Window{bda020 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-01 08:58:50.439  6295  6295 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-01 08:58:50.449  6295  6295 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cd31cdd time:158990
,07-01 08:58:50.449   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe825364
,07-01 08:58:50.449   770   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-01 08:58:50.449   770   908 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +532ms (total +757ms)
07-01 08:58:50.449   770   770 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-01 08:58:50.449   770   770 I KnoxTimeoutHandler: SD activityfalse
,07-01 08:58:50.459   770   908 D ActivityManager: mDVFSHelper.release()
07-01 08:58:50.459   770   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{51ef9cb u0 com.test.thalitest/.MainActivity t64} time:159002
,07-01 08:58:50.459   770   908 D ViewRootImpl: #3 mView = null
,07-01 08:58:50.459   294   365 I SurfaceFlinger: id=15 Removed uhalitest (7/9)
07-01 08:58:50.459   294  1790 I SurfaceFlinger: id=15 Removed uhalitest (-2/9)
,07-01 08:58:50.469   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8253a4
,07-01 08:58:50.489  6295  6354 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-01 08:58:50.489  6295  6354 D libEGL  : eglInitialize EGLDisplay = 0x9b5bf3ec
,07-01 08:58:50.529  6295  6295 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6295
,07-01 08:58:50.599  6295  6295 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 08:58:50.749  6295  6363 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1703937744
,07-01 08:58:50.759  6295  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:50.759  6295  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:50.759  6295  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:50.759  6295  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:50.759  6295  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 08:58:50.759  6295  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@279f74d added. We now have 1 listener(s)
,07-01 08:58:50.769  6295  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,07-01 08:58:50.769  6295  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,07-01 08:58:50.769  6295  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 08:58:50.769  6295  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-01 08:58:50.769  6295  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9758d50 added. We now have 1 listener(s)
07-01 08:58:50.769  6295  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:58:50.769  6295  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:58:50.769  6295  6363 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-01 08:58:50.779  6295  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-01 08:58:50.779  6295  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:50.779  6295  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 08:58:50.779  6295  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:58:50.779  6295  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 08:58:50.779  6295  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,07-01 08:58:50.779  6295  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 08:58:50.779  6295  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 08:58:50.779  6295  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:50.779  6295  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 08:58:50.779  6295  6363 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 08:58:50.799  6295  6295 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:50.919   770  3349 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-01 08:58:51.329  1447  1447 D Recents : onTaskStackChanged
,07-01 08:58:51.339  1447  1447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-01 08:58:51.669  6295  6364 W jxcore-log: Initializing JXcore engine
,07-01 08:58:51.669  6295  6364 W jxcore-log: JXcore engine is ready
,07-01 08:58:51.709  2238  2238 E audit   : type=1400 msg=audit(1467356331.709:278): avc:  denied  { ioctl } for  pid=6364 comm="Thread-895" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 08:58:51.709  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 08:58:51.709  2238  2238 E audit   : type=1300 msg=audit(1467356331.709:278): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=2 a3=990ae3c8 items=0 ppid=352 ppcomm=main pid=6364 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-895" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-01 08:58:51.709  2238  2238 E audit   : type=1327 msg=audit(1467356331.709:278): proctitle="com.test.thalitest"
07-01 08:58:51.709  2238  2238 E audit   : type=1320 msg=audit(1467356331.709:278): 
,07-01 08:58:51.719  2238  2238 E audit   : type=1400 msg=audit(1467356331.719:279): avc:  denied  { ioctl } for  pid=6364 comm="Thread-895" path="socket:[40148]" dev="sockfs" ino=40148 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-01 08:58:51.719  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 08:58:51.719  2238  2238 E audit   : type=1300 msg=audit(1467356331.719:279): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=2 a3=990ae3c8 items=0 ppid=352 ppcomm=main pid=6364 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-895" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-01 08:58:51.719  2238  2238 E audit   : type=1327 msg=audit(1467356331.719:279): proctitle="com.test.thalitest"
,07-01 08:58:51.719  2238  2238 E audit   : type=1320 msg=audit(1467356331.719:279): 
,07-01 08:58:51.729  6295  6364 W jxcore-log: Starting JXcore engine
,07-01 08:58:51.809  6295  6364 W jxcore-log: Platform android
07-01 08:58:51.809  6295  6364 W jxcore-log: 
07-01 08:58:51.809  6295  6364 W jxcore-log: Process ARCH arm
07-01 08:58:51.809  6295  6364 W jxcore-log: 
,07-01 08:58:52.019  6295  6364 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:52.019  6295  6364 I jxcore-log: 
,07-01 08:58:52.019  6295  6364 W jxcore-log: JXcore engine is started
,07-01 08:58:52.019  6295  6363 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 08:58:52.029   770  1735 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package null
,07-01 08:58:52.039   770  1735 D ActivityManager: mDVFSHelper.acquire()
,07-01 08:58:52.049   770  1735 V WindowManager: addAppToken: AppWindowToken{f095150 token=Token{b992b13 ActivityRecord{52b1602 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}}} to stack=1 task=64 at 1
,07-01 08:58:52.059   770  1735 I ActivityManager: Start proc 6365:com.android.packageinstaller/u0a129 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,07-01 08:58:52.059   770  1735 D InputDispatcher: Focused application set to: xxxx
07-01 08:58:52.059  6365  6365 E Zygote  : v2
07-01 08:58:52.059  6365  6365 I libpersona: KNOX_SDCARD checking this for 10129
07-01 08:58:52.059  6365  6365 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:52.059  6365  6365 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 08:58:52.059  6365  6365 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 08:58:52.059   770  1735 D InputDispatcher: Focus left window: 6295
,07-01 08:58:52.059  6365  6365 E Zygote  : accessInfo : 0
07-01 08:58:52.059  6365  6365 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,07-01 08:58:52.059   770   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
,07-01 08:58:52.059   770   908 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:52.059   770   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-01 08:58:52.059   770   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-01 08:58:52.059  6295  6363 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
,07-01 08:58:52.079  6365  6365 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:52.079  6365  6365 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:52.089   770   788 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,07-01 08:58:52.089   770   865 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,07-01 08:58:52.399   770   788 I WindowManager: Screenshot max retries 4 of Token{b992b13 ActivityRecord{52b1602 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}} appWin=Window{bda020 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,07-01 08:58:52.419  6365  6365 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.429  6365  6365 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,07-01 08:58:52.449  6365  6365 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.449  6365  6365 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.469  6365  6365 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.479  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.489  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.489  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.489  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.499  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.499  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.549  6365  6365 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,07-01 08:58:52.559  6365  6365 D SecWifiDisplayUtil: Metadata value : none
,07-01 08:58:52.559  6365  6365 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d5a9adc I.E...... R.....I. 0,0-0,0}
,07-01 08:58:52.559  6365  6384 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:58:52.559   770  1722 D ISSUE_DEBUG: InputChannelName : 5117705 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,07-01 08:58:52.569   770   788 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,07-01 08:58:52.569   770   788 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 08:58:52.569   770   770 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-01 08:58:52.569   770   770 I KnoxTimeoutHandler: Shared devices show user statefalse
07-01 08:58:52.569   770   770 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,07-01 08:58:52.589   294   294 I SurfaceFlinger: id=17 createSurf (145x145),1 flag=4, HrantPermis
,07-01 08:58:52.589   770   872 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5117705 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,07-01 08:58:52.589  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,07-01 08:58:52.599   770   789 D InputDispatcher: Focus entered window: 6365
,07-01 08:58:52.609   770   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
,07-01 08:58:52.609   770   908 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:52.609   770   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-01 08:58:52.609   770   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-01 08:58:52.609  6365  6384 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-01 08:58:52.609  6365  6384 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-01 08:58:52.609  6365  6384 I Adreno-EGL: Build Date: 01/28/16 Thu
07-01 08:58:52.609  6365  6384 I Adreno-EGL: Local Branch: ss
07-01 08:58:52.609  6365  6384 I Adreno-EGL: Remote Branch: 
07-01 08:58:52.609  6365  6384 I Adreno-EGL: Local Patches: 
07-01 08:58:52.609  6365  6384 I Adreno-EGL: Reconstruct Branch: 
,07-01 08:58:52.609  6365  6384 D libEGL  : eglInitialize EGLDisplay = 0xae20b7c4
,07-01 08:58:52.609  6365  6384 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:52.639  6365  6365 V ActivityThread: updateVisibility : ActivityRecord{533bd47 token=android.os.BinderProxy@e5ab34f {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,07-01 08:58:52.639  6365  6365 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-01 08:58:52.639   770  1252 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-01 08:58:52.649  1949  1949 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-01 08:58:52.669  6365  6365 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-01 08:58:52.689   770  1735 V WindowStateAnimator: Finishing drawing window Window{5117705 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,07-01 08:58:52.699  6365  6365 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e5ab34f time:161240
,07-01 08:58:52.699   770   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-01 08:58:52.699   770   908 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +298ms (total +654ms)
07-01 08:58:52.699   770   770 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-01 08:58:52.699   770   770 I KnoxTimeoutHandler: SD activityfalse
,07-01 08:58:52.699   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe825364
,07-01 08:58:52.699   770   908 D ActivityManager: mDVFSHelper.release()
,07-01 08:58:52.699   770   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{52b1602 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64} time:161248
,07-01 08:58:52.729   770  1363 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,07-01 08:58:53.569  1447  1447 D Recents : onTaskStackChanged
,07-01 08:58:57.499   770  3348 D SSRM:n  : SIOP:: AP = 330, PST = 366, CUR = 450, LCD = 0
,07-01 08:58:58.449   770  3348 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-01 08:58:59.709   770   942 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-01 08:58:59.739   770   942 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-01 08:58:59.899   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:58:59.989   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 08:59:07.559   770  3348 D SSRM:n  : SIOP:: AP = 310, PST = 358, CUR = 450, LCD = 0
,07-01 08:59:09.509   770  1236 V AlarmManager: Expired Alarm result :4
,07-01 08:59:09.529   770  1639 D NtpTrustedTime: forceRefresh: no connectivity
,07-01 08:59:09.529   770  1639 V AlarmManager:  remove PendingIntent] PendingIntent{3ca0c0e: PendingIntentRecord{d87962f android broadcastIntent}}
,07-01 08:59:09.579   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 08:59:09.579   770  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 08:59:09.579   770  1722 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-01 08:59:09.579   770  1722 D BatteryService: stay LED for fully charged
,07-01 08:59:09.599   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6da9367 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2708df4 2077:com.google.android.gms.persistent/u0a11}
,07-01 08:59:09.619   770  1236 I ActivityManager: Start proc 6406:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-01 08:59:09.629  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 08:59:09.629  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-01 08:59:09.629  6406  6406 E Zygote  : v2
07-01 08:59:09.629  6406  6406 I libpersona: KNOX_SDCARD checking this for 1000
07-01 08:59:09.629  6406  6406 I libpersona: KNOX_SDCARD not a persona
,07-01 08:59:09.629  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 08:59:09.639  6406  6406 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 08:59:09.639  6406  6406 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 08:59:09.639  6406  6406 E Zygote  : accessInfo : 0
,07-01 08:59:09.659   770  1570 V AlarmManager:  remove PendingIntent] PendingIntent{ca45514: PendingIntentRecord{5fe34b6 com.google.android.gms broadcastIntent}}
,07-01 08:59:09.659  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-01 08:59:09.669   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 08:59:09.669  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-01 08:59:09.679   770   770 I MotionRecognitionService: Plugged
,07-01 08:59:09.679   770   770 D MotionRecognitionService:   cableConnection= 1
07-01 08:59:09.679   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 08:59:09.679   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 08:59:09.689  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.689  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.689  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.689  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.699  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.709  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.719  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.719  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-01 08:59:09.719  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 08:59:09.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:59:09.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:59:09.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:09.719  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 08:59:09.739  6406  6406 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:59:09.739  6406  6406 D ActivityThread: Added TimaKeyStore provider
,07-01 08:59:09.749  6406  6406 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-01 08:59:09.769  6406  6406 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-01 08:59:09.769  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 08:59:09.789   770  1577 I ActivityManager: Killing 5059:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,07-01 08:59:09.809   770  1736 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,07-01 08:59:12.359   770  1581 E Watchdog: !@Sync 5 [07-01 08:59:12.365]
,07-01 08:59:12.559   770  3349 W ResourcesManager: getTopLevelResources: /system/app/bootagent/bootagent.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.559   770  3349 W ResourcesManager: getTopLevelResources: /system/app/BluetoothTest/BluetoothTest.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.569   770  3349 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.569   770  3349 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.589   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.589   770  3349 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.609   770  3349 W ResourcesManager: getTopLevelResources: /system/app/EdmSimPinService/EdmSimPinService.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.609   770  3349 W ResourcesManager: getTopLevelResources: /system/app/AntHalService/AntHalService.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.609   770  3349 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.619   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/CSC/CSC.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.629   770  3349 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.629   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.639   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/Telecom/Telecom.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.639   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartcardManager/SmartcardManager.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.639   770  3349 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.649   770  3349 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.649   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMediaProvider/SecMediaProvider.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.659   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/ContextProvider/ContextProvider.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.669   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in null rsrc of package null
,07-01 08:59:12.669   770  3349 W ResourcesManager: getTopLevelResources: /system/priv-app/UcsPinpad/UcsPinpad.apk / 1.0 running in null rsrc of package null
,07-01 08:59:17.219   770  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-01 08:59:17.229   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ad32ac u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b2b0259 5884:com.samsung.android.sm.provider/1000}
,07-01 08:59:17.239   770  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-01 08:59:17.239   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{639570a u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b2b0259 5884:com.samsung.android.sm.provider/1000}
,07-01 08:59:17.639   770  3348 D SSRM:n  : SIOP:: AP = 330, PST = 356, CUR = 450, LCD = 0
,07-01 08:59:19.669   770   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 08:59:19.679   770   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 08:59:19.679   770   789 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 08:59:19.679   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 08:59:19.689   770   770 I MotionRecognitionService: Plugged
,07-01 08:59:19.699   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 08:59:19.699   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 08:59:19.699   770   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-01 08:59:19.699   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 08:59:19.709   770   789 D BatteryService: stay LED for fully charged
,07-01 08:59:19.709  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 08:59:19.709  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 08:59:19.709  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 08:59:19.739  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:19.739  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:59:19.739  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:19.909   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:59:20.519  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.529  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.529  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.539  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings/SecSettings.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.549  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.559  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera3/SamsungCamera3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.559  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.569  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.569  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.579  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.589  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.599  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.609  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.619  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Flipboard/Flipboard.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.619  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.629  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.639  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.649  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.659  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.669  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.669  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M_OS_UPG/SPlanner_M_OS_UPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.679  5884  6453 W ResourcesManager: getTopLevelResources: /data/app/com.android.vending-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.689  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.689  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.699  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.699  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideo/SecVideo.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.709  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.709  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.719  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote/VoiceNote.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.719  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.729  5884  6453 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator2_LMUPG/SecCalculator2_LMUPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.729  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.739  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.749  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.759  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.769  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/app-production-release-3.3.3-newSDK_23/app-production-release-3.3.3-newSDK_23.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.779  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/SecMemoDL/SecMemoDL.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.789  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.859  5884  6453 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_MUPG/ClockPackage_MUPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.869  5884  6453 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.879  5884  6453 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:20.889  5884  6453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-01 08:59:27.699   770  3348 D SSRM:n  : SIOP:: AP = 310, PST = 350, CUR = 450, LCD = 0
,07-01 08:59:37.779   770  3348 D SSRM:n  : SIOP:: AP = 310, PST = 338, CUR = 450, LCD = 0
,07-01 08:59:39.609   770  1236 V AlarmManager: Expired Alarm result :4
,07-01 08:59:39.659   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95c09f1 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2708df4 2077:com.google.android.gms.persistent/u0a11}
,07-01 08:59:39.669   770  1410 V AlarmManager:  remove PendingIntent] PendingIntent{89dd9d6: PendingIntentRecord{5fe34b6 com.google.android.gms broadcastIntent}}
,07-01 08:59:39.679   770  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 08:59:39.679   770  1570 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-01 08:59:39.679   770  1570 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 08:59:39.679   770  1570 D BatteryService: stay LED for fully charged
07-01 08:59:39.679   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 08:59:39.689   770   770 I MotionRecognitionService: Plugged
,07-01 08:59:39.689   770   770 D MotionRecognitionService:   cableConnection= 1
07-01 08:59:39.689   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-01 08:59:39.689   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 08:59:39.689  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 08:59:39.689  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 08:59:39.689  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 08:59:39.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:39.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:59:39.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:39.909   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:59:40.479  2077  2077 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=48776d75-fa81-41d0-893c-bed2e74b8161
,07-01 08:59:40.509  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 08:59:40.509  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 08:59:40.649  2077  2219 W GCoreFlp: No location to return for getLastLocation()
,07-01 08:59:40.709  4149  6466 D UdcContextInitService: registered all accounts: true
,07-01 08:59:40.729  2077  2402 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 08:59:40.739  2077  2556 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-01 08:59:40.869  2077  2556 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-01 08:59:40.909   770  1466 V AlarmManager:  remove PendingIntent] PendingIntent{61830c5: PendingIntentRecord{5fe34b6 com.google.android.gms broadcastIntent}}
,07-01 08:59:40.939  2077  2556 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-01 08:59:41.049  4149  4958 D NetworkUsageDbReporter: Started reporting usage
,07-01 08:59:41.149  4149  4958 D NetworkUsageDbReporter: Finished reporting usage.
,07-01 08:59:41.199   770  1722 V AlarmManager:  remove PendingIntent] PendingIntent{20a9de6: PendingIntentRecord{5fe34b6 com.google.android.gms broadcastIntent}}
,07-01 08:59:42.359   770  1581 E Watchdog: !@Sync 6 [07-01 08:59:42.373]
,07-01 08:59:43.009  2077  2556 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-01 08:59:43.009  2077  2556 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-01 08:59:43.229  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 08:59:47.839   770  3348 D SSRM:n  : SIOP:: AP = 300, PST = 325, CUR = 450, LCD = 0
,07-01 08:59:49.769   770  1721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 08:59:49.769   770  1721 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 08:59:49.769   770  1721 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 08:59:49.769   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 08:59:49.789   770   770 I MotionRecognitionService: Plugged
,07-01 08:59:49.789   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 08:59:49.789   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 08:59:49.789   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 08:59:49.799   770  1721 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-01 08:59:49.799   770  1721 D BatteryService: stay LED for fully charged
,07-01 08:59:49.809  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 08:59:49.809  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 08:59:49.819  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 08:59:49.849  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:49.849  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:59:49.849  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 08:59:57.899   770  3348 D SSRM:n  : SIOP:: AP = 300, PST = 318, CUR = 450, LCD = 0
,07-01 08:59:59.909   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:59:59.999   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:00:00.099   770  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:00:00.099   770  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:00:00.099   770  1466 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:00:00.109   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:00:00.119   770   770 I MotionRecognitionService: Plugged
,07-01 09:00:00.119   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:00:00.119   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:00:00.119   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:00:00.129   770  1466 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:00:00.129   770  1466 D BatteryService: stay LED for fully charged
,07-01 09:00:00.139  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:00:00.139  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:00:00.139  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:00:00.169  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:00:00.179  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:00:00.179  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:00:07.959   770  3348 D SSRM:n  : SIOP:: AP = 300, PST = 314, CUR = 450, LCD = 0
,07-01 09:00:09.619   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:00:12.369   770  1581 E Watchdog: !@Sync 7 [07-01 09:00:12.378]
,07-01 09:00:18.019   770  3348 D SSRM:n  : SIOP:: AP = 300, PST = 311, CUR = 450, LCD = 0
,07-01 09:00:19.919   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:00:28.069   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 308, CUR = 450, LCD = 0
,07-01 09:00:30.159   770  1721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:00:30.159   770  1721 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:00:30.159   770  1721 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:00:30.169   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:00:30.179   770   770 I MotionRecognitionService: Plugged
,07-01 09:00:30.179   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:00:30.179   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:00:30.179   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:00:30.189   770  1721 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:00:30.189   770  1721 D BatteryService: stay LED for fully charged
,07-01 09:00:30.199  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:00:30.209  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:00:30.209  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:00:30.239  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:00:30.239  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:00:30.249  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:00:38.149   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 304, CUR = 450, LCD = 0
,07-01 09:00:39.919   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:00:42.379   770  1581 E Watchdog: !@Sync 8 [07-01 09:00:42.382]
,07-01 09:00:43.239  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:00:43.449  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 205ms lastUpdatedAfter : 160733ms
,07-01 09:00:48.199   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 302, CUR = 450, LCD = 0
,07-01 09:00:58.259   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-01 09:00:59.929   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:01:00.239   770  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:00.239   770  1706 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:01:00.239   770  1706 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:01:00.249   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:01:00.259   770   770 I MotionRecognitionService: Plugged
,07-01 09:01:00.259   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:01:00.259   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:01:00.259   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:01:00.269   770  1706 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:01:00.269   770  1706 D BatteryService: stay LED for fully charged
,07-01 09:01:00.279  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:01:00.279  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:01:00.279  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:01:00.299  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:00.299  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:01:00.299  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:08.319   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-01 09:01:12.369   770  1581 E Watchdog: !@Sync 9 [07-01 09:01:12.386]
,07-01 09:01:18.369   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-01 09:01:19.929   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:01:27.179   770  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 09:01:27.179   770  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 09:01:27.179   770  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 09:01:27.189   770  1230 I TLC_TIMA_PKM_initialize: initializing...
,07-01 09:01:27.189   770  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-01 09:01:27.189   770  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-01 09:01:27.199   770  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-01 09:01:27.199   770  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-01 09:01:27.199   770  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-01 09:01:27.199   770  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-01 09:01:27.199   770  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-01 09:01:27.209   770  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-01 09:01:27.209   770  1230 D QSEECOMAPI: : App is not loaded in QSEE
,07-01 09:01:27.249   770  1230 D QSEECOMAPI: : Loaded image: APP id = 3
,07-01 09:01:27.259   770  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-01 09:01:27.269   770  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-01 09:01:28.429   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-01 09:01:30.319   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 09:01:30.319   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
07-01 09:01:30.329   770  1701 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:30.329   770  1701 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:01:30.329   770  1701 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:01:30.329   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:01:30.339   770   770 I MotionRecognitionService: Plugged
,07-01 09:01:30.339   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:01:30.339   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:01:30.349   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:01:30.349   770  1701 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 18ms
,07-01 09:01:30.349   770  1701 D BatteryService: stay LED for fully charged
,07-01 09:01:30.359  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:01:30.359  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:01:30.359  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:01:30.369   770  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:01:30.369   770  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:01:30.399  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:30.399  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:01:30.399  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:38.499   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-01 09:01:39.929   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:01:40.579  2077  2923 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:01:42.389   770  1581 E Watchdog: !@Sync 10 [07-01 09:01:42.392]
,07-01 09:01:43.459  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:01:48.559   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-01 09:01:58.609   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:01:59.939   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:00.389   770  1252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:00.389   770  1252 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:02:00.389   770  1252 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:02:00.389   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:02:00.409   770   770 I MotionRecognitionService: Plugged
,07-01 09:02:00.409   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:02:00.409   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:02:00.409   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:02:00.419   770  1252 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-01 09:02:00.419   770  1252 D BatteryService: stay LED for fully charged
,07-01 09:02:00.429  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:02:00.429  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:02:00.429  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:02:00.449  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:02:00.449  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:02:00.449  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:02:04.389  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:04.399  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:04.409  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:04.469  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:02:04.469  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:02:04.479   305  1158 D EnterpriseController: netId is 0
07-01 09:02:04.479   305  1158 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,07-01 09:02:08.669   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:02:12.389   770  1581 E Watchdog: !@Sync 11 [07-01 09:02:12.396]
,07-01 09:02:18.719   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:02:19.939   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:28.789   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:02:30.469   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:38.849   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:02:39.949   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:42.399   770  1581 E Watchdog: !@Sync 12 [07-01 09:02:42.401]
,07-01 09:02:43.489  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:02:48.899   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:02:58.949   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:02:59.939   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:59.999   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:02:59.999   770  1236 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=408536 batch.start=501497
,07-01 09:03:00.029  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 09:03:00.029  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-01 09:03:00.029  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 09:03:00.059  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-01 09:03:00.079  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-01 09:03:00.079   770  1639 D NtpTrustedTime: forceRefresh: no connectivity
,07-01 09:03:00.089   770  1639 V AlarmManager:  remove PendingIntent] PendingIntent{3ca0c0e: PendingIntentRecord{d87962f android broadcastIntent}}
,07-01 09:03:00.109  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.109  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.109  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.109  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.109  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.119  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.129   770  1639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,07-01 09:03:00.139  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.189  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:03:00.559   770   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:03:00.559   770   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:03:00.569   770   788 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:03:00.569   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:03:00.579   770   770 I MotionRecognitionService: Plugged
,07-01 09:03:00.579   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:03:00.579   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:03:00.589   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:03:00.589   770   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-01 09:03:00.589   770   788 D BatteryService: stay LED for fully charged
,07-01 09:03:00.609  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:03:00.609  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:03:00.609  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:03:00.629  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:03:00.629  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:03:00.629  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:03:09.039   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:03:12.389   770  1581 E Watchdog: !@Sync 13 [07-01 09:03:12.405]
,07-01 09:03:19.099   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:03:19.949   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:03:29.149   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:03:30.639   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:03:30.639   770  1735 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:03:30.639   770  1735 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:03:30.649   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:03:30.659   770   770 I MotionRecognitionService: Plugged
,07-01 09:03:30.659   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:03:30.659   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:03:30.659   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:03:30.669   770  1735 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-01 09:03:30.669   770  1735 D BatteryService: stay LED for fully charged
,07-01 09:03:30.689  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:03:30.689  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:03:30.689  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:03:30.719  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:03:30.729  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:03:30.729  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:03:39.209   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:03:39.959   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:03:42.399   770  1581 E Watchdog: !@Sync 14 [07-01 09:03:42.409]
,07-01 09:03:43.509  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:03:43.659  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 143ms lastUpdatedAfter : 180211ms
,07-01 09:03:49.269   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:03:59.329   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:03:59.949   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:03:59.989   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:04:00.719   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:04:00.719   770  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:04:00.719   770  1722 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:04:00.729   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:04:00.739   770   770 I MotionRecognitionService: Plugged
,07-01 09:04:00.739   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:04:00.739   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:04:00.739   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:04:00.749   770  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:04:00.749   770  1722 D BatteryService: stay LED for fully charged
,07-01 09:04:00.759  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:04:00.759  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:04:00.759  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:04:00.779  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:04:00.779  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:04:00.779  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:04:09.379   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:04:12.399   770  1581 E Watchdog: !@Sync 15 [07-01 09:04:12.413]
,07-01 09:04:16.839   369   369 I bootchecker: bootchecker wake up!!
,07-01 09:04:19.429   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:04:19.959   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:04:29.489   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:04:32.969   770  1236 V AlarmManager: Expired Alarm result :4
,07-01 09:04:33.049   770  1252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:04:33.069   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{42c4c96 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc6d420 4149:com.google.android.gms/u0a11}
,07-01 09:04:33.079  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 09:04:33.079  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-01 09:04:33.079  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 09:04:33.099  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-01 09:04:33.099  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-01 09:04:33.119  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.129  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.129  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.129  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.129  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.129  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.139  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.189  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:04:33.279  4149  6551 I EventLogChimeraService: Aggregate from 1467354872777 (log), 1467354872777 (data)
,07-01 09:04:33.419   770   779 I art     : Background partial concurrent mark sweep GC freed 53988(5MB) AllocSpace objects, 175(3MB) LOS objects, 27% free, 42MB/58MB, paused 2.072ms total 173.139ms
,07-01 09:04:33.439   770   865 I ActivityManager: Start proc 6552:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,07-01 09:04:33.439  6552  6552 E Zygote  : v2
07-01 09:04:33.439  6552  6552 I libpersona: KNOX_SDCARD checking this for 1000
07-01 09:04:33.439  6552  6552 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 09:04:33.439  6552  6552 I libpersona: KNOX_SDCARD not a persona
07-01 09:04:33.439  6552  6552 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-01 09:04:33.439  6552  6552 E Zygote  : accessInfo : 0
,07-01 09:04:33.479  6552  6552 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 09:04:33.479  6552  6552 D ActivityThread: Added TimaKeyStore provider
,07-01 09:04:33.489   770  1252 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e1906b3 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2249470 6552:com.samsung.android.sm/1000}
,07-01 09:04:33.499  6552  6552 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,07-01 09:04:33.549   770  1735 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e1906b3 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc6d420 4149:com.google.android.gms/u0a11}
,07-01 09:04:33.589   770  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{508586e u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2249470 6552:com.samsung.android.sm/1000}
,07-01 09:04:33.629   770  1721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{508586e u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc6d420 4149:com.google.android.gms/u0a11}
,07-01 09:04:33.979  4149  6565 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-01 09:04:34.029  4149  6565 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-01 09:04:34.039   770  1735 I ActivityManager: Killing 5076:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,07-01 09:04:34.069   770  1466 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,07-01 09:04:39.549   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:04:39.959   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:04:42.409   770  1581 E Watchdog: !@Sync 16 [07-01 09:04:42.417]
,07-01 09:04:43.709  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:04:49.599   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:04:59.659   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:04:59.959   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:04:59.989   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:05:03.119   770  1706 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:05:09.729   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:05:12.419   770  1581 E Watchdog: !@Sync 17 [07-01 09:05:12.424]
,07-01 09:05:19.779   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:05:19.969   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:05:29.839   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:05:33.199   770   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:05:33.199   770   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:05:33.199   770   789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:05:33.209   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:05:33.219   770   770 I MotionRecognitionService: Plugged
,07-01 09:05:33.219   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:05:33.219   770   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,07-01 09:05:33.219   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:05:33.229   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:05:33.229   770   789 D BatteryService: stay LED for fully charged
,07-01 09:05:33.249  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:05:33.249  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:05:33.249  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:05:33.279  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:05:33.289  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:05:33.289  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:05:39.889   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:05:39.969   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:05:42.419   770  1581 E Watchdog: !@Sync 18 [07-01 09:05:42.428]
,07-01 09:05:43.729  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:05:49.939   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:05:59.979   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:06:00.019   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:06:03.279   770  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:06:10.089   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:06:12.419   770  1581 E Watchdog: !@Sync 19 [07-01 09:06:12.433]
,07-01 09:06:19.979   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:06:20.139   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:06:27.169   770  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 09:06:27.169   770  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 09:06:27.169   770  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 09:06:28.509   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 09:06:28.509   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 09:06:28.519   770  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:06:28.519   770  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:06:30.199   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:06:33.359   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:06:39.979   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:06:40.249   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:06:42.429   770  1581 E Watchdog: !@Sync 20 [07-01 09:06:42.437]
,07-01 09:06:43.749  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:06:43.909  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 153ms lastUpdatedAfter : 180249ms
,07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.199   770   859 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.209   770   859 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.219   770   859 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-01 09:06:46.229   770   859 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-01 09:06:46.319   770   908 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-01 09:06:46.319   770   908 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-01 09:06:50.309   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:06:59.999   770  3379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:07:00.359   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:07:03.439   770   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:07:03.439   770   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:07:03.449   770   789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:07:03.449   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:07:03.459   770   770 I MotionRecognitionService: Plugged
,07-01 09:07:03.459   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:07:03.459   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:07:03.459   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:07:03.469   770   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:07:03.469   770   789 D BatteryService: stay LED for fully charged
,07-01 09:07:03.479  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:07:03.479  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:07:03.479  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:07:03.519  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:07:03.519  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:07:03.519  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:07:04.559   770  1701 I ActivityManager: Killing 4446:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 603s, lastActivityTime 603s
,07-01 09:07:04.559   770  1701 I ActivityManager: Killing 3785:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 607s, lastActivityTime 607s
,07-01 09:07:04.579  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:04.599   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-01 09:07:04.599   378  5013 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-01 09:07:04.609   378  5013 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:07:04.609   770  1577 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-01 09:07:04.609   770  1577 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-01 09:07:04.609   770  1577 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-01 09:07:04.629  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:04.629  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:04.689  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 09:07:04.689  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:07:04.699   305  1158 D EnterpriseController: netId is 0
07-01 09:07:04.699   305  1158 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,07-01 09:07:04.699   770  1570 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
07-01 09:07:04.699   770  1570 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-01 09:07:04.699   770  1570 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10911ms
,07-01 09:07:05.619   378  5013 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:07:05.679   770   865 I ActivityManager: Start proc 6609:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-01 09:07:05.699  6609  6609 E Zygote  : v2
,07-01 09:07:05.699  6609  6609 I libpersona: KNOX_SDCARD checking this for 1000
07-01 09:07:05.699  6609  6609 I libpersona: KNOX_SDCARD not a persona
,07-01 09:07:05.699  6609  6609 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-01 09:07:05.699  6609  6609 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:07:05.709  6609  6609 E Zygote  : accessInfo : 0
,07-01 09:07:05.749  6609  6609 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:07:05.749  6609  6609 D ActivityThread: Added TimaKeyStore provider
,07-01 09:07:05.769  6609  6609 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-01 09:07:05.789  6609  6609 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-01 09:07:05.789  6609  6609 D AtFwdService: onCreate method
,07-01 09:07:05.789  6609  6609 I AtFwdService: Instantiate AtCmdFwd Service
,07-01 09:07:05.809  6609  6621 D AtCkpdCmdHandler: De-queing command
,07-01 09:07:10.419   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:07:12.439   770  1581 E Watchdog: !@Sync 21 [07-01 09:07:12.444]
,07-01 09:07:15.679   770   865 I ActivityManager: Start proc 6623:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-01 09:07:15.699  6623  6623 E Zygote  : v2
,07-01 09:07:15.699  6623  6623 I libpersona: KNOX_SDCARD checking this for 10026
07-01 09:07:15.699  6623  6623 I libpersona: KNOX_SDCARD not a persona
,07-01 09:07:15.699  6623  6623 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-01 09:07:15.699  6623  6623 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:07:15.709  6623  6623 E Zygote  : accessInfo : 0
,07-01 09:07:15.709  6623  6623 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-01 09:07:15.749  6623  6623 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:07:15.749  6623  6623 D ActivityThread: Added TimaKeyStore provider
,07-01 09:07:15.759   770  1701 I ActivityManager: Killing 3887:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 618s, lastActivityTime 607s
,07-01 09:07:15.789  6623  6623 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-01 09:07:15.799   770  1410 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,07-01 09:07:15.799   770  1410 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-01 09:07:15.819  6623  6623 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-01 09:07:15.839  6623  6623 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-01 09:07:15.839  6623  6623 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-01 09:07:16.309   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:07:20.509   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:07:30.559   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:07:33.519   770   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:07:33.519   770   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:07:33.529   770   788 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:07:33.529   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:07:33.539   770   770 I MotionRecognitionService: Plugged
,07-01 09:07:33.539   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:07:33.539   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:07:33.549   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:07:33.549   770   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-01 09:07:33.549   770   788 D BatteryService: stay LED for fully charged
,07-01 09:07:33.559  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:07:33.559  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:07:33.569  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:07:33.599  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:07:33.599  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:07:33.599  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:07:40.609   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:07:42.439   770  1581 E Watchdog: !@Sync 22 [07-01 09:07:42.448]
,07-01 09:07:43.929  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:07:50.669   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:08:00.719   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:08:03.599   770  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:08:03.599   770  1410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:08:03.609   770  1410 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:08:03.609   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:08:03.619   770   770 I MotionRecognitionService: Plugged
,07-01 09:08:03.619   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:08:03.619   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:08:03.629   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:08:03.629   770  1410 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-01 09:08:03.629   770  1410 D BatteryService: stay LED for fully charged
,07-01 09:08:03.649  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:08:03.649  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:08:03.649  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:08:03.669  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:08:03.669  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:08:03.669  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:08:10.789   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:08:12.439   770  1581 E Watchdog: !@Sync 23 [07-01 09:08:12.455]
,07-01 09:08:20.849   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:08:30.899   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:08:33.679   770  1701 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:08:33.679   770  1701 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:08:33.679   770  1701 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:08:33.689   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:08:33.699   770   770 I MotionRecognitionService: Plugged
,07-01 09:08:33.699   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:08:33.699   770  1701 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
,07-01 09:08:33.709   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:08:33.709   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:08:33.709   770  1701 D BatteryService: stay LED for fully charged
,07-01 09:08:33.729  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:08:33.729  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:08:33.729  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:08:33.759  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:08:33.769  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:08:33.769  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:08:40.959   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:08:42.459   770  1581 E Watchdog: !@Sync 24 [07-01 09:08:42.461]
,07-01 09:08:44.019  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:08:51.019   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:09:01.069   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:09:03.759   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:09:03.769   770  1735 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:09:03.769   770  1735 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:09:03.769   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:09:03.779   770   770 I MotionRecognitionService: Plugged
,07-01 09:09:03.779   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:09:03.789   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:09:03.789   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:09:03.789   770  1735 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:09:03.789   770  1735 D BatteryService: stay LED for fully charged
,07-01 09:09:03.799  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:09:03.799  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:09:03.799  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:09:03.819  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:09:03.829  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:09:03.829  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:09:11.149   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:09:12.449   770  1581 E Watchdog: !@Sync 25 [07-01 09:09:12.465]
,07-01 09:09:21.229   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:09:31.279   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:09:33.839   770  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:09:41.339   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:09:42.459   770  1581 E Watchdog: !@Sync 26 [07-01 09:09:42.471]
,07-01 09:09:44.039  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:09:44.189  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 147ms lastUpdatedAfter : 180277ms
,07-01 09:09:46.309   770  2329 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-01 09:09:46.309   770  2329 V MARsPolicyManager: updateSMDBValues
,07-01 09:09:46.319   770   905 E MARsDBManager: updateDBAll : begin --size 1
,07-01 09:09:46.339   770   905 I ActivityManager: Killing 1846:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 782s, lastActivityTime 701s
,07-01 09:09:46.349   770   905 I ActivityManager: Killing 1511:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 759s, lastActivityTime 749s
,07-01 09:09:46.409   770   905 E MARsDBManager: updateDBAll : end
,07-01 09:09:46.409   770   905 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-01 09:09:46.459   770  1736 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,07-01 09:09:46.459   770  1736 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
,07-01 09:09:46.459   770  1736 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-01 09:09:46.479   770  1735 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-01 09:09:46.479   770  1735 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-01 09:09:46.479   770  1735 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10982ms
,07-01 09:09:46.479   770  1735 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-01 09:09:46.479   770  1735 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 20981ms
,07-01 09:09:46.479  5622  5622 D HealthConsole: Service for HealthDataStore is disconnected
,07-01 09:09:46.529  6666  6666 E Zygote  : v2
07-01 09:09:46.529  6666  6666 I libpersona: KNOX_SDCARD checking this for 10034
07-01 09:09:46.529  6666  6666 I libpersona: KNOX_SDCARD not a persona
,07-01 09:09:46.529  6666  6666 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 09:09:46.529  6666  6666 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:09:46.529  6666  6666 E Zygote  : accessInfo : 0
07-01 09:09:46.529  6666  6666 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-01 09:09:46.539   770  1570 I ActivityManager: Start proc 6666:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,07-01 09:09:46.559  6666  6666 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:09:46.559  6666  6666 D ActivityThread: Added TimaKeyStore provider
,07-01 09:09:46.579  6666  6666 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-01 09:09:46.599  6666  6666 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-01 09:09:46.599  6666  6666 I MultiDex: VM with version 2.1.0 has multidex support
,07-01 09:09:46.599  6666  6666 I MultiDex: install
07-01 09:09:46.599  6666  6666 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-01 09:09:46.599  6666  6666 I MultiDex: install
07-01 09:09:46.599  6666  6666 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 09:09:46.689  6682  6682 E Zygote  : v2
07-01 09:09:46.689  6682  6682 I libpersona: KNOX_SDCARD checking this for 10016
,07-01 09:09:46.689  6682  6682 I libpersona: KNOX_SDCARD not a persona
07-01 09:09:46.689  6682  6682 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-01 09:09:46.689  6682  6682 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:09:46.689  6682  6682 E Zygote  : accessInfo : 0
,07-01 09:09:46.689  6682  6682 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
07-01 09:09:46.689   770  1721 I ActivityManager: Start proc 6682:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,07-01 09:09:46.719  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 09:09:46.719  6682  6682 D ActivityThread: Added TimaKeyStore provider
,07-01 09:09:46.739  6682  6682 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-01 09:09:46.789  6666  6666 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
07-01 09:09:46.789  6666  6666 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-01 09:09:46.889  1380  1380 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-01 09:09:46.889   770  1706 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-01 09:09:46.909   770  4209 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-01 09:09:46.929   770  1736 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-01 09:09:46.929  1380  1380 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{4874758 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,07-01 09:09:46.929  1380  1380 D AdaptiveEventManager: M updateContainers()
,07-01 09:09:46.929  1380  1380 D AdaptiveEventContainerSmall: C updatePedoContainer()
,07-01 09:09:46.939  1380  1380 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-01 09:09:46.939  1380  1380 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-01 09:09:46.949   770  1577 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-01 09:09:47.049  6666  6666 I Health.HealthService: HealthService: onCreate() start (6666)
,07-01 09:09:47.279  5622  5622 D HealthDataStore: Service for HealthDataStore is connected
,07-01 09:09:47.279  5622  5622 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-01 09:09:47.299   770  1736 I ActivityManager: Killing 4572:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,07-01 09:09:47.319  5622  5622 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-01 09:09:47.319  5622  5622 E HealthDataStore: disconnectService: Context instance is invalid
,07-01 09:09:47.339  6666  6666 D HealthDataStore: Service for HealthDataStore is connected
,07-01 09:09:47.349  6666  6666 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-01 09:09:47.349  6666  6666 D HealthConsole: Service for HealthDataConsole is connected
,07-01 09:09:47.359  6666  6666 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-01 09:09:47.359  6666  6666 E HealthDataStore: disconnectService: Context instance is invalid
,07-01 09:09:47.389   770  1706 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,07-01 09:09:47.499   770   865 I ActivityManager: Start proc 6726:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
07-01 09:09:47.509   770  1321 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-01 09:09:47.509  6726  6726 E Zygote  : v2
,07-01 09:09:47.509  6726  6726 I libpersona: KNOX_SDCARD checking this for 10181
07-01 09:09:47.509  6726  6726 I libpersona: KNOX_SDCARD not a persona
,07-01 09:09:47.509  6726  6726 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 09:09:47.519  6726  6726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:09:47.519  6726  6726 E Zygote  : accessInfo : 0
,07-01 09:09:47.519  6726  6726 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-01 09:09:47.569  6726  6726 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:09:47.569  6726  6726 D ActivityThread: Added TimaKeyStore provider
,07-01 09:09:47.589   770  1321 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-01 09:09:47.599  6726  6726 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-01 09:09:47.639  6726  6726 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-01 09:09:47.649  6666  6707 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-01 09:09:47.669  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-01 09:09:47.679  6726  6726 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-01 09:09:47.689   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1c8e83 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be6c800 6726:com.sec.android.daemonapp/u0a181}
,07-01 09:09:47.709  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-01 09:09:47.709  6726  6726 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-01 09:09:47.709  6726  6726 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-01 09:09:47.719  6726  6726 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-01 09:09:47.719  6726  6726 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-01 09:09:47.719  6726  6726 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-01 09:09:47.749  6666  6739 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-01 09:09:47.779  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-01 09:09:47.779  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-01 09:09:47.779  6682  6693 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-01 09:09:47.789  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-01 09:09:47.799  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-01 09:09:47.799   418   418 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 10016, gid 10016, pid 6682
07-01 09:09:47.799   418   418 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,07-01 09:09:47.799  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-01 09:09:47.799  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-01 09:09:47.809  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-01 09:09:47.839  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-01 09:09:47.859  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-01 09:09:47.859  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-01 09:09:47.859  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-01 09:09:47.859  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-01 09:09:47.869  6726  6726 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-01 09:09:47.879  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-01 09:09:47.879  6726  6726 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-01 09:09:47.879  6726  6726 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-01 09:09:47.879  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-01 09:09:47.889  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-01 09:09:47.889  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-01 09:09:47.889  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-01 09:09:47.889  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-01 09:09:47.889  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-01 09:09:47.889  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
07-01 09:09:47.899  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-01 09:09:47.899   770  4209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df0642c u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be6c800 6726:com.sec.android.daemonapp/u0a181}
,07-01 09:09:47.909  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-01 09:09:47.909  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-01 09:09:47.909  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-01 09:09:47.909  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-01 09:09:47.919  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-01 09:09:47.919  6726  6726 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-01 09:09:47.919  6726  6726 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-01 09:09:47.919  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-01 09:09:47.919  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-01 09:09:47.929  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-01 09:09:47.929   770  1252 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3e83ef5 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be6c800 6726:com.sec.android.daemonapp/u0a181}
,07-01 09:09:47.949  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-01 09:09:47.949  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-01 09:09:47.949  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-01 09:09:47.949  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-01 09:09:47.959  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-01 09:09:47.959  6726  6726 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-01 09:09:47.959  6726  6726 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-01 09:09:47.959  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-01 09:09:47.959  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-01 09:09:47.969  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-01 09:09:47.979   770  1736 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38fa48a u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be6c800 6726:com.sec.android.daemonapp/u0a181}
,07-01 09:09:47.989  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
07-01 09:09:47.989  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-01 09:09:47.989  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-01 09:09:47.989  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-01 09:09:47.999  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-01 09:09:47.999  6726  6726 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-01 09:09:47.999  6726  6726 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-01 09:09:47.999  6726  6726 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-01 09:09:47.999  6726  6726 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-01 09:09:48.009  6726  6726 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-01 09:09:48.019  6682  6693 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-01 09:09:48.059  6666  6739 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-01 09:09:48.179  6666  6739 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
07-01 09:09:48.179  6666  6739 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-01 09:09:48.409   418   418 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,07-01 09:09:48.479  6682  6693 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,07-01 09:09:48.479  6682  6693 I SecureStorage: [INFO]: SPID(0x00000007)Skip using SecureStorageExceptionJNI
,07-01 09:09:48.479  6682  6693 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-01 09:09:51.389   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:10:01.449   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:10:03.919   770  4209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:10:03.929   770  4209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:10:03.929   770  4209 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:10:03.929   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:10:03.939   770   770 I MotionRecognitionService: Plugged
,07-01 09:10:03.949   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:10:03.949   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:10:03.949   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:10:03.949   770  4209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:10:03.959   770  4209 D BatteryService: stay LED for fully charged
,07-01 09:10:03.969  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:10:03.979  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:10:03.979  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:10:03.999  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:10:03.999  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:10:03.999  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:10:11.499   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:10:12.459   770  1581 E Watchdog: !@Sync 27 [07-01 09:10:12.475]
,07-01 09:10:21.579   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:10:31.629   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:10:33.999   770  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:10:33.999   770  1410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:10:34.009   770  1410 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:10:34.009   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:10:34.019   770   770 I MotionRecognitionService: Plugged
,07-01 09:10:34.019   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:10:34.029   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:10:34.029   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:10:34.029   770  1410 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:10:34.029   770  1410 D BatteryService: stay LED for fully charged
,07-01 09:10:34.039  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:10:34.039  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:10:34.049  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:10:34.079  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:10:34.079  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:10:34.079  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:10:41.719   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:10:42.469   770  1581 E Watchdog: !@Sync 28 [07-01 09:10:42.480]
,07-01 09:10:44.259  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:10:51.769   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:11:01.829   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:11:04.079   770   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:11:04.079   770   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:11:04.089   770   788 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:11:04.089   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:11:04.099   770   770 I MotionRecognitionService: Plugged
,07-01 09:11:04.099   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:11:04.099   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:11:04.099   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:11:04.109   770   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:11:04.109   770   788 D BatteryService: stay LED for fully charged
,07-01 09:11:04.129  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:11:04.129  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:11:04.129  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:11:04.149  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:11:04.149  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:11:04.149  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:11:11.909   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:11:12.469   770  1581 E Watchdog: !@Sync 29 [07-01 09:11:12.485]
,07-01 09:11:21.959   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:11:27.169   770  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 09:11:27.169   770  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 09:11:27.169   770  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 09:11:30.219   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 09:11:30.219   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 09:11:30.239   770  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:11:30.239   770  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:11:32.009   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:11:34.159   770  1701 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:11:34.159   770  1701 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:11:34.169   770  1701 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:11:34.169   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:11:34.179   770   770 I MotionRecognitionService: Plugged
,07-01 09:11:34.179   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:11:34.179   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:11:34.189   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:11:34.189   770  1701 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-01 09:11:34.189   770  1701 D BatteryService: stay LED for fully charged
,07-01 09:11:34.199  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:11:34.209  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:11:34.209  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:11:34.239  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:11:34.249  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:11:34.249  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:11:42.069   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:11:42.489   770  1581 E Watchdog: !@Sync 30 [07-01 09:11:42.490]
,07-01 09:11:44.289  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:11:52.119   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:02.169   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:02.429   770  1236 V AlarmManager: Expired Alarm result :4
,07-01 09:12:02.489   770  1236 I ActivityManager: Start proc 6766:com.wssyncmldm/1000 for service com.wssyncmldm/com.samsung.android.app.fotaclient.device.PollingIntentService
,07-01 09:12:02.499  6766  6766 E Zygote  : v2
,07-01 09:12:02.509  6766  6766 I libpersona: KNOX_SDCARD checking this for 1000
,07-01 09:12:02.509  6766  6766 I libpersona: KNOX_SDCARD not a persona
,07-01 09:12:02.509  6766  6766 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-01 09:12:02.509  6766  6766 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:12:02.509  6766  6766 E Zygote  : accessInfo : 0
,07-01 09:12:02.529  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 09:12:02.529  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-01 09:12:02.529  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 09:12:02.539  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-01 09:12:02.539   770   865 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-01 09:12:02.549  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-01 09:12:02.549  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.559   770   770 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
07-01 09:12:02.559  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.559  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.559  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.559   770   770 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-01 09:12:02.559  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.569  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.569   770   770 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-01 09:12:02.579  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.589   770   770 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-01 09:12:02.609  1801  6784 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-01 09:12:02.619  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 09:12:02.619  6766  6766 D ActivityThread: Added TimaKeyStore provider
,07-01 09:12:02.639  6766  6766 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,07-01 09:12:02.639  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-01 09:12:02.659  6766  6766 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
,07-01 09:12:02.659  1801  6772 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-01 09:12:02.689  6766  6766 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,07-01 09:12:02.739  6766  6766 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-01 09:12:02.779  1801  6772 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-01 09:12:02.779  1801  6772 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-01 09:12:02.789  1801  6772 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-01 09:12:02.789  1801  6772 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-01 09:12:02.809  6766  6766 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,07-01 09:12:02.819  6766  6766 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,07-01 09:12:02.819  6766  6766 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,07-01 09:12:02.829  6766  6766 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-01 09:12:02.839  6766  6766 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-01 09:12:02.839  1801  6772 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-01 09:12:02.839  1801  6772 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-01 09:12:02.849  6766  6766 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,07-01 09:12:02.849  6766  6802 I FOTA_AGENT: [com.samsung.android.app.fotaclient.device.PollingIntentService(19/onHandleIntent)] Polling State: Start to check polling
,07-01 09:12:02.849  6766  6802 I FOTA_AGENT: [IIllIIllIIIlllIlIIll(57/llIIIIlllllIIllIIllI)] Polling State: Check condition to update polling
,07-01 09:12:02.859  6766  6802 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(88/llIIIIlllllIIllIIllI)] Polling State: updating polling by current URL
,07-01 09:12:02.869   770  1701 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-01 09:12:02.869  6766  6802 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1049/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,07-01 09:12:02.889  6766  6802 W FOTA_AGENT: [lIlIIlIlIlIllllllIII(37/llIIIIlllllIIllIIllI)] NetworkInfo is null
,07-01 09:12:02.889  1801  6772 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,07-01 09:12:02.889  6766  6802 W FOTA_AGENT: [com.samsung.android.fem.network.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Fail to set up!
,07-01 09:12:02.889  6766  6802 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(137/llIIIIlllllIIllIIllI)] Receive result: fail in PollingRestClient
,07-01 09:12:02.889  6766  6802 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(139/llIIIIlllllIIllIIllI)] Network is not available. Wait next repeat time
,07-01 09:12:02.899  6766  6802 I FOTA_AGENT: [com.samsung.android.app.fotaclient.device.PollingIntentService(25/onHandleIntent)] Polling State: Finish to check polling
,07-01 09:12:02.899   770   789 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,07-01 09:12:02.949  4149  6806 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-01 09:12:02.949   770  1219 E LightSensor: RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,07-01 09:12:02.949   770   923 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-01 09:12:02.949   770   923 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-01 09:12:02.959   770   923 D SensorManager: unregisterListener ::   
07-01 09:12:02.959   770   923 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 1
,07-01 09:12:02.959   770   923 D lights  : led_pattern : 5 +
,07-01 09:12:02.969   770   923 D lights  : led_pattern : 5 -
07-01 09:12:02.969   770   923 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-01 09:12:02.969   770   923 V AlarmManager:  remove PendingIntent] PendingIntent{5289ec2: PendingIntentRecord{eb6e4d3 android broadcastIntent}}
,07-01 09:12:03.049  4149  4959 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-01 09:12:03.199  1801  6772 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-01 09:12:03.199  1801  6772 E native  : request_context {
07-01 09:12:03.199  1801  6772 E native  :   type: DYNAMIC_CLASS
07-01 09:12:03.199  1801  6772 E native  :   dynamic_class_context {
07-01 09:12:03.199  1801  6772 E native  :     class_type: APP_NAME
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Maps"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Settings"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Gmail"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "YouTube"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Hangouts"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Google+"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Play Store"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Chrome"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Play Books"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Play Music"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Dropbox"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Play Movies & TV"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Contacts"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Phone"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Flipboard"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Play Newsstand"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Drive"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Player"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "ThaliTest"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "S Health"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Peel Smart Remote"
07-01 09:12:03.199  1801  6772 E n,ative  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Photos"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Music"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Calculator"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Messages"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "S Planner"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Camera"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Clock"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "My Files"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Email"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Smart Manager"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Video"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Memo"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Gallery"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Voice Recorder"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Galaxy Apps"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Play Games"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "S Voice"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Docs"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :     instance {
07-01 09:12:03.199  1801  6772 E native  :       value: "Internet"
07-01 09:12:03.199  1801  6772 E native  :     }
07-01 09:12:03.199  1801  6772 E native  :   }
07-01 09:12:03.199  1801  6772 E native  : }
07-01 09:12:03.199  1801  6772 E native  : 
07-01 09:12:03.209  1801  6772 E ContextCompilationHandl: Compiling recognition context failed for APP_NAMES en-US
07-01 09:12:03.209  1801  6772 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
07-01 09:12:03.239  4149  5638 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-01 09:12:03.279  4149  4959 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-01 09:12:03.309  4149  4959 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-01 09:12:03.339  4149  4959 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-01 09:12:03.349  1801  6772 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-01 09:12:03.349  1801  6772 E native  : request_context {
07-01 09:12:03.349  1801  6772 E native  :   type: DYNAMIC_CLASS
07-01 09:12:03.349  1801  6772 E native  :   dynamic_class_context {
07-01 09:12:03.349  1801  6772 E native  :     class_type: SONG_NAME
07-01 09:12:03.349  1801  6772 E native  :     instance {
07-01 09:12:03.349  1801  6772 E native  :       value: "Over the Horizon"
07-01 09:12:03.349  1801  6772 E native  :     }
07-01 09:12:03.349  1801  6772 E native  :   }
07-01 09:12:03.349  1801  6772 E native  : }
07-01 09:12:03.349  1801  6772 E native  : request_context {
07-01 09:12:03.349  1801  6772 E native  :   type: DYNAMIC_CLASS
07-01 09:12:03.349  1801  6772 E native  :   dynamic_class_context {
07-01 09:12:03.349  1801  6772 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
07-01 09:12:03.349  1801  6772 E native  :     instance {
07-01 09:12:03.349  1801  6772 E native  :       value: "Brand Music"
07-01 09:12:03.349  1801  6772 E native  :     }
07-01 09:12:03.349  1801  6772 E native  :   }
07-01 09:12:03.349  1801  6772 E native  : }
07-01 09:12:03.349  1801  6772 E native  : request_context {
07-01 09:12:03.349  1801  6772 E native  :   type: DYNAMIC_CLASS
07-01 09:12:03.349  1801  6772 E native  :   dynamic_class_context {
07-01 09:12:03.349  1801  6772 E native  :     class_type: ARTIST_NAME
07-01 09:12:03.349  1801  6772 E native  :     instance {
07-01 09:12:03.349  1801  6772 E native  :       value: "Samsung"
07-01 09:12:03.349  1801  6772 E native  :     }
07-01 09:12:03.349  1801  6772 E native  :   }
07-01 09:12:03.349  1801  6772 E native  : }
07-01 09:12:03.349  1801  6772 E native  : 
,07-01 09:12:03.359  1801  6772 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
,07-01 09:12:04.239   770   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:12:04.249   770   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:12:04.249   770   788 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:12:04.249   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:12:04.259   770   770 I MotionRecognitionService: Plugged
,07-01 09:12:04.259   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:12:04.269   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:12:04.269   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:12:04.269   770   788 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:12:04.269   770   788 D BatteryService: stay LED for fully charged
,07-01 09:12:04.279  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:12:04.279  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:12:04.279  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:12:04.309  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:12:04.309  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:12:04.309  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:12:04.829  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:04.849  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:04.849  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:04.919  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:12:04.919  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:12:04.919   305  1158 D EnterpriseController: netId is 0
07-01 09:12:04.919   305  1158 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,07-01 09:12:08.409   770   788 I ActivityManager: Killing 4962:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,07-01 09:12:08.509   770  1577 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,07-01 09:12:12.229   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:12.479   770  1581 E Watchdog: !@Sync 31 [07-01 09:12:12.495]
,07-01 09:12:22.289   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:32.339   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:34.319   770  1736 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:12:34.319   770  1736 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:12:34.329   770  1736 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:12:34.329   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:12:34.339   770   770 I MotionRecognitionService: Plugged
,07-01 09:12:34.339   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:12:34.349   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:12:34.349   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:12:34.349   770  1736 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:12:34.349   770  1736 D BatteryService: stay LED for fully charged
,07-01 09:12:34.369  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:12:34.369  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:12:34.369  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:12:34.399  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:12:34.399  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:12:34.409  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:12:42.399   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:42.499   770  1581 E Watchdog: !@Sync 32 [07-01 09:12:42.502]
,07-01 09:12:44.309  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:12:52.449   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:12:59.989   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:13:02.499   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:13:04.399   770  1721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:13:04.399   770  1721 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:13:04.409   770  1721 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:13:04.409   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:13:04.419   770   770 I MotionRecognitionService: Plugged
,07-01 09:13:04.419   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:13:04.429   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:13:04.429   770  1721 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-01 09:13:04.429   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:13:04.429   770  1721 D BatteryService: stay LED for fully charged
,07-01 09:13:04.449  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:13:04.449  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:13:04.449  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:13:04.469  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:13:04.469  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:13:04.469  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:13:12.489   770  1581 E Watchdog: !@Sync 33 [07-01 09:13:12.506]
,07-01 09:13:12.559   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-01 09:13:22.609   770  3348 D SSRM:n  : SIOP:: AP = 280, PST = 289, CUR = 450, LCD = 0,
,07-01 09:13:32.669   770  3348 D SSRM:n  : SIOP:: AP = 280, PST = 288, CUR = 450, LCD = 0
,07-01 09:13:34.479   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:13:34.479   770  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:13:34.479   770  1722 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:13:34.489   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:13:34.499   770   770 I MotionRecognitionService: Plugged
,07-01 09:13:34.499   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:13:34.499   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:13:34.509   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:13:34.509   770  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:13:34.509   770  1722 D BatteryService: stay LED for fully charged
,07-01 09:13:34.529  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:13:34.529  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:13:34.529  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:13:34.569  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:13:34.569  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:13:34.569  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:13:42.509   770  1581 E Watchdog: !@Sync 34 [07-01 09:13:42.512]
,07-01 09:13:42.729   770  3348 D SSRM:n  : SIOP:: AP = 280, PST = 287, CUR = 450, LCD = 0
,07-01 09:13:44.329  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:13:52.799   770  3348 D SSRM:n  : SIOP:: AP = 280, PST = 286, CUR = 450, LCD = 0
,07-01 09:14:02.849   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 284, CUR = 450, LCD = 0
,07-01 09:14:04.559   770   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:14:12.499   770  1581 E Watchdog: !@Sync 35 [07-01 09:14:12.516]
,07-01 09:14:12.909   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 282, CUR = 450, LCD = 0
,07-01 09:14:22.959   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 280, CUR = 450, LCD = 0
,07-01 09:14:33.019   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 278, CUR = 450, LCD = 0
,07-01 09:14:34.639   770  1410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:14:42.519   770  1581 E Watchdog: !@Sync 36 [07-01 09:14:42.521]
,07-01 09:14:43.069   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 276, CUR = 450, LCD = 0
,07-01 09:14:44.349  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:14:44.519  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 151ms lastUpdatedAfter : 161579ms
,07-01 09:14:53.129   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 274, CUR = 450, LCD = 0
,07-01 09:15:03.179   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 273, CUR = 450, LCD = 0
,07-01 09:15:04.719   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:15:04.719   770  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:15:04.719   770  1722 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:15:04.729   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:15:04.739   770   770 I MotionRecognitionService: Plugged
,07-01 09:15:04.739   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:15:04.739   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:15:04.749   770  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:15:04.749   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:15:04.749   770  1722 D BatteryService: stay LED for fully charged
,07-01 09:15:04.759  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:15:04.759  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:15:04.759  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:15:04.799  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:15:04.799  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:15:04.799  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:15:12.509   770  1581 E Watchdog: !@Sync 37 [07-01 09:15:12.525]
,07-01 09:15:13.239   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:15:23.299   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 271, CUR = 450, LCD = 0
,07-01 09:15:33.379   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:15:34.799   770  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:15:42.529   770  1581 E Watchdog: !@Sync 38 [07-01 09:15:42.531]
,07-01 09:15:43.439   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:15:44.519  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:15:53.489   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:16:03.539   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:16:04.879   770  4209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:16:04.879   770  4209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:16:04.889   770  4209 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:16:04.889   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:16:04.899   770   770 I MotionRecognitionService: Plugged
,07-01 09:16:04.899   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:16:04.899   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:16:04.909   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:16:04.909   770  4209 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-01 09:16:04.909   770  4209 D BatteryService: stay LED for fully charged
,07-01 09:16:04.929  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:16:04.929  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:16:04.929  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:16:04.969  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:16:04.969  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:16:04.969  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:16:12.529   770  1581 E Watchdog: !@Sync 39 [07-01 09:16:12.536]
,07-01 09:16:13.599   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:16:23.649   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:16:27.169   770  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 09:16:27.169   770  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 09:16:27.169   770  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 09:16:28.519   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 09:16:28.519   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 09:16:28.529   770  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:16:28.529   770  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:16:33.699   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 272, CUR = 450, LCD = 0
,07-01 09:16:34.959   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:16:34.959   770  1735 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:16:34.969   770  1735 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:16:34.969   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:16:34.979   770   770 I MotionRecognitionService: Plugged
,07-01 09:16:34.979   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:16:34.979   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:16:34.989   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:16:34.989   770  1735 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-01 09:16:34.999   770  1735 D BatteryService: stay LED for fully charged
,07-01 09:16:34.999  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:16:34.999  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:16:34.999  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:16:35.019  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:16:35.019  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:16:35.029  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:16:39.179   770   859 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 09:16:42.529   770  1581 E Watchdog: !@Sync 40 [07-01 09:16:42.541]
,07-01 09:16:43.759   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:16:44.549  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:16:53.809   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:17:03.869   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:17:05.049   770  1570 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:17:05.079  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:05.099  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:05.099  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:05.179  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 09:17:05.179  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:17:05.179   305  1158 D EnterpriseController: netId is 0
07-01 09:17:05.179   305  1158 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,07-01 09:17:05.269   770   779 I art     : Background partial concurrent mark sweep GC freed 60844(8MB) AllocSpace objects, 379(7MB) LOS objects, 27% free, 42MB/58MB, paused 2.790ms total 266.228ms
,07-01 09:17:12.529   770  1581 E Watchdog: !@Sync 41 [07-01 09:17:12.546]
,07-01 09:17:13.919   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 274, CUR = 450, LCD = 0
,07-01 09:17:23.989   770  3348 D SSRM:n  : SIOP:: AP = 280, PST = 275, CUR = 450, LCD = 0
,07-01 09:17:34.049   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 275, CUR = 450, LCD = 0
,07-01 09:17:35.109   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:17:42.549   770  1581 E Watchdog: !@Sync 42 [07-01 09:17:42.553]
,07-01 09:17:44.099   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 275, CUR = 450, LCD = 0
,07-01 09:17:44.559  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:17:44.779  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 203ms lastUpdatedAfter : 180266ms
,07-01 09:17:54.159   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 275, CUR = 450, LCD = 0
,07-01 09:18:04.209   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 275, CUR = 450, LCD = 0
,07-01 09:18:05.189   770  1577 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:18:12.549   770  1581 E Watchdog: !@Sync 43 [07-01 09:18:12.560]
,07-01 09:18:14.269   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 273, CUR = 450, LCD = 0
,07-01 09:18:24.329   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 273, CUR = 450, LCD = 0
,07-01 09:18:34.379   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 273, CUR = 450, LCD = 0
,07-01 09:18:35.269   770  1252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:18:35.269   770  1252 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:18:35.279   770  1252 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:18:35.279   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:18:35.289   770   770 I MotionRecognitionService: Plugged
,07-01 09:18:35.289   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:18:35.289   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:18:35.299   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:18:35.299   770  1252 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-01 09:18:35.299   770  1252 D BatteryService: stay LED for fully charged
,07-01 09:18:35.319  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:18:35.319  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:18:35.319  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:18:35.349  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:18:35.349  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:18:35.349  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:18:42.559   770  1581 E Watchdog: !@Sync 44 [07-01 09:18:42.564]
,07-01 09:18:44.439   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 273, CUR = 450, LCD = 0
,07-01 09:18:44.789  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:18:54.499   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 271, CUR = 450, LCD = 0
,07-01 09:19:04.559   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:19:05.349   770   789 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:19:05.349   770   789 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:19:05.359   770   789 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:19:05.359   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:19:05.369   770   770 I MotionRecognitionService: Plugged
,07-01 09:19:05.369   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:19:05.369   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:19:05.379   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:19:05.379   770   789 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-01 09:19:05.379   770   789 D BatteryService: stay LED for fully charged
,07-01 09:19:05.389  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:19:05.389  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:19:05.399  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:19:05.429  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:19:05.429  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:19:05.429  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:19:12.569   770  1581 E Watchdog: !@Sync 45 [07-01 09:19:12.571]
,07-01 09:19:14.619   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:19:24.669   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:19:34.729   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:19:35.429   770  1735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:19:35.429   770  1735 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:19:35.429   770  1735 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:19:35.439   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:19:35.449   770   770 I MotionRecognitionService: Plugged
,07-01 09:19:35.449   770   770 D MotionRecognitionService:   cableConnection= 1
07-01 09:19:35.449   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:19:35.449   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:19:35.459   770  1735 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-01 09:19:35.459   770  1735 D BatteryService: stay LED for fully charged
,07-01 09:19:35.469  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:19:35.479  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:19:35.479  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:19:35.499  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:19:35.499  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:19:35.499  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:19:42.559   770  1581 E Watchdog: !@Sync 46 [07-01 09:19:42.575]
,07-01 09:19:44.799   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:19:44.809  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:19:54.849   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:20:04.899   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:20:05.509   770  1736 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:20:12.569   770  1581 E Watchdog: !@Sync 47 [07-01 09:20:12.581]
,07-01 09:20:14.949   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:20:25.009   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:20:35.059   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:20:35.589   770  1701 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:20:35.589   770  1701 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:20:35.589   770  1701 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:20:35.599   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:20:35.609   770   770 I MotionRecognitionService: Plugged
,07-01 09:20:35.609   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:20:35.609   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:20:35.609   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:20:35.619   770  1701 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:20:35.619   770  1701 D BatteryService: stay LED for fully charged
,07-01 09:20:35.629  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:20:35.629  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:20:35.629  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:20:35.649  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:20:35.649  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:20:35.659  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:20:42.569   770  1581 E Watchdog: !@Sync 48 [07-01 09:20:42.585]
,07-01 09:20:44.839  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:20:44.989  1670  1761 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 146ms lastUpdatedAfter : 180212ms
,07-01 09:20:45.119   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:20:55.169   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:21:05.219   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:21:05.669   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:21:05.669   770  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:21:05.669   770  1722 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:21:05.679   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:21:05.689   770   770 I MotionRecognitionService: Plugged
,07-01 09:21:05.689   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:21:05.689   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-01 09:21:05.699   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:21:05.699   770  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-01 09:21:05.699   770  1722 D BatteryService: stay LED for fully charged
,07-01 09:21:05.719  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:21:05.719  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:21:05.719  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:21:05.749  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:21:05.749  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:21:05.749  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:21:12.589   770  1581 E Watchdog: !@Sync 49 [07-01 09:21:12.591]
,07-01 09:21:15.279   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:21:25.329   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 270, CUR = 450, LCD = 0
,07-01 09:21:27.169   770  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 09:21:27.169   770  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 09:21:27.169   770  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 09:21:30.239   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 09:21:30.239   770  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 09:21:30.249   770  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:21:30.249   770  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:21:35.389   770  3348 D SSRM:n  : SIOP:: AP = 290, PST = 272, CUR = 450, LCD = 0
,07-01 09:21:35.749   770  1721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:21:42.579   770  1581 E Watchdog: !@Sync 50 [07-01 09:21:42.595]
,07-01 09:21:44.999  1670  1761 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-01 09:21:45.479   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:21:46.339   770  2329 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-01 09:21:46.339   770  2329 V MARsPolicyManager: updateSMDBValues
,07-01 09:21:46.339   770   905 E MARsDBManager: updateDBAll : begin --size 0
,07-01 09:21:46.339   770   905 E MARsDBManager: updateDBAll : end
,07-01 09:21:55.539   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:22:02.969   770  1236 V AlarmManager: Expired Alarm result :8
,07-01 09:22:05.319   770  4209 I ActivityManager: Killing 6726:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 737s, lastActivityTime 737s
,07-01 09:22:05.319   770  4209 I ActivityManager: Killing 6666:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 738s, lastActivityTime 738s
,07-01 09:22:05.319   770  4209 I ActivityManager: Killing 6623:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 889s, lastActivityTime 889s
,07-01 09:22:05.319   770  4209 I ActivityManager: Killing 6609:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 899s, lastActivityTime 899s
,07-01 09:22:05.339  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:22:05.359  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:22:05.369  2077  2077 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:22:05.379   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-01 09:22:05.379   378  5014 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-01 09:22:05.379   378  5014 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:22:05.379   770  4209 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-01 09:22:05.379   770  4209 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-01 09:22:05.389   770  4209 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-01 09:22:05.419   770  1735 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-01 09:22:05.419   770  1735 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
,07-01 09:22:05.419   770  1735 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10966ms
,07-01 09:22:05.429   770  1722 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-01 09:22:05.429   770  1722 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-01 09:22:05.429   770  1722 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20957ms
,07-01 09:22:05.429   770  1570 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-01 09:22:05.429   770  1570 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,07-01 09:22:05.429   770  1570 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 30951ms
,07-01 09:22:05.449  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 09:22:05.449  4846  4882 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:22:05.449   305  1158 D EnterpriseController: netId is 0
07-01 09:22:05.449   305  1158 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,07-01 09:22:05.589   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:22:05.839   770  1722 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:22:05.849   770  1722 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-01 09:22:05.849   770  1722 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-01 09:22:05.849   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:22:05.859   770   770 I MotionRecognitionService: Plugged
,07-01 09:22:05.859   770   770 D MotionRecognitionService:   cableConnection= 1
,07-01 09:22:05.869   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-01 09:22:05.869   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-01 09:22:05.869   770  1722 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-01 09:22:05.869   770  1722 D BatteryService: stay LED for fully charged
,07-01 09:22:05.869  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:22:05.869  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:22:05.869  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:22:05.899  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:22:05.899  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:22:05.899  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:22:06.379   378  5014 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:22:06.459   770   865 I ActivityManager: Start proc 6899:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-01 09:22:06.469  6899  6899 E Zygote  : v2
,07-01 09:22:06.469  6899  6899 I libpersona: KNOX_SDCARD checking this for 1000
07-01 09:22:06.469  6899  6899 I libpersona: KNOX_SDCARD not a persona
,07-01 09:22:06.479  6899  6899 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-01 09:22:06.479  6899  6899 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:22:06.479  6899  6899 E Zygote  : accessInfo : 0
,07-01 09:22:06.529  6899  6899 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:22:06.529  6899  6899 D ActivityThread: Added TimaKeyStore provider
,07-01 09:22:06.549  6899  6899 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-01 09:22:06.559  6899  6899 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-01 09:22:06.559  6899  6899 D AtFwdService: onCreate method
,07-01 09:22:06.559  6899  6899 I AtFwdService: Instantiate AtCmdFwd Service
,07-01 09:22:06.579  6899  6911 D AtCkpdCmdHandler: De-queing command
,07-01 09:22:12.589   770  1581 E Watchdog: !@Sync 51 [07-01 09:22:12.599]
,07-01 09:22:15.639   770  3348 D SSRM:n  : SIOP:: AP = 270, PST = 272, CUR = 450, LCD = 0
,07-01 09:22:16.459   770   865 I ActivityManager: Start proc 6913:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-01 09:22:16.469  6913  6913 E Zygote  : v2
,07-01 09:22:16.469  6913  6913 I libpersona: KNOX_SDCARD checking this for 10026
,07-01 09:22:16.469  6913  6913 I libpersona: KNOX_SDCARD not a persona
,07-01 09:22:16.469  6913  6913 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 09:22:16.469  6913  6913 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-01 09:22:16.479  6913  6913 E Zygote  : accessInfo : 0
,07-01 09:22:16.479  6913  6913 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-01 09:22:16.519  6913  6913 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:22:16.519  6913  6913 D ActivityThread: Added TimaKeyStore provider
,07-01 09:22:16.539  6913  6913 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-01 09:22:16.559  6913  6913 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-01 09:22:16.569  6913  6913 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-01 09:22:16.569  6913  6913 D ContextualPageNotification: resetAllNotification : all clear!!!
,TIME-OUT KILL (timeout was 1400000ms),07-01 09:22:20.929  2238  2238 E audit   : type=1400 msg=audit(1467357740.929:284): avc:  denied  { execmod } for  pid=6926 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-01 09:22:20.929  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 09:22:20.929  2238  2238 E audit   : type=1300 msg=audit(1467357740.929:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4005000 a1=51000 a2=5 a3=4 items=0 ppid=3489 ppcomm=adbd pid=6926 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-01 09:22:20.929  2238  2238 E audit   : type=1327 msg=audit(1467357740.929:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-01 09:22:20.929  2238  2238 E audit   : type=1320 msg=audit(1467357740.929:284): 
07-01 09:22:20.989  2238  2238 E audit   : type=1400 msg=audit(1467357740.989:285): avc:  denied  { execmod } for  pid=6926 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-01 09:22:20.989  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 09:22:20.989  2238  2238 E audit   : type=1300 msg=audit(1467357740.989:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc8000 a1=51000 a2=5 a3=4 items=0 ppid=3489 ppcomm=adbd pid=6926 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-01 09:22:20.999  2238  2238 E audit   : type=1327 msg=audit(1467357740.989:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-01 09:22:20.999  2238  2238 E audit   : type=1320 msg=audit(1467357740.989:285): 
07-01 09:22:21.039  2238  2238 E audit   : type=1400 msg=audit(1467357741.039:286): avc:  denied  { execmod } for  pid=6926 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-01 09:22:21.039  2238  2238 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-01 09:22:21.039  2238  2238 E audit   : type=1300 msg=audit(1467357741.039:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc8000 a1=51000 a2=5 a3=4 items=0 ppid=3489 ppcomm=adbd pid=6926 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-01 09:22:21.039  2238  2238 E audit   : type=1327 msg=audit(1467357741.039:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-01 09:22:21.039  2238  2238 E audit   : type=1320 msg=audit(1467357741.039:286): 
07-01 09:22:21.049  6926  6926 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-01 09:22:21.049  6926  6926 D AndroidRuntime: CheckJNI is OFF
07-01 09:22:21.049  6926  6926 D AndroidRuntime: readGMSProperty: start
07-01 09:22:21.049  6926  6926 D AndroidRuntime: readGMSProperty: already setted!!
07-01 09:22:21.049  6926  6926 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 09:22:21.049  6926  6926 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 09:22:21.049  6926  6926 D AndroidRuntime: readGMSProperty: end
07-01 09:22:21.049  6926  6926 D AndroidRuntime: addProductProperty: start
07-01 09:22:21.059  6926  6926 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-01 09:22:21.059  6926  6926 W art     : aee2c000-b1d52000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-01 09:22:21.059  6926  6926 W art     : b1d52000-b3fc1000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-01 09:22:21.059  6926  6926 W art     : b3fc1000-b3fc2000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-01 09:22:21.059  6926  6926 W art     : b3fc2000-b3fc3000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.069  6926  6926 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-01 09:22:21.069  6926  6926 W art     : b4323000-b4771000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-01 09:22:21.069  6926  6926 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b4772000-b477c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-01 09:22:21.069  6926  6926 W art     : b477c000-b477d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-01 09:22:21.069  6926  6926 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-01 09:22:21.069  6926  6926 W art     : b4896000-b4899000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-01 09:22:21.069  6926  6926 W art     : b4899000-b489a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-01 09:22:21.069  6926  6926 W art     : b489a000-b489b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-01 09:22:21.069  6926  6926 W art     : b489b000-b489c000 r--p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b489c000-b48bc000 r--s 00000000 00:0b 8200       /dev/__properties__
07-01 09:22:21.069  6926  6926 W art     : b48bc000-b52cd000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-01 09:22:21.069  6926  6926 W art     : b52cd000-b52ce000 ---p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b52ce000-b5317000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-01 09:22:21.069  6926  6926 W art     : b5317000-b5318000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-01 09:22:21.069  6926  6926 W art     : b5318000-b5320000 rw-p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b5320000-b5321000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.069  6926  6926 W art     : b5321000-b5356000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-01 09:22:21.069  6926  6926 W art     : b5356000-b5357000 ---p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b5357000-b5358000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-01 09:22:21.069  6926  6926 W art     : b5358000-b5359000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-01 09:22:21.069  6926  6926 W art     : b5359000-b53b1000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-01 09:22:21.069  6926  6926 W art     : b53b1000-b53b2000 ---p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b53b2000-b53b3000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-01 09:22:21.069  6926  6926 W art     : b53b3000-b53b4000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-01 09:22:21.069  6926  6926 W art     : b53b5000-b53bb000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-01 09:22:21.069  6926  6926 W art     : b53bb000-b53bc000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-01 09:22:21.069  6926  6926 W art     : b53bc000-b53bd000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-01 09:22:21.069  6926  6926 W art     : b53bd000-b53bf000 rw-p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b53c0000-b53ca000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-01 09:22:21.069  6926  6926 W art     : b53ca000-b53cd000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-01 09:22:21.069  6926  6926 W art     : b53cd000-b53ce000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-01 09:22:21.069  6926  6926 W art     : b53cf000-b53e6000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-01 09:22:21.069  6926  6926 W art     : b53e6000-b53e7000 ---p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b53e7000-b53e8000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-01 09:22:21.069  6926  6926 W art     : b53e8000-b53e9000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-01 09:22:21.069  6926  6926 W art     : b53ea000-b53f4000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-01 09:22:21.069  6926  6926 W art     : b53f4000-b53f5000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-01 09:22:21.069  6926  6926 W art     : b53f5000-b53f6000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-01 09:22:21.069  6926  6926 W art     : b53f6000-b53fa000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-01 09:22:21.069  6926  6926 W art     : b53fa000-b53fb000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-01 09:22:21.069  6926  6926 W art     : b53fb000-b53fc000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-01 09:22:21.069  6926  6926 W art     : b53fc000-b5412000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-01 09:22:21.069  6926  6926 W art     : b5412000-b5413000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-01 09:22:21.069  6926  6926 W art     : b5413000-b5414000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-01 09:22:21.069  6926  6926 W art     : b5414000-b5421000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-01 09:22:21.069  6926  6926 W art     : b5421000-b5422000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-01 09:22:21.069  6926  6926 W art     : b5422000-b5423000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-01 09:22:21.069  6926  6926 W art     : b5423000-b5483000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-01 09:22:21.069  6926  6926 W art     : b5483000-b5486000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-01 09:22:21.069  6926  6926 W art     : b5486000-b548a000 rw-p 00000000 00:00 0 
07-01 09:22:21.069  6926  6926 W art     : b548a000-b54eb000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-01 09:22:21.069  6926  6926 W art     : b54eb000-b54ec000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-01 09:22:21.069  6926  6926 W art     : b54ec000-b553b000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-01 09:22:21.069  6926  6926 W art     : b553b000-b553d000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-01 09:22:21.069  6926  6926 W art     : b553d000-b553e000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-01 09:22:21.069  6926  6926 W art     : b553e000-b553f000 rw-p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b553f000-b5546000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-01 09:22:21.079  6926  6926 W art     : b5546000-b5547000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-01 09:22:21.079  6926  6926 W art     : b5547000-b5548000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-01 09:22:21.079  6926  6926 W art     : b5549000-b554c000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-01 09:22:21.079  6926  6926 W art     : b554c000-b554d000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-01 09:22:21.079  6926  6926 W art     : b554d000-b554e000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-01 09:22:21.079  6926  6926 W art     : b554f000-b5553000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-01 09:22:21.079  6926  6926 W art     : b5553000-b5554000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5554000-b5555000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-01 09:22:21.079  6926  6926 W art     : b5555000-b5556000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-01 09:22:21.079  6926  6926 W art     : b5557000-b5574000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-01 09:22:21.079  6926  6926 W art     : b5574000-b5575000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-01 09:22:21.079  6926  6926 W art     : b5575000-b5576000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-01 09:22:21.079  6926  6926 W art     : b5577000-b557c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-01 09:22:21.079  6926  6926 W art     : b557c000-b557d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-01 09:22:21.079  6926  6926 W art     : b557d000-b557e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-01 09:22:21.079  6926  6926 W art     : b557f000-b55b0000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-01 09:22:21.079  6926  6926 W art     : b55b0000-b55b3000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-01 09:22:21.079  6926  6926 W art     : b55b3000-b55b4000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-01 09:22:21.079  6926  6926 W art     : b55b5000-b55f0000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-01 09:22:21.079  6926  6926 W art     : b55f0000-b55f1000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-01 09:22:21.079  6926  6926 W art     : b55f1000-b55f2000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-01 09:22:21.079  6926  6926 W art     : b55f3000-b55fa000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-01 09:22:21.079  6926  6926 W art     : b55fa000-b55fb000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b55fb000-b55fc000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-01 09:22:21.079  6926  6926 W art     : b55fc000-b55fd000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-01 09:22:21.079  6926  6926 W art     : b55fd000-b55fe000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.079  6926  6926 W art     : b55fe000-b5615000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-01 09:22:21.079  6926  6926 W art     : b5615000-b5616000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5616000-b5619000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-01 09:22:21.079  6926  6926 W art     : b5619000-b561a000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-01 09:22:21.079  6926  6926 W art     : b561a000-b5639000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-01 09:22:21.079  6926  6926 W art     : b5639000-b563a000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-01 09:22:21.079  6926  6926 W art     : b563a000-b563b000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-01 09:22:21.079  6926  6926 W art     : b563b000-b5679000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-01 09:22:21.079  6926  6926 W art     : b5679000-b567a000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b567a000-b567c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-01 09:22:21.079  6926  6926 W art     : b567c000-b567d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-01 09:22:21.079  6926  6926 W art     : b567e000-b5685000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-01 09:22:21.079  6926  6926 W art     : b5685000-b5686000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-01 09:22:21.079  6926  6926 W art     : b5686000-b5687000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-01 09:22:21.079  6926  6926 W art     : b5688000-b568b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-01 09:22:21.079  6926  6926 W art     : b568b000-b568c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-01 09:22:21.079  6926  6926 W art     : b568c000-b568d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-01 09:22:21.079  6926  6926 W art     : b568d000-b5693000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-01 09:22:21.079  6926  6926 W art     : b5693000-b5694000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5694000-b5695000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-01 09:22:21.079  6926  6926 W art     : b5695000-b5696000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-01 09:22:21.079  6926  6926 W art     : b5696000-b569f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-01 09:22:21.079  6926  6926 W art     : b569f000-b56a0000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-01 09:22:21.079  6926  6926 W art     : b56a0000-b56a1000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-01 09:22:21.079  6926  6926 W art     : b56a1000-b5732000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-01 09:22:21.079  6926  6926 W art     : b5732000-b5733000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5733000-b573e000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-01 09:22:21.079  6926  6926 W art     : b573e000-b573f000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-01 09:22:21.079  6926  6926 W art     : b5740000-b5752000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-01 09:22:21.079  6926  6926 W art     : b5752000-b5753000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-01 09:22:21.079  6926  6926 W art     : b5753000-b5754000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-01 09:22:21.079  6926  6926 W art     : b5755000-b575a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-01 09:22:21.079  6926  6926 W art     : b575a000-b575b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-01 09:22:21.079  6926  6926 W art     : b575b000-b575c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-01 09:22:21.079  6926  6926 W art     : b575d000-b57ca000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-01 09:22:21.079  6926  6926 W art     : b57ca000-b57cb000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b57cb000-b57cd000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-01 09:22:21.079  6926  6926 W art     : b57cd000-b57ce000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-01 09:22:21.079  6926  6926 W art     : b57ce000-b57cf000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.079  6926  6926 W art     : b57cf000-b57d6000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-01 09:22:21.079  6926  6926 W art     : b57d6000-b57d7000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-01 09:22:21.079  6926  6926 W art     : b57d7000-b57d8000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-01 09:22:21.079  6926  6926 W art     : b57d9000-b5859000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-01 09:22:21.079  6926  6926 W art     : b5859000-b585a000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b585a000-b585b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-01 09:22:21.079  6926  6926 W art     : b585b000-b585c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-01 09:22:21.079  6926  6926 W art     : b585c000-b5873000 rw-p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5873000-b58aa000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-01 09:22:21.079  6926  6926 W art     : ib/libqc-opt.so
07-01 09:22:21.079  6926  6926 W art     : b58aa000-b58ab000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-01 09:22:21.079  6926  6926 W art     : b58ab000-b58ac000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-01 09:22:21.079  6926  6926 W art     : b58ac000-b58c8000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-01 09:22:21.079  6926  6926 W art     : b58c8000-b58c9000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-01 09:22:21.079  6926  6926 W art     : b58c9000-b58ca000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-01 09:22:21.079  6926  6926 W art     : b58cb000-b592c000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-01 09:22:21.079  6926  6926 W art     : b592c000-b592e000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-01 09:22:21.079  6926  6926 W art     : b592e000-b592f000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-01 09:22:21.079  6926  6926 W art     : b5930000-b5957000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-01 09:22:21.079  6926  6926 W art     : b5957000-b5958000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5958000-b5959000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-01 09:22:21.079  6926  6926 W art     : b5959000-b595a000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-01 09:22:21.079  6926  6926 W art     : b595b000-b5963000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-01 09:22:21.079  6926  6926 W art     : b5963000-b5965000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-01 09:22:21.079  6926  6926 W art     : b5965000-b5966000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-01 09:22:21.079  6926  6926 W art     : b5967000-b596a000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-01 09:22:21.079  6926  6926 W art     : b596a000-b596b000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-01 09:22:21.079  6926  6926 W art     : b596b000-b596c000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-01 09:22:21.079  6926  6926 W art     : b596c000-b5970000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-01 09:22:21.079  6926  6926 W art     : b5970000-b5971000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b5971000-b5972000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-01 09:22:21.079  6926  6926 W art     : b5972000-b5973000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-01 09:22:21.079  6926  6926 W art     : b5973000-b5983000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-01 09:22:21.079  6926  6926 W art     : b5983000-b5984000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-01 09:22:21.079  6926  6926 W art     : b5984000-b5985000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-01 09:22:21.079  6926  6926 W art     : b5985000-b59cb000 rw-p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b59cb000-b59d4000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-01 09:22:21.079  6926  6926 W art     : b59d4000-b59d5000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-01 09:22:21.079  6926  6926 W art     : b59d5000-b59d6000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-01 09:22:21.079  6926  6926 W art     : b59d7000-b59dc000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-01 09:22:21.079  6926  6926 W art     : b59dc000-b59dd000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-01 09:22:21.079  6926  6926 W art     : b59dd000-b59de000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-01 09:22:21.079  6926  6926 W art     : b59de000-b59e1000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-01 09:22:21.079  6926  6926 W art     : b59e1000-b59e2000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b59e2000-b59e3000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-01 09:22:21.079  6926  6926 W art     : b59e3000-b59e4000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-01 09:22:21.079  6926  6926 W art     : b59e5000-b59fd000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-01 09:22:21.079  6926  6926 W art     : b59fd000-b59fe000 ---p 00000000 00:00 0 
07-01 09:22:21.079  6926  6926 W art     : b59fe000-b59ff000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-01 09:22:21.079  6926  6926 W art     : b59ff000-b5a00000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-01 09:22:21.079  6926  6926 W art     : b5a01000-b5b9b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-01 09:22:21.089  6926  6926 W art     : b5b9b000-b5b9c000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5b9c000-b5ba9000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-01 09:22:21.089  6926  6926 W art     : b5ba9000-b5baa000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-01 09:22:21.089  6926  6926 W art     : b5baa000-b5bae000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-01 09:22:21.089  6926  6926 W art     : b5bae000-b5baf000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5baf000-b5bb0000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-01 09:22:21.089  6926  6926 W art     : b5bb0000-b5bb1000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-01 09:22:21.089  6926  6926 W art     : b5bb1000-b5bc4000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-01 09:22:21.089  6926  6926 W art     : b5bc4000-b5bc5000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-01 09:22:21.089  6926  6926 W art     : b5bc5000-b5bc6000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-01 09:22:21.089  6926  6926 W art     : b5bc7000-b5c12000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-01 09:22:21.089  6926  6926 W art     : b5c12000-b5c13000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-01 09:22:21.089  6926  6926 W art     : b5c13000-b5c14000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-01 09:22:21.089  6926  6926 W art     : b5c14000-b5c16000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5c16000-b5c17000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 09:22:21.089  6926  6926 W art     : b5c17000-b5c28000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-01 09:22:21.089  6926  6926 W art     : b5c28000-b5c29000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5c29000-b5c2a000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-01 09:22:21.089  6926  6926 W art     : b5c2a000-b5c2b000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-01 09:22:21.089  6926  6926 W art     : b5c2c000-b5c36000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-01 09:22:21.089  6926  6926 W art     : b5c36000-b5c38000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-01 09:22:21.089  6926  6926 W art     : b5c38000-b5c39000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-01 09:22:21.089  6926  6926 W art     : b5c39000-b5c52000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-01 09:22:21.089  6926  6926 W art     : b5c52000-b5c53000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-01 09:22:21.089  6926  6926 W art     : b5c53000-b5c56000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-01 09:22:21.089  6926  6926 W art     : b5c56000-b5c5a000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5c5a000-b5cce000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-01 09:22:21.089  6926  6926 W art     : b5cce000-b5ccf000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5ccf000-b5cd2000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-01 09:22:21.089  6926  6926 W art     : b5cd2000-b5cd3000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-01 09:22:21.089  6926  6926 W art     : b5cd4000-b5cd7000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-01 09:22:21.089  6926  6926 W art     : b5cd7000-b5cd8000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-01 09:22:21.089  6926  6926 W art     : b5cd8000-b5cd9000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-01 09:22:21.089  6926  6926 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5cda000-b5cdf000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-01 09:22:21.089  6926  6926 W art     : b5cdf000-b5ce0000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-01 09:22:21.089  6926  6926 W art     : b5ce0000-b5ce1000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-01 09:22:21.089  6926  6926 W art     : b5ce1000-b5ce2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b5ce2000-b5ce5000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-01 09:22:21.089  6926  6926 W art     : b5ce5000-b5ce6000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-01 09:22:21.089  6926  6926 W art     : b5ce6000-b5ce7000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-01 09:22:21.089  6926  6926 W art     : b5ce7000-b5ce8000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b5ce8000-b5cec000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-01 09:22:21.089  6926  6926 W art     : b5cec000-b5ced000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-01 09:22:21.089  6926  6926 W art     : b5ced000-b5cee000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-01 09:22:21.089  6926  6926 W art     : b5cee000-b5cef000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 09:22:21.089  6926  6926 W art     : b5cef000-b5cf3000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-01 09:22:21.089  6926  6926 W art     : b5cf3000-b5cf4000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-01 09:22:21.089  6926  6926 W art     : b5cf4000-b5cf5000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-01 09:22:21.089  6926  6926 W art     : b5cf5000-b5cf6000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b5cf6000-b5d04000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-01 09:22:21.089  6926  6926 W art     : b5d04000-b5d05000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b5d05000-b5d06000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-01 09:22:21.089  6926  6926 W art     : b5d06000-b5d07000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-01 09:22:21.089  6926  6926 W art     : b5d07000-b5d11000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-01 09:22:21.089  6926  6926 W art     : b5d11000-b5d14000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-01 09:22:21.089  6926  6926 W art     : b5d14000-b5d15000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-01 09:22:21.089  6926  6926 W art     : b5d15000-b5d16000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b5d16000-b5d20000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-01 09:22:21.089  6926  6926 W art     : b5d20000-b5d23000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-01 09:22:21.089  6926  6926 W art     : b5d23000-b5d24000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-01 09:22:21.089  6926  6926 W art     : b5d24000-b5d28000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-01 09:22:21.089  6926  6926 W art     : b5d28000-b5d29000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-01 09:22:21.089  6926  6926 W art     : b5d29000-b5d2a000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-01 09:22:21.089  6926  6926 W art     : b5d2a000-b5d2b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b5d2b000-b5d38000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-01 09:22:21.089  6926  6926 W art     : b5d38000-b5d3a000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-01 09:22:21.089  6926  6926 W art     : b5d3a000-b5d3b000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-01 09:22:21.089  6926  6926 W art     : b5d3b000-b614d000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-01 09:22:21.089  6926  6926 W art     : b614d000-b614e000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b614e000-b6157000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-01 09:22:21.089  6926  6926 W art     : b6157000-b615b000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-01 09:22:21.089  6926  6926 W art     : b615b000-b615c000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b615c000-b6163000 r-xp 00000000 b3:17 2571       /system/lib/libaud
07-01 09:22:21.089  6926  6926 W art     : ioutils.so
07-01 09:22:21.089  6926  6926 W art     : b6163000-b6164000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-01 09:22:21.089  6926  6926 W art     : b6164000-b6165000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-01 09:22:21.089  6926  6926 W art     : b6165000-b6166000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b6166000-b6181000 r-xp 00000000
07-01 09:22:21.089  6926  6926 W art     :  b3:17 1184       /system/lib/libz.so
07-01 09:22:21.089  6926  6926 W art     : b6181000-b6182000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-01 09:22:21.089  6926  6926 W art     : b6182000-b6183000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-01 09:22:21.089  6926  6926 W art     : b6183000-b6184000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b6184000-b61d0000 r-xp 00000000 b3:17 994        
07-01 09:22:21.089  6926  6926 W art     : /system/lib/libharfbuzz_ng.so
07-01 09:22:21.089  6926  6926 W art     : b61d0000-b61d1000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b61d1000-b61d2000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-01 09:22:21.089  6926  6926 W art     : b61d2000-b61d3000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-01 09:22:21.089  6926  6926 W art     : b61d3000-b61d4000 r--p 00000000 00:00 0          [anon:li
07-01 09:22:21.089  6926  6926 W art     : nker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b61d4000-b61d8000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-01 09:22:21.089  6926  6926 W art     : b61d8000-b61d9000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b61d9000-b61da000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-01 09:22:21.089  6926  6926 W art     : b61da000-b61db000 rw-p 00005000 b3:17 2681       /system/lib/libu
07-01 09:22:21.089  6926  6926 W art     : sbhost.so
07-01 09:22:21.089  6926  6926 W art     : b61db000-b6213000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-01 09:22:21.089  6926  6926 W art     : b6213000-b6214000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-01 09:22:21.089  6926  6926 W art     : b6214000-b6215000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-01 09:22:21.089  6926  6926 W art     : b6215000-b6216000 r--p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     :          [anon:linker_alloc]
07-01 09:22:21.089  6926  6926 W art     : b6216000-b62b4000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-01 09:22:21.089  6926  6926 W art     : b62b4000-b62b5000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b62b5000-b62d3000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-01 09:22:21.089  6926  6926 W art     : b62d3000-b62d4000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
07-01 09:22:21.089  6926  6926 W art     : .so
07-01 09:22:21.089  6926  6926 W art     : b62d4000-b6447000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-01 09:22:21.089  6926  6926 W art     : b6447000-b6452000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-01 09:22:21.089  6926  6926 W art     : b6452000-b6453000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-01 09:22:21.089  6926  6926 W art     : b6453000-b656a000 r-xp 00000000
07-01 09:22:21.089  6926  6926 W art     :  b3:17 2041       /system/lib/libicuuc.so
07-01 09:22:21.089  6926  6926 W art     : b656a000-b6575000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-01 09:22:21.089  6926  6926 W art     : b6575000-b6576000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-01 09:22:21.089  6926  6926 W art     : b6576000-b657a000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b657a000-b659e000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
07-01 09:22:21.089  6926  6926 W art     : o
07-01 09:22:21.089  6926  6926 W art     : b659e000-b65a0000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-01 09:22:21.089  6926  6926 W art     : b65a0000-b65a1000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-01 09:22:21.089  6926  6926 W art     : b65a1000-b6647000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-01 09:22:21.089  6926  6926 W art     : b6647000-b6654000 r--p 000a5000 b3:17 13
07-01 09:22:21.089  6926  6926 W art     : 2        /system/lib/libcrypto.so
07-01 09:22:21.089  6926  6926 W art     : b6654000-b6655000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-01 09:22:21.089  6926  6926 W art     : b6655000-b6656000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b6656000-b66a9000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-01 09:22:21.089  6926  6926 W art     : b66a9000-b66aa000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b66aa000-b66ab000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-01 09:22:21.089  6926  6926 W art     : b66ab000-b66ac000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-01 09:22:21.089  6926  6926 W art     : b66ac000-b66b1000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b66b1000-b66c3000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-01 09:22:21.089  6926  6926 W art     : b66c3000-b66c4000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b66c4000-b66c5000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-01 09:22:21.089  6926  6926 W art     : b66c5000-b66c6000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-01 09:22:21.089  6926  6926 W art     : b66c6000-b66cd000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-01 09:22:21.089  6926  6926 W art     : b66cd000-b66ce000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-01 09:22:21.089  6926  6926 W art     : b66ce000-b66cf000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-01 09:22:21.089  6926  6926 W art     : b66cf000-b66d0000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b66d0000-b66d3000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-01 09:22:21.089  6926  6926 W art     : b66d3000-b66d4000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-01 09:22:21.089  6926  6926 W art     : b66d4000-b66d5000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-01 09:22:21.089  6926  6926 W art     : b66d5000-b66d9000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-01 09:22:21.089  6926  6926 W art     : b66d9000-b66da000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-01 09:22:21.089  6926  6926 W art     : b66da000-b66db000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-01 09:22:21.089  6926  6926 W art     : b66db000-b66e9000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-01 09:22:21.089  6926  6926 W art     : b66e9000-b66ea000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b66ea000-b66eb000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-01 09:22:21.089  6926  6926 W art     : b66eb000-b66ec000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-01 09:22:21.089  6926  6926 W art     : b66ec000-b66f5000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-01 09:22:21.089  6926  6926 W art     : b66f5000-b66f6000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-01 09:22:21.089  6926  6926 W art     : b66f6000-b66f7000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-01 09:22:21.089  6926  6926 W art     : b66f7000-b675d000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-01 09:22:21.089  6926  6926 W art     : b675d000-b675e000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b675e000-b6760000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-01 09:22:21.089  6926  6926 W art     : b6760000-b6769000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-01 09:22:21.089  6926  6926 W art     : b6769000-b676c000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b676c000-b6803000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-01 09:22:21.089  6926  6926 W art     : b6803000-b6805000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-01 09:22:21.089  6926  6926 W art     : b6805000-b6806000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-01 09:22:21.089  6926  6926 W art     : b6806000-b6807000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b6807000-b6b28000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-01 09:22:21.089  6926  6926 W art     : b6b28000-b6b29000 ---p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b6b29000-b6b44000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-01 09:22:21.089  6926  6926 W art     : b6b44000-b6b48000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-01 09:22:21.089  6926  6926 W art     : b6b48000-b6b4d000 rw-p 00000000 00:00 0 
07-01 09:22:21.089  6926  6926 W art     : b6b4d000-b6b55000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-01 09:22:21.099  6926  6926 W art     : b6b55000-b6b56000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-01 09:22:21.099  6926  6926 W art     : b6b56000-b6b57000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-01 09:22:21.099  6926  6926 W art     : b6b57000-b6b85000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-01 09:22:21.099  6926  6926 W art     : b6b85000-b6b86000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6b86000-b6b8d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-01 09:22:21.099  6926  6926 W art     : b6b8d000-b6b8e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-01 09:22:21.099  6926  6926 W art     : b6b8e000-b6bd4000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-01 09:22:21.099  6926  6926 W art     : b6bd4000-b6bd5000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6bd5000-b6bd8000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-01 09:22:21.099  6926  6926 W art     : b6bd8000-b6bd9000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-01 09:22:21.099  6926  6926 W art     : b6bd9000-b6bf4000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-01 09:22:21.099  6926  6926 W art     : b6bf4000-b6bf8000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-01 09:22:21.099  6926  6926 W art     : b6bf8000-b6bf9000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-01 09:22:21.099  6926  6926 W art     : b6bf9000-b6c46000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-01 09:22:21.099  6926  6926 W art     : b6c46000-b6c47000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6c47000-b6c53000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-01 09:22:21.099  6926  6926 W art     : b6c53000-b6c54000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-01 09:22:21.099  6926  6926 W art     : b6c54000-b6c61000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-01 09:22:21.099  6926  6926 W art     : b6c61000-b6c62000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6c62000-b6c63000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-01 09:22:21.099  6926  6926 W art     : b6c63000-b6c64000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-01 09:22:21.099  6926  6926 W art     : b6c64000-b6c6c000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-01 09:22:21.099  6926  6926 W art     : b6c6c000-b6c6d000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6c6d000-b6c6e000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-01 09:22:21.099  6926  6926 W art     : b6c6e000-b6c6f000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-01 09:22:21.099  6926  6926 W art     : b6c6f000-b6c76000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-01 09:22:21.099  6926  6926 W art     : b6c76000-b6c77000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-01 09:22:21.099  6926  6926 W art     : b6c77000-b6c78000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-01 09:22:21.099  6926  6926 W art     : b6c78000-b6c8c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-01 09:22:21.099  6926  6926 W art     : b6c8c000-b6c8e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-01 09:22:21.099  6926  6926 W art     : b6c8e000-b6c8f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-01 09:22:21.099  6926  6926 W art     : b6c8f000-b6cb7000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-01 09:22:21.099  6926  6926 W art     : b6cb7000-b6cb9000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-01 09:22:21.099  6926  6926 W art     : b6cb9000-b6cba000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-01 09:22:21.099  6926  6926 W art     : b6cba000-b6cbd000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-01 09:22:21.099  6926  6926 W art     : b6cbd000-b6cbe000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-01 09:22:21.099  6926  6926 W art     : b6cbe000-b6cbf000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-01 09:22:21.099  6926  6926 W art     : b6cbf000-b6cc8000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-01 09:22:21.099  6926  6926 W art     : b6cc8000-b6cc9000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-01 09:22:21.099  6926  6926 W art     : b6cc9000-b6cca000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-01 09:22:21.099  6926  6926 W art     : b6cca000-b6cea000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-01 09:22:21.099  6926  6926 W art     : b6cea000-b6ceb000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-01 09:22:21.099  6926  6926 W art     : b6ceb000-b6cec000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-01 09:22:21.099  6926  6926 W art     : b6cec000-b6d5f000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-01 09:22:21.099  6926  6926 W art     : b6d5f000-b6d63000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-01 09:22:21.099  6926  6926 W art     : b6d63000-b6d66000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-01 09:22:21.099  6926  6926 W art     : b6d66000-b6d70000 rw-p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6d70000-b6df8000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-01 09:22:21.099  6926  6926 W art     : b6df8000-b6df9000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6df9000-b6dfd000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-01 09:22:21.099  6926  6926 W art     : b6dfd000-b6dfe000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-01 09:22:21.099  6926  6926 W art     : b6dfe000-b6dff000 rw-p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6dff000-b6e28000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-01 09:22:21.099  6926  6926 W art     : b6e28000-b6e29000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6e29000-b6e2c000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-01 09:22:21.099  6926  6926 W art     : b6e2c000-b6e2d000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-01 09:22:21.099  6926  6926 W art     : b6e2d000-b6f07000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-01 09:22:21.099  6926  6926 W art     : b6f07000-b6f0e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-01 09:22:21.099  6926  6926 W art     : b6f0e000-b6f16000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-01 09:22:21.099  6926  6926 W art     : b6f16000-b6f17000 rw-p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6f17000-b6f18000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 09:22:21.099  6926  6926 W art     : b6f18000-b6f19000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-01 09:22:21.099  6926  6926 W art     : b6f19000-b6f1a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.099  6926  6926 W art     : b6f1a000-b6f1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.099  6926  6926 W art     : b6f1d000-b6f42000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-01 09:22:21.099  6926  6926 W art     : b6f42000-b6f43000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6f43000-b6f4a000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-01 09:22:21.099  6926  6926 W art     : b6f4a000-b6f4b000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-01 09:22:21.099  6926  6926 W art     : b6f4b000-b6f52000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-01 09:22:21.099  6926  6926 W art     : b6f52000-b6f53000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-01 09:22:21.099  6926  6926 W art     : b6f53000-b6f54000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-01 09:22:21.099  6926  6926 W art     : b6f54000-b6f55000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.099  6926  6926 W art     : b6f55000-b6f6d000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-01 09:22:21.099  6926  6926 W art     : b6f6d000-b6f6e000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6f6e000-b6f6f000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-01 09:22:21.099  6926  6926 W art     : b6f6f000-b6f70000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-01 09:22:21.099  6926  6926 W art     : b6f70000-b6f7e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-01 09:22:21.099  6926  6926 W art     : b6f7e000-b6f7f000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6f7f000-b6f80000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-01 09:22:21.099  6926  6926 W art     : b6f80000-b6f81000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-01 09:22:21.099  6926  6926 W art     : b6f81000-b6f82000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 09:22:21.099  6926  6926 W art     : b6f82000-b6f84000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.099  6926  6926 W art     : b6f84000-b6f85000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.099  6926  6926 W art     : b6f85000-b6f86000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-01 09:22:21.099  6926  6926 W art     : b6f86000-b6f87000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-01 09:22:21.099  6926  6926 W art     : b6f87000-b6f88000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-01 09:22:21.099  6926  6926 W art     : b6f88000-b6fa8000 r--s 00000000 00:0b 8200       /dev/__properties__
07-01 09:22:21.099  6926  6926 W art     : b6fa8000-b6fa9000 r--p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6fa9000-b6faa000 ---p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6faa000-b6fac000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-01 09:22:21.099  6926  6926 W art     : b6fac000-b6fad000 r-xp 00000000 00:00 0          [sigpage]
07-01 09:22:21.099  6926  6926 W art     : b6fad000-b6fc8000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-01 09:22:21.099  6926  6926 W art     : b6fc8000-b6fc9000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-01 09:22:21.099  6926  6926 W art     : b6fc9000-b6fcb000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-01 09:22:21.099  6926  6926 W art     : b6fcb000-b6fcd000 rw-p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : b6fcd000-b6fd2000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-01 09:22:21.099  6926  6926 W art     : b6fd2000-b6fd3000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-01 09:22:21.099  6926  6926 W art     : b6fd3000-b6fd4000 rw-p 00000000 00:00 0 
07-01 09:22:21.099  6926  6926 W art     : be8f1000-be912000 rw-p 00000000 00:00 0          [stack]
07-01 09:22:21.099  6926  6926 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-01 09:22:21.149  6926  6926 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-01 09:22:21.199  6926  6926 I Radio-JNI: register_android_hardware_Radio DONE
07-01 09:22:21.209  6926  6926 E AffinityControl: AffinityControl: registerfunction enter
07-01 09:22:21.219  6926  6926 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-01 09:22:21.229   770  1735 D PackageManager: START PACKAGE DELETE: observer{126581054}
07-01 09:22:21.229   770  1735 D PackageManager: pkg{<packageName>}
07-01 09:22:21.229   770  1735 D PackageManager: user{0}
07-01 09:22:21.229   770  1735 D PackageManager: caller{2000}
07-01 09:22:21.229   770  1735 D PackageManager: flags{2}
07-01 09:22:21.229   770  1735 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-01 09:22:21.229   770  1735 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-01 09:22:21.229   770  1735 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-01 09:22:21.239   770  1735 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 09:22:21.239   770  1735 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 09:22:21.239   770   942 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-01 09:22:21.239   770   942 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-01 09:22:21.239   770   942 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-01 09:22:21.239   770   942 D ApplicationPolicy: getApplicationUninstallationEnabled
07-01 09:22:21.239   770   942 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-01 09:22:21.239   770   942 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-01 09:22:21.239   770   942 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-01 09:22:21.239   770   942 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-01 09:22:21.239   770   865 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-01 09:22:21.239   770   942 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-01 09:22:21.239   770   942 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-01 09:22:21.239   770   865 I ActivityManager: Killing 6295:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
07-01 09:22:21.249   770   865 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-01 09:22:21.249   770   865 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-01 09:22:21.269  6941  6941 E Zygote  : v2
07-01 09:22:21.269  6941  6941 I libpersona: KNOX_SDCARD checking this for 10004
07-01 09:22:21.269  6941  6941 I libpersona: KNOX_SDCARD not a persona
07-01 09:22:21.269  6941  6941 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-01 09:22:21.269  6941  6941 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-01 09:22:21.269  6941  6941 E Zygote  : accessInfo : 0
07-01 09:22:21.269  6941  6941 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-01 09:22:21.269   770   865 I ActivityManager: Start proc 6941:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-01 09:22:21.279   770   865 I ActivityManager:   Force finishing activity ActivityRecord{51ef9cb u0 com.test.thalitest/.MainActivity t64}
07-01 09:22:21.279   770   865 I ActivityManager:   Force finishing activity ActivityRecord{52b1602 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}
07-01 09:22:21.279   770   865 D InputDispatcher: Focused application set to: xxxx
07-01 09:22:21.299   770   865 I ActivityManager: Killing 4692:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
07-01 09:22:21.299   770   942 D AASAinstall: there is not AASApackages.xml file
07-01 09:22:21.299  6941  6941 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 09:22:21.299  6941  6941 D ActivityThread: Added TimaKeyStore provider
07-01 09:22:21.309   770   865 D ActivityManager: mDVFSHelper.acquire()
07-01 09:22:21.319  6365  6365 D ViewRootImpl: #3 mView = null
07-01 09:22:21.319   294  1790 I SurfaceFlinger: id=17 Removed HrantPermis (7/9)
07-01 09:22:21.319   294  1298 I SurfaceFlinger: id=17 Removed HrantPermis (-2/9)
07-01 09:22:21.329   770  1722 D InputDispatcher: Focus left window: 6365
07-01 09:22:21.329   770  1722 D InputDispatcher: Focus entered window: 6295
07-01 09:22:21.329   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8253a4
07-01 09:22:21.339   770  4209 D GraphicsStats: Buffer count: 5
07-01 09:22:21.339   770  4209 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@947b39f)
07-01 09:22:21.339   770  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:22:21.349   770   788 I WindowState: WIN DEATH: Window{bda020 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 09:22:21.349   770  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:22:21.349   294  1298 I SurfaceFlinger: id=16 Removed NainActivit (4/8)
07-01 09:22:21.349   294  1790 I SurfaceFlinger: id=16 Removed NainActivit (-2/8)
07-01 09:22:21.349   294   361 I SurfaceFlinger: id=16 Removed NainActivit (-2/8)
07-01 09:22:21.349   770  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:22:21.349   770   788 D InputDispatcher: Focus left window: 6295
07-01 09:22:21.359   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8253a4
07-01 09:22:21.609   770   942 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-01 09:22:21.639   770   942 W PackageSettings: Skipping PackageSetting{ffe98a6 com.example.hello/10192} due to missing metadata
07-01 09:22:21.729   770   942 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-01 09:22:21.739   328   328 W keystore: ENTER clear_uid from uid 1000 for 10004
07-01 09:22:21.739   770   942 I art     : Starting a blocking GC Explicit
07-01 09:22:21.759   770  1466 I ActivityManager: Killing 5560:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
07-01 09:22:21.779  1723  1723 D Launcher: onRestart, Launcher: 203783616
07-01 09:22:21.779   294   294 I SurfaceFlinger: id=18 createSurf (1146x1876),1 flag=4, VSBConnecti
07-01 09:22:21.779   770  1410 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
07-01 09:22:21.779   770   789 D InputDispatcher: Focus entered window: 3415
07-01 09:22:21.789   770   908 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
07-01 09:22:21.789   770   908 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 09:22:21.789   770   908 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-01 09:22:21.789   770   908 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-01 09:22:21.799   770   865 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
07-01 09:22:21.799   770  1701 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-01 09:22:21.799   770  1701 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 09:22:21.799   770   770 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 09:22:21.799   770   770 I KnoxTimeoutHandler: Shared devices show user statefalse
07-01 09:22:21.799   770   770 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
07-01 09:22:21.799  1723  1723 D Launcher: onStart, Launcher: 203783616
07-01 09:22:21.799  1723  1723 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
07-01 09:22:21.799  1723  1723 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-01 09:22:21.799  1723  1723 D Launcher.HomeView: onStart
07-01 09:22:21.799   770   872 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{bda020 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 09:22:21.809  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
07-01 09:22:21.809  1723  1723 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
07-01 09:22:21.809  1723  1723 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
07-01 09:22:21.809  2127  2138 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
07-01 09:22:21.809  1723  1723 V ActivityThread: updateVisibility : ActivityRecord{4169a27 token=android.os.BinderProxy@4df88c4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-01 09:22:21.819   770  6958 V WindowStateAnimator: Finishing drawing window Window{117248f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-01 09:22:21.819   294   294 I SurfaceFlinger: id=19 createSurf (1194x288),1 flag=4, VSBConnecti
07-01 09:22:21.829   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe825364
07-01 09:22:21.829   770  3348 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-01 09:22:21.829   770   788 V WindowOrientationListener: setCurrentAppOrientation :1
07-01 09:22:21.829   770   788 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-01 09:22:21.829   770   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 09:22:21.829   770   872 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{117248f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
07-01 09:22:21.829   770   770 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 09:22:21.829   294   294 I SurfaceFlinger: id=20 createSurf (1080x1,920),1 flag=4, Mauncher
07-01 09:22:21.829   770   770 I KnoxTimeoutHandler: SD activityfalse
07-01 09:22:21.829  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
07-01 09:22:21.839  6941  6941 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-01 09:22:21.839  3415  3415 V ActivityThread: updateVisibility : ActivityRecord{2740b28 token=android.os.BinderProxy@f4e70c2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
07-01 09:22:21.839  6365  6365 E ViewRootImpl: sendUserActionEvent() mView == null
07-01 09:22:21.839   770   908 D ActivityManager: mDVFSHelper.release()
07-01 09:22:21.839   770   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{334b54a u0 com.samsung.android.MtpApplication/.USBConnection t63} time:1570385
07-01 09:22:21.849  1723  1723 D Launcher.HomeView: onStop
07-01 09:22:21.849  6941  6941 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
07-01 09:22:21.849  6941  6941 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
07-01 09:22:21.849  6941  6941 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
07-01 09:22:21.849  6941  6941 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
07-01 09:22:21.849   770  1701 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
07-01 09:22:21.859  6941  6941 D AndroidRuntime: Shutting down VM
07-01 09:22:21.859  6941  6941 E AndroidRuntime: FATAL EXCEPTION: main
07-01 09:22:21.859  6941  6941 E AndroidRuntime: Process: com.test.thalitest, PID: 6941
07-01 09:22:21.859  6941  6941 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
07-01 09:22:21.859  6941  6941 E AndroidRuntime: 	... 9 more
07-01 09:22:21.869   770  1735 V WindowStateAnimator: Finishing drawing window Window{2d61b25 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-01 09:22:21.869  3415  3415 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f4e70c2 time:1570416
07-01 09:22:21.869  6941  6941 I Process : Sending signal. PID: 6941 SIG: 9
07-01 09:22:21.879   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe825364
07-01 09:22:21.879   770   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 09:22:21.879   770   770 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-01 09:22:21.879   770   770 I KnoxTimeoutHandler: SD activityfalse
07-01 09:22:21.879   770   865 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83c1cec u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2249470 6552:com.samsung.android.sm/1000}
07-01 09:22:21.889  6552  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
07-01 09:22:21.889   770   789 I ActivityManager: Process com.test.thalitest (pid 6941)(adj 9) has died(118,776)
07-01 09:22:21.889   770   789 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-01 09:22:21.889   770   789 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-01 09:22:21.899   770   789 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
07-01 09:22:21.909   770  4209 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{83c1cec u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc6d420 4149:com.google.android.gms/u0a11}
07-01 09:22:21.909   770   865 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
07-01 09:22:21.909   770   865 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
07-01 09:22:21.919   770  1410 V WindowStateAnimator: Finishing drawing window Window{19ad319 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
07-01 09:22:21.919   770   908 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-01 09:22:21.919   770   770 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-01 09:22:21.919   770   908 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35232f7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t61} time:1570469
07-01 09:22:21.929   770   770 I KnoxTimeoutHandler: SD activityfalse
07-01 09:22:21.929   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe825364
07-01 09:22:21.949   770   942 I art     : Explicit concurrent mark sweep GC freed 99898(6MB) AllocSpace objects, 160(3MB) LOS objects, 27% free, 42MB/58MB, paused 1.736ms total 213.689ms
07-01 09:22:21.969  4149  6987 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
07-01 09:22:21.979   770   942 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-01 09:22:21.979   770   942 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
07-01 09:22:21.979   770   942 D AASAinstall: there is not AASApackages.xml file
07-01 09:22:21.979   770   942 D PackageManager: result of delete: 1{126581054}
07-01 09:22:21.979  6926  6926 I art     : System.exit called, status: 0
07-01 09:22:21.979  6926  6926 I AndroidRuntime: VM exiting with result code 0.

```
