#### Test 833712394bbb446_thali01_samsung-SM-G900F Logs


```
--------- beginning of system,
08-31 03:04:15.918   756  1554 E Watchdog: !@Sync 8 [08-31 03:04:15.928]
08-31 03:04:16.118   756  3635 D SSRM:n  : SIOP:: AP = 300, PST = 311, CUR = 300, LCD = 0
--------- beginning of main
08-31 03:04:16.998  2221  2221 E audit   : type=1400 msg=audit(1472605456.998:285): avc:  denied  { execmod } for  pid=7090 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 03:04:17.008  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:17.008  2221  2221 E audit   : type=1300 msg=audit(1472605456.998:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b402b000 a1=51000 a2=5 a3=4 items=0 ppid=3741 ppcomm=adbd pid=7090 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 03:04:17.008  2221  2221 E audit   : type=1327 msg=audit(1472605456.998:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-31 03:04:17.018  2221  2221 E audit   : type=1320 msg=audit(1472605456.998:285): 
08-31 03:04:17.058  2221  2221 E audit   : type=1400 msg=audit(1472605457.048:286): avc:  denied  { execmod } for  pid=7090 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 03:04:17.058  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:17.058  2221  2221 E audit   : type=1300 msg=audit(1472605457.048:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3741 ppcomm=adbd pid=7090 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 03:04:17.058  2221  2221 E audit   : type=1327 msg=audit(1472605457.048:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-31 03:04:17.058  2221  2221 E audit   : type=1320 msg=audit(1472605457.048:286): 
08-31 03:04:17.098  2221  2221 E audit   : type=1400 msg=audit(1472605457.098:287): avc:  denied  { execmod } for  pid=7090 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 03:04:17.098  7090  7090 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 03:04:17.098  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:17.098  2221  2221 E audit   : type=1300 msg=audit(1472605457.098:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3741 ppcomm=adbd pid=7090 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 03:04:17.108  2221  2221 E audit   : type=1327 msg=audit(1472605457.098:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-31 03:04:17.108  2221  2221 E audit   : type=1320 msg=audit(1472605457.098:287): 
08-31 03:04:17.108  7090  7090 D AndroidRuntime: CheckJNI is OFF
08-31 03:04:17.108  7090  7090 D AndroidRuntime: readGMSProperty: start
08-31 03:04:17.108  7090  7090 D AndroidRuntime: readGMSProperty: already setted!!
08-31 03:04:17.108  7090  7090 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 03:04:17.108  7090  7090 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 03:04:17.108  7090  7090 D AndroidRuntime: readGMSProperty: end
08-31 03:04:17.108  7090  7090 D AndroidRuntime: addProductProperty: start
08-31 03:04:17.118  7090  7090 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 03:04:17.118  7090  7090 W art     : af18e000-b20b4000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-31 03:04:17.118  7090  7090 W art     : b20b4000-b4323000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-31 03:04:17.118  7090  7090 W art     : b4323000-b4324000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-31 03:04:17.118  7090  7090 W art     : b4324000-b4772000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-31 03:04:17.118  7090  7090 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b4773000-b477d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-31 03:04:17.118  7090  7090 W art     : b477d000-b477e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-31 03:04:17.118  7090  7090 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-31 03:04:17.118  7090  7090 W art     : b488f000-b48b8000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 03:04:17.118  7090  7090 W art     : b48b8000-b48bb000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-31 03:04:17.118  7090  7090 W art     : b48bb000-b48bc000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-31 03:04:17.118  7090  7090 W art     : b48bc000-b48bd000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-31 03:04:17.118  7090  7090 W art     : b48bd000-b48be000 r--p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b48be000-b48de000 r--s 00000000 00:0b 8195       /dev/__properties__
08-31 03:04:17.118  7090  7090 W art     : b48de000-b52ef000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-31 03:04:17.118  7090  7090 W art     : b52ef000-b52f0000 ---p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b52f0000-b5339000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-31 03:04:17.118  7090  7090 W art     : b5339000-b533a000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-31 03:04:17.118  7090  7090 W art     : b533a000-b5342000 rw-p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b5342000-b5377000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-31 03:04:17.118  7090  7090 W art     : b5377000-b5378000 ---p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b5378000-b5379000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-31 03:04:17.118  7090  7090 W art     : b5379000-b537a000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-31 03:04:17.118  7090  7090 W art     : b537a000-b53d2000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-31 03:04:17.118  7090  7090 W art     : b53d2000-b53d3000 ---p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b53d3000-b53d4000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-31 03:04:17.118  7090  7090 W art     : b53d4000-b53d5000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-31 03:04:17.118  7090  7090 W art     : b53d6000-b53dc000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 03:04:17.118  7090  7090 W art     : b53dc000-b53dd000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 03:04:17.118  7090  7090 W art     : b53dd000-b53de000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 03:04:17.118  7090  7090 W art     : b53de000-b53e0000 rw-p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b53e1000-b53eb000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 03:04:17.118  7090  7090 W art     : b53eb000-b53ee000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 03:04:17.118  7090  7090 W art     : b53ee000-b53ef000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 03:04:17.118  7090  7090 W art     : b53f0000-b5407000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 03:04:17.118  7090  7090 W art     : b5407000-b5408000 ---p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b5408000-b5409000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 03:04:17.118  7090  7090 W art     : b5409000-b540a000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 03:04:17.118  7090  7090 W art     : b540b000-b5415000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-31 03:04:17.118  7090  7090 W art     : b5415000-b5416000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-31 03:04:17.118  7090  7090 W art     : b5416000-b5417000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-31 03:04:17.118  7090  7090 W art     : b5417000-b541b000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 03:04:17.118  7090  7090 W art     : b541b000-b541c000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 03:04:17.118  7090  7090 W art     : b541c000-b541d000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 03:04:17.118  7090  7090 W art     : b541d000-b5433000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-31 03:04:17.118  7090  7090 W art     : b5433000-b5434000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-31 03:04:17.118  7090  7090 W art     : b5434000-b5435000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-31 03:04:17.118  7090  7090 W art     : b5435000-b5442000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-31 03:04:17.118  7090  7090 W art     : b5442000-b5443000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-31 03:04:17.118  7090  7090 W art     : b5443000-b5444000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-31 03:04:17.118  7090  7090 W art     : b5444000-b54a4000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-31 03:04:17.118  7090  7090 W art     : b54a4000-b54a7000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-31 03:04:17.118  7090  7090 W art     : b54a7000-b54ab000 rw-p 00000000 00:00 0 
08-31 03:04:17.118  7090  7090 W art     : b54ab000-b550c000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-31 03:04:17.118  7090  7090 W art     : b550c000-b550d000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-31 03:04:17.118  7090  7090 W art     : b550d000-b555c000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-31 03:04:17.128  7090  7090 W art     : b555c000-b555e000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-31 03:04:17.128  7090  7090 W art     : b555e000-b555f000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-31 03:04:17.128  7090  7090 W art     : b555f000-b5560000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5560000-b5567000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 03:04:17.128  7090  7090 W art     : b5567000-b5568000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 03:04:17.128  7090  7090 W art     : b5568000-b5569000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-31 03:04:17.128  7090  7090 W art     : avc_common.so
08-31 03:04:17.128  7090  7090 W art     : b556a000-b556d000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 03:04:17.128  7090  7090 W art     : b556d000-b556e000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 03:04:17.128  7090  7090 W art     : b556e000-b556f000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-31 03:04:17.128  7090  7090 W art     : enc_common.so
08-31 03:04:17.128  7090  7090 W art     : b5570000-b5574000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-31 03:04:17.128  7090  7090 W art     : b5574000-b5575000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5575000-b5576000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-31 03:04:17.128  7090  7090 W art     : b5576000-b5577000 rw-p 00005000 b3:17 2510       /syste
08-31 03:04:17.128  7090  7090 W art     : m/lib/libpowermanager.so
08-31 03:04:17.128  7090  7090 W art     : b5578000-b5595000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 03:04:17.128  7090  7090 W art     : b5595000-b5596000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 03:04:17.128  7090  7090 W art     : b5596000-b5597000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 03:04:17.128  7090  7090 W art     : b5598000-b559d000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 03:04:17.128  7090  7090 W art     : b559d000-b559e000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 03:04:17.128  7090  7090 W art     : b559e000-b559f000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 03:04:17.128  7090  7090 W art     : b55a0000-b55d1000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 03:04:17.128  7090  7090 W art     : b55d1000-b55d2000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b55d2000-b55d5000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 03:04:17.128  7090  7090 W art     : b55d5000-b55d6000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 03:04:17.128  7090  7090 W art     : b55d7000-b5612000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-31 03:04:17.128  7090  7090 W art     : b5612000-b5613000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-31 03:04:17.128  7090  7090 W art     : b5613000-b5614000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-31 03:04:17.128  7090  7090 W art     : b5615000-b561c000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-31 03:04:17.128  7090  7090 W art     : b561c000-b561d000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b561d000-b561e000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-31 03:04:17.128  7090  7090 W art     : b561e000-b561f000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-31 03:04:17.128  7090  7090 W art     : b561f000-b5620000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5620000-b5637000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-31 03:04:17.128  7090  7090 W art     : b5637000-b5638000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5638000-b563b000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-31 03:04:17.128  7090  7090 W art     : b563b000-b563c000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-31 03:04:17.128  7090  7090 W art     : b563c000-b565b000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-31 03:04:17.128  7090  7090 W art     : b565b000-b565c000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-31 03:04:17.128  7090  7090 W art     : b565c000-b565d000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-31 03:04:17.128  7090  7090 W art     : b565d000-b569b000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-31 03:04:17.128  7090  7090 W art     : b569b000-b569c000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b569c000-b569e000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-31 03:04:17.128  7090  7090 W art     : b569e000-b569f000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-31 03:04:17.128  7090  7090 W art     : b56a0000-b56a7000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 03:04:17.128  7090  7090 W art     : b56a7000-b56a8000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 03:04:17.128  7090  7090 W art     : b56a8000-b56a9000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 03:04:17.128  7090  7090 W art     : b56aa000-b56ad000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 03:04:17.128  7090  7090 W art     : b56ad000-b56ae000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 03:04:17.128  7090  7090 W art     : b56ae000-b56af000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 03:04:17.128  7090  7090 W art     : b56af000-b56b5000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 03:04:17.128  7090  7090 W art     : b56b5000-b56b6000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b56b6000-b56b7000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 03:04:17.128  7090  7090 W art     : b56b7000-b56b8000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 03:04:17.128  7090  7090 W art     : b56b8000-b56c1000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-31 03:04:17.128  7090  7090 W art     : b56c1000-b56c2000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-31 03:04:17.128  7090  7090 W art     : b56c2000-b56c3000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-31 03:04:17.128  7090  7090 W art     : b56c3000-b5754000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 03:04:17.128  7090  7090 W art     : b5754000-b5755000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5755000-b5760000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 03:04:17.128  7090  7090 W art     : b5760000-b5761000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 03:04:17.128  7090  7090 W art     : b5762000-b5774000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-31 03:04:17.128  7090  7090 W art     : b5774000-b5775000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-31 03:04:17.128  7090  7090 W art     : b5775000-b5776000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-31 03:04:17.128  7090  7090 W art     : b5777000-b577c000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-31 03:04:17.128  7090  7090 W art     : b577c000-b577d000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-31 03:04:17.128  7090  7090 W art     : b577d000-b577e000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-31 03:04:17.128  7090  7090 W art     : b577f000-b57ec000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-31 03:04:17.128  7090  7090 W art     : b57ec000-b57ed000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b57ed000-b57ef000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-31 03:04:17.128  7090  7090 W art     : b57ef000-b57f0000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-31 03:04:17.128  7090  7090 W art     : b57f0000-b57f1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b57f1000-b57f8000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 03:04:17.128  7090  7090 W art     : b57f8000-b57f9000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 03:04:17.128  7090  7090 W art     : b57f9000-b57fa000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 03:04:17.128  7090  7090 W art     : b57fb000-b587b000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 03:04:17.128  7090  7090 W art     : b587b000-b587c000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b587c000-b587d000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 03:04:17.128  7090  7090 W art     : b587d000-b587e000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 03:04:17.128  7090  7090 W art     : b587e000-b5895000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5895000-b58cc000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 03:04:17.128  7090  7090 W art     : b58cc000-b58cd000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 03:04:17.128  7090  7090 W art     : b58cd000-b58ce000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 03:04:17.128  7090  7090 W art     : b58ce000-b58ea000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 03:04:17.128  7090  7090 W art     : b58ea000-b58eb000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 03:04:17.128  7090  7090 W art     : b58eb000-b58ec000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 03:04:17.128  7090  7090 W art     : b58ed000-b594e000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-31 03:04:17.128  7090  7090 W art     : b594e000-b5950000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-31 03:04:17.128  7090  7090 W art     : b5950000-b5951000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-31 03:04:17.128  7090  7090 W art     : b5952000-b5977000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-31 03:04:17.128  7090  7090 W art     : b5977000-b5978000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-31 03:04:17.128  7090  7090 W art     : b5978000-b5979000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-31 03:04:17.128  7090  7090 W art     : b597a000-b5982000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 03:04:17.128  7090  7090 W art     : b5982000-b5984000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 03:04:17.128  7090  7090 W art     : b5984000-b5985000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 03:04:17.128  7090  7090 W art     : b5986000-b5989000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-31 03:04:17.128  7090  7090 W art     : b5989000-b598a000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-31 03:04:17.128  7090  7090 W art     : b598a000-b598b000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-31 03:04:17.128  7090  7090 W art     : b598b000-b598f000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-31 03:04:17.128  7090  7090 W art     : b598f000-b5990000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5990000-b5991000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-31 03:04:17.128  7090  7090 W art     : b5991000-b5992000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-31 03:04:17.128  7090  7090 W art     : b5992000-b59a2000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-31 03:04:17.128  7090  7090 W art     : b59a2000-b59a3000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-31 03:04:17.128  7090  7090 W art     : b59a3000-b59a4000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-31 03:04:17.128  7090  7090 W art     : b59a4000-b59ea000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b59ea000-b59f3000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-31 03:04:17.128  7090  7090 W art     : b59f3000-b59f4000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-31 03:04:17.128  7090  7090 W art     : b59f4000-b59f5000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-31 03:04:17.128  7090  7090 W art     : b59f6000-b59fb000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-31 03:04:17.128  7090  7090 W art     : b59fb000-b59fc000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-31 03:04:17.128  7090  7090 W art     : b59fc000-b59fd000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-31 03:04:17.128  7090  7090 W art     : b59fd000-b5a00000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 03:04:17.128  7090  7090 W art     : b5a00000-b5a01000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5a01000-b5a02000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 03:04:17.128  7090  7090 W art     : b5a02000-b5a03000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 03:04:17.128  7090  7090 W art     : b5a03000-b5a04000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-31 03:04:17.128  7090  7090 W art     : or]
08-31 03:04:17.128  7090  7090 W art     : b5a04000-b5a1c000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 03:04:17.128  7090  7090 W art     : b5a1c000-b5a1d000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5a1d000-b5a1e000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 03:04:17.128  7090  7090 W art     : b5a1e000-b5a1f000 rw-p 00019000 b3:
08-31 03:04:17.128  7090  7090 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-31 03:04:17.128  7090  7090 W art     : b5a20000-b5bba000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-31 03:04:17.128  7090  7090 W art     : b5bba000-b5bbb000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5bbb000-b5bc8000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-31 03:04:17.128  7090  7090 W art     : b5bc8000-b5bc9000 rw-p 001a7000 b3:17 604        /system/
08-31 03:04:17.128  7090  7090 W art     : lib/libstagefright.so
08-31 03:04:17.128  7090  7090 W art     : b5bc9000-b5bcd000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-31 03:04:17.128  7090  7090 W art     : b5bcd000-b5bce000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5bce000-b5bcf000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-31 03:04:17.128  7090  7090 W art     : b5bcf000-b5bd0000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-31 03:04:17.128  7090  7090 W art     : ersona.so
08-31 03:04:17.128  7090  7090 W art     : b5bd0000-b5be3000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-31 03:04:17.128  7090  7090 W art     : b5be3000-b5be4000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-31 03:04:17.128  7090  7090 W art     : b5be4000-b5be5000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-31 03:04:17.128  7090  7090 W art     : b5be6000-b5c31000 r
08-31 03:04:17.128  7090  7090 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-31 03:04:17.128  7090  7090 W art     : b5c31000-b5c32000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-31 03:04:17.128  7090  7090 W art     : b5c32000-b5c33000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-31 03:04:17.128  7090  7090 W art     : b5c33000-b5c35000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5c35000-b5c36000 r--p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5c36000-b5c47000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 03:04:17.128  7090  7090 W art     : b5c47000-b5c48000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5c48000-b5c49000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 03:04:17.128  7090  7090 W art     : b5c49000-b5c4a000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 03:04:17.128  7090  7090 W art     : b5c4a000-b5c4b000 r--p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5c4b000-b5c55000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-31 03:04:17.128  7090  7090 W art     : b5c55000-b5c57000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-31 03:04:17.128  7090  7090 W art     : b5c57000-b5c58000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-31 03:04:17.128  7090  7090 W art     : b5c58000-b5c71000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-31 03:04:17.128  7090  7090 W art     : b5c71000-b5c72000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-31 03:04:17.128  7090  7090 W art     : b5c72000-b5c75000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-31 03:04:17.128  7090  7090 W art     : b5c75000-b5c79000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5c79000-b5ced000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-31 03:04:17.128  7090  7090 W art     : b5ced000-b5cee000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5cee000-b5cf1000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-31 03:04:17.128  7090  7090 W art     : b5cf1000-b5cf2000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-31 03:04:17.128  7090  7090 W art     : b5cf2000-b5cf3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5cf3000-b5cf6000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-31 03:04:17.128  7090  7090 W art     : b5cf6000-b5cf7000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-31 03:04:17.128  7090  7090 W art     : b5cf7000-b5cf8000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-31 03:04:17.128  7090  7090 W art     : b5cf8000-b5cf9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5cf9000-b5cfe000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 03:04:17.128  7090  7090 W art     : b5cfe000-b5cff000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 03:04:17.128  7090  7090 W art     : b5cff000-b5d00000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 03:04:17.128  7090  7090 W art     : b5d00000-b5d01000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5d01000-b5d04000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 03:04:17.128  7090  7090 W art     : b5d04000-b5d05000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 03:04:17.128  7090  7090 W art     : b5d05000-b5d06000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 03:04:17.128  7090  7090 W art     : b5d06000-b5d07000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:17.128  7090  7090 W art     : b5d07000-b5d0b000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-31 03:04:17.128  7090  7090 W art     : b5d0b000-b5d0c000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-31 03:04:17.128  7090  7090 W art     : b5d0c000-b5d0d000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-31 03:04:17.128  7090  7090 W art     : b5d0d000-b5d0e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5d0e000-b5d12000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 03:04:17.128  7090  7090 W art     : b5d12000-b5d13000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 03:04:17.128  7090  7090 W art     : b5d13000-b5d14000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 03:04:17.128  7090  7090 W art     : b5d14000-b5d15000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5d15000-b5d23000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-31 03:04:17.128  7090  7090 W art     : b5d23000-b5d24000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b5d24000-b5d25000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-31 03:04:17.128  7090  7090 W art     : b5d25000-b5d26000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-31 03:04:17.128  7090  7090 W art     : b5d26000-b5d30000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 03:04:17.128  7090  7090 W art     : b5d30000-b5d33000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 03:04:17.128  7090  7090 W art     : b5d33000-b5d34000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 03:04:17.128  7090  7090 W art     : b5d34000-b5d35000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5d35000-b5d3f000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-31 03:04:17.128  7090  7090 W art     : b5d3f000-b5d42000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-31 03:04:17.128  7090  7090 W art     : b5d42000-b5d43000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-31 03:04:17.128  7090  7090 W art     : b5d43000-b5d47000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-31 03:04:17.128  7090  7090 W art     : b5d47000-b5d48000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-31 03:04:17.128  7090  7090 W art     : b5d48000-b5d49000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-31 03:04:17.128  7090  7090 W art     : b5d49000-b5d4a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b5d4a000-b5d57000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-31 03:04:17.128  7090  7090 W art     : b5d57000-b5d59000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-31 03:04:17.128  7090  7090 W art     : b5d59000-b5d5a000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-31 03:04:17.128  7090  7090 W art     : b5d5a000-b616c000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-31 03:04:17.128  7090  7090 W art     : b616c000-b616d000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b616d000-b6176000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-31 03:04:17.128  7090  7090 W art     : b6176000-b617a000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-31 03:04:17.128  7090  7090 W art     : b617a000-b617b000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b617b000-b6182000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-31 03:04:17.128  7090  7090 W art     : b6182000-b6183000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-31 03:04:17.128  7090  7090 W art     : b6183000-b6184000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-31 03:04:17.128  7090  7090 W art     : b6184000-b6185000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6185000-b61a0000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-31 03:04:17.128  7090  7090 W art     : b61a0000-b61a1000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-31 03:04:17.128  7090  7090 W art     : b61a1000-b61a2000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-31 03:04:17.128  7090  7090 W art     : b61a2000-b61a3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b61a3000-b61ef000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 03:04:17.128  7090  7090 W art     : b61ef000-b61f0000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b61f0000-b61f1000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 03:04:17.128  7090  7090 W art     : b61f1000-b61f2000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 03:04:17.128  7090  7090 W art     : b61f2000-b61f3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b61f3000-b61f7000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-31 03:04:17.128  7090  7090 W art     : b61f7000-b61f8000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b61f8000-b61f9000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-31 03:04:17.128  7090  7090 W art     : b61f9000-b61fa000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-31 03:04:17.128  7090  7090 W art     : b61fa000-b6232000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-31 03:04:17.128  7090  7090 W art     : b6232000-b6233000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-31 03:04:17.128  7090  7090 W art     : b6233000-b6234000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-31 03:04:17.128  7090  7090 W art     : b6234000-b6235000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6235000-b62d4000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-31 03:04:17.128  7090  7090 W art     : b62d4000-b62f2000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-31 03:04:17.128  7090  7090 W art     : b62f2000-b62f3000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-31 03:04:17.128  7090  7090 W art     : b62f3000-b6466000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-31 03:04:17.128  7090  7090 W art     : b6466000-b6471000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-31 03:04:17.128  7090  7090 W art     : b6471000-b6472000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-31 03:04:17.128  7090  7090 W art     : b6472000-b6589000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-31 03:04:17.128  7090  7090 W art     : b6589000-b6594000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-31 03:04:17.128  7090  7090 W art     : b6594000-b6595000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-31 03:04:17.128  7090  7090 W art     : b6595000-b6599000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6599000-b65bd000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-31 03:04:17.128  7090  7090 W art     : b65bd000-b65bf000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-31 03:04:17.128  7090  7090 W art     : b65bf000-b65c0000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-31 03:04:17.128  7090  7090 W art     : b65c0000-b6666000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-31 03:04:17.128  7090  7090 W art     : b6666000-b6673000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-31 03:04:17.128  7090  7090 W art     : b6673000-b6674000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-31 03:04:17.128  7090  7090 W art     : b6674000-b6675000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6675000-b66c8000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-31 03:04:17.128  7090  7090 W art     : b66c8000-b66c9000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b66c9000-b66ca000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-31 03:04:17.128  7090  7090 W art     : b66ca000-b66cb000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-31 03:04:17.128  7090  7090 W art     : b66cb000-b66d0000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b66d0000-b66e2000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-31 03:04:17.128  7090  7090 W art     : b66e2000-b66e3000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b66e3000-b66e4000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-31 03:04:17.128  7090  7090 W art     : b66e4000-b66e5000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-31 03:04:17.128  7090  7090 W art     : b66e5000-b66ec000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 03:04:17.128  7090  7090 W art     : b66ec000-b66ed000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 03:04:17.128  7090  7090 W art     : b66ed000-b66ee000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 03:04:17.128  7090  7090 W art     : b66ee000-b66ef000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b66ef000-b66f2000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-31 03:04:17.128  7090  7090 W art     : b66f2000-b66f3000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-31 03:04:17.128  7090  7090 W art     : b66f3000-b66f4000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-31 03:04:17.128  7090  7090 W art     : b66f4000-b66f8000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-31 03:04:17.128  7090  7090 W art     : b66f8000-b66f9000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-31 03:04:17.128  7090  7090 W art     : b66f9000-b66fa000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-31 03:04:17.128  7090  7090 W art     : b66fa000-b6708000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-31 03:04:17.128  7090  7090 W art     : b6708000-b6709000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6709000-b670a000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-31 03:04:17.128  7090  7090 W art     : b670a000-b670b000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-31 03:04:17.128  7090  7090 W art     : b670b000-b6714000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 03:04:17.128  7090  7090 W art     : b6714000-b6715000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 03:04:17.128  7090  7090 W art     : b6715000-b6716000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 03:04:17.128  7090  7090 W art     : b6716000-b677c000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-31 03:04:17.128  7090  7090 W art     : b677c000-b677d000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b677d000-b677f000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-31 03:04:17.128  7090  7090 W art     : b677f000-b6788000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-31 03:04:17.128  7090  7090 W art     : b6788000-b678b000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b678b000-b6822000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-31 03:04:17.128  7090  7090 W art     : b6822000-b6824000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-31 03:04:17.128  7090  7090 W art     : b6824000-b6825000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-31 03:04:17.128  7090  7090 W art     : b6825000-b6826000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6826000-b6b44000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-31 03:04:17.128  7090  7090 W art     : b6b44000-b6b45000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6b45000-b6b60000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-31 03:04:17.128  7090  7090 W art     : b6b60000-b6b64000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-31 03:04:17.128  7090  7090 W art     : b6b64000-b6b69000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6b69000-b6b71000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 03:04:17.128  7090  7090 W art     : b6b71000-b6b72000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 03:04:17.128  7090  7090 W art     : b6b72000-b6b73000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 03:04:17.128  7090  7090 W art     : b6b73000-b6ba1000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-31 03:04:17.128  7090  7090 W art     : b6ba1000-b6ba2000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6ba2000-b6ba9000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-31 03:04:17.128  7090  7090 W art     : b6ba9000-b6baa000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-31 03:04:17.128  7090  7090 W art     : b6baa000-b6bf0000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-31 03:04:17.128  7090  7090 W art     : b6bf0000-b6bf1000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6bf1000-b6bf4000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-31 03:04:17.128  7090  7090 W art     : b6bf4000-b6bf5000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-31 03:04:17.128  7090  7090 W art     : b6bf5000-b6c10000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-31 03:04:17.128  7090  7090 W art     : b6c10000-b6c14000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-31 03:04:17.128  7090  7090 W art     : b6c14000-b6c15000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-31 03:04:17.128  7090  7090 W art     : b6c15000-b6c62000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-31 03:04:17.128  7090  7090 W art     : b6c62000-b6c63000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6c63000-b6c6f000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-31 03:04:17.128  7090  7090 W art     : b6c6f000-b6c70000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-31 03:04:17.128  7090  7090 W art     : b6c70000-b6c7d000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-31 03:04:17.128  7090  7090 W art     : b6c7d000-b6c7e000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6c7e000-b6c7f000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-31 03:04:17.128  7090  7090 W art     : b6c7f000-b6c80000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-31 03:04:17.128  7090  7090 W art     : b6c80000-b6c88000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-31 03:04:17.128  7090  7090 W art     : b6c88000-b6c89000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6c89000-b6c8a000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-31 03:04:17.128  7090  7090 W art     : b6c8a000-b6c8b000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-31 03:04:17.128  7090  7090 W art     : b6c8b000-b6c92000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-31 03:04:17.128  7090  7090 W art     : b6c92000-b6c93000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-31 03:04:17.128  7090  7090 W art     : b6c93000-b6c94000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-31 03:04:17.128  7090  7090 W art     : b6c94000-b6ca8000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-31 03:04:17.128  7090  7090 W art     : b6ca8000-b6caa000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-31 03:04:17.128  7090  7090 W art     : b6caa000-b6cab000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-31 03:04:17.128  7090  7090 W art     : b6cab000-b6cd3000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-31 03:04:17.128  7090  7090 W art     : b6cd3000-b6cd5000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-31 03:04:17.128  7090  7090 W art     : b6cd5000-b6cd6000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-31 03:04:17.128  7090  7090 W art     : b6cd6000-b6cd9000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-31 03:04:17.128  7090  7090 W art     : b6cd9000-b6cda000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-31 03:04:17.128  7090  7090 W art     : b6cda000-b6cdb000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-31 03:04:17.128  7090  7090 W art     : b6cdb000-b6ce4000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-31 03:04:17.128  7090  7090 W art     : b6ce4000-b6ce5000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-31 03:04:17.128  7090  7090 W art     : b6ce5000-b6ce6000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-31 03:04:17.128  7090  7090 W art     : b6ce6000-b6d06000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-31 03:04:17.128  7090  7090 W art     : b6d06000-b6d07000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-31 03:04:17.128  7090  7090 W art     : b6d07000-b6d08000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-31 03:04:17.128  7090  7090 W art     : b6d08000-b6d7b000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-31 03:04:17.128  7090  7090 W art     : b6d7b000-b6d7f000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-31 03:04:17.128  7090  7090 W art     : b6d7f000-b6d82000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-31 03:04:17.128  7090  7090 W art     : b6d82000-b6d8c000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6d8c000-b6e14000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-31 03:04:17.128  7090  7090 W art     : b6e14000-b6e15000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6e15000-b6e19000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-31 03:04:17.128  7090  7090 W art     : b6e19000-b6e1a000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-31 03:04:17.128  7090  7090 W art     : b6e1a000-b6e1b000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6e1b000-b6e44000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-31 03:04:17.128  7090  7090 W art     : b6e44000-b6e45000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6e45000-b6e48000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-31 03:04:17.128  7090  7090 W art     : b6e48000-b6e49000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-31 03:04:17.128  7090  7090 W art     : b6e49000-b6f23000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 03:04:17.128  7090  7090 W art     : b6f23000-b6f2a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 03:04:17.128  7090  7090 W art     : b6f2a000-b6f32000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 03:04:17.128  7090  7090 W art     : b6f32000-b6f33000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6f33000-b6f34000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:17.128  7090  7090 W art     : b6f34000-b6f35000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-31 03:04:17.128  7090  7090 W art     : b6f35000-b6f36000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6f36000-b6f39000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6f39000-b6f5e000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-31 03:04:17.128  7090  7090 W art     : b6f5e000-b6f5f000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6f5f000-b6f66000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-31 03:04:17.128  7090  7090 W art     : b6f66000-b6f67000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-31 03:04:17.128  7090  7090 W art     : b6f67000-b6f6e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-31 03:04:17.128  7090  7090 W art     : b6f6e000-b6f6f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-31 03:04:17.128  7090  7090 W art     : b6f6f000-b6f70000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-31 03:04:17.128  7090  7090 W art     : b6f70000-b6f71000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6f71000-b6f89000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-31 03:04:17.128  7090  7090 W art     : b6f89000-b6f8a000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6f8a000-b6f8b000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-31 03:04:17.128  7090  7090 W art     : b6f8b000-b6f8c000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-31 03:04:17.128  7090  7090 W art     : b6f8c000-b6f9a000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-31 03:04:17.128  7090  7090 W art     : b6f9a000-b6f9b000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6f9b000-b6f9c000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-31 03:04:17.128  7090  7090 W art     : b6f9c000-b6f9d000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-31 03:04:17.128  7090  7090 W art     : b6f9d000-b6f9e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:17.128  7090  7090 W art     : b6f9e000-b6fa0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6fa0000-b6fa1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6fa1000-b6fa2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:17.128  7090  7090 W art     : b6fa2000-b6fa3000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-31 03:04:17.128  7090  7090 W art     : b6fa3000-b6fa4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:17.128  7090  7090 W art     : b6fa4000-b6fc4000 r--s 00000000 00:0b 8195       /dev/__properties__
08-31 03:04:17.128  7090  7090 W art     : b6fc4000-b6fc5000 r--p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6fc5000-b6fc6000 ---p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6fc6000-b6fc8000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-31 03:04:17.128  7090  7090 W art     : b6fc8000-b6fc9000 r-xp 00000000 00:00 0          [sigpage]
08-31 03:04:17.128  7090  7090 W art     : b6fc9000-b6fe4000 r-xp 00000000 b3:17 341        /system/bin/linker
08-31 03:04:17.128  7090  7090 W art     : b6fe4000-b6fe5000 r--p 0001a000 b3:17 341        /system/bin/linker
08-31 03:04:17.128  7090  7090 W art     : b6fe5000-b6fe7000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-31 03:04:17.128  7090  7090 W art     : b6fe7000-b6fe9000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : b6fe9000-b6fee000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-31 03:04:17.128  7090  7090 W art     : b6fee000-b6fef000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-31 03:04:17.128  7090  7090 W art     : b6fef000-b6ff0000 rw-p 00000000 00:00 0 
08-31 03:04:17.128  7090  7090 W art     : bea6e000-bea8f000 rw-p 00000000 00:00 0          [stack]
08-31 03:04:17.128  7090  7090 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-31 03:04:17.178  1642  1722 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
08-31 03:04:17.208  7090  7090 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 03:04:17.278  7090  7090 I Radio-JNI: register_android_hardware_Radio DONE
08-31 03:04:17.288  7090  7090 E AffinityControl: AffinityControl: registerfunction enter
08-31 03:04:17.308  7090  7090 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 03:04:17.338   756  1640 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-31 03:04:17.348   756  1640 D ActivityManager: mDVFSHelper.acquire()
08-31 03:04:17.358   756  1640 V WindowManager: addAppToken: AppWindowToken{827444a token=Token{51f85b5 ActivityRecord{7718dec u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-31 03:04:17.378   756   907 D SecWifiDisplayUtil: Metadata value : none
08-31 03:04:17.378   756   907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{88c12a2 V.E...... R.....ID 0,0-0,0}
08-31 03:04:17.388   756   907 D ISSUE_DEBUG: InputChannelName : 7092ef0 Starting com.test.thalitest
08-31 03:04:17.388  7105  7105 E Zygote  : v2
08-31 03:04:17.388  7105  7105 I libpersona: KNOX_SDCARD checking this for 10004
08-31 03:04:17.388  7105  7105 I libpersona: KNOX_SDCARD not a persona
08-31 03:04:17.398   756  1640 I ActivityManager: Start proc 7105:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-31 03:04:17.398   756  1640 D InputDispatcher: Focused application set to: xxxx
08-31 03:04:17.398   756  1640 D InputDispatcher: Focus left window: 3854
08-31 03:04:17.398   756  1321 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-31 03:04:17.398   756   865 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6385502 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-31 03:04:17.398  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-31 03:04:17.398  7105  7105 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 03:04:17.398  7105  7105 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:17.398   292   292 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
08-31 03:04:17.408  7105  7105 E Zygote  : accessInfo : 0
08-31 03:04:17.408  7105  7105 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-31 03:04:17.408  7090  7090 D AndroidRuntime: Shutting down VM
08-31 03:04:17.418   756   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
08-31 03:04:17.418   756   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 03:04:17.418   756   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-31 03:04:17.418   756   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-31 03:04:17.418   756   907 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-31 03:04:17.428  1642  1722 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 251ms lastUpdatedAfter : 173829ms
08-31 03:04:17.458   756   907 V WindowStateAnimator: Finishing drawing window Window{7092ef0 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-31 03:04:17.468   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeaf364
08-31 03:04:17.468  7105  7105 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 03:04:17.468  7105  7105 D ActivityThread: Added TimaKeyStore provider
08-31 03:04:17.468   756  1697 V WindowOrientationListener: setCurrentAppOrientation :-1
08-31 03:04:17.468   756  1697 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-31 03:04:17.478   756   865 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7092ef0 u0 d0 Starting com.test.thalitest}
08-31 03:04:17.478  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-31 03:04:17.488   756  1697 D ActivityManager:  Launching com.test.thalitest, updated priority
08-31 03:04:17.498   756   863 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-31 03:04:17.508  1688  1871 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-31 03:04:17.508  1688  1688 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-31 03:04:17.518   292   334 D libEGL  : eglTerminate EGLDisplay = 0xb677f64c
08-31 03:04:17.528   292   334 D libEGL  : eglTerminate EGLDisplay = 0xb677f64c
08-31 03:04:17.528   292   334 D libEGL  : eglTerminate EGLDisplay = 0xb677f64c
08-31 03:04:17.528   292   332 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
08-31 03:04:17.528   292  4936 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
08-31 03:04:17.528   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
08-31 03:04:17.548   292  4936 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-31 03:04:17.548   292   334 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-31 03:04:17.548   292   949 I SurfaceFlinger: id=20 Removed VSBConnecti (4/9)
08-31 03:04:17.558   292   332 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/9)
08-31 03:04:17.558  1688  1688 V ActivityThread: updateVisibility : ActivityRecord{59e35a3 token=android.os.BinderProxy@96f1f6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 03:04:17.558  1688  1688 D Launcher: onTrimMemory. Level: 20
08-31 03:04:17.558  2301  2318 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-31 03:04:17.558   756  1321 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-31 03:04:17.568   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
08-31 03:04:17.568   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
08-31 03:04:17.568  3854  3854 V ActivityThread: updateVisibility : ActivityRecord{4b77aba token=android.os.BinderProxy@f02ef44 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-31 03:04:17.568  7105  7105 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-31 03:04:17.578   756  3635 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 03:04:17.598  7105  7105 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-31 03:04:17.598  7105  7105 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-31 03:04:17.618  7105  7105 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-31 03:04:17.648  7105  7105 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-31 03:04:17.658  7105  7105 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 03:04:17.668  7105  7105 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3256-3259)
,08-31 03:04:17.668  7105  7105 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-31 03:04:17.678  7105  7105 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ab8306}
,08-31 03:04:17.678  7105  7105 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-31 03:04:17.678  7105  7105 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 03:04:17.688   756   771 I art     : Background partial concurrent mark sweep GC freed 51639(3MB) AllocSpace objects, 78(1560KB) LOS objects, 27% free, 42MB/58MB, paused 1.631ms total 152.660ms
,08-31 03:04:17.688  7105  7132 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-31 03:04:17.688  7105  7105 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 03:04:17.718  7105  7105 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 03:04:17.718  7105  7105 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 03:04:17.718  7105  7105 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 03:04:17.718  7105  7105 I Adreno-EGL: Local Branch: ss
08-31 03:04:17.718  7105  7105 I Adreno-EGL: Remote Branch: 
08-31 03:04:17.718  7105  7105 I Adreno-EGL: Local Patches: 
08-31 03:04:17.718  7105  7105 I Adreno-EGL: Reconstruct Branch: 
,08-31 03:04:17.718  7105  7105 D libEGL  : eglInitialize EGLDisplay = 0xbefa7dac
,08-31 03:04:17.748   756  2315 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-31 03:04:17.758   756  2315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-31 03:04:17.798  7105  7105 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 03:04:17.808  7105  7105 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 03:04:17.808  7105  7105 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-31 03:04:17.808  7105  7105 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-31 03:04:17.808  7105  7105 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 03:04:17.828  7105  7105 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-31 03:04:17.838  7105  7105 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 03:04:17.928  7105  7105 D SecWifiDisplayUtil: Metadata value : none
,08-31 03:04:17.928  7105  7105 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cfebba7 I.E...... R.....ID 0,0-0,0}
,08-31 03:04:17.928  7105  7162 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 03:04:17.938   756  1482 D ISSUE_DEBUG: InputChannelName : cc4ef4d com.test.thalitest/com.test.thalitest.MainActivity
,08-31 03:04:17.938   756  1640 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-31 03:04:17.938   756  1640 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-31 03:04:17.938   756   756 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 03:04:17.938   756   756 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-31 03:04:17.958  7105  7105 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7105
,08-31 03:04:17.968   756  1640 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7105 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:04:17.968   756  1330 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 03:04:17.968   756  1330 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 03:04:17.968   756  1330 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 03:04:17.968   756  1330 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-31 03:04:17.968   756  1330 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:04:17.978  7105  7105 D SecWifiDisplayUtil: Metadata value : none
,08-31 03:04:17.988  7105  7132 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-31 03:04:17.998   292   292 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,08-31 03:04:18.008   756  2016 D InputDispatcher: Focus entered window: 7105
,08-31 03:04:18.018   756   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
,08-31 03:04:18.018   756   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 03:04:18.018   756   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-31 03:04:18.018   756   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 03:04:18.018  7105  7162 D libEGL  : eglInitialize EGLDisplay = 0x9ca3f7c4
08-31 03:04:18.018  7105  7162 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 03:04:18.068  7105  7105 V ActivityThread: updateVisibility : ActivityRecord{d11323e token=android.os.BinderProxy@e8fc66 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 03:04:18.068  7105  7105 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-31 03:04:18.068  7105  7105 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-31 03:04:18.068   756  1697 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 03:04:18.088  7105  7105 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-31 03:04:18.098   756  1482 V WindowStateAnimator: Finishing drawing window Window{cc4ef4d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-31 03:04:18.108  7105  7105 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-31 03:04:18.108  7105  7105 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e8fc66 time:273703
,08-31 03:04:18.108   756   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 03:04:18.108   756   756 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 03:04:18.108   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeaf364
08-31 03:04:18.108   756   756 I KnoxTimeoutHandler: SD activityfalse
,08-31 03:04:18.118   756   907 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms (total +741ms)
,08-31 03:04:18.118   756   907 D ActivityManager: mDVFSHelper.release()
,08-31 03:04:18.118   756   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7718dec u0 com.test.thalitest/.MainActivity t168} time:273713
,08-31 03:04:18.118   756   907 D ViewRootImpl: #3 mView = null
,08-31 03:04:18.118   292   949 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
08-31 03:04:18.118   292  4936 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
08-31 03:04:18.128   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
,08-31 03:04:18.168  7105  7170 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 03:04:18.168  7105  7170 D libEGL  : eglInitialize EGLDisplay = 0x9a52c3ec
,08-31 03:04:18.208  7105  7105 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7105
,08-31 03:04:18.288   756  3663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 03:04:18.368  7105  7105 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 03:04:18.468  7105  7176 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1714955984
,08-31 03:04:18.478  7105  7176 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 03:04:18.478  7105  7176 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 03:04:18.478  7105  7176 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 03:04:18.478  7105  7176 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 03:04:18.478  7105  7176 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 03:04:18.478  7105  7176 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@491e84 added. We now have 1 listener(s)
,08-31 03:04:18.478  7105  7176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-31 03:04:18.478  7105  7176 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-31 03:04:18.478  7105  7176 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 03:04:18.478  7105  7176 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 03:04:18.488  7105  7176 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@393ab33 added. We now have 1 listener(s)
08-31 03:04:18.488  7105  7176 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 03:04:18.488  7105  7176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 03:04:18.488  7105  7176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 03:04:18.488  7105  7176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 03:04:18.488  7105  7176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 03:04:18.488  7105  7176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 03:04:18.488  7105  7176 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 03:04:18.498  7105  7176 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-31 03:04:18.498  7105  7176 D BluetoothAdapter: STATE_ON
,08-31 03:04:18.498  7105  7176 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:04:18.498  7105  7176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 03:04:18.498  7105  7176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 03:04:18.498  7105  7176 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 03:04:18.498  7105  7176 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 03:04:18.498  7105  7105 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 03:04:18.498  7105  7105 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 03:04:18.528  7105  7105 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 03:04:18.558   756  3636 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-31 03:04:18.938  1449  1449 D Recents : onTaskStackChanged
,08-31 03:04:18.958  1449  1449 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 03:04:19.428  7105  7177 W jxcore-log: Initializing JXcore engine
08-31 03:04:19.428  7105  7177 W jxcore-log: JXcore engine is ready
,08-31 03:04:19.478  2221  2221 E audit   : type=1400 msg=audit(1472605459.478:288): avc:  denied  { ioctl } for  pid=7177 comm="Thread-995" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 03:04:19.478  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-31 03:04:19.478  2221  2221 E audit   : type=1300 msg=audit(1472605459.478:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=99b783c8 items=0 ppid=350 ppcomm=main pid=7177 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-995" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 03:04:19.478  2221  2221 E audit   : type=1327 msg=audit(1472605459.478:288): proctitle="com.test.thalitest"
08-31 03:04:19.478  2221  2221 E audit   : type=1320 msg=audit(1472605459.478:288): 
08-31 03:04:19.478  2221  2221 E audit   : type=1400 msg=audit(1472605459.478:289): avc:  denied  { ioctl } for  pid=7177 comm="Thread-995" path="socket:[44751]" dev="sockfs" ino=44751 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-31 03:04:19.478  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:19.478  2221  2221 E audit   : type=1300 msg=audit(1472605459.478:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=1 a3=99b783c8 items=0 ppid=350 ppcomm=main pid=7177 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-995" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 03:04:19.478  2221  2221 E audit   : type=1327 msg=audit(1472605459.478:289): proctitle="com.test.thalitest"
08-31 03:04:19.478  2221  2221 E audit   : type=1320 msg=audit(1472605459.478:289): 
,08-31 03:04:19.488  7105  7177 W jxcore-log: Starting JXcore engine
,08-31 03:04:19.578  7105  7177 W jxcore-log: Platform android
08-31 03:04:19.578  7105  7177 W jxcore-log: 
08-31 03:04:19.578  7105  7177 W jxcore-log: Process ARCH arm
08-31 03:04:19.578  7105  7177 W jxcore-log: 
,08-31 03:04:19.768  7105  7177 I jxcore-log: JXcore Cordova bridge is ready!
08-31 03:04:19.768  7105  7177 I jxcore-log: 
08-31 03:04:19.768  7105  7177 W jxcore-log: JXcore engine is started
,08-31 03:04:19.778  7105  7176 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 03:04:19.788  7105  7105 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 03:04:20.418   756  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-31 03:04:22.678   756  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 03:04:22.678   756  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-31 03:04:22.678   756  1218 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-31 03:04:22.678   756  1218 D BatteryService: stay LED for fully charged
08-31 03:04:22.678   756   756 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 03:04:22.688   756   756 I MotionRecognitionService: Plugged
08-31 03:04:22.688   756   756 D MotionRecognitionService:   cableConnection= 1
,08-31 03:04:22.688   756   756 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-31 03:04:22.688   756   756 D MotionRecognitionService: skip setTransmitPower. 
,08-31 03:04:22.688  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 03:04:22.688  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-31 03:04:22.688  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 03:04:22.688  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 03:04:22.688  2216  2216 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 03:04:22.688  2216  2745 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 03:04:22.708  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 03:04:22.708  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 03:04:23.598   756  3635 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 03:04:26.168   756  3635 D SSRM:n  : SIOP:: AP = 340, PST = 313, CUR = 300, LCD = 0
,08-31 03:04:27.418   756   990 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 03:04:27.458   756   990 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 03:04:32.778   756  2306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 03:04:32.788   756  2306 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-31 03:04:32.788   756  2306 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-31 03:04:32.788   756   756 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 03:04:32.788   756  2306 D BatteryService: stay LED for fully charged
,08-31 03:04:32.798   756   756 I MotionRecognitionService: Plugged
,08-31 03:04:32.798   756   756 D MotionRecognitionService:   cableConnection= 1
08-31 03:04:32.798   756   756 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-31 03:04:32.798   756   756 D MotionRecognitionService: skip setTransmitPower. 
,08-31 03:04:32.798  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 03:04:32.798  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-31 03:04:32.798  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 03:04:32.808  2216  2216 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 03:04:32.808  2216  2745 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 03:04:32.818  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 03:04:32.818  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 03:04:32.818  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 03:04:33.708  7105  7177 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 03:04:33.708  7105  7177 I jxcore-log: 
,08-31 03:04:33.718  7105  7177 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 03:04:33.718  7105  7177 I jxcore-log: 
,08-31 03:04:33.718  7105  7177 D BluetoothAdapter: STATE_ON
,08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:04:33.718  7105  7177 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 03:04:33.728  7105  7177 D BluetoothAdapter: STATE_ON
,08-31 03:04:33.728  7105  7177 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 03:04:33.728  7105  7177 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-31 03:04:33.728  7105  7177 I jxcore-log: 
,08-31 03:04:33.728  7105  7177 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-31 03:04:33.728  7105  7177 I jxcore-log: 
,08-31 03:04:34.088  7105  7177 I jxcore-log: Running unit tests
08-31 03:04:34.088  7105  7177 I jxcore-log: 
08-31 03:04:34.088  7105  7177 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-31 03:04:34.088  7105  7177 I jxcore-log: Failed to execute UT.
08-31 03:04:34.088  7105  7177 I jxcore-log: 
,08-31 03:04:34.088  7105  7177 I jxcore-log: Unit Test app is loaded
08-31 03:04:34.088  7105  7177 I jxcore-log: 
,08-31 03:04:34.098  7105  7177 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 03:04:34.098  7105  7177 I jxcore-log: 
,08-31 03:04:34.098  7105  7105 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 03:04:34.108  7105  7177 I jxcore-log: My device name is: samsung-SM-G900F
08-31 03:04:34.108  7105  7177 I jxcore-log: 
,08-31 03:04:36.198   756  3635 D SSRM:n  : SIOP:: AP = 350, PST = 315, CUR = 300, LCD = 0
,08-31 03:04:36.618  7105  7177 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 03:04:36.618  7105  7177 I jxcore-log: 
,08-31 03:04:37.078  7105  7177 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 03:04:37.078  7105  7177 I jxcore-log: 
,08-31 03:04:37.098  7105  7177 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 03:04:37.098  7105  7177 I jxcore-log: 
,08-31 03:04:38.288   756  3663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 03:04:38.488  7105  7177 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 03:04:38.488  7105  7177 I jxcore-log: 
,08-31 03:04:38.728  7105  7177 I jxcore-log: ERROR runTests: 
08-31 03:04:38.728  7105  7177 I jxcore-log: 
,08-31 03:04:38.728  7105  7177 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:04:38.728  7105  7177 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 03:04:38.748  7105  7177 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _functionName: 'loadFile',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _lineNumber: '26',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _columnNumber: '11',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 03:04:38.748  7105  7177 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _functionName: '',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _lineNumber: '38',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _columnNumber: '7',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 03:04:38.748  7105  7177 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _functionName: '',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _lineNumber: '35',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _columnNumber: '3',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 03:04:38.748  7105  7177 I jxcore-log:   { _fileName: 'module.js',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _lineNumber: '621',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _columnNumber: '8',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 03:04:38.748  7105  7177 I jxcore-log:   { _fileName: 'module.js',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _lineNumber: '651',
08-31 03:04:38.748  7105  7177 I jxcore-log:     _columnNumber: '1',
08-31 03:04:38.748  7105  7177 I jxcore-log:    
08-31 03:04:38.748  7105  7177 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 03:04:38.748  7105  7177 I jxcore-log: 
,08-31 03:04:38.748  7105  7177 E jxcore-log: Error: 
08-31 03:04:38.748  7105  7177 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:04:38.748  7105  7177 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 03:04:38.748  7105  7177 E jxcore-log: 
,08-31 03:04:39.738  2221  2221 E audit   : type=1400 msg=audit(1472605479.738:290): avc:  denied  { execmod } for  pid=7194 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 03:04:39.748  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:39.748  2221  2221 E audit   : type=1300 msg=audit(1472605479.738:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f62000 a1=51000 a2=5 a3=4 items=0 ppid=3741 ppcomm=adbd pid=7194 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 03:04:39.748  2221  2221 E audit   : type=1327 msg=audit(1472605479.738:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-31 03:04:39.748  2221  2221 E audit   : type=1320 msg=audit(1472605479.738:290): 
,08-31 03:04:39.798  2221  2221 E audit   : type=1400 msg=audit(1472605479.798:291): avc:  denied  { execmod } for  pid=7194 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 03:04:39.798  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:39.798  2221  2221 E audit   : type=1300 msg=audit(1472605479.798:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f22000 a1=51000 a2=5 a3=4 items=0 ppid=3741 ppcomm=adbd pid=7194 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 03:04:39.798  2221  2221 E audit   : type=1327 msg=audit(1472605479.798:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-31 03:04:39.798  2221  2221 E audit   : type=1320 msg=audit(1472605479.798:291): 
,08-31 03:04:39.838  2221  2221 E audit   : type=1400 msg=audit(1472605479.838:292): avc:  denied  { execmod } for  pid=7194 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 03:04:39.838  2221  2221 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 03:04:39.838  7194  7194 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 03:04:39.838  2221  2221 E audit   : type=1300 msg=audit(1472605479.838:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f22000 a1=51000 a2=5 a3=4 items=0 ppid=3741 ppcomm=adbd pid=7194 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 03:04:39.838  2221  2221 E audit   : type=1327 msg=audit(1472605479.838:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
,08-31 03:04:39.838  2221  2221 E audit   : type=1320 msg=audit(1472605479.838:292): 
,08-31 03:04:39.848  7194  7194 D AndroidRuntime: CheckJNI is OFF
08-31 03:04:39.848  7194  7194 D AndroidRuntime: readGMSProperty: start
08-31 03:04:39.848  7194  7194 D AndroidRuntime: readGMSProperty: already setted!!
08-31 03:04:39.848  7194  7194 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 03:04:39.848  7194  7194 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 03:04:39.848  7194  7194 D AndroidRuntime: readGMSProperty: end
08-31 03:04:39.848  7194  7194 D AndroidRuntime: addProductProperty: start
,08-31 03:04:39.858  7194  7194 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 03:04:39.858  7194  7194 W art     : aed89000-b1caf000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-31 03:04:39.858  7194  7194 W art     : b1caf000-b3f1e000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-31 03:04:39.858  7194  7194 W art     : b3f1e000-b3f1f000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-31 03:04:39.858  7194  7194 W art     : b3f1f000-b3f20000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.858  7194  7194 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-31 03:04:39.858  7194  7194 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-31 03:04:39.858  7194  7194 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-31 03:04:39.858  7194  7194 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-31 03:04:39.858  7194  7194 W art     : b47ca000-b47f3000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 03:04:39.858  7194  7194 W art     : b47f3000-b47f6000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-31 03:04:39.858  7194  7194 W art     : b47f6000-b47f7000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-31 03:04:39.858  7194  7194 W art     : b47f7000-b47f8000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-31 03:04:39.858  7194  7194 W art     : b47f8000-b47f9000 r--p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b47f9000-b4819000 r--s 00000000 00:0b 8195       /dev/__properties__
,08-31 03:04:39.858  7194  7194 W art     : b4819000-b522a000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-31 03:04:39.858  7194  7194 W art     : b522a000-b522b000 ---p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b522b000-b5274000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-31 03:04:39.858  7194  7194 W art     : b5274000-b5275000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-31 03:04:39.858  7194  7194 W art     : b5275000-b527d000 rw-p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b527d000-b52b2000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-31 03:04:39.858  7194  7194 W art     : b52b2000-b52b3000 ---p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b52b3000-b52b4000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-31 03:04:39.858  7194  7194 W art     : b52b4000-b52b5000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-31 03:04:39.858  7194  7194 W art     : b52b5000-b530d000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-31 03:04:39.858  7194  7194 W art     : b530d000-b530e000 ---p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b530e000-b530f000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-31 03:04:39.858  7194  7194 W art     : b530f000-b5310000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
,08-31 03:04:39.858  7194  7194 W art     : b5311000-b5317000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
08-31 03:04:39.858  7194  7194 W art     : AD_v01009.so
08-31 03:04:39.858  7194  7194 W art     : b5317000-b5318000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 03:04:39.858  7194  7194 W art     : b5318000-b5319000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so,
08-31 03:04:39.858  7194  7194 W art     : b5319000-b531b000 rw-p 00000000 00:00 0 
08-31 03:04:39.858  7194  7194 W art     : b531c000-b5326000 r-xp 00000000 b3:17 1088 
08-31 03:04:39.858  7194  7194 W art     :       /system/lib/libcommon_time_client.so
08-31 03:04:39.858  7194  7194 W art     : b5326000-b5329000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 03:04:39.858  7194  7194 W art     : b5329000-b532a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 03:04:39.858  7194  7194 W art     : b532b000-b5342000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-31 03:04:39.868  7194  7194 W art     : b5342000-b5343000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5343000-b5344000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 03:04:39.868  7194  7194 W art     : b5344000-b5345000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 03:04:39.868  7194  7194 W art     : b5346000-b5350000 r-xp 00000000 b3:17 2671   
08-31 03:04:39.868  7194  7194 W art     :     /system/lib/libsec_km.so
,08-31 03:04:39.868  7194  7194 W art     : b5350000-b5351000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-31 03:04:39.868  7194  7194 W art     : b5351000-b5352000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-31 03:04:39.868  7194  7194 W art     : b5352000-b5356000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-31 03:04:39.868  7194  7194 W art     : b5356000-b5357000 r--p 00003000 b
08-31 03:04:39.868  7194  7194 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
08-31 03:04:39.868  7194  7194 W art     : b5357000-b5358000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 03:04:39.868  7194  7194 W art     : b5358000-b536e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-31 03:04:39.868  7194  7194 W art     : b536e000-b536f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-31 03:04:39.868  7194  7194 W art     : b536f000-b5370000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-31 03:04:39.868  7194  7194 W art     : b5370000-b537d000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-31 03:04:39.868  7194  7194 W art     : b537d000-b537e000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,08-31 03:04:39.868  7194  7194 W art     : b537e000-b537f000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-31 03:04:39.868  7194  7194 W art     : b537f000-b53df000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-31 03:04:39.868  7194  7194 W art     : b53df000-b53e2000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-31 03:04:39.868  7194  7194 W art     : b53e2000-b53e6000 rw-p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b53e6000-b5447000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-31 03:04:39.868  7194  7194 W art     : b5447000-b5448000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-31 03:04:39.868  7194  7194 W art     : b5448000-b5497000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-31 03:04:39.868  7194  7194 W art     : b5497000-b5499000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-31 03:04:39.868  7194  7194 W art     : b5499000-b549a000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-31 03:04:39.868  7194  7194 W art     : b549a000-b549b000 rw-p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b549b000-b54a2000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 03:04:39.868  7194  7194 W art     : b54a2000-b54a3000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 03:04:39.868  7194  7194 W art     : b54a3000-b54a4000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-31 03:04:39.868  7194  7194 W art     : avc_common.so
08-31 03:04:39.868  7194  7194 W art     : b54a5000-b54a8000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 03:04:39.868  7194  7194 W art     : b54a8000-b54a9000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 03:04:39.868  7194  7194 W art     : b54a9000-b54aa000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
,08-31 03:04:39.868  7194  7194 W art     : enc_common.so
08-31 03:04:39.868  7194  7194 W art     : b54ab000-b54af000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-31 03:04:39.868  7194  7194 W art     : b54af000-b54b0000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b54b0000-b54b1000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-31 03:04:39.868  7194  7194 W art     : b54b1000-b54b2000 rw-p 00005000 b3:17 2510       /syste
08-31 03:04:39.868  7194  7194 W art     : m/lib/libpowermanager.so
08-31 03:04:39.868  7194  7194 W art     : b54b3000-b54d0000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 03:04:39.868  7194  7194 W art     : b54d0000-b54d1000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 03:04:39.868  7194  7194 W art     : b54d1000-b54d2000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 03:04:39.868  7194  7194 W art     : b54d3000-b54d8000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
,08-31 03:04:39.868  7194  7194 W art     : b54d8000-b54d9000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 03:04:39.868  7194  7194 W art     : b54d9000-b54da000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 03:04:39.868  7194  7194 W art     : b54db000-b550c000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 03:04:39.868  7194  7194 W art     : b550c000-b550d000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b550d000-b5510000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 03:04:39.868  7194  7194 W art     : b5510000-b5511000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 03:04:39.868  7194  7194 W art     : b5512000-b554d000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-31 03:04:39.868  7194  7194 W art     : b554d000-b554e000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-31 03:04:39.868  7194  7194 W art     : b554e000-b554f000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
,08-31 03:04:39.868  7194  7194 W art     : b5550000-b5557000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-31 03:04:39.868  7194  7194 W art     : b5557000-b5558000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5558000-b5559000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-31 03:04:39.868  7194  7194 W art     : b5559000-b555a000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-31 03:04:39.868  7194  7194 W art     : b555a000-b555b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.868  7194  7194 W art     : b555b000-b5572000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-31 03:04:39.868  7194  7194 W art     : b5572000-b5573000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5573000-b5576000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-31 03:04:39.868  7194  7194 W art     : b5576000-b5577000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-31 03:04:39.868  7194  7194 W art     : b5577000-b5596000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
,08-31 03:04:39.868  7194  7194 W art     : b5596000-b5597000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-31 03:04:39.868  7194  7194 W art     : b5597000-b5598000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-31 03:04:39.868  7194  7194 W art     : b5598000-b55d6000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-31 03:04:39.868  7194  7194 W art     : b55d6000-b55d7000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b55d7000-b55d9000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-31 03:04:39.868  7194  7194 W art     : b55d9000-b55da000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-31 03:04:39.868  7194  7194 W art     : b55db000-b55e2000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 03:04:39.868  7194  7194 W art     : b55e2000-b55e3000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 03:04:39.868  7194  7194 W art     : b55e3000-b55e4000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
,08-31 03:04:39.868  7194  7194 W art     : b55e5000-b55e8000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 03:04:39.868  7194  7194 W art     : b55e8000-b55e9000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 03:04:39.868  7194  7194 W art     : b55e9000-b55ea000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 03:04:39.868  7194  7194 W art     : b55ea000-b55f0000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 03:04:39.868  7194  7194 W art     : b55f0000-b55f1000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b55f1000-b55f2000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 03:04:39.868  7194  7194 W art     : b55f2000-b55f3000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 03:04:39.868  7194  7194 W art     : b55f3000-b55fc000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-31 03:04:39.868  7194  7194 W art     : b55fc000-b55fd000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
,08-31 03:04:39.868  7194  7194 W art     : b55fd000-b55fe000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-31 03:04:39.868  7194  7194 W art     : b55fe000-b568f000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 03:04:39.868  7194  7194 W art     : b568f000-b5690000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5690000-b569b000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 03:04:39.868  7194  7194 W art     : b569b000-b569c000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 03:04:39.868  7194  7194 W art     : b569d000-b56af000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-31 03:04:39.868  7194  7194 W art     : b56af000-b56b0000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-31 03:04:39.868  7194  7194 W art     : b56b0000-b56b1000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-31 03:04:39.868  7194  7194 W art     : b56b2000-b56b7000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-31 03:04:39.868  7194  7194 W art     : b56b7000-b56b8000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-31 03:04:39.868  7194  7194 W art     : b56b8000-b56b9000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-31 03:04:39.868  7194  7194 W art     : b56ba000-b5727000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so,
08-31 03:04:39.868  7194  7194 W art     : b5727000-b5728000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5728000-b572a000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-31 03:04:39.868  7194  7194 W art     : b572a000-b572b000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-31 03:04:39.868  7194  7194 W art     : b572b000-b572c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.868  7194  7194 W art     : b572c000-b5733000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-31 03:04:39.868  7194  7194 W art     : b5733000-b5734000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 03:04:39.868  7194  7194 W art     : b5734000-b5735000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 03:04:39.868  7194  7194 W art     : b5736000-b57b6000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 03:04:39.868  7194  7194 W art     : b57b6000-b57b7000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b57b7000-b57b8000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 03:04:39.868  7194  7194 W art     : b57b8000-b57b9000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-31 03:04:39.868  7194  7194 W art     : b57b9000-b57d0000 rw-p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b57d0000-b5807000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 03:04:39.868  7194  7194 W art     : b5807000-b5808000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 03:04:39.868  7194  7194 W art     : b5808000-b5809000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 03:04:39.868  7194  7194 W art     : b5809000-b5825000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
,08-31 03:04:39.868  7194  7194 W art     : b5825000-b5826000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 03:04:39.868  7194  7194 W art     : b5826000-b5827000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 03:04:39.868  7194  7194 W art     : b5828000-b5889000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-31 03:04:39.868  7194  7194 W art     : b5889000-b588b000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-31 03:04:39.868  7194  7194 W art     : b588b000-b588c000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-31 03:04:39.868  7194  7194 W art     : b588d000-b58b2000 r-xp 00000000 b3:17 126        /system/lib/libpng.so,
08-31 03:04:39.868  7194  7194 W art     : b58b2000-b58b3000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-31 03:04:39.868  7194  7194 W art     : b58b3000-b58b4000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-31 03:04:39.868  7194  7194 W art     : b58b5000-b58bd000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 03:04:39.868  7194  7194 W art     : b58bd000-b58bf000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 03:04:39.868  7194  7194 W art     : b58bf000-b58c0000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-31 03:04:39.868  7194  7194 W art     : b58c1000-b58c4000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-31 03:04:39.868  7194  7194 W art     : b58c4000-b58c5000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-31 03:04:39.868  7194  7194 W art     : b58c5000-b58c6000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-31 03:04:39.868  7194  7194 W art     : b58c6000-b58ca000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-31 03:04:39.868  7194  7194 W art     : b58ca000-b58cb000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b58cb000-b58cc000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
,08-31 03:04:39.868  7194  7194 W art     : b58cc000-b58cd000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-31 03:04:39.868  7194  7194 W art     : b58cd000-b58dd000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-31 03:04:39.868  7194  7194 W art     : b58dd000-b58de000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-31 03:04:39.868  7194  7194 W art     : b58de000-b58df000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-31 03:04:39.868  7194  7194 W art     : b58df000-b5925000 rw-p 00000000 00:00 0 
,08-31 03:04:39.868  7194  7194 W art     : b5925000-b592e000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-31 03:04:39.868  7194  7194 W art     : b592e000-b592f000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-31 03:04:39.868  7194  7194 W art     : b592f000-b5930000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-31 03:04:39.868  7194  7194 W art     : b5931000-b5936000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-31 03:04:39.868  7194  7194 W art     : b5936000-b5937000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-31 03:04:39.868  7194  7194 W art     : b5937000-b5938000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
,08-31 03:04:39.868  7194  7194 W art     : b5938000-b593b000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 03:04:39.868  7194  7194 W art     : b593b000-b593c000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b593c000-b593d000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 03:04:39.868  7194  7194 W art     : b593d000-b593e000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 03:04:39.868  7194  7194 W art     : b593f000-b5957000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
08-31 03:04:39.868  7194  7194 W art     : ght_foundation.so,
08-31 03:04:39.868  7194  7194 W art     : b5957000-b5958000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5958000-b5959000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 03:04:39.868  7194  7194 W art     : b5959000-b595a000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 03:04:39.868  7194  7194 W art     : b595a000-b595b000 rw-p 00000000 00:
08-31 03:04:39.868  7194  7194 W art     : 00 0          [anon:linker_alloc_vector]
08-31 03:04:39.868  7194  7194 W art     : b595b000-b5af5000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so,
08-31 03:04:39.868  7194  7194 W art     : b5af5000-b5af6000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5af6000-b5b03000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-31 03:04:39.868  7194  7194 W art     : b5b03000-b5b04000 rw-p 001a7000 b3:17 604        /system/
08-31 03:04:39.868  7194  7194 W art     : lib/libstagefright.so
08-31 03:04:39.868  7194  7194 W art     : b5b04000-b5b08000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-31 03:04:39.868  7194  7194 W art     : b5b08000-b5b09000 ---p 00000000 00:00 0 ,
08-31 03:04:39.868  7194  7194 W art     : b5b09000-b5b0a000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-31 03:04:39.868  7194  7194 W art     : b5b0a000-b5b0b000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-31 03:04:39.868  7194  7194 W art     : ersona.so
08-31 03:04:39.868  7194  7194 W art     : b5b0b000-b5b1e000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-31 03:04:39.868  7194  7194 W art     : b5b1e000-b5b1f000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so,
08-31 03:04:39.868  7194  7194 W art     : b5b1f000-b5b20000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-31 03:04:39.868  7194  7194 W art     : b5b21000-b5b6c000 r
08-31 03:04:39.868  7194  7194 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-31 03:04:39.868  7194  7194 W art     : b5b6c000-b5b6d000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
,08-31 03:04:39.868  7194  7194 W art     : b5b6d000-b5b6e000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-31 03:04:39.868  7194  7194 W art     : b5b6e000-b5b70000 rw-p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5b71000-b5b82000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 03:04:39.868  7194  7194 W art     : b5b82000-b5b83000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5b83000-b5b84000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 03:04:39.868  7194  7194 W art     : b5b84000-b5b85000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-31 03:04:39.868  7194  7194 W art     : b5b85000-b5b86000 r--p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5b86000-b5b90000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
,08-31 03:04:39.868  7194  7194 W art     : b5b90000-b5b92000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-31 03:04:39.868  7194  7194 W art     : b5b92000-b5b93000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-31 03:04:39.868  7194  7194 W art     : b5b93000-b5bac000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-31 03:04:39.868  7194  7194 W art     : b5bac000-b5bad000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-31 03:04:39.868  7194  7194 W art     : b5bad000-b5bb0000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-31 03:04:39.868  7194  7194 W art     : b5bb0000-b5bb4000 rw-p 00000000 00:00 0 
,08-31 03:04:39.868  7194  7194 W art     : b5bb4000-b5c28000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-31 03:04:39.868  7194  7194 W art     : b5c28000-b5c29000 ---p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5c29000-b5c2c000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-31 03:04:39.868  7194  7194 W art     : b5c2c000-b5c2d000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-31 03:04:39.868  7194  7194 W art     : b5c2d000-b5c2e000 r--p 00000000 00:00 0 
08-31 03:04:39.868  7194  7194 W art     : b5c2e000-b5c31000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so,
08-31 03:04:39.868  7194  7194 W art     : b5c31000-b5c32000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-31 03:04:39.868  7194  7194 W art     : b5c32000-b5c33000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-31 03:04:39.868  7194  7194 W art     : b5c33000-b5c34000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.868  7194  7194 W art     : b5c34000-b5c39000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 03:04:39.868  7194  7194 W art     : b5c39000-b5c3a000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
,08-31 03:04:39.868  7194  7194 W art     : b5c3a000-b5c3b000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 03:04:39.868  7194  7194 W art     : b5c3b000-b5c3c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.868  7194  7194 W art     : b5c3c000-b5c3f000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 03:04:39.868  7194  7194 W art     : b5c3f000-b5c40000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 03:04:39.878  7194  7194 W art     : b5c40000-b5c41000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
,08-31 03:04:39.878  7194  7194 W art     : b5c41000-b5c42000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:39.878  7194  7194 W art     : b5c42000-b5c46000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-31 03:04:39.878  7194  7194 W art     : b5c46000-b5c47000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-31 03:04:39.878  7194  7194 W art     : b5c47000-b5c48000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-31 03:04:39.878  7194  7194 W art     : b5c48000-b5c49000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b5c49000-b5c4d000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 03:04:39.878  7194  7194 W art     : b5c4d000-b5c4e000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 03:04:39.878  7194  7194 W art     : b5c4e000-b5c4f000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
,08-31 03:04:39.878  7194  7194 W art     : b5c4f000-b5c50000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b5c50000-b5c5e000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-31 03:04:39.878  7194  7194 W art     : b5c5e000-b5c5f000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b5c5f000-b5c60000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-31 03:04:39.878  7194  7194 W art     : b5c60000-b5c61000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-31 03:04:39.878  7194  7194 W art     : b5c61000-b5c6b000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
,08-31 03:04:39.878  7194  7194 W art     : b5c6b000-b5c6e000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 03:04:39.878  7194  7194 W art     : b5c6e000-b5c6f000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 03:04:39.878  7194  7194 W art     : b5c6f000-b5c70000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b5c70000-b5c7a000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-31 03:04:39.878  7194  7194 W art     : b5c7a000-b5c7d000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
,08-31 03:04:39.878  7194  7194 W art     : b5c7d000-b5c7e000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-31 03:04:39.878  7194  7194 W art     : b5c7e000-b5c82000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-31 03:04:39.878  7194  7194 W art     : b5c82000-b5c83000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-31 03:04:39.878  7194  7194 W art     : b5c83000-b5c84000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
,08-31 03:04:39.878  7194  7194 W art     : b5c84000-b5c85000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b5c85000-b5c92000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-31 03:04:39.878  7194  7194 W art     : b5c92000-b5c94000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-31 03:04:39.878  7194  7194 W art     : b5c94000-b5c95000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
,08-31 03:04:39.878  7194  7194 W art     : b5c95000-b60a7000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
,08-31 03:04:39.878  7194  7194 W art     : b60a7000-b60a8000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b60a8000-b60b1000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-31 03:04:39.878  7194  7194 W art     : b60b1000-b60b5000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so,
08-31 03:04:39.878  7194  7194 W art     : b60b5000-b60b6000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b60b6000-b60bd000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-31 03:04:39.878  7194  7194 W art     : b60bd000-b60be000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
,08-31 03:04:39.878  7194  7194 W art     : b60be000-b60bf000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-31 03:04:39.878  7194  7194 W art     : b60bf000-b60c0000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b60c0000-b60db000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-31 03:04:39.878  7194  7194 W art     : b60db000-b60dc000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
,08-31 03:04:39.878  7194  7194 W art     : b60dc000-b60dd000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-31 03:04:39.878  7194  7194 W art     : b60dd000-b60de000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b60de000-b612a000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 03:04:39.878  7194  7194 W art     : b612a000-b612b000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b612b000-b612c000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so,
08-31 03:04:39.878  7194  7194 W art     : b612c000-b612d000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 03:04:39.878  7194  7194 W art     : b612d000-b612e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b612e000-b6132000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-31 03:04:39.878  7194  7194 W art     : b6132000-b6133000 ---p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6133000-b6134000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-31 03:04:39.878  7194  7194 W art     : b6134000-b6135000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-31 03:04:39.878  7194  7194 W art     : b6135000-b616d000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-31 03:04:39.878  7194  7194 W art     : b616d000-b616e000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
,08-31 03:04:39.878  7194  7194 W art     : b616e000-b616f000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-31 03:04:39.878  7194  7194 W art     : b616f000-b6170000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b6170000-b620f000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-31 03:04:39.878  7194  7194 W art     : b620f000-b622d000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
,08-31 03:04:39.878  7194  7194 W art     : b622d000-b622e000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-31 03:04:39.878  7194  7194 W art     : b622e000-b63a1000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-31 03:04:39.878  7194  7194 W art     : b63a1000-b63ac000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-31 03:04:39.878  7194  7194 W art     : b63ac000-b63ad000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-31 03:04:39.878  7194  7194 W art     : b63ad000-b64c4000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so,
08-31 03:04:39.878  7194  7194 W art     : b64c4000-b64cf000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-31 03:04:39.878  7194  7194 W art     : b64cf000-b64d0000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-31 03:04:39.878  7194  7194 W art     : b64d0000-b64d4000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b64d4000-b64f8000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
,08-31 03:04:39.878  7194  7194 W art     : b64f8000-b64fa000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-31 03:04:39.878  7194  7194 W art     : b64fa000-b64fb000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-31 03:04:39.878  7194  7194 W art     : b64fb000-b65a1000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-31 03:04:39.878  7194  7194 W art     : b65a1000-b65ae000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
,08-31 03:04:39.878  7194  7194 W art     : b65ae000-b65af000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-31 03:04:39.878  7194  7194 W art     : b65af000-b65b0000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b65b0000-b6603000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-31 03:04:39.878  7194  7194 W art     : b6603000-b6604000 ---p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6604000-b6605000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-31 03:04:39.878  7194  7194 W art     : b6605000-b6606000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-31 03:04:39.878  7194  7194 W art     : b6606000-b660b000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b660b000-b661d000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
,08-31 03:04:39.878  7194  7194 W art     : b661d000-b661e000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b661e000-b661f000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-31 03:04:39.878  7194  7194 W art     : b661f000-b6620000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-31 03:04:39.878  7194  7194 W art     : b6620000-b6627000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-31 03:04:39.878  7194  7194 W art     : b6627000-b6628000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 03:04:39.878  7194  7194 W art     : b6628000-b6629000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 03:04:39.878  7194  7194 W art     : b6629000-b662a000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b662a000-b662d000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
,08-31 03:04:39.878  7194  7194 W art     : b662d000-b662e000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-31 03:04:39.878  7194  7194 W art     : b662e000-b662f000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-31 03:04:39.878  7194  7194 W art     : b662f000-b6633000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-31 03:04:39.878  7194  7194 W art     : b6633000-b6634000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
,08-31 03:04:39.878  7194  7194 W art     : b6634000-b6635000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-31 03:04:39.878  7194  7194 W art     : b6635000-b6643000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-31 03:04:39.878  7194  7194 W art     : b6643000-b6644000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6644000-b6645000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
,08-31 03:04:39.878  7194  7194 W art     : b6645000-b6646000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-31 03:04:39.878  7194  7194 W art     : b6646000-b664f000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 03:04:39.878  7194  7194 W art     : b664f000-b6650000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 03:04:39.878  7194  7194 W art     : b6650000-b6651000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
,08-31 03:04:39.878  7194  7194 W art     : b6651000-b66b7000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-31 03:04:39.878  7194  7194 W art     : b66b7000-b66b8000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b66b8000-b66ba000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-31 03:04:39.878  7194  7194 W art     : b66ba000-b66c3000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so,
08-31 03:04:39.878  7194  7194 W art     : b66c3000-b66c6000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b66c6000-b675d000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-31 03:04:39.878  7194  7194 W art     : b675d000-b675f000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-31 03:04:39.878  7194  7194 W art     : b675f000-b6760000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so,
08-31 03:04:39.878  7194  7194 W art     : b6760000-b6761000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6761000-b6a7f000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-31 03:04:39.878  7194  7194 W art     : b6a7f000-b6a80000 ---p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6a80000-b6a9b000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-31 03:04:39.878  7194  7194 W art     : b6a9b000-b6a9f000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-31 03:04:39.878  7194  7194 W art     : b6a9f000-b6aa4000 rw-p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6aa4000-b6aac000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 03:04:39.878  7194  7194 W art     : b6aac000-b6aad000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 03:04:39.878  7194  7194 W art     : b6aad000-b6aae000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 03:04:39.878  7194  7194 W art     : b6aae000-b6adc000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
,08-31 03:04:39.878  7194  7194 W art     : b6adc000-b6add000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6add000-b6ae4000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-31 03:04:39.878  7194  7194 W art     : b6ae4000-b6ae5000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
,08-31 03:04:39.878  7194  7194 W art     : b6ae5000-b6b2b000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-31 03:04:39.878  7194  7194 W art     : b6b2b000-b6b2c000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6b2c000-b6b2f000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-31 03:04:39.878  7194  7194 W art     : b6b2f000-b6b30000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
,08-31 03:04:39.878  7194  7194 W art     : b6b30000-b6b4b000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-31 03:04:39.878  7194  7194 W art     : b6b4b000-b6b4f000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-31 03:04:39.878  7194  7194 W art     : b6b4f000-b6b50000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
,08-31 03:04:39.878  7194  7194 W art     : b6b50000-b6b9d000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-31 03:04:39.878  7194  7194 W art     : b6b9d000-b6b9e000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6b9e000-b6baa000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
,08-31 03:04:39.878  7194  7194 W art     : b6baa000-b6bab000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-31 03:04:39.878  7194  7194 W art     : b6bab000-b6bb8000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-31 03:04:39.878  7194  7194 W art     : b6bb8000-b6bb9000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6bb9000-b6bba000 r--p 0000d000 b3:17 1126       /system/lib/libui.so,
08-31 03:04:39.878  7194  7194 W art     : b6bba000-b6bbb000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-31 03:04:39.878  7194  7194 W art     : b6bbb000-b6bc3000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-31 03:04:39.878  7194  7194 W art     : b6bc3000-b6bc4000 ---p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6bc4000-b6bc5000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-31 03:04:39.878  7194  7194 W art     : b6bc5000-b6bc6000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-31 03:04:39.878  7194  7194 W art     : b6bc6000-b6bcd000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so,
08-31 03:04:39.878  7194  7194 W art     : b6bcd000-b6bce000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-31 03:04:39.878  7194  7194 W art     : b6bce000-b6bcf000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-31 03:04:39.878  7194  7194 W art     : b6bcf000-b6be3000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
,08-31 03:04:39.878  7194  7194 W art     : b6be3000-b6be5000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-31 03:04:39.878  7194  7194 W art     : b6be5000-b6be6000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-31 03:04:39.878  7194  7194 W art     : b6be6000-b6c0e000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-31 03:04:39.878  7194  7194 W art     : b6c0e000-b6c10000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
,08-31 03:04:39.878  7194  7194 W art     : b6c10000-b6c11000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-31 03:04:39.878  7194  7194 W art     : b6c11000-b6c14000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-31 03:04:39.878  7194  7194 W art     : b6c14000-b6c15000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so,
08-31 03:04:39.878  7194  7194 W art     : b6c15000-b6c16000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-31 03:04:39.878  7194  7194 W art     : b6c16000-b6c1f000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-31 03:04:39.878  7194  7194 W art     : b6c1f000-b6c20000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
,08-31 03:04:39.878  7194  7194 W art     : b6c20000-b6c21000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-31 03:04:39.878  7194  7194 W art     : b6c21000-b6c41000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-31 03:04:39.878  7194  7194 W art     : b6c41000-b6c42000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-31 03:04:39.878  7194  7194 W art     : b6c42000-b6c43000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
,08-31 03:04:39.878  7194  7194 W art     : b6c43000-b6cb6000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-31 03:04:39.878  7194  7194 W art     : b6cb6000-b6cba000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-31 03:04:39.878  7194  7194 W art     : b6cba000-b6cbd000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-31 03:04:39.878  7194  7194 W art     : b6cbd000-b6cc7000 rw-p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6cc7000-b6d4f000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-31 03:04:39.878  7194  7194 W art     : b6d4f000-b6d50000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6d50000-b6d54000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
,08-31 03:04:39.878  7194  7194 W art     : b6d54000-b6d55000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-31 03:04:39.878  7194  7194 W art     : b6d55000-b6d56000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6d56000-b6d7f000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-31 03:04:39.878  7194  7194 W art     : b6d7f000-b6d80000 ---p 00000000 00:00 0 ,
08-31 03:04:39.878  7194  7194 W art     : b6d80000-b6d83000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-31 03:04:39.878  7194  7194 W art     : b6d83000-b6d84000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-31 03:04:39.878  7194  7194 W art     : b6d84000-b6e5e000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
,08-31 03:04:39.878  7194  7194 W art     : b6e5e000-b6e65000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 03:04:39.878  7194  7194 W art     : b6e65000-b6e6d000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 03:04:39.878  7194  7194 W art     : b6e6d000-b6e6e000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6e6e000-b6e6f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-31 03:04:39.878  7194  7194 W art     : b6e6f000-b6e70000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-31 03:04:39.878  7194  7194 W art     : b6e70000-b6e71000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b6e71000-b6e74000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b6e74000-b6e99000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
,08-31 03:04:39.878  7194  7194 W art     : b6e99000-b6e9a000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6e9a000-b6ea1000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-31 03:04:39.878  7194  7194 W art     : b6ea1000-b6ea2000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-31 03:04:39.878  7194  7194 W art     : b6ea2000-b6ea9000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
,08-31 03:04:39.878  7194  7194 W art     : b6ea9000-b6eaa000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-31 03:04:39.878  7194  7194 W art     : b6eaa000-b6eab000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-31 03:04:39.878  7194  7194 W art     : b6eab000-b6eac000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b6eac000-b6ec4000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
,08-31 03:04:39.878  7194  7194 W art     : b6ec4000-b6ec5000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6ec5000-b6ec6000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-31 03:04:39.878  7194  7194 W art     : b6ec6000-b6ec7000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-31 03:04:39.878  7194  7194 W art     : b6ec7000-b6ed5000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
,08-31 03:04:39.878  7194  7194 W art     : b6ed5000-b6ed6000 ---p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6ed6000-b6ed7000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-31 03:04:39.878  7194  7194 W art     : b6ed7000-b6ed8000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-31 03:04:39.878  7194  7194 W art     : b6ed8000-b6ed9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:39.878  7194  7194 W art     : b6ed9000-b6edb000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-31 03:04:39.878  7194  7194 W art     : b6edb000-b6edc000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b6edc000-b6edd000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 03:04:39.878  7194  7194 W art     : b6edd000-b6ede000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
,08-31 03:04:39.878  7194  7194 W art     : b6ede000-b6edf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 03:04:39.878  7194  7194 W art     : b6edf000-b6eff000 r--s 00000000 00:0b 8195       /dev/__properties__
08-31 03:04:39.878  7194  7194 W art     : b6eff000-b6f00000 r--p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6f00000-b6f01000 ---p 00000000 00:00 0 
,08-31 03:04:39.878  7194  7194 W art     : b6f01000-b6f03000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-31 03:04:39.878  7194  7194 W art     : b6f03000-b6f04000 r-xp 00000000 00:00 0          [sigpage]
08-31 03:04:39.878  7194  7194 W art     : b6f04000-b6f1f000 r-xp 00000000 b3:17 341        /system/bin/linker
08-31 03:04:39.878  7194  7194 W art     : b6f1f000-b6f20000 r--p 0001a000 b3:17 341        /system/bin/linker
,08-31 03:04:39.878  7194  7194 W art     : b6f20000-b6f22000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-31 03:04:39.878  7194  7194 W art     : b6f22000-b6f24000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : b6f24000-b6f29000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-31 03:04:39.878  7194  7194 W art     : b6f29000-b6f2a000 r--p 00004000 b3:17 978        /system/bin/app_process32
,08-31 03:04:39.878  7194  7194 W art     : b6f2a000-b6f2b000 rw-p 00000000 00:00 0 
08-31 03:04:39.878  7194  7194 W art     : bee2f000-bee50000 rw-p 00000000 00:00 0          [stack]
08-31 03:04:39.878  7194  7194 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-31 03:04:39.948  7194  7194 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 03:04:39.988  7194  7194 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 03:04:39.998  7194  7194 E AffinityControl: AffinityControl: registerfunction enter
,08-31 03:04:40.008  7194  7194 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 03:04:40.028   756   776 D PackageManager: START PACKAGE DELETE: observer{229947239}
08-31 03:04:40.028   756   776 D PackageManager: pkg{<packageName>}
08-31 03:04:40.028   756   776 D PackageManager: user{0}
08-31 03:04:40.028   756   776 D PackageManager: caller{2000}
08-31 03:04:40.028   756   776 D PackageManager: flags{2}
,08-31 03:04:40.028   756   776 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-31 03:04:40.028   756   776 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-31 03:04:40.028   756   776 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-31 03:04:40.028   756   776 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 03:04:40.028   756   776 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 03:04:40.028   756   990 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 03:04:40.028   756   990 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 03:04:40.028   756   990 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 03:04:40.028   756   990 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 03:04:40.028   756   990 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 03:04:40.038   756   990 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 03:04:40.038   756   990 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-31 03:04:40.038   756   990 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-31 03:04:40.038   756   863 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-31 03:04:40.038   756   863 I ActivityManager: Killing 7105:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
08-31 03:04:40.038   756   990 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-31 03:04:40.038   756   990 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-31 03:04:40.048   756   863 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-31 03:04:40.048   756   863 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 03:04:40.048   756   863 D ActivityManager: mDVFSHelper.acquire()
,08-31 03:04:40.068   756   990 D AASAinstall: there is not AASApackages.xml file
,08-31 03:04:40.118   756  2014 D GraphicsStats: Buffer count: 4
,08-31 03:04:40.118   756  1318 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@bc477b2)
,08-31 03:04:40.118   756  1330 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:04:40.118   756  1330 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:04:40.118   756  1697 I WindowState: WIN DEATH: Window{cc4ef4d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 03:04:40.118   756  1330 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 03:04:40.118   292   334 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
,08-31 03:04:40.128   292  4936 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
08-31 03:04:40.128   292  4936 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
,08-31 03:04:40.128   756  1697 D InputDispatcher: Focus left window: 7105
,08-31 03:04:40.128   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
,08-31 03:04:40.258   303  1192 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-31 03:04:40.258   303  1192 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-31 03:04:40.258   303  1192 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-31 03:04:40.428   756   990 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-31 03:04:40.528   756   990 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 03:04:40.528   756   863 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 03:04:40.528   756   907 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-31 03:04:40.538   756   863 E ActivityManager: Failure starting process com.test.thalitest
08-31 03:04:40.538   756   863 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5275)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5192)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5030)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4999)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4960)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7377)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9144)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8767)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8922)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2599)
08-31 03:04:40.538   756   863 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:04:40.538   756   863 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-31 03:04:40.538   756   863 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:04:40.538   756   863 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 03:04:40.538   326   326 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-31 03:04:40.538   756   907 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,08-31 03:04:40.538   756   907 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-31 03:04:40.538   756   907 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-31 03:04:40.538   756   907 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4351)
,08-31 03:04:40.538   756   907 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13486)
08-31 03:04:40.538   756   907 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:04:40.538   756   907 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-31 03:04:40.538   756   907 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:04:40.538   756   907 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 03:04:40.538   756   907 D SecWifiDisplayUtil: Metadata value : none
08-31 03:04:40.538   756   907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ffe5cfe V.E...... R.....ID 0,0-0,0}
,08-31 03:04:40.538   756   907 D ISSUE_DEBUG: InputChannelName : bdd06ac Starting com.test.thalitest
,08-31 03:04:40.548   756   863 I ActivityManager:   Force finishing activity ActivityRecord{7718dec u0 com.test.thalitest/.MainActivity t168}
,08-31 03:04:40.548   756   990 I art     : Starting a blocking GC Explicit
,08-31 03:04:40.568   292   292 I SurfaceFlinger: id=23 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-31 03:04:40.588  1688  1688 D Launcher: onRestart, Launcher: 37238658
,08-31 03:04:40.678   756   990 I art     : Explicit concurrent mark sweep GC freed 86366(4MB) AllocSpace objects, 19(380KB) LOS objects, 27% free, 42MB/58MB, paused 1.491ms total 129.292ms
,08-31 03:04:40.708   756   990 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 03:04:40.708   756   990 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-31 03:04:40.708   756   990 D AASAinstall: there is not AASApackages.xml file
,08-31 03:04:40.708   756   990 D PackageManager: result of delete: 1{229947239}
,08-31 03:04:40.708  7194  7194 I art     : System.exit called, status: 0
08-31 03:04:40.708  7194  7194 I AndroidRuntime: VM exiting with result code 0.
,08-31 03:04:40.708   756   990 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 03:04:40.708   756   990 D PackageManager: userId{-1}
08-31 03:04:40.708   756   990 D PackageManager: andCode{true}
,08-31 03:04:40.878   756   863 I WindowManager: Screenshot max retries 4 of Token{e7d3570 ActivityRecord{1db8bb3 u0 com.samsung.android.MtpApplication/.USBConnection t167}} appWin=Window{137f421 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,08-31 03:04:40.888   756   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
,08-31 03:04:40.888   756   777 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-31 03:04:40.888   756   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 03:04:40.888   756   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-31 03:04:40.888   756   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 03:04:40.888  1688  1688 D Launcher: onStart, Launcher: 37238658
08-31 03:04:40.888   756   777 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 03:04:40.888   756   756 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 03:04:40.888  1688  1688 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-31 03:04:40.888   756   756 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-31 03:04:40.888   756   756 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-31 03:04:40.888  1688  1688 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-31 03:04:40.888  1688  1688 D Launcher.HomeView: onStart
,08-31 03:04:40.888   292   292 I SurfaceFlinger: id=24 createSurf (1080x1920),1 flag=404, uhalitest
,08-31 03:04:40.898   756   863 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-31 03:04:40.898  1688  1688 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,08-31 03:04:40.898  1688  1688 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,08-31 03:04:40.898  2301  2319 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,08-31 03:04:40.898   756   907 D ViewRootImpl: #3 mView = null
,08-31 03:04:40.898  1688  1688 V ActivityThread: updateVisibility : ActivityRecord{59e35a3 token=android.os.BinderProxy@96f1f6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-31 03:04:40.898   292   334 I SurfaceFlinger: id=24 Removed uhalitest (7/9)
,08-31 03:04:40.898   292   332 I SurfaceFlinger: id=24 Removed uhalitest (-2/9)
08-31 03:04:40.908   756   865 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{137f421 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-31 03:04:40.908   756   863 D InputDispatcher: Focus entered window: 3854
08-31 03:04:40.908   756   863 D InputDispatcher: Focused application released
08-31 03:04:40.908  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-31 03:04:40.908   756   907 W WindowManager: Failed looking up window
08-31 03:04:40.908   756   907 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@a172c5f does not exist
08-31 03:04:40.908   756   907 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14806)
08-31 03:04:40.908   756   907 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14797)
08-31 03:04:40.908   756   907 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4614)
08-31 03:04:40.908   756   907 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
08-31 03:04:40.908   756   907 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3748)
08-31 03:04:40.908   756   907 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6887)
08-31 03:04:40.908   756   907 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4232)
08-31 03:04:40.908   756   907 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:04:40.908   756   907 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-31 03:04:40.908   756   907 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:04:40.908   756   907 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 03:04:40.908   292   292 I SurfaceFlinger: id=25 createSurf (1080x1920),1 flag=4, Mauncher
,08-31 03:04:40.918   756  1218 V WindowOrientationListener: setCurrentAppOrientation :1
,08-31 03:04:40.918   756  1218 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-31 03:04:40.918   756   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:756 uid:1000
08-31 03:04:40.918   756   907 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 03:04:40.918   756   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:756 uid:1000
08-31 03:04:40.918   756   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 03:04:40.918   756   776 V WindowStateAnimator: Finishing drawing window Window{137f421 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 03:04:40.928   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeaf364
,08-31 03:04:40.938   292   292 I SurfaceFlinger: id=26 createSurf (1194x288),1 flag=4, VSBConnecti
,08-31 03:04:40.948   756  1296 I EventHub: Removing device '/dev/input/event4' due to inotify event
08-31 03:04:40.958   756   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 03:04:40.968   756   756 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 03:04:40.968   756   756 I KnoxTimeoutHandler: SD activityfalse
,08-31 03:04:40.968   756   907 D ActivityManager: mDVFSHelper.release()
,08-31 03:04:40.968   756   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1db8bb3 u0 com.samsung.android.MtpApplication/.USBConnection t167} time:296565
,08-31 03:04:40.988   756  1296 I EventHub: Removing device '/dev/input/event5' due to inotify event
,08-31 03:04:40.998   756  1703 V WindowStateAnimator: Finishing drawing window Window{b8d1207 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-31 03:04:40.998   756   990 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-31 03:04:41.008  3854  3854 V ActivityThread: updateVisibility : ActivityRecord{4b77aba token=android.os.BinderProxy@f02ef44 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-31 03:04:41.008  3854  3854 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f02ef44 time:296602
,08-31 03:04:41.008   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeaf364
,08-31 03:04:41.018  6089  7219 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2e0a070 in tid 7219 (IntentService[D)
,08-31 03:04:41.018  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.028  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.028   756  1296 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-31 03:04:41.078   350   350 I Zygote  : Process 6089 exited due to signal (7)
,08-31 03:04:41.078   756  1296 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-31 03:04:41.098  1449  1459 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e119f41 in tid 1459 (HeapTaskDaemon)
,08-31 03:04:41.098  1449  1459 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 03:04:41.098   756  1703 V WindowStateAnimator: Finishing drawing window Window{6385502 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-31 03:04:41.098  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.108   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeeaf364
,08-31 03:04:41.118   756   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 03:04:41.118   756   756 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 03:04:41.118   756   863 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 03:04:41.118   756   863 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 03:04:41.118   756   863 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 03:04:41.118   756   756 I KnoxTimeoutHandler: SD activityfalse
,08-31 03:04:41.118   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.128  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-31 03:04:41.128  1382  1382 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-31 03:04:41.128   756   756 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.128   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756  1296 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756   756 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-31 03:04:41.138   756  3635 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x92e62eb8 in tid 3635 (SSRM Handler Th)
,08-31 03:04:41.138   756  3635 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 03:04:41.138  1819  1819 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2dd5774 in tid 1819 (.service:remote)
08-31 03:04:41.138  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
08-31 03:04:41.138  1819  1819 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 03:04:41.138  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.188   350   350 I Zygote  : Process 1819 exited due to signal (7)
,08-31 03:04:41.198   350   350 I Zygote  : Process 1449 exited due to signal (7)
,08-31 03:04:41.208   324   324 E installd: eof
08-31 03:04:41.208   324   324 E installd: failed to read size
08-31 03:04:41.208   324   324 I installd: closing connection
08-31 03:04:41.208   291   291 I ServiceManager: service 'edmnativehelper' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sec_analytics' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'telecom' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'mount' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'lock_settings' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'deviceidle' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'device_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'harmony_eas_service' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sdp' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sdp_log' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'dlp' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'log_manager_service' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'user' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'procstats' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'meminfo' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'gfxinfo' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'dbinfo' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'cpuinfo' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'permission' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'processinfo' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sensorservice' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'mdm.remotedesktop' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'battery' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'usagestats' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'webviewupdate' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'scheduling_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'telephony.registry' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'persona' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'display' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'persona_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'context_aware' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'scontext' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'barbeam' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'multiwindow_facade' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'window' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'input' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'bluetooth_manager' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'rcp' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'input_method' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'accessibility' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'knox_ccm_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'enterprise_license_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'application_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'wifi_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'phone_restriction_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'remoteinjection' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'knox_ucsm_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'edm_proxy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'mum_container_policy' died
08-31 03:04:41.208   291  , 291 I ServiceManager: service 'enterprise_billing_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'otp_service' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'enterprise_shared_device_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'knox_timakeystore_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'enterprise_policy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'statusbar' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'clipboard' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'clipboardEx' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'network_management' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'notification' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'devicestoragemonitor' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'location' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'country_detector' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sec_location' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'search' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'execute' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'dropbox' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'wallpaper' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'audio' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'DockObserver' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'midi' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'usb' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'serial' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'kiesusb' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'jobscheduler' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'backup' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'appwidget' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'voiceinteraction' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'SecExternalDisplayService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'diskstats' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'mDNIe' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'AAS' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'MSCS' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'spengestureservice' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'quickconnect' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'samplingprofiler' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'commontime_management' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'dreams' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'graphicsstats' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'print' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'restrictions' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'media_session' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'media_router' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'trust' died
08-31 03:04:41.208   321   900 W AudioFlinger: power manager service died !!!
08-31 03:04:41.208   291   291 I ServiceManager: service 'fingerprint' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'launcherapps' died
08-31 03:04:41.208   321   900 W AudioFlinger: power manager service died !!!
08-31 03:04:41.208   291   291 I ServiceManager: service 'voip' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'media_projection' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'lpnet' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'imms' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'ABTPersistenceService' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'textservices' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'network_score' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'netstats' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'netpolicy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'wifip2p' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'wifi' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'wifihs20' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'wifiscanner' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'rttmanager' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'ethernet' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'connectivity' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sb_service' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'servicediscovery' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'updatelock' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'package' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'activity' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'SEAMService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'media.camera.proxy' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'account' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'content' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'DirEncryptService' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'LSManager' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'ReactiveService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'DeviceRootKeyService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'EngineeringModeService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'SatsService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'sedenial' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'vibrator' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'tw_toolbox' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'tima' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'iccc' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'cepproxyks' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'emailksproxy' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'CustomFrequencyManagerService' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'cover' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'consumer_ir' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'alarm' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'uimode' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'batterystats' died
,08-31 03:04:41.208   291   291 I ServiceManager: service 'appops' died
08-31 03:04:41.208   291   291 I ServiceManager: service 'power' died
08-31 03:04:41.208  1796  1925 E WifiManager: Channel connection lost
08-31 03:04:41.218  1994  2004 W Sensors : sensorservice died [0xa9237cc0]
08-31 03:04:41.218  1676  1676 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-31 03:04:41.218  1994  2444 E WifiManager: Channel connection lost
,08-31 03:04:41.218  1676  2323 E WifiManager: Channel connection lost
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=25 Removed Mauncher (4/10)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=26 Removed VSBConnecti (4/9)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=5 Removed TtatusBar (7/8)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=5 Removed TtatusBar (-2/8)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=7 Removed JmageWallpa (3/7)
,08-31 03:04:41.218   292   332 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/7)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=25 Removed Mauncher (-2/7)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=18 Removed DolorFade (6/6)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=18 Removed DolorFade (-2/6)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=23 Removed VSBConnecti (4/5)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=26 Removed VSBConnecti (-2/5)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=23 Removed VSBConnecti (-2/5)
,08-31 03:04:41.218   292   332 I SurfaceFlinger: id=14 Removed EimLayer(Di (3/4)
08-31 03:04:41.218   292   332 I SurfaceFlinger: id=15 Removed EimLayer(An (2/3)
08-31 03:04:41.218  2264  2290 W Sensors : sensorservice died [0xada7ae00]
08-31 03:04:41.218  1382  1605 E WifiManager: Channel connection lost
08-31 03:04:41.218  6147  6202 E WifiManager: Channel connection lost
,08-31 03:04:41.228   292   949 D libEGL  : eglTerminate EGLDisplay = 0xb234d6fc
,08-31 03:04:41.228   292   949 D libEGL  : eglTerminate EGLDisplay = 0xb234d6fc
,08-31 03:04:41.228   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf38c
,08-31 03:04:41.228  1688  1898 W Sensors : sensorservice died [0xa923b240]
08-31 03:04:41.228   292  4936 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-31 03:04:41.228  1937  2893 W Sensors : sensorservice died [0xb3a73f40]
,08-31 03:04:41.228  1382  2172 W Sensors : sensorservice died [0xb3f17040]
,08-31 03:04:41.228   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf38c
,08-31 03:04:41.238   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf38c
,08-31 03:04:41.238  2216  2216 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ef37cac in tid 2216 (droid.bluetooth)
08-31 03:04:41.238   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf38c
08-31 03:04:41.238   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf38c
,08-31 03:04:41.238   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
08-31 03:04:41.238  2216  2216 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 03:04:41.238  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.238   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf3a4
,08-31 03:04:41.238   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeeaf38c
,08-31 03:04:41.238   292   334 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-31 03:04:41.238   292   334 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
08-31 03:04:41.238   292   334 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-31 03:04:41.238   292   334 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-31 03:04:41.238   292   334 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
08-31 03:04:41.238   292   334 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-31 03:04:41.238  1666  1666 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2c5ec02 in tid 1666 (com.android.nfc)
,08-31 03:04:41.238   292   292 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-31 03:04:41.238   292   292 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-31 03:04:41.238  1666  1666 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 03:04:41.238  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.268  2250  2250 D BluetoothA2dp: Proxy object disconnected
,08-31 03:04:41.268  5184  5184 D BluetoothA2dp: Proxy object disconnected
,08-31 03:04:41.268  5184  5184 D A2dpProfile: Bluetooth service disconnected
08-31 03:04:41.268  5184  5184 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 03:04:41.268   291   291 I ServiceManager: service 'nfc' died
08-31 03:04:41.268  5184  5184 D PanProfile: Bluetooth service disconnected
08-31 03:04:41.268   291   291 I ServiceManager: service 'secontroller' died
08-31 03:04:41.268   291   291 I ServiceManager: service 'nfccontroller' died
,08-31 03:04:41.268  5184  5184 D BluetoothMap: Proxy object disconnected
08-31 03:04:41.268  5184  5184 D MapProfile: Bluetooth service disconnected
,08-31 03:04:41.268  5184  5184 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9212bd in tid 5184 (ndroid.settings)
08-31 03:04:41.268  5184  5184 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 03:04:41.268  2221  2221 E audit_log: File locking failed. error= Bad file descriptor
,08-31 03:04:41.308   350   350 I Zygote  : Process 1666 exited due to signal (7)
08-31 03:04:41.308   350   350 I Zygote  : Process 2216 exited due to signal (7)
08-31 03:04:41.308   350   350 I Zygote  : Process 5184 exited due to signal (7)
,08-31 03:04:41.378   290   290 I lowmemorykiller: ActivityManager disconnected
08-31 03:04:41.378   290   290 I lowmemorykiller: Closing Activity Manager data connection
,08-31 03:04:41.488   292   292 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-31 03:04:41.488   292   545 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-31 03:04:41.488   292   566 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-31 03:04:41.488   292   566 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-31 03:04:41.708   292   545 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-31 03:04:41.748   292   292 I SurfaceFlinger: Disp[0] Orientation 0=>0

```
