#### Test 72145431fdae11f_thali03_samsung-SM-G900F Logs


```
--------- beginning of main
06-30 10:34:54.288  1943  5917 W IcingInternalCorpora: getNumBytesRead when not calculated.
06-30 10:34:54.338   747   756 I art     : Background partial concurrent mark sweep GC freed 142484(8MB) AllocSpace objects, 13(1996KB) LOS objects, 27% free, 41MB/57MB, paused 1.976ms total 151.137ms
,--------- beginning of system
06-30 10:34:55.768   747  1236 V AlarmManager: Expired Alarm result :4
06-30 10:34:55.818   747   747 I BackgroundCompactionService: onStart. jobID=801
06-30 10:34:55.818   747   747 I BackgroundCompactionService: onStart done. jobID=801
06-30 10:34:55.818   747  5942 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
06-30 10:34:55.818   747  5942 I BackgroundCompactionService: compact_memory command done
06-30 10:34:55.848   747  1619 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:34:55.858   747  1619 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 10:34:55.858   747  1619 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 10:34:55.858   747  1619 D BatteryService: stay LED for charging
06-30 10:34:55.858   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:34:55.858   747   747 I MotionRecognitionService: Plugged
06-30 10:34:55.858   747   747 D MotionRecognitionService:   cableConnection= 1
06-30 10:34:55.858   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:34:55.858   747   747 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:34:55.868  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:34:55.868  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:34:55.868  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:34:55.888  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 10:34:55.888  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 10:34:55.888  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 10:34:55.938  2197  2197 E audit   : type=1400 msg=audit(1467275695.928:275): avc:  denied  { execmod } for  pid=5934 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:34:55.938  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:34:55.938  2197  2197 E audit   : type=1300 msg=audit(1467275695.928:275): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff0000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=5934 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:34:55.938  2197  2197 E audit   : type=1327 msg=audit(1467275695.928:275): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 10:34:55.938  2197  2197 E audit   : type=1320 msg=audit(1467275695.928:275): 
06-30 10:34:55.998  2197  2197 E audit   : type=1400 msg=audit(1467275695.998:276): avc:  denied  { execmod } for  pid=5934 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:34:55.998  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:34:55.998  2197  2197 E audit   : type=1300 msg=audit(1467275695.998:276): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3faf000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=5934 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:34:55.998  2197  2197 E audit   : type=1327 msg=audit(1467275695.998:276): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 10:34:55.998  2197  2197 E audit   : type=1320 msg=audit(1467275695.998:276): 
06-30 10:34:56.048  2197  2197 E audit   : type=1400 msg=audit(1467275696.048:277): avc:  denied  { execmod } for  pid=5934 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:34:56.048  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:34:56.048  5934  5934 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:34:56.048  2197  2197 E audit   : type=1300 msg=audit(1467275696.048:277): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fb0000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=5934 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:34:56.048  2197  2197 E audit   : type=1327 msg=audit(1467275696.048:277): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 10:34:56.048  2197  2197 E audit   : type=1320 msg=audit(1467275696.048:277): 
06-30 10:34:56.058  5934  5934 D AndroidRuntime: CheckJNI is OFF
06-30 10:34:56.058  5934  5934 D AndroidRuntime: readGMSProperty: start
06-30 10:34:56.058  5934  5934 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:34:56.058  5934  5934 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:34:56.058  5934  5934 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:34:56.058  5934  5934 D AndroidRuntime: readGMSProperty: end
06-30 10:34:56.058  5934  5934 D AndroidRuntime: addProductProperty: start
06-30 10:34:56.068  5934  5934 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 10:34:56.068  5934  5934 W art     : af15f000-b2085000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:34:56.068  5934  5934 W art     : b2085000-b42f4000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:34:56.068  5934  5934 W art     : b42f4000-b42f5000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:34:56.068  5934  5934 W art     : b42f5000-b431e000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 10:34:56.068  5934  5934 W art     : b431e000-b4321000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
06-30 10:34:56.068  5934  5934 W art     : b4321000-b4322000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
06-30 10:34:56.068  5934  5934 W art     : b4322000-b4323000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
06-30 10:34:56.068  5934  5934 W art     : b4323000-b4771000 r-xp 00000000 b3:17 594        /system/lib/libart.so
06-30 10:34:56.068  5934  5934 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b4772000-b477c000 r--p 0044e000 b3:17 594        /system/lib/libart.so
06-30 10:34:56.068  5934  5934 W art     : b477c000-b477d000 rw-p 00458000 b3:17 594        /system/lib/libart.so
06-30 10:34:56.068  5934  5934 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 10:34:56.068  5934  5934 W art     : b4883000-b4884000 r--p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b4884000-b48a4000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 10:34:56.068  5934  5934 W art     : b48a4000-b52b5000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
06-30 10:34:56.068  5934  5934 W art     : b52b5000-b52b6000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b52b6000-b52ff000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
06-30 10:34:56.068  5934  5934 W art     : b52ff000-b5300000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
06-30 10:34:56.068  5934  5934 W art     : b5300000-b5308000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5308000-b5309000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5309000-b533e000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
06-30 10:34:56.068  5934  5934 W art     : b533e000-b533f000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b533f000-b5340000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
06-30 10:34:56.068  5934  5934 W art     : b5340000-b5341000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
06-30 10:34:56.068  5934  5934 W art     : b5341000-b5399000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
06-30 10:34:56.068  5934  5934 W art     : b5399000-b539a000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b539a000-b539b000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
06-30 10:34:56.068  5934  5934 W art     : b539b000-b539c000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
06-30 10:34:56.068  5934  5934 W art     : b539d000-b53a3000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:34:56.068  5934  5934 W art     : b53a3000-b53a4000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:34:56.068  5934  5934 W art     : b53a4000-b53a5000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:34:56.068  5934  5934 W art     : b53a5000-b53a7000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b53a8000-b53b2000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 10:34:56.068  5934  5934 W art     : b53b2000-b53b5000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 10:34:56.068  5934  5934 W art     : b53b5000-b53b6000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 10:34:56.068  5934  5934 W art     : b53b7000-b53ce000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 10:34:56.068  5934  5934 W art     : b53ce000-b53cf000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b53cf000-b53d0000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 10:34:56.068  5934  5934 W art     : b53d0000-b53d1000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 10:34:56.068  5934  5934 W art     : b53d2000-b53dc000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
06-30 10:34:56.068  5934  5934 W art     : b53dc000-b53dd000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
06-30 10:34:56.068  5934  5934 W art     : b53dd000-b53de000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
06-30 10:34:56.068  5934  5934 W art     : b53de000-b53e2000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 10:34:56.068  5934  5934 W art     : b53e2000-b53e3000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 10:34:56.068  5934  5934 W art     : b53e3000-b53e4000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 10:34:56.068  5934  5934 W art     : b53e4000-b53fa000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
06-30 10:34:56.068  5934  5934 W art     : b53fa000-b53fb000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
06-30 10:34:56.068  5934  5934 W art     : b53fb000-b53fc000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
06-30 10:34:56.068  5934  5934 W art     : b53fc000-b5409000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
06-30 10:34:56.068  5934  5934 W art     : b5409000-b540a000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
06-30 10:34:56.068  5934  5934 W art     : b540a000-b540b000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
06-30 10:34:56.068  5934  5934 W art     : b540b000-b546b000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
06-30 10:34:56.068  5934  5934 W art     : b546b000-b546e000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
06-30 10:34:56.068  5934  5934 W art     : b546e000-b5472000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5472000-b54d3000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
06-30 10:34:56.068  5934  5934 W art     : b54d3000-b54d4000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
06-30 10:34:56.068  5934  5934 W art     : b54d4000-b5523000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
06-30 10:34:56.068  5934  5934 W art     : b5523000-b5525000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
06-30 10:34:56.068  5934  5934 W art     : b5525000-b5526000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
06-30 10:34:56.068  5934  5934 W art     : b5526000-b5527000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5527000-b552e000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 10:34:56.068  5934  5934 W art     : b552e000-b552f000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 10:34:56.068  5934  5934 W art     : b552f000-b5530000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_
06-30 10:34:56.068  5934  5934 W art     : avc_common.so
06-30 10:34:56.068  5934  5934 W art     : b5531000-b5534000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 10:34:56.068  5934  5934 W art     : b5534000-b5535000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 10:34:56.068  5934  5934 W art     : b5535000-b5536000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_
06-30 10:34:56.068  5934  5934 W art     : enc_common.so
06-30 10:34:56.068  5934  5934 W art     : b5537000-b553b000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
06-30 10:34:56.068  5934  5934 W art     : b553b000-b553c000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b553c000-b553d000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
06-30 10:34:56.068  5934  5934 W art     : b553d000-b553e000 rw-p 00005000 b3:17 2517       /syste
06-30 10:34:56.068  5934  5934 W art     : m/lib/libpowermanager.so
06-30 10:34:56.068  5934  5934 W art     : b553f000-b555c000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 10:34:56.068  5934  5934 W art     : b555c000-b555d000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 10:34:56.068  5934  5934 W art     : b555d000-b555e000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 10:34:56.068  5934  5934 W art     : b555f000-b5564000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 10:34:56.068  5934  5934 W art     : b5564000-b5565000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 10:34:56.068  5934  5934 W art     : b5565000-b5566000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 10:34:56.068  5934  5934 W art     : b5567000-b5598000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 10:34:56.068  5934  5934 W art     : b5598000-b559b000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 10:34:56.068  5934  5934 W art     : b559b000-b559c000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 10:34:56.068  5934  5934 W art     : b559d000-b55d8000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
06-30 10:34:56.068  5934  5934 W art     : b55d8000-b55d9000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
06-30 10:34:56.068  5934  5934 W art     : b55d9000-b55da000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
06-30 10:34:56.068  5934  5934 W art     : b55db000-b55e2000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
06-30 10:34:56.068  5934  5934 W art     : b55e2000-b55e3000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b55e3000-b55e4000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
06-30 10:34:56.068  5934  5934 W art     : b55e4000-b55e5000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
06-30 10:34:56.068  5934  5934 W art     : b55e5000-b55e6000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b55e6000-b55fd000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
06-30 10:34:56.068  5934  5934 W art     : b55fd000-b55fe000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b55fe000-b5601000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
06-30 10:34:56.068  5934  5934 W art     : b5601000-b5602000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
06-30 10:34:56.068  5934  5934 W art     : b5602000-b5621000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
06-30 10:34:56.068  5934  5934 W art     : b5621000-b5622000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
06-30 10:34:56.068  5934  5934 W art     : b5622000-b5623000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
06-30 10:34:56.068  5934  5934 W art     : b5623000-b5661000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 10:34:56.068  5934  5934 W art     : b5661000-b5662000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5662000-b5664000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 10:34:56.068  5934  5934 W art     : b5664000-b5665000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 10:34:56.068  5934  5934 W art     : b5666000-b566d000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
06-30 10:34:56.068  5934  5934 W art     : b566d000-b566e000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
06-30 10:34:56.068  5934  5934 W art     : b566e000-b566f000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
06-30 10:34:56.068  5934  5934 W art     : b5670000-b5673000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
06-30 10:34:56.068  5934  5934 W art     : b5673000-b5674000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
06-30 10:34:56.068  5934  5934 W art     : b5674000-b5675000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
06-30 10:34:56.068  5934  5934 W art     : b5675000-b567b000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:34:56.068  5934  5934 W art     : b567b000-b567c000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b567c000-b567d000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:34:56.068  5934  5934 W art     : b567d000-b567e000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:34:56.068  5934  5934 W art     : b567e000-b5687000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
06-30 10:34:56.068  5934  5934 W art     : b5687000-b5688000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
06-30 10:34:56.068  5934  5934 W art     : b5688000-b5689000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
06-30 10:34:56.068  5934  5934 W art     : b5689000-b571a000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 10:34:56.068  5934  5934 W art     : b571a000-b571b000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b571b000-b5726000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 10:34:56.068  5934  5934 W art     : b5726000-b5727000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 10:34:56.068  5934  5934 W art     : b5728000-b573a000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
06-30 10:34:56.068  5934  5934 W art     : b573a000-b573b000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
06-30 10:34:56.068  5934  5934 W art     : b573b000-b573c000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
06-30 10:34:56.068  5934  5934 W art     : b573d000-b5742000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
06-30 10:34:56.068  5934  5934 W art     : b5742000-b5743000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
06-30 10:34:56.068  5934  5934 W art     : b5743000-b5744000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
06-30 10:34:56.068  5934  5934 W art     : b5745000-b57b2000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 10:34:56.068  5934  5934 W art     : b57b2000-b57b3000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b57b3000-b57b5000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 10:34:56.068  5934  5934 W art     : b57b5000-b57b6000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 10:34:56.068  5934  5934 W art     : b57b6000-b57b7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b57b7000-b57be000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:34:56.068  5934  5934 W art     : b57be000-b57bf000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:34:56.068  5934  5934 W art     : b57bf000-b57c0000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:34:56.068  5934  5934 W art     : b57c1000-b5841000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 10:34:56.068  5934  5934 W art     : b5841000-b5842000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5842000-b5843000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 10:34:56.068  5934  5934 W art     : b5843000-b5844000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 10:34:56.068  5934  5934 W art     : b5844000-b585b000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b585b000-b5892000 r-xp 00000000 b3:17 3247       /system/vendor/l
06-30 10:34:56.068  5934  5934 W art     : ib/libqc-opt.so
06-30 10:34:56.068  5934  5934 W art     : b5892000-b5893000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 10:34:56.068  5934  5934 W art     : b5893000-b5894000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 10:34:56.068  5934  5934 W art     : b5894000-b58b0000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 10:34:56.068  5934  5934 W art     : b58b0000-b58b1000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 10:34:56.068  5934  5934 W art     : b58b1000-b58b2000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 10:34:56.068  5934  5934 W art     : b58b3000-b5914000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 10:34:56.068  5934  5934 W art     : b5914000-b5916000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 10:34:56.068  5934  5934 W art     : b5916000-b5917000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 10:34:56.068  5934  5934 W art     : b5918000-b593f000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
06-30 10:34:56.068  5934  5934 W art     : b593f000-b5940000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5940000-b5941000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
06-30 10:34:56.068  5934  5934 W art     : b5941000-b5942000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
06-30 10:34:56.068  5934  5934 W art     : b5943000-b594b000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 10:34:56.068  5934  5934 W art     : b594b000-b594d000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 10:34:56.068  5934  5934 W art     : b594d000-b594e000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 10:34:56.068  5934  5934 W art     : b594f000-b5952000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
06-30 10:34:56.068  5934  5934 W art     : b5952000-b5953000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
06-30 10:34:56.068  5934  5934 W art     : b5953000-b5954000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
06-30 10:34:56.068  5934  5934 W art     : b5954000-b5958000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
06-30 10:34:56.068  5934  5934 W art     : b5958000-b5959000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5959000-b595a000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
06-30 10:34:56.068  5934  5934 W art     : b595a000-b595b000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
06-30 10:34:56.068  5934  5934 W art     : b595b000-b596b000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
06-30 10:34:56.068  5934  5934 W art     : b596b000-b596c000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
06-30 10:34:56.068  5934  5934 W art     : b596c000-b596d000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
06-30 10:34:56.068  5934  5934 W art     : b596d000-b59b3000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b59b3000-b59bc000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
06-30 10:34:56.068  5934  5934 W art     : b59bc000-b59bd000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
06-30 10:34:56.068  5934  5934 W art     : b59bd000-b59be000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
06-30 10:34:56.068  5934  5934 W art     : b59bf000-b59c4000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
06-30 10:34:56.068  5934  5934 W art     : b59c4000-b59c5000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
06-30 10:34:56.068  5934  5934 W art     : b59c5000-b59c6000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
06-30 10:34:56.068  5934  5934 W art     : b59c6000-b59c9000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 10:34:56.068  5934  5934 W art     : b59c9000-b59ca000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b59ca000-b59cb000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 10:34:56.068  5934  5934 W art     : b59cb000-b59cc000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 10:34:56.068  5934  5934 W art     : b59cd000-b59e5000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:34:56.068  5934  5934 W art     : b59e5000-b59e6000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b59e6000-b59e7000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:34:56.068  5934  5934 W art     : b59e7000-b59e8000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:34:56.068  5934  5934 W art     : b59e9000-b5b83000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
06-30 10:34:56.068  5934  5934 W art     : b5b83000-b5b84000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5b84000-b5b91000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
06-30 10:34:56.068  5934  5934 W art     : b5b91000-b5b92000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
06-30 10:34:56.068  5934  5934 W art     : b5b92000-b5b96000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
06-30 10:34:56.068  5934  5934 W art     : b5b96000-b5b97000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5b97000-b5b98000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
06-30 10:34:56.068  5934  5934 W art     : b5b98000-b5b99000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
06-30 10:34:56.068  5934  5934 W art     : b5b99000-b5bac000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
06-30 10:34:56.068  5934  5934 W art     : b5bac000-b5bad000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
06-30 10:34:56.068  5934  5934 W art     : b5bad000-b5bae000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
06-30 10:34:56.068  5934  5934 W art     : b5bae000-b5baf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:34:56.068  5934  5934 W art     : b5baf000-b5bfa000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 10:34:56.068  5934  5934 W art     : b5bfa000-b5bfb000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 10:34:56.068  5934  5934 W art     : b5bfb000-b5bfc000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 10:34:56.068  5934  5934 W art     : b5bfc000-b5bfe000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5bff000-b5c10000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 10:34:56.068  5934  5934 W art     : b5c10000-b5c11000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5c11000-b5c12000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 10:34:56.068  5934  5934 W art     : b5c12000-b5c13000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 10:34:56.068  5934  5934 W art     : b5c14000-b5c1e000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
06-30 10:34:56.068  5934  5934 W art     : b5c1e000-b5c20000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
06-30 10:34:56.068  5934  5934 W art     : b5c20000-b5c21000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
06-30 10:34:56.068  5934  5934 W art     : b5c21000-b5c3a000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
06-30 10:34:56.068  5934  5934 W art     : b5c3a000-b5c3b000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
06-30 10:34:56.068  5934  5934 W art     : b5c3b000-b5c3e000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
06-30 10:34:56.068  5934  5934 W art     : b5c3e000-b5c42000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5c42000-b5cb6000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
06-30 10:34:56.068  5934  5934 W art     : b5cb6000-b5cb7000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5cb7000-b5cba000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
06-30 10:34:56.068  5934  5934 W art     : b5cba000-b5cbb000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
06-30 10:34:56.068  5934  5934 W art     : b5cbb000-b5cbc000 r--p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5cbc000-b5cbf000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
06-30 10:34:56.068  5934  5934 W art     : b5cbf000-b5cc0000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
06-30 10:34:56.068  5934  5934 W art     : b5cc0000-b5cc1000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
06-30 10:34:56.068  5934  5934 W art     : b5cc1000-b5cc2000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5cc2000-b5cc7000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 10:34:56.068  5934  5934 W art     : b5cc7000-b5cc8000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 10:34:56.068  5934  5934 W art     : b5cc8000-b5cc9000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 10:34:56.068  5934  5934 W art     : b5cc9000-b5cca000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5cca000-b5ccd000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 10:34:56.068  5934  5934 W art     : b5ccd000-b5cce000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 10:34:56.068  5934  5934 W art     : b5cce000-b5ccf000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 10:34:56.068  5934  5934 W art     : b5ccf000-b5cd0000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5cd0000-b5cd4000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
06-30 10:34:56.068  5934  5934 W art     : b5cd4000-b5cd5000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
06-30 10:34:56.068  5934  5934 W art     : b5cd5000-b5cd6000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
06-30 10:34:56.068  5934  5934 W art     : b5cd6000-b5cd7000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:34:56.068  5934  5934 W art     : b5cd7000-b5cdb000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 10:34:56.068  5934  5934 W art     : b5cdb000-b5cdc000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 10:34:56.068  5934  5934 W art     : b5cdc000-b5cdd000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 10:34:56.068  5934  5934 W art     : b5cdd000-b5cde000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5cde000-b5cec000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 10:34:56.068  5934  5934 W art     : b5cec000-b5ced000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b5ced000-b5cee000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 10:34:56.068  5934  5934 W art     : b5cee000-b5cef000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 10:34:56.068  5934  5934 W art     : b5cef000-b5cf9000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 10:34:56.068  5934  5934 W art     : b5cf9000-b5cfc000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 10:34:56.068  5934  5934 W art     : b5cfc000-b5cfd000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 10:34:56.068  5934  5934 W art     : b5cfd000-b5cfe000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5cfe000-b5d08000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
06-30 10:34:56.068  5934  5934 W art     : b5d08000-b5d0b000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
06-30 10:34:56.068  5934  5934 W art     : b5d0b000-b5d0c000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
06-30 10:34:56.068  5934  5934 W art     : b5d0c000-b5d10000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
06-30 10:34:56.068  5934  5934 W art     : b5d10000-b5d11000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
06-30 10:34:56.068  5934  5934 W art     : b5d11000-b5d12000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
06-30 10:34:56.068  5934  5934 W art     : b5d12000-b5d13000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b5d13000-b5d20000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:34:56.068  5934  5934 W art     : b5d20000-b5d22000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:34:56.068  5934  5934 W art     : b5d22000-b5d23000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:34:56.068  5934  5934 W art     : b5d23000-b6135000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
06-30 10:34:56.068  5934  5934 W art     : b6135000-b6136000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6136000-b613f000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
06-30 10:34:56.068  5934  5934 W art     : b613f000-b6143000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
06-30 10:34:56.068  5934  5934 W art     : b6143000-b6144000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6144000-b614b000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:34:56.068  5934  5934 W art     : b614b000-b614c000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:34:56.068  5934  5934 W art     : b614c000-b614d000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:34:56.068  5934  5934 W art     : b614d000-b614e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b614e000-b6169000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 10:34:56.068  5934  5934 W art     : b6169000-b616a000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 10:34:56.068  5934  5934 W art     : b616a000-b616b000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 10:34:56.068  5934  5934 W art     : b616b000-b616c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b616c000-b61b8000 r-xp 00000000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 10:34:56.068  5934  5934 W art     : b61b8000-b61b9000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b61b9000-b61ba000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 10:34:56.068  5934  5934 W art     : b61ba000-b61bb000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 10:34:56.068  5934  5934 W art     : b61bb000-b61bc000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b61bc000-b61c0000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
06-30 10:34:56.068  5934  5934 W art     : b61c0000-b61c1000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b61c1000-b61c2000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
06-30 10:34:56.068  5934  5934 W art     : b61c2000-b61c3000 rw-p 00005000 b3:17 2688       /system/lib/libusbhost.so
06-30 10:34:56.068  5934  5934 W art     : b61c3000-b61fb000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
06-30 10:34:56.068  5934  5934 W art     : b61fb000-b61fc000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
06-30 10:34:56.068  5934  5934 W art     : b61fc000-b61fd000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
06-30 10:34:56.068  5934  5934 W art     : b61fd000-b61fe000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b61fe000-b629c000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
06-30 10:34:56.068  5934  5934 W art     : b629c000-b629d000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b629d000-b62bb000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
06-30 10:34:56.068  5934  5934 W art     : b62bb000-b62bc000 rw-p 000bc000 b3:17 409        /system/lib/libmedia.so
06-30 10:34:56.068  5934  5934 W art     : b62bc000-b642f000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
06-30 10:34:56.068  5934  5934 W art     : b642f000-b643a000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
06-30 10:34:56.068  5934  5934 W art     : b643a000-b643b000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
06-30 10:34:56.068  5934  5934 W art     : b643b000-b6552000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:34:56.068  5934  5934 W art     : b6552000-b655d000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:34:56.068  5934  5934 W art     : b655d000-b655e000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:34:56.068  5934  5934 W art     : b655e000-b6562000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6562000-b6586000 r-xp 00000000 b3:17 405        /system/lib/libssl.so
06-30 10:34:56.068  5934  5934 W art     : b6586000-b6588000 r--p 00023000 b3:17 405        /system/lib/libssl.so
06-30 10:34:56.068  5934  5934 W art     : b6588000-b6589000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
06-30 10:34:56.068  5934  5934 W art     : b6589000-b662f000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
06-30 10:34:56.068  5934  5934 W art     : b662f000-b663c000 r--p 000a5000 b3:17 110        /system/lib/libcrypto.so
06-30 10:34:56.068  5934  5934 W art     : b663c000-b663d000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
06-30 10:34:56.068  5934  5934 W art     : b663d000-b663e000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b663e000-b6691000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
06-30 10:34:56.068  5934  5934 W art     : b6691000-b6692000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6692000-b6693000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
06-30 10:34:56.068  5934  5934 W art     : b6693000-b6694000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
06-30 10:34:56.068  5934  5934 W art     : b6694000-b6699000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6699000-b66ab000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
06-30 10:34:56.068  5934  5934 W art     : b66ab000-b66ac000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b66ac000-b66ad000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
06-30 10:34:56.068  5934  5934 W art     : b66ad000-b66ae000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
06-30 10:34:56.068  5934  5934 W art     : b66ae000-b66b5000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 10:34:56.068  5934  5934 W art     : b66b5000-b66b6000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 10:34:56.068  5934  5934 W art     : b66b6000-b66b7000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 10:34:56.068  5934  5934 W art     : b66b7000-b66b8000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b66b8000-b66bb000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
06-30 10:34:56.068  5934  5934 W art     : b66bb000-b66bc000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
06-30 10:34:56.068  5934  5934 W art     : b66bc000-b66bd000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
06-30 10:34:56.068  5934  5934 W art     : b66bd000-b66c1000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
06-30 10:34:56.068  5934  5934 W art     : b66c1000-b66c2000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
06-30 10:34:56.068  5934  5934 W art     : b66c2000-b66c3000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
06-30 10:34:56.068  5934  5934 W art     : b66c3000-b66d1000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
06-30 10:34:56.068  5934  5934 W art     : b66d1000-b66d2000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b66d2000-b66d3000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
06-30 10:34:56.068  5934  5934 W art     : b66d3000-b66d4000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
06-30 10:34:56.068  5934  5934 W art     : b66d4000-b66dd000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 10:34:56.068  5934  5934 W art     : b66dd000-b66de000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 10:34:56.068  5934  5934 W art     : b66de000-b66df000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 10:34:56.068  5934  5934 W art     : b66df000-b6745000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
06-30 10:34:56.068  5934  5934 W art     : b6745000-b6746000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6746000-b6748000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
06-30 10:34:56.068  5934  5934 W art     : b6748000-b6751000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
06-30 10:34:56.068  5934  5934 W art     : b6751000-b6754000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6754000-b67eb000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 10:34:56.068  5934  5934 W art     : b67eb000-b67ed000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 10:34:56.068  5934  5934 W art     : b67ed000-b67ee000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 10:34:56.068  5934  5934 W art     : b67ee000-b67ef000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b67ef000-b6b10000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
06-30 10:34:56.068  5934  5934 W art     : b6b10000-b6b11000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6b11000-b6b2c000 r--p 00321000 b3:17 286        /system/lib/libskia.so
06-30 10:34:56.068  5934  5934 W art     : b6b2c000-b6b30000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
06-30 10:34:56.068  5934  5934 W art     : b6b30000-b6b35000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6b35000-b6b3d000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 10:34:56.068  5934  5934 W art     : b6b3d000-b6b3e000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 10:34:56.068  5934  5934 W art     : b6b3e000-b6b3f000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 10:34:56.068  5934  5934 W art     : b6b3f000-b6b6d000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:34:56.068  5934  5934 W art     : b6b6d000-b6b6e000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6b6e000-b6b75000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:34:56.068  5934  5934 W art     : b6b75000-b6b76000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:34:56.068  5934  5934 W art     : b6b76000-b6bbc000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:34:56.068  5934  5934 W art     : b6bbc000-b6bbd000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6bbd000-b6bc0000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:34:56.068  5934  5934 W art     : b6bc0000-b6bc1000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:34:56.068  5934  5934 W art     : b6bc1000-b6bdc000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
06-30 10:34:56.068  5934  5934 W art     : b6bdc000-b6be0000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
06-30 10:34:56.068  5934  5934 W art     : b6be0000-b6be1000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
06-30 10:34:56.068  5934  5934 W art     : b6be1000-b6c2e000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
06-30 10:34:56.068  5934  5934 W art     : b6c2e000-b6c2f000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6c2f000-b6c3b000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
06-30 10:34:56.068  5934  5934 W art     : b6c3b000-b6c3c000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
06-30 10:34:56.068  5934  5934 W art     : b6c3c000-b6c49000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
06-30 10:34:56.068  5934  5934 W art     : b6c49000-b6c4a000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6c4a000-b6c4b000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
06-30 10:34:56.068  5934  5934 W art     : b6c4b000-b6c4c000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
06-30 10:34:56.068  5934  5934 W art     : b6c4c000-b6c54000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
06-30 10:34:56.068  5934  5934 W art     : b6c54000-b6c55000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6c55000-b6c56000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
06-30 10:34:56.068  5934  5934 W art     : b6c56000-b6c57000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
06-30 10:34:56.068  5934  5934 W art     : b6c57000-b6c5e000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:34:56.068  5934  5934 W art     : b6c5e000-b6c5f000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:34:56.068  5934  5934 W art     : b6c5f000-b6c60000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:34:56.068  5934  5934 W art     : b6c60000-b6c74000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
06-30 10:34:56.068  5934  5934 W art     : b6c74000-b6c76000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
06-30 10:34:56.068  5934  5934 W art     : b6c76000-b6c77000 rw-p 00015000 b3:17 2082       /system/lib/libexpat.so
06-30 10:34:56.068  5934  5934 W art     : b6c77000-b6c9f000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
06-30 10:34:56.068  5934  5934 W art     : b6c9f000-b6ca1000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
06-30 10:34:56.068  5934  5934 W art     : b6ca1000-b6ca2000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
06-30 10:34:56.068  5934  5934 W art     : b6ca2000-b6ca5000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
06-30 10:34:56.068  5934  5934 W art     : b6ca5000-b6ca6000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
06-30 10:34:56.068  5934  5934 W art     : b6ca6000-b6ca7000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
06-30 10:34:56.068  5934  5934 W art     : b6ca7000-b6cb0000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:34:56.068  5934  5934 W art     : b6cb0000-b6cb1000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:34:56.068  5934  5934 W art     : b6cb1000-b6cb2000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:34:56.068  5934  5934 W art     : b6cb2000-b6cd2000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 10:34:56.068  5934  5934 W art     : b6cd2000-b6cd3000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 10:34:56.068  5934  5934 W art     : b6cd3000-b6cd4000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 10:34:56.068  5934  5934 W art     : b6cd4000-b6d47000 r-xp 00000000 b3:17 328        /system/lib/libc.so
06-30 10:34:56.068  5934  5934 W art     : b6d47000-b6d4b000 r--p 00072000 b3:17 328        /system/lib/libc.so
06-30 10:34:56.068  5934  5934 W art     : b6d4b000-b6d4e000 rw-p 00076000 b3:17 328        /system/lib/libc.so
06-30 10:34:56.068  5934  5934 W art     : b6d4e000-b6d58000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6d58000-b6de0000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 10:34:56.068  5934  5934 W art     : b6de0000-b6de1000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6de1000-b6de5000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 10:34:56.068  5934  5934 W art     : b6de5000-b6de6000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 10:34:56.068  5934  5934 W art     : b6de6000-b6de7000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6de7000-b6e10000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:34:56.068  5934  5934 W art     : b6e10000-b6e11000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6e11000-b6e14000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:34:56.068  5934  5934 W art     : b6e14000-b6e15000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:34:56.068  5934  5934 W art     : b6e15000-b6eef000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 10:34:56.068  5934  5934 W art     : b6eef000-b6ef6000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 10:34:56.068  5934  5934 W art     : b6ef6000-b6efe000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 10:34:56.068  5934  5934 W art     : b6efe000-b6eff000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6eff000-b6f00000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:34:56.068  5934  5934 W art     : b6f00000-b6f01000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 10:34:56.068  5934  5934 W art     : b6f01000-b6f02000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b6f02000-b6f05000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b6f05000-b6f2a000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
06-30 10:34:56.068  5934  5934 W art     : b6f2a000-b6f2b000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6f2b000-b6f32000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
06-30 10:34:56.068  5934  5934 W art     : b6f32000-b6f33000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
06-30 10:34:56.068  5934  5934 W art     : b6f33000-b6f3a000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 10:34:56.068  5934  5934 W art     : b6f3a000-b6f3b000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 10:34:56.068  5934  5934 W art     : b6f3b000-b6f3c000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 10:34:56.068  5934  5934 W art     : b6f3c000-b6f3d000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b6f3d000-b6f55000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
06-30 10:34:56.068  5934  5934 W art     : b6f55000-b6f56000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6f56000-b6f57000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
06-30 10:34:56.068  5934  5934 W art     : b6f57000-b6f58000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
06-30 10:34:56.068  5934  5934 W art     : b6f58000-b6f66000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
06-30 10:34:56.068  5934  5934 W art     : b6f66000-b6f67000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6f67000-b6f68000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
06-30 10:34:56.068  5934  5934 W art     : b6f68000-b6f69000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
06-30 10:34:56.068  5934  5934 W art     : b6f69000-b6f6a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:34:56.068  5934  5934 W art     : b6f6a000-b6f6c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b6f6c000-b6f6d000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b6f6d000-b6f6e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:34:56.068  5934  5934 W art     : b6f6e000-b6f6f000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 10:34:56.068  5934  5934 W art     : b6f6f000-b6f70000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:34:56.068  5934  5934 W art     : b6f70000-b6f90000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 10:34:56.068  5934  5934 W art     : b6f90000-b6f91000 r--p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6f91000-b6f92000 ---p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6f92000-b6f94000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 10:34:56.068  5934  5934 W art     : b6f94000-b6f95000 r-xp 00000000 00:00 0          [sigpage]
06-30 10:34:56.068  5934  5934 W art     : b6f95000-b6fb0000 r-xp 00000000 b3:17 2771       /system/bin/linker
06-30 10:34:56.068  5934  5934 W art     : b6fb0000-b6fb1000 r--p 0001a000 b3:17 2771       /system/bin/linker
06-30 10:34:56.068  5934  5934 W art     : b6fb1000-b6fb3000 rw-p 0001b000 b3:17 2771       /system/bin/linker
06-30 10:34:56.068  5934  5934 W art     : b6fb3000-b6fb5000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : b6fb5000-b6fba000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 10:34:56.068  5934  5934 W art     : b6fba000-b6fbb000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 10:34:56.068  5934  5934 W art     : b6fbb000-b6fbc000 rw-p 00000000 00:00 0 
06-30 10:34:56.068  5934  5934 W art     : beba0000-bebc1000 rw-p 00000000 00:00 0          [stack]
06-30 10:34:56.068  5934  5934 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 10:34:56.108  5934  5934 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:34:56.128   747   821 I ActivityManager: Waited long enough for: ServiceRecord{a25e131 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
06-30 10:34:56.158  5934  5934 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:34:56.168  5934  5934 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:34:56.188  5934  5934 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:34:56.198   747  1711 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
06-30 10:34:56.208   747  1711 D ActivityManager: mDVFSHelper.acquire()
06-30 10:34:56.208   747  1711 D FocusedStackFrame: Set to : 0
06-30 10:34:56.208   747  1711 V WindowManager: addAppToken: AppWindowToken{db35e6b token=Token{13b1fba ActivityRecord{854e8e5 u0 com.test.thalitest/.MainActivity t77}}} to stack=1 task=77 at 0
06-30 10:34:56.218   747   874 D SecWifiDisplayUtil: Metadata value : none
06-30 10:34:56.218   747   874 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7db2fe3 V.E...... R.....ID 0,0-0,0}
06-30 10:34:56.218   747   874 D ISSUE_DEBUG: InputChannelName : b374899 Starting com.test.thalitest
06-30 10:34:56.228  5966  5966 E Zygote  : v2
06-30 10:34:56.228  5966  5966 I libpersona: KNOX_SDCARD checking this for 10004
06-30 10:34:56.228  5966  5966 I libpersona: KNOX_SDCARD not a persona
06-30 10:34:56.228   747  1711 I ActivityManager: Start proc 5966:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 10:34:56.228   747  1711 D InputDispatcher: Focused application set to: xxxx
06-30 10:34:56.228  5966  5966 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:34:56.228  5966  5966 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:34:56.228   747  1711 D InputDispatcher: Focus left window: 1697
06-30 10:34:56.228  5966  5966 E Zygote  : accessInfo : 0
06-30 10:34:56.228  5966  5966 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 10:34:56.228  5934  5934 D AndroidRuntime: Shutting down VM
06-30 10:34:56.238   293   293 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
06-30 10:34:56.258  5966  5966 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:34:56.258  5966  5966 D ActivityThread: Added TimaKeyStore provider
06-30 10:34:56.258   747   761 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 10:34:56.258   747   761 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 10:34:56.268   747   822 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b374899 u0 d0 Starting com.test.thalitest}
06-30 10:34:56.268  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 10:34:56.268   747   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:747 uid:1000
06-30 10:34:56.268   747   874 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:34:56.268   747   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:747 uid:1000
06-30 10:34:56.268   747   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 10:34:56.268   747   874 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 10:34:56.278   747   761 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 10:34:56.288  1697  1891 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
06-30 10:34:56.288  1697  1697 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
06-30 10:34:56.298   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb49ff64c
06-30 10:34:56.298   293  1297 D libEGL  : eglTerminate EGLDisplay = 0xb49ff64c
06-30 10:34:56.308   747   874 V WindowStateAnimator: Finishing drawing window Window{b374899 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 10:34:56.308   293  1503 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
06-30 10:34:56.308   293   361 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
06-30 10:34:56.308  2280  2298 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
06-30 10:34:56.308  1697  1697 V ActivityThread: updateVisibility : ActivityRecord{48ba595 token=android.os.BinderProxy@626d92f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 10:34:56.308   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9263a4
06-30 10:34:56.308  1697  1697 D Launcher: onTrimMemory. Level: 20
06-30 10:34:56.308   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe926364
06-30 10:34:56.378   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:34:56.588   747   761 I WindowManager: Screenshot max retries 4 of Token{13b1fba ActivityRecord{854e8e5 u0 com.test.thalitest/.MainActivity t77}} appWin=Window{b374899 u0 d0 Starting com.test.thalitest} drawState=4
,06-30 10:34:56.598   747   821 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,06-30 10:34:56.608  5966  5966 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 10:34:56.618   747  3322 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:34:56.628  5966  5966 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 10:34:56.638  5966  5966 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 10:34:56.638  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:34:56.648  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:34:56.648  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:34:56.648  5966  5966 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,06-30 10:34:56.668  1630  1644 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:34:56.668  1630  1644 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:34:56.668  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:34:56.668  1630  1644 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:34:56.668  1630  1644 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:34:56.668  1630  1644 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:34:56.678  5966  5966 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,06-30 10:34:56.678  5306  5306 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:34:56.678  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:34:56.678  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 10:34:56.688  5966  5966 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 10:34:56.718  5966  5966 I cr_LibraryLoader: Time to load native libraries: 15 ms (timestamps 8973-8988)
06-30 10:34:56.718  5966  5966 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 10:34:56.738  5966  5966 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14086a0}
,06-30 10:34:56.738  5966  5966 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 10:34:56.748  5966  5983 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-30 10:34:56.758  5966  5966 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:34:56.758  5966  5966 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-30 10:34:56.808  5966  5984 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,06-30 10:34:56.828  5966  5966 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 10:34:56.828  5966  5966 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 10:34:56.828  5966  5966 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 10:34:56.828  5966  5966 I Adreno-EGL: Local Branch: ss
06-30 10:34:56.828  5966  5966 I Adreno-EGL: Remote Branch: 
06-30 10:34:56.828  5966  5966 I Adreno-EGL: Local Patches: 
06-30 10:34:56.828  5966  5966 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:34:56.838  5966  5966 D libEGL  : eglInitialize EGLDisplay = 0xbeeeadac
,06-30 10:34:56.868   747  1757 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,06-30 10:34:56.868   747  1757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,06-30 10:34:56.918  5966  5966 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-30 10:34:56.928  5966  5966 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:34:56.938  5966  5966 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,06-30 10:34:56.938  5966  5966 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-30 10:34:56.938  5966  5966 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-30 10:34:56.948  5966  5966 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-30 10:34:56.948  5966  5966 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 10:34:56.978  5966  5966 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:34:56.988  5966  5966 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{737e I.E...... R.....ID 0,0-0,0}
,06-30 10:34:56.988  5966  6007 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:34:56.988   747  1703 D ISSUE_DEBUG: InputChannelName : 711e517 com.test.thalitest/com.test.thalitest.MainActivity
,06-30 10:34:56.998   747  1764 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 10:34:56.998   747  1764 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:34:56.998   747   747 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:34:56.998   747   747 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 10:34:57.008  5966  5966 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 5966
,06-30 10:34:57.008   747  1321 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/5966 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:34:57.018  5966  5966 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:34:57.028  5966  5983 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-30 10:34:57.038   293   293 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,06-30 10:34:57.048   747  1764 D InputDispatcher: Focus entered window: 5966
,06-30 10:34:57.058   747   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:747 uid:1000
06-30 10:34:57.058   747   874 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:34:57.058   747   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:747 uid:1000
06-30 10:34:57.058   747   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 10:34:57.058  5966  6007 D libEGL  : eglInitialize EGLDisplay = 0x9d6ff7c4
06-30 10:34:57.058  5966  6007 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:34:57.088  5966  5966 V ActivityThread: updateVisibility : ActivityRecord{a7f8bfb token=android.os.BinderProxy@b7e139 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 10:34:57.098  5966  5966 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,06-30 10:34:57.098  5966  5966 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 10:34:57.098   747  1711 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:34:57.108  5966  5966 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:34:57.128   747  1764 V WindowStateAnimator: Finishing drawing window Window{711e517 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-30 10:34:57.128  5966  5966 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 10:34:57.128  5966  5966 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b7e139 time:89393
,06-30 10:34:57.128   747   874 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:34:57.138   747   747 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:34:57.138   747   874 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +546ms (total +921ms)
,06-30 10:34:57.138   747   874 D ActivityManager: mDVFSHelper.release()
06-30 10:34:57.138   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe926364
06-30 10:34:57.138   747   874 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{854e8e5 u0 com.test.thalitest/.MainActivity t77} time:89401
06-30 10:34:57.138   747   874 D ViewRootImpl: #3 mView = null
,06-30 10:34:57.138   293   361 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,06-30 10:34:57.138   747   747 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:34:57.138   293   367 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,06-30 10:34:57.148  5966  6015 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:34:57.148  5966  6015 D libEGL  : eglInitialize EGLDisplay = 0x9c03f3ec
,06-30 10:34:57.148   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9263a4
,06-30 10:34:57.188  5966  5966 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5966
,06-30 10:34:57.318  5966  5966 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:34:57.418  5966  6021 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1684539088
,06-30 10:34:57.418  5966  6021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:34:57.418  5966  6021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:34:57.418  5966  6021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:34:57.418  5966  6021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:34:57.418  5966  6021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 10:34:57.418  5966  6021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f68aa9 added. We now have 1 listener(s)
,06-30 10:34:57.418  5966  6021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:3F:75:69
,06-30 10:34:57.418  5966  6021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:3F:75:69"
06-30 10:34:57.418  5966  6021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:34:57.418  5966  6021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:3F:75:69
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 10:34:57.428  5966  6021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fad4d5c added. We now have 1 listener(s)
06-30 10:34:57.428  5966  6021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 10:34:57.428  5966  6021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:34:57.428  5966  6021 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 10:34:57.428  5966  6021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:34:57.428  5966  6021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:34:57.428  5966  6021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:34:57.428  5966  6021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:34:57.428  5966  6021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:34:57.428  5966  6021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:3F:75:69
06-30 10:34:57.428  5966  6021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:34:57.428  5966  6021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:34:57.428  5966  6021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:34:57.428  5966  6021 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-30 10:34:57.428  5966  6021 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:34:57.458  5966  5966 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:34:57.608   747  3323 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,06-30 10:34:57.998  1452  1452 D Recents : onTaskStackChanged
,06-30 10:34:58.008  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,06-30 10:34:58.258  5966  6025 W jxcore-log: Initializing JXcore engine
,06-30 10:34:58.258  5966  6025 W jxcore-log: JXcore engine is ready
,06-30 10:34:58.298  2197  2197 E audit   : type=1400 msg=audit(1467275698.298:278): avc:  denied  { ioctl } for  pid=6025 comm="Thread-859" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:34:58.298  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,06-30 10:34:58.298  2197  2197 E audit   : type=1300 msg=audit(1467275698.298:278): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9b87a3c8 items=0 ppid=348 ppcomm=main pid=6025 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-859" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:34:58.298  2197  2197 E audit   : type=1327 msg=audit(1467275698.298:278): proctitle="com.test.thalitest"
06-30 10:34:58.298  2197  2197 E audit   : type=1320 msg=audit(1467275698.298:278): 
06-30 10:34:58.298  2197  2197 E audit   : type=1400 msg=audit(1467275698.298:279): avc:  denied  { ioctl } for  pid=6025 comm="Thread-859" path="socket:[34673]" dev="sockfs" ino=34673 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 10:34:58.298  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,06-30 10:34:58.298  2197  2197 E audit   : type=1300 msg=audit(1467275698.298:279): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=3 a3=9b87a3c8 items=0 ppid=348 ppcomm=main pid=6025 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-859" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:34:58.298  2197  2197 E audit   : type=1327 msg=audit(1467275698.298:279): proctitle="com.test.thalitest"
06-30 10:34:58.298  2197  2197 E audit   : type=1320 msg=audit(1467275698.298:279): 
,06-30 10:34:58.308  5966  6025 W jxcore-log: Starting JXcore engine
,06-30 10:34:58.388  5966  6025 W jxcore-log: Platform android
06-30 10:34:58.388  5966  6025 W jxcore-log: 
,06-30 10:34:58.388  5966  6025 W jxcore-log: Process ARCH arm
06-30 10:34:58.388  5966  6025 W jxcore-log: 
,06-30 10:34:58.558   747  1572 E Watchdog: !@Sync 2 [06-30 10:34:58.565]
,06-30 10:34:58.578  5966  6025 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:34:58.578  5966  6025 I jxcore-log: 
,06-30 10:34:58.578  5966  6025 W jxcore-log: JXcore engine is started
,06-30 10:34:58.588  5966  6021 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:34:58.598   747   760 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package null
,06-30 10:34:58.608   747   760 D ActivityManager: mDVFSHelper.acquire()
,06-30 10:34:58.608   747   760 V WindowManager: addAppToken: AppWindowToken{e604207 token=Token{e1d2046 ActivityRecord{12ba421 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t77}}} to stack=1 task=77 at 1
,06-30 10:34:58.618  6028  6028 E Zygote  : v2
,06-30 10:34:58.618  6028  6028 I libpersona: KNOX_SDCARD checking this for 10130
06-30 10:34:58.618  6028  6028 I libpersona: KNOX_SDCARD not a persona
,06-30 10:34:58.618  6028  6028 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:34:58.618  6028  6028 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:34:58.628  6028  6028 E Zygote  : accessInfo : 0
,06-30 10:34:58.628  6028  6028 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
06-30 10:34:58.628   747   760 I ActivityManager: Start proc 6028:com.android.packageinstaller/u0a130 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 10:34:58.628   747   760 D InputDispatcher: Focused application set to: xxxx
,06-30 10:34:58.628   747   760 D InputDispatcher: Focus left window: 5966
,06-30 10:34:58.628  5966  6021 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:34:58.638   747   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:747 uid:1000
06-30 10:34:58.638   747   874 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:34:58.638   747   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:747 uid:1000
06-30 10:34:58.638   747   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:34:58.648  6028  6028 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:34:58.648  6028  6028 D ActivityThread: Added TimaKeyStore provider
,06-30 10:34:58.648   747   761 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 10:34:58.658   747   821 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 10:34:58.958   747   761 I WindowManager: Screenshot max retries 4 of Token{e1d2046 ActivityRecord{12ba421 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t77}} appWin=Window{711e517 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 10:34:58.988  6028  6028 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.008  6028  6028 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 10:34:59.018  6028  6028 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.018  6028  6028 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.098  6028  6028 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.128  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.128  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.138  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.138  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.148  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.148  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.228  6028  6028 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:34:59.238  6028  6028 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:34:59.238  6028  6028 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b3ea5a8 I.E...... R.....I. 0,0-0,0}
,06-30 10:34:59.238  6028  6047 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:34:59.248   747  1757 D ISSUE_DEBUG: InputChannelName : 934aa0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
06-30 10:34:59.248   747  1622 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 10:34:59.248   747  1622 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:34:59.248   747   747 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:34:59.248   747   747 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 10:34:59.248   747   747 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 10:34:59.258   747  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/77_task.xml.bak
,06-30 10:34:59.268   293   293 I SurfaceFlinger: id=15 createSurf (145x145),1 flag=4, HrantPermis
,06-30 10:34:59.278   747   822 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{934aa0 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
06-30 10:34:59.278  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 10:34:59.288   747   761 D InputDispatcher: Focus entered window: 6028
,06-30 10:34:59.288   747   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:747 uid:1000
06-30 10:34:59.288   747   874 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:34:59.288   747   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:747 uid:1000
06-30 10:34:59.288   747   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:34:59.288  6028  6047 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 10:34:59.288  6028  6047 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 10:34:59.288  6028  6047 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 10:34:59.288  6028  6047 I Adreno-EGL: Local Branch: ss
06-30 10:34:59.288  6028  6047 I Adreno-EGL: Remote Branch: 
06-30 10:34:59.288  6028  6047 I Adreno-EGL: Local Patches: 
06-30 10:34:59.288  6028  6047 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:34:59.298  6028  6047 D libEGL  : eglInitialize EGLDisplay = 0xae2447c4
06-30 10:34:59.298  6028  6047 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:34:59.338  6028  6028 V ActivityThread: updateVisibility : ActivityRecord{a641743 token=android.os.BinderProxy@4a839cb {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 10:34:59.348  6028  6028 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 10:34:59.348   747  1623 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:34:59.378  6028  6028 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:34:59.378  1987  1987 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 10:34:59.458   747   760 V WindowStateAnimator: Finishing drawing window Window{934aa0 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,06-30 10:34:59.468  6028  6028 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4a839cb time:91730
,06-30 10:34:59.468   747   874 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:34:59.468   747   874 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +504ms (total +864ms)
06-30 10:34:59.468   747   747 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:34:59.478   747   747 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:34:59.478   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe926364
,06-30 10:34:59.478   747   874 D ActivityManager: mDVFSHelper.release()
06-30 10:34:59.478   747   874 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12ba421 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t77} time:91744
,06-30 10:34:59.658  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:34:59.988   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:35:00.248  1452  1452 D Recents : onTaskStackChanged
,06-30 10:35:01.608   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:02.148   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:35:02.158   747  1623 V AlarmManager:  remove PendingIntent] PendingIntent{1f270cc: PendingIntentRecord{4d22e55 com.google.android.gms broadcastIntent}}
,06-30 10:35:02.158   747  1324 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:35:02.158   747  1324 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:35:02.158   747   747 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,06-30 10:35:02.168   747   747 V AlarmManagerEXT: <AppSync3 Whitelist>
,06-30 10:35:02.168   747   747 V AlarmManagerEXT: (AppSync) ### 0 added ###
,06-30 10:35:02.178  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:35:02.178  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 10:35:02.178  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:35:02.188  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:35:02.188  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:35:02.208  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.208  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.208  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.208  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.218  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.218  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.218  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.288  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:35:02.338   747  2296 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 10:35:02.338   747  2296 V MARsPolicyManager: updateSMDBValues
,06-30 10:35:02.338   747   871 E MARsDBManager: updateDBAll : begin --size 1
,06-30 10:35:02.348   747   871 E MARsDBManager: updateDBAll : end
,06-30 10:35:02.348   747   871 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 10:35:02.358   747  3322 D SSRM:n  : SIOP:: AP = 410, PST = 461, CUR = 300, LCD = 0
,06-30 10:35:05.018   747  3322 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:35:05.928   747   760 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:05.938   747   760 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4376, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:35:05.938   747   760 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:35:05.938   747   760 D BatteryService: stay LED for charging
,06-30 10:35:05.948   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:05.958   747   747 I MotionRecognitionService: Plugged
,06-30 10:35:05.958   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:35:05.958   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:35:05.958   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:35:05.968  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:05.968  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:05.968  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:05.998  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:05.998  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:05.998  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:06.218   747   912 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 10:35:06.278   747   912 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 10:35:06.608   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:11.608   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:12.178   747  1324 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:35:12.188   747  1324 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:35:12.418   747  3322 D SSRM:n  : SIOP:: AP = 380, PST = 454, CUR = 300, LCD = 0
,06-30 10:35:13.018  3581  3581 D FactoryTest: User mode
,06-30 10:35:13.018  3581  3581 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,06-30 10:35:13.018  3581  3581 D MTPRx   : still no open session command from host, so toast
,06-30 10:35:13.028   747  1619 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,06-30 10:35:13.038   747  1619 D ActivityManager: mDVFSHelper.acquire()
,06-30 10:35:13.048   747  1619 V WindowManager: addAppToken: AppWindowToken{a3bcdb8 token=Token{5dfb81b ActivityRecord{13f122a u0 com.samsung.android.MtpApplication/.USBConnection t78}}} to stack=1 task=78 at 0
,06-30 10:35:13.048   747  1619 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,06-30 10:35:13.058   747   821 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,06-30 10:35:13.088   747  1619 D InputDispatcher: Focused application set to: xxxx
,06-30 10:35:13.088   747  1619 D InputDispatcher: Focus left window: 6028
,06-30 10:35:13.088   747   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:747 uid:1000
,06-30 10:35:13.088   747   874 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 10:35:13.088   747   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:747 uid:1000
06-30 10:35:13.088   747   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:35:13.098   747   822 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{711e517 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,06-30 10:35:13.098  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,06-30 10:35:13.108   747  3322 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:35:13.108  3581  3581 E MTPRx   : started activity for popup
,06-30 10:35:13.118  3581  3581 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,06-30 10:35:13.118  3581  3581 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,06-30 10:35:13.138  3581  3581 D MTPUSBConnection: onCreate in USBConnection
,06-30 10:35:13.138  3581  3581 V MTPUSBConnection: Registering broadcast receiver.
,06-30 10:35:13.138  3581  3581 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,06-30 10:35:13.138   747  1619 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,06-30 10:35:13.198  3581  3581 D TAG     : dev.kiessupport is : TRUE
,06-30 10:35:13.238  3581  3581 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:35:13.248  3581  3581 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{70b8869 V.E...... R.....I. 0,0-0,0}
,06-30 10:35:13.248  3581  6094 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:13.248   747   761 D ISSUE_DEBUG: InputChannelName : 6de9bd0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,06-30 10:35:13.248   747   761 D InputDispatcher: Focus entered window: 3581
,06-30 10:35:13.258   747   822 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6de9bd0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,06-30 10:35:13.258   747   874 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:747 uid:1000
,06-30 10:35:13.258  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 10:35:13.258   747   874 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:35:13.258   747   874 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:747 uid:1000
,06-30 10:35:13.258   747   874 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:35:13.268  3581  3581 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b12dba1 I.E...... R.....I. 0,0-0,0}
,06-30 10:35:13.268   747  1711 D ISSUE_DEBUG: InputChannelName : 8851ece com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,06-30 10:35:13.268   747  1765 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 10:35:13.268   747  1765 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:35:13.268   747   747 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:35:13.268   747   747 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 10:35:13.268   747   747 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 10:35:13.308   293   293 I SurfaceFlinger: id=16 createSurf (145x145),1 flag=4, VSBConnecti
,06-30 10:35:13.318  3581  6094 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 10:35:13.318  3581  6094 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 10:35:13.318  3581  6094 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 10:35:13.318  3581  6094 I Adreno-EGL: Local Branch: ss
06-30 10:35:13.318  3581  6094 I Adreno-EGL: Remote Branch: 
06-30 10:35:13.318  3581  6094 I Adreno-EGL: Local Patches: 
06-30 10:35:13.318  3581  6094 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:35:13.328  3581  6094 D libEGL  : eglInitialize EGLDisplay = 0x9f08d7c4
06-30 10:35:13.328  3581  6094 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:13.418   293   293 I SurfaceFlinger: id=17 createSurf (193x193),1 flag=4, VSBConnecti
,06-30 10:35:13.458  3581  3581 V ActivityThread: updateVisibility : ActivityRecord{240acb4 token=android.os.BinderProxy@daf42ee {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,06-30 10:35:13.458  3581  3581 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:35:13.548   747  1703 V WindowStateAnimator: Finishing drawing window Window{6de9bd0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,06-30 10:35:13.548  3581  3581 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:35:13.548   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe926364
,06-30 10:35:13.558   747  1321 V WindowStateAnimator: Finishing drawing window Window{8851ece u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,06-30 10:35:13.558  3581  3581 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
06-30 10:35:13.558  3581  3581 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 10:35:13.558   747  1622 V WindowStateAnimator: Finishing drawing window Window{6de9bd0 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,06-30 10:35:13.558   747   874 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:35:13.568   747  1737 V WindowStateAnimator: Finishing drawing window Window{8851ece u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,06-30 10:35:13.568   747   747 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:35:13.568  3581  3581 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@daf42ee time:105830
,06-30 10:35:13.568   747   747 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:35:13.568   747   874 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +488ms (total +518ms)
,06-30 10:35:13.568   747   874 D ActivityManager: mDVFSHelper.release()
,06-30 10:35:13.568   747   874 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{13f122a u0 com.samsung.android.MtpApplication/.USBConnection t78} time:105833
,06-30 10:35:13.568   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe926364
06-30 10:35:13.568   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe926364
,06-30 10:35:14.098   747  3323 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,06-30 10:35:14.278  1452  1452 D Recents : onTaskStackChanged
,06-30 10:35:14.308  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,06-30 10:35:16.008   747  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:16.018   747  1623 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4380, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:35:16.018   747  1623 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:35:16.018   747  1623 D BatteryService: stay LED for charging
,06-30 10:35:16.028   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:16.038   747   747 I MotionRecognitionService: Plugged
,06-30 10:35:16.038   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:35:16.038   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:35:16.048   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:35:16.058  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:16.058  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:16.068  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:16.088  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:16.088  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:16.088  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:16.618   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:19.138   747  3322 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:35:22.478   747  3322 D SSRM:n  : SIOP:: AP = 350, PST = 444, CUR = 300, LCD = 0
,06-30 10:35:22.518   747  3322 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:35:26.578   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:35:26.658   747   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:26.658   747   761 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:35:26.658   747   761 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:35:26.658   747   761 D BatteryService: stay LED for charging
,06-30 10:35:26.678   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e5859da u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f342f7c 1630:com.google.android.gms.persistent/u0a12}
,06-30 10:35:26.678   747  2278 V AlarmManager:  remove PendingIntent] PendingIntent{f9ade0b: PendingIntentRecord{d30f336 com.google.android.gms broadcastIntent}}
,06-30 10:35:26.688   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:26.688   747  1642 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 10:35:26.698   747  1642 V AlarmManager:  remove PendingIntent] PendingIntent{3143ab5: PendingIntentRecord{67e554a android broadcastIntent}}
,06-30 10:35:26.698  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:26.698  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:35:26.698  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:26.728  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 10:35:26.728  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
06-30 10:35:26.728  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:26.738   747   747 I MotionRecognitionService: Plugged
06-30 10:35:26.738   747   747 D MotionRecognitionService:   cableConnection= 1
06-30 10:35:26.738   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:35:26.738   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:35:27.078  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:35:27.098  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:35:27.098  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:35:27.118  1630  1644 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:35:27.118  1630  1644 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:35:27.118  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:35:27.118  1630  1644 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:35:27.118  1630  1644 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:35:27.118  1630  1644 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:35:27.138  5306  5306 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:35:27.138  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:35:27.138  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 10:35:28.558   747  1572 E Watchdog: !@Sync 3 [06-30 10:35:28.567]
,06-30 10:35:32.578   747  3322 D SSRM:n  : SIOP:: AP = 340, PST = 433, CUR = 300, LCD = 0
,06-30 10:35:36.618   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:36.728   747  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:36.738   747  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:35:36.738   747  1321 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:35:36.738   747  1321 D BatteryService: stay LED for charging
,06-30 10:35:36.748   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:36.758   747   747 I MotionRecognitionService: Plugged
,06-30 10:35:36.758   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:35:36.758   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:35:36.758   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:35:36.778  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:36.778  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:36.778  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:36.808  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:36.808  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:36.808  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:42.638   747  3322 D SSRM:n  : SIOP:: AP = 330, PST = 418, CUR = 300, LCD = 0
,06-30 10:35:42.648   747  3322 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,06-30 10:35:42.708  4883  4883 D SystemBroadcastReceiver: [FACE] Received broadcast 
,06-30 10:35:42.718  6138  6138 E Zygote  : v2
,06-30 10:35:42.718   747   821 I ActivityManager: Start proc 6138:com.sec.android.app.videoplayer/u0a54 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,06-30 10:35:42.718   747  1324 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 10:35:42.728  6138  6138 I libpersona: KNOX_SDCARD checking this for 10054
,06-30 10:35:42.728  6138  6138 I libpersona: KNOX_SDCARD not a persona
,06-30 10:35:42.728  6138  6138 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:35:42.738  6138  6138 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:35:42.738  6138  6138 E Zygote  : accessInfo : 0
,06-30 10:35:42.738   747  3322 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:35:42.738  4883  4883 I SystemBroadcastReceiver: [FACE] onReceive broadcastcompleted  
,06-30 10:35:42.748  6138  6138 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,06-30 10:35:42.768  2700  2700 D ContentApp:  LEVEL : 0
,06-30 10:35:42.778  4883  6144 I SystemBroadcastReceiver: [FACE] Calling notifyListeners. 
,06-30 10:35:42.778  4883  6144 D SystemBroadcastReceiver: [FACE] Event id =  EVENT_SIOP
,06-30 10:35:42.788  4883  6144 D SystemBroadcastReceiver: [FACE] getRegisteredListnersForIntent completed 
,06-30 10:35:42.788  4883  6144 I PolicyManager: [FACE] onReceive action = EVENT_SIOP
06-30 10:35:42.788  4883  6144 D FaceGroupingTask: [FACE] onCanProcess  false
06-30 10:35:42.788  4883  6144 I FaceGroupingTask: [FACE] Grouping task pausing due to policy request 
,06-30 10:35:42.858  6138  6138 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:42.858  6138  6138 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:42.878   747  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef17271 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2125856 6138:com.sec.android.app.videoplayer/u0a54}
,06-30 10:35:42.888   747  1324 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,06-30 10:35:42.898  6138  6138 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,06-30 10:35:42.928  6138  6138 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,06-30 10:35:42.948  6138  6138 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,06-30 10:35:42.978  6138  6138 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,06-30 10:35:42.978  6138  6138 D videowall-Global: core_num = 4
,06-30 10:35:42.998  6138  6138 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
06-30 10:35:42.998  6138  6138 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,06-30 10:35:43.008  6138  6138 D TranscodeReceiver:  SIOP_LEVEL: 0
,06-30 10:35:43.008   747   761 I ActivityManager: Killing 4883:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,06-30 10:35:43.038   747  2278 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,06-30 10:35:47.158   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:35:47.228   747  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:47.228   747  1623 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:35:47.228   747  1623 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:35:47.228   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:35:47.228   747  1623 D BatteryService: stay LED for charging
,06-30 10:35:47.238  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:47.238  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:35:47.238  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:35:47.258   747   747 I MotionRecognitionService: Plugged
,06-30 10:35:47.258   747   747 D MotionRecognitionService:   cableConnection= 1
06-30 10:35:47.258   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:35:47.258   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:35:47.268  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:47.268  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:47.268  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:35:47.668  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:35:47.678  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:35:47.688  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:35:47.708  1630  1643 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:35:47.708  1630  1643 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:35:47.708  1630  1643 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:35:47.708  1630  1643 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:35:47.708  1630  1643 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:35:47.708  1630  1643 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:35:47.728  5306  5306 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:35:47.738  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:35:47.738  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 10:35:52.788   747  3322 D SSRM:n  : SIOP:: AP = 330, PST = 402, CUR = 300, LCD = 0
,06-30 10:35:52.788   747  3322 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,06-30 10:35:52.818  2700  2700 D ContentApp:  LEVEL : -1
,06-30 10:35:52.848   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8f8306 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2125856 6138:com.sec.android.app.videoplayer/u0a54}
,06-30 10:35:52.848  6138  6138 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,06-30 10:35:52.848  6138  6138 D TranscodeReceiver:  SIOP_LEVEL: -1
,06-30 10:35:56.628   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:35:57.308   747  1765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:35:58.568   747  1572 E Watchdog: !@Sync 4 [06-30 10:35:58.577]
,06-30 10:35:59.668  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:35:59.988   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:36:02.898   747  3322 D SSRM:n  : SIOP:: AP = 320, PST = 385, CUR = 300, LCD = 0
,06-30 10:36:07.748   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:36:07.818  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:36:07.818  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 10:36:07.828   747  1705 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:07.828   747  1705 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:36:07.828   747  1705 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:36:07.828   747  1705 D BatteryService: stay LED for charging
,06-30 10:36:07.828  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:36:07.848   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:07.868  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:36:07.868  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:36:07.868   747   747 I MotionRecognitionService: Plugged
,06-30 10:36:07.868   747   747 D MotionRecognitionService:   cableConnection= 1
06-30 10:36:07.868   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:36:07.878   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:36:07.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.888  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.888  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:07.888  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:36:07.888  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:07.888  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:36:07.888  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:36:07.888  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,06-30 10:36:07.898  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:07.938  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:08.308  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:08.318  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:08.328  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:08.348  1630  3998 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:36:08.348  1630  3998 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:36:08.348  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:36:08.348  1630  3998 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:36:08.348  1630  3998 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:36:08.348  1630  3998 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:36:08.368  5306  5306 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:36:08.368  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:36:08.368  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 10:36:12.958   747  3322 D SSRM:n  : SIOP:: AP = 320, PST = 368, CUR = 300, LCD = 0
,06-30 10:36:16.628   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:17.928   747  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:17.938   747  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:36:17.938   747  1764 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:36:17.938   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:17.948   747   747 I MotionRecognitionService: Plugged
,06-30 10:36:17.948   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:36:17.958   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:36:17.958   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:36:17.958   747  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:36:17.968   747  1764 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 747) 
,06-30 10:36:17.968   747  1764 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,06-30 10:36:17.978  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:17.978  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:17.978  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:17.978  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:36:17.998   747  1764 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 10:36:18.018  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:18.018   747  1764 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 10:36:18.018  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:18.028  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:18.038   747  1764 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 10:36:18.038   747  1764 D BatteryService: turn on LED for fully charged
,06-30 10:36:18.238   747  1219 E LightSensor: RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,06-30 10:36:18.238   747   898 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 10:36:18.248   747   898 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 10:36:18.258   747   898 D SensorManager: unregisterListener ::   
,06-30 10:36:18.258   747   898 D lights  : led_pattern : 5 +
,06-30 10:36:18.268   747   898 D lights  : led_pattern : 5 -
,06-30 10:36:18.268   747   898 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,06-30 10:36:18.278   747   898 V AlarmManager:  remove PendingIntent] PendingIntent{259d06a: PendingIntentRecord{9ba395b android broadcastIntent}}
,06-30 10:36:23.028   747  3322 D SSRM:n  : SIOP:: AP = 310, PST = 351, CUR = 300, LCD = 0
,06-30 10:36:23.888  1630  3102 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:36:28.378   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:36:28.438   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b1d8d u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f342f7c 1630:com.google.android.gms.persistent/u0a12}
,06-30 10:36:28.458   747  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:28.458   747  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:36:28.468   747  1623 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:36:28.468   747  1623 D BatteryService: stay LED for fully charged
,06-30 10:36:28.468   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:28.498   747  1764 V AlarmManager:  remove PendingIntent] PendingIntent{dfc9890: PendingIntentRecord{d30f336 com.google.android.gms broadcastIntent}}
,06-30 10:36:28.508  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:28.508  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:36:28.508  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:28.538  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:28.538  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:28.538  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:28.538  6211  6211 E Zygote  : v2
,06-30 10:36:28.548   747  1236 I ActivityManager: Start proc 6211:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 10:36:28.548  6211  6211 I libpersona: KNOX_SDCARD checking this for 1000
,06-30 10:36:28.548  6211  6211 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:28.548  6211  6211 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:36:28.548  6211  6211 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:36:28.558  6211  6211 E Zygote  : accessInfo : 0
,06-30 10:36:28.558   747   747 I MotionRecognitionService: Plugged
,06-30 10:36:28.558   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:36:28.558   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:36:28.558   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:36:28.568   747  1642 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 10:36:28.568   747  1642 V AlarmManager:  remove PendingIntent] PendingIntent{3143ab5: PendingIntentRecord{67e554a android broadcastIntent}}
,06-30 10:36:28.568   747  1572 E Watchdog: !@Sync 5 [06-30 10:36:28.583]
,06-30 10:36:28.628  6211  6211 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:36:28.628  6211  6211 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:28.658  6211  6211 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,06-30 10:36:28.668  6211  6211 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,06-30 10:36:28.798   747   756 I art     : Background partial concurrent mark sweep GC freed 55812(3MB) AllocSpace objects, 56(1120KB) LOS objects, 27% free, 41MB/57MB, paused 4.893ms total 212.029ms
,06-30 10:36:28.838   747  3323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 10:36:28.848   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a162f9 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f98eab 5580:com.samsung.android.sm.provider/1000}
,06-30 10:36:28.938   747  3323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 10:36:28.948   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e29789f u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f98eab 5580:com.samsung.android.sm.provider/1000}
,06-30 10:36:29.018  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:29.038  1630  1630 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=20a7a72d-31a5-43fd-8c6e-0904e851d241
,06-30 10:36:29.038  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:29.048  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:29.078  1630  2623 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:36:29.078  1630  2623 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:36:29.078  1630  2623 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:36:29.078  1630  2623 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:36:29.078  1630  2623 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:36:29.078  1630  2623 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:36:29.118  5306  5306 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:36:29.118  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:36:29.118  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 10:36:29.198  1630  2124 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 10:36:29.198  1943  6237 D UdcContextInitService: registered all accounts: true
,06-30 10:36:29.218  1630  6241 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 10:36:29.308   747  1765 V AlarmManager:  remove PendingIntent] PendingIntent{7ad738: PendingIntentRecord{d30f336 com.google.android.gms broadcastIntent}}
,06-30 10:36:29.318  1630  6241 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10012, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 10:36:29.388   747  1622 I ActivityManager: Killing 4903:com.sec.android.app.music:service/u0a44 (adj 15): DHA:empty #37
,06-30 10:36:29.398  1630  1630 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 10:36:29.398  1630  6254 I VacuumService: Vacuum at: now=1467275789412 tag=VacuumService
,06-30 10:36:29.448   747   761 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,06-30 10:36:29.498   747  1757 V AlarmManager:  remove PendingIntent] PendingIntent{d260c76: PendingIntentRecord{d30f336 com.google.android.gms broadcastIntent}}
,06-30 10:36:33.088   747  3322 D SSRM:n  : SIOP:: AP = 320, PST = 341, CUR = 300, LCD = 0
,06-30 10:36:36.638   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:38.538   747  1765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:43.138   747  3322 D SSRM:n  : SIOP:: AP = 310, PST = 331, CUR = 300, LCD = 0
,06-30 10:36:49.128   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:36:49.198   747  1619 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:36:49.198   747  1619 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 10:36:49.198   747  1619 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
06-30 10:36:49.208   747  1619 D BatteryService: stay LED for fully charged
,06-30 10:36:49.208   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:49.208   747   747 I MotionRecognitionService: Plugged
,06-30 10:36:49.218   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:36:49.218   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:36:49.218   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:36:49.218  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:36:49.218  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:49.218  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:49.238  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:49.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:36:49.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:49.508  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:49.518  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:49.518  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:49.538  1630  1644 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:36:49.538  1630  1644 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:36:49.538  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:36:49.538  1630  1644 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:36:49.538  1630  1644 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:36:49.538  1630  1644 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:36:49.558  5306  5306 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 10:36:49.558  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:36:49.558  5306  5306 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 10:36:53.198   747  3322 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 300, LCD = 0
,06-30 10:36:56.638   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:58.588   747  1572 E Watchdog: !@Sync 6 [06-30 10:36:58.595]
,06-30 10:36:59.718  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:36:59.918  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 196ms lastUpdatedAfter : 125636ms
,06-30 10:36:59.998   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:37:00.078   747  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:00.078   747  1412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:37:00.088   747  1412 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:37:00.088   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:00.098   747   747 I MotionRecognitionService: Plugged
,06-30 10:37:00.098   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:37:00.098   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:37:00.108   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:00.108   747  1412 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:37:00.108   747  1412 D BatteryService: stay LED for fully charged
,06-30 10:37:00.128  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:00.128  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:00.128  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:00.148  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:00.148  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:00.148  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:03.258   747  3322 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 300, LCD = 0
,06-30 10:37:10.158   747  1711 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:10.168   747  1711 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:37:10.168   747  1711 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:37:10.168   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:10.178   747   747 I MotionRecognitionService: Plugged
,06-30 10:37:10.188   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:37:10.188   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:37:10.188   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:10.188   747  1711 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:37:10.198   747  1711 D BatteryService: stay LED for fully charged
,06-30 10:37:10.208  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:10.208  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:10.218  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:10.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:10.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:10.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:13.318   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 316, CUR = 300, LCD = 0
,06-30 10:37:16.648   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:20.248   747  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:20.248   747  1757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:37:20.248   747  1757 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:37:20.248   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:20.268   747   747 I MotionRecognitionService: Plugged
,06-30 10:37:20.268   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:37:20.268   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:37:20.268   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:20.278   747  1757 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
06-30 10:37:20.278   747  1757 D BatteryService: stay LED for fully charged
,06-30 10:37:20.278  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:20.278  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:20.278  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:20.308  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:20.308  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:20.308  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:23.378   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 313, CUR = 300, LCD = 0
,06-30 10:37:28.568   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:37:28.588   747  1572 E Watchdog: !@Sync 7 [06-30 10:37:28.601]
,06-30 10:37:29.488  1630  6241 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:37:29.488  1630  6241 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:37:29.488  1630  6241 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 10:37:29.488  1630  6241 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 10:37:29.488  1630  6241 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 10:37:29.498  1630  6241 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 10:37:30.328   747  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:30.338   747  1321 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:37:30.338   747  1321 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:37:30.338   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:30.348   747   747 I MotionRecognitionService: Plugged
,06-30 10:37:30.358   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:37:30.358   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:37:30.358   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:30.358   747  1321 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:37:30.368   747  1321 D BatteryService: stay LED for fully charged
,06-30 10:37:30.378  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:30.378  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:30.378  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:30.398  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:30.398  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:30.398  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:33.438   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 310, CUR = 300, LCD = 0
,06-30 10:37:36.648   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:40.408   747  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:43.488   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,06-30 10:37:50.498   747  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:37:50.498   747  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:37:50.498   747  1764 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:37:50.508   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:50.518   747   747 I MotionRecognitionService: Plugged
,06-30 10:37:50.518   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:37:50.518   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:37:50.518   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:50.528   747  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:37:50.528   747  1764 D BatteryService: stay LED for fully charged
,06-30 10:37:50.528  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:50.528  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:37:50.528  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:50.558  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:50.558  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:50.558  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:53.548   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,06-30 10:37:56.658   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:58.598   747  1572 E Watchdog: !@Sync 8 [06-30 10:37:58.605]
,06-30 10:37:59.928  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:38:00.588   747  1619 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:00.588   747  1619 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:38:00.588   747  1619 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:38:00.588   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:00.608   747   747 I MotionRecognitionService: Plugged
,06-30 10:38:00.608   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:38:00.608   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:38:00.608   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:00.608   747  1619 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:38:00.618   747  1619 D BatteryService: stay LED for fully charged
,06-30 10:38:00.628  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:00.628  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:00.628  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:00.648  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:00.648  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:00.648  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:03.608   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,06-30 10:38:10.668   747  2278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:10.678   747  2278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:38:10.678   747  2278 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:38:10.678   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:10.688   747   747 I MotionRecognitionService: Plugged
,06-30 10:38:10.688   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:38:10.698   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:38:10.698   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:10.698   747  2278 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:38:10.708   747  2278 D BatteryService: stay LED for fully charged
,06-30 10:38:10.718  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:10.718  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:10.718  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:10.748  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:10.748  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:10.748  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:13.668   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,06-30 10:38:16.658   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:20.758   747   760 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:23.718   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,06-30 10:38:28.598   747  1572 E Watchdog: !@Sync 9 [06-30 10:38:28.610]
,06-30 10:38:30.838   747   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:33.788   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,06-30 10:38:36.658   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:40.928   747  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:43.388   747  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:38:43.398   747  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:38:43.398   747  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:38:43.408   747  1230 I TLC_TIMA_PKM_initialize: initializing...
,06-30 10:38:43.408   747  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 10:38:43.408   747  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,06-30 10:38:43.418   747  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 10:38:43.418   747  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 10:38:43.418   747  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,06-30 10:38:43.418   747  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 10:38:43.418   747  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 10:38:43.428   747  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 10:38:43.428   747  1230 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 10:38:43.488   747  1230 D QSEECOMAPI: : Loaded image: APP id = 3
,06-30 10:38:43.508   747  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 10:38:43.528   747  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 10:38:43.868   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 10:38:46.558   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:38:46.558   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:38:46.568   747  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:46.578   747  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:51.038   747   760 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:51.038   747   760 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:38:51.048   747   760 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:38:51.048   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:51.058   747   747 I MotionRecognitionService: Plugged
,06-30 10:38:51.058   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:38:51.058   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:38:51.068   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:51.068   747   760 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:38:51.068   747   760 D BatteryService: stay LED for fully charged
,06-30 10:38:51.078  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:51.078  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:51.078  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:51.098  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:51.098  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:51.098  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:53.928   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 10:38:56.668   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:58.608   747  1572 E Watchdog: !@Sync 10 [06-30 10:38:58.615]
,06-30 10:38:59.958  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:39:04.028   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 10:39:14.088   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 10:39:16.668   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:21.108   747  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:21.118   747  1757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:39:21.118   747  1757 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:39:21.118   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:21.128   747   747 I MotionRecognitionService: Plugged
,06-30 10:39:21.128   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:39:21.138   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:39:21.138   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:39:21.138   747  1757 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:39:21.138   747  1757 D BatteryService: stay LED for fully charged
,06-30 10:39:21.158  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:21.158  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:21.168  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:21.198  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:21.198  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:21.198  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:24.138   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 10:39:28.608   747  1572 E Watchdog: !@Sync 11 [06-30 10:39:28.619]
,06-30 10:39:29.238  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:29.278  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:29.278  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:29.308  1630  1644 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:39:29.308  1630  1644 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:39:29.308  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:39:29.308  1630  1644 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:39:29.308  1630  1644 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:39:29.308  1630  1644 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:29.338  1630  1644 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:39:29.338  1630  1644 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:39:29.338  1630  1644 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:39:29.338  1630  1644 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:39:29.338  1630  1644 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:39:29.338  1630  1644 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:39:29.338  1630  1644 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:29.338  5306  5348 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:39:29.338  5306  5348 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:39:29.338  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:39:29.338  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:39:29.338  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:39:29.338  5306  5348 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:39:29.338  5306  5348 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:29.378  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:39:29.378  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:39:29.388   306  1154 D EnterpriseController: netId is 0
06-30 10:39:29.388   306  1154 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 10:39:34.198   747  3322 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,06-30 10:39:36.668   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:44.248   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,06-30 10:39:51.188   747  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:51.188   747  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:39:51.188   747  1703 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:39:51.198   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:51.208   747   747 I MotionRecognitionService: Plugged
,06-30 10:39:51.208   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:39:51.208   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:39:51.208   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:39:51.218   747  1703 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:39:51.218   747  1703 D BatteryService: stay LED for fully charged
,06-30 10:39:51.228  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:51.228  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:39:51.228  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:51.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:51.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:51.248  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:54.308   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,06-30 10:39:56.678   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:58.618   747  1572 E Watchdog: !@Sync 12 [06-30 10:39:58.623]
,06-30 10:40:00.008   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:40:00.008   747  1236 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=392266 batch.start=432781
,06-30 10:40:00.028  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:40:00.028  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 10:40:00.028  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:40:00.078   747  1642 D NtpTrustedTime: forceRefresh: no connectivity
,06-30 10:40:00.078   747  1642 V AlarmManager:  remove PendingIntent] PendingIntent{3143ab5: PendingIntentRecord{67e554a android broadcastIntent}}
,06-30 10:40:00.088  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:40:00.098  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:40:00.098  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.108  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.108  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.108  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.118   747  1642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 10:40:00.128  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.128  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.138  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.148  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:40:00.198  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:40:00.288  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 89ms lastUpdatedAfter : 180362ms
,06-30 10:40:04.368   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,06-30 10:40:14.418   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,06-30 10:40:16.678   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:21.268   747  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:21.268   747  1412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:40:21.268   747  1412 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:40:21.278   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:21.288   747   747 I MotionRecognitionService: Plugged
,06-30 10:40:21.288   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:40:21.288   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:40:21.288   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:21.298   747  1412 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:40:21.298   747  1412 D BatteryService: stay LED for fully charged
,06-30 10:40:21.308  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:21.318  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:21.318  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:21.348  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:21.348  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:21.358  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:24.478   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,06-30 10:40:28.618   747  1572 E Watchdog: !@Sync 13 [06-30 10:40:28.630]
,06-30 10:40:34.538   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,06-30 10:40:36.688   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:40.518   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:40:40.598   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37b7857 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{62f7f94 1943:com.google.android.gms/u0a12}
,06-30 10:40:40.658  1943  6324 I EventLogService: Aggregate from 1467274239654 (log), 1467274239654 (data)
,06-30 10:40:40.898   747   821 I ActivityManager: Start proc 6331:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,06-30 10:40:40.908  6331  6331 E Zygote  : v2
,06-30 10:40:40.908  6331  6331 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:40:40.908  6331  6331 I libpersona: KNOX_SDCARD not a persona
,06-30 10:40:40.918  6331  6331 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:40:40.918  6331  6331 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:40:40.928  6331  6331 E Zygote  : accessInfo : 0
,06-30 10:40:41.008  6331  6331 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:40:41.008  6331  6331 D ActivityThread: Added TimaKeyStore provider
,06-30 10:40:41.028   747  1705 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a5bbb0 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae0ba29 6331:com.samsung.android.sm/1000}
,06-30 10:40:41.038  6331  6331 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,06-30 10:40:41.098   747  1765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f1df1ae u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae0ba29 6331:com.samsung.android.sm/1000}
,06-30 10:40:41.108   747  1765 I ActivityManager: Killing 3712:com.google.android.talk/u0a117 (adj 15): DHA:empty #37
,06-30 10:40:41.198   747   760 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,06-30 10:40:44.598   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,06-30 10:40:51.348   747  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:51.348   747  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:40:51.358   747  1737 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:40:51.358   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:51.368   747   747 I MotionRecognitionService: Plugged
,06-30 10:40:51.368   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:40:51.368   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:40:51.368   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:51.378   747  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:40:51.378   747  1737 D BatteryService: stay LED for fully charged
,06-30 10:40:51.388  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:51.388  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:40:51.388  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:51.408  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:51.408  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:40:51.418  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:54.658   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,06-30 10:40:56.688   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:58.628   747  1572 E Watchdog: !@Sync 14 [06-30 10:40:58.635]
,06-30 10:40:59.988   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:41:00.288  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:41:04.718   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,06-30 10:41:14.768   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:41:16.688   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:21.428   747  1711 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:24.828   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:41:28.628   747  1572 E Watchdog: !@Sync 15 [06-30 10:41:28.638]
,06-30 10:41:33.258   370   370 I bootchecker: bootchecker wake up!!
,06-30 10:41:34.888   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:41:36.698   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:44.938   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:41:51.508   747  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:51.508   747  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:41:51.518   747  1737 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:41:51.518   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:41:51.528   747   747 I MotionRecognitionService: Plugged
,06-30 10:41:51.528   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:41:51.538   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:41:51.538   747  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:41:51.538   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:41:51.538   747  1737 D BatteryService: stay LED for fully charged
,06-30 10:41:51.548  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:51.548  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:51.558  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:51.588  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:51.588  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:51.588  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:54.998   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:41:56.698   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:58.638   747  1572 E Watchdog: !@Sync 16 [06-30 10:41:58.642]
,06-30 10:42:00.408  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:42:05.048   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:42:15.108   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:42:16.708   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:21.588   747  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:25.158   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:42:28.638   747  1572 E Watchdog: !@Sync 17 [06-30 10:42:28.648]
,06-30 10:42:35.218   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:42:36.708   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:45.268   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:42:51.668   747  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:51.668   747  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:42:51.678   747  1737 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:42:51.678   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:42:51.688   747   747 I MotionRecognitionService: Plugged
,06-30 10:42:51.688   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:42:51.698   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:42:51.698   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:42:51.698   747  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:42:51.698   747  1737 D BatteryService: stay LED for fully charged
,06-30 10:42:51.718  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:51.718  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:51.718  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:51.758  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:51.758  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:51.758  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:55.328   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:42:56.708   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:58.648   747  1572 E Watchdog: !@Sync 18 [06-30 10:42:58.653]
,06-30 10:43:00.428  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:43:00.658  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 214ms lastUpdatedAfter : 180372ms
,06-30 10:43:05.378   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:43:15.428   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:43:16.718   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:21.748   747  1619 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:25.488   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:43:28.648   747  1572 E Watchdog: !@Sync 19 [06-30 10:43:28.660]
,06-30 10:43:35.538   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:43:36.718   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:43.388   747  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:43:43.388   747  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:43:43.388   747  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:43:44.718   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:43:44.728   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:43:44.738   747  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:44.738   747  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:45.598   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:43:51.828   747  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:51.828   747  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:43:51.838   747  1737 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:43:51.838   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:43:51.848   747   747 I MotionRecognitionService: Plugged
,06-30 10:43:51.848   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:43:51.848   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:43:51.858   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:43:51.858   747  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:43:51.858   747  1737 D BatteryService: stay LED for fully charged
,06-30 10:43:51.878  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:51.878  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:51.878  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:51.908  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:51.908  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:51.908  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:55.648   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:43:56.728   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:58.658   747  1572 E Watchdog: !@Sync 20 [06-30 10:43:58.665]
,06-30 10:44:00.678  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.278   747   814 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10051, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10058, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10076, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.288   747   814 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10084, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10088, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10092, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10096, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10103, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.298   747   814 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10138, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10141, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10143, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10173, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10175, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.308   747   814 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10207, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10211, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10212, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10213, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.318   747   814 D NetworkPolicy: isUidForegroundLocked: 10221, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.368   747   874 I ActivityManager: setMaxStartingBackgroundTimer onfinish
06-30 10:44:02.368   747   874 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 10:44:05.698   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:44:15.758   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:44:16.728   747  3344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:44:21.908   747  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:21.918   747  1757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:44:21.918   747  1757 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:44:21.918   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:21.928   747   747 I MotionRecognitionService: Plugged
,06-30 10:44:21.938   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:44:21.938   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:44:21.938   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:44:21.938   747  1757 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:44:21.938   747  1757 D BatteryService: stay LED for fully charged
,06-30 10:44:21.948  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:21.958  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:21.958  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:21.988  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:21.988  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:21.988  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:25.808   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:44:28.658   747  1572 E Watchdog: !@Sync 21 [06-30 10:44:28.670]
,06-30 10:44:29.408   747  1623 I ActivityManager: Killing 4257:com.sec.spp.push/u0a38 (adj 8): SSR - service for lastStateTime 612s, lastActivityTime 602s
,06-30 10:44:29.418   747  1623 I ActivityManager: Killing 3928:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 614s, lastActivityTime 614s
,06-30 10:44:29.428   747  1623 I ActivityManager: Killing 3629:com.sec.android.pagebuddynotisvc/u0a27 (adj 8): SSR - service for lastStateTime 616s, lastActivityTime 616s
,06-30 10:44:29.458  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:29.518  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:29.528  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:29.558  1630  1644 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:44:29.558  1630  1644 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:44:29.558  1630  1644 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:44:29.558  1630  1644 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:44:29.558  1630  1644 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:44:29.558  1630  1644 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:29.578   292   292 I ServiceManager: service 'AtCmdFwd' died
,06-30 10:44:29.578   375  4793 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 10:44:29.578  1630  1644 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:44:29.578  1630  1644 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:44:29.578  1630  1644 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:44:29.578  1630  1644 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:44:29.578  1630  1644 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:44:29.578  1630  1644 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:44:29.578  1630  1644 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:29.588   375  4793 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:44:29.588   747  1757 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 10:44:29.588   747  1757 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 10:44:29.588   747  1757 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 10:44:29.608  5306  5348 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:44:29.608  5306  5348 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:44:29.608  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:44:29.608  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:44:29.608  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:44:29.608  5306  5348 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:44:29.608  5306  5348 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
06-30 10:44:29.608  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:44:29.608  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:44:29.608   306  1154 D EnterpriseController: netId is 0
06-30 10:44:29.608   306  1154 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 10:44:29.628   747  1321 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
06-30 10:44:29.628   747  1321 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,06-30 10:44:29.648   747   760 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 10:44:29.648   747   760 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 10:44:29.648   747   760 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10937ms
,06-30 10:44:30.588   375  4793 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:44:30.668  6403  6403 E Zygote  : v2
,06-30 10:44:30.668  6403  6403 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:44:30.668  6403  6403 I libpersona: KNOX_SDCARD not a persona
,06-30 10:44:30.668   747   821 I ActivityManager: Start proc 6403:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 10:44:30.678  6403  6403 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:44:30.678  6403  6403 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:44:30.678  6403  6403 E Zygote  : accessInfo : 0
,06-30 10:44:30.718  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:44:30.718  6403  6403 D ActivityThread: Added TimaKeyStore provider
,06-30 10:44:30.738  6403  6403 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 10:44:30.758  6403  6403 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 10:44:30.758  6403  6403 D AtFwdService: onCreate method
,06-30 10:44:30.758  6403  6403 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 10:44:30.778  6403  6415 D AtCkpdCmdHandler: De-queing command
,06-30 10:44:32.118   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:44:35.908   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:44:40.668   747   821 I ActivityManager: Start proc 6418:com.sec.android.pagebuddynotisvc/u0a27 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 10:44:40.678  6418  6418 E Zygote  : v2
,06-30 10:44:40.678  6418  6418 I libpersona: KNOX_SDCARD checking this for 10027
,06-30 10:44:40.678  6418  6418 I libpersona: KNOX_SDCARD not a persona
,06-30 10:44:40.678  6418  6418 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:44:40.678  6418  6418 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:44:40.678  6418  6418 E Zygote  : accessInfo : 0
,06-30 10:44:40.678  6418  6418 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 10:44:40.728  6418  6418 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:44:40.728  6418  6418 D ActivityThread: Added TimaKeyStore provider
,06-30 10:44:40.738   747   761 I ActivityManager: Killing 1513:com.sec.android.daemonapp/u0a182 (adj 8): SSR - service for lastStateTime 615s, lastActivityTime 608s
,06-30 10:44:40.758  6418  6418 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 10:44:40.768   747  1412 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,06-30 10:44:40.768   747  1412 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 10:44:40.768   747  1412 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,06-30 10:44:40.798  6418  6418 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 10:44:40.818  6418  6418 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 10:44:40.818  6418  6418 D ContextualPageNotification: resetAllNotification : all clear!!!
,06-30 10:44:41.828   747   821 I ActivityManager: Start proc 6440:com.sec.android.daemonapp/u0a182 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,06-30 10:44:41.828   747  1324 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 10:44:41.848  6440  6440 E Zygote  : v2
,06-30 10:44:41.858  6440  6440 I libpersona: KNOX_SDCARD checking this for 10182
,06-30 10:44:41.858  6440  6440 I libpersona: KNOX_SDCARD not a persona
,06-30 10:44:41.858  6440  6440 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:44:41.858  6440  6440 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:44:41.868  6440  6440 E Zygote  : accessInfo : 0
,06-30 10:44:41.868  6440  6440 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,06-30 10:44:41.918  6440  6440 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:44:41.918  6440  6440 D ActivityThread: Added TimaKeyStore provider
,06-30 10:44:41.928   747  1764 I ActivityManager: Killing 5667:com.samsung.android.sdk.samsunglink/u0a42 (adj 8): SSR - service for lastStateTime 600s, lastActivityTime 600s
,06-30 10:44:41.938   747  1324 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:44:41.958  6440  6440 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,06-30 10:44:41.978   747  1757 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,06-30 10:44:41.978   747  1757 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,06-30 10:44:41.988  6440  6440 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,06-30 10:44:42.018  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,06-30 10:44:42.028  6440  6440 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:44:42.038   747   821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e8066a u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebb375b 6440:com.sec.android.daemonapp/u0a182}
,06-30 10:44:42.038  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,06-30 10:44:42.038  6440  6440 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:44:42.048  6440  6440 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,06-30 10:44:42.048  6440  6440 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:44:42.048  6440  6440 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,06-30 10:44:42.048  6440  6440 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:44:42.068  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:44:42.068  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 10:44:42.078  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,06-30 10:44:42.078  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:44:42.078  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:44:42.078  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,06-30 10:44:42.088  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 10:44:42.118  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,06-30 10:44:42.118  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:44:42.118  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:44:42.118  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,06-30 10:44:42.128  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 10:44:42.128  6440  6440 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:44:42.138  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:44:42.138  6440  6440 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:44:42.138  6440  6440 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:44:42.138  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:44:42.138  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:44:42.138  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 10:44:42.138  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:44:42.138  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 10:44:42.148  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:44:42.148  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.148  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:44:42.158   747  1703 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76bee37 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebb375b 6440:com.sec.android.daemonapp/u0a182}
,06-30 10:44:42.168  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:44:42.178  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 10:44:42.178  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:44:42.178  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.178  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:44:42.188  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:44:42.188  6440  6440 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 10:44:42.188  6440  6440 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:44:42.188  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.188  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:44:42.198   747  1321 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1135fa4 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebb375b 6440:com.sec.android.daemonapp/u0a182}
,06-30 10:44:42.198  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:44:42.198  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:44:42.198  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:44:42.208  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.208  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:44:42.208  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:44:42.208  6440  6440 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:44:42.208  6440  6440 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:44:42.208  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:44:42.208  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:44:42.218  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:44:42.218  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,06-30 10:44:42.218  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 10:44:42.218  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 10:44:42.218  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.218  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:44:42.228   747   761 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{93be10d u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebb375b 6440:com.sec.android.daemonapp/u0a182}
,06-30 10:44:42.238  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:44:42.238  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:44:42.238  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:44:42.238  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:44:42.248  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:44:42.248  6440  6440 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:44:42.248  6440  6440 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:44:42.248  6440  6440 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:44:42.248  6440  6440 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:44:42.258  6440  6440 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:44:45.978   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:44:51.988   747  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:56.028   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:44:58.668   747  1572 E Watchdog: !@Sync 22 [06-30 10:44:58.674]
,06-30 10:45:00.788  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:45:06.108   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:45:16.158   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:45:22.068   747   760 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:22.068   747   760 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:45:22.078   747   760 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:45:22.078   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:22.088   747   747 I MotionRecognitionService: Plugged
,06-30 10:45:22.088   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:45:22.098   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:45:22.098   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:45:22.098   747   760 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:45:22.098   747   760 D BatteryService: stay LED for fully charged
,06-30 10:45:22.118  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:22.118  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:45:22.118  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:22.138  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:22.138  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:45:22.138  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:26.228   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:45:28.668   747  1572 E Watchdog: !@Sync 23 [06-30 10:45:28.678]
,06-30 10:45:36.288   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:45:46.338   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:45:52.148   747  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:52.148   747  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:45:52.158   747  1764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:45:52.158   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:52.168   747   747 I MotionRecognitionService: Plugged
,06-30 10:45:52.168   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:45:52.168   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:45:52.178   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:45:52.178   747  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:45:52.178   747  1764 D BatteryService: stay LED for fully charged
,06-30 10:45:52.198  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:52.198  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:52.198  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:52.228  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:52.238  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:45:52.238  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:56.388   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:45:58.678   747  1572 E Watchdog: !@Sync 24 [06-30 10:45:58.682]
,06-30 10:46:00.818  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:46:00.978  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 153ms lastUpdatedAfter : 180321ms
,06-30 10:46:06.448   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:46:16.498   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:46:22.228   747  1765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:22.238   747  1765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:46:22.238   747  1765 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:46:22.238   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:22.248   747   747 I MotionRecognitionService: Plugged
,06-30 10:46:22.248   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:46:22.258   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:46:22.258   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:22.258   747  1765 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:46:22.268   747  1765 D BatteryService: stay LED for fully charged
,06-30 10:46:22.268  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:22.268  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:22.268  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:22.288  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:22.298  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:22.298  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:26.548   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:46:28.678   747  1572 E Watchdog: !@Sync 25 [06-30 10:46:28.687]
,06-30 10:46:29.588  1630  3102 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:46:36.608   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:46:46.658   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:46:52.308   747   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:52.308   747   761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:46:52.308   747   761 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:46:52.318   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:52.328   747   747 I MotionRecognitionService: Plugged
,06-30 10:46:52.328   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:46:52.328   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:46:52.338   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:52.338   747   761 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:46:52.338   747   761 D BatteryService: stay LED for fully charged
,06-30 10:46:52.358  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:52.358  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:52.358  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:52.388  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:52.388  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:52.388  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:56.708   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:46:58.678   747  1572 E Watchdog: !@Sync 26 [06-30 10:46:58.692]
,06-30 10:47:00.988  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:47:02.338   747  2296 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 10:47:02.338   747  2296 V MARsPolicyManager: updateSMDBValues
,06-30 10:47:02.348   747   871 E MARsDBManager: updateDBAll : begin --size 0
,06-30 10:47:02.348   747   871 E MARsDBManager: updateDBAll : end
,06-30 10:47:06.778   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:47:16.828   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:47:22.388   747  1711 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:26.888   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:47:28.688   747  1572 E Watchdog: !@Sync 27 [06-30 10:47:28.697]
,06-30 10:47:36.948   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:47:46.998   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:47:52.468   747   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:57.088   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:47:58.688   747  1572 E Watchdog: !@Sync 28 [06-30 10:47:58.702]
,06-30 10:48:01.008  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:48:07.148   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:48:17.198   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:48:22.548   747  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:22.548   747  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:48:22.558   747  1623 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:48:22.558   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:22.568   747   747 I MotionRecognitionService: Plugged
,06-30 10:48:22.568   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:48:22.568   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:48:22.578   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:48:22.578   747  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:48:22.578   747  1623 D BatteryService: stay LED for fully charged
,06-30 10:48:22.598  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:22.598  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:22.598  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:22.638  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:22.638  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:22.638  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:27.248   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:48:28.698   747  1572 E Watchdog: !@Sync 29 [06-30 10:48:28.709]
,06-30 10:48:37.308   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:48:43.388   747  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:48:43.388   747  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:48:43.388   747  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:48:46.458   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:48:46.458   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:48:46.468   747  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:48:46.468   747  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:48:47.358   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:48:52.628   747  1703 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:52.628   747  1703 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:48:52.638   747  1703 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:48:52.638   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:52.648   747   747 I MotionRecognitionService: Plugged
,06-30 10:48:52.648   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:48:52.648   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:48:52.658   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:48:52.658   747  1703 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:48:52.658   747  1703 D BatteryService: stay LED for fully charged
,06-30 10:48:52.668  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:52.668  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:52.668  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:52.688  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:52.698  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:52.698  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:57.408   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:48:58.708   747  1572 E Watchdog: !@Sync 30 [06-30 10:48:58.713]
,06-30 10:49:01.028  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:49:01.208  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 168ms lastUpdatedAfter : 180232ms
,06-30 10:49:07.508   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:49:07.638   747   756 I art     : Background sticky concurrent mark sweep GC freed 59754(7MB) AllocSpace objects, 380(7MB) LOS objects, 27% free, 41MB/57MB, paused 2.506ms total 155.454ms
,06-30 10:49:17.558   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:49:22.708   747   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:22.708   747   761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:49:22.718   747   761 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:49:22.718   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:22.728   747   747 I MotionRecognitionService: Plugged
,06-30 10:49:22.728   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:49:22.728   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:49:22.738   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:49:22.738   747   761 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:49:22.738   747   761 D BatteryService: stay LED for fully charged
,06-30 10:49:22.758  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:22.758  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:22.758  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:22.788  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:22.788  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:22.788  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:27.618   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:49:28.708   747  1572 E Watchdog: !@Sync 31 [06-30 10:49:28.720]
,06-30 10:49:29.648   747  1412 I ActivityManager: Killing 1880:com.sec.android.app.shealth:remote/u0a35 (adj 8): SSR - service for lastStateTime 929s, lastActivityTime 886s
,06-30 10:49:29.688  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.728  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.728  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.768  1630  3998 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:29.768  1630  3998 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:49:29.768  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:49:29.768  1630  3998 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:29.768  1630  3998 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:29.768  1630  3998 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.788  1630  3998 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:49:29.788  1630  3998 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:49:29.788  1630  3998 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:49:29.788  1630  3998 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:49:29.788  1630  3998 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:29.788  1630  3998 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:29.788  1630  3998 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.798  5306  5348 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:49:29.798  5306  5348 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:49:29.798  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:49:29.798  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:49:29.798  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:49:29.798  5306  5348 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:49:29.798  5306  5348 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.808  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:29.808  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:29.818   747  1705 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,06-30 10:49:29.818   747  1705 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 10:49:29.818   747  1705 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 1000ms
06-30 10:49:29.818   747  1705 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,06-30 10:49:29.818   747  1705 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10999ms
,06-30 10:49:29.828  5468  5468 D HealthConsole: Service for HealthDataStore is disconnected
,06-30 10:49:29.828   306  1154 D EnterpriseController: netId is 0
06-30 10:49:29.828   306  1154 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 10:49:29.868  6488  6488 E Zygote  : v2
06-30 10:49:29.868  6488  6488 I libpersona: KNOX_SDCARD checking this for 10035
06-30 10:49:29.868  6488  6488 I libpersona: KNOX_SDCARD not a persona
,06-30 10:49:29.868  6488  6488 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:49:29.868  6488  6488 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:49:29.868   747  1711 I ActivityManager: Start proc 6488:com.sec.android.app.shealth:remote/u0a35 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,06-30 10:49:29.868  6488  6488 E Zygote  : accessInfo : 0
,06-30 10:49:29.868  6488  6488 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,06-30 10:49:29.908  6488  6488 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:49:29.908  6488  6488 D ActivityThread: Added TimaKeyStore provider
,06-30 10:49:29.928  6488  6488 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,06-30 10:49:29.958  6488  6488 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,06-30 10:49:29.968  6488  6488 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 10:49:29.968  6488  6488 I MultiDex: install
06-30 10:49:29.968  6488  6488 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 10:49:29.968  6488  6488 I MultiDex: install
06-30 10:49:29.968  6488  6488 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:49:30.098   747  1705 I ActivityManager: Start proc 6504:com.sec.android.service.health/u0a17 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,06-30 10:49:30.108  6504  6504 E Zygote  : v2
06-30 10:49:30.108  6504  6504 I libpersona: KNOX_SDCARD checking this for 10017
06-30 10:49:30.108  6504  6504 I libpersona: KNOX_SDCARD not a persona
,06-30 10:49:30.108  6504  6504 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:49:30.108  6504  6504 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:49:30.108  6504  6504 E Zygote  : accessInfo : 0
,06-30 10:49:30.108  6504  6504 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,06-30 10:49:30.138  6504  6504 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:49:30.138  6504  6504 D ActivityThread: Added TimaKeyStore provider
,06-30 10:49:30.158  6504  6504 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,06-30 10:49:30.188  6488  6488 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 10:49:30.188  6488  6488 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 10:49:30.238  1383  1383 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,06-30 10:49:30.248   747  1623 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10035
,06-30 10:49:30.258   747  2278 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10035
,06-30 10:49:30.258   747  1412 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10035
,06-30 10:49:30.268  1383  1383 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{1119bac VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
06-30 10:49:30.268  1383  1383 D AdaptiveEventManager: M updateContainers()
06-30 10:49:30.268  1383  1383 D AdaptiveEventContainerSmall: C updatePedoContainer()
06-30 10:49:30.268  1383  1383 D AdaptiveEventContainerSmall: handlePedoUpdate()
,06-30 10:49:30.268  1383  1383 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,06-30 10:49:30.268   747  1622 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10035
,06-30 10:49:30.298  6488  6488 I Health.HealthService: HealthService: onCreate() start (6488)
,06-30 10:49:30.438  5468  5468 D HealthDataStore: Service for HealthDataStore is connected
,06-30 10:49:30.458  5468  5468 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 10:49:30.458   747  1412 I ActivityManager: Killing 5356:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,06-30 10:49:30.498  6488  6488 D HealthDataStore: Service for HealthDataStore is connected
06-30 10:49:30.498   747  1737 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,06-30 10:49:30.498  6488  6488 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 10:49:30.498  6488  6488 D HealthConsole: Service for HealthDataConsole is connected
,06-30 10:49:30.508  6488  6488 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 10:49:30.508  6488  6488 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 10:49:30.518  5468  5468 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 10:49:30.518  5468  5468 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 10:49:30.668  6488  6523 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,06-30 10:49:30.708  6488  6533 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,06-30 10:49:30.728  6504  6518 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 10:49:30.738   437   437 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 10017, gid 10017, pid 6504
06-30 10:49:30.738   437   437 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,06-30 10:49:30.898  6504  6518 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,06-30 10:49:31.008  6488  6533 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,06-30 10:49:31.138  6488  6533 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 10:49:31.138  6488  6533 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 10:49:31.358   437   437 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,06-30 10:49:31.408  6504  6518 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,06-30 10:49:31.408  6504  6518 I SecureStorage: [INFO]: SPID(0x00000007)Skip using SecureStorageExceptionJNI
,06-30 10:49:31.408  6504  6518 D HSCheck : SS_G-2d de 1c 15 c8 bf 9d d9 69 c1 84 f0 50 9f a4 42 
,06-30 10:49:37.698   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:49:47.748   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:49:52.788   747  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:52.798   747  1321 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:49:52.798   747  1321 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:49:52.798   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:52.808   747   747 I MotionRecognitionService: Plugged
,06-30 10:49:52.808   747   747 D MotionRecognitionService:   cableConnection= 1,
,06-30 10:49:52.818   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:49:52.818   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:49:52.818   747  1321 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:49:52.828   747  1321 D BatteryService: stay LED for fully charged
,06-30 10:49:52.838  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:52.838  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:52.838  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:52.868  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:52.868  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:52.868  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:57.828   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:49:58.718   747  1572 E Watchdog: !@Sync 32 [06-30 10:49:58.727]
,06-30 10:50:01.228  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:50:07.878   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:50:17.938   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:50:22.868   747   761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:22.878   747   761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:50:22.878   747   761 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:50:22.878   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:22.888   747   747 I MotionRecognitionService: Plugged
,06-30 10:50:22.888   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:50:22.888   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:50:22.898   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:22.898   747   761 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:50:22.898   747   761 D BatteryService: stay LED for fully charged
,06-30 10:50:22.918  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:22.918  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:22.918  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:22.938  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:22.938  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:22.938  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:27.988   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:50:28.718   747  1572 E Watchdog: !@Sync 33 [06-30 10:50:28.731]
,06-30 10:50:38.048   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:50:48.098   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:50:52.948   747  1765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:52.948   747  1765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:50:52.958   747  1765 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:50:52.958   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:52.968   747   747 I MotionRecognitionService: Plugged
,06-30 10:50:52.968   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:50:52.968   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:50:52.978   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:52.978   747  1765 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:50:52.978   747  1765 D BatteryService: stay LED for fully charged
,06-30 10:50:52.998  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:52.998  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:52.998  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:53.038  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:53.038  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:53.038  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:58.148   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:50:58.728   747  1572 E Watchdog: !@Sync 34 [06-30 10:50:58.736]
,06-30 10:51:01.308  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:51:08.208   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:51:18.268   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:51:19.698   747  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:51:19.798  6550  6550 E Zygote  : v2
,06-30 10:51:19.798  6550  6550 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:51:19.798  6550  6550 I libpersona: KNOX_SDCARD not a persona
,06-30 10:51:19.798  6550  6550 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:51:19.798  6550  6550 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:51:19.808  6550  6550 E Zygote  : accessInfo : 0
,06-30 10:51:19.808   747  1236 I ActivityManager: Start proc 6550:com.wssyncmldm/1000 for service com.wssyncmldm/com.samsung.android.app.fotaclient.device.PollingIntentService
,06-30 10:51:19.838  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:51:19.838  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 10:51:19.838  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:51:19.848   747   821 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,06-30 10:51:19.858  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:51:19.858  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:51:19.868  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.868  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 10:51:19.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.878  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.878  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.888   747   747 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 10:51:19.888   747   747 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 10:51:19.888   747   747 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 10:51:19.898   747   747 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 10:51:19.908  6550  6550 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:51:19.908  6550  6550 D ActivityThread: Added TimaKeyStore provider
,06-30 10:51:19.938  1820  6580 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,06-30 10:51:19.938  6550  6550 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,06-30 10:51:19.958  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:51:19.968  6550  6550 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
,06-30 10:51:20.008  1820  6556 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 10:51:20.008  6550  6550 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,06-30 10:51:20.088  1820  6556 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
06-30 10:51:20.088  1820  6556 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 10:51:20.098  1820  6556 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 10:51:20.098  1820  6556 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 10:51:20.108  6550  6550 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2021/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,06-30 10:51:20.128  1820  6556 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
06-30 10:51:20.128  1820  6556 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 10:51:20.198  6550  6550 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,06-30 10:51:20.208  6550  6550 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,06-30 10:51:20.208  6550  6550 I FOTA_AGENT: [llIIlIllIIIlllIlIlII(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,06-30 10:51:20.238  6550  6550 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3216/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,06-30 10:51:20.238  6550  6550 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3268/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,06-30 10:51:20.258   747  1219 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,06-30 10:51:20.258  6550  6550 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
06-30 10:51:20.258   747   898 D LightsService: [SvcLED]  onSensorChanged::light value = 0
06-30 10:51:20.258   747   898 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 10:51:20.268  6550  6592 I FOTA_AGENT: [com.samsung.android.app.fotaclient.device.PollingIntentService(19/onHandleIntent)] Polling State: Start to check polling
,06-30 10:51:20.268  6550  6592 I FOTA_AGENT: [IIllIIllIIIlllIlIIll(57/llIIIIlllllIIllIIllI)] Polling State: Check condition to update polling
,06-30 10:51:20.268   747   898 D SensorManager: unregisterListener ::   
06-30 10:51:20.268   747   898 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
06-30 10:51:20.268   747   898 V AlarmManager:  remove PendingIntent] PendingIntent{259d06a: PendingIntentRecord{9ba395b android broadcastIntent}}
,06-30 10:51:20.278  6550  6592 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(88/llIIIIlllllIIllIIllI)] Polling State: updating polling by current URL
,06-30 10:51:20.288   747  1412 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:51:20.288  6550  6592 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1049/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,06-30 10:51:20.298  6550  6592 W FOTA_AGENT: [lIlIIlIlIlIllllllIII(37/llIIIIlllllIIllIIllI)] NetworkInfo is null
,06-30 10:51:20.298  6550  6592 W FOTA_AGENT: [com.samsung.android.fem.network.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Fail to set up!
,06-30 10:51:20.298  6550  6592 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(137/llIIIIlllllIIllIIllI)] Receive result: fail in PollingRestClient
,06-30 10:51:20.298  6550  6592 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(139/llIIIIlllllIIllIIllI)] Network is not available. Wait next repeat time
,06-30 10:51:20.308  6550  6592 I FOTA_AGENT: [com.samsung.android.app.fotaclient.device.PollingIntentService(25/onHandleIntent)] Polling State: Finish to check polling
,06-30 10:51:20.328  1943  5325 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-30 10:51:21.228  1820  6556 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 10:51:21.308  1943  5318 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 10:51:21.328  1943  5326 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:51:21.368  1943  3888 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:51:21.398  1943  5325 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:51:21.418  1820  6556 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,06-30 10:51:23.028   747  2278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:23.038   747  2278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:51:23.038   747  2278 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:51:23.038   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:23.048   747   747 I MotionRecognitionService: Plugged
,06-30 10:51:23.058   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:51:23.058   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:51:23.058   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:51:23.058   747  2278 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:51:23.068   747  2278 D BatteryService: stay LED for fully charged
,06-30 10:51:23.078  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:23.078  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:23.088  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:23.108  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:23.108  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:23.108  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:26.458   747  1764 I ActivityManager: Killing 5368:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): DHA:empty #37
,06-30 10:51:26.508   747  1737 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,06-30 10:51:28.328   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:51:28.728   747  1572 E Watchdog: !@Sync 35 [06-30 10:51:28.741]
,06-30 10:51:38.378   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:51:48.468   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:51:53.108   747  2278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:53.108   747  2278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:51:53.118   747  2278 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:51:53.118   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:53.128   747   747 I MotionRecognitionService: Plugged
,06-30 10:51:53.128   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:51:53.128   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:51:53.138   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:51:53.138   747  2278 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:51:53.138   747  2278 D BatteryService: stay LED for fully charged
,06-30 10:51:53.148  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:53.148  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:53.148  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:53.188  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:53.188  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:53.188  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:58.518   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:51:58.738   747  1572 E Watchdog: !@Sync 36 [06-30 10:51:58.745]
,06-30 10:51:59.988   747  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:52:01.328  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:52:08.578   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:52:18.628   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:52:23.188   747  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:28.678   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:52:28.738   747  1572 E Watchdog: !@Sync 37 [06-30 10:52:28.749]
,06-30 10:52:38.738   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:52:48.828   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:52:53.268   747  2278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:53.268   747  2278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:52:53.278   747  2278 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:52:53.278   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:52:53.288   747   747 I MotionRecognitionService: Plugged
,06-30 10:52:53.288   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:52:53.298   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:52:53.298   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:52:53.298   747  2278 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:52:53.308   747  2278 D BatteryService: stay LED for fully charged
,06-30 10:52:53.318  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:53.318  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:53.318  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:53.358  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:53.358  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:53.358  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:58.748   747  1572 E Watchdog: !@Sync 38 [06-30 10:52:58.753]
,06-30 10:52:58.878   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:53:01.378  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:53:08.928   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:53:18.998   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:53:23.348   747  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:23.348   747  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:53:23.358   747  1764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:53:23.358   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:53:23.368   747   747 I MotionRecognitionService: Plugged
,06-30 10:53:23.368   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:53:23.368   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:53:23.378   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:23.378   747  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:53:23.378   747  1764 D BatteryService: stay LED for fully charged
,06-30 10:53:23.388  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:23.388  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:23.388  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:23.408  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:23.418  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:23.418  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:28.748   747  1572 E Watchdog: !@Sync 39 [06-30 10:53:28.759]
,06-30 10:53:29.048   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:53:39.108   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:53:43.388   747  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:53:43.388   747  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:53:43.388   747  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:53:44.738   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:53:44.738   747  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:53:44.748   747  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:44.748   747  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:49.158   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:53:53.428   747  1737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:53.438   747  1737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:53:53.438   747  1737 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:53:53.438   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:53:53.448   747   747 I MotionRecognitionService: Plugged
,06-30 10:53:53.448   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:53:53.458   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:53:53.458   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:53.458   747  1737 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:53:53.468   747  1737 D BatteryService: stay LED for fully charged
,06-30 10:53:53.478  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:53.478  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:53.478  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:53.508  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:53.508  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:53.508  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:55.408   747   814 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:53:58.758   747  1572 E Watchdog: !@Sync 40 [06-30 10:53:58.763]
,06-30 10:53:59.218   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:54:01.408  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:54:01.588  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 170ms lastUpdatedAfter : 161459ms
,06-30 10:54:09.268   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:54:19.328   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:54:23.508   747  1623 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:23.508   747  1623 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:54:23.508   747  1623 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:54:23.518   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:23.528   747   747 I MotionRecognitionService: Plugged
,06-30 10:54:23.528   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:54:23.528   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:54:23.528   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:54:23.538   747  1623 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:54:23.538   747  1623 D BatteryService: stay LED for fully charged
,06-30 10:54:23.548  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:23.548  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:23.558  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:23.588  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:23.588  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:54:23.588  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:28.758   747  1572 E Watchdog: !@Sync 41 [06-30 10:54:28.771]
,06-30 10:54:29.378   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:54:29.928  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:29.968  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:29.978  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:30.028  1630  3998 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:54:30.028  1630  3998 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:54:30.028  1630  3998 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:54:30.028  1630  3998 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:54:30.028  1630  3998 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:54:30.028  1630  3998 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:30.048  1630  3998 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:54:30.048  1630  3998 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:54:30.048  1630  3998 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:54:30.048  1630  3998 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:54:30.048  1630  3998 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:54:30.048  1630  3998 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:54:30.048  1630  3998 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:30.048  5306  5348 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:54:30.048  5306  5348 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:54:30.048  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:54:30.048  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:54:30.048  5306  5348 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:54:30.048  5306  5348 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:54:30.048  5306  5348 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:30.058  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:54:30.058  5306  5348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:54:30.058   306  1154 D EnterpriseController: netId is 0
06-30 10:54:30.058   306  1154 D Netd    : getNetworkForDns: using netid 0 for uid 10030
,06-30 10:54:39.438   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:54:49.488   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:54:53.598   747  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:58.768   747  1572 E Watchdog: !@Sync 42 [06-30 10:54:58.775]
,06-30 10:54:59.548   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:55:01.598  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:55:09.608   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:55:19.658   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:55:23.678   747  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:28.768   747  1572 E Watchdog: !@Sync 43 [06-30 10:55:28.779]
,06-30 10:55:29.718   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:55:39.768   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:55:49.818   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:55:53.758   747  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:53.758   747  1321 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:55:53.768   747  1321 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:55:53.768   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:53.778   747   747 I MotionRecognitionService: Plugged
,06-30 10:55:53.778   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:55:53.778   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:55:53.788   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:55:53.788   747  1321 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:55:53.788   747  1321 D BatteryService: stay LED for fully charged
,06-30 10:55:53.798  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:53.798  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:53.808  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:53.838  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:53.838  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:53.838  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:58.778   747  1572 E Watchdog: !@Sync 44 [06-30 10:55:58.785]
,06-30 10:55:59.878   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:56:01.618  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:56:09.928   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:56:19.998   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:56:23.838   747  2278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:23.838   747  2278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:56:23.848   747  2278 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:56:23.848   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:23.858   747   747 I MotionRecognitionService: Plugged
,06-30 10:56:23.858   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:56:23.858   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:56:23.868   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:56:23.868   747  2278 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:56:23.868   747  2278 D BatteryService: stay LED for fully charged
,06-30 10:56:23.888  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:23.888  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:56:23.888  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:23.908  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:23.908  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:56:23.908  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:28.778   747  1572 E Watchdog: !@Sync 45 [06-30 10:56:28.789]
,06-30 10:56:30.048   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:56:40.098   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:56:50.158   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:56:53.918   747  1757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:58.788   747  1572 E Watchdog: !@Sync 46 [06-30 10:56:58.796]
,06-30 10:57:00.208   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:57:01.648  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:57:01.808  1730  1814 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 157ms lastUpdatedAfter : 180224ms
,06-30 10:57:10.258   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:57:20.318   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:57:23.998   747  2278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:28.788   747  1572 E Watchdog: !@Sync 47 [06-30 10:57:28.801]
,06-30 10:57:30.368   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:57:40.418   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:57:50.498   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:57:54.078   747  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:54.078   747  1412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:57:54.088   747  1412 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:57:54.088   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:54.098   747   747 I MotionRecognitionService: Plugged
,06-30 10:57:54.098   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:57:54.098   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:57:54.108   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:57:54.108   747  1412 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:57:54.108   747  1412 D BatteryService: stay LED for fully charged
,06-30 10:57:54.128  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:54.128  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:54.128  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:54.158  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:54.158  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:54.158  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:58.798   747  1572 E Watchdog: !@Sync 48 [06-30 10:57:58.806]
,06-30 10:58:00.558   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:58:01.828  1730  1814 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:58:10.608   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:58:20.658   747  3322 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,06-30 10:58:24.158   747  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:24.158   747  1321 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:58:24.158   747  1321 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,06-30 10:58:24.168   747   747 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:58:24.178   747   747 I MotionRecognitionService: Plugged
,06-30 10:58:24.178   747   747 D MotionRecognitionService:   cableConnection= 1
,06-30 10:58:24.178   747   747 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:58:24.178   747  1321 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,06-30 10:58:24.188   747   747 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:58:24.188   747  1321 D BatteryService: stay LED for fully charged
,06-30 10:58:24.198  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:24.198  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:24.198  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:24.238  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:24.238  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:24.238  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),06-30 10:58:27.708  2197  2197 E audit   : type=1400 msg=audit(1467277107.698:284): avc:  denied  { execmod } for  pid=6630 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:58:27.708  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:58:27.718  2197  2197 E audit   : type=1300 msg=audit(1467277107.698:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fab000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=6630 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:58:27.718  2197  2197 E audit   : type=1327 msg=audit(1467277107.698:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 10:58:27.718  2197  2197 E audit   : type=1320 msg=audit(1467277107.698:284): 
06-30 10:58:27.758  2197  2197 E audit   : type=1400 msg=audit(1467277107.758:285): avc:  denied  { execmod } for  pid=6630 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:58:27.758  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:58:27.768  2197  2197 E audit   : type=1300 msg=audit(1467277107.758:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f6b000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=6630 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:58:27.768  2197  2197 E audit   : type=1327 msg=audit(1467277107.758:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 10:58:27.768  2197  2197 E audit   : type=1320 msg=audit(1467277107.758:285): 
06-30 10:58:27.808  2197  2197 E audit   : type=1400 msg=audit(1467277107.808:286): avc:  denied  { execmod } for  pid=6630 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:58:27.808  6630  6630 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:58:27.808  2197  2197 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:58:27.808  6630  6630 D AndroidRuntime: CheckJNI is OFF
06-30 10:58:27.808  6630  6630 D AndroidRuntime: readGMSProperty: start
06-30 10:58:27.808  6630  6630 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:58:27.808  6630  6630 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:58:27.808  6630  6630 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:58:27.808  6630  6630 D AndroidRuntime: readGMSProperty: end
06-30 10:58:27.808  6630  6630 D AndroidRuntime: addProductProperty: start
06-30 10:58:27.818  2197  2197 E audit   : type=1300 msg=audit(1467277107.808:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f6b000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=6630 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:58:27.818  2197  2197 E audit   : type=1327 msg=audit(1467277107.808:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 10:58:27.818  2197  2197 E audit   : type=1320 msg=audit(1467277107.808:286): 
06-30 10:58:27.818  6630  6630 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 10:58:27.818  6630  6630 W art     : af10e000-b2034000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:58:27.818  6630  6630 W art     : b2034000-b42a3000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:58:27.818  6630  6630 W art     : b42a3000-b42a4000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:58:27.818  6630  6630 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 594        /system/lib/libart.so
06-30 10:58:27.818  6630  6630 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 594        /system/lib/libart.so
06-30 10:58:27.818  6630  6630 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 594        /system/lib/libart.so
06-30 10:58:27.818  6630  6630 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 10:58:27.818  6630  6630 W art     : b480f000-b4838000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
06-30 10:58:27.818  6630  6630 W art     : b4838000-b483b000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
06-30 10:58:27.818  6630  6630 W art     : b483b000-b483c000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
06-30 10:58:27.818  6630  6630 W art     : b483c000-b483d000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
06-30 10:58:27.818  6630  6630 W art     : b483d000-b483e000 r--p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b483e000-b485e000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 10:58:27.818  6630  6630 W art     : b485e000-b526f000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
06-30 10:58:27.818  6630  6630 W art     : b526f000-b5270000 ---p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b5270000-b52b9000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
06-30 10:58:27.818  6630  6630 W art     : b52b9000-b52ba000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
06-30 10:58:27.818  6630  6630 W art     : b52ba000-b52c2000 rw-p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b52c2000-b52c3000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.818  6630  6630 W art     : b52c3000-b52f8000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
06-30 10:58:27.818  6630  6630 W art     : b52f8000-b52f9000 ---p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b52f9000-b52fa000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
06-30 10:58:27.818  6630  6630 W art     : b52fa000-b52fb000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
06-30 10:58:27.818  6630  6630 W art     : b52fb000-b5353000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
06-30 10:58:27.818  6630  6630 W art     : b5353000-b5354000 ---p 00000000 00:00 0 
06-30 10:58:27.818  6630  6630 W art     : b5354000-b5355000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
06-30 10:58:27.818  6630  6630 W art     : b5355000-b5356000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
06-30 10:58:27.818  6630  6630 W art     : b5357000-b535d000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:58:27.818  6630  6630 W art     : b535d000-b535e000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:58:27.818  6630  6630 W art     : b535e000-b535f000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:58:27.828  6630  6630 W art     : b535f000-b5361000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5362000-b536c000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 10:58:27.828  6630  6630 W art     : b536c000-b536f000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 10:58:27.828  6630  6630 W art     : b536f000-b5370000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
06-30 10:58:27.828  6630  6630 W art     : b5371000-b5388000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 10:58:27.828  6630  6630 W art     : b5388000-b5389000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5389000-b538a000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 10:58:27.828  6630  6630 W art     : b538a000-b538b000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
06-30 10:58:27.828  6630  6630 W art     : b538c000-b5396000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
06-30 10:58:27.828  6630  6630 W art     : b5396000-b5397000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
06-30 10:58:27.828  6630  6630 W art     : b5397000-b5398000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
06-30 10:58:27.828  6630  6630 W art     : b5398000-b539c000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 10:58:27.828  6630  6630 W art     : b539c000-b539d000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 10:58:27.828  6630  6630 W art     : b539d000-b539e000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
06-30 10:58:27.828  6630  6630 W art     : b539e000-b53b4000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
06-30 10:58:27.828  6630  6630 W art     : b53b4000-b53b5000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
06-30 10:58:27.828  6630  6630 W art     : b53b5000-b53b6000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
06-30 10:58:27.828  6630  6630 W art     : b53b6000-b53c3000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
06-30 10:58:27.828  6630  6630 W art     : b53c3000-b53c4000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
06-30 10:58:27.828  6630  6630 W art     : b53c4000-b53c5000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
06-30 10:58:27.828  6630  6630 W art     : b53c5000-b5425000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
06-30 10:58:27.828  6630  6630 W art     : b5425000-b5428000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
06-30 10:58:27.828  6630  6630 W art     : b5428000-b542c000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b542c000-b548d000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
06-30 10:58:27.828  6630  6630 W art     : b548d000-b548e000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
06-30 10:58:27.828  6630  6630 W art     : b548e000-b54dd000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
06-30 10:58:27.828  6630  6630 W art     : b54dd000-b54df000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
06-30 10:58:27.828  6630  6630 W art     : b54df000-b54e0000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
06-30 10:58:27.828  6630  6630 W art     : b54e0000-b54e1000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b54e1000-b54e8000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 10:58:27.828  6630  6630 W art     : b54e8000-b54e9000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 10:58:27.828  6630  6630 W art     : b54e9000-b54ea000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_avc_common.so
06-30 10:58:27.828  6630  6630 W art     : b54eb000-b54ee000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 10:58:27.828  6630  6630 W art     : b54ee000-b54ef000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 10:58:27.828  6630  6630 W art     : b54ef000-b54f0000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_enc_common.so
06-30 10:58:27.828  6630  6630 W art     : b54f1000-b54f5000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
06-30 10:58:27.828  6630  6630 W art     : b54f5000-b54f6000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b54f6000-b54f7000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
06-30 10:58:27.828  6630  6630 W art     : b54f7000-b54f8000 rw-p 00005000 b3:17 2517       /system/lib/libpowermanager.so
06-30 10:58:27.828  6630  6630 W art     : b54f9000-b5516000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 10:58:27.828  6630  6630 W art     : b5516000-b5517000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 10:58:27.828  6630  6630 W art     : b5517000-b5518000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
06-30 10:58:27.828  6630  6630 W art     : b5519000-b551e000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 10:58:27.828  6630  6630 W art     : b551e000-b551f000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 10:58:27.828  6630  6630 W art     : b551f000-b5520000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
06-30 10:58:27.828  6630  6630 W art     : b5521000-b5552000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 10:58:27.828  6630  6630 W art     : b5552000-b5555000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 10:58:27.828  6630  6630 W art     : b5555000-b5556000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
06-30 10:58:27.828  6630  6630 W art     : b5557000-b5592000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
06-30 10:58:27.828  6630  6630 W art     : b5592000-b5593000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
06-30 10:58:27.828  6630  6630 W art     : b5593000-b5594000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
06-30 10:58:27.828  6630  6630 W art     : b5595000-b559c000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
06-30 10:58:27.828  6630  6630 W art     : b559c000-b559d000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b559d000-b559e000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
06-30 10:58:27.828  6630  6630 W art     : b559e000-b559f000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
06-30 10:58:27.828  6630  6630 W art     : b559f000-b55a0000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.828  6630  6630 W art     : b55a0000-b55b7000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
06-30 10:58:27.828  6630  6630 W art     : b55b7000-b55b8000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b55b8000-b55bb000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
06-30 10:58:27.828  6630  6630 W art     : b55bb000-b55bc000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
06-30 10:58:27.828  6630  6630 W art     : b55bc000-b55db000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
06-30 10:58:27.828  6630  6630 W art     : b55db000-b55dc000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
06-30 10:58:27.828  6630  6630 W art     : b55dc000-b55dd000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
06-30 10:58:27.828  6630  6630 W art     : b55dd000-b561b000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 10:58:27.828  6630  6630 W art     : b561b000-b561c000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b561c000-b561e000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 10:58:27.828  6630  6630 W art     : b561e000-b561f000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 10:58:27.828  6630  6630 W art     : b5620000-b5627000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
06-30 10:58:27.828  6630  6630 W art     : b5627000-b5628000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
06-30 10:58:27.828  6630  6630 W art     : b5628000-b5629000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
06-30 10:58:27.828  6630  6630 W art     : b562a000-b562d000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
06-30 10:58:27.828  6630  6630 W art     : b562d000-b562e000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
06-30 10:58:27.828  6630  6630 W art     : b562e000-b562f000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
06-30 10:58:27.828  6630  6630 W art     : b562f000-b5635000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:58:27.828  6630  6630 W art     : b5635000-b5636000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5636000-b5637000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:58:27.828  6630  6630 W art     : b5637000-b5638000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:58:27.828  6630  6630 W art     : b5638000-b5641000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
06-30 10:58:27.828  6630  6630 W art     : b5641000-b5642000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
06-30 10:58:27.828  6630  6630 W art     : b5642000-b5643000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
06-30 10:58:27.828  6630  6630 W art     : b5643000-b56d4000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 10:58:27.828  6630  6630 W art     : b56d4000-b56d5000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b56d5000-b56e0000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 10:58:27.828  6630  6630 W art     : b56e0000-b56e1000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
06-30 10:58:27.828  6630  6630 W art     : b56e2000-b56f4000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
06-30 10:58:27.828  6630  6630 W art     : b56f4000-b56f5000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
06-30 10:58:27.828  6630  6630 W art     : b56f5000-b56f6000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
06-30 10:58:27.828  6630  6630 W art     : b56f7000-b56fc000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
06-30 10:58:27.828  6630  6630 W art     : b56fc000-b56fd000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
06-30 10:58:27.828  6630  6630 W art     : b56fd000-b56fe000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
06-30 10:58:27.828  6630  6630 W art     : b56ff000-b576c000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 10:58:27.828  6630  6630 W art     : b576c000-b576d000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b576d000-b576f000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 10:58:27.828  6630  6630 W art     : b576f000-b5770000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
06-30 10:58:27.828  6630  6630 W art     : b5770000-b5771000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.828  6630  6630 W art     : b5771000-b5778000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:58:27.828  6630  6630 W art     : b5778000-b5779000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:58:27.828  6630  6630 W art     : b5779000-b577a000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:58:27.828  6630  6630 W art     : b577b000-b57fb000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 10:58:27.828  6630  6630 W art     : b57fb000-b57fc000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b57fc000-b57fd000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 10:58:27.828  6630  6630 W art     : b57fd000-b57fe000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
06-30 10:58:27.828  6630  6630 W art     : b57fe000-b5815000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5815000-b584c000 r-xp 00000000 b3:17 3247       /system/vendor/l
06-30 10:58:27.828  6630  6630 W art     : ib/libqc-opt.so
06-30 10:58:27.828  6630  6630 W art     : b584c000-b584d000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 10:58:27.828  6630  6630 W art     : b584d000-b584e000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
06-30 10:58:27.828  6630  6630 W art     : b584e000-b586a000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 10:58:27.828  6630  6630 W art     : b586a000-b586b000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 10:58:27.828  6630  6630 W art     : b586b000-b586c000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
06-30 10:58:27.828  6630  6630 W art     : b586d000-b58ce000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 10:58:27.828  6630  6630 W art     : b58ce000-b58d0000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 10:58:27.828  6630  6630 W art     : b58d0000-b58d1000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 10:58:27.828  6630  6630 W art     : b58d2000-b58f9000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
06-30 10:58:27.828  6630  6630 W art     : b58f9000-b58fa000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b58fa000-b58fb000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
06-30 10:58:27.828  6630  6630 W art     : b58fb000-b58fc000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
06-30 10:58:27.828  6630  6630 W art     : b58fd000-b5905000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 10:58:27.828  6630  6630 W art     : b5905000-b5907000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 10:58:27.828  6630  6630 W art     : b5907000-b5908000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
06-30 10:58:27.828  6630  6630 W art     : b5909000-b590c000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
06-30 10:58:27.828  6630  6630 W art     : b590c000-b590d000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
06-30 10:58:27.828  6630  6630 W art     : b590d000-b590e000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
06-30 10:58:27.828  6630  6630 W art     : b590e000-b5912000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
06-30 10:58:27.828  6630  6630 W art     : b5912000-b5913000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5913000-b5914000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
06-30 10:58:27.828  6630  6630 W art     : b5914000-b5915000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
06-30 10:58:27.828  6630  6630 W art     : b5915000-b5925000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
06-30 10:58:27.828  6630  6630 W art     : b5925000-b5926000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
06-30 10:58:27.828  6630  6630 W art     : b5926000-b5927000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
06-30 10:58:27.828  6630  6630 W art     : b5927000-b596d000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b596d000-b5976000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
06-30 10:58:27.828  6630  6630 W art     : b5976000-b5977000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
06-30 10:58:27.828  6630  6630 W art     : b5977000-b5978000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
06-30 10:58:27.828  6630  6630 W art     : b5979000-b597e000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
06-30 10:58:27.828  6630  6630 W art     : b597e000-b597f000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
06-30 10:58:27.828  6630  6630 W art     : b597f000-b5980000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
06-30 10:58:27.828  6630  6630 W art     : b5980000-b5983000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 10:58:27.828  6630  6630 W art     : b5983000-b5984000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5984000-b5985000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 10:58:27.828  6630  6630 W art     : b5985000-b5986000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
06-30 10:58:27.828  6630  6630 W art     : b5987000-b599f000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:58:27.828  6630  6630 W art     : b599f000-b59a0000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b59a0000-b59a1000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:58:27.828  6630  6630 W art     : b59a1000-b59a2000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:58:27.828  6630  6630 W art     : b59a2000-b59a3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:58:27.828  6630  6630 W art     : b59a3000-b5b3d000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
06-30 10:58:27.828  6630  6630 W art     : b5b3d000-b5b3e000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5b3e000-b5b4b000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
06-30 10:58:27.828  6630  6630 W art     : b5b4b000-b5b4c000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
06-30 10:58:27.828  6630  6630 W art     : b5b4c000-b5b50000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
06-30 10:58:27.828  6630  6630 W art     : b5b50000-b5b51000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5b51000-b5b52000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
06-30 10:58:27.828  6630  6630 W art     : b5b52000-b5b53000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
06-30 10:58:27.828  6630  6630 W art     : b5b53000-b5b66000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
06-30 10:58:27.828  6630  6630 W art     : b5b66000-b5b67000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
06-30 10:58:27.828  6630  6630 W art     : b5b67000-b5b68000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
06-30 10:58:27.828  6630  6630 W art     : b5b69000-b5bb4000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 10:58:27.828  6630  6630 W art     : b5bb4000-b5bb5000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 10:58:27.828  6630  6630 W art     : b5bb5000-b5bb6000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
06-30 10:58:27.828  6630  6630 W art     : b5bb6000-b5bb8000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5bb9000-b5bca000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 10:58:27.828  6630  6630 W art     : b5bca000-b5bcb000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5bcb000-b5bcc000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 10:58:27.828  6630  6630 W art     : b5bcc000-b5bcd000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
06-30 10:58:27.828  6630  6630 W art     : b5bcd000-b5bce000 r--p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5bce000-b5bd8000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
06-30 10:58:27.828  6630  6630 W art     : b5bd8000-b5bda000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
06-30 10:58:27.828  6630  6630 W art     : b5bda000-b5bdb000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
06-30 10:58:27.828  6630  6630 W art     : b5bdb000-b5bf4000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
06-30 10:58:27.828  6630  6630 W art     : b5bf4000-b5bf5000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
06-30 10:58:27.828  6630  6630 W art     : b5bf5000-b5bf8000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
06-30 10:58:27.828  6630  6630 W art     : b5bf8000-b5bfc000 rw-p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5bfc000-b5c70000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
06-30 10:58:27.828  6630  6630 W art     : b5c70000-b5c71000 ---p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5c71000-b5c74000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
06-30 10:58:27.828  6630  6630 W art     : b5c74000-b5c75000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
06-30 10:58:27.828  6630  6630 W art     : b5c75000-b5c76000 r--p 00000000 00:00 0 
06-30 10:58:27.828  6630  6630 W art     : b5c76000-b5c79000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
06-30 10:58:27.828  6630  6630 W art     : b5c79000-b5c7a000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
06-30 10:58:27.828  6630  6630 W art     : b5c7a000-b5c7b000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
06-30 10:58:27.828  6630  6630 W art     : b5c7b000-b5c7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.828  6630  6630 W art     : b5c7c000-b5c81000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 10:58:27.828  6630  6630 W art     : b5c81000-b5c82000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 10:58:27.828  6630  6630 W art     : b5c82000-b5c83000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
06-30 10:58:27.828  6630  6630 W art     : b5c83000-b5c84000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.828  6630  6630 W art     : b5c84000-b5c87000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 10:58:27.828  6630  6630 W art     : b5c87000-b5c88000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 10:58:27.838  6630  6630 W art     : b5c88000-b5c89000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
06-30 10:58:27.838  6630  6630 W art     : b5c89000-b5c8a000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b5c8a000-b5c8e000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
06-30 10:58:27.838  6630  6630 W art     : b5c8e000-b5c8f000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
06-30 10:58:27.838  6630  6630 W art     : b5c8f000-b5c90000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
06-30 10:58:27.838  6630  6630 W art     : b5c90000-b5c91000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:58:27.838  6630  6630 W art     : b5c91000-b5c95000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 10:58:27.838  6630  6630 W art     : b5c95000-b5c96000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 10:58:27.838  6630  6630 W art     : b5c96000-b5c97000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
06-30 10:58:27.838  6630  6630 W art     : b5c97000-b5c98000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b5c98000-b5ca6000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 10:58:27.838  6630  6630 W art     : b5ca6000-b5ca7000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b5ca7000-b5ca8000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 10:58:27.838  6630  6630 W art     : b5ca8000-b5ca9000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 10:58:27.838  6630  6630 W art     : b5ca9000-b5cb3000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 10:58:27.838  6630  6630 W art     : b5cb3000-b5cb6000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 10:58:27.838  6630  6630 W art     : b5cb6000-b5cb7000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
06-30 10:58:27.838  6630  6630 W art     : b5cb7000-b5cb8000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b5cb8000-b5cc2000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
06-30 10:58:27.838  6630  6630 W art     : b5cc2000-b5cc5000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
06-30 10:58:27.838  6630  6630 W art     : b5cc5000-b5cc6000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
06-30 10:58:27.838  6630  6630 W art     : b5cc6000-b5cca000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
06-30 10:58:27.838  6630  6630 W art     : b5cca000-b5ccb000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
06-30 10:58:27.838  6630  6630 W art     : b5ccb000-b5ccc000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
06-30 10:58:27.838  6630  6630 W art     : b5ccc000-b5ccd000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b5ccd000-b5cda000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:58:27.838  6630  6630 W art     : b5cda000-b5cdc000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:58:27.838  6630  6630 W art     : b5cdc000-b5cdd000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:58:27.838  6630  6630 W art     : b5cdd000-b60ef000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
06-30 10:58:27.838  6630  6630 W art     : b60ef000-b60f0000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b60f0000-b60f9000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
06-30 10:58:27.838  6630  6630 W art     : b60f9000-b60fd000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
06-30 10:58:27.838  6630  6630 W art     : b60fd000-b60fe000 rw-p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b60fe000-b6105000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:58:27.838  6630  6630 W art     : b6105000-b6106000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:58:27.838  6630  6630 W art     : b6106000-b6107000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:58:27.838  6630  6630 W art     : b6107000-b6108000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b6108000-b6123000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 10:58:27.838  6630  6630 W art     : b6123000-b6124000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 10:58:27.838  6630  6630 W art     : b6124000-b6125000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 10:58:27.838  6630  6630 W art     : b6125000-b6126000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b6126000-b6172000 r-xp 00000000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 10:58:27.838  6630  6630 W art     : b6172000-b6173000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b6173000-b6174000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 10:58:27.838  6630  6630 W art     : b6174000-b6175000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
06-30 10:58:27.838  6630  6630 W art     : b6175000-b6176000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b6176000-b617a000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
06-30 10:58:27.838  6630  6630 W art     : b617a000-b617b000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b617b000-b617c000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
06-30 10:58:27.838  6630  6630 W art     : b617c000-b617d000 rw-p 00005000 b3:17 2688       /system/lib/libusbhost.so
06-30 10:58:27.838  6630  6630 W art     : b617d000-b61b5000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
06-30 10:58:27.838  6630  6630 W art     : b61b5000-b61b6000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
06-30 10:58:27.838  6630  6630 W art     : b61b6000-b61b7000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
06-30 10:58:27.838  6630  6630 W art     : b61b7000-b61b8000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.838  6630  6630 W art     : b61b8000-b6256000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
06-30 10:58:27.838  6630  6630 W art     : b6256000-b6257000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b6257000-b6275000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
06-30 10:58:27.838  6630  6630 W art     : b6275000-b6276000 rw-p 000bc000 b3:17 409        /system/lib/libmedia.so
06-30 10:58:27.838  6630  6630 W art     : b6276000-b63e9000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
06-30 10:58:27.838  6630  6630 W art     : b63e9000-b63f4000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
06-30 10:58:27.838  6630  6630 W art     : b63f4000-b63f5000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
06-30 10:58:27.838  6630  6630 W art     : b63f5000-b650c000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:58:27.838  6630  6630 W art     : b650c000-b6517000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:58:27.838  6630  6630 W art     : b6517000-b6518000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:58:27.838  6630  6630 W art     : b6518000-b651c000 rw-p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b651c000-b6540000 r-xp 00000000 b3:17 405        /system/lib/libssl.so
06-30 10:58:27.838  6630  6630 W art     : b6540000-b6542000 r--p 00023000 b3:17 405        /system/lib/libssl.so
06-30 10:58:27.838  6630  6630 W art     : b6542000-b6543000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
06-30 10:58:27.838  6630  6630 W art     : b6543000-b65e9000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
06-30 10:58:27.838  6630  6630 W art     : b65e9000-b65f6000 r--p 000a5000 b3:17 110        /system/lib/libcrypto.so
06-30 10:58:27.838  6630  6630 W art     : b65f6000-b65f7000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
06-30 10:58:27.838  6630  6630 W art     : b65f7000-b65f8000 rw-p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b65f8000-b664b000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
06-30 10:58:27.838  6630  6630 W art     : b664b000-b664c000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b664c000-b664d000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
06-30 10:58:27.838  6630  6630 W art     : b664d000-b664e000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
06-30 10:58:27.838  6630  6630 W art     : b664e000-b6653000 rw-p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b6653000-b6665000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
06-30 10:58:27.838  6630  6630 W art     : b6665000-b6666000 ---p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b6666000-b6667000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
06-30 10:58:27.838  6630  6630 W art     : b6667000-b6668000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
06-30 10:58:27.838  6630  6630 W art     : b6668000-b666f000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 10:58:27.838  6630  6630 W art     : b666f000-b6670000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 10:58:27.838  6630  6630 W art     : b6670000-b6671000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
06-30 10:58:27.838  6630  6630 W art     : b6671000-b6672000 rw-p 00000000 00:00 0 
06-30 10:58:27.838  6630  6630 W art     : b6672000-b6675000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
06-30 10:58:27.838  6630  6630 W art     : b6675000-b6676000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
06-30 10:58:27.848  6630  6630 W art     : b6676000-b6677000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
06-30 10:58:27.848  6630  6630 W art     : b6677000-b667b000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
06-30 10:58:27.848  6630  6630 W art     : b667b000-b667c000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
06-30 10:58:27.848  6630  6630 W art     : b667c000-b667d000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
06-30 10:58:27.848  6630  6630 W art     : b667d000-b668b000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
06-30 10:58:27.848  6630  6630 W art     : b668b000-b668c000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b668c000-b668d000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
06-30 10:58:27.848  6630  6630 W art     : b668d000-b668e000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
06-30 10:58:27.848  6630  6630 W art     : b668e000-b6697000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 10:58:27.848  6630  6630 W art     : b6697000-b6698000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 10:58:27.848  6630  6630 W art     : b6698000-b6699000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
06-30 10:58:27.848  6630  6630 W art     : b6699000-b66ff000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
06-30 10:58:27.848  6630  6630 W art     : b66ff000-b6700000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6700000-b6702000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
06-30 10:58:27.848  6630  6630 W art     : b6702000-b670b000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
06-30 10:58:27.848  6630  6630 W art     : b670b000-b670e000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b670e000-b67a5000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 10:58:27.848  6630  6630 W art     : b67a5000-b67a7000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 10:58:27.848  6630  6630 W art     : b67a7000-b67a8000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 10:58:27.848  6630  6630 W art     : b67a8000-b67a9000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b67a9000-b6aca000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
06-30 10:58:27.848  6630  6630 W art     : b6aca000-b6acb000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6acb000-b6ae6000 r--p 00321000 b3:17 286        /system/lib/libskia.so
06-30 10:58:27.848  6630  6630 W art     : b6ae6000-b6aea000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
06-30 10:58:27.848  6630  6630 W art     : b6aea000-b6aef000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6aef000-b6af7000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 10:58:27.848  6630  6630 W art     : b6af7000-b6af8000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 10:58:27.848  6630  6630 W art     : b6af8000-b6af9000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
06-30 10:58:27.848  6630  6630 W art     : b6af9000-b6b27000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:58:27.848  6630  6630 W art     : b6b27000-b6b28000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6b28000-b6b2f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:58:27.848  6630  6630 W art     : b6b2f000-b6b30000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:58:27.848  6630  6630 W art     : b6b30000-b6b76000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:58:27.848  6630  6630 W art     : b6b76000-b6b77000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6b77000-b6b7a000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:58:27.848  6630  6630 W art     : b6b7a000-b6b7b000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:58:27.848  6630  6630 W art     : b6b7b000-b6b96000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
06-30 10:58:27.848  6630  6630 W art     : b6b96000-b6b9a000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
06-30 10:58:27.848  6630  6630 W art     : b6b9a000-b6b9b000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
06-30 10:58:27.848  6630  6630 W art     : b6b9b000-b6be8000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
06-30 10:58:27.848  6630  6630 W art     : b6be8000-b6be9000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6be9000-b6bf5000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
06-30 10:58:27.848  6630  6630 W art     : b6bf5000-b6bf6000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
06-30 10:58:27.848  6630  6630 W art     : b6bf6000-b6c03000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
06-30 10:58:27.848  6630  6630 W art     : b6c03000-b6c04000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6c04000-b6c05000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
06-30 10:58:27.848  6630  6630 W art     : b6c05000-b6c06000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
06-30 10:58:27.848  6630  6630 W art     : b6c06000-b6c0e000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
06-30 10:58:27.848  6630  6630 W art     : b6c0e000-b6c0f000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6c0f000-b6c10000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
06-30 10:58:27.848  6630  6630 W art     : b6c10000-b6c11000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
06-30 10:58:27.848  6630  6630 W art     : b6c11000-b6c18000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:58:27.848  6630  6630 W art     : b6c18000-b6c19000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:58:27.848  6630  6630 W art     : b6c19000-b6c1a000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:58:27.848  6630  6630 W art     : b6c1a000-b6c2e000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
06-30 10:58:27.848  6630  6630 W art     : b6c2e000-b6c30000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
06-30 10:58:27.848  6630  6630 W art     : b6c30000-b6c31000 rw-p 00015000 b3:17 2082       /system/lib/libexpat.so
06-30 10:58:27.848  6630  6630 W art     : b6c31000-b6c59000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
06-30 10:58:27.848  6630  6630 W art     : b6c59000-b6c5b000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
06-30 10:58:27.848  6630  6630 W art     : b6c5b000-b6c5c000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
06-30 10:58:27.848  6630  6630 W art     : b6c5c000-b6c5f000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
06-30 10:58:27.848  6630  6630 W art     : b6c5f000-b6c60000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
06-30 10:58:27.848  6630  6630 W art     : b6c60000-b6c61000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
06-30 10:58:27.848  6630  6630 W art     : b6c61000-b6c6a000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:58:27.848  6630  6630 W art     : b6c6a000-b6c6b000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:58:27.848  6630  6630 W art     : b6c6b000-b6c6c000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:58:27.848  6630  6630 W art     : b6c6c000-b6c8c000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 10:58:27.848  6630  6630 W art     : b6c8c000-b6c8d000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 10:58:27.848  6630  6630 W art     : b6c8d000-b6c8e000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 10:58:27.848  6630  6630 W art     : b6c8e000-b6d01000 r-xp 00000000 b3:17 328        /system/lib/libc.so
06-30 10:58:27.848  6630  6630 W art     : b6d01000-b6d05000 r--p 00072000 b3:17 328        /system/lib/libc.so
06-30 10:58:27.848  6630  6630 W art     : b6d05000-b6d08000 rw-p 00076000 b3:17 328        /system/lib/libc.so
06-30 10:58:27.848  6630  6630 W art     : b6d08000-b6d12000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6d12000-b6d9a000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 10:58:27.848  6630  6630 W art     : b6d9a000-b6d9b000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6d9b000-b6d9f000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 10:58:27.848  6630  6630 W art     : b6d9f000-b6da0000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 10:58:27.848  6630  6630 W art     : b6da0000-b6da1000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6da1000-b6dca000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:58:27.848  6630  6630 W art     : b6dca000-b6dcb000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6dcb000-b6dce000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:58:27.848  6630  6630 W art     : b6dce000-b6dcf000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:58:27.848  6630  6630 W art     : b6dcf000-b6ea9000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 10:58:27.848  6630  6630 W art     : b6ea9000-b6eb0000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 10:58:27.848  6630  6630 W art     : b6eb0000-b6eb8000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
06-30 10:58:27.848  6630  6630 W art     : b6eb8000-b6eb9000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6eb9000-b6eba000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:58:27.848  6630  6630 W art     : b6eba000-b6ebb000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 10:58:27.848  6630  6630 W art     : b6ebb000-b6ebc000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.848  6630  6630 W art     : b6ebc000-b6ebf000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.848  6630  6630 W art     : b6ebf000-b6ee4000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
06-30 10:58:27.848  6630  6630 W art     : b6ee4000-b6ee5000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6ee5000-b6eec000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
06-30 10:58:27.848  6630  6630 W art     : b6eec000-b6eed000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
06-30 10:58:27.848  6630  6630 W art     : b6eed000-b6ef4000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 10:58:27.848  6630  6630 W art     : b6ef4000-b6ef5000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 10:58:27.848  6630  6630 W art     : b6ef5000-b6ef6000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 10:58:27.848  6630  6630 W art     : b6ef6000-b6ef7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.848  6630  6630 W art     : b6ef7000-b6f0f000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
06-30 10:58:27.848  6630  6630 W art     : b6f0f000-b6f10000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6f10000-b6f11000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
06-30 10:58:27.848  6630  6630 W art     : b6f11000-b6f12000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
06-30 10:58:27.848  6630  6630 W art     : b6f12000-b6f20000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
06-30 10:58:27.848  6630  6630 W art     : b6f20000-b6f21000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6f21000-b6f22000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
06-30 10:58:27.848  6630  6630 W art     : b6f22000-b6f23000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
06-30 10:58:27.848  6630  6630 W art     : b6f23000-b6f24000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:58:27.848  6630  6630 W art     : b6f24000-b6f26000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.848  6630  6630 W art     : b6f26000-b6f27000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.848  6630  6630 W art     : b6f27000-b6f28000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:58:27.848  6630  6630 W art     : b6f28000-b6f29000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 10:58:27.848  6630  6630 W art     : b6f29000-b6f2a000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:58:27.848  6630  6630 W art     : b6f2a000-b6f4a000 r--s 00000000 00:0b 6700       /dev/__properties__
06-30 10:58:27.848  6630  6630 W art     : b6f4a000-b6f4b000 r--p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6f4b000-b6f4c000 ---p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6f4c000-b6f4e000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 10:58:27.848  6630  6630 W art     : b6f4e000-b6f4f000 r-xp 00000000 00:00 0          [sigpage]
06-30 10:58:27.848  6630  6630 W art     : b6f4f000-b6f6a000 r-xp 00000000 b3:17 2771       /system/bin/linker
06-30 10:58:27.848  6630  6630 W art     : b6f6a000-b6f6b000 r--p 0001a000 b3:17 2771       /system/bin/linker
06-30 10:58:27.848  6630  6630 W art     : b6f6b000-b6f6d000 rw-p 0001b000 b3:17 2771       /system/bin/linker
06-30 10:58:27.848  6630  6630 W art     : b6f6d000-b6f6f000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : b6f6f000-b6f74000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 10:58:27.848  6630  6630 W art     : b6f74000-b6f75000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 10:58:27.848  6630  6630 W art     : b6f75000-b6f76000 rw-p 00000000 00:00 0 
06-30 10:58:27.848  6630  6630 W art     : bec4f000-bec70000 rw-p 00000000 00:00 0          [stack]
06-30 10:58:27.848  6630  6630 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 10:58:27.908  6630  6630 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:58:27.968  6630  6630 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:58:27.978  6630  6630 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:58:27.988  6630  6630 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 10:58:28.008   747  1703 D PackageManager: START PACKAGE DELETE: observer{216736387}
06-30 10:58:28.008   747  1703 D PackageManager: pkg{<packageName>}
06-30 10:58:28.008   747  1703 D PackageManager: user{0}
06-30 10:58:28.008   747  1703 D PackageManager: caller{2000}
06-30 10:58:28.008   747  1703 D PackageManager: flags{2}
06-30 10:58:28.008   747  1703 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 10:58:28.008   747  1703 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 10:58:28.008   747  1703 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 10:58:28.008   747  1703 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:58:28.008   747  1703 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:58:28.018   747   912 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 10:58:28.018   747   912 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 10:58:28.018   747   912 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 10:58:28.018   747   912 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 10:58:28.018   747   912 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 10:58:28.018   747   912 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 10:58:28.018   747   912 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 10:58:28.018   747   912 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
06-30 10:58:28.018   747   821 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
06-30 10:58:28.018   747   912 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 10:58:28.018   747   912 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 10:58:28.028   747   821 I ActivityManager: Killing 5966:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
06-30 10:58:28.028   747   821 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 10:58:28.028   747   821 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 10:58:28.048   747   821 I ActivityManager: Start proc 6647:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 10:58:28.048   747   821 I ActivityManager: Killing 6440:com.sec.android.daemonapp/u0a182 (adj 5): SSR - service for lastStateTime 826s, lastActivityTime 825s
06-30 10:58:28.048   747   821 I ActivityManager: Killing 6418:com.sec.android.pagebuddynotisvc/u0a27 (adj 8): SSR - service for lastStateTime 827s, lastActivityTime 827s
06-30 10:58:28.048   747   821 I ActivityManager: Killing 6403:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 837s, lastActivityTime 837s
06-30 10:58:28.048   747   821 I ActivityManager:   Force finishing activity ActivityRecord{854e8e5 u0 com.test.thalitest/.MainActivity t77}
06-30 10:58:28.048   747   821 I ActivityManager:   Force finishing activity ActivityRecord{12ba421 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t77}
06-30 10:58:28.048   747   821 I ActivityManager: Killing 5410:com.sec.android.app.camera/u0a154 (adj 15): DHA:empty #37
06-30 10:58:28.058  6647  6647 E Zygote  : v2
06-30 10:58:28.058  6647  6647 I libpersona: KNOX_SDCARD checking this for 10004
06-30 10:58:28.058  6647  6647 I libpersona: KNOX_SDCARD not a persona
06-30 10:58:28.058  6647  6647 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:58:28.058  6647  6647 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:58:28.058  6647  6647 E Zygote  : accessInfo : 0
06-30 10:58:28.058  6647  6647 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 10:58:28.078   293   367 I SurfaceFlinger: id=14 Removed NainActivit (4/11)
06-30 10:58:28.078   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe92638c
06-30 10:58:28.078   293   361 I SurfaceFlinger: id=14 Removed NainActivit (-2/11)
06-30 10:58:28.108  6647  6647 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:58:28.108  6647  6647 D ActivityThread: Added TimaKeyStore provider
06-30 10:58:28.118  6028  6028 D ViewRootImpl: #3 mView = null
06-30 10:58:28.118   293  1503 I SurfaceFlinger: id=15 Removed HrantPermis (4/10)

```
