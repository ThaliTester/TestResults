#### Test 82642184ea62b6e_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-30 23:11:00.350   779  1235 V AlarmManager: Expired Alarm result :4
,08-30 23:11:00.370   779   779 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
08-30 23:11:00.370   779   779 V AlarmManagerEXT: <AppSync3 Whitelist>
08-30 23:11:00.370   779   779 V AlarmManagerEXT: (AppSync) ### 0 added ###
--------- beginning of main
08-30 23:11:00.370  5827  5876 I Finsky  : [828] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
08-30 23:11:00.380  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-30 23:11:00.380  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
08-30 23:11:00.380  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 23:11:00.400  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-30 23:11:00.400  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
08-30 23:11:00.410  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.410  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.410  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.410  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.410  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.410  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.410  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.420   779  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 23:11:00.420   779  1747 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-30 23:11:00.420   779  1747 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-30 23:11:00.420   779  1747 D BatteryService: stay LED for charging
08-30 23:11:00.420   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 23:11:00.420   779   779 I MotionRecognitionService: Plugged
08-30 23:11:00.420   779   779 D MotionRecognitionService:   cableConnection= 1
08-30 23:11:00.420   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 23:11:00.420   779   779 D MotionRecognitionService: skip setTransmitPower. 
08-30 23:11:00.440  2325  2325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 23:11:00.440  2325  2738 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 23:11:00.450  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 23:11:00.450  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-30 23:11:00.450  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 23:11:00.450  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 23:11:00.450  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 23:11:00.450  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 23:11:00.540  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-30 23:11:00.890  5827  5876 I Finsky  : [828] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
08-30 23:11:00.890  5827  5827 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
08-30 23:11:01.420  2331  2331 E audit   : type=1400 msg=audit(1472591461.420:284): avc:  denied  { execmod } for  pid=6520 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 23:11:01.420  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:01.420  2331  2331 E audit   : type=1300 msg=audit(1472591461.420:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4013000 a1=51000 a2=5 a3=4 items=0 ppid=3783 ppcomm=adbd pid=6520 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 23:11:01.420  2331  2331 E audit   : type=1327 msg=audit(1472591461.420:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 23:11:01.420  2331  2331 E audit   : type=1320 msg=audit(1472591461.420:284): 
08-30 23:11:01.500  2331  2331 E audit   : type=1400 msg=audit(1472591461.490:285): avc:  denied  { execmod } for  pid=6520 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 23:11:01.500  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:01.500  2331  2331 E audit   : type=1300 msg=audit(1472591461.490:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd3000 a1=51000 a2=5 a3=4 items=0 ppid=3783 ppcomm=adbd pid=6520 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 23:11:01.500  2331  2331 E audit   : type=1327 msg=audit(1472591461.490:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 23:11:01.500  2331  2331 E audit   : type=1320 msg=audit(1472591461.490:285): 
08-30 23:11:01.550  2331  2331 E audit   : type=1400 msg=audit(1472591461.550:286): avc:  denied  { execmod } for  pid=6520 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 23:11:01.550  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:01.550  2331  2331 E audit   : type=1300 msg=audit(1472591461.550:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd3000 a1=51000 a2=5 a3=4 items=0 ppid=3783 ppcomm=adbd pid=6520 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 23:11:01.550  2331  2331 E audit   : type=1327 msg=audit(1472591461.550:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-30 23:11:01.550  2331  2331 E audit   : type=1320 msg=audit(1472591461.550:286): 
08-30 23:11:01.550  6520  6520 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 23:11:01.560  6520  6520 D AndroidRuntime: CheckJNI is OFF
08-30 23:11:01.560  6520  6520 D AndroidRuntime: readGMSProperty: start
08-30 23:11:01.560  6520  6520 D AndroidRuntime: readGMSProperty: already setted!!
08-30 23:11:01.560  6520  6520 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 23:11:01.560  6520  6520 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 23:11:01.560  6520  6520 D AndroidRuntime: readGMSProperty: end
08-30 23:11:01.560  6520  6520 D AndroidRuntime: addProductProperty: start
08-30 23:11:01.570  6520  6520 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 23:11:01.570  6520  6520 W art     : af165000-b208b000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-30 23:11:01.570  6520  6520 W art     : b208b000-b42fa000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-30 23:11:01.570  6520  6520 W art     : b42fa000-b42fb000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-30 23:11:01.570  6520  6520 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 23:11:01.570  6520  6520 W art     : b4324000-b4772000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-30 23:11:01.570  6520  6520 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b4773000-b477d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-30 23:11:01.570  6520  6520 W art     : b477d000-b477e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-30 23:11:01.570  6520  6520 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-30 23:11:01.570  6520  6520 W art     : b48a0000-b48a3000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-30 23:11:01.570  6520  6520 W art     : b48a3000-b48a4000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-30 23:11:01.570  6520  6520 W art     : b48a4000-b48a5000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-30 23:11:01.570  6520  6520 W art     : b48a5000-b48a6000 r--p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b48a6000-b48c6000 r--s 00000000 00:0b 7184       /dev/__properties__
08-30 23:11:01.570  6520  6520 W art     : b48c6000-b52d7000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-30 23:11:01.570  6520  6520 W art     : b52d7000-b52d8000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b52d8000-b5321000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-30 23:11:01.570  6520  6520 W art     : b5321000-b5322000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-30 23:11:01.570  6520  6520 W art     : b5322000-b532a000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b532a000-b535f000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-30 23:11:01.570  6520  6520 W art     : b535f000-b5360000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5360000-b5361000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-30 23:11:01.570  6520  6520 W art     : b5361000-b5362000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-30 23:11:01.570  6520  6520 W art     : b5362000-b53ba000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-30 23:11:01.570  6520  6520 W art     : b53ba000-b53bb000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b53bb000-b53bc000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-30 23:11:01.570  6520  6520 W art     : b53bc000-b53bd000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-30 23:11:01.570  6520  6520 W art     : b53be000-b53c4000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 23:11:01.570  6520  6520 W art     : b53c4000-b53c5000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 23:11:01.570  6520  6520 W art     : b53c5000-b53c6000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 23:11:01.570  6520  6520 W art     : b53c6000-b53c8000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b53c9000-b53d3000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 23:11:01.570  6520  6520 W art     : b53d3000-b53d6000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 23:11:01.570  6520  6520 W art     : b53d6000-b53d7000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 23:11:01.570  6520  6520 W art     : b53d8000-b53ef000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 23:11:01.570  6520  6520 W art     : b53ef000-b53f0000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b53f0000-b53f1000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 23:11:01.570  6520  6520 W art     : b53f1000-b53f2000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 23:11:01.570  6520  6520 W art     : b53f3000-b53fd000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-30 23:11:01.570  6520  6520 W art     : b53fd000-b53fe000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-30 23:11:01.570  6520  6520 W art     : b53fe000-b53ff000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-30 23:11:01.570  6520  6520 W art     : b53ff000-b5403000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 23:11:01.570  6520  6520 W art     : b5403000-b5404000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 23:11:01.570  6520  6520 W art     : b5404000-b5405000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-30 23:11:01.570  6520  6520 W art     : b5405000-b541b000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-30 23:11:01.570  6520  6520 W art     : b541b000-b541c000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-30 23:11:01.570  6520  6520 W art     : b541c000-b541d000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-30 23:11:01.570  6520  6520 W art     : b541d000-b542a000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-30 23:11:01.570  6520  6520 W art     : b542a000-b542b000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-30 23:11:01.570  6520  6520 W art     : b542b000-b542c000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-30 23:11:01.570  6520  6520 W art     : b542c000-b548c000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-30 23:11:01.570  6520  6520 W art     : b548c000-b548f000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-30 23:11:01.570  6520  6520 W art     : b548f000-b5493000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5493000-b54f4000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-30 23:11:01.570  6520  6520 W art     : b54f4000-b54f5000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-30 23:11:01.570  6520  6520 W art     : b54f5000-b5544000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-30 23:11:01.570  6520  6520 W art     : b5544000-b5546000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-30 23:11:01.570  6520  6520 W art     : b5546000-b5547000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-30 23:11:01.570  6520  6520 W art     : b5547000-b5548000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5548000-b554f000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 23:11:01.570  6520  6520 W art     : b554f000-b5550000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-30 23:11:01.570  6520  6520 W art     : b5550000-b5551000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-30 23:11:01.570  6520  6520 W art     : avc_common.so
08-30 23:11:01.570  6520  6520 W art     : b5552000-b5555000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 23:11:01.570  6520  6520 W art     : b5555000-b5556000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 23:11:01.570  6520  6520 W art     : b5556000-b5557000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-30 23:11:01.570  6520  6520 W art     : enc_common.so
08-30 23:11:01.570  6520  6520 W art     : b5558000-b555c000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-30 23:11:01.570  6520  6520 W art     : b555c000-b555d000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b555d000-b555e000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-30 23:11:01.570  6520  6520 W art     : b555e000-b555f000 rw-p 00005000 b3:17 2510       /syste
08-30 23:11:01.570  6520  6520 W art     : m/lib/libpowermanager.so
08-30 23:11:01.570  6520  6520 W art     : b5560000-b557d000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 23:11:01.570  6520  6520 W art     : b557d000-b557e000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 23:11:01.570  6520  6520 W art     : b557e000-b557f000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 23:11:01.570  6520  6520 W art     : b5580000-b5585000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 23:11:01.570  6520  6520 W art     : b5585000-b5586000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 23:11:01.570  6520  6520 W art     : b5586000-b5587000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 23:11:01.570  6520  6520 W art     : b5588000-b55b9000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 23:11:01.570  6520  6520 W art     : b55b9000-b55ba000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b55ba000-b55bd000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 23:11:01.570  6520  6520 W art     : b55bd000-b55be000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 23:11:01.570  6520  6520 W art     : b55bf000-b55fa000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-30 23:11:01.570  6520  6520 W art     : b55fa000-b55fb000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-30 23:11:01.570  6520  6520 W art     : b55fb000-b55fc000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-30 23:11:01.570  6520  6520 W art     : b55fd000-b5604000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-30 23:11:01.570  6520  6520 W art     : b5604000-b5605000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5605000-b5606000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-30 23:11:01.570  6520  6520 W art     : b5606000-b5607000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-30 23:11:01.570  6520  6520 W art     : b5607000-b5608000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5608000-b561f000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-30 23:11:01.570  6520  6520 W art     : b561f000-b5620000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5620000-b5623000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-30 23:11:01.570  6520  6520 W art     : b5623000-b5624000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-30 23:11:01.570  6520  6520 W art     : b5624000-b5643000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-30 23:11:01.570  6520  6520 W art     : b5643000-b5644000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-30 23:11:01.570  6520  6520 W art     : b5644000-b5645000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-30 23:11:01.570  6520  6520 W art     : b5645000-b5683000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-30 23:11:01.570  6520  6520 W art     : b5683000-b5684000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5684000-b5686000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-30 23:11:01.570  6520  6520 W art     : b5686000-b5687000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-30 23:11:01.570  6520  6520 W art     : b5688000-b568f000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 23:11:01.570  6520  6520 W art     : b568f000-b5690000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 23:11:01.570  6520  6520 W art     : b5690000-b5691000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 23:11:01.570  6520  6520 W art     : b5692000-b5695000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 23:11:01.570  6520  6520 W art     : b5695000-b5696000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 23:11:01.570  6520  6520 W art     : b5696000-b5697000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 23:11:01.570  6520  6520 W art     : b5697000-b569d000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 23:11:01.570  6520  6520 W art     : b569d000-b569e000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b569e000-b569f000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 23:11:01.570  6520  6520 W art     : b569f000-b56a0000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 23:11:01.570  6520  6520 W art     : b56a0000-b56a9000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-30 23:11:01.570  6520  6520 W art     : b56a9000-b56aa000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-30 23:11:01.570  6520  6520 W art     : b56aa000-b56ab000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-30 23:11:01.570  6520  6520 W art     : b56ab000-b573c000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 23:11:01.570  6520  6520 W art     : b573c000-b573d000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b573d000-b5748000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 23:11:01.570  6520  6520 W art     : b5748000-b5749000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 23:11:01.570  6520  6520 W art     : b574a000-b575c000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-30 23:11:01.570  6520  6520 W art     : b575c000-b575d000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-30 23:11:01.570  6520  6520 W art     : b575d000-b575e000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-30 23:11:01.570  6520  6520 W art     : b575f000-b5764000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-30 23:11:01.570  6520  6520 W art     : b5764000-b5765000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-30 23:11:01.570  6520  6520 W art     : b5765000-b5766000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-30 23:11:01.570  6520  6520 W art     : b5767000-b57d4000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-30 23:11:01.570  6520  6520 W art     : b57d4000-b57d5000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b57d5000-b57d7000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-30 23:11:01.570  6520  6520 W art     : b57d7000-b57d8000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-30 23:11:01.570  6520  6520 W art     : b57d8000-b57d9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b57d9000-b57e0000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 23:11:01.570  6520  6520 W art     : b57e0000-b57e1000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 23:11:01.570  6520  6520 W art     : b57e1000-b57e2000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 23:11:01.570  6520  6520 W art     : b57e3000-b5863000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 23:11:01.570  6520  6520 W art     : b5863000-b5864000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5864000-b5865000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 23:11:01.570  6520  6520 W art     : b5865000-b5866000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 23:11:01.570  6520  6520 W art     : b5866000-b587d000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b587d000-b58b4000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 23:11:01.570  6520  6520 W art     : b58b4000-b58b5000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 23:11:01.570  6520  6520 W art     : b58b5000-b58b6000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 23:11:01.570  6520  6520 W art     : b58b6000-b58d2000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 23:11:01.570  6520  6520 W art     : b58d2000-b58d3000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 23:11:01.570  6520  6520 W art     : b58d3000-b58d4000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 23:11:01.570  6520  6520 W art     : b58d5000-b5936000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-30 23:11:01.570  6520  6520 W art     : b5936000-b5938000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-30 23:11:01.570  6520  6520 W art     : b5938000-b5939000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-30 23:11:01.570  6520  6520 W art     : b593a000-b595f000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-30 23:11:01.570  6520  6520 W art     : b595f000-b5960000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-30 23:11:01.570  6520  6520 W art     : b5960000-b5961000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-30 23:11:01.570  6520  6520 W art     : b5962000-b596a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 23:11:01.570  6520  6520 W art     : b596a000-b596c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 23:11:01.570  6520  6520 W art     : b596c000-b596d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 23:11:01.570  6520  6520 W art     : b596e000-b5971000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-30 23:11:01.570  6520  6520 W art     : b5971000-b5972000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-30 23:11:01.570  6520  6520 W art     : b5972000-b5973000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-30 23:11:01.570  6520  6520 W art     : b5973000-b5977000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-30 23:11:01.570  6520  6520 W art     : b5977000-b5978000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5978000-b5979000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-30 23:11:01.570  6520  6520 W art     : b5979000-b597a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-30 23:11:01.570  6520  6520 W art     : b597a000-b598a000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-30 23:11:01.570  6520  6520 W art     : b598a000-b598b000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-30 23:11:01.570  6520  6520 W art     : b598b000-b598c000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-30 23:11:01.570  6520  6520 W art     : b598c000-b59d2000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b59d2000-b59db000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-30 23:11:01.570  6520  6520 W art     : b59db000-b59dc000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-30 23:11:01.570  6520  6520 W art     : b59dc000-b59dd000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-30 23:11:01.570  6520  6520 W art     : b59de000-b59e3000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-30 23:11:01.570  6520  6520 W art     : b59e3000-b59e4000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-30 23:11:01.570  6520  6520 W art     : b59e4000-b59e5000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-30 23:11:01.570  6520  6520 W art     : b59e5000-b59e8000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 23:11:01.570  6520  6520 W art     : b59e8000-b59e9000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b59e9000-b59ea000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 23:11:01.570  6520  6520 W art     : b59ea000-b59eb000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 23:11:01.570  6520  6520 W art     : b59eb000-b59ec000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-30 23:11:01.570  6520  6520 W art     : or]
08-30 23:11:01.570  6520  6520 W art     : b59ec000-b5a04000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 23:11:01.570  6520  6520 W art     : b5a04000-b5a05000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5a05000-b5a06000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 23:11:01.570  6520  6520 W art     : b5a06000-b5a07000 rw-p 00019000 b3:
08-30 23:11:01.570  6520  6520 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-30 23:11:01.570  6520  6520 W art     : b5a08000-b5ba2000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-30 23:11:01.570  6520  6520 W art     : b5ba2000-b5ba3000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5ba3000-b5bb0000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-30 23:11:01.570  6520  6520 W art     : b5bb0000-b5bb1000 rw-p 001a7000 b3:17 604        /system/
08-30 23:11:01.570  6520  6520 W art     : lib/libstagefright.so
08-30 23:11:01.570  6520  6520 W art     : b5bb1000-b5bb5000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-30 23:11:01.570  6520  6520 W art     : b5bb5000-b5bb6000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5bb6000-b5bb7000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-30 23:11:01.570  6520  6520 W art     : b5bb7000-b5bb8000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-30 23:11:01.570  6520  6520 W art     : ersona.so
08-30 23:11:01.570  6520  6520 W art     : b5bb8000-b5bcb000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-30 23:11:01.570  6520  6520 W art     : b5bcb000-b5bcc000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-30 23:11:01.570  6520  6520 W art     : b5bcc000-b5bcd000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-30 23:11:01.570  6520  6520 W art     : b5bce000-b5c19000 r
08-30 23:11:01.570  6520  6520 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-30 23:11:01.570  6520  6520 W art     : b5c19000-b5c1a000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-30 23:11:01.570  6520  6520 W art     : b5c1a000-b5c1b000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-30 23:11:01.570  6520  6520 W art     : b5c1b000-b5c1d000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5c1d000-b5c1e000 r--p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5c1e000-b5c2f000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 23:11:01.570  6520  6520 W art     : b5c2f000-b5c30000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5c30000-b5c31000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 23:11:01.570  6520  6520 W art     : b5c31000-b5c32000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 23:11:01.570  6520  6520 W art     : b5c32000-b5c33000 r--p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5c33000-b5c3d000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-30 23:11:01.570  6520  6520 W art     : b5c3d000-b5c3f000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-30 23:11:01.570  6520  6520 W art     : b5c3f000-b5c40000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-30 23:11:01.570  6520  6520 W art     : b5c40000-b5c59000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-30 23:11:01.570  6520  6520 W art     : b5c59000-b5c5a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-30 23:11:01.570  6520  6520 W art     : b5c5a000-b5c5d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-30 23:11:01.570  6520  6520 W art     : b5c5d000-b5c61000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5c61000-b5cd5000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-30 23:11:01.570  6520  6520 W art     : b5cd5000-b5cd6000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5cd6000-b5cd9000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-30 23:11:01.570  6520  6520 W art     : b5cd9000-b5cda000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-30 23:11:01.570  6520  6520 W art     : b5cda000-b5cdb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5cdb000-b5cde000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-30 23:11:01.570  6520  6520 W art     : b5cde000-b5cdf000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-30 23:11:01.570  6520  6520 W art     : b5cdf000-b5ce0000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-30 23:11:01.570  6520  6520 W art     : b5ce0000-b5ce1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5ce1000-b5ce6000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 23:11:01.570  6520  6520 W art     : b5ce6000-b5ce7000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 23:11:01.570  6520  6520 W art     : b5ce7000-b5ce8000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 23:11:01.570  6520  6520 W art     : b5ce8000-b5ce9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5ce9000-b5cec000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 23:11:01.570  6520  6520 W art     : b5cec000-b5ced000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 23:11:01.570  6520  6520 W art     : b5ced000-b5cee000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 23:11:01.570  6520  6520 W art     : b5cee000-b5cef000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:01.570  6520  6520 W art     : b5cef000-b5cf3000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-30 23:11:01.570  6520  6520 W art     : b5cf3000-b5cf4000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-30 23:11:01.570  6520  6520 W art     : b5cf4000-b5cf5000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-30 23:11:01.570  6520  6520 W art     : b5cf5000-b5cf6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5cf6000-b5cfa000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 23:11:01.570  6520  6520 W art     : b5cfa000-b5cfb000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 23:11:01.570  6520  6520 W art     : b5cfb000-b5cfc000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 23:11:01.570  6520  6520 W art     : b5cfc000-b5cfd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5cfd000-b5d0b000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-30 23:11:01.570  6520  6520 W art     : b5d0b000-b5d0c000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b5d0c000-b5d0d000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-30 23:11:01.570  6520  6520 W art     : b5d0d000-b5d0e000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-30 23:11:01.570  6520  6520 W art     : b5d0e000-b5d18000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 23:11:01.570  6520  6520 W art     : b5d18000-b5d1b000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 23:11:01.570  6520  6520 W art     : b5d1b000-b5d1c000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 23:11:01.570  6520  6520 W art     : b5d1c000-b5d1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5d1d000-b5d27000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-30 23:11:01.570  6520  6520 W art     : b5d27000-b5d2a000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-30 23:11:01.570  6520  6520 W art     : b5d2a000-b5d2b000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-30 23:11:01.570  6520  6520 W art     : b5d2b000-b5d2f000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-30 23:11:01.570  6520  6520 W art     : b5d2f000-b5d30000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-30 23:11:01.570  6520  6520 W art     : b5d30000-b5d31000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-30 23:11:01.570  6520  6520 W art     : b5d31000-b5d32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b5d32000-b5d3f000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-30 23:11:01.570  6520  6520 W art     : b5d3f000-b5d41000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-30 23:11:01.570  6520  6520 W art     : b5d41000-b5d42000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-30 23:11:01.570  6520  6520 W art     : b5d42000-b6154000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-30 23:11:01.570  6520  6520 W art     : b6154000-b6155000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6155000-b615e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-30 23:11:01.570  6520  6520 W art     : b615e000-b6162000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-30 23:11:01.570  6520  6520 W art     : b6162000-b6163000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6163000-b616a000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-30 23:11:01.570  6520  6520 W art     : b616a000-b616b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-30 23:11:01.570  6520  6520 W art     : b616b000-b616c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-30 23:11:01.570  6520  6520 W art     : b616c000-b616d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b616d000-b6188000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-30 23:11:01.570  6520  6520 W art     : b6188000-b6189000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-30 23:11:01.570  6520  6520 W art     : b6189000-b618a000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-30 23:11:01.570  6520  6520 W art     : b618a000-b618b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b618b000-b61d7000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 23:11:01.570  6520  6520 W art     : b61d7000-b61d8000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b61d8000-b61d9000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 23:11:01.570  6520  6520 W art     : b61d9000-b61da000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 23:11:01.570  6520  6520 W art     : b61da000-b61db000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b61db000-b61df000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-30 23:11:01.570  6520  6520 W art     : b61df000-b61e0000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b61e0000-b61e1000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-30 23:11:01.570  6520  6520 W art     : b61e1000-b61e2000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-30 23:11:01.570  6520  6520 W art     : b61e2000-b621a000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-30 23:11:01.570  6520  6520 W art     : b621a000-b621b000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-30 23:11:01.570  6520  6520 W art     : b621b000-b621c000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-30 23:11:01.570  6520  6520 W art     : b621c000-b621d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.570  6520  6520 W art     : b621d000-b62bc000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-30 23:11:01.570  6520  6520 W art     : b62bc000-b62da000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-30 23:11:01.570  6520  6520 W art     : b62da000-b62db000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-30 23:11:01.570  6520  6520 W art     : b62db000-b644e000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-30 23:11:01.570  6520  6520 W art     : b644e000-b6459000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-30 23:11:01.570  6520  6520 W art     : b6459000-b645a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-30 23:11:01.570  6520  6520 W art     : b645a000-b6571000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-30 23:11:01.570  6520  6520 W art     : b6571000-b657c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-30 23:11:01.570  6520  6520 W art     : b657c000-b657d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-30 23:11:01.570  6520  6520 W art     : b657d000-b6581000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6581000-b65a5000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-30 23:11:01.570  6520  6520 W art     : b65a5000-b65a7000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-30 23:11:01.570  6520  6520 W art     : b65a7000-b65a8000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-30 23:11:01.570  6520  6520 W art     : b65a8000-b664e000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-30 23:11:01.570  6520  6520 W art     : b664e000-b665b000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-30 23:11:01.570  6520  6520 W art     : b665b000-b665c000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-30 23:11:01.570  6520  6520 W art     : b665c000-b665d000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b665d000-b66b0000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-30 23:11:01.570  6520  6520 W art     : b66b0000-b66b1000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b66b1000-b66b2000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-30 23:11:01.570  6520  6520 W art     : b66b2000-b66b3000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-30 23:11:01.570  6520  6520 W art     : b66b3000-b66b8000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b66b8000-b66ca000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-30 23:11:01.570  6520  6520 W art     : b66ca000-b66cb000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b66cb000-b66cc000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-30 23:11:01.570  6520  6520 W art     : b66cc000-b66cd000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-30 23:11:01.570  6520  6520 W art     : b66cd000-b66d4000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 23:11:01.570  6520  6520 W art     : b66d4000-b66d5000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 23:11:01.570  6520  6520 W art     : b66d5000-b66d6000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 23:11:01.570  6520  6520 W art     : b66d6000-b66d7000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b66d7000-b66da000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-30 23:11:01.570  6520  6520 W art     : b66da000-b66db000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-30 23:11:01.570  6520  6520 W art     : b66db000-b66dc000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-30 23:11:01.570  6520  6520 W art     : b66dc000-b66e0000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-30 23:11:01.570  6520  6520 W art     : b66e0000-b66e1000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-30 23:11:01.570  6520  6520 W art     : b66e1000-b66e2000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-30 23:11:01.570  6520  6520 W art     : b66e2000-b66f0000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-30 23:11:01.570  6520  6520 W art     : b66f0000-b66f1000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b66f1000-b66f2000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-30 23:11:01.570  6520  6520 W art     : b66f2000-b66f3000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-30 23:11:01.570  6520  6520 W art     : b66f3000-b66fc000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 23:11:01.570  6520  6520 W art     : b66fc000-b66fd000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 23:11:01.570  6520  6520 W art     : b66fd000-b66fe000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 23:11:01.570  6520  6520 W art     : b66fe000-b6764000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-30 23:11:01.570  6520  6520 W art     : b6764000-b6765000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6765000-b6767000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-30 23:11:01.570  6520  6520 W art     : b6767000-b6770000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-30 23:11:01.570  6520  6520 W art     : b6770000-b6773000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6773000-b680a000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-30 23:11:01.570  6520  6520 W art     : b680a000-b680c000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-30 23:11:01.570  6520  6520 W art     : b680c000-b680d000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-30 23:11:01.570  6520  6520 W art     : b680d000-b680e000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b680e000-b6b2c000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-30 23:11:01.570  6520  6520 W art     : b6b2c000-b6b2d000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6b2d000-b6b48000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-30 23:11:01.570  6520  6520 W art     : b6b48000-b6b4c000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-30 23:11:01.570  6520  6520 W art     : b6b4c000-b6b51000 rw-p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6b51000-b6b59000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 23:11:01.570  6520  6520 W art     : b6b59000-b6b5a000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 23:11:01.570  6520  6520 W art     : b6b5a000-b6b5b000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 23:11:01.570  6520  6520 W art     : b6b5b000-b6b89000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-30 23:11:01.570  6520  6520 W art     : b6b89000-b6b8a000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6b8a000-b6b91000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-30 23:11:01.570  6520  6520 W art     : b6b91000-b6b92000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-30 23:11:01.570  6520  6520 W art     : b6b92000-b6bd8000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-30 23:11:01.570  6520  6520 W art     : b6bd8000-b6bd9000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6bd9000-b6bdc000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-30 23:11:01.570  6520  6520 W art     : b6bdc000-b6bdd000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-30 23:11:01.570  6520  6520 W art     : b6bdd000-b6bf8000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-30 23:11:01.570  6520  6520 W art     : b6bf8000-b6bfc000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-30 23:11:01.570  6520  6520 W art     : b6bfc000-b6bfd000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-30 23:11:01.570  6520  6520 W art     : b6bfd000-b6c4a000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-30 23:11:01.570  6520  6520 W art     : b6c4a000-b6c4b000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6c4b000-b6c57000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-30 23:11:01.570  6520  6520 W art     : b6c57000-b6c58000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-30 23:11:01.570  6520  6520 W art     : b6c58000-b6c65000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-30 23:11:01.570  6520  6520 W art     : b6c65000-b6c66000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6c66000-b6c67000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-30 23:11:01.570  6520  6520 W art     : b6c67000-b6c68000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-30 23:11:01.570  6520  6520 W art     : b6c68000-b6c70000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-30 23:11:01.570  6520  6520 W art     : b6c70000-b6c71000 ---p 00000000 00:00 0 
08-30 23:11:01.570  6520  6520 W art     : b6c71000-b6c72000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-30 23:11:01.570  6520  6520 W art     : b6c72000-b6c73000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-30 23:11:01.570  6520  6520 W art     : b6c73000-b6c7a000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-30 23:11:01.570  6520  6520 W art     : b6c7a000-b6c7b000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-30 23:11:01.570  6520  6520 W art     : b6c7b000-b6c7c000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-30 23:11:01.570  6520  6520 W art     : b6c7c000-b6c90000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-30 23:11:01.570  6520  6520 W art     : b6c90000-b6c92000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-30 23:11:01.570  6520  6520 W art     : b6c92000-b6c93000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-30 23:11:01.570  6520  6520 W art     : b6c93000-b6cbb000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-30 23:11:01.570  6520  6520 W art     : b6cbb000-b6cbd000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-30 23:11:01.570  6520  6520 W art     : b6cbd000-b6cbe000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-30 23:11:01.580  6520  6520 W art     : b6cbe000-b6cc1000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-30 23:11:01.580  6520  6520 W art     : b6cc1000-b6cc2000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-30 23:11:01.580  6520  6520 W art     : b6cc2000-b6cc3000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-30 23:11:01.580  6520  6520 W art     : b6cc3000-b6ccc000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-30 23:11:01.580  6520  6520 W art     : b6ccc000-b6ccd000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-30 23:11:01.580  6520  6520 W art     : b6ccd000-b6cce000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-30 23:11:01.580  6520  6520 W art     : b6cce000-b6cee000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-30 23:11:01.580  6520  6520 W art     : b6cee000-b6cef000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-30 23:11:01.580  6520  6520 W art     : b6cef000-b6cf0000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-30 23:11:01.580  6520  6520 W art     : b6cf0000-b6d63000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-30 23:11:01.580  6520  6520 W art     : b6d63000-b6d67000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-30 23:11:01.580  6520  6520 W art     : b6d67000-b6d6a000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-30 23:11:01.580  6520  6520 W art     : b6d6a000-b6d74000 rw-p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6d74000-b6dfc000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-30 23:11:01.580  6520  6520 W art     : b6dfc000-b6dfd000 ---p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6dfd000-b6e01000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-30 23:11:01.580  6520  6520 W art     : b6e01000-b6e02000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-30 23:11:01.580  6520  6520 W art     : b6e02000-b6e03000 rw-p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6e03000-b6e2c000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-30 23:11:01.580  6520  6520 W art     : b6e2c000-b6e2d000 ---p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6e2d000-b6e30000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-30 23:11:01.580  6520  6520 W art     : b6e30000-b6e31000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-30 23:11:01.580  6520  6520 W art     : b6e31000-b6f0b000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 23:11:01.580  6520  6520 W art     : b6f0b000-b6f12000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 23:11:01.580  6520  6520 W art     : b6f12000-b6f1a000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 23:11:01.580  6520  6520 W art     : b6f1a000-b6f1b000 rw-p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6f1b000-b6f1c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:01.580  6520  6520 W art     : b6f1c000-b6f1d000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-30 23:11:01.580  6520  6520 W art     : b6f1d000-b6f1e000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.580  6520  6520 W art     : b6f1e000-b6f21000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.580  6520  6520 W art     : b6f21000-b6f46000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-30 23:11:01.580  6520  6520 W art     : b6f46000-b6f47000 ---p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6f47000-b6f4e000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-30 23:11:01.580  6520  6520 W art     : b6f4e000-b6f4f000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-30 23:11:01.580  6520  6520 W art     : b6f4f000-b6f56000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-30 23:11:01.580  6520  6520 W art     : b6f56000-b6f57000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-30 23:11:01.580  6520  6520 W art     : b6f57000-b6f58000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-30 23:11:01.580  6520  6520 W art     : b6f58000-b6f59000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.580  6520  6520 W art     : b6f59000-b6f71000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-30 23:11:01.580  6520  6520 W art     : b6f71000-b6f72000 ---p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6f72000-b6f73000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-30 23:11:01.580  6520  6520 W art     : b6f73000-b6f74000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-30 23:11:01.580  6520  6520 W art     : b6f74000-b6f82000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-30 23:11:01.580  6520  6520 W art     : b6f82000-b6f83000 ---p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6f83000-b6f84000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-30 23:11:01.580  6520  6520 W art     : b6f84000-b6f85000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-30 23:11:01.580  6520  6520 W art     : b6f85000-b6f86000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:01.580  6520  6520 W art     : b6f86000-b6f88000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.580  6520  6520 W art     : b6f88000-b6f89000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.580  6520  6520 W art     : b6f89000-b6f8a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:01.580  6520  6520 W art     : b6f8a000-b6f8b000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-30 23:11:01.580  6520  6520 W art     : b6f8b000-b6f8c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:01.580  6520  6520 W art     : b6f8c000-b6fac000 r--s 00000000 00:0b 7184       /dev/__properties__
08-30 23:11:01.580  6520  6520 W art     : b6fac000-b6fad000 r--p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6fad000-b6fae000 ---p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6fae000-b6fb0000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-30 23:11:01.580  6520  6520 W art     : b6fb0000-b6fb1000 r-xp 00000000 00:00 0          [sigpage]
08-30 23:11:01.580  6520  6520 W art     : b6fb1000-b6fcc000 r-xp 00000000 b3:17 341        /system/bin/linker
08-30 23:11:01.580  6520  6520 W art     : b6fcc000-b6fcd000 r--p 0001a000 b3:17 341        /system/bin/linker
08-30 23:11:01.580  6520  6520 W art     : b6fcd000-b6fcf000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-30 23:11:01.580  6520  6520 W art     : b6fcf000-b6fd1000 rw-p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : b6fd1000-b6fd6000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-30 23:11:01.580  6520  6520 W art     : b6fd6000-b6fd7000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-30 23:11:01.580  6520  6520 W art     : b6fd7000-b6fd8000 rw-p 00000000 00:00 0 
08-30 23:11:01.580  6520  6520 W art     : be89a000-be8bb000 rw-p 00000000 00:00 0          [stack]
08-30 23:11:01.580  6520  6520 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-30 23:11:01.620  6520  6520 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 23:11:01.680  6520  6520 I Radio-JNI: register_android_hardware_Radio DONE
08-30 23:11:01.690  6520  6520 E AffinityControl: AffinityControl: registerfunction enter
08-30 23:11:01.710  6520  6520 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 23:11:01.730   779  1767 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:01.740   779  1767 D ActivityManager: mDVFSHelper.acquire()
08-30 23:11:01.740   779  1767 D FocusedStackFrame: Set to : 0
08-30 23:11:01.740   779  1767 V WindowManager: addAppToken: AppWindowToken{80b57b7 token=Token{7b53eb6 ActivityRecord{d107651 u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-30 23:11:01.750   779   918 D SecWifiDisplayUtil: Metadata value : none
08-30 23:11:01.750   779   918 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9f786af V.E...... R.....ID 0,0-0,0}
08-30 23:11:01.750   779   918 D ISSUE_DEBUG: InputChannelName : a259a45 Starting com.test.thalitest
08-30 23:11:01.770   779  1767 I ActivityManager: Start proc 6541:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-30 23:11:01.770   779  1767 D InputDispatcher: Focused application set to: xxxx
08-30 23:11:01.770  6541  6541 E Zygote  : v2
08-30 23:11:01.770  6541  6541 I libpersona: KNOX_SDCARD checking this for 10004
08-30 23:11:01.770  6541  6541 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:01.770  6541  6541 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:01.770   779  1767 D InputDispatcher: Focus left window: 1733
08-30 23:11:01.770  6541  6541 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:01.770   294   294 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-30 23:11:01.770   779  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-30 23:11:01.770  6520  6520 D AndroidRuntime: Shutting down VM
08-30 23:11:01.770  6541  6541 E Zygote  : accessInfo : 0
08-30 23:11:01.770  6541  6541 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-30 23:11:01.790   779   918 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
08-30 23:11:01.790   779   918 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:11:01.790   779   918 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
08-30 23:11:01.790   779   918 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-30 23:11:01.790   779   918 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-30 23:11:01.810  6541  6541 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:01.810  6541  6541 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:01.810   779  1621 V WindowOrientationListener: setCurrentAppOrientation :-1
08-30 23:11:01.810   779  1621 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-30 23:11:01.820   779   870 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a259a45 u0 d0 Starting com.test.thalitest}
08-30 23:11:01.820  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-30 23:11:01.820   779  1621 D ActivityManager:  Launching com.test.thalitest, updated priority
08-30 23:11:01.830  1733  1857 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-30 23:11:01.830  1733  1733 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-30 23:11:01.840   779   918 V WindowStateAnimator: Finishing drawing window Window{a259a45 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-30 23:11:01.850   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbee3d364
08-30 23:11:01.860   294   369 D libEGL  : eglTerminate EGLDisplay = 0xb670e64c
08-30 23:11:01.860   294   369 D libEGL  : eglTerminate EGLDisplay = 0xb670e64c
08-30 23:11:01.880   294  4870 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-30 23:11:01.880   294   369 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-30 23:11:01.880   779   867 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-30 23:11:01.890   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d3a4
08-30 23:11:01.890   779  1320 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-30 23:11:01.900  6541  6541 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 23:11:01.900   779  3640 D M       : limitCPUFreq:: freq = -1
08-30 23:11:01.900   779  3640 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 779  tag : SIOP_ARM_MAX@25
08-30 23:11:01.900   779  3640 D M       : limitGPUFreq:: freq = -1
08-30 23:11:01.910   779  3640 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-30 23:11:01.910  2226  2240 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-30 23:11:01.920  1733  1733 V ActivityThread: updateVisibility : ActivityRecord{4c9d5d3 token=android.os.BinderProxy@e743c6e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 23:11:01.920  1733  1733 D Launcher: onTrimMemory. Level: 20
08-30 23:11:01.930  6541  6541 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 23:11:01.930  6541  6541 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 23:11:01.950  6541  6541 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
08-30 23:11:01.980  6541  6541 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
08-30 23:11:01.990  6541  6541 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 23:11:02.010  6541  6541 I cr_LibraryLoader: Time to load native libraries: 13 ms (timestamps 6478-6491)
08-30 23:11:02.010  6541  6541 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-30 23:11:02.020   779   789 I art     : Background partial concurrent mark sweep GC freed 45766(2MB) AllocSpace objects, 4(220KB) LOS objects, 27% free, 42MB/58MB, paused 1.783ms total 142.070ms
,08-30 23:11:02.030  6541  6541 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cc09539}
08-30 23:11:02.030  6541  6541 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-30 23:11:02.030  6541  6541 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 23:11:02.030  6541  6556 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-30 23:11:02.040  6541  6541 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 23:11:02.070  6541  6541 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 23:11:02.070  6541  6541 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 23:11:02.070  6541  6541 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 23:11:02.070  6541  6541 I Adreno-EGL: Local Branch: ss
08-30 23:11:02.070  6541  6541 I Adreno-EGL: Remote Branch: 
08-30 23:11:02.070  6541  6541 I Adreno-EGL: Local Patches: 
08-30 23:11:02.070  6541  6541 I Adreno-EGL: Reconstruct Branch: 
,08-30 23:11:02.080  6541  6541 D libEGL  : eglInitialize EGLDisplay = 0xbea10dac
,08-30 23:11:02.120   779  1752 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-30 23:11:02.120   779  1752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-30 23:11:02.180  6541  6541 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-30 23:11:02.190  6541  6541 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 23:11:02.190  6541  6541 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-30 23:11:02.190  6541  6541 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-30 23:11:02.190  6541  6541 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-30 23:11:02.200  6541  6541 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-30 23:11:02.210  6541  6541 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 23:11:02.280  6541  6541 D SecWifiDisplayUtil: Metadata value : none
,08-30 23:11:02.290  6541  6541 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1be2cde I.E...... R.....ID 0,0-0,0}
,08-30 23:11:02.290  6541  6580 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 23:11:02.290   779  1621 D ISSUE_DEBUG: InputChannelName : f434bee com.test.thalitest/com.test.thalitest.MainActivity
,08-30 23:11:02.300   779  1413 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-30 23:11:02.300   779  1413 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 23:11:02.300   779   779 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 23:11:02.310   779   779 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-30 23:11:02.320  6541  6541 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6541
,08-30 23:11:02.320   779  1767 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6541 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:11:02.320   779  1329 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-30 23:11:02.320   779  1329 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 23:11:02.320   779  1329 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-30 23:11:02.320   779  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 23:11:02.320   779  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 23:11:02.320   779  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 23:11:02.320   779  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-30 23:11:02.320   779  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-30 23:11:02.320   779  1329 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-30 23:11:02.320   779  1329 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:11:02.330  6541  6541 D SecWifiDisplayUtil: Metadata value : none
,08-30 23:11:02.330  6541  6556 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-30 23:11:02.340   294   294 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-30 23:11:02.350   779   792 D InputDispatcher: Focus entered window: 6541
,08-30 23:11:02.350   779   918 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
,08-30 23:11:02.350   779   918 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:11:02.350   779   918 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
08-30 23:11:02.350   779   918 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 23:11:02.350  6541  6580 D libEGL  : eglInitialize EGLDisplay = 0x9cabf7c4
08-30 23:11:02.350  6541  6580 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 23:11:02.400  6541  6541 V ActivityThread: updateVisibility : ActivityRecord{3e63d51 token=android.os.BinderProxy@1d2419 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 23:11:02.400  6541  6541 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-30 23:11:02.400  6541  6541 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 23:11:02.430   779   793 V WindowStateAnimator: Finishing drawing window Window{f434bee u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-30 23:11:02.430  6541  6541 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-30 23:11:02.430   779  1751 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 23:11:02.430   779   918 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 23:11:02.430   779   779 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-30 23:11:02.430   779   779 I KnoxTimeoutHandler: SD activityfalse
,08-30 23:11:02.430   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbee3d364
,08-30 23:11:02.430   779   918 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +550ms (total +678ms)
,08-30 23:11:02.430   779   918 D ActivityManager: mDVFSHelper.release()
,08-30 23:11:02.440   779   918 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d107651 u0 com.test.thalitest/.MainActivity t167} time:106920
,08-30 23:11:02.440   779   918 D ViewRootImpl: #3 mView = null
,08-30 23:11:02.440   294  1749 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-30 23:11:02.440  6541  6541 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-30 23:11:02.440   294   369 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-30 23:11:02.450   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d3a4
,08-30 23:11:02.450  6541  6541 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d2419 time:106935
,08-30 23:11:02.480  6541  6588 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:11:02.480  6541  6588 D libEGL  : eglInitialize EGLDisplay = 0x9b5ea3ec
,08-30 23:11:02.530  6541  6541 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6541
,08-30 23:11:02.610  6541  6541 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 23:11:02.750  5523  5523 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-30 23:11:02.750  5523  5523 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-30 23:11:02.750  5523  5523 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-30 23:11:02.760  5523  5523 I art     : System.exit called, status: 0
08-30 23:11:02.760  5523  5523 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 23:11:02.760  6541  6595 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1696593616
,08-30 23:11:02.760  6541  6595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 23:11:02.760  6541  6595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 23:11:02.760  6541  6595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 23:11:02.760  6541  6595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 23:11:02.760  6541  6595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 23:11:02.760  6541  6595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57105af added. We now have 1 listener(s)
,08-30 23:11:02.770  6541  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-30 23:11:02.770  6541  6595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-30 23:11:02.770  6541  6595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 23:11:02.770  6541  6595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 23:11:02.770  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 23:11:02.780  6541  6595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68cb09a added. We now have 1 listener(s)
,08-30 23:11:02.780  6541  6595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 23:11:02.780  6541  6595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
08-30 23:11:02.790  6541  6595 D BluetoothAdapter: STATE_ON
08-30 23:11:02.790  6541  6595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:02.790  6541  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 23:11:02.790  6541  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 23:11:02.790  6541  6595 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 23:11:02.790  6541  6595 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 23:11:02.790  6541  6541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:11:02.790  6541  6541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:11:02.810   779  1747 I ActivityManager: Process com.samsung.aasaservice (pid 5523)(adj 0) has died(102,754)
,08-30 23:11:02.810   779  1747 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-30 23:11:02.810   779  1747 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-30 23:11:02.810   779  1747 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,08-30 23:11:02.810  5478  5478 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
,08-30 23:11:02.820  6598  6598 E Zygote  : v2
08-30 23:11:02.820  6598  6598 I libpersona: KNOX_SDCARD checking this for 10014
08-30 23:11:02.820  6598  6598 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:02.820   779   867 I ActivityManager: Start proc 6598:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-30 23:11:02.820   779  1320 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-30 23:11:02.820  6598  6598 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:02.820  6598  6598 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:02.830  6598  6598 E Zygote  : accessInfo : 0
08-30 23:11:02.830  6598  6598 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-30 23:11:02.830  6541  6541 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 23:11:02.850  6598  6598 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:02.850  6598  6598 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:02.850   779  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc22ad9 6598:com.google.android.partnersetup/u0a14}
,08-30 23:11:02.850   779  1320 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-30 23:11:02.860  6598  6598 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
,08-30 23:11:02.880  6598  6598 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-30 23:11:02.890   779  3647 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:02.910   779  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc22ad9 6598:com.google.android.partnersetup/u0a14}
,08-30 23:11:02.920  6613  6613 E Zygote  : v2
,08-30 23:11:02.920  6613  6613 I libpersona: KNOX_SDCARD checking this for 10015
08-30 23:11:02.930  6613  6613 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:02.930  6613  6613 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:02.930  6613  6613 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:02.930  6613  6613 E Zygote  : accessInfo : 0
,08-30 23:11:02.930  6613  6613 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
,08-30 23:11:02.930   779  1409 I ActivityManager: Start proc 6613:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
,08-30 23:11:02.940   779  1413 I ActivityManager: Killing 5661:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
,08-30 23:11:02.960  6613  6613 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:02.960  6613  6613 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:02.960   779  1751 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,08-30 23:11:02.970   779   793 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eb8cf4c 6613:com.samsung.groupcast/u0a15}
,08-30 23:11:02.970  6613  6613 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
,08-30 23:11:02.990  6613  6613 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
,08-30 23:11:03.000  6613  6613 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
,08-30 23:11:03.010  6613  6613 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,08-30 23:11:03.010  6613  6613 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-30 23:11:03.010  6613  6613 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-30 23:11:03.010  6613  6613 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
,08-30 23:11:03.010  6613  6613 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-30 23:11:03.010  6613  6613 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-30 23:11:03.010  6613  6613 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-30 23:11:03.010  6613  6613 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 23:11:03.010  6613  6613 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:11:03.010  6613  6613 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,08-30 23:11:03.010  6613  6613 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 23:11:03.010  6613  6613 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:11:03.010  6613  6613 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 23:11:03.010  6613  6613 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-30 23:11:03.010   779  1751 I ActivityManager: Killing 5355:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-30 23:11:03.020   779  1751 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{967ef2d 1870:com.sec.android.app.shealth:remote/u0a34}
,08-30 23:11:03.030   779   793 D CountryDetector: No listener is left
,08-30 23:11:03.030  6625  6625 E Zygote  : v2
08-30 23:11:03.030  6625  6625 I libpersona: KNOX_SDCARD checking this for 10041
08-30 23:11:03.030  6625  6625 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:03.040  6625  6625 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:03.040  6625  6625 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:03.040   779  1570 I ActivityManager: Start proc 6625:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,08-30 23:11:03.040  6625  6625 E Zygote  : accessInfo : 0
08-30 23:11:03.040  6625  6625 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-30 23:11:03.040   779  1621 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-30 23:11:03.060  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:03.060  6625  6625 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:03.070   779  2437 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4a19b95 6625:com.samsung.android.sdk.samsunglink/u0a41}
,08-30 23:11:03.080  6625  6625 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
,08-30 23:11:03.140  6625  6625 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-30 23:11:03.140  6625  6625 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 23:11:03.180   779  3680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:11:03.180  6625  6625 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-30 23:11:03.190  6625  6625 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-30 23:11:03.200   779  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.200   779  1752 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-30 23:11:03.200   779  2437 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.200   779  2441 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.210   779  1409 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.210   779  1413 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.210   779  1745 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.210   779  1767 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.210   779  1622 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.220   779   793 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-30 23:11:03.300  1452  1452 D Recents : onTaskStackChanged
,08-30 23:11:03.310  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-30 23:11:03.320  6625  6625 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-30 23:11:03.320  6625  6625 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
,08-30 23:11:03.320  6625  6625 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-30 23:11:03.320  6625  6625 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-30 23:11:03.320  6625  6625 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
,08-30 23:11:03.320  6625  6625 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-30 23:11:03.320  6625  6625 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-30 23:11:03.320  6625  6625 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
,08-30 23:11:03.320  6625  6625 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-30 23:11:03.320  6625  6625 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 23:11:03.320  6625  6625 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:11:03.320  6625  6625 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,08-30 23:11:03.320  6625  6625 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 23:11:03.320  6625  6625 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:11:03.320  6625  6625 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
,08-30 23:11:03.320  6625  6625 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-30 23:11:03.330   779   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{37318ec 1634:android.process.acore/u0a19}
,08-30 23:11:03.340   779  2437 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{431c3e3 5193:com.sec.android.gallery3d/u0a47}
,08-30 23:11:03.340  5193  5193 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-30 23:11:03.350   779  1767 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:11:03.360  6648  6648 E Zygote  : v2
08-30 23:11:03.360  6648  6648 I libpersona: KNOX_SDCARD checking this for 10050
08-30 23:11:03.360  6648  6648 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:03.360  6648  6648 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:03.360  6648  6648 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:03.360   779  1622 I ActivityManager: Start proc 6648:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-30 23:11:03.360  6648  6648 E Zygote  : accessInfo : 0
08-30 23:11:03.360  6648  6648 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-30 23:11:03.390  6648  6648 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:03.390  6648  6648 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:03.400   779  1751 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{da19405 6648:com.sec.android.app.myfiles/u0a50}
,08-30 23:11:03.410  6648  6648 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-30 23:11:03.420  6648  6648 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-30 23:11:03.460  6648  6648 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-30 23:11:03.460   779  2441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a33156 5062:com.android.settings/1000}
,08-30 23:11:03.480   330   330 E installd: system dir 0 : /system/app/
08-30 23:11:03.480   330   330 E installd: system dir 1 : /system/priv-app/
08-30 23:11:03.480   330   330 E installd: system dir 2 : /vendor/app/
08-30 23:11:03.480   330   330 E installd: system dir 3 : /oem/app/
,08-30 23:11:03.490   779   949 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-30 23:11:03.500   779   793 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a33156 5062:com.android.settings/1000}
,08-30 23:11:03.520  6663  6663 E Zygote  : v2
,08-30 23:11:03.520  6663  6663 I libpersona: KNOX_SDCARD checking this for 10169
08-30 23:11:03.520  6663  6663 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:03.520  6663  6663 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-30 23:11:03.520   779  1747 I ActivityManager: Start proc 6663:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-30 23:11:03.520  6663  6663 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:03.530  6663  6663 E Zygote  : accessInfo : 0
,08-30 23:11:03.530  6663  6663 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-30 23:11:03.560  6663  6663 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:03.560  6663  6663 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:03.570   779   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ac6b81 6663:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-30 23:11:03.580  6663  6663 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-30 23:11:03.590  6663  6663 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-30 23:11:03.610   779  1747 I ActivityManager: Killing 5674:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,08-30 23:11:03.610   779  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9b0e425 1717:com.android.phone/1001}
,08-30 23:11:03.620   779  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8308d6d 1816:com.google.android.googlequicksearchbox:search/u0a61}
,08-30 23:11:03.640   779   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8308d6d 1816:com.google.android.googlequicksearchbox:search/u0a61}
,08-30 23:11:03.650   779  1409 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
,08-30 23:11:03.660   779  1745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e1c867 6467:com.samsung.android.sm.provider/1000}
,08-30 23:11:03.660  1816  6675 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 23:11:03.690  6541  6597 W jxcore-log: Initializing JXcore engine
,08-30 23:11:03.690  6541  6597 W jxcore-log: JXcore engine is ready
,08-30 23:11:03.690  6678  6678 E Zygote  : v2
08-30 23:11:03.690  6678  6678 I libpersona: KNOX_SDCARD checking this for 5012
08-30 23:11:03.690  6678  6678 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:03.690  6678  6678 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:03.690  6678  6678 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:03.690  6678  6678 E Zygote  : accessInfo : 0
,08-30 23:11:03.690  6678  6678 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-30 23:11:03.690   779  1751 I ActivityManager: Start proc 6678:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-30 23:11:03.720  6678  6678 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:03.720  6678  6678 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:03.730   779  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1dbe614 6678:com.samsung.android.sm.devicesecurity/5012}
08-30 23:11:03.730  2331  2331 E audit   : type=1400 msg=audit(1472591463.730:287): avc:  denied  { ioctl } for  pid=6597 comm="Thread-899" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 23:11:03.730  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:03.730  2331  2331 E audit   : type=1300 msg=audit(1472591463.730:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9acfb3c8 items=0 ppid=353 ppcomm=main pid=6597 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 23:11:03.730  2331  2331 E audit   : type=1327 msg=audit(1472591463.730:287): proctitle="com.test.thalitest"
08-30 23:11:03.730  2331  2331 E audit   : type=1320 msg=audit(1472591463.730:287): 
08-30 23:11:03.740  2331  2331 E audit   : type=1400 msg=audit(1472591463.730:288): avc:  denied  { ioctl } for  pid=6597 comm="Thread-899" path="socket:[40280]" dev="sockfs" ino=40280 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 23:11:03.740  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:03.740  2331  2331 E audit   : type=1300 msg=audit(1472591463.730:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9acfb3c8 items=0 ppid=353 ppcomm=main pid=6597 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-30 23:11:03.740  2331  2331 E audit   : type=1327 msg=audit(1472591463.730:288): proctitle="com.test.thalitest"
08-30 23:11:03.740  2331  2331 E audit   : type=1320 msg=audit(1472591463.730:288): 
08-30 23:11:03.740  1816  6675 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-30 23:11:03.740  6678  6678 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-30 23:11:03.750  6541  6597 W jxcore-log: Starting JXcore engine
08-30 23:11:03.750  1816  6675 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-30 23:11:03.750  6678  6678 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-30 23:11:03.790   779  2437 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-30 23:11:03.790   779  1570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{805f3ee 3196:com.android.contacts/u0a19}
08-30 23:11:03.810  6690  6690 E Zygote  : v2
08-30 23:11:03.810  6690  6690 I libpersona: KNOX_SDCARD checking this for 10049
08-30 23:11:03.810  6690  6690 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:03.810  6690  6690 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:03.810  6690  6690 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:03.810  6690  6690 E Zygote  : accessInfo : 0
08-30 23:11:03.810  6690  6690 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-30 23:11:03.810   779  1409 I ActivityManager: Start proc 6690:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-30 23:11:03.830  6700  6700 E Zygote  : v2
08-30 23:11:03.830  6700  6700 I libpersona: KNOX_SDCARD checking this for 10210
08-30 23:11:03.830  6700  6700 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:03.830  6700  6700 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:03.830  6700  6700 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:03.830   779   867 I ActivityManager: Start proc 6700:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-30 23:11:03.830  6700  6700 E Zygote  : accessInfo : 0
08-30 23:11:03.840  6700  6700 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
08-30 23:11:03.850  6541  6597 W jxcore-log: Platform android
08-30 23:11:03.850  6541  6597 W jxcore-log: 
08-30 23:11:03.850  6541  6597 W jxcore-log: Process ARCH arm
08-30 23:11:03.850  6541  6597 W jxcore-log: 
08-30 23:11:03.860  6690  6690 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:03.860  6690  6690 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:03.860   779  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b55d5f 6690:com.android.mms/u0a49}
08-30 23:11:03.890  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:03.890  6700  6700 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:03.890  6690  6690 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-30 23:11:03.910  6700  6700 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
08-30 23:11:03.930  6690  6690 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-30 23:11:03.940  4474  6714 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-30 23:11:03.940  6700  6700 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
08-30 23:11:03.940  6700  6700 D AASAservice: onCreate()
08-30 23:11:03.950  5478  5478 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-30 23:11:03.960  6690  6690 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-30 23:11:03.960   779  1622 I ActivityManager: Killing 5244:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
08-30 23:11:03.970  6690  6690 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-30 23:11:03.980  6690  6717 D Mms/ArtClassLoader: init before art third
08-30 23:11:03.990   779  1752 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
08-30 23:11:03.990  1816  6675 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 330 ms] updated apps [took 330 ms] 
08-30 23:11:03.990  6690  6690 D Mms/TelephonyPermission: start operation mode monitor
08-30 23:11:03.990  6690  6690 D Mms/TelephonyPermission: User ID is null set current User Id
08-30 23:11:04.000  6690  6716 D Mms/ArtClassLoader: init before art second
08-30 23:11:04.000  6690  6715 D Mms/ArtClassLoader: init before art first
08-30 23:11:04.010  6690  6690 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-30 23:11:04.010  6690  6690 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-30 23:11:04.020  6690  6717 D Mms/ArtClassLoader: init [DONE] art
08-30 23:11:04.030  6690  6690 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-30 23:11:04.030  6690  6690 D Mms/TelephonyPermission: isDefault true
08-30 23:11:04.030  6690  6690 D Mms/MmsApp: onCreate() com.android.mms
08-30 23:11:04.060  6690  6690 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
08-30 23:11:04.070  6690  6690 D Mms/MmsApp: [start]    initCountryIso consume time = 94.335886
08-30 23:11:04.070   779  2437 D CountryDetector: The first listener is added
08-30 23:11:04.070  6690  6690 D Mms/MmsApp: [end]    initCountryIso consume time = 7.375676
08-30 23:11:04.070  6690  6690 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.100157
08-30 23:11:04.070  6541  6597 I jxcore-log: JXcore Cordova bridge is ready!
08-30 23:11:04.070  6541  6597 I jxcore-log: 
08-30 23:11:04.070  6541  6597 W jxcore-log: JXcore engine is started
08-30 23:11:04.080  6541  6595 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 23:11:04.080  6690  6690 D Mms/MmsConfig: before partial update
08-30 23:11:04.080  6541  6541 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 23:11:04.110  6690  6715 D Mms/ArtClassLoader: init [DONE] art
08-30 23:11:04.120  6690  6690 D Mms/MmsConfig: Load Resize quality : 80
08-30 23:11:04.140  6690  6690 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-30 23:11:04.140  6690  6690 D EasySignUpManager_1.0.5: isAuth is false
08-30 23:11:04.140  6690  6690 I EasySignUpManager_1.0.5: auth : false, join : 2
08-30 23:11:04.140  6690  6690 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
08-30 23:11:04.140  6690  6690 D EasySignUpManager_1.0.5: userSerialNumber = 0
08-30 23:11:04.140  6690  6690 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-30 23:11:04.140  6690  6690 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-30 23:11:04.140  6690  6690 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-30 23:11:04.140  6690  6690 D EasySignUpManager_1.0.5: isAuth is false
08-30 23:11:04.140  6690  6690 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-30 23:11:04.140  6690  6690 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
08-30 23:11:04.150  1717  1731 D TP/MmsSmsProvider: query, match:2117, calling pid = 6690, accessRestricted = false
08-30 23:11:04.150  1717  1731 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 0.951 ms
08-30 23:11:04.150  6690  6716 D Mms/ArtClassLoader: init [DONE] art
08-30 23:11:04.160  6690  6690 E CscParser: mps_code.dat does not exist
08-30 23:11:04.160  6690  6690 E CscParser: customer_path =/system/csc/customer.xml
08-30 23:11:04.160  6690  6690 E CscParser: fileName + /system/csc/customer.xml
08-30 23:11:04.160  6690  6690 E CscParser: mps_code.dat does not exist
08-30 23:11:04.160  6690  6690 E CscParser: customer_path =/system/csc/customer.xml
08-30 23:11:04.160  6690  6690 E CscParser: fileName + /system/csc/customer.xml
08-30 23:11:04.170  6690  6690 D CscParser: getInstance fileName =/system/csc/customer.xml
08-30 23:11:04.170  6690  6690 D Mms/MmsConfig:  enable multiwindow = true
08-30 23:11:04.170  6690  6690 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
08-30 23:11:04.170  6690  6690 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-30 23:11:04.170  6690  6690 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-30 23:11:04.170  6690  6690 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-30 23:11:04.170  6690  6690 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-30 23:11:04.170  6690  6690 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-30 23:11:04.170  6690  6690 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-30 23:11:04.180  6690  6690 D Mms/MmsConfig: [end]    init() consume time = 104.804999
08-30 23:11:04.180  6690  6690 D Mms/Contact: [start]    init() consume time = 3.610208
08-30 23:11:04.190  1717  1919 D TP/MmsSmsProvider: query, match:13, calling pid = 6690, accessRestricted = false
08-30 23:11:04.190  1717  1919 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.014 ms
08-30 23:11:04.200  6690  6690 D Mms/Contact: [end]    init consume time = 13.892136
08-30 23:11:04.200  6690  6723 D Mms/DraftCache: [start]    rebuildCache consume time = 5.169219
08-30 23:11:04.200  6690  6690 D Mms:transaction: roaming -> false (slotId = 0)
08-30 23:11:04.200  6690  6690 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 23:11:04.200  6690  6690 D Mms:transaction: auto download without roaming -> true
08-30 23:11:04.200  6690  6690 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-30 23:11:04.200  6690  6690 D Mms:transaction: roaming -> false (slotId = 1)
08-30 23:11:04.200  6690  6690 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-30 23:11:04.200  6690  6690 D Mms:transaction: auto download without roaming -> true
08-30 23:11:04.200  6690  6690 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-30 23:11:04.200  6690  6690 D Mms:transaction: auto download during roaming secondary -> false
08-30 23:11:04.200  6690  6690 D Mms:transaction: mAutoDownload ------> true
08-30 23:11:04.210  1717  1920 D TP/MmsSmsProvider: query, match:12, calling pid = 6690, accessRestricted = false
08-30 23:11:04.210  1717  1920 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.115 ms
08-30 23:11:04.220  6690  6723 D Mms/DraftCache: [end]    rebuildCache consume time = 14.39052
08-30 23:11:04.230  6690  6690 D ComposerPerformance: 1472591464238 ms / [DONE] Composer constructor
08-30 23:11:04.230  6690  6690 D CII     : Log Level [5]
08-30 23:11:04.230  6690  6690 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-30 23:11:04.230  6690  6690 I Mms/ReservationManager: ReservationManager()
08-30 23:11:04.230  6690  6690 I Mms/ReservationManager: resetAfterConnected()
08-30 23:11:04.240  1717  1919 D TP/MmsSmsProvider: query, match:7, calling pid = 6690, accessRestricted = false
08-30 23:11:04.240  1717  1919 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.245 ms
08-30 23:11:04.240  6690  6690 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-30 23:11:04.240  6690  6690 D Mms/MmsApp: [end]    onCreate() consume time = 29.706146
08-30 23:11:04.240  6690  6690 D Mms/MmsApp: [end]    onCreate() consume time = 0.081927
08-30 23:11:04.250  6690  6725 D Mms/Conversation: [start]    init() consume time = 1.914219
08-30 23:11:04.250  1717  1730 D TP/MmsSmsProvider: delete, match:1, calling pid = 6690
08-30 23:11:04.250  1717  1730 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-30 23:11:04.250  1717  1730 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-30 23:11:04.250  1717  1730 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
08-30 23:11:04.250  1717  1730 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-30 23:11:04.250  1717  1730 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-30 23:11:04.250  1717  1730 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
08-30 23:11:04.260  1717  1730 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-30 23:11:04.260  1717  1730 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-30 23:11:04.260  1717  1730 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-30 23:11:04.260  1717  1730 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 14.446 ms
08-30 23:11:04.260  1717  1730 D TP/MmsSmsProvider: need read changed broadcast:false
08-30 23:11:04.260  6690  6725 D Mms/Conversation: [end]    init consume time = 16.488125
08-30 23:11:04.270  6690  6725 D Mms/MessagingNotification: [start]    init() consume time = 2.16448
08-30 23:11:04.270  6690  6690 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
08-30 23:11:04.270  6690  6690 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-30 23:11:04.270  6690  6690 D Mms:transaction: roaming -> false (slotId = 0)
08-30 23:11:04.270  6690  6690 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 23:11:04.270  6690  6690 D Mms:transaction: auto download without roaming -> true
08-30 23:11:04.270  6690  6690 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-30 23:11:04.270  6690  6690 D Mms:transaction: mAutoDownload ------> true
08-30 23:11:04.280  6726  6726 E Zygote  : v2
08-30 23:11:04.280  6726  6726 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:04.280   779  1752 I ActivityManager: Start proc 6726:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-30 23:11:04.280   779  1752 I ActivityManager: Killing 5216:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-30 23:11:04.280  6726  6726 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:04.280  6726  6726 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:04.280  6726  6726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:04.280  6726  6726 E Zygote  : accessInfo : 0
08-30 23:11:04.300  6690  6725 D Mms/MessagingNotification: [end]    init consume time = 29.869739
08-30 23:11:04.310   779  1413 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
08-30 23:11:04.310  6690  6734 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 14.773125
08-30 23:11:04.320  6726  6726 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:04.320  6726  6726 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:04.320  6690  6737 D Mms/Synchronizer: [start]    doSync consume time = 4.634791
08-30 23:11:04.320   779  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{723cdc8 6726:com.samsung.android.bbc.bbcagent/1000}
08-30 23:11:04.330  1717  1919 D TP/MmsSmsProvider: query, match:400, calling pid = 6690, accessRestricted = false
08-30 23:11:04.330  1717  1731 D TP/MmsSmsProvider: query, match:0, calling pid = 6690, accessRestricted = false
08-30 23:11:04.330  1717  1731 V TP/MmsSmsProvider: getSimpleConversations entered.
08-30 23:11:04.330  1717  1920 D TP/MmsSmsProvider: update, match:300, calling pid = 6690
08-30 23:11:04.330  1717  1920 V TP/MmsSmsProvider: syncDBData start
08-30 23:11:04.330  1717  1731 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.182 ms
08-30 23:11:04.330  1717  1920 V TP/MmsSmsProvider: syncDBData sms end
08-30 23:11:04.330  1717  1920 V TP/MmsSmsProvider: syncDBData mms end
08-30 23:11:04.330  1717  1920 V TP/MmsSmsProvider: syncDBData end
08-30 23:11:04.330  1717  1920 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.713 ms
08-30 23:11:04.330  6690  6737 D Mms/Synchronizer: [end]    doSync consume time = 17.164636
08-30 23:11:04.330  6690  6734 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 1.227552
08-30 23:11:04.340  6726  6726 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
08-30 23:11:04.340  6232  6257 D BadgeProvider: query, [selection] : package=?
08-30 23:11:04.350  6690  6725 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-30 23:11:04.360  1717  1731 D TP/SmsProvider: query,matched:26, calling pid = 6690
08-30 23:11:04.360  1717  1731 D TP/SmsProvider: query, match 26:Elapsed time : 0.986 ms
08-30 23:11:04.370  6726  6726 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
08-30 23:11:04.370  1717  1730 D TP/MmsSmsProvider: query, match:6, calling pid = 6690, accessRestricted = false
08-30 23:11:04.370  1717  1730 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.006 ms
08-30 23:11:04.390  6740  6740 E Zygote  : v2
08-30 23:11:04.390  6740  6740 I libpersona: KNOX_SDCARD checking this for 10024
08-30 23:11:04.390  6740  6740 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:04.390  6740  6740 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:04.390  6740  6740 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:04.400  6740  6740 E Zygote  : accessInfo : 0
08-30 23:11:04.400   779  1751 I ActivityManager: Start proc 6740:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-30 23:11:04.400  6740  6740 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
08-30 23:11:04.410   779  2437 I ActivityManager: Start proc 6751:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-30 23:11:04.410   779  2437 I ActivityManager: Killing 5274:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
08-30 23:11:04.410  6751  6751 E Zygote  : v2
08-30 23:11:04.410  6751  6751 I libpersona: KNOX_SDCARD checking this for 10097
08-30 23:11:04.410  6751  6751 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:04.410  6751  6751 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:04.410  6751  6751 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:04.410  6751  6751 E Zygote  : accessInfo : 0
08-30 23:11:04.420  6751  6751 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-30 23:11:04.420  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:04.420  6740  6740 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:04.420   779  1622 I ActivityManager: Killing 5579:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-30 23:11:04.440  6751  6751 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:04.440  6751  6751 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:04.450   779   793 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
08-30 23:11:04.460   779  1413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3a1be61 6751:com.google.android.apps.docs/u0a97}
08-30 23:11:04.460  6740  6740 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
08-30 23:11:04.460  6751  6751 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-30 23:11:04.470   779  1570 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
08-30 23:11:04.480  6740  6740 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
08-30 23:11:04.490  6751  6751 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
08-30 23:11:04.530  6740  6740 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
08-30 23:11:04.540  6690  6725 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-30 23:11:04.560  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-30 23:11:04.570  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-30 23:11:04.570  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-30 23:11:04.570  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-30 23:11:04.570  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-30 23:11:04.570  6740  6740 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-30 23:11:04.770  6751  6767 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-30 23:11:04.770  6751  6767 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 23:11:04.770  6751  6767 I GAv4    :   adb logcat -s GAv4
,08-30 23:11:04.810   779  1364 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-30 23:11:04.820  6751  6767 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 23:11:04.820   779  1752 V AlarmManager:  remove PendingIntent] PendingIntent{5dadf9d: PendingIntentRecord{ec13c12 com.google.android.apps.docs broadcastIntent}}
,08-30 23:11:04.820  6751  6767 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 23:11:04.830  6751  6767 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 23:11:04.830  6751  6773 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 23:11:04.860   779  1235 V AlarmManager: Expired Alarm result :4
,08-30 23:11:04.880  6751  6751 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-30 23:11:04.880  6751  6751 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-30 23:11:04.920  6751  6767 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-30 23:11:04.920  6751  6767 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-30 23:11:04.920  6751  6767 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-30 23:11:04.920  6751  6767 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-30 23:11:04.950  6779  6779 E Zygote  : v2
08-30 23:11:04.950  6779  6779 I libpersona: KNOX_SDCARD checking this for 10098
08-30 23:11:04.950  6779  6779 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:04.950  6779  6779 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:04.950  6779  6779 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:04.950   779  1413 I ActivityManager: Start proc 6779:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-30 23:11:04.950  6779  6779 E Zygote  : accessInfo : 0
08-30 23:11:04.950   779  1413 I ActivityManager: Killing 5164:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
08-30 23:11:04.950  6779  6779 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-30 23:11:04.990  6779  6779 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:04.990  6779  6779 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:04.990   779  2441 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-30 23:11:04.990  4474  5162 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-30 23:11:05.010   779  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ecf73f 6779:com.sec.android.automotive.drivelink/u0a98}
,08-30 23:11:05.020  6779  6779 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-30 23:11:05.020   779  3640 D SSRM:n  : SIOP:: AP = 460, PST = 457, CUR = 350, LCD = 0
,08-30 23:11:05.040  6779  6779 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-30 23:11:05.050   779  3640 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:11:05.070  4474  5162 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-30 23:11:05.080  6779  6779 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-30 23:11:05.090   779  1570 V AlarmManager:  remove PendingIntent] PendingIntent{cf4a80c: PendingIntentRecord{4a76555 com.sec.android.automotive.drivelink broadcastIntent}}
,08-30 23:11:05.120  3894  3894 D FactoryTest: User mode
,08-30 23:11:05.120  3894  3894 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 23:11:05.120  3894  3894 D MTPRx   : still no open session command from host, so toast
,08-30 23:11:05.120   779   793 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-30 23:11:05.120   779   789 I art     : Background partial concurrent mark sweep GC freed 23906(1564KB) AllocSpace objects, 6(120KB) LOS objects, 27% free, 42MB/58MB, paused 1.624ms total 101.622ms
,08-30 23:11:05.130   779   793 D ActivityManager: mDVFSHelper.acquire()
,08-30 23:11:05.130  6779  6779 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
08-30 23:11:05.130   779   793 V WindowManager: addAppToken: AppWindowToken{a4a38f8 token=Token{943c85b ActivityRecord{e43b6a u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-30 23:11:05.130   779   793 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-30 23:11:05.130  6779  6795 I GMPM    : App measurement is starting up
,08-30 23:11:05.150  6779  6795 E GMPM    : getGoogleAppId failed with status: 10
,08-30 23:11:05.160  6779  6795 E GMPM    : Uploading is not possible. App measurement disabled
,08-30 23:11:05.160   779   793 D InputDispatcher: Focused application set to: xxxx
,08-30 23:11:05.160   779   793 D InputDispatcher: Focus left window: 6541
,08-30 23:11:05.160   779   867 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-30 23:11:05.160  3894  3894 E MTPRx   : started activity for popup
,08-30 23:11:05.170  3894  3894 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-30 23:11:05.170  3894  3894 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-30 23:11:05.170   779   918 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
,08-30 23:11:05.170   779   918 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:11:05.170   779   918 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
,08-30 23:11:05.170   779   918 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 23:11:05.180   779   793 V AlarmManager:  remove PendingIntent] PendingIntent{6c601d1: PendingIntentRecord{4a76555 com.sec.android.automotive.drivelink broadcastIntent}}
,08-30 23:11:05.190  3894  3894 D MTPUSBConnection: onCreate in USBConnection
,08-30 23:11:05.190  3894  3894 V MTPUSBConnection: Registering broadcast receiver.
,08-30 23:11:05.190  3894  3894 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-30 23:11:05.190   779  1747 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-30 23:11:05.210  6779  6779 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-30 23:11:05.210  6779  6779 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-30 23:11:05.240  3894  3894 D TAG     : dev.kiessupport is : TRUE
,08-30 23:11:05.260  6802  6802 E Zygote  : v2
08-30 23:11:05.260  6802  6802 I libpersona: KNOX_SDCARD checking this for 10032
08-30 23:11:05.260  6802  6802 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:05.260  6802  6802 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:05.260  6802  6802 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:05.260  6802  6802 E Zygote  : accessInfo : 0
08-30 23:11:05.270  6802  6802 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-30 23:11:05.270   779  1413 I ActivityManager: Start proc 6802:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-30 23:11:05.270   779  1320 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-30 23:11:05.280  3894  3894 D SecWifiDisplayUtil: Metadata value : none
,08-30 23:11:05.300  3894  3894 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a5e744e V.E...... R.....I. 0,0-0,0}
,08-30 23:11:05.300  6802  6802 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:05.300  6802  6802 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:05.310   779  1320 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-30 23:11:05.310  3894  6814 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 23:11:05.310   779  1621 D ISSUE_DEBUG: InputChannelName : 8a61a09 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-30 23:11:05.320   779   870 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8a61a09 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-30 23:11:05.320   779  1621 D InputDispatcher: Focus entered window: 3894
,08-30 23:11:05.320  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-30 23:11:05.320   779   918 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
08-30 23:11:05.320   779   918 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:11:05.320   779   918 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
08-30 23:11:05.320   779   918 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-30 23:11:05.330  3894  3894 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3f0bf26 I.E...... R.....I. 0,0-0,0}
,08-30 23:11:05.330   779   793 D ISSUE_DEBUG: InputChannelName : 7582e2f com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-30 23:11:05.330   779  1409 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-30 23:11:05.330   779  1409 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-30 23:11:05.330   779   779 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 23:11:05.340   779   779 I KnoxTimeoutHandler: Shared devices show user statefalse
08-30 23:11:05.340   779   779 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-30 23:11:05.360   294   294 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,08-30 23:11:05.370  6802  6802 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-30 23:11:05.380  3894  6814 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 23:11:05.380  3894  6814 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 23:11:05.380  3894  6814 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 23:11:05.380  3894  6814 I Adreno-EGL: Local Branch: ss
08-30 23:11:05.380  3894  6814 I Adreno-EGL: Remote Branch: 
08-30 23:11:05.380  3894  6814 I Adreno-EGL: Local Patches: 
08-30 23:11:05.380  3894  6814 I Adreno-EGL: Reconstruct Branch: 
,08-30 23:11:05.380  3894  6814 D libEGL  : eglInitialize EGLDisplay = 0x9efff7c4
,08-30 23:11:05.380  3894  6814 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 23:11:05.390  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:05.390  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:05.410  6802  6802 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-30 23:11:05.430   294   294 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
,08-30 23:11:05.450  3894  3894 V ActivityThread: updateVisibility : ActivityRecord{22935bd token=android.os.BinderProxy@3fb796f {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-30 23:11:05.460  3894  3894 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 23:11:05.580   779  1745 V WindowStateAnimator: Finishing drawing window Window{8a61a09 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 23:11:05.580  3894  3894 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-30 23:11:05.580  4474  5162 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-30 23:11:05.580   779  1621 V WindowStateAnimator: Finishing drawing window Window{7582e2f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-30 23:11:05.580  3894  3894 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-30 23:11:05.580  3894  3894 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-30 23:11:05.590   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbee3d364
,08-30 23:11:05.590   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbee3d364
,08-30 23:11:05.590   779  1570 V WindowStateAnimator: Finishing drawing window Window{8a61a09 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 23:11:05.590   779   918 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 23:11:05.590   779   918 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +439ms (total +465ms)
,08-30 23:11:05.600   779   918 D ActivityManager: mDVFSHelper.release()
08-30 23:11:05.600   779   918 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e43b6a u0 com.samsung.android.MtpApplication/.USBConnection t168} time:110080
08-30 23:11:05.600   779   779 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-30 23:11:05.600   779  1745 V WindowStateAnimator: Finishing drawing window Window{7582e2f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-30 23:11:05.600   779   779 I KnoxTimeoutHandler: SD activityfalse
,08-30 23:11:05.600  3894  3894 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3fb796f time:110081
,08-30 23:11:05.610   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbee3d364
,08-30 23:11:05.660  6802  6802 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-30 23:11:05.680  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:05.680   779  6437 I HarmonyEASService: Updating for all 1
,08-30 23:11:05.690  6779  6779 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-30 23:11:05.700  6802  6802 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-30 23:11:05.700  6779  6779 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-30 23:11:05.700  6779  6779 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-30 23:11:05.720  6779  6779 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDTue Aug 30 23:11:05 GMT+02:00 2016
,08-30 23:11:05.730  6779  6779 D DialogFlow: initQueue()
,08-30 23:11:05.730  6825  6825 E Zygote  : v2
08-30 23:11:05.730  6825  6825 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:05.730  6825  6825 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:05.730  6825  6825 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:05.730  6825  6825 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:05.730  6825  6825 E Zygote  : accessInfo : 0
,08-30 23:11:05.740   779  2441 I ActivityManager: Start proc 6825:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-30 23:11:05.740   779  2441 I ActivityManager: Killing 5884:com.sec.android.app.shealth/u0a34 (adj 15): DHA:empty #37
,08-30 23:11:05.740   779  2441 I ActivityManager: Killing 5783:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-30 23:11:05.760   779  1747 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-30 23:11:05.760  6825  6825 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:05.760  6825  6825 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:05.770   779  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{38c9779 6825:com.samsung.android.app.filterinstaller/1000}
,08-30 23:11:05.770  6751  6768 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-30 23:11:05.770   779  1570 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,08-30 23:11:05.780  6825  6825 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-30 23:11:05.790   779   793 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-30 23:11:05.790  6825  6825 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-30 23:11:05.800  6825  6825 E FilterPackageIntentReceiver: This package is not a effect filter
,08-30 23:11:05.810  6838  6838 E Zygote  : v2
08-30 23:11:05.810  6838  6838 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:05.810  6838  6838 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:05.810  6838  6838 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:05.810   779  1767 I ActivityManager: Start proc 6838:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-30 23:11:05.810   779  1767 I ActivityManager: Killing 4856:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
08-30 23:11:05.810  6838  6838 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:05.810  6838  6838 E Zygote  : accessInfo : 0
,08-30 23:11:05.830  6802  6802 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-30 23:11:05.830  6802  6802 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-30 23:11:05.840  6838  6838 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:05.840  6838  6838 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:05.840   779   793 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
08-30 23:11:05.840  6802  6802 D DialogFlow: initQueue()
,08-30 23:11:05.850   779  2437 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4959358 6838:com.samsung.helphub/1000}
08-30 23:11:05.860  6838  6838 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
08-30 23:11:05.870  6838  6838 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-30 23:11:05.880  6751  6768 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-30 23:11:05.900  6751  6768 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-30 23:11:05.900  6751  6768 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-30 23:11:05.900  6751  6768 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 23:11:05.910  6850  6850 E Zygote  : v2
08-30 23:11:05.910  6850  6850 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:05.910  6850  6850 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:05.910  6850  6850 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:05.910  6850  6850 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:05.920   779  1413 I ActivityManager: Start proc 6850:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-30 23:11:05.910  6850  6850 E Zygote  : accessInfo : 0
,08-30 23:11:05.920   779  1413 I ActivityManager: Killing 5613:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-30 23:11:05.940  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:05.940  6850  6850 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:05.950   779  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4a4bcb1 6850:com.samsung.android.app.mirrorlink/1000}
,08-30 23:11:05.960   779  2441 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-30 23:11:05.960  6850  6850 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-30 23:11:05.970  6850  6850 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-30 23:11:05.980  6751  6768 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 23:11:06.000  6850  6850 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-30 23:11:06.000  6850  6850 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-30 23:11:06.000   779  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{205188e 5795:com.google.android.apps.plus/u0a134}
,08-30 23:11:06.020   779  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{205188e 5795:com.google.android.apps.plus/u0a134}
,08-30 23:11:06.030   779  1413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{205188e 5795:com.google.android.apps.plus/u0a134}
,08-30 23:11:06.060   779  1621 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-30 23:11:06.060   779   793 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-30 23:11:06.060   779  1413 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-30 23:11:06.060   779  1751 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-30 23:11:06.070   779  1622 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-30 23:11:06.080   779  2441 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-30 23:11:06.080   779  2437 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-30 23:11:06.080   779  1752 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-30 23:11:06.110  6864  6864 E Zygote  : v2
08-30 23:11:06.110  6864  6864 I libpersona: KNOX_SDCARD checking this for 10165
08-30 23:11:06.110  6864  6864 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:06.110  6864  6864 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:06.110  6864  6864 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:06.120  6864  6864 E Zygote  : accessInfo : 0
08-30 23:11:06.120   779  1751 I ActivityManager: Start proc 6864:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
08-30 23:11:06.120  6864  6864 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-30 23:11:06.120   779  1751 I ActivityManager: Killing 6058:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #37
,08-30 23:11:06.140   779  2441 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,08-30 23:11:06.140  6864  6864 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:06.140  6864  6864 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:06.150   779  1752 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7c8d04 6864:com.sec.kidsplat.installer/u0a165}
,08-30 23:11:06.160  6864  6864 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-30 23:11:06.170  6864  6864 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-30 23:11:06.170   779  3647 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-30 23:11:06.170   779  2437 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c7c8d04 6864:com.sec.kidsplat.installer/u0a165}
,08-30 23:11:06.180  6864  6864 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-30 23:11:06.190  6876  6876 E Zygote  : v2
08-30 23:11:06.190   779  1767 I ActivityManager: Start proc 6876:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-30 23:11:06.190  6876  6876 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 23:11:06.190  6876  6876 I libpersona: KNOX_SDCARD checking this for 10142
08-30 23:11:06.190  6876  6876 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:06.190  6876  6876 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:06.190  6876  6876 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:06.190   779  1767 I ActivityManager: Killing 5771:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
08-30 23:11:06.190  6876  6876 E Zygote  : accessInfo : 64
08-30 23:11:06.190  6876  6876 E Zygote  : isSdpEnabledProcess - SDP enabled
08-30 23:11:06.190  6876  6876 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-30 23:11:06.190  6876  6876 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-30 23:11:06.210   779  1752 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-30 23:11:06.210  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:06.210  6876  6876 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:06.220   779  1747 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91772ed 6876:com.sec.android.app.sbrowser/u0a142}
,08-30 23:11:06.240  6876  6876 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-30 23:11:06.260  6876  6876 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-30 23:11:06.270  6876  6876 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-30 23:11:06.270  6876  6876 D ManifestProvider: onCreate()
,08-30 23:11:06.280  6690  6690 I Mms/MmsApp:  start initViewCache mms
,08-30 23:11:06.300  6876  6876 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-30 23:11:06.300  6876  6876 I SBrowserUtils: getSystemProperty of country_code : Poland
08-30 23:11:06.300  6876  6876 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-30 23:11:06.300  6876  6876 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-30 23:11:06.300  6876  6876 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-30 23:11:06.300  6876  6876 D [MM]MHDataBaseProvider: onCreate()
,08-30 23:11:06.320  6876  6876 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@d5f2d8a)
,08-30 23:11:06.330  1452  1452 D Recents : onTaskStackChanged
,08-30 23:11:06.340  1452  1452 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-30 23:11:06.370   779  1622 I ActivityManager: Killing 5463:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-30 23:11:06.370   779  1622 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a593526 2045:com.google.android.gms.persistent/u0a11}
,08-30 23:11:06.380   779  2437 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-30 23:11:06.390  4474  6892 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 23:11:06.390  4474  6891 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-30 23:11:06.390   779  1570 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84ffde9 4474:com.google.android.gms/u0a11}
,08-30 23:11:06.400  4474  6892 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 23:11:06.410  4474  6892 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 23:11:06.410  4474  4474 D AsyncTaskServiceImpl: Submit a task: nzm
,08-30 23:11:06.420  4474  6892 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-30 23:11:06.420   779  1413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a593526 2045:com.google.android.gms.persistent/u0a11}
,08-30 23:11:06.440   779  1413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84ffde9 4474:com.google.android.gms/u0a11}
,08-30 23:11:06.450  4474  4474 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 23:11:06.450  4474  5107 D nzm     : Processing package: com.test.thalitest
,08-30 23:11:06.480  4474  5107 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-30 23:11:06.480  4474  5107 D nzm     : Found info for package com.test.thalitest in db.
,08-30 23:11:06.550   779  1752 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9ca89db 6279:com.sec.android.app.samsungapps/u0a39}
,08-30 23:11:06.560   779  1752 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a83206a u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96a4d95 5827:com.android.vending/u0a29}
,08-30 23:11:06.610  6690  6690 D Mms/BubbleViewCache: fillCache bubble = 4
,08-30 23:11:06.620  6898  6898 E Zygote  : v2
08-30 23:11:06.620  6898  6898 I libpersona: KNOX_SDCARD checking this for 10034
08-30 23:11:06.620  6898  6898 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:06.620  6898  6898 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:06.620  6898  6898 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:06.620   779   779 I ActivityManager: Start proc 6898:com.sec.android.app.shealth/u0a34 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.serviceframework.partner.PluginBroadcastReceiver
08-30 23:11:06.630  6898  6898 E Zygote  : accessInfo : 0
08-30 23:11:06.630  6898  6898 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth 
,08-30 23:11:06.630  5827  5827 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-30 23:11:06.650   779   779 I BackgroundCompactionService: onStart. jobID=801
,08-30 23:11:06.650  2045  2045 D WearableService: callingUid 10011, callindPid: 2045
,08-30 23:11:06.650   779   779 I BackgroundCompactionService: onStart done. jobID=801
,08-30 23:11:06.650   779  6909 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-30 23:11:06.650  5827  5827 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
08-30 23:11:06.650   779  6909 I BackgroundCompactionService: compact_memory command done
,08-30 23:11:06.670  5827  5827 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-30 23:11:06.670  6898  6898 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:06.670  6898  6898 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:06.670  5827  5827 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-30 23:11:06.680   779  1621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46cef15 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{278622a 6898:com.sec.android.app.shealth/u0a34}
,08-30 23:11:06.700  6898  6898 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-30 23:11:06.730  6898  6898 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-30 23:11:06.740  6898  6898 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 23:11:06.740  6898  6898 I MultiDex: install
,08-30 23:11:06.740  6898  6898 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 23:11:06.740  6898  6898 I MultiDex: install
08-30 23:11:06.740  6898  6898 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:11:06.880   779  1409 I ActivityManager: Killing 6076:com.samsung.android.sm.policy/u0a203 (adj 15): DHA:empty #37
,08-30 23:11:06.880   779  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46cef15 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{967ef2d 1870:com.sec.android.app.shealth:remote/u0a34}
,08-30 23:11:06.890  6898  6898 D HealthDataStore: Service for HealthDataStore is connected
,08-30 23:11:06.890  6898  6898 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-30 23:11:06.890   779  1751 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,08-30 23:11:06.900  6898  6898 D HealthConsole: Service for HealthDataConsole is connected
,08-30 23:11:06.910   779   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{46cef15 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{967ef2d 1870:com.sec.android.app.shealth:remote/u0a34}
,08-30 23:11:06.920  6898  6898 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-30 23:11:06.920  6898  6898 E HealthDataStore: disconnectService: Context instance is invalid
,08-30 23:11:06.930   779   793 V AlarmManager:  remove PendingIntent] PendingIntent{9ea6bd0: PendingIntentRecord{bb98eb1 com.google.android.gms broadcastIntent}}
,08-30 23:11:06.940   779  1767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{88977c9 u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a593526 2045:com.google.android.gms.persistent/u0a11}
,08-30 23:11:06.940   779  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-30 23:11:06.940   779  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-30 23:11:06.960  6802  6824 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 23:11:06.960  6802  6824 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 23:11:07.000  6802  6824 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 23:11:07.000  6802  6824 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-30 23:11:07.000  6802  6824 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-30 23:11:07.010  6802  6824 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 23:11:07.010  6802  6824 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 23:11:07.610  4474  5112 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-30 23:11:07.680  4474  5112 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 23:11:07.690  4474  5112 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 23:11:07.700  4474  5112 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-30 23:11:08.180   779  3680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:11:10.480   779  2437 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 23:11:10.480   779  2437 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4331, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-30 23:11:10.480   779  2437 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-30 23:11:10.480   779  2437 D BatteryService: stay LED for charging
,08-30 23:11:10.480   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 23:11:10.480   779   779 I MotionRecognitionService: Plugged
08-30 23:11:10.480   779   779 D MotionRecognitionService:   cableConnection= 1
08-30 23:11:10.480   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 23:11:10.480   779   779 D MotionRecognitionService: skip setTransmitPower. 
,08-30 23:11:10.480  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 23:11:10.480  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-30 23:11:10.480  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 23:11:10.490  2325  2325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 23:11:10.490  2325  2738 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 23:11:10.500  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 23:11:10.510  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 23:11:10.510  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 23:11:11.180   779  3640 D M       : limitCPUFreq:: freq = 1728000
,08-30 23:11:11.180   779  3640 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 779  pkgName : SIOP_ARM_MAX@25
08-30 23:11:11.180   779  3640 D M       : limitGPUFreq:: freq = 389000000
,08-30 23:11:11.200   779  3640 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:11:11.790   779   949 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 23:11:11.810   779   949 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 23:11:13.530   779   949 D PackageManager: [MSG] MCS_UNBIND
,08-30 23:11:13.550   779  1751 I ActivityManager: Killing 6095:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-30 23:11:13.550   779  1751 I ActivityManager: Killing 5478:com.policydm/1000 (adj 15): DHA:empty #37
,08-30 23:11:13.610   779  2437 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-30 23:11:13.610  6700  6700 D AASAservice: onDestroy()
,08-30 23:11:13.610  6700  6700 I art     : System.exit called, status: 80
,08-30 23:11:13.610  6700  6700 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-30 23:11:13.620   779   793 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-30 23:11:13.630   779  1745 I ActivityManager: Process com.samsung.aasaservice (pid 6700)(adj 0) has died(80,709)
,08-30 23:11:13.630   779  1745 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-30 23:11:13.690   353   353 I Zygote  : Process 6700 exited cleanly (80)
,08-30 23:11:15.090   779  3640 D SSRM:n  : SIOP:: AP = 450, PST = 455, CUR = 350, LCD = 0
,08-30 23:11:15.110   779  3640 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-30 23:11:16.490   779  1572 E Watchdog: !@Sync 3 [08-30 23:11:16.495]
,08-30 23:11:16.960   779  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-30 23:11:16.960   779  1320 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-30 23:11:18.310   779   867 I ActivityManager: Waited long enough for: ServiceRecord{71aa84d u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-30 23:11:21.020  6541  6597 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 23:11:21.020  6541  6597 I jxcore-log: 
,08-30 23:11:21.020  6541  6597 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 23:11:21.020  6541  6597 I jxcore-log: 
,08-30 23:11:21.030  6541  6597 D BluetoothAdapter: STATE_ON
,08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:21.030  6541  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 23:11:21.030  6541  6597 D BluetoothAdapter: STATE_ON
,08-30 23:11:21.030  6541  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-30 23:11:21.040  6541  6597 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 23:11:21.040  6541  6597 I jxcore-log: 
,08-30 23:11:21.040  6541  6597 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 23:11:21.040  6541  6597 I jxcore-log: 
,08-30 23:11:21.500  6541  6597 I jxcore-log: Running unit tests
08-30 23:11:21.500  6541  6597 I jxcore-log: 
,08-30 23:11:21.500  6541  6597 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 23:11:21.500  6541  6597 I jxcore-log: Failed to execute UT.
08-30 23:11:21.500  6541  6597 I jxcore-log: 
,08-30 23:11:21.510  6541  6597 I jxcore-log: Unit Test app is loaded
08-30 23:11:21.510  6541  6597 I jxcore-log: 
,08-30 23:11:21.510  6541  6597 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 23:11:21.510  6541  6597 I jxcore-log: 
,08-30 23:11:21.520  6541  6597 I jxcore-log: My device name is: samsung-SM-G900F
08-30 23:11:21.520  6541  6597 I jxcore-log: 
,08-30 23:11:21.520  6541  6597 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 23:11:21.520  6541  6597 I jxcore-log: 
,08-30 23:11:21.520  6541  6541 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 23:11:21.580   779  1235 V AlarmManager: Expired Alarm result :4
,08-30 23:11:21.630   779   867 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{885a9da u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a593526 2045:com.google.android.gms.persistent/u0a11}
,08-30 23:11:21.640   779  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 23:11:21.640   779  1745 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4357, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-30 23:11:21.650   779  1745 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-30 23:11:21.650   779  1745 D BatteryService: stay LED for charging
,08-30 23:11:21.660   779  2441 V AlarmManager:  remove PendingIntent] PendingIntent{5b35701: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:21.670   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 23:11:21.670   779   779 I MotionRecognitionService: Plugged
,08-30 23:11:21.670   779   779 D MotionRecognitionService:   cableConnection= 1
,08-30 23:11:21.670   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-30 23:11:21.670   779   779 D MotionRecognitionService: skip setTransmitPower. 
,08-30 23:11:21.670  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 23:11:21.670  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-30 23:11:21.670  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 23:11:21.680  5827  5876 I Finsky  : [828] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,08-30 23:11:21.690  2325  2325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 23:11:21.690  2325  2738 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-30 23:11:21.690  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 23:11:21.690  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 23:11:21.700  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 23:11:21.800   779   792 V AlarmManager:  remove PendingIntent] PendingIntent{d635fe7: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:21.900  4474  6958 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 23:11:21.900  4474  6958 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 23:11:21.930  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:21.940   779  1409 V AlarmManager:  remove PendingIntent] PendingIntent{189277e: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:21.960   779   867 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae264df u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a593526 2045:com.google.android.gms.persistent/u0a11}
,08-30 23:11:22.000   779  1752 V AlarmManager:  remove PendingIntent] PendingIntent{9b152c: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:22.150   779  2437 V AlarmManager:  remove PendingIntent] PendingIntent{2f8a856: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:22.190  5827  5876 I Finsky  : [828] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,08-30 23:11:22.200  5827  5827 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-30 23:11:22.260  6964  6964 E Zygote  : v2
08-30 23:11:22.260  6964  6964 I libpersona: KNOX_SDCARD checking this for 10011
08-30 23:11:22.260  6964  6964 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:22.270   779  1751 I ActivityManager: Start proc 6964:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-30 23:11:22.270  6964  6964 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:22.270  6964  6964 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:22.270  6964  6964 E Zygote  : accessInfo : 0
,08-30 23:11:22.270  6964  6964 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-30 23:11:22.300  6964  6964 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:22.300  6964  6964 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:22.310  6964  6964 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-30 23:11:22.350  6964  6964 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:11:22.350  6964  6964 I MultiDex: install
08-30 23:11:22.350  6964  6964 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:11:22.380  6964  6964 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-30 23:11:22.390  6964  6964 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-30 23:11:22.390  6964  6964 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-30 23:11:22.400  6964  6964 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 23:11:22.440  6964  6964 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 23:11:22.460  6964  6964 D ChimeraCfgMgr: Reading stored module config
,08-30 23:11:22.580  2045  2057 W art     : Suspending all threads took: 10.555ms
,08-30 23:11:22.580  2045  2045 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=ef67dcc8-7ba9-4aba-964d-cd8be755dc71
,08-30 23:11:22.580  6964  6978 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 23:11:22.590  2045  2057 I art     : Background partial concurrent mark sweep GC freed 45116(3MB) AllocSpace objects, 26(520KB) LOS objects, 40% free, 19MB/32MB, paused 12.323ms total 62.675ms
,08-30 23:11:22.610  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:22.610  2045  2045 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:22.640   327   327 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6964)
,08-30 23:11:22.710   327   978 D WVCdm   : Instantiating CDM.
,08-30 23:11:22.710   327   975 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6964)
08-30 23:11:22.710   327   975 I WVCdm   : CdmEngine::OpenSession
08-30 23:11:22.710   327   975 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-30 23:11:22.740   327   975 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 23:11:22.750   327   975 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-30 23:11:22.750   327   975 D DrmWidevineDash: Service_Initialize: starts!
08-30 23:11:22.750   327   975 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-30 23:11:22.750   327   975 D QSEECOMAPI: : App is not loaded in QSEE
08-30 23:11:22.750   327   975 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-30 23:11:22.750   327   975 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 23:11:22.750   327   975 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 23:11:22.750   327   975 D QSEECOMAPI: : App is not loaded in QSEE
08-30 23:11:22.750   327   975 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-30 23:11:22.750   327   975 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 23:11:22.750   327   975 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 23:11:22.750   327   975 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 23:11:22.760   779   789 I art     : Background partial concurrent mark sweep GC freed 35577(2027KB) AllocSpace objects, 12(240KB) LOS objects, 27% free, 42MB/58MB, paused 2.026ms total 158.248ms
,08-30 23:11:22.770  6964  6975 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:22.770  6964  6975 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:22.780   309  1100 D EnterpriseController: netId is 0
08-30 23:11:22.780   309  1100 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:22.780   327   975 D QSEECOMAPI: : Loaded image: APP id = 2
,08-30 23:11:22.790   327   975 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-30 23:11:22.790   327   975 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef95000
08-30 23:11:22.790   327   975 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef95000
,08-30 23:11:22.820   327   975 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-30 23:11:22.820   327   975 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-30 23:11:22.820   327   975 D DrmWidevineDash: hlos api version =  10
08-30 23:11:22.820   327   975 D DrmWidevineDash: tz api version =  10
08-30 23:11:22.820   327   975 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-30 23:11:22.820   327   975 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-30 23:11:22.830   327   975 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf22f924
,08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e5dc48, dataLength=8
08-30 23:11:22.830  6964  6975 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6964, getuid(): 10011
,08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-30 23:11:22.830   327   975 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae94f800, wrapped_rsa_key_length=1280
,08-30 23:11:22.840   327   975 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-30 23:11:22.840   327   975 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 23:11:22.840   327   984 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 23:11:22.840   327   984 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-30 23:11:22.840   327   984 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 23:11:22.840   327   984 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xae3c94a0, idLength=0xaed7ff2c
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-30 23:11:22.860   327   984 D DrmWidevineDash: hlos api version =  10
,08-30 23:11:22.860   327   984 D DrmWidevineDash: tz api version =  10
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-30 23:11:22.860   327   984 D WVCdm   : PrepareKeyRequest: nonce=3411087475
08-30 23:11:22.860   327   984 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xae783c00
08-30 23:11:22.860   327   984 D DrmWidevineDash: message_length=1631, signature=0xaeeb5a40, signature_length=2933391364
,08-30 23:11:22.880  2045  2203 W GCoreFlp: No location to return for getLastLocation()
,08-30 23:11:22.990  4474  6959 D UdcContextInitService: registered all accounts: true
,08-30 23:11:23.000   327   984 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-30 23:11:23.000   327   978 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6964)
08-30 23:11:23.000   327   978 I WVCdm   : CdmEngine::CloseSession
08-30 23:11:23.000   327   978 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-30 23:11:23.000   327   978 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-30 23:11:23.000   327   978 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-30 23:11:23.010   327   978 D DrmWidevineDash: Service_Uninitialize: starts!
08-30 23:11:23.010   327   978 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-30 23:11:23.010   327   978 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,08-30 23:11:23.010   327   978 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-30 23:11:23.010   327   978 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-30 23:11:23.010  6964  6975 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6964, getuid(): 10011
,08-30 23:11:23.020  2045  2275 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 23:11:23.020  2045  2623 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 23:11:23.110   779   793 V AlarmManager:  remove PendingIntent] PendingIntent{7f3c8f2: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:23.180  6964  6975 I qtaguid : Untagging socket 21
,08-30 23:11:23.230  6964  6975 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-30 23:11:23.230  6964  6975 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-30 23:11:23.320  2045  6993 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:23.320  2045  6990 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 23:11:23.340  2045  6993 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:23.340  2045  6990 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 23:11:23.350  2045  6993 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:23.360  2045  6990 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 23:11:23.360  2045  6990 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 23:11:23.370  2045  6990 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 23:11:23.430   779   792 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:23.450  2045  6990 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-30 23:11:23.520  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:23.520  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:23.520   309  1100 D EnterpriseController: netId is 0
08-30 23:11:23.520   309  1100 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:23.570  2045  6990 I qtaguid : Tagging socket 55 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:23.600  2045  6990 I qtaguid : Tagging socket 58 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:23.700  6996  6996 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-30 23:11:23.780  6996  6996 I dex2oat : ----------------------------------------------------
08-30 23:11:23.780  6996  6996 I dex2oat : <SS>: S T A R T I N G . . .
08-30 23:11:23.780  6996  6996 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-30 23:11:23.780  6996  6996 I dex2oat : dex2oat took 85.573ms (threads: 4) arena alloc=91KB java alloc=79KB native alloc=1800KB free=1527KB
,08-30 23:11:23.790  6964  6975 W System  : ClassLoader referenced unknown path: 
,08-30 23:11:23.790  6964  6975 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-30 23:11:23.800  6964  6975 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 23:11:23.800  6964  6975 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 23:11:23.800  6964  6975 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 23:11:23.800  6964  6975 I Adreno-EGL: Local Branch: ss
08-30 23:11:23.800  6964  6975 I Adreno-EGL: Remote Branch: 
08-30 23:11:23.800  6964  6975 I Adreno-EGL: Local Patches: 
08-30 23:11:23.800  6964  6975 I Adreno-EGL: Reconstruct Branch: 
,08-30 23:11:23.800  6964  6975 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,08-30 23:11:23.890  6964  6975 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,08-30 23:11:23.910   779  1413 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:23.920  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:23.920  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:23.920  2045  6990 I qtaguid : Tagging socket 55 with tag 11065c0800000000{285629448,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:24.050   779  1621 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:24.060  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.060  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.060  2045  6990 I qtaguid : Tagging socket 55 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:24.100  6964  6975 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 23:11:24.100  6964  6975 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 23:11:24.100  6964  6975 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 23:11:24.100  6964  6975 I Adreno-EGL: Local Branch: ss
08-30 23:11:24.100  6964  6975 I Adreno-EGL: Remote Branch: 
08-30 23:11:24.100  6964  6975 I Adreno-EGL: Local Patches: 
08-30 23:11:24.100  6964  6975 I Adreno-EGL: Reconstruct Branch: 
08-30 23:11:24.100  6964  6975 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,08-30 23:11:24.170  6964  6975 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,08-30 23:11:24.170  6964  6975 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-30 23:11:24.170  6964  6975 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-30 23:11:24.170  6964  6975 I Adreno-EGL: Build Date: 01/28/16 Thu
08-30 23:11:24.170  6964  6975 I Adreno-EGL: Local Branch: ss
08-30 23:11:24.170  6964  6975 I Adreno-EGL: Remote Branch: 
08-30 23:11:24.170  6964  6975 I Adreno-EGL: Local Patches: 
08-30 23:11:24.170  6964  6975 I Adreno-EGL: Reconstruct Branch: 
08-30 23:11:24.170  6964  6975 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,08-30 23:11:24.210   779  1622 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:24.220  6964  6975 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,08-30 23:11:24.230  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.230  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.230  2045  6990 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:24.340   779  1752 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:24.340  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.340  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.340  2045  6990 I qtaguid : Tagging socket 55 with tag 11065c9100000000{285629585,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:24.450  2045  6962 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.450  2045  6962 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.450   309  1100 D EnterpriseController: netId is 0
08-30 23:11:24.450   309  1100 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:24.450   779   792 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:24.450  2045  6962 I qtaguid : Tagging socket 54 with tag 1000040100000000{268436481,0} uid 10011, pid: 2045, getuid(): 10011
,08-30 23:11:24.470  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.470  2045  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.470  2045  6990 I qtaguid : Tagging socket 55 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2045, getuid(): 10011
,08-30 23:11:24.480  2045  6962 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} uid 10011, pid: 2045, getuid(): 10011
,08-30 23:11:24.640   779  1767 V AlarmManager:  remove PendingIntent] PendingIntent{c750831: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:24.640  2045  2623 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 23:11:24.640  2045  2623 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 23:11:24.650  2045  2623 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 23:11:23.094+0200, stopTime=2016-08-30 23:11:24.656+0200, duration=1562ms
,08-30 23:11:24.670  2045  7019 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:24.670  2045  7019 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:24.670   309  1100 D EnterpriseController: netId is 0
08-30 23:11:24.670   309  1100 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:24.670  2045  7019 I qtaguid : Tagging socket 48 with tag 1000310500000000{268448005,0} uid 10011, pid: 2045, getuid(): 10011
,08-30 23:11:24.700   779   792 V AlarmManager:  remove PendingIntent] PendingIntent{d399b16: PendingIntentRecord{128cc1b com.google.android.gms broadcastIntent}}
,08-30 23:11:24.710  2045  7019 I qtaguid : Tagging socket 51 with tag 1000310500000000{268448005,0} uid 10011, pid: 2045, getuid(): 10011
,08-30 23:11:24.970  2045  7019 I qtaguid : Untagging socket 48
,08-30 23:11:24.980  2045  2623 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 23:11:25.060  6541  6597 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 23:11:25.060  6541  6597 I jxcore-log: 
,08-30 23:11:25.160   779  3640 D SSRM:n  : SIOP:: AP = 440, PST = 452, CUR = 350, LCD = 0
,08-30 23:11:25.680  6541  6597 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 23:11:25.680  6541  6597 I jxcore-log: 
,08-30 23:11:25.710  6541  6597 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 23:11:25.710  6541  6597 I jxcore-log: 
,08-30 23:11:26.800  2045  7020 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:26.800  2045  7020 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:26.800  2045  7020 I qtaguid : Tagging socket 48 with tag 1000310200000000{268448002,0} uid 10011, pid: 2045, getuid(): 10011
,08-30 23:11:27.000  2045  7020 I qtaguid : Untagging socket 48
,08-30 23:11:27.010  2045  2623 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 23:11:27.510  6541  6597 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 23:11:27.510  6541  6597 I jxcore-log: 
,08-30 23:11:27.810  6541  6597 I jxcore-log: ERROR runTests: 
08-30 23:11:27.810  6541  6597 I jxcore-log: 
,08-30 23:11:27.810  6541  6597 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:11:27.810  6541  6597 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 23:11:27.810  6541  6597 I jxcore-log: WARN testUtils: logCallback not set!
08-30 23:11:27.810  6541  6597 I jxcore-log: 
,08-30 23:11:27.830  6541  6597 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _functionName: 'loadFile',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _lineNumber: '26',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _columnNumber: '11',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 23:11:27.830  6541  6597 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _functionName: '',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _lineNumber: '38',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _columnNumber: '7',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 23:11:27.830  6541  6597 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _functionName: '',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _lineNumber: '35',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _columnNumber: '3',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 23:11:27.830  6541  6597 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _lineNumber: '621',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _columnNumber: '8',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 23:11:27.830  6541  6597 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _lineNumber: '651',
08-30 23:11:27.830  6541  6597 I jxcore-log:     _columnNumber: '1',
08-30 23:11:27.830  6541  6597 I jxcore-log:    
08-30 23:11:27.830  6541  6597 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 23:11:27.830  6541  6597 I jxcore-log: 
08-30 23:11:27.830  6541  6597 E jxcore-log: Error: 
08-30 23:11:27.830  6541  6597 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
,08-30 23:11:27.830  6541  6597 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 23:11:27.830  6541  6597 E jxcore-log: 
,08-30 23:11:28.180   779  3680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:11:29.040  2331  2331 E audit   : type=1400 msg=audit(1472591489.040:289): avc:  denied  { execmod } for  pid=7035 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 23:11:29.040  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:29.040  2331  2331 E audit   : type=1300 msg=audit(1472591489.040:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4039000 a1=51000 a2=5 a3=4 items=0 ppid=3783 ppcomm=adbd pid=7035 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 23:11:29.040  2331  2331 E audit   : type=1327 msg=audit(1472591489.040:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-30 23:11:29.040  2331  2331 E audit   : type=1320 msg=audit(1472591489.040:289): 
,08-30 23:11:29.120  2331  2331 E audit   : type=1400 msg=audit(1472591489.110:290): avc:  denied  { execmod } for  pid=7035 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 23:11:29.120  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:29.120  2331  2331 E audit   : type=1300 msg=audit(1472591489.110:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff9000 a1=51000 a2=5 a3=4 items=0 ppid=3783 ppcomm=adbd pid=7035 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 23:11:29.120  2331  2331 E audit   : type=1327 msg=audit(1472591489.110:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-30 23:11:29.120  2331  2331 E audit   : type=1320 msg=audit(1472591489.110:290): 
,08-30 23:11:29.170  2331  2331 E audit   : type=1400 msg=audit(1472591489.170:291): avc:  denied  { execmod } for  pid=7035 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-30 23:11:29.170  2331  2331 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:29.170  2331  2331 E audit   : type=1300 msg=audit(1472591489.170:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ff9000 a1=51000 a2=5 a3=4 items=0 ppid=3783 ppcomm=adbd pid=7035 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-30 23:11:29.170  2331  2331 E audit   : type=1327 msg=audit(1472591489.170:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-30 23:11:29.170  2331  2331 E audit   : type=1320 msg=audit(1472591489.170:291): 
,08-30 23:11:29.180  7035  7035 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 23:11:29.180  7035  7035 D AndroidRuntime: CheckJNI is OFF
,08-30 23:11:29.180  7035  7035 D AndroidRuntime: readGMSProperty: start
08-30 23:11:29.180  7035  7035 D AndroidRuntime: readGMSProperty: already setted!!
,08-30 23:11:29.180  7035  7035 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 23:11:29.180  7035  7035 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 23:11:29.180  7035  7035 D AndroidRuntime: readGMSProperty: end
08-30 23:11:29.180  7035  7035 D AndroidRuntime: addProductProperty: start
,08-30 23:11:29.200  7035  7035 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 23:11:29.200  7035  7035 W art     : aee60000-b1d86000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-30 23:11:29.200  7035  7035 W art     : b1d86000-b3ff5000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-30 23:11:29.200  7035  7035 W art     : b3ff5000-b3ff6000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
,08-30 23:11:29.200  7035  7035 W art     : b3ff6000-b3ff7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.200  7035  7035 W art     : b433b000-b4364000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-30 23:11:29.200  7035  7035 W art     : b4364000-b47b2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-30 23:11:29.200  7035  7035 W art     : b47b2000-b47b3000 ---p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b47b3000-b47bd000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-30 23:11:29.200  7035  7035 W art     : b47bd000-b47be000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-30 23:11:29.200  7035  7035 W art     : b47be000-b47c0000 rw-p 00000000 00:00 0 
,08-30 23:11:29.200  7035  7035 W art     : b47c0000-b48c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-30 23:11:29.200  7035  7035 W art     : b48ca000-b48cd000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-30 23:11:29.200  7035  7035 W art     : b48cd000-b48ce000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-30 23:11:29.200  7035  7035 W art     : b48ce000-b48cf000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-30 23:11:29.200  7035  7035 W art     : b48cf000-b48d0000 r--p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b48d0000-b48f0000 r--s 00000000 00:0b 7184       /dev/__properties__
08-30 23:11:29.200  7035  7035 W art     : b48f0000-b5301000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
,08-30 23:11:29.200  7035  7035 W art     : b5301000-b5302000 ---p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b5302000-b534b000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-30 23:11:29.200  7035  7035 W art     : b534b000-b534c000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-30 23:11:29.200  7035  7035 W art     : b534c000-b5354000 rw-p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b5354000-b5389000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-30 23:11:29.200  7035  7035 W art     : b5389000-b538a000 ---p 00000000 00:00 0 
,08-30 23:11:29.200  7035  7035 W art     : b538a000-b538b000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-30 23:11:29.200  7035  7035 W art     : b538b000-b538c000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-30 23:11:29.200  7035  7035 W art     : b538c000-b53e4000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-30 23:11:29.200  7035  7035 W art     : b53e4000-b53e5000 ---p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b53e5000-b53e6000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-30 23:11:29.200  7035  7035 W art     : b53e6000-b53e7000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-30 23:11:29.200  7035  7035 W art     : b53e8000-b53ee000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
,08-30 23:11:29.200  7035  7035 W art     : AD_v01009.so
08-30 23:11:29.200  7035  7035 W art     : b53ee000-b53ef000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 23:11:29.200  7035  7035 W art     : b53ef000-b53f0000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-30 23:11:29.200  7035  7035 W art     : b53f0000-b53f2000 rw-p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b53f3000-b53fd000 r-xp 00000000 b3:17 1088 
08-30 23:11:29.200  7035  7035 W art     :       /system/lib/libcommon_time_client.so
,08-30 23:11:29.200  7035  7035 W art     : b53fd000-b5400000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 23:11:29.200  7035  7035 W art     : b5400000-b5401000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-30 23:11:29.200  7035  7035 W art     : b5402000-b5419000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-30 23:11:29.200  7035  7035 W art     : b5419000-b541a000 ---p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b541a000-b541b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-30 23:11:29.200  7035  7035 W art     : b541b000-b541c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-30 23:11:29.200  7035  7035 W art     : b541d000-b5427000 r-xp 00000000 b3:17 2671   ,
,08-30 23:11:29.200  7035  7035 W art     :     /system/lib/libsec_km.so
,08-30 23:11:29.200  7035  7035 W art     : b5427000-b5428000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
,08-30 23:11:29.200  7035  7035 W art     : b5428000-b5429000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
,08-30 23:11:29.200  7035  7035 W art     : b5429000-b542d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-30 23:11:29.200  7035  7035 W art     : b542d000-b542e000 r--p 00003000 b
,08-30 23:11:29.200  7035  7035 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
,08-30 23:11:29.200  7035  7035 W art     : b542e000-b542f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-30 23:11:29.200  7035  7035 W art     : b542f000-b5445000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,08-30 23:11:29.200  7035  7035 W art     : b5445000-b5446000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
,08-30 23:11:29.200  7035  7035 W art     : b5446000-b5447000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
,08-30 23:11:29.200  7035  7035 W art     : b5447000-b5454000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
,08-30 23:11:29.200  7035  7035 W art     : b5454000-b5455000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,08-30 23:11:29.200  7035  7035 W art     : b5455000-b5456000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
,08-30 23:11:29.200  7035  7035 W art     : b5456000-b54b6000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
,08-30 23:11:29.200  7035  7035 W art     : b54b6000-b54b9000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
,08-30 23:11:29.200  7035  7035 W art     : b54b9000-b54bd000 rw-p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b54bd000-b551e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
,08-30 23:11:29.200  7035  7035 W art     : b551e000-b551f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-30 23:11:29.200  7035  7035 W art     : b551f000-b556e000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
,08-30 23:11:29.200  7035  7035 W art     : b556e000-b5570000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
,08-30 23:11:29.200  7035  7035 W art     : b5570000-b5571000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-30 23:11:29.200  7035  7035 W art     : b5571000-b5572000 rw-p 00000000 00:00 0 ,
08-30 23:11:29.200  7035  7035 W art     : b5572000-b5579000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so,
08-30 23:11:29.200  7035  7035 W art     : b5579000-b557a000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-30 23:11:29.200  7035  7035 W art     : b557a000-b557b000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_,
08-30 23:11:29.200  7035  7035 W art     : avc_common.so
,08-30 23:11:29.200  7035  7035 W art     : b557c000-b557f000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-30 23:11:29.200  7035  7035 W art     : b557f000-b5580000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-30 23:11:29.200  7035  7035 W art     : b5580000-b5581000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
,08-30 23:11:29.200  7035  7035 W art     : enc_common.so
,08-30 23:11:29.200  7035  7035 W art     : b5582000-b5586000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
,08-30 23:11:29.200  7035  7035 W art     : b5586000-b5587000 ---p 00000000 00:00 0 
08-30 23:11:29.200  7035  7035 W art     : b5587000-b5588000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
,08-30 23:11:29.200  7035  7035 W art     : b5588000-b5589000 rw-p 00005000 b3:17 2510       /syste
,08-30 23:11:29.200  7035  7035 W art     : m/lib/libpowermanager.so
08-30 23:11:29.200  7035  7035 W art     : b558a000-b55a7000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
,08-30 23:11:29.200  7035  7035 W art     : b55a7000-b55a8000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-30 23:11:29.200  7035  7035 W art     : b55a8000-b55a9000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so,
08-30 23:11:29.200  7035  7035 W art     : b55aa000-b55af000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
,08-30 23:11:29.200  7035  7035 W art     : b55af000-b55b0000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
,08-30 23:11:29.200  7035  7035 W art     : b55b0000-b55b1000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-30 23:11:29.200  7035  7035 W art     : b55b2000-b55e3000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
,08-30 23:11:29.200  7035  7035 W art     : b55e3000-b55e4000 ---p 00000000 00:00 0 
,08-30 23:11:29.200  7035  7035 W art     : b55e4000-b55e7000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-30 23:11:29.200  7035  7035 W art     : b55e7000-b55e8000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so,
08-30 23:11:29.200  7035  7035 W art     : b55e9000-b5624000 r-xp 00000000 b3:17 893        /system/lib/libopus.so,
08-30 23:11:29.200  7035  7035 W art     : b5624000-b5625000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
,08-30 23:11:29.200  7035  7035 W art     : b5625000-b5626000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-30 23:11:29.200  7035  7035 W art     : b5627000-b562e000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so,
08-30 23:11:29.200  7035  7035 W art     : b562e000-b562f000 ---p 00000000 00:00 0 
,08-30 23:11:29.200  7035  7035 W art     : b562f000-b5630000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
,08-30 23:11:29.200  7035  7035 W art     : b5630000-b5631000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
,08-30 23:11:29.210  7035  7035 W art     : b5631000-b5632000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5632000-b5649000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so,
08-30 23:11:29.210  7035  7035 W art     : b5649000-b564a000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b564a000-b564d000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-30 23:11:29.210  7035  7035 W art     : b564d000-b564e000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so,
08-30 23:11:29.210  7035  7035 W art     : b564e000-b566d000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so,
08-30 23:11:29.210  7035  7035 W art     : b566d000-b566e000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-30 23:11:29.210  7035  7035 W art     : b566e000-b566f000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
,08-30 23:11:29.210  7035  7035 W art     : b566f000-b56ad000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-30 23:11:29.210  7035  7035 W art     : b56ad000-b56ae000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b56ae000-b56b0000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
,08-30 23:11:29.210  7035  7035 W art     : b56b0000-b56b1000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
,08-30 23:11:29.210  7035  7035 W art     : b56b2000-b56b9000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so,
,08-30 23:11:29.210  7035  7035 W art     : b56b9000-b56ba000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
,08-30 23:11:29.210  7035  7035 W art     : b56ba000-b56bb000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-30 23:11:29.210  7035  7035 W art     : b56bc000-b56bf000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
,08-30 23:11:29.210  7035  7035 W art     : b56bf000-b56c0000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,08-30 23:11:29.210  7035  7035 W art     : b56c0000-b56c1000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-30 23:11:29.210  7035  7035 W art     : b56c1000-b56c7000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-30 23:11:29.210  7035  7035 W art     : b56c7000-b56c8000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b56c8000-b56c9000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
,08-30 23:11:29.210  7035  7035 W art     : b56c9000-b56ca000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-30 23:11:29.210  7035  7035 W art     : b56ca000-b56d3000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
,08-30 23:11:29.210  7035  7035 W art     : b56d3000-b56d4000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
,08-30 23:11:29.210  7035  7035 W art     : b56d4000-b56d5000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-30 23:11:29.210  7035  7035 W art     : b56d5000-b5766000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
,08-30 23:11:29.210  7035  7035 W art     : b5766000-b5767000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b5767000-b5772000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
,08-30 23:11:29.210  7035  7035 W art     : b5772000-b5773000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-30 23:11:29.210  7035  7035 W art     : b5774000-b5786000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-30 23:11:29.210  7035  7035 W art     : b5786000-b5787000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-30 23:11:29.210  7035  7035 W art     : b5787000-b5788000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-30 23:11:29.210  7035  7035 W art     : b5789000-b578e000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
,08-30 23:11:29.210  7035  7035 W art     : b578e000-b578f000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-30 23:11:29.210  7035  7035 W art     : b578f000-b5790000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-30 23:11:29.210  7035  7035 W art     : b5791000-b57fe000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-30 23:11:29.210  7035  7035 W art     : b57fe000-b57ff000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b57ff000-b5801000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
,08-30 23:11:29.210  7035  7035 W art     : b5801000-b5802000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-30 23:11:29.210  7035  7035 W art     : b5802000-b5803000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5803000-b580a000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 23:11:29.210  7035  7035 W art     : b580a000-b580b000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-30 23:11:29.210  7035  7035 W art     : b580b000-b580c000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-30 23:11:29.210  7035  7035 W art     : b580d000-b588d000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 23:11:29.210  7035  7035 W art     : b588d000-b588e000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b588e000-b588f000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-30 23:11:29.210  7035  7035 W art     : b588f000-b5890000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-30 23:11:29.210  7035  7035 W art     : b5890000-b58a7000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b58a7000-b58de000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 23:11:29.210  7035  7035 W art     : b58de000-b58df000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-30 23:11:29.210  7035  7035 W art     : b58df000-b58e0000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,08-30 23:11:29.210  7035  7035 W art     : b58e0000-b58fc000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 23:11:29.210  7035  7035 W art     : b58fc000-b58fd000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 23:11:29.210  7035  7035 W art     : b58fd000-b58fe000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-30 23:11:29.210  7035  7035 W art     : b58ff000-b5960000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-30 23:11:29.210  7035  7035 W art     : b5960000-b5962000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
,08-30 23:11:29.210  7035  7035 W art     : b5962000-b5963000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-30 23:11:29.210  7035  7035 W art     : b5964000-b5989000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-30 23:11:29.210  7035  7035 W art     : b5989000-b598a000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-30 23:11:29.210  7035  7035 W art     : b598a000-b598b000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-30 23:11:29.210  7035  7035 W art     : b598c000-b5994000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
,08-30 23:11:29.210  7035  7035 W art     : b5994000-b5996000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 23:11:29.210  7035  7035 W art     : b5996000-b5997000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-30 23:11:29.210  7035  7035 W art     : b5998000-b599b000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-30 23:11:29.210  7035  7035 W art     : b599b000-b599c000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-30 23:11:29.210  7035  7035 W art     : b599c000-b599d000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
,08-30 23:11:29.210  7035  7035 W art     : b599d000-b59a1000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-30 23:11:29.210  7035  7035 W art     : b59a1000-b59a2000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b59a2000-b59a3000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-30 23:11:29.210  7035  7035 W art     : b59a3000-b59a4000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-30 23:11:29.210  7035  7035 W art     : b59a4000-b59b4000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-30 23:11:29.210  7035  7035 W art     : b59b4000-b59b5000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
,08-30 23:11:29.210  7035  7035 W art     : b59b5000-b59b6000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-30 23:11:29.210  7035  7035 W art     : b59b6000-b59fc000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b59fc000-b5a05000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-30 23:11:29.210  7035  7035 W art     : b5a05000-b5a06000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-30 23:11:29.210  7035  7035 W art     : b5a06000-b5a07000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
,08-30 23:11:29.210  7035  7035 W art     : b5a08000-b5a0d000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-30 23:11:29.210  7035  7035 W art     : b5a0d000-b5a0e000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-30 23:11:29.210  7035  7035 W art     : b5a0e000-b5a0f000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-30 23:11:29.210  7035  7035 W art     : b5a0f000-b5a12000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 23:11:29.210  7035  7035 W art     : b5a12000-b5a13000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b5a13000-b5a14000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 23:11:29.210  7035  7035 W art     : b5a14000-b5a15000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-30 23:11:29.210  7035  7035 W art     : b5a16000-b5a2e000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
08-30 23:11:29.210  7035  7035 W art     : ght_foundation.so
,08-30 23:11:29.210  7035  7035 W art     : b5a2e000-b5a2f000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5a2f000-b5a30000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 23:11:29.210  7035  7035 W art     : b5a30000-b5a31000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-30 23:11:29.210  7035  7035 W art     : b5a31000-b5a32000 rw-p 00000000 00:
08-30 23:11:29.210  7035  7035 W art     : 00 0          [anon:linker_alloc_vector]
,08-30 23:11:29.210  7035  7035 W art     : b5a32000-b5bcc000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-30 23:11:29.210  7035  7035 W art     : b5bcc000-b5bcd000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5bcd000-b5bda000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-30 23:11:29.210  7035  7035 W art     : b5bda000-b5bdb000 rw-p 001a7000 b3:17 604        /system/
08-30 23:11:29.210  7035  7035 W art     : lib/libstagefright.so
,08-30 23:11:29.210  7035  7035 W art     : b5bdb000-b5bdf000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-30 23:11:29.210  7035  7035 W art     : b5bdf000-b5be0000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5be0000-b5be1000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-30 23:11:29.210  7035  7035 W art     : b5be1000-b5be2000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-30 23:11:29.210  7035  7035 W art     : ersona.so
,08-30 23:11:29.210  7035  7035 W art     : b5be2000-b5bf5000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-30 23:11:29.210  7035  7035 W art     : b5bf5000-b5bf6000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-30 23:11:29.210  7035  7035 W art     : b5bf6000-b5bf7000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-30 23:11:29.210  7035  7035 W art     : b5bf8000-b5c43000 r
,08-30 23:11:29.210  7035  7035 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-30 23:11:29.210  7035  7035 W art     : b5c43000-b5c44000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-30 23:11:29.210  7035  7035 W art     : b5c44000-b5c45000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-30 23:11:29.210  7035  7035 W art     : b5c45000-b5c47000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5c48000-b5c59000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-30 23:11:29.210  7035  7035 W art     : b5c59000-b5c5a000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5c5a000-b5c5b000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 23:11:29.210  7035  7035 W art     : b5c5b000-b5c5c000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-30 23:11:29.210  7035  7035 W art     : b5c5c000-b5c5d000 r--p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5c5d000-b5c67000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
,08-30 23:11:29.210  7035  7035 W art     : b5c67000-b5c69000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-30 23:11:29.210  7035  7035 W art     : b5c69000-b5c6a000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-30 23:11:29.210  7035  7035 W art     : b5c6a000-b5c83000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-30 23:11:29.210  7035  7035 W art     : b5c83000-b5c84000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-30 23:11:29.210  7035  7035 W art     : b5c84000-b5c87000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
,08-30 23:11:29.210  7035  7035 W art     : b5c87000-b5c8b000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5c8b000-b5cff000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-30 23:11:29.210  7035  7035 W art     : b5cff000-b5d00000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5d00000-b5d03000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
,08-30 23:11:29.210  7035  7035 W art     : b5d03000-b5d04000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-30 23:11:29.210  7035  7035 W art     : b5d04000-b5d05000 r--p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5d05000-b5d08000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-30 23:11:29.210  7035  7035 W art     : b5d08000-b5d09000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-30 23:11:29.210  7035  7035 W art     : b5d09000-b5d0a000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
,08-30 23:11:29.210  7035  7035 W art     : b5d0a000-b5d0b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5d0b000-b5d10000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 23:11:29.210  7035  7035 W art     : b5d10000-b5d11000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 23:11:29.210  7035  7035 W art     : b5d11000-b5d12000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-30 23:11:29.210  7035  7035 W art     : b5d12000-b5d13000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-30 23:11:29.210  7035  7035 W art     : b5d13000-b5d16000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 23:11:29.210  7035  7035 W art     : b5d16000-b5d17000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-30 23:11:29.210  7035  7035 W art     : b5d17000-b5d18000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
,08-30 23:11:29.210  7035  7035 W art     : b5d18000-b5d19000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:29.210  7035  7035 W art     : b5d19000-b5d1d000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-30 23:11:29.210  7035  7035 W art     : b5d1d000-b5d1e000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-30 23:11:29.210  7035  7035 W art     : b5d1e000-b5d1f000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
,08-30 23:11:29.210  7035  7035 W art     : b5d1f000-b5d20000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5d20000-b5d24000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 23:11:29.210  7035  7035 W art     : b5d24000-b5d25000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-30 23:11:29.210  7035  7035 W art     : b5d25000-b5d26000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
,08-30 23:11:29.210  7035  7035 W art     : b5d26000-b5d27000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5d27000-b5d35000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-30 23:11:29.210  7035  7035 W art     : b5d35000-b5d36000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b5d36000-b5d37000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-30 23:11:29.210  7035  7035 W art     : b5d37000-b5d38000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
,08-30 23:11:29.210  7035  7035 W art     : b5d38000-b5d42000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 23:11:29.210  7035  7035 W art     : b5d42000-b5d45000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 23:11:29.210  7035  7035 W art     : b5d45000-b5d46000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-30 23:11:29.210  7035  7035 W art     : b5d46000-b5d47000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5d47000-b5d51000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
,08-30 23:11:29.210  7035  7035 W art     : b5d51000-b5d54000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-30 23:11:29.210  7035  7035 W art     : b5d54000-b5d55000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-30 23:11:29.210  7035  7035 W art     : b5d55000-b5d59000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-30 23:11:29.210  7035  7035 W art     : b5d59000-b5d5a000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-30 23:11:29.210  7035  7035 W art     : b5d5a000-b5d5b000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
,08-30 23:11:29.210  7035  7035 W art     : b5d5b000-b5d5c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b5d5c000-b5d69000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-30 23:11:29.210  7035  7035 W art     : b5d69000-b5d6b000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-30 23:11:29.210  7035  7035 W art     : b5d6b000-b5d6c000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
,08-30 23:11:29.210  7035  7035 W art     : b5d6c000-b617e000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-30 23:11:29.210  7035  7035 W art     : b617e000-b617f000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b617f000-b6188000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-30 23:11:29.210  7035  7035 W art     : b6188000-b618c000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-30 23:11:29.210  7035  7035 W art     : b618c000-b618d000 rw-p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b618d000-b6194000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-30 23:11:29.210  7035  7035 W art     : b6194000-b6195000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-30 23:11:29.210  7035  7035 W art     : b6195000-b6196000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-30 23:11:29.210  7035  7035 W art     : b6196000-b6197000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6197000-b61b2000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
,08-30 23:11:29.210  7035  7035 W art     : b61b2000-b61b3000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-30 23:11:29.210  7035  7035 W art     : b61b3000-b61b4000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-30 23:11:29.210  7035  7035 W art     : b61b4000-b61b5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b61b5000-b6201000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 23:11:29.210  7035  7035 W art     : b6201000-b6202000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b6202000-b6203000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 23:11:29.210  7035  7035 W art     : b6203000-b6204000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-30 23:11:29.210  7035  7035 W art     : b6204000-b6205000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6205000-b6209000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-30 23:11:29.210  7035  7035 W art     : b6209000-b620a000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b620a000-b620b000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-30 23:11:29.210  7035  7035 W art     : b620b000-b620c000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-30 23:11:29.210  7035  7035 W art     : b620c000-b6244000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-30 23:11:29.210  7035  7035 W art     : b6244000-b6245000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
,08-30 23:11:29.210  7035  7035 W art     : b6245000-b6246000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-30 23:11:29.210  7035  7035 W art     : b6246000-b6247000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6247000-b62e6000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-30 23:11:29.210  7035  7035 W art     : b62e6000-b6304000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-30 23:11:29.210  7035  7035 W art     : b6304000-b6305000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
,08-30 23:11:29.210  7035  7035 W art     : b6305000-b6478000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-30 23:11:29.210  7035  7035 W art     : b6478000-b6483000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-30 23:11:29.210  7035  7035 W art     : b6483000-b6484000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-30 23:11:29.210  7035  7035 W art     : b6484000-b659b000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-30 23:11:29.210  7035  7035 W art     : b659b000-b65a6000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
,08-30 23:11:29.210  7035  7035 W art     : b65a6000-b65a7000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-30 23:11:29.210  7035  7035 W art     : b65a7000-b65ab000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b65ab000-b65cf000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-30 23:11:29.210  7035  7035 W art     : b65cf000-b65d1000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-30 23:11:29.210  7035  7035 W art     : b65d1000-b65d2000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
,08-30 23:11:29.210  7035  7035 W art     : b65d2000-b6678000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-30 23:11:29.210  7035  7035 W art     : b6678000-b6685000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-30 23:11:29.210  7035  7035 W art     : b6685000-b6686000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-30 23:11:29.210  7035  7035 W art     : b6686000-b6687000 rw-p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b6687000-b66da000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-30 23:11:29.210  7035  7035 W art     : b66da000-b66db000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b66db000-b66dc000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-30 23:11:29.210  7035  7035 W art     : b66dc000-b66dd000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
,08-30 23:11:29.210  7035  7035 W art     : b66dd000-b66e2000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b66e2000-b66f4000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-30 23:11:29.210  7035  7035 W art     : b66f4000-b66f5000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b66f5000-b66f6000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
,08-30 23:11:29.210  7035  7035 W art     : b66f6000-b66f7000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-30 23:11:29.210  7035  7035 W art     : b66f7000-b66fe000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 23:11:29.210  7035  7035 W art     : b66fe000-b66ff000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-30 23:11:29.210  7035  7035 W art     : b66ff000-b6700000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
,08-30 23:11:29.210  7035  7035 W art     : b6700000-b6701000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6701000-b6704000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-30 23:11:29.210  7035  7035 W art     : b6704000-b6705000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-30 23:11:29.210  7035  7035 W art     : b6705000-b6706000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
,08-30 23:11:29.210  7035  7035 W art     : b6706000-b670a000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-30 23:11:29.210  7035  7035 W art     : b670a000-b670b000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-30 23:11:29.210  7035  7035 W art     : b670b000-b670c000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
,08-30 23:11:29.210  7035  7035 W art     : b670c000-b671a000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-30 23:11:29.210  7035  7035 W art     : b671a000-b671b000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b671b000-b671c000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-30 23:11:29.210  7035  7035 W art     : b671c000-b671d000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
,08-30 23:11:29.210  7035  7035 W art     : b671d000-b6726000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 23:11:29.210  7035  7035 W art     : b6726000-b6727000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 23:11:29.210  7035  7035 W art     : b6727000-b6728000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-30 23:11:29.210  7035  7035 W art     : b6728000-b678e000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
,08-30 23:11:29.210  7035  7035 W art     : b678e000-b678f000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b678f000-b6791000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-30 23:11:29.210  7035  7035 W art     : b6791000-b679a000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-30 23:11:29.210  7035  7035 W art     : b679a000-b679d000 rw-p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b679d000-b6834000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-30 23:11:29.210  7035  7035 W art     : b6834000-b6836000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-30 23:11:29.210  7035  7035 W art     : b6836000-b6837000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-30 23:11:29.210  7035  7035 W art     : b6837000-b6838000 rw-p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b6838000-b6b56000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-30 23:11:29.210  7035  7035 W art     : b6b56000-b6b57000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6b57000-b6b72000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-30 23:11:29.210  7035  7035 W art     : b6b72000-b6b76000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
,08-30 23:11:29.210  7035  7035 W art     : b6b76000-b6b7b000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6b7b000-b6b83000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 23:11:29.210  7035  7035 W art     : b6b83000-b6b84000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
,08-30 23:11:29.210  7035  7035 W art     : b6b84000-b6b85000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-30 23:11:29.210  7035  7035 W art     : b6b85000-b6bb3000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-30 23:11:29.210  7035  7035 W art     : b6bb3000-b6bb4000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6bb4000-b6bbb000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
,08-30 23:11:29.210  7035  7035 W art     : b6bbb000-b6bbc000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-30 23:11:29.210  7035  7035 W art     : b6bbc000-b6c02000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-30 23:11:29.210  7035  7035 W art     : b6c02000-b6c03000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6c03000-b6c06000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
,08-30 23:11:29.210  7035  7035 W art     : b6c06000-b6c07000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-30 23:11:29.210  7035  7035 W art     : b6c07000-b6c22000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-30 23:11:29.210  7035  7035 W art     : b6c22000-b6c26000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-30 23:11:29.210  7035  7035 W art     : b6c26000-b6c27000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
,08-30 23:11:29.210  7035  7035 W art     : b6c27000-b6c74000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-30 23:11:29.210  7035  7035 W art     : b6c74000-b6c75000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6c75000-b6c81000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-30 23:11:29.210  7035  7035 W art     : b6c81000-b6c82000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
,08-30 23:11:29.210  7035  7035 W art     : b6c82000-b6c8f000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-30 23:11:29.210  7035  7035 W art     : b6c8f000-b6c90000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6c90000-b6c91000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-30 23:11:29.210  7035  7035 W art     : b6c91000-b6c92000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
,08-30 23:11:29.210  7035  7035 W art     : b6c92000-b6c9a000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-30 23:11:29.210  7035  7035 W art     : b6c9a000-b6c9b000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6c9b000-b6c9c000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-30 23:11:29.210  7035  7035 W art     : b6c9c000-b6c9d000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
,08-30 23:11:29.210  7035  7035 W art     : b6c9d000-b6ca4000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-30 23:11:29.210  7035  7035 W art     : b6ca4000-b6ca5000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-30 23:11:29.210  7035  7035 W art     : b6ca5000-b6ca6000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-30 23:11:29.210  7035  7035 W art     : b6ca6000-b6cba000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
,08-30 23:11:29.210  7035  7035 W art     : b6cba000-b6cbc000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-30 23:11:29.210  7035  7035 W art     : b6cbc000-b6cbd000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-30 23:11:29.210  7035  7035 W art     : b6cbd000-b6ce5000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-30 23:11:29.210  7035  7035 W art     : b6ce5000-b6ce7000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
,08-30 23:11:29.210  7035  7035 W art     : b6ce7000-b6ce8000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-30 23:11:29.210  7035  7035 W art     : b6ce8000-b6ceb000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-30 23:11:29.210  7035  7035 W art     : b6ceb000-b6cec000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-30 23:11:29.210  7035  7035 W art     : b6cec000-b6ced000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
,08-30 23:11:29.210  7035  7035 W art     : b6ced000-b6cf6000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-30 23:11:29.210  7035  7035 W art     : b6cf6000-b6cf7000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
,08-30 23:11:29.210  7035  7035 W art     : b6cf7000-b6cf8000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-30 23:11:29.210  7035  7035 W art     : b6cf8000-b6d18000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-30 23:11:29.210  7035  7035 W art     : b6d18000-b6d19000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
,08-30 23:11:29.210  7035  7035 W art     : b6d19000-b6d1a000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-30 23:11:29.210  7035  7035 W art     : b6d1a000-b6d8d000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-30 23:11:29.210  7035  7035 W art     : b6d8d000-b6d91000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-30 23:11:29.210  7035  7035 W art     : b6d91000-b6d94000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
,08-30 23:11:29.210  7035  7035 W art     : b6d94000-b6d9e000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6d9e000-b6e26000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-30 23:11:29.210  7035  7035 W art     : b6e26000-b6e27000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6e27000-b6e2b000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
,08-30 23:11:29.210  7035  7035 W art     : b6e2b000-b6e2c000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-30 23:11:29.210  7035  7035 W art     : b6e2c000-b6e2d000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6e2d000-b6e56000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-30 23:11:29.210  7035  7035 W art     : b6e56000-b6e57000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b6e57000-b6e5a000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-30 23:11:29.210  7035  7035 W art     : b6e5a000-b6e5b000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-30 23:11:29.210  7035  7035 W art     : b6e5b000-b6f35000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 23:11:29.210  7035  7035 W art     : b6f35000-b6f3c000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
,08-30 23:11:29.210  7035  7035 W art     : b6f3c000-b6f44000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-30 23:11:29.210  7035  7035 W art     : b6f44000-b6f45000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6f45000-b6f46000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-30 23:11:29.210  7035  7035 W art     : b6f46000-b6f47000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-30 23:11:29.210  7035  7035 W art     : b6f47000-b6f48000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6f48000-b6f4b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6f4b000-b6f70000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
,08-30 23:11:29.210  7035  7035 W art     : b6f70000-b6f71000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6f71000-b6f78000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-30 23:11:29.210  7035  7035 W art     : b6f78000-b6f79000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-30 23:11:29.210  7035  7035 W art     : b6f79000-b6f80000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
,08-30 23:11:29.210  7035  7035 W art     : b6f80000-b6f81000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-30 23:11:29.210  7035  7035 W art     : b6f81000-b6f82000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-30 23:11:29.210  7035  7035 W art     : b6f82000-b6f83000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6f83000-b6f9b000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-30 23:11:29.210  7035  7035 W art     : b6f9b000-b6f9c000 ---p 00000000 00:00 0 
,08-30 23:11:29.210  7035  7035 W art     : b6f9c000-b6f9d000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-30 23:11:29.210  7035  7035 W art     : b6f9d000-b6f9e000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-30 23:11:29.210  7035  7035 W art     : b6f9e000-b6fac000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-30 23:11:29.210  7035  7035 W art     : b6fac000-b6fad000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6fad000-b6fae000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-30 23:11:29.210  7035  7035 W art     : b6fae000-b6faf000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so,
08-30 23:11:29.210  7035  7035 W art     : b6faf000-b6fb0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:29.210  7035  7035 W art     : b6fb0000-b6fb2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6fb2000-b6fb3000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-30 23:11:29.210  7035  7035 W art     : b6fb3000-b6fb4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-30 23:11:29.210  7035  7035 W art     : b6fb4000-b6fb5000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-30 23:11:29.210  7035  7035 W art     : b6fb5000-b6fb6000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-30 23:11:29.210  7035  7035 W art     : b6fb6000-b6fd6000 r--s 00000000 00:0b 7184       /dev/__properties__
08-30 23:11:29.210  7035  7035 W art     : b6fd6000-b6fd7000 r--p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6fd7000-b6fd8000 ---p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6fd8000-b6fda000 rw-p 00000000 00:00 0          [anon:thread signal stack]
,08-30 23:11:29.210  7035  7035 W art     : b6fda000-b6fdb000 r-xp 00000000 00:00 0          [sigpage]
08-30 23:11:29.210  7035  7035 W art     : b6fdb000-b6ff6000 r-xp 00000000 b3:17 341        /system/bin/linker
08-30 23:11:29.210  7035  7035 W art     : b6ff6000-b6ff7000 r--p 0001a000 b3:17 341        /system/bin/linker
,08-30 23:11:29.210  7035  7035 W art     : b6ff7000-b6ff9000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-30 23:11:29.210  7035  7035 W art     : b6ff9000-b6ffb000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : b6ffb000-b7000000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-30 23:11:29.210  7035  7035 W art     : b7000000-b7001000 r--p 00004000 b3:17 978        /system/bin/app_process32
,08-30 23:11:29.210  7035  7035 W art     : b7001000-b7002000 rw-p 00000000 00:00 0 
08-30 23:11:29.210  7035  7035 W art     : bebff000-bec20000 rw-p 00000000 00:00 0          [stack]
08-30 23:11:29.210  7035  7035 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-30 23:11:29.300  7035  7035 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 23:11:29.370  7035  7035 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 23:11:29.380  7035  7035 E AffinityControl: AffinityControl: registerfunction enter
,08-30 23:11:29.400  7035  7035 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 23:11:29.420   779  1767 D PackageManager: START PACKAGE DELETE: observer{140572269}
08-30 23:11:29.420   779  1767 D PackageManager: pkg{<packageName>}
08-30 23:11:29.420   779  1767 D PackageManager: user{0}
08-30 23:11:29.420   779  1767 D PackageManager: caller{2000}
08-30 23:11:29.420   779  1767 D PackageManager: flags{2}
08-30 23:11:29.420   779  1767 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 23:11:29.420   779  1767 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 23:11:29.420   779  1767 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 23:11:29.420   779  1767 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 23:11:29.420   779  1767 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 23:11:29.420   779   949 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 23:11:29.420   779   949 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 23:11:29.420   779   949 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 23:11:29.420   779   949 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 23:11:29.420   779   949 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 23:11:29.420   779   949 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 23:11:29.420   779   949 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-30 23:11:29.430   779   949 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-30 23:11:29.430   779   867 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-30 23:11:29.430   779   949 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-30 23:11:29.430   779   949 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-30 23:11:29.430   779   867 I ActivityManager: Killing 6541:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
08-30 23:11:29.430   779   867 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 23:11:29.430   779   867 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-30 23:11:29.450   779   949 D AASAinstall: there is not AASApackages.xml file
08-30 23:11:29.450   779   867 I ActivityManager: Start proc 7050:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-30 23:11:29.460   779   867 I ActivityManager:   Force finishing activity ActivityRecord{d107651 u0 com.test.thalitest/.MainActivity t167}
,08-30 23:11:29.460  7050  7050 E Zygote  : v2
08-30 23:11:29.460  7050  7050 I libpersona: KNOX_SDCARD checking this for 10004
08-30 23:11:29.460  7050  7050 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:29.470  7050  7050 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:29.470  7050  7050 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-30 23:11:29.470   294   362 I SurfaceFlinger: id=20 Removed NainActivit (4/10)
08-30 23:11:29.470   294  4870 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
08-30 23:11:29.480   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d38c
08-30 23:11:29.480  7050  7050 E Zygote  : accessInfo : 0
08-30 23:11:29.490  7050  7050 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-30 23:11:29.520  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:29.520  7050  7050 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:29.550   779  1621 D GraphicsStats: Buffer count: 4
08-30 23:11:29.550   779  2437 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1ac52a2)
,08-30 23:11:29.550   779  1329 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:11:29.550   779  1329 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:11:29.550   779  1329 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:11:29.840   779   949 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-30 23:11:30.000   779   949 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-30 23:11:30.020   779  1747 I ActivityManager: Killing 4588:com.wssyncmldm/1000 (adj 15): DHA:empty #37
,08-30 23:11:30.020   332   332 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-30 23:11:30.030   779   949 I art     : Starting a blocking GC Explicit
,08-30 23:11:30.070   779  1570 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,08-30 23:11:30.080  7050  7050 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-30 23:11:30.100  7050  7050 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-30 23:11:30.100  7050  7050 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-30 23:11:30.100  7050  7050 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
,08-30 23:11:30.100  7050  7050 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-30 23:11:30.130  7050  7050 D AndroidRuntime: Shutting down VM
,08-30 23:11:30.130  7050  7050 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:11:30.130  7050  7050 E AndroidRuntime: Process: com.test.thalitest, PID: 7050
08-30 23:11:30.130  7050  7050 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-30 23:11:30.130  7050  7050 E AndroidRuntime: 	... 9 more
,08-30 23:11:30.160   779   867 I ActivityManager: Start proc 7071:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-30 23:11:30.160  7071  7071 E Zygote  : v2
08-30 23:11:30.160  7071  7071 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:30.160  7071  7071 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:30.160  7050  7050 I Process : Sending signal. PID: 7050 SIG: 9
,08-30 23:11:30.160  7071  7071 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-30 23:11:30.160  7071  7071 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-30 23:11:30.170  7071  7071 E Zygote  : accessInfo : 0
,08-30 23:11:30.180   779  1752 I ActivityManager: Process com.test.thalitest (pid 7050)(adj 9) has died(164,709)
,08-30 23:11:30.180   779  1752 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 23:11:30.180   779  1752 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-30 23:11:30.190   779  1752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26698 com.android.server.am.ActivityManagerService.appDiedLocked:7560 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-30 23:11:30.190   779   867 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-30 23:11:30.190   779   867 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-30 23:11:30.200  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:30.200  7071  7071 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:30.210   779  2441 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d8bb33 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc36ef0 7071:com.samsung.android.sm/1000}
,08-30 23:11:30.220  7071  7071 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-30 23:11:30.280  7071  7071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-30 23:11:30.290   779   949 I art     : Explicit concurrent mark sweep GC freed 88820(4MB) AllocSpace objects, 9(180KB) LOS objects, 27% free, 42MB/58MB, paused 1.934ms total 250.096ms
,08-30 23:11:30.300   779   792 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d8bb33 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84ffde9 4474:com.google.android.gms/u0a11}
,08-30 23:11:30.330   779   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 23:11:30.330   779   949 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-30 23:11:30.340   779   949 D AASAinstall: there is not AASApackages.xml file
,08-30 23:11:30.340   779   949 D PackageManager: result of delete: 1{140572269}
,08-30 23:11:30.340  7035  7035 I art     : System.exit called, status: 0
08-30 23:11:30.340  7035  7035 I AndroidRuntime: VM exiting with result code 0.
,08-30 23:11:30.340   779   949 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 23:11:30.340   779   949 D PackageManager: userId{-1}
08-30 23:11:30.340   779   949 D PackageManager: andCode{true}
,08-30 23:11:30.370   779   949 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-30 23:11:30.390  6177  7092 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-30 23:11:30.410  6177  7092 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-30 23:11:30.410  6177  7092 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-30 23:11:30.440   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.450   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.450   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.450  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-30 23:11:30.450  1383  1383 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-30 23:11:30.450   779   863 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.450   779   918 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.460   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.460   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.460  2023  2023 E SamsungIME: mOCRHelper is null
,08-30 23:11:30.460   779   918 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.460  2045  2275 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 23:11:30.470   779  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.470   779   779 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.480   779   779 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.480   779   867 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{332a852 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e517ef1 3315:com.samsung.klmsagent/u0a18}
,08-30 23:11:30.490   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.490  3315  3315 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Aug 30 23:11:30 GMT+02:00 2016
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.500  1717  1717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-30 23:11:30.500   779   779 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.510   779   779 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.510   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.520   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.520   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.520  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 23:11:30.520  3315  3315 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-30 23:11:30.520  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 23:11:30.520   779   863 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.520   779   863 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.520  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 23:11:30.530  3196  3211 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-30 23:11:30.530   779  1409 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-30 23:11:30.530  3315  3315 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-30 23:11:30.530  3315  3315 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 23:11:30.530   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.530   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.530  3315  3315 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-30 23:11:30.530   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.530   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.530  3315  7101 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
,08-30 23:11:30.530  3315  7101 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-30 23:11:30.530  3315  7101 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-30 23:11:30.530  3315  7101 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-30 23:11:30.530  3315  7101 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
,08-30 23:11:30.530  3315  7101 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-30 23:11:30.540  3315  7101 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 23:11:30.540   779  1320 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
,08-30 23:11:30.540   779  1320 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-30 23:11:30.540  3315  7101 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.550   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.560   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.560   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.560   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.560  3315  7101 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7285ddde in tid 7101 (IntentService[K)
,08-30 23:11:30.560   779  1296 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-30 23:11:30.560  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
,08-30 23:11:30.560  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
,08-30 23:11:30.560   779   779 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.560   779   779 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.570   779  2437 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{332a852 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{82f4350 779:system/1000}
08-30 23:11:30.570   779   779 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.570   779   779 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.570   779   863 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.570   779   779 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.570   779   779 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.580   779   779 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.580   779   779 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.580   779   779 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.580   779   779 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.590   292   292 E lowmemorykiller: Error writing /proc/3315/oom_score_adj; errno=22
,08-30 23:11:30.590   779   779 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   863 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   863 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   863 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.600   779   779 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.600   779   863 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9def4eec in tid 863 (android.bg)
,08-30 23:11:30.610   779  1296 I EventHub: Removing device '/dev/input/event5' due to inotify event
,08-30 23:11:30.610   779  1767 I ActivityManager: Process com.samsung.klmsagent (pid 3315)(adj 5) has died(194,692)
,08-30 23:11:30.610   779   779 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.610   779   779 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.610   779   863 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 23:11:30.610  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
08-30 23:11:30.610   779  1767 D ActivityManager: isAutoRunBlockedApp:: com.samsung.klmsagent, Auto Run ON
08-30 23:11:30.610   779  1767 I ActivityManager: isWidgetUsingPkg : com.samsung.klmsagent no widget is using.
08-30 23:11:30.620   779   779 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.620   779   779 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.620   779   779 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.620   779   779 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   353   353 I Zygote  : Process 3315 exited due to signal (7)
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.630   779   779 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.640   779   779 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.640   779   779 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.640   779   779 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.640  1705  7102 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-30 23:11:30.640  1705  7102 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-30 23:11:30.640  1705  7102 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-30 23:11:30.640  1705  7102 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-30 23:11:30.640  1705  7102 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 23:11:30.650   779  1296 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.650   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
08-30 23:11:30.660   779   779 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-30 23:11:30.770  2395  2422 W Sensors : sensorservice died [0xad9fad00]
,08-30 23:11:30.770   327   975 W AudioFlinger: power manager service died !!!
08-30 23:11:30.770   327   975 W AudioFlinger: power manager service died !!!
,08-30 23:11:30.770  1816  1962 E WifiManager: Channel connection lost
08-30 23:11:30.770  1717  1717 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
08-30 23:11:30.770  1717  2205 E WifiManager: Channel connection lost
,08-30 23:11:30.770   293   293 I ServiceManager: service 'imms' died
,08-30 23:11:30.770  1870  1885 W Sensors : sensorservice died [0xad7a2d40]
08-30 23:11:30.770   294   369 I SurfaceFlinger: restart the boot-animation @ binderDied
08-30 23:11:30.770   294   294 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
08-30 23:11:30.770   294   294 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-30 23:11:30.770  2325  2325 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ee2539a in tid 2325 (droid.bluetooth)
,08-30 23:11:30.770   294  4870 D libEGL  : eglTerminate EGLDisplay = 0xb46fa6fc
08-30 23:11:30.770  2325  2325 F libc    : Unable to open connection to debuggerd: Connection refused
,08-30 23:11:30.770  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
08-30 23:11:30.770   294  1749 I SurfaceFlinger: id=2 Removed GocusedStac (4/9)
,08-30 23:11:30.770  1383  1394 W Sensors : sensorservice died [0xad7cfe40]
,08-30 23:11:30.780  1383  1623 E WifiManager: Channel connection lost
08-30 23:11:30.780  1733  2249 W Sensors : sensorservice died [0xad80c480]
,08-30 23:11:30.780   294  4870 D libEGL  : eglTerminate EGLDisplay = 0xb46fa6fc
,08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
,08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=15 Removed EimLayer(An (0/6)
08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=14 Removed EimLayer(Di (2/5)
08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
,08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-30 23:11:30.780   294  1749 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/5)
,08-30 23:11:30.780  2045  2525 W Sensors : sensorservice died [0xaceb9ec0]
,08-30 23:11:30.780  1705  1705 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7166035f in tid 1705 (com.android.nfc)
,08-30 23:11:30.780   294   362 I SurfaceFlinger: id=5 Removed TtatusBar (3/4)
08-30 23:11:30.780   294   362 I SurfaceFlinger: id=5 Removed TtatusBar (-2/4)
08-30 23:11:30.780   294   362 I SurfaceFlinger: id=7 Removed JmageWallpa (0/3)
08-30 23:11:30.780   294   362 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/3)
,08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=18 Removed DolorFade (2/2)
08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=18 Removed DolorFade (-2/2)
08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=21 Removed VSBConnecti (1/1)
08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=22 Removed VSBConnecti (0/0)
,08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/0)
08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/0)
,08-30 23:11:30.780  1705  1705 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 23:11:30.780   294  4870 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
,08-30 23:11:30.790  2045  2270 E WifiManager: Channel connection lost
,08-30 23:11:30.790  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
,08-30 23:11:30.790  5991  6056 E WifiManager: Channel connection lost
,08-30 23:11:30.790  4474  7085 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x7333391a in tid 7085 (IntentService[D)
,08-30 23:11:30.790  4474  7085 F libc    : Unable to open connection to debuggerd: Connection refused
,08-30 23:11:30.790  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
,08-30 23:11:30.800   293   293 I ServiceManager: service 'telecom' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sec_analytics' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'servicediscovery' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'updatelock' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'notification' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'devicestoragemonitor' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'location' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'country_detector' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sec_location' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'search' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'execute' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'dropbox' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'wallpaper' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'audio' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'DockObserver' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'midi' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'usb' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'serial' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'kiesusb' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'jobscheduler' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'backup' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'appwidget' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'voiceinteraction' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'SecExternalDisplayService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'diskstats' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'mDNIe' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'AAS' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'MSCS' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'spengestureservice' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'quickconnect' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'samplingprofiler' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'commontime_management' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'dreams' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'graphicsstats' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'print' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'restrictions' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'media_session' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'media_router' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'trust' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'fingerprint' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'launcherapps' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'context_aware' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'scontext' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'barbeam' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'multiwindow_facade' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'window' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'voip' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'input' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'bluetooth_manager' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'rcp' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'input_method' died
08-30 23:11:30.800   293 ,  293 I ServiceManager: service 'accessibility' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'display' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'activity' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'persona_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'user' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'procstats' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'meminfo' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'gfxinfo' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'dbinfo' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'cpuinfo' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'permission' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'processinfo' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sensorservice' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'mdm.remotedesktop' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'battery' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'usagestats' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'webviewupdate' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'scheduling_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'telephony.registry' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'persona' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'SEAMService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'media.camera.proxy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'account' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'content' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'DirEncryptService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'LSManager' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'ReactiveService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'DeviceRootKeyService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'EngineeringModeService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'SatsService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sedenial' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'vibrator' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'tw_toolbox' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'tima' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'iccc' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'cepproxyks' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'emailksproxy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'CustomFrequencyManagerService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'consumer_ir' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'alarm' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'edmnativehelper' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'enterprise_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'statusbar' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'clipboard' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'clipboardEx' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'network_management' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'media_projection' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'lpnet' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'ABTPersistenceService' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'textservices' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'network_score' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'netstats' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'netpolicy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'wifip2p' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'wifi' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'wifihs20' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'wifiscanner' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'rttmanager' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'ethernet' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'connectivity' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sb_service' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'cover' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'mount' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'deviceidle' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'lock_settings' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'device_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'harmony_eas_service' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sdp' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'sdp_log' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'dlp' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'log_manager_service' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'knox_ccm_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'enterprise_license_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'application_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'wifi_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'phone_restriction_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'remoteinjection' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'knox_ucsm_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'edm_proxy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'mum_container_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'enterprise_billing_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'otp_service' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'enterprise_shared_device_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'knox_timakeystore_policy' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'uimode' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'batterystats' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'appops' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'package' died
08-30 23:11:30.800   293   293 I ServiceManager: service 'power' died
08-30 23:11:30.820  5062  5062 D BluetoothA2dp: Proxy object disconnected
08-30 23:11:30.820  2382  2382 D BluetoothA2dp: Proxy object disconnected
08-30 23:11:30.820  5062  5062 D A2dpProfile: Bluetooth service disconnected
08-30 23:11:30.820  5062  5062 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 23:11:30.820  5062  5062 D PanProfile: Bluetooth service disconnected
08-30 23:11:30.820  5062  5062 D BluetoothMap: Proxy object disconnected
08-30 23:11:30.820  5062  5062 D MapProfile: Bluetooth service disconnected
08-30 23:11:30.820  5062  5062 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9582bd in tid 5062 (ndroid.settings)
08-30 23:11:30.820  5062  5062 F libc    : Unable to open connection to debuggerd: Connection refused
08-30 23:11:30.820   293   293 I ServiceManager: service 'nfc' died
08-30 23:11:30.820   293   293 I ServiceManager: service 'nfccontroller' died
08-30 23:11:30.820   293   293 I ServiceManager: service 'secontroller' died
08-30 23:11:30.820  2331  2331 E audit_log: File locking failed. error= Bad file descriptor
,08-30 23:11:30.880   353   353 I Zygote  : Process 5062 exited due to signal (7)
,08-30 23:11:30.890   353   353 I Zygote  : Process 1705 exited due to signal (7)
08-30 23:11:30.890   353   353 I Zygote  : Process 4474 exited due to signal (7)
,08-30 23:11:30.890   353   353 I Zygote  : Process 2325 exited due to signal (7)
,08-30 23:11:30.990   330   330 E installd: eof
08-30 23:11:30.990   330   330 E installd: failed to read size
08-30 23:11:30.990   330   330 I installd: closing connection
08-30 23:11:30.990   292   292 I lowmemorykiller: ActivityManager disconnected
08-30 23:11:30.990   292   292 I lowmemorykiller: Closing Activity Manager data connection
,08-30 23:11:31.020   294   580 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-30 23:11:31.020   294   294 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-30 23:11:31.020   294   629 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-30 23:11:31.020   294   629 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-30 23:11:31.240   294   580 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 23:11:31.270   294   294 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-30 23:11:31.270   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d3a4
,08-30 23:11:31.280   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d38c
,08-30 23:11:31.280   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d38c
08-30 23:11:31.280   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d38c
,08-30 23:11:31.280   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d38c
,08-30 23:11:31.280   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbee3d3a4

```
