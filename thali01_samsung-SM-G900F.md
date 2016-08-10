#### Test 797638305e9d4c1_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-10 15:46:38.949   788  1649 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,08-10 15:46:39.879   788  1236 V AlarmManager: Expired Alarm result :4
--------- beginning of main
08-10 15:46:39.889  2374  2374 E audit   : type=1400 msg=audit(1470836799.889:285): avc:  denied  { execmod } for  pid=6327 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 15:46:39.889  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:39.889  2374  2374 E audit   : type=1300 msg=audit(1470836799.889:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc3000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6327 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 15:46:39.889  2374  2374 E audit   : type=1327 msg=audit(1470836799.889:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-10 15:46:39.889  2374  2374 E audit   : type=1320 msg=audit(1470836799.889:285): 
08-10 15:46:39.949  2374  2374 E audit   : type=1400 msg=audit(1470836799.949:286): avc:  denied  { execmod } for  pid=6327 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 15:46:39.949  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:39.949  2374  2374 E audit   : type=1300 msg=audit(1470836799.949:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f82000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6327 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 15:46:39.949  2374  2374 E audit   : type=1327 msg=audit(1470836799.949:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-10 15:46:39.949  2374  2374 E audit   : type=1320 msg=audit(1470836799.949:286): 
08-10 15:46:39.999  2374  2374 E audit   : type=1400 msg=audit(1470836799.999:287): avc:  denied  { execmod } for  pid=6327 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 15:46:39.999  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:39.999  2374  2374 E audit   : type=1300 msg=audit(1470836799.999:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f83000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6327 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 15:46:39.999  2374  2374 E audit   : type=1327 msg=audit(1470836799.999:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-10 15:46:39.999  2374  2374 E audit   : type=1320 msg=audit(1470836799.999:287): 
08-10 15:46:39.999  6327  6327 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 15:46:39.999  6327  6327 D AndroidRuntime: CheckJNI is OFF
08-10 15:46:39.999  6327  6327 D AndroidRuntime: readGMSProperty: start
08-10 15:46:39.999  6327  6327 D AndroidRuntime: readGMSProperty: already setted!!
08-10 15:46:39.999  6327  6327 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-10 15:46:39.999  6327  6327 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-10 15:46:39.999  6327  6327 D AndroidRuntime: readGMSProperty: end
08-10 15:46:39.999  6327  6327 D AndroidRuntime: addProductProperty: start
08-10 15:46:40.009  6327  6327 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-10 15:46:40.009  6327  6327 W art     : af124000-b204a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-10 15:46:40.009  6327  6327 W art     : b204a000-b42b9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-10 15:46:40.009  6327  6327 W art     : b42b9000-b42ba000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-10 15:46:40.009  6327  6327 W art     : b42ba000-b42e3000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-10 15:46:40.009  6327  6327 W art     : b42e3000-b4731000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-10 15:46:40.009  6327  6327 W art     : b4731000-b4732000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b4732000-b473c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-10 15:46:40.009  6327  6327 W art     : b473c000-b473d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-10 15:46:40.009  6327  6327 W art     : b473d000-b473f000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b473f000-b4740000 r--p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-10 15:46:40.009  6327  6327 W art     : b4854000-b4857000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-10 15:46:40.009  6327  6327 W art     : b4857000-b4858000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-10 15:46:40.009  6327  6327 W art     : b4858000-b4859000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-10 15:46:40.009  6327  6327 W art     : b4859000-b485a000 r--p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b485a000-b487a000 r--s 00000000 00:0b 9219       /dev/__properties__
08-10 15:46:40.009  6327  6327 W art     : b487a000-b528b000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-10 15:46:40.009  6327  6327 W art     : b528b000-b528c000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b528c000-b52d5000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-10 15:46:40.009  6327  6327 W art     : b52d5000-b52d6000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-10 15:46:40.009  6327  6327 W art     : b52d6000-b52de000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b52de000-b52df000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b52df000-b5314000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-10 15:46:40.009  6327  6327 W art     : b5314000-b5315000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5315000-b5316000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-10 15:46:40.009  6327  6327 W art     : b5316000-b5317000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-10 15:46:40.009  6327  6327 W art     : b5317000-b536f000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-10 15:46:40.009  6327  6327 W art     : b536f000-b5370000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5370000-b5371000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-10 15:46:40.009  6327  6327 W art     : b5371000-b5372000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-10 15:46:40.009  6327  6327 W art     : b5373000-b5379000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 15:46:40.009  6327  6327 W art     : b5379000-b537a000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 15:46:40.009  6327  6327 W art     : b537a000-b537b000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 15:46:40.009  6327  6327 W art     : b537b000-b537d000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b537e000-b5388000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 15:46:40.009  6327  6327 W art     : b5388000-b538b000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 15:46:40.009  6327  6327 W art     : b538b000-b538c000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 15:46:40.009  6327  6327 W art     : b538d000-b53a4000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 15:46:40.009  6327  6327 W art     : b53a4000-b53a5000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b53a5000-b53a6000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 15:46:40.009  6327  6327 W art     : b53a6000-b53a7000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 15:46:40.009  6327  6327 W art     : b53a8000-b53b2000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-10 15:46:40.009  6327  6327 W art     : b53b2000-b53b3000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-10 15:46:40.009  6327  6327 W art     : b53b3000-b53b4000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-10 15:46:40.009  6327  6327 W art     : b53b4000-b53b8000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 15:46:40.009  6327  6327 W art     : b53b8000-b53b9000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 15:46:40.009  6327  6327 W art     : b53b9000-b53ba000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 15:46:40.009  6327  6327 W art     : b53ba000-b53d0000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-10 15:46:40.009  6327  6327 W art     : b53d0000-b53d1000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-10 15:46:40.009  6327  6327 W art     : b53d1000-b53d2000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-10 15:46:40.009  6327  6327 W art     : b53d2000-b53df000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-10 15:46:40.009  6327  6327 W art     : b53df000-b53e0000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-10 15:46:40.009  6327  6327 W art     : b53e0000-b53e1000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-10 15:46:40.009  6327  6327 W art     : b53e1000-b5441000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-10 15:46:40.009  6327  6327 W art     : b5441000-b5444000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-10 15:46:40.009  6327  6327 W art     : b5444000-b5448000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5448000-b54a9000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-10 15:46:40.009  6327  6327 W art     : b54a9000-b54aa000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-10 15:46:40.009  6327  6327 W art     : b54aa000-b54f9000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-10 15:46:40.009  6327  6327 W art     : b54f9000-b54fb000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-10 15:46:40.009  6327  6327 W art     : b54fb000-b54fc000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-10 15:46:40.009  6327  6327 W art     : b54fc000-b54fd000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b54fd000-b5504000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-10 15:46:40.009  6327  6327 W art     : b5504000-b5505000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-10 15:46:40.009  6327  6327 W art     : b5505000-b5506000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-10 15:46:40.009  6327  6327 W art     : avc_common.so
08-10 15:46:40.009  6327  6327 W art     : b5507000-b550a000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 15:46:40.009  6327  6327 W art     : b550a000-b550b000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 15:46:40.009  6327  6327 W art     : b550b000-b550c000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-10 15:46:40.009  6327  6327 W art     : enc_common.so
08-10 15:46:40.009  6327  6327 W art     : b550d000-b5511000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-10 15:46:40.009  6327  6327 W art     : b5511000-b5512000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5512000-b5513000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-10 15:46:40.009  6327  6327 W art     : b5513000-b5514000 rw-p 00005000 b3:17 2510       /syste
08-10 15:46:40.009  6327  6327 W art     : m/lib/libpowermanager.so
08-10 15:46:40.009  6327  6327 W art     : b5515000-b5532000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 15:46:40.009  6327  6327 W art     : b5532000-b5533000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 15:46:40.009  6327  6327 W art     : b5533000-b5534000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 15:46:40.009  6327  6327 W art     : b5535000-b553a000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 15:46:40.009  6327  6327 W art     : b553a000-b553b000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 15:46:40.009  6327  6327 W art     : b553b000-b553c000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 15:46:40.009  6327  6327 W art     : b553d000-b556e000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 15:46:40.009  6327  6327 W art     : b556e000-b5571000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 15:46:40.009  6327  6327 W art     : b5571000-b5572000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 15:46:40.009  6327  6327 W art     : b5573000-b55ae000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-10 15:46:40.009  6327  6327 W art     : b55ae000-b55af000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-10 15:46:40.009  6327  6327 W art     : b55af000-b55b0000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-10 15:46:40.009  6327  6327 W art     : b55b1000-b55b8000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-10 15:46:40.009  6327  6327 W art     : b55b8000-b55b9000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b55b9000-b55ba000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-10 15:46:40.009  6327  6327 W art     : b55ba000-b55bb000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-10 15:46:40.009  6327  6327 W art     : b55bb000-b55bc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b55bc000-b55d3000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-10 15:46:40.009  6327  6327 W art     : b55d3000-b55d4000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b55d4000-b55d7000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-10 15:46:40.009  6327  6327 W art     : b55d7000-b55d8000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-10 15:46:40.009  6327  6327 W art     : b55d8000-b55f7000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-10 15:46:40.009  6327  6327 W art     : b55f7000-b55f8000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-10 15:46:40.009  6327  6327 W art     : b55f8000-b55f9000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-10 15:46:40.009  6327  6327 W art     : b55f9000-b5637000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-10 15:46:40.009  6327  6327 W art     : b5637000-b5638000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5638000-b563a000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-10 15:46:40.009  6327  6327 W art     : b563a000-b563b000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-10 15:46:40.009  6327  6327 W art     : b563c000-b5643000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 15:46:40.009  6327  6327 W art     : b5643000-b5644000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 15:46:40.009  6327  6327 W art     : b5644000-b5645000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 15:46:40.009  6327  6327 W art     : b5646000-b5649000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 15:46:40.009  6327  6327 W art     : b5649000-b564a000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 15:46:40.009  6327  6327 W art     : b564a000-b564b000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 15:46:40.009  6327  6327 W art     : b564b000-b5651000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 15:46:40.009  6327  6327 W art     : b5651000-b5652000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5652000-b5653000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 15:46:40.009  6327  6327 W art     : b5653000-b5654000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 15:46:40.009  6327  6327 W art     : b5654000-b565d000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-10 15:46:40.009  6327  6327 W art     : b565d000-b565e000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-10 15:46:40.009  6327  6327 W art     : b565e000-b565f000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-10 15:46:40.009  6327  6327 W art     : b565f000-b56f0000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 15:46:40.009  6327  6327 W art     : b56f0000-b56f1000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b56f1000-b56fc000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 15:46:40.009  6327  6327 W art     : b56fc000-b56fd000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 15:46:40.009  6327  6327 W art     : b56fe000-b5710000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-10 15:46:40.009  6327  6327 W art     : b5710000-b5711000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-10 15:46:40.009  6327  6327 W art     : b5711000-b5712000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-10 15:46:40.009  6327  6327 W art     : b5713000-b5718000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-10 15:46:40.009  6327  6327 W art     : b5718000-b5719000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-10 15:46:40.009  6327  6327 W art     : b5719000-b571a000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-10 15:46:40.009  6327  6327 W art     : b571b000-b5788000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-10 15:46:40.009  6327  6327 W art     : b5788000-b5789000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5789000-b578b000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-10 15:46:40.009  6327  6327 W art     : b578b000-b578c000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-10 15:46:40.009  6327  6327 W art     : b578c000-b578d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b578d000-b5794000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 15:46:40.009  6327  6327 W art     : b5794000-b5795000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 15:46:40.009  6327  6327 W art     : b5795000-b5796000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 15:46:40.009  6327  6327 W art     : b5797000-b5817000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 15:46:40.009  6327  6327 W art     : b5817000-b5818000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5818000-b5819000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 15:46:40.009  6327  6327 W art     : b5819000-b581a000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 15:46:40.009  6327  6327 W art     : b581a000-b5831000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5831000-b5868000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-10 15:46:40.009  6327  6327 W art     : ib/libqc-opt.so
08-10 15:46:40.009  6327  6327 W art     : b5868000-b5869000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 15:46:40.009  6327  6327 W art     : b5869000-b586a000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 15:46:40.009  6327  6327 W art     : b586a000-b5886000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 15:46:40.009  6327  6327 W art     : b5886000-b5887000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 15:46:40.009  6327  6327 W art     : b5887000-b5888000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 15:46:40.009  6327  6327 W art     : b5889000-b58ea000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-10 15:46:40.009  6327  6327 W art     : b58ea000-b58ec000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-10 15:46:40.009  6327  6327 W art     : b58ec000-b58ed000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-10 15:46:40.009  6327  6327 W art     : b58ee000-b5915000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-10 15:46:40.009  6327  6327 W art     : b5915000-b5916000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5916000-b5917000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-10 15:46:40.009  6327  6327 W art     : b5917000-b5918000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-10 15:46:40.009  6327  6327 W art     : b5919000-b5921000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 15:46:40.009  6327  6327 W art     : b5921000-b5923000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 15:46:40.009  6327  6327 W art     : b5923000-b5924000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 15:46:40.009  6327  6327 W art     : b5925000-b5928000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-10 15:46:40.009  6327  6327 W art     : b5928000-b5929000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-10 15:46:40.009  6327  6327 W art     : b5929000-b592a000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-10 15:46:40.009  6327  6327 W art     : b592a000-b592e000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-10 15:46:40.009  6327  6327 W art     : b592e000-b592f000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b592f000-b5930000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-10 15:46:40.009  6327  6327 W art     : b5930000-b5931000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-10 15:46:40.009  6327  6327 W art     : b5931000-b5941000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-10 15:46:40.009  6327  6327 W art     : b5941000-b5942000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-10 15:46:40.009  6327  6327 W art     : b5942000-b5943000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-10 15:46:40.009  6327  6327 W art     : b5943000-b5989000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5989000-b5992000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-10 15:46:40.009  6327  6327 W art     : b5992000-b5993000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-10 15:46:40.009  6327  6327 W art     : b5993000-b5994000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-10 15:46:40.009  6327  6327 W art     : b5995000-b599a000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-10 15:46:40.009  6327  6327 W art     : b599a000-b599b000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-10 15:46:40.009  6327  6327 W art     : b599b000-b599c000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-10 15:46:40.009  6327  6327 W art     : b599c000-b599f000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 15:46:40.009  6327  6327 W art     : b599f000-b59a0000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b59a0000-b59a1000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 15:46:40.009  6327  6327 W art     : b59a1000-b59a2000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 15:46:40.009  6327  6327 W art     : b59a3000-b59bb000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 15:46:40.009  6327  6327 W art     : b59bb000-b59bc000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b59bc000-b59bd000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 15:46:40.009  6327  6327 W art     : b59bd000-b59be000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 15:46:40.009  6327  6327 W art     : b59bf000-b5b59000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-10 15:46:40.009  6327  6327 W art     : b5b59000-b5b5a000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5b5a000-b5b67000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-10 15:46:40.009  6327  6327 W art     : b5b67000-b5b68000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-10 15:46:40.009  6327  6327 W art     : b5b68000-b5b6c000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-10 15:46:40.009  6327  6327 W art     : b5b6c000-b5b6d000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5b6d000-b5b6e000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-10 15:46:40.009  6327  6327 W art     : b5b6e000-b5b6f000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-10 15:46:40.009  6327  6327 W art     : b5b6f000-b5b82000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-10 15:46:40.009  6327  6327 W art     : b5b82000-b5b83000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-10 15:46:40.009  6327  6327 W art     : b5b83000-b5b84000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-10 15:46:40.009  6327  6327 W art     : b5b84000-b5b85000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:40.009  6327  6327 W art     : b5b85000-b5bd0000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-10 15:46:40.009  6327  6327 W art     : b5bd0000-b5bd1000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-10 15:46:40.009  6327  6327 W art     : b5bd1000-b5bd2000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-10 15:46:40.009  6327  6327 W art     : b5bd2000-b5bd4000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5bd5000-b5be6000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 15:46:40.009  6327  6327 W art     : b5be6000-b5be7000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5be7000-b5be8000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 15:46:40.009  6327  6327 W art     : b5be8000-b5be9000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 15:46:40.009  6327  6327 W art     : b5bea000-b5bf4000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-10 15:46:40.009  6327  6327 W art     : b5bf4000-b5bf6000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-10 15:46:40.009  6327  6327 W art     : b5bf6000-b5bf7000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-10 15:46:40.009  6327  6327 W art     : b5bf7000-b5c10000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-10 15:46:40.009  6327  6327 W art     : b5c10000-b5c11000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-10 15:46:40.009  6327  6327 W art     : b5c11000-b5c14000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-10 15:46:40.009  6327  6327 W art     : b5c14000-b5c18000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5c18000-b5c8c000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-10 15:46:40.009  6327  6327 W art     : b5c8c000-b5c8d000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5c8d000-b5c90000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-10 15:46:40.009  6327  6327 W art     : b5c90000-b5c91000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-10 15:46:40.009  6327  6327 W art     : b5c91000-b5c92000 r--p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5c92000-b5c95000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-10 15:46:40.009  6327  6327 W art     : b5c95000-b5c96000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-10 15:46:40.009  6327  6327 W art     : b5c96000-b5c97000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-10 15:46:40.009  6327  6327 W art     : b5c97000-b5c98000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b5c98000-b5c9d000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 15:46:40.009  6327  6327 W art     : b5c9d000-b5c9e000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 15:46:40.009  6327  6327 W art     : b5c9e000-b5c9f000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 15:46:40.009  6327  6327 W art     : b5c9f000-b5ca0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b5ca0000-b5ca3000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 15:46:40.009  6327  6327 W art     : b5ca3000-b5ca4000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 15:46:40.009  6327  6327 W art     : b5ca4000-b5ca5000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 15:46:40.009  6327  6327 W art     : b5ca5000-b5ca6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b5ca6000-b5caa000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-10 15:46:40.009  6327  6327 W art     : b5caa000-b5cab000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-10 15:46:40.009  6327  6327 W art     : b5cab000-b5cac000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-10 15:46:40.009  6327  6327 W art     : b5cac000-b5cad000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:40.009  6327  6327 W art     : b5cad000-b5cb1000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 15:46:40.009  6327  6327 W art     : b5cb1000-b5cb2000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 15:46:40.009  6327  6327 W art     : b5cb2000-b5cb3000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 15:46:40.009  6327  6327 W art     : b5cb3000-b5cb4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b5cb4000-b5cc2000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-10 15:46:40.009  6327  6327 W art     : b5cc2000-b5cc3000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b5cc3000-b5cc4000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-10 15:46:40.009  6327  6327 W art     : b5cc4000-b5cc5000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-10 15:46:40.009  6327  6327 W art     : b5cc5000-b5ccf000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 15:46:40.009  6327  6327 W art     : b5ccf000-b5cd2000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 15:46:40.009  6327  6327 W art     : b5cd2000-b5cd3000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 15:46:40.009  6327  6327 W art     : b5cd3000-b5cd4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b5cd4000-b5cde000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-10 15:46:40.009  6327  6327 W art     : b5cde000-b5ce1000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-10 15:46:40.009  6327  6327 W art     : b5ce1000-b5ce2000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-10 15:46:40.009  6327  6327 W art     : b5ce2000-b5ce6000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-10 15:46:40.009  6327  6327 W art     : b5ce6000-b5ce7000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-10 15:46:40.009  6327  6327 W art     : b5ce7000-b5ce8000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-10 15:46:40.009  6327  6327 W art     : b5ce8000-b5ce9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b5ce9000-b5cf6000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-10 15:46:40.009  6327  6327 W art     : b5cf6000-b5cf8000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-10 15:46:40.009  6327  6327 W art     : b5cf8000-b5cf9000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-10 15:46:40.009  6327  6327 W art     : b5cf9000-b610b000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-10 15:46:40.009  6327  6327 W art     : b610b000-b610c000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b610c000-b6115000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-10 15:46:40.009  6327  6327 W art     : b6115000-b6119000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-10 15:46:40.009  6327  6327 W art     : b6119000-b611a000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b611a000-b6121000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-10 15:46:40.009  6327  6327 W art     : b6121000-b6122000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-10 15:46:40.009  6327  6327 W art     : b6122000-b6123000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-10 15:46:40.009  6327  6327 W art     : b6123000-b6124000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b6124000-b613f000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-10 15:46:40.009  6327  6327 W art     : b613f000-b6140000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-10 15:46:40.009  6327  6327 W art     : b6140000-b6141000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-10 15:46:40.009  6327  6327 W art     : b6141000-b6142000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b6142000-b618e000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 15:46:40.009  6327  6327 W art     : b618e000-b618f000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b618f000-b6190000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 15:46:40.009  6327  6327 W art     : b6190000-b6191000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 15:46:40.009  6327  6327 W art     : b6191000-b6192000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b6192000-b6196000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-10 15:46:40.009  6327  6327 W art     : b6196000-b6197000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b6197000-b6198000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-10 15:46:40.009  6327  6327 W art     : b6198000-b6199000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-10 15:46:40.009  6327  6327 W art     : b6199000-b61d1000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-10 15:46:40.009  6327  6327 W art     : b61d1000-b61d2000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-10 15:46:40.009  6327  6327 W art     : b61d2000-b61d3000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-10 15:46:40.009  6327  6327 W art     : b61d3000-b61d4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.009  6327  6327 W art     : b61d4000-b6272000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-10 15:46:40.009  6327  6327 W art     : b6272000-b6273000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b6273000-b6291000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-10 15:46:40.009  6327  6327 W art     : b6291000-b6292000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-10 15:46:40.009  6327  6327 W art     : b6292000-b6405000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-10 15:46:40.009  6327  6327 W art     : b6405000-b6410000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-10 15:46:40.009  6327  6327 W art     : b6410000-b6411000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-10 15:46:40.009  6327  6327 W art     : b6411000-b6528000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-10 15:46:40.009  6327  6327 W art     : b6528000-b6533000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-10 15:46:40.009  6327  6327 W art     : b6533000-b6534000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-10 15:46:40.009  6327  6327 W art     : b6534000-b6538000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b6538000-b655c000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-10 15:46:40.009  6327  6327 W art     : b655c000-b655e000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-10 15:46:40.009  6327  6327 W art     : b655e000-b655f000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-10 15:46:40.009  6327  6327 W art     : b655f000-b6605000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-10 15:46:40.009  6327  6327 W art     : b6605000-b6612000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-10 15:46:40.009  6327  6327 W art     : b6612000-b6613000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-10 15:46:40.009  6327  6327 W art     : b6613000-b6614000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b6614000-b6667000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-10 15:46:40.009  6327  6327 W art     : b6667000-b6668000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b6668000-b6669000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-10 15:46:40.009  6327  6327 W art     : b6669000-b666a000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-10 15:46:40.009  6327  6327 W art     : b666a000-b666f000 rw-p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b666f000-b6681000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-10 15:46:40.009  6327  6327 W art     : b6681000-b6682000 ---p 00000000 00:00 0 
08-10 15:46:40.009  6327  6327 W art     : b6682000-b6683000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-10 15:46:40.009  6327  6327 W art     : b6683000-b6684000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-10 15:46:40.009  6327  6327 W art     : b6684000-b668b000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 15:46:40.019  6327  6327 W art     : b668b000-b668c000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 15:46:40.019  6327  6327 W art     : b668c000-b668d000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 15:46:40.019  6327  6327 W art     : b668d000-b668e000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b668e000-b6691000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-10 15:46:40.019  6327  6327 W art     : b6691000-b6692000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-10 15:46:40.019  6327  6327 W art     : b6692000-b6693000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-10 15:46:40.019  6327  6327 W art     : b6693000-b6697000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-10 15:46:40.019  6327  6327 W art     : b6697000-b6698000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-10 15:46:40.019  6327  6327 W art     : b6698000-b6699000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-10 15:46:40.019  6327  6327 W art     : b6699000-b66a7000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-10 15:46:40.019  6327  6327 W art     : b66a7000-b66a8000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b66a8000-b66a9000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-10 15:46:40.019  6327  6327 W art     : b66a9000-b66aa000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-10 15:46:40.019  6327  6327 W art     : b66aa000-b66b3000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 15:46:40.019  6327  6327 W art     : b66b3000-b66b4000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 15:46:40.019  6327  6327 W art     : b66b4000-b66b5000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 15:46:40.019  6327  6327 W art     : b66b5000-b671b000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-10 15:46:40.019  6327  6327 W art     : b671b000-b671c000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b671c000-b671e000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-10 15:46:40.019  6327  6327 W art     : b671e000-b6727000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-10 15:46:40.019  6327  6327 W art     : b6727000-b672a000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b672a000-b67c1000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-10 15:46:40.019  6327  6327 W art     : b67c1000-b67c3000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-10 15:46:40.019  6327  6327 W art     : b67c3000-b67c4000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-10 15:46:40.019  6327  6327 W art     : b67c4000-b67c5000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b67c5000-b6ae6000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-10 15:46:40.019  6327  6327 W art     : b6ae6000-b6ae7000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6ae7000-b6b02000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-10 15:46:40.019  6327  6327 W art     : b6b02000-b6b06000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-10 15:46:40.019  6327  6327 W art     : b6b06000-b6b0b000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6b0b000-b6b13000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 15:46:40.019  6327  6327 W art     : b6b13000-b6b14000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 15:46:40.019  6327  6327 W art     : b6b14000-b6b15000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 15:46:40.019  6327  6327 W art     : b6b15000-b6b43000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-10 15:46:40.019  6327  6327 W art     : b6b43000-b6b44000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6b44000-b6b4b000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-10 15:46:40.019  6327  6327 W art     : b6b4b000-b6b4c000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-10 15:46:40.019  6327  6327 W art     : b6b4c000-b6b92000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-10 15:46:40.019  6327  6327 W art     : b6b92000-b6b93000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6b93000-b6b96000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-10 15:46:40.019  6327  6327 W art     : b6b96000-b6b97000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-10 15:46:40.019  6327  6327 W art     : b6b97000-b6bb2000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-10 15:46:40.019  6327  6327 W art     : b6bb2000-b6bb6000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-10 15:46:40.019  6327  6327 W art     : b6bb6000-b6bb7000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-10 15:46:40.019  6327  6327 W art     : b6bb7000-b6c04000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-10 15:46:40.019  6327  6327 W art     : b6c04000-b6c05000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6c05000-b6c11000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-10 15:46:40.019  6327  6327 W art     : b6c11000-b6c12000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-10 15:46:40.019  6327  6327 W art     : b6c12000-b6c1f000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-10 15:46:40.019  6327  6327 W art     : b6c1f000-b6c20000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6c20000-b6c21000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-10 15:46:40.019  6327  6327 W art     : b6c21000-b6c22000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-10 15:46:40.019  6327  6327 W art     : b6c22000-b6c2a000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-10 15:46:40.019  6327  6327 W art     : b6c2a000-b6c2b000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6c2b000-b6c2c000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-10 15:46:40.019  6327  6327 W art     : b6c2c000-b6c2d000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-10 15:46:40.019  6327  6327 W art     : b6c2d000-b6c34000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-10 15:46:40.019  6327  6327 W art     : b6c34000-b6c35000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-10 15:46:40.019  6327  6327 W art     : b6c35000-b6c36000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-10 15:46:40.019  6327  6327 W art     : b6c36000-b6c4a000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-10 15:46:40.019  6327  6327 W art     : b6c4a000-b6c4c000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-10 15:46:40.019  6327  6327 W art     : b6c4c000-b6c4d000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-10 15:46:40.019  6327  6327 W art     : b6c4d000-b6c75000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-10 15:46:40.019  6327  6327 W art     : b6c75000-b6c77000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-10 15:46:40.019  6327  6327 W art     : b6c77000-b6c78000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-10 15:46:40.019  6327  6327 W art     : b6c78000-b6c7b000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-10 15:46:40.019  6327  6327 W art     : b6c7b000-b6c7c000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-10 15:46:40.019  6327  6327 W art     : b6c7c000-b6c7d000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-10 15:46:40.019  6327  6327 W art     : b6c7d000-b6c86000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-10 15:46:40.019  6327  6327 W art     : b6c86000-b6c87000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-10 15:46:40.019  6327  6327 W art     : b6c87000-b6c88000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-10 15:46:40.019  6327  6327 W art     : b6c88000-b6ca8000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-10 15:46:40.019  6327  6327 W art     : b6ca8000-b6ca9000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-10 15:46:40.019  6327  6327 W art     : b6ca9000-b6caa000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-10 15:46:40.019  6327  6327 W art     : b6caa000-b6d1d000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-10 15:46:40.019  6327  6327 W art     : b6d1d000-b6d21000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-10 15:46:40.019  6327  6327 W art     : b6d21000-b6d24000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-10 15:46:40.019  6327  6327 W art     : b6d24000-b6d2e000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6d2e000-b6db6000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-10 15:46:40.019  6327  6327 W art     : b6db6000-b6db7000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6db7000-b6dbb000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-10 15:46:40.019  6327  6327 W art     : b6dbb000-b6dbc000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-10 15:46:40.019  6327  6327 W art     : b6dbc000-b6dbd000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6dbd000-b6de6000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-10 15:46:40.019  6327  6327 W art     : b6de6000-b6de7000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6de7000-b6dea000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-10 15:46:40.019  6327  6327 W art     : b6dea000-b6deb000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-10 15:46:40.019  6327  6327 W art     : b6deb000-b6ec5000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 15:46:40.019  6327  6327 W art     : b6ec5000-b6ecc000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 15:46:40.019  6327  6327 W art     : b6ecc000-b6ed4000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 15:46:40.019  6327  6327 W art     : b6ed4000-b6ed5000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6ed5000-b6ed6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:40.019  6327  6327 W art     : b6ed6000-b6ed7000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-10 15:46:40.019  6327  6327 W art     : b6ed7000-b6ed8000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.019  6327  6327 W art     : b6ed8000-b6edb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.019  6327  6327 W art     : b6edb000-b6f00000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-10 15:46:40.019  6327  6327 W art     : b6f00000-b6f01000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6f01000-b6f08000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-10 15:46:40.019  6327  6327 W art     : b6f08000-b6f09000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-10 15:46:40.019  6327  6327 W art     : b6f09000-b6f10000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-10 15:46:40.019  6327  6327 W art     : b6f10000-b6f11000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-10 15:46:40.019  6327  6327 W art     : b6f11000-b6f12000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-10 15:46:40.019  6327  6327 W art     : b6f12000-b6f13000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.019  6327  6327 W art     : b6f13000-b6f2b000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-10 15:46:40.019  6327  6327 W art     : b6f2b000-b6f2c000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6f2c000-b6f2d000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-10 15:46:40.019  6327  6327 W art     : b6f2d000-b6f2e000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-10 15:46:40.019  6327  6327 W art     : b6f2e000-b6f3c000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-10 15:46:40.019  6327  6327 W art     : b6f3c000-b6f3d000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6f3d000-b6f3e000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-10 15:46:40.019  6327  6327 W art     : b6f3e000-b6f3f000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-10 15:46:40.019  6327  6327 W art     : b6f3f000-b6f40000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:40.019  6327  6327 W art     : b6f40000-b6f42000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.019  6327  6327 W art     : b6f42000-b6f43000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.019  6327  6327 W art     : b6f43000-b6f44000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:40.019  6327  6327 W art     : b6f44000-b6f45000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-10 15:46:40.019  6327  6327 W art     : b6f45000-b6f46000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:40.019  6327  6327 W art     : b6f46000-b6f66000 r--s 00000000 00:0b 9219       /dev/__properties__
08-10 15:46:40.019  6327  6327 W art     : b6f66000-b6f67000 r--p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6f67000-b6f68000 ---p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6f68000-b6f6a000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-10 15:46:40.019  6327  6327 W art     : b6f6a000-b6f6b000 r-xp 00000000 00:00 0          [sigpage]
08-10 15:46:40.019  6327  6327 W art     : b6f6b000-b6f86000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-10 15:46:40.019  6327  6327 W art     : b6f86000-b6f87000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-10 15:46:40.019  6327  6327 W art     : b6f87000-b6f89000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-10 15:46:40.019  6327  6327 W art     : b6f89000-b6f8b000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : b6f8b000-b6f90000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-10 15:46:40.019  6327  6327 W art     : b6f90000-b6f91000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-10 15:46:40.019  6327  6327 W art     : b6f91000-b6f92000 rw-p 00000000 00:00 0 
08-10 15:46:40.019  6327  6327 W art     : bef93000-befb4000 rw-p 00000000 00:00 0          [stack]
08-10 15:46:40.019  6327  6327 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-10 15:46:40.049  6327  6327 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 15:46:40.099  6327  6327 I Radio-JNI: register_android_hardware_Radio DONE
08-10 15:46:40.109  6327  6327 E AffinityControl: AffinityControl: registerfunction enter
08-10 15:46:40.119  6327  6327 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-10 15:46:40.129   788  1569 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:40.149   788  1569 D ActivityManager: mDVFSHelper.acquire()
08-10 15:46:40.149   788  1569 D FocusedStackFrame: Set to : 0
08-10 15:46:40.149   788  1569 V WindowManager: addAppToken: AppWindowToken{b941501 token=Token{8e4dae8 ActivityRecord{55cfc0b u0 com.test.thalitest/.MainActivity t152}}} to stack=1 task=152 at 0
08-10 15:46:40.159   788   906 D SecWifiDisplayUtil: Metadata value : none
08-10 15:46:40.159   788   906 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a5d6339 V.E...... R.....ID 0,0-0,0}
08-10 15:46:40.159   788   906 D ISSUE_DEBUG: InputChannelName : dec12df Starting com.test.thalitest
08-10 15:46:40.169  6345  6345 E Zygote  : v2
08-10 15:46:40.169  6345  6345 I libpersona: KNOX_SDCARD checking this for 10004
08-10 15:46:40.169  6345  6345 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:40.169  6345  6345 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:40.169  6345  6345 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:40.169   788  1569 I ActivityManager: Start proc 6345:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-10 15:46:40.169  6345  6345 E Zygote  : accessInfo : 0
08-10 15:46:40.169   788  1569 D InputDispatcher: Focused application set to: xxxx
08-10 15:46:40.169  6345  6345 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-10 15:46:40.169   788  1569 D InputDispatcher: Focus left window: 1733
08-10 15:46:40.169   788  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-10 15:46:40.169  6327  6327 D AndroidRuntime: Shutting down VM
08-10 15:46:40.179   294   294 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-10 15:46:40.189  6345  6345 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:40.189  6345  6345 D ActivityThread: Added TimaKeyStore provider
08-10 15:46:40.199   788  1749 V WindowOrientationListener: setCurrentAppOrientation :-1
08-10 15:46:40.199   788   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:788 uid:1000
08-10 15:46:40.199   788   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-10 15:46:40.199   788   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:788 uid:1000
08-10 15:46:40.199   788   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-10 15:46:40.199   788   906 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-10 15:46:40.199   788  1749 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-10 15:46:40.209   788   865 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{dec12df u0 d0 Starting com.test.thalitest}
08-10 15:46:40.209   788  1749 D ActivityManager:  Launching com.test.thalitest, updated priority
08-10 15:46:40.219  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-10 15:46:40.219  1733  1944 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-10 15:46:40.219  1733  1733 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-10 15:46:40.229   788   906 V WindowStateAnimator: Finishing drawing window Window{dec12df u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-10 15:46:40.239   294   368 D libEGL  : eglTerminate EGLDisplay = 0xb663f64c
08-10 15:46:40.239   294   368 D libEGL  : eglTerminate EGLDisplay = 0xb663f64c
08-10 15:46:40.239   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8cb364
08-10 15:46:40.239   294   359 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-10 15:46:40.239   294  5194 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-10 15:46:40.249  2220  2240 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-10 15:46:40.249  1733  1733 V ActivityThread: updateVisibility : ActivityRecord{ad9fedc token=android.os.BinderProxy@7b8735e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-10 15:46:40.249  1733  1733 D Launcher: onTrimMemory. Level: 20
08-10 15:46:40.259   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb3a4
,08-10 15:46:40.529   788  1749 I WindowManager: Screenshot max retries 4 of Token{8e4dae8 ActivityRecord{55cfc0b u0 com.test.thalitest/.MainActivity t152}} appWin=Window{dec12df u0 d0 Starting com.test.thalitest} drawState=4
,08-10 15:46:40.539   788   862 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-10 15:46:40.539   788  2470 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-10 15:46:40.539   788  2470 V MARsPolicyManager: updateSMDBValues
,08-10 15:46:40.549   788  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-10 15:46:40.549   788   903 E MARsDBManager: updateDBAll : begin --size 1
,08-10 15:46:40.549  6345  6345 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 15:46:40.559   788  3429 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 15:46:40.579  6345  6345 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 15:46:40.579   788   903 E MARsDBManager: updateDBAll : end
,08-10 15:46:40.579  6345  6345 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-10 15:46:40.579   788   903 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-10 15:46:40.589  6345  6345 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-10 15:46:40.619  6345  6345 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 15:46:40.629  6345  6345 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 15:46:40.629  6345  6345 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 6184-6188)
08-10 15:46:40.629  6345  6345 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-10 15:46:40.649  6345  6345 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {277626e}
08-10 15:46:40.649  6345  6345 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-10 15:46:40.649  6345  6345 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 15:46:40.659  6345  6366 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-10 15:46:40.659  6345  6345 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-10 15:46:40.669  5432  5432 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
,08-10 15:46:40.669  5432  5432 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
,08-10 15:46:40.669  5432  5432 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-10 15:46:40.679  5432  5432 I art     : System.exit called, status: 0
,08-10 15:46:40.679  5432  5432 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 15:46:40.689  6345  6345 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-10 15:46:40.689  6345  6345 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-10 15:46:40.689  6345  6345 I Adreno-EGL: Build Date: 01/28/16 Thu
08-10 15:46:40.689  6345  6345 I Adreno-EGL: Local Branch: ss
08-10 15:46:40.689  6345  6345 I Adreno-EGL: Remote Branch: 
08-10 15:46:40.689  6345  6345 I Adreno-EGL: Local Patches: 
08-10 15:46:40.689  6345  6345 I Adreno-EGL: Reconstruct Branch: 
,08-10 15:46:40.699  6345  6345 D libEGL  : eglInitialize EGLDisplay = 0xbec91dac
,08-10 15:46:40.699  5396  5396 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
,08-10 15:46:40.699   788  1568 I ActivityManager: Process com.samsung.aasaservice (pid 5432)(adj 0) has died(78,766)
,08-10 15:46:40.699   788  1568 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-10 15:46:40.699   788  1568 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
,08-10 15:46:40.699   788  1568 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,08-10 15:46:40.709   788  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 15:46:40.719  6372  6372 E Zygote  : v2
08-10 15:46:40.719  6372  6372 I libpersona: KNOX_SDCARD checking this for 10014
08-10 15:46:40.719  6372  6372 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:40.719  6372  6372 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:40.719  6372  6372 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:40.719  6372  6372 E Zygote  : accessInfo : 0
08-10 15:46:40.719  6372  6372 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
,08-10 15:46:40.719   788   862 I ActivityManager: Start proc 6372:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
,08-10 15:46:40.719   788  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-10 15:46:40.739   788  1749 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-10 15:46:40.739   788  1749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-10 15:46:40.749  6372  6372 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:40.749  6372  6372 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:40.759   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ef4830 6372:com.google.android.partnersetup/u0a14}
,08-10 15:46:40.759   788  1323 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-10 15:46:40.769  6372  6372 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
,08-10 15:46:40.779  6372  6372 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-10 15:46:40.799  6345  6345 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-10 15:46:40.809  6345  6345 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 15:46:40.809  6345  6345 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-10 15:46:40.809  6345  6345 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-10 15:46:40.809  6345  6345 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-10 15:46:40.809   788  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ef4830 6372:com.google.android.partnersetup/u0a14}
,08-10 15:46:40.829  6403  6403 E Zygote  : v2
,08-10 15:46:40.829  6403  6403 I libpersona: KNOX_SDCARD checking this for 10015
08-10 15:46:40.829  6403  6403 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:40.829  6403  6403 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:40.829  6403  6403 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:40.829   788  1569 I ActivityManager: Start proc 6403:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
,08-10 15:46:40.829  6403  6403 E Zygote  : accessInfo : 0
,08-10 15:46:40.829  6403  6403 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
,08-10 15:46:40.839  6345  6345 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-10 15:46:40.849  6345  6345 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-10 15:46:40.849  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:40.849  6403  6403 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:40.859   788  1693 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a58e2de 6403:com.samsung.groupcast/u0a15}
,08-10 15:46:40.869  6403  6403 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
,08-10 15:46:40.909  6403  6403 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
,08-10 15:46:40.939  6403  6403 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
,08-10 15:46:40.949  6403  6403 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,08-10 15:46:40.949  6403  6403 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-10 15:46:40.949  6403  6403 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-10 15:46:40.949  6403  6403 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:40.949  6403  6403 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 15:46:40.949  6403  6403 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:46:40.949  6403  6403 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 15:46:40.949  6403  6403 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-10 15:46:40.949   788  1569 I ActivityManager: Killing 5232:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-10 15:46:40.959   788  1569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ecb26d 1875:com.sec.android.app.shealth:remote/u0a34}
,08-10 15:46:40.959  6345  6345 D SecWifiDisplayUtil: Metadata value : none
,08-10 15:46:40.959  6345  6345 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{34a1dfc I.E...... R.....ID 0,0-0,0}
,08-10 15:46:40.959  6345  6419 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 15:46:40.969   788   801 D ISSUE_DEBUG: InputChannelName : 40c4eea com.test.thalitest/com.test.thalitest.MainActivity
,08-10 15:46:40.969  6420  6420 E Zygote  : v2
08-10 15:46:40.969  6420  6420 I libpersona: KNOX_SDCARD checking this for 10041
08-10 15:46:40.969  6420  6420 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:40.969  6420  6420 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:40.969  6420  6420 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:40.979  6420  6420 E Zygote  : accessInfo : 0
,08-10 15:46:40.979  6420  6420 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-10 15:46:40.979   788  1746 I ActivityManager: Start proc 6420:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,08-10 15:46:40.979   788  2460 D CountryDetector: No listener is left
,08-10 15:46:40.979   788  2459 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-10 15:46:40.979   788  2459 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-10 15:46:40.979   788   788 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-10 15:46:40.979   788   788 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-10 15:46:40.989   788  1747 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-10 15:46:41.009  6345  6345 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6345
,08-10 15:46:41.009   788  1414 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6345 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 15:46:41.019   788  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-10 15:46:41.019   788  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-10 15:46:41.019   788  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-10 15:46:41.019   788  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 15:46:41.019  6420  6420 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:41.019  6420  6420 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:41.019   788  1649 I ActivityManager: Killing 5566:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,08-10 15:46:41.029  6345  6345 D SecWifiDisplayUtil: Metadata value : none
,08-10 15:46:41.029   788   800 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f2cb8d 6420:com.samsung.android.sdk.samsunglink/u0a41}
,08-10 15:46:41.039  6345  6366 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-10 15:46:41.039  6420  6420 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
08-10 15:46:41.039   294   294 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-10 15:46:41.049   788  1568 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,08-10 15:46:41.059   788   800 D InputDispatcher: Focus entered window: 6345
,08-10 15:46:41.059   788   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:788 uid:1000
,08-10 15:46:41.059  6345  6419 D libEGL  : eglInitialize EGLDisplay = 0x9c9ff7c4
08-10 15:46:41.059  6345  6419 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 15:46:41.059   788   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-10 15:46:41.059   788   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:788 uid:1000
08-10 15:46:41.059   788   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-10 15:46:41.099  6345  6345 V ActivityThread: updateVisibility : ActivityRecord{4ace7 token=android.os.BinderProxy@557ceef {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-10 15:46:41.099  6345  6345 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-10 15:46:41.109  6345  6345 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-10 15:46:41.129   788   801 V WindowStateAnimator: Finishing drawing window Window{40c4eea u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-10 15:46:41.129  6345  6345 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-10 15:46:41.129   788  1649 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-10 15:46:41.139   788   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-10 15:46:41.139   788   788 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-10 15:46:41.139   788   788 I KnoxTimeoutHandler: SD activityfalse
,08-10 15:46:41.139   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8cb364
,08-10 15:46:41.149   788   906 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +613ms (total +992ms)
,08-10 15:46:41.149   788   906 D ActivityManager: mDVFSHelper.release()
,08-10 15:46:41.149   788   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{55cfc0b u0 com.test.thalitest/.MainActivity t152} time:96704
,08-10 15:46:41.149   788   906 D ViewRootImpl: #3 mView = null
,08-10 15:46:41.149   294   368 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-10 15:46:41.149   294  5194 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-10 15:46:41.149   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb3a4
,08-10 15:46:41.169  6345  6345 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-10 15:46:41.169  6345  6345 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@557ceef time:96720
,08-10 15:46:41.169  6420  6420 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-10 15:46:41.179  6420  6420 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 15:46:41.189  6345  6440 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 15:46:41.189  6345  6440 D libEGL  : eglInitialize EGLDisplay = 0x9b1d13ec
,08-10 15:46:41.239  6345  6345 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6345
,08-10 15:46:41.249  6420  6420 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-10 15:46:41.259  6420  6420 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-10 15:46:41.269   788  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.269   788  1414 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-10 15:46:41.269   788  1649 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.279   788  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.279   788  1784 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.279   788  1749 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.279   788  1568 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.279   788   800 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.289   788   801 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.289   788  1746 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-10 15:46:41.389  6345  6345 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 15:46:41.389  6420  6420 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-10 15:46:41.399  6420  6420 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-10 15:46:41.399  6420  6420 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-10 15:46:41.399  6420  6420 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-10 15:46:41.399  6420  6420 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-10 15:46:41.399  6420  6420 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:41.399  6420  6420 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 15:46:41.399  6420  6420 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:46:41.399  6420  6420 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 15:46:41.399  6420  6420 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-10 15:46:41.399   788  2459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53a53f1 1652:android.process.acore/u0a19}
,08-10 15:46:41.409  5108  5108 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-10 15:46:41.409   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1490c34 5108:com.sec.android.gallery3d/u0a47}
,08-10 15:46:41.419   788  1784 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 15:46:41.439  6457  6457 E Zygote  : v2
08-10 15:46:41.439  6457  6457 I libpersona: KNOX_SDCARD checking this for 10050
08-10 15:46:41.439  6457  6457 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:41.439  6457  6457 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:41.439  6457  6457 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:41.439   788  1749 I ActivityManager: Start proc 6457:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-10 15:46:41.439  6457  6457 E Zygote  : accessInfo : 0
08-10 15:46:41.439  6457  6457 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-10 15:46:41.469  6457  6457 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:41.469  6457  6457 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:41.479   788  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3a70ef2 6457:com.sec.android.app.myfiles/u0a50}
,08-10 15:46:41.489  6457  6457 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
08-10 15:46:41.489   788  1746 I ActivityManager: Killing 5126:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-10 15:46:41.509   788  1693 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-10 15:46:41.519  6457  6457 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-10 15:46:41.519  6345  6470 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1699743440
,08-10 15:46:41.529  6345  6470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 15:46:41.529  6345  6470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 15:46:41.529  6345  6470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 15:46:41.529  6345  6470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 15:46:41.529  6345  6470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 15:46:41.529  6345  6470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1bd0f5 added. We now have 1 listener(s)
,08-10 15:46:41.529  6345  6470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-10 15:46:41.529  6345  6470 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-10 15:46:41.539  6345  6470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 15:46:41.539  6345  6470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 15:46:41.539  6345  6470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d118 added. We now have 1 listener(s)
08-10 15:46:41.539  6345  6470 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 15:46:41.539  6345  6470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 15:46:41.539  6345  6470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 15:46:41.539  6345  6470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 15:46:41.539  6345  6470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 15:46:41.539  6345  6470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 15:46:41.549  6345  6470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:46:41.549  6345  6470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-10 15:46:41.549   788  3430 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:41.549  6345  6470 D BluetoothAdapter: STATE_ON
,08-10 15:46:41.549  6345  6470 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:46:41.549  6345  6470 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 15:46:41.549  6345  6470 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 15:46:41.549  6345  6470 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 15:46:41.559  6345  6345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:46:41.559  6345  6345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:46:41.559  6345  6470 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 15:46:41.579  6457  6457 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-10 15:46:41.579  6345  6345 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 15:46:41.599   788  1784 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{42fef79 2786:com.android.settings/1000}
,08-10 15:46:41.609   327   327 E installd: system dir 0 : /system/app/
08-10 15:46:41.609   327   327 E installd: system dir 1 : /system/priv-app/
08-10 15:46:41.609   327   327 E installd: system dir 2 : /vendor/app/
08-10 15:46:41.609   327   327 E installd: system dir 3 : /oem/app/
,08-10 15:46:41.619   788   800 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{42fef79 2786:com.android.settings/1000}
,08-10 15:46:41.639  6474  6474 E Zygote  : v2
08-10 15:46:41.639  6474  6474 I libpersona: KNOX_SDCARD checking this for 10169
08-10 15:46:41.639  6474  6474 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:41.639  6474  6474 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:41.639  6474  6474 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:41.639  6474  6474 E Zygote  : accessInfo : 0
,08-10 15:46:41.639  6474  6474 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-10 15:46:41.639   788   801 I ActivityManager: Start proc 6474:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-10 15:46:41.649   788   930 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-10 15:46:41.669  6474  6474 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:41.669  6474  6474 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:41.669   788  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d3652d8 6474:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-10 15:46:41.679  6474  6474 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-10 15:46:41.699  6474  6474 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-10 15:46:41.709  6488  6488 E Zygote  : v2
08-10 15:46:41.709  6488  6488 I libpersona: KNOX_SDCARD checking this for 10210
08-10 15:46:41.709  6488  6488 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:41.709  6488  6488 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:41.709  6488  6488 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:41.719  6488  6488 E Zygote  : accessInfo : 0
,08-10 15:46:41.719  6488  6488 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-10 15:46:41.719   788   862 I ActivityManager: Start proc 6488:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-10 15:46:41.729   788  1569 I ActivityManager: Killing 5146:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-10 15:46:41.729   788  1569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9aab648 1717:com.android.phone/1001}
,08-10 15:46:41.759   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f89394 1818:com.google.android.googlequicksearchbox:search/u0a61}
,08-10 15:46:41.759   788  1414 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-10 15:46:41.769  6488  6488 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:41.769  6488  6488 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:41.789   788  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f89394 1818:com.google.android.googlequicksearchbox:search/u0a61}
,08-10 15:46:41.789  6488  6488 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-10 15:46:41.799   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9aa0116 6246:com.samsung.android.sm.provider/1000}
,08-10 15:46:41.799  6488  6488 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-10 15:46:41.799  6488  6488 D AASAservice: onCreate()
,08-10 15:46:41.809  5396  5396 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-10 15:46:41.829  6502  6502 E Zygote  : v2
08-10 15:46:41.829  6502  6502 I libpersona: KNOX_SDCARD checking this for 5012
08-10 15:46:41.829  6502  6502 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:41.829  6502  6502 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-10 15:46:41.829  6502  6502 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:41.829  6502  6502 E Zygote  : accessInfo : 0
08-10 15:46:41.829  6502  6502 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-10 15:46:41.829   788  1693 I ActivityManager: Start proc 6502:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-10 15:46:41.839   788  1693 I ActivityManager: Killing 5173:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-10 15:46:41.849  1818  6500 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-10 15:46:41.859  6502  6502 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:41.859  6502  6502 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:41.869   788  2459 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-10 15:46:41.879   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6bb5a97 6502:com.samsung.android.sm.devicesecurity/5012}
,08-10 15:46:41.889  6502  6502 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-10 15:46:41.909  6502  6502 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-10 15:46:41.969   788  2460 I ActivityManager: Killing 4639:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-10 15:46:41.969   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9bac84 3187:com.android.contacts/u0a19}
,08-10 15:46:41.989  1818  6500 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-10 15:46:41.999   788   798 I art     : Background partial concurrent mark sweep GC freed 149448(8MB) AllocSpace objects, 6(1836KB) LOS objects, 27% free, 42MB/58MB, paused 1.602ms total 125.301ms
,08-10 15:46:41.999  1456  1456 D Recents : onTaskStackChanged
,08-10 15:46:42.009  6514  6514 E Zygote  : v2
08-10 15:46:42.009   788   801 I ActivityManager: Start proc 6514:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-10 15:46:42.009  6514  6514 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:42.009  6514  6514 I libpersona: KNOX_SDCARD checking this for 10049
08-10 15:46:42.009  6514  6514 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:42.009  6514  6514 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:42.009  6514  6514 E Zygote  : accessInfo : 0
08-10 15:46:42.009  6514  6514 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-10 15:46:42.029  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-10 15:46:42.039   788  1747 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-10 15:46:42.049  6514  6514 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 15:46:42.049  6514  6514 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:42.059  1818  6500 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-10 15:46:42.069   788  1568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b29c484 6514:com.android.mms/u0a49}
,08-10 15:46:42.079  6514  6514 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-10 15:46:42.119  6514  6514 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-10 15:46:42.129  6514  6514 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-10 15:46:42.169  1818  6500 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 315 ms] updated apps [took 314 ms] 
,08-10 15:46:42.189  6514  6514 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-10 15:46:42.189  6514  6527 D Mms/ArtClassLoader: init before art first
,08-10 15:46:42.199  6514  6528 D Mms/ArtClassLoader: init before art second
,08-10 15:46:42.209  6514  6529 D Mms/ArtClassLoader: init before art third
,08-10 15:46:42.209  6514  6514 D Mms/TelephonyPermission: start operation mode monitor
08-10 15:46:42.209  6514  6514 D Mms/TelephonyPermission: User ID is null set current User Id
,08-10 15:46:42.219  6514  6514 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-10 15:46:42.229  6514  6514 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-10 15:46:42.229  6514  6529 D Mms/ArtClassLoader: init [DONE] art
,08-10 15:46:42.249  6514  6514 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-10 15:46:42.249  6514  6514 D Mms/TelephonyPermission: isDefault true
,08-10 15:46:42.249  6514  6514 D Mms/MmsApp: onCreate() com.android.mms
,08-10 15:46:42.269  6514  6514 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-10 15:46:42.289  6514  6514 D Mms/MmsApp: [start]    initCountryIso consume time = 99.013906
,08-10 15:46:42.289   788  1693 D CountryDetector: The first listener is added
,08-10 15:46:42.299  6514  6514 D Mms/MmsApp: [end]    initCountryIso consume time = 6.611146
,08-10 15:46:42.299  6514  6514 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.256979
,08-10 15:46:42.309  6514  6514 D Mms/MmsConfig: before partial update
,08-10 15:46:42.339  6345  6472 W jxcore-log: Initializing JXcore engine
,08-10 15:46:42.339  6345  6472 W jxcore-log: JXcore engine is ready
,08-10 15:46:42.349  6514  6527 D Mms/ArtClassLoader: init [DONE] art
,08-10 15:46:42.389  2374  2374 E audit   : type=1400 msg=audit(1470836802.389:288): avc:  denied  { ioctl } for  pid=6472 comm="Thread-884" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-10 15:46:42.389  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:42.389  2374  2374 E audit   : type=1300 msg=audit(1470836802.389:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a0ff3c8 items=0 ppid=350 ppcomm=main pid=6472 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-884" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-10 15:46:42.389  2374  2374 E audit   : type=1327 msg=audit(1470836802.389:288): proctitle="com.test.thalitest"
08-10 15:46:42.389  2374  2374 E audit   : type=1320 msg=audit(1470836802.389:288): 
,08-10 15:46:42.389  2374  2374 E audit   : type=1400 msg=audit(1470836802.389:289): avc:  denied  { ioctl } for  pid=6472 comm="Thread-884" path="socket:[40389]" dev="sockfs" ino=40389 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-10 15:46:42.389  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:42.389  2374  2374 E audit   : type=1300 msg=audit(1470836802.389:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a0ff3c8 items=0 ppid=350 ppcomm=main pid=6472 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-884" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-10 15:46:42.389  2374  2374 E audit   : type=1327 msg=audit(1470836802.389:289): proctitle="com.test.thalitest"
08-10 15:46:42.389  2374  2374 E audit   : type=1320 msg=audit(1470836802.389:289): 
,08-10 15:46:42.389  6514  6514 D Mms/MmsConfig: Load Resize quality : 80
,08-10 15:46:42.399  6514  6528 D Mms/ArtClassLoader: init [DONE] art
,08-10 15:46:42.399  6345  6472 W jxcore-log: Starting JXcore engine
,08-10 15:46:42.399  6514  6514 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-10 15:46:42.399  6514  6514 D EasySignUpManager_1.0.5: isAuth is false
08-10 15:46:42.399  6514  6514 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-10 15:46:42.399  6514  6514 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-10 15:46:42.399  6514  6514 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-10 15:46:42.399  6514  6514 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-10 15:46:42.399  6514  6514 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-10 15:46:42.399  6514  6514 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-10 15:46:42.399  6514  6514 D EasySignUpManager_1.0.5: isAuth is false
08-10 15:46:42.399  6514  6514 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-10 15:46:42.399  6514  6514 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-10 15:46:42.409  1717  1938 D TP/MmsSmsProvider: query, match:2117, calling pid = 6514, accessRestricted = false
,08-10 15:46:42.419  1717  1938 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.079 ms
,08-10 15:46:42.419  6514  6514 E CscParser: mps_code.dat does not exist
08-10 15:46:42.419  6514  6514 E CscParser: customer_path =/system/csc/customer.xml
08-10 15:46:42.419  6514  6514 E CscParser: fileName + /system/csc/customer.xml
,08-10 15:46:42.429  6514  6514 E CscParser: mps_code.dat does not exist
08-10 15:46:42.429  6514  6514 E CscParser: customer_path =/system/csc/customer.xml
08-10 15:46:42.429  6514  6514 E CscParser: fileName + /system/csc/customer.xml
,08-10 15:46:42.439  6514  6514 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-10 15:46:42.439  6514  6514 D Mms/MmsConfig:  enable multiwindow = true
,08-10 15:46:42.439  6514  6514 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-10 15:46:42.439  6514  6514 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-10 15:46:42.439  6514  6514 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-10 15:46:42.439  6514  6514 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-10 15:46:42.439  6514  6514 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-10 15:46:42.439  6514  6514 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-10 15:46:42.439  6514  6514 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-10 15:46:42.449  6514  6514 D Mms/MmsConfig: [end]    init() consume time = 149.708282
,08-10 15:46:42.449  6514  6514 D Mms/Contact: [start]    init() consume time = 4.087239
,08-10 15:46:42.459  1717  2309 D TP/MmsSmsProvider: query, match:13, calling pid = 6514, accessRestricted = false
,08-10 15:46:42.459  1717  2309 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.252 ms
,08-10 15:46:42.459  6514  6514 D Mms/Contact: [end]    init consume time = 12.528333
,08-10 15:46:42.469  6514  6514 D Mms:transaction: roaming -> false (slotId = 0)
08-10 15:46:42.469  6514  6514 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-10 15:46:42.469  6514  6514 D Mms:transaction: auto download without roaming -> true
08-10 15:46:42.469  6514  6514 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-10 15:46:42.469  6514  6514 D Mms:transaction: roaming -> false (slotId = 1)
08-10 15:46:42.469  6514  6514 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-10 15:46:42.469  6514  6514 D Mms:transaction: auto download without roaming -> true
08-10 15:46:42.469  6514  6514 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-10 15:46:42.469  6514  6514 D Mms:transaction: auto download during roaming secondary -> false
08-10 15:46:42.469  6514  6514 D Mms:transaction: mAutoDownload ------> true
,08-10 15:46:42.469  6514  6536 D Mms/DraftCache: [start]    rebuildCache consume time = 12.192344
,08-10 15:46:42.479  1717  1731 D TP/MmsSmsProvider: query, match:12, calling pid = 6514, accessRestricted = false
,08-10 15:46:42.479  1717  1731 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.316 ms
,08-10 15:46:42.489  6514  6536 D Mms/DraftCache: [end]    rebuildCache consume time = 11.008959
,08-10 15:46:42.489  6345  6472 W jxcore-log: Platform android
08-10 15:46:42.489  6345  6472 W jxcore-log: 
08-10 15:46:42.489  6345  6472 W jxcore-log: Process ARCH arm
08-10 15:46:42.489  6345  6472 W jxcore-log: 
,08-10 15:46:42.489  6514  6514 D ComposerPerformance: 1470836802499 ms / [DONE] Composer constructor
,08-10 15:46:42.489  6514  6538 D Mms/Conversation: [start]    init() consume time = 8.341614
,08-10 15:46:42.489  1717  2285 D TP/MmsSmsProvider: delete, match:1, calling pid = 6514
08-10 15:46:42.489  1717  2285 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-10 15:46:42.489  1717  2285 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-10 15:46:42.499  1717  2285 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-10 15:46:42.499  1717  2285 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-10 15:46:42.499  1717  2285 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-10 15:46:42.499  6514  6514 D CII     : Log Level [5]
,08-10 15:46:42.499  6514  6514 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-10 15:46:42.499  6514  6514 I Mms/ReservationManager: ReservationManager()
08-10 15:46:42.499  6514  6514 I Mms/ReservationManager: resetAfterConnected()
,08-10 15:46:42.499  1717  2285 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-10 15:46:42.509  1717  2309 D TP/MmsSmsProvider: query, match:7, calling pid = 6514, accessRestricted = false
,08-10 15:46:42.509  1717  2309 D TP/MmsSmsProvider: query, match 7:Elapsed time : 3.110 ms
,08-10 15:46:42.509  1717  2285 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-10 15:46:42.509  1717  2285 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-10 15:46:42.509  1717  2285 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-10 15:46:42.509  1717  2285 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 5.602 ms
08-10 15:46:42.509  1717  2285 D TP/MmsSmsProvider: need read changed broadcast:false
,08-10 15:46:42.519  6514  6538 D Mms/Conversation: [end]    init consume time = 21.780782
,08-10 15:46:42.519  6514  6514 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-10 15:46:42.519  6514  6538 D Mms/MessagingNotification: [start]    init() consume time = 3.26776
,08-10 15:46:42.519  6514  6538 D Mms/MessagingNotification: [end]    init consume time = 1.631927
,08-10 15:46:42.519  6514  6514 D Mms/MmsApp: [end]    onCreate() consume time = 1.602291
,08-10 15:46:42.519  6514  6514 D Mms/MmsApp: [end]    onCreate() consume time = 0.216406
,08-10 15:46:42.529  6514  6540 D Mms/Synchronizer: [start]    doSync consume time = 4.248595
,08-10 15:46:42.529  6514  6539 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.985312
,08-10 15:46:42.529  6514  6514 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-10 15:46:42.529  6514  6514 D Mms:transaction: roaming ------> false, mSimSlot = 0
,08-10 15:46:42.529  1717  1730 D TP/MmsSmsProvider: update, match:300, calling pid = 6514
08-10 15:46:42.529  1717  1730 V TP/MmsSmsProvider: syncDBData start
,08-10 15:46:42.529  1717  1730 V TP/MmsSmsProvider: syncDBData sms end
,08-10 15:46:42.529  6514  6514 D Mms:transaction: roaming -> false (slotId = 0)
08-10 15:46:42.529  6514  6514 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-10 15:46:42.529  6514  6514 D Mms:transaction: auto download without roaming -> true
,08-10 15:46:42.529  1717  1731 D TP/MmsSmsProvider: query, match:0, calling pid = 6514, accessRestricted = false
08-10 15:46:42.529  1717  1731 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-10 15:46:42.529  6514  6514 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-10 15:46:42.529  6514  6514 D Mms:transaction: mAutoDownload ------> true
08-10 15:46:42.529  1717  1730 V TP/MmsSmsProvider: syncDBData mms end
,08-10 15:46:42.539  1717  1730 V TP/MmsSmsProvider: syncDBData end
,08-10 15:46:42.539  1717  1730 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.947 ms
,08-10 15:46:42.539  1717  1731 D TP/MmsSmsProvider: query, match 0:Elapsed time : 3.730 ms
,08-10 15:46:42.539  6541  6541 E Zygote  : v2
08-10 15:46:42.539  6541  6541 I libpersona: KNOX_SDCARD checking this for 1000
08-10 15:46:42.539  6541  6541 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:42.539  6541  6541 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:42.539  6541  6541 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:42.539  6541  6541 E Zygote  : accessInfo : 0
,08-10 15:46:42.539   788   801 I ActivityManager: Start proc 6541:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-10 15:46:42.559  1717  2285 D TP/MmsSmsProvider: query, match:400, calling pid = 6514, accessRestricted = false
,08-10 15:46:42.559  6130  6152 D BadgeProvider: query, [selection] : package=?
,08-10 15:46:42.569  6514  6540 D Mms/Synchronizer: [end]    doSync consume time = 38.008802
,08-10 15:46:42.569  6514  6538 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-10 15:46:42.569  6541  6541 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:42.569  6541  6541 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:42.579   788  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{57f2a20 6541:com.samsung.android.bbc.bbcagent/1000}
,08-10 15:46:42.579  1717  1731 D TP/SmsProvider: query,matched:26, calling pid = 6514
,08-10 15:46:42.589  6514  6539 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 20.612552
,08-10 15:46:42.589  1717  1731 D TP/SmsProvider: query, match 26:Elapsed time : 1.708 ms
,08-10 15:46:42.599  6541  6541 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-10 15:46:42.599  1717  1938 D TP/MmsSmsProvider: query, match:6, calling pid = 6514, accessRestricted = false
,08-10 15:46:42.599  1717  1938 D TP/MmsSmsProvider: query, match 6:Elapsed time : 0.988 ms
,08-10 15:46:42.629  6541  6541 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
08-10 15:46:42.629  6553  6553 I libpersona: KNOX_SDCARD checking this for 10024
08-10 15:46:42.629  6553  6553 E Zygote  : v2
08-10 15:46:42.629  6553  6553 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:42.629  6553  6553 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:42.629  6553  6553 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:42.629   788  1746 I ActivityManager: Start proc 6553:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-10 15:46:42.629  6553  6553 E Zygote  : accessInfo : 0
08-10 15:46:42.629  6553  6553 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-10 15:46:42.659  6553  6553 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 15:46:42.659  6553  6553 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:42.669  6565  6565 E Zygote  : v2
,08-10 15:46:42.669  6565  6565 I libpersona: KNOX_SDCARD checking this for 10097
08-10 15:46:42.669  6565  6565 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:42.669  6565  6565 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:42.669  6565  6565 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:42.669  6565  6565 E Zygote  : accessInfo : 0
,08-10 15:46:42.669  6565  6565 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-10 15:46:42.679   788  1568 I ActivityManager: Start proc 6565:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,08-10 15:46:42.679   788  1568 I ActivityManager: Killing 5489:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-10 15:46:42.689   788  2460 I ActivityManager: Killing 5060:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-10 15:46:42.699  6565  6565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 15:46:42.699  6565  6565 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:42.709  6345  6472 I jxcore-log: JXcore Cordova bridge is ready!
08-10 15:46:42.709  6345  6472 I jxcore-log: 
,08-10 15:46:42.709  6345  6472 W jxcore-log: JXcore engine is started
,08-10 15:46:42.709   788  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{abadfd9 6565:com.google.android.apps.docs/u0a97}
,08-10 15:46:42.709  6345  6470 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 15:46:42.709  6345  6345 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 15:46:42.749  6553  6553 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-10 15:46:42.749  6565  6565 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-10 15:46:42.749   788  2459 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-10 15:46:42.769   788  1749 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-10 15:46:42.769   788  6227 I HarmonyEASService: Updating for all 1
,08-10 15:46:42.779  6553  6553 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-10 15:46:42.789  6565  6565 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-10 15:46:42.829  6553  6553 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-10 15:46:42.839  6514  6538 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-10 15:46:42.859  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-10 15:46:42.859  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-10 15:46:42.859  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-10 15:46:42.869  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-10 15:46:42.879  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-10 15:46:42.879  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-10 15:46:42.879  6553  6553 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-10 15:46:43.059  6565  6579 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-10 15:46:43.059  6565  6579 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 15:46:43.059  6565  6579 I GAv4    :   adb logcat -s GAv4
,08-10 15:46:43.079  6565  6579 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-10 15:46:43.079   788  1649 V AlarmManager:  remove PendingIntent] PendingIntent{ef0a095: PendingIntentRecord{59ff5aa com.google.android.apps.docs broadcastIntent}}
,08-10 15:46:43.089  6565  6579 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 15:46:43.089  6565  6579 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 15:46:43.089  6565  6585 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 15:46:43.159  4270  5034 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-10 15:46:43.169  6565  6565 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-10 15:46:43.179  6565  6565 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-10 15:46:43.199  6565  6579 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-10 15:46:43.199  6565  6579 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,08-10 15:46:43.199  6565  6579 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-10 15:46:43.199  6565  6579 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-10 15:46:43.199   788  1368 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/152_task.xml.bak
,08-10 15:46:43.219  4270  5034 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-10 15:46:43.239  6591  6591 E Zygote  : v2
08-10 15:46:43.239  6591  6591 I libpersona: KNOX_SDCARD checking this for 10098
08-10 15:46:43.239  6591  6591 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:43.239  6591  6591 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:43.239  6591  6591 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:43.239   788  1749 I ActivityManager: Start proc 6591:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-10 15:46:43.239  6591  6591 E Zygote  : accessInfo : 0
08-10 15:46:43.239  6591  6591 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-10 15:46:43.249   788  1749 I ActivityManager: Killing 5613:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-10 15:46:43.269   788   800 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-10 15:46:43.269  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 15:46:43.279  6591  6591 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:43.279  6282  6282 D CAR.SERVICE: onUnbind
08-10 15:46:43.279  6282  6282 D CAR.SERVICE: CSB onClientsDisconnected
08-10 15:46:43.279  6282  6282 D CAR.SERVICE: tearDown
08-10 15:46:43.279  6282  6282 D CAR.SERVICE: tearDownCarState
08-10 15:46:43.279  6282  6282 D CAR.SERVICE: Skip, car not connected.
08-10 15:46:43.279  6282  6282 D CAR.SERVICE: tearDownClientState
,08-10 15:46:43.279  6282  6282 D CAR.SERVICE: requestStop
,08-10 15:46:43.289   788  1749 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{edfc276 6591:com.sec.android.automotive.drivelink/u0a98}
,08-10 15:46:43.289  6282  6282 D CAR.SERVICE: onDestroy
,08-10 15:46:43.289  6282  6282 D CAR.SERVICE: tearDown
08-10 15:46:43.289  6282  6282 D CAR.SERVICE: tearDownCarState
08-10 15:46:43.289  6282  6282 D CAR.SERVICE: Skip, car not connected.
08-10 15:46:43.289  6282  6282 D CAR.SERVICE: tearDownClientState
08-10 15:46:43.289  6282  6282 D CAR.SERVICE: requestStop
,08-10 15:46:43.299  6591  6591 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-10 15:46:43.299  6282  6282 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@c4d4c3b that was originally bound here
08-10 15:46:43.299  6282  6282 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@c4d4c3b that was originally bound here
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 15:46:43.299  6282  6282 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-10 15:46:43.299   788  1747 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@fc9f077
,08-10 15:46:43.319  6591  6591 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-10 15:46:43.319  4270  5034 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-10 15:46:43.349  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-10 15:46:43.359  6591  6591 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-10 15:46:43.369   788  2460 V AlarmManager:  remove PendingIntent] PendingIntent{c38aa4e: PendingIntentRecord{e58776f com.sec.android.automotive.drivelink broadcastIntent}}
,08-10 15:46:43.379  6591  6591 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-10 15:46:43.379  6591  6607 I GMPM    : App measurement is starting up
,08-10 15:46:43.389  6591  6607 E GMPM    : getGoogleAppId failed with status: 10
,08-10 15:46:43.399  6591  6607 E GMPM    : Uploading is not possible. App measurement disabled
,08-10 15:46:43.399   788  1414 V AlarmManager:  remove PendingIntent] PendingIntent{ee8dc7c: PendingIntentRecord{e58776f com.sec.android.automotive.drivelink broadcastIntent}}
,08-10 15:46:43.409  6591  6591 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-10 15:46:43.409  6591  6591 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-10 15:46:43.419  6565  6580 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-10 15:46:43.459  6613  6613 E Zygote  : v2
08-10 15:46:43.459  6613  6613 I libpersona: KNOX_SDCARD checking this for 10032
08-10 15:46:43.459  6613  6613 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:43.459  6613  6613 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:43.459  6613  6613 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:43.459  6613  6613 E Zygote  : accessInfo : 0
,08-10 15:46:43.459  6613  6613 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-10 15:46:43.459   788  1693 I ActivityManager: Start proc 6613:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-10 15:46:43.459   788  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-10 15:46:43.479  6613  6613 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:43.479  6613  6613 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:43.489  6565  6580 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-10 15:46:43.489   788  1323 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-10 15:46:43.489  6613  6613 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-10 15:46:43.499  6565  6580 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-10 15:46:43.499  6565  6580 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-10 15:46:43.509  6613  6613 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-10 15:46:43.509  6565  6580 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-10 15:46:43.529  6565  6580 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 15:46:43.589  6591  6591 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-10 15:46:43.589  6591  6591 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-10 15:46:43.599  6591  6591 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-10 15:46:43.609  6591  6591 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDWed Aug 10 15:46:43 GMT+02:00 2016
,08-10 15:46:43.619  6613  6613 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-10 15:46:43.629   788  2459 I ActivityManager: Start proc 6627:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-10 15:46:43.629  6627  6627 E Zygote  : v2
08-10 15:46:43.629  6627  6627 I libpersona: KNOX_SDCARD checking this for 1000
08-10 15:46:43.629  6627  6627 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:43.629  6627  6627 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:43.629  6627  6627 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:43.629  6627  6627 E Zygote  : accessInfo : 0
08-10 15:46:43.629   788  2459 I ActivityManager: Killing 5384:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-10 15:46:43.629   788  2459 I ActivityManager: Killing 5647:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-10 15:46:43.649   788  1569 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-10 15:46:43.649   788  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-10 15:46:43.659  6627  6627 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:43.659  6627  6627 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:43.659  6591  6591 D DialogFlow: initQueue()
,08-10 15:46:43.669   788  1649 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{261e567 6627:com.samsung.android.app.filterinstaller/1000}
,08-10 15:46:43.669  6613  6613 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-10 15:46:43.669  6627  6627 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-10 15:46:43.679  6627  6627 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-10 15:46:43.689  6627  6627 E FilterPackageIntentReceiver: This package is not a effect filter
,08-10 15:46:43.699  6643  6643 E Zygote  : v2
,08-10 15:46:43.699  6643  6643 I libpersona: KNOX_SDCARD checking this for 1000
08-10 15:46:43.699  6643  6643 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:43.699   788  2460 I ActivityManager: Start proc 6643:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-10 15:46:43.699  6643  6643 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:43.699  6643  6643 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:43.699   788  2460 I ActivityManager: Killing 5680:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-10 15:46:43.709   788  2459 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-10 15:46:43.719   788  1693 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-10 15:46:43.729  6643  6643 E Zygote  : accessInfo : 0
,08-10 15:46:43.749  6643  6643 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 15:46:43.749  6643  6643 D ActivityThread: Added TimaKeyStore provider
08-10 15:46:43.749  6613  6613 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-10 15:46:43.749  6613  6613 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-10 15:46:43.749   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{34a42fe 6643:com.samsung.helphub/1000}
,08-10 15:46:43.759  6613  6613 D DialogFlow: initQueue()
,08-10 15:46:43.759  6643  6643 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-10 15:46:43.769  6643  6643 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-10 15:46:43.799   788  3429 D SSRM:n  : SIOP:: AP = 490, PST = 459, CUR = 450, LCD = 0
,08-10 15:46:43.819  6655  6655 E Zygote  : v2
,08-10 15:46:43.819  6655  6655 I libpersona: KNOX_SDCARD checking this for 1000
08-10 15:46:43.819  6655  6655 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:43.819  6655  6655 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-10 15:46:43.819   788  1784 I ActivityManager: Start proc 6655:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-10 15:46:43.819   788  1784 I ActivityManager: Killing 4742:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
08-10 15:46:43.819  6655  6655 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:43.819  6655  6655 E Zygote  : accessInfo : 0
,08-10 15:46:43.839  6655  6655 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:43.839  6655  6655 D ActivityThread: Added TimaKeyStore provider
08-10 15:46:43.839   788  1320 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-10 15:46:43.849   788  1569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{57c1a5f 6655:com.samsung.android.app.mirrorlink/1000}
,08-10 15:46:43.859  6655  6655 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-10 15:46:43.879  6655  6655 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-10 15:46:43.909  6655  6655 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-10 15:46:43.909  6655  6655 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-10 15:46:43.909   788  1784 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d72cd8 5796:com.google.android.apps.plus/u0a134}
,08-10 15:46:43.919   788  1569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d72cd8 5796:com.google.android.apps.plus/u0a134}
,08-10 15:46:43.939   788  1746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d72cd8 5796:com.google.android.apps.plus/u0a134}
,08-10 15:46:43.959   788  2459 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-10 15:46:43.969   788  1649 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-10 15:46:43.969   788  1749 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-10 15:46:43.969   788  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-10 15:46:43.979   788  1569 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-10 15:46:43.979   788  2460 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-10 15:46:43.979   788  1320 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-10 15:46:43.989   788   800 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-10 15:46:44.009   788  1414 I ActivityManager: Start proc 6669:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-10 15:46:44.009  6669  6669 E Zygote  : v2
08-10 15:46:44.009  6669  6669 I libpersona: KNOX_SDCARD checking this for 10165
08-10 15:46:44.009  6669  6669 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:44.009  6669  6669 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:44.009  6669  6669 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:44.009  6669  6669 E Zygote  : accessInfo : 0
,08-10 15:46:44.009  6669  6669 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-10 15:46:44.009   788  1414 I ActivityManager: Killing 5664:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-10 15:46:44.029   788  1320 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-10 15:46:44.039  6669  6669 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-10 15:46:44.039  6669  6669 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:44.049   788  2459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b83910a 6669:com.sec.kidsplat.installer/u0a165}
,08-10 15:46:44.049  6669  6669 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-10 15:46:44.059  6669  6669 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-10 15:46:44.069   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b83910a 6669:com.sec.kidsplat.installer/u0a165}
,08-10 15:46:44.079  6669  6669 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-10 15:46:44.089  6682  6682 E Zygote  : v2
,08-10 15:46:44.089  6682  6682 I libpersona: KNOX_SDCARD checking this for 10142
08-10 15:46:44.089  6682  6682 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:44.089  6682  6682 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-10 15:46:44.089   788  1649 I ActivityManager: Start proc 6682:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-10 15:46:44.089  6682  6682 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-10 15:46:44.089  6682  6682 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:44.089  6682  6682 E Zygote  : accessInfo : 64
08-10 15:46:44.089  6682  6682 E Zygote  : isSdpEnabledProcess - SDP enabled
,08-10 15:46:44.089  6682  6682 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
,08-10 15:46:44.089  6682  6682 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
08-10 15:46:44.089   788  1649 I ActivityManager: Killing 5781:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-10 15:46:44.109   788  1568 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-10 15:46:44.119  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:44.119  6682  6682 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:44.129   788   801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f1fd7b 6682:com.sec.android.app.sbrowser/u0a142}
,08-10 15:46:44.139  6682  6682 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-10 15:46:44.159  6682  6682 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-10 15:46:44.219  6682  6682 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-10 15:46:44.229  6682  6682 D ManifestProvider: onCreate()
,08-10 15:46:44.239  6682  6682 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-10 15:46:44.239  6682  6682 I SBrowserUtils: getSystemProperty of country_code : Poland
08-10 15:46:44.239  6682  6682 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-10 15:46:44.239  6682  6682 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-10 15:46:44.249  6682  6682 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-10 15:46:44.249  6682  6682 D [MM]MHDataBaseProvider: onCreate()
,08-10 15:46:44.259  6682  6682 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@8f9fb2b)
,08-10 15:46:44.279   788  1320 I ActivityManager: Killing 5866:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-10 15:46:44.279   788  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d0f05c 1975:com.google.android.gms.persistent/u0a11}
,08-10 15:46:44.289   788  1649 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb3b115 4270:com.google.android.gms/u0a11}
,08-10 15:46:44.299  4270  6697 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 15:46:44.299   788  1784 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-10 15:46:44.299  4270  6696 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-10 15:46:44.309  4270  6697 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 15:46:44.319  4270  4270 D AsyncTaskServiceImpl: Submit a task: nzm
,08-10 15:46:44.329  4270  6697 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 15:46:44.329  4270  6697 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-10 15:46:44.329   788   800 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d0f05c 1975:com.google.android.gms.persistent/u0a11}
,08-10 15:46:44.349  4270  5059 D nzm     : Processing package: com.test.thalitest
,08-10 15:46:44.349   788   801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb3b115 4270:com.google.android.gms/u0a11}
,08-10 15:46:44.359  4270  4270 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 15:46:44.379  4270  5059 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-10 15:46:44.379  4270  5059 D nzm     : Found info for package com.test.thalitest in db.
,08-10 15:46:44.459   788  1693 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8b96ac 5821:com.android.vending/u0a29}
,08-10 15:46:44.499   788  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c4577de u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e18fd7 6171:com.sec.android.app.samsungapps/u0a39}
,08-10 15:46:44.519  5821  5821 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-10 15:46:44.519   788   788 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{faa50ba u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d0f05c 1975:com.google.android.gms.persistent/u0a11}
,08-10 15:46:44.529  6613  6641 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-10 15:46:44.529  6613  6641 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 15:46:44.529  5821  5821 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-10 15:46:44.539   788  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ee2347 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8b96ac 5821:com.android.vending/u0a29}
,08-10 15:46:44.549   788  1569 V AlarmManager:  remove PendingIntent] PendingIntent{e0ed774: PendingIntentRecord{a8548d0 com.google.android.gms broadcastIntent}}
,08-10 15:46:44.559  6514  6514 I Mms/MmsApp:  start initViewCache mms
,08-10 15:46:44.559   788   788 I BackgroundCompactionService: onStart. jobID=801
,08-10 15:46:44.559   788   788 I BackgroundCompactionService: onStart done. jobID=801
,08-10 15:46:44.559   788  6703 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-10 15:46:44.569   788  6703 I BackgroundCompactionService: compact_memory command done
,08-10 15:46:44.579  5821  6705 I Finsky  : [839] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-10 15:46:44.579  5821  5844 I PlayCommon: [809] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-10 15:46:44.589  6613  6641 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-10 15:46:44.589  6613  6641 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 15:46:44.589  6613  6641 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-10 15:46:44.609   788   801 I ActivityManager: Start proc 6707:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
,08-10 15:46:44.619  6707  6707 E Zygote  : v2
08-10 15:46:44.619  6707  6707 I libpersona: KNOX_SDCARD checking this for 10034
08-10 15:46:44.619  6707  6707 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:44.619  6707  6707 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:44.619  6707  6707 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:44.619  6707  6707 E Zygote  : accessInfo : 0
,08-10 15:46:44.619  6707  6707 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-10 15:46:44.659  6707  6707 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:44.659  6707  6707 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:44.669   788  1569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd6343f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d9a10c 6707:com.sec.android.app.shealth/u0a34}
,08-10 15:46:44.699  1975  1975 D WearableService: callingUid 10011, callindPid: 1975
,08-10 15:46:44.709  1975  1975 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-10 15:46:44.709  6613  6641 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-10 15:46:44.709  6613  6641 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-10 15:46:44.729  5821  5821 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-10 15:46:44.739  5821  5821 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-10 15:46:44.739  5821  5844 I PlayCommon: [809] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-10 15:46:44.749  5821  6720 I PlayCommon: [840] com.google.android.play.a.w.a(27553): Starting to flush logs
,08-10 15:46:44.749  5821  6720 I PlayCommon: [840] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-10 15:46:44.749  5821  5844 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-10 15:46:44.749  5821  5844 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-10 15:46:44.749   306  1101 D EnterpriseController: netId is 0
08-10 15:46:44.749   306  1101 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-10 15:46:44.759  6707  6707 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-10 15:46:44.789   788   798 I art     : Background partial concurrent mark sweep GC freed 27060(1742KB) AllocSpace objects, 7(140KB) LOS objects, 27% free, 41MB/57MB, paused 1.582ms total 119.889ms
,08-10 15:46:44.819  6707  6707 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-10 15:46:44.829  6707  6707 I MultiDex: VM with version 2.1.0 has multidex support
08-10 15:46:44.829  6707  6707 I MultiDex: install
08-10 15:46:44.829  6707  6707 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-10 15:46:44.829  6707  6707 I MultiDex: install
08-10 15:46:44.829  6707  6707 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 15:46:44.979   788  2460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd6343f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ecb26d 1875:com.sec.android.app.shealth:remote/u0a34}
,08-10 15:46:44.979  6707  6707 D HealthDataStore: Service for HealthDataStore is connected
,08-10 15:46:44.989  6707  6707 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-10 15:46:44.989  6707  6707 D HealthConsole: Service for HealthDataConsole is connected
,08-10 15:46:45.009   788  2459 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd6343f u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ecb26d 1875:com.sec.android.app.shealth:remote/u0a34}
,08-10 15:46:45.029  6707  6707 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-10 15:46:45.029  6707  6707 E HealthDataStore: disconnectService: Context instance is invalid
,08-10 15:46:45.039   788   801 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a0cb4b u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d0f05c 1975:com.google.android.gms.persistent/u0a11}
,08-10 15:46:45.079  6514  6514 D Mms/BubbleViewCache: fillCache bubble = 4
,08-10 15:46:45.119  4270  6701 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 15:46:45.189  5821  5844 I PlayCommon: [809] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-10 15:46:45.189  5821  5844 I PlayCommon: [809] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-10 15:46:45.189  5821  5844 I PlayCommon: [809] com.google.android.play.a.al.e(732): No file ready to send
,08-10 15:46:45.209   788   801 I ActivityManager: Killing 5396:com.policydm/1000 (adj 15): DHA:empty #37
,08-10 15:46:45.229  6488  6488 D AASAservice: onDestroy()
08-10 15:46:45.229   788  1569 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-10 15:46:45.229  6488  6488 I art     : System.exit called, status: 80
08-10 15:46:45.229  6488  6488 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-10 15:46:45.239   788  1568 I ActivityManager: Process com.samsung.aasaservice (pid 6488)(adj 0) has died(49,749)
,08-10 15:46:45.249   788  1568 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-10 15:46:45.269   350   350 I Zygote  : Process 6488 exited cleanly (80)
,08-10 15:46:45.529  4270  5034 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-10 15:46:45.579  4270  5034 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 15:46:45.589  4270  5034 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-10 15:46:45.589  4270  5034 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-10 15:46:45.729   788  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 15:46:46.569   788  3429 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 15:46:50.199   788   930 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-10 15:46:50.219   788   930 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-10 15:46:50.729   788  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 15:46:51.679   788   930 D PackageManager: [MSG] MCS_UNBIND
,08-10 15:46:51.709   788  1414 I ActivityManager: Killing 5920:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-10 15:46:51.729   788  1746 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-10 15:46:52.399  3660  3660 D FactoryTest: User mode
,08-10 15:46:52.409  3660  3660 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-10 15:46:52.409  3660  3660 D MTPRx   : still no open session command from host, so toast
,08-10 15:46:52.409   788  1749 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-10 15:46:52.419   788  1749 D ActivityManager: mDVFSHelper.acquire()
,08-10 15:46:52.419   788  1749 V WindowManager: addAppToken: AppWindowToken{caed127 token=Token{e9df7e6 ActivityRecord{c909641 u0 com.samsung.android.MtpApplication/.USBConnection t153}}} to stack=1 task=153 at 0
,08-10 15:46:52.419   788  1749 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-10 15:46:52.429   788   862 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-10 15:46:52.449   788  1749 D InputDispatcher: Focused application set to: xxxx
,08-10 15:46:52.449   788  1749 D InputDispatcher: Focus left window: 6345
,08-10 15:46:52.459   788   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:788 uid:1000
08-10 15:46:52.459   788   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-10 15:46:52.459   788   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:788 uid:1000
08-10 15:46:52.459   788   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-10 15:46:52.459  3660  3660 E MTPRx   : started activity for popup
,08-10 15:46:52.459  3660  3660 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-10 15:46:52.469  3660  3660 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-10 15:46:52.469   788  3429 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-10 15:46:52.479  3660  3660 D MTPUSBConnection: onCreate in USBConnection
08-10 15:46:52.479  3660  3660 V MTPUSBConnection: Registering broadcast receiver.
,08-10 15:46:52.479  3660  3660 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-10 15:46:52.479   788   801 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-10 15:46:52.529  3660  3660 D TAG     : dev.kiessupport is : TRUE
,08-10 15:46:52.549  3660  3660 D SecWifiDisplayUtil: Metadata value : none
,08-10 15:46:52.549  3660  3660 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{18a759f V.E...... R.....I. 0,0-0,0}
,08-10 15:46:52.559  3660  6743 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 15:46:52.559   788  1649 D ISSUE_DEBUG: InputChannelName : f82be1f com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-10 15:46:52.559   788  1649 D InputDispatcher: Focus entered window: 3660
,08-10 15:46:52.559   788   906 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:788 uid:1000
08-10 15:46:52.559   788   906 D PointerIcon: setMouseCustomIcon IconType is same.101
08-10 15:46:52.559   788   906 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:788 uid:1000
08-10 15:46:52.559   788   906 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-10 15:46:52.559   788   865 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{f82be1f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-10 15:46:52.559  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-10 15:46:52.569  3660  3660 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7af7997 I.E...... R.....I. 0,0-0,0}
,08-10 15:46:52.569   788  1649 D ISSUE_DEBUG: InputChannelName : 478b735 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-10 15:46:52.569   788   800 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-10 15:46:52.569   788   800 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-10 15:46:52.569   788   788 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-10 15:46:52.579   788   788 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-10 15:46:52.579   788   788 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-10 15:46:52.609   294   294 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,08-10 15:46:52.619  3660  6743 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-10 15:46:52.619  3660  6743 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-10 15:46:52.619  3660  6743 I Adreno-EGL: Build Date: 01/28/16 Thu
08-10 15:46:52.619  3660  6743 I Adreno-EGL: Local Branch: ss
08-10 15:46:52.619  3660  6743 I Adreno-EGL: Remote Branch: 
08-10 15:46:52.619  3660  6743 I Adreno-EGL: Local Patches: 
08-10 15:46:52.619  3660  6743 I Adreno-EGL: Reconstruct Branch: 
,08-10 15:46:52.619  3660  6743 D libEGL  : eglInitialize EGLDisplay = 0x9f0387c4
,08-10 15:46:52.619  3660  6743 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 15:46:52.659   294   294 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
,08-10 15:46:52.679  3660  3660 V ActivityThread: updateVisibility : ActivityRecord{21b03a2 token=android.os.BinderProxy@fc4b6ec {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-10 15:46:52.679  3660  3660 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-10 15:46:52.769   788  1693 V WindowStateAnimator: Finishing drawing window Window{f82be1f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-10 15:46:52.779  3660  3660 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-10 15:46:52.779   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8cb364
,08-10 15:46:52.779   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8cb364
,08-10 15:46:52.779   788  1569 V WindowStateAnimator: Finishing drawing window Window{478b735 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-10 15:46:52.779  3660  3660 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-10 15:46:52.779  3660  3660 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-10 15:46:52.789   788   906 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-10 15:46:52.789   788   788 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-10 15:46:52.789   788   906 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +341ms (total +368ms)
,08-10 15:46:52.789   788   788 I KnoxTimeoutHandler: SD activityfalse
,08-10 15:46:52.789   788  1747 V WindowStateAnimator: Finishing drawing window Window{f82be1f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-10 15:46:52.789   788  2460 V WindowStateAnimator: Finishing drawing window Window{478b735 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-10 15:46:52.789  3660  3660 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fc4b6ec time:108349
,08-10 15:46:52.799   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbe8cb364
,08-10 15:46:52.799   788   906 D ActivityManager: mDVFSHelper.release()
,08-10 15:46:52.799   788   906 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c909641 u0 com.samsung.android.MtpApplication/.USBConnection t153} time:108351
,08-10 15:46:53.279  6345  6472 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 15:46:53.279  6345  6472 I jxcore-log: 
,08-10 15:46:53.289  6345  6472 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 15:46:53.289  6345  6472 I jxcore-log: 
,08-10 15:46:53.289  6345  6472 D BluetoothAdapter: STATE_ON
,08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:46:53.289  6345  6472 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 15:46:53.289  6345  6472 D BluetoothAdapter: STATE_ON
,08-10 15:46:53.289  6345  6472 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 15:46:53.299  6345  6472 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 15:46:53.299  6345  6472 I jxcore-log: 
,08-10 15:46:53.299  6345  6472 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 15:46:53.299  6345  6472 I jxcore-log: 
,08-10 15:46:53.459   788  3430 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-10 15:46:53.579  1456  1456 D Recents : onTaskStackChanged
,08-10 15:46:53.599  1456  1456 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-10 15:46:53.649  6345  6472 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-10 15:46:53.649  6345  6472 I jxcore-log: Failed to execute UT.
08-10 15:46:53.649  6345  6472 I jxcore-log: 
08-10 15:46:53.649  6345  6472 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 15:46:53.649  6345  6472 I jxcore-log: 
,08-10 15:46:53.649  6345  6472 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 15:46:53.649  6345  6472 I jxcore-log: 
08-10 15:46:53.659  6345  6345 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 15:46:53.689   788  1236 V AlarmManager: Expired Alarm result :4
,08-10 15:46:53.699   788  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-10 15:46:53.699   788  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-10 15:46:53.699   788  1693 V AlarmManager:  remove PendingIntent] PendingIntent{11f1d3b: PendingIntentRecord{2241da0 com.google.android.gms broadcastIntent}}
,08-10 15:46:53.759   788  1569 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-10 15:46:53.759   788  1569 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4358, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-10 15:46:53.759   788  1569 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-10 15:46:53.759   788  1569 D BatteryService: stay LED for charging
,08-10 15:46:53.759   788   788 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-10 15:46:53.759   788   788 I MotionRecognitionService: Plugged
08-10 15:46:53.759   788   788 D MotionRecognitionService:   cableConnection= 1
08-10 15:46:53.759   788   788 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-10 15:46:53.759   788   788 D MotionRecognitionService: skip setTransmitPower. 
,08-10 15:46:53.759  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-10 15:46:53.759  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-10 15:46:53.759  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-10 15:46:53.779  2362  2362 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-10 15:46:53.779  2362  2773 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-10 15:46:53.789  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-10 15:46:53.789  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-10 15:46:53.789  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-10 15:46:53.839   788  3429 D SSRM:n  : SIOP:: AP = 470, PST = 460, CUR = 450, LCD = 0
,08-10 15:46:54.619  2374  2374 E audit   : type=1400 msg=audit(1470836814.619:290): avc:  denied  { execmod } for  pid=6752 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 15:46:54.619  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:54.619  2374  2374 E audit   : type=1300 msg=audit(1470836814.619:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcb000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6752 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-10 15:46:54.619  2374  2374 E audit   : type=1327 msg=audit(1470836814.619:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-10 15:46:54.619  2374  2374 E audit   : type=1320 msg=audit(1470836814.619:290): 
,08-10 15:46:54.679  2374  2374 E audit   : type=1400 msg=audit(1470836814.679:291): avc:  denied  { execmod } for  pid=6752 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-10 15:46:54.679  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:54.679  2374  2374 E audit   : type=1300 msg=audit(1470836814.679:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8b000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6752 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-10 15:46:54.679  2374  2374 E audit   : type=1327 msg=audit(1470836814.679:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-10 15:46:54.689  2374  2374 E audit   : type=1320 msg=audit(1470836814.679:291): 
,08-10 15:46:54.719  2374  2374 E audit   : type=1400 msg=audit(1470836814.719:292): avc:  denied  { execmod } for  pid=6752 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-10 15:46:54.719  6752  6752 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-10 15:46:54.729  2374  2374 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-10 15:46:54.729  2374  2374 E audit   : type=1300 msg=audit(1470836814.719:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f8b000 a1=51000 a2=5 a3=4 items=0 ppid=3560 ppcomm=adbd pid=6752 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,08-10 15:46:54.729  2374  2374 E audit   : type=1327 msg=audit(1470836814.719:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-10 15:46:54.729  2374  2374 E audit   : type=1320 msg=audit(1470836814.719:292): 
,08-10 15:46:54.729  6752  6752 D AndroidRuntime: CheckJNI is OFF
,08-10 15:46:54.729  6752  6752 D AndroidRuntime: readGMSProperty: start
08-10 15:46:54.729  6752  6752 D AndroidRuntime: readGMSProperty: already setted!!
08-10 15:46:54.729  6752  6752 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-10 15:46:54.729  6752  6752 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-10 15:46:54.729  6752  6752 D AndroidRuntime: readGMSProperty: end
,08-10 15:46:54.729  6752  6752 D AndroidRuntime: addProductProperty: start
,08-10 15:46:54.739  6752  6752 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-10 15:46:54.739  6752  6752 W art     : aedf2000-b1d18000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-10 15:46:54.739  6752  6752 W art     : b1d18000-b3f87000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-10 15:46:54.739  6752  6752 W art     : b3f87000-b3f88000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-10 15:46:54.739  6752  6752 W art     : b3f88000-b3f89000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.739  6752  6752 W art     : b42bb000-b42e4000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-10 15:46:54.739  6752  6752 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-10 15:46:54.739  6752  6752 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
,08-10 15:46:54.739  6752  6752 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-10 15:46:54.739  6752  6752 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-10 15:46:54.739  6752  6752 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-10 15:46:54.739  6752  6752 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-10 15:46:54.739  6752  6752 W art     : b485c000-b485f000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-10 15:46:54.739  6752  6752 W art     : b485f000-b4860000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-10 15:46:54.739  6752  6752 W art     : b4860000-b4861000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-10 15:46:54.739  6752  6752 W art     : b4861000-b4862000 r--p 00000000 00:00 0 
08-10 15:46:54.739  6752  6752 W art     : b4862000-b4882000 r--s 00000000 00:0b 9219       /dev/__properties__
08-10 15:46:54.739  6752  6752 W art     : b4882000-b5293000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-10 15:46:54.739  6752  6752 W art     : b5293000-b5294000 ---p 00000000 00:00 0 
08-10 15:46:54.739  6752  6752 W art     : b5294000-b52dd000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-10 15:46:54.739  6752  6752 W art     : b52dd000-b52de000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
,08-10 15:46:54.739  6752  6752 W art     : b52de000-b52e6000 rw-p 00000000 00:00 0 
08-10 15:46:54.739  6752  6752 W art     : b52e6000-b52e7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.739  6752  6752 W art     : b52e7000-b531c000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-10 15:46:54.739  6752  6752 W art     : b531c000-b531d000 ---p 00000000 00:00 0 
08-10 15:46:54.739  6752  6752 W art     : b531d000-b531e000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-10 15:46:54.739  6752  6752 W art     : b531e000-b531f000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-10 15:46:54.739  6752  6752 W art     : b531f000-b5377000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
,08-10 15:46:54.739  6752  6752 W art     : b5377000-b5378000 ---p 00000000 00:00 0 
08-10 15:46:54.739  6752  6752 W art     : b5378000-b5379000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-10 15:46:54.749  6752  6752 W art     : b5379000-b537a000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-10 15:46:54.749  6752  6752 W art     : b537b000-b5381000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 15:46:54.749  6752  6752 W art     : b5381000-b5382000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-10 15:46:54.749  6752  6752 W art     : b5382000-b5383000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
,08-10 15:46:54.749  6752  6752 W art     : b5383000-b5385000 rw-p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5386000-b5390000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 15:46:54.749  6752  6752 W art     : b5390000-b5393000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 15:46:54.749  6752  6752 W art     : b5393000-b5394000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-10 15:46:54.749  6752  6752 W art     : b5395000-b53ac000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 15:46:54.749  6752  6752 W art     : b53ac000-b53ad000 ---p 00000000 00:00 0 
,08-10 15:46:54.749  6752  6752 W art     : b53ad000-b53ae000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 15:46:54.749  6752  6752 W art     : b53ae000-b53af000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-10 15:46:54.749  6752  6752 W art     : b53b0000-b53ba000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-10 15:46:54.749  6752  6752 W art     : b53ba000-b53bb000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-10 15:46:54.749  6752  6752 W art     : b53bb000-b53bc000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-10 15:46:54.749  6752  6752 W art     : b53bc000-b53c0000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 15:46:54.749  6752  6752 W art     : b53c0000-b53c1000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-10 15:46:54.749  6752  6752 W art     : b53c1000-b53c2000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-10 15:46:54.749  6752  6752 W art     : b53c2000-b53d8000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-10 15:46:54.749  6752  6752 W art     : b53d8000-b53d9000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-10 15:46:54.749  6752  6752 W art     : b53d9000-b53da000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-10 15:46:54.749  6752  6752 W art     : b53da000-b53e7000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-10 15:46:54.749  6752  6752 W art     : b53e7000-b53e8000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,08-10 15:46:54.749  6752  6752 W art     : b53e8000-b53e9000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-10 15:46:54.749  6752  6752 W art     : b53e9000-b5449000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-10 15:46:54.749  6752  6752 W art     : b5449000-b544c000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-10 15:46:54.749  6752  6752 W art     : b544c000-b5450000 rw-p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5450000-b54b1000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-10 15:46:54.749  6752  6752 W art     : b54b1000-b54b2000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
,08-10 15:46:54.749  6752  6752 W art     : b54b2000-b5501000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-10 15:46:54.749  6752  6752 W art     : b5501000-b5503000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-10 15:46:54.749  6752  6752 W art     : b5503000-b5504000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-10 15:46:54.749  6752  6752 W art     : b5504000-b5505000 rw-p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5505000-b550c000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-10 15:46:54.749  6752  6752 W art     : b550c000-b550d000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-10 15:46:54.749  6752  6752 W art     : b550d000-b550e000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
,08-10 15:46:54.749  6752  6752 W art     : avc_common.so
08-10 15:46:54.749  6752  6752 W art     : b550f000-b5512000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 15:46:54.749  6752  6752 W art     : b5512000-b5513000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-10 15:46:54.749  6752  6752 W art     : b5513000-b5514000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-10 15:46:54.749  6752  6752 W art     : enc_common.so
08-10 15:46:54.749  6752  6752 W art     : b5515000-b5519000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-10 15:46:54.749  6752  6752 W art     : b5519000-b551a000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b551a000-b551b000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-10 15:46:54.749  6752  6752 W art     : b551b000-b551c000 rw-p 00005000 b3:17 2510       /syste
,08-10 15:46:54.749  6752  6752 W art     : m/lib/libpowermanager.so
08-10 15:46:54.749  6752  6752 W art     : b551d000-b553a000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 15:46:54.749  6752  6752 W art     : b553a000-b553b000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 15:46:54.749  6752  6752 W art     : b553b000-b553c000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-10 15:46:54.749  6752  6752 W art     : b553d000-b5542000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 15:46:54.749  6752  6752 W art     : b5542000-b5543000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 15:46:54.749  6752  6752 W art     : b5543000-b5544000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-10 15:46:54.749  6752  6752 W art     : b5545000-b5576000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 15:46:54.749  6752  6752 W art     : b5576000-b5579000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-10 15:46:54.749  6752  6752 W art     : b5579000-b557a000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-10 15:46:54.749  6752  6752 W art     : b557b000-b55b6000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-10 15:46:54.749  6752  6752 W art     : b55b6000-b55b7000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-10 15:46:54.749  6752  6752 W art     : b55b7000-b55b8000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-10 15:46:54.749  6752  6752 W art     : b55b9000-b55c0000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-10 15:46:54.749  6752  6752 W art     : b55c0000-b55c1000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b55c1000-b55c2000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-10 15:46:54.749  6752  6752 W art     : b55c2000-b55c3000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-10 15:46:54.749  6752  6752 W art     : b55c3000-b55c4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.749  6752  6752 W art     : b55c4000-b55db000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
,08-10 15:46:54.749  6752  6752 W art     : b55db000-b55dc000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b55dc000-b55df000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-10 15:46:54.749  6752  6752 W art     : b55df000-b55e0000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-10 15:46:54.749  6752  6752 W art     : b55e0000-b55ff000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-10 15:46:54.749  6752  6752 W art     : b55ff000-b5600000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-10 15:46:54.749  6752  6752 W art     : b5600000-b5601000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-10 15:46:54.749  6752  6752 W art     : b5601000-b563f000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-10 15:46:54.749  6752  6752 W art     : b563f000-b5640000 ---p 00000000 00:00 0 
,08-10 15:46:54.749  6752  6752 W art     : b5640000-b5642000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-10 15:46:54.749  6752  6752 W art     : b5642000-b5643000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-10 15:46:54.749  6752  6752 W art     : b5644000-b564b000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 15:46:54.749  6752  6752 W art     : b564b000-b564c000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 15:46:54.749  6752  6752 W art     : b564c000-b564d000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-10 15:46:54.749  6752  6752 W art     : b564e000-b5651000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 15:46:54.749  6752  6752 W art     : b5651000-b5652000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 15:46:54.749  6752  6752 W art     : b5652000-b5653000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-10 15:46:54.749  6752  6752 W art     : b5653000-b5659000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 15:46:54.749  6752  6752 W art     : b5659000-b565a000 ---p 00000000 00:00 0 
,08-10 15:46:54.749  6752  6752 W art     : b565a000-b565b000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 15:46:54.749  6752  6752 W art     : b565b000-b565c000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-10 15:46:54.749  6752  6752 W art     : b565c000-b5665000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-10 15:46:54.749  6752  6752 W art     : b5665000-b5666000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-10 15:46:54.749  6752  6752 W art     : b5666000-b5667000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-10 15:46:54.749  6752  6752 W art     : b5667000-b56f8000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 15:46:54.749  6752  6752 W art     : b56f8000-b56f9000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b56f9000-b5704000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 15:46:54.749  6752  6752 W art     : b5704000-b5705000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-10 15:46:54.749  6752  6752 W art     : b5706000-b5718000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-10 15:46:54.749  6752  6752 W art     : b5718000-b5719000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-10 15:46:54.749  6752  6752 W art     : b5719000-b571a000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-10 15:46:54.749  6752  6752 W art     : b571b000-b5720000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-10 15:46:54.749  6752  6752 W art     : b5720000-b5721000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-10 15:46:54.749  6752  6752 W art     : b5721000-b5722000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-10 15:46:54.749  6752  6752 W art     : b5723000-b5790000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-10 15:46:54.749  6752  6752 W art     : b5790000-b5791000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5791000-b5793000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-10 15:46:54.749  6752  6752 W art     : b5793000-b5794000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-10 15:46:54.749  6752  6752 W art     : b5794000-b5795000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 15:46:54.749  6752  6752 W art     : b5795000-b579c000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 15:46:54.749  6752  6752 W art     : b579c000-b579d000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 15:46:54.749  6752  6752 W art     : b579d000-b579e000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-10 15:46:54.749  6752  6752 W art     : b579f000-b581f000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 15:46:54.749  6752  6752 W art     : b581f000-b5820000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5820000-b5821000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 15:46:54.749  6752  6752 W art     : b5821000-b5822000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-10 15:46:54.749  6752  6752 W art     : b5822000-b5839000 rw-p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5839000-b5870000 r-xp 00000000 b3:17 3244       /system/vendor/l
,08-10 15:46:54.749  6752  6752 W art     : ib/libqc-opt.so
08-10 15:46:54.749  6752  6752 W art     : b5870000-b5871000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 15:46:54.749  6752  6752 W art     : b5871000-b5872000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-10 15:46:54.749  6752  6752 W art     : b5872000-b588e000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 15:46:54.749  6752  6752 W art     : b588e000-b588f000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 15:46:54.749  6752  6752 W art     : b588f000-b5890000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-10 15:46:54.749  6752  6752 W art     : b5891000-b58f2000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-10 15:46:54.749  6752  6752 W art     : b58f2000-b58f4000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-10 15:46:54.749  6752  6752 W art     : b58f4000-b58f5000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
,08-10 15:46:54.749  6752  6752 W art     : b58f6000-b591d000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-10 15:46:54.749  6752  6752 W art     : b591d000-b591e000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b591e000-b591f000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-10 15:46:54.749  6752  6752 W art     : b591f000-b5920000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-10 15:46:54.749  6752  6752 W art     : b5921000-b5929000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 15:46:54.749  6752  6752 W art     : b5929000-b592b000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 15:46:54.749  6752  6752 W art     : b592b000-b592c000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-10 15:46:54.749  6752  6752 W art     : b592d000-b5930000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-10 15:46:54.749  6752  6752 W art     : b5930000-b5931000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-10 15:46:54.749  6752  6752 W art     : b5931000-b5932000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
,08-10 15:46:54.749  6752  6752 W art     : b5932000-b5936000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-10 15:46:54.749  6752  6752 W art     : b5936000-b5937000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5937000-b5938000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-10 15:46:54.749  6752  6752 W art     : b5938000-b5939000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-10 15:46:54.749  6752  6752 W art     : b5939000-b5949000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-10 15:46:54.749  6752  6752 W art     : b5949000-b594a000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-10 15:46:54.749  6752  6752 W art     : b594a000-b594b000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-10 15:46:54.749  6752  6752 W art     : b594b000-b5991000 rw-p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5991000-b599a000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
,08-10 15:46:54.749  6752  6752 W art     : b599a000-b599b000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-10 15:46:54.749  6752  6752 W art     : b599b000-b599c000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-10 15:46:54.749  6752  6752 W art     : b599d000-b59a2000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-10 15:46:54.749  6752  6752 W art     : b59a2000-b59a3000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-10 15:46:54.749  6752  6752 W art     : b59a3000-b59a4000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-10 15:46:54.749  6752  6752 W art     : b59a4000-b59a7000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 15:46:54.749  6752  6752 W art     : b59a7000-b59a8000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b59a8000-b59a9000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-10 15:46:54.749  6752  6752 W art     : b59a9000-b59aa000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-10 15:46:54.749  6752  6752 W art     : b59ab000-b59c3000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 15:46:54.749  6752  6752 W art     : b59c3000-b59c4000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b59c4000-b59c5000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 15:46:54.749  6752  6752 W art     : b59c5000-b59c6000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-10 15:46:54.749  6752  6752 W art     : b59c7000-b5b61000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-10 15:46:54.749  6752  6752 W art     : b5b61000-b5b62000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5b62000-b5b6f000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-10 15:46:54.749  6752  6752 W art     : b5b6f000-b5b70000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-10 15:46:54.749  6752  6752 W art     : b5b70000-b5b74000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-10 15:46:54.749  6752  6752 W art     : b5b74000-b5b75000 ---p 00000000 00:00 0 
,08-10 15:46:54.749  6752  6752 W art     : b5b75000-b5b76000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-10 15:46:54.749  6752  6752 W art     : b5b76000-b5b77000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-10 15:46:54.749  6752  6752 W art     : b5b77000-b5b8a000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-10 15:46:54.749  6752  6752 W art     : b5b8a000-b5b8b000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-10 15:46:54.749  6752  6752 W art     : b5b8b000-b5b8c000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-10 15:46:54.749  6752  6752 W art     : b5b8c000-b5b8d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:54.749  6752  6752 W art     : b5b8d000-b5bd8000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-10 15:46:54.749  6752  6752 W art     : b5bd8000-b5bd9000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-10 15:46:54.749  6752  6752 W art     : b5bd9000-b5bda000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-10 15:46:54.749  6752  6752 W art     : b5bda000-b5bdc000 rw-p 00000000 00:00 0 
,08-10 15:46:54.749  6752  6752 W art     : b5bdd000-b5bee000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 15:46:54.749  6752  6752 W art     : b5bee000-b5bef000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5bef000-b5bf0000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 15:46:54.749  6752  6752 W art     : b5bf0000-b5bf1000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-10 15:46:54.749  6752  6752 W art     : b5bf2000-b5bfc000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-10 15:46:54.749  6752  6752 W art     : b5bfc000-b5bfe000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-10 15:46:54.749  6752  6752 W art     : b5bfe000-b5bff000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-10 15:46:54.749  6752  6752 W art     : b5bff000-b5c18000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-10 15:46:54.749  6752  6752 W art     : b5c18000-b5c19000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-10 15:46:54.749  6752  6752 W art     : b5c19000-b5c1c000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
,08-10 15:46:54.749  6752  6752 W art     : b5c1c000-b5c20000 rw-p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5c20000-b5c94000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-10 15:46:54.749  6752  6752 W art     : b5c94000-b5c95000 ---p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5c95000-b5c98000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-10 15:46:54.749  6752  6752 W art     : b5c98000-b5c99000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-10 15:46:54.749  6752  6752 W art     : b5c99000-b5c9a000 r--p 00000000 00:00 0 
08-10 15:46:54.749  6752  6752 W art     : b5c9a000-b5c9d000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-10 15:46:54.759  6752  6752 W art     : b5c9d000-b5c9e000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-10 15:46:54.759  6752  6752 W art     : b5c9e000-b5c9f000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-10 15:46:54.759  6752  6752 W art     : b5c9f000-b5ca0000 r--p 00000000 00:00 0 
,08-10 15:46:54.759  6752  6752 W art     : b5ca0000-b5ca5000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 15:46:54.759  6752  6752 W art     : b5ca5000-b5ca6000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 15:46:54.759  6752  6752 W art     : b5ca6000-b5ca7000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-10 15:46:54.759  6752  6752 W art     : b5ca7000-b5ca8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b5ca8000-b5cab000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 15:46:54.759  6752  6752 W art     : b5cab000-b5cac000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 15:46:54.759  6752  6752 W art     : b5cac000-b5cad000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-10 15:46:54.759  6752  6752 W art     : b5cad000-b5cae000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b5cae000-b5cb2000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-10 15:46:54.759  6752  6752 W art     : b5cb2000-b5cb3000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
,08-10 15:46:54.759  6752  6752 W art     : b5cb3000-b5cb4000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-10 15:46:54.759  6752  6752 W art     : b5cb4000-b5cb5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:54.759  6752  6752 W art     : b5cb5000-b5cb9000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 15:46:54.759  6752  6752 W art     : b5cb9000-b5cba000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 15:46:54.759  6752  6752 W art     : b5cba000-b5cbb000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-10 15:46:54.759  6752  6752 W art     : b5cbb000-b5cbc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b5cbc000-b5cca000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-10 15:46:54.759  6752  6752 W art     : b5cca000-b5ccb000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b5ccb000-b5ccc000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
,08-10 15:46:54.759  6752  6752 W art     : b5ccc000-b5ccd000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-10 15:46:54.759  6752  6752 W art     : b5ccd000-b5cd7000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 15:46:54.759  6752  6752 W art     : b5cd7000-b5cda000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 15:46:54.759  6752  6752 W art     : b5cda000-b5cdb000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-10 15:46:54.759  6752  6752 W art     : b5cdb000-b5cdc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b5cdc000-b5ce6000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-10 15:46:54.759  6752  6752 W art     : b5ce6000-b5ce9000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-10 15:46:54.759  6752  6752 W art     : b5ce9000-b5cea000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-10 15:46:54.759  6752  6752 W art     : b5cea000-b5cee000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-10 15:46:54.759  6752  6752 W art     : b5cee000-b5cef000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
,08-10 15:46:54.759  6752  6752 W art     : b5cef000-b5cf0000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-10 15:46:54.759  6752  6752 W art     : b5cf0000-b5cf1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b5cf1000-b5cfe000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-10 15:46:54.759  6752  6752 W art     : b5cfe000-b5d00000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-10 15:46:54.759  6752  6752 W art     : b5d00000-b5d01000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-10 15:46:54.759  6752  6752 W art     : b5d01000-b6113000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-10 15:46:54.759  6752  6752 W art     : b6113000-b6114000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6114000-b611d000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-10 15:46:54.759  6752  6752 W art     : b611d000-b6121000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
,08-10 15:46:54.759  6752  6752 W art     : b6121000-b6122000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6122000-b6129000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-10 15:46:54.759  6752  6752 W art     : b6129000-b612a000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-10 15:46:54.759  6752  6752 W art     : b612a000-b612b000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-10 15:46:54.759  6752  6752 W art     : b612b000-b612c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b612c000-b6147000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-10 15:46:54.759  6752  6752 W art     : b6147000-b6148000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-10 15:46:54.759  6752  6752 W art     : b6148000-b6149000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-10 15:46:54.759  6752  6752 W art     : b6149000-b614a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b614a000-b6196000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
,08-10 15:46:54.759  6752  6752 W art     : b6196000-b6197000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6197000-b6198000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 15:46:54.759  6752  6752 W art     : b6198000-b6199000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-10 15:46:54.759  6752  6752 W art     : b6199000-b619a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b619a000-b619e000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-10 15:46:54.759  6752  6752 W art     : b619e000-b619f000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b619f000-b61a0000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-10 15:46:54.759  6752  6752 W art     : b61a0000-b61a1000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-10 15:46:54.759  6752  6752 W art     : b61a1000-b61d9000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
,08-10 15:46:54.759  6752  6752 W art     : b61d9000-b61da000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-10 15:46:54.759  6752  6752 W art     : b61da000-b61db000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-10 15:46:54.759  6752  6752 W art     : b61db000-b61dc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.759  6752  6752 W art     : b61dc000-b627a000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-10 15:46:54.759  6752  6752 W art     : b627a000-b627b000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b627b000-b6299000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-10 15:46:54.759  6752  6752 W art     : b6299000-b629a000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-10 15:46:54.759  6752  6752 W art     : b629a000-b640d000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-10 15:46:54.759  6752  6752 W art     : b640d000-b6418000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-10 15:46:54.759  6752  6752 W art     : b6418000-b6419000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
,08-10 15:46:54.759  6752  6752 W art     : b6419000-b6530000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-10 15:46:54.759  6752  6752 W art     : b6530000-b653b000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-10 15:46:54.759  6752  6752 W art     : b653b000-b653c000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-10 15:46:54.759  6752  6752 W art     : b653c000-b6540000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6540000-b6564000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-10 15:46:54.759  6752  6752 W art     : b6564000-b6566000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-10 15:46:54.759  6752  6752 W art     : b6566000-b6567000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-10 15:46:54.759  6752  6752 W art     : b6567000-b660d000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-10 15:46:54.759  6752  6752 W art     : b660d000-b661a000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-10 15:46:54.759  6752  6752 W art     : b661a000-b661b000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
,08-10 15:46:54.759  6752  6752 W art     : b661b000-b661c000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b661c000-b666f000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-10 15:46:54.759  6752  6752 W art     : b666f000-b6670000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6670000-b6671000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-10 15:46:54.759  6752  6752 W art     : b6671000-b6672000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-10 15:46:54.759  6752  6752 W art     : b6672000-b6677000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6677000-b6689000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-10 15:46:54.759  6752  6752 W art     : b6689000-b668a000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b668a000-b668b000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-10 15:46:54.759  6752  6752 W art     : b668b000-b668c000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-10 15:46:54.759  6752  6752 W art     : b668c000-b6693000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 15:46:54.759  6752  6752 W art     : b6693000-b6694000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 15:46:54.759  6752  6752 W art     : b6694000-b6695000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-10 15:46:54.759  6752  6752 W art     : b6695000-b6696000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6696000-b6699000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-10 15:46:54.759  6752  6752 W art     : b6699000-b669a000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-10 15:46:54.759  6752  6752 W art     : b669a000-b669b000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-10 15:46:54.759  6752  6752 W art     : b669b000-b669f000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-10 15:46:54.759  6752  6752 W art     : b669f000-b66a0000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-10 15:46:54.759  6752  6752 W art     : b66a0000-b66a1000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-10 15:46:54.759  6752  6752 W art     : b66a1000-b66af000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-10 15:46:54.759  6752  6752 W art     : b66af000-b66b0000 ---p 00000000 00:00 0 
,08-10 15:46:54.759  6752  6752 W art     : b66b0000-b66b1000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-10 15:46:54.759  6752  6752 W art     : b66b1000-b66b2000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-10 15:46:54.759  6752  6752 W art     : b66b2000-b66bb000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 15:46:54.759  6752  6752 W art     : b66bb000-b66bc000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 15:46:54.759  6752  6752 W art     : b66bc000-b66bd000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-10 15:46:54.759  6752  6752 W art     : b66bd000-b6723000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so,
08-10 15:46:54.759  6752  6752 W art     : b6723000-b6724000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6724000-b6726000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-10 15:46:54.759  6752  6752 W art     : b6726000-b672f000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-10 15:46:54.759  6752  6752 W art     : b672f000-b6732000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6732000-b67c9000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
,08-10 15:46:54.759  6752  6752 W art     : b67c9000-b67cb000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-10 15:46:54.759  6752  6752 W art     : b67cb000-b67cc000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-10 15:46:54.759  6752  6752 W art     : b67cc000-b67cd000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b67cd000-b6aee000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-10 15:46:54.759  6752  6752 W art     : b6aee000-b6aef000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6aef000-b6b0a000 r--p 00321000 b3:17 377        /system/lib/libskia.so
,08-10 15:46:54.759  6752  6752 W art     : b6b0a000-b6b0e000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-10 15:46:54.759  6752  6752 W art     : b6b0e000-b6b13000 rw-p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6b13000-b6b1b000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 15:46:54.759  6752  6752 W art     : b6b1b000-b6b1c000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 15:46:54.759  6752  6752 W art     : b6b1c000-b6b1d000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-10 15:46:54.759  6752  6752 W art     : b6b1d000-b6b4b000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-10 15:46:54.759  6752  6752 W art     : b6b4b000-b6b4c000 ---p 00000000 00:00 0 
08-10 15:46:54.759  6752  6752 W art     : b6b4c000-b6b53000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
,08-10 15:46:54.769  6752  6752 W art     : b6b53000-b6b54000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-10 15:46:54.769  6752  6752 W art     : b6b54000-b6b9a000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-10 15:46:54.769  6752  6752 W art     : b6b9a000-b6b9b000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6b9b000-b6b9e000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-10 15:46:54.769  6752  6752 W art     : b6b9e000-b6b9f000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-10 15:46:54.769  6752  6752 W art     : b6b9f000-b6bba000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-10 15:46:54.769  6752  6752 W art     : b6bba000-b6bbe000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
,08-10 15:46:54.769  6752  6752 W art     : b6bbe000-b6bbf000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-10 15:46:54.769  6752  6752 W art     : b6bbf000-b6c0c000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-10 15:46:54.769  6752  6752 W art     : b6c0c000-b6c0d000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6c0d000-b6c19000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-10 15:46:54.769  6752  6752 W art     : b6c19000-b6c1a000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-10 15:46:54.769  6752  6752 W art     : b6c1a000-b6c27000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-10 15:46:54.769  6752  6752 W art     : b6c27000-b6c28000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6c28000-b6c29000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
,08-10 15:46:54.769  6752  6752 W art     : b6c29000-b6c2a000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-10 15:46:54.769  6752  6752 W art     : b6c2a000-b6c32000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-10 15:46:54.769  6752  6752 W art     : b6c32000-b6c33000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6c33000-b6c34000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-10 15:46:54.769  6752  6752 W art     : b6c34000-b6c35000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-10 15:46:54.769  6752  6752 W art     : b6c35000-b6c3c000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-10 15:46:54.769  6752  6752 W art     : b6c3c000-b6c3d000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-10 15:46:54.769  6752  6752 W art     : b6c3d000-b6c3e000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
,08-10 15:46:54.769  6752  6752 W art     : b6c3e000-b6c52000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-10 15:46:54.769  6752  6752 W art     : b6c52000-b6c54000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-10 15:46:54.769  6752  6752 W art     : b6c54000-b6c55000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-10 15:46:54.769  6752  6752 W art     : b6c55000-b6c7d000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-10 15:46:54.769  6752  6752 W art     : b6c7d000-b6c7f000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-10 15:46:54.769  6752  6752 W art     : b6c7f000-b6c80000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-10 15:46:54.769  6752  6752 W art     : b6c80000-b6c83000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-10 15:46:54.769  6752  6752 W art     : b6c83000-b6c84000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
,08-10 15:46:54.769  6752  6752 W art     : b6c84000-b6c85000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-10 15:46:54.769  6752  6752 W art     : b6c85000-b6c8e000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-10 15:46:54.769  6752  6752 W art     : b6c8e000-b6c8f000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-10 15:46:54.769  6752  6752 W art     : b6c8f000-b6c90000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-10 15:46:54.769  6752  6752 W art     : b6c90000-b6cb0000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-10 15:46:54.769  6752  6752 W art     : b6cb0000-b6cb1000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-10 15:46:54.769  6752  6752 W art     : b6cb1000-b6cb2000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
,08-10 15:46:54.769  6752  6752 W art     : b6cb2000-b6d25000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-10 15:46:54.769  6752  6752 W art     : b6d25000-b6d29000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-10 15:46:54.769  6752  6752 W art     : b6d29000-b6d2c000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-10 15:46:54.769  6752  6752 W art     : b6d2c000-b6d36000 rw-p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6d36000-b6dbe000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-10 15:46:54.769  6752  6752 W art     : b6dbe000-b6dbf000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6dbf000-b6dc3000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-10 15:46:54.769  6752  6752 W art     : b6dc3000-b6dc4000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
,08-10 15:46:54.769  6752  6752 W art     : b6dc4000-b6dc5000 rw-p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6dc5000-b6dee000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-10 15:46:54.769  6752  6752 W art     : b6dee000-b6def000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6def000-b6df2000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-10 15:46:54.769  6752  6752 W art     : b6df2000-b6df3000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-10 15:46:54.769  6752  6752 W art     : b6df3000-b6ecd000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 15:46:54.769  6752  6752 W art     : b6ecd000-b6ed4000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 15:46:54.769  6752  6752 W art     : b6ed4000-b6edc000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-10 15:46:54.769  6752  6752 W art     : b6edc000-b6edd000 rw-p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6edd000-b6ede000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-10 15:46:54.769  6752  6752 W art     : b6ede000-b6edf000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-10 15:46:54.769  6752  6752 W art     : b6edf000-b6ee0000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.769  6752  6752 W art     : b6ee0000-b6ee3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.769  6752  6752 W art     : b6ee3000-b6f08000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-10 15:46:54.769  6752  6752 W art     : b6f08000-b6f09000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6f09000-b6f10000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
,08-10 15:46:54.769  6752  6752 W art     : b6f10000-b6f11000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-10 15:46:54.769  6752  6752 W art     : b6f11000-b6f18000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-10 15:46:54.769  6752  6752 W art     : b6f18000-b6f19000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-10 15:46:54.769  6752  6752 W art     : b6f19000-b6f1a000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-10 15:46:54.769  6752  6752 W art     : b6f1a000-b6f1b000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-10 15:46:54.769  6752  6752 W art     : b6f1b000-b6f33000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-10 15:46:54.769  6752  6752 W art     : b6f33000-b6f34000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6f34000-b6f35000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-10 15:46:54.769  6752  6752 W art     : b6f35000-b6f36000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-10 15:46:54.769  6752  6752 W art     : b6f36000-b6f44000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so,
08-10 15:46:54.769  6752  6752 W art     : b6f44000-b6f45000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6f45000-b6f46000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
,08-10 15:46:54.769  6752  6752 W art     : b6f46000-b6f47000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-10 15:46:54.769  6752  6752 W art     : b6f47000-b6f48000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-10 15:46:54.769  6752  6752 W art     : b6f48000-b6f4a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.769  6752  6752 W art     : b6f4a000-b6f4b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.769  6752  6752 W art     : b6f4b000-b6f4c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-10 15:46:54.769  6752  6752 W art     : b6f4c000-b6f4d000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-10 15:46:54.769  6752  6752 W art     : b6f4d000-b6f4e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-10 15:46:54.769  6752  6752 W art     : b6f4e000-b6f6e000 r--s 00000000 00:0b 9219       /dev/__properties__
08-10 15:46:54.769  6752  6752 W art     : b6f6e000-b6f6f000 r--p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6f6f000-b6f70000 ---p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6f70000-b6f72000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-10 15:46:54.769  6752  6752 W art     : b6f72000-b6f73000 r-xp 00000000 00:00 0          [sigpage]
08-10 15:46:54.769  6752  6752 W art     : b6f73000-b6f8e000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-10 15:46:54.769  6752  6752 W art     : b6f8e000-b6f8f000 r--p 0001a000 b3:17 2770       /system/bin/linker
,08-10 15:46:54.769  6752  6752 W art     : b6f8f000-b6f91000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-10 15:46:54.769  6752  6752 W art     : b6f91000-b6f93000 rw-p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : b6f93000-b6f98000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-10 15:46:54.769  6752  6752 W art     : b6f98000-b6f99000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-10 15:46:54.769  6752  6752 W art     : b6f99000-b6f9a000 rw-p 00000000 00:00 0 
08-10 15:46:54.769  6752  6752 W art     : bef02000-bef23000 rw-p 00000000 00:00 0          [stack]
08-10 15:46:54.769  6752  6752 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-10 15:46:54.839  6752  6752 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-10 15:46:54.889  6752  6752 I Radio-JNI: register_android_hardware_Radio DONE
,08-10 15:46:54.899  6752  6752 E AffinityControl: AffinityControl: registerfunction enter
,08-10 15:46:54.919  6752  6752 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 15:46:54.929   788   800 D PackageManager: START PACKAGE DELETE: observer{197762136}
08-10 15:46:54.929   788   800 D PackageManager: pkg{<packageName>}
08-10 15:46:54.929   788   800 D PackageManager: user{0}
08-10 15:46:54.929   788   800 D PackageManager: caller{2000}
08-10 15:46:54.929   788   800 D PackageManager: flags{2}
08-10 15:46:54.929   788   800 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-10 15:46:54.929   788   800 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-10 15:46:54.929   788   800 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-10 15:46:54.929   788   800 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-10 15:46:54.929   788   800 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-10 15:46:54.929   788   930 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-10 15:46:54.929   788   930 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-10 15:46:54.929   788   930 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-10 15:46:54.929   788   930 D ApplicationPolicy: getApplicationUninstallationEnabled
08-10 15:46:54.929   788   930 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-10 15:46:54.929   788   930 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-10 15:46:54.929   788   930 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-10 15:46:54.929   788   930 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-10 15:46:54.929   788   862 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-10 15:46:54.929   788   930 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-10 15:46:54.929   788   930 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-10 15:46:54.929   788   862 I ActivityManager: Killing 6345:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-10 15:46:54.939   788   862 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 15:46:54.939   788   862 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-10 15:46:54.949  6768  6768 E Zygote  : v2
08-10 15:46:54.949  6768  6768 I libpersona: KNOX_SDCARD checking this for 10004
08-10 15:46:54.949  6768  6768 I libpersona: KNOX_SDCARD not a persona
,08-10 15:46:54.949  6768  6768 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:54.949  6768  6768 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:54.949  6768  6768 E Zygote  : accessInfo : 0
08-10 15:46:54.949   788   862 I ActivityManager: Start proc 6768:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-10 15:46:54.949  6768  6768 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-10 15:46:54.959   788   862 I ActivityManager:   Force finishing activity ActivityRecord{55cfc0b u0 com.test.thalitest/.MainActivity t152}
,08-10 15:46:54.969   294   359 I SurfaceFlinger: id=20 Removed NainActivit (4/10)
,08-10 15:46:54.969   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:54.969   294   368 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-10 15:46:54.989  6768  6768 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:54.989  6768  6768 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:54.999   788   930 D AASAinstall: there is not AASApackages.xml file
,08-10 15:46:55.029   788   801 D GraphicsStats: Buffer count: 4
08-10 15:46:55.029   788  1320 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@68a91b1)
,08-10 15:46:55.029   788  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 15:46:55.029   788  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 15:46:55.029   788  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 15:46:55.279   788   930 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-10 15:46:55.299   788   930 W PackageSettings: Skipping PackageSetting{1a5be62 com.example.hello/10192} due to missing metadata
,08-10 15:46:55.369   788   930 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-10 15:46:55.379   788  1568 I ActivityManager: Killing 5515:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-10 15:46:55.389   329   329 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-10 15:46:55.399  6768  6768 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-10 15:46:55.399   788  1749 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-10 15:46:55.409   788   930 I art     : Starting a blocking GC Explicit
,08-10 15:46:55.419  6768  6768 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
08-10 15:46:55.419  6768  6768 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-10 15:46:55.419  6768  6768 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-10 15:46:55.419  6768  6768 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-10 15:46:55.439  6768  6768 D AndroidRuntime: Shutting down VM
,08-10 15:46:55.439  6768  6768 E AndroidRuntime: FATAL EXCEPTION: main
08-10 15:46:55.439  6768  6768 E AndroidRuntime: Process: com.test.thalitest, PID: 6768
08-10 15:46:55.439  6768  6768 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-10 15:46:55.439  6768  6768 E AndroidRuntime: 	... 9 more
,08-10 15:46:55.459  6800  6800 E Zygote  : v2
,08-10 15:46:55.459  6800  6800 I libpersona: KNOX_SDCARD checking this for 1000
08-10 15:46:55.459  6800  6800 I libpersona: KNOX_SDCARD not a persona
08-10 15:46:55.459  6800  6800 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-10 15:46:55.459  6800  6800 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-10 15:46:55.459   788   862 I ActivityManager: Start proc 6800:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-10 15:46:55.459  6768  6768 I Process : Sending signal. PID: 6768 SIG: 9
08-10 15:46:55.459  6800  6800 E Zygote  : accessInfo : 0
,08-10 15:46:55.479   788   801 I ActivityManager: Process com.test.thalitest (pid 6768)(adj 9) has died(144,748)
,08-10 15:46:55.479   788   801 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 15:46:55.479   788   801 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-10 15:46:55.489   788   801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-10 15:46:55.489   788   862 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-10 15:46:55.489   788   862 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-10 15:46:55.499  6800  6800 D TimaKeyStoreProvider: TimaSignature is unavailable
08-10 15:46:55.499  6800  6800 D ActivityThread: Added TimaKeyStore provider
,08-10 15:46:55.499   788  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14a2696 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2585217 6800:com.samsung.android.sm/1000}
,08-10 15:46:55.509  6800  6800 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-10 15:46:55.549  6800  6800 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-10 15:46:55.559   788  1568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14a2696 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb3b115 4270:com.google.android.gms/u0a11}
,08-10 15:46:55.589   788   930 I art     : Explicit concurrent mark sweep GC freed 87924(4MB) AllocSpace objects, 13(260KB) LOS objects, 27% free, 41MB/57MB, paused 1.846ms total 181.312ms
,08-10 15:46:55.619   788   930 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-10 15:46:55.619   788   930 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-10 15:46:55.619   788   930 D AASAinstall: there is not AASApackages.xml file
,08-10 15:46:55.619   788   930 D PackageManager: result of delete: 1{197762136}
,08-10 15:46:55.619  6752  6752 I art     : System.exit called, status: 0
08-10 15:46:55.619  6752  6752 I AndroidRuntime: VM exiting with result code 0.
,08-10 15:46:55.629   788   930 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-10 15:46:55.629   788   930 D PackageManager: userId{-1}
08-10 15:46:55.629   788   930 D PackageManager: andCode{true}
,08-10 15:46:55.629   788   930 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-10 15:46:55.649  5961  6817 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-10 15:46:55.649  5961  6817 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-10 15:46:55.649  5961  6817 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-10 15:46:55.689   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.689   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.689   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.689  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,08-10 15:46:55.689  1383  1383 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-10 15:46:55.689   788   906 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699   788   906 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.699   788  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.699   788   788 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.699  2046  2046 E SamsungIME: mOCRHelper is null
,08-10 15:46:55.709   788   788 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.709   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.709   788   862 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f724921 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b529a9d 4331:com.samsung.klmsagent/u0a18}
,08-10 15:46:55.709   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.709  4331  4331 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Aug 10 15:46:55 GMT+02:00 2016
08-10 15:46:55.709   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.709   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719  1975  2212 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719   788   788 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.719  3187  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 15:46:55.729  3187  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 15:46:55.729   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.729   788  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-10 15:46:55.729  3187  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 15:46:55.729  1717  1717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-10 15:46:55.729  3187  3216 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-10 15:46:55.739   788  1649 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-10 15:46:55.739   788   847 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.739  4331  4331 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-10 15:46:55.739  4331  4331 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-10 15:46:55.739  4331  4331 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.749  4331  4331 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-10 15:46:55.749  4331  6828 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-10 15:46:55.749  4331  6828 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-10 15:46:55.749  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-10 15:46:55.749  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-10 15:46:55.749  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-10 15:46:55.749  4331  6828 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.749   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759  4331  6828 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759  4331  6828 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788  1323 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
08-10 15:46:55.759   788  1323 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788  1322 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-10 15:46:55.759   788  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-10 15:46:55.759   788  1322 V NetworkStats: performPollLocked(flags=0x3)
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.759   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.769  4331  6828 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-10 15:46:55.769   788   800 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f724921 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{263e13e 788:system/1000}
,08-10 15:46:55.769   788  1322 V NetworkStats: performPollLocked() took 10ms
08-10 15:46:55.769   788  1322 D NtpTrustedTime: currentTimeMillis() cache hit
08-10 15:46:55.769  4331  6828 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-10 15:46:55.769   788   788 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.779   788   788 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.779   788  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-10 15:46:55.779   788  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-10 15:46:55.779  4331  6828 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-10 15:46:55.779   788   788 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.779   788   788 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.789  4331  6828 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: #################################################################
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: #################################################################
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:55.789  4331  6828 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: #################################################################
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: #################################################################
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:55.789  4331  6828 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-10 15:46:55.789   788   788 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.789   788   788 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.789  4331  6828 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-10 15:46:55.789  4331  6828 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-10 15:46:55.799   788   847 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   847 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.799   788   788 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.809   788   788 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.809   788   788 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.809  1707  6829 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-10 15:46:55.809   788   788 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.809  1707  6829 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-10 15:46:55.809   788   788 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.809  1707  6829 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,08-10 15:46:55.809  1707  6829 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-10 15:46:55.809  1707  6829 D RegisteredComponentCache: Collect Tech packages for Knox
,08-10 15:46:55.819   788   788 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.819   788   788 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.819   788  1746 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-10 15:46:55.819   788  1746 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-10 15:46:55.819   788  1746 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-10 15:46:55.819   788  1746 D SettingsProvider: selectionArgs: false
08-10 15:46:55.819   788  1746 D SettingsProvider: selectionArgs: 10018
,08-10 15:46:55.819   788  1746 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-10 15:46:55.829   788  1746 D SettingsProvider: ret = -1
,08-10 15:46:55.829  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-10 15:46:55.829  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-10 15:46:55.829   788   788 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.839   788   788 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.839   788   788 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.839   788   788 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.839  4270  6815 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9afad16c in tid 6815 (IntentService[D)
,08-10 15:46:55.839   788   788 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.839   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.839   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.849   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.849   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.849   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.849  2374  2374 E audit_log: File locking failed. error= Bad file descriptor
,08-10 15:46:55.849  2374  2374 E audit_log: File locking failed. error= Bad file descriptor
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.859   788  1298 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.859   788   788 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   847 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.869   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.879   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-10 15:46:55.879   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.879   788   788 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-10 15:46:55.879   788   788 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-10 15:46:55.879   788   788 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d7c9aeb in tid 788 (system_server)
08-10 15:46:55.879   788   788 F libc    : Unable to open connection to debuggerd: Connection refused
,08-10 15:46:55.879  2374  2374 E audit_log: File locking failed. error= Bad file descriptor
,08-10 15:46:55.939   350   350 I Zygote  : Process 4270 exited due to signal (7)
,08-10 15:46:55.949   293   293 I ServiceManager: service 'servicediscovery' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'updatelock' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'notification' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'devicestoragemonitor' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'location' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'country_detector' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sec_location' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'search' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'execute' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'dropbox' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'wallpaper' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'audio' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'DockObserver' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'midi' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'usb' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'serial' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'kiesusb' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'jobscheduler' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'backup' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'appwidget' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'voiceinteraction' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'SecExternalDisplayService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'diskstats' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'mDNIe' died
08-10 15:46:55.949  2786  2799 W Sensors : sensorservice died [0xada0ac00]
08-10 15:46:55.949   293   293 I ServiceManager: service 'AAS' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'MSCS' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'spengestureservice' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'quickconnect' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'samplingprofiler' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'commontime_management' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'dreams' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'graphicsstats' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'print' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'restrictions' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'media_session' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'media_router' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'trust' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'fingerprint' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'launcherapps' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'voip' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'media_projection' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'telecom' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'activity' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'user' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'procstats' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'meminfo' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'gfxinfo' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'dbinfo' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'cpuinfo' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'permission' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'processinfo' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sen,sorservice' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'mdm.remotedesktop' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'battery' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'usagestats' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'webviewupdate' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'scheduling_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'telephony.registry' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'persona' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'knox_ccm_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'enterprise_license_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'application_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'wifi_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'phone_restriction_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'remoteinjection' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'knox_ucsm_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'edm_proxy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'mum_container_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'enterprise_billing_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'otp_service' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'enterprise_shared_device_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'knox_timakeystore_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'SEAMService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'media.camera.proxy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'account' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'content' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'DirEncryptService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'LSManager' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'ReactiveService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'DeviceRootKeyService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'EngineeringModeService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'SatsService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sedenial' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'vibrator' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'tw_toolbox' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'tima' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'iccc' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'cepproxyks' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'emailksproxy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'CustomFrequencyManagerService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'consumer_ir' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'alarm' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'package' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'persona_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sec_analytics' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'cover' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'mount' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'lock_settings' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'deviceidle' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'device_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'harmony_eas_service' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sdp' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sdp_log' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'dlp' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'log_manager_service' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'enterprise_policy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'statusbar' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'clipboard' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'clipboardEx' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'network_management' died
08-10 15:46:55.949  1875  1889 W Sensors : sensorservice died [0xad826e80]
08-10 15:46:55.949   293   293 I ServiceManager: service 'lpnet' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'ABTPersistenceService' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'textservices' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'network_score' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'netstats' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'netpolicy' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'wifip2p' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'wifi' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'wifihs20' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'wifiscanner' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'rttmanager' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'ethernet' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'connectivity' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'sb_service' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'context_aware' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'scontext' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'barbeam' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'multiwindow_facade' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'window' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'input' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'imms' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'bluetooth_manager' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'rcp' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'input_method' died
08-10 15:46:55.969  2374  2374 E audit_log: File locking failed. error= Bad file descriptor
08-10 15:46:55.949   293   293 I ServiceManager: service 'accessibility' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'edmnativehelper' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'uimode' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'batterystats' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'appops' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'power' died
08-10 15:46:55.949   293   293 I ServiceManager: service 'display' died
08-10 15:46:55.949  1733  1744 W Sensors : sensorservice died [0xad825280]
08-10 15:46:55.959   323   987 W AudioFlinger: power manager service died !!!
08-10 15:46:55.959   323   987 W AudioFlinger: power manager service died !!!
08-10 15:46:55.959   294  5194 D libEGL  : eglTerminate EGLDisplay = 0xb2a7f6fc
08-10 15:46:55.959   294  5194 I SurfaceFlinger: restart the boot-animation @ binderDied
08-10 15:46:55.959  1717  2163 E WifiManager: Channel connection lost
08-10 15:46:55.959  1818  1953 E WifiManager: Channel connection lost
08-10 15:46:55.959  2786  3171 E WifiManager: Channel connection lost
08-10 15:46:55.959  5701  5777 E WifiManager: Channel connection lost
08-10 15:46:55.959   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-10 15:46:55.959   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-10 15:46:55.969  2362  2362 D HeadsetStateMachine: Proxy object disconnected
08-10 15:46:55.969  1975  2208 E WifiManager: Channel connection lost
08-10 15:46:55.969  2362  2362 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ed96894 in tid 2362 (droid.bluetooth)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=14 Removed EimLayer(Di (6/9)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=15 Removed EimLayer(An (2/8)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=2 Removed GocusedStac (3/7)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/6)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=4 Removed EimLayer(An (0/5)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-10 15:46:55.969   294   368 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-10 15:46:55.969  2362  2362 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 15:46:55.969  1717  1717 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-10 15:46:55.969  1383  1626 E WifiManager: Channel connection lost
08-10 15:46:55.979  1975  1998 W Sensors : sensorservice died [0xb2dfea00]
08-10 15:46:55.979  2419  2454 W Sensors : sensorservice died [0xb3a72d40]
08-10 15:46:55.979   327   327 E installd: eof
08-10 15:46:55.979   327   327 E installd: failed to read size
08-10 15:46:55.979   327   327 I installd: closing connection
08-10 15:46:55.979  1383  2204 W Sensors : sensorservice died [0xaa7f0d80]
08-10 15:46:55.979   294   368 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/5)
08-10 15:46:55.979   294  1296 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-10 15:46:55.979   294  1296 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-10 15:46:55.979   294  1296 I SurfaceFlinger: id=7 Removed JmageWallpa (0/3)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/3)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=21 Removed VSBConnecti (1/2)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=22 Removed VSBConnecti (0/1)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/1)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/1)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=18 Removed DolorFade (0/0)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=18 Removed DolorFade (-2/0)
08-10 15:46:55.979   294   359 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: Failure retrieving array; only received 99 of 302
08-10 15:46:55.979  4331  6828 W ParceledListSlice: android.os.DeadObjectException
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.os.BinderProxy.transact(Binder.java:503)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.content.pm.ParceledListSlice.<init>(ParceledListSlice.java:97)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.content.pm.ParceledListSlice.<init>(ParceledListSlice.java:41)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.content.pm.ParceledListSlice$2.createFromParcel(ParceledListSlice.java:200)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.content.pm.ParceledListSlice$2.createFromParcel(ParceledListSlice.java:198)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.content.pm.IPackageManager$Stub$Proxy.getInstalledPackages(IPackageManager.java:4012)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.app.ApplicationPackageManager.getInstalledPackages(ApplicationPackageManager.java:669)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.app.ApplicationPackageManager.getInstalledPackages(ApplicationPackageManager.java:662)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at com.samsung.klmsagent.util.KLMSUtility.IsPackageExistInDevice(KLMSUtility.java:236)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:618)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:55.979  4331  6828 W ParceledListSlice: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:46:55.979  4331  6828 D KLMS-2.6.032: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 99
08-10 15:46:55.979  4331  6828 D KLMS-2.6.032: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
08-10 15:46:55.979  4331  6828 I KLMS-2.6.032: : KLMSSharedPreferences(): getNotificationAppList(): null
08-10 15:46:55.979  4331  6828 D KLMS-2.6.032: : Systemprocess(): Notification App List is Null. Remove Notification.
08-10 15:46:55.979  4331  6828 E KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM() has Exception.
08-10 15:46:55.979  4331  6828 W System.err: java.lang.NullPointerException: Attempt to invoke interface method 'void android.app.INotificationManager.cancelNotificationWithTag(java.lang.String, java.lang.String, int, int)' on a null object reference
08-10 15:46:55.979  4331  6828 W System.err: 	at android.app.NotificationManager.cancel(NotificationManager.java:342)
08-10 15:46:55.979  4331  6828 W System.err: 	at android.app.NotificationManager.cancel(NotificationManager.java:328)
08-10 15:46:55.989  4331  6828 W System.err: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:624)
08-10 15:46:55.989  4331  6828 W System.err: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-10 15:46:55.989  4331  6828 W System.err: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-10 15:46:55.989  4331  6828 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:46:55.989  4331  6828 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:46:55.989  4331  6828 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-10 15:46:55.989  4331  6828 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:46:55.989  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().END
08-10 15:46:55.989  4331  6828 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().END
08-10 15:46:55.989  4331  6828 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x70f97766 in tid 6828 (IntentService[K)
08-10 15:46:55.989  4331  6828 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 15:46:55.989  2374  2374 E audit_log: File locking failed. error= Bad file descriptor
08-10 15:46:55.989  2411  2411 D BluetoothA2dp: Proxy object disconnected
,08-10 15:46:55.999  2786  2786 D BluetoothA2dp: Proxy object disconnected
08-10 15:46:55.999  2786  2786 D A2dpProfile: Bluetooth service disconnected
08-10 15:46:55.999  2786  2786 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 15:46:55.999  2786  2786 D PanProfile: Bluetooth service disconnected
08-10 15:46:55.999  2786  2786 D BluetoothMap: Proxy object disconnected
08-10 15:46:55.999  2786  2786 D MapProfile: Bluetooth service disconnected
08-10 15:46:55.999  2786  2786 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9b72bd in tid 2786 (ndroid.settings)
08-10 15:46:55.999  2786  2786 F libc    : Unable to open connection to debuggerd: Connection refused
08-10 15:46:55.999  2374  2374 E audit_log: File locking failed. error= Bad file descriptor
08-10 15:46:56.009   350   350 I Zygote  : Process 4331 exited due to signal (7)
,08-10 15:46:56.049   350   350 I Zygote  : Process 2786 exited due to signal (7)
,08-10 15:46:56.049   350   350 I Zygote  : Process 2362 exited due to signal (7)
,08-10 15:46:56.209   294   552 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-10 15:46:56.209   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-10 15:46:56.419   292   292 I lowmemorykiller: ActivityManager disconnected
08-10 15:46:56.419   292   292 I lowmemorykiller: Closing Activity Manager data connection
,08-10 15:46:56.459   294   294 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-10 15:46:56.459   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb3a4
,08-10 15:46:56.469   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.469   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.469   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.469   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.479   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.479   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.479   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb38c
,08-10 15:46:56.479   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbe8cb3a4
,08-10 15:46:56.499   294   294 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,08-10 15:46:56.499   294   294 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
08-10 15:46:56.499   294   294 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,08-10 15:46:56.519   294   552 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
